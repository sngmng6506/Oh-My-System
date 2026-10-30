# Skill 목록

스킬은 미리 설치하지 않는다. 기본 AI 도구로 해결하기 어려운 작업에서만 아래 전제를 확인한다.
사용 전제를 충족해도 해당 작업에 필요한 스킬만 설치한다. 설치된 스킬은 자체 설명에 따라 자동으로 선택될 수 있으므로, 목록의 사용 전제만으로 호출을 제한할 수는 없다.

| Skill | 사용 전제 | 설명 | 원본 |
| --- | --- | --- | --- |
| **Web Design Guidelines** | 기본 UI 검토로 접근성·사용성 문제의 범위를 파악하기 어렵고, 항목별 점검이 필요할 때 | 완성된 화면의 키보드 조작, 입력 폼, 이미지 설명, 피드백 등을 항목별로 검토한다. | [Vercel](https://github.com/vercel-labs/agent-skills/tree/main/skills/web-design-guidelines) |
| **Security Review** | 일반 코드 검토로 인증·권한 경계나 입력값의 흐름이 안전한지 판단하기 어려울 때 | 파일 사이의 데이터 흐름을 추적해 취약점이 실제로 발생할 수 있는지 검토한다. | [GitHub](https://github.com/github/awesome-copilot/tree/main/skills/security-review) |
| **Webapp Testing** | 코드와 기존 테스트가 통과했지만 실제 브라우저의 사용자 흐름까지 확인해야 할 때 | 로컬 웹 앱을 실행하고 브라우저에서 주요 흐름을 테스트한다. | [Anthropic](https://github.com/anthropics/skills/tree/main/skills/webapp-testing) |
| **Frontend Design** | 새 화면의 시각적 방향을 정해야 하는데 기존 디자인 시스템과 기본 시안만으로 제품에 맞는 방향을 잡기 어려울 때 | 화면을 만들기 전에 타이포그래피·색상·레이아웃의 방향을 정하고 결과를 검토한다. | [Anthropic](https://github.com/anthropics/skills/tree/main/skills/frontend-design) |
| **Systematic Debugging** | 재현한 오류의 원인을 일반적인 로그·코드 추적으로 찾지 못해 수정 가설을 반복하고 있을 때 | 재현, 원인 추적, 가설 검증, 수정 확인을 순서대로 수행한다. | [Superpowers](https://github.com/obra/superpowers/tree/main/skills/systematic-debugging) |
| **Diagnosing Bugs** | 반복되는 버그나 성능 저하를 재현했지만 원인을 좁힐 측정·검증 흐름을 만들기 어려울 때 | 실패를 보여주는 짧은 재현 절차를 만들고 계측과 회귀 검증까지 연결한다. | [Matt Pocock](https://github.com/mattpocock/skills/tree/main/skills/engineering/diagnosing-bugs) |
| **UI/UX Pro Max** | 디자인 시스템 문서와 기본 디자인 검토로 선택지를 좁히기 어렵고 스타일·색상·폰트 등의 자료를 비교해야 할 때 | 검색 가능한 디자인 자료를 바탕으로 후보를 만들고 디자인 시스템 값으로 정리한다. | [NextLevelBuilder](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) |
| **Graphify** | 큰 저장소에서 코드·문서·SQL 스키마의 연결을 반복해서 조사해야 하고 기존 검색·Serena·GitNexus로 관계를 파악하기 어려울 때 | 자료를 그래프로 만들어 관계 경로와 전체 구조를 조회한다. | [Graphify Labs](https://github.com/Graphify-Labs/graphify) |
| **Caveman (스킬만)** | 실제 작업 기록에서 토큰 소모가 반복적으로 크고 출력 축약을 시험해도 필요한 정보가 유지되는지 확인할 때 | 응답을 줄이는 스킬만 사용한다. 프록시와 자동 모델 선택 기능은 포함하지 않는다. | [JuliusBrussee](https://github.com/JuliusBrussee/caveman) |

## 설치 명령

아래 명령은 프로젝트 디렉터리에서 실행하는 Codex CLI·Claude Code용이다. `npx skills` 명령에는 Node.js 22.20 이상이 필요하다. 설치 전에는 공식 저장소의 최신 안내를 확인한다.

| Skill | Codex CLI | Claude Code |
| --- | --- | --- |
| Web Design Guidelines | `npx skills add vercel-labs/agent-skills --skill web-design-guidelines -a codex` | `npx skills add vercel-labs/agent-skills --skill web-design-guidelines -a claude-code` |
| Security Review | `npx skills add github/awesome-copilot --skill security-review -a codex` | `npx skills add github/awesome-copilot --skill security-review -a claude-code` |
| Webapp Testing | `npx skills add anthropics/skills --skill webapp-testing -a codex` | `npx skills add anthropics/skills --skill webapp-testing -a claude-code` |
| Frontend Design | `npx skills add anthropics/skills --skill frontend-design -a codex` | `npx skills add anthropics/skills --skill frontend-design -a claude-code` |
| Systematic Debugging | `npx skills add obra/superpowers --skill systematic-debugging -a codex` | `npx skills add obra/superpowers --skill systematic-debugging -a claude-code` |
| Diagnosing Bugs | `npx skills add mattpocock/skills --skill diagnosing-bugs -a codex` | `npx skills add mattpocock/skills --skill diagnosing-bugs -a claude-code` |
| UI/UX Pro Max | `npx ui-ux-pro-max-cli init --ai codex` | `npx ui-ux-pro-max-cli init --ai claude` |
| Graphify | `uv tool install graphifyy` → `graphify install --project --platform codex` | `uv tool install graphifyy` → `graphify install --project --platform claude` |
| Caveman (스킬만) | `npx skills add JuliusBrussee/caveman --skill caveman -a codex` | `npx skills add JuliusBrussee/caveman --skill caveman -a claude-code` |

Graphify는 Python 3.10 이상과 `uv`가 필요하다. Caveman은 위 스킬 설치 명령만 사용하며 프록시 전체 설치 명령은 사용하지 않는다.
