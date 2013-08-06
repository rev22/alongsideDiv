alongsideDiv
============

```alongsideDiv``` is a flexible, responsive css layout, aimed at displaying multiple blocks of text without enforcing a visual structure.


Usage
-----
```html
<div class=alongsideCnt>
  <div class=alongside>
    content (text, images)
  </div>
  <div class=alognside>
    more content (text, images)
  </div>
  ...and so on
</div>
```

Source
------

Because of the minimalistic approach, alongsideDiv has a small source code that can be included here.

```css
.alongsideCnt {
  vertical-align: top;
  text-align: center;
  clear:none;
  position:relative;
  display:inline-box;
}
.alongside {
  max-width:25em;
  display:inline-block;
  vertical-align:top;
  padding:1em;
  overflow:hidden;
}
.alongside:hover {
  overflow: auto;
}
.alongside > * {
  vertical-align:baseline;
}
```

Authors and licensing
---------------------

© 2013 Michele Bini

```alongsideDiv``` is released with a permissive MIT-style license.



