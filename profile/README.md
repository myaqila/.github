# AQILA

**AQILA. Your IT companion.**

GitHub org for the AQILA platform and every AQILA-hosted client site. Linear stays on workspace **ssqinc**. SSQ product repos (Keera, Dryynk, Hajzi, Shams, Mawsel, Qudsbus, Neotracker) stay on `ssqInfo`.

## Map

Local workspace parent is `Documents/Code/aqila/` (after Phase 0). Disk folder = GitHub repo = slug.

### Platform

| Folder | GitHub | Notes |
| --- | --- | --- |
| `platform/` | [`myaqila/aqila`](https://github.com/myaqila/aqila) | Monorepo until the app/SDK split. Holds `aqila-app/`, `aqila-site/`, `aqila-demo/`, `aqila-mobile/`, `aqila-video/`, `packages/` |

### Clients

| Folder | GitHub | Worker root |
| --- | --- | --- |
| `clients/aywa/` | [`myaqila/aywa`](https://github.com/myaqila/aywa) | `aywa-site/` |
| `clients/ssqinc/` | [`myaqila/ssqinc`](https://github.com/myaqila/ssqinc) | `website/` |
| `clients/mpactx/` | [`myaqila/mpactx`](https://github.com/myaqila/mpactx) | `mpactx-website/` |
| `clients/jcu/` | [`myaqila/jcu`](https://github.com/myaqila/jcu) | `jcu-site/` |
| `clients/mend/` | [`myaqila/mend`](https://github.com/myaqila/mend) | `mend-website/` |
| `clients/khashaba/` | [`myaqila/khashaba`](https://github.com/myaqila/khashaba) | `khashaba-website/` |
| `clients/talinesharaf/` | [`myaqila/talinesharaf`](https://github.com/myaqila/talinesharaf) | `frontend/` |
| `clients/kevoze/` | [`myaqila/kevoze`](https://github.com/myaqila/kevoze) | `frontend/` |
| `clients/timeout/` | [`myaqila/timeout`](https://github.com/myaqila/timeout) | `timeout-website/` |
| `clients/fadimurad/` | [`myaqila/fadimurad`](https://github.com/myaqila/fadimurad) | `frontend/` |
| `clients/astrid/` | [`myaqila/astrid`](https://github.com/myaqila/astrid) | `astrid-portfolio/` |
| `clients/albright/` | [`myaqila/albright`](https://github.com/myaqila/albright) | `albright-site/` |
| `clients/skafieng/` | [`myaqila/skafieng`](https://github.com/myaqila/skafieng) | `skafieng-site/` |
| `clients/cfi/` | [`myaqila/cfi`](https://github.com/myaqila/cfi) | `cfi-site/` |
| `clients/hr-engine/` | [`myaqila/hr-engine`](https://github.com/myaqila/hr-engine) | `hr-engine-site/` |

## Teams

- **platform** — AQILA product repos
- **clients** — client site repos

Packages `@myaqila/cms` and `@myaqila/analytics` live on this org. Client CI in the same org can read them with `GITHUB_TOKEN`.
