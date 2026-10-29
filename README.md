# 노영빈 (Noh Youngbeen)

2D 포즈 기반 스포츠 동작 분석을 연구하고, 그 결과를 골프·양궁 AI 분석 서비스로 만들고 있습니다.

인천대학교 대학원 임베디드시스템공학과 석사과정(2027.02 졸업 예정) · 인공지능 응용 시스템 연구실

- Email: noyoungbin40@gmail.com
- 관심 분야: 2D Pose Estimation · Motion Representation Learning · AI 서비스 백엔드

## Research

- **Learning Professional Golf Swing Signatures from Monocular 2D Pose: A Controlled Study of Coordinate Normalization and Phase Decomposition**
  **Y.-B. Noh**, J.-E. Byun, K.-I. Hwang — *Sensors* (투고 중) · [code](https://github.com/Youngbeen-Noh/golf-swing-phase-reid)
  프로 골퍼 25명·영상 450개로 인코더·좌표 정규화·구간 구성 45개 조합을 통제 비교, 보류 테스트 Top-1 91.5%
- **A Spatial-Temporal Normalized Contrastive Embedding for Robust Motion Similarity Retrieval**
  S.-S. Lee, **Y.-B. Noh**, H. Y. Jeong, K.-I. Hwang — *Computers, Materials & Continua* 88(3), 2026 · [DOI](https://doi.org/10.32604/cmc.2026.081251)
- **Reinforcement Learning-Based Golf Swing Correction Framework Incorporating Temporal Rhythm and Kinematic Stability**
  D.-J. Lee, **Y.-B. Noh**, J. Byun, K.-I. Hwang — *Sensors* 26, 392, 2026 · [DOI](https://doi.org/10.3390/s26020392)

## Projects

| 프로젝트 | 역할 | 내용 |
|---|---|---|
| **MoVine** — AI 양궁 퍼포먼스 플랫폼 ([서비스](https://ar2.tempodiall.com)) | V1 단독 개발 · V2 Backend | 엔드 영상을 화살 단위로 자동 분할해 자세·리듬을 분석. FastAPI · PostgreSQL · AWS(ECS·SQS·RDS·S3) 비동기 분석 파이프라인 |
| **KM** — AI 골프 스윙 분석 | 4인 팀 | MediaPipe 기반 스윙 분석, 측면+정면 듀얼 뷰를 촬영부터 재생 UI까지 구현 |
| **자율주행 AI 챌린지 2025** | 팀장 | 실시간 시맨틱 세그멘테이션, 연산량 제한 안에서 mIoU 42.22 → 50.97, 43팀 중 9위 |
| [Luckthon](https://github.com/Youngbeen-Noh/Luckthon) | CV 서버·웹 연동 | YOLO11 인원 산출로 건물 평면도 위에 실시간 혼잡도 표시 |
| [AI_project](https://github.com/Youngbeen-Noh/AI_project) | 개인 | 프레임워크 없이 CUDA C++로 MLP 순전파·역전파 직접 구현 |

> 연구실 프로젝트(MoVine, KM)는 비공개 저장소라 코드 대신 서비스와 포트폴리오로 소개합니다.

## Tech

`Python` `PyTorch` `MediaPipe` `YOLO` `OpenCV` `FastAPI` `NestJS` `PostgreSQL` `AWS` `Docker` `React`
