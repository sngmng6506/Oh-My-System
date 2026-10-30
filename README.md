# Oh-My-System

개발 원칙과 도구 선택 기준을 정리한다. 디테일한 기능 명세와 합의 사항은 각 프로젝트에서 관리한다.


## 문서

| 문서 | 내용 |
| --- | --- |
| [DEVELOPMENT_PRINCIPLES.md](DEVELOPMENT_PRINCIPLES.md) | 구현, 검증, 기록에 관한 공통 원칙 |
| [DESIGN_PRINCIPLES.md](DESIGN_PRINCIPLES.md) | 화면 구성과 디자인 시스템 문서화에 관한 원칙 |
| [API_PRINCIPLES.md](API_PRINCIPLES.md) | API 계약, 오류 처리, 명세 관리에 관한 원칙 |
| [SECURITY_PRINCIPLES.md](SECURITY_PRINCIPLES.md) | 비밀값, 입력 검증, 권한, 암호화, 개인정보, 의존성에 관한 원칙 |
| [GIT_PRINCIPLES.md](GIT_PRINCIPLES.md) | 커밋, 브랜치, PR, 이력 관리에 관한 원칙 |
| [DEPLOY_PRINCIPLES.md](DEPLOY_PRINCIPLES.md) | 배포 자동화, 검증, 되돌리기, 호환성, 장애 감지에 관한 원칙 |
| [MCP.md](MCP.md) | 필요할 때 연결할 MCP 목록 |
| [SKILLS.md](SKILLS.md) | 필요할 때 설치할 스킬 목록과 설치 명령 |


## 프로젝트에 적용하기

CLI에서 프로젝트 열고 다음처럼 요청한다.

> sngmng6506/Oh-My-System 저장소를 참고해줘. 이번 작업과 관련된 원칙을 확인해서 적용해줘.

이 방식은 저장소를 읽을 수 있는 환경에서 사용한다. 접근할 수 없다면 Codex에게 그 사실을 확인하고 필요한 문서를 제공한다. 새 대화를 시작할 때는 다시 요청한다.

매번 요청하는 대신 프로젝트에 작업 지침을 두고 싶다면 루트에 [AGENTS.md 예시](examples/AGENTS.md)를 복사한다. Claude Code에서도 사용하려면 [CLAUDE.md 예시](examples/CLAUDE.md)를 함께 복사할 수 있다. 예시의 링크는 문서 내용을 자동으로 불러오지 않으므로, 관련 작업에서 링크를 열 수 있어야 한다.
