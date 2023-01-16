  ### 블록 레벨 요소

혼자 한 줄을 차지하는 것.  ex) h1, div, p



### 인라인 레벨 요소

-한 줄을 차지하지 않음.

-콘텐츠 영역만 차지

-ex)span, img, strong



### 마진(margin)

주변의 여백 의미.

요소와 요소 사이의 간격을 조절

```html
#id{margin 50px;} 4개 마진 모두 50px
#id{margin 20px 50px;} 위 아래 30px, 좌우 마진 50px
#id{margin 20px 30px 50px;} 위 20px, 좌우 30px, 아래 50px
#id{margin 20px 50px 20px 50px} 위 아래 30px, 좌우 마진 50px
```



### 마진 중첩

요소가 세로로 배치될 때 마진이 서로 겹치게 되면 마진값이 큰 쪽으로 겹쳐짐



### 패딩(padding)

콘텐츠 영역과 테두리 사이의 공간,



지정하는 방법은 마진과 동일



### display 속성

블록 레벨 요소와 인라인 레벨 요소를 바꾸면서 사용이 가능

| block            | 인라인 레벨 요소를 블록 레벨로 만들어줌.                     |
| ---------------- | ------------------------------------------------------------ |
| **inline**       | **블록 레벨 요소를 인라인 레벨로 만들어줌.**                 |
| **inline-block** | **인라인과 블록 레벨 요소 속성 모두 가지며 마진과 패딩 지정 가능** |
| **none**         | **화면에 표시 X**                                            |

```html
display: inline-block;
```



### float 속성

블록 레벨 요소끼리 나란히 사용 X - float 속성이 해결해줌 

이미지 주변에 텍스트가 올 수 있음.

문서 위에 떠 있게 만들어줌

left, right, none 

**float 속성을 그만 사용하려면 clear 속성을 사용해줘야 함.**



### position 속성



웹 요소의 위치를 원하는 곳에 정함.

left, right, top, bottom : 각각 기준 위치와 요소 사이에 얼마나 떨어져 있는지 지정

***static*** -문서의 흐름에 맞춰 배치

***relative***  -위치값을 지정할 수 있다는 점을 제외하면 static과 동일

***absolute***-relative값을 사용한 상위 요소를 기준으로 위치를 지정해 배치

***fixed*** -브라우저 창을 기준으로 위치를 지정해 배치

```html
#static{position:static}
#relative{position:relative}
```

요소에 position:absolute 로 위치 지정하면 'position: relative'를 사용한 요소를 기준으로 위치 결정함
