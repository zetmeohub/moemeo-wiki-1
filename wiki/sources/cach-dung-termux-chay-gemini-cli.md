---
title: "Cách dùng Termux để chạy gemini cli vào đúng đường link của vault"
type: source
tags: ["termux", "android", "automation", "workflow"]
date: 2026-04-12
source_file: raw/Cách dùng Termux để chạy gemini cli vào đúng đường link của vault.md
---

## Summary
Hướng dẫn cách tối ưu hóa việc truy cập vào thư mục vault Obsidian trên Android thông qua Termux. Bài viết đề xuất hai phương án: sử dụng Symbolic Link (Lối tắt) hoặc cấu hình file `.bashrc` để tự động chuyển vào thư mục vault khi mở ứng dụng.

## Key Claims
- Việc truy cập trực tiếp vào đường dẫn sâu trong bộ nhớ Android (/storage/emulated/0/...) là rắc rối và cần được tối ưu.
- Symbolic Link (`ln -s`) là phương pháp "khuyên dùng" để tạo lối tắt gọn nhẹ.
- Tự động hóa thông qua `.bashrc` giúp giảm thiểu thao tác gõ lệnh thủ công.

## Key Quotes
> "ln -s /storage/emulated/0/Documents/meomeowiki-mobi ~/vault"
> "Làm xong cái này là cái Samsung S20+ của mày chính thức trở thành 'vũ khí tối thượng' của The Concept Weaver rồi đấy!"

## Connections
- [[Termux]] — Môi trường terminal trên Android để chạy Gemini CLI.
- [[ConceptWeaver]] — Định danh người dùng trong hệ thống tri thức.
- [[Automation]] — Triết lý tối ưu hóa quy trình làm việc.
- [[Symbolic-Link]] — Kỹ thuật tạo lối tắt trong hệ điều hành Linux/Android.

## Contradictions
- Không có mâu thuẫn trực tiếp với các tài liệu hiện tại.
