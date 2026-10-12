# Repolex Knowledge Graph of litestar-org/litestar

RDF knowledge graph data for [litestar-org/litestar](https://github.com/litestar-org/litestar), parsed by [repolex](https://repolex.ai).

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
rlex download litestar-org/litestar
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── afd3b039ab5fc588d8f6e3a35d2f9b033b575669
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── afd3b039ab5fc588d8f6e3a35d2f9b033b575669
│           └── chunk-001.nq.gz
└── blob
    ├── 00438b821bba2dca3d673b92890b02b1ef13bd37.nq.gz
    ├── 007a0e786d56dbc9c38cf2233a9876f093ca0de6.nq.gz
    ├── 00b381ac498b1bbdb05847713221aec5255e4ea0.nq.gz
    ├── 01be80e5903839fd310584f826f25aa4fa87cfaa.nq.gz
    ├── 0280914e0cf9411149fa6389f56966baf84156f7.nq.gz
    ├── 028e64dd6194379290867d3ba2b84556abbcbd44.nq.gz
    ├── 02b0bcf992bbe210b0483ac5733ddef8538c5093.nq.gz
    ├── 0303c676d9ea9f9c7d2949029f1669f82450d6dc.nq.gz
    ├── 03909d37eed976873378ea436cf59eae9a8c049b.nq.gz
    ├── 04d7b221e7071fc9af02cdc87fb7ddf6938b760f.nq.gz
    ├── 05a1335bd5eca93c7802af32052ff3a295106331.nq.gz
    ├── 060890fb883e8b7ab312484b9c041bab7222a4d2.nq.gz
    ├── 062478613d07ddfb7ebe48047e6bb32a27783891.nq.gz
    ├── 069b3f792387d9820238ee2107bce89daba41fbe.nq.gz
    ├── 071a91bd229d31aa27d403339f808595e6901764.nq.gz
    ├── 073c5a5416d1161aecf1e7279a36bf38e72dbca7.nq.gz
    ├── 07515cec61b5d37330ca04e41cae5902c8da92e7.nq.gz
    ├── 07f46a3580baa2e0143628e628699f935859814f.nq.gz
    ├── 0818fe53d0555266b7c115b548a5fc3f49074dc9.nq.gz
    ├── 099a4f1af3a29041b2abb8e1b2bb01367f801902.nq.gz
    ├── 0a8dc29c49477f5b5fb9607485fbe0c39438643b.nq.gz
    ├── 0b1122dc55d86167ca29ea71e859002d8c6ffa19.nq.gz
    ├── 0bbc3fef66f72d0504a03e136e8fbffe23e775e0.nq.gz
    ├── 0c8a3aaec7bd2beb98509403e72931d23a01ff33.nq.gz
    ├── 0cab9a1835968839767b97216e94fd38cd921bae.nq.gz
    ├── 0d25bbf06f613af57b77a2ef7e602e0ddbff184f.nq.gz
    ├── 0d4d1b165fef82793b4746c5c08008956f03f129.nq.gz
    ├── 0e665c437ee6553bbb993d883ce14761aad398ad.nq.gz
    ├── 0e807e832f8b52febb7ac4b51449c97a2b637b93.nq.gz
    ├── 0f025623173f38bcd341a2f281bf2645650d4cb9.nq.gz
    ├── 104e9ace7ab8c831b6fc735d0f14f2d1b0222c1e.nq.gz
    ├── 12cdae26ec8aece1662dd1e068b71ddf98074ad5.nq.gz
    ├── 12f7deabb94262a1942296d59d13553697329e77.nq.gz
    ├── 1303d932aa27ce0c98f1df18ce36f050f6355113.nq.gz
    ├── 134fb8c276b7e33930efcc4d9cb47043a170db73.nq.gz
    ├── 13c3aff25c69306c0d70bd167c542eab37060670.nq.gz
    ├── 13f83c0767f006ccdd88b954800bbf19d8eabcce.nq.gz
    ├── 140d014a293af5a8f8ed18f53f609a0e3f015e8f.nq.gz
    ├── 14171e6fe675bac2c93b8e5c7d84189c7c65955b.nq.gz
    ├── 1472994db85d652de8f23a526be8373c554e8253.nq.gz
    ├── 149032a9fb261eb9c847cd06b23b5b902fd24935.nq.gz
    ├── 14e9592c9fc30e3e4c37090702dbaa6897b1ca68.nq.gz
    ├── 14f405362438e8edd6cb29cdcdecdb3b02c65767.nq.gz
    ├── 15a0e961ef6a4f936b89bdd4595981da1a872b7e.nq.gz
    ├── 15ccbd7c7204e6f16e667b5730565e8986c9a7c1.nq.gz
    ├── 169f5f25332d8bf31a0c53e3d8e3edc3bdebb932.nq.gz
    ├── 16b7758b32d446901f3883c7582696d7d69bf47c.nq.gz
    ├── 16d02b09430be2a6ff09a0df34dbb32eed3446fb.nq.gz
    ├── 17005c5eed1910359a38e6eb3b753e190d7f755f.nq.gz
    ├── 175521e00dce07f2ecd659f6b2a198dbd37167fa.nq.gz
    ├── 17ff0b29624565777af32222b7ca725b2ce56e35.nq.gz
    ├── 18cba57401ac26864eafb88bcb34e42760d569cd.nq.gz
    ├── 195491a708c294ee112fcdfe275bd87b81e70b3c.nq.gz
    ├── 19ffb4c2cb0bd1b7f5d14d0565d38bb452a7fa5c.nq.gz
    ├── 1ac4ee0bbabef643f8d549ca7f83a059cd4c6154.nq.gz
    ├── 1b0b92abf00897cd6d80cc1c7d80b7fdce21eb08.nq.gz
    ├── 1b12b1e3992e306621ba12d6504752d37dc6bd95.nq.gz
    ├── 1ca9c174b100bc5e4f3e41618985e8bcc2cc7d4d.nq.gz
    ├── 1cd5bb915d7c91d675986255a827436c552e1a11.nq.gz
    ├── 1cee87969c27f9d86869a601b96118ef81d8b5b4.nq.gz
    ├── 1cfa98de9fa74ec53613bb65dedb1769da71ec2c.nq.gz
    ├── 1d6333ad727fc8c27422412e81b9b1db66ef4e01.nq.gz
    ├── 1f8a834be92aa2aad851198e7e94de89d1b37d81.nq.gz
    ├── 1fab38bc611a92088302974ac7265982f587a5ea.nq.gz
    ├── 200e8e0d4afafe2bf11b53a217dd25c30cda5612.nq.gz
    ├── 209ca901c321740868e46cff3335f0b92947a730.nq.gz
    ├── 20f4939ddf922fc21f26c55604fa98d123225fad.nq.gz
    ├── 2137957e9be0deee14bc5f3abb8a1d8512e39f5b.nq.gz
    ├── 21938c248e2a81febe85ee00e56d8cad3a8af1b4.nq.gz
    ├── 2234d9acbca5ea24a33f46a4465b2c0cfe3fd2f9.nq.gz
    ├── 224d331e31af83d08fb9c30cc10bb0382e0e6cf7.nq.gz
    ├── 2259dc7909b6292edd2e8f20c7ca61626c6b94f8.nq.gz
    ├── 22d0c2cc8d081ba38ca47a5cd247b3f5f67b7249.nq.gz
    ├── 233b75b6fc8bbc86b8e1ff065cc036ff506bfaec.nq.gz
    ├── 236bc40d70e787eb833e086dbe82c450ae308993.nq.gz
    ├── 244174a21b14df764707d666a30201b6dfc08957.nq.gz
    ├── 24741291164f39f475755baf0f34c95db7784bd9.nq.gz
    ├── 24e14abf95af7f25cd269ab4232f0343aaa22eb2.nq.gz
    ├── 253aeca22892b29711f67dae136c91c263a6db8a.nq.gz
    ├── 262a10f9d1808389b5e7855a3f05d3a7ebb146b6.nq.gz
    ├── 283d039b2541a52f4c27061efaa0105158db2ad3.nq.gz
    ├── 288118c2e35d2fa2294538b6d70b1a7b26d50dc9.nq.gz
    ├── 289a4a3619fc6c13c396f51dfd1d8b198e975bdc.nq.gz
    ├── 28d6210637ac6fb95b256342a47924be883fba6a.nq.gz
    ├── 29025b47c40d8ec6e075a0826b9e8790ea145522.nq.gz
    ├── 293d50a610d76f59b34dcb6df81f3d1c1c2c6b9b.nq.gz
    ├── 29bd4343a3068ab18e7519784ef53e7b0d30498f.nq.gz
    ├── 2c6a8f60857ee1733c8a0741b0b92625d641509f.nq.gz
    ├── 2d6c8ef6e83718d7a74fd0d563562f9b3b7a84aa.nq.gz
    ├── 2e7b276cc43d2edca8c23581d1148dbddec68ece.nq.gz
    ├── 2ec98ca5dc00249acc4ee8746caabad9ba5e86b8.nq.gz
    ├── 2fd738597d3cb3bf6d02a573b36fd5df9c8ee7ea.nq.gz
    ├── 2fed9ca2ab016ba99591791764d6d5a123de340e.nq.gz
    ├── 3039a2cc7d26f3787fe7a3d8bf6c799b0ed10d4a.nq.gz
    ├── 317e22c2d84e1e3e0900b2e612e8b74f18459ab4.nq.gz
    ├── 33cc56475ec875a7b70a7ff6e3b8514eabf599d0.nq.gz
    ├── 33df410ccf2f33a1871054075f469471ab717d39.nq.gz
    ├── 33f08ca6ce61f7b10641fac7b885c82a24b81c59.nq.gz
    ├── 346087adf8fbf34776e69748d843e51fd2e888cf.nq.gz
    ├── 34d1b411d52980752c42602761453527cc0ee371.nq.gz
    ├── 3573e48a2597b3fef81eb2e904ad8c564ce1ad2b.nq.gz
    ├── 357b63a1852dedf49c000601cc3f3c982bfd5e67.nq.gz
    ├── 3595edcb91d871e13477c3816cf9cd22bb6b63cd.nq.gz
    ├── 35aa7252cd18d21605ab3a99854c652fddaabe23.nq.gz
    ├── 3620a69ea391d9e91945a51481335a13643155a0.nq.gz
    ├── 364b54992fad13f6912cc05b55b5055c0bc2e459.nq.gz
    ├── 3750f8ff3938504cca7446c4b52cb6bddf2f3a0d.nq.gz
    ├── 37e28c36bb39c82c06189ee06471dd2fb96c03c2.nq.gz
    ├── 38026a371610ba7334e56e1e6445219c14647edd.nq.gz
    ├── 3825fa2ec38e66b53ea4e27cbf6c1ec0d9ccb4e7.nq.gz
    ├── 38341dd762ee932c1c820dd236738ad90c927578.nq.gz
    ├── 38a99a91bc5dc3fb787aa3d62dba0e03fc7acd6e.nq.gz
    ├── 38d2cc9db65a7fc672b2cad8c516acafebc7d941.nq.gz
    ├── 38dfc73eba432e47e0f4e2f1cd0dbc0bc8f84eee.nq.gz
    ├── 38ffe2b4b0e80f7a18379ab1c5c7613a44b7abb6.nq.gz
    ├── 395a2f612d36d7618323588bb1df65002d8e5515.nq.gz
    ├── 3a0ea0bf6072e712635f101e626b16d6f0f13b25.nq.gz
    ├── 3b3a193619a42c44fe40f6a900756f5f311c7e16.nq.gz
    ├── 3b5da99448d5cd879bc35e2bc14e4d0b5c27da46.nq.gz
    ├── 3c292ce0f634e686d429e42daba1c129b02ac8e5.nq.gz
    ├── 3e5456ec3e8b536ee05f37f61b0f078a4548a3f2.nq.gz
    ├── 3e74d4252bd3f1a6e64628b45a7f020154eb0163.nq.gz
    ├── 3e83fb5e0a6b5f983dc4ad91b8896c3a47448ac4.nq.gz
    ├── 403b2a2dea3ff2af64feee6960fc1320a1b56e24.nq.gz
    ├── 406b287e8714592e97d06b64794acd76745e2cc9.nq.gz
    ├── 4084ab7bf5db9c28c8d7dde9778e5f395e08eafc.nq.gz
    ├── 40d90f091fd0cd05bf19f8fee5aaebd97447c808.nq.gz
    ├── 40e61554bc503b763418dc47668cf482f25f6029.nq.gz
    ├── 4195915ca10814ca90c97cc04b5b67f6e62cfb1a.nq.gz
    ├── 41a493f6c86d4e288aa89a4950f1b13c9b700e7b.nq.gz
    ├── 41c6d46fbccd57a6eea32425c7e2190b2b1c9d55.nq.gz
    ├── 427a4e5c7a273f7965fc174390ccf5a516d1b039.nq.gz
    ├── 4320bd2c3f076bfef6cca5bf2a7ac86774273b90.nq.gz
    ├── 46a5b6599400c82877f2acd9ad43de92b01dbf38.nq.gz
    ├── 4741b64160fa7f50d0a35611f733b5690f02cfbf.nq.gz
    ├── 4793bc2394e0b37294a8e0b4fc12ed5e02fc1933.nq.gz
    ├── 48344f8bbbb59faedee5739f623263df3b59e5ab.nq.gz
    ├── 4849ed0db0e23130710238c6594c70af41e11252.nq.gz
    ├── 487ea57f8650d20e1f8865df01e58e85aa9e2e83.nq.gz
    ├── 48d992f1d17799e2b03ee4b17bd7aba2ed865e02.nq.gz
    ├── 498b2b462b83ee987d888c1d1cb0eadbb31dfe44.nq.gz
    ├── 4a2fa1cf70c65fb2088830e72f410412c5006133.nq.gz
    ├── 4af1fc60325028b35dc5ddf359e9a9f9dade073f.nq.gz
    ├── 4b6b7b336017e7134a94477bfe6bfc9931f5b9c3.nq.gz
    ├── 4cad694ded6958bac9239fe8722787f3dc58467b.nq.gz
    ├── 4cb42ad282dc0691f59d96dbdd9e5a27adbd3837.nq.gz
    ├── 4d0f20a0ec0a826818a7706dc6eee1801839a4e4.nq.gz
    ├── 4e715f772911ffcfcc4612bace988c7cb6f6cf50.nq.gz
    ├── 4e7534f9351a0bf0d18faf14d4ffa4e8c1ecf7d9.nq.gz
    ├── 4e8d1296fa7399a0595633552d39677dea189a92.nq.gz
    ├── 4eb07f4f54b5f55e79b2e2c29bc67c7924d3a15e.nq.gz
    ├── 4f9ca010ad5dc05f9313f7e5365cfdbeee3e944d.nq.gz
    ├── 4fd88ded10719e8b3fc6254a97d976d0b3956f5b.nq.gz
    ├── 506df55cf94f24b5d6d62685e8f6ee5c070d7fe6.nq.gz
    ├── 50a2223624c517948af456861d1c484192f72bc8.nq.gz
    ├── 51183e940e2ec1690839b499539ea696603229cc.nq.gz
    ├── 511f146db85b136fd1899df5d182dc37ed7f1ea0.nq.gz
    ├── 5386d946a3283b9eab98f4689f0dbd1ee6246643.nq.gz
    ├── 5497625a0f0463d7145c6f1e8091fea57054bb3d.nq.gz
    ├── 54b55321821df313ad28d05729eed6f75a5daf7e.nq.gz
    ├── 55465fa456a27ba235076c2cda9572dc923879ed.nq.gz
    ├── 566e57518fd815c968e627441c279031da3733a9.nq.gz
    ├── 568a1423f3ae06162750823404db72ddef451c72.nq.gz
    ├── 56efb1180b68d43b5b5fcf19d497f340edede572.nq.gz
    ├── 572b9f837e5943e4d47be91c7bb2bd024e7be423.nq.gz
    ├── 57a245b8e7c22fd0feeadeccfac553208c2e4ec5.nq.gz
    ├── 57b01343c887fb3c83817d77c31203551bc40256.nq.gz
    ├── 57b725072d7f073e6eed105fd6f5933f03d3ec23.nq.gz
    ├── 57c4dcbbd567471cf7f6f0c95b100b5c8df6ad37.nq.gz
    ├── 5a579486826131ce10328f036b983f9caf8f553b.nq.gz
    ├── 5aef94aa066e8920172160c60b901d3dd7947676.nq.gz
    ├── 5b2ec2c745a43888c197af03a94911c04252ed9b.nq.gz
    ├── 5b5093b8058cd1a9797c805b11d13e646c37cf85.nq.gz
    ├── 5b5fd6711c75fe33b1044b46cfd16a52a9a61953.nq.gz
    ├── 5b85c2a5352026d3d8a55ddb9bfd57d6e2f6f1ce.nq.gz
    ├── 5bc9e3248918ed0c5b7693a4c4b752d26aa04b35.nq.gz
    ├── 5c29facc726dc72582a79cd6527cc4727c1c808e.nq.gz
    ├── 5d18dfb5e8275e8a1198545cadc5d191b81286cd.nq.gz
    ├── 5d2b3946d9821da64c640788580cd116033c3095.nq.gz
    ├── 5d3d27bd1ca7b9fced71d4d17ceeee95f8d573d0.nq.gz
    ├── 5d558bb56352e4c14d165ffa89cafb5f5df842b8.nq.gz
    ├── 5ddf6395676ca8e300b00404e10edfcf192e58f0.nq.gz
    ├── 5e4251f206bc9cbe7c602962ce69f3e69ed8c431.nq.gz
    ├── 5e64de253febb789b89bdb35f9217969da491902.nq.gz
    ├── 5e865accc0ee87090dc300cbe3ced72fbdcd1a38.nq.gz
    ├── 5fa654aa3fb43947bb7cbdc881e8b0648ccec0a1.nq.gz
    ├── 60ed61048c14b745c9e22efe2f32ecbaf773a342.nq.gz
    ├── 60f11e0e54b7f0c254776d2daf8978880ea70b0c.nq.gz
    ├── 611f7d9f19ec0598f3f2a0559a29ea3fb639e4d0.nq.gz
    ├── 616ba962f65bba05d9995938a38ff385d8d9d0ec.nq.gz
    ├── 6189cab86e0b0057f76c04d258c04ee1bcdebda5.nq.gz
    ├── 61e42407c0c426dda67425181545040e739a1ead.nq.gz
    ├── 62d2db378979fceb16fb308d41c54130e2686507.nq.gz
    ├── 6357dbeff1e935403deaecdb9931c04b36debbc2.nq.gz
    ├── 638b423514bfb548fd5fdc0f729959ae538fec9b.nq.gz
    ├── 63d44ae4ccc80e22c53cf378a7b6c7f79e6eb99e.nq.gz
    ├── 63e74ccb6050954d60bad4b4ebb0f6c317b7c2e5.nq.gz
    └── 63f4449c17fa86ed2fc03c14f5efe013c66db39d.nq.gz

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

[litestar-org/litestar](https://github.com/litestar-org/litestar)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
