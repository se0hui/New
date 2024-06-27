# <span style = "color:blueviolet"> JSON(JavaScript Object Notation) </span>


- 데이터를 **저장** 또는 **교환**하기 위해 사용되는 텍스트 기반의 **DATA 교환 표준**
- JavaScript에서 객체를 만들 때 사용하는 표현식을 의미한다.
- JSON 표현식은 사람과 기계 모두 이해하기 쉽고 용량이 작다.
- JSON은 데이터 포맷일 뿐, 어떠한 통신 방법도, 프로그래밍 문법도 아닌 단순 데이터를 표시하는 표현 방법이다.

---

## <span style="background-color:#C0FFFF; color : black"> JSON 특징 </span>

- 서버와 클라이언트 간의 교류에서 일반적으로 많이 사용된다.
- 자바스크립트 객체 표기법과 유사하다.
- 자바스크립트를 이용하여 JSON 형식의 문서를 자바스크립트 객체로 쉽게 변환할 수 있다.
- JSON 문서 형식은 자바스크립트 객체의 형식을 기반으로 만들어졌다.
- 텍스트 기반이기 때문에 다양한 프로그램이 언어에서 데이터를 읽고 사용할 수 있다.

---



## <span style="background-color:#C0FFFF; color : black">XML & JSON</span>

데이터를 나타낼 수 있는 방식이 여러가지가 있지만, 대표적인 것은 XML이고, JSON 또한 많이 사용된다.

### XML
- 데이터 값 양쪽으로 태그가 있다.
(HTML을 근본으로 한 데이터 표현 형식)

### JSON
- 태그로 표현하기 보다는 중괄호 형식으로하고, 값을 ','로 나열하기 때문에 표현이 간단하다.
- JSON 형식은 key/value가 존재할 수 있으며 key 값이나 문자열은 쌍따옴표를 이용하여 표기해야한다.
- 객체, 배열 등의 표기를 사용할 수 있고, null, number, string, boolean을 사용할 수 있다.

---
## <span style="background-color:#C0FFFF; color : black">JSON 형식</span>
1. name-value 형식의 쌍
   1. 여러가지 언어들에서 object등으로 실현되었다
   2. {String key : String value}
2. 값들의 순서화된 리스트 형식
   1. 여러가지 언어들에서 배열 등으로 실현되었다.
   2. [value1, value2, ...]
    ### JSON의 기본 규칙
    JavaScript의 객체와 비슷해 보이지만, JavaScript의객체와는 다른 규칙이 있는데,
키, 문자열 값에 반드시 큰 따옴표를 붙여야 한다는 것이다.
또한 키와 값 사이의 공백이나 키-값 쌍 사이 공백 사용이 불가하다.

---

## <span style="background-color:#C0FFFF; color : black">JSON의 문제점</span>
AJAX는 단순히 데이터만이 아닌 JavaScript 그 자체도 전달 할 수 있기 때문에, 데이터인 줄 알고 받았지만 악성 스크립트가 될 수 있다는 단점이 있다.

이 때문에 받은 내용에서 순수하게 데이터만 추출하기 위한 JSON 라이브러리를 따로 사용하기도 한다.

---

## <span style="background-color:#C0FFFF; color : black">가져올 수 있는 데이터</span>
JSON이 가져올 수 있는 데이터는 해당 자바스크립트가 로드된 서버의 데이터에 한정된다.

