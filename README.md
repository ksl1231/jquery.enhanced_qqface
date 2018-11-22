# jquery.enhanced_qqface

基于jQuery的QQ表情包插件加强版。     
点击弹出选择组件，即可选择QQ表情，以文字形式插入到textara，或者以图像形式插入到你想要的地方。

# 使用方法
1. 引入jQuery
2. 引入jquery.enhanced_qqface.min.js
2. 引入jquery.enhanced_qqface.css

# 在html添加以下内容
```
<div>
    <textarea id="liveChatContent" spellcheck="false"></textarea>
</div>
<div contenteditable="true" id="emoji_area"></div>
<a href="javascript:;" id="face">表情</a>

```

# js
```js
//按照以下方法引入即可
$.qqface({
    imgPath: 'gif/',    // gif的文件路径（绝对路径）
    handle: $('#face'),  // 表情包弹出按钮
    textarea: $('#liveChatContent'),  // 以文字形式显示表情包的地方
    emoji_area: $('#emoji_area')  // 以图像形式显示表情包的地方
});


