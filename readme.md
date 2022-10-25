> This is a JavaScript practice with [JavaScript30](https://javascript30.com/) by [Wes Bos](https://github.com/wesbos) without any frameworks, no compilers, no boilerplate, and no libraries.

# JavaScript30

Starter Files + Completed solutions for the JavaScript 30 Day Challenge.

## Logs

---

### Day 1 : Javascript Drum Kit [Demo](#)

What I Learned:

- `audio.currentTime = 0` 를 통해 오디오 시간 지연 현상을 해결합니다.  
  [참조 - currentTime](https://developer.mozilla.org/en-US/docs/Web/API/HTMLMediaElement/currentTime)

- querySelector에서 요소의 특정 attribute - value를 갖고 있는 요소를 찾을수 있습니다.  
  [참조 - Element.querySelector()](https://developer.mozilla.org/en-US/docs/Web/API/Element/querySelector)

```js
const item = document.querySelector("element[attribute = value]");

const key = document.querySelector(`div[data-key="${event.keyCode}"]`);
const audio = document.querySelector(`audio[data-key="${event.keyCode}"]`);
```

- `transitionend`은 transition이 완료 되면 발생하는 이벤트다.
