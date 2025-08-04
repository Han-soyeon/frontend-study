# Git 명령어 정리

# 원하는 폴더로 이동
cd D:\project\vscode\frontend-study

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

# 루트 폴더 생성 및 이동
mkdir frontend-study && cd frontend-study

# 메인 폴더들 생성
mkdir docs projects presentation

# docs 하위 폴더 생성
mkdir -p docs/html-css
mkdir -p docs/javascript
mkdir -p docs/vue
mkdir -p docs/react
mkdir -p docs/typescript
mkdir -p docs/git

# 프로젝트 예시 폴더 생성 (기업명 제거, 포트폴리오 지향)
mkdir -p projects/dashboard-prototype

# 예시 파일 생성
echo "# 프론트엔드 학습 및 실습 레포지토리" > README.md
echo "# Git 명령어 정리" > docs/git/README.md
echo "# Vue 정리" > docs/vue/README.md
echo "# 프로젝트 - 대시보드 프로토타입" > projects/dashboard-prototype/README.md

# 커밋 메세지
git add .
git commit -m "기본 폴더 구조 및 대시보드 프로토타입 생성"
git push origin main
