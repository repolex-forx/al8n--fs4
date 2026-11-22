# Repolex Knowledge Graph of al8n/fs4

RDF knowledge graph data for [al8n/fs4](https://github.com/al8n/fs4), parsed by [repolex](https://repolex.ai).

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
rlex download al8n/fs4
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5f81cf254d3e1db4a98a9a49723b7405a4d3e383
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 5f81cf254d3e1db4a98a9a49723b7405a4d3e383.nq.gz
│   └── repolex
│       └── 5f81cf254d3e1db4a98a9a49723b7405a4d3e383
│           └── chunk-001.nq.gz
├── blob
│   ├── 04f14e94b88fc256020abd54a0032aa0c0ab0a44.nq.gz
│   ├── 0959ab9643764f748e61061afa02ecd9200ca601.nq.gz
│   ├── 0db1a2db7d46fd6289504fe25cc907fabb042b0f.nq.gz
│   ├── 116653a0b14665185179dff247ee81ad020bf295.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 1830aba3881d76d8a0a5e283358ef1122f0ee824.nq.gz
│   ├── 195f5dafbba664ddb26bf3ec5a758863cda45465.nq.gz
│   ├── 21fdf08310aca8c6afa6bb6d0689b1f47eb3c843.nq.gz
│   ├── 24ea5a28287bd515f0275f3e9faa2bd09f54b9e7.nq.gz
│   ├── 26d33b97f09e350a2830d8b5a4cfcd04173e2d8f.nq.gz
│   ├── 29ccec77b920bbbf4bdaa8648f086f90b68a8cfa.nq.gz
│   ├── 2ba84074f1c7a3e5778103a8ce5d6e211b203e18.nq.gz
│   ├── 318cdf49b7dbcae23cf81b7dfd84ac4b73c69fea.nq.gz
│   ├── 385d9ac4f763a5052918b8735eb44f65afe23511.nq.gz
│   ├── 3941323f71dad682927813df40a9af17a048f0f3.nq.gz
│   ├── 395b95de269acb10a3eed2baaa22607b5c45964d.nq.gz
│   ├── 437a4c47587d853380bf9252c07d013f84cadc43.nq.gz
│   ├── 43f8a6da82aaab799586a56d2981c5a3d5832d8c.nq.gz
│   ├── 5012cc17a566fb0a4cc92bd3dde8ea3665086247.nq.gz
│   ├── 58a32f185c78b89d1126d6d93d14d26ae17888bd.nq.gz
│   ├── 5a9c842f7d24ce3df5dbb3a7fa18c73c13e00880.nq.gz
│   ├── 5b93271999336f579beb4f363a062c49d39930b7.nq.gz
│   ├── 5f7e92718c655e96e9569382d3810dd5a746f7b4.nq.gz
│   ├── 614d0eb15e3c8a34bced26920e1f96943794e766.nq.gz
│   ├── 6356935d25af1e4171add58f7678c13a7c1a0b71.nq.gz
│   ├── 68a0355ae04b5fa384f5a3824bdae7bca0faddab.nq.gz
│   ├── 6b151c0b9babf05dfd63903b66ed97478b4ff493.nq.gz
│   ├── 6f794a0d63629fae8d217e1f1a404e9df46d3b8e.nq.gz
│   ├── 72273d722915264958b9cc2587a408522e0af468.nq.gz
│   ├── 74058f7afb813443b72577c9e321f2e28d4b9a2e.nq.gz
│   ├── 7c8eb718e61c8376315f2cc1564e6a7b273d94b3.nq.gz
│   ├── 8298ecb6bb5e6a7c86557eee76101696db088d72.nq.gz
│   ├── 82c8c310a3ca5cac144769ce81d3d27ae1bcdfb9.nq.gz
│   ├── 8d70b4efa5f8b032497375f54c3fed4555c6bbf7.nq.gz
│   ├── 8ef8f2cfa945e64bd529461c82a21cdbd22dc5c0.nq.gz
│   ├── 943eb92d249631ee5e15ebc0240470d3b6d8fe72.nq.gz
│   ├── 9594411f8c8e92cf19adfccab44cf09cacddb0e0.nq.gz
│   ├── a25833ce77b2868ec7864d4a7e335c91c2caa38f.nq.gz
│   ├── ad6ff76b126b7f0583a03f4025385695d8a23e54.nq.gz
│   ├── b0e5e2aef893e8372f2808ad35fd6546d56c6f06.nq.gz
│   ├── c8d2872c079ade1ab7f59d2281c1b3a80d18a348.nq.gz
│   ├── cfd0fa0f0d49eb10eeff088226f119eee25b2010.nq.gz
│   ├── d111899a228e82b06fc0930ff0046fbecf0ee07d.nq.gz
│   ├── d13522c6b7941745cfb26bb48bd5cbbab34779ab.nq.gz
│   ├── da9b49447ede2b4ac2206a12f8ebab6591fbcac6.nq.gz
│   ├── deee6b1d5bbe3870783c479d9fe68789bea5ebfe.nq.gz
│   ├── e3741ebc3084a6f47277d0e11cf1ea5e3902e514.nq.gz
│   ├── e3f5f1f7883409e30ede44451680965a64ad8d25.nq.gz
│   ├── e69282e381bc07152cc7598f21f3162e4bbb1f22.nq.gz
│   └── fa98a16054c063eeeda37e98af85e74fffa456ff.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 5f81cf254d3e1db4a98a9a49723b7405a4d3e383.nq.gz
├── filetree
│   └── 5f81cf254d3e1db4a98a9a49723b7405a4d3e383.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 60 files
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

[al8n/fs4](https://github.com/al8n/fs4)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
