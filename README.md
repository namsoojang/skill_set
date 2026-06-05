# 🛠️ Antigravity AI Agent Skillset List

이 문서는 Antigravity AI 에이전트가 프로젝트를 수행할 때 활용할 수 있는 전체 스킬셋(Skillset) 목록을 정리한 문서입니다. 프로젝트 진행 시 필요한 스킬이 있다면 이 문서를 참고하여 에이전트에게 지시하거나 적절한 스킬을 호출하도록 유도할 수 있습니다.

---

## 📂 목차
1. [마이온컴퍼니 전용 스킬 (MyOwn Company Exclusive)](#1-마이온컴퍼니-전용-스킬-myown-company-exclusive)
2. [문서 작성 및 생산성 (Office/Media)](#2-문서-작성-및-생산성-officemedia)
3. [디자인 및 미디어 생성 (Design/AI Canvas)](#3-디자인-및-미디어-생성-designai-canvas)
4. [개발 프로세스 & QA (Development & Quality Assurance)](#4-개발-프로세스--qa-development--quality-assurance)
5. [마케팅 & 기획 전략 (Marketing & Strategy - 에이전트 탑재형 스킬)](#5-마케팅--기획-전략-marketing--strategy---에이전트-탑재형-스킬)
6. [한국어 특화 및 글쓰기 교정 스킬 (Korean-Specific Skills - 글로벌 적용)](#6-한국어-특화-및-글쓰기-교정-스킬-korean-specific-skills---글로벌-적용)

---

## 1. 마이온컴퍼니 전용 스킬 (MyOwn Company Exclusive)

마이온컴퍼니의 사업적 특성(공모전 추천 등) 및 자체 개발 가이드라인을 준수하기 위한 전용 스킬셋입니다.

| 스킬명 | 설명 | 주요 사용 목적 |
| :--- | :--- | :--- |
| **`myown-bidding-recommender`** | 마이온컴퍼니의 사업 역량(청년, 취업, 일경험, 교육 등)에 맞춰 통합 수집된 입찰/공모 공고를 분석하고 알짜 공고를 추천합니다. | 공고 추천 및 적합성 분석 |
| **`antigravity-dev-guidelines`** | Antigravity 시스템의 프론트엔드 UI/UX, 백엔드 데이터 처리, 에러 핸들링 및 LLM 코딩 행동 지침 가이드라인을 제공합니다. | 개발 표준 준수 (특히 `02_EGO_ver5_ANALYSIS` 작업 시 필수) |

---

## 2. 문서 작성 및 생산성 (Office/Media)

다양한 형태의 문서를 추출, 분석하고 정형화된 오피스 파일 형식으로 출력 및 편집하는 스킬입니다.

| 스킬명 | 설명 / 출처 | 주요 사용 목적 |
| :--- | :--- | :--- |
| **`xlsx`** | Excel 스프레드시트 생성, 데이터 분석, 수식 설정, 서식 적용 및 시각화 지원.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/xlsx) | 대용량 데이터 정렬, 엑셀 보고서 자동 생성 |
| **`docx`** | Word 문서(.docx)의 내용 작성, 편집, 코멘트 추가, 변경 내용 추적 및 텍스트 추출.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/docx) | 기획서/제안서 초안 작성 및 문서 가공 |
| **`pptx`** | PowerPoint 프레젠테이션 슬라이드 생성, 편집, 레이아웃 및 텍스트 관리.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/pptx) | 발표 자료 및 사업 제안 요약 프레젠테이션 제작 |
| **`pdf`** | PDF 파일에서 텍스트 및 표 추출, PDF 폼 작성, 페이지 분할 및 병합.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/pdf) | 기존 PDF 자료 분석 및 요약 |
| **`doc-coauthoring`** | 기획서, 제안서, 기술 명세 등 공동 문서 작성을 위한 협업 워크플로우를 제공합니다.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/doc-coauthoring) | 정형화된 대형 문서의 일관성 및 정밀성 개선 |
| **`internal-comms`** | 보고서, FAQ, 사내 뉴스레터, 공지사항, 사건(incident) 보고 등 목적별 문서 템플릿을 제공합니다.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/internal-comms) | 표준화된 사내 커뮤니케이션용 문서 신속 작성 |
| **`youtube-summarizer`** | YouTube 동영상 링크로부터 자막(Transcript)을 추출하고 요약을 생성합니다.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/youtube-summarizer) | 영상 콘텐츠 분석 및 자료 조사 |
| **`audio-transcriber`** | 음성 녹음본(.wav 등)을 텍스트로 전사하고 전문적인 마크다운 요약 문서를 생성합니다.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/audio-transcriber) | 회의록 작성 및 오디오 인터뷰 요약 |
| **`beautiful-prose`** | 세련되고 군더더기 없는 전문적인 영문 산문(Prose)을 작성하도록 지원합니다.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/beautiful-prose) | 글로벌 문서 작성 및 전문 영문 다듬기 |

