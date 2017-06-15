# 前言

> 一直想做一个系统性的项目，后来看到豆瓣有个开源的api，所以我就模仿豆瓣的电影显示界面做了几个界面,小白请进，大神绕道~

# 用到的技术栈

> vue + axios + vue-cli + vue-router + mint-ui + sass

# 用到的接口

> 用到的是豆瓣的开源接口

> - **正在热映** ：<https://api.douban.com/v2/movie/in_theaters>
> - **即将上映** ：<https://api.douban.com/v2/movie/coming_soon>
> - **电影详情** ：<https://api.douban.com/v2/movie/subject/:id>
> - **TOP250** ：<https://api.douban.com/v2/movie/top250>

#

## Build Setup

```bash
# install dependencies 下载依赖
npm install

# serve with hot reload at localhost:8080 启动项目端口为8080
npm run dev

# build for production with minification 打包上传
npm run build
```

# 预览地址

<http://recklesslmz.com/vue-douban/dist/#/home>
> 好吧，我还是没解决接口的跨域的问题，还是把项目down下来看吧~

如果你觉得你这个项目对你有帮助的话，请不要吝啬你的小手点个star吧~

# License

> MIT

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
