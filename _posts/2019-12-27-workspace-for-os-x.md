<!-- ---
title: "OS X관련 단축키 정리"
categories:
tags:
data: "2019-12-27 23:00"


--- -->

## Linux Command 

``` 
### alias을 이용한 단축기 설정법
code ~/.zprofile 
alias desk='cd ~/Desktop'
alias cl='clear' 

df -h  현재남은 용량 확인

la 
las
 
```

### Network 

```
lsof -i:[Port No.] : 해당하는 Port와 관련된 프로세스 확인
kill -9 [해당하는 PID No.] : o: -9 강제종료
ssh -f lee -L [target port]:localhost:[local port] -N

```
### Github 
```
git init
git add .
git commit -m "initial commit"
git status
git push origin master 
```
### AnaConda 

```
conda remove -n [name] --all ### remove a [name] env.
conda create -n [new name] --clone [old name] ### copy env.
conda remove -n [old name] --all ### remove old one

conda env list ### show env. list
conda info --envs

conda create -n [name] [install module] ### ex. conda create -n new python=3.4

conda update conda 
conda update --all
conda activate [name] ### activate env.


```
## OS X 관련 단축키 정리

Command + Shift + g : 경로 입력창   
Command + Shift + h : 이전에 작성한 명령어 확인 (터미널)

## github.io 홈페이지 관련 

```
bundle exec jekyll serve ### port 4000 으로 확인 가능 
```




## pip 

```
pip install [name] --upgrade ### upgrade package 

pip install freeze 
pip freeze > requirements.txt : Save installed packages
pip install -r requirements.txt

pip install --upgrade pip

```




## Docker 

```
docker commit [container name] [new image name] ### docker image 작성업 

```

## Vim

```
w <-> b 단어단위
e : 단어의 끝 마지막
hjkl : 방향키
^ 첫번째 문자
0

$ 문장끝

문자 찾기

f+:문자 , ;
t+문자, ;(계속검색,정방향) , (역방향) 
/(문자 검색) 소문자 n
x: 삭제
dd: 한문장 삭제  
D 현재문장에서 끝까지
J 위로 당겨주기
p P 붙여넣기
dj
dj

y 한줄 복사
u 작업취소
ctr r

```


PyCharm 리모트 
```
ssh -f (name) -L 5000(Localpy):localhost:22 -N
```




