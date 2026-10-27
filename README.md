# weaviate

[中文版本](./README.cn.md)

Weaviate is an open-source vector database that stores both objects and vectors, allowing for the combination of vector search with structured filtering with the fault tolerance and scalability of a cloud-native database​.

[![x-cmd/install — weaviate Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/weaviate.svg)](https://x-cmd.com/install/weaviate)

## Install

```sh
x install weaviate
```

## Code insight

Total: **1,219,908** lines of code across **5645** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 1,157,185 | 201,248 | 189,103 | 5484 |
| Json | 31,149 | 0 | 0 | 31 |
| Python | 14,035 | 1,002 | 2,126 | 54 |
| AssemblyGAS | 7,108 | 381 | 489 | 36 |
| Sh | 4,133 | 579 | 647 | 40 |

## OpenSSF Scorecard

Overall score: **6.7 / 10**

Lowest-scoring checks:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Security-Policy** (0/10) — security policy file not detected

## Source

- **Upstream**: <https://github.com/weaviate/weaviate>
- **Homepage**: <https://weaviate.io/developers/weaviate/>
- **License**: NOASSERTION

## Release

- **Latest**: `v1.37.18` (2026-10-25)
- **Last commit**: 2026-10-16
- **Assets in release**: 9

## Popularity

- **Stars**: 16,921 · **Forks**: 1,429 · **Open issues**: 2,926 · **Contributors**: 166

## Totals (cumulative)

- **Releases**: 606 · **Merged PRs**: 8307 · **Open PRs**: 315 · **Closed issues**: 2429 · **Open issues**: 497 · **Commits**: 31004

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-27 | 17 | 184 | 74 | 2 | 24 | 378 |
| last60d | 2026-08-28 | 30 | 496 | 121 | 6 | 48 | 1905 |
| 90d | 2026-07-29 | 41 | 758 | 163 | 12 | 102 | 3355 |
| last180d | 2026-04-30 | 80 | 1576 | 274 | 52 | 175 | 6517 |
| 360d | 2025-11-01 | 100 | 2719 | 300 | 76 | 203 | 10068 |
| last720d | 2024-11-06 | 100 | 5218 | 314 | 196 | 299 | 16450 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [weaviate-v1.40.2-darwin-all.zip](https://github.com/weaviate/weaviate/releases/download/v1.40.2/weaviate-v1.40.2-darwin-all.zip) | 139.1 MiB | `native/darwin/x64` |
| [weaviate-v1.40.2-darwin-all.zip.md5](https://github.com/weaviate/weaviate/releases/download/v1.40.2/weaviate-v1.40.2-darwin-all.zip.md5) | 33 B | `native/darwin/x64` |
| [weaviate-v1.40.2-darwin-all.zip.sha256](https://github.com/weaviate/weaviate/releases/download/v1.40.2/weaviate-v1.40.2-darwin-all.zip.sha256) | 65 B | `native/darwin/x64` |
| [weaviate-v1.40.2-linux-amd64.tar.gz](https://github.com/weaviate/weaviate/releases/download/v1.40.2/weaviate-v1.40.2-linux-amd64.tar.gz) | 70.6 MiB | `native/linux/x64` |
| [weaviate-v1.40.2-linux-amd64.tar.gz.md5](https://github.com/weaviate/weaviate/releases/download/v1.40.2/weaviate-v1.40.2-linux-amd64.tar.gz.md5) | 33 B | `native/linux/x64` |
| [weaviate-v1.40.2-linux-amd64.tar.gz.sha256](https://github.com/weaviate/weaviate/releases/download/v1.40.2/weaviate-v1.40.2-linux-amd64.tar.gz.sha256) | 65 B | `native/linux/x64` |
| [weaviate-v1.40.2-linux-arm64.tar.gz](https://github.com/weaviate/weaviate/releases/download/v1.40.2/weaviate-v1.40.2-linux-arm64.tar.gz) | 67.0 MiB | `native/linux/arm64` |
| [weaviate-v1.40.2-linux-arm64.tar.gz.md5](https://github.com/weaviate/weaviate/releases/download/v1.40.2/weaviate-v1.40.2-linux-arm64.tar.gz.md5) | 33 B | `native/linux/arm64` |
| [weaviate-v1.40.2-linux-arm64.tar.gz.sha256](https://github.com/weaviate/weaviate/releases/download/v1.40.2/weaviate-v1.40.2-linux-arm64.tar.gz.sha256) | 65 B | `native/linux/arm64` |

## Distribution status

Reported by **10** distros on [repology.org](https://repology.org/project/weaviate). **4** are ✅ on the latest upstream release, **6** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Homebrew | `1.40.2` | ✅ latest |
| Nix unstable | `1.39.2` | ⚠️ outdated |

## Improve this data

Install metadata for weaviate lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `weaviate` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/weaviate.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261027.yml` · 2026-10-27T05:42:59Z._
