# \<full-width-text\>

Makes the inner text fit the width of the element

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="full-width-text.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<style>
  .demo * {
    text-transform: uppercase;
    line-height: 0.85em;
    font-weight: 500;
  }
</style>
<div class="demo">
  <full-width-text>Lorem ipsum</full-width-text>
  <full-width-text>dolor</full-width-text>
  <full-width-text>sit amet</full-width-text>
</div>
```

## Demo

[https://pomber.github.io/full-width-text/](https://pomber.github.io/full-width-text/)


## Install

Install the component using Bower:
```
$ bower install full-width-text --save
```

## Usage

1. Import web components' polyfill (if needed):
```html
<script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
```
2. Import element:
```html
<link rel="import" href="bower_components/full-width-text/full-width-text.html">
```
3. Use it:
```html
<full-width-text>Lorem Ipsum</full-width-text>
```