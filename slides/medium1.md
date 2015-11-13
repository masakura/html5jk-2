## ソースマップ
 * CSS の代わりに [Sass](http://sass-lang.com/) が使うことが多い

```scss
$blue: blue; /* 変数 */

.btn-primary {
  background-color: $blue;
}

.header-primary {
  background-color: $blue;
}
```

これをコンパイルするとこんな CSS が生成される。

```css
.btn-primary {
  background-color: blue; }

.header-primary {
  background-color: blue; }
```
