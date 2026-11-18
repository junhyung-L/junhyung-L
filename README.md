# 이준형 Junhyung Lee | Data Scientist

고객·정책·공간 데이터로 예측 모델과 의사결정 시뮬레이션을 만들고, 각 결과가 어디까지 유효한지 함께 밝힙니다.

- **현재** 하나금융융합기술원 BigData&AI Cell 인턴 (2026.07–)
- **연구** [DIVE Lab](https://github.com/thekimk/DIVE-Research) 학부연구생 (2025.02–2026.02) — 마케팅 피로도의 처치 효과를 위한 인과추론·준실험 설계
- **관심** Machine Learning · RecSys · GIS · Causal Inference · XAI

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

## 수상 프로젝트

| 수상 | 프로젝트 | 내용 |
|---|---|---|
| **대상** · 2024 임업통계 스마트활용 경진대회 (산림청·한국임업진흥원, 2024.12) | [forestry-crop-suitability](https://github.com/junhyung-L/forestry-crop-suitability) | GIS·기후·토양·생산 데이터를 연결해 작물 적합지와 생산량 분석 |
| **대상** · 2025 PBL 프로그램 인천광역시장상 (2026.02) | [dongincheon-marketing-pilot](https://github.com/junhyung-L/dongincheon-marketing-pilot) | Marketing & Data Analysis 역할, 공실 데이터·현장 조사 기반 마담티 30일 마케팅 파일럿 |
| **금상** · 인천대학교 산학 캡스톤디자인 경진대회 (2025.07) | [incheon-eeum-policy-simulation](https://github.com/junhyung-L/incheon-eeum-policy-simulation) | 예산 제약 아래 66개 캐시백 정책 시나리오 비교 |

## 연구

**[마케팅 피로도와 구매 전환 예측](https://github.com/junhyung-L/crm-conversion-prediction)** — REES46 다채널 CRM 로그 약 1억 7,200만 건(고객 약 185만 명, 캠페인 1,907개)에서 구매 주기·반응 시점·피로도·채널 효과성 피처를 설계했습니다. 원고의 원분포 holdout에서 XGBoost F1 0.3806, PR-AUC 0.3620. 상위 0.78% 선별 시 전환 95.83% 포착·발송 대상 99.22% 감소는 오프라인 모의 선별 결과이며, 실제 비용 절감이나 인과 효과가 아닙니다.

## 대표 프로젝트

| 프로젝트 | 구현·분석 초점 | 결과 (측정 조건) |
|---|---|---|
| [ctr-sequence-modeling](https://github.com/junhyung-L/ctr-sequence-modeling) | DCN-V2 + DIN·DIEN·BST 행동 시퀀스 인코더, 262,144개 해시 버킷 | DIEN 검증 ROC-AUC 0.7413, PR-AUC 0.0792 |
| [used-ev-price-forecasting](https://github.com/junhyung-L/used-ev-price-forecasting) | 배터리 용량 모델 기반 대체 + XGBoost 가격 회귀 | 사용자 확인 DACON 정규화 RMSE 0.919 |
| [credit-card-customer-segmentation](https://github.com/junhyung-L/credit-card-customer-segmentation) | 학습 240만 행·857개 변수의 결측 처리와 세그먼트 분류 | 2만 건 검증 스태킹 weighted F1 0.8936 |
| [ai-interview-simulator](https://github.com/junhyung-L/ai-interview-simulator) | Next.js 역할극·피드백 API, 실제 LLM·데모 모드 분리 | 9개 시나리오, 선택적 Supabase 세션 기록 |

수치마다 측정 조건(검증·holdout·리더보드·시뮬레이션)이 다릅니다. 데이터 분할과 공개 범위는 각 저장소 README에 정리했습니다. 전체 11개 프로젝트는 [포트폴리오](https://github.com/junhyung-L/Portfolio/blob/main/README.ko.md)에 있습니다.

[포트폴리오](https://github.com/junhyung-L/Portfolio/blob/main/README.ko.md) · [이력서](https://github.com/junhyung-L/Resume) · [LinkedIn](https://www.linkedin.com/in/junhyung-lee-data) · [Email](mailto:jun010914@inu.ac.kr)

<details>
<summary><b>English</b></summary>

I build prediction models and decision simulations from customer, policy, and spatial data, and state how far each result holds.

- **Now** Intern, BigData&AI Cell, Hana Financial Convergence Technology Institute (Jul 2026–)
- **Research** Undergraduate researcher, [DIVE Lab](https://github.com/thekimk/DIVE-Research) (Feb 2025–Feb 2026) — causal-inference and quasi-experimental designs for marketing-fatigue treatment effects
- **Interests** Machine Learning · RecSys · GIS · Causal Inference · XAI

### Awards

| Award | Project | Work |
|---|---|---|
| **Grand Prize** · 2024 Forestry Statistics Smart Use Competition (Korea Forest Service & Korea Forestry Promotion Institute, Dec 2024) | [forestry-crop-suitability](https://github.com/junhyung-L/forestry-crop-suitability) | Crop suitability and yield analysis combining GIS, climate, soil, and production data |
| **Grand Prize** · 2025 PBL Program, Incheon Metropolitan City Mayor Award (Feb 2026) | [dongincheon-marketing-pilot](https://github.com/junhyung-L/dongincheon-marketing-pilot) | Marketing & Data Analysis role; 30-day Madam Tea marketing pilot based on vacant-store data and field research |
| **Gold Prize** · Industry-Academic Capstone Design Competition, Incheon National University (Jul 2025) | [incheon-eeum-policy-simulation](https://github.com/junhyung-L/incheon-eeum-policy-simulation) | Comparison of 66 budget-constrained cashback policy scenarios |

### Research

**[Marketing Fatigue and Purchase Conversion Prediction](https://github.com/junhyung-L/crm-conversion-prediction)** — From approximately 172 million REES46 multichannel CRM logs (about 1.85 million customers, 1,907 campaigns), I designed purchase-cycle, response-timing, fatigue, and channel-effectiveness features. On the manuscript's original-distribution holdout, XGBoost reached F1 0.3806 and PR-AUC 0.3620. Selecting the top 0.78% captured 95.83% of conversions with 99.22% fewer candidates; this is an offline ranking simulation, not realised savings or causal uplift.

### Selected projects

| Project | Focus | Result (setting) |
|---|---|---|
| [ctr-sequence-modeling](https://github.com/junhyung-L/ctr-sequence-modeling) | DCN-V2 with DIN/DIEN/BST behaviour-sequence encoders, 262,144 hash buckets | DIEN validation ROC-AUC 0.7413, PR-AUC 0.0792 |
| [used-ev-price-forecasting](https://github.com/junhyung-L/used-ev-price-forecasting) | Model-based battery-capacity imputation + XGBoost price regression | User-confirmed DACON normalized RMSE 0.919 |
| [credit-card-customer-segmentation](https://github.com/junhyung-L/credit-card-customer-segmentation) | Missingness-aware segmentation over 2,400,000 training rows and 857 features | Stacking weighted F1 0.8936 on a 20k validation sample |
| [ai-interview-simulator](https://github.com/junhyung-L/ai-interview-simulator) | Next.js roleplay and feedback APIs, separate live-LLM and demo paths | Nine scenarios, optional Supabase session history |

Each figure has its own setting (validation, holdout, leaderboard, simulation); splits and data availability are documented in each repository's README. All 11 projects are in the [Portfolio](https://github.com/junhyung-L/Portfolio).

[Portfolio](https://github.com/junhyung-L/Portfolio) · [Resume](https://github.com/junhyung-L/Resume/blob/main/README.en.md) · [LinkedIn](https://www.linkedin.com/in/junhyung-lee-data) · [Email](mailto:jun010914@inu.ac.kr)

</details>
