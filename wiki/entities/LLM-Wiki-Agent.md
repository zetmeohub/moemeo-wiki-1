---
title: "LLM Wiki Agent"
type: entity
tags: [Agent, Automation, KnowledgeManagement]
sources: [[[may-mo-su-dung-llm-wiki-agent]]]
last_updated: 2026-04-12
---

## Description
Một hệ thống đại lý AI (AI Agent) được thiết kế để tự động hóa việc tổ chức và tinh lọc tri thức từ các ghi chép thô sơ (raw notes). Hệ thống này giải quyết vấn đề "ngập lụt thông tin" và giúp người dùng không cần lo lắng về việc đặt tên file hay tạo liên kết thủ công.

## Key Features
- Tự động nhận diện thực thể và khái niệm.
- Tạo liên kết (`[[link]]`) thông minh dựa trên ngữ cảnh và mục lục (`index.md`).
- Cung cấp giao diện truy vấn (`query:`) để tìm kiếm thông tin nhanh chóng.
- Hỗ trợ mô hình "Lọc dầu" (Knowledge Refining).

## Connections
- [[Obsidian]] — Hoạt động như một plugin hoặc công cụ hỗ trợ cho Obsidian.
- [[Gemini-Pro]] — Sử dụng Gemini Pro làm bộ não xử lý.
- [[KnowledgeRefining]] — Thực hiện quy trình tinh lọc tri thức.
- [[WorkflowOptimization]] — Mục tiêu cuối cùng của việc tự động hóa đầu vào.
- [[StreamOfConsciousness]] — Nguồn dữ liệu từ các cuộc đối thoại Gemini.
- [[Local-LLM]] — Khả năng triển khai trực tiếp trên phần cứng cá nhân để bảo mật và hiệu năng.
- [[Apple-Silicon]] — Nền tảng phần cứng tối ưu cho việc vận hành agent thông qua các mô hình MoE.
