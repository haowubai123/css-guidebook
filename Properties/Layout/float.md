---
默认值: none
继承性: no
版本: CSS1
---

## `float`

`float` 属性用于定义元素向左或者向右浮动放置。请参阅 [`clear`](clear.md) 属性。[🔍详细文档](http://css.doyoe.com/properties/layout/float.htm)

```css
float: none | left | right
```

### 说明

浮动元素会生成一个块级框，而不论它本身是何种元素。

假如在一行之上只有极少的空间可供浮动元素，那么这个元素会跳至下一行，这个过程会持续到某一行拥有足够的空间为止。

- 如果 `float` 不是 `none`
  - 当 `display: inline-table` 时，`display` 的计算值为 `table`；
  - 当 `display: inline | inline-block | run-in | table-*` 系时，`display` 的计算值为 `block`
  - 其它情况为指定值
- 当一个元素是绝对定位元素或者定义了 `display` 为 `none` 时，`float` 定义不生效

**脚本特性**

对应的脚本特性为：

* 非 IE 浏览器：`cssFloat`
* IE8以下浏览器：`styleFloat`