# 비밀정보 관리

## 원칙
- 레포에 비밀정보 금지
- .env.example만 제공
- 실제 값은 Secret Manager에 저장

## Phase 0~4 체크리스트

### Phase 0: Plan
- [ ] 비밀정보 분류 정의

### Phase 1: Infra
- [ ] .env.example 작성

### Phase 2: External Access
- [ ] 인증서/키 관리 절차 정의

### Phase 3: CI/CD
- [ ] 배포 시크릿 주입 방식 정의

### Phase 4: Operations
- [ ] 주기적 교체 절차 정의
