v0.0.5 - 2016.9.9

* e3554bc Feat: ykit-config-{type}插件支持查找全局模式
* 92ecfa3 Feat: 默认改为按请求资源打包，整体打包改为可选参数
* a6bac57 Feat: server支持https
* e6563ab Feat: 添加初始化说明，支持无默认类型
* 2c12dd7 Revise: devtool默认使用source map
* d02b242 Revise: minify模式不使用source map
* 05117d9 Revise: 根据lint结果区分返回值
* 97aca37 Revise: 更改.cache目录为.ykit_cache
* f5b6d0e Fix: 修复windows下pack移除目录命令不生效
* 1401222 Fix: 修复一些情况下启动server livereload不生效
* b81f867 Fix: 修复node_modules中resolve extension不生效
* 56a4983 Fix: 修复eslint设置extend不生效
* 9a59d61 ab7c1b0 Fix: 修复watch入口文件造成的内存泄露问题
* 1880c2f 14330fe Fix: 修复更改入口以后服务 / 打包报错

v0.0.4 - 2016.8.26

* 1ca6010 aa9a1e2 7483355 Feat: 优化编译报错 log
* d1c8e9e Revise: json-loader exclude node_modules
* 744f7f4 Revise: config api setCompile 改为 setCompiler
* fa170a3 Revise: 初始化时使用内网环境
* 7136403 Fix: 修复404请求一直 pending
* e0462e5 Fix: 修复 init 命令重写 package.json 问题

v0.0.3 - 2016.8.15

* 423d485 Feat: 检测到config文件变化后可以重新生成compiler
* 0e086ef Feat: 添加 jerryproxy 作为初始组件
* c9ff1b9 Feat: 兼容 fekit 形式 alias
* 8c6302c Feat: 默认添加 context 为 resolve.root
* f4e9a12 Fix: 修复资源过大时第一次渲染失败
* b904079 Fix: 修复 setConfig 中覆盖 loaders 未生效
* 53498bb Fix: 修复没有使用到本地 lint 规则

v0.0.2 - 2016.7.30

* 4380c73 Feat: 兼容 node 0.12.*
* 6afd43d Feat: 支持设置 context 相对路径
* bbb5808 Feat: 支持入口每一项为数组
* 3189f29 Feat: 添加 JerryProxy
* a8d90ff Fix: 修复 Windows 路径格式问题
* f679c63 Fix: 修复在不同 context 下 .cache 路径问题

v0.0.1 - 2016.7.15

* dc8ad5f Feat: 完成 server / pack logger
* e77692b Feat: 完成 server livereload
* edca9f8 Feat: 完成 stylelint
* 68e7fcb Feat: 支持 gulp & grunt
* 551c0b4 Feat: 支持分组打包
* a5013b3 Docs: 添加初始使用文档