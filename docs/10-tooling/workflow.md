# Codex/Claude Code 협업 워크플로우

## 흐름
1. Codex로 문서/템플릿 생성
2. Claude Code로 실행 가능한 구성 보강
3. 변경 내용 검토 후 커밋
4. NAS에서 테스트
5. 결과/결정은 ADR로 기록

## Phase 0~4 체크리스트

### Phase 0: Plan
- [ ] 문서/템플릿 생성 요청
- [ ] 변경 파일 목록 검토

### Phase 1: Infra
- [ ] compose 템플릿 개선
- [ ] .env.example 검증

### Phase 2: External Access
- [ ] Reverse Proxy 경로 확인
- [ ] 인증서 발급 절차 확인

### Phase 3: CI/CD
- [ ] 배포 자동화 수준 합의

### Phase 4: Operations
- [ ] 운영 체크리스트 검증
