# Repolex Knowledge Graph of poolsideai/sturdyc

RDF knowledge graph data for [poolsideai/sturdyc](https://github.com/poolsideai/sturdyc), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download poolsideai/sturdyc
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 79cb70fafee272c1f90e356a244bec106e4c4567
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 79cb70fafee272c1f90e356a244bec106e4c4567.nq.gz
│   └── repolex
│       └── 79cb70fafee272c1f90e356a244bec106e4c4567
│           └── chunk-001.nq.gz
├── blob
│   ├── 02ac8955d86ce770f80e8b3837b06ecfc842d0c9.nq.gz
│   ├── 05657e14867bf1c3399705d4edc3bf5912442184.nq.gz
│   ├── 061bd92dc2ea1f15fdd1f139313a78405914e27f.nq.gz
│   ├── 0642a63f3edc3b9321eb1babb13ed7ed6bdecdc4.nq.gz
│   ├── 071ca7bf04dbc29f66adf637f4cb9e7388c9d3c3.nq.gz
│   ├── 09516c975de69dfe44abd023e7b380d4204426d4.nq.gz
│   ├── 0a5f577756f11df42fb8cf9b71190bb7f64c4e58.nq.gz
│   ├── 0c348eb5ea4cf0611823fc8c10d479c938064fe9.nq.gz
│   ├── 0f09c2350213852c4df131fa0aaeb6f91ee773c1.nq.gz
│   ├── 1080d71c9a46a6aa6854afb79bec0c3d71ee80f8.nq.gz
│   ├── 1360b659cb43fc6187eaafb2978f34aacd94c716.nq.gz
│   ├── 13d080afbb17eeb9fbfedf25086138629b92e063.nq.gz
│   ├── 145fbdfb3b5c7265e192ce00fb919760e107745e.nq.gz
│   ├── 18c91471812cb6f4c4e8d0fc407f70c4612e1648.nq.gz
│   ├── 2eee13fe6a2853d89678415dc0c8d7885e67f0d9.nq.gz
│   ├── 303e8fd806094eb5a077be0dbda1e2d557a8180a.nq.gz
│   ├── 356a44354f833871732bdd6138daa65164d7a781.nq.gz
│   ├── 369844ebd3afd505fd16fe9983643af5270ae610.nq.gz
│   ├── 3b10a6c9eb06197b11cc3edd7ec91e8496e14c4a.nq.gz
│   ├── 3e4c0580e8be69e1e20887baab76a1b323aaec12.nq.gz
│   ├── 4460fcc0197b43804861babffd6dd858aaad53bb.nq.gz
│   ├── 467c8f49a32f7b7579675de2e6931c2829c13dce.nq.gz
│   ├── 506c7a8673076c2a5f996f61492b01e7ec68d301.nq.gz
│   ├── 50b231fdf4a2ddb3eba72573f6c214ff950885aa.nq.gz
│   ├── 525794eb1b54f5c495a9c9365b9bf6a1ae8af4a1.nq.gz
│   ├── 58959705bfd8cd639ebc8e972f6f3aeb9d119b18.nq.gz
│   ├── 59094e261a8176c958d244800c462f705a4f319e.nq.gz
│   ├── 5c7da74ff13bc856596412f020f7d24e131c7627.nq.gz
│   ├── 61aed3b24abfb5447732f5002a13ddc7e7c32c7b.nq.gz
│   ├── 652c4239655f420a6a1a6e52a3dee98804a6bf5f.nq.gz
│   ├── 7342a204e1780e328fa50b8b496a0572a41daecd.nq.gz
│   ├── 7aaf1ab856da4731aefc435d63493c8c7466bb1a.nq.gz
│   ├── 8007ade7f5623e562e67c19d77dde619b0fb392c.nq.gz
│   ├── 81cb3d3c1f05b496bfc8795b4317c93ff6b8b325.nq.gz
│   ├── 923c5bc7b9b6f240f44c03e48e1d6de2d6230ae2.nq.gz
│   ├── 93b2912a7b837f0e69ab626fb972700548246830.nq.gz
│   ├── 9b53c604fe197b5bbd1447cee6a27d3ca4cbbeb9.nq.gz
│   ├── a683d77eabbc2f7b92102b4a0b0cd1cca7159ff4.nq.gz
│   ├── ad0049b2708566fe28e38f792bbca759f3f6d9ee.nq.gz
│   ├── b2ab12ecd0ad3f92861255f75c6a7d3392ad6892.nq.gz
│   ├── b39ec66512b1baab9cef5f6a308e82c7c339c243.nq.gz
│   ├── b8f076820f079cc26eddd5803f3c9076e9a6d966.nq.gz
│   ├── ba1fa0e62f3f70fb39a31ab48ced6eaade07f783.nq.gz
│   ├── c32c9542ec1774a50f0df43ea65b46db8d336149.nq.gz
│   ├── c525a7656667824954321e739b9856a31ca92a32.nq.gz
│   ├── c58d145b37f4b5d34412f6c31c5d31514169e1ee.nq.gz
│   ├── c7e6ddf0be0636162e3eca214c0a91bff618f2a9.nq.gz
│   ├── cfa4a9ec092b2e89906ce5a18fafe4ce56aa5da3.nq.gz
│   ├── d4a002d4c5fb4739bd6fa84e7fde2489eecb11d1.nq.gz
│   ├── dadbef8bf286cf3f700354f221b874f71774627f.nq.gz
│   ├── dcdb0420aa89afc1de9c6c8b7fae1b8c9a39364b.nq.gz
│   ├── dd99bc88d26f0741c681ff13cbdfae8fc6a5676c.nq.gz
│   ├── ea397a11f2fa2da5b61086e82869a0b58438b6f2.nq.gz
│   ├── ecde0595de766fa7a5f8a6f4513f734a4d7746ea.nq.gz
│   ├── f051ad4fd9b0eaad3902e4aa65407fe98a41f752.nq.gz
│   ├── f056e08301dc477c939319ff7bcc21b63fda416e.nq.gz
│   └── f226d6e57f30838c5896c74ef4f63590cc4164f1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 79cb70fafee272c1f90e356a244bec106e4c4567.nq.gz
├── filetree
│   └── 79cb70fafee272c1f90e356a244bec106e4c4567.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 66 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[poolsideai/sturdyc](https://github.com/poolsideai/sturdyc)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
