# 롤백 절차

## 단계
1. 이전 태그 확인
2. docker compose pull <tag>
3. docker compose up -d

## Phase 0~4 체크리스트

### Phase 0: Plan
- [ ] 롤백 기준 확인

### Phase 1: Infra
- [ ] compose 버전 확인

### Phase 2: External Access
- [ ] 서비스 상태 확인

### Phase 3: CI/CD
- [ ] 태그 관리 정책 적용

### Phase 4: Operations
- [ ] 롤백 결과 기록
