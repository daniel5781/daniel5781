<p align="center">
  <img src="assets/profile-banner.svg" alt="Daniel — Data Science & Machine Learning. From data to decisions." width="100%" />
</p>

<p align="center">
  <b>Predictive Modeling · Temporal Validation · Decision Support</b><br />
  식품 안전·유통 재고·스포츠 데이터를 활용해 확률과 수량을 예측합니다.
</p>

<p align="center">
  <a href="#current-focus">Current Focus</a> ·
  <a href="#selected-projects">프로젝트</a> ·
  <a href="#approach-in-practice">프로젝트별 접근</a> ·
  <a href="#toolkit">기술 스택</a>
</p>

## Current Focus

| 프로젝트 | 연구 초점 | 상태 | 공개 자료 |
| --- | --- | --- | --- |
| **황색포도상구균 검출확률 예측** | 희소 양성 데이터의 위험도 예측과 검사 우선순위 평가 | **Active Research** | [소개](projects/food-safety.md) · 코드 비공개 |

## Selected Projects

| 프로젝트 | 문제와 접근 | 결과 | 공개 자료 |
| --- | --- | --- | --- |
| **세븐일레븐 재고 최적화** | 신상품 초도발주 예측·발주 수량별 재고 비교 | 예측 모델·재고 시뮬레이션·MD 대시보드 구현<br>합성 데이터 실행 예제 공개 | [소개](projects/inventory.md) · [코드](https://github.com/daniel5781/7Eleven_MD_Dashboard) |
| **LG Aimers** | 야구 경기 상황과 선수 이력을 제구 확률 예측으로 연결 | **예선 24위 · 본선 진출**<br>**본선 17위** | [소개](projects/lg-aimers.md) · 코드 비공개 |
| **산업연관분석** | Leontief 모형과 네트워크로 산업 간 파급효과 분석 | 산업 분류 계층·BEA 자료 처리 확장 | [소개](projects/industrial-network.md) · [코드](https://github.com/daniel5781/khu-subapp) |

프로젝트별 소개에서 담당 역할, 기술적 접근, 검증 과정과 공개 결과물을 확인할 수 있습니다.

## Approach in Practice

- **희소 양성 데이터와 검사 우선순위 — [황색포도상구균](projects/food-safety.md)**<br />
  비정기 검사 이력에서 예측 시점까지의 정보로 피처를 구성하고 있습니다. Average Precision·Recall과 검사 효율을 함께 확인하며, 희소한 양성 사례를 찾는 모델을 개선하고 있습니다.

- **출고 예측과 발주 수량별 재고 비교 — [세븐일레븐](projects/inventory.md)**<br />
  출시 후 4일간의 센터 출고량을 타깃으로 두고, 고정 발주 공식과 모델 예측을 비교했습니다. 발주 수량에 따른 과소·과다 물량과 잔여 재고를 시뮬레이션해 수량 검토에 연결했습니다.

- **도메인 이해를 모델 설계로 연결 — [LG Aimers](projects/lg-aimers.md)**<br />
  경기 상황·선수 이력·리그별 기록 차이를 파악해 피처와 보정 방식에 반영했습니다. 예선과 본선의 타깃·평가 기준 변화에 맞춰 모델을 재구성하며, 도메인 분석부터 모델 개발과 대회 제출까지 수행했습니다.

## Toolkit

| 영역 | 도구 |
| --- | --- |
| Data | Python · SQL · pandas · NumPy |
| Modeling | scikit-learn · LightGBM · CatBoost · FT-Transformer |
| Analysis & Applications | Streamlit · NetworkX · Matplotlib · React |
| Workflow | Git · Jupyter · 실험 기록 · 시계열 검증 |

<details>
<summary><b>Other Work</b></summary>

- **LLM-based Financial Assistant** — 금융 도메인 질의응답 프로토타입, GPT-3 fine-tuning과 RAG 접근 비교.
- **Weather & Traffic Accident Prediction** — 기상·교통 데이터를 결합한 지역별 사고 패턴 분석과 예측 실험.
- **Generative AI Advertisement Prototype** — 생성형 이미지, 객체 탐지, 텍스트 배치 영역 탐색을 결합한 광고 제작 실험.

</details>

<sub>기업 협력·대회·연구 프로젝트의 원자료와 비공개 코드는 공개하지 않습니다. 공개 소개는 문제 정의, 기술적 접근, 개인 기여와 검증 관점에 한정합니다.</sub>
