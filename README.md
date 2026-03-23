# Repolex Knowledge Graph of rtfd/commonmark.py

RDF knowledge graph data for [rtfd/commonmark.py](https://github.com/rtfd/commonmark.py), parsed by [repolex](https://repolex.ai).

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
lexq download rtfd/commonmark.py
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 277044484c0a37a5060891c1bdececcf2e82f209.nq.gz
│   │   └── ae4cb27cd4da4d0b87bff19d2f480eecd96290a1.nq.gz
│   ├── lsp
│   │   ├── 277044484c0a37a5060891c1bdececcf2e82f209.nq.gz
│   │   └── ae4cb27cd4da4d0b87bff19d2f480eecd96290a1.nq.gz
│   └── repolex
│       ├── 277044484c0a37a5060891c1bdececcf2e82f209.nq.gz
│       └── ae4cb27cd4da4d0b87bff19d2f480eecd96290a1.nq.gz
├── blob
│   ├── 07c752b533a3249a0d3e801eb77ef250a176653d.nq.gz
│   ├── 09db05efac8b1d2d6a040958071cb0ffc4016975.nq.gz
│   ├── 102670063eb6b9c221af90d7ba9b39278a4586d3.nq.gz
│   ├── 11215b5d422884765816dc7f37b4d9d53be517b8.nq.gz
│   ├── 15b893cb5de23738929f6764108ece81ce267345.nq.gz
│   ├── 1bbf8168d82f725a0b7b4061e106b6d1deb054d1.nq.gz
│   ├── 1e840dcef2bad35cd51df2ef21ee296abd44a585.nq.gz
│   ├── 232f3e9cce22897fd6d6f4379ee732f1e12e6dce.nq.gz
│   ├── 2d98de1883eb634a91521aed6c9ead367e836c0d.nq.gz
│   ├── 3a301c6be58fcced7a10a4b09b5100df36541439.nq.gz
│   ├── 3cdd50e884a75e8d507b8f2c307c903452c0486a.nq.gz
│   ├── 3e1f047316eaf0b98c9ebd746445db94737e8780.nq.gz
│   ├── 45c7336d8fd32becb469cc5bab7d835ce01b08ec.nq.gz
│   ├── 4911c7b59726a1f230af1a85cd40d26bb2646325.nq.gz
│   ├── 4eee387c062b2f8dad11d8c1a3b115c4df250bb2.nq.gz
│   ├── 5155e560d63731cdac27efd0200ebe34f894fdeb.nq.gz
│   ├── 5339e03cf3ec398c1d4e355f9872b9292b5ca8e5.nq.gz
│   ├── 54cba24ea8387987636d1abd159555f5d19319e0.nq.gz
│   ├── 5b1a1d090c82b048833ed97204ec0a6e87c3bad5.nq.gz
│   ├── 6011b61858fafb33dbe53788a7d101879dd9f441.nq.gz
│   ├── 6645843ec5885a2d9095c33794d8535509973af5.nq.gz
│   ├── 66e2ef982656c92c1f014648d9b1bba99d4f785c.nq.gz
│   ├── 71c8025bd52b2cc9fdc2e14421eb0a8e51dfdcfa.nq.gz
│   ├── 74694888384de1b28dbafddf4e3e4d471c7ad698.nq.gz
│   ├── 7aedcfea3e60bb0580cba2f53ae859376058cbb8.nq.gz
│   ├── 7be9b0c87a55e338f246c390393f8bc23181602d.nq.gz
│   ├── 7eb9c0ebc595ae41c60cf99c6cb20a5f78b075c1.nq.gz
│   ├── 8690fd05a3a1cd0a599b82e770adefccfac4244f.nq.gz
│   ├── 8f36457781adee4a66e41e718bb24c7f2266f3b2.nq.gz
│   ├── 91255580e6359c62d6dc646ae369372810067312.nq.gz
│   ├── 9b569de425c83f741b635fe5196f94852ae2ec9f.nq.gz
│   ├── 9ebb4b04215fa429d1b48c5bcb1f03ae80b1d38f.nq.gz
│   ├── a8e20cf28ade08edbf93fe61d6ad804b6789da2c.nq.gz
│   ├── bb4b59188329db8b4a44acfff5bd4862f43fe015.nq.gz
│   ├── bc75a52a0ca9c606dcc0bfc71fe1667775ae8e67.nq.gz
│   ├── c682ba2c6c1603151f170437b607be804defa2b8.nq.gz
│   ├── c7055a94c55de83f63d1ca178a987b3f1b5736fd.nq.gz
│   ├── c861ba29c69ff8b15e3c0bddcc4b851eb3da3df8.nq.gz
│   ├── db7b77f137bf3d90ba1dd7f74239d67ca4b4c6e4.nq.gz
│   ├── e57339a4b10c22ba6da65f26fed776a8c7200e54.nq.gz
│   ├── e9542a2cb06bef3ddb8a4a793c3d508ef6757e68.nq.gz
│   ├── e9ced78a5b814ca7c349439f85cc293d0f77976d.nq.gz
│   ├── ee9cb35180fed2aeb1bdb7a8c36f5f30fa6218f9.nq.gz
│   ├── ef572ec606d2e2ce9b28277d5957fa1f7d88f062.nq.gz
│   └── f30c12a34f3d1f6a78f4a21543e0a83f229f1165.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 277044484c0a37a5060891c1bdececcf2e82f209.nq.gz
│   └── ae4cb27cd4da4d0b87bff19d2f480eecd96290a1.nq.gz
├── filetree
│   ├── 277044484c0a37a5060891c1bdececcf2e82f209.nq.gz
│   ├── ae4cb27cd4da4d0b87bff19d2f480eecd96290a1.nq.gz
│   └── ebf011ea5d781bc0f2d1ed1d0c15da5bb3941071.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 61 files
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

[rtfd/commonmark.py](https://github.com/rtfd/commonmark.py)

---
*Parsed on 2026-03-23 by [repolex](https://repolex.ai)*
