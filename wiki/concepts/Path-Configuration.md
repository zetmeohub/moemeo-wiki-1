---
title: "Path Configuration"
type: concept
tags: [Setup, PowerShell, Windows]
sources: [[[scripts-tu-dong-ingest-powershell-windows]]]
last_updated: 2026-04-11
---

## Description
Việc thiết lập đúng các đường dẫn thư mục (Path) là yếu tố tiên quyết để các script tự động hóa hoạt động chính xác, đặc biệt khi AI Agent được đặt bên trong một cấu trúc thư mục phức tạp như Vault Obsidian.

## Key Considerations
- **VaultPath**: Đường dẫn gốc của AI Agent, nơi chứa file `GEMINI.md`.
- **Relative Paths**: Sử dụng đường dẫn tương đối từ `VaultPath` để định vị thư mục `raw/` và `wiki/`.
- **Set-Location**: Lệnh PowerShell để đảm bảo ngữ cảnh thực thi của script trùng khớp với thư mục gốc của dự án.
