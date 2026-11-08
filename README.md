# Repolex Knowledge Graph of canonical/cloud-init

RDF knowledge graph data for [canonical/cloud-init](https://github.com/canonical/cloud-init), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/cloud-init
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0d7893291a7e7c0c0cb2a087c107aef3fcb90b47
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0d7893291a7e7c0c0cb2a087c107aef3fcb90b47
│           └── chunk-001.nq.gz
└── blob
    ├── 01188159dc1b99abd2615ed978cbfc27e5d9dab8.nq.gz
    ├── 01da83fcffb25a87c597a97b0050c482da837633.nq.gz
    ├── 023dfa2a94ba6424939972ffeb1ea592804a57c8.nq.gz
    ├── 02abdfead7143d87e1a1877996335bf7945006bf.nq.gz
    ├── 02b421b7c412480e6f0799fe1db0e89cae5c2079.nq.gz
    ├── 036b80bf116daf63528ddcf08e06417fd2bfb535.nq.gz
    ├── 038dfb4d10ce415f7cbfa0255aaadc6942bbb45e.nq.gz
    ├── 039d1f15b26f9915fe3ce12dfbd643780c9b6acf.nq.gz
    ├── 0427dee67124291a1de1bdea5db0babcc12f3b9f.nq.gz
    ├── 042de31c8d093cc8258bfd3e3c90a5c3c7b16183.nq.gz
    ├── 0489114bd5a00ce0858dd50b2538606b06522ee0.nq.gz
    ├── 059c65e7a78a47d0e67a5659c649a6cba88e72cf.nq.gz
    ├── 05a69b88fc160cefeef64f2c0e4ef0a6449b8d9a.nq.gz
    ├── 05c8a50aa609726bcea66b91239454742d21fe70.nq.gz
    ├── 07adf40890f86ab267a743cb32fc282db8ca1cc2.nq.gz
    ├── 085946e19e3852d94f7c9259b1f3651115c803b1.nq.gz
    ├── 088530ce5cb02b35b1cee95a0cc934588ebb7e9d.nq.gz
    ├── 08d4c4c5ef88efe43a0fccd986678422278d0ac4.nq.gz
    ├── 0906d3dbb10094b85fb6eac45ef229f4932d8fcb.nq.gz
    ├── 0a0233eb8688c0f2a3221859d7a2f0b37a4b53f2.nq.gz
    ├── 0a99114a94faf5cd99e7ff3466b78af5c49bc3b5.nq.gz
    ├── 0af1ae6543c668887e0f852ebe4ffb1f2316a322.nq.gz
    ├── 0b6401108a461b8f2f1dee2a9ffc9db655da20b6.nq.gz
    ├── 0c02abffb7d34241c8a2ab62c6d95d476d720ae3.nq.gz
    ├── 0cd100033c46e254e9ed27f29072bd71dbc781eb.nq.gz
    ├── 0ee0d33f386862bd35e4ad53693937eefd1d582d.nq.gz
    ├── 0ee33d0b8210026964667c9bf7211bc3b1c550a7.nq.gz
    ├── 0ee68ba653db35380516ae623616143df0e16d94.nq.gz
    ├── 0f329faf3b2064a55ac27e344318a26af61180e1.nq.gz
    ├── 0f3e0c76439ce34055510cfd5cec5e0ce9407ab7.nq.gz
    ├── 0f4a5dac50bb2e8bdc106641f53a978256b66c54.nq.gz
    ├── 0f5a16cf7640ce79a3a1b352c3b108689d916bba.nq.gz
    ├── 0f60ce4fa573599c95cbfd3bc4f1e6d8600b29be.nq.gz
    ├── 0f83f7473dcfa9f25d4638a17c9edd633b2dfd9e.nq.gz
    ├── 0fd6f72294ffcfdaaf06a43d499742ddb39a59b8.nq.gz
    ├── 113488cf108551af38e30aba8e3e0278695c752f.nq.gz
    ├── 12bab32a1b4dab0a8ebe384fca24d888519c3e37.nq.gz
    ├── 12bb1c12c2accfdca35a6e8dc5e94858320f8cf8.nq.gz
    ├── 12d7c24475af1b98652e3df93e7badb48aa9ba5f.nq.gz
    ├── 1391aff17b600bcba31aa3bd30e7c49861adbad0.nq.gz
    ├── 139542bd9b5ec6155830da19ce3e63ede8ddda52.nq.gz
    ├── 142c9048b1ede6d6a617ddd61f44d8c8a39e1462.nq.gz
    ├── 149bb8520278e5e555bb69ef8ce6460fbf39b46c.nq.gz
    ├── 15b1087f533199b361637c2b0599cd15d4a2f611.nq.gz
    ├── 163aaf8d82b6c54f23c45f32895dbdfdcc27b047.nq.gz
    ├── 166e033f40b121518cedf1611076ea4cff4f99e7.nq.gz
    ├── 167fc940afd5ca3a340b9df6f25ac632b9a29d44.nq.gz
    ├── 16cf72ade835c5781e7ada2e6b71587baa84c2e3.nq.gz
    ├── 16ea4e32dfb5dd5d121e8cfd398e6007f2b870fe.nq.gz
    ├── 171f45c3c65fe1c9c0e5361ea25ec980f38d4761.nq.gz
    ├── 18d13dd41c707c9f93f19f22f2a683521b6098b7.nq.gz
    ├── 1927ee70a4c073ecfe7e99bec014f22ef1ee2bdb.nq.gz
    ├── 19e5db2fedc304850dd2436bdd77d6fcfc5add64.nq.gz
    ├── 1d522b6a17d749c009692e13dbc7e03ee0b45c6a.nq.gz
    ├── 1e04fc2314d87e275d39135ce9c4553f32d0fb74.nq.gz
    ├── 200d2e1af01ca8abf5b9b2b1d400231595a8923b.nq.gz
    ├── 20143c0484eaced7dd8f9e019844663f89600b94.nq.gz
    ├── 21240582f9aab494e2c630042d4d7032e817ac9b.nq.gz
    ├── 219b5edc387f875b8d3ad929cece61d5c9ac805a.nq.gz
    ├── 2221f82ae7815c756ff4df1ae64e5275cc31a8d2.nq.gz
    ├── 22df4fb3f257d7de0a8cbb5a966456db2c53e457.nq.gz
    ├── 22f059a5b3e4e934ffd598528a4370c638c69d25.nq.gz
    ├── 23293460719c2aeefdee9ecbd53ebe28889ec0a7.nq.gz
    ├── 2391447e2af0cd6d6d55f975b3685960cc72c2f2.nq.gz
    ├── 23a9b0eecffcff7d51e5b47aa3da2042aaf0b7dc.nq.gz
    ├── 23d2961cf1c7482bebf98dda449600e1d1909e75.nq.gz
    ├── 2421309836a908114216e85597cd9548238f20bb.nq.gz
    ├── 2528264d1e81ea670ffc9ad22173d71d2806273f.nq.gz
    ├── 283c6069a3910bd404aa7c5d1293dc845a75c23a.nq.gz
    ├── 28a4527c812edaac648779cb6bf0e504409b334e.nq.gz
    ├── 28f537a913f3ed3e493de05ea6c6bb91101bcd82.nq.gz
    ├── 298c2557fa45081b3917283b03790d429b690d71.nq.gz
    ├── 2a3b18226b5e0833efe3a5748a89449fc0d48b28.nq.gz
    ├── 2afecf86c810c7388271f0059f57872199413ea7.nq.gz
    ├── 2b192831e5c2996175ed4c0f16beb12d5e3f0d7b.nq.gz
    ├── 2b7339459020cd7fc0b60a389d63531d92143c81.nq.gz
    ├── 2ca4689d1d8904dffdd2f93b291c8af44626c8da.nq.gz
    ├── 2cfb8faf6fcda7b492ae5e17a83654d845acc406.nq.gz
    ├── 2d8e8fba03f0ae0e06db1cfd4e14bd3b412b3735.nq.gz
    ├── 2dab5b428fbbdd019a8acdde0cbde5081a0cf7da.nq.gz
    ├── 2daffdd999788e79792582c71cc4cdc44cb52c41.nq.gz
    ├── 2dd0bb425eb4a293145b13579cd9a1549d12adc5.nq.gz
    ├── 2df71d93580dce1e7b22d203348c36ba599e8830.nq.gz
    ├── 2ed528c06b3de386e88a71163b9372c0d6e49b57.nq.gz
    ├── 2f07f6eb0f9dd5fa994bdffb6514aa7c0d93d331.nq.gz
    ├── 2fa3aa2f512ff9d79363c5d3781f0c492ac8d8bb.nq.gz
    ├── 2fe51de577a738c8e45510fced01939b888b8df2.nq.gz
    ├── 30450f7ff23c27a2dc5a3e54073d1f4d9d4e9cc3.nq.gz
    ├── 31d66f8b4f2e3b5f34fe5e480352ac9c9fb0ff70.nq.gz
    ├── 3232503bcba1dc01f929725253954a3485e2b394.nq.gz
    ├── 32926da1dd2b23ad482d838a30b8748b7edc41e8.nq.gz
    ├── 34064bad064e071bfa40e1506c44e1a320d39a6b.nq.gz
    ├── 3409d6b65472a8b38b0eef0daba0f04a8358310d.nq.gz
    ├── 342265817c08d6ca0333d4416b80329ee02edb63.nq.gz
    ├── 347e81ae71b5dbe0758c44f1b0beee350b9a780c.nq.gz
    ├── 36fd336d8f020f64d987ee02064155d0f780c27f.nq.gz
    ├── 36ff605a4e5527c4f1c64e4bf80b3a0898f7caa1.nq.gz
    ├── 374997b8f0cfe6cc201beca0d54a482acb42fe84.nq.gz
    ├── 37df7d23451bb154a7dabf0d5cb43b4dec48914f.nq.gz
    ├── 3848263e9f0806c0586597c99a542028b106cead.nq.gz
    ├── 385964b77abc571f1ca15de9a6630f164c4252d5.nq.gz
    ├── 38baca9a1c184c20ac5cac40e02791406035a855.nq.gz
    ├── 3b0036196c2622eb2bba8ccb6385208f82a63397.nq.gz
    ├── 3b0744582bd66c0103a602e7b402d94233effe7c.nq.gz
    ├── 3b82b0161b844e8147373ccb8ac1f61b49012764.nq.gz
    ├── 3b8ca9dcf07eceb71205b70946c395cd3d9cd781.nq.gz
    ├── 3bd1790d3ae8ba6cf7514c8a08a947135c6cf7dd.nq.gz
    ├── 3bfa677dd3d1d71045591dcd1509e679612411fe.nq.gz
    ├── 3e358c8f2c80c03f3351ea1e2b6d863f48cd5aaa.nq.gz
    ├── 3f7fabb2470a4f78d7a518ea23de5e58c1fd586a.nq.gz
    ├── 3f7fc22b1ce1b95212b86a97c1c3bee6cfb643c5.nq.gz
    ├── 40112a58e1733145ac7556611428501f7848f3b3.nq.gz
    ├── 40c0a725a6dffd0f8c5cf2d18f178e0f5a3b201c.nq.gz
    ├── 427465d470cae640cff67308194aea8c6bc1a2a8.nq.gz
    ├── 429e80b95578ec1282def2e33d49ea7acb389258.nq.gz
    ├── 430c21a1396570407c9181fa310a3ce830aef41f.nq.gz
    ├── 434ba234c13cc6adae1912e9b60057002baee17b.nq.gz
    ├── 43a0a338e2054a79ce42b8087ca3a3fab03940aa.nq.gz
    ├── 43b1f5d7c38a54ef1028fa9ed6fe89a45aa2728e.nq.gz
    ├── 44167c104834f29608b3b227cdd22731aa4f29d4.nq.gz
    ├── 46035af9e2c3c539be7fe5e64350fcf6e24621a1.nq.gz
    ├── 46263d28f68cfdcc0d0ed64cbc44bedf1ebd74e9.nq.gz
    ├── 46c062cbfcf6360e819c9b34749119ff7575bebe.nq.gz
    ├── 46d81e076f68673e60f0028f44c8ee53d64ff6eb.nq.gz
    ├── 4712b73c6808824ad4323d2fc627ddcde7b02caf.nq.gz
    ├── 480d1a1d789291c7ae2f19d6823bb77e6d99b660.nq.gz
    ├── 485cff19ec5a791425328a4d2da7a2ecdaae5bfb.nq.gz
    ├── 48a59d6b281caf46886908d902d831d9e452d7d8.nq.gz
    ├── 498f1c219466532b3904d52b74d521c81dbd1403.nq.gz
    ├── 499bd6dc229807edcfaabe184ae1d241eda4928b.nq.gz
    ├── 49ea2ce7d3c4e1132fb0e79cfe26f8bf2f73fd4a.nq.gz
    ├── 49ef8108d6324e15c7de1b1c07a2e9c95f592ede.nq.gz
    ├── 4a748f56ddca685c583bd7f109ad7937eea6dacd.nq.gz
    ├── 4ab109484d0420f5f4f8768dcbfa6cbf7ae11628.nq.gz
    ├── 4af742bde2bf7e75fa28ccb998dc36bc0ab4cebe.nq.gz
    ├── 4b1ba1deef07f97f57d950cd5564e3e28955eeaf.nq.gz
    ├── 4b3db0dc3eb39f17fd0817c2dac892bc5cdaf97e.nq.gz
    ├── 4b5efcf347b43990e04d5d9b19ce37d322f44bb0.nq.gz
    ├── 4b669b0fd38a6bb3f4ecc41dd7bd7c029553dd3e.nq.gz
    ├── 4c2e702d88759432c2dfcec6f293c4bedbb7762f.nq.gz
    ├── 4c584c1333d2e0ffc03ecb1e2b9284cc9730e825.nq.gz
    ├── 4d129230bd752e89e382e43c23e1345ba230c817.nq.gz
    ├── 4d583e04d05e13a845975aab5ebb11fbecbcff4a.nq.gz
    ├── 4d86c477b5e56733142a749df8b5bce25a48ad10.nq.gz
    ├── 4d89bf7694601af7a4598f48f16fb29e860702ef.nq.gz
    ├── 4e1e5da792e11107633de4bd58fd7c1a755fac28.nq.gz
    ├── 4f774d59968691c01f63594f08d3889411476703.nq.gz
    ├── 4f8b41a8dc8ff425010ee82f872c58e859072e98.nq.gz
    ├── 5179b11150deb203c7a6742c72b98a73886e939b.nq.gz
    ├── 5200c428e8cb62c756fef92a2cd49fb4c59c3b96.nq.gz
    ├── 5261a803a9e2fd8a4e3431a3a78b9db1dd73964d.nq.gz
    ├── 52699cbec3bb6cb205e316c842977c91b4eb0708.nq.gz
    ├── 52fac3077a86b12afb6a718c2d55c964334146c0.nq.gz
    ├── 53c7a33305bef5c4eee70c70a71230b06f236feb.nq.gz
    ├── 53d04ef5486e5dc7dd97f546a447ac66574de3a0.nq.gz
    ├── 5422d4b1c33f58f7adbdd49a25cbfc4460575452.nq.gz
    ├── 545784f35315712b7daa8b92baaf297be00785fd.nq.gz
    ├── 5484fb3a626833e4139a9d9270e225f0d9ac8ee1.nq.gz
    ├── 54915fd73080b19ed51f8c0d0572f1f96764e8cf.nq.gz
    ├── 54a7bab343708b6194e884b5fc71c69a691dd1fd.nq.gz
    ├── 54d749ed517cf20242b15be553ed0aec7642a9d8.nq.gz
    ├── 558e0b9a3715d4a4373a745eb24c8aed3185325b.nq.gz
    ├── 56118ede17b2427d51a1950cf7e1dbd8d63fe1f8.nq.gz
    ├── 5651316e74b7b7ce1deab77e6d790c1cac9cf75c.nq.gz
    ├── 56534b67db9ad41a33a026f275baf240875e2752.nq.gz
    ├── 57a44c125e9997c85091ca27c7fde3113ebc64f6.nq.gz
    ├── 583a28a679d8b1fdcce3f000b1f96f364bb55a7d.nq.gz
    ├── 584741dbe3b3966316242d74d98f8994641659e4.nq.gz
    ├── 58a36f5dfe0b567e39cd98e9b75ee5adbcfdd224.nq.gz
    ├── 58e41beb478b9b943eb45679663466272489175e.nq.gz
    ├── 595f4e4546a2f9a5228502f3f7e0ef628d7ce98b.nq.gz
    ├── 59c0de358c096e7b9d10edef6683ed077fbec787.nq.gz
    ├── 5a1babb3a81192c524a7ccb58b5c72973ef9f8e5.nq.gz
    ├── 5a58f4a7cc3ee52db28bbcac0994d179799c20f3.nq.gz
    ├── 5a814989927ed82336517a91452053711c50137e.nq.gz
    ├── 5b481d53f12f7bd34bfe289003c320a888ed5028.nq.gz
    ├── 5b70be7818df5ee8a1ec87ac5094d313584002ad.nq.gz
    ├── 5ba51ae70382be09f6494552a12c2e00f95b901e.nq.gz
    ├── 5cd462a717a8de036168c2ee1aef54f9b7cde45b.nq.gz
    ├── 5cdd3fbe9f4e37308d2d970f47338b4bf81ed932.nq.gz
    ├── 5d12e352f42c6f25db0ad60f6f50384fd8b70f7a.nq.gz
    ├── 5d2e2e1b30d1bc032f65c47ea5f1e8411faa3ce1.nq.gz
    ├── 5d4206310b4a94e6ae7a8fa80724162fd8820fb3.nq.gz
    ├── 5e2452df6798d35dd22c93c7868882241dbfccaf.nq.gz
    ├── 5f4c8e8385c5768ff2238c08d5b894bb03750b91.nq.gz
    ├── 5f7ed52995376aa3c40e927e7ebb6b45498c7597.nq.gz
    ├── 5fa431a195c38ef7e621a9b7d310806675d32524.nq.gz
    ├── 5fdea1fba42839356ce01d7d182d5122f48e583d.nq.gz
    ├── 605cfd67af388ae6e354ce26ad2730177cff5b45.nq.gz
    ├── 60fb690458c731fc42a880aaa212603327d96f7a.nq.gz
    ├── 61e516fe4684b88d0419d2deefafd9e2eba94f7b.nq.gz
    ├── 62df367095b047d386519f24842e175cab87b61a.nq.gz
    ├── 62f1368a116cb45be6214e65d21ed5e8890a9915.nq.gz
    ├── 640ffe1fe20a8e306499a078f3142c03a34885af.nq.gz
    ├── 6456336478c34510208c030ba232f8791bb0fa54.nq.gz
    ├── 64f80ada903d26299d77634ac22f54cec0a4360a.nq.gz
    ├── 657b2c20bfeab439bfc25c0b09233f41e71fdab3.nq.gz
    └── 663f32e214d4b45fdd2a86ebc97b0fa0f94e6548.nq.gz

7 directories, 200 files
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

[canonical/cloud-init](https://github.com/canonical/cloud-init)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
