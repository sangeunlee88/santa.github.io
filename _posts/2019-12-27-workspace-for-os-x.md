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
```

### Network 

```
lsof -i:[Port No.] : 해당하는 Port와 관련된 프로세스 확인
kill -9 [해당하는 PID No.] : o: -9 강제종료
ssh -f lee -L [target port]:localhost:[local port] -N

```
### Github 

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

### github.io 홈페이지 관련 

```

```


