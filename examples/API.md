# 내부 API 명세 작성 예시

프로젝트의 `API.md`에 실제 입력·출력·오류를 기록한다. 아래 경로와 값은 형식을 보여주는 예시다.

## POST /items

항목을 생성한다.

### 요청

| 필드 | 형식 | 필수 | 설명 |
| --- | --- | --- | --- |
| `name` | string | 예 | 항목 이름 |

```json
{"name": "Sample item"}
```

### 성공

- HTTP 상태: `201 Created`

```json
{"id": "item_123", "name": "Sample item"}
```

### 오류

| HTTP 상태 | 코드 | 상황 |
| --- | --- | --- |
| `400 Bad Request` | `INVALID_NAME` | 이름이 비어 있거나 허용 길이를 초과함 |

```json
{"error": {"code": "INVALID_NAME", "message": "이름을 확인해 주세요."}}
```
