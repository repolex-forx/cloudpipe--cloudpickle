# Repolex Knowledge Graph of cloudpipe/cloudpickle

RDF knowledge graph data for [cloudpipe/cloudpickle](https://github.com/cloudpipe/cloudpickle), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download cloudpipe/cloudpickle
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7576fff24b9769432f76cc6d2c01282583ee87a9
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7576fff24b9769432f76cc6d2c01282583ee87a9.nq.gz
│   └── repolex
│       └── 7576fff24b9769432f76cc6d2c01282583ee87a9
│           └── chunk-001.nq.gz
├── blob
│   ├── 026737e1fc4dbbd8ee12ba986f54adddbc5c1c1c.nq.gz
│   ├── 0f6019d4f0058a1b9874b7bc2e86bbd00b6b5e4f.nq.gz
│   ├── 10cd20ec6e94d4be133198119edc4c7495a1514d.nq.gz
│   ├── 1153fcb5c072809278349049c4cbebb34a41ec64.nq.gz
│   ├── 12df590384720b3330b9b78c5f7cee85ec7bbb03.nq.gz
│   ├── 13175fdc437138f09019c0688f900c1c227be1e9.nq.gz
│   ├── 1c41f5346504ce06af8d8835732c50e8ab60dd88.nq.gz
│   ├── 1d1d70a92a5369e427312627e238c445278ef239.nq.gz
│   ├── 1e9dcd0621b1a253ff5c1e5b856b50149dabe060.nq.gz
│   ├── 1fe67c53a35d801a7e870793fe0e31632a253db1.nq.gz
│   ├── 20280f0ca354a691861ab6f17821bbeb04632003.nq.gz
│   ├── 2051e4c0662d978de6df9a37e1bccc3cd96cf010.nq.gz
│   ├── 2f8f9f9557d424b8e4ed0d9b355b0c612bce31eb.nq.gz
│   ├── 31aae20ea570abd6e5df7877ad4e0b740eb4ee59.nq.gz
│   ├── 34d515dc3158b0f9e57588382af9cc12e72fd08e.nq.gz
│   ├── 35c529fe62a1aab8396e0ab6726167212317a6e9.nq.gz
│   ├── 403b69f7609a6299cbe6459ea96556ff0ff849e8.nq.gz
│   ├── 45c99738525fc99596c1d8e83ff813a7a97c5471.nq.gz
│   ├── 4ca72f5c50d09ea63a0d8114f84c18c5e9350c7d.nq.gz
│   ├── 4e49b68540e41f6650f67ee38dbb6751aed5598a.nq.gz
│   ├── 50e430ef2ed5c0c17d0e746d840c7bb1dbc6ef3f.nq.gz
│   ├── 517c5db57f5ae4b57d9444795ace6af9e5afc431.nq.gz
│   ├── 517d5013de93d874295d9c67120723c3e8736bb7.nq.gz
│   ├── 56c5e1839134aaa6d863285a6dfd2ba532610aec.nq.gz
│   ├── 62226000178be818cc0fc0fb4e7d151939b0693c.nq.gz
│   ├── 71579a85caf3f4ab7a26aa477b8c94514e2dab81.nq.gz
│   ├── 7319d359a5e8f3a982e2beda4c67d3912dfb3996.nq.gz
│   ├── 74f5b2004382cc0940f84825045e2235ee3b1ed2.nq.gz
│   ├── 7b9cb74939d217fce8b9256e6606c77fedb5f44f.nq.gz
│   ├── 7e8053d90207f5f323d8f28aa6cfad1df6c1c088.nq.gz
│   ├── 81c8abff840b8104458759a6b1735983fb1d1731.nq.gz
│   ├── 8b1b613b51a82c85fe249693997e7bff456189d6.nq.gz
│   ├── 8d9591a1bd7325179256f298ee0a5e92f3077918.nq.gz
│   ├── 91ad4c02750b062e21e80f1b6a6d6f121134fc2f.nq.gz
│   ├── 9bac7d4097a0f0f1f043a67da14a0a6313a10d62.nq.gz
│   ├── 9faf0b6d81e958a7c41da4d920a5b77a2548b526.nq.gz
│   ├── a4fcaff70cc8961be01b6217ad0bf68681e3367e.nq.gz
│   ├── a5f850623abe2833cca4ae844ca5eb889f83e4f3.nq.gz
│   ├── a7becfb44739735271ebd7494578aa2edfd35d0d.nq.gz
│   ├── a842ce961acfe5e678a230b30f06fd539f8b3051.nq.gz
│   ├── a9d3eded3b11505c61cc6cd2978bcc506be09fad.nq.gz
│   ├── aaee1f0c0887137da702d77643e9576bf4230a21.nq.gz
│   ├── bf2d3bcadc256af4d0f4f31fb30a6e45af128f9e.nq.gz
│   ├── ca9dcc4f80a777ff67a1c89e33884a785bc7371e.nq.gz
│   ├── cba8b326134fbe17689c32dd38ae3d63f676b07c.nq.gz
│   ├── cd9f0fba6ff73bb344188342103970c4b25c4394.nq.gz
│   ├── ce260e4091934ef100cb70f9f4f141fd78943339.nq.gz
│   ├── ce26d9a195894f5e0ca2b6d9a15c7832ccbea2b3.nq.gz
│   ├── d112c4806aa90b4c911b360fa0ce1d0ee7c031ce.nq.gz
│   ├── d331a249b2c8e0dfb7645f40481fa40f2a0fd456.nq.gz
│   ├── db284fe24de58489d7296430f7f1e73f4e0a9ea0.nq.gz
│   ├── dd1f6a55471bd89527170befaebd33d1f5673e0c.nq.gz
│   ├── deebc1477809d036169561a8e9997d7fb6fc03f6.nq.gz
│   ├── df46ab6a5b0062eab312e7b52f4e693cf5fa9f38.nq.gz
│   ├── e38daca87729dcb72059b5268bc41314ec8fab89.nq.gz
│   ├── e600b35f28422096173a783380ec912a66b453cf.nq.gz
│   ├── f35182765b99002cb4df44f66e64f1c0282b8919.nq.gz
│   ├── f38cdb7014ee666ff2de639ff6f55001f1690bf7.nq.gz
│   ├── f9400f2434132eb509e38cbd5a8668686088bb63.nq.gz
│   ├── fae692e41d4f76365046a2c9da3349f2f6f1384d.nq.gz
│   └── ff80777040c1ed8a307f0dc0473b4ba31338c0b0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 7576fff24b9769432f76cc6d2c01282583ee87a9.nq.gz
├── filetree
│   └── 7576fff24b9769432f76cc6d2c01282583ee87a9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 71 files
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

## Source repository

[cloudpipe/cloudpickle](https://github.com/cloudpipe/cloudpickle)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
