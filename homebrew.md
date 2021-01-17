# Homebrew 

## Homebrew란 

* mac용 패키지 관리자
* 터미널을 통해 프로그램 설치, 삭제, 업데이트 가능

## cask 패키지 설치

* 프로그램 설치를 그래픽을 통해 볼 수 있는 것
* "brew install cask" 작성 후 설치

## homebrew 명령어

* 설치 항목 확인
~~~
brew list
~~~

* homebrew 최신 버전으로 업데이트
~~~
brew update
~~~

* homebrew에 설치된 프로그램 최신버전으로 업데이트
~~~
brew upgrade [프로그램명]
~~~

* homebrew 를 통해 설치 가능여부 확인
~~~
brew search [프로그램명]

//크롬 확인
brew search chrome  // homebrew/cask/google-chrome
~~~

### cask 사용

* 업데이트 후 필요없는 이전 버전의 패키지 삭제
~~~
brew cleanup
~~~

* 프로그램 설치 
~~~
brew cask install [프로그램명]

brew cask install google-chrome
~~~

* 설치 프로그램 확인
~~~
brew caskk list
~~~

* 프로그램 삭제(karabiner-elements)
~~~
brew cask remove karabiner-elements
~~~
---
## 출처

[WHITEPAEK Tech Docs](https://whitepaek.tistory.com/3)





