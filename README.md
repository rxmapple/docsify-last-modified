# docsify-last-modified

> 基于Docsify的最后修改时间插件(解决docsify-updated 部署在github pages时间相同的问题)

### 特性
- 🎉 支持定义显示位置
- 🎉 支持定义前缀文本
- 🎉 支持定义时间格式


### 使用
1. 在 index.html 中引入脚本
```html
<script src="//cdn.jsdelivr.net/npm/tinydate@1.3.0/dist/tinydate.min.js"></script>
<script src="//cdn.jsdelivr.net/gh/rxmapple/docsify-last-modified@master/src/docsify-last-modified.js"></script>

```

2. 配置插件
```js
window.$docsify = {
    // ...
    lastModified: {
        repo: 'rxmapple/docsify-last-modified'
    },
};
```


### 配置项
lastModified.repo
* 默认: 
* 类型: String
* 描述: 你的repo
> 注意：repo必须填写，否则会显示默认的{docsify-updated}参数。

lastModified.basePath
* 默认: docs
* 类型: String
* 描述: 站点所在路径

lastModified.preString
* 默认: Last modified:
* 类型: String
* 描述: 日期前缀

lastModified.dateFormat
* 默认: {YYYY}-{MM}-{DD} {HH}:{mm}:{ss}
* 类型: String
* 描述: 日期格式

lastModified.align
* 默认: right
* 类型: String
* 描述: 对齐方式


### 相关链接
[Docsify](https://github.com/docsifyjs/docsify/)


### LICENSE
MIT
