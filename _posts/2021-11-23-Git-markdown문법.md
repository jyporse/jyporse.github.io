---
layout: post
title: Git markdown 문법
date: 2021-11-23 21:24
last_modified_at: 2021-11-23 21:24
tags: [Git, Markdown, tutorial]
categories: [Git]
toc:  false
---

<h4>Markdown이란 ?</h4>

**마크다운(Markdown)**은 마크업 언어의 일종으로 온갖 태그로 범덕된 HTML문서 등과 달리, 읽기도 쓰기도 쉬운 문서 양식을 지향하며 확장자로는 .md 또는 .markdown을 쓰지만 .md를 압도적으로 많이 사용한다.

#### 문단 제목 '#'
문단의 제목을 사용할 때 사용하며 총 6단계까지 할 수 있으며, **#** 의 개수가 커질수록 크기가 작아진다.  
# 1단계 제목
## 2단계 제목
### 3단계 제목
#### 4단계 제목
##### 5단계 제목
###### 6단계 제목  

  

#### 강제 개행
문단을 구별하려면 한 개 이상의 빈 줄을 문단 사이에 삽입하거나, 줄의 마지막에 **Space Bar**를 **두 번** 이상 눌러 띄어쓰기를 하면 된다.
첫 번째 문장(공백없음)
두 번째 문장  강제개행

#### 목록(List)
Unordered list 와 Ordered list로 나뉘어진다.  
Unordered list  
'*'를 사용하며 들여쓰기를 통해 목록안에 목록을 만들 수도 있다.
* Item 1
* Item 2
    * Item 2a
    * Itam 2b  


Ordered list  
'1'을 사용하며 굳이 다음 숫자를 쓰지않고 '1'만을 사용하여도 된다.   들여쓰기를 통해 목록안에 목록을 만들 수도 있다. 
1. Item 1
1. Item 2
1. Item 3
    1. Item 3a
    1. Item 3b


#### 이미지(Images)
두 가지 방법이 존재한다.
1. Format: ![이미지 alt명](url 링크)





