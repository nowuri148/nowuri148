# Hi, I'm Nuri! 👋

### Multimodal AI · Reinforcement Learning · Vision AI · V2X · Applied AI · SW Engineering

I am interested in designing AI systems that connect **data → prediction → decision-making → validation → real-world services**.

Currently, I am researching V2X decision-making and resource optimization using multimodal AI and reinforcement learning.

---

## 🔬 Research

### Multimodal Cost-Aware DRL for Beam Realignment in mmWave V2X Communications
**ICAIIC 2026 · Excellent Paper Award**

A proactive beam-management framework that predicts future link degradation and determines **when beam realignment is necessary**.

- Fused temporal features from visual data and mmWave received-power sequences
- Designed a PPO-based decision policy considering both link quality and realignment cost
- Performed ablation studies on visual information and temporal modeling
- Proactively responded **0.64 s before link-quality degradation**
- Achieved **38.2% proactive realignment success rate**
- Reduced unnecessary beam realignments by **26.3%**

**Tech**  
`Python` `PyTorch` `YOLO` `GRU` `PPO` `DeepSense 6G`

---

### Multimodal Two-Stage Beam Realignment Framework for mmWave V2X
**KICS Summer Conference 2026**

A follow-up study extending the decision problem from **“when to realign”** to **“which region to explore when realignment is required.”**

- Grouped 64 beams into 8 regions and predicted the future beam region from multimodal temporal features
- Stage 1: PPO decides whether to maintain/re-align and selects the region to explore
- Stage 2: a supervised model selects the final beam within the chosen region
- Reduced the search space from **64 beams to at most 8 candidates**
- Achieved **96.03% Power Capture Ratio**
- Achieved **97.21% Effective Achievable Rate Ratio**

**Tech**  
`Python` `PyTorch` `YOLO` `GRU` `PPO` `DeepSense 6G`

---

### Uncertainty-Aware Dynamic Beam Resource Allocation
**Hanyang University CAM Lab · 2026 – Present**

An uncertainty-aware decision framework that dynamically adjusts beam-search resources according to prediction confidence.

- Predicted future beam states from image and mmWave received-power sequences
- Estimated uncertainty from ensemble prediction disagreement
- Designed PPO to determine the search range using prediction, uncertainty, and current link state
- Allocated fewer resources for high-confidence cases and expanded exploration under uncertainty
- Achieved **92.54% within 1 dB of the optimal beam** while exploring **1.77 candidates on average**

**Tech**  
`Python` `PyTorch` `YOLO` `GRU` `PPO` `Ensemble` `DeepSense 6G`

---

### Facial Emotion Recognition-Based Empathic Avatar Generation Technology
**Co-author · Korea Multimedia Society Fall Conference 2024**

An end-to-end AI service that recognizes facial emotion in real time and connects the inference result to an interactive 3D avatar and user-facing functions.

- Applied an MTCNN-based facial emotion recognition model
- Stabilized frame-level prediction variation using smoothing
- Modeled empathy using time delay and expression intensity
- Implemented 14 avatar expressions: 7 emotions × 2 intensity levels
- Connected Android · Python · Firebase · Unity into an end-to-end service pipeline

**Tech**  
`Python` `Android` `Unity` `Firebase` `HTTP` `JSON`

---

## 🚀 주요 프로젝트

### 📄 미래에셋증권 AI Festival 2026 — 공시 QA Agent

기업 공시를 검색·분석하고 근거와 함께 답변하는 질의응답 Agent를 개발했습니다.

- 자연어 질의에서 기업·기간·문서유형·지표·작업 유형 구조화
- BGE-M3 + Chroma 기반 공시 검색
- HNSW 검색, Python post-filter, adaptive candidate expansion을 적용해 검색 구조 개선
- 의미 유사도와 키워드·지표 일치도를 반영한 Reranking
- 검색 근거만 활용한 답변 생성 및 출처 연결
- FastAPI 기반 평가 API 구현 및 Naver Cloud 배포
- Nginx · HTTPS · systemd를 활용한 외부 서비스 환경 구성

**Tech**  
`Python` `LLM` `HyperCLOVAX` `BGE-M3` `Chroma` `Reranking` `FastAPI` `Naver Cloud`

---

### 💰 한화생명 AI 금융 아이디어 공모전
**MZ 소비 패턴 기반 XAI 연금 리밸런싱 Agent**

소비·세무 정보를 활용해 추천 근거를 설명하고 실제 금융 행동까지 연결하는 Agent 구조를 기획했습니다.

- 소비·세무 정보를 AI가 활용할 수 있는 Context로 통합
- SHAP 기반 포트폴리오 추천 근거 설명
- Counterfactual AI를 활용한 행동 변화 시나리오 제안
- Tool Call을 통해 분석 결과를 실제 금융 Action으로 연결하는 구조 설계
- 세액공제 환급금을 다시 투자하는 Tax-Return → Reinvestment Loop 제안
- 적합성 원칙, 설명의무, 명시적 동의 등 금융 규제·리스크 고려

