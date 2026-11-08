# Repolex Knowledge Graph of zenml-io/zenml-changelog

RDF knowledge graph data for [zenml-io/zenml-changelog](https://github.com/zenml-io/zenml-changelog), parsed by [repolex](https://repolex.ai).

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
rlex download zenml-io/zenml-changelog
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fc98ce9c4e4535eb754129107c9403868ce5ed4d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fc98ce9c4e4535eb754129107c9403868ce5ed4d
│           └── chunk-001.nq.gz
├── blob
│   ├── 039cad2a2783387241e0a67b927f9c041a0d694e.nq.gz
│   ├── 03e3abf9808b55f72188ef8fdd0b402d17cc90fc.nq.gz
│   ├── 08fa731d8a2fe3a03ad055b57a5619f623edac49.nq.gz
│   ├── 0ab3bee442fc5635d2e55c3a65379c5f520247e3.nq.gz
│   ├── 0abc05849c55bc0d09e9af1aea44f781ac465d40.nq.gz
│   ├── 0df3777ea192ceaa58c263c9291961ffd92ffec1.nq.gz
│   ├── 0ec0d3583dc7f15883f79f1ba5217c50ff11e554.nq.gz
│   ├── 1288f36e96c6d3c814efa6c7026fa83407d31a2a.nq.gz
│   ├── 12ad72d796efb20b9aaf790fb54d6c090e25ed07.nq.gz
│   ├── 246f74436978928b28faa043d8465b20914843bc.nq.gz
│   ├── 2ca448b125092f93843848c86c975a7a793ed6d8.nq.gz
│   ├── 2daf5835c487e2d4c8cae3599b41604681d0fce3.nq.gz
│   ├── 2e4415505951059c08e325ef37eda7d03f2d9abb.nq.gz
│   ├── 3a8bd63bca651b0cf86be74e72e70fbf7d8537e8.nq.gz
│   ├── 3d3c51c3943f49e4f1fa549346bcca3508fa9d97.nq.gz
│   ├── 3e11631e3c4db25db723e8f296096036493e6a72.nq.gz
│   ├── 40b5da85f20f419a72788d028da37d2e100d8ec2.nq.gz
│   ├── 4339025dbb164c21a2ac9bc1ebd708456aa49d01.nq.gz
│   ├── 4da1285ab93c588f69eeaacce7caa7cff110e03e.nq.gz
│   ├── 53c95cbaa83e307d0468a17f7aeff88d60f3290d.nq.gz
│   ├── 57921692f52a7862a45b409c38e866cdab3f7359.nq.gz
│   ├── 58d7414c98bbb2aa198f14f0add8e58c66f57e90.nq.gz
│   ├── 5c205e2937c0a7373387fb2231fa50ca1eb6618e.nq.gz
│   ├── 5f56f1be6637fa02a28864e57d582edb85a78af5.nq.gz
│   ├── 68a9c3f889d53f740cb738b86163457924db46df.nq.gz
│   ├── 6b5e30e5e9a6edb43c71eb2a805a47bf675a68db.nq.gz
│   ├── 6fb766bf438e59f45350dd404caef26fe11ea090.nq.gz
│   ├── 73560751455918b3fe08047a9305e67990b1f3f7.nq.gz
│   ├── 794f62e658ba43ed4a9ed9f66997e29cbe7cefb2.nq.gz
│   ├── 7a065d38696360e8f2c50a0a83f2806e4eebab84.nq.gz
│   ├── 86f7445e74894a2ea18c28041718d289f0bc65bd.nq.gz
│   ├── 8f347c5b275ad51509c9efc098c92bbeb036575d.nq.gz
│   ├── 9291a634671d16ba72a6df4e22fa853a85feaa97.nq.gz
│   ├── 998954876f2765b75673f063a71ed1a0154bbb48.nq.gz
│   ├── 9a0d98dde486718ef33aafa608e0043013e3c9f8.nq.gz
│   ├── 9ae596c929cb4f5a9f391eba25309795c005e8b6.nq.gz
│   ├── a194ed37031a0f926f2cea63c0feee4a12d60e33.nq.gz
│   ├── a60ee6007ff20e23264969f77f4f677cd2bcfde6.nq.gz
│   ├── aaa67c256d0ce1ad2e6792eebabba25d9a521ba4.nq.gz
│   ├── b013e70ab5a23a000f5273f4e70b0d2d51e6abe2.nq.gz
│   ├── b3005f2bc8e37aadf8e279561d91b5a6c237edc9.nq.gz
│   ├── b700e7bfa78cc22f9c47da4ecdc2251bbe938619.nq.gz
│   ├── b7dca2570bdb60097b679a2adc709542b03e82a2.nq.gz
│   ├── bce573a8449cff542077d8722c204e09a12cc4b0.nq.gz
│   ├── be7793866654e22ac9a9d6a00f283a0bbfb50c39.nq.gz
│   ├── c451495d20208e73100f67e75a17265fb489e31c.nq.gz
│   ├── c55227707a8d83d521ea8d3319ebd285ede773c5.nq.gz
│   ├── cda4349407615f54c4268e2d3ef6fb1bd8c59792.nq.gz
│   ├── d2d17f160585bfe39fc6843c1981b9977c2e7579.nq.gz
│   ├── da698ae6fe6c3d335c3b448616b7a1a1e05a64af.nq.gz
│   ├── de3e2345761f947318b1c7f51a82e7a94fd4a517.nq.gz
│   ├── e4bfc3eccb14abc15fc5f58b9ef853d942563661.nq.gz
│   ├── e52aebd17b554427ff65fc769f697806b7099843.nq.gz
│   ├── ebfb333b074cad77889c01d5c97a6dfad308d5a4.nq.gz
│   └── f919c0e2b7f1f63fa31cee843a5b2ef343105a13.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fc98ce9c4e4535eb754129107c9403868ce5ed4d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[zenml-io/zenml-changelog](https://github.com/zenml-io/zenml-changelog)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
