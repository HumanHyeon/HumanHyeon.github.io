---
layout: post
section-type: post
title: 마크다운은 어떻게 사용할까?
category: Daliy
tags: [ '마크다운', '사용법' ]
---
<br>
# <center>[ 마크다운 문법 ]</center>
  
<br>
### 주석 : `<!-- 내용 -->`  
<!-- ```{no-highlight} -->
주석은 안에 내용을 작성하고 `<!--  -->` 로 감싸서 주석 처리 한다. <!-- ex)예시 -->  
<!-- ``` --> 
<br>  
  
***

<br> 
### 줄 띄기('\n') : `'  '` (공백 2개 이상)  or  `<br>`
마크다운의 띄어쓰기는 Spacebar 2번 이상을 이용하여 '\n'처리를 한다.  
혹은 br태그를 이용하여 '\n'처리를 한다.  
마크다운에서는 Enter를 줄 띄기로 인식하지 않는다.  
<br>
  
***

<br>
### 제목 Headers  
제목은 총 6단계를 사용할 수 있다. (아래 단계로 내려갈 수록 글자가 작아지며 조금씩 차이가 난다.)
```
<1단계>
    • # 제목1
    • 제목1
       =
    • <h1> 제목1 </h1>
<2단계>
    • ## 제목2
    • 제목2
       -
    • <h2> 제목2 </h2>
<3단계>
    • ### 제목3
    • <h3> 제목3 </h3>
<4단계>
    • #### 제목4
    • <h4> 제목4 </h4>
<5단계>
    • ##### 제목5
    • <h5> 제목5 </h5>
<6단계>
    • ###### 제목6
    • <h6> 제목6 </h6>
```  
# Header1
## Header2
### Header3
#### Header4
##### Header5
###### Header6  
<br>
  
***
  
<br>
### 강조(Emphasis)

  
`<em>`  
> <em>em 태그를 사용한 강조<em>   
> *이는 * *로 묶은 효과와 같다*  
> _under bar를 사용해서 묶은 것과도 같다_  

`<strong>`  
> <strong>strong 태그를 사용한 강조<strong>  
> **이는 ** **로 묶은 효과와 같다**  
> __2개의 underbar를 사용해서 묶은 것과도 같다__  

`<em> + <strong>`  
> **_em과 strong태그를 두 개 합쳐서 같이 사용할 수 있다_**  

`<del>`  
> <del>del 태그를 사용한 강조<del>  
> ~~2개의 ~(tilde)로 묶은 효과와 같다~~

`<u>`
> <u> 밑줄은 u태그와 /u 태그로 묶어 사용할 수 있다.</u>   
  
<br>
  
***
  
<br>
### 목록(List)
`<ol>` - 순서o
> 1.로 순서 있는 목록을 만든다.  

1. 순서가 필요한 목록  
1. 앞 숫자를 무엇으로 사용하든 상관이 없다.(현재 1.)
2. 다른 숫자를 주어져도 상관이 없다.(현재 2.)  

> -로 순서 목록 내 서브 목록을 생성한다.  

1. 목록
- 서브1
- 서브2
- 서브3
  
`<ul>` - 순서x  
> -, *, +를 사용하여 순서가 필요하지 않은 목록을 만든다.  

- -(hyphen)  
* *(asterisks)  
+ +(plus sign)  
  
<br>
  
***
  
<br>
### 링크(List)
`<a>`  
> [Google](https://google.com)   
> ```[Google](https://google.com)``` 

> [Naver](https://naver.com "마우스를 가져다가 대면 링크에 대한 설명이 나타나는 부분")  
> ```[Naver](https://naver.com "마우스를 가져다가 대면 링크에 대한 설명이 나타나는 부분")```
  
> 일반 링크를 적으면 : https://HumanHyeon.github.io  
> <>로 묶어 일반 링크를 적으면 : <https://HumanHyeon.github.io >  

<br>
  
***
  
<br>
### 이미지(Images)  
`<img>`  
  
앞에 `!`를 붙여 사용.  

> **! [대체 텍스트] (이미지 링크 주소 "링크 설명")**  
![고양이 사진](data:image/jpeg;base64,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 "고양이 사진")  

<br>  
### 이미지에 링크

> **[ ! [대체 텍스트] (이미지 링크 주소 "링크 설명") ] (주소)**  
[![깃헙 아이콘](https://img.icons8.com/clouds/452/github.png "Github 블로그로 이동")](https://HumanHyeon.github.io)  

<br><br><br><br><br>
  
사용하면서 추가해나갈 예정입니다!