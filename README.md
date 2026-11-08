# Repolex Knowledge Graph of modal-labs/vhost

RDF knowledge graph data for [modal-labs/vhost](https://github.com/modal-labs/vhost), parsed by [repolex](https://repolex.ai).

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
rlex download modal-labs/vhost
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e50f1d8ae24378932229d2d884c7d2ecf72cd2e8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e50f1d8ae24378932229d2d884c7d2ecf72cd2e8
│           └── chunk-001.nq.gz
├── blob
│   ├── 028de6e59d45e16dc3a2234f98a09a5c4afde4fe.nq.gz
│   ├── 04f42c84c07c3ceae6570821ffddb8a35fbfbe9c.nq.gz
│   ├── 06a5e47f1ad1deceeea346840db3cc1105ee143a.nq.gz
│   ├── 1047b8530c073a039f77af41558dfc738dcfb650.nq.gz
│   ├── 1393cf38dc181b96f3c59cd3c7b640bea3bf301b.nq.gz
│   ├── 1e1b0b9b5b97ae2ec3d732392e03bc1ec370d0e4.nq.gz
│   ├── 1e44568390c464ad2f4a3f2a05caf2fc93c60464.nq.gz
│   ├── 1e735a2db81d799e4935cf99875eb742d5fb7746.nq.gz
│   ├── 1ff0cd75ee29683f98e6225ccf4c619e6d3d4d66.nq.gz
│   ├── 37675b73db2b1ad5322f91fc2af80006411d683f.nq.gz
│   ├── 3b28bcfc1890ac85c198f1e610102c8d8ab902e8.nq.gz
│   ├── 3d8813eed7abcf08dd1d637f391a71472be40112.nq.gz
│   ├── 43073a5942cacc9b09555bd1b4652ef5adf7607a.nq.gz
│   ├── 45d9b6ce319978a3d1a4a8b343a2582d91617176.nq.gz
│   ├── 46b771ce7f32b422fede24a4a6cbd0cc72c63e01.nq.gz
│   ├── 4c50ad0da1393a9a6ee498f95dbed83f60692e8c.nq.gz
│   ├── 4d1e2bc07d1ec72ede0862e9898b48421f243a49.nq.gz
│   ├── 506938ed7e80cc86d0655b6acb1062849f98acda.nq.gz
│   ├── 545ef38002624d10307db73b6dc5564538977b7a.nq.gz
│   ├── 569f34e1e9aac69bce0344e0a094e2273ae2e47d.nq.gz
│   ├── 5d0a9fd6164530a84542e538fa8dcd4334f6bbe9.nq.gz
│   ├── 5e561101527a708f20d82eeb7465038ff89c2861.nq.gz
│   ├── 610aff41f29b4d57d609dc1fc54544886279dcc0.nq.gz
│   ├── 65f6e17803536a0913aa4fcb0472932e2cd3e433.nq.gz
│   ├── 69baec2f9af6cbd14c03db2aafb90e48042c096b.nq.gz
│   ├── 6af01cf309a6427452746d5b0a9a31817abe841f.nq.gz
│   ├── 6be26f20d487f4cbc8deb5e932385b58fdcdc355.nq.gz
│   ├── 71eca74c23662f474edbfe4508fac17a94784ebd.nq.gz
│   ├── 834fed4af2f9fb3b23954c89919680060c9d001a.nq.gz
│   ├── 8381ab923c7a7257b1e3355cfa8adb59b29a4e77.nq.gz
│   ├── 93d0b6d9bd0f5ecc3f7ac5a24635894a9ade5429.nq.gz
│   ├── bda97eb3542ee2af4e83b535e31117f060bd771c.nq.gz
│   ├── beb4bc62a38fcc1f15f7962607819c00a4c07352.nq.gz
│   ├── bf8523e02f4c62f0cb15351791936e26174d4f33.nq.gz
│   ├── c721435e55fe1fe7560b3be661380c017aba2ee3.nq.gz
│   ├── c8fcbdd92bc7e86af38e55e69fda16de52d2e3d1.nq.gz
│   ├── d2887562e0553fbb1cf9283ff45c214fc67bbfab.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d98591824bec99b043490637e903af07589d0278.nq.gz
│   ├── dc4bea42c97f6025003f3155b9d4321caeeb8dbd.nq.gz
│   ├── dd2488cd48518d2c9c0c32bbbc80a3c555180376.nq.gz
│   ├── e0a1d38f67c604983e6c07998cfd185f0e9d8b5c.nq.gz
│   ├── e17cee7c5b016882240b494460b9a61179166be2.nq.gz
│   ├── e3d85011eb19e10456bd3006fade85ae6830b53a.nq.gz
│   ├── e6f3d1e66e220c9454bac7b46e8dce25b3eec32a.nq.gz
│   ├── ea5ba1fcba76b32e6e85d23bb81448388be5dbcf.nq.gz
│   ├── f738aa84a65cbb7c4d62ab93eedd77811eee1ccf.nq.gz
│   └── fd42c7cca30a0d6ab539fac3d172d9b7df65490a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e50f1d8ae24378932229d2d884c7d2ecf72cd2e8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 56 files
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

[modal-labs/vhost](https://github.com/modal-labs/vhost)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
