<p align="center"><a href="https://vuejs.org" target="_blank" rel="noopener noreferrer"><img width="100" src="https://vuejs.org/images/logo.png" alt="Vue logo"></a></p>

# vue 2 源码阅读

## 目录结构
```
|-- benchmarks            # 基准测试
|-- dist                  # 构建后的文件
|-- examples              # 例子
|-- flow                  # Flow 的类型声明
|-- packages              # vue-server-renderer 和 vue-template-compiler 及 weex 相关包，
|                           它们作为单独的 NPM 包发布
|-- scripts               # 和构建相关的脚本和配置文件
|-- src                   # 源代码
|   |-- compiler          # 与模板编译相关的代码
|   |-- core              # 通用的、和平台无关的运行时代码
|   |   |-- components    # 通用的抽象组件
|   |   |-- global-api    # 全局 API 的代码
|   |   |-- instance      # Vue.js 的实例构造和原型方法
|   |   |-- observer      # 实现变化侦测的代码
|   |   |-- util          # 工具函数
|   |   |-- vdom          # 实现虚拟 DOM 的代码
|   |-- platforms         # 特定平台的代码
|   |-- server            # 与服务端渲染相关的代码
|   |-- sfc               # 单文件组件（*.vue）解析逻辑
|   |-- shared            # 整个项目的公用工具代码
|-- test                  # unit、e2e 等测试代码
|-- types                 # TypeScript 类型定义
```
