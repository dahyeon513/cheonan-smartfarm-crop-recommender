# 🌱 SmartFarm Crop Recommendation

> 천안 지역 공공데이터 기반 **작물 추천 시스템**
> (단일 작물 추천 + 2작물 조합 추천)

---

## 📌 Overview
스마트팜 창업자가 “어떤 작물을 재배해야 가장 안정적이고 수익성이 높은지”  
데이터 기반으로 판단할 수 있도록 만든 **작물 추천 시스템**입니다.

### 평가 기준
- 🌡 **환경 적합성** (Ecocrop: 최적 온도/강수량/pH)
- 🐛 **병해충 위험도** (농촌진흥청 데이터)
- 💰 **가격 안정성 / 수익성** (KAMIS 도매가격)
- 📈 **가격 변동성(CV)** 기반 안정성
- ⭐ **Point Ranking (단일) / 2-crop Pair Ranking (복합)**

---

## ✨ Features

| 기능 | 설명 |
|------|------|
| ✅ 공공데이터 수집 (병해충, 가격, 기후) |
| ✅ 가격 예측 (Prophet 사용) |
| ✅ 단일 작물 추천 (Top-N Ranking) |
| ✅ 복합 작물 추천 (작물 2개 조합 평가) |
| ✅ Radar-chart 시각화 |

---

## 🧠 Tech Stack
- Python
- Pandas, NumPy
- Prophet (price forecasting)
- Matplotlib / Seaborn

---

## 📁 Project Structure
smartfarm-crop-recommendation/
├─ notebooks/
│  ├── pest_crawling.ipynb         # 병해충 데이터 수집
│  ├── forecast_price.ipynb        # 가격 예측
│  └── ranking_visualization.ipynb # 단일/복합 추천 + 시각화
├─ data/
│  └── README.md                   # 데이터 출처 (원본은 포함하지 않음)
└─ README.md

---

