---
title: Git 기본 명령어
date: 2020-12-02 14:06:32
categories: ["Git"]
tags: ["Git"]
---

### 사용자이름, 이메일주소 설정
```
git config --global user.name "본인이름"
git config --global user.email "본인 이메일 주소"
```

### 설정 리스트 확인
```
git config --list
```

### 새로운 깃 저장소 만들기
```
git init
```

### 원격서버 저장소 받아오기
```
git clone <원격저장소 경로>
```

### 인덱스에 추가
```
git add <파일이름>
```
전체 내용을 반영하려면 `git add *` 명령어를 사용하면 된다.

### 변경내용 확정
```
git commit -m "코멘트"
```
`-m` 을 사용하면 코멘트 작성이 가능하다.


### 원격 저장소의 주소 등록
```
git remote add origin <원격저장소 경로>
```
`git clone`으로 받아왔다면 이과정은 필요없다.

### 원격 저장소에 올리기
```
git push origin master
```


