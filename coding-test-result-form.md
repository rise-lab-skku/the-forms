<div style="display: flex; justify-content: center;">
<div style="margin-top: 2rem; margin-bottom: 10rem; width: 80%; 	min-width: 580px; max-width: 1050px;">

<div style="text-align:center;">
<div style="text-align:right;">
	<a href="https://github.com/rise-lab-skku/the-forms">(원본 양식 링크)</a>
</div>
<h1 style="font-weight: bold;">RISE LAB 코딩테스트 평가지</h1>
</div>

<div style="display:flex;">
<div style="flex:50%; padding-right:10px; border-right: 1px solid #dcdde1">

1. [효율적 사고](#효율적-사고)
2. [모듈화 능력](#모듈화-능력)
3. [안전한 코딩](#안전한-코딩)
4. [코딩 습관](#코딩-습관)

</div>
<div style="flex:50%; padding-right:10px;">

- 평가학생: 홍길동
- 지원목적: 2021년 1학기 입학
- 평가시기: 2020-08-21
- 평가자: OOO
- 평가자 결론: B+
  - 코딩테스트 점수는 75점으로 문제풀이는 무난하나, 전반적으로 코딩 습관 지도가 필요합니다.

</div>
</div>

<!-- @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@ -->
<div style="display: flex; justify-content: center; margin-top:1rem;">
<div style="border: 1px solid gray;">

| 구분        | 항목                                | 우수 | 양호 | 아쉬움 | 부정 |
| ----------- | ----------------------------------- | ---- | ---- | ------ | ---- |
| 효율적 사고 | 1. 반복 효율성                      |      | O    |        |      |
|             | 2. 계산 효율성                      |      |      | O      |      |
|             | 3. 올바른 변수 사용                 |      | O    |        |      |
| 모듈화 능력 | 1. 문제분해 능력                    | O    |      |        |      |
|             | 2. 추상화 능력                      |      |      | O      |      |
|             | 3. 중복방지                         |      | O    |        |      |
|             | 4. 객체지향 프로그래밍 친숙도       |      |      | O      |      |
| 안전한 코딩 | 1. 위험한 기능을 사용하진 않았는가? |      |      |        | O    |
|             | 2. Fool-proof 설계를 하였는가?      |      |      | O      |      |
| 코딩 습관   | 1. 코딩 스타일이 일관적인가?        |      |      |        | O    |
|             | 2. 가독성                           |      | O    |        |      |
|             | 3. 확장성을 염두한 코딩             |      | O    |        |      |

</div>
</div>
<!-- @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@ -->

<div style="text-align:center; font-weight: 900;">

## 효율적 사고

</div>

#### 1. 반복 효율성

<div style="margin-left: 4rem">

> 평가Tip: 가독성을 해치지 않는 범위에서 for문, while문, recursive func을 효율적으로 사용했는가?

</div>

#### 2. 계산 효율성

<div style="margin-left: 4rem">

- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

> 평가Tip: 사용하지 않을 요소를 제외하고 계산할 수 있는가? e.g. Transformation matrix에서 0으로 안쓰이는 부분을 제외하고 계산하는 것이 전체를 계산하는 것보다 효율적이다.

</div>

#### 3. 올바른 변수 사용

<div style="margin-left: 4rem">

- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

> 평가Tip: 자주 사용하는 데이터를 적절한 변수로 활용하였는가?

</div>

<!-- @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@ -->

<div style="text-align:center">

## 모듈화 능력

</div>

#### 1. 문제분해 능력

<div style="margin-left: 4rem">

- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

> 평가Tip: 큰 기능을 작은 함수로 나누려 했는가?

</div>

#### 2. 추상화 능력

<div style="margin-left: 4rem">

- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

> 평가Tip: 함수가 블랙박스 형태로 잘 추상화 되었나?

</div>

#### 3. 중복방지

<div style="margin-left: 4rem">

- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

> 평가Tip: 같은/비슷한 기능을 하는 중복 코드는 없는가?

</div>

#### 4. 객체지향 프로그래밍 친숙도

<div style="margin-left: 4rem">

- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

> 평가Tip: 함수나 Class를 "객체"를 기준으로 사용했는가?

</div>

<!-- @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@ -->

<div style="text-align:center">

## 안전한 코딩

</div>

#### 1. 위험한 함수나 메크로를 사용하진 않았는가?

<div style="margin-left: 4rem">

- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

> 평가Tip: e.g. Python의 `exec` 함수

</div>

#### 2. Fool-proof 설계를 하였는가?

<div style="margin-left: 4rem">

- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

> 평가Tip: 예상 가능한 실수나 에러를 예방 또는 헨들링하는 코드. Magic-number를 쓰지 않고, 변수를 적절히 생성하여 사용했나?

</div>

<!-- @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@ -->

<div style="text-align:center">

## 코딩 습관

</div>

#### 1. 코딩 스타일이 일관적인가?

<div style="margin-left: 4rem">

- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

> 평가Tip: i.e. Class이름이 대문자로 시작하게 썼다면 항상 대문자로 썼는가? 다른 것도 마찬가지로 일관성을 잘 지켰는가?

</div>

#### 2. 가독성

<div style="margin-left: 4rem">

- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

> 평가Tip: 코드를 쉽게 읽을 수 있고, 코드만 읽고 이해할 수 있는가, 다른 사람을 잘 배려하였는가, 간결한가?

</div>

#### 3. 확장성을 염두한 코딩

<div style="margin-left: 4rem">

- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

> 평가Tip: 기본 요소들로 구분된 기능, 사용빈도가 높은 옵션을 미리 구현해두었는가?

</div>

</div>
</div>
