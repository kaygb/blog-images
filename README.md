# blog-images
静态图片
## 烟花点击效果
https://cdn.jsdelivr.net/gh/kaygb/blog-images/fireworks.js
### 同步加载
~~~html
<script src="//cdn.jsdelivr.net/gh/kaygb/blog-images/fireworks.js"></script>
~~~
### JS监听加载
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
