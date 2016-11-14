# 静态页面开发-自动化

## 作用

通过使用 gulp & browser-sync 来：

- 生成静态文件服务器；
- 检测文件变化并自动刷新浏览器；
- eslint 监测文件错误；

## 使用说明

1. `cnpm i -S gulp gulp-eslint browser-sync`
2. `touch gulpfile.js`
3. 将此目录中的 `gulpfile.js` 文件内容复制到上面创建的文件中，并修改文件中的相关入口文件就可以了。
