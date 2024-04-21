# Git Command

$ pwd : 현재 디렉토리 확인

$ ls : 현재 폴더의 파일 리스트

$ ls -a : 숨김 파일 보기

$ ls -l : 파일 상세 리스트 보기

$ cd Documents/ : 폴더 위치 이동

$ mkdir dev : 폴더 만들기

$ touch hello.py : 빈 파일 만들기

$ mv README.md dest : 파일 이동 시키기

$ mv ../*.py ./  : 와일드 카드로 파일 이동 시기키

$ cp main.py ./main_copy.py : 파일 복사하기

$ mv LICENSE license.txt : 파일 이름 바꾸기

$ rm license.txt : 파일 지우기

$ rm -rf dest : 폴더 지우기

$ vi hello.md : 파일 편집

$ cat hello.md : 파일 내용 보기

$ git config --list : git 환경 설정 내용 보기

$ git config --global user.name "ktbaek72" 

$ git config --global user.email "ktbaek72@gmail.com"

$ git config --global core.editor "vim"

$ git config --global core.pager "cat"

$ git config --global alias.lg "log --graph --pretty=tformat:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --decorate=full"

# github 저장소 복제

$ git clone https://github.com/ktbaek72/first-repo.git

# 상태 보기

$ git status

# staging

$ git add main.py

# 

$ git commit

# 변경 내용 확인 하기

$ git diff main.py

# 원격 github에 변경 내용 올리기

$ git push origin main

# 간단 log 보기

$ git lg

# LF 경고 처리
# $ git add main.py
# warning: in the working copy of 'main.py', LF will be replaced by CRLF the next time Git touches it

$ git config --global core.autocrlf false

# version

$ node -v
v20.12.2

$ npm -v
10.5.0

# hexo update

$ npm install -g hexo-cli

# blogging : Start blogging with Hexo!

$ hexo init ghblog

# 추가 update

$ npm install

# 

$ hexo clean
INFO  Validating config

# Generate static files

$ hexo generate

# Run server

$ hexo server

# Create a new post

$ hexo new post "My First Blog"


# 현재 폴더가 Editor(vscode)에서 열림

$ code .

# clean and generate 명령을 아래와 같이 한번에 하기

$ hexo clean && hexo generate

# 블로그 테마 install

$ npm install hexo-theme-next@latest

# deploy install

$ npm install hexo-deployer-git --save

# Deploy to remote sites  

$ vi _config.yml

$ hexo deploy

# git clone

git clone https://github.com/ktbaek72/TIL.git



