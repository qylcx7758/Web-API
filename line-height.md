## line-height的研究

参考资料:
[MDN-lineHeight](https://developer.mozilla.org/zh-CN/docs/Web/CSS/line-height)

一、定义
> line-height CSS 属性用于设置多行元素的空间量，如多行文本的间距。对于块级元素，它指定元素行盒（line boxes）的最小高度。对于非替代的 inline 元素，它用于计算行盒（line box）的高度。

二、属性值
1. 可以选择`normal`，`数字、长度、百分比`
1. `normal`：具体行高取决于用户端。桌面浏览器（包括Firefox）使用默认值，约为1.2，不同浏览器不同，不过具体取决于元素的 font-family。


二、应用
1. 多方浏览器测试，包括ie11、edge、安卓部分手机浏览器，当`line-height:1`与`line-height:100%`是一致的，即行高为字体高度；
2. 如果该元素不设置大小，则行高默认为`line-height:normal`，该属性不显示在控制台（主要在Chrome下测试）;

四、使用建议
1. 推荐在设置 line-height 时使用无单位数值（比如百分比，1）；
2. 主段落内容的 line-height 至少应为 1.5。 这将有助于改善低可视条件下的体验，也对认知阻碍者，如阅读困难者，有帮助。如果文字的大小要随页面的缩放而变化，请使用无单位的值，以确保行高也会等比例缩放。

