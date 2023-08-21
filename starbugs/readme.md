# HTML 클래스 속성의 작명법

BEM(Block Element Modifier)

- 요소\_\_일부분 Underscore(Lodash) 기호로 요소의 일부분을 표시
  .container > .container\_\_name + item > item\_\_name

  ```html
  <div class="item__contents">
    <div class="contents__menu"></div>
    <div class="contents__texture">
      <div class="inner">
        <h4>나와 어울리는 커피 찾기</h4>
        <p>스타벅스가 여러분에게 어울리는 커피를 찾아드립니다.</p>
        <h4>최상의 커피를 즐기는 법</h4>
        <p>여러가지 방법을 통해 다양한 풍미의 커피를 즐겨보세요.</p>
      </div>
    </div>
  </div>
  ```

- 요소-상태 Hyphen(Dash) 기호로 요소의 상태를 표시
  .btn--primary + .btn--success + .btn--error

```html
<button class="btn btn--primary"></button>
<button class="btn btn--success"></button>
<button class="btn btn--error"></button>
```
