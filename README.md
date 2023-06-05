# Git 명령어

## Git 로컬 컴퓨터에 사용자 등록하기

- git init
- git config --global user.name "knh1766"
- git config --global user.email "knh1766@naver.com"

## Git 시작하기

- git init
- git add .
- git commit -m "최초커밋"

## Git 업로드하기

- git remote add origin 주소
- git push origin master

- 소스코드변경
- git add .
- git commit -m "변경내용적고"
- git push origin master

## 잘안될때 해결법

- git remote -v
- git remote rm origin

## 깃헙 소스코드 다운로드 하는법

- git clone 주소
