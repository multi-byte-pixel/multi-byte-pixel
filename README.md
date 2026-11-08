# Jonathan Canady

Senior SDET and AI quality engineer. I build test automation and evaluation gates for web, API, cloud and LLM/RAG/agent systems, and I review AI-written code for the ways it quietly breaks those gates.

## Featured work

- **[non-deterministic-eval-sandbox](https://github.com/multi-byte-pixel/non-deterministic-eval-sandbox)**: three realistic failures in agent-written LLM-eval code (a weakened faithfulness test, a Ragas gate that passes on `NaN`, exact-match asserts on Bedrock output with an over-broad IAM policy). Each fix is its own PR with root cause and reasoning.
- **[grad-cam-1](https://github.com/multi-byte-pixel/grad-cam-1)**: Grad-CAM / Grad-CAM++ from scratch for visual QA, with explanation-quality metrics, artifact-integrity checks and an offline pytest suite.

## Toolkit

Python · pytest · DeepEval · Ragas · LangChain · Amazon Bedrock · AWS · Playwright · PyTorch · GitHub Actions

## Focus

LLM and agent evaluation · test design for non-deterministic systems · reviewing and grading AI-generated code · CI quality gates
