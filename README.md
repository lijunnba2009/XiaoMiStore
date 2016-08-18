# XiaoMiStore
此项目仿照的是小米官网商城的功能，按照我自己的想法实现的一个自营模式的商城应用。 目前只实现了前台的功能，主要有登录，注册，商品展示，购物车等模块。为了便于此项目日后的完善和扩展， 我采用了前后端分离的架构设计。前端主要使用AngularJS，ui-router构建的单页web应用， 通过使用指令，服务，模板，控制器完成前端的MVC分层，各个模板页面的效果实现则使用了基本的HTML，CSS3等技术， 结合JS完成页面的基本交互效果。由于没有实现数据库和后台模块等功能， 项目的测试数据我采用的是JSON格式的数据文件，通过AJax请求完成整个前台功能的数据交互， 后期再考虑实现一个后台管理系统及数据库系统，还有前端页面资源的异步加载及优化。

## Usege
注册账号（没有验证限制随意填写）->登陆->首页->查看，搜索商品（小米手机5的测试数据相对完善）->立即购买->购物车结算->订单（未完成）->支付（没有实现，如有大神希望可以指点一下支付功能的实现）

### Versioning
此作品目前只有个前台架构，目前只有小米手机5的测试数据相对完善，如果需要演示功能请点击小米手机5，很多产品的图片没有切，浏览器的兼容性也暂时不考虑，代码的压缩及打包，性能的优化等下个版本完成
如果后期能完成后台及数据库系统，到时再调用后台的api接口，完成数据的呈现。

#### Explain
此项目仅是个人模仿小米官网的实践作品，BUG还有很多，代码实现的比较烂，欢迎大家提出问题和改进建议，一起学习和交流。此项目只供学习参考，如有其他用途，本人概不负责。

### Sample
[点击这里你可以链接到项目演示地址](http://weboey.github.io/XiaoMiStore)