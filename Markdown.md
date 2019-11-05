# 마크다운 사용법 
### 2019년 11월 5일

> Markdown?         

일반 텍스트 기반의 마크업언어로 README.md 파일이나 온라인 문서, 혹은 일반 텍스트 편집기로 문서 양식을 편집할 때 쉽게 쓰고 읽을 수 있으며 HTML로 변환이 가능하다.

# 헤더(Header)
'#' 기호로 제목 (h1~h6 태그)을 설정할 수 있다.
# h1  '#'
## h2  '##'
### h3  '###'
#### h4  '####'
##### h5  '#####'
###### h6  '######'


# 목록(Lists)
[Unordered]
* Item 1
* Item 2
    * Items a
    * Items b

[Ordered]
1. A 1
2. A 2
3. A 3
    1. B 1
    2. B 2

# 이미지(Images)

1. 형식 : ![이미지 alt명](url 링크)
2. 형식 : img태그 사용 - 이미지 경로는 상대 경로 or 절대 경로

# 하이퍼링크(Links)
형식 : [이름] (주소)

# 코드 블록(Code Blocks)  
해당 프로그래밍 언어와 구문 구별 표시를 적용한 코드를 볼 수 있습니다.
``` python
words = "Hello, CutyApple!"
print(f"{words}")
```
> '```Code```'

# 인용 상자(Blockquotes)
>'> blabla...'.   
>CutyApple!


# 강조(Emphasis)
*Italic*
_Italic_
**bold**
__bold__
> '*word* or _word_ => italic'   
>'**word** or __word__ => bold'

# 테이블(Tables)
  A  |  B  
-----|-----
cell1|cell2
 col1|col2
> 'Head1|Head2'  
> '-----|-----'   
> 'cell1|cell2'

# 체크 박스(Task Lists)
- [x] It is complete!     
- [ ] It isn't complete...     
- [X] Is CutyApple really Cute?   

> '- [x] blabla'
> '- [ ] bla'
> '- [X] blablabla'

# 인라인 코드()


### CutyApple