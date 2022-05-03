---
title: "Frosted Glass Effect"
---

> The **`backdrop-filter`** [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) property lets you apply graphical effects such as blurring or color shifting to the area behind an element. Because it applies to everything _behind_ the element, to see the effect you must make the element or its background at least partially transparent.

```css
.card {
	border-radius: 8px;
	backdrop-filter: blur(20px);
	background-color: rgba(255, 255, 255, 0.5);
	box-shadow: 0 1px 12px rgba(0, 0, 0, 0.25);
	border: 1px solid rgba(255, 255, 255, 0.3)
}
```
Not [supported](https://caniuse.com/css-backdrop-filter) by Firefox yet.

Resources:
- [Frosted Glass Effect](https://twitter.com/steve8708/status/1515413842657832964?s=12&t=ZiHk2lELIRqRYBrB9VDmsQ)
- [MDN: backdrop-filter](https://developer.mozilla.org/en-US/docs/Web/CSS/backdrop-filter)
- [CSS Tricks: backdrop-filter](https://css-tricks.com/almanac/properties/b/backdrop-filter/)
- [Can I Use: backdrop-filter](https://caniuse.com/css-backdrop-filter)