---

## 3. 디자인 및 미디어 생성 (Design/AI Canvas)

다양한 생성형 AI 도구와 디자인 룰을 기반으로 시각 자산(Asset)이나 목업을 만드는 스킬입니다.

| 스킬명 | 설명 / 출처 | 주요 사용 목적 |
| :--- | :--- | :--- |
| **`canvas-design`** | 포스터, 카드뉴스, 보고서 커버 등 비주얼 아트를 PDF/PNG 형식으로 자체 디자인 및 생성합니다.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/canvas-design) | 마케팅 리소스 및 보고서 비주얼 제작 |
| **`logo-generator`** | 기하학적 형태(도트 매트릭스, 라인 시스템 등)의 6+가지 SVG 로고 디자인 변형과 12가지 배경 목업 쇼케이스 이미지를 자동으로 생성합니다.<br>🔗 [GitHub Source](https://github.com/op7418/logo-generator-skill) | 브랜드 로고 디자인 및 목업 쇼케이스 제작 |
| **`algorithmic-art`** | p5.js와 시드 무작위성을 기반으로 한 제너러티브 아트/알고리즘 예술을 생성합니다.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/algorithmic-art) | 인터랙션 기반의 독창적이고 생성적인 비주얼 아트 제작 |
| **`slack-gif-creator`** | Slack 메신저 환경에 최적화된 크기 및 프레임 속도의 애니메이션 GIF를 디자인 및 렌더링합니다.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/slack-gif-creator) | 사내 소통 및 재미 요소를 더한 Slack 전용 GIF 에셋 제작 |
| **`theme-factory`** | 슬라이드, 문서, 보고서 등에 10여 가지 사전 정의된 색상 및 폰트 테마를 적용해 일관된 디자인을 부여합니다.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/theme-factory) | 문서 레이아웃 및 프레젠테이션 디자인 표준화 |
| **`fal-generate`** | fal.ai API를 이용하여 최신 모델 기반의 고품질 이미지 및 비디오를 생성합니다. | 시각 자산 및 AI 프로토타입 비디오 제작 |
| **`fal-image-edit`** | 스타일 트랜스퍼, 객체 제거, 아웃페인팅 등 AI 기반 이미지 편집을 수행합니다. | 이미지 보정 및 합성 |
| **`fal-upscale`** | 저해상도 이미지 및 비디오를 고해상도로 개선하고 디테일을 강화합니다. | 미디어 품질 향상 |
| **`imagen`** | Google Imagen 모델을 통해 고품질의 이미지를 생성하고 편집합니다. | UI/UX 컨셉 일러스트 및 에셋 생성 |

---

## 4. 개발 프로세스 & QA (Development & Quality Assurance)

프로젝트 설계부터 TDD 기반 구현, 품질 검증(Review), 버전 제어, 디버깅 및 연동 개발까지 지원하는 개발 특화 스킬입니다.

### 4.1. 기획 및 아키텍처 (Planning & Architecture)
* **`writing-plans` / `concise-planning`**: 상세 태스크 구성, 의존성 식별 및 원자 단위의 체크리스트 작성. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/writing-plans))
* **`architecture`**: 시스템 설계 의사결정(ADR) 작성, 트레이드오프 분석 및 구조 설계 지원. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/architecture))

### 4.2. 구현 및 개발 방법론 (Implementation & TDD)
* **`test-driven-development` / `tdd-workflow`**: Red-Green-Refactor 단계를 세분화하여 테스트 코드 및 실제 코드 구현. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/test-driven-development))
* **`executing-plans`**: 수립된 계획의 구현 세션을 분할하고 단계별로 실행 및 검증. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/executing-plans))
* **`subagent-driven-development` / `parallel-agents`**: 하위 에이전트를 생성하거나 멀티 에이전트 협업 체계를 만들어 병렬 태스크 실행. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/subagent-driven-development))

