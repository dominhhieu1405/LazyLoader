# LazyLoader
Simple Lazy Loader in html
[Demo](https://git.k6vn.org/)

Download file "LaztLoader.js" and include in the `head` tag of your page.
```html
<script type="text/javascript" src="/path-to-file/LazyLoader.js"></script>
```
Orvia **CDN** and include in the `head` tag of your page.
```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/dominhhieu1405/LazyLoader@main/LazyLoader.js"></script>
```
In HTML, add an identifier to the element (default selector identified is `lozad` class):
```html
<img class="lazy" data-src="image.png" src="loading.gif">
```
