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

## Placeholders

  - %flex
  - %row
  - %column
  - %wrap
  - %align-start
  - %align-center
  - %align-end
  - %justify-space-between
  - %justify-space-around
  - %justify-end
  - %justify-center

## HTML Attributes

  - [flex]

  - [column]

  - [row]

  - [wrap]

  - [align="center"], [align="center center"], [align="center start"], [align="center end"]

  - [align="end"], [align="end center"], [align="end start"], [align="end end"]

  - [align="space-around"], [align="space-around center"], [align="space-around start"], [align="space-around end"]

  - [align="space-between"], [align="space-between center"], [align="space-between start"], [align="space-between end"]

  - [align="center center"], [align="start center"], [align="end center"], [align="space-between center"], [align="space-around center"]

  - [align="center start"], [align="start start"], [align="end start"], [align="space-between start"], [align="space-around start"]

  - [align="center end"], [align="start end"], [align="end end"], [align="space-between end"], [align="space-around end"]
