# 📚 Awesome OpenTool [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 精选的 `OpenTool` 相关资源、工具和库集合。

---

## 📖 目录

- [介绍](#-介绍)
- [简介](#-简介)
    - [📚 文档](#-文档)
    - [📦 SDK](#-sdk)
    - [🛠 OpenTool Servers (Tools)](#-opentool-servers-tools)
        - [1. 直接可用类](#直接可用类)
        - [2. 协议转换类](#协议转换类)
        - [3. 请求转发类](#请求转发类需要配置业务函数的opentool-json描述文件)
    - [⚙️ 管理工具](#-管理工具)

---

## 📖 介绍

本仓库收录了与 **OpenTool** 相关的优秀资源，包括开源库、工具、文章教程和社区项目。

---

## 📂 简介

### 📚 文档
- [OpenTool Docs](https://github.com/opentool-hub/opentool-spec) - 官方规格文档集合和说明
- [OpenTool Spec](https://github.com/opentool-hub/opentool-spec/blob/main/opentool-specification-cn.md) - OpenTool Schema数据结构文档
- [Client Server Spec](https://github.com/opentool-hub/opentool-spec/blob/main/client-server-specification-cn.md) - OpenTool客户端（Agent端）与OpenTool服务端（工具端）交互文档
- [CLI Guidelines](https://github.com/opentool-hub/opentool-spec/blob/main/opentool-server-cli-guidelines-cn.md) - OpenTool Server 命令行建议做法

### 📦 SDK
- [Java](https://github.com/opentool-hub/opentool-java) - OpenTool client和sever的Java SDK,并连带OpenTool JSON的Parser
- [TypeScript](https://github.com/opentool-hub/opentool-typescript) - OpenTool 的 TypeScript 客户端和服务端 SDK，提供 JSON 规范解析器。
- [Dart](https://github.com/opentool-hub/opentool-dart) - OpenTool的client和server的Dart SDK，并连带OpenTool JSON的Parser
- [C# .NET](https://github.com/opentool-hub/opentool-csharp-net) 8 或更高版本 - OpenTool 的 .NET SDK，支持 JSON-RPC 协议的 Tool Server 与 Client，实现了 OpenTool 规范中的核心能力。
- [C# .NET Framework](https://github.com/opentool-hub/opentool-csharp-netfx) 4.8.1 - OpenTool 的 .NET Framework SDK，支持 JSON-RPC 协议的 Tool Server 与 Client，实现了 OpenTool 规范中的核心能力。
- [LabVIEW](https://github.com/opentool-hub/opentool-labview) - OpenTool的LabVIEW SDK，用于LabVIEW应用程序中实现OpenTool Server。

### 🛠 OpenTool Servers (Tools)

#### 直接可用类
- [Modbus](https://github.com/opentool-hub/opentool-server-modbus) - OpenTool的Modbus客户端实现，运行opentool的请求来执行Modbus的操作
- [PTY](https://github.com/opentool-hub/opentool-server-pty) - OpenTool的伪终端实现，运行opentool的请求来执行伪终端的命令行操作
- [Serial Port](https://github.com/opentool-hub/opentool-server-serial-port) - OpenTool的串口，允许使用OpenTool的方式访问串口
- [NI VISA](https://github.com/opentool-hub/opentool-server-ni-visa) - OpenTool的NI VISA接口，允许使用OpenTool的方式访问NI VISA

#### 协议转换类
- [MCP HTTP](https://github.com/opentool-hub/opentool-server-mcp-http) - OpenTool的MCP HTTP客户端实现，运行opentool的请求来执行MCP HTTP的操作
- [MCP STDIO](https://github.com/opentool-hub/opentool-server-mcp-stdio) - OpenTool的MCP STDIO客户端实现，运行opentool的请求来执行MCP STDIO的操作

#### 请求转发类：需要配置业务函数的OpenTool JSON描述文件
- [WebSocket Proxy](https://github.com/opentool-hub/opentool-server-websocket-proxy) - OpenTool的WebSocket代理，允许浏览器也可以收到OpenTool的call推送
- [MQTT Proxy](https://github.com/opentool-hub/opentool-server-mqtt-proxy) - OpenTool的MQTT代理，允许支持MQTT的物联网设备也可以收到OpenTool的call推送

### ⚙️ 管理工具
- [OpenTool Daemon](https://github.com/opentool-hub/opentool-util-daemon) - 提供用于管理 OpenTool Server 的本地常驻守护进程服务。该服务监听本地端口，提供 HTTP 接口以供 CLI 或其他前端程序调用。
- [OpenTool CLI](https://github.com/opentool-hub/opentool-util-cli) - OpenTool的命令行工具，用于访问OpenTool Daemon服务，管理本地OpenTool Server

## 🤝 贡献
欢迎提交 Pull Request 来补充或改进资源，请先阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 📜 License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)  
本仓库采用 **[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)** 协议。