---
title: "Outer Harness - Hạ tầng quản trị AI Agent trong doanh nghiệp"
type: source
tags: [AI-Agent, Governance, Outer-Harness, Inner-Harness, Cost-Control, Knowledge-Management]
date: 2026-04-12
source_file: raw/AI/Chưa đặt tên.md
---

## Summary
Tài liệu phân tích sâu về nhu cầu cấp thiết của một lớp hạ tầng quản trị AI Agent trong doanh nghiệp, được gọi là **Outer Harness**. Khác với **Inner Harness** (do các nhà cung cấp model như OpenAI/Anthropic tối ưu), Outer Harness là phần mang DNA của tổ chức, chịu trách nhiệm về kiểm soát chi phí, luồng tri thức đa tầng, theo dõi tác vụ, cổng chất lượng và phân tích dữ liệu. Việc thiếu Outer Harness dẫn đến nợ kỹ thuật, context phân mảnh và chi phí API mù mờ.

## Key Claims
- **Agent = Model + Harness.** Trong đó Harness chia thành Inner (của provider) và Outer (của doanh nghiệp).
- **Nghịch lý chi phí:** Doanh nghiệp chi hàng trăm ngàn đô cho Inner (token fees) nhưng bỏ mặc Outer (chất lượng output).
- **5 trụ cột của Outer Harness:** 1. Định danh chi phí (Cost Attribution), 2. Luồng tri thức đa tầng (Multi-layer Knowledge Flow), 3. Theo dõi tác vụ (Task Tracking), 4. Cổng chất lượng (Quality Gates), 5. Kiểm toán & Phân tích (Audit & Analytics).
- **Triết lý xây dựng:** Lấy quy trình làm trung tâm (Process-centric) và dựa trên dữ liệu (Data-driven).

## Key Quotes
> "Mỗi ngày không có Outer Harness là một ngày bạn tích thêm nợ kỹ thuật mà không ai đo được."
> "Kẻ viết code không nên là kẻ duy nhất judge code của chính mình."
> "Outer Harness mới là thứ quyết định output đó có thực sự phục vụ tổ chức hay không."

## Connections
- [[LLM-Wiki-Agent]] — Một dạng của Outer Harness giúp quản trị tri thức cá nhân/tổ chức.
- [[Claude-Code]] — Ví dụ tiên phong về thiết kế Inner Harness chuẩn mực.
- [[KnowledgeRefining]] — Tương ứng với trụ cột "Multi-layer Knowledge Flow" để tinh lọc tri thức.
- [[WorkflowOptimization]] — Mục tiêu của việc xây dựng Outer Harness bài bản.
- [[Automation]] — Quy trình tự động phân phối tri thức và kiểm soát chất lượng.

## Contradictions
- Không có mâu thuẫn. Tài liệu này cung cấp khung lý thuyết quản trị cao cấp cho các hệ thống agent.
