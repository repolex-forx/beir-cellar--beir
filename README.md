# Repolex Knowledge Graph of beir-cellar/beir

RDF knowledge graph data for [beir-cellar/beir](https://github.com/beir-cellar/beir), parsed by [repolex](https://repolex.ai).

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
rlex download beir-cellar/beir
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ef83d29307061c65d04b035b4f4e7c18bd8374af
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ef83d29307061c65d04b035b4f4e7c18bd8374af
│           └── chunk-001.nq.gz
├── blob
│   ├── 02a0914a129794b87425c0a75e342ef3a14bdc16.nq.gz
│   ├── 03cc8970a51e258c233128c556295fa5d43aa295.nq.gz
│   ├── 04d2809168b3e9d5b302df6e68bf2a6adfe0bff9.nq.gz
│   ├── 0520493a74f65c03894d8b4f837872da92afbb34.nq.gz
│   ├── 05c2d819eb43c5a9d0cc74cfc0461c4f7fe3e6da.nq.gz
│   ├── 070c786e3ede1f6d8b56b511fa4fccb3aed9a1dd.nq.gz
│   ├── 097828c23f4f36a1e20a1c79b7e61188085082d6.nq.gz
│   ├── 09c0b0952db6686197f3ea74b6eeb235feca1be0.nq.gz
│   ├── 0b05a8095aef1fc4724bc16b54de4ca6aca77ca7.nq.gz
│   ├── 0daba064b20a38d61d1fd0252d1cefcd759be960.nq.gz
│   ├── 0fdea849ad83f09f9d731ef057eae3ed988b573f.nq.gz
│   ├── 1545696e7a05c354f9dec892c3a3bd01d040407c.nq.gz
│   ├── 17559a5106a11186aedd61955934d8ede083aa93.nq.gz
│   ├── 1c664f6c801b820b5e359dd360a5576acbab4b4b.nq.gz
│   ├── 1de9dc7b6e361f9d5742003316fbf6fb8752c335.nq.gz
│   ├── 200259f3ea242637c14016f961cf0e5a7603ffe5.nq.gz
│   ├── 21ca7b7a273f2500a2ef77c4734ee3b7ec9d56a8.nq.gz
│   ├── 22a5fde1112d22128ea5ee5de48bf2ba394d047e.nq.gz
│   ├── 22ba4ca9576bb16a16a11d5f436dc97a5b49dd55.nq.gz
│   ├── 24c733c09b1a834c01165614309b35351d99d7c6.nq.gz
│   ├── 29b860b71127917de34fbf40e9b4edd0b8f6f756.nq.gz
│   ├── 2bd5f4c5d48ad30d3c561a500eb3dadeefefe1b8.nq.gz
│   ├── 2de5ce412305df9d79a247c56eac5402df61fb9d.nq.gz
│   ├── 2dee6c47f04d8913b47702b6c5196388e059759f.nq.gz
│   ├── 2eff437016fa1e4e380dd1e1399df9cd7edc804c.nq.gz
│   ├── 2ff1bdc18fccd154111d30e65334a7940c08455e.nq.gz
│   ├── 31f7e932f38d19ca3aa8168f481789d1b0861278.nq.gz
│   ├── 3ca0743e6b190ae277cb0d0ece887f19a2368fa0.nq.gz
│   ├── 3f31c474f90f6bb246da2011518a2b8e43b06ceb.nq.gz
│   ├── 401efb578d227450fa8c24b7a9fb15fab464fbce.nq.gz
│   ├── 405be05d580bf313c66a26522f153046619e25fd.nq.gz
│   ├── 40cc7ceeb6a99fb2934c08d1df778efb4edb8c2e.nq.gz
│   ├── 41e7ee322e0a0d7a1c07c6a17375d1bcf64cc4d9.nq.gz
│   ├── 43b54617f7a4625158fe39256ebeda8a070975fd.nq.gz
│   ├── 447d68725093738c6947b7b64b69aafa67bb770c.nq.gz
│   ├── 46a3587a4ed1cb003f8ce1fe8db2c3450ea4df7a.nq.gz
│   ├── 4a39226635f0051b2b34b8343c1a58fc295f7646.nq.gz
│   ├── 4a7a630ea2fffde5b0b90bba630550eef50b2061.nq.gz
│   ├── 4cc976638b1d1d4823897dad21e004ce2ea85f2f.nq.gz
│   ├── 4eb91b3710ac535f495f0e6e55770f14987506b8.nq.gz
│   ├── 4fa06e705278c3b4c378140cdfd1c5ddad408248.nq.gz
│   ├── 5469569377b819bae58fcf7fa88ac8ec233d571b.nq.gz
│   ├── 5868022a628cd6bb8bde91048d7b37957c5680f1.nq.gz
│   ├── 58a97830c9f076d3d6e522a381d88d873f603041.nq.gz
│   ├── 5a143e72e2bd891115d428212b8c3a8a52ce2f04.nq.gz
│   ├── 5a7ee250b6040af55d840f72fc361107a099ef9a.nq.gz
│   ├── 5d8e7690ca269edb1db9f3d3b21948831e3ccbbf.nq.gz
│   ├── 5e4e8be1918a7c81fce5f85cea6e6f0ab9615ad7.nq.gz
│   ├── 5e6136ef6b81c94a36a685784343695a7c504c22.nq.gz
│   ├── 5f08309e14bea1d05348c5e52d0e794c7e840fac.nq.gz
│   ├── 62107c7b1b2bcb2eb77c02a695dce9cb8d47b6bc.nq.gz
│   ├── 669c59c1c16d9736f7e7405bcec5bca58aa3392e.nq.gz
│   ├── 6e327389c6ea9ea4f8f7aa8489235e3d7c5fa583.nq.gz
│   ├── 6ed5aa1e6a724a8cbbc150310b5e463d69072304.nq.gz
│   ├── 70b73dd5812b86d2852d7bd8876ff2cd6c306f98.nq.gz
│   ├── 70b9c476e68ab6914cdda436c8781324398db6f1.nq.gz
│   ├── 72354469604d847067e3351b16b0abe51bb4b76b.nq.gz
│   ├── 7b069c9e6ca1689eb6fd915269bad72eb575cca6.nq.gz
│   ├── 7b245704a4a126e7abe5aeb78cf4fd8ee26f5e59.nq.gz
│   ├── 7c3a2b4318f5cdfadca524f5034b5428d7e62fd5.nq.gz
│   ├── 7c8d4d18e5a20819b30a9a4c56fce7cd8663a212.nq.gz
│   ├── 7e2fd2743ba050a18ee721e2b5684df65c686b7b.nq.gz
│   ├── 80594ed2df3fdbd1fd69694439f3f454105f32bf.nq.gz
│   ├── 8248725593744a7c54f743778f86167eee590a25.nq.gz
│   ├── 82d98b2c8a068398ef315dda3f16bd64cb5875c0.nq.gz
│   ├── 83bbfe1d77c6366088e3ae0b7833acca95db11c5.nq.gz
│   ├── 85d3f94f1d1a897fcf0b45f51876cc98a55bbeec.nq.gz
│   ├── 8aeeceb8a76a7a4e298a4d340a9ce9ca3b1a17e8.nq.gz
│   ├── 8c990411ce80e8d3c9eddcac25cbb6604ff441ad.nq.gz
│   ├── 8ca5cd51bd70b8f592b00d1e10dba181ff44e1ae.nq.gz
│   ├── 8ce6a48b2432f0ea7ccea3c11bc979a0db2e342f.nq.gz
│   ├── 8e3f8755f80b3218586c0a86615fb9f8855dde59.nq.gz
│   ├── 91aaf2bff505b7a9d8669d3c98c39a0bf3394715.nq.gz
│   ├── 9373587a81e009beb7f47371e8e9c1e9344c2dcd.nq.gz
│   ├── 93c1130009ec114c74061cee9282fa4199c077b1.nq.gz
│   ├── 95bfa0546597f58a257df46e71d73a55102bee19.nq.gz
│   ├── 961dbd2bf0296d77fb45455166fdb5a6eb9b4994.nq.gz
│   ├── 96f37f1f1185bcc148d704b9a65d0da809268e6b.nq.gz
│   ├── 9c5fbed6ad98aca31e5de2d82d10b45ab90cf574.nq.gz
│   ├── a3219603b1cdae0bc7f06099c65e4bda5f249217.nq.gz
│   ├── a39c36bf506dcde271c1d48c5e8f26da6da72210.nq.gz
│   ├── a58e1e82104973facb62ea3cf4aae482d3d24db8.nq.gz
│   ├── aedeb594d046c79110ababcc8642765bfed54b09.nq.gz
│   ├── af489fb67e6ad596cd3e4bb7b077e195ac1b438e.nq.gz
│   ├── b4223f4ab30a55868becece044cc4b2b86181233.nq.gz
│   ├── bb41d8555cf5f8eb721cff8605eb81b4eeff6347.nq.gz
│   ├── c62d64ea1550b99c3e1ecfca2dff987d6adeb360.nq.gz
│   ├── c678fa29c134c2790c103a354905b4e08353e737.nq.gz
│   ├── c779ca5ceb2b20ad4e1eb16c9cf9da20c2263108.nq.gz
│   ├── c8f925a1b8365c1de9cdffa90125360e5ea56e1a.nq.gz
│   ├── c8f9820cecd4827157bcd01e3d36062eaee6af7a.nq.gz
│   ├── cb993f3020b19ba6f9d9c734ffdd2102915d78ff.nq.gz
│   ├── cdcd41b7563a5126f0daa285a261aff2235614f6.nq.gz
│   ├── ce55b94f65a4951487ccf57ff8d50a210917864d.nq.gz
│   ├── cfcdb5be0eb0c876d3e4d7db9e26ba8c059a777f.nq.gz
│   ├── d44eda241d98616989da830bdbf820dbe5fc5d4a.nq.gz
│   ├── d5d1208240b6e5e983d202caf2148f29e32918fc.nq.gz
│   ├── d6faf7680d0eb360bf762696ea851a97dd24493e.nq.gz
│   ├── da3c197976c2f2ec3fb781f352ec07a146238905.nq.gz
│   ├── dbd4b00aa31bffcfc4bc16e2410439e2cb0e9fd3.nq.gz
│   ├── dc1f3619b1da2ea33e03b61b12993ddbcb8c693b.nq.gz
│   ├── dca6ec0074896b1d65de2a83653cd72eb66f823b.nq.gz
│   ├── e0e7e1019c116dc091deb7ce44657d7c887ed08e.nq.gz
│   ├── e212561ecff1d0c78f5cb9c647b54f1513806fad.nq.gz
│   ├── e4823406361381aad5649d989ac2bbb93b8c2fda.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e76ac50f7fec558f8ac9d8517c12d331eb7f7fd4.nq.gz
│   ├── e7bed1c773693ee4849cccb8cffb3bcc91de4fec.nq.gz
│   ├── e9609ef7a4e520ea5120a9aa6911cf9c8c28f0a3.nq.gz
│   ├── e98148b89531a2d2e15c6952bc582a9146fe5759.nq.gz
│   ├── ebc30482a5e3de9c356ec77d22239f1b89b8849c.nq.gz
│   ├── ec0426b23ac135fe3f307af0cdbf967812ce4e8e.nq.gz
│   ├── edce369807bd906272bf4f221b28fe3caac9f09a.nq.gz
│   ├── f452ee37a2876bcc8e91bc1a7344565e62072222.nq.gz
│   ├── f7b3a7a836157e8c420622365d9a3341d258e644.nq.gz
│   ├── f80f9f15e3c10f98348b9e25343b9d2fc1dc1f9f.nq.gz
│   ├── f8766f3440b63662787087c93e8ba1ad3ae448bc.nq.gz
│   ├── fc3db482124f58312a87189c979b3373804f8613.nq.gz
│   └── fd6dc4ff9802d08ad652f52be2e8cf4ff00cb2fa.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ef83d29307061c65d04b035b4f4e7c18bd8374af.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 127 files
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

[beir-cellar/beir](https://github.com/beir-cellar/beir)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
