#ModuleShop

A simple, cross-platform, modular mall system based on .NET Core

**Cross-platform**

> Docker, Windows, Linux, Mac. Microsoft SQL Server, PostgreSQL, MySQL, SQLite

**Modular**

> The application is divided into a number of self-contained modules

**Free and Open Source**

> ModuleShop is completely free and open source

##Backend service/API

Project address:/src/server

Online preview: [https://demo.shopapi.circle.ac.cn/swagger](https://demo.shopapi.circle.ac.cn/swagger)

### Project structure

![Product](/docs/screenshots/devenv_2019-07-06_20-48-19.png)

## Backstage management

Project address:/src/client

Online preview: [https://demo.shop.circle.ac.cn](https://demo.shop.circle.ac.cn) *admin/123456*

Front-end framework: [Ant Design Pro](https://pro.ant.design)

Usage documentation: http://pro.ant.design/docs/getting-started-cn

### Project screenshots

![Product](/docs/screenshots/chrome_2019-07-06_20-59-32.png)
![Product](/docs/screenshots/chrome_2019-07-06_20-59-21.png)
![Order](/docs/screenshots/chrome_2019-07-06_20-59-55.png)
![Home page display configuration](/docs/screenshots/chrome_2019-07-06_21-00-04.png)

### function list

+ Product: category, brand, unit, option (sales attribute), attribute, attribute template, attribute group
+ Sales: Orders, Logistics
+ Content: Home page configuration, comments, replies
+ Configuration: country, user, warehouse, freight, advanced settings, ~~subjectification~~, ~~localization~~, ~~tax~~
+ System: sample data
+ ~~Activity: Discount~~
+ ~~Home page: Home page~~

## WeChat Mini Program

Project address:/src/mini-program

Online preview (Skynet Mall):

![Mini program code](/docs/screenshots/shop_mp_8.jpg)

### Project screenshots

![Home](/docs/screenshots/wechatdevtools_2019-07-06_21-05-55.png)

![Category](/docs/screenshots/wechatdevtools_2019-07-06_21-06-27.png)

![Shopping cart](/docs/screenshots/wechatdevtools_2019-07-06_21-07-05.png)

![Product details](/docs/screenshots/wechatdevtools_2019-07-07_01-42-31.png)

![Order List](/docs/screenshots/wechatdevtools_2019-07-07_01-32-17.png)

![Order details](/docs/screenshots/wechatdevtools_2019-07-06_21-07-35.png)

![Evaluation](/docs/screenshots/wechatdevtools_2019-07-07_01-41-17.png)

![My](/docs/screenshots/wechatdevtools_2019-07-07_01-35-29.png)


### function list
+ Home
+ Classification home page, classified products, new product launches, popular recommendations, product pages, etc., can be configured through the backend
+ Product details page, including add to shopping cart, favorite products, and product comment functions
+ Search function
+ Complete shopping process, including product addition, editing, deletion, batch selection, delivery address selection, order payment
+ Member Center (orders, collections, footprints, delivery addresses, feedback)
....

### Project structure
```
├─config
├─lib
│ └─wxParse　
├─pages
│ ├─auth
│ │ ├─login
│ │ ├─register
│ │ └─reset
│ ├─brand
│ ├─brandDetail
│ ├─cart
│ ├─catalog
│ ├─category
│ ├─comment
│ ├─goods
│ ├─hotGoods
│ ├─index
│ ├─logs
│ ├─newGoods
│ ├─pay
│ ├─search
│ ├─shopping
│ │ ├─address
│ │ ├─addressAdd
│ │ └─checkout
│ ├─topic
│ ├─topicDetail
│ └─ucenter
│ ├─address
│ ├─addressAdd
│ ├─collect
│ ├─coupon
│ ├─feedback
│ ├─footprint
│ ├─index
│ ├─order
│ └─orderDetail
├─static
│ └─images
└─utils
```

## comminicate

If you like it, don’t forget to star. If you have any questions, you can contact me through WeChat, official account, or QQ group. Thank you for your attention.

[ModuleShop Communication Group](https://jq.qq.com/?_wv=1027&k=5AUnOw5 "ModuleShop Communication Group (863275860)") (QQ Group: 863275860)

![ModuleShop communication group QR code](/docs/screenshots/863275860_8_8.png)
