# Heroku-vless

再次声明，免费服务，且用且珍惜，尽量不要滥用。

## 简介
Heroku是一个支持多种编程语言的云平台即服务。目前支持Ruby、Java、Node.js、Scala、Clojure、Python、PHP和Perl等语言，基础操作系统是Debian。

本项目用于在 Heroku 上部署 vless+websocket+tls，每次部署自动选择最新的 alpine linux 和 xray core。相比vmess，vless的性能更加优秀，占用资源更少，运行更加稳定。

建议使用cloudflare的workers的流量中转，速度更快，原则上使用后不会有被墙风险。

## 一键部署

经测试本镜像占用内存资源较低，运行稳定。点击下方紫色图标部署。

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/kerooh/rooht)




`WebSocket` 路径(配置文件中的 `path` )为 `/` 。你也可以自行修改

### 端口

`端口` 为 `443` 。

### UUID

`UUID` 默认为 `10974d1a-cbd6-4b6f-dcbd-8b3fb10938d7` 你也可以在部署时自由修改（建议修改）。


