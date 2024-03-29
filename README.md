# grunt-tbf2e

一个前端的Build工具集合

## 如何开始
在终端中`cd`到你的项目目录（你的`grunt.js`所在目录），然后使用`npm install grunt-tbf2e`来安装插件

然后在你的配置文件 `grunt.js` 中引入该插件:

```javascript
grunt.loadNpmTasks('grunt-tbf2e');
```
## Grunt的使用请参考
 * [grunt](https://github.com/cowboy/grunt)
 * [getting_started](https://github.com/cowboy/grunt/blob/master/docs/getting_started.md)

## 包含的插件

除了使用grunt的内置组件：

* [concat](/gruntjs/grunt/blob/master/docs/task_concat.md) - Concatenate files.
* [init](/gruntjs/grunt/blob/master/docs/task_init.md) - Generate project scaffolding from a predefined template.
* [lint](/gruntjs/grunt/blob/master/docs/task_lint.md) - Validate files with [JSHint][jshint].
* [min](/gruntjs/grunt/blob/master/docs/task_min.md) - Minify files with [UglifyJS][uglify].
* [qunit](/gruntjs/grunt/blob/master/docs/task_qunit.md) - Run [QUnit][qunit] unit tests in a headless [PhantomJS][phantom] instance.
* [server](/gruntjs/grunt/blob/master/docs/task_server.md) - Start a static web server.
* test - Run unit tests with [nodeunit][nodeunit].
* watch - Run predefined tasks whenever watched files change.

以外，`tbf2e`提供了以下额外组件：

#### [`copy`](https://github.com/gruntjs/grunt-contrib-copy/)
复制文件到制定目录.

#### [`less`](https://github.com/gruntjs/grunt-contrib-less/)
将LESS文件编译为CSS.

#### [`compass`](https://github.com/kahlil/grunt-compass)
在你的项目中使用Compass(SASS)

#### [`mincss`](https://github.com/gruntjs/grunt-contrib-mincss/)
对CSS文件进行压缩.

#### [`ksp`](https://github.com/neekey/grunt-ksp)
对遵循KISSY 1.2 的包规范的脚本文件进行打包


## License
Copyright (c) 2012 neekey  
Licensed under the MIT license.
