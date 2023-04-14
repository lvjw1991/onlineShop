# fork from https://github.com/Richar-Dada/cakeShop
# 电商网站
nodejs + express + mongodb 完成的一个小型电商网站

#安装部署
1. 安装nodejs、mongoDB
2. 启动mongoDB
3. $npm install 安装依赖包
4. npm run dev 在开发环境中运行  
5. 前台网站 http://localhost:7777 
![image](https://user-images.githubusercontent.com/29093438/232134330-cfcdda1a-f2cf-4ba2-b961-f559e15741be.png)

6. 后台管理 http://localhost:7777/admin/list
![image](https://user-images.githubusercontent.com/29093438/232134373-a05c0d35-5073-4cd0-9647-0f6022e84c1d.png)


#目录结构
<pre>
- controllers 存放控制器的
- models 存放model，一些表的结构
- router 存放路由文件
- static 存在静态资源
- views 存放页面html文件
- app.js 入口文件
- .bowerrc 指定bower安装的目录
- .editorconfig 配置一些编程习惯配置
- gulpfile.js gulp自动化配置文件
- index.js 总的入口文件，npm run时调用
- package.json npm的配置文件
</pre>

#前台网站功能-支持用户登录后浏览产品加入购物车和结账功能
1. 登录注册
2. 首页-轮播图（写死）、上架新品、热门新品
3. 全部商品页-产品列表
4. 个人中心页-我的订单，我的购物车

#后台管理功能-仅支持管理产品
1. 产品增删改查
2. 无登录验证
3. 无订单列表
