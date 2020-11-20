# AwesomePOS

> 了解和熟悉 Vue2.X 的练习作品

## 技术栈

vue2 + webpack + vueRouter + elementUI

## 项目整体

<hr>

项目总体分为三个区域 分别为：侧边栏 操作区域 商品展示区域
在操作区域内目前共有点餐、挂单、外卖 三种可操作功能 （目前只实现了点餐功能！ 后续有机会更换 <b>Vue3.0+Ts</b> 来全部实现）

[![DQf6DH.png](https://s3.ax1x.com/2020/11/20/DQf6DH.png)](https://imgchr.com/i/DQf6DH)

<hr>

### 功能介绍

1.在商品展示区域 可以通过点击商品 将商品添加至左侧操作栏中 <br>2.左侧操作栏中可以通过点击‘操作’子类下 <font color=#7fc1f0 size=3>删除/增加</font> 按钮来进行商品数量和增减 <br>3.操作栏内部可以根据点击进行数量和金额变化 <br>4.自动进行数量统计 和 总价的计算 <br>5.可以点击红色的<font color=red size=3>删除</font>按钮 进行操作页商品清空 <br>6.可以点击绿色的<font color=green size=3>结账</font>按钮 进行商品的结算并清空
[![DQfcbd.png](https://s3.ax1x.com/2020/11/20/DQfcbd.png)](https://imgchr.com/i/DQfcbd)

## Build Setup

```bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
