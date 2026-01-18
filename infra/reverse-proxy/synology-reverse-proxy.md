# Synology Reverse Proxy 설정

## 절차
1. 제어판 → 로그인 포털 → 고급 → Reverse Proxy
2. 규칙 추가
3. 소스: https://example.synology.me
4. 대상: http://localhost:8080

## Phase 0~4 체크리스트

### Phase 0: Plan
- [ ] 경로/도메인 정의

### Phase 1: Infra
- [ ] 서비스 포트 확인

### Phase 2: External Access
- [ ] Reverse Proxy 규칙 적용

### Phase 3: CI/CD
- [ ] 도메인 변경 시 규칙 업데이트

### Phase 4: Operations
- [ ] 접근 로그 확인
