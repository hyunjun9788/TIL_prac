# CSS 기본



- ###  CSS 기본 선택자

1. 전체 선택자 : 문서의 모든 요소에 스타일을 적용 **'*{}'**

2. 타입 선택자 : 특정 태그를 사용한 모든 요소에서 스타일을 적용 **p{}**

3. 클래스 선택자 : 특정 부분만 선택해서 문서 안에 여러 번 적용, **마침표(.) 사용**

4. id 선택자 : 특정 부분만 선택해서 문서 안에서 한 번만 적용, **#사용**

5. 그룹 선택자 : 여러 요소에 같은 스타일을 적용할 때 사용, **h1,h2{}**  

   



- ### 스타일 우선순위

1. ​	사용자 스타일 → 제작자 스타일 →브라우저 기본 스타일 (비교했을 때 동일하면 적용범위를 살펴봄)

2. !important → 인라인 스타일 → id 스타일 → 클래스 스타일 → 타입 스타일 

3. 나중에 작성한 스타일이 먼저 작성한 스타일을 덮어씀  

   

​	

- ### 글자속성

1. 글꼴 지정: 태그{font-family: "맑은 고딕"}

	2. 글자 크기 지정: font-size ( 단위: em, rem,ex,px,pt)
	2. 글자를 이탤릭체로 표시할지 지정 : font-style:italic
	2. 글자의 굵기 : font-weight  





- ### 텍스트 스타일 속성

1. 글자색 : color
2. 텍스트 밑줄 및 취소선- text-decoration:underline, overline, linethrough
3. 텍스트 대소문자 - text-transform: capitalize(첫 번째 글자를 대문자로),uppercase
4. 텍스트 정렬 : text-align: center, right, justify, left ,,,
5. 줄 간격: text-height:2.5 (글자 크기의 2.5배)
6. 그림자 - text-shadow: 가로, 세로, 번짐, 색상
7. 글자 사이 간격 : letter-spacing:0.5em  





- ### 목록 스타일

1. list-style-type:upper-alpha;  (알파벳 대분자 목록)
2. list-style-position:inside(들여쓰기)  





- ### 표 스타일 

1. 셀 사이의 여백 - border-spacing: 수평거리 수직거리
2. 표와 셀 테두리 합치기- border-collapse:collapse  

