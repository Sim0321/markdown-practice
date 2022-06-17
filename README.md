# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려강산<br>
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

물결은 영어로 틸드, *은 애스터리스크  
_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>  밑줄은 마크다운에서 지원을 해주지 않아 u태그로 대체  


# 목록(List)
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록  
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)
html 문법으론
<a href="https://google.com">GOOGLE</a>  
마크다운 문법으론
[GOOGLE](https://google.com)  

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>  
[NAVER](https://naver.com "NAVER로 이동!")

마크다운은 target 속성을 지원하지 않음

# 이미지(Images)
![대체 텍스트] (경로)  
![HEROPY](https://heropy.blog/css/images/logo.png)

이미지태그 안에 링크를 걸려면
![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog)  


# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는  
 간접으로 따온 문장.  
> (네이버국어사전)

중첩기능  
> 인용문을 작성하세요!
>>중첩된 인용문
>>> 중첩된 인용문 1  
>>> 중첩된 인용문 2  
>>> 중첩된 인용문 3  

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경이미지를 삽입할 수 있습니다.

# 블록(Block) 코드 강조


```html
<a href="https://www.google.co.kr" target ="_blank">GOOGLE</a>
```
```css
.list > li {
  position:absolute;
  top:40px;
}
```
```javascript
function func(){
  let a = 'AAA';
  return a;
}
```
```bash
$ git commit -m 'study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성

값 | 의미 | 기본값
--|--|--
static | 기준없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X 


값 | 의미 | 기본값
--|:--:|--:
static | 기준없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X 

# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br>
하느님이 보우하사 우리나라 만세

<a href="https://naver.com" title ="NAVER로 이동" target="_blank">NAVER</a>

---

<img width="70" src ="https://heropy.blog/css/images/logo.png" alt ="HEROPY">  

# 수평선(Horizontal Rule)

---

***

___





