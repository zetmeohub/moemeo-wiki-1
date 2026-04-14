---
title: "UTF-8 Encoding"
type: concept
tags: [Encoding, Vietnamese, Technical]
sources: [[[cap-nhat-scripts-auto-ingest]]]
last_updated: 2026-04-11
---

## Description
Chuẩn mã hóa ký tự phổ biến nhất hiện nay, hỗ trợ đầy đủ các ký tự tiếng Việt.

## Importance in Wiki Agent
Khi sử dụng các script tự động hóa trên Windows (như [[PowerShell]]), việc không thiết lập đúng chuẩn UTF-8 (thường mặc định là Code Page 437) sẽ dẫn đến lỗi hiển thị phông chữ tiếng Việt trong tên file và nội dung tri thức.

## Solutions
- Sử dụng lệnh `chcp 65001` trong console.
- Thiết lập `$OutputEncoding = [System.Text.Encoding]::UTF8` trong script PowerShell.
