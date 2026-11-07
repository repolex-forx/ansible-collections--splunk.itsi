# Repolex Knowledge Graph of ansible-collections/splunk.itsi

RDF knowledge graph data for [ansible-collections/splunk.itsi](https://github.com/ansible-collections/splunk.itsi), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/splunk.itsi
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 09107efc6e2de40d99007de5732d96e0a3a44613
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 09107efc6e2de40d99007de5732d96e0a3a44613
│           └── chunk-001.nq.gz
├── blob
│   ├── 0348046464cb804fb8a50480d5a6c0b22d2ff5f8.nq.gz
│   ├── 03b10dc0acfcea5a2f0184cd5b96cec4418ed552.nq.gz
│   ├── 0689a57ac84b575ee35a1de5a14a4fb17acbc20f.nq.gz
│   ├── 07129ca2ff7892ce2ade7df779359909bdf6ddd8.nq.gz
│   ├── 0ff2edf69fcfbfbab3a7b36db97b060537ed5422.nq.gz
│   ├── 1507158d38cc1f7670959be88425265c476a7f03.nq.gz
│   ├── 15493ee47465d5084dad433eefd41ed549675fa8.nq.gz
│   ├── 17493cc286ffca969b6040184eefa73779e9310b.nq.gz
│   ├── 191e942b2ac0124f524267fceb689f3a205135b1.nq.gz
│   ├── 1e941c517a6d0fcd3fc22aa64ccf125c585167ec.nq.gz
│   ├── 21bf29dd4c9cb9c2b95d1a512d64406d5ff7a9d0.nq.gz
│   ├── 23d65c7ef4514be9029e7c1d73b885867d81c383.nq.gz
│   ├── 25ee44ac478a48056890b8f5d203058d589db52f.nq.gz
│   ├── 263d1f45e4aa9c04e4a1147530b233f47bdf1428.nq.gz
│   ├── 2908c39fdbaff4b72fd364ac62bf087a346168d5.nq.gz
│   ├── 2a07f4db9b28f772a27b20860d0f8077e99e2199.nq.gz
│   ├── 31368dcb706b75bcac97144613cf8c5b6bfe7002.nq.gz
│   ├── 3367661448a4853a0dee833e5739ff289bb7c663.nq.gz
│   ├── 380a5fd0d00bec004dd0453ed554da1ba10d8aba.nq.gz
│   ├── 385d0724a66a9df52485a574dc5ada291f013e6d.nq.gz
│   ├── 39867bc51e9a9b86ec3a6aeed7e801b0f6839b75.nq.gz
│   ├── 3c8e0eaea72422cb44556cc6f4b54fb190613258.nq.gz
│   ├── 3f5c555f90f78e81802426d94d530dea10d23289.nq.gz
│   ├── 3fc06f8fcb342b7ccdaef597e12611bd0620a7cc.nq.gz
│   ├── 421d8bf2fdf391d0fa9f78182b2c7f4a4319d2b6.nq.gz
│   ├── 423c4589ac4f19bb663548bebb39b54b36e3fedb.nq.gz
│   ├── 426d9afcc7722413feba6f81b971ad85fe247d36.nq.gz
│   ├── 46614f4cc8f9bf27f2f50772d6706e0f2e4ead48.nq.gz
│   ├── 491ffb23fb22e7beaba9223f13d50679c5c8f435.nq.gz
│   ├── 49c7554d4b2efff8e88120c51a2ac96526c1dba7.nq.gz
│   ├── 4a571f63013032ab58fdb28c94e2d3f79cf6f70d.nq.gz
│   ├── 4d8ae665b68e2f1debd74df5a1edefccfa507203.nq.gz
│   ├── 4d9a1d540ee17bdfeba3cfcc1a202cbfd6f6ee91.nq.gz
│   ├── 4df123f5c5f378576510f6f8aeac4a3005c29049.nq.gz
│   ├── 4ebb95395297a5f3d890d498985015e6d7251955.nq.gz
│   ├── 52b761f0318ebab7985b2861cb0587e61c312460.nq.gz
│   ├── 53ed891fa0be59bcaecc71fd742c13d21df3889e.nq.gz
│   ├── 542b09c3752728a97b8fdd3f4657bbecff09ba9b.nq.gz
│   ├── 5a9e963636961b973065381ee709f84230c33975.nq.gz
│   ├── 5ab837490c67b7400f0ecc406eebe785211b5202.nq.gz
│   ├── 5c2caff7a19866ab7dd91543e3551060216f2e79.nq.gz
│   ├── 5d177f369a29f4d527b7d652c79fe9286efac385.nq.gz
│   ├── 5d838fad79c10c6ed99b8095a77db0d83cb5d8ab.nq.gz
│   ├── 5e95ee10ffbc939d4e9b7e6767ef20b2b18c8a62.nq.gz
│   ├── 5f709c5aac15f11a4cb08bbb627883011ff762b7.nq.gz
│   ├── 628a96a93d7206db41f52dda2db82190830d75d3.nq.gz
│   ├── 63b8c1056d4f0965977e210955fde21e146f155a.nq.gz
│   ├── 650330179af03dfc3268a977982ebfea883bd35d.nq.gz
│   ├── 6599700c6e917762ca01c9925212846a9bb3106d.nq.gz
│   ├── 677cfa873adbf9c7c0f06c40305edb242cb544cd.nq.gz
│   ├── 6a2c5c1c5facf53dc4240a0fd86478b5b765d03b.nq.gz
│   ├── 6b6c807529ede4e68b37f0e1daf96271e8aff207.nq.gz
│   ├── 6f5e54a6a74f3d9246991bdb7451d7759205aa61.nq.gz
│   ├── 6fe2c43ad80ed3695917f9155b12d97ba5afda5c.nq.gz
│   ├── 740c8115458b12e3a8f24220e718e0b33ef2e16d.nq.gz
│   ├── 78686b65c48ae86eeef1bd99bd0b5a7b6dd5be49.nq.gz
│   ├── 793e272ca6452ad470e60a778f2aaf8e9ae0ce44.nq.gz
│   ├── 7a190e6d9eefb401b75d7498d3c08be970364acd.nq.gz
│   ├── 7ac266b790e58f00bbb626166075d20545f34507.nq.gz
│   ├── 833e0002cbee79d1e656d17488479c6828bbc4b9.nq.gz
│   ├── 84634922bd169e63647f84c1ac56ed849c3f5651.nq.gz
│   ├── 873a02b1dcbfa9a63fc9384ffbdd87e173d2d55d.nq.gz
│   ├── 88986566aacdb333927827515c0ac959c6d0e746.nq.gz
│   ├── 8b363cbd282a4b2f79f60e481ba20f88139105fb.nq.gz
│   ├── 8e23a46dfae03c38f7e81b2e34344972836cc671.nq.gz
│   ├── 8e68aa3ec801b174874ea29f387635ce82446cc0.nq.gz
│   ├── 943a537d6e1b4cd0743ddf2e7230d37396708640.nq.gz
│   ├── 95458405b092a0a207639a21c3b77a055fbe122a.nq.gz
│   ├── 985040b60afaa60f46d81f35adb55f64fed7b15b.nq.gz
│   ├── 9a2fbbb00e2f942369cec3491f65601bd68d3cf8.nq.gz
│   ├── 9ad544282d1e477485b51688f2bbc6cf0e32615d.nq.gz
│   ├── 9bbeec070b6a8bc5fa53cc075d6689291f7d0cb9.nq.gz
│   ├── 9d8e641fddf67ee256517a328181706667ae4362.nq.gz
│   ├── a348569689f3d1ff6921072a493d52fede70502f.nq.gz
│   ├── a358b4be1f9ac5e04525d1408dafbe89aaf9f46d.nq.gz
│   ├── a3f8c75d78b45e05637518551d04957ec8a08cf7.nq.gz
│   ├── ab19d04537cd7fbedd46ee4f8f9aec5a12061f05.nq.gz
│   ├── ad1dac22008aea5c0a238f32a6fdc7feff80437d.nq.gz
│   ├── ad796546fab19b8807ee322936a418c4c091cdf1.nq.gz
│   ├── aef3c01bdf58d52c5cf9792d06253f1eaacb5381.nq.gz
│   ├── afcd8349f2bd5cbd6dbf2f0e63dc4071a1df7f40.nq.gz
│   ├── b23a3b7717a80e2bd6666a2010d926f4d7c0bb23.nq.gz
│   ├── b28dd7729322dcc564d2a233e5635a34bcb0e0bb.nq.gz
│   ├── bc43668b6939a0a0fe23cfa09e335de191716f27.nq.gz
│   ├── beed132db3040c32bc783ca06df1093cedbc4b11.nq.gz
│   ├── c536b90c51a89c93810937ff2034eff3e9a4e3fd.nq.gz
│   ├── c77c91a907b70246b052ad4ea0abe51f052aa88f.nq.gz
│   ├── c7e4fd2e684b80a99759f8eec513566a8ad9f36e.nq.gz
│   ├── cc0747458e7b097144c642a6a3e10f5a04a8d78b.nq.gz
│   ├── cdf46a5276bad3f91421bddf2acbed28afe57e71.nq.gz
│   ├── ce18928b52b7dc28d5235c5b6170ebe75f6887fa.nq.gz
│   ├── cf89705393934742255781bb36f0a2c15ad1416b.nq.gz
│   ├── d0970ec0ca671212cb1d6573a6871bc90f08e889.nq.gz
│   ├── d12c1efe28855cdc80e307a52f723a465d57920b.nq.gz
│   ├── d1e2a14dbee07d697d9883e039cb56b487a881fe.nq.gz
│   ├── d78b4e9187a7fb3d4f29986325d6f86bec01ae41.nq.gz
│   ├── d8e72b0c2ebddc0012c637e69930612303d4cfdb.nq.gz
│   ├── db24c92565dac771c58991d04faa213f77d5f016.nq.gz
│   ├── db6c7fe32f3790968174d5b6c166a46f0df326de.nq.gz
│   ├── e0f191ed12a1b907df06d60dea6df2573894d0b5.nq.gz
│   ├── e5817ab2b261acc36aad318adeffdd4f6504e724.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e969535766bd5fc5183b31ff29380345fe6b0709.nq.gz
│   ├── ea01f64217c4f4c36cfb2afb4ffb1b1760132807.nq.gz
│   ├── f08d083ca2bf477715d76aa54800ec9caf3c997c.nq.gz
│   ├── f08f43191b8b85ff1a00ce3bcbfbe470179dfebe.nq.gz
│   ├── f10ea9c20140f34817f6dea82bc1d7639a386f14.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f5682a01af29b7c9992abdc3e61779aa87f6f542.nq.gz
│   ├── f7ddbc1f89407a38c093d3f4d18ece7dfdb72ae2.nq.gz
│   ├── f9159976df37c2d5e00ef45bd5902cf699daefa3.nq.gz
│   ├── fa491961be2af3c306b116e7a0ee301abb073811.nq.gz
│   ├── fae464a3a00a23fa07e97a06167b5559811bdce4.nq.gz
│   ├── fb273549b80a85f83b82e00ab671c1e1803aef68.nq.gz
│   └── fc8ff48f1d6a8bf31edd06f19b9d2bde001de981.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 09107efc6e2de40d99007de5732d96e0a3a44613.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 123 files
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

[ansible-collections/splunk.itsi](https://github.com/ansible-collections/splunk.itsi)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
