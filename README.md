# Green Light

Just another theme for [Hexo](https://hexo.io),  modified based on [Light](https://github.com/hexojs/hexo-theme-light).

[Live Preview](http://www.pingan.im)

## Install

Execute the following command and modify `theme` in `_config.yml` to `GreenLight`.

```
git clone https://github.com/qwong/hexo-theme-green-light.git themes/GreenLight
```

## Update

Execute the following command to update Light.

```
cd themes/GreenLight
git pull
```

## Config

See [theme light config](https://github.com/hexojs/hexo-theme-light#config).

## 中文介绍

自用Hexo博客主题, 基于官方主题[Light](https://github.com/hexojs/hexo-theme-light)修改.  
[在线预览](http://www.pingan.im)

主要有以下改动:

- 修改: 部分样式
- 新增: 文章上下篇链接
- 新增: 多说评论插件
- 新增: 百度分享插件
- 新增: 百度统计插件

## 配置项

参考light主题配置, 另外以下几项特殊配置:

#### 多说评论插件  
  1. 主题_config.yml配置文件启用多说评论插件, 新增配置项: duoshuo: true  
  2. 博客_config.yml配置文件新增配置项: duoshuo: ${你的[多说](http://www.duoshuo.com)ID}

#### 百度分享插件  
  主题_config.yml配置文件启用百度分享插件, 新增配置项: baidushare: true  

#### 百度统计插件  
  1. 主题_config.yml配置文件启用百度统计插件, 新增配置项: baidutongji: true  
  2. 博客_config.yml配置文件新增配置项: baidutongji: ${你的[百度统计](http://tongji.baidu.com)ID}

#### Google analytics插件  
  1. 主题_config.yml配置文件启用Google analytics插件, 新增配置项: google_analytics: true  
  2. 博客_config.yml配置文件新增配置项: google_analytics: ${你的[Google analytics](https://www.google.com/analytics)ID}

## 补充说明
  本人非专业前端, 样式也是用Chrome F12一点一点抠出来改的.  
  基于官方主题light修改, 样式是参考网上的, 背景图也是从某个网站上扒过来的.  
  二期修改参考了[这个主题](https://github.com/licheedev/hexo-theme-lightgreen), 他本身也是参考我原来的主题修改的.