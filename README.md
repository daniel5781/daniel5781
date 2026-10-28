<p align="center">
  <img src="assets/profile-banner.svg" alt="오동근 — Data Science &amp; Machine Learning. From domain to model." width="100%" />
</p>

<p align="center">
  식품 검사·유통 재고·스포츠 데이터로 예측 모델을 만들고 있습니다.<br />
  예측 시점의 정보와 검증 조건을 함께 점검합니다.
</p>

<p align="center">
  <a href="#프로젝트">프로젝트</a> ·
  <a href="#기술-스택">기술 스택</a>
</p>

## 프로젝트

### 황색포도상구균 검출확률 예측 · Active Research

비정기 검사 이력과 희소한 양성 사례를 다루는 모델링 연구입니다.
기준일까지 알 수 있는 정보로 피처를 구성하고, 검출 위험도와 검사 우선순위를 평가하고 있습니다.

[연구 내용과 담당 작업](projects/food-safety.md) · 원자료·팀 코드 비공개

### 세븐일레븐 재고 최적화

출시 후 4일간의 센터 → 점포 출고량을 예측하고, 발주 수량별 재고 부담을 비교했습니다.
팀 프로젝트에서 PM·전처리·모델 검증·재고 시뮬레이션·대시보드 구현에 참여했습니다.
공개 결과물은 **합성 데이터 모델 예제와 독립된 웹 데모**입니다.

[프로젝트 소개](projects/inventory.md) · [모델·검증 코드](https://github.com/daniel5781/7Eleven_MD_Dashboard/tree/main/modeling) · [웹 데모](https://daniel5781.github.io/7Eleven_MD_Dashboard/)

### LG Aimers

투구별 제구 확률을 예측하며 FTT의 표현 방식, 앙상블 기여, 투수 이력과 상황 효과의 분리를 실험했습니다.
**팀 성적: 예선 24위·본선 진출 / 본선 17위.**

[주요 실험과 개인 기여](projects/lg-aimers.md) · 대회 데이터·팀 코드 비공개

### 산업연관분석과 산업 네트워크

산업연관표와 Leontief 모형을 이용한 네트워크 분석 도구입니다.
BEA 자료 처리, 산업 분류 계층, 분석 모듈 분리에 기여했으며 공개 커밋으로 연결했습니다.

[기능과 기여 근거](projects/industrial-network.md) · [개인 작업 저장소](https://github.com/daniel5781/khu-subapp)

## 기술 스택

| 영역 | 도구 |
| --- | --- |
| 언어·데이터 처리 | Python · SQL · pandas · NumPy |
| 모델링 도구 | scikit-learn · LightGBM · CatBoost · PyTorch |
| 분석·화면 구현 | NetworkX · Matplotlib · Streamlit · React |
| 개발·실험 | Git · Jupyter |

<details>
<summary><b>기타 경험</b></summary>

- **LLM-based Financial Assistant** — 금융 도메인 질의응답 프로토타입, GPT-3 fine-tuning과 RAG 접근 비교.
- **Weather & Traffic Accident Prediction** — 기상·교통 데이터를 결합한 지역별 사고 패턴 분석과 예측 실험.
- **Generative AI Advertisement Prototype** — 생성형 이미지, 객체 탐지, 텍스트 배치 영역 탐색을 결합한 광고 제작 실험.

</details>

<sub>기업·대회·연구 원자료와 비공개 팀 코드는 제외하고, 프로젝트 소개와 합성 데이터 기반 실행 예제를 공개합니다.</sub>
