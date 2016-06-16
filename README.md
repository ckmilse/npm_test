##1.package.json  有入口键名 main
 "main": "index.js",
##2.index.js
采用 module.exports提供对外接口

##其他项目引用 
###安装
 npm install  https://github.com/ckmilse/npm_test.git --save-dev
### 使用
 var cktest = require('npm_test');
 
##发布到npm 需要有npm 账号，具体参考https://cnodejs.org/topic/5364dcde31a870830700b847
####（未实践发布）

