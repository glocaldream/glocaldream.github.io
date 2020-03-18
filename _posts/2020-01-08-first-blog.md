---
layout: post
title: Mark Down에 대해서 알아볼까요?
tags: [MarkDown]
color: rgb(24, 139, 91)
author: hahyun
excerpt_separator: <!--more--> # <!--more--> 블로그 목록에서 해당하는 내용을 여기까지만 보여주겠다는 표시
---

오늘은 마크다운에 대해서 한번 알아볼건데요!  <br>
마크다운이라고 다들 들어보셨나요? 👀  <br>
모르셔도 괜찮습니다 ! 같이 알아보아요  <br>

<!--more-->

### MarkDown 이란?
> 일반 텍스트 문서의 양식을 편집하는 문법이다.  
README 파일이나 온라인 문서, 혹은 일반 텍스트 편집기로  
문서 양식을 편집할 때 쓰인다.   

----

### MarkDown의 장점과 단점

* 장점  
문법이 쉽다  <br>
관리가 쉽다  <br>
지원 가능한 플랫폼과 프로그램이 다양하다  <br>

<br>

* 단점 <br>  
표준이 없어 사용자마다 문법이 상이할 수 있다.  <br>
모든 HTML 마크업을 대신 하지 못한다.  <br>



### MarkDown 문법  
----
* **제목**  
```html
#
##
###
####
#####
```

순서대로 h1,h2,h3 ...입니다

<br>


* **강조**

```html
이텔릭체는 *별표(asterisks)* 혹은 _언더바(underscore)_를 사용하세요.  
두껍게는 **별표(asterisks)** 혹은 __언더바(underscore)__를 사용하세요.  
**_이텔릭체_와 두껍게**를 같이 사용할 수 있습니다.  
취소선은 ~~물결표시(tilde)~~를 사용하세요.  
<u>밑줄</u>은 `<u></u>`를 사용하세요.  
```
<br>

* **링크**  

```html
[GOOGLE]

[NAVER]

[GOOGLE]:https://google.com
[NAVER]:https://naver.com
```
<br>

* **코드강조**  

`를 3번 이상 입력하고 코드 종류도 적습니다.  

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

```python
s = "Python syntax highlighting"
print s
```
<br>

* **표(Table)**  

헤더 셀을 구분할 때 3개 이상의 -(hyphen/dash) 기호가 필요합니다.   <br>
헤더 셀을 구분하면서 :(Colons) 기호로 셀(열/칸) 안에 내용을 정렬할 수 있습니다.  <br>
가장 좌측과 가장 우측에 있는 |(vertical bar) 기호는 생략 가능합니다.  <br>

```html
| 값 | 의미 | 기본값 |
|----------|------------------------------|--------------|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 |  |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
| `fixed` | 브라우저 창을 기준으로 배치 |  |
```  

<br>

| 값 | 의미 | 기본값 |
|----------|------------------------------|--------------|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 |  |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
| `fixed` | 브라우저 창을 기준으로 배치 |  |  

이런식으로 결과가 나오게 됩니다!

<br>

* **인용문**  

``` html
인용문(blockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_

```

결과는 <br>


인용문(blockQuote)  

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> _(네이버 국어 사전)_  

<br>
자 이렇게 해서 markdown 사용법을 알아보았습니다! 😊<br>

생각보다 재미 있네요 ~! 다음번에도 더욱 재미있는 컨텐츠로 돌아오겠습니다  <br>
안녕   !<br>


