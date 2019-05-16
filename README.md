# Kung Fu Pro 

[![](https://img.shields.io/github/tag-date/kungfu-pro/kungfu-pro-issues.svg?style=for-the-badge)](https://github.com/kungfu-pro/kungfu-pro-issues/releases)
[![](https://img.shields.io/github/downloads/kungfu-pro/kungfu-pro-issues/total.svg?style=for-the-badge)](https://github.com/kungfu-pro/kungfu-pro-issues/releases)

开箱即用的透明代理解决方案 <br>
灵活的规则配置，兼容多种代理协议 <br>
支持大型网络环境，无惧 DNS 污染，不影响正常流量 <br>

[使用](https://kungfu-pro.github.io/doc/#/?id=%E6%A1%88%E4%BE%8B%E4%BD%BF%E7%94%A8)

## 更新日志
* **v0.1.5** <br>
  * 更新DNS依赖库
  * 修复DNS对大UDP包对响应处理

* **v0.1.4** <br>
  * 更新升级底层依赖
  * 更新升级管理界面（antd-pro）
  * 升级到 go 1.12.4

* **v0.1.3** <br>
  * 升级部分底层依赖
  * 升级到 go 1.11.5

* **v0.1.2** <br>
  * 修复规则组缓存
  * 修复 for openwrt x86 编译

* **v0.1.1** <br>
  * 添加 daemon 启动参数
  * 部分代码优化

* **v0.0.11** <br>
  * 优化 NAT 会话管理
  * 优化 MIPS 构建
  * 支持 http/https 代理

* **v0.0.10** <br>
  * 管理支持自动登录
  * 优化 tcp 超时策略
  * ssh 隧道支持忽略端口号
  * 更新了部分底层依赖库
  * 修复并发短连接过多时 nat 池回收 bug
  * 修复更换网段时，缓存数据清理 bug

* **v0.0.9** <br>
  支持 ssh 隧道

* **v0.0.8** <br>
  date: 2018-12-08 <br>
  稳定版，添加了自定义 hosts 功能
