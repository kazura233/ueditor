<h1 align="center">Welcome to @kazura/ueditor 👋</h1>
<p>
  <a href="https://www.npmjs.com/package/@kazura/ueditor" target="_blank">
    <img alt="Version" src="https://img.shields.io/npm/v/@kazura/ueditor.svg">
  </a>
  <a href="https://github.com/kazura233/ueditor/blob/master/LICENSE" target="_blank">
    <img alt="License" src="https://img.shields.io/npm/l/@kazura/ueditor.svg?color=blue" />
  </a>
</p>

> 由于现在 [ueditor](https://github.com/fex-team/ueditor) 并没有官方 cdn，所以创建一个 npm 包，让其支持 cdn。没有做代码改动。

### 🏠 [Homepage](https://github.com/kazura233/ueditor)

## Usage

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>ueditor demo</title>
    <!-- 配置文件 -->
    <script src="https://cdn.jsdelivr.net/npm/@kazura/ueditor@1.5.0/ueditor.config.js"></script>
    <!-- 编辑器源码文件 -->
    <script src="https://cdn.jsdelivr.net/npm/@kazura/ueditor@1.5.0/ueditor.all.min.js"></script>
    <!-- 简体中文语言包 -->
    <script src="https://cdn.jsdelivr.net/npm/@kazura/ueditor@1.5.0/lang/zh-cn/zh-cn.js"></script>
  </head>
  <body>
    <!-- 加载编辑器的容器 -->
    <script id="container" name="content" type="text/plain">
      这里写你的初始化内容
    </script>
    <!-- 实例化编辑器 -->
    <script>
      var ue = UE.getEditor('container')
    </script>
  </body>
</html>
```

## Author

👤 **kazura233**

- Website: https://github.com/kazura233
- Github: [@kazura233](https://github.com/kazura233)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/kazura233/ueditor/issues).

## Show your support

Give a ⭐️ if this project helped you!

---

_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
