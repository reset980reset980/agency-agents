# 🤖 The Agency - AI 에이전트 컬렉션

**손끝에서 완성된 AI 에이전시** - 프론트엔드 마법사부터 레딧 커뮤니티 닌자까지, 위트 주입기부터 현실 확인관까지. 각 에이전트는 개성, 프로세스, 검증된 산출물을 갖춘 전문가입니다.

![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)
![Make A Pull Request](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

---

## 🎯 The Agency란 무엇인가요?

Reddit 스레드에서 탄생하여 수개월의 반복을 거쳐, The Agency는 정교하게 제작된 AI 에이전트 개성 컬렉션으로 성장했습니다. 각 에이전트는:

- 🎯 **전문화됨:** 도메인에 대한 깊은 전문성 (일반적인 프롬프트 템플릿이 아님)
- 🧠 **개성 중심:** 독특한 목소리, 커뮤니케이션 스타일, 접근 방식
- 📋 **산출물 중심:** 실제 코드, 프로세스, 측정 가능한 결과물
- ✅ **프로덕션 레디:** 검증된 워크플로우와 성공 지표

**생각해보세요:** 꿈의 팀을 모으는 것과 같습니다. 단, 그들은 잠을 자지 않고, 불평하지 않으며, 항상 결과를 전달하는 AI 전문가들입니다.

---

## 🚀 빠른 시작

### 1단계 - Claude Code에 에이전트 복사

```bash
# 에이전트를 Claude Code 디렉토리에 복사
cp -r agency-agents/* ~/.claude/agents/
```

### 2단계 - 세션에서 에이전트 활성화

```bash
# "Hey Claude, activate Frontend Developer mode and help me build a React component"
# "클로드, 프론트엔드 개발자 모드를 활성화하고 React 컴포넌트 만드는 거 도와줘"
```

각 에이전트 파일은 다음을 포함합니다:
- 정체성 및 개성 특성
- 핵심 미션 및 워크플로우
- 코드 예제가 포함된 기술 산출물
- 성공 지표 및 커뮤니케이션 스타일

---

## 🛠️ 멀티 툴 통합

### 지원되는 도구
- Cursor
- Aider
- Windsurf
- Claude Code
- 기타 CLI 기반 AI 도구

### 설치 스크립트

```bash
# 1단계 - 모든 지원 도구의 통합 파일 생성
./scripts/convert.sh

# 2단계 - 대화형 설치 (설치된 항목 자동 감지)
./scripts/install.sh

# 또는 특정 도구를 직접 타겟팅
./scripts/install.sh --tool cursor
./scripts/install.sh --tool aider
./scripts/install.sh --tool windsurf
```

---

## 👥 에이전트 카탈로그

### 🔧 엔지니어링

| 에이전트 | 전문 분야 | 사용 시기 |
|---------|----------|-----------|
| 🎨 [프론트엔드 개발자](engineering/engineering-frontend-developer.md) | React/Vue/Angular, UI 구현, 성능 | 최신 웹 앱, 픽셀 완벽 UI, Core Web Vitals 최적화 |
| 🏗️ [백엔드 아키텍트](engineering/engineering-backend-architect.md) | API 설계, DB 아키텍처, 확장성 | 서버 사이드 시스템, 마이크로서비스, 클라우드 인프라 |
| 📱 [모바일 앱 빌더](engineering/engineering-mobile-app-builder.md) | iOS/Android, React Native, Flutter | 네이티브 및 크로스 플랫폼 모바일 앱 |
| 🤖 [AI 엔지니어](engineering/engineering-ai-engineer.md) | ML 모델, 배포, AI 통합 | 머신러닝 기능, 데이터 파이프라인, AI 기반 앱 |
| 🚀 [DevOps 자동화](engineering/engineering-devops-automator.md) | CI/CD, 인프라 자동화, 클라우드 옵스 | 파이프라인 개발, 배포 자동화, 모니터링 |
| ⚡ [빠른 프로토타이퍼](engineering/engineering-rapid-prototyper.md) | 빠른 POC 개발, MVP | 빠른 개념 증명, 해커톤 프로젝트, 빠른 반복 |
| 💎 [시니어 개발자](engineering/engineering-senior-developer.md) | Laravel/Livewire, 고급 패턴 | 복잡한 구현, 아키텍처 결정 |
| 🔒 [보안 엔지니어](engineering/engineering-security-engineer.md) | 위협 모델링, 안전 코드 리뷰, 보안 아키텍처 | 애플리케이션 보안, 취약성 평가, 보안 CI/CD |

**미학과 유용성을 만듭니다.**

---

### 🎨 디자인

| 에이전트 | 전문 분야 | 사용 시기 |
|---------|----------|-----------|
| 🎯 [UI 디자이너](design/design-ui-designer.md) | 비주얼 디자인, 컴포넌트 라이브러리, 디자인 시스템 | 인터페이스 생성, 브랜드 일관성, 컴포넌트 디자인 |
| 🔍 [UX 연구원](design/design-ux-researcher.md) | 사용자 테스트, 행동 분석, 연구 | 사용자 이해, 사용성 테스트, 디자인 인사이트 |
| 🏛️ [UX 아키텍트](design/design-ux-architect.md) | 기술 아키텍처, CSS 시스템, 구현 | 개발자 친화적 기반, 구현 가이드 |
| 🎭 [브랜드 가디언](design/design-brand-guardian.md) | 브랜드 정체성, 일관성, 포지셔닝 | 브랜드 전략, 정체성 개발, 가이드라인 |
| 📖 [비주얼 스토리텔러](design/design-visual-storyteller.md) | 비주얼 내러티브, 멀티미디어 콘텐츠 | 매력적인 비주얼 스토리, 브랜드 스토리텔링 |
| ✨ [위트 주입기](design/design-whimsy-injector.md) | 개성, 즐거움, 장난스러운 상호작용 | 기쁨 추가, 마이크로 인터랙션, 이스터 에그, 브랜드 개성 |
| 📷 [이미지 프롬프트 엔지니어](design/design-image-prompt-engineer.md) | AI 이미지 생성 프롬프트, 사진 | Midjourney, DALL-E, Stable Diffusion용 사진 프롬프트 |

---

### 📈 마케팅

| 에이전트 | 전문 분야 | 사용 시기 |
|---------|----------|-----------|
| 🚀 [성장 해커](marketing/marketing-growth-hacker.md) | 빠른 사용자 획득, 바이럴 루프, 실험 | 폭발적 성장, 사용자 획득, 전환 최적화 |
| 📝 [콘텐츠 크리에이터](marketing/marketing-content-creator.md) | 멀티 플랫폼 콘텐츠, 에디토리얼 캘린더 | 콘텐츠 전략, 카피라이팅, 브랜드 스토리텔링 |
| 🐦 [트위터 참여자](marketing/marketing-twitter-engager.md) | 실시간 참여, 사고 리더십 | 트위터 전략, LinkedIn 캠페인, 전문 소셜 |
| 📱 [틱톡 전략가](marketing/marketing-tiktok-strategist.md) | 바이럴 콘텐츠, 알고리즘 최적화 | 틱톡 성장, 바이럴 콘텐츠, Z세대/밀레니얼 오디언스 |
| 📸 [인스타그램 큐레이터](marketing/marketing-instagram-curator.md) | 비주얼 스토리텔링, 커뮤니티 빌딩 | 인스타그램 전략, 미적 개발, 비주얼 콘텐츠 |
| 🤝 [레딧 커뮤니티 빌더](marketing/marketing-reddit-community-builder.md) | 진정한 참여, 가치 기반 콘텐츠 | 레딧 전략, 커뮤니티 신뢰, 진정한 마케팅 |
| 📱 [앱 스토어 최적화](marketing/marketing-app-store-optimizer.md) | ASO, 전환 최적화, 검색 가능성 | 앱 마케팅, 스토어 최적화, 앱 성장 |
| 🌐 [소셜 미디어 전략가](marketing/marketing-social-media-strategist.md) | 크로스 플랫폼 전략, 캠페인 | 전체 소셜 전략, 멀티 플랫폼 캠페인 |
| 📕 [샤오홍슈 전문가](marketing/marketing-xiaohongshu-specialist.md) | 라이프스타일 콘텐츠, 트렌드 기반 전략 | 샤오홍슈 성장, 미적 스토리텔링, Z세대 오디언스 |
| 💬 [위챗 공식 계정 관리자](marketing/marketing-wechat-official-account.md) | 구독자 참여, 콘텐츠 마케팅 | 위챗 OA 전략, 커뮤니티 빌딩, 전환 최적화 |
| 🧠 [즈후 전략가](marketing/marketing-zhihu-strategist.md) | 사고 리더십, 지식 기반 참여 | 즈후 권위 구축, Q&A 전략, 리드 생성 |

**진정한 상호작용으로 청중을 성장시킵니다.**

---

### 🎯 제품

| 에이전트 | 전문 분야 | 사용 시기 |
|---------|----------|-----------|
| 🎯 [스프린트 우선순위](product/product-sprint-prioritizer.md) | 애자일 계획, 기능 우선순위 | 스프린트 계획, 리소스 할당, 백로그 관리 |
| 🔍 [트렌드 연구원](product/product-trend-researcher.md) | 시장 인텔리전스, 경쟁 분석 | 시장 연구, 기회 평가, 트렌드 식별 |
| 💬 [피드백 종합자](product/product-feedback-synthesizer.md) | 사용자 피드백 분석, 인사이트 추출 | 피드백 분석, 사용자 인사이트, 제품 우선순위 |

**적절한 시기에 적절한 것을 구축합니다.**

---

### 📊 프로젝트 관리

| 에이전트 | 전문 분야 | 사용 시기 |
|---------|----------|-----------|
| 🎬 [스튜디오 프로듀서](project-management/project-management-studio-producer.md) | 고급 조율, 포트폴리오 관리 | 멀티 프로젝트 감독, 전략적 정렬, 리소스 할당 |
| 🐑 [프로젝트 셰퍼드](project-management/project-management-project-shepherd.md) | 교차 기능 조율, 타임라인 관리 | 종단 프로젝트 조율, 이해관계자 관리 |
| ⚙️ [스튜디오 운영](project-management/project-management-studio-operations.md) | 일일 효율성, 프로세스 최적화 | 운영 우수성, 팀 지원, 생산성 |
| 🧪 [실험 추적자](project-management/project-management-experiment-tracker.md) | A/B 테스트, 가설 검증 | 실험 관리, 데이터 기반 결정, 테스트 |
| 👔 [시니어 프로젝트 관리자](project-management/project-manager-senior.md) | 현실적인 범위 설정, 작업 변환 | 사양을 작업으로 변환, 범위 관리 |

**기차를 정시에 (예산 내로) 운행합니다.**

---

### 🔍 테스팅

| 에이전트 | 전문 분야 | 사용 시기 |
|---------|----------|-----------|
| 📸 [증거 수집가](testing/testing-evidence-collector.md) | 스크린샷 기반 QA, 비주얼 증명 | UI 테스트, 비주얼 검증, 버그 문서화 |
| 🔍 [현실 확인관](testing/testing-reality-checker.md) | 증거 기반 인증, 품질 게이트 | 프로덕션 준비, 품질 승인, 릴리스 인증 |
| 📊 [테스트 결과 분석가](testing/testing-test-results-analyzer.md) | 테스트 평가, 지표 분석 | 테스트 출력 분석, 품질 인사이트, 커버리지 보고 |
| ⚡ [성능 벤치마커](testing/testing-performance-benchmarker.md) | 성능 테스트, 최적화 | 속도 테스트, 부하 테스트, 성능 튜닝 |
| 🔌 [API 테스터](testing/testing-api-tester.md) | API 검증, 통합 테스트 | API 테스트, 엔드포인트 검증, 통합 QA |
| 🛠️ [도구 평가자](testing/testing-tool-evaluator.md) | 기술 평가, 도구 선택 | 도구 평가, 소프트웨어 추천, 기술 결정 |
| 🔄 [워크플로우 최적화](testing/testing-workflow-optimizer.md) | 프로세스 분석, 워크플로우 개선 | 프로세스 최적화, 효율성 개선, 자동화 기회 |
| ♿ [접근성 감사자](testing/testing-accessibility-auditor.md) | WCAG 감사, 보조 기술 테스트 | 접근성 준수, 스크린 리더 테스트, 포용적 디자인 검증 |

**사용자가 겪지 않도록 먼저 깹니다.**

---

### 💾 지원

| 에이전트 | 전문 분야 | 사용 시기 |
|---------|----------|-----------|
| 💬 [지원 응답자](support/support-support-responder.md) | 고객 서비스, 문제 해결 | 고객 지원, 사용자 경험, 지원 운영 |
| 📊 [분석 리포터](support/support-analytics-reporter.md) | 데이터 분석, 대시보드, 인사이트 | 비즈니스 인텔리전스, KPI 추적, 데이터 시각화 |
| 💰 [재무 추적자](support/support-finance-tracker.md) | 재무 계획, 예산 관리 | 재무 분석, 현금 흐름, 비즈니스 성과 |
| 🏗️ [인프라 유지관리자](support/support-infrastructure-maintainer.md) | 시스템 신뢰성, 성능 최적화 | 인프라 관리, 시스템 운영, 모니터링 |
| ⚖️ [법적 준수 확인자](support/support-legal-compliance-checker.md) | 준수, 규정, 법적 리뷰 | 법적 준수, 규제 요구사항, 리스크 관리 |
| 📑 [경영진 요약 생성자](support/support-executive-summary-generator.md) | C레벨 커뮤니케이션, 전략 요약 | 경영진 보고, 전략적 커뮤니케이션, 결정 지원 |

**운영의 척추입니다.**

---

### 🥽 공간 컴퓨팅

| 에이전트 | 전문 분야 | 사용 시기 |
|---------|----------|-----------|
| 🏗️ [XR 인터페이스 아키텍트](spatial-computing/xr-interface-architect.md) | 공간 상호작용 디자인, 몰입형 UX | AR/VR/XR 인터페이스 디자인, 공간 컴퓨팅 UX |
| 💻 [macOS Spatial/Metal 엔지니어](spatial-computing/macos-spatial-metal-engineer.md) | Swift, Metal, 고성능 3D | macOS 공간 컴퓨팅, Vision Pro 네이티브 앱 |
| 🌐 [XR 몰입형 개발자](spatial-computing/xr-immersive-developer.md) | WebXR, 브라우저 기반 AR/VR | 브라우저 기반 몰입형 경험, WebXR 앱 |
| 🎮 [XR cockpit 상호작용 전문가](spatial-computing/xr-cockpit-interaction-specialist.md) | cockpit 기반 컨트롤, 몰입형 시스템 | cockpit 컨트롤 시스템, 몰입형 컨트롤 인터페이스 |
| 🍎 [visionOS 공간 엔지니어](spatial-computing/visionos-spatial-engineer.md) | Apple Vision Pro 개발 | Vision Pro 앱, 공간 컴퓨팅 경험 |
| 🔌 [터미널 통합 전문가](spatial-computing/terminal-integration-specialist.md) | 터미널 통합, 명령줄 도구 | CLI 도구, 터미널 워크플로우, 개발자 도구 |

**몰입형 미래를 구축합니다.**

---

### 🌟 전문화된 에이전트

틀에 맞지 않는 독특한 전문가들입니다.

| 에이전트 | 전문 분야 | 사용 시기 |
|---------|----------|-----------|
| 🎭 [에이전트 오케스트레이터](specialized/agents-orchestrator.md) | 멀티 에이전트 조율, 워크플로우 관리 | 여러 에이전트 조율이 필요한 복잡한 프로젝트 |
| 📊 [데이터 분석 리포터](specialized/data-analytics-reporter.md) | 비즈니스 인텔리전스, 데이터 인사이트 | 깊은 데이터 분석, 비즈니스 지표, 전략적 인사이트 |
| 🔍 [LSP/인덱스 엔지니어](specialized/lsp-index-engineer.md) | 언어 서버 프로토콜, 코드 인덱싱 | LSP 개발, IDE 통합, 코드 인텔리전스 |

---

## 🤝 기여

기여를 환영합니다! Pull Request를 만들어주세요.

## 📄 라이선스

MIT License - 자유롭게 사용, 수정, 배포하세요.

---

**미래를 구축합니다, 커밋씩 하나씩.** 🚀
