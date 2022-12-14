---
layout: post
title:  "마크다운(Markdown)"
date:   2022-11-19 05:05:36 +0900
categories: jekyll update
---

마크다운이란 일반 텍스트 기반의 경량 마크업 언어이다.  
마크업 언어란 태그 등을 이용하여 문서나 데이터의 구조 등을 명기하는 언어의 한 가지이다.  
주로 텍스트만으로 서식이 있는 문서들을 작성할 때 자주 사용되며,  
**다른 마크업 언어들에 비해 문법이 쉽고 간단하며**  
**다양한 플랫폼에 지원하고**  
**대부분의 환경에서 작성 및 수정이 가능하다.**  
**하지만 모든 HTML의 마크업을 대신하지는 못하며**  
**표준이 없기 때문에 툴에 따라 생성물이 다르다.**  
  

마크다운태그의 가장 많이 사용되는 종류들은 다음과 같다.

![마크다운태그의 종류]({{site.baseurl}}/assets/images/md.PNG)  
  

![제목]({{site.baseurl}}/assets/images/제목.PNG)
# 제목1
## 제목2
### 제목3
#### 제목4  
  

![줄바꿈]({{site.baseurl}}/assets/images/줄바꿈.PNG)  
띄어쓰기 2번  
또는 <br/>  
  

![수평선]({{site.baseurl}}/assets/images/수평선.PNG)  
---
***
___
***  
  

![강조]({{site.baseurl}}/assets/images/글자강조.PNG)  
**굵은 글씨**
*이텔릭*  
_이탤릭_  
~~취소선~~  
<u>밑줄</u>  
ex) This is the **bold** text and this is the *italic* text and <u>let's</u> do ~~strikethrough~~  
  

![인용]({{site.baseurl}}/assets/images/인용문.PNG)  

> 인용문장  
>   > 중첩된 인용문  
>   >   > 중첩된 인용문 2  


![리스트]({{site.baseurl}}/assets/images/목록.PNG)  
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
        - 순서가 필요하지 않은 목록  

* 순서가 필요하지 않은 목록
    * 순서가 필요하지 않은 목록
        * 순서가 필요하지 않은 목록  

+ 순서가 필요하지 않은 목록
    + 순서가 필요하지 않은 목록
        + 순서가 필요하지 않은 목록  

- 순서가 필요하지 않은 목록
    * 순서가 필요하지 않은 목록
        + 순서가 필요하지 않은 목록
  

![리스트]({{site.baseurl}}/assets/images/목록1.PNG)  
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

1. 순서가 필요한 목록
    9. 순서가 필요한 목록
    3. 순서가 필요한 목록
8. 순서가 필요한 목록
  

![링크]({{site.baseurl}}/assets/images/링크2.PNG)  
Click [here](https://shimwoojun.github.io/)  
[심우준의 Devlog](https://shimwoojun.github.io/)  
  

![이미지]({{site.baseurl}}/assets/images/이미지.PNG)  
![Bare-Metal]({{site.baseurl}}/assets/images/BM.PNG)
  

![코드]({{site.baseurl}}/assets/images/코드1.PNG)  
```javascript
const name = "심우준"
const.log(name);
```  

`YEAR-MONTH-DAY-title.MARKUP`