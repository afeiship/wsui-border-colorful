# wsui-border-colorful
> Colorful border for wsui.

[![version][version-image]][version-url]
[![license][license-image]][license-url]
[![size][size-image]][size-url]
[![download][download-image]][download-url]

## installation
```shell
npm i @jswork/wsui-border-colorful
```

## usage
```scss
// use sass
@import '~@jswork/wsui-border-colorful/dist/index.scss';
// use css
@import '~@jswork/wsui-border-colorful/dist/style.css';


.box {
  width: 80%;
  margin: 50px auto;
  max-width: 400px;
  @include wsui-border-colorful();

  > .is-body {
    padding: 10px;
  }
}
```

```html
<div class="box">
  <div class="is-body">
    <figure>
      <center><img src="https://tva1.sinaimg.cn/large/007S8ZIlgy1gexw87htqhj305k05k74o.jpg" alt=""></center>
    </figure>
    <p>道可道，非常道；名可名，非常名。</p>
    <p>无名，天地之始，有名，万物之母。</p>
    <p>故常无欲，以观其妙，常有欲，以观其徼。</p>
    <p>此两者，同出而异名，同谓之玄，玄之又玄，众妙之门。</p>
  </div>
</div>
```

## resources
- https://afeiship.github.io/wsui-border-colorful/
- https://css-tricks.com/everything-you-need-to-know-about-date-in-javascript/

## license
Code released under [the MIT license](https://github.com/afeiship/wsui-border-colorful/blob/master/LICENSE.txt).

[version-image]: https://img.shields.io/npm/v/@jswork/wsui-border-colorful
[version-url]: https://npmjs.org/package/@jswork/wsui-border-colorful

[license-image]: https://img.shields.io/npm/l/@jswork/wsui-border-colorful
[license-url]: https://github.com/afeiship/wsui-border-colorful/blob/master/LICENSE.txt

[size-image]: https://img.shields.io/bundlephobia/minzip/@jswork/wsui-border-colorful
[size-url]: https://github.com/afeiship/wsui-border-colorful/blob/master/dist/wsui-border-colorful.min.js

[download-image]: https://img.shields.io/npm/dm/@jswork/wsui-border-colorful
[download-url]: https://www.npmjs.com/package/@jswork/wsui-border-colorful

