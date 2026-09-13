# weaviate

[中文版本](./README.cn.md)

Weaviate is an open-source vector database that stores both objects and vectors, allowing for the combination of vector search with structured filtering with the fault tolerance and scalability of a cloud-native database​.

![weaviate](https://repo.x-cmd.io/weaviate.svg)

## Install

```sh
x install weaviate
```

## Code insight

Total: **1,133,029** lines of code across **5346** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 1,070,703 | 189,593 | 177,661 | 5185 |
| Json | 30,879 | 0 | 0 | 31 |
| Python | 14,027 | 1,001 | 2,122 | 54 |
| AssemblyGAS | 7,108 | 381 | 489 | 36 |
| Sh | 4,025 | 578 | 635 | 40 |

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

- **Latest**: `v1.39.4` (2026-09-11)
- **Last commit**: 2026-09-11
- **Assets in release**: 9

## Popularity

- **Stars**: 16,802 · **Forks**: 1,399 · **Open issues**: 2,888 · **Contributors**: 165

## Totals (cumulative)

- **Releases**: 580 · **Merged PRs**: 7905 · **Open PRs**: 277 · **Closed issues**: 2420 · **Open issues**: 468 · **Commits**: 29551

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-14 | 11 | 218 | 79 | 3 | 21 | 755 |
| last60d | 2026-07-15 | 24 | 493 | 148 | 9 | 78 | 2225 |
| 90d | 2026-06-15 | 35 | 827 | 202 | 21 | 109 | 3575 |
| last180d | 2026-03-17 | 71 | 1441 | 241 | 53 | 148 | 5677 |
| 360d | 2025-09-18 | 100 | 2561 | 265 | 83 | 181 | 9110 |
| last720d | 2024-09-23 | 100 | 5071 | 276 | 208 | 288 | 15752 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [weaviate-v1.39.4-darwin-all.zip](https://github.com/weaviate/weaviate/releases/download/v1.39.4/weaviate-v1.39.4-darwin-all.zip) | 137.3 MiB | `native/darwin/x64` |
| [weaviate-v1.39.4-darwin-all.zip.md5](https://github.com/weaviate/weaviate/releases/download/v1.39.4/weaviate-v1.39.4-darwin-all.zip.md5) | 33 B | `native/darwin/x64` |
| [weaviate-v1.39.4-darwin-all.zip.sha256](https://github.com/weaviate/weaviate/releases/download/v1.39.4/weaviate-v1.39.4-darwin-all.zip.sha256) | 65 B | `native/darwin/x64` |
| [weaviate-v1.39.4-linux-amd64.tar.gz](https://github.com/weaviate/weaviate/releases/download/v1.39.4/weaviate-v1.39.4-linux-amd64.tar.gz) | 69.6 MiB | `native/linux/x64` |
| [weaviate-v1.39.4-linux-amd64.tar.gz.md5](https://github.com/weaviate/weaviate/releases/download/v1.39.4/weaviate-v1.39.4-linux-amd64.tar.gz.md5) | 33 B | `native/linux/x64` |
| [weaviate-v1.39.4-linux-amd64.tar.gz.sha256](https://github.com/weaviate/weaviate/releases/download/v1.39.4/weaviate-v1.39.4-linux-amd64.tar.gz.sha256) | 65 B | `native/linux/x64` |
| [weaviate-v1.39.4-linux-arm64.tar.gz](https://github.com/weaviate/weaviate/releases/download/v1.39.4/weaviate-v1.39.4-linux-arm64.tar.gz) | 66.1 MiB | `native/linux/arm64` |
| [weaviate-v1.39.4-linux-arm64.tar.gz.md5](https://github.com/weaviate/weaviate/releases/download/v1.39.4/weaviate-v1.39.4-linux-arm64.tar.gz.md5) | 33 B | `native/linux/arm64` |
| [weaviate-v1.39.4-linux-arm64.tar.gz.sha256](https://github.com/weaviate/weaviate/releases/download/v1.39.4/weaviate-v1.39.4-linux-arm64.tar.gz.sha256) | 65 B | `native/linux/arm64` |

## Distribution status

Reported by **10** distros on [repology.org](https://repology.org/project/weaviate). **3** are ✅ on the latest upstream release, **7** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Homebrew | `1.39.4` | ✅ latest |
| Nix unstable | `1.39.2` | ⚠️ outdated |

## Improve this data

Install metadata for weaviate lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `weaviate` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/weaviate.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260913.yml` · 2026-09-13T05:40:30Z._
