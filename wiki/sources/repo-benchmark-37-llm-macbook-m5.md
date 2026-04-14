---
title: "Repo Benchmark 37 LLM trên MacBook Air M5"
type: source
tags: [AI, LLM, Benchmark, Apple Silicon, Local LLM, MoE]
date: 2026-04-12
source_file: raw/AI/Repo Benchmark 37 LLM trên MacBook Air M5.md
---

## Summary
Báo cáo về kết quả benchmark 37 mô hình ngôn ngữ lớn (LLM) trên phần cứng MacBook Air M5 (32GB RAM). Tài liệu nhấn mạnh ưu thế vượt trội của kiến trúc Mixture of Experts (MoE) trong việc tối ưu hóa tốc độ xử lý trên các thiết bị đầu cuối (edge devices). Ngoài ra, báo cáo giới thiệu công cụ mã nguồn mở `mac-llm-bench` giúp cộng đồng tự thực hiện benchmark và xây dựng cơ sở dữ liệu hiệu năng cho các dòng chip Apple Silicon.

## Key Claims
- Kiến trúc MoE (Mixture of Experts) giúp tăng tốc độ xử lý lên đến 12 lần so với mô hình Dense có cùng lượng RAM (ví dụ: Qwen 3.5 35B MoE đạt ~31 tok/s trong khi bản Dense 32B chỉ đạt ~2.5 tok/s).
- Giới hạn "32GB wall" trên Mac khiến các mô hình Dense 32B trở nên không khả dụng cho chat real-time (~2.5 tok/s).
- Các mô hình khuyến nghị cho Mac 32GB: Qwen 3.5 35B MoE (Best overall), Qwen 2.5 Coder 7B/14B (Coding), DeepSeek R1 Distill (Reasoning), Qwen 3.5 4B (Lightweight).
- Benchmark thực tế quan trọng hơn thông số kỹ thuật (spec) lý thuyết.

## Key Quotes
> "MoE đang 'phá game'... Nhanh hơn ~12x nhưng RAM tương đương."
> "Đây là 'sweet spot' thực tế, không phải lý thuyết."

## Connections
- [[Apple-Silicon]] — Nền tảng phần cứng thực hiện benchmark.
- [[Local-LLM]] — Xu hướng chạy mô hình AI trực tiếp trên thiết bị cá nhân.
- [[Mixture-of-Experts-MoE]] — Công nghệ then chốt giúp tối ưu hiệu năng.
- [[Qwen-3.5-35B-MoE]] — Mô hình đạt hiệu năng ấn tượng nhất trong bài test.
- [[DeepSeek-R1]] — Mô hình khuyến nghị cho tác vụ suy luận (Reasoning).
- [[Mac-LLM-Bench]] — Công cụ benchmark được giới thiệu.

## Contradictions
- Không có mâu thuẫn trực tiếp với các nội dung khác trong wiki, nhưng bổ sung thêm khía cạnh kỹ thuật về hiệu năng phần cứng cho hệ thống [[LLM-Wiki-Agent]].
