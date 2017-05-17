# Micro Flex

Micro CSS framework created over flexbox layout, with placeholders and HTML attributes

You can see examples in "examples" folder.

## Install

Bower
```
bower install --save micro-flex
```
NPM
```
npm install --save micro-flex
```

## Example with HTML Attributes

```html
<link rel="stylesheet" href="../../dist/micro-flex.min.css">

<main column align="space-around center">
  <h1>It's a </h1>
  <h2> example </h2>
  <h3>ussing Micro-Flex on HTML</h3>
</main>
```
## Example with Placeholders

```scss
@import '../../../src/placeholders';

...

main {
  min-height: 100vh;
  @extend %column;
  @extend %justify-space-around;
  @extend %align-center;
}
```
