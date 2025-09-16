# 📚 Awesome OpenTool [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of **awesome OpenTool resources**, SDKs, servers, and utilities.

---

## 📖 Contents

* [Introduction](#-introduction)
* [Documentation](#-documentation)
* [SDKs](#-sdks)
* [OpenTool Servers](#-opentool-servers)

    * [Directly Usable Tools](#directly-usable-tools)
    * [Protocol Conversion Tools](#protocol-conversion-tools)
    * [Forwarding Tools](#forwarding-tools)
* [Management Utilities](#-management-utilities)
* [Contributing](#-contributing)
* [License](#-license)

---

## 📖 Introduction

This repository collects high-quality resources related to **OpenTool**,
including open-source specifications, SDKs, server implementations, utilities, and community projects.

---

## 📚 Documentation

* [OpenTool Docs](https://github.com/opentool-hub/opentool-spec) - Official specifications and documentation collection
* [OpenTool Spec](https://github.com/opentool-hub/opentool-spec/blob/main/opentool-specification-cn.md) - OpenTool schema data structure
* [Client-Server Spec](https://github.com/opentool-hub/opentool-spec/blob/main/client-server-specification-cn.md) - Agent-side and Tool-side interaction specification
* [CLI Guidelines](https://github.com/opentool-hub/opentool-spec/blob/main/opentool-server-cli-guidelines-cn.md) - Command-line interface best practices for OpenTool servers

---

## 📦 SDKs

* [Java](https://github.com/opentool-hub/opentool-java) - Java SDK for OpenTool client and server, including OpenTool JSON Parser
* [TypeScript](https://github.com/opentool-hub/opentool-typescript) - A TypeScript client and server SDK for OpenTool with JSON Spec Parser.
* [Dart](https://github.com/opentool-hub/opentool-dart) - Dart SDK for OpenTool client and server, including OpenTool JSON parser.
* [C# .NET](https://github.com/opentool-hub/opentool-csharp-net) 8 or Later - The OpenTool SDK for .NET supports Tool Server and Client communication over the JSON-RPC protocol, implementing the core capabilities defined in the OpenTool specification.
* [C# .NET Framework](https://github.com/opentool-hub/opentool-csharp-netfx) 4.8.1 - The OpenTool SDK for .NET Framework supports Tool Server and Client communication over the JSON-RPC protocol, implementing the core capabilities defined in the OpenTool specification.
* [LabVIEW](https://github.com/opentool-hub/opentool-labview) - The OpenTool LabVIEW SDK is used to implement an OpenTool Server within LabVIEW applications.

---

## 🛠 OpenTool Servers

### Directly Usable Tools

* [Modbus](https://github.com/opentool-hub/opentool-server-modbus) - An OpenTool-compatible Modbus client implementation that handles OpenTool requests to perform Modbus operations.
* [PTY](https://github.com/opentool-hub/opentool-server-pty) - A pseudo-terminal (PTY) implementation for OpenTool. This server handles OpenTool requests by executing commands via a pseudo-terminal.
* [Serial Port](https://github.com/opentool-hub/opentool-server-serial-port) - A serial port implementation for OpenTool, enabling serial port access through the OpenTool protocol.
* [NI VISA](https://github.com/opentool-hub/opentool-server-ni-visa) - An NI VISA interface for OpenTool, enabling access to NI VISA through the OpenTool protocol.

### Protocol Conversion Tools

* [MCP HTTP](https://github.com/opentool-hub/opentool-server-mcp-http) - An OpenTool-compatible MCP HTTP client implementation that handles OpenTool requests to perform MCP HTTP operations.
* [MCP STDIO](https://github.com/opentool-hub/opentool-server-mcp-stdio) - An OpenTool-compatible MCP STDIO client implementation that handles OpenTool requests to perform MCP STDIO operations.

### Forwarding Tools

* [WebSocket Proxy](https://github.com/opentool-hub/opentool-server-websocket-proxy) - A WebSocket proxy for OpenTool that enables browsers to receive OpenTool call pushes.
* [MQTT Proxy](https://github.com/opentool-hub/opentool-server-mqtt-proxy) - An MQTT proxy for OpenTool that enables MQTT Device to receive OpenTool call pushes.

---

## ⚙️ Management Utilities

* [OpenTool Daemon](https://github.com/opentool-hub/opentool-util-daemon) - OpenTool Daemon provides a local persistent service for managing OpenTool Server instances. It listens on a local port and exposes HTTP endpoints for CLI or other frontend applications.
* [OpenTool CLI](https://github.com/opentool-hub/opentool-util-cli) - A command-line interface (CLI) to access the OpenTool Daemon Server for managing native OpenTool Servers.

---

## 🤝 Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for details before submitting a pull request.

Guidelines:

* Add entries in **alphabetical order**
* Use the format: `- [Name](Link) - Short description`
* Keep descriptions concise and free from marketing language

---

## 📜 License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)

This work is licensed under **CC0 1.0 Universal (Public Domain Dedication)**.
