# Hi, I'm Abbas Ramazanov 👋

**AI Engineer** with a production backend core. Python and PyTorch for the models, Java and Kafka for the systems around them.

I build ML services end to end: RAG with hybrid retrieval, LLM fine-tuning with LoRA, real-time fraud scoring, computer-vision inference on ONNX Runtime. Before that, 3+ years of Java/Spring backend work (sole backend developer of a company-wide accounting & HR platform, a construction ERP, high-volume telemetry pipelines) and a performance-critical C++ / game-dev background. I care about what code costs at runtime.

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-ML-EE4C2C?logo=pytorch&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-Runtime-005CED?logo=onnx&logoColor=white)
![Java](https://img.shields.io/badge/Java-17-orange?logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3-6DB33F?logo=springboot&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache-Kafka-231F20?logo=apachekafka&logoColor=white)
![CI](https://img.shields.io/badge/GitHub-Actions-2088FF?logo=githubactions&logoColor=white)

## Featured projects

| Project | What it shows |
|---|---|
| [rag-knowledge-platform](https://github.com/abbas1123/rag-knowledge-platform) | Document Q&A with **hybrid retrieval** (dense embeddings + BM25, RRF fusion) on Qdrant, a golden-set eval harness (hit@k / MRR across retrieval modes) and an extractive fallback when no LLM key is set |
| [realtime-fraud-ml](https://github.com/abbas1123/realtime-fraud-ml) | **XGBoost fraud scoring** on a card-transaction stream: leakage-free point-in-time features, MLflow tracking, Evidently drift report, Kafka scoring consumer (PR-AUC 0.95 vs 0.83 baseline) |
| [llm-merchant-finetune](https://github.com/abbas1123/llm-merchant-finetune) | **LoRA fine-tuning** of Qwen2.5-0.5B (transformers + peft) to normalize card-statement merchant strings: category accuracy 18.6% → 98.2% vs zero-shot, before/after eval harness |
| [vision-liveness-service](https://github.com/abbas1123/vision-liveness-service) | Face **anti-spoofing**: MobileNetV3 trained against synthesized print/replay attacks, exported to ONNX and served torch-free at ~3 ms/image on CPU |

The ML work builds on the Java side of this account: realtime-fraud-ml picks up where [realtime-transaction-analytics](https://github.com/abbas1123/realtime-transaction-analytics) (Kafka Streams, rule-based) leaves off, while [payment-transactions-api](https://github.com/abbas1123/payment-transactions-api) and [fx-rates-service](https://github.com/abbas1123/fx-rates-service) cover the backend patterns: Oracle PL/SQL business rules, resilience, caching. Everything ships with tests and green GitHub Actions pipelines.

## Contact

[LinkedIn](https://www.linkedin.com/in/abbas-ramazanov-943b3422b) · aramazanov107@gmail.com · Sumgayit, Azerbaijan