### 4.3. 코드 검증 및 리뷰 (Review & Git Workflow)
* **`code-review` / `code-reviewer`**: 보안 취약점, 성능 병목, 코드 스타일 분석 및 개선 제안. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/code-review))
* **`receiving-code-review`**: 코드 리뷰 피드백 수렴 시 검증을 거쳐 안전하게 반영. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/receiving-code-review))
* **`commit` / `create-pr`**: Sentry 컨벤션과 일치하는 커밋 메시지 및 PR 설명 작성. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/commit))
* **`git-pr-workflows-git-workflow` / `git-pushing`**: 원격 저장소 푸시 및 PR 발행 워크플로우 자동화. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/git-pr-workflows-git-workflow))

### 4.4. 디버깅 및 환경 관리 (Debugging & Tools)
* **`debugger` / `debugging-strategies` / `debugging-toolkit-smart-debug` / `error-diagnostics-smart-debug`**: 에러 로그 및 시스템 리크, 예상치 못한 동작 분석 및 패치. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/debugger))
* **`agent-manager-skill`**: 로컬 CLI 에이전트들을 tmux 세션으로 실행, 모니터링 및 스케줄링.
* **`dx-optimizer`**: 개발자 경험 향상을 위한 툴링 및 워크플로우 설정 개선. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/dx-optimizer))
* **`screenshots`**: Playwright를 이용해 UI 검증용 또는 랜딩 페이지 홍보용 스크린샷 자동 촬영. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/screenshots))
* **`uv`**: 고속 Python 패키지 인스톨러 uv 설치 유무 및 환경 경로 점검.

### 4.5. 에이전트 및 연동 개발 (Agent & Integration Dev)
* **`claude-api`**: Claude API / Anthropic SDK 연동, 프롬프트 캐싱 및 마이그레이션 지원. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/claude-api))
* **`mcp-builder`**: Model Context Protocol(MCP) 서버 개발 지원 (FastMCP 및 Node SDK). (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/mcp-builder))
* **`skill-creator`**: 새로운 에이전트 스킬 생성, 테스트/평가(eval) 및 성능 튜닝. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/skill-creator))
* **`web-artifacts-builder`**: React, Tailwind, shadcn/ui 기반의 멀티 컴포넌트 웹 아티팩트 빌드 지원. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder))
* **`webapp-testing`**: Playwright를 이용한 로컬 웹 애플리케이션 기능성 테스트 및 브라우저 로그 검증. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/webapp-testing))
* **`android-cli`**: 안드로이드 프로젝트 빌드, 기기 배포, SDK 및 실행 환경 진단.
* **`workflow-skill-creator`**: 수행 완료된 복잡한 워크플로우를 분석하여 향후 재사용 가능한 새로운 에이전트 스킬로 빌드. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/workflow-skill-creator))

---

## 5. 마케팅 & 기획 전략 (Marketing & Strategy - 에이전트 탑재형 스킬)

비즈니스 성장, 신규 서비스 기획, 검색 최적화, 획득 및 전환율 최적화를 아우르는 마케팅 오케스트레이션 스킬셋입니다.

### 5.1. 공통 인프라 및 설정 (Infrastructure & Ops)
* **`marketing-ops`**: 마케팅 스킬 에코시스템의 중앙 라우터이자 통합 코디네이터. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/marketing-ops))
* **`marketing-skills`**: 42가지 마케팅 스킬 및 플러그인을 연결하고 관리하는 백본 시스템. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/marketing-skills))
* **`marketing-context`**: 브랜드 보이스, 타겟 오디언스(ICP), 브랜드 스타일 등을 정의하고 참조하는 컨텍스트 관리. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/marketing-context))
* **`prompt-engineer-toolkit`**: 광고, 이메일, SNS 등 마케팅 목적별 프롬프트 템플릿 개발 및 최적화 워크플로우 구성. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/prompt-engineer-toolkit))

