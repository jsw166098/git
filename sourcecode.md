# git 소스코드 수정

* 해당 프로젝트에 소속된 사람이 아닌경우 -> 오픈 소스에 관리자가 아닌경우, 권한이 없는 경우로 Pr(Pull requests) 보낸다.
* 해당 프로젝트에 소속된 사람인 경우

## 소스코드 업로드

~~~
1. `git add filename.~`, `git add .`을 이용해서 Staging Area로 이동시킨다.
2. `git commit -m "Add filename [Add]"`를 작성하여 커밋을 진행하여 Local repository로 이동시킨다.
3. `git push`을 입력하여 깃 원격 저장소(Remote Repository)로 이동시킨다.
~~~

* 클론의 경우 권한이 없어도 다운로드 가능하다.
* `git status` 상태확인 -> 커밋, push, add 등의 현황을 보여준다.
* 'git reset' 입력시 Working Directory로 다시 이동된다.
* 'git add .' 모든 수정 내용들이 Staging Directory로 이동된다. 
* `git checkout` 이용시 수정전으로 돌아간다.
* 커밋 메시지를 잘 못 입력했을 경우  append를 사용한다.
