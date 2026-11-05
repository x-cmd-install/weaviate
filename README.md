# weaviate

[中文版本](./README.cn.md)

Weaviate is an open-source vector database that stores both objects and vectors, allowing for the combination of vector search with structured filtering with the fault tolerance and scalability of a cloud-native database​.

[![x-cmd/install — weaviate Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/weaviate.svg)](https://x-cmd.com/install/weaviate)

## Install

```sh
x install weaviate
```

## Code insight

Total: **1,235,980** lines of code across **5735** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 1,173,621 | 199,793 | 190,989 | 5573 |
| Json | 30,733 | 0 | 0 | 31 |
| Python | 14,037 | 1,002 | 2,126 | 54 |
| AssemblyGAS | 7,108 | 381 | 489 | 36 |
| Sh | 4,181 | 590 | 655 | 41 |

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

- **Latest**: `v1.39.15` (2026-11-04)
- **Last commit**: 2026-11-04
- **Assets in release**: 9

## Popularity

- **Stars**: 16,937 · **Forks**: 1,433 · **Open issues**: 2,935 · **Contributors**: 166

## Totals (cumulative)

- **Releases**: 611 · **Merged PRs**: 8406 · **Open PRs**: 330 · **Closed issues**: 2432 · **Open issues**: 503 · **Commits**: 31618

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-06 | 18 | 174 | 66 | 3 | 18 | 651 |
| last60d | 2026-09-06 | 35 | 527 | 130 | 8 | 46 | 2340 |
| 90d | 2026-08-07 | 42 | 774 | 170 | 14 | 102 | 3994 |
| last180d | 2026-05-09 | 83 | 1625 | 287 | 55 | 181 | 7160 |
| 360d | 2025-11-10 | 100 | 2763 | 315 | 79 | 208 | 10930 |
| last720d | 2024-11-15 | 100 | 5206 | 329 | 192 | 303 | 16676 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [weaviate-v1.40.3-darwin-all.zip](https://github.com/weaviate/weaviate/releases/download/v1.40.3/weaviate-v1.40.3-darwin-all.zip) | 145.4 MiB | `native/darwin/x64` |
| [weaviate-v1.40.3-darwin-all.zip.md5](https://github.com/weaviate/weaviate/releases/download/v1.40.3/weaviate-v1.40.3-darwin-all.zip.md5) | 33 B | `native/darwin/x64` |
| [weaviate-v1.40.3-darwin-all.zip.sha256](https://github.com/weaviate/weaviate/releases/download/v1.40.3/weaviate-v1.40.3-darwin-all.zip.sha256) | 65 B | `native/darwin/x64` |
| [weaviate-v1.40.3-linux-amd64.tar.gz](https://github.com/weaviate/weaviate/releases/download/v1.40.3/weaviate-v1.40.3-linux-amd64.tar.gz) | 73.7 MiB | `native/linux/x64` |
| [weaviate-v1.40.3-linux-amd64.tar.gz.md5](https://github.com/weaviate/weaviate/releases/download/v1.40.3/weaviate-v1.40.3-linux-amd64.tar.gz.md5) | 33 B | `native/linux/x64` |
| [weaviate-v1.40.3-linux-amd64.tar.gz.sha256](https://github.com/weaviate/weaviate/releases/download/v1.40.3/weaviate-v1.40.3-linux-amd64.tar.gz.sha256) | 65 B | `native/linux/x64` |
| [weaviate-v1.40.3-linux-arm64.tar.gz](https://github.com/weaviate/weaviate/releases/download/v1.40.3/weaviate-v1.40.3-linux-arm64.tar.gz) | 70.1 MiB | `native/linux/arm64` |
| [weaviate-v1.40.3-linux-arm64.tar.gz.md5](https://github.com/weaviate/weaviate/releases/download/v1.40.3/weaviate-v1.40.3-linux-arm64.tar.gz.md5) | 33 B | `native/linux/arm64` |
| [weaviate-v1.40.3-linux-arm64.tar.gz.sha256](https://github.com/weaviate/weaviate/releases/download/v1.40.3/weaviate-v1.40.3-linux-arm64.tar.gz.sha256) | 65 B | `native/linux/arm64` |

## Distribution status

Reported by **10** distros on [repology.org](https://repology.org/project/weaviate). **4** are ✅ on the latest upstream release, **6** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Homebrew | `1.40.3` | ✅ latest |
| Nix unstable | `1.39.2` | ⚠️ outdated |

## Improve this data

Install metadata for weaviate lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `weaviate` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/weaviate.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261105.yml` · 2026-11-05T07:27:19Z._
