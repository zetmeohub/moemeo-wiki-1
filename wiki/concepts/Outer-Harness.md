---
title: "Outer Harness"
type: concept
tags: [AI-Agent, Governance, Architecture, Enterprise, Strategy]
sources: [[[outer-harness-governance]]]
last_updated: 2026-04-12
---

# Outer Harness (Hạ tầng quản trị Agent)

Outer Harness là một thuật ngữ mới dùng để chỉ lớp hạ tầng bao bọc bên ngoài **Inner Harness**, mang DNA và quy trình riêng biệt của một tổ chức hay doanh nghiệp.

## Mục tiêu
Outer Harness không tập trung vào việc mô hình AI chạy như thế nào, mà tập trung vào việc **output của AI có thực sự phục vụ tổ chức hay không**.

## 5 Trụ cột cốt lõi
1. **Cost Attribution (Định danh chi phí):** Log mọi agent run, phân loại chi phí theo team/dự án, alert và hard stop khi vượt budget.
2. **Multi-layer Knowledge Flow (Luồng tri thức đa tầng):** Quản lý context theo tầng (Layer 1-5), từ chính sách công ty (CTO) đến các kỹ năng cá nhân (Dev), giúp tri thức không bị mất đi khi nhân sự nghỉ việc.
3. **Task Tracking (Theo dõi tác vụ):** Lưu trữ audit trail đầy đủ cho mỗi nhiệm vụ, các cổng phê duyệt (approval gates) để đảm bảo an toàn.
4. **Quality Gates (Cổng chất lượng):** Hệ miễn dịch độc lập bên ngoài agent để kiểm soát coverage, linter, và compliance.
5. **Audit & Analytics (Kiểm toán & Phân tích):** Sử dụng append-only log để làm cơ sở cho các quyết định chiến lược về AI.

## Triết lý xây dựng
- **Process-centric:** Quy trình là xương sống, con người và Agent chỉ là các node cắm vào pipeline.
- **Data-driven:** Mọi thao tác phải sinh ra dữ liệu có cấu trúc để phân tích và cải tiến.

## Liên kết
- [[Inner-Harness]] — Lớp hạ tầng kỹ thuật tương ứng do Provider xây dựng.
- [[LLM-Wiki-Agent]] — Một dạng của Outer Harness cá nhân để quản trị tri thức và context.
- [[Automation]] — Quy trình cốt lõi để duy trì Outer Harness bền vững.
