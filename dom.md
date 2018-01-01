## API

Application Programming Interface.

즉 어플리케이션을 프로그래밍할 수 있는 **접점**

---

[Web APIs](https://developer.mozilla.org/en-US/docs/Web/API)

---

## DOM API

- Document Object Model, 문서 객체 모델
- HTML, XML 문서를 프로그래밍하는 인터페이스
- JavaScript에만 있는 것이 아님
- 웹 브라우저에서는 DOM API를 기반으로 여러 부가 기능을 사용할 수 있음
- [MDN DOM](https://developer.mozilla.org/ko/docs/DOM)
- [트리](https://javascript-fds.netlify.com/pages/282-data-structures#트리-tree)

---

## 노드 선택

- `document.querySelector`
- `document.querySelectorAll`
- `el.querySelector`
- `el.closest`
- `el.matches`

<!-- NodeList -->

---

## 엘리먼트 내용 조작하기

- `el.textContent`
- `el.innerHTML`

<!-- innerHTML과 XSS -->

---

## 엘리먼트 어트리뷰트 조작하기

- `el.hasAttribute`
- `el.getAttribute`
- `el.setAttribute`
- `el.removeAttribute`

---

## classList

- `el.classList.add`
- `el.classList.remove`
- `el.classList.contains`

---

## 인라인 스타일

- `el.style`

---

## 이벤트 리스너

- `el.addEventListener`
- `el.removeEventListener`

---

## DOM 노드 생성

- `document.createElement`
- `document.createTextNode`
- `el.cloneNode`

---

## DOM 트리 조작

- `el.appendChild`
- `el.insertBefore`
- `el.replaceChild`
- `el.removeChild`

<!-- appendChild, insertBefore를 통한 위치의 이동 -->

---

## dataset

- `el.dataset`

---

## 노드 간 관계

- `el.childNodes`
- `el.firstChild`
- `el.lastChild`
- `el.previousSibling`
- `el.nextSibling`
- `el.parentNode`
- `el.offsetParent`

---

## 엘리먼트 크기 및 위치

- `el.getBoundingClientRect()`
- `el.offsetHeight` / `el.offsetWidth`
- `el.clientHeight` / `el.clientWidth`
- `el.scrollHeight` / `el.scrollWidth`
- `el.offsetTop` / `el.offsetLeft`
- `el.scrollTop` / `el.scrollLeft`
- `el.clientTop` / `el.clientLeft`
