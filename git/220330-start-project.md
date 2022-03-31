# branch

- 브랜치란 독립적으로 어떤 작업을 진행하기 위한 개념이다.

- git branch (이름) : branch 만들기

- git switch (이름) : branch 전환

- git branch -d (이름) : branch 삭제

- git merge (이름) : branch 병합

# Git Flow

- git flow는 git을 형상관리를 할때 branch를 효율적으로 관리하기 위해 사용하는 branch 입니다.

- git flow init : 초기화

- git flow feature start (이름) : develop 안에 branch 생성

- git flow feature finish (이름) : develop에 병합하면서 기존 branch 삭제

- git flow release start (이름) : release 시작

- git flow release finish (이름) : release branch를 (main) branch 병합
