# git_connect

#git 설치 방법---> 기본값으로 그대로 설치했음
google에 git검색 
64-bit Git for Windows Setup.다운로드

#시작버튼에서 git bash열기 (실행)

```
GG@DESKTOP-4DR04SQ MINGW64 ~
$ git config --global user.name "whasun"
```

#github 가입 시 입력한 이메일과 동일해야햔다.
```
ESKTOP-4DR04SQ MINGW64 ~
$ git config --global user.email "tlsgml1225@naver.com" 
```


#정보확인하기
```
$ git config --list
```
![image](https://github.com/yunshinhee/git_connect/assets/145514638/f9099e81-3b06-4255-970e-cc198b0bed2c)

🔝위의 내용은 컴퓨터에 한번만 설치하면 됨 

이모키콘 :알파벳 (🥐🥖🍞)
-------------------
-------------------(줄은 짧아도 끝까지 실행됨)

#github에 코드 업로드하기

vs에 업로드할 파일 넣기 -terminal
파일에 숨김항목 체크 후 .git파일 생겼는지 확인 

1.초기화

```
git init
```
#.git이라는 폴더가 생성된다


2.파일 올리기 
```
git add .
```

3.히스토리 만들기
```
git commit -m "내가 적고 싶은 메세지"
```
메세지에는 한글이 가능함
-m는 메세지의 준말

4.github repository랑 내 로컬 프로젝트랑 연결(깃업에 프로젝트를 올릴 repository를 먼저 만들어야한다)
#아래 주소는 깃헙에서 만든 repository에서 복사해서 가져와야한다(repository를 만들때 readme선택하지 말기)
```
git remote add origin https://github.com/yunshinhee/webstandard.git(복사)
```

5.잘 연결되었는지 확인(필수 아님)
```
git remote-v
```
6.github에 자료 올리기
```
git push origin master
```
#🔝여기까지 하면 github의 repository에 자료가 올라가 있다.
