# HIUI Core CSS

[![CircleCI](https://circleci.com/gh/hiui-group/core-css.svg?style=shield)](https://circleci.com/gh/hiui-group/core-css)

HIUI 模板核心样式文件，包含初始化、布局、排版等样式。

## 使用

### 组件
组件依赖直接引入 `@import '@hi-ui/core-css';`，只包含变量和函数，不会插入任何实质代码。

### 主题
主题依赖包含了核心文件以及必备的 normalize、helper classes、排版、多语言等支持，使用方法如下：

```scss
@import '@hi-ui/core-css/i18n/zh-CN.scss';
@import '@hi-ui/core-css/base.scss';
```

-- EOF --
