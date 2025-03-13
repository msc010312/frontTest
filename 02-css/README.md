# CSS 내용 정리

## CSS
+ Cascading Stlye Sheets의 약자로 상위선택자로부터 상속을 받는 스타일 시트라는 뜻
+ 마크업언어로 이루어진 문서를 표현하기위한 스타일시트 언어

## CSS의 기본 구조
+ 선택자: 스타일을 적용할 HTML 요소를 지정합니다
+ 속성: 스타일을 지정할 항목(예: color, font-size, margin 등)
+ 값: 해당 속성에 대한 구체적인 스타일 값
```
선택자 {
  속성 : 값
}
```

## 선택자의 종류
+ 태그 선택자 : 특정 태그에 스타일 적용
+ 클래스 선택자 : 선언된 클래스를 가진 요소에 스타일 적용
+ 아이디 선택자 : 선언된 아이디를 가진 요소에 스타일 적용
+ 속성 선택자 : 특정 속성을 가진 요소에 스타일 적용
+ 가상 선택자 : 실제론 존재하지않지만 가상의 영역을 만들어 스타일 적용
+ 자식 선택자 : 특정 요소의 직계 자식 요소에 스타일을 적용
+ 후손 선택자 : 특정 요소의 모든 후손 요소에 스타일을 적용
```
div { // 태그선택자
 display : block;
}

.class { // 클래스 선택자
  display : block;
}

#id { // 아이디 선택자
  display : block;
}

input[type=text] { // 속성 선택자
  display : block;
}

.virtural:hover { // 가상 선택자
  display : block
}

.parents>.child { // 자식선택자
  display : block
}

div span { // 후손 선택자
  display : blcok
}

```
