# 🌐 HTTP协议 · 从入门到精通

> 📘 28章 实战体系

一套完整的 **HTTP协议 · 从入门到精通** 全中文实战课程体系，共 **28 章**。本课程以 HTML 可视化的形式呈现，从基础原理到工程实践循序渐进，适合系统性学习与复习。

## 🚀 快速开始

无需安装任何依赖，直接用浏览器打开 `index.html` 即可在线阅读全部章节：

```bash
open index.html   # macOS
# 或在浏览器中直接打开 index.html
```

## 📖 章节目录

| # | 章节 | 核心主题 |
|---|------|----------|
| 01 | HTTP协议概述 | 发展历史、客户端-服务器模型、版本差异速览 |
| 02 | URL与资源定位 | URI/URL/URN、URL语法结构、URL编码规则 |
| 03 | HTTP报文结构 | 请求报文解剖、响应报文解剖、头部/消息体 |
| 04 | HTTP请求方法 | GET/POST/PUT/DELETE、安全性与幂等性、HEAD/OPTIONS |
| 05 | HTTP状态码 | 1xx~5xx分类、常用状态码详解、状态码选择实践 |
| 06 | HTTP头部字段 | 通用头/请求头/响应头、实体头/自定义头、大小写与重复 |
| 07 | MIME类型与内容协商 | MIME结构、Content-Type、Accept系列头 |
| 08 | 连接管理 | 短连接/长连接、Keep-Alive、管线化/连接池 |
| 09 | HTTP缓存 | Cache-Control、ETag/Last-Modified、缓存层级策略 |
| 10 | Cookie与会话 | Set-Cookie/Cookie、Session机制、SameSite/HttpOnly |
| 11 | HTTP认证 | Basic/Digest/Bearer、OAuth2流程、JWT结构 |
| 12 | 跨域资源共享(CORS) | 同源策略、预检请求、Access-Control头 |
| 13 | 内容编码与传输 | gzip/brotli压缩、分块传输、范围请求/断点续传 |
| 14 | 重定向与URL重写 | 301/302/307/308、Nginx rewrite、重定向循环 |
| 15 | HTTPS概述 | 对称/非对称加密、TLS握手过程、证书信任链 |
| 16 | TLS深入 | 版本演进、密码套件、前向保密/ALPN |
| 17 | 证书管理 | DV/OV/EV证书、s Encrypt",  |
| 18 | HTTP安全头部 | HSTS/CSP、X-Frame-Options、Referrer-Policy |
| 19 | 代理与网关 | 正向/反向代理、X-Forwarded-For、CDN原理 |
| 20 | 负载均衡与限流 | 负载均衡算法、Nginx upstream、限流策略 |
| 21 | RESTful API设计 | REST约束、资源建模、状态码/HATEOAS |
| 22 | HTTP性能优化 | 请求/体积优化、资源提示、HTTP/2优化差异 |
| 23 | HTTP调试工具 | curl实战、DevTools Network、Wireshark抓包 |
| 24 | Web服务器配置 | Nginx基础、HTTPS配置、日志分析 |
| 25 | HTTP抓包实战 | 抓包环境搭建、请求分析、时序图解读 |
| 26 | HTTP/2 | 二进制帧层、HPACK头部压缩、服务器推送 |
| 27 | HTTP/3 (QUIC) | UDP/QUIC基础、0-RTT连接、连接迁移 |
| 28 | HTTP项目实战 | Nginx+HTTPS搭建、安全头部验证、性能基准测试 |

## 📂 项目结构

```text
HTTP-protocol-tutorial/
├── index.html      # 课程主入口（在线阅读全部章节）
├── 01.html ~ 28.html   # 各章节正文
├── courses.json    # 课程元数据（标题/章节/主题）
└── theme.css       # 统一主题样式
```

## ✨ 课程特色

- **全中文实战体系**：面向中文读者，由浅入深，覆盖原理与工程实践
- **28 章完整内容**：系统化章节编排，形成完整知识闭环
- **可视化呈现**：HTML 图文并茂，适合快速浏览与重点回顾
- **即开即用**：无需构建、无需服务器，纯静态页面随开随看

---
*本课程由 `HTTP-protocol-tutorial/` 项目维护。*