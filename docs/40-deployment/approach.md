# 배포 접근 방식

## 원칙
- Docker 기반 배포
- 태그 기반 롤백 가능
- 로그/데이터 볼륨 분리

## Phase 0~4 체크리스트

### Phase 0: Plan
- [ ] 배포 범위 정의

### Phase 1: Infra
- [ ] compose 기반 배포 템플릿 준비

### Phase 2: External Access
- [ ] 외부 접속 경로 확정

### Phase 3: CI/CD
- [ ] 태그/릴리즈 전략 정의

### Phase 4: Operations
- [ ] 배포/롤백 로그 기록
