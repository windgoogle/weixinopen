# weapp-demo
🤖 小程序DEMO

## 安装项目`NPM`依赖

```bash
$ npm install
```

## 使用

### 开发阶段

执行如下命令

```bash
# 启动监视
$ npm run watch
```

通过**微信Web开放者工具**打开项目根目录下`dist`文件夹，预览~

可以通过任意开发工具完成`src`下的编码，`gulp`会监视项目根目录下`src`文件夹，当文件变化自动编译

#### 创建新页面

执行如下命令

```bash
# 启动生成器
$ npm run generate
# 完成每一个问题
# 自动生成...
```

由于微信小程序的每一个页面有特定的结构，新建工作比较繁琐。可以通过此任务减少操作。

### 生产阶段

执行如下命令

```bash
# 启动编译
$ npm run build
```

生产阶段的代码会经过压缩处理，最终输出到`dist`下。

同样可以通过**微信Web开放者工具**测试。
