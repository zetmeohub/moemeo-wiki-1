---
title: "Cập Nhật Scripts auto ingest"
type: source
tags: [PowerShell, Gemini-CLI, UTF-8, Automation]
date: 2026-04-11
source_file: raw/AI/Cập Nhật Scripts auto ingest.md
---

## Summary
Bản cập nhật quan trọng cho script PowerShell tự động hóa quá trình `ingest`. Giải quyết lỗi tham số `--system` không tồn tại trong một số phiên bản Gemini CLI và khắc phục triệt để lỗi hiển thị phông chữ tiếng Việt (UTF-8) trên Windows Terminal.

## Key Claims
- Lỗi **`Unknown argument: system`** xảy ra do phiên bản Gemini CLI thay đổi cách nạp hướng dẫn hệ thống.
- Giải pháp: Gộp nội dung `GEMINI.md` trực tiếp vào tham số `--prompt`.
- Lỗi hiển thị tiếng Việt (`Báº£o Cáo Vá»...`) do Code Page mặc định của PowerShell (437).
- Giải pháp: Sử dụng `chcp 65001` và ép `OutputEncoding` sang UTF-8.

## Key Quotes
> "Mày cần thêm một lệnh ép Windows Terminal dùng chuẩn UTF-8 (Code Page 65001) ngay khi bắt đầu script."
> "Thay vì dùng --system (bị báo lỗi), tao đưa toàn bộ 'luật chơi' trong file GEMINI.md vào làm phần đầu của câu lệnh gửi đi."

## Connections
- [[Gemini-CLI]] — Công cụ chính thực hiện lệnh `ingest`.
- [[PowerShell]] — Ngôn ngữ dùng để viết script tự động hóa.
- [[WorkflowOptimization]] — Một phần của nỗ lực tối ưu hóa quy trình đưa dữ liệu vào wiki.
- [[UTF-8-Encoding]] — Giải pháp cho vấn đề hiển thị tiếng Việt.

## Contradictions
- Cập nhật này thay thế phương pháp dùng `--system` đã được đề cập trong các tài liệu hoặc script trước đó ([[chay-lenh-ingest-cho-folder-raw]]).
