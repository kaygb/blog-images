# blog-images
img文件夹内是博客的静态图片，别的JS引用在下面
## 烟花点击效果
代码来源：https://www.onesrc.cn/p/add-a-fireworks-click-effect-to-your-website.html
https://cdn.jsdelivr.net/gh/kaygb/blog-images/fireworks.js
### 同步加载
~~~html
<script src="//cdn.jsdelivr.net/gh/kaygb/blog-images/fireworks.js"></script>
~~~
### JS监听加载（测试）
~~~html
<script>
window.onload = function() {
        setTimeout(function() {
                let script = document.createElement("script");
                script.src = "//cdn.jsdelivr.net/gh/kaygb/blog-images/fireworks.js";
                document.body.appendChild(script);
        }, 2e3);
}
</script>
~~~
