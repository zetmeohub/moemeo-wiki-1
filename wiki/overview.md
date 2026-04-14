---
title: "Overview"
type: synthesis
tags: []
sources: [[[may-mo-su-dung-llm-wiki-agent]], [[chay-lenh-ingest-cho-folder-raw]], [[kien-tao-ban-sac-ca-nhan-journaling]], [[cap-nhat-scripts-auto-ingest]], [[scripts-tu-dong-ingest-powershell-windows]], [[cach-dung-termux-chay-gemini-cli]], [[phuong-an-deal-voi-bank]], [[lay-ngan-nuoi-dai]], [[awesome-ai-apps-catalog]], [[outer-harness-governance]], [[cach-cai-openclaw-free-api]]]
last_updated: 2026-04-12
---

# Overview

*This page is maintained by the LLM. It is updated on every ingest to reflect the current synthesis across all sources.*

## Hệ thống LLM Wiki Agent

Hệ thống [[LLM-Wiki-Agent]] được thiết kế như một "nhà máy lọc dầu" cho tri thức cá nhân. Triết lý cốt lõi của hệ thống là tách biệt quá trình **thu thập** (raw notes) và quá trình **tổ chức** (wiki pages).

### Quy trình "Lọc dầu" và Hạ tầng Quản trị (Harness)
- **Dầu thô (`raw/`)**: Là nơi người dùng ghi chép tự do, bao gồm cả các cuộc hội thoại Gemini được lưu lại dưới dạng **[[StreamOfConsciousness|dòng chảy tư duy]]**.
- **Dàn máy lọc (`ingest`)**: Quy trình AI tự động xử lý nội dung, dán nhãn và tạo liên kết tri thức.
- **Xăng sạch (`wiki/`)**: Sản phẩm tri thức tinh gọn, sẵn sàng cho việc sử dụng và phát triển dự án.

Hệ thống được thiết kế dựa trên triết lý tách biệt giữa **[[Inner-Harness]]** (hạ tầng kỹ thuật của model) và **[[Outer-Harness]]** (hạ tầng quản trị của người dùng/tổ chức). Trong khi các công cụ như **[[Claude-Code]]** đại diện cho một Inner Harness chuẩn mực, thì LLM Wiki Agent đóng vai trò là một Outer Harness giúp kiểm soát luồng tri thức, tối ưu hóa chi phí và đảm bảo chất lượng output thông qua các cổng kiểm soát (Quality Gates).

### Tối ưu hóa quy trình (Workflow Optimization)
Để nâng cao hiệu suất, hệ thống đề xuất các giải pháp **[[WorkflowOptimization|tự động hóa đầu vào]]** từ Gemini sang folder `raw/`, bao gồm việc sử dụng Browser Extensions, Google Docs hoặc **[[PythonScript]]**. Ngoài ra, việc sử dụng các script **[[PowerShell]]** trên Windows hoặc **[[Termux]]** trên Android giúp tự động hóa quá trình `ingest`. Việc thiết lập các **[[Symbolic-Link|lối tắt (Symbolic Links)]]** trong Termux giúp người dùng di động truy cập trực tiếp vào hệ thống wiki một cách nhanh chóng, biến điện thoại **[[Samsung-S20+]]** thành một công cụ mạnh mẽ của [[ConceptWeaver]]. Các vấn đề kỹ thuật như **[[UTF-8-Encoding|mã hóa tiếng Việt]]** cũng được xử lý triệt để trong các script này.

### Bản sắc cá nhân và Tự sự (Personal Identity & Narrative)
Hệ thống không chỉ dừng lại ở việc quản lý thông tin mà còn hướng tới việc giúp người dùng kiến tạo **[[Personal-Identity|bản sắc cá nhân]]**. Thông qua việc duy trì **[[Journaling|nhật ký (Journaling)]]**, người dùng có thể biến các trải nghiệm thô thành một **[[Narrative-Identity|căn tính tự sự]]** có ý nghĩa. Các lý thuyết từ các chuyên gia như **[[John-Locke]]**, **[[Erik-Erikson]]**, **[[Dan-McAdams]]** và **[[James-Pennebaker]]** cung cấp nền tảng khoa học để phân tích và thấu hiểu cái tôi thông qua ngôn ngữ.

### Đối tượng sử dụng
Hệ thống hỗ trợ đắc lực cho các [[ConceptWeaver|người dệt ý tưởng]] trong việc vượt qua tình trạng [[InformationOverload|quá tải thông tin]], đồng thời cung cấp công cụ để họ tự viết nên câu chuyện cuộc đời mình một cách chủ động và tỉnh thức.

