# weaviate

[English version](./README.md)

Weaviate is an open-source vector database that stores both objects and vectors, allowing for the combination of vector search with structured filtering with the fault tolerance and scalability of a cloud-native database​.

![weaviate](https://repo.x-cmd.io/weaviate.svg?lang=zh)

## 安装

```sh
x install weaviate
```

## 代码规模

合计: **1,132,551** 行代码（覆盖前 5 种语言、共 **5344** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 1,070,227 | 189,495 | 177,599 | 5183 |
| Json | 30,879 | 0 | 0 | 31 |
| Python | 14,027 | 1,001 | 2,122 | 54 |
| AssemblyGAS | 7,108 | 381 | 489 | 36 |
| Sh | 4,023 | 578 | 635 | 40 |

## OpenSSF Scorecard 评分

总评分: **6.7 / 10**

评分最低的几项:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Security-Policy** (0/10) — security policy file not detected

## 源代码

- **上游仓库**: <https://github.com/weaviate/weaviate>
- **官网**: <https://weaviate.io/developers/weaviate/>
- **许可证**: NOASSERTION

## 发布

- **最新版本**: `v1.39.3` (2026-09-07)
- **最近提交**: 2026-09-10
- **Release 含资产**: 9 个

## 流行度

- **Star**: 16,799 · **Fork**: 1,399 · **开放 issue**: 2,888 · **贡献者**: 164

## 累计统计

- **发布数**: 579 · **已合并 PR**: 7895 · **开放 PR**: 268 · **已关闭 issue**: 2419 · **开放 issue**: 469 · **提交数**: 29527

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 10 | 236 | 73 | 3 | 59 | 1014 |
| last60d | 2026-07-12 | 23 | 554 | 148 | 10 | 87 | 2655 |
| 90d | 2026-06-12 | 34 | 825 | 195 | 20 | 110 | 3762 |
| last180d | 2026-03-14 | 70 | 1455 | 234 | 54 | 149 | 5777 |
| 360d | 2025-09-15 | 100 | 2584 | 256 | 82 | 182 | 9226 |
| last720d | 2024-09-20 | 100 | 5075 | 267 | 209 | 290 | 15749 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [weaviate-v1.39.3-darwin-all.zip](https://github.com/weaviate/weaviate/releases/download/v1.39.3/weaviate-v1.39.3-darwin-all.zip) | 137.2 MiB | `native/darwin/x64` |
| [weaviate-v1.39.3-darwin-all.zip.md5](https://github.com/weaviate/weaviate/releases/download/v1.39.3/weaviate-v1.39.3-darwin-all.zip.md5) | 33 B | `native/darwin/x64` |
| [weaviate-v1.39.3-darwin-all.zip.sha256](https://github.com/weaviate/weaviate/releases/download/v1.39.3/weaviate-v1.39.3-darwin-all.zip.sha256) | 65 B | `native/darwin/x64` |
| [weaviate-v1.39.3-linux-amd64.tar.gz](https://github.com/weaviate/weaviate/releases/download/v1.39.3/weaviate-v1.39.3-linux-amd64.tar.gz) | 69.6 MiB | `native/linux/x64` |
| [weaviate-v1.39.3-linux-amd64.tar.gz.md5](https://github.com/weaviate/weaviate/releases/download/v1.39.3/weaviate-v1.39.3-linux-amd64.tar.gz.md5) | 33 B | `native/linux/x64` |
| [weaviate-v1.39.3-linux-amd64.tar.gz.sha256](https://github.com/weaviate/weaviate/releases/download/v1.39.3/weaviate-v1.39.3-linux-amd64.tar.gz.sha256) | 65 B | `native/linux/x64` |
| [weaviate-v1.39.3-linux-arm64.tar.gz](https://github.com/weaviate/weaviate/releases/download/v1.39.3/weaviate-v1.39.3-linux-arm64.tar.gz) | 66.1 MiB | `native/linux/arm64` |
| [weaviate-v1.39.3-linux-arm64.tar.gz.md5](https://github.com/weaviate/weaviate/releases/download/v1.39.3/weaviate-v1.39.3-linux-arm64.tar.gz.md5) | 33 B | `native/linux/arm64` |
| [weaviate-v1.39.3-linux-arm64.tar.gz.sha256](https://github.com/weaviate/weaviate/releases/download/v1.39.3/weaviate-v1.39.3-linux-arm64.tar.gz.sha256) | 65 B | `native/linux/arm64` |

## 发行版状态

在 [repology.org](https://repology.org/project/weaviate) 上共有 **10** 个发行版报告此项目。**4** 个 ✅ 已是最新上游版本，**6** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Homebrew | `1.39.3` | ✅ latest |
| Nix unstable | `1.39.2` | ⚠️ outdated |

## 改进这些数据

weaviate 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `weaviate` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/weaviate.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T20:32:19Z._
