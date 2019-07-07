# vw-layout

> vw-layout

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

# 如何使用
## 1、添加全局样式

``` bash
[aspectratio] {
	  position: relative;
  }
  [aspectratio]::before {
	  content: '';
	  display: block;
	  width: 1px;
	  margin-left: -1px;
	  height: 0;
  }

  [aspectratio-content] {
	  position: absolute;
	  top: 0;
	  left: 0;
	  right: 0;
	  bottom: 0;
	  width: 100%;
	  height: 100%;
  }
```

## 2、html结构
  aspectratio容器包裹aspectratio-content容器。
  如果在设计图上测量某个容器宽度为246px,则给这个容器添加 w-246 自定义属性，如果某个容器的宽为188px，高为246px,则给这个容器添加自定义属性 w-188-246

## 3、css样式
``` bash
  [w-750-246]{  // 自定义属性(设计图测量出的容器的宽高)
  	width: 750px;   // postcss-px-to-viewport插件解析成100vw(以设计图宽度为750px为例)
  }
  [w-350] {
    width: 350px;  // postcss-px-to-viewport插件解析成50vw(以设计图宽度为750px为例)
  }
  [w-188-246]{
  	aspect-ratio:'188:246';  // 容器的长宽比缩放postcss-aspect-ratio-mini插件会被解析成padding-top: (188/246)%  一般用于图片容器，使图片不会被拉伸变形
  }
```
