<div align="center">

# 장민준 · JANG MINJUN

### 아이디어를 서비스로 만들고, 경험을 코드와 기록으로 남깁니다

명지대학교 융합소프트웨어학부 · 데이터사이언스전공

**AI 기능 개발 · LLM API 연동 및 출력 검증 · 풀스택 웹 개발**

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-18181B?style=for-the-badge&logo=readme&logoColor=white)](https://jmj-archive.ai.studio/)
[![GitHub](https://img.shields.io/badge/PROJECTS-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/peach20040909?tab=repositories)
[![Email](https://img.shields.io/badge/CONTACT-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:a01027010769@gmail.com)

</div>

---

## About Me

사용자 인터뷰에서 문제를 찾고, 웹앱과 API로 해결 방법을 구현합니다.
개인 서비스와 팀 프로젝트에서 맡은 역할, 설계 판단, 문제 해결 과정을 코드와 문서로 남깁니다.

- **AI 서비스 개발** — 한만큼의 Claude Haiku 기반 기록 분류·요약, 고리(Go:RE)의 GPT-4o mini 사진 분석, 혼밥지도의 Gemini API 연동
- **웹 개발** — 혼밥지도 개인 개발, 고리(Go:RE) 팀 메인 개발, 프로젝트 아카이브
- **서비스 기획 · 데이터** — 한만큼 사용자 인터뷰와 팀 기여도 근거 리포트 설계
- **현장조사** — 해외탐방 프로그램 선발, Mobility Field Lab 개발 및 해외 현장조사 준비
- **팀 협업** — Loadmap 프론트엔드, SetPIK 백엔드 개발 참여

## Highlights

| 🏆 해커톤 우수상 | 🏆 AI 리터러시 우수상 | 🌍 해외탐방 선발 |
| --- | --- | --- |
| 2026 명지대학교<br>**AI 창의적 아이디어 해커톤**<br>[고리(Go:RE)](https://github.com/peach20040909/GoRe) · 6인 팀 메인 개발<br>2026.11.06 | 2026 명지대학교<br>**AI 리터러시 경진대회**<br>[한만큼](https://github.com/peach20040909/hanmankeum)<br>2026.11.26 | **[Mobility Field Lab](https://github.com/peach20040909/mobility-field-lab)**<br>공유 이동수단 현장조사 웹앱 |

## Selected Projects

<table>
<tr>
<td width="50%" valign="top">

### 고리 · Go:RE
**장소와 추억을 연결하는 AI 타임캡슐**

관광명소에 사진과 편지를 남기고, GPS·사진 확인을 거쳐 재방문 시 열어 보는 서비스입니다.

**담당** 6인 팀 메인 개발 · 웹앱 및 API 연동  
**기술** Next.js 15 · TypeScript · Supabase · GPT-4o mini · NAVER Maps · model-viewer  
**성과** 2026 명지대학교 AI 창의적 아이디어 해커톤 우수상

[서비스 방문 ↗](https://go-re.vercel.app/) · [소스코드](https://github.com/peach20040909/GoRe)

</td>
<td width="50%" valign="top">

### 한만큼
**흩어진 작업 기록을 팀 기여의 근거로**

교수가 쓰는 평가 기준에 GitHub·Notion 작업 기록을 연결해 팀 프로젝트 기여 근거를 보여주는 서비스입니다. Claude Haiku로 기준 정리, 기록 분류, 근거 요약을 지원합니다.

**담당** 교수 인터뷰 설계·진행 · UX·UI 설계 및 사이트 구현 총괄 · 시연 영상·최종 결과물 제작  
**기술** Node.js · Vercel · Turso (libSQL) · Anthropic Claude Haiku API · GitHub REST API · Notion Webhook  
**AI 검증** 규칙과 AI의 분류가 다르면 ‘확인 필요’로 표시하고, 근거 기록 번호가 없는 요약 문장은 제외합니다. 교수는 원본을 확인해 최종 평가합니다.  
**성과** 2026 명지대학교 AI 리터러시 경진대회 우수상 (2026.11.26)

[서비스 방문 ↗](https://hanmankeum.vercel.app/) · [소스코드](https://github.com/peach20040909/hanmankeum)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 혼밥지도 · SoloMap
**학우 리뷰와 방문 기록으로 키우는 혼밥 지도**

명지대 인문캠 주변 식당을 혼밥 난이도 Lv.1~5로 탐색하고, 학교 메일로 인증한 학우의 리뷰와 방문 체크인으로 식당 난이도와 나의 혼밥 레벨을 갱신하는 모바일 웹 서비스입니다.

**담당** 기획 · 디자인 · 프론트엔드 · 백엔드 · 배포 전부 (개인)  
**기술** TypeScript · Express 5 · Prisma 7 · PostgreSQL(Supabase) · NAVER Maps · Gemini API · Vercel  
**구현** 학교 메일 인증 · 리뷰 CRUD·난이도 보정 · 체크인·레벨 · 식당 검색·지도·랜덤 추천  
**상태** 개발·배포 완료  
**검증 기록** 서버 테스트 27개 · 평가용 API 요청 31개 통과 · 트러블슈팅 20건 기록

[서비스 방문 ↗](https://mju-solomap.vercel.app/) · [소스코드](https://github.com/peach20040909/MJU_solomap)

</td>
<td width="50%" valign="top">

### Mobility Field Lab
**해외탐방 공유 이동수단 현장조사 플랫폼**

사진·측정 기록, A/B 독립 검수, 지도·지표와 CSV 내보내기를 구현했습니다.

**담당** 조사 웹앱 개발 · 데이터 흐름 설계  
**기술** Next.js · TypeScript · IndexedDB · Python / FastAPI  
**진행** 해외탐방 선발 완료 · 실제 해외 현장조사 준비 중. 로컬 비전 AI는 실험 단계

[조사 웹앱 ↗](https://peach20040909.github.io/mobility-field-lab/) · [소스코드](https://github.com/peach20040909/mobility-field-lab)

</td>
</tr>
</table>

### JMJ Archive

프로젝트·학습 기록을 구조화하고, 공개 포트폴리오와 JSON/Markdown 내보내기를 제공하는 개인 프로젝트입니다.

**React · TypeScript · Express · Gemini API**  
[포트폴리오 방문 ↗](https://jmj-archive.ai.studio/) · [소스코드](https://github.com/peach20040909/JMJ_Project_Archive)

## Team Experience

| 프로젝트 | 참여 내용 | 기술 |
|---|---|---|
| [Loadmap](https://github.com/6eaverr/SW-programming) | 강의 복습 후보 구간 시각화 · 프론트엔드 서브 개발 | React · TypeScript |
| [SetPIK](https://github.com/DEPthes/5th-MVP-SetPIK-Server)<br>[라이브 데모 ↗](https://5th-mvp-set-pik-web.vercel.app/) | Spotify 기반 공연 추천 · 백엔드 서브 개발 · 다국어 아티스트 매칭 문제 해결 | Java · Spring Boot |

## Skills in Context

| 영역 | 프로젝트에서 활용한 경험 |
|---|---|
| **LLM API 연동** | Claude Haiku로 협업 기록 분류·요약 구현, Gemini API를 혼밥지도와 포트폴리오에 연동 |
| **AI 출력 검증** | 한만큼에서 규칙 기반 교차 검토, 요약의 근거 인용 검사, 교수 확인 흐름을 구현 |
| **AI 개발 도구** | Codex로 학원 변형문제 생성기 개발, Claude Code를 한만큼 구현에 활용 |
| **TypeScript · JavaScript · React** | 혼밥지도, 프로젝트 아카이브, 고리, 조사 웹앱 |
| **Node.js · Express · Turso (libSQL)** | API 서버 개발, 협업 기록 수집과 저장 |
| **Java · Spring Boot** | SetPIK 팀 백엔드 개발 |
| **멀티모달 AI · Python** | GPT-4o mini 사진 분석 연동, Qwen3 멀티모달 모델 사용, 현장조사 도구에서 로컬 비전 AI 실험 |
| **Git · 외부 API** | 팀 협업, 지도·GitHub·Notion 데이터 연동 |

---

<div align="center">

프로젝트별 본인 역할과 구현 내용, 트러블슈팅은 [포트폴리오](https://jmj-archive.ai.studio/)에서 확인할 수 있습니다.

</div>
