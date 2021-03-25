## UML 图、思维脑图、博客/笔记图片的图床仓库

### 使用

- PicGo设置好github图床，可结合Typora使用。
- IThoungtsX 画完思维导图后保存多一份png图片， 通过git push更新。
- drawio 画完UML图后保存多一份png图片，通过drawio update来更新。

图片路径见： https://browser-helper.vercel.app/diagrams/ 或者 browserHelper的 diagrams工具

### 好处

- 图床由自己控制，比较集中且容量完全足够。
- 更新uml和mind的目录下uml或脑图的内容，进而动态更新对应img目录下生成的图片（之前找了一圈没有发现这样的产品）。
- 采用[https://cdn.jsdelivr.net](https://cdn.jsdelivr.net)提供的cdn服务加速

### 缺点（目前的缺点已经解决）

- github在国内网速有点感人。（最近找到了解决方法，采用[https://cdn.jsdelivr.net](https://cdn.jsdelivr.net)提供的cdn服务加速）


### TODO

- [x] 怎么方便获取md，url等连接
- [x] 图片压缩
