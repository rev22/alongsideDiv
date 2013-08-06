alongsideDiv
============

```alongsideDiv``` is a flexible, responsive css layout, aimed at displaying multiple blocks of text in different columns, without enforcing a visual structure.


Usage
-----
```html
<div class=alongsideCnt>
  <div class=alongside>
    content (text and in-text content)
  </div>
  <div class=alongside>
    more content (text and in-text content)
  </div>
  ...and so on
</div>
```

The text centered horizontally, by default.

Source
------

Because of the minimalistic approach, alongsideDiv has a small source code that can be included here.

```css
.alongsideCnt {
  vertical-align:  top;
  text-align:      center;
}
.alongside {
  max-width:       25em;
  display:         inline-block;
  vertical-align:  top;
  padding:         1em;
  overflow:        hidden;
}
.alongside:hover {
  overflow: auto;
}
.alongside > * {
  vertical-align: baseline;
}
```

Authors and licensing
---------------------

© 2013 Michele Bini <michele.bini@gmail.com>

```alongsideDiv``` is released with a permissive MIT-style license.

