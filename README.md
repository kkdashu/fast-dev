# fast-dev
解决每次开坑都要配置Babel、Browserify等东西太麻烦了。

# 使用
```
1. npm install kkdashu/fast-dev --save-dev
2. cp -r node_modules/fast-dev/example node_modules/fast-dev/index.js node_modules/fast-dev/Makefile node_modules/fast-dev/.babelrc ./
3. make start
```

# 命令
```
1. make build 通过 babel 打包成一个 js 文件。
2. make start 通过 ecstatic 启动一个 node 服务，并且用 watchify 监听文件变化进行增量编译。
```

详情见 Makefile