**Tech**  
`XAI` `SHAP` `Counterfactual AI`

---

## 🧪 Research Projects & Experience

### 차세대 모빌리티 고속통신 전파예측 기술 연구
**한양대학교 CAM Lab · 2026.04 – 2026.12**

멀티모달 AI 기반 V2X 통신환경 분석과 빔 자원 의사결정 알고리즘 설계·성능 검증을 수행하고 있습니다.

- 이미지와 mmWave 수신전력 시퀀스를 활용한 미래 빔 상태 예측
- Ensemble 기반 예측 불확실성 추정
- PPO 기반 동적 탐색 자원 배분
- 정확도와 자원 효율 간 trade-off를 정량적으로 검증

**Tech**  
`Python` `PyTorch` `YOLO` `GRU` `PPO` `Ensemble` `DeepSense 6G`

---

### Beyond-G 글로벌 혁신센터
**한양대학교 CAM Lab · 2025.05 – Present**

멀티모달 AI 기반 V2X Connectivity 의사결정 연구와 통합 검증 시나리오 설계에 참여했습니다.

- Vision과 mmWave 수신전력을 활용한 핸드오버 의사결정 연구
- 연구 범위를 핸드오버에서 빔 관리 최적화로 확장
- Radio SLAM · ISAC · Vision · Robotics 간 데이터 흐름과 연동 관계 검토
- 센서 신뢰도 저하 상황을 고려한 상호 보완형 시스템 시나리오 설계

**Tech**  
`Python` `PyTorch` `ViT` `GRU` `Multimodal Fusion` `V2X`

---

### 생성형 AI 기반 공감형 아바타 생성 기술 연구
**숙명여자대학교 IVPL · 학부연구생 · 2024.03 – 2024.08**

얼굴 감정 인식 결과를 아바타와 콘텐츠 기능으로 연결하는 End-to-End AI 서비스 파이프라인을 개발했습니다.

- Android 카메라 입력을 Python 감정 인식 모듈과 연결
- 추론 결과를 Unity 아바타 표정에 반영
- Socket 기반 구조의 연결 불안정 문제를 분석해 HTTP 방식으로 개선
- 감정값·얼굴 Landmark·Timestamp를 JSON 형태로 저장·전달
- 추론 결과를 음악·명상 콘텐츠와 비상 연락망 기능으로 연결

**Tech**  
`Python` `Android` `Unity` `Firebase` `HTTP` `JSON`

---

### 사용자 감정 인식을 위한 시각 신호 분석과 공감 모델링 기술 개발
**숙명여자대학교 IVPL · 학부연구생 · 2024.09 – 2024.11**

텍스트와 비디오의 감정 예측 불일치를 분석하고 멀티모달 Fusion 알고리즘을 설계했습니다.

- 7개 감정 간 관계를 각도와 좌표로 표현한 감정 유사도 그래프 설계
- Top-3 예측 결과 간 cosine similarity를 활용한 이상치 제거
- 모달리티별 특성을 반영한 가중 Fusion 구조 설계
- 복합 감정의 상대적 강도를 반영한 최종 판단 로직 구현

**Tech**  
`Python` `Multimodal Fusion` `Cosine Similarity` `Emotion Recognition`

---

## 🏆 Awards

| 수상 | 결과 | 연도 |
| --- | --- | ---: |
| ICAIIC 2026 | **Excellent Paper Award** | 2026 |
| AI PC 이미지 인식 및 생성형 AI 해커톤 | **3위** | 2024 |
| MEIT 융합프로젝트 대회 | **장려상** | 2022 |

---

## 🌏 활동

### UNESCO UNITWIN
**라오스 국립대학교 React Native 멘토링**

- 2개 팀의 개발 환경 설정, 아이디어 구체화, 기능 구현, 최종 시연 지원
- API 문서를 함께 분석하며 학생들이 직접 문제를 해결할 수 있도록 멘토링

**Tech**  
`React Native` `API`

### UMC 3·4기
- Android 프론트엔드 및 Spring Boot 백엔드 개발
- API 응답 구조와 화면 데이터 불일치 문제 분석 및 인터페이스 재정의
- DB 구조와 API 설계 경험

**Tech**  
`Android` `Spring Boot` `JPA` `MySQL`

### 학생회
- 총무·재정 업무 수행
- 예산 집행, 물품 조달, 장부·증빙 관리 및 정기 재정검사 대응

---

## 🛠 Tech Stack

### AI / ML
`Python` `PyTorch` `YOLO` `ViT` `GRU` `PPO` `Multimodal Fusion`

### Backend / Application
`FastAPI` `Spring Boot` `Android` `Unity` `Firebase`

### Data / Simulation
`MATLAB` `WiLabV2Xsim` `DeepSense 6G`

### Tools
`Git` `GitHub` `Linux`

---

## 🎯 Focus

```text
Data
→ Prediction
→ Decision
→ Validation
→ Service
```

**AI 모델의 결과를 실제 의사결정과 서비스로 연결하는 시스템을 만들고 있습니다.**
