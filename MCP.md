# MCP 목록

MCP는 미리 설치하지 않는다. 기본 도구로 해결하기 어렵고 사용 전제에 맞을 때만 검토한다.
새 MCP 설치 전 용도·접근 범위를 알리고 확인받는다(사용자가 직접 설치를 요청했다면 제외).

| MCP | 사용 전제 | 설명 | 공식 문서 |
| --- | --- | --- | --- |
| **Context7** | 기본 검색으로 해당 버전의 API 사용법을 확인하기 어려울 때 | 라이브러리 문서와 코드 예시를 찾아 실제 사용하는 버전의 구현 방법을 확인한다. | [설치 및 사용법](https://github.com/upstash/context7) |
| **Playwright MCP** | 코드·테스트만으로 실제 화면 동작을 확인할 수 없을 때 | 브라우저에서 클릭과 입력을 수행해 사용자 흐름을 확인한다. | [설치 및 사용법](https://github.com/microsoft/playwright-mcp) |
| **Chrome DevTools MCP** | 일반적인 재현·로그 확인만으로 브라우저 문제의 원인을 찾기 어려울 때 | 콘솔, 네트워크 요청, 성능 기록을 조사한다. | [설치 및 사용법](https://github.com/ChromeDevTools/chrome-devtools-mcp) |
| **Serena** | 기본 코드 검색으로 큰 코드베이스의 수정 범위를 파악하기 어려울 때 | 함수·클래스와 파일 사이의 참조 관계를 찾아 분석·수정한다. | [설치 및 사용법](https://github.com/oraios/serena) |
| **GitNexus** | 큰 코드베이스에서 Serena로도 변경 영향 범위를 파악하기 어려울 때 | 코드 관계를 그래프로 만들어 호출 경로와 수정이 미칠 범위를 추적한다. | [설치 및 사용법](https://github.com/abhigyanpatwari/GitNexus) |
| **Codebase Memory MCP** | 큰 규모의 코드·문서 관계를 여러 작업에 걸쳐 반복 조회해야 하고 기본 검색으로 재구성하기 어려울 때 | 코드와 문서를 로컬 그래프로 색인해 관계를 검색하고 재사용한다. | [설치 및 사용법](https://github.com/DeusData/codebase-memory-mcp) |
| **Repomix** | 필요한 파일만 골라서는 저장소 전체 맥락을 전달하기 어려울 때 | 저장소를 AI가 읽기 쉬운 단일 자료로 묶는다. | [설치 및 사용법](https://github.com/yamadashy/repomix) |
| **MarkItDown** | 기본 파일 읽기 기능으로 필요한 내용을 추출하기 어려울 때 | PDF·Word·PPT·Excel 등의 내용을 Markdown으로 변환한다. | [설치 및 사용법](https://github.com/microsoft/markitdown) |
| **Semgrep MCP** | 기존 테스트·코드 검토만으로 보안 규칙 위반을 확인하기 어려울 때 | 로컬 Semgrep 검사로 코드의 보안 패턴과 규칙 위반을 찾아 분석한다. | [설치 및 사용법](https://github.com/semgrep/semgrep/tree/develop/cli/src/semgrep/mcp) |
| **REA** | 소스가 없는 앱·Electron 패키지·바이너리의 동작을 확인해야 하고, 실행 관찰과 일반 파일 분석만으로 구현 단서를 찾기 어려울 때 | 앱의 구성과 실행 동작을 조사해 근거가 있는 구현 단서를 찾는다. 설치 시 MCP와 작업 지침이 함께 등록된다. | [설치 및 사용법](https://github.com/morluto/rea) |
