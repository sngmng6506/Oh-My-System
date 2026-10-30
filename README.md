# Oh-My-System

개발 원칙과 도구 선택 기준을 정리한다. 디테일한 기능 명세와 합의 사항은 각 프로젝트에서 관리한다.


## 문서

| 문서 | 내용 |
| --- | --- |
| [DEVELOPMENT_PRINCIPLES.md](DEVELOPMENT_PRINCIPLES.md) | 구현, 검증, 기록에 관한 공통 원칙 |
| [DESIGN_PRINCIPLES.md](DESIGN_PRINCIPLES.md) | 화면 구성과 디자인 시스템 문서화에 관한 원칙 |
| [API_PRINCIPLES.md](API_PRINCIPLES.md) | API 계약, 오류 처리, 명세 관리에 관한 원칙 |
| [MCP.md](MCP.md) | 필요할 때 연결할 MCP 목록 |
| [SKILLS.md](SKILLS.md) | 필요할 때 설치할 스킬 목록과 설치 명령 |

새 문서는 실제 필요가 생길 때 추가하고 이 표에 연결한다.

## 프로젝트에 적용하기

프로젝트 루트에 [AGENTS.md 예시](examples/AGENTS.md)를 복사해 작업 지침으로 사용한다. Claude Code에서 함께 사용할 때는 [CLAUDE.md 예시](examples/CLAUDE.md)도 복사한다. `CLAUDE.md`는 `AGENTS.md`를 가져오므로 같은 지침을 중복 작성할 필요가 없다.

예시에 적힌 원칙 문서 링크는 자동으로 내용을 불러오지 않는다. 작업 환경에서 링크를 열 수 있는지 확인하고, 접근할 수 없다면 필요한 문서를 프로젝트에서 읽을 수 있는 위치에 두고 링크를 바꾼다.
