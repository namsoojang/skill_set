# 🛠️ Antigravity AI Agent Skillset List

이 문서는 Antigravity AI 에이전트가 프로젝트를 수행할 때 활용할 수 있는 스킬셋(Skillset) 목록을 정리한 문서입니다. 프로젝트 진행 시 필요한 스킬이 있다면 이 문서를 참고하여 에이전트에게 지시하거나 적절한 스킬을 호출하도록 유도할 수 있습니다.

---

## 📂 목차
1. [마이온컴퍼니 전용 스킬 (MyOwn Company Exclusive)](#1-마이온컴퍼니-전용-스킬-myown-company-exclusive)
2. [문서 작성 및 생산성 (Office/Media)](#2-문서-작성-및-생산성-officemedia)
3. [디자인 및 미디어 생성 (Design/AI Canvas)](#3-디자인-및-미디어-생성-designai-canvas)
4. [개발 프로세스 & QA (Development & Quality Assurance)](#4-개발-프로세스--qa-development--quality-assurance)
5. [마케팅 & 기획 전략 (Marketing & Strategy - 외부 공개 스킬)](#5-마케팅--기획-전략-marketing--strategy---외부-공개-스킬)
6. [한국어 특화 및 글쓰기 교정 스킬 (Korean-Specific Skills - 글로벌 적용)](#6-한국어-특화-및-글쓰기-교정-스킬-korean-specific-skills---글로벌-적용)

---

## 1. 마이온컴퍼니 전용 스킬 (MyOwn Company Exclusive)

마이온컴퍼니의 사업적 특성(공모전 추천 등) 및 자체 개발 가이드라인을 준수하기 위한 전용 스킬셋입니다.

| 스킬명 | 설명 | 주요 사용 목적 |
| :--- | :--- | :--- |
| **`myown-bidding-recommender`** | 마이온컴퍼니의 사업 역량(청년, 취업, 일경험, 교육 등)에 맞춰 통합 수집된 입찰/공모 공고를 분석하고 알짜 공고를 추천합니다. | 공고 추천 및 적합성 분석 |
| **`antigravity-dev-guidelines`** | Antigravity 시스템의 프론트엔드 UI/UX, 백엔드 데이터 처리, 에러 핸들링 및 LLM 코딩 행동 지침 가이드라인을 제공합니다. | 개발 표준 준수 (특히 `02_EGO_ver5_ANALYSIS` 작업 시 필수) |

---

## 2. 문서 작성 및 생산성 (Office/Media - Anthropic 공식 스킬)

다양한 형태의 문서를 추출, 분석하고 정형화된 오피스 파일 형식으로 출력 및 편집하는 스킬입니다. 대부분 Anthropic 공식 저장소([anthropics/skills](https://github.com/anthropics/skills))에서 제공됩니다.

| 스킬명 | 설명 / 출처 | 주요 사용 목적 |
| :--- | :--- | :--- |
| **`xlsx`** | Excel 스프레드시트 생성, 데이터 분석, 수식 설정, 서식 적용 및 시각화 지원.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/xlsx) | 대용량 데이터 정렬, 엑셀 보고서 자동 생성 |
| **`docx`** | Word 문서(.docx)의 내용 작성, 편집, 코멘트 추가, 변경 내용 추적 및 텍스트 추출.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/docx) | 기획서/제안서 초안 작성 및 문서 가공 |
| **`pptx`** | PowerPoint 프레젠테이션 슬라이드 생성, 편집, 레이아웃 및 텍스트 관리.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/pptx) | 발표 자료 및 사업 제안 요약 프레젠테이션 제작 |
| **`pdf`** | PDF 파일에서 텍스트 및 표 추출, PDF 폼 작성, 페이지 분할 및 병합.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/pdf) | 기존 PDF 자료 분석 및 요약 |
| **`youtube-summarizer`** | YouTube 동영상 링크로부터 자막(Transcript)을 추출하고 요약을 생성합니다.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/youtube-summarizer) | 영상 콘텐츠 분석 및 자료 조사 |
| **`audio-transcriber`** | 음성 녹음본(.wav 등)을 텍스트로 전사하고 전문적인 마크다운 요약 문서를 생성합니다.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/audio-transcriber) | 회의록 작성 및 오디오 인터뷰 요약 |
| **`beautiful-prose`** | 세련되고 군더더기 없는 영문 산문(Prose)을 작성하도록 지원합니다.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/beautiful-prose) | 글로벌 문서 작성 및 전문 영문 다듬기 |

---

## 3. 디자인 및 미디어 생성 (Design/AI Canvas)

다양한 생성형 AI 도구와 디자인 룰을 기반으로 시각 자산(Asset)이나 목업을 만드는 스킬입니다.

| 스킬명 | 설명 / 출처 | 주요 사용 목적 |
| :--- | :--- | :--- |
| **`canvas-design`** | 포스터, 카드뉴스, 보고서 커버 등 비주얼 아트를 PDF/PNG 형식으로 자체 디자인 및 생성합니다.<br>🔗 [GitHub Source](https://github.com/anthropics/skills/tree/main/skills/canvas-design) | 마케팅 리소스 및 보고서 비주얼 제작 |
| **`fal-generate`** | fal.ai API를 이용하여 최신 모델 기반의 이미지 및 비디오를 생성합니다. | 시각 자산 및 AI 프로토타입 비디오 제작 |
| **`fal-image-edit`** | 스타일 트랜스퍼, 객체 제거 등 AI 기반 이미지 편집을 수행합니다. | 이미지 보정 및 합성 |
| **`fal-upscale`** | 저해상도 이미지 및 비디오를 고해상도로 개선하고 디테일을 강화합니다. | 미디어 품질 향상 |
| **`imagen`** | Google Imagen 모델을 통해 고품질의 이미지를 생성하고 편집합니다. | UI/UX 컨셉 일러스트 및 에셋 생성 |
| **`logo-generator`** | 기하학적 형태(도트 매트릭스, 라인 시스템 등)의 6+가지 SVG 로고 디자인 변형과 12가지 배경 목업 쇼케이스 이미지를 자동으로 생성합니다.<br>🔗 [GitHub Source](https://github.com/op7418/logo-generator-skill)<br>💻 `npx skills add https://github.com/op7418/logo-generator-skill.git` | 브랜드 로고 디자인 및 목업 쇼케이스 제작 |

---

## 4. 개발 프로세스 & QA (Development & Quality Assurance - Anthropic 공식 스킬)

프로젝트 기획 단계부터 설계(Architecture), 구현(TDD), 품질 검증(Review), 디버깅 및 버전 관리(Git)까지 전체 개발 라이프사이클을 지원하는 개발 특화 스킬입니다. 대부분 Anthropic 공식 저장소([anthropics/skills](https://github.com/anthropics/skills))에서 제공됩니다.

### 4.1. 기획 및 아키텍처 (Planning & Architecture)
* **`writing-plans` / `concise-planning`**: 상세 태스크 구성, 의존성 식별 및 원자 단위의 체크리스트 작성. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/writing-plans))
* **`architecture`**: 시스템 설계 의사결정(ADR) 작성, 트레이드오프 분석 및 구조 설계 지원. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/architecture))

### 4.2. 구현 및 개발 방법론 (Implementation & TDD)
* **`test-driven-development` / `tdd-workflow`**: TDD(테스트 주도 개발) 워크플로우 적용. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/test-driven-development))
* **`tdd-workflows-tdd-red` / `tdd-workflows-tdd-green` / `tdd-workflows-tdd-refactor` / `tdd-workflows-tdd-cycle`**: Red-Green-Refactor 단계를 세분화하여 테스트 코드 및 실제 코드 구현.
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
* **`workflow-skill-creator`**: 수행 완료된 복잡한 워크플로우를 분석하여 향후 재사용 가능한 새로운 에이전트 스킬로 빌드. (🔗 [Source](https://github.com/anthropics/skills/tree/main/skills/workflow-skill-creator))

---

## 5. 마케팅 & 기획 전략 (Marketing & Strategy - 외부 공개 스킬)

외부 오픈소스 저장소에서 제공되는 비즈니스 홍보, 신규 서비스 기획, 랜딩페이지 제작 및 고객 획득을 위한 마케팅 특화 스킬셋입니다.

| 스킬명 | 설명 / 설치 경로 | 주요 사용 목적 |
| :--- | :--- | :--- |
| **`marketing/landing`** | **설명**: GSAP 3D 애니메이션 및 스크롤 연출 효과가 가미된 단일 HTML 프리미엄 랜딩 페이지를 알고리즘 기반으로 생성합니다.<br>🔗 [GitHub Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing/landing)<br>💻 `npx ai-agent-skills install alirezarezvani/claude-skills/marketing/landing` | 신규 교육/일경험 프로그램 원페이지 홍보 페이지 제작 |
| **`content-creator`** | **설명**: 텍스트의 가독성 및 톤앤매너를 분석하는 Brand Voice Analyzer와 검색 최적화를 돕는 SEO Optimizer가 포함되어 있습니다.<br>🔗 [GitHub Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/content-creator)<br>💻 `npx ai-agent-skills install alirezarezvani/claude-skills/marketing-skill/content-creator` | 블로그 포스트, 뉴스레터, 소셜 미디어 게시글 작성 및 최적화 |
| **`marketing-demand-acquisition`** | **설명**: LinkedIn, Google, Meta 광고 가이드 및 blended CAC(고객 획득 비용) 계산 프레임워크를 제공합니다.<br>🔗 [GitHub Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/marketing-demand-acquisition)<br>💻 `npx ai-agent-skills install alirezarezvani/claude-skills/marketing-skill/marketing-demand-acquisition` | 유무료 마케팅 채널 설계 및 효율성 산정 |
| **`marketing-strategy-pmm`** | **설명**: 핵심 고객(ICP) 정의, GTM 포지셔닝(April Dunford 방법론), 90일 신규 서비스 론칭 캠페인 기획 및 경쟁 분석 배틀카드를 지원합니다.<br>🔗 [GitHub Source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/marketing-strategy-pmm)<br>💻 `npx ai-agent-skills install alirezarezvani/claude-skills/marketing-skill/marketing-strategy-pmm` | 신규 서비스 론칭 및 마켓 포지셔닝 기획 |

---

## 6. 한국어 특화 및 글쓰기 교정 스킬 (Korean-Specific Skills - 글로벌 적용)

AI 에이전트 환경에서 한국어 텍스트 작성을 자연스럽게 다듬고, 맞춤법 및 문법을 체계적으로 점검할 수 있도록 돕는 한국어 특화 스킬셋입니다. 이 스킬은 로컬 프로젝트뿐만 아니라 사용자 전역(Global) 범위에 설치하여 어디서나 사용할 수 있습니다.

* 🔗 **GitHub 저장소**: [DaleSeo/korean-skills](https://github.com/DaleSeo/korean-skills)
* 💻 **글로벌 설치 명령어 (전역 적용)**:
  ```bash
  # 사용자 전역 범위로 설치 (모든 경로에서 에이전트가 바로 사용 가능)
  gh skill install daleseo/korean-skills --agent claude-code --scope user
  ```
* 🔌 **Claude Code 플러그인 연동 설치**:
  ```bash
  claude /plugin marketplace add daleseo/korean-skills
  claude /plugin install korean-skills@korean-skills
  ```

### 📦 포함된 스킬 상세

| 스킬명 | 호출 명령어 | 주요 설명 및 기능 |
| :--- | :--- | :--- |
| **`humanizer`** | `/korean-skills:humanizer` | AI가 생성한 어색한 한국어 번역투나 부자연스러운 문장 구조를 자연스러운 인간의 구어/문어체로 교정합니다. (40여 가지 어휘 및 문장구조 감지 패턴 제공) |
| **`grammar-checker`** | `/korean-skills:grammar-checker` | 한국어 문법, 맞춤법, 띄어쓰기 및 구두점 오류를 자동으로 검사하고 수정안을 제시합니다. |
| **`style-guide`** | `/korean-skills:style-guide` | 문서 내 격식(존댓말, 반말 등)과 톤앤매너가 일정하게 유지되고 있는지 스타일 일관성을 평가합니다. |


