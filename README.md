# Team_Project
-------------------
2022년도 씨애랑 라온 하계워크샵 / 소프트웨어 전시회 팀 프로젝트



Trello - https://trello.com/b/GYNyQinF

<img src = "https://github.com/kevin1113-github/Raon_Team_Project/blob/master/trello-board-qr-code.png">


# 사용 유니티 버전
-------------------
2021.3.6f1


# 프로젝트 연결 방법
-------------------
```
$ mkdir Team_Project
$ cd Team_Project/
$ git init
$ git remote add origin https://github.com/kevin1113-github/Raon_Team_Project.git
$ git pull origin master
```
origin : 원격 저장소
origin master : 원격 저장소의 마스터 브랜치

# Git Pull
-------------------
작업을 시작하기전 항상 git pull 을 통해 동기화를 해주세요.

	$ git pull origin [브랜치 이름]


# Git Push 순서
-------------------
커밋 메시지는 알아보기 쉽게 작성해주세요.
작업 브랜치는 헷갈리지않도록 주의해주세요.
```
$ git add .
$ git commit -m "커밋 메시지"
$ git push origin [본인의 작업 브랜치]
```


# Git Branch 생성법
-------------------
	$ git branch [브랜치 이름]
로컬 저장소에 브랜치를 생성합니다.

	$ git chechout [브랜치 이름]
로컬 작업영역을 생성한 브랜치로 전환합니다.

	$ git push origin [브랜치 이름]
생성한 브랜치를 원격 저장소에 반영합니다.

