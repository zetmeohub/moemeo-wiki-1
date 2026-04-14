---
title: "Mixture of Experts (MoE)"
type: concept
tags: [AI Architecture, Efficiency, LLM]
sources: [[[repo-benchmark-37-llm-macbook-m5]]]
last_updated: 2026-04-12
---

Một kiến trúc mô hình ngôn ngữ lớn giúp tăng hiệu năng suy luận bằng cách chỉ kích hoạt một phần nhỏ mạng lưới thần kinh (các "Experts") cho mỗi đầu vào cụ thể. Kỹ thuật này giúp mô hình có khả năng xử lý thông tin phức tạp với tốc độ cực nhanh (thậm chí gấp 12 lần) so với kiến trúc Dense truyền thống khi chạy trên các thiết bị hạn chế về phần cứng.
