
//package.json中的script会安装一定顺序寻找命令对应位置，本地的node_modules/.bin路径就在这个寻找清单中，所以无论是全局还是局部安装的Webpack，你都不需要写前面那指明详细的路径了。

//set script execution path
...
"scripts": {
  "start": "node app.js",
  "test": "NODE_ENV=test mocha --reporter spec"
},
...