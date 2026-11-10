# weaviate

[中文版本](./README.cn.md)

Weaviate is an open-source vector database that stores both objects and vectors, allowing for the combination of vector search with structured filtering with the fault tolerance and scalability of a cloud-native database​.

[![x-cmd/install — weaviate Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/weaviate.svg)](https://x-cmd.com/install/weaviate)

## Install

```sh
x install weaviate
```

## Code insight

Total: **1,255,945** lines of code across **5824** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 1,193,180 | 203,659 | 193,837 | 5661 |
| Json | 31,126 | 0 | 0 | 31 |
| Python | 14,037 | 1,002 | 2,126 | 54 |
| AssemblyGAS | 7,113 | 383 | 491 | 37 |
| Sh | 4,188 | 592 | 656 | 41 |

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

- **Latest**: `v1.40.4` (2026-11-05)
- **Last commit**: 2026-11-10
- **Assets in release**: 9

## Popularity

- **Stars**: 16,945 · **Forks**: 1,434 · **Open issues**: 2,942 · **Contributors**: 166

## Totals (cumulative)

- **Releases**: 612 · **Merged PRs**: 8451 · **Open PRs**: 337 · **Closed issues**: 2432 · **Open issues**: 510 · **Commits**: 31908

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-11 | 14 | 188 | 80 | 3 | 25 | 692 |
| last60d | 2026-09-11 | 33 | 504 | 133 | 8 | 44 | 2215 |
| 90d | 2026-08-12 | 43 | 776 | 164 | 12 | 101 | 3778 |
| last180d | 2026-05-14 | 83 | 1624 | 293 | 53 | 186 | 7269 |
| 360d | 2025-11-15 | 100 | 2795 | 322 | 79 | 213 | 11183 |
| last720d | 2024-11-20 | 100 | 5210 | 336 | 190 | 308 | 16838 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [weaviate-v1.40.4-darwin-all.zip](https://github.com/weaviate/weaviate/releases/download/v1.40.4/weaviate-v1.40.4-darwin-all.zip) | 161.0 MiB | `native/darwin/x64` |
| [weaviate-v1.40.4-darwin-all.zip.md5](https://github.com/weaviate/weaviate/releases/download/v1.40.4/weaviate-v1.40.4-darwin-all.zip.md5) | 33 B | `native/darwin/x64` |
| [weaviate-v1.40.4-darwin-all.zip.sha256](https://github.com/weaviate/weaviate/releases/download/v1.40.4/weaviate-v1.40.4-darwin-all.zip.sha256) | 65 B | `native/darwin/x64` |
| [weaviate-v1.40.4-linux-amd64.tar.gz](https://github.com/weaviate/weaviate/releases/download/v1.40.4/weaviate-v1.40.4-linux-amd64.tar.gz) | 81.4 MiB | `native/linux/x64` |
| [weaviate-v1.40.4-linux-amd64.tar.gz.md5](https://github.com/weaviate/weaviate/releases/download/v1.40.4/weaviate-v1.40.4-linux-amd64.tar.gz.md5) | 33 B | `native/linux/x64` |
| [weaviate-v1.40.4-linux-amd64.tar.gz.sha256](https://github.com/weaviate/weaviate/releases/download/v1.40.4/weaviate-v1.40.4-linux-amd64.tar.gz.sha256) | 65 B | `native/linux/x64` |
| [weaviate-v1.40.4-linux-arm64.tar.gz](https://github.com/weaviate/weaviate/releases/download/v1.40.4/weaviate-v1.40.4-linux-arm64.tar.gz) | 77.7 MiB | `native/linux/arm64` |
| [weaviate-v1.40.4-linux-arm64.tar.gz.md5](https://github.com/weaviate/weaviate/releases/download/v1.40.4/weaviate-v1.40.4-linux-arm64.tar.gz.md5) | 33 B | `native/linux/arm64` |
| [weaviate-v1.40.4-linux-arm64.tar.gz.sha256](https://github.com/weaviate/weaviate/releases/download/v1.40.4/weaviate-v1.40.4-linux-arm64.tar.gz.sha256) | 65 B | `native/linux/arm64` |

## Distribution status

Reported by **10** distros on [repology.org](https://repology.org/project/weaviate). **4** are ✅ on the latest upstream release, **6** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Homebrew | `1.40.4` | ✅ latest |
| Nix unstable | `1.39.2` | ⚠️ outdated |

## Improve this data

Install metadata for weaviate lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `weaviate` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/weaviate.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261110.yml` · 2026-11-10T08:12:04Z._
