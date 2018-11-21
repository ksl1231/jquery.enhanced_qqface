# jquery.qqface

jQuery QQ 表情插件。     
点击一个按钮，弹出一个选择QQ表情的组件，点击即可选择表情，以文字形式插入到textara里面，或者以图像形式插入到你想要的区域。

# 使用方法
1. 引入jQuery
2. 引入jquery.qqface.js

# 在html添加以下内容
```
<div>
    <textarea id="liveChatContent" spellcheck="false"></textarea>
</div>
<div id="emoji_area"></div>
<a href="javascript:;" id="face">表情</a>

```

# js
```js
//按照以下方法引入即可
$.qqface({
    imgPath: 'gif/',    // gif的文件路径
    handle: $('#face'),  // 表情包按钮
    textarea: $('#liveChatContent'),  // 以文字形式显示表情包的地方
    emoji_area: $('#emoji_area')  // 以图像形式显示表情包的地方
});


