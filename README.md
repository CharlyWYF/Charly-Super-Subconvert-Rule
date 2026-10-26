# Charly Super Subconvert Rule

基于 [ACL4SSR Online Full MultiMode](https://github.com/ACL4SSR/ACL4SSR) 定制的 subconverter 分流模板。

## 主要定制

- AI 平台默认走日本节点。
- 🎓 东南大学：匹配 `seu.edu.cn` 及其子域名，默认直连。
- 提供 12 个国家和地区分组，支持自动测速、故障转移和负载均衡。

## 使用方法

在兼容 subconverter 的订阅转换前端中，填写自己的订阅地址，并将以下任一链接填入「远程配置」，生成配置后导入客户端。

### 普通版

模板及引用的规则通过 GitHub Raw 下载。

```text
https://raw.githubusercontent.com/CharlyWYF/Charly-Super-Subconvert-Rule/main/CW-MultiMode.ini
```

### 镜像版

模板及引用的规则通过 GH-Proxy 下载，适合后端访问 GitHub Raw 不畅时尝试。可用性取决于后端网络和镜像服务。

```text
https://gh-proxy.org/https://raw.githubusercontent.com/CharlyWYF/Charly-Super-Subconvert-Rule/main/CW-MultiMode-mirror.ini
```

本仓库仅提供规则模板，需要自备订阅和支持相应节点协议的转换后端。上述链接用于「远程配置」，不能直接作为节点订阅导入客户端。
