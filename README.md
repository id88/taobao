# 仿淘宝首页

## 效果预览
<img src="./images/taobao.png"/>

## 说明
- 目前只做了淘宝首页的一屏，没有继续做下去的原因有两个：第一，做完第一屏，发现基础还不够牢固。第二，下半部分如果还是只做静态的话基本就是简单的图片堆砌，继续做意义不大。
- 全静态效果，因为没有写js。

## 感悟
`学完到的东西，一定要多实践，要不然知识点很容易忘记！`

一开始觉得只做静态页面的话，应该挺简单的，真正做起来发现也不是那么容易。尤其看过淘宝网页的源码后发现，本觉得几个div就能搞定的东西，其实还是很复杂的，里面的div嵌套了一层有一层。而且淘宝网页考虑考虑的问题有很多，比如去掉网页的css，依然保证能正常购买商品；有些以图片形式存在的链接，当图片没有加载进来时，需要以文字链接的形式存在，而图片形式存在时又该如何把文字隐藏?

----------------------------------

总结一下吧。
总的来说，收获还是有的，但不是很大，毕竟还是第一次做这么复杂的页面。
（虽然以前Dreamweaver做过一个比较完整的网站页面，但是。。呵呵）

- html负责网页的结构，写网页时，结构要清晰，先写整体的框架，写上必要的注释。即使是模仿，有时也要在草稿纸上画出网页结构的草图。

- 写整体框架布局时，最好用background-color区分开来，而不是用border将区域分割开来，因为border是要“占空间”的啊，这就容易造成去掉border后，发现总是差那么1px 2px。

- 定义class时尽量语义化，这就不多说了，多写，多看几个项目，自然会知道这个div该叫什么类名。

- 写css时，尽量使用父子选择器，虽然这会造成像`.search-nav-wrap .search-nav .search-nav-box .search-box-bd{...}`
那么长的代码，但是查找起来方便啊，不用担心class重名啊。

## 啊啊啊

就写到这吧，想出来和写出来完全两回事。文笔太烂。。。😔

下一步，把《css权威指南》过一遍再说吧，真是太菜了
再学点js，把做的淘宝首页动态效果做了，这估计我得把静态页面重新写一遍了
做完淘宝这部分，再做个网易云吧，因为我看了下天猫、京东、苏宁首页和淘宝差不多，还没淘宝好看


呜——，我已入坑前端了

# 补充
右边浮动菜单，本以为一个 position：fixed; 就能搞定的小玩意，我竟然弄了半天都没做好，
百度了一上午，有一半时说在移动端这个属性不好使。还有就是父级如果存在 transform 属性，子元素的 position: fixed 属性无效。总之，百度上各种方法都亲测无效，包括将这个div放在外部，所以啊，继续学习css，┭┮﹏┭┮




