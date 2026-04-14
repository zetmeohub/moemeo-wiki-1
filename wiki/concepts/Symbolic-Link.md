---
title: "Symbolic Link"
type: concept
tags: ["linux", "filesystem", "optimization"]
sources: ["[[cach-dung-termux-chay-gemini-cli]]"]
last_updated: 2026-04-12
---

## Description
Symbolic Link (liên kết mềm) là một loại tệp đặc biệt trong hệ điều hành Linux/Unix đóng vai trò như một lối tắt đến một tệp hoặc thư mục khác.

## Core Ideas
- **Lối tắt (Shortcut)**: Thay vì gõ một đường dẫn dài dặc, người dùng có thể tạo một tên ngắn gọn trỏ đến đường dẫn đó.
- **Tính trong suốt**: Hầu hết các ứng dụng xử lý symbolic link như thể chúng chính là tệp hoặc thư mục gốc.
- **Lệnh tạo**: `ln -s <đường_dẫn_nguồn> <đường_dẫn_đích>`.

## Connections
- [[Termux]] — Sử dụng symbolic link để truy cập nhanh vào bộ nhớ Obsidian.
- [[WorkflowOptimization]] — Một kỹ thuật nhỏ nhưng hiệu quả để tăng tốc độ làm việc.
