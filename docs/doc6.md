---
id: doc6
title: This is Doc 6
---

I can write content using [GitHub-flavored Markdown syntax](https://github.github.com/gfm/).

## Markdown Syntax

**Bold** _italic_ `code` [Links](#url)

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

- Hey
- Ho
- Let's Go

## Here some javascript for you:

```js
const hello = 'hello world';
```

## Here some php for you:

```php
function hello() {
  return 'Hello World'
}
```

## Does jsx work?

```jsx
const React = require('react');

const CompLibrary = require('../../core/CompLibrary.js');

const Container = CompLibrary.Container;
const GridBlock = CompLibrary.GridBlock;

function HelloWorld(props) {
  return (
    <div className="docMainWrapper wrapper">
      <Container className="mainContainer documentContainer postContainer">
        <h1>Hello World!</h1>
        <p>This is my first page!</p>
      </Container>
    </div>
  );
}

module.exports = HelloWorld;
```
