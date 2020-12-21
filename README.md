# 开发

```bash
$ npm install
$ npm run build
$ npm run min:css
$ npm run min:js
$ npm run server
```

# 接口响应
```json
[
  {
    // 必填－名字
    "name":"JSLint",
    // 必填－网址
    "url":"http://jslint.com/",
    // 选填－图标 
    // => 默认在根目录下的 favicon.ico 可以不填这项
    "ico":"http://easings.net/favicon.png",
    // 必填－可以留空 － 描述说明
    "des":"在线JS校验工具" ,
    // 选填－标签，便于归类
    "tags":["工具"]
  }
]
```

# FEATURE
- 支持上拉刷新，分页展示
- 支持接口获取数据列表