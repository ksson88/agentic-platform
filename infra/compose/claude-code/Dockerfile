FROM node:20-bookworm

# 시스템 패키지 설치
RUN apt-get update && apt-get install -y \
    git \
    curl \
    vim \
    jq \
    openssh-client \
    && rm -rf /var/lib/apt/lists/*

# Claude Code 설치
RUN npm install -g @anthropic-ai/claude-code

# 작업 디렉토리 설정
WORKDIR /workspace

# 기본 쉘을 bash로 설정
SHELL ["/bin/bash", "-c"]

# 컨테이너 시작 시 bash 실행
CMD ["bash"]
