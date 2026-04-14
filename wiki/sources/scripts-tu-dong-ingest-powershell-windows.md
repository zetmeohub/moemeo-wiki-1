---
title: "Scritps Tự Động Ingest bằng PowerShell - windows"
type: source
tags: [PowerShell, Automation, Windows, Path-Configuration]
date: 2026-04-11
source_file: raw/AI/Scritps Tự Động Ingest bằng PowerShell - windows.md
---

## Summary
Hướng dẫn cấu hình script PowerShell (đặt tên là "Tèo Ingest Pro V2.3") để tự động hóa quy trình `ingest` cho Windows. Script tập trung vào việc xác định đúng đường dẫn root của Agent (`vaultPath`) và sử dụng cơ chế so sánh timestamp để tránh ingest lặp lại các file không thay đổi.

## Key Claims
- Script cần được trỏ chính xác vào "tổng hành dinh" (Root) của AI Agent để tìm thấy `GEMINI.md` và folder `raw/`.
- Sử dụng `.ingested_history.json` để lưu trữ lịch sử và so sánh `LastWriteTime` (timestamp) của file.
- Hỗ trợ quét đệ quy các file `.md` trong thư mục `raw/`.

## Key Quotes
> "Mày đang để toàn bộ code của cái repo llm-wiki-agent-main vào một thư mục con bên trong Vault Obsidian của mày... mày cần sửa lại biến $vaultPath."
> "Sử dụng .ingested_history.json để lưu trữ hồ sơ và so sánh timestamp để tránh tiêu hóa lại cái cũ."

## Connections
- [[PowerShell]] — Ngôn ngữ thực thi script.
- [[Gemini-CLI]] — Công cụ được script gọi để thực hiện lệnh.
- [[WorkflowOptimization]] — Tự động hóa việc đưa dữ liệu vào hệ thống.
- [[Path-Configuration]] — Khái niệm quan trọng để script chạy đúng trong môi trường Obsidian.

## Contradictions
- Script này sử dụng tham số `--system "$(Get-Content $geminiConfig -Raw)"`. Tuy nhiên, nguồn [[cap-nhat-scripts-auto-ingest]] chỉ ra rằng một số phiên bản Gemini CLI sẽ báo lỗi `Unknown argument: system` và cần chuyển sang dùng `--prompt`.
