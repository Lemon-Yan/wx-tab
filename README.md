# tab的实现


> tab功能的实现需要在项目根目录下app.json文件中配置,创建tab时，需要准备相应的图标文件和新建对应的页面，然后就可以在对应页面中写项目原型了。下面是一个简单的tab实现，直接可以拷贝到项目中使用，没有多余的代码。

### 效果图：

![tab.png](http://upload-images.jianshu.io/upload_images/4041074-9f9eef38688730f4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


###### 示例代码：

```
"tabBar": {
    "selectedColor": "#20B3AD",
    "color": "#999",
    "borderStyle": "white",
    "backgroundColor": "#F0F0F0",
    "list": [
      {
        "pagePath": "pages/index/index",
        "iconPath": "images/home.png",
        "selectedIconPath": "images/homeSelected.png",
        "text": "首页"
      },
      {
        "text": "租赁",
        "pagePath": "pages/lease/lease",
        "iconPath": "images/lease.png",
        "selectedIconPath": "images/leaseSelected.png"
      },
      {
        "text": "预售",
        "pagePath": "pages/sale/sale",
        "iconPath": "images/sale.png",
        "selectedIconPath": "images/saleSelected.png"
      },
      {
        "pagePath": "pages/my/my",
        "iconPath": "images/mine.png",
        "selectedIconPath": "images/mineSelected.png",
        "text": "我的"
      }
    ]
  }
```
