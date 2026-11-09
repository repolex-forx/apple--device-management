# Repolex Knowledge Graph of apple/device-management

RDF knowledge graph data for [apple/device-management](https://github.com/apple/device-management), parsed by [repolex](https://repolex.ai).

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
rlex download apple/device-management
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9e7fdbe23990b2551c4b29b39bc8b0de956805eb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9e7fdbe23990b2551c4b29b39bc8b0de956805eb
│           └── chunk-001.nq.gz
└── blob
    ├── 006625949f3a1b00297e84f5e8b08e3f41476252.nq.gz
    ├── 02347d57a1f64c8e4979f656063ba952139656ac.nq.gz
    ├── 02b4b8d09c41d3b081f684f848332c9db937ded4.nq.gz
    ├── 02f88b80afc095a21c1374d04e27b4248eed64ea.nq.gz
    ├── 034fd3006eb804e53b36862ae28f7e6127341f3d.nq.gz
    ├── 050e11f2a60a02b56dc984e4bf59b7bd07c837a3.nq.gz
    ├── 05a3d1f256c0a2a80692f6da69da3e38d2ea9fbb.nq.gz
    ├── 069f288f22818cc158b3fa7aaef4fc47ddcb3028.nq.gz
    ├── 06bdc299ab3a7261d2237afb84f211d8abc51155.nq.gz
    ├── 07cb41ce3499ed1b8c08b6b666db5feb58197e49.nq.gz
    ├── 083fb25fd565301f30709787c42176bad607c1af.nq.gz
    ├── 088579f77784071b51c0641d9b563a6a71c1f525.nq.gz
    ├── 0995d066c4a0f90ab40c97d48e63e32bc538e8f6.nq.gz
    ├── 099a7049aefc7fc8accdb5f5f8eba874c9b9b3f3.nq.gz
    ├── 09b6bf02189d29fd3403d2c8992f20b2fb68a46a.nq.gz
    ├── 09dba550b8c707c042dd912604d3764e4c540b55.nq.gz
    ├── 0a0f9fe6c9889fb8fba038269409a8ee5df9fa37.nq.gz
    ├── 0a3e40e1885f8664e6cbc96120400d23e3361baa.nq.gz
    ├── 0a626f0390a6f193ff6dcdd7a0c812b34a83322a.nq.gz
    ├── 0a9a8418fcfb5a87dc7041dcc886a8e908cee9cc.nq.gz
    ├── 0ac68eb6a6f79ced35c58f4e587eb9cb95997438.nq.gz
    ├── 0b61942d928082f4e42cc5e5f0125e4b2de080fe.nq.gz
    ├── 0ca8835f9d084ce3cfa3df6c8be87c1b33f858c8.nq.gz
    ├── 0cd141fc1ebc0096b00fd9c38ef8cefe738541ce.nq.gz
    ├── 0d6e77ee036341da027bc37652bd60d1ec2fdb1b.nq.gz
    ├── 0dc0f7d0a7ed8b5646007643e9306d2ab6f255d6.nq.gz
    ├── 0e43cb994db2235792101ce6a1fd68d41249104f.nq.gz
    ├── 0e98052b79ca240053eebdf9473356e990ca3611.nq.gz
    ├── 0f0c50548a6c4f4ffa6f6dabc23c1b42f3873f23.nq.gz
    ├── 0f6991f8f363069fc763482b2298217ce1b61973.nq.gz
    ├── 0f9d6534c1ea7b8b4e06c958e27588e15de15490.nq.gz
    ├── 108da866f061ce330dcbb0389696bd9e35e27a3c.nq.gz
    ├── 10d690ee04fc980ba6988cef8eeb2f0a80c8bcbb.nq.gz
    ├── 10ea7a4670329ca87bd4d9d59077720ac3a09617.nq.gz
    ├── 10ec7e30f41ce3acc953a789ae45722a1a63d963.nq.gz
    ├── 1258377ba70c65d5868f49246f9fd131efec89d9.nq.gz
    ├── 12757efc421e1d7a6d0f474627dde4537560ff71.nq.gz
    ├── 129e46b3d897dcedfc02d59e422a4d6176c8f7de.nq.gz
    ├── 12b0ad778f248de9fa38d4570eacd803806a512f.nq.gz
    ├── 12c23434dabf697afb41a450192e8b240f3d6fc6.nq.gz
    ├── 12c2bda851919354e4d01896c5fb336733162546.nq.gz
    ├── 12e266e0016329ee39572bf2a13e7cde324232ff.nq.gz
    ├── 141837bb06e5730a9dacd501f03553e13153db52.nq.gz
    ├── 149d24abd9e6429544081ee7e3fd1ed69279adb4.nq.gz
    ├── 14ed638548a8fef0f972bd366e4ec8038bc61018.nq.gz
    ├── 16e98c8fc6796a4a0a47ad77e8f98dd89310a963.nq.gz
    ├── 170cf8c8131439332760b189f8a6bb31b59a6d67.nq.gz
    ├── 17865339e1d6536372c6b182dbd917f71e4c1104.nq.gz
    ├── 17896f59885aace98f44b25d51af6c8e4452c94f.nq.gz
    ├── 17b9cf445f10627e7dad37faab22fa45b903b21b.nq.gz
    ├── 1873972a3693ae85e79687e761a2499229fcbefe.nq.gz
    ├── 188ee9e59a9b2121fd6ed71139f8bb549c5689c8.nq.gz
    ├── 18bf45a40e62039ff64f670b8dcd7aa8fe176bd5.nq.gz
    ├── 1972b912cbd8052c10690b5d850b466f1a25ba5b.nq.gz
    ├── 197a3aa35364171a9be766411f6831105fdf6ff2.nq.gz
    ├── 19999c5fa09a080be9e7bd47834f9692f8db048c.nq.gz
    ├── 1a7019c6fbec679d05d8ccb60c2ae10c03a5f46a.nq.gz
    ├── 1b287919c047a3902387ce0e58587b92328b0038.nq.gz
    ├── 1b4ff6981b90932e9a58bf102f6d0624d66a460a.nq.gz
    ├── 1c53b0dafa7bcd40d0e529fbdd7877e8ff4a9438.nq.gz
    ├── 1c842c9a069a9fe0b666043015cead2dfd397119.nq.gz
    ├── 1d00e0b991cf62c6a93cc4f43df064b40433b536.nq.gz
    ├── 1d97d71b27d15a11801828240752d3dc210230b8.nq.gz
    ├── 1ed329538859f3413e1ff860bf443d168538376f.nq.gz
    ├── 1eeab51257e771e5f4ac6f79041efb9ea37e2f4b.nq.gz
    ├── 1f33324d5eac98b05cfdf1df3423964cb48a8092.nq.gz
    ├── 1f7b3eba4dd33e48684bda73d0638f119d1953a6.nq.gz
    ├── 206f14e9a4a8d14db52c7154e209ce6818584115.nq.gz
    ├── 20e91f26dae7f8c78642dbbbe6e1af34d9f311d0.nq.gz
    ├── 21059078e4e85e29ca6658f4f12ca0d458724832.nq.gz
    ├── 216610afcadeb2084d34479913ca167c05137754.nq.gz
    ├── 21706c07d909704c5afdf948a24363557420a02f.nq.gz
    ├── 21842cd4c04ce0ee922c0fd13bd85e609b87e702.nq.gz
    ├── 22f97c2c8f28a7757bbf891c7ef101f0df6e5dbe.nq.gz
    ├── 2380bdf2c2486325057944b57b2ec7dfb514a224.nq.gz
    ├── 238ccf265dd643c05f8b24e2776315a27b7a8bc2.nq.gz
    ├── 2422cd40e3e1587c69f92157d3188a1c5eedbf61.nq.gz
    ├── 24baa3666bab4846dee87a523ab670efce053c2e.nq.gz
    ├── 24d806ca3c13274ccac9b8c78cc5acce4d0caba4.nq.gz
    ├── 258cf21130bda780d49112eee04be1268b749ced.nq.gz
    ├── 258f9a9949eb29bc73222c732948da2c1c844933.nq.gz
    ├── 2771972f53af53e412e659134850a4ac0564c617.nq.gz
    ├── 286b6dfe7283427e78ae4d31362c22c4be70c127.nq.gz
    ├── 28d297fb8cb7a2ab2498361c6d527e931750345b.nq.gz
    ├── 29c4eb82cf4f6e019625fc17082c5bb53dbece31.nq.gz
    ├── 29ef902531817dc780caf1b8c61902dadc8b4e40.nq.gz
    ├── 2a26021ec42b23bfaaa2efdffd54e06b71906fbc.nq.gz
    ├── 2a4a2fc4dc9dca102d2958168e4b99ee49321675.nq.gz
    ├── 2a63b1cc3c6518c592077e45f32bf00929d39d32.nq.gz
    ├── 2a917fb7e04e783e70d08d1f9872333c411d3ba0.nq.gz
    ├── 2aaf8a1b9cfcdcfa404aeb3ebb1c705ac14f8f40.nq.gz
    ├── 2abc95849e22a93f9398f313cc5d0f2cd043892e.nq.gz
    ├── 2ac74155da507c39fcb1ef18a2d9c13473384767.nq.gz
    ├── 2adae8e76a98548d4d9ad2ea1bed338882322a19.nq.gz
    ├── 2b7e8a13360c68c3a6a5e8b6289013d9a023603e.nq.gz
    ├── 2cf94defb2d3ad4bd0593a64cafef6c98d7d76d0.nq.gz
    ├── 2db24cb8b1dd7ce350d8b146ade0dee6ea0483db.nq.gz
    ├── 2fafe0a277070c2ce28a7c868cfbff1be03c29ea.nq.gz
    ├── 30f0565cfd3b9d9ddedcbc9640fbd07c0265347c.nq.gz
    ├── 3146f604a8e5185c33b8d3dd8245dae963819d47.nq.gz
    ├── 3185725e8e994c9fe9768e0fd626e15f7a2accae.nq.gz
    ├── 323ce0c5e26b6fd3f626d73e9f817f333d4c0f35.nq.gz
    ├── 32cd77fab9df21d928d2bc5ebf0a32c79060e905.nq.gz
    ├── 33f73ece836370b96ebb1a28aa083498e71dd3c3.nq.gz
    ├── 3470164268b5ff9a0a105aa13fe9363fe8c7c705.nq.gz
    ├── 35de742f7a390bf62c7c20f31873c0542e35e237.nq.gz
    ├── 35f562232a03e10fcf823dffd8334aea7d0fa03e.nq.gz
    ├── 36944631e5f6eb252762d3aa6a4df9bd91a25ddb.nq.gz
    ├── 36fd5255c6d70748068747101d43613367113408.nq.gz
    ├── 37eb9065858673833d8a76b623c1bd1ac14be2eb.nq.gz
    ├── 38716425188e4c81ae086004094f71cfdecfbbaf.nq.gz
    ├── 3af791dd9a5d7b9273f658893cd490d5b63c8677.nq.gz
    ├── 3bcad90afaa1fce58df56911c23f46c44200eac2.nq.gz
    ├── 3bdc209894f5be860666ad2179f083408f81f9a1.nq.gz
    ├── 3c242fce0754e48add234f31b69c628c0efdd803.nq.gz
    ├── 3c3b15a6728e600ac9e344972c52d82810a5413a.nq.gz
    ├── 3c75a72dd354407e5a4a3370490bb3cd9fb67d5a.nq.gz
    ├── 3c773648dc4902c9d915f0868153410d007b46b8.nq.gz
    ├── 3d4903e2a55f5018c014a848ee018ec10f7c2b4c.nq.gz
    ├── 3d73e9ad73cc59c788c90f7c0d296baedd1b2646.nq.gz
    ├── 3dbb14407c5e716c2a955f03d15ab7b72677c5ed.nq.gz
    ├── 3e34ac9506813ce46edfa551bb4ba26523be48d0.nq.gz
    ├── 3f3d07a3f07b69bf522b1b074f57f031c248a5de.nq.gz
    ├── 3f79f7ea60fe9517293d683fcc3d6397a8a7d52a.nq.gz
    ├── 3fb0b4fb146d66e60b85ef594b732bb434bf46e8.nq.gz
    ├── 41b276f35c19923543e4c02920be4dfcb10f648d.nq.gz
    ├── 41c6d0bdff0cb6a1f7976844384f22512f8d0bfe.nq.gz
    ├── 4371259a5547ed014f73214a439420651eb3f1b3.nq.gz
    ├── 4384da61effbd8300548197fc72196a537dc55aa.nq.gz
    ├── 44a92241446a74482f341bb596605cb7077fc1a5.nq.gz
    ├── 44af71ef684a0ff441c169dbcc736d2a0805704b.nq.gz
    ├── 467bf3f2d9ad789ad482fe1fc195b43cd5887915.nq.gz
    ├── 46983f9a830e6f595b9af7ba7447454d93562dea.nq.gz
    ├── 46f3aeb59abf5b9e7a9d2655a648689c5f84cf5b.nq.gz
    ├── 470deedbdc9b9b03f914a2dee601bc96955c247f.nq.gz
    ├── 47568250cf0759a203e0b775299f60738606d84e.nq.gz
    ├── 48789d0166964d061ba61bfa013fcec7c0c73311.nq.gz
    ├── 48813216072aa8abd83bbcbb84fb7ab787f46c72.nq.gz
    ├── 48e97e41a22b2ec9da14d07774900ae01099d1e5.nq.gz
    ├── 48fc4c7dd77944bb138149d5ef0915888c907ced.nq.gz
    ├── 498bc09ba42a06ad6096c1c7375eae776797b376.nq.gz
    ├── 4a253fb69db40437f82fbb34e4e6ed7ec1492231.nq.gz
    ├── 4a763380b43a8f12931c7d28e0054766585d90e5.nq.gz
    ├── 4a78f4a8e53411809b851289692ad1b2103ef208.nq.gz
    ├── 4ad24b5417058ca96ab14195da86001939433c45.nq.gz
    ├── 4aeaa58642639e0ab4580971f243db68b3d856f1.nq.gz
    ├── 4af54112befb75ef4b710c54e105ac9f88b5ba2b.nq.gz
    ├── 4b7c8572d44f19355ff7210c979652e664fdc84f.nq.gz
    ├── 4cfc09ccd1fd3b3d773eca14bc018b05ee79af7a.nq.gz
    ├── 4d742ac2163df105d67407a90cf8cd4e8fffbde2.nq.gz
    ├── 4e728930a77bb4852462c234045c95598ba60ea7.nq.gz
    ├── 4ebbf5da8d1efa386da0476aa2726edc26b46718.nq.gz
    ├── 4f40c32b1fdbe7031d5fe96c7fd32f48fe0de9b3.nq.gz
    ├── 4f470ab6c419c3fbc96b605e2ac819472c784d8d.nq.gz
    ├── 4f56824f7ad122bee954b4ab5370ac3755ce08df.nq.gz
    ├── 4fc2fe476fddf6b9616e385159ea7f31dbc3aeba.nq.gz
    ├── 503673a9282244800064c1b6bba8814e0c811fac.nq.gz
    ├── 5052f84ddc012fad82bdebe9f8b28769940cdeb6.nq.gz
    ├── 512fb4ecc6be9d7fabb02de0adb4939a51087b31.nq.gz
    ├── 51683623ba4b24f13d6b556560b266a631291f6a.nq.gz
    ├── 5240c31b2f231b4b76a2e2f6339a1cb3b1a83cb3.nq.gz
    ├── 52a4c428294e38f322c8d1a28f09886192de85ef.nq.gz
    ├── 530ca711c9fc2e25492b1ac067730ad8d0727f19.nq.gz
    ├── 537be7c92bd5ce6945e3ee2a5b7f5430f09df7fa.nq.gz
    ├── 53cd409ce13c3d5ea656f85f69ba197d47259bbc.nq.gz
    ├── 5559da6d9fe972b31302547fd785abc6e6d412a7.nq.gz
    ├── 5580162dbd9771ed196f1ff7a89e7f5b731a656f.nq.gz
    ├── 5633135546299074d497ce34bb6d3c5efb27eea8.nq.gz
    ├── 569d123419cc79d063a79603a973877f78e7be1f.nq.gz
    ├── 58098ffb346f36159a4b6042986381ecc93cfc39.nq.gz
    ├── 5896494eea9cb6c631196a31eff31923b8b74037.nq.gz
    ├── 5957affe90d3a61e4ae4b390eeb1e9e17d8f0abb.nq.gz
    ├── 5a51b3d7efb089c6b70f2b0a372f47aed54fe39d.nq.gz
    ├── 5a6186a4439e8066d396f815a3ec3eeee8acc830.nq.gz
    ├── 5a907a767e3bb4a020b5f3a8ea6374c1f2fc819c.nq.gz
    ├── 5af7a63e2519bc2a58628022244caee63acff397.nq.gz
    ├── 5b3466c957e28f3e77b6c15b4a774168ba887cd8.nq.gz
    ├── 5b7c8d44fd3c0d2a7aedea7cc2064d7e57ca1fc5.nq.gz
    ├── 5ba06bdfaae9b9a50b8fdeeef5d273135d1e4a6a.nq.gz
    ├── 5c1ea71408dbc6e40b93e7a59d430c20b1c5642e.nq.gz
    ├── 5c64df6a94156b5f1f11fdbfc0dac059a7a6470b.nq.gz
    ├── 5c705c667b6c8eb1596983e9943bab95baec742b.nq.gz
    ├── 5eb70addc3b577c32dc1885399483d3d54802961.nq.gz
    ├── 5f3c6b2a6add525e573e0ffca59c657743da5b90.nq.gz
    ├── 5f61fd8912dc64a892467fb8994f606abb97d113.nq.gz
    ├── 5fbae8d8013b42f3a7400e5cf433df8e3accd46b.nq.gz
    ├── 6053cf2e6f8834474e0003ca55675cca1bd466e8.nq.gz
    ├── 60a67b608cf82c605362d33b58cf4a7f45d07da9.nq.gz
    ├── 61157c975a4932a536009a081f20174a178224c4.nq.gz
    ├── 611580c460bc528a2762fd64c2ff612c508436bd.nq.gz
    ├── 616a3a31022e38642c76210e7f02735703d39efe.nq.gz
    ├── 61d778d05beeb0721eede7dfabb00f9b5ecb3a9e.nq.gz
    ├── 628266d7ec30af19a5ca898fb4fcf6a7ca2f5eec.nq.gz
    ├── 631e409edb50a12d5035663c386aaea49770e99a.nq.gz
    ├── 632bdf5a629f51760db0b749ccd0caf1189e00fb.nq.gz
    ├── 633c1eb0d98fcae6cbe07714bff4a5b0966af514.nq.gz
    ├── 6352948c2ea6699257b68e3548bd828b37601ebe.nq.gz
    └── 64075f2b7291855f3792a4b17acac9e065c7d921.nq.gz

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

[apple/device-management](https://github.com/apple/device-management)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
