# Grido

Grido is a flexbox grid developed between Star Wars Rebels and A New Hope (Han shot first!)

## Installation

```sh
// with npm
npm install grido

// with yarn
yarn add grido
```

## Usage

```js
// [file].js
import 'grido'
```

```html
<!-- [file].html -->
<div class="grido"> <!-- creates a container with flexbox -->
  <div class="g__col--1"> <!-- creates a column -->
  </div>
  <div class="g__col--5">
  </div>
  <div class="g__col--12"><!-- Grido supports 12 columns max -->
  </div>
  ...
</div>
```

[![Edit Grido](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/grido-mfyfv?fontsize=14&hidenavigation=1&theme=dark&view=preview)

### Reverse order

```html
<div class="grido g--reverse">
  ...
</div>
```

### Vertical

```html
<div class="grido g--vertical">
  ...
</div>
```

### Vertical and reverse

```html
<div class="grido g--vertical g--reverse">
  ...
</div>
```

### No wrap

```html
<div class="grido g--nowrap">
  ...
</div>
```

### Wrap reverse

```html
<div class="grido g--wrap-reverse">
  ...
</div>
```

### Changed order

```html
<div class="grido">
  <div class="g__col--2 g__order--5">
  </div>
  <div class="g__col--2 g__order--3">
  </div>
  <div class="g__col--2 g__order--1">
  </div>
  <div class="g__col--2">
  </div>
  <div class="g__col--2 g__order--2">
  </div>
</div>
```

### Align-self

```html
<div class="grido">
  <div class="g__col--4">
  </div>
  <div class="g__col--4 g--align-self-end">
  </div>
  <div class="g__col--4 g--align-self-center">
  </div>
</div>
```

## License

This project is licensed under the terms of [the MIT license](https://github.com/vilaboim/grido/blob/master/LICENSE).
