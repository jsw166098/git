# git 사용법 정리

## git의 목적

* version(버전 관리)
* backup(백업)
* collaborate(협업)

## git의 동작 원리

### git의 3가지 구성요소

* Working Directory: 작업할 파일이 있는 디렉토리
* Staging Area: 커밋을 수행할 파일들이 올라가는 영역
* Git Directory

### 동작 원리
~~~
//파일 업로드
[Working Directory] ---> [Staging Directory] ---> [Local Repository] ---> [Remote Repository]
                "git add"                 "git commit"            "git push"

//파일 가져옴
[Working Directory] <--- [Staging Directory] <--- [Local Repository] <--- [Remote Repository]
                     "git                        merge"             "git fetch"                
~~~

* Working Directory: 사용자 컴퓨터 경로, 작업 파일
* Staging Directory(.git): 수정된 파일이며 commit을 기다리는 곳, .git 폴더에 존재하며 아직 사용자 컴퓨터에 존재
* Local Repositiry(.git): commit된 상태의 파일들이 저장되는 곳, .git 폴더에 존재하며 아직 사용자 컴퓨터에 존재
* Remote Repository: push 가 된 파일들, 깃 저장소이며 push 할 시 깃 저장소로 업로드 된다.

* git fetch: 파일 저장소로 local 저장소로 가져온다.
* git merge: 기존의 파일들과 충돌이 발생할 수 있기 때문에 병합하는 작업이다.
* git pull: fetch, merge 작업을 동시에 수행

## 출처
[생활코딩_ngit](https://opentutorials.org/course/3837/22434)

[동빈나 Git의 동작원리](https://www.youtube.com/watch?v=66c9QBXM2Fs&list=PLRx0vPvlEmdD5FLIdwTM4mKBgyjv4no81&index=4)
