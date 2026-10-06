# AI Systems Research & Engineering

AI Systems Researcher / Software Architect

Agent Harness · LLM/RAG · AI Infrastructure · Computer Vision

AI 연구방법론과 시스템 설계 경험을 바탕으로, 모델 적응부터 도메인 근거 검증과
실행 제어까지 연결하는 AI 시스템을 개발합니다.

## Selected Engineering Work

실제 운영한 도메인 AI 플랫폼의 구현 경험을 **실행·검증 / 모델 적응 / 이미지 도구 / 데이터·리포트**의 네 가지 기술 책임으로 구분해 정리했습니다. 각 저장소는 하나의 AI 시스템을 서로 다른 관점에서 설명하며, 전체 실행·검증 구조는 Agent Harness 저장소를 중심으로 연결됩니다.

1. [Reliable Domain Agent Harness](https://github.com/YeongjoonKim/reliable-domain-agent-harness)
   — 질문의 정보 요구, 도구 실행과 근거를 검증하는 실행 구조.
   제한된 복구, Docker Sandbox, configuration/evidence replay와 MCP stdio 구현.
   관리자 API·서명 실행기·컨테이너 제어와 실제 Scientific 실행 기록을 함께 제공합니다.
2. [Efficient Fine-tuning Lab](https://github.com/YeongjoonKim/efficient-finetuning-lab)
   — QLoRA 학습·실험 관리·vLLM adapter serving 경험과 별도의 CPU 재현 예제.
3. [Multimodal Domain AI](https://github.com/YeongjoonKim/multimodal-domain-ai)
   — Vision 후보를 표준명·공식 근거·상담으로 연결한 구조와 실제 실패 사례 분석.
4. [AI Domain Intelligence Reporting](https://github.com/YeongjoonKim/ai-domain-intelligence-reporting)
   — 공공데이터 수집·추출·보정, 관리자 검수와 근거 기반 리포트 생성.

각 저장소는 운영 경험을 설명하는 문서·화면과 독립적으로 작성한 공개 참조 구현을 담습니다.
공개 예제의 합성 평가와 운영 모델·서비스 평가는 구분합니다.

| 확인할 내용 | 바로 보기 |
|---|---|
| 전체 실행 구조 | [운영 상담·Scientific Runtime·Public Core](https://github.com/YeongjoonKim/reliable-domain-agent-harness/blob/main/docs/architecture/01_system_architecture.svg) |
| 실행 권한과 운영 제어 | [관리자 API → 서명 요청 → 호스트 실행기](https://github.com/YeongjoonKim/reliable-domain-agent-harness/blob/main/docs/execution-control.md) |
| 검증·재현과 비용 관측 | [실제 저장된 실행·인용·모델 사용량](https://github.com/YeongjoonKim/reliable-domain-agent-harness/blob/main/docs/scientific-execution.md) · [실행 가능한 공개 코어](https://github.com/YeongjoonKim/reliable-domain-agent-harness/blob/main/docs/public-core.md) |

## Selected Research

영상 복원·품질 평가, Few-shot Learning, Vision-Language 연구에서 다룬
모델 설계와 평가 경험을 현재의 AI 시스템 개발로 확장하고 있습니다.

### Enhancing video frame interpolation with region of motion loss and self-attention mechanisms: A dual approach to address large, nonlinear motions

**Neurocomputing, 2025**

큰 비선형 움직임의 프레임 보간을 위해 Region of Motion loss와 self-attention을 결합한 연구.
Research focus: Video Frame Interpolation · Motion-aware Loss · Self-attention.
Technical contribution: 연구 개념 및 방법론 설계.

### Bidirectional meta-Kronecker factored optimizer and Hausdorff distance loss for few-shot medical image segmentation

**Scientific Reports, 2023**

적은 의료영상으로 분할 모델을 적응시키기 위해 meta-optimizer와 경계 기반 loss를 결합한 연구.
Research focus: Few-shot Learning · Meta-learning · Medical Image Segmentation.
Technical contribution: 알고리즘 설계·개발 및 실험.

### Video Quality Assessment System Using Deep Optical Flow and Fourier Property

**IEEE Access, 2023**

Deep optical flow로 카메라 흔들림을, Fourier 특성으로 흐림을 분석하는 영상 품질 평가 연구.
Research focus: Video Quality Assessment · Optical Flow · Frequency Analysis.

### VLM-HOI: Vision Language Models for Interpretable Human-Object Interaction Analysis

**ECCV 2024 Workshops, 2025**

사람·객체·상호작용을 표현한 텍스트와 이미지의 VLM 유사도를 대조학습에 활용하는 연구.
Research focus: Vision-Language Models · Human-Object Interaction · Contrastive Learning.

## Engineering

Fullstack · Python · FastAPI · Docker · vLLM · PostgreSQL · Vector Search · MSSql

LLM Agents · RAG · Model Adaptation · Evidence Verification · AI Serving
