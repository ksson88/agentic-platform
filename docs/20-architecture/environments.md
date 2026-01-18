# 환경 구성

## 환경 구분
- 로컬: 개발/검증
- NAS: 운영

## 공통 원칙
- 민감정보는 .env.example에만 템플릿으로 제공
- 실제 비밀은 Secret Manager 또는 NAS 안전 저장소 사용

## Phase 0~4 체크리스트

### Phase 0: Plan
- [ ] 환경 정의

### Phase 1: Infra
- [ ] 환경별 compose 분리

### Phase 2: External Access
- [ ] 환경별 도메인/인증서 구분

### Phase 3: CI/CD
- [ ] 환경별 태그 전략 정의

### Phase 4: Operations
- [ ] 환경별 모니터링 기준 정리
