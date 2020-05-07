# 课程特色

```cmd
vuex模块化管理
Vue-router二次封装
使用element-ui库
支付模块
多权限管理
商品多规格实现
对象存储
api接口安全
部署服务器上线
```

## 安装创建vue项目和配置

一、安装
>npm install -g @vue/cli
>
>vue create vue-el-admin
>
>cd vue-el-admin
>
>npm run serve

二、配置vue.config.js(关闭保存代码错误提示)

```javascrupt
module.exports = {
    lintOnSave:false
}
```

或vue ui（可视化管理项目）==》导入项目==》项目配置==》ESLint configuration==》关闭保存代码错误提示，会自动创建上述代码

## 安装element-ui和基础使用

vue add element
全局、覆盖元素的SCSS变量、中文
npm run serve

## 配置高效代码块

https://element.eleme.cn/#/zh-CN/component/installation

## 使用bootstra4工具提高开发效率

https://getbootstrap.com/

## 安装vue-router和使用

第一步：
    npm install vue-router --save
第二步：
    src新建router.js

```javascript
import Vue from "vue"
import Router from "vue-router"

Vue.use(Router)

export default new Router({
    routes:[]
})
```

第三步：
    在main.js引入router.js

```javascript
import Vue from 'vue'
import App from './App.vue'
import './plugins/element.js'
import router from './router.js'

Vue.config.productionTip = false

new Vue({
  router,
  render: h => h(App),
}).$mount('#app')
```

## vue-router二次封装一

分离和重定向

## vue-router二次封装二

简化component路径

## vue-router二次封装三四

简化path、name属性

## 登录页开发

UI构建、登陆表单验证实现（element、bootstrap）

## 后台全局布局开发

全局顶、侧部开发