## Hiệu năng và Triển khai Local AI
Để hệ thống [[LLM-Wiki-Agent]] hoạt động mượt mà và bảo mật, việc triển khai **[[Local-LLM]]** là một hướng đi quan trọng. Các thử nghiệm trên phần cứng **[[Apple-Silicon]]** (như MacBook Air M5) cho thấy kiến trúc **[[Mixture-of-Experts-MoE]]** là chìa khóa để chạy các mô hình lớn (trên 30B tham số) với tốc độ chat real-time. Các công cụ như **[[Mac-LLM-Bench]]** giúp người dùng xác định cấu hình tối ưu cho thiết bị của mình, đảm bảo "nhà máy lọc dầu" tri thức luôn vận hành với hiệu suất cao nhất.

## Sự thủ đắc kỹ năng và Làm chủ (Skill Acquisition & Mastery)
Hệ thống không chỉ quản lý tri thức mà còn là công cụ hỗ trợ người dùng trong lộ trình **[[Skill-Acquisition|thủ đắc kỹ năng]]**. Dựa trên **[[Dreyfus-Model]]** và **[[Blooms-Taxonomy]]**, người dùng có thể theo dõi sự tiến hóa từ một "người mới" tuân thủ quy tắc đến một "bậc thầy" sở hữu trực giác và khả năng kiến tạo di sản. Việc áp dụng **[[Deliberate-Practice|luyện tập có chủ đích]]**, xây dựng các **[[Mental-Models|mô hình tâm trí]]** sắc bén và rèn luyện kỹ năng **[[Meta-learning|học cách học]]** là những yếu tố then chốt để đạt tới sự **[[Mastery|làm chủ]]**. Quá trình này được tiếp dẫn bởi việc **[[Energy-Management|quản trị năng lượng]]** đa chiều, đảm bảo hiệu suất bền vững trong dài hạn.

## Quản trị cuộc sống và Tài chính thực tiễn (Practical Life & Finance)
Hệ thống [[LLM-Wiki-Agent]] mở rộng khả năng hỗ trợ người dùng sang các lĩnh vực thực tiễn như quản lý nợ và đàm phán tài chính thông qua chiến lược **[[lay-ngan-nuoi-dai|Lấy ngắn nuôi dài]]**. Bằng cách áp dụng mô hình **[[Barbell-Strategy|Thanh đòn tạ (Barbell Strategy)]]**, người dùng có thể duy trì sự an toàn tài chính từ các công việc ổn định (như chạy xe **[[Xanh-SM]]** để chi trả sinh hoạt và hướng tới **[[Debt-Settlement|tất toán nợ]]**) trong khi vẫn dành nguồn lực để nuôi dưỡng các dự án tiềm năng cao như viết sách và phát triển hệ sinh thái tri thức.

Việc kết hợp giữa thu nhập thực tế với các **[[Negotiation-Strategy|chiến thuật đàm phán]]** bài bản giúp tạo ra một lộ trình tài chính minh bạch và khả thi với các chủ nợ như **[[VPBank]]**. Quan trọng hơn, các công việc lao động chân tay được biến thành một "phòng thí nghiệm thực địa" để thu thập dữ liệu sống cho hệ thống tri thức, giúp quá trình kiến tạo bản sắc diễn ra ngay trong dòng chảy của cuộc sống thường nhật.

## Các Nguồn Tri Thức
1. [[may-mo-su-dung-llm-wiki-agent]] — Khởi đầu và triết lý của hệ thống.
2. [[chay-lenh-ingest-cho-folder-raw]] — Các phương thức tự động hóa dữ liệu đầu vào.
3. [[kien-tao-ban-sac-ca-nhan-journaling]] — Nền tảng lý thuyết về bản sắc và journaling.
4. [[cap-nhat-scripts-auto-ingest]] — Các cập nhật kỹ thuật cho script PowerShell.
5. [[scripts-tu-dong-ingest-powershell-windows]] — Cấu hình script tự động cho Windows.
6. [[repo-benchmark-37-llm-macbook-m5]] — Đánh giá hiệu năng LLM trên phần cứng Apple Silicon.
7. [[lo-trinh-thu-dac-ky-nang]] — Phân tích hệ thống về lộ trình phát triển năng lực.
8. [[cach-dung-termux-chay-gemini-cli]] — Tối ưu hóa Termux cho môi trường Android.
9. [[phuong-an-deal-voi-bank]] — Chiến thuật đàm phán và giải quyết nợ thực tế.
10. [[lay-ngan-nuoi-dai]] — Chiến lược kết hợp kinh tế thực tế và phát triển tri thức.
11. [[awesome-ai-apps-catalog]] — Danh mục các dự án AI thực tế năm 2026.
12. [[outer-harness-governance]] — Khung quản trị AI Agent cho doanh nghiệp.
13. [[cach-cai-openclaw-free-api]] — Hướng dẫn cài đặt OpenClaw và dùng API miễn phí.


