# 夜间模式样式

通过编辑卡片模板的操作，可以自定义当夜间模式/深色模式启用时卡片呈现的样子。

如果你想要一个灰色的背景而不是黑色，可以使用类似如下的代码：

```css
.card.nightMode {
  background-color: #555;
}
```

如果你有一个 `myclass` 样式类，通过以下示例代码可以在启用夜间模式时将文本显示为黄色：

```css
.nightMode .myclass {
  color: yellow;
}
```
