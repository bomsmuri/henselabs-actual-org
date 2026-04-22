# henselabs-actual-org

> 1인+AI 기반 미디어커머스 기업 에이전트 조직 운영 레포

---

## 이 레포의 목적

실전 에이전트 조직을 운영하는 곳. 학습 커리큘럼(ProjectClaude1)과 별개로 운영한다.

## 에이전트 구조

대표 (한범님)
    ↑
.claude/agents/
    ├── intelligence.md    ← 현재 팩트 수집 (수렴적 리서치)
    ├── discovery.md       ← 미래 신호 탐지 (발산적 리서치)
    ├── strategy-finance.md ← 사업성 평가 + 재무 시뮬레이션
    └── owned-media.md     ← 콘텐츠 재가공 + 오디언스 빌딩

## 핵심 문서

docs/01_company_blueprint.md — 회사 전체 설계도
docs/02_claude_code_setup_guide.md — 에이전트 셋업 가이드

## 현재 Phase

Phase 0: 카테고리 탐색 + 오디언스 빌딩 기반 구축

활성 프로젝트:
- Project Compass: 카테고리 탐색 → 진입 후보 Top 3~5 선정 (Intelligence 주도)
- Project Lighthouse: 채널 포지셔닝 + 오디언스 빌딩 착수 (Owned Media 주도)

## 공통 산출물 포맷

[TL;DR] 3줄 요약
[핵심 발견/제안] 불렛 5개 이내
[상세] 섹션별 구조화
[데이터] 정량 지표
[출처/가정] 신뢰도 등급 포함
[한계·불확실성]

신뢰도: A = 공시·정부통계·감사보고서 / B = 업계전문지·리서치기관 / C = 블로그·SNS

## 에이전트 공통 규칙

1. 대표를 대신해 결정하지 않는다 (옵션 제시까지만)
2. 확인되지 않은 숫자 생성 금지 (추정 시 "추정" 명시 + 근거)
3. 자기 역할 경계 준수
4. 중대 발견 시 즉시 에스컬레이션
5. 법률·세무·의료 조언 금지

## 파일 저장 규칙

- research/intelligence/ : Intelligence 리포트 (YYYYMMDD_주제_vN.md)
- research/intelligence/raw/ : 원자료
- research/discovery/ : Discovery 아이디어
- research/discovery/weekly/ : 주간 Top 5
- strategy/ : 전략·재무 문서
- strategy/models/ : 재무 모델
- content/drafts/ : 콘텐츠 초안
- content/approved/ : 승인 완료
- content/published/ : 발행 완료
