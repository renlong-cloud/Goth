Goth官网
============

## Build Setup
```
# install dependencies
npm install

# server with hot reload at localhost:8080
npm run dev

# build production
npm run build
```

## 技术栈
- [vue](https://cn.vuejs.org/)

- [vue-router](https://router.vuejs.org/zh-cn/installation.html)

- [webpack](http://webpack.github.io/docs/)

- [element-ui](http://element.eleme.io/#/)

- [less](http://lesscss.cn/)

- [es6](http://es6.ruanyifeng.com/)

## 项目目录

```
Goth
|
├── dist                               
|  ├── article               		   # 干货页面的图片
|  ├── team                            # 团队页面的图片
├── src                                
|  ├── assets                          
|     ├── css                          
|		├── reset.css                  # 样式重置文件
|     ├── img                          
|       ├── code.png                   # 二维码图片
|		├── index.jpg                  # 主页图片
|		├── story.jpg                  # 故事页面图片
|		├── us.jpg                     # 我们页面图片
|		├── vip-five.jpg               # VIP VI背景图片
|		├── vip-one.jpg                # VIP I背景图片
|		├── vip-three.jpg              # VIP III背景图片
|		├── vip-two.jpg                # VIP II背景图片
|     ├── less                         
|		├── article-item.less          # 干货页面中每个干货详情的公共样式
|		├── product.less               # 产品页面中每个产品详情的公共样式
|  ├── components                            
|     ├── article                      # 干货页面的细分      
|        ├── vue-america.vue           # 如何顺利申请到美国名校
|        ├── vue-ap.vue                # 关于AP考试(美国大学先修课程)
|        └── vue-defer.vue             # 被defer和waitlisted的原因及区别
|        └── vue-enroll.vue            # 美国春季入学和秋季入学
|        └── vue-ielts.vue             # 托福考试的基本认识以及意义
|        └── vue-sat.vue               # 解读新SAT
|        └── vue-transfer.vue          # 论美国大学转学
|     ├── product			           # 产品页面细分
|        ├── vue-family-member.vue     # family-member产品
|        ├── vue-mature-love.vue       # mature-love产品
|        ├── vue-puppy-love.vue        # puppy-love产品
|        └── vue-pure-love.vue         # pure-love产品
|     ├── vue-article.vue              # 干货
|     ├── vue-content.vue              # 内容
|     ├── vue-footer.vue               # 尾部
|     ├── vue-header.vue               # 头部
|     └── vue-index.vue                # Goth
|     ├── vue-product.vue              # 产品
|     ├── vue-story.vue                # 故事
|     ├── vue-team.vue                 # 团队
|     ├── vue-us.vue                   # 我们
|  ├── element                              
|     └── index.js                     # 按需引入element-ui的控件
|  └── router
|     └── index.js                     # 路由(懒加载)
|  ├── app.vue
|  ├── index.js                        
├── .babelrc                           # 设置转码和规则
├── favicon.ico                        # 图标
├── index.html                         
├── package.json                       # 依赖  
├── README.md                        
└── webpack.config.js                  # webpack配置文件
```

## 项目总结

## 项目图片
### PC端
![image](https://github.com/renlong-cloud/Goth/blob/master/_image/pc/1.png)
![image](https://github.com/renlong-cloud/Goth/blob/master/_image/pc/2.png)
![image](https://github.com/renlong-cloud/Goth/blob/master/_image/pc/3.png)
![image](https://github.com/renlong-cloud/Goth/blob/master/_image/pc/4.png)
![image](https://github.com/renlong-cloud/Goth/blob/master/_image/pc/5.png)
![image](https://github.com/renlong-cloud/Goth/blob/master/_image/pc/6.png)
### 移动端
<img src="https://github.com/renlong-cloud/Goth/blob/master/_image/mobile/1.jpg" width="300px">　　<img src="https://github.com/renlong-cloud/Goth/blob/master/_image/mobile/2.jpg" width="300px" style="clear:both;float: right">
<br/><br/><br/><br/>
<img src="https://github.com/renlong-cloud/Goth/blob/master/_image/mobile/3.jpg" width="300px">　　<img src="https://github.com/renlong-cloud/Goth/blob/master/_image/mobile/4.jpg" width="300px" style="clear:both;float: right">
<br/><br/><br/><br/>
<img src="https://github.com/renlong-cloud/Goth/blob/master/_image/mobile/5.jpg" width="300px">　　<img src="https://github.com/renlong-cloud/Goth/blob/master/_image/mobile/6.jpg" width="300px" style="clear:both;float: right">