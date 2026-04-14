Benchmark 37 LLM trên MacBook Air M5 – Thông tin đầy đủ về local AI (và tool để bạn tự test), mình vẫn trung thành với Mac Studio M4 16GB

Một dev đã benchmark 37 LLM trên MacBook Air M5 32GB và kết quả cho thấy một điều rất rõ:

![👉](https://static.xx.fbcdn.net/images/emoji.php/v9/t51/1/16/1f449.png) Không phải model nào cũng “chạy được local” theo cách bạn nghĩ.

![🚀](https://static.xx.fbcdn.net/images/emoji.php/v9/tc6/1/16/1f680.png) Insight quan trọng nhất

![🔥](https://static.xx.fbcdn.net/images/emoji.php/v9/t50/1/16/1f525.png) MoE đang “phá game”

• Qwen 3.5 35B MoE chạy ~31 tok/s

• Trong khi dense 32B chỉ ~2.5 tok/s

![👉](https://static.xx.fbcdn.net/images/emoji.php/v9/t51/1/16/1f449.png) Nhanh hơn ~12x nhưng RAM tương đương

→ Lần đầu tiên bạn có thể dùng model 30B+ mượt như 3B trên laptop

![⚡](https://static.xx.fbcdn.net/images/emoji.php/v9/t5d/1/16/26a1.png) “32GB wall” – giới hạn cứng của Mac

• Tất cả model 32B dense đều ~2.5 tok/s

• RAM ~18–19GB

![👉](https://static.xx.fbcdn.net/images/emoji.php/v9/t51/1/16/1f449.png) Dùng được cho batch

![👉](https://static.xx.fbcdn.net/images/emoji.php/v9/t51/1/16/1f449.png) Nhưng không usable cho chat real-time ￼

![🧠](https://static.xx.fbcdn.net/images/emoji.php/v9/t7c/1/16/1f9e0.png) Best setup cho Mac 32GB

• ![🏆](https://static.xx.fbcdn.net/images/emoji.php/v9/tbe/1/16/1f3c6.png) Best overall: Qwen 3.5 35B MoE

• ![💻](https://static.xx.fbcdn.net/images/emoji.php/v9/t8c/1/16/1f4bb.png) Coding: Qwen 2.5 Coder 7B / 14B

• ![🤔](https://static.xx.fbcdn.net/images/emoji.php/v9/t34/1/16/1f914.png) Reasoning: DeepSeek R1 Distill

• ![⚡](https://static.xx.fbcdn.net/images/emoji.php/v9/t5d/1/16/26a1.png) Nhẹ & nhanh: Qwen 3.5 4B (~29 tok/s)

![👉](https://static.xx.fbcdn.net/images/emoji.php/v9/t51/1/16/1f449.png) Đây là “sweet spot” thực tế, không phải lý thuyết

![🛠️](https://static.xx.fbcdn.net/images/emoji.php/v9/tb9/1/16/1f6e0.png) Tool benchmark open-source

Project: mac-llm-bench

• Tự detect hardware

• Auto tải model phù hợp RAM

• Benchmark bằng llama-bench (standardized)

• Lưu kết quả + submit cộng đồng

![👉](https://static.xx.fbcdn.net/images/emoji.php/v9/t51/1/16/1f449.png) Không subjective, không prompt bias, chỉ đo raw tốc độ ￼

![🎯](https://static.xx.fbcdn.net/images/emoji.php/v9/tb0/1/16/1f3af.png) Mục tiêu lớn hơn

Không chỉ là test cá nhân.

![👉](https://static.xx.fbcdn.net/images/emoji.php/v9/t51/1/16/1f449.png) Đây là bước đầu xây:

• Database benchmark cho toàn bộ Apple Silicon (M1 → M5)

• So sánh performance theo chip thật, không phải lý thuyết

![🧠](https://static.xx.fbcdn.net/images/emoji.php/v9/t7c/1/16/1f9e0.png) Kết luận

Project này cho thấy 3 điều rất quan trọng:

1. Local LLM đã đủ mạnh để dùng thật

2. MoE là tương lai cho edge device

3. Benchmark thực tế quan trọng hơn spec
   
   Link repo: https://github.com/enescingoz/mac-llm-bench/tree/main/results/m5/base?fbclid=IwY2xjawRH5JdleHRuA2FlbQIxMABicmlkETE1TkZ5cWF0aDVVZERxNXpYc3J0YwZhcHBfaWQQMjIyMDM5MTc4ODIwMDg5MgABHjJdi2ckxKTaQ0ngNjSpUqmkjbMf79Avf4UQsqKAonCf44656qIN29J9CfL5_aem_U7Cz69wPikY-k9q-67PjoA