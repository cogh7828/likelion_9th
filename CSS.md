## CSS

---

### CSS 기초 문법

```
p{
  font-family: '맑은 고딕';
  font-size: 18px;
  color: blue;
}
```

- 선택자(Selector)

  스타일을 적용하고자 하는 HTML 요소를 선택하는 역활 따라서 반드시 HTML과 함께 쓰여야함

- 속성(Property)

  지정할 스타일의 속성명에 해당 속성: 값; 이 한 단위(;) 을 이용하여 구분

- 값(Value)

  키워드나 특정 단위를 이용하여 원하는 스타일을 적 속성(Proprty)와 쌍을 이룸

- 선언 블럭(Declaration block)

  { Declartion; Declaration; ...}

---

### HTML에 CSS를 적용시키는 방법

- Link style

  HTML에 외부에 있는 CSS파일을 불러옴

```
<link rel="stylesheet" href="test.css">
```

- Enbedding style

  HTML의 에 <style>를 이용하여 CSS를 작성

```
<style>
  h1 {color: red;}
</style>
```

- Inline style

  HTML요소에서 attribute를 이용해 CSS작성 

```
<h1 style="color : red;">123</h1>
```