# 위협 모델

## 범위
- NAS 호스트
- Docker 컨테이너
- 외부 접속(DDNS/HTTPS)

## 주요 위협
- 인증 정보 노출
- 외부 서비스 스캐닝
- 로그/백업 누출

## Phase 0~4 체크리스트

### Phase 0: Plan
- [ ] 위협 범위 정의

### Phase 1: Infra
- [ ] 최소 권한 컨테이너 구성

### Phase 2: External Access
- [ ] Reverse Proxy 접근 제어

### Phase 3: CI/CD
- [ ] 이미지 무결성 확인 절차

### Phase 4: Operations
- [ ] 보안 이벤트 알림 구성
