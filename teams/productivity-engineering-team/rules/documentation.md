# 문서화 규칙

## 목적

팀의 지식이 축적되고, 누구든 이해하고 유지보수할 수 있도록 한다.

## 적용 대상

모든 파트

## 반드시 해야 할 것

- 모든 프로젝트는 `projects/{project-id}/` 하위에 다음 문서를 작성한다:
  - `request.md`: 요청 배경과 문제 정의
  - `plan.md`: 작업 계획
  - `decisions.md`: 주요 결정과 근거
  - `validation.md`: 검증 결과
  - `handoff.md`: 인수인계 내용
- 프로젝트 종료 시 `report/`에 최종 보고서를 작성한다.
- Wiki 문서에는 배경, 현재 방식, 표준 절차, 관련 링크를 포함한다.
- 문서 간 연결은 Obsidian 내부 링크 형식(`[[파일명]]`)을 사용한다.

## 금지할 것

- 결과물 위치와 사용 방법 없이 작업을 완료로 처리하는 것
- 타인이 이해할 수 없는 약어나 내부 용어를 설명 없이 사용하는 것

## 프로젝트 ID 형식

```
YYYYMMDD-short-topic
예시: 20260530-build-log-analyzer
```

## 관련 문서

- [[rules/general]]
- [[docs/templates/project-request]]
- [[docs/templates/final-report]]
