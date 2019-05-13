jquery.fullScreen.js
============

[![Greenkeeper badge](https://badges.greenkeeper.io/dyygtfx/jquery.fullScreen.js.svg)](https://greenkeeper.io/)

jquery全屏插件

### Usage

1. link jquery
2. demo
```html
<div class="mod">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur, veniam modi debitis sed officia beatae iure nam iusto eaque esse voluptatibus, accusamus eos mollitia at omnis asperiores adipisci incidunt autem!</p>
        <button id="btn"> 点我全屏 </button>
    </div>
```

```javascript
$(function () {
    if($.support.fullscreen){
        $('#btn').click(function(e){
            $('.mod').fullScreen();
        });
    }
})
```
