## Capturing & Bubbling

![inline](./images/eventphases.png)

- 버블링이 일어나는 이벤트도 있고, 일어나지 않는 이벤트도 있음 (submit, focus, blur, change 등)

<!--
참고 링크
- https://stackoverflow.com/questions/5574207/html-dom-which-events-do-not-bubble
- https://www.quirksmode.org/js/events_order.html
-->

---

## Event Object

- `e.target`
- `e.currentTarget`
- `e.stopPropagation()`
- `e.preventDefault()`

---

## 폼 이벤트

- change
- input
- focus
- blur
- submit

<!-- https://httpbin.org/ -->

---

## 마우스 이벤트

- click / dblclick
- mouseover / mouseout
- mousedown / mouseup
- mousemove

---

## 키보드 이벤트

- keydown
- keyup

---

## 스크롤 이벤트

- scroll