### 5.2. 비즈니스 및 제품 마케팅 전략 (Strategy & PMM)
* **`marketing-strategy-pmm`**: ICP 정의, April Dunford 포지셔닝 프레임워크 수립, 90일 GTM 출시 캠페인 기획 및 경쟁 분석 배틀카드 제작. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/marketing-strategy-pmm))
* **`launch-strategy`**: Product Hunt 론칭, 베타 테스트, 신규 기능 릴리즈 및 모멘텀 구축 전략 설계. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/launch-strategy))
* **`pricing-strategy`**: SaaS 요금제 티어 설계, 가치 메트릭 도출, 요금 인상 전략 및 가격 페이지 전환 최적화. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/pricing-strategy))
* **`free-tool-strategy`**: 리드 획득 및 SEO 트래픽 생성을 위한 무료 도구(계산기, 생성기, 평가 Grader) 기획 및 출시 전략. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/free-tool-strategy))
* **`referral-program`**: 리워드 인센티브 설계, 가입 루프 형성 및 제휴사(Affiliate) 관리 프로그램 기획. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/referral-program))
* **`marketing-psychology`**: 70가지 이상의 행동경제학/심리학 모델(인지적 편향, 사회적 증거 등)을 마케팅에 접목. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/marketing-psychology))
* **`marketing-ideas`**: 성장을 촉진하기 위한 139가지 검증된 카테고리별 마케팅 아이디어 모음 및 적용 방안 추천. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/marketing-ideas))

### 5.3. 콘텐츠 및 검색 최적화 (Content & SEO/AEO)
* **`content-production`**: 주제 선정부터 자료 수집, 초안 작성 및 SEO 반영까지 포함하는 콘텐츠 집필 파이프라인. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/content-production))
* **`content-strategy`**: 블로그 전략 수립, 토픽 클러스터링 구성 및 콘텐츠 기획 캘린더 생성. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/content-strategy))
* **`content-humanizer`**: AI 생성 텍스트 특유의 어투를 배제하고 자연스럽고 살아있는 문체로 변경(휴머니어라이징). (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/content-humanizer))
* **`copy-editing`**: 완성된 마케팅 카피의 명확성, 가독성, 어조 및 일관성을 다각도로 검토하고 윤문. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/copy-editing))
* **`seo-audit`**: 웹사이트의 기술적 SEO 문제, 온페이지(On-page) 메타 태그, 모바일 친화성 등 종합 진단. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/seo-audit))
* **`programmatic-seo`**: 대량의 데이터 및 템플릿을 조합해 구조적 키워드를 타겟팅하는 대규모 검색 최적화 페이지 설계. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/programmatic-seo))
* **`schema-markup`**: 검색 엔진이 콘텐츠를 이해하고 리치 스니핏을 표시하도록 JSON-LD 구조화 데이터 설계 및 검증. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/schema-markup))
* **`site-architecture`**: 사이트 내부 링크 구조, URL 구조 최적화, 사일로(Silo) 구조 등 정보 설계 분석 및 구축. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/site-architecture))
* **`aeo` (Answer Engine Optimization)**: ChatGPT, Perplexity, Gemini 등 대화형 AI 검색의 답변에 신뢰성 있는 소스로 인용(Citation)될 수 있도록 콘텐츠 최적화. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/aeo))
* **`ai-seo`**: 생성형 검색 엔진의 AI Overviews 및 AI 복합 검색 노출(GEO)을 타겟으로 한 콘텐츠 전략 수립. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/ai-seo))

### 5.4. 획득 채널 및 광고 운영 (Acquisition & Channels)
* **`marketing-demand-acquisition`**: 유료 채널과 무료 획득 채널을 믹스하여 Blended CAC(고객 획득 비용)를 제어하고 파이프라인 형성 설계. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/marketing-demand-acquisition))
* **`paid-ads`**: Google, Meta, LinkedIn 광고 플랫폼 타겟팅, 입찰 전략 및 어트리뷰션 설계. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/paid-ads))
* **`ad-creative`**: paid 광고에 사용할 문장 패턴, RSA(반응형 검색 광고) 헤드라인, 광고 문구 배리에이션 생성 및 검증. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/ad-creative))
* **`social-content`**: LinkedIn, Twitter 등 플랫폼별 성격에 맞는 바이럴 스레드 및 마이크로 카피 작성. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/social-content))
* **`social-media-manager`**: 브랜드 소셜 미디어 채널의 육성 방향 설정, 콘텐츠 캘린더 및 커뮤니티 인게이지먼트 관리. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/social-media-manager))
* **`x-twitter-growth`**: X(트위터) 플랫폼의 알고리즘에 따른 스레드 작성 기획, 프로필 설계 및 팔로워 성장 전략 수립. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/x-twitter-growth))
* **`cold-email`**: B2B 잠재 고객에게 보내는 무단/아웃바운드 콜드 이메일 시퀀스 기획 및 발신 어조 다듬기. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/cold-email))

