# 대상 NAS 환경

## 사양
- 모델: Synology DS224+
- DSM: 7.3.2
- CPU: Intel J4125 (x86_64)
- RAM: 16GB 예정

## 네트워크
- 외부 접속: Synology DDNS
- 공인 IP, L3 브릿지 모드
- HTTPS: Let’s Encrypt + Reverse Proxy

## Phase 0~4 체크리스트

### Phase 0: Plan
- [ ] 대상 NAS 사양 확정
- [ ] 네트워크 구성 확인

### Phase 1: Infra
- [ ] NAS 볼륨 경로 규칙 정의

### Phase 2: External Access
- [ ] DDNS 등록 확인
- [ ] Reverse Proxy 정책 정의

### Phase 3: CI/CD
- [ ] 배포 대상 리소스 제한 정의

### Phase 4: Operations
- [ ] 자원 모니터링 기준 정의
