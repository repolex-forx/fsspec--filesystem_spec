# Repolex Knowledge Graph of fsspec/filesystem_spec

RDF knowledge graph data for [fsspec/filesystem_spec](https://github.com/fsspec/filesystem_spec), parsed by [repolex](https://repolex.ai).

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
rlex download fsspec/filesystem_spec
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 685f62eaf4baa00a974e1f7865746a1879816d9b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 685f62eaf4baa00a974e1f7865746a1879816d9b
│           └── chunk-001.nq.gz
├── blob
│   ├── 005e15a1c374d15c954f30204b317a1593974ad2.nq.gz
│   ├── 02d33ff13959436d882897e35293468e1f818557.nq.gz
│   ├── 03dc7eb0607656744a98020a3c0be9a7b1cfbd54.nq.gz
│   ├── 0593eed6b5ce0dc0b2abba3f6531c39d9a4bbaff.nq.gz
│   ├── 06dfd7a12577b18232b3b35cffd2a7bc70a13db8.nq.gz
│   ├── 0969ac68b52da6038fb1c7939e4e1042c2a03ec9.nq.gz
│   ├── 0a93955540b8e69f10c714b7e657b5107d6d18db.nq.gz
│   ├── 0c7579481305b0c70dcd3d27aab3d63aa78b420e.nq.gz
│   ├── 0cf6480538083244727c5ca2be2166b168612bc4.nq.gz
│   ├── 0fdf4497bbf25acd37c4cbd4a285c3945af0c596.nq.gz
│   ├── 12a690c24889cb4e72d4e107574bcc7832893a25.nq.gz
│   ├── 13756d95b8c6d05cd39542864cd0f0bee46e7f43.nq.gz
│   ├── 13fb5e1216051962358989b9cdf3510ea4115f3a.nq.gz
│   ├── 1415d65cd5fcb52f699ff57b2729a334cfa2d87a.nq.gz
│   ├── 14573eef3c55b380c42332534c74afc9874e5bd0.nq.gz
│   ├── 156f036652ddedec19f729e2a38ab6af373fffbf.nq.gz
│   ├── 16fffc59dc4381614b90acd9bc2875116bc9774d.nq.gz
│   ├── 1b7f03f66c94dccf7880546728ce1c3f110bc10a.nq.gz
│   ├── 1bd3ae4aad2e8c6fd35d7039d719b95bef9362ce.nq.gz
│   ├── 1efa1aa6b5e0c885fd4c07f1aae6d9b9b1b238b5.nq.gz
│   ├── 1efad1242ebccd793cf0defe29d3cf66ac9a0fd3.nq.gz
│   ├── 2053949a446c50ce2a9b893b339d05d69c4618f7.nq.gz
│   ├── 2093f1d15ffb1750a786c48fb259c66d918b6032.nq.gz
│   ├── 20fd78f6ddd735a46e3e086ca9fddc21af2a323c.nq.gz
│   ├── 22e7c4140404ab2a8928689721419cf05c2760b9.nq.gz
│   ├── 23adf59b83a10e3214e123b5482909a9f796ed9f.nq.gz
│   ├── 243ac8c6c3f45a5e674f8ad27462f3cbfcf5ed4b.nq.gz
│   ├── 2549772527d15e2ea975533ad8c5afe2f43c5cb2.nq.gz
│   ├── 25bd341e93edc0c05518a4ea3b64fb9900125754.nq.gz
│   ├── 2678089b56fb0a725a588e78acef5836c59f0095.nq.gz
│   ├── 271cc990f013f03d965b92f5b57cf92699b4819c.nq.gz
│   ├── 2a48231cac9f984f3e41bc9f81a113ae28a1f5dd.nq.gz
│   ├── 2bf435e20c3472a7dfcdcc5a0c53764af6fc47fc.nq.gz
│   ├── 2cc679d0299ed4ecf4407be3e0a0f85cfa766feb.nq.gz
│   ├── 2cd534e9554faacc83d3b29433381e8c0053c850.nq.gz
│   ├── 31d0e87a2da8334c09023ecf8e3e044258a2eb95.nq.gz
│   ├── 3671e1226807f94fc90091d1fcabb16055d70b65.nq.gz
│   ├── 370158d13cc7c5217acb4cb0c7e36f2e89731578.nq.gz
│   ├── 38b83a2cfb49517e387091441d77f80e1ffa1aec.nq.gz
│   ├── 39834aa9db727e7c90d8b6410df3436ce078c4f1.nq.gz
│   ├── 39a62b6d3b6a895fc07e0a59821d428d1ac66cf2.nq.gz
│   ├── 39f6caa3de815e024fa84de2acecc986c823ed29.nq.gz
│   ├── 3a0d233e2579b720c5880a399d081c1dd19042ed.nq.gz
│   ├── 3cff3aef0b70c2cdd34b1f684245f093a85faf5c.nq.gz
│   ├── 3d178e2b46f7bd205236ef2df07d83222f01efca.nq.gz
│   ├── 3e1276463db6866665e6a0fe114efc247971b57e.nq.gz
│   ├── 41386ff30e827581563de87df562d88832eedf7c.nq.gz
│   ├── 44ad398f8d525ab60235501631ed192c553b3a61.nq.gz
│   ├── 4692e699d00d1db6a767b374a22755dffe73d6ca.nq.gz
│   ├── 4890890fe9979dff753878c6d9ba867dea2974f6.nq.gz
│   ├── 4b6a35a1c2ca6b894f5945edddba75791efa7eaf.nq.gz
│   ├── 4c95a92c8b78adee796c2bc182bf714360d77970.nq.gz
│   ├── 4efc98fa0d6564d52f1ef44216311cd39548a3e8.nq.gz
│   ├── 566d520fce3e94e3bbaee48c3c6acc9f1db315a8.nq.gz
│   ├── 590321a1eea2cfb07299a9c2d9abed6d57c060da.nq.gz
│   ├── 591fabfe19541a4d80c58c055d0ebfe30767b195.nq.gz
│   ├── 5a1a32cba7f524d1427c3aa75e58af6c9ebef0f4.nq.gz
│   ├── 5ab6cff949415e60d051949317e5f797d4d1ceca.nq.gz
│   ├── 5b0cd5792d48c7dcb007c6de24ab45de48c86424.nq.gz
│   ├── 5c338eb2e2442524a4d80e4053cb1160be1d3458.nq.gz
│   ├── 5cda044eb606d5356c1a21eacad9d62b2262ea2f.nq.gz
│   ├── 5cfc693ee917fc694b8833f580f94efca0ca5093.nq.gz
│   ├── 5de87eda16630e55f6a48eae3e145515c167d9cb.nq.gz
│   ├── 5e1fcffbbf48ab9abe7f3454852d5fac16d82a8f.nq.gz
│   ├── 608097a72d047a29342534c9fd87d293dd22b2db.nq.gz
│   ├── 652c758aace9c942404e62a0399a67c1fa690b71.nq.gz
│   ├── 65cd84c0078ad626f4b28b5e9531dc291222624c.nq.gz
│   ├── 664980a695531e9d9f57bfcb1ec014e92c6406a3.nq.gz
│   ├── 67590a5e5be5a5a2dde3fe53a7512e404a896c22.nq.gz
│   ├── 67b4a0f929cabbe8891aaf2ec448908c459f8618.nq.gz
│   ├── 6958a33b1723a529b9b3dc7886a430803a1e466d.nq.gz
│   ├── 6d1359bfab734fe22bb3745f1f8eecd4d81999c4.nq.gz
│   ├── 6d6c2837c45a9a11705f389d9d549b06d41d2133.nq.gz
│   ├── 6e7c7d88afdddf12f77b26bb635bd8bf1e2bd7f1.nq.gz
│   ├── 6f23e7ae5eb03ef6979108aa5b69efb28ade16d7.nq.gz
│   ├── 6fd13bd783c3c02839abfd7ab82bcb5f7613a885.nq.gz
│   ├── 70c5c0c070e1e13c4a5705b05b8773673871def3.nq.gz
│   ├── 7167efad17b5874697f5935bcab47f03df850988.nq.gz
│   ├── 73d6ec40b7f7a7aff2fede8d61b8581ebbf9b21e.nq.gz
│   ├── 75d18ebba7db998293b2511af07670b439bd0b06.nq.gz
│   ├── 784f50753f2af9fde4f16a7945a10bce8f76f1c5.nq.gz
│   ├── 7884ab41d8ee97cd62363d8916deb274953baf66.nq.gz
│   ├── 79272ad201fa2ea340843806efbbcfa9fc258b2e.nq.gz
│   ├── 7b02e61ed56e4d87a81f2c868d2f7c4b67f1e94a.nq.gz
│   ├── 7ca99ca6ac3cd69b28bcd1550f6550e8e648c5fe.nq.gz
│   ├── 7cab1d1cec8ac2fc2cd3fa6e945424c17ba3431e.nq.gz
│   ├── 7dce3ee4ee98c6392e3b21ffc96ca9ecce550e0a.nq.gz
│   ├── 800f1a3f09aa74e9768caa1098b9aa2e58cee8af.nq.gz
│   ├── 801cebffd475bd999a07180fe78e8df7356e2fa3.nq.gz
│   ├── 82318ceb28b350d7746c470ede23ebff6cf3b584.nq.gz
│   ├── 825af1e8a45817dadd8d31230f0424b48ec9206f.nq.gz
│   ├── 8313ced05fa16331996f0576d7539ff9aeb3c21c.nq.gz
│   ├── 842ad8cdc42ebf64a1f1fc3829372290f1b775f1.nq.gz
│   ├── 851ab81ee581e74cac41c64c83ef0af75826d6b0.nq.gz
│   ├── 866506bc5c039dcbaa682267f927b030c59aa9c5.nq.gz
│   ├── 87132562966feed01afccf2ad312d404fb5de791.nq.gz
│   ├── 8c36312212f3c2ecbdb15e83fc9accc5c581e96d.nq.gz
│   ├── 8ecca96e9d23ff268a253c48269d5cca451ea270.nq.gz
│   ├── 92b27ea59115cd929c72338c58c3606f2d4da318.nq.gz
│   ├── 96692a703003f38bb88d4654b1495dde505db6da.nq.gz
│   ├── 96fc7ce236cbfa2a9c501aa345ee4827a329ec87.nq.gz
│   ├── 9ad3eea47d31ab8f6d6e71a441653b7153afec99.nq.gz
│   ├── 9d914c8beb6cabb2c2700eb8eee31028559be2bd.nq.gz
│   ├── 9fc349977f0384d9fc86126498be5c6ad99a21d3.nq.gz
│   ├── a0a41331753bc841e3d9cc4dfb57db37b25d391c.nq.gz
│   ├── a2c01431502a7be0a714b268ba4475397bcaf4b0.nq.gz
│   ├── a368d06bb26edb7ab3182324c32c4c4f2d6cdd01.nq.gz
│   ├── a49d42aba39cac3fb046adc2a2e76e410c2cbf97.nq.gz
│   ├── a5ae427be086c6005304d6b2185d19088ad210ed.nq.gz
│   ├── aa29f1268a619d5c0b6c5f34ced44db94926eb7c.nq.gz
│   ├── ad9ac0b6a1cdbcfba6188e2cdeab2350bb9aad0a.nq.gz
│   ├── ae8905475f02655f4fc5863931d99ca9da55db78.nq.gz
│   ├── afbc54f1b6ecad84dec8f0aa624290c63642bce1.nq.gz
│   ├── b24d7e4c2d5cd4b8335052be51a7dad43f0fc622.nq.gz
│   ├── b3909e6715ae283ea59fadb83e923fe8cfe266e4.nq.gz
│   ├── b71ed64632d5a29428866c37f54a92eee50a6cfe.nq.gz
│   ├── b8cf8b5587a82e3057e6aeb64141e5a8f778c7cd.nq.gz
│   ├── b94b13b104a91f089da868e85d86828a45bb50a4.nq.gz
│   ├── bb75ea852276fb8d834345883813b8e27a0ae24c.nq.gz
│   ├── bfce64334e8db0272eefa96b4428b23524b059f0.nq.gz
│   ├── c165d4d8275a5a0a67cc8f5aadde44379426d793.nq.gz
│   ├── c5136fb99a5b8fc9385fed59218914df17a04dbe.nq.gz
│   ├── c5280b70302c7d7b02db70016feaf1c43761e956.nq.gz
│   ├── c6cd634284379c93b2da8d6c8f59dadc52e523b1.nq.gz
│   ├── c74dca9de2f9b173216ff987688d92d8676dd032.nq.gz
│   ├── c8bbd264aba49d390401a00770150e09b7fbb7db.nq.gz
│   ├── c92967c847740e472478720bbd9357ed8806edc1.nq.gz
│   ├── cc268da0bd17231338856b3536ca258869d8b001.nq.gz
│   ├── cd36acaaa3c6302c90b47d5fd86446376774c7d2.nq.gz
│   ├── ce1f239ac0cad2ea732241a7594dd4ab5e5fc7cc.nq.gz
│   ├── d07c1613fb117a919d1052c43714ba782f8481dc.nq.gz
│   ├── d14d049612a867f3f2ab39bb8c496e2ec8bb36e1.nq.gz
│   ├── d19f87c8288e0a5596a0cc3306c4c2b6d6ac6e72.nq.gz
│   ├── d34357994bbbb0042859a366baf9e98f2e0b3ce6.nq.gz
│   ├── d3df39ce4ddfe0dbd62a403631bf8c69939968c0.nq.gz
│   ├── d53546abfac5715d779b688d453f4be644d14466.nq.gz
│   ├── d59902d701fe21932547fd65ff5ce3d6b677c01c.nq.gz
│   ├── dc730cf56893b9c9b542fb4b91710cf25ba921bc.nq.gz
│   ├── dded3c8f8b08bbe48ea4e573dc50ed9863d94f09.nq.gz
│   ├── e2d2dd46c3aed10b1f0da750f47c6a09fc7ebd11.nq.gz
│   ├── e39e57e5f7d52bfda8ab5e2398b04cc2303630a0.nq.gz
│   ├── e55bc0f4b213fb4e8d5ffdbc89e74518abab57e5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6e03fb14f9ec9224804a2ccb77bb84fe3390952.nq.gz
│   ├── e6f29760d2c09faae2c08f12a18374b89b5af0cc.nq.gz
│   ├── e9e57e8d036e644eb9c6ede3428254a822dca8c6.nq.gz
│   ├── ea7f6cf83bcaa10241894fa00224e1e6f3717e0f.nq.gz
│   ├── eaedbae5dbab224a9f7cf957a84cc8b0d780c291.nq.gz
│   ├── eb279ea828762df3298296205a8f6732bd44513e.nq.gz
│   ├── ef300536774e82685d8ae1c8a23d1b6158c14d77.nq.gz
│   ├── f05eb5c30d42b0c1c5cc432f9c217d8f0e01f412.nq.gz
│   ├── f09f13ce048fd05a0e3f4a7bc199087706e2fb71.nq.gz
│   ├── f14fd003eb494b8a21449235a857814e20f48d33.nq.gz
│   ├── f5414dfd4239b27fd9a7c3946cf82d889d45106e.nq.gz
│   ├── f61360991804ea1a20ad87efbcfd7d6dbba6c311.nq.gz
│   ├── f7fe08fb1ca9d00fd1e58a12a3371792a04b687a.nq.gz
│   ├── fae72368f5a9afdf83143da74dd2786644f7664b.nq.gz
│   ├── fd669707cb755597770a2e6fde36bd61932ff798.nq.gz
│   └── fef9bcdd90e392b83c107edcba2d53f52fc7f97f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 685f62eaf4baa00a974e1f7865746a1879816d9b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 167 files
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

[fsspec/filesystem_spec](https://github.com/fsspec/filesystem_spec)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
