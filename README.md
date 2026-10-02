# Repolex Knowledge Graph of block/lhm

RDF knowledge graph data for [block/lhm](https://github.com/block/lhm), parsed by [repolex](https://repolex.ai).

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
rlex download block/lhm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 40f0d6076d88e997ddad1514c1d055d803219ff8
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 40f0d6076d88e997ddad1514c1d055d803219ff8.nq.gz
│   └── repolex
│       └── 40f0d6076d88e997ddad1514c1d055d803219ff8
│           └── chunk-001.nq.gz
├── blob
│   ├── 027a074bb1b84dced39bae7371161c6e82e81794.nq.gz
│   ├── 02cb8fcb5372748d4273b6a49eceb78fbdb15ce6.nq.gz
│   ├── 0367d2331a2cbfb3dadb43da08affe106a235c28.nq.gz
│   ├── 0719ad1e1258ae80e09a69fb0d50268cf7a99be8.nq.gz
│   ├── 0ba9db25329d0b336e39ca8cde8470c5b7bc45eb.nq.gz
│   ├── 1ab4cc2c75207fee8b44f42696f6def6d522f128.nq.gz
│   ├── 1aebca0d4c6ddff88620a0d110fe95ad9ff10597.nq.gz
│   ├── 1bcfe0e6534b9a4ad8ca41703ba3f3b624e8d922.nq.gz
│   ├── 1dc9a8cbb1d50b96940e03fd10df302b02e3b858.nq.gz
│   ├── 25f0bc5ed80683a81f46e6bfd1cf8ea0b56c6807.nq.gz
│   ├── 28f6b8451f950dc4dfc9c64325f3bab8a7624a96.nq.gz
│   ├── 2bac73f8cc9f42c945faaef621c3cd02c08fba2c.nq.gz
│   ├── 2ce23ff63951363f2b47acfa345e723ab7a20ab8.nq.gz
│   ├── 31559b7d115e3c105b328cce9b9dcd9774025061.nq.gz
│   ├── 3522e68cfcea36da60ce150da98f3f3a2e53090a.nq.gz
│   ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
│   ├── 3beb42b608d6e6c5a85c4a94f16441847be85a09.nq.gz
│   ├── 4389fe526b130798551e8252760bf2268b24d298.nq.gz
│   ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
│   ├── 486e5395496ced00fa67639bfaff0524013169c8.nq.gz
│   ├── 49c79cb0cdc36988cc3af9ef67bb713e9287946e.nq.gz
│   ├── 4d1c45d23ffd577746d477649fbc4f25fb84bc8c.nq.gz
│   ├── 4d6c69c1c247028d4ef0ae8629db751661118921.nq.gz
│   ├── 5d71f648c7ee02e0887138976c7623c20911df59.nq.gz
│   ├── 6341ae45ae1711193d24b2d47c9ee21f3bc28dae.nq.gz
│   ├── 69e96b8e33dbdd2f7131d876cd027d450be30f4e.nq.gz
│   ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
│   ├── 6c025bc563895062e8e9558416c1926d60ee2245.nq.gz
│   ├── 6e8778d250bc899ca393ec2eec7cb8e80726a357.nq.gz
│   ├── 700f01ed185f84d55512185f5258af240ba17163.nq.gz
│   ├── 75306517965a54731b94dca8bace640e856af115.nq.gz
│   ├── 7c2ee9b5ee0b69389214db6e571318aaad7fa2e2.nq.gz
│   ├── 816066f4755caecbea428ebfe33fecd477e0bb7e.nq.gz
│   ├── 862ee3c28647e7a58801a75236855c269c1448ae.nq.gz
│   ├── 8a16a4cc79b69cfc15fdcf1b8d2df0b72fe99d8a.nq.gz
│   ├── 8cffadf6c6b89cc657ca7c9084f966bcc82854d5.nq.gz
│   ├── 8e1322d41652cb9dd410a944712e618e73f82c4c.nq.gz
│   ├── 906ee94ca6891416a56b8a1df9e0bbcc0000429d.nq.gz
│   ├── 9582fc588754f78d9875691a3bd5e674295436b3.nq.gz
│   ├── 999a89e6a5906586f27b7034370255feb835f67d.nq.gz
│   ├── 9c0764186ebe1fba24864545a8ec23c41df25fbd.nq.gz
│   ├── aabfd4ab5e49ed4237cc1ca6ff9213775c076f49.nq.gz
│   ├── c32f09744a1c05d648a3cce3895f63849c8a8153.nq.gz
│   ├── e4a3ccdf129c89b3536247394eecd3cbc635e378.nq.gz
│   ├── e889550ba4cbc92a720527042e5f6e7a303bfcbc.nq.gz
│   ├── ea8c4bf7f35f6f77f75d92ad8ce8349f6e81ddba.nq.gz
│   ├── f8803abcbd09d8d45884e9c6a3f09570c3963b88.nq.gz
│   ├── fb6d193b736e9328861731e2583ac518d06b928f.nq.gz
│   ├── fd2674fdecbcb3389588290ae6e3105b47c057aa.nq.gz
│   ├── fe0867819936afc4af0bf1512d453bc7465e7db2.nq.gz
│   └── fe28214d3352b0ed40820a4999317694c8b1ef57.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 40f0d6076d88e997ddad1514c1d055d803219ff8.nq.gz
├── filetree
│   └── 40f0d6076d88e997ddad1514c1d055d803219ff8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 61 files
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

[block/lhm](https://github.com/block/lhm)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
