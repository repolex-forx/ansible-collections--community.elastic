# Repolex Knowledge Graph of ansible-collections/community.elastic

RDF knowledge graph data for [ansible-collections/community.elastic](https://github.com/ansible-collections/community.elastic), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.elastic
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4f0e87f22e41d475f574a86ee6527513297e7e69
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4f0e87f22e41d475f574a86ee6527513297e7e69
│           └── chunk-001.nq.gz
├── blob
│   ├── 004b0489d3feab0fadbe0967e9306e5bf13982f1.nq.gz
│   ├── 05bff7020ccbfdcff55a5746395500ab3fda86cd.nq.gz
│   ├── 13ed0a2ef698dea337bd103b6ca0d3a10bc0ff94.nq.gz
│   ├── 15e7843cf93aaac5431cd8e368bcdb6f23c51d6e.nq.gz
│   ├── 16788bc9fc554b598d3faabc3eaadeab3088b5f2.nq.gz
│   ├── 1954cc6b4b297fda8f2d1ddb4a869758abc9311d.nq.gz
│   ├── 1cae6dc2bbcc510577df69b98d9129a4fe08a348.nq.gz
│   ├── 1cf63e1f3d775b11f6fc0862d7448e2c40505e31.nq.gz
│   ├── 1d29c06f33d1dc0811232e0be681e9157a666bd9.nq.gz
│   ├── 1e2b80b9165c4958828bd4d36789182a8dd54469.nq.gz
│   ├── 1e7dc15188a5be41a2d6a3f2f663538145937009.nq.gz
│   ├── 205b2ef9afa995d841959007cd6b963bb1cdbf47.nq.gz
│   ├── 22441c65fd0013fe5100943ad97059a1297b5e8e.nq.gz
│   ├── 275e913503236f2c1b3639e9d2b7ad87a8962d0b.nq.gz
│   ├── 2bed87d7af55c3fd7944e906f67ee3077b13ce68.nq.gz
│   ├── 2ed254d3a9cf329f49fc8979ed383b4603ff964a.nq.gz
│   ├── 2ef2b4f7fb3e98fa7f287d9cb6cc6d0b6131f64f.nq.gz
│   ├── 2f324257a4ce1922cdb939fa759d1b73546460c4.nq.gz
│   ├── 35ea9b00dbdaa8b96b3cbfeaba95254b44e8f40a.nq.gz
│   ├── 3c5c71acec77b34e9170d076bc19d029f0b92163.nq.gz
│   ├── 408f0cdcef5e25b4dadbcb44c952bb5b0857b93c.nq.gz
│   ├── 4096dc07dab31c45c8de959e40d68d32693ef8d2.nq.gz
│   ├── 421e701f8fbd97194cd1005fd3118be3e449ccd4.nq.gz
│   ├── 428dba95055e91c86a2ef7cb13b23d344a9ea596.nq.gz
│   ├── 4543a7035ed12128a8d29fc1b4c4a9796b516b50.nq.gz
│   ├── 45f17e75633a7bfc8204afccafb9b9faa26ad54d.nq.gz
│   ├── 46db45796e5da07a479d3c5112089507c7e3b1ae.nq.gz
│   ├── 4b3c5c1e59242e61fb18a2ca061401d13b25bf20.nq.gz
│   ├── 4c531d3007dcc4bdd19347ec9512b65ad7b9cc9e.nq.gz
│   ├── 4ec4858addf685adaf56caa229e694d894e4a3e0.nq.gz
│   ├── 51bcf186d44875aca63fbf59543d8809047c272f.nq.gz
│   ├── 537f782950e929b9b3c83efefa6240cc0a730fe0.nq.gz
│   ├── 54e8cd662d27f54a3580ae185001af745094c0cc.nq.gz
│   ├── 554ccb0d1751279b506cb59b45268463e4db8a20.nq.gz
│   ├── 5575acf4060010b1b5301585f94b760dd81996d8.nq.gz
│   ├── 636a2cd071d5fb48b045efe5a96622a9a683949b.nq.gz
│   ├── 6c1889255a4944912ea39c08e68f3a3f34d7a6b0.nq.gz
│   ├── 72849e2ec5722f25723ee9730f0bceaafc0e48e7.nq.gz
│   ├── 77a2366d6a8efa06114e06d1db75e9df6c56f97b.nq.gz
│   ├── 77cf943edccc4da90566a56262c62c052bf2f945.nq.gz
│   ├── 78376bf0ab928970587a87eec7d3fd527d04da6e.nq.gz
│   ├── 7ab26e513f1b72bde44be90a28e0bcfc027143fa.nq.gz
│   ├── 7d16453d8a889a7ca61919aa28ef151e5026518f.nq.gz
│   ├── 80fbdf92da1fe80025b45089f843f2b04e871423.nq.gz
│   ├── 8479824688f0626073911f792e959820ac4189f1.nq.gz
│   ├── 8602143273d576b269bf2a709f00a273a2473d22.nq.gz
│   ├── 86edd0fbec7277aac8c1bd82cebd28051fe93900.nq.gz
│   ├── 888394448360ac5479431eedf447b5e6cd92fdaa.nq.gz
│   ├── 89191d997faf8c3ba4ea7784cd1a271da89127f9.nq.gz
│   ├── 897aad4029c54c73e34a74a3e5fc97b6c73a07dc.nq.gz
│   ├── 8d73b0aae071f3f89de555d90ea03a3ea66dc438.nq.gz
│   ├── 8d9227810e00c39c9ad65f87c4d6740eafe665af.nq.gz
│   ├── 916d1e16615f724acf30ef7c460d91cd39636ca0.nq.gz
│   ├── 9862eccaa02dbe7fa2f70c66aad41889e87f2847.nq.gz
│   ├── a0c3d0dc55a0448f970b47700b6c4d90dc553762.nq.gz
│   ├── a447760309a85af097d97e66f1ccb36e9d530d4d.nq.gz
│   ├── a5b34628ae7eaeefe4a76ff46e765dba53dbdc5b.nq.gz
│   ├── a6a25261540b4d122aa6796dc82d445d64abe655.nq.gz
│   ├── a89b4549397673c3a79024585cb6e832dc6ef602.nq.gz
│   ├── a9ef2bdf6d54f18cddd58428c6847dab84f28cbe.nq.gz
│   ├── aa38370b8fb921a51f2869beac83077f2d43ba52.nq.gz
│   ├── aa4a7f5e43a76bafbdb6b039d27e9af8c79e10a7.nq.gz
│   ├── b8cbb9a1bfc9452d2589894d8b17a3e8fbb372a3.nq.gz
│   ├── b9e08cdfd5acec0b5f857ba112d5a8b7d015a210.nq.gz
│   ├── b9f2b420700958e8cafa00e45602cfb82bcf657a.nq.gz
│   ├── bce282fa080b25746a33f69b9cc63271c1873dfa.nq.gz
│   ├── bde1f9fffb101a65faf669aecf43165e9e525c61.nq.gz
│   ├── c3f5b52d35d2ad072bf18419ac706ca689eb7b91.nq.gz
│   ├── c531c1929ac77e80e037a09726621200f144cf17.nq.gz
│   ├── c6d4eb22c07578264d1b0ace8652f44af5c8bce6.nq.gz
│   ├── c7652ada3db46e25e90129d15e24b8b72c4f935a.nq.gz
│   ├── d58d2525e31605e71b8dabea17114b01f265a213.nq.gz
│   ├── d5c5d5bc1e3f7f7b87873f874d3f8d057d01d99a.nq.gz
│   ├── d5dcc1cdb1b3190c2d9d34ca9ec9b6b547452fec.nq.gz
│   ├── d7af7cba680ecf025b40b6a5376433a4bc1068a5.nq.gz
│   ├── da6e2ecc2b5e9ea56888ef7b8a45c51303b5961e.nq.gz
│   ├── db040d5ad7a9bfb8200007042908c72e44a64e88.nq.gz
│   ├── ddb7c67c6eb8e13556755af54f7cfa98ee7c3f58.nq.gz
│   ├── de82e636205d1157664dfac9d3d5023a5c15c1ef.nq.gz
│   ├── e01f564ecc7bb568e37570f596d6440c58b79721.nq.gz
│   ├── e08785a66f6b483f9398fabb499c9b2f72425ec6.nq.gz
│   ├── e24289e5e5e47f9af39d23ec3265ad8475173809.nq.gz
│   ├── e3c6133c9733fb896584cf4283c2e989191de12c.nq.gz
│   ├── e538344c3bb7dd3337a8d04d99a936c0fe88d7a9.nq.gz
│   ├── e6d8e136bdefa369e05c5f4b0399beb2e7b7101e.nq.gz
│   ├── e9ad47b321ab2c4272e0a220fb4be25395a89137.nq.gz
│   ├── ea174d85395c8fe2640c0940c45263b9ea4b1e6d.nq.gz
│   ├── eb9eb7a2fd56c09a56bc990cdb048e7f3fd7b2f1.nq.gz
│   ├── eddfb8088fa75c91476f5aaca38a6c023cd1a062.nq.gz
│   ├── eea60d4f59ecda5ba1b1a3929d94f008f94bf817.nq.gz
│   ├── f737addf5ca84d0201824ac43e2fb823997bc5cd.nq.gz
│   ├── f7cac76f6e5f2a020f69fcfe65f09bb7fef1bfaf.nq.gz
│   ├── fb9c1c91df8f1188dc4062cbe7526319fa8474a5.nq.gz
│   ├── fc38b10376c7a9ac05037a54782b4cbe9dd94bd2.nq.gz
│   └── fed69bc7c1e4c73c0d5255713e870f1c680bbc0f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4f0e87f22e41d475f574a86ee6527513297e7e69.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 103 files
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

[ansible-collections/community.elastic](https://github.com/ansible-collections/community.elastic)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
