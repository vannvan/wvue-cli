## About

集成了`sass` 、`axios` 、`vuex`等vue项目必要依赖，同时完善了这些插件的使用配置，对vuex进行了模块化管理，集成了部分常用的方法，包含自定义指令的运用场景参考、全局混入的运用场景参考、接口封装等实际项目的标准化模块。

![](https://badgen.net/npm/dm/wwvue-cli)
![](https://badgen.net/npm/v/wwvue-cli)
![](https://badgen.net/npm/node/next)
![](https://badgen.net/github/commits/vannvan/wvue-cli)
![](https://badgen.net/github/last-commit/vannvan/wvue-cli)

## Function List
- 静态资源存放位置统一管理
- 公共样式管理、字体库、第三方脚本统一管理
- 开箱即用的sass
- router统一管理
- vuex模块化管理 store
- 接口统一管理  urlconfig
- 公共指令基础配置 directive
- 全局混入基础配置 mixins
- 自定义组件导出和引入a
- 命令行打包压缩  
- 命令行生成项目目录树
- 命令行一步push本地仓库
- 自动获取局域网ip，打开局域网server
- 等待挖掘...

## Install

> npm i wwvue-cli -g

## Usage

> wwvue init project-name



## Command line deployment

运用命令行完成每次版本的更新,将本地更新推送至远程仓库。

> npm run push init

## Command line packaging

运用命令行完成每次需要交付的项目压缩文件。

> npm run pack

## Generate directory tree

运用命令行生成项目目录树

> npm run tree    //命令行查看  
> npm run tree >>tree.txt    //生成文件  
## Analog interface data
本地模拟数据接口  
此功能算不上刚需，如不需要可在初始化完毕后删除mock目录，如有模拟数据的需要，可采取mock的方案，此方案可以避免`mock`插件的某些坑，当然任何方案都不可能是完美的，可按需选择。  
因为可能不算刚需，故采取将此功能做独立配置，不与主项目依赖产生交集，需在mock目录下单独安装依赖,安装完依赖后，运行命令：
> npm run serve
## 更多便于vue项目开发的功能还在不断迭代更新！
