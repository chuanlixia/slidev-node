---
# try also 'default' to start simple
theme: seriph
# apply any windi css classes to the current slide
class: "text-center"
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# persist drawings in exports and build
drawings:
  persist: false
# page transition
transition: false
# use UnoCSS
css: unocss
---

<!-- Node.js讲解 -->

# Node.js

Node.js 是一个基于 Chrome 的 V8 引擎的 JavaScript 运行时环境。

Node.js 使用了一个事件驱动、非阻塞式 I/O 的模型，使其轻量又高效。

---

# 什么是 Node.js

Chrome 里写 JS，控制浏览器
Node 里写 JS，控制服务器

---

# Node.js 用途

- Web 服务器后台 - 腾讯视频

  - 搜索引擎优化+首屏速度优化 = 服务端渲染
  - 服务端渲染 + 前后端同构

- 构建工具
  - webpack - 模块打包
  - gulp - 文件预编译 - 文件合并 - 文件压缩 - 文件监听 - 文件上传
  - grunt - 文件预编译 - 文件合并 - 文件压缩 - 文件监听 - 文件上传

---

# Node.js 用途

- 命令行工具
  - npm - 包管理工具
  - nrm - npm 源管理工具
  - nvm - node 版本管理工具
  - pm2 - node 进程管理工具
  - vue-cli - vue 脚手架工具
  - create-react-app - react 脚手架工具

---

# Node.js 用途

- vscode
  - 插件开发
  - 插件调试
  - 插件发布

---

# Node.js 用途

- 游戏
  - 游戏插件

---

# Node.js 用途

- 客户端应用
  - Electron - 用 HTML，CSS 和 JavaScript 构建跨平台的桌面应用

---

# Node.js 技术预研

- BFF - Backend For Frontend
  - 对用户侧提供的接口
  - 对服务器 RPC 接口整合调用

---

# Node.js 开发准备

- 安装 Node.js
  - 注意环境变量，一般没有问题
- 安装 vscode

---

# Node.js 特有变量

与浏览器环境不同的是，Node.js 有一些特有的变量，如：

- \_\_dirname - 当前文件所在目录
- \_\_filename - 当前文件的绝对路径
- setImmediate - 立即执行
- process - 进程

---
layout: two-cols
---

# process

- process.cwd() - 当前工作目录
- process.env - 环境变量
- process.nextTick - 下一个事件循环
- process.pid - 进程 id
- process.platform - 平台
- process.versions - 版本
- process.exit - 退出进程

::right::

# process

- hrtime - 高精度时间
- cpuUsage - CPU 使用情况
- memoryUsage - 内存使用情况
- kill - 杀死进程
- argv - 命令行参数

---

# Node.js 项目开发

---

# Node.js 性能优化

---

# Node.js 框架和工程化

---
