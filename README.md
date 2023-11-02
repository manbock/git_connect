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
