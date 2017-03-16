[![加入聊天 https://gitter.im/nolimits4web/Swiper](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/nolimits4web/Swiper)
[![Build Status](https://travis-ci.org/nolimits4web/Swiper.svg?branch=master)](https://travis-ci.org/nolimits4web/Swiper)
[![devDependency Status](https://david-dm.org/nolimits4web/swiper/dev-status.svg)](https://david-dm.org/nolimits4web/swiper#info=devDependencies)

Swiper 滑动组件
==========

Swiper常用于移动端网站的内容触摸滑动。

Swiper是纯javascript打造的滑动特效插件，面向手机、平板电脑等移动终端。

Swiper能实现触屏焦点图、触屏Tab切换、触屏多图切换等常用效果。
Swiper开源、免费、稳定、使用简单、功能强大，是架构移动终端网站的重要选择！


# 入门

  * [入门指南](http://www.idangero.us/swiper/get-started/)
  
  * [API](http://www.idangero.us/swiper/api/)
  
  * [示例](http://www.idangero.us/swiper/demos/)
  
  * [论坛](http://www.idangero.us/swiper/forum/)

# Dist / Build

On production use files (JS and CSS) only from `dist/` folder, there will be the most stable versions, `build/` folder is only for development purpose

### Build

Swiper uses `gulp` to build a development (build) and dist versions.

First you need to have `gulp-cli` which you should install globally.

```
$ npm install --global gulp
```

Then install all dependencies, in repo's root:

```
$ npm install
```

And build development version of Swiper:
```
$ gulp build
```

The result is available in `build/` folder.

### Dist/Release

After you have made build:

```
$ gulp dist
```

Distributable version will available in `dist/` folder.

# Contributing

All changes should be committed to `src/` files. Swiper uses LESS for CSS compliations, and concatenated JS files (look at gulpfile.js for concat files order)

Swiper 2.x.x
==========

If you still using Swiper 2.x.x or you need old browsers support, you may find it in [Swiper2 Branch](https://github.com/nolimits4web/Swiper/tree/Swiper2)
* [Download Latest Swiper 2.7.6](https://github.com/nolimits4web/Swiper/archive/v2.7.6.zip)
* [Source Files](https://github.com/nolimits4web/Swiper/tree/Swiper2/src)
* [API](https://github.com/nolimits4web/Swiper/blob/Swiper2/API.md)
