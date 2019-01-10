# WXBootstrap
微信小程序Bootstrap

### 微信小程序版Bootstrap封装
可以按照bootstrap风格开发微信小程序

方便有bootstrap基础的开发人员进行二次开发  
文件超小只有29K(还会继续优化),不占用2M小程序限制  
**欢迎大家提[issues](https://github.com/WilleamZhao/WXBootstrap/issues/new)**
**欢迎 [star](https://github.com/WilleamZhao/WXBootstrap)**

**使用方法:**  
在app.wxss里引入即可

```
/* 引入wxbootstrap */
@import "./plugins/wxbootstrap.wxss";
```

![使用wxbootstrap](http://sourcod.oss-cn-beijing.aliyuncs.com/hexo/8037b92bec112a9f67de28eb7866cc8d.png)


v0.1
- 去掉一些无用的bootstrap设置
- 去掉默认col
`padding-left 15px; padding-left 15px;` 样式
- 取消小程序按钮，默认button边框
- 内置bootstrap默认布局,p-1/6,m-1/6,按钮样式,对齐方式,flex布局,颜色等。

v0.2
- 新增.card样式
