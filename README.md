<div align="center">

<img src="assets/portfolio-banner.svg" alt="Haetae — Project Portfolio. 해커톤에서 직접 쓰는 도구까지, 문제를 해결하는 프로젝트." width="100%" />

# Project Portfolio

**필요한 도구를 만들고, 구현 과정과 설계 이유를 기록합니다.**

[GitHub](https://github.com/haetae8554) · [대표 프로젝트](#featured) · [프로젝트 추가하기](CONTRIBUTING.md)

</div>

해커톤 팀장으로 참여한 **복지나침반**을 중심으로 개인 프로젝트와 팀 프로젝트를 모았습니다. 각 프로젝트의 소스와 개발 이력은 원래 저장소에서 관리하고, 이곳에서는 프로젝트별 문제와 접근 방법을 소개합니다.

<a id="featured"></a>

## 대표 프로젝트

### 01 · 복지나침반 — 필요한 복지를 찾고 신청을 준비하는 길잡이

**2026 광운대학교 KW 해커톤 · 팀장 참여 · 본선 진출**

공공 복지 공고를 수집·정리하고, 사용자 조건에 따른 탐색부터 신청 준비와 지속 안내까지 연결하는 팀 프로젝트입니다. 현재 본선 점수 집계 중이며 수상 결과는 발표 전입니다.

`Python` `FastAPI` `SQLAlchemy` `MySQL` `React` `TypeScript` `React Native` `Codex CLI`

- **본인 역할:** 기획·팀 운영, 백엔드 개발과 일부 DB 스키마 작업, Codex CLI 연동
- **프론트엔드 작업:** 디자인 레퍼런스를 찾고 Codex에 작업을 지시하는 방식으로 참여
- **현재 기술 과제:** 자연어 요청 해석이 충분하지 않아 `jev` 활용을 고민 중. 시험 이후 검토할 계획이며 아직 구현 성과로 제시하지 않음

[프로젝트 상세 →](projects/bokji-compass.md) · [팀 소스 코드](https://github.com/2026-KW-HACKATHON/15_bokji-compass) · [README에 안내된 웹 서비스](https://bokji.commitnaru.com/)

### 02 · 모아 — 내 PC에서 사용하는 투자 데스크

**보유 종목 조회와 소수점 분할 주문을 토스 화면 옆에서.**

총금액 또는 총수량으로 주문을 계획하고 약 $9 단위로 나누어 전송하는 도구입니다. 재사용 가능한 Python 주문 모듈, 로컬 웹 UI, Chrome 사이드 패널로 구성했습니다.

`Python` `JavaScript` `SQLite` `Chrome Manifest V3` `Windows Native Messaging`

- **사용 흐름:** 내 투자 조회 → 분할 계획 확인 → 주문 실행·기록 확인
- **설계 포인트:** UI와 주문 모듈 분리, Windows 자격 증명 저장, 결과 불명 주문의 자동 재전송 차단
- **현재 단계:** 개인 프로젝트 · 개발 중 · 확장 웹 스토어 미등록

[프로젝트 상세 →](projects/moa-invest.md) · [소스 코드](https://github.com/haetae8554/moa-invest) · [자동 검사](https://github.com/haetae8554/moa-invest/actions/workflows/ci.yml)

### 03 · AI Closet Stylist — 옷장과 날씨를 연결하는 코디 추천

**등록한 옷과 날씨 정보를 바탕으로 AI 코디를 제안하는 팀 프로젝트.**

React 화면과 Express API를 연결하고, 옷장·날씨 정보를 Gemini에 전달하는 추천 흐름을 구현했습니다. 프로젝트 README에 기재된 담당 영역은 AI API 연동, 프롬프트 구성, JSON 응답 파싱입니다.

`React` `JavaScript` `Node.js` `Express` `Gemini API`

- **사용 흐름:** 옷 등록 → 날씨·옷장 정보 반영 → 코디 추천 결과 확인
- **담당 영역:** AI 연동. 프론트엔드·백엔드는 팀원 역할과 구분해서 소개합니다.
- **현재 단계:** 팀 프로젝트 · 공개 소스 기준 소개 · 실행 데모 검증 전

[프로젝트 상세 →](projects/ai-closet-stylist.md) · [소스 코드](https://github.com/haetae8554/AI-Closet-Stylist)

## 읽는 순서

1. **기획·팀 운영과 AI 도구를 활용한 개발**은 복지나침반의 역할·구조·현재 기술 과제를 확인하세요.
2. **제품 구성과 오류 처리**는 모아의 구조·주문 상태 설계를 확인하세요.
3. **AI API 연동**은 AI Closet Stylist의 담당 영역과 소스를 확인하세요.

## 기록 원칙

- 구현된 기능과 향후 계획을 구분합니다.
- 팀 프로젝트에서는 개인 담당 영역을 명시합니다.
- 성능 수치·테스트 결과는 확인한 버전과 근거를 함께 기록합니다.
- 데모 화면에는 가상 데이터를 사용합니다.

새 프로젝트는 [공통 템플릿](templates/project.md)으로 추가합니다. [선정 기준과 보완할 내용](docs/curation.md)도 함께 관리합니다.
