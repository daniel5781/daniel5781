# 산업연관분석과 산업 네트워크

**Economic Data Analysis · Network Science · Streamlit**

[개인 작업 저장소](https://github.com/daniel5781/khu-subapp) · [원본 팀 저장소](https://github.com/conquer-bok/khu-subapp)

## 문제와 접근

산업연관표에서 산업 간 상호의존성과 수요 변화의 파급효과를 살펴보는 분석 도구입니다.
Leontief 모형과 네트워크 분석을 연결하고, 국가·분류체계가 다른 자료를 다루는 구조를 개선했습니다.

## 코드로 확인되는 개인 기여

| 기여 | 근거 |
| --- | --- |
| Leontief 급수 기반 네트워크 구성 | [b3cea16](https://github.com/daniel5781/khu-subapp/commit/b3cea1690d8621b363185f419390727fa3f967ae) |
| BEA 모드와 데이터 수집 경로 연계 | [d0fb471](https://github.com/daniel5781/khu-subapp/commit/d0fb47186ef5712e766545ae6ba7e68ed4711132) |
| BEA Detail 자료 처리 확장 | [cbc7c5b](https://github.com/daniel5781/khu-subapp/commit/cbc7c5bd8651c5e01d941238301611589dabc751) |
| 산업 분류 계층 처리 | [d29c286](https://github.com/daniel5781/khu-subapp/commit/d29c2868a4ffe0965299ecb1d4c34510df2c97b6) |
| 분석 라이브러리 모듈 분리 | [5bdd59f](https://github.com/daniel5781/khu-subapp/commit/5bdd59f838855c06b6811d9447c68483a7085198) |
| Supply → Use 처리 개선 | [3f76e40](https://github.com/daniel5781/khu-subapp/commit/3f76e40cf8e82d6bb91aa5eeb7271d63d4219d70) |

## 설계 관점

- 경제적 의미를 가진 행렬 연산과 네트워크 시각화를 연결합니다.
- 분류·집계 수준의 차이가 분석 결과에 미치는 영향을 확인합니다.
- 화면 코드와 분석 로직을 분리해 데이터 소스 확장과 검증을 쉽게 합니다.

위 링크는 공개 커밋으로 확인되는 개인 기여입니다. 팀 프로젝트의 나머지 구현은 원본 저장소의 이력과 출처를 따릅니다.

[← 프로필로 돌아가기](../README.md)
