# 更多功能

## Javascript

关于电脑版的[警告](https://docs.ankiweb.net/templates/styling.html#javascript)同样适用于 AnkiMobile 。

除了上述之外，AnkiMobile 中另外一件需要注意的事情是，你的代码还需要与 AnkiMobile 的 Tap 很好地配合检测。点击 A/BUTTON 元素或具有 onclick 的元素处理程序应该按预期工作。

如果你有其他元素必须接收点击事件，请给它们 `tappable` 的类来告诉 AnkiMobile 2.0.39或更高的版本应该将按下的动作传递给它们。

## 播放按钮

如果需要修改音频重放按钮的样式，请查阅
<https://docs.ankiweb.net/templates/styling.html#audio-replay-buttons>

## 图像尺寸调整

当你从相册添加一张图片作为附件时，AnkiMobile 会自动等比例缩放，将它的较长边最大值调整到1024。
当前的 Anki 版本允许你自定义限制，以决定是否将此限制应用到粘贴板里的图片。**（偏好设置 > 通用）**
