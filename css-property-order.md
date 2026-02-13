# CSS 속성 정렬 규칙

CSS 속성을 작성할 때 아래 순서를 따릅니다.

## 1. Position 관련 속성

위치와 관련된 속성을 가장 먼저 작성합니다.

- `position`
- `top`, `right`, `bottom`, `left`, `inset`
- `z-index`
- `transform`

## 2. Display 관련 속성

레이아웃과 관련된 속성을 두 번째로 작성합니다.

- `display`
- `flex-direction`, `flex-wrap`, `flex`, `flex-shrink`, `flex-grow`
- `justify-content`, `align-items`, `align-self`
- `gap`
- `order`

## 3. 나머지 속성

나머지 속성을 작성하되, `width`와 `height`를 가장 먼저 작성합니다.

- `width`, `min-width`, `max-width`
- `height`, `min-height`, `max-height`
- `margin`
- `padding`
- `border`, `border-radius`
- `background`
- `color`
- `font-family`, `font-size`, `font-weight`, `font-style`
- `line-height`
- `text-align`, `text-decoration`, `text-shadow`
- `box-shadow`
- `overflow`
- `object-fit`
- `cursor`
- `pointer-events`
- 기타

## 예시

```css
.example {
  position: absolute;
  left: 50%;
  top: 0;
  z-index: 2;
  transform: translateX(-50%);
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 20px;
  width: 300px;
  height: 200px;
  margin: 0 auto;
  padding: 16px;
  border-radius: 8px;
  background: #041018;
  color: #ffffff;
  font-family: "Pretendard", sans-serif;
  font-size: 16px;
}
```
