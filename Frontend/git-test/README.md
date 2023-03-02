## Git Command

- `git init`
  - **git을 사용하기 위한 준비단계이다. 해당 명령어를 실행하면 .git이라는 숨겨진 폴더가 생성되며, 그 때 부터 git 명령어를 사용할 수 있게 된다.**
- `git remote add origin <remote repository url>`
  - **원격 레포지토리를 로컬에 연동시키기 위한 명령어이다.**
- `git add <file name>`
  - **변경사항이 있는 파일을 마치 쇼핑몰 장바구니에 담아두는 것처럼 stage라는 공간에 적재시킨다. commit 이전에 이 단계가 수행되어야 한다.**
- `git commit`
  - \*_앞서 add로 stage에 등재된 파일들을 원격 레포지토리에 기록하는 작업이다._
- `git push origin <branch name>`
  - **push 명령어를 치면 커밋된 파일들이 원격 레포지토리에 등재된다. 즉, 타 팀원이 푸시된 소스를 반영할 수 있는 상태가 된다.**
- `git pull origin <branch name>`
  - **원격 레포지토리의 소스를 내 로컬로 반영시킨다.**
- `git merge <branch name>`
  - **[branch name]의 변경사항을 현재 있는 브랜치로 가져와 적용시킨다. 동일한 파일을 변경했다면 충돌이 생길 수 있다.**
