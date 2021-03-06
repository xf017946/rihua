<h2 align="center">pc官网页面素材描述</h2>
# 图片素材
图片素材最好提供 [七牛云](https://www.qiniu.com/) 图片链接，可将图片命名整理后由我这边整理上传。企业七牛云有免费空间的话，最好注册公司的七牛云统一管理。

## 网页标题以及网页图标favicon.ico(ico文件直接提供源文件，浏览器标签栏图标)
<img width="350px" src="http://indust.app.rihuabiology.com/101543802844_.pic.jpg">

## 网页顶部logo
<img width="350px" src="http://indust.app.rihuabiology.com/111543802894_.pic.jpg">

## 网页轮播图
<img width="350px" src="http://indust.app.rihuabiology.com/121543803039_.pic.jpg">

## 关于我们图片文案
<img width="350px" src="http://indust.app.rihuabiology.com/131543803062_.pic.jpg">

## 公司新闻
<img width="350px" src="http://indust.app.rihuabiology.com/141543803828_.pic.jpg">

## 加入我们 公司描述信息以及下方图片文案 
<img width="350px" src="http://indust.app.rihuabiology.com/151543803855_.pic.jpg">

## 联系我们 地图公司描述信息
<img width="350px" src="http://indust.app.rihuabiology.com/161543803901_.pic.jpg">

## 产品信息数据结构
```html
数据结构为一个对象  
{
  '手术无影灯': [
    // 注释：手术无影灯 第一页数据 如果手术无影灯有多页数据 现有布局是4行4列，在一个数组'[]'内配置16个对象'{}',如果配置4*5列，可自行调整配置对象数量
    [{
      imgUrl: 'http://www.shrhyl.com/Upload/Product/5bff6227-2dca-41df-af36-d90e9c9e27d3.jpg',  // 产品图片
      desc: '11.11狂欢返场65英寸/4K超清/3+64超大配置/自动体育模式/CD纹外置低音/VIDAA AI人工智能',        // 列表页描述
      breadTitle: '11.11狂欢返场65英寸',                                                          // 面包板文案：  控制前进后退那个
      model: 'YDZ700/700-TV',                                                                   // 产品型号
      details: {
        desc: '本产品YDZ700/700-TV内置摄像手术无影灯有摄像功能，供医院手术室照明使用，其摄像功能也可供于医校教学使用，由上海日花医疗器械有限公司生产。',  // 详情页产品描述
        params: [
          { '规格型号': 'YDZ700/700-TV' },
          { '照度': '15000' },
          { '色温': '有效光斑直径' }
        ]
      }
    },
    {
      ....
    }],
    // 注释：手术无影灯 第二页数据
    [{
      ...
    },
    {
      ...
    }
  ],
  '医用吊塔': [
    [{
      imgUrl: 'http://www.shrhyl.com/Upload/Product/5bff6227-2dca-41df-af36-d90e9c9e27d3.jpg',
      desc: '吊塔 第一页 11.11狂欢返场65英寸/4K超清/3+64超大配置/自动体育模式/CD纹外置低音/VIDAA ,AI人工智能',
      breadTitle: '详情页标题',
      model: 'YDZ700/700-TV',
      details: {
        desc: '本产品YDZ700/700-TV内置摄像手术无影灯有摄像功能，供医院手术室照明使用，其摄像功能也可供于医校教学使用，由上海日花医疗器械有限公司生产。',
        params: [
          { '规格型号': 'YDZ700/700-TV' },
          { '照度': '15000' },
          { '色温': '有效光斑直径' }
        ]
      }
    },
    {
      ...
    }],
    // 第二页数据
    [{
      ...
    },
    {
      ...
    }]
  ]
}
```

## 图片存在七牛云好处
免费并且可以享受cdn加速服务，提高网页图片加载速度，并且可以配置公司二级（三级也可以）域名访问图片链接
<img width="500px" src="http://indust.app.rihuabiology.com/81543802138_.pic.jpg">

## 七牛云上传图片步骤
<img width="500px" src="http://indust.app.rihuabiology.com/31543801860_.pic.jpg">
<img width="500px" src="http://indust.app.rihuabiology.com/41543801883_.pic.jpg">
<img width="500px" src="http://indust.app.rihuabiology.com/41543801883_.pic.jpg">
<p>新建完存储空间(页面左侧)后，点击内容管理</p>
<img width="500px" src="http://indust.app.rihuabiology.com/61543801950_.pic.jpg">
<img width="500px" src="http://indust.app.rihuabiology.com/71543802109_.pic.jpg">
