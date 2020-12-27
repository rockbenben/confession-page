表白专用静态页面，已针对手机端自适应优化。

2020.12.27 将 github cdn 部署在 jsDelivr，针对国内加速。本地设置备份在「静态备份」文件夹。

原项目为 hackerzhou 庆祝与 mm 相恋一周年纪念日写的静态页面，PC 端效果相当不错。
原项目主页：https://github.com/hackerzhou/Love

## 显示规则

* index.html 默认载入移动页面。如果判断为 pc 端，则跳转显示 index_pc.html 页面。
* one.html 为单页面，通过判断手机端或 pc 端，加载不同 css 样式。

## 修改部分

* 加入 bootstrap 框架，增加网页多客户端自适应；
* 添加手机端或 pc 端判断规则，不同客户端展示不同样式；
* 放大移动端字体；
* 添加「心」型网页图标。

