# Repolex Knowledge Graph of pytoolz/toolz

RDF knowledge graph data for [pytoolz/toolz](https://github.com/pytoolz/toolz), parsed by [repolex](https://repolex.ai).

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
rlex download pytoolz/toolz
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 451af60dec590a6010e2babdbf391ea8f815122f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 451af60dec590a6010e2babdbf391ea8f815122f
│           └── chunk-001.nq.gz
├── blob
│   ├── 03b9293c05a9b86ae17bf85d110edd3cae626764.nq.gz
│   ├── 05c36cca8ca1ebf242486ec4a3fbd578c6b3009a.nq.gz
│   ├── 0a5b88d9024103f0f22753a1696ee0c35b6cdd07.nq.gz
│   ├── 0abda1cb427ed8f070a7f02e638f35191861013c.nq.gz
│   ├── 1002c4649f8dc114f55e1169e3ad5ff23599e256.nq.gz
│   ├── 16d8be9ef6ac5dda57c01c6cb85ca3befc4955ff.nq.gz
│   ├── 1c967d92b51e40ad59462bf6d38f320aad0a721d.nq.gz
│   ├── 1ca0d112d779936216f35aaf56862f3615a5cc64.nq.gz
│   ├── 1d3d5c6e8ea63abdd4d8a79e0e3bf10da1ea8795.nq.gz
│   ├── 1dae938335d38096c86238e76343fece8f2f2266.nq.gz
│   ├── 1ddbdf8d6b0f0c670b696b0b56881af5eeb8a5c6.nq.gz
│   ├── 1fe557cb2559fe07319163634e321b596215dde8.nq.gz
│   ├── 28bef91dc80cbbe412da6d860904f23561705f3d.nq.gz
│   ├── 28f20678c5b2fe1b996d2e4392962cecfa1416f9.nq.gz
│   ├── 309b9308d01e6ddeb68274f982c890dbfcddf269.nq.gz
│   ├── 3188b4fb9a58221ec3bbb7f0226772f3813bf324.nq.gz
│   ├── 32c4be5b66116ea7307a136bd9e81a75ceadfbc4.nq.gz
│   ├── 356eddbd3ba311e4841b6baed4e50913b15075c4.nq.gz
│   ├── 3da61a9a40849377edbafde00ca5d51356fdf5d1.nq.gz
│   ├── 3ef203c860d474caeedb1160d522a6fe43772786.nq.gz
│   ├── 457bc2692862782e5b2db4dee16e3a123b19ba8d.nq.gz
│   ├── 4b032921e58747436ce397506e382430d089826c.nq.gz
│   ├── 4cd5d64ac54e90d424fe9e7d563710d519bcc11b.nq.gz
│   ├── 52dcc5ce3791dca2df639e9d74d4f8fd8627e5f7.nq.gz
│   ├── 5345b64304f62917ca08461b427d77c77a2073b1.nq.gz
│   ├── 5a5e66ba3b363499abcfe9611b970a22e71e2c5e.nq.gz
│   ├── 5e9316bf9a4dbef81e4a5cf1ef9369425ce4a51d.nq.gz
│   ├── 5fa09356576f02b4e18bebabc1d59dae71d201f1.nq.gz
│   ├── 5ffa2c3fce4d0c8b0ca4e6898de4bc6e830f4748.nq.gz
│   ├── 62b72cb451a35af7e8d5b40f38f0fcab42405e79.nq.gz
│   ├── 6907af7fb872a060fbad4070745da4566e09979c.nq.gz
│   ├── 6d108c3e7c03c471472bc08eff8190ba8511b066.nq.gz
│   ├── 6e8411e2ed77ee0fc86242f170991c5d8ba060ad.nq.gz
│   ├── 70076f1200403cf6acc4ae3933996d1b5cb9febe.nq.gz
│   ├── 7016e3bb42a2ebf80212dedaaab98649d7d1af18.nq.gz
│   ├── 72728f6d8247e31edea39de57137851090c6f3b6.nq.gz
│   ├── 75a52bbbf27ee0779edcef942a58d9268c3eaf92.nq.gz
│   ├── 77dc2a4d9d26b5facf4b215b9bddc430a2bc14d1.nq.gz
│   ├── 7952b119f465829cf728cd9d6a25ab390ca7ed23.nq.gz
│   ├── 7c1ff66244b0e3c1c72bdf2cdd0600ddd223648a.nq.gz
│   ├── 7fe39c658ba8c4f50f9e0a36280ec93096904799.nq.gz
│   ├── 83d0bffae74b1af477127f044bec0b34babbb754.nq.gz
│   ├── 864fac7fc485e215c7d5b1231daf63fac3586c81.nq.gz
│   ├── 89de88db2b46d9a50231ffdf18aa0aa280f051f0.nq.gz
│   ├── 8b82fb4f2893d1bdca3d843267ac5f8a5f174e73.nq.gz
│   ├── 92c7234d9247f0258c3eee4bc22b26249314c293.nq.gz
│   ├── 98b14883b58863d15ae74853230fd46c38fbc832.nq.gz
│   ├── 9c9c84afe1b6deb26533013c4d8b2d9c93a11890.nq.gz
│   ├── a0825ddb1eaaed2b46f94c0d4315e7ba7925a88a.nq.gz
│   ├── a08f39bcbf72e6a1e5e48e51be24fa71deacd4eb.nq.gz
│   ├── a14ca33af94f65d476f1d9a2325a16ccb7f2887b.nq.gz
│   ├── a392a6fde7e14200e2a63defea38663f74d1728b.nq.gz
│   ├── a45c054fe768f009d196030643de0aed6a8ae54b.nq.gz
│   ├── aad22158dd51354c02354ec9473ef5c948961180.nq.gz
│   ├── b4cacac45643a186d84d8a32537432a715e265af.nq.gz
│   ├── bd4a563d9b3cb9feb97c9e85cad4e6d8c1da4e93.nq.gz
│   ├── bf4aebed456cb85255e97aefa709aea7b068d3a8.nq.gz
│   ├── c449f60713da199296a40ff41c84559bfec203ee.nq.gz
│   ├── c5aecd6022cd9eb121b3e01a8a37183402b97bdc.nq.gz
│   ├── cd0eb6cb8f24bc795c73bf5f0e83675efe437ff6.nq.gz
│   ├── d011ecb8eae240773e543f9619c2d49f3b199054.nq.gz
│   ├── d20da2b844f66815a09589b3b381e1cea9530893.nq.gz
│   ├── d2a5ed0809549232fdded1c5f2fff6fe7c85acd0.nq.gz
│   ├── d35e0de2f2b2d150a578bd7f8e3839f7e7b7d8fa.nq.gz
│   ├── d57a1167d5f052296e5cb83107997ba69e96c61a.nq.gz
│   ├── d6eda2db518f519ef10912d5c683ef1ad8dff938.nq.gz
│   ├── d7a60b59f6a50881cab63f78265098ac5945a69a.nq.gz
│   ├── d82894b9a55da56521c67e681d66f09368e0429a.nq.gz
│   ├── dd5ecde0679e8bc9b31d99719c94df6f12a09c21.nq.gz
│   ├── e12636d6e5c403bcef0de905e9d121edf043f56a.nq.gz
│   ├── e47a12408af19cd06ef53f953c66e03c96f7e886.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e71c62bf6c5aaa5f347b69dd2d22a0c1c8cf3e58.nq.gz
│   ├── e7a0eabaa2378f9e20bed8ab933e08410e6a9883.nq.gz
│   ├── e7d6716d4a0db48c883d0c67e8d1a38be9fa3435.nq.gz
│   ├── ec21448c8a624bc618ef76cfd94723c1577fcdbd.nq.gz
│   ├── eeb91b202ca96aebc14d8d1ea5630e6e6212711f.nq.gz
│   ├── f12129f247f3a049d97aaf875b6dc63f5a958ab7.nq.gz
│   ├── f94d38986e5e7dee34a305d47536f2cd10f2a7d6.nq.gz
│   └── fbf2a0c1f97bbb28bcd094f9fa49797aadbac3ea.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 451af60dec590a6010e2babdbf391ea8f815122f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 88 files
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

[pytoolz/toolz](https://github.com/pytoolz/toolz)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
