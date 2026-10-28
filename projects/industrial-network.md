# 산업연관분석과 산업 네트워크

**Economic Data Analysis · Network Science · Streamlit**

[개인 작업 저장소](https://github.com/daniel5781/khu-subapp) · [원본 팀 저장소](https://github.com/conquer-bok/khu-subapp)

## 도구의 기능

산업연관표에서 산업 간 상호의존성과 수요 변화의 파급효과를 살펴보는 분석 도구입니다.
산업 분류를 편집한 뒤 Leontief 모형의 파급효과를 계산하고, 산업 네트워크와 중심성을 살펴볼 수 있습니다.
이 전체 도구는 팀 결과물이며, 아래에는 제가 기여한 변경 이력을 따로 정리했습니다.

## 개인 기여와 근거

| 기여 | 근거 |
| --- | --- |
| Leontief 급수 기반 네트워크 구성 | [b3cea16](https://github.com/daniel5781/khu-subapp/commit/b3cea1690d8621b363185f419390727fa3f967ae) |
| BEA 모드와 데이터 수집 경로 연계 | [d0fb471](https://github.com/daniel5781/khu-subapp/commit/d0fb47186ef5712e766545ae6ba7e68ed4711132) |
| BEA Detail 자료 처리 확장 | [cbc7c5b](https://github.com/daniel5781/khu-subapp/commit/cbc7c5bd8651c5e01d941238301611589dabc751) |
| 산업 분류 계층 처리 | [d29c286](https://github.com/daniel5781/khu-subapp/commit/d29c2868a4ffe0965299ecb1d4c34510df2c97b6) |
| 분석 라이브러리 모듈 분리 | [5bdd59f](https://github.com/daniel5781/khu-subapp/commit/5bdd59f838855c06b6811d9447c68483a7085198) |
| Supply 기반 처리에서 Use 기반 처리로 변경 | [3f76e40](https://github.com/daniel5781/khu-subapp/commit/3f76e40cf8e82d6bb91aa5eeb7271d63d4219d70) |

## 자료 처리와 코드 구성

국가별 자료 형식과 산업 분류 수준의 차이를 다루기 위해 BEA 수집·Detail 처리와 분류 계층 처리를 확장했습니다.
화면에서 사용하는 분석 로직은 라이브러리 모듈로 분리했습니다.
공개 커밋은 이러한 변경의 근거이며, 구현의 정확성이나 분석 효과를 커밋 메시지만으로 입증하는 것은 아닙니다.

## 버전과 출처

연결한 `khu-subapp`은 공개된 개인 작업 이력을 확인하는 저장소입니다.
로컬 작업본과의 최종 버전 관계는 확인이 필요하므로 최신 완성본으로 단정하지 않습니다.
팀 프로젝트의 나머지 구현은 원본 저장소의 이력과 출처를 따릅니다.

[← 프로필로 돌아가기](../README.md)
