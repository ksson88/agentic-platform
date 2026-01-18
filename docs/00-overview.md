# 개요

이 레포는 Codex/Claude Code를 활용해 NAS 배포 및 운영을 자동화/기록하는 베이스라인입니다.

## Phase 0~4 체크리스트

### Phase 0: Plan
- [ ] 목표/범위 정의
- [ ] 대상 NAS 스펙 정리
- [ ] 문서 구조 확정
- [ ] ADR 템플릿 준비

### Phase 1: Infra
- [ ] docker-compose 템플릿 구성
- [ ] 볼륨/로그 경로 설계
- [ ] healthcheck/로그 회전 옵션 포함

### Phase 2: External Access
- [ ] DDNS 구성
- [ ] HTTPS(LE) 발급
- [ ] Reverse Proxy 경로 설계

### Phase 3: CI/CD
- [ ] 이미지 태그 전략 정의
- [ ] 롤백 기준 정의
- [ ] 배포 자동화 수준 결정

### Phase 4: Operations
- [ ] 모니터링/로그 수집
- [ ] 백업/복구 절차
- [ ] 장애 대응 체크리스트
