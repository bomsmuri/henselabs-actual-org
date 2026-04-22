# Claude Code Setup Guide v0.1

## 1. 에이전트 호출 방법

```
@intelligence APR의 최근 매출 데이터를 A등급 소스 기준으로 정리해줘

@discovery 이번 주 탐색 필터 기준으로 5개 아이디어 발굴해줘

@strategy-finance research/intelligence/[파일명] 읽고 사업성 초기 평가해줘

@owned-media intelligence 최신 리포트 기반으로 인스타 카드뉴스 초안 1개 만들어줘
```

## 2. 에이전트 동작 테스트

처음 셋업 후 역할 이해 확인:

```
@intelligence 네 역할과 Project Compass에서 담당하는 섹션을 요약해봐

@discovery 네 역할과 Intelligence와의 차이를 설명해봐

@strategy-finance 가정 테이블 예시를 보여줘

@owned-media 현재 Phase 미션과 금지사항을 말해봐
```

## 3. Project Compass 착수 순서

**Week 1:**
```
@intelligence Project Compass 섹션 A 착수. APR부터. 신뢰도 A/B 중심.
@discovery 이번 주 5개 아이디어 발굴. weekly_top5 리포트 주말까지.
```

**Week 2:**
```
@intelligence 섹션 B, C 진행
@strategy-finance intelligence+discovery 산출물 읽고 카테고리 초기 스코어카드 작성
```

**Week 3:**
```
@intelligence 섹션 D 완료
@strategy-finance 카테고리 Top 3~5 추천 리포트 초안
@owned-media 첫 콘텐츠 5~10개 draft 완성
```

## 4. 에이전트 간 협업

에이전트는 직접 대화 불가. 대표가 중재자.

예시:
```
@strategy-finance research/intelligence/20260422_apr_v1.md 읽고 단위경제 추정해줘. 가정 테이블 먼저.
```

## 5. 운영 팁

- 에이전트 호출 시 관련 파일 경로 명시하면 정확도 높아짐
- 주 1회 "이번 주 산출물 자가 평가" 수행
- 산출물 품질 낮으면 해당 에이전트 .md 금지사항 섹션 보강
- 모든 파일명: YYYYMMDD_주제_vN.md
