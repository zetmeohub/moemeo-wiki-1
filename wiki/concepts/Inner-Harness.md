---
title: "Inner Harness"
type: concept
tags: [AI-Agent, Architecture, Infrastructure, Model-Context]
sources: [[[outer-harness-governance]]]
last_updated: 2026-04-12
---

# Inner Harness

Inner Harness là lớp hạ tầng kỹ thuật bao quanh mô hình AI (Model), do các nhà cung cấp như Anthropic, OpenAI hay Cursor tối ưu hóa.

## Đặc điểm
- **Gắn liền với Model:** Chịu trách nhiệm về việc nạp system prompt, context files, skills, sensors, hooks và sandbox thực thi.
- **Tối ưu hóa sâu:** Được đầu tư hàng chục triệu đô để đảm bảo mô hình hoạt động an toàn và hiệu quả (ví dụ như loop TDD tự sửa lỗi).
- **Tính đóng:** Thường là phần mà người dùng không cần và không nên can thiệp sâu vào việc thay đổi cấu trúc lõi.

## Liên kết
- [[Outer-Harness]] — Lớp hạ tầng quản trị bên ngoài tương ứng.
- [[Claude-Code]] — Ví dụ về Inner Harness được thiết kế tốt nhất hiện nay.
