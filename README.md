# agentic-platform

Codex/Claude Code로 설계-개발-배포-운영을 자동화한 기록을 남기는 레포지토리입니다.
대상 환경 중 하나로 Synology NAS(DSM 7.3.2)를 포함합니다.

## 목적
- NAS에 배포 및 운영하는 전 과정을 문서화
- 재현 가능한 템플릿(Compose/Runbook/Checklist) 제공
- 결정 사항을 ADR로 기록

## 구성
- docs/: 설계/운영 문서
- infra/: 실행 템플릿(Compose, Reverse Proxy)
- runbooks/: 운영 절차서
- .github/ISSUE_TEMPLATE/: 이슈 템플릿

## 빠른 시작
1. docs/00-overview.md 확인
2. infra/compose/base/docker-compose.yml 템플릿 확인
3. runbooks/deploy.md 절차대로 배포
