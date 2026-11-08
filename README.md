# Repolex Knowledge Graph of UKPLab/arXiv2026-uncertainty-aware

RDF knowledge graph data for [UKPLab/arXiv2026-uncertainty-aware](https://github.com/UKPLab/arXiv2026-uncertainty-aware), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/arXiv2026-uncertainty-aware
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ab400614f515cb72956304b95758ece1b9829012
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ab400614f515cb72956304b95758ece1b9829012
│           └── chunk-001.nq.gz
├── blob
│   ├── 0d03bf268c448d14aeb9becbc045bcde4ae6c9b7.nq.gz
│   ├── 0d39a67c24f01c1af1e9cb675f380c3a1d1b2422.nq.gz
│   ├── 0d9360dc35d158ea1ccd025d9520994762579eec.nq.gz
│   ├── 0da4f4b6f7c6f6f263586c780fd221104a59dad9.nq.gz
│   ├── 120c6893b8af8f69dddc51b2734ed561b78c6091.nq.gz
│   ├── 14411fd93d699377c6e17280cabaf9a39d67dbdc.nq.gz
│   ├── 18601e688ebb0cd737df79d10a53ff7b90eafed1.nq.gz
│   ├── 1b047d26352c602b1aa3ad192574cbd685ccd067.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 2d90f3a212a263f9169f577df9e375cf429b70a1.nq.gz
│   ├── 2dc2a8fa00f487a8b3db7731a440640af682db3d.nq.gz
│   ├── 309ac928c3e738e97a0433e98bf3387ad72fbd45.nq.gz
│   ├── 3dc429a6613bf85898a47643fe31d4439fe9d973.nq.gz
│   ├── 4003b3efdaaf1b47494a98c42e67ff429515345a.nq.gz
│   ├── 45c94f6d8e39f3b7ace728febbb20e6294eff290.nq.gz
│   ├── 4cef27e61ea9ac6f982e68a89dcb12432298bb71.nq.gz
│   ├── 4f4aa985e37fc585138faafffbaf22de03840d0b.nq.gz
│   ├── 5479ab2290a8d882677648b008d488be97d83883.nq.gz
│   ├── 54e057d26522075e7b5abb29c3c22ca36274e711.nq.gz
│   ├── 556a15fa8556b8385ec37e53ac3a8ee1ff984b21.nq.gz
│   ├── 56199b8900c0a8afeb4a2269f7ab3f4bf2eb5e5c.nq.gz
│   ├── 5dcef726f671e400c7a0873dc8e9d9f061889630.nq.gz
│   ├── 5e2f2bfc5d841e26012f3860e2b3d9959a0b41d1.nq.gz
│   ├── 5ee03113d48cffc852f89a3f0c294f73686603f2.nq.gz
│   ├── 663e946086ae449c56688cf207f37d2fcb5dc287.nq.gz
│   ├── 682747d55a9e401d87bc134341d339ea5811f9db.nq.gz
│   ├── 68eb69b23434984ce6053d307b6b6b7f709a7e7e.nq.gz
│   ├── 698e9f972a96948e15606d89ceda254e571d2692.nq.gz
│   ├── 6a171a558f6a2db926e56026b27c8a2cc3de9a48.nq.gz
│   ├── 72ee670569fc56fbd9c71c0a9752f9b2ee174c0a.nq.gz
│   ├── 765f7fd7479d9b5142d3feb001d022d52f4eb61b.nq.gz
│   ├── 7ecc6ac770a62294c02eccbb272ff361816bfd43.nq.gz
│   ├── 80f9dedb22582266a9daa4b5a74a2b7ef60f99a4.nq.gz
│   ├── 829cafe545fbc5b6a622128620b975639019a6ef.nq.gz
│   ├── 88602b3730084b3ce32b7dc437a161fa992753b4.nq.gz
│   ├── 8871abfdc9c3745a372d1b55952f4d24481e3ea0.nq.gz
│   ├── 89f79d04b69ed907c42ae436aa16e9cfa7cfd9bf.nq.gz
│   ├── 8a32ee34b1603953ed79a91dec01453f67fb93c4.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8b14d41f730e3642c5986d15e956bb8af5134367.nq.gz
│   ├── 8dac209865b12ea365cfc7792afe1ac6b87e1ee9.nq.gz
│   ├── 99cbf04b592178574d2608b3fc03c3b1113f15f1.nq.gz
│   ├── 9b3703a912d40f58fb0fb57d20742e53d9fe7671.nq.gz
│   ├── 9ccc7363dcc9155dec920e64a9820737d3fff0e3.nq.gz
│   ├── a6112cb41380bf508dc0716db9edfd4c35f6591b.nq.gz
│   ├── a70d291241eea483a3e2ca58d7c779b17cc164b8.nq.gz
│   ├── aa32243e8c9d3c58a6841382e0fe99b070118699.nq.gz
│   ├── aad994aa50cb5cda46936c1dc221ae914805214d.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c3b0e3794ef28f22adb871d69f41e454a05ef7c9.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── c7a351776c6d721e4c4b745d42d4091fc5346cc1.nq.gz
│   ├── cc98b6933cd0df2705fd39225f24282258cd3685.nq.gz
│   ├── d4a7963f0e041cf6e188e259b7c3cbedcac81419.nq.gz
│   ├── d61c5a0d497e13f693ef5371343d53fb87a0d637.nq.gz
│   ├── d62fc66df4b9acdd5381753fde4173a5775b1ddf.nq.gz
│   ├── db6e79434b426e217445fdb68d5c227c304de061.nq.gz
│   ├── dc7db98e9ef12b98e222b9a0a11facf9100feeb1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e74a2102e69774e070071220328a6f19bb97fdc5.nq.gz
│   ├── ed3a9d377ba3c30e6eb8b2a35e08e8dc814a0725.nq.gz
│   ├── ee5ee4661c9a4fe9609290a3e8e5e538bd7299ca.nq.gz
│   ├── ee99117ffef76da2ac0cca463fc89183ecd1a283.nq.gz
│   ├── f47c06cc18baa434989aa2d46756a0b678957242.nq.gz
│   ├── f738fc2f058fb6ffcf3594f542f464ed6bb4d06f.nq.gz
│   ├── f8a756cfc7a18d4b4d911ec4361e9150832a00dc.nq.gz
│   └── fbbb2b9cf652850183071c931c3b36417d4491b0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ab400614f515cb72956304b95758ece1b9829012.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 74 files
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

[UKPLab/arXiv2026-uncertainty-aware](https://github.com/UKPLab/arXiv2026-uncertainty-aware)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
