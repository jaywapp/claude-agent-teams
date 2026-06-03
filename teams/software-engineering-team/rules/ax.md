# AX부 규칙 (AI Experience)

## 역할 정의
AX부는 두 트랙으로 운영된다:
- **Internal Track**: 회사 내부 에이전트 인프라 최적화 (박승수, 정상빈, 오현규)
- **External Track**: 고객 AI 솔루션 설계 및 구현 (이준재, 장석환)

## 주요 업무 트리거
- PM이 "반복 작업 자동화 필요" 판단 시 → 오현규(Skill Developer)에게 할당
- 에이전트 응답 품질 저하 감지 시 → 박승수(Prompt Engineer)가 개선
- 성능 평가 주기 도래 시 → 정상빈(AI Performance Analyst)이 리포트 작성
- 신규 모델 출시 시 → 염기훈이 도입 여부 검토
- 고객 프로젝트에 AI 솔루션 필요 시 → 이준재(AI Solution Architect) 투입

## Skill/Plugin 개발 원칙
- 오픈소스 우선 탐색 → 없을 경우 직접 제작
- 모든 Skill은 `wiki/ax/skill-catalog.md`에 등록
- 반복 3회 이상인 업무는 반드시 자동화 검토

## 성능 평가 기준
- 에이전트 응답 정확도
- 토큰 사용 효율 (목표: 매 스프린트 5% 절감)
- 재작업 요청 발생률
