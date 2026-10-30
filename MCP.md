# MCP 목록

MCP는 미리 설치하지 않는다. 기본 AI 도구로 해결하기 어려운 작업에서만 아래 전제를 확인한다. 설정은 각 공식 문서의 설치 방법을 따른다.

새 MCP를 설치하기 전에는 용도와 접근 범위를 사용자에게 알리고 확인받는다. 사용자가 설치를 직접 요청했다면 다시 묻지 않는다.

| MCP | 사용 전제 | 설명 | 공식 문서 |
| --- | --- | --- | --- |
| **Context7** | 기본 검색으로 해당 버전의 API 사용법을 확인하기 어려울 때 | 라이브러리 문서와 코드 예시를 찾아 실제 사용하는 버전의 구현 방법을 확인한다. | [설치 및 사용법](https://github.com/upstash/context7) |
| **Playwright MCP** | 코드·테스트만으로 실제 화면 동작을 확인할 수 없을 때 | 브라우저에서 클릭과 입력을 수행해 사용자 흐름을 확인한다. | [설치 및 사용법](https://github.com/microsoft/playwright-mcp) |
| **Chrome DevTools MCP** | 일반적인 재현·로그 확인만으로 브라우저 문제의 원인을 찾기 어려울 때 | 콘솔, 네트워크 요청, 성능 기록을 조사한다. | [설치 및 사용법](https://github.com/ChromeDevTools/chrome-devtools-mcp) |
| **Serena** | 기본 코드 검색으로 큰 코드베이스의 수정 범위를 파악하기 어려울 때 | 함수·클래스와 파일 사이의 참조 관계를 찾아 분석·수정한다. | [설치 및 사용법](https://github.com/oraios/serena) |
| **Repomix** | 필요한 파일만 골라서는 저장소 전체 맥락을 전달하기 어려울 때 | 저장소를 AI가 읽기 쉬운 단일 자료로 묶는다. | [설치 및 사용법](https://github.com/yamadashy/repomix) |
| **MarkItDown** | 기본 파일 읽기 기능으로 필요한 내용을 추출하기 어려울 때 | PDF·Word·PPT·Excel 등의 내용을 Markdown으로 변환한다. | [설치 및 사용법](https://github.com/microsoft/markitdown) |
