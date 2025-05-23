# 🧠 제4회 ETRI 휴먼이해 인공지능 논문경진대회 참여 프로젝트

본 저장소는 [제4회 ETRI 휴먼이해 인공지능 논문경진대회](https://dacon.io/competitions/official/236468/overview/description)에 참여하기 위해 생성되었습니다. 라이프로그 데이터를 활용하여 수면 품질 및 상태를 예측하는 모델을 개발하고자 합니다.

---

## 📌 대회 개요

- **주제**: 라이프로그 데이터를 활용한 수면 품질 및 상태 예측
- **주최**: 한국전자통신연구원 (ETRI)
- **후원**: 과학기술정보통신부, 국가과학기술연구회 (NST)
- **운영**: DACON
- **대회 기간**: 2025년 4월 14일 ~ 2025년 10월 14일
- **총 상금**: 770만원
- **참가 자격**: 만 18세 이상의 일반 성인 (중·고등학교 재학 중이 아닌 자)

---

## 🗂️ 데이터 설명

본 대회에서는 스마트폰, 스마트워치, 수면 센서, 자가 기록 앱을 통해 수집된 라이프로그 데이터와 수면 건강 관련 지표를 제공합니다.

총 **700일 분량**의 라이프로그 데이터는 아래 **12가지 항목**으로 구성되어 있으며, **비상업적 및 학술적 연구 목적**으로만 공개됩니다.

---

### 📱 라이프로그 데이터 항목 (12종)

| 항목 | 설명 |
|------|------|
| `mACStatus` | 스마트폰이 현재 충전 중인지 여부 |
| `mActivity` | Google 활동 인식 API로 계산된 활동 값 |
| `mAmbience` | 주변 소리 식별 레이블 및 해당 확률 |
| `mBle` | 개별 피험자 주변의 블루투스 장치 정보 |
| `mGps` | 1분 내 측정된 GPS 좌표들 |
| `mLight` | 스마트폰으로 측정한 주변 광량 |
| `mScreenStatus` | 스마트폰 화면이 사용 중인지 여부 |
| `mUsageStats` | 앱 사용량(어떤 앱을 얼마나 사용했는지) |
| `mWifi` | 개별 피험자 주변의 Wi-Fi 장치 정보 |
| `wHr` | 스마트워치로 기록한 심박수 데이터 |
| `wLight` | 스마트워치가 측정한 주변 조도 |
| `wPedo` | 스마트워치가 기록한 걸음 수 |

---

### 💤 수면 건강 예측 지표 (6종)

| 지표 | 설명 |
|------|------|
| `Q1` | 기상 직후 인지된 전반적인 수면의 질 |
| `Q2` | 수면 직전 신체적 피로도 |
| `Q3` | 수면 직전 스트레스 수준 |
| `S1` | 총 수면 시간(TST) 가이드라인 준수 여부 |
| `S2` | 수면 효율(SE) 가이드라인 준수 여부 |
| `S3` | 수면 시작 지연 시간(SOL/SL) 가이드라인 준수 여부 |

---

## 🧪 프로젝트 구조


---


## 📚 참고 문헌

1. **ETRI_Lifelog_Dataset_2020.** (2021)  
   [https://nanum.etri.re.kr/share/schung/ETRILifelogDataset2020](https://nanum.etri.re.kr/share/schung/ETRILifelogDataset2020)

2. **정승근 외.**  
   "인간 행동 연구를 위한 실세계 멀티모달 라이프로그 데이터셋", *ETRI 저널* 44.3 (2022): 426–437.

3. **오세원 외.**  
   "인간 이해 AI 논문 챌린지 2024--데이터셋 설계", *arXiv preprint* arXiv:2403.16509 (2024).

---
