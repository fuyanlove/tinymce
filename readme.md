# TinyMCE


## 引用
```html
<script src="https://cdn.deepberry.cn/static/tinymce/tinymce.min.js"></script>
```

## 构建
`npm run build`更新css构建

## 特性
+ 基于tinymce v5.2.2扩展
+ 保留v4版本分割线规则
+ 内置powerpaste&checklist插件
+ 增加插入B站视频插件
+ 增加插入折叠文本插件
+ 增加mathjax支持latex


## 插件添加步骤
1. icons/custom/icons.js 添加svg图标,需设置尺寸,注意视口大小,移除换行符等
2. plugins目录，复制videox(input),foldtext(null)目录作为参考新建插件目录，替换videox为新插件名
3. 编辑器配置中激活插件和添加工具栏项

## CDN更新
```
https://cdn.deepberry.cn/static/tinymce/tinymce.min.js
https://cdn.deepberry.cn/static/tinymce/skins/content/default/content.min.css
```