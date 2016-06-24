JavaScript Hand-Written Templates
---

## Objectives

1. Work with the web as strings
2. Modularize changes to the DOM on a larger scale
3. Encapsulate changes to the DOM as functions

## Introduction

- We can tie this lab directly to updating the DOM
- Draw parallels between encapsulating code in functions and encapsulating DOM behavior in the same
- This is also analogous to having students write their own ORM in Ruby before introducing ActiveRecord

## Implementation

- Start by having students manually insert a <div> into the provided index.html
- Have them update its contents manually
- Have them insert child nodes
- Show them how to insert new nodes by setting innerHTML with a string, e.g.:

``` javascript
var main = document.getElementsByTagName('main')[0]
main.innerHTML = '<div>Hi<p>I'm on a new line!</p></div><div>This is hard to keep track of</div><div>Students <div>should <div>feel <div>the <div> pain.</div></div></div></div></div>'
```

- Finally, encapsulate this functionality in a few functions (e.g., `createDiv()`, `insertTextAsHTML()`, etc.)

## Resources

- [MDN: innerHTML](https://developer.mozilla.org/en-US/docs/Web/API/Element/innerHTML)
