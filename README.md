<div align="center">

<img src="assets/portfolio-banner.svg" alt="Haetae — Project Portfolio. 직접 쓰는 도구부터 팀 프로젝트와 자료구조 학습까지." width="100%" />

# Project Portfolio

**필요한 도구를 만들고, 구현 과정과 설계 이유를 기록합니다.**

[GitHub](https://github.com/haetae8554) · [대표 프로젝트](#featured) · [학습 프로젝트](#learning) · [프로젝트 추가하기](CONTRIBUTING.md)

</div>

개인 프로젝트, 팀 프로젝트, 학습 기록을 모은 포트폴리오입니다. 각 프로젝트의 소스와 개발 이력은 원래 저장소에서 관리하고, 이곳에서는 프로젝트별 문제와 접근 방법을 소개합니다.

<a id="featured"></a>

## 대표 프로젝트

### 01 · 모아 — 내 PC에서 사용하는 투자 데스크

**보유 종목 조회와 소수점 분할 주문을 토스 화면 옆에서.**

총금액 또는 총수량으로 주문을 계획하고 약 $9 단위로 나누어 전송하는 도구입니다. 재사용 가능한 Python 주문 모듈, 로컬 웹 UI, Chrome 사이드 패널로 구성했습니다.

`Python` `JavaScript` `SQLite` `Chrome Manifest V3` `Windows Native Messaging`

- **사용 흐름:** 내 투자 조회 → 분할 계획 확인 → 주문 실행·기록 확인
- **설계 포인트:** UI와 주문 모듈 분리, Windows 자격 증명 저장, 결과 불명 주문의 자동 재전송 차단
- **현재 단계:** 개인 프로젝트 · 개발 중 · 확장 웹 스토어 미등록

[프로젝트 상세 →](projects/moa-invest.md) · [소스 코드](https://github.com/haetae8554/moa-invest) · [자동 검사](https://github.com/haetae8554/moa-invest/actions/workflows/ci.yml)

### 02 · AI Closet Stylist — 옷장과 날씨를 연결하는 코디 추천

**등록한 옷과 날씨 정보를 바탕으로 AI 코디를 제안하는 팀 프로젝트.**

React 화면과 Express API를 연결하고, 옷장·날씨 정보를 Gemini에 전달하는 추천 흐름을 구현했습니다. 프로젝트 README에 기재된 담당 영역은 AI API 연동, 프롬프트 구성, JSON 응답 파싱입니다.

`React` `JavaScript` `Node.js` `Express` `Gemini API`

- **사용 흐름:** 옷 등록 → 날씨·옷장 정보 반영 → 코디 추천 결과 확인
- **담당 영역:** AI 연동. 프론트엔드·백엔드는 팀원 역할과 구분해서 소개합니다.
- **현재 단계:** 팀 프로젝트 · 공개 소스 기준 소개 · 실행 데모 검증 전

[프로젝트 상세 →](projects/ai-closet-stylist.md) · [소스 코드](https://github.com/haetae8554/AI-Closet-Stylist)

<a id="learning"></a>

## 학습 프로젝트

수업 과제의 원본에서 fork한 저장소입니다. 서비스 프로젝트와 구분하고, 제공 코드와 추가 구현의 기여 범위를 확인할 수 있도록 원본 링크를 함께 남깁니다.

| 프로젝트 | 학습 주제 | 링크 |
| :--- | :--- | :--- |
| C++ 그래프 알고리즘 | 인접 리스트·행렬, BFS·DFS, 최소 신장 트리, 최단 경로 | [소개](projects/data-structures.md#graph) · [코드](https://github.com/haetae8554/2025_Kwangwoon_DS_Project_3) |
| C++ 자료구조 기반 데이터 관리 | B+ Tree, Heap, Selection Tree | [소개](projects/data-structures.md#trees) · [코드](https://github.com/haetae8554/2025_Kwangwoon_DS_Project_2) |

## 읽는 순서

1. **제품 구성과 오류 처리**가 궁금하다면 모아의 구조·주문 상태 설계를 확인하세요.
2. **외부 AI API 연동과 팀 프로젝트**가 궁금하다면 AI Closet Stylist의 담당 영역과 소스를 확인하세요.
3. **자료구조 구현 학습**은 C++ 프로젝트에서 확인할 수 있습니다.

## 기록 원칙

- 구현된 기능과 향후 계획을 구분합니다.
- 팀 프로젝트에서는 개인 담당 영역을 명시합니다.
- 성능 수치·테스트 결과는 확인한 버전과 근거를 함께 기록합니다.
- 데모 화면에는 가상 데이터를 사용합니다.

새 프로젝트는 [공통 템플릿](templates/project.md)으로 추가합니다. [선정 기준과 보완할 내용](docs/curation.md)도 함께 관리합니다.