### 5.5. 전환율 최적화 및 유저 여정 (CRO & Funnel)
* **`landing`**: GSAP 스크롤 효과와 3D 레이아웃을 포함한 인터랙티브 프리미엄 HTML 랜딩 페이지 자동 생성. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-landing/skills/landing))
* **`copywriting`**: 홈페이지, 요금제, 소개 페이지 등의 핵심 전환 문구 및 CTA 버튼 메시지 라이팅. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/copywriting))
* **`page-cro`**: 웹사이트 주요 상세 페이지의 이탈 요소를 차단하고 유저 행동을 유도하는 전환율 최적화 진단. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/page-cro))
* **`signup-flow-cro`**: 회원가입 단계의 필드를 줄이고 마찰을 제거하여 가입 중도 탈퇴율을 개선. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/signup-flow-cro))
* **`onboarding-cro`**: 가입 직후 사용자 첫 활성화 및 가치 체감(Aha-moment)을 극대화하는 온보딩 플로우 최적화. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/onboarding-cro))
* **`form-cro`**: 리드 생성 폼, 설문 조사, 데모 요청 폼 등 가입 이외 양식의 마찰 요소를 줄여 제출율 향상. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/form-cro))
* **`popup-cro`**: 이탈 의도(Exit-intent) 감지 팝업, 슬라이드인 배너 및 상단 알림 배너 전환율 극대화. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/popup-cro))
* **`paywall-upgrade-cro`**: 인앱 페이월(요금 장벽), 가격 안내 요금 테이블 및 유료 업그레이드 모달 유도 설계 최적화. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/paywall-upgrade-cro))
* **`ab-test-setup`**: A/B 테스트 설계, 대조군/실험군 분할, 가설 검증 및 전환율 유의성 통계 분석. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/ab-test-setup))
* **`churn-prevention`**: 탈퇴 흐름 내 설문 및 해지 방지 오퍼(Save Offers) 제공, 결제 실패 시 회수 이메일(Dunning) 설계. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/churn-prevention))

### 5.6. 성과 분석 및 관리 (Analytics)
* **`analytics-tracking`**: GA4, Google Tag Manager(GTM) 이벤트 설계, 데이터 수집 누수 분석 및 매핑 감사. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/analytics-tracking))
* **`campaign-analytics`**: 멀티터치 기여 분석(Attribution), 퍼널 단계별 전환율 산정 및 마케팅 ROI 계산. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/campaign-analytics))
* **`social-media-analyzer`**: SNS 채널별 인터랙션, 도달 및 기여도를 비교 분석하고 플랫폼 효율 산출. (🔗 [Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/social-media-analyzer))

---

## 6. 한국어 특화 및 글쓰기 교정 스킬 (Korean-Specific Skills - 글로벌 적용)

AI 에이전트 환경에서 한국어 텍스트 작성을 자연스럽게 다듬고, 맞춤법 및 문법을 체계적으로 점검할 수 있도록 돕는 한국어 특화 스킬셋입니다.

* 🔗 **GitHub 저장소**: [DaleSeo/korean-skills](https://github.com/DaleSeo/korean-skills)

### 📦 포함된 스킬 상세

| 스킬명 | 호출 명령어 | 주요 설명 및 기능 |
| :--- | :--- | :--- |
| **`humanizer`** (`humanize-korean`) | `/korean-skills:humanizer` | AI가 생성한 어색한 한국어 번역투나 부자연스러운 문장 구조를 자연스러운 인간의 구어/문어체로 교정합니다. (40여 가지 어휘 및 문장구조 감지 패턴 제공) |
| **`grammar-checker`** | `/korean-skills:grammar-checker` | 한국어 문법, 맞춤법, 띄어쓰기 및 구두점 오류를 자동으로 검사하고 수정안을 제시합니다. |
| **`style-guide`** | `/korean-skills:style-guide` | 문서 내 격식(존댓말, 반말 등)과 톤앤매너가 일정하게 유지되고 있는지 스타일 일관성을 평가합니다. |
