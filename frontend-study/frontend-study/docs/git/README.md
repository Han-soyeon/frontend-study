# Git 명령어 정리

# 원하는 폴더로 이동
cd ~/Documents

# 폴더 생성
mkdir frontend-study
cd frontend-study

# Git 초기화
git init

# 원격 저장소 연결 (URL은 네가 만든 GitHub 주소)
git remote add origin https://github.com/사용자명/frontend-study.git

# 기본 브랜치 설정 (GitHub의 기본은 main)
git branch -M main

# README 등 최초 파일 복사 (GitHub에서 직접 만든 경우 clone이 더 낫다!)
git pull origin main
