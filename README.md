# Repolex Knowledge Graph of canonical/subiquity

RDF knowledge graph data for [canonical/subiquity](https://github.com/canonical/subiquity), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/subiquity
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d05694b1cd06873eac8f91e69afbbb4525ae58ac
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d05694b1cd06873eac8f91e69afbbb4525ae58ac
│           └── chunk-001.nq.gz
└── blob
    ├── 002b3470d28f17841d07ce15d36362cd1af83d93.nq.gz
    ├── 01151b86893bfc50a10fea7eacffa18abedc0f83.nq.gz
    ├── 01d9ca2ac973d1452200337c6f83336d064287c6.nq.gz
    ├── 02219300dc949b222dd181c5b638fc35494cfe8e.nq.gz
    ├── 027297e7f6ec5dad0568028024db39b6dbef1824.nq.gz
    ├── 03d0a5af143a748a4c29e6b4c020146231a7e5c1.nq.gz
    ├── 04df4551a00951823161dcc58ef7839a4335db59.nq.gz
    ├── 04ef3c26e5479100e3e627f771738035fff950e4.nq.gz
    ├── 055978c30908169b6bed6f80403e562624d59457.nq.gz
    ├── 05c479cd42a54719276734b8c58aafb30ca07034.nq.gz
    ├── 05ede10287ee7772e6d582e4a0f5f9c9823fd5f5.nq.gz
    ├── 061787f18ae32f6f965be4a6b243618284bf6eae.nq.gz
    ├── 062647d7c9a19880ee7b98366ba3efda0b6c3f18.nq.gz
    ├── 06711ffec91f56c34d0b6cdd9258fdbc15bd63f0.nq.gz
    ├── 07147d636129b3048545ff09371cf03e718cebca.nq.gz
    ├── 07419a13e5525d20f937d5adddc2b07c24df40dd.nq.gz
    ├── 0791ae00f98fd501d5030e14c8d0a1f7a802f1fe.nq.gz
    ├── 07c9d0594786b87d4e6191ea3ccb876e5de9d83c.nq.gz
    ├── 07e0b48cbd1569fbf0e610fa77b6a4e96330574f.nq.gz
    ├── 082105d03583ac5882d598acd1841593e628b37c.nq.gz
    ├── 084e620c256b3526c87a47256e5cc904b5949dc3.nq.gz
    ├── 086b37427f75732f80dc40620c98fc81ee012748.nq.gz
    ├── 08d3b6472fb8f34a3deb1479d74013cbd895d597.nq.gz
    ├── 099376fde1622dc247486a80d7666ab14b110303.nq.gz
    ├── 0bb1aec4ebfd7499a6e47d320d89914b230da429.nq.gz
    ├── 0bd3c910f13d5f29e766159051157a4e1b29a719.nq.gz
    ├── 0c0febe57e7c9b9ec54d04e7e701069d0fb4a611.nq.gz
    ├── 0c43a6322db05a974710ba119e19e456c64fe0c8.nq.gz
    ├── 0c4f8ddb1eec5879964c8cd4039b2b2a5b7ffdf1.nq.gz
    ├── 0cc0b7d42f5ba4001e004a31ca5473e264979ed3.nq.gz
    ├── 0cd0c1de52d7c3725e17fac55f7aa8f7c5b3086e.nq.gz
    ├── 0cf21a7e2d9eef485c30effc2a6107b41b31a3c5.nq.gz
    ├── 0d56469bc82a696b51126475a0a3a1f000376edf.nq.gz
    ├── 0dae1bda9f801cbfc3fdb30ba28da04acb302047.nq.gz
    ├── 0de41d07fbdcbdf9abfd9f090cfb639801c23c36.nq.gz
    ├── 0e044c93661b4b1614baf01631b5e5fd107800b9.nq.gz
    ├── 0e2d4a9bcabb105274323f799c49b85bd969afc2.nq.gz
    ├── 0e6e653fc97424eee5b891a0c4bc29dce183ec73.nq.gz
    ├── 1063d9428778391d7e53087b67ee7577803c59c7.nq.gz
    ├── 107cb8ea2263e4bf40903d385ba3bb9ded39e519.nq.gz
    ├── 12577b331e9b04e03a3189bc19d75b76be49d037.nq.gz
    ├── 14017a1fb495a06bdb190ab47116bc9dfcca58ba.nq.gz
    ├── 14485b0eebd471207c9ef805acf5487a42939c70.nq.gz
    ├── 144ae8bfd75bcfca1c50cc31033172af379f48ba.nq.gz
    ├── 146761ee3602fcb065753dba629d604620fab929.nq.gz
    ├── 14ed62145d4797a26e08c056e212137ff592b4f1.nq.gz
    ├── 15043720b23ce59846ce6d4e3f1143a67edce832.nq.gz
    ├── 152cf92bd8664c62538736b23dc096a1ce774333.nq.gz
    ├── 155b02935de61e002c8c43f6cd7c2388b81a54a7.nq.gz
    ├── 15c863328120d9d6b52b6319470984d6b51d6f20.nq.gz
    ├── 16419a0036c9c77f0786bab67a00edb8754b4ece.nq.gz
    ├── 1688e4102103af4e15106d38d518070781b54e64.nq.gz
    ├── 17911920a69edf8e21431387c239ba6585cb955d.nq.gz
    ├── 192265fc62a8bc42c5cb6f201d2d3205fac370bf.nq.gz
    ├── 1aa30270ecdf45a89dc40cbe3d0065572dc43a8f.nq.gz
    ├── 1b0f8d1acbd81a8658b45f3a2a77133a14bf05bb.nq.gz
    ├── 1b1f92687a73b46d037ded8aebb6ee9c1f4ed400.nq.gz
    ├── 1f9686c815668ca64c80fd54aa4a06095cc8dd76.nq.gz
    ├── 1ff48efa08781c5716a9a480f98491b492596140.nq.gz
    ├── 20ae3091460f23c87d099aef471e682d8b1307d9.nq.gz
    ├── 21589a2bc167ea58c3c50de71885e02d8eaa5941.nq.gz
    ├── 2181dcfd686f8253a944a2a72d51b3708204a439.nq.gz
    ├── 225d3054c91905a2af5f1b3de375fd699f7a1325.nq.gz
    ├── 22d70e3da779e31a045bac015f93e90985d95a60.nq.gz
    ├── 23d3d5bd7ab61e7b7d0f5bf085d709b16caa2676.nq.gz
    ├── 2432ebe30dcc2805f0aa0e77016d47c8a20b01d9.nq.gz
    ├── 24804d84207d26a61f7f7bd243dfe38bb12a0759.nq.gz
    ├── 24941be4a820b45c06674435780a224bf7a2d215.nq.gz
    ├── 249b41d5db29cb10e4051fbd470fa64c599bcc72.nq.gz
    ├── 24ba21ca198de957d6738515b228dee4379385d5.nq.gz
    ├── 25c1e19cb0d7063342a12085cef3fc0646e1c3f7.nq.gz
    ├── 25c5b534846801395b88eaab82147039b34a3cda.nq.gz
    ├── 2669d59f637c3d4f8c8c8b570742b17f162d59e3.nq.gz
    ├── 2686cca5ac6c14dea16d10fd26e20f521e4dde5a.nq.gz
    ├── 27d2dde99beacf8be2b9c4e6f03b99cdc7c1531c.nq.gz
    ├── 2897e74a0cf85e631c56fc3be0d6385f62d81ef5.nq.gz
    ├── 28df390c86f5c9329fca3dfc497148d92dae0481.nq.gz
    ├── 29359fddd35b6267a296ba27279b8d4e70d6453f.nq.gz
    ├── 29cd7563bf6ae96a088c3a9180a5f9cdf3408251.nq.gz
    ├── 2a586a8fd17432a0f820567dca5809e4daeb8c07.nq.gz
    ├── 2b5e159ad83d57600422573f19a62727c0d8d4d3.nq.gz
    ├── 2b8413dd86dc8d1bf51df5b1d66f95f23e05c9dc.nq.gz
    ├── 2d6ff6a9353c0f05e8743b00e4cd874941af5aa2.nq.gz
    ├── 2e383410d3539e4704672dcec6235bd53abaafc9.nq.gz
    ├── 2f18eeeb78e138fad48d91b0e81ec352d828077d.nq.gz
    ├── 2f695b36d5b511998689eda84f69b14bf7b2a3c8.nq.gz
    ├── 306e349d29e60b143f3c649be1edf9b3333a1017.nq.gz
    ├── 30ab976b58a1ee5f58bd41e4be10e47a27fb0f79.nq.gz
    ├── 3115dfd1ee8e66b82c9ee9458583e4ee33ba3d31.nq.gz
    ├── 32ad39be1b2a57117b07e01747e8688033aed01f.nq.gz
    ├── 345e3356fe0acdf130dd9be7fc2217610c0b186a.nq.gz
    ├── 3478bfb85efb1e91a699f3374a84e0ee583e4a58.nq.gz
    ├── 34b0216c7146ecaf878984ffc7a630aa659d7e43.nq.gz
    ├── 353ad1f95f01b4d418a067f9f8fe9c7fc9780e02.nq.gz
    ├── 35570d4f74c997f7511160da27da31e1a6598ce2.nq.gz
    ├── 35e283582126892f854e1707e45e734ed7f0a64f.nq.gz
    ├── 366c94c204268bb32339969f917a7a3422ecae1a.nq.gz
    ├── 367d6ea902ae5e07cacfc6cd2b7647b184b41a36.nq.gz
    ├── 36895e53db48f92635658d0bf53098e5a11d9dcc.nq.gz
    ├── 37d7f495d0ac4da7fe5643f3af7c782729573ee7.nq.gz
    ├── 38895b3eabdafd3cec65089d4bcfc11c28631803.nq.gz
    ├── 392bc5740e7d32bddc26165c836e50e2351341e4.nq.gz
    ├── 3996bd5cbcbc153853ee8d8770c4cff0f893c4bd.nq.gz
    ├── 39b4adf56e3bb2a67669c499fde3e10eb0e5ff3d.nq.gz
    ├── 3a24d9df993a191987ca643a5b26d1e3c8211494.nq.gz
    ├── 3a60a8c46e5ed7daa674296ac3b7e76ed466bb2d.nq.gz
    ├── 3b0665e8a325caecf9e8083d53ac3261a5f46326.nq.gz
    ├── 3c1042cbbdf59ee1aee7b19915d0f8a19ca69b1e.nq.gz
    ├── 3cb583b8aa9cd33fcabb54f980e97ad4282c31a0.nq.gz
    ├── 3d3a63067f6ed31e880c99767ddee3f59a835253.nq.gz
    ├── 3e84936543c42339f97229ec8f53db8178d579c1.nq.gz
    ├── 3fce52f2ad79cef9805c5aad5706638075dd9079.nq.gz
    ├── 3fd39a687081abec3d664ba24f0b14db0d338b4a.nq.gz
    ├── 4021b1410cf02a7765314979ba0c6f9c4a5a5680.nq.gz
    ├── 407c72fc29d2c5ed3cf9fcecb6c170eeed0b4604.nq.gz
    ├── 40ab23c59b728b82c4986f2e0e8e95218450c009.nq.gz
    ├── 41482c783aa2bf1a19fc241154b4ae3d58fb4ca6.nq.gz
    ├── 416c472f0930d9f3051b844c0095ef636eaaaa97.nq.gz
    ├── 41a357b5d1c5de2129b5376c3670d5bcd5c493cc.nq.gz
    ├── 425d2d79ec9f9e0e4233b8b8773249472db17514.nq.gz
    ├── 429b56f7462b4cd30598093f730e25c8748c8bf3.nq.gz
    ├── 42c0f756875668be586d833137c51e826867b5f5.nq.gz
    ├── 44956b1b885c2cda5073bb398ed9bf03971338ab.nq.gz
    ├── 44eaca6e2296c504f92cfa69c79a0e80081188f2.nq.gz
    ├── 45e57ce6b8f105a16df0bc028e42c69450b5b49b.nq.gz
    ├── 45ef8aaaaf79adf7340c22a900d1f0390e7beb93.nq.gz
    ├── 4696974c47f90bdcf6f1932e0861d4ac8d1227e2.nq.gz
    ├── 47375ccb646f2d0f7234b8be0071459e205b6a86.nq.gz
    ├── 47c1c1daf0031e7645a4b2e5570cfa937bc700c4.nq.gz
    ├── 47f798c8df9e88ed191e2a1a3927cca226019b51.nq.gz
    ├── 48baeda8756de6a278472d16d813475d9b91a222.nq.gz
    ├── 491666fdc2d302664f4c777d7e51653f0f750952.nq.gz
    ├── 495eee16be23286423d1b5f8054ee559d77836e6.nq.gz
    ├── 4969063f3a8b40d5e895fe7b327e0f0bb0a00eaf.nq.gz
    ├── 497dd25d5845da7ac3fc532f1b576f150449365f.nq.gz
    ├── 49fb020c6a38cdb1866cdb5262720c9a0d593e67.nq.gz
    ├── 4a75a2ce44039e8a515bc50d1f2d1ebacf02f2e4.nq.gz
    ├── 4aa8d7f23ece2d5167f840ad40581bc16dfa0616.nq.gz
    ├── 4ab008611a8ab6543eec8e14670295695f08adda.nq.gz
    ├── 4b2119d5a4660eab5af5881b81629fbe2a52b282.nq.gz
    ├── 4c5dd12cc4475cddb8697b1bd5638bc27f259ad4.nq.gz
    ├── 4c9ce1f6334bf3714835a933fb1503826d942b1b.nq.gz
    ├── 4e1765950aa2ea1036fb9651cea540f327da9d77.nq.gz
    ├── 4e4a3e2c0060366a4586457cdd0079a0507f15da.nq.gz
    ├── 4e4ee07a0c7d4b3225232f053d635f8b454c6f7e.nq.gz
    ├── 4f6d06ddd00ad9a51354a2252b9dea9fdf12f8f5.nq.gz
    ├── 4f7eafa2e26b5f82dbe837f0f7d1f4caa8b49852.nq.gz
    ├── 5013e00a7e186ccd83e2508eb01a1e3b33835bf0.nq.gz
    ├── 50bd4570b4f0b5edee245b11d3e08a4c244be2ac.nq.gz
    ├── 50d0d569d7276724f617bf23f48b56e218080ab2.nq.gz
    ├── 51ab719983ec8acc93e915a76fc1309ad599a123.nq.gz
    ├── 5202f8a780efb4c4840ae3142ba2d3f311f356d9.nq.gz
    ├── 537a8c26a3fe1a97209542bf49866a9573a8630a.nq.gz
    ├── 53b8f74ec32c3b6679e0c86d9e4cf2406d65adb0.nq.gz
    ├── 53fced9e7932de94a2bd68b59795c0bad991db75.nq.gz
    ├── 544051b14c5c19da68470c8daf0bea2cf8f75168.nq.gz
    ├── 54b525cc0145f0dfde8febc4bdcf92fbf6066e80.nq.gz
    ├── 55705859d6cf2708181539faf2f9fe43605f5637.nq.gz
    ├── 5641e590f3be2ee377583659d8d440767e55f970.nq.gz
    ├── 564718901f780d7319ab6273a5a4915e93b0bec4.nq.gz
    ├── 56c1a60a2e5c1421d90582f33610cb704011fd7c.nq.gz
    ├── 56caf8c06299bd689452bdbb5a0c15fa59b0bef6.nq.gz
    ├── 585f96e63b3c270dcb6d116246ee7ce071bab82c.nq.gz
    ├── 5878a1115bb414bc93cf6444f598d5e6b53355da.nq.gz
    ├── 5962fce1ecb83d16fc7f35076f8307187b116612.nq.gz
    ├── 59f8064cb0a6b8e21e48a77164c210eee5f3d6eb.nq.gz
    ├── 5a410a4e4b5a9788f9d373c6407a2cdd6f4bb1fb.nq.gz
    ├── 5b2d1fd8d3b1318ae589f8e635d4e4755080b472.nq.gz
    ├── 5bc818cf7216c85395bb7ba41206d8447b4612a4.nq.gz
    ├── 5bf5969ffb7157d48a944b06d12e75375f214528.nq.gz
    ├── 5c06bcf0fcc73ce027b33f03e4ce143d706809e1.nq.gz
    ├── 5c9017dab63e448a2e718c4011109c00a64ae40b.nq.gz
    ├── 5d0d070ab5e6f8467e8d1b89cb8cc8cc1bf8c52a.nq.gz
    ├── 5d6198563baa9beba966166a0e24a8d178dd5261.nq.gz
    ├── 5dd701ead322813252f820122c3a6c76c80707c6.nq.gz
    ├── 5e6bd66fb551096ba87858a23993b9575faec435.nq.gz
    ├── 5e9e1397dc7a0a4f902179867a13f726f2065f7c.nq.gz
    ├── 5eecf6764b55249645b2617643a13e023f37d3cd.nq.gz
    ├── 5f45b5bdfe0fe662490fd4fff16ab27b9118c590.nq.gz
    ├── 5fb917d64ed8426a8c52eca5a21bd02cf03d801d.nq.gz
    ├── 60c5cb2292d9efbd26bb33fcdfb18bf506561f51.nq.gz
    ├── 613dcb24ec389c8c669dfc59792bea6148ff2ab3.nq.gz
    ├── 6154d4f4bdffa176255610b877aba3885ad89b27.nq.gz
    ├── 61c6ba1dd630765e2d3d1dcc93531e6b26c4dad1.nq.gz
    ├── 624f70eed0321abd0449efc61d990196b643944c.nq.gz
    ├── 626c1b1e8bd2876d9aa8f410d44f003d1e363a7f.nq.gz
    ├── 628c8993d5c82e9f5ad5f6047dd81f85f417b1ca.nq.gz
    ├── 62c0a8d371ef5989731164ff13e9ad0327e88009.nq.gz
    ├── 633e8b01249348f1a3629ef852a375170de0ee2a.nq.gz
    ├── 634e5d961fd0f9b73163dd68450d5f802f5636eb.nq.gz
    ├── 63bd3963251b053bb576b4af454cf41ea9055c10.nq.gz
    ├── 64300edcfb9c1908f7d93c562ed0fa353a4de51e.nq.gz
    ├── 64d643556555b7f626d286b6623eec080ae6c3ae.nq.gz
    ├── 653d1c16720528ba6b5601a6858a99fa7fac3e1d.nq.gz
    ├── 659bba0ac9891b5c05f3c863f8940efbb373af5f.nq.gz
    ├── 66f2ff1d519813b35687323f0e501209fb4f0099.nq.gz
    ├── 67036276a74565d60f81fb096b3eca2b2ea774b4.nq.gz
    └── 6746a47ab2818f4133aa96bc5e61ba7018611691.nq.gz

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

[canonical/subiquity](https://github.com/canonical/subiquity)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
