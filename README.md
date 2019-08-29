# <center>Web开发</center>

> web的概念就是门户网站，web工程师开发网页与后台，使网站能够被用户访问。
>
> web开发正是我在努力成就的，web工程师需要掌握的技能有前端三板斧，html、css、js，以及一些封装好的框架，后台需要一门编程语言，常用的有Java\php\node等。还有一些如数据库，linux系统之类的技术也需要掌握。



## 一、前端技能

### 1、html/css/js

三门语言中html用来展示数据，css用来改变样式，js使页面与用户交互起来。  

相对而言，js或许比较重要，薪酬水平也受js水平影响较大。当然js有许多框架和库可以调用，使我们开发更加简单了。

### 2、框架与库

目前比较流行的框架有react,vue等，库有jquery等。

如vue的一个demo.

```html
<div id="One">
    <h1>{{username}}</h1>
    <label>
        <input type="text" v-model="other">
        {{other}}
    </label>
    <br>
    <h1 v-text="userage"></h1>
</div>
<script>
    var Data={name:"Tom",age:18,"gender":"female"};
    new Vue({
        el:"#One",
        data:{
          username:Data.name,
          userage:Data.age,
          usersex:Data.gender,
          other:"Yes 1"
        },
        method:{
            shows:function () {
                alert(Data.gender)
            }
        }
    })
</script>

```

### 3、规范和工具

1. 前端规范非常多，浏览器支持也有兼容性问题，学习太多规范显然是浪费，现在主流浏览器都支持ESMAScript规范。
2. 前端的一些工具可以帮助开发，如npm包管理工具，webpack打包工具



![](https://ss.csdn.net/p?https://mmbiz.qpic.cn/mmbiz_jpg/Pn4Sm0RsAujibm5pV7xAlozo1fslfZEkict9fFKJONGNfZfwtgjStMCYZpmw6baMM8hb7DbJvexuxBpMKvB7wxPA/640?wx_fmt=jpeg)

<a href="https://cgl-dong.github.io/Spring/SSM.html">SSM整合</a>
<a href="https://cgl-dong.github.io/Vue/bind-class.html">Vue绑定class</a>
