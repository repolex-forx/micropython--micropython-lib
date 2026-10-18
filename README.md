# Repolex Knowledge Graph of micropython/micropython-lib

RDF knowledge graph data for [micropython/micropython-lib](https://github.com/micropython/micropython-lib), parsed by [repolex](https://repolex.ai).

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
rlex download micropython/micropython-lib
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 90028be0829c6e988b5e239b28f39fb91b6b20e2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 90028be0829c6e988b5e239b28f39fb91b6b20e2
│           └── chunk-001.nq.gz
└── blob
    ├── 002bc3726b5baf87bf2daba7d47fcc22934b006c.nq.gz
    ├── 00b271137f2d43fd40cad967644df196557a2aee.nq.gz
    ├── 00da8155ccd73d93a309ec51ae0ee6d5111f1684.nq.gz
    ├── 02a319002f92bd01d0adc9740e580cfde5fa471a.nq.gz
    ├── 033022711f538c9ba7df4f0dcb716fbd233b3240.nq.gz
    ├── 03ede9f0a43f6cb9e4dfe215ef57fe3d3117c7b2.nq.gz
    ├── 03f8b2df1a4e26dab0050364f446be18f60d3880.nq.gz
    ├── 04afc12e5e1da508f1900ac13434460b0406b0fd.nq.gz
    ├── 04e4763e40ed2a13a6718e1b129a4d7a618c6b5f.nq.gz
    ├── 0577229e2ccead78ad2551a3f0ba2fd57972b3a6.nq.gz
    ├── 05d69f7740189648104f56dd7a5a878990875cba.nq.gz
    ├── 05fd4863edc62a8589ed2465ecdcdebe1ed56afe.nq.gz
    ├── 0647201bd3f33f2653f521eba34105ee85d9c26c.nq.gz
    ├── 066a05fb96085a9cf4d7adf109641a77f9a02e36.nq.gz
    ├── 074e8ae6daf57a655d841bb73a5eeb82b4650aef.nq.gz
    ├── 075d3403dd23d22c8f9b492cece8961e02a3ea82.nq.gz
    ├── 082069cd4fb713a3e7c1a9c3fef51553bcd7df9c.nq.gz
    ├── 0840359f82f90ca9f8a4383e19fc41f61301619b.nq.gz
    ├── 087d6fb51b817bc1a1be566324d507f1a806966f.nq.gz
    ├── 090d69eebd19efc2f87326e6ec9ef874091f33d2.nq.gz
    ├── 098920b9e628276dde9febc52f6227f264aac3e3.nq.gz
    ├── 09dfd03b98bf3e2bd101b8768c9c40c58bbf03b6.nq.gz
    ├── 0a6476064c32bcabc92ea2279e3fb9dc04d5f8d5.nq.gz
    ├── 0a6fefc970469b32c5624ca0aa50285c56a1c5e7.nq.gz
    ├── 0aec4d21e9314131a37e1e00f354f217fed52bba.nq.gz
    ├── 0aef3214315349b25317383336e707a6a545618e.nq.gz
    ├── 0b527ec27bcb93bfedda72e1d82895f6df03b9b1.nq.gz
    ├── 0bb19899ca278e18b6dcdc5beecae6597a92ee84.nq.gz
    ├── 0be7e85c216987e111f5cb10cef9950e5ab3759e.nq.gz
    ├── 0c42bc19b367380e7cfbd668f2b50c8a5ca53dce.nq.gz
    ├── 0ce56d1fa3c0e9ab7682b4790b0d4bb00627f2a7.nq.gz
    ├── 0ddfc31d392b18b7141da6578223433e00fb82bb.nq.gz
    ├── 0e828e226d1c8fb87aa1d55dff683d408bb1a207.nq.gz
    ├── 0e9e41d3523e77fbeca72515af6ffa29af5f0238.nq.gz
    ├── 0f0ad65baedfd01c7214d667f0e5590eb117c7db.nq.gz
    ├── 110e3c7cf8b41c1f55d8f572ee389be86d2b1a2b.nq.gz
    ├── 11c28f47956370565b5719277bef8b3a64de79ac.nq.gz
    ├── 1222f9d618138f0906dc7c98f2113bcda75a2d37.nq.gz
    ├── 12bfb1ff5db6723e0c7c53c2ab1271e4babcbc82.nq.gz
    ├── 13a8b3791f5ad84b84ba8aed0cd1627c2860fa07.nq.gz
    ├── 13c903d31c6c495930f7bd455de974e3d7412256.nq.gz
    ├── 1401e5f5ef6d02c0c53f0a74de11b5b4458db25f.nq.gz
    ├── 15ef8aa12113d73e07fab5eacb10ec08beca3705.nq.gz
    ├── 15f7fffa7ab4d2caca9f47c4f2b2d353ec228ce9.nq.gz
    ├── 163175d824c28ea0e5eb9f86219e7209fa871ca1.nq.gz
    ├── 163cbe23dcb9f19dbd4bf71e7d717d01efaa2cfc.nq.gz
    ├── 163f558c826a31a9dd83226015f1ec84199a726f.nq.gz
    ├── 168ff8e622bfa9f2178cdd840b8c504caeb219ed.nq.gz
    ├── 16d661b0c0195a3f7615047db08cde0bae9c488c.nq.gz
    ├── 16e5f76e655e42695853e326bd636ad1d8e9b756.nq.gz
    ├── 177877091a23d06259acae9610ace9474906dfb8.nq.gz
    ├── 178294c9669b8dc57043c0d20b8902cec4dff0f4.nq.gz
    ├── 1936a50e451c41b2b0253410a9b8f0c8fa7572e8.nq.gz
    ├── 19afe623ce3a50b415a916f476388160518ea52d.nq.gz
    ├── 1af12fba834fcb703b46776116c3e144e45e1b43.nq.gz
    ├── 1beb996188353508674d328a1239e55745d3e630.nq.gz
    ├── 1cb31b53896b52e1e636f47d55749a1d49f6c38d.nq.gz
    ├── 1d55cbd8fc26f2b4c252cb85e935bb8e71e0670e.nq.gz
    ├── 1d5da2293ad4b847fd13d7c472109a738abaa9d1.nq.gz
    ├── 1d71a3180ad6a4b16f8bc9e6e5ba2e294546506d.nq.gz
    ├── 1d84f025a8decabd0c1165437625a97aec29de9a.nq.gz
    ├── 1deefdf0e52a3facb821b348123b316aa05ee7fb.nq.gz
    ├── 1e4a940c3511e9230cc758352895d622603b614a.nq.gz
    ├── 1ec75378ceb742468c0a30a848ad1e793a9c9fde.nq.gz
    ├── 20527db4ff3a49cfdcbaee1f3b786f75579fd733.nq.gz
    ├── 21b905c155f1ca242c29628caef8040d986b62f2.nq.gz
    ├── 2256cd4f5b83de0a48ecb39c0738d8d485acc15b.nq.gz
    ├── 227a1ae5c6b1f2f696024174f16da7936a52a61c.nq.gz
    ├── 22982fe9ac7dc284924584ea699b758c863f59f1.nq.gz
    ├── 2374489c68b9c08fd5070fa7568966abcc91bc6a.nq.gz
    ├── 24da54c2d27950cbf889c118aa7c064764b11e53.nq.gz
    ├── 25264ff15a5c992645e69c3270d3db1794fe6de0.nq.gz
    ├── 25701034e44a32f3b9df02f0ed18533ec1d54ced.nq.gz
    ├── 2589343d46efddc82a869e01c6f52e1b33755527.nq.gz
    ├── 25c05d05f1b96d0d50a3daf451c31c803b2c10f7.nq.gz
    ├── 262f1c227f427597d9b61a2e01b0f36ec156ea0f.nq.gz
    ├── 263aa314a4c77ef78964ed89ddabceb406cf3b72.nq.gz
    ├── 270ef018a1430e3c1e780b1ec919bfb0360a3eb6.nq.gz
    ├── 282f3e5e371021f9702438aebbab374c36206c93.nq.gz
    ├── 288625dfecad2f589facf465abeb8ba85c5a4c94.nq.gz
    ├── 28a05483ef3bb9974823573f688c62458a605c2d.nq.gz
    ├── 28c2c7c2d1e499c965a6576cb12de7a4a3fab6d4.nq.gz
    ├── 28fc53536b0e6bff5e918829d735e72bf1565909.nq.gz
    ├── 296d87b43057a65e0c5d478541879ef7f06a762a.nq.gz
    ├── 29732c939fb3ef20f111a60d1c923dea8b085917.nq.gz
    ├── 299f8247d8d8eb57e9ed0f4660a68c87173c1727.nq.gz
    ├── 29d01cca77439eda212ec9504ef168b297df95cf.nq.gz
    ├── 2a07c531912b04784136b586e408eb43cab73d5b.nq.gz
    ├── 2a53b9402491e085c5759f51da02f10c3847a017.nq.gz
    ├── 2ab4231db01b6dbad1e041fa8e121fc418596f5f.nq.gz
    ├── 2adf366e3be7ab1653082beb2ccf35bae6a63f55.nq.gz
    ├── 2bef38fddb1256a88f12857c909915e21a571470.nq.gz
    ├── 2c70304a0b7894995c3d4d4487e920ccca2af491.nq.gz
    ├── 2c73ed272c7438e3461cf9e72a1ee5f854d7c036.nq.gz
    ├── 2d2fab31c1838eef8a15dcbeaedc58d63f3cab20.nq.gz
    ├── 2d36a9ab44395419a830010a57f2eef1ad6144b1.nq.gz
    ├── 2d89bfe9dc1b486488630a457f1b0c861154e51f.nq.gz
    ├── 2e3af32d66bd81a44977805137e50486bbd3456f.nq.gz
    ├── 2f6d4a9287211860f549a7f434a51486fe8b6899.nq.gz
    ├── 30a2c25316a410a33544ba77c739e9ea03a422ca.nq.gz
    ├── 30fa9ab770bdf65611957b22f81968c5e949cbef.nq.gz
    ├── 313649f36a9d19f3883a8b1f2f2bc32e14fa895a.nq.gz
    ├── 31650040b2ed6e7fec9ef6ce6d01323d71c3caa4.nq.gz
    ├── 319228dc8f9ac292195201e53eaab9df9975c619.nq.gz
    ├── 31c34ba91f6a185c741fe3d6761d75bc94b5c911.nq.gz
    ├── 32084a56b40163f89badabaef83ff8173dcf43ee.nq.gz
    ├── 322201b24baed08c529d824c4746eff138ddaa63.nq.gz
    ├── 324150e2751b2cf5bc84d76d5b198620ac81b1cd.nq.gz
    ├── 32e2b57d679e7e67d4e9cdf8ab710c0a2d728f7d.nq.gz
    ├── 32fb7cc7b3455b5dc3773279ec64d66fa85873e0.nq.gz
    ├── 332df8de76bbba59067064f1af9e06347cdccfab.nq.gz
    ├── 34a96344e74a28711c0eed13ba5772067f249555.nq.gz
    ├── 34b1fd262486880cb18865cc86139e023d6e68dc.nq.gz
    ├── 35a47d86c0d544bfd862e9d3d658e44e8ba3f4b7.nq.gz
    ├── 366af008beebb0017d51c561a7f3b5b72325601e.nq.gz
    ├── 36dfc1c41e6b40f58a86b968b8f49fcdea5af133.nq.gz
    ├── 37ad682de94a11687c6afdac8cdc4dc88eb2b46c.nq.gz
    ├── 381daeb64ae9500a25edb40a5465e818cfa62962.nq.gz
    ├── 38c32cc7b02a1e8ea2720552c7ee90be19a8220c.nq.gz
    ├── 397b7ceb641dfb09cfd46016d87a11d86c803e3f.nq.gz
    ├── 3a9543bc2c3515669f474991f0485bf43250fee0.nq.gz
    ├── 3ba07a22b3773efc676001fa6ec54eaafd1900be.nq.gz
    ├── 3c00eacff6406a1f13398b4e56941e1d5369a16a.nq.gz
    ├── 3c89226456801e8269ff59325f3ea2e2d35bb71b.nq.gz
    ├── 3d2982779c922ea8c0b6461516acccd570d961d5.nq.gz
    ├── 3df2248de0bc886379e0a6e4c28ee0c30b9fdd15.nq.gz
    ├── 3df24490063ed8d1f32d31954dfeb51410cd4eea.nq.gz
    ├── 3e05bca185dac35f82b8e48bf48baafb964e3fb0.nq.gz
    ├── 3f29bbceb4c997de4d633f537f31d6b6150bb385.nq.gz
    ├── 3f3ed6150fef88cea52f51a312a72cc7ceff8d1a.nq.gz
    ├── 3fb29cc04a552dd21fe31ecf2317e9d0786bf68b.nq.gz
    ├── 3fbe61c252b529d4d6598309d73199588d050d22.nq.gz
    ├── 403c51ea19b5fa52898ddedbaaf5b3d38fd0c0bc.nq.gz
    ├── 40b87d45bb353d58b3eb656adb9ab9573d10040a.nq.gz
    ├── 40eff7ed2b2fc2caacd221664be498989e8b75ae.nq.gz
    ├── 412373a33bbb1358ec18ed3166d34e74e7988df0.nq.gz
    ├── 41fc55bcf0ad6407fa8e296772b0df9c9d60031a.nq.gz
    ├── 42a859e1d51554c3bb94b0423a773ae7e505a02c.nq.gz
    ├── 435fa92240b8f6e781f962165106dc21a5f285a8.nq.gz
    ├── 43fc1522b797279cb5499abb3ced56c4bc245bc0.nq.gz
    ├── 442cf2121f6fe5b08be1db543ed3dc2daf701629.nq.gz
    ├── 4433e6a4deac5a508c2250a85bfcbb7d91da16ce.nq.gz
    ├── 44e8656a695763914c292b99d0def75a82edaefa.nq.gz
    ├── 44ed4797b39cbee89b94986793e2873cf51e082d.nq.gz
    ├── 4500c5e513d0ef655c22c7c86d8002a53546bf68.nq.gz
    ├── 4533fe204a3c6939fda498d63305115dac963f7a.nq.gz
    ├── 4535d780e9abe398967d270d929b134702dae878.nq.gz
    ├── 467fbd1fef232d6509352969472f7d27df8e5096.nq.gz
    ├── 46fec1e0c90423a102109978aab7385e8da60593.nq.gz
    ├── 477bbce4ea5df8468324ea50f087a5c401f41f57.nq.gz
    ├── 4a51cff7807275b4d0b13e084319bc9ea409d9fa.nq.gz
    ├── 4af4a784824c06d35b5dbb0d50dd308bc4306386.nq.gz
    ├── 4b7d220a00c9fa823dfdf7ae4765037c898173a8.nq.gz
    ├── 4c14d6f11c965c4fda4cf695f18892a3df7f1dbe.nq.gz
    ├── 4c6da741c74cea7448ab9579625b42ab5d9028f5.nq.gz
    ├── 4c76f6f7d53b0efad1fc8f3dfee4d55143118092.nq.gz
    ├── 4cebd43453ab192c438c56d6eef51b629b786670.nq.gz
    ├── 4e7339c76d167c6dbf143d006a168a68363f5b16.nq.gz
    ├── 4f202ed6315d04a1df3dc3f549c956cc3a3323b7.nq.gz
    ├── 4f6dc71814b29829527001e0069998777b41cf61.nq.gz
    ├── 5064e5d88c3b669ec6e1fca2afa59fba81d4cc94.nq.gz
    ├── 515f865c38bfb8b0ac132db9adb89febfd50a143.nq.gz
    ├── 527b3317be712b1139e85c49a648d2517e6b0548.nq.gz
    ├── 5286cbed5f8460cb630fa0c6865ca26ff6d1d4f8.nq.gz
    ├── 52a2afa96b62003e95a319d5acd0ee352beedce3.nq.gz
    ├── 53b34f06dcacdb3fa2b2ab09c569b44c372ea501.nq.gz
    ├── 540c85f87278e442a94b1cf69d3acc966e0a4716.nq.gz
    ├── 540d1b3de1c87e5512156758398f2ce1f76dfc37.nq.gz
    ├── 549043567dbfcf50dd36e4eaf1f6c6a29d1bb76c.nq.gz
    ├── 550d68cd36949eab5d4266ee76fbd6ad6cdef771.nq.gz
    ├── 551bf715254a550dca7a0c52e088b324a3320520.nq.gz
    ├── 55a3199e02b87beeb1e5fac9578e84fca6535f87.nq.gz
    ├── 55fe8af69fe15fcc6117e41a491da9232c77b8ac.nq.gz
    ├── 5610f41e2696ead47a0b1d8da5326add605b7215.nq.gz
    ├── 5647763131b4bbe0b2dfd88708b3e618209e13a1.nq.gz
    ├── 571b42a340b8b831570186f050aa6f1fcf305dde.nq.gz
    ├── 5773f71fc69512dd9f020547d0671d07662fa563.nq.gz
    ├── 585ae2cb42f8533cadf4ebc8b3618c8b13f8e7e2.nq.gz
    ├── 586c47c082c7cbca59e64765a84b2a986c2bcb35.nq.gz
    ├── 5917840cb99706ee32238fd55ede5787a12200a2.nq.gz
    ├── 5a2ff307d4be505090dc108b2bad7c864904b605.nq.gz
    ├── 5b04d71d3870572f7b31f7b718a918e67505d4d3.nq.gz
    ├── 5b97869acb725b3b85def060c8b7649411c8cd86.nq.gz
    ├── 5be268d402188914961a49e386844dbd6f794ae6.nq.gz
    ├── 5c6404d6f94866dc4a71c492334035ba821bb17c.nq.gz
    ├── 5c7857531339f0b05f624d2d0d93de3393188539.nq.gz
    ├── 5ce5e14bc199c6d38633eadffa37750db1091668.nq.gz
    ├── 5cfd52260b55005ee32b850bad42c09e66b9ce6a.nq.gz
    ├── 5d5d7399b39591c3bb1c895a971b5a6886f1a268.nq.gz
    ├── 5ddf305b33717c5a5143437c01dcf71b70adf78e.nq.gz
    ├── 5e02ae6b1c8cb7febbb96c9e1913b3c3300398b4.nq.gz
    ├── 5e503509e316492a4e91eea8add7f8b4c3026dac.nq.gz
    ├── 5e5f13b278c4f31c87507f2e71ec2da56569d8ec.nq.gz
    ├── 5f1bfb6cc780c543e623809d644fa53cf8a1567b.nq.gz
    ├── 5f4c21a2956d12e82af811b02ee723736f0afe89.nq.gz
    ├── 61345276b53e2e41a9858c4b9b863b18426d7365.nq.gz
    ├── 61b13c24d2bf2ceb3e6351f7c0234190308e5002.nq.gz
    └── 62c0a5147dad327600b87ea27ef4c31658cc3a2c.nq.gz

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

[micropython/micropython-lib](https://github.com/micropython/micropython-lib)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
