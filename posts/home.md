## Hello world!

Blog này được sử dụng cho mục đích kiểm thử AzerothJS cho việc viết blog thường xuyên. Mọi bài blog sẽ được cập nhật ở `lvnam96.github.io` trước khi dần chuyển sang sử dụng hoàn toàn blog này.

![](./img/azeroth_screenshot.png)

## Azeroth có thật sự tốt?

- Được viết trên nền JS nên rất nhẹ
- Không cần cài đặt hơi phức tạp như Jekyll
- Dễ dàng tuỳ chỉnh giao diện

## Mã nguồn AzerothJS

Của huytd (the full snack developer) [Github](http://github.com/huytd/azeroth-js)

## Cách sử dụng đâu?

Ở trang mã nguồn

## Tuỳ chỉnh như nào mà bảo dễ?

### Change code highlighting theme
The original theme for the code highlighting is `Tomorrow Night`. If you don't like it, there are many pre-installed themes inside `css/highlight` folder. Pick one and replace to `line 6` of `index.html`:

```
<link rel="stylesheet" href="./css/highlight/tomorrow-night.css">
```

### Change the font family
The original font for the blog is `Roboto Slab`. You can change the new font by replacing `line 4` of `index.html`:

```
<link href='https://fonts.googleapis.com/css?family=Roboto+Slab:400,300&subset=latin,vietnamese' rel='stylesheet' type='text/css'>
```

And change the font in `css/theme.css`:

```
* {
    font-family: 'Roboto Slab', serif;
    font-size: 20px;
    font-weight: 100;
}
```

### Insert your Social links
There are some social icon links in `footer`, put your own one by edit the `index.html`:

```
<div class="footer">
    <p>Created with <a href="http://github.com/huytd/azeroth-js">azeroth.js</a></p>
    <div class="social">
        <a href="#"><i class="icon-facebook-squared"></i></a>
        <a href="#"><i class="icon-twitter-squared"></i></a>
        <a href="#"><i class="icon-linkedin-squared"></i></a>
        <a href="#"><i class="icon-github-squared"></i></a>
        <a href="#"><i class="icon-mail-alt"></i></a>
    </div>
</div>
```

## Want to read more about Markdown?

- [Markdown Test Page](#lorem-ipsum)
