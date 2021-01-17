# 깃 설치

## 깃 소프트웨어 설치

<http://git-scm.com/downloads>

디폴트 설정을 next 클릭 -> 터미널에서 깃 명령어(git으로 시작된다.) 작성할 수 있도록 설정되어 있다.

설치 확인을 위해 ~git~, ~git --verion~ 작성한다.

## 깃 환경설정

~~~
git config --global user.name jsw166098
git config --global user.email jsw166098@gmail.com
~~~

* 컴퓨터 환경 전체에서 사용할수 있도록 global 작성
* username 으로 깃허브 계정을 넣어준다.
* useremail도 깃허브 이메일 주소 넣는다.

## 특정 경로를 깃허브 저장소와 연결-> 컴퓨터 경로(local)로 깃허브(remote) 저장소 클론

1. 깃허브 경로를 복사한다.
2. cmd에서 특정 경로로 이동한다. (cd 명령어 이용)
3. ~git clone~ 이용해서 깃허브 경로를 붙여 넣는다. 
4. 깃허브 폴더 명이 특정 경로에 생성된다. 

~~~
git clone https:~~
~~~

## 파일 업로드

* cmd에서 클론된 경로로 이동하여 명령어를 입력한다.

~~~
git add document.txt
git commit -m "Add Text File [document.txt]"  //로컬 저장소로 컴밋
git push   //깃 저장소로 업로드
~~~

