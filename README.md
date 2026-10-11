# Repolex Knowledge Graph of jazzband/django-floppyforms

RDF knowledge graph data for [jazzband/django-floppyforms](https://github.com/jazzband/django-floppyforms), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-floppyforms
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3c019feda452407522b61c71c1df373c7cc6152c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3c019feda452407522b61c71c1df373c7cc6152c
│           └── chunk-001.nq.gz
├── blob
│   ├── 038bd37c329e23ceabb366065566b39a5648bb3a.nq.gz
│   ├── 05a2cc5a8c5fe75aa0de1b99cef405dc6732d704.nq.gz
│   ├── 066a028bcaf21e18c6b542ddf7fc0b780cc3531f.nq.gz
│   ├── 06ab66f999995f694a5d717d3657f3098fec5083.nq.gz
│   ├── 07fa48091935a2894c721f8ec7d52bc8bdf0f394.nq.gz
│   ├── 1097657f8227f3d20e136af07a0f35832cdd3919.nq.gz
│   ├── 10d791913f8b3f6e2e8cff5014700aa176fce0a4.nq.gz
│   ├── 1294a2c160af789cf615576f8e23ac32c7c736d3.nq.gz
│   ├── 13afb006252399c4de4ff7fa26c499db03fba9cf.nq.gz
│   ├── 14b78cafddefcb06b59156a1d5e3e2f392580ab3.nq.gz
│   ├── 15f1599992ee6fce7dbf0ce738a3a887f26a6610.nq.gz
│   ├── 1b748ef3e5905001e63682af6cc2e6efa8bcb893.nq.gz
│   ├── 21219fbab4de094dc219d40eabfb1d33fafd15be.nq.gz
│   ├── 21f4758d9cd80f49df3083bc28d736713ef5e60e.nq.gz
│   ├── 261c2db4dfc5421cc0a0c3a0e44c2fd5752def64.nq.gz
│   ├── 26c023309a83e6487e7d4893a0071384dcc13cdc.nq.gz
│   ├── 28d74099b4a6b890a001e03d35c676cee9d00010.nq.gz
│   ├── 296b2e29c970fca4222db7cb86e91deb56c5a7d6.nq.gz
│   ├── 29d98997181424df139f0882ae22953fafc5b687.nq.gz
│   ├── 2eca3a20364d51737ff9fa51250c8c9abe6fd610.nq.gz
│   ├── 2ed2d5b088366d411a609fa43650f5bcc7a823f4.nq.gz
│   ├── 30b2aed4d94eee3d9cd12469e71e35a6889db174.nq.gz
│   ├── 31f1d3e94e3ac533b45678da7362bb0ce7e23bad.nq.gz
│   ├── 33be013202f16781ef1d56a3925664217f59e4cd.nq.gz
│   ├── 382a81d9a1af6e7c2b822f8d1edb5684a55b14df.nq.gz
│   ├── 3d305b622a6afc555ef30e0cd140460c15031fdd.nq.gz
│   ├── 429f31112f99551f271e820e3bee70ad32cb6b65.nq.gz
│   ├── 47a847b4baf9c124206b3588f4a90abb8f2ae5b0.nq.gz
│   ├── 4bcc753a12e9854923af4b9b5b9a4b76f1bc53a6.nq.gz
│   ├── 4fc477a8dd377a1c84c81f907d071de49a768f54.nq.gz
│   ├── 50fc76e8ba7b0e3cdce7c101f6296b80a2cf4c1f.nq.gz
│   ├── 528ec90e988b6dadca520231a691154f0ed08702.nq.gz
│   ├── 52c4c925923deae7a8326a31c18e98a6ee7a9226.nq.gz
│   ├── 535915e8dc2062990aacfaa2b8ba1572bcd7e267.nq.gz
│   ├── 56334072a886b0c32d35d33a1bf77e43567c8f25.nq.gz
│   ├── 5640ae888ba2bee0e9758d24e2cf144db4cf685f.nq.gz
│   ├── 58d5aae9b546f790a495865d2d9b9ced4576fb64.nq.gz
│   ├── 5977856cf7cd3ee88f8c98fd4722a166636eba6d.nq.gz
│   ├── 5c30be74799d0db259a057912f51466ab800439e.nq.gz
│   ├── 6159e7b1c1ec14e503949ce657b29f06b63e4fb7.nq.gz
│   ├── 62226a2d71adbde8377b7ff7df08349e23f48546.nq.gz
│   ├── 63280839a8967e2e75c9bdfa91a3450e3a750c30.nq.gz
│   ├── 6987268840f5325b526364a929132c55c63e2f7c.nq.gz
│   ├── 6fb55a2b8bcac1609d4581cc85648034e659ed0f.nq.gz
│   ├── 745601f24d64632d62fa59f0b117740d426e8c21.nq.gz
│   ├── 76c8606f550c1d95cb9df2e8b8656447e8a9e58d.nq.gz
│   ├── 7748078a57c6bcecda5d4ace321d21fe35a7d7b9.nq.gz
│   ├── 7a122741aeef0df6d692c5b1c688a0eebbc95469.nq.gz
│   ├── 7c8a02c26ae691ec738b7d32a1b025dd5ef789e3.nq.gz
│   ├── 7f2f98f4afeba5017eb05efa4e78483770855e38.nq.gz
│   ├── 84e3489852eba0359b7eb48e520798b442897b55.nq.gz
│   ├── 8851e21180c987f9ec2984ebf44edaccb13936ec.nq.gz
│   ├── 8a45b9da1898efa7b6e30847564e9edc5d9a8809.nq.gz
│   ├── 8a9ef2179068162b995102feba2a248d53136484.nq.gz
│   ├── 8ac948e4b5be6fdd3ac4cfaba3a51f2281b2bb14.nq.gz
│   ├── 8f2ea1568193c57a85b1de6f0755778506ab4bdd.nq.gz
│   ├── 90dcf3e35f963efb4a948bb618921bf25dde49df.nq.gz
│   ├── 9149a24209a235c1681e032de44bcd2d0b340a90.nq.gz
│   ├── 917af3597b67c353025191184572e460ec08754a.nq.gz
│   ├── 917d1b96f769a4561dbfa2467e75a2ec6005ea10.nq.gz
│   ├── 929815d975750febfb49a993604c00b76308f912.nq.gz
│   ├── 92e7d00d4ca4742096ace2c8a95a89a4c8025657.nq.gz
│   ├── 9380912d07026b9a904643bed7f98be28f6715ec.nq.gz
│   ├── 9649ab97c6f954d24273bf2618d8dd5321503840.nq.gz
│   ├── 9b7e0646d74e76ebff18d2c2646bd5db1c79db68.nq.gz
│   ├── a0835fec5fe2de59b72125bfbcc0005c47226342.nq.gz
│   ├── a0fd7c63920dc3d088c99665009301aa1e92305e.nq.gz
│   ├── a279e062d49e829470d58148bba1f12661c7610d.nq.gz
│   ├── a357fda159b763a055db3ee4c72e0d04b0b03b6f.nq.gz
│   ├── a4d67b3b97802b8a2ca281f82351da5d5ab98f81.nq.gz
│   ├── a640a860e4343e537927ee2e991de5d50a2b6788.nq.gz
│   ├── a82cf5fc54cc0064099720322d62e9bf4dde05c9.nq.gz
│   ├── a83144c13394b4e1d1d8be29f2658dbe9846e644.nq.gz
│   ├── a8515622d57523712baa43368913dc0515267090.nq.gz
│   ├── a8958de9b429ae00f56bb282c4b133ecbaf334bd.nq.gz
│   ├── aa4883bcd458311d93861a9a9d7574a53b979e97.nq.gz
│   ├── acf9e2bd8447efe2be5badf5a5ac16363ea0d3ac.nq.gz
│   ├── ae90e9d7c1435e5bb2b2e0bc46ed97ce30434834.nq.gz
│   ├── b2cf5047daef20d7b06bf4b5dfe0a52058cc6b1c.nq.gz
│   ├── b75320ef663fe9c96ac5e07f66fb92f8b32600da.nq.gz
│   ├── b87dc2ae7f5188bb5c7c64eba28811ccc5ab0f3f.nq.gz
│   ├── bfe7c01a1807d4f97b33d7baef568add45ceaa9e.nq.gz
│   ├── c009c255ef8f129ad1b562f1f699de02fcb3c2a5.nq.gz
│   ├── c2de27beaa265e13c397de059f2609cea51c7dc1.nq.gz
│   ├── c2f7a24fc6df8c6d6f6ea46aa4f44c46a6b65761.nq.gz
│   ├── c38d67d40606533827aa35a0be007712db609e8e.nq.gz
│   ├── c91a4ef3c935bd5540c8997341cdff48b3376cc4.nq.gz
│   ├── cbed84e8c4aee4b2b494a8ac591e92d6855f59fd.nq.gz
│   ├── cc8d7b2c679d5b2588363020226523f455cb50e3.nq.gz
│   ├── cdde6fc7ee621e569bd7f0e62eabf756ed9b8367.nq.gz
│   ├── d1c593e1df5900ffc37e749d748065635e9d6e43.nq.gz
│   ├── d3c66b0db3b66923d29c116d8936205dbcc70261.nq.gz
│   ├── d4e295415206e0c176c54bcc4f07af0b051c3e40.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── d9e4fd255840f6501d698e3ca1b50206efa425c7.nq.gz
│   ├── dceae3a80cde1f0b9690def68fdb104ef77d9736.nq.gz
│   ├── dfe67481ca1b7e781ff179f1243396c93e459f38.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e139179c8d3e01a2240ba323a5d6368eae129d5f.nq.gz
│   ├── e16ee26e4f1665926c8849598d6dd6a5f9593c67.nq.gz
│   ├── e3953a82488fb1363e074aad3dab3ef10665265d.nq.gz
│   ├── e41fb7bddfa186b688e88991fe805c70c7158608.nq.gz
│   ├── e5cd55037b4b0330e48aa80b99a1c65afc19f58a.nq.gz
│   ├── e5e117053c7546f9f9fbdc76cdf6cb6fafa70567.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8b88a938a76c373998d1437ad22751134f47442.nq.gz
│   ├── ed4472dd8971c49f17a1f9bf972a04f0b9bca523.nq.gz
│   ├── edea117db8dd5c564ad72b0f254b3b915ea6dad6.nq.gz
│   ├── edf4dabda5be5ee91fe7595c313ad30ac0001ead.nq.gz
│   ├── f029dc62d7c0af36d0029bf7125accfbb94a0985.nq.gz
│   ├── f22e8ed8703c4da2329f8aebd56f378ee6cc5fdf.nq.gz
│   ├── f4305641848f78d43259428008a9ce4e4cef9df1.nq.gz
│   ├── fd6207c3b717299952f95343fdb29f27ee377f10.nq.gz
│   └── fff50b7b0ed8f74272310a17a0e3910087a1e939.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3c019feda452407522b61c71c1df373c7cc6152c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 122 files
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

[jazzband/django-floppyforms](https://github.com/jazzband/django-floppyforms)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
