# Claude Code Docker 설치 가이드 (Synology NAS)

## 개요
Synology NAS에서 Claude Code를 Docker 컨테이너로 실행하는 방법을 설명합니다.

## 사전 요구사항
- DSM 7.x 이상
- Container Manager 패키지 설치
- SSH 접근 활성화

## 설치 절차

### 1. Docker 권한 설정
```bash
# docker 그룹 생성 및 유저 추가
sudo synogroup --add docker
sudo synogroup --member docker <username>
sudo chown root:docker /var/run/docker.sock

# SSH 재접속 후 확인
id  # docker 그룹 포함 확인
docker ps  # sudo 없이 실행 가능 확인
```

### 2. 디렉토리 생성
```bash
mkdir -p /volume1/docker/claude-code/config
mkdir -p /volume1/docker/claude-code/gitconfig
mkdir -p /volume1/docker/claude-code/ssh
mkdir -p /volume1/projects
```

### 3. 컨테이너 빌드 및 실행
```bash
cd /volume1/docker/claude-code
docker-compose up -d --build
```

### 4. Claude Code 실행
```bash
docker exec -it claude-code bash
claude
```

## 트러블슈팅

### 네이티브 설치 시 Segmentation fault
시놀로지 네이티브 환경에서 Claude Code 실행 시 Segmentation fault 발생할 수 있음.
→ Docker 컨테이너 방식으로 우회

### npm 전역 설치 권한 문제
```bash
sudo chmod -R 755 /usr/local/lib/node_modules/@anthropic-ai/
```

## Phase 체크리스트
- [x] Docker 컨테이너 구성
- [x] 볼륨 마운트 설정
- [ ] Git 연동 설정
- [ ] Ralph Loop 플러그인 설치
