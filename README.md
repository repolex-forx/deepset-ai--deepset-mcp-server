# Repolex Knowledge Graph of deepset-ai/deepset-mcp-server

RDF knowledge graph data for [deepset-ai/deepset-mcp-server](https://github.com/deepset-ai/deepset-mcp-server), parsed by [repolex](https://repolex.ai).

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
rlex download deepset-ai/deepset-mcp-server
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── af059c05e8ba9bb2c3ec000cb94b326bfdaecf50
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── af059c05e8ba9bb2c3ec000cb94b326bfdaecf50
│           └── chunk-001.nq.gz
├── blob
│   ├── 00836fb78ccff73f3b91c9aaf0f297cd99a6f550.nq.gz
│   ├── 024ea1335297014a2160de48e6678b3c305f718b.nq.gz
│   ├── 048ef3af0d00361bae699186591af5327201e2a1.nq.gz
│   ├── 0496ae55b1aab2be4106e26b3f37f1966d08c999.nq.gz
│   ├── 06f8fc24184d1cfa1a3ec184a2f04bee6d3939d2.nq.gz
│   ├── 07272478630c186f32bec0c42bfaf7ab8bd99bb3.nq.gz
│   ├── 0784b76ce1f69ef0d7495920e80fb921aded438c.nq.gz
│   ├── 07987b701e6e21526d5598477a40abdc23ea3b81.nq.gz
│   ├── 08717e90ad751d9c1cead0000fd08f34a6f929ce.nq.gz
│   ├── 09cba90fd69fa5a1aa3e0dbb9ad1c6844615d0c0.nq.gz
│   ├── 09dfd90dc7bbadd90bd9b2050d1672fbc073635d.nq.gz
│   ├── 0a0746141cf1d3b8ddd72bbc7a7463e62e5bffa0.nq.gz
│   ├── 0ca685d7d1579a8e605679a8aa877638202623e4.nq.gz
│   ├── 0fc4123493ce6a193a3d4f4197379fbbda01e990.nq.gz
│   ├── 0febf4c5540f5d15290cd3417dd7eec8f77af914.nq.gz
│   ├── 1005eefb638ab72959efbc01e4da9d42fcac408f.nq.gz
│   ├── 10429d780398e85847a94ec0c8c58de6654c5852.nq.gz
│   ├── 14b26e8e83d924b3d84721ec41a54748fdb6211f.nq.gz
│   ├── 14f71a074295e6c90961fb7f21a218082874bea6.nq.gz
│   ├── 183886a3f01a946726f5bd847955e71da7f78fce.nq.gz
│   ├── 18c036db8f1e99cf79ee9afa56797fc5177aa86c.nq.gz
│   ├── 1974c19bc40621801fa4fa88bd427d3c7d5fa588.nq.gz
│   ├── 1b5289ff14c8c17942b6fe08355e215fe7939180.nq.gz
│   ├── 1ccb90ed9605ce13e7d2c867f3a324afe1f409e4.nq.gz
│   ├── 1dffff09f13cbeabe2863b41721b7f517884ca58.nq.gz
│   ├── 1e7ec739543fe6c29c0d67e562021653cf59dbf1.nq.gz
│   ├── 2062685d578c58bca1e49f84b1e431f99809b88c.nq.gz
│   ├── 2281f611297d7000cb4424a96862d558415f3a72.nq.gz
│   ├── 22f5595800ece91cad4d710a1ccf9ccf0e4758b8.nq.gz
│   ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
│   ├── 26fbc3489271de75c192949e714cfb77796510ee.nq.gz
│   ├── 2734c52f4f092adaca8bd04247517b1235be8dd9.nq.gz
│   ├── 2950137bf7d096ec300715497aa8ed9914ff9204.nq.gz
│   ├── 2ace4f4be6db837b84b68a411cc82dc12aac3024.nq.gz
│   ├── 2e2d28ff090b724b6b4b11358f07135e23955a5b.nq.gz
│   ├── 306bfa034696ad70370476370c671d2487721d4c.nq.gz
│   ├── 319c838ef86c5c9d2ae22881ad742b1626b7d3e6.nq.gz
│   ├── 32e837351abbe77385dbb328791e56819f03b521.nq.gz
│   ├── 331de54b6b3b7f3de12fa15937702545fd3578b6.nq.gz
│   ├── 3397862e6dc776fd9e6be27d872dbb585e8cee66.nq.gz
│   ├── 354b30d980ad11a72ba827251338c61768c7d57b.nq.gz
│   ├── 36295b39052d01aa6aca031f8e07cad42aedf5b6.nq.gz
│   ├── 3790676bfe4e2aa50f8104a357e17a8eebb4f4ad.nq.gz
│   ├── 3b1f179051902d5e7ec81f1231516fb6b60a5f13.nq.gz
│   ├── 3be5a299e4256bdf1cbeb51be9f169bc8b8e3000.nq.gz
│   ├── 3d15a198202c81ce814e926b62561ab03cb494d8.nq.gz
│   ├── 3d65f710c1143124481d922829cd5e1eb047085a.nq.gz
│   ├── 3ebd8d65cd7506921143bced68e4ce6be1b89c10.nq.gz
│   ├── 3fd12f1e92ee8318ae2dc99dae290730eb3a802f.nq.gz
│   ├── 40373e6047e0fe6c9f40fb4a7b9280d089901db5.nq.gz
│   ├── 42de0ca115cc784bc0d5551b9e73c2c2e41970d2.nq.gz
│   ├── 44cbde7472266ff2c5e34b95d958fe898c994b86.nq.gz
│   ├── 46432b5d1bfec63e1528a88175040df9f2f45833.nq.gz
│   ├── 466abaee67c336eae4b27c3cdba0aaf416136f7a.nq.gz
│   ├── 497bbc031e09a5a1893d86359b9d649020257fae.nq.gz
│   ├── 4b4679d5d796bbf515d6bdb1b855bdfd6811f13d.nq.gz
│   ├── 4e67f72436d19ccfdf28d723b6fcb9a9fbd2233b.nq.gz
│   ├── 4f7d953dd0b9546e12e201e4c159bde2e24a301a.nq.gz
│   ├── 5355e2442efd0c56a7de5614c807b3bde2436b75.nq.gz
│   ├── 5473ecd6af7af9233bd81879b0c69df48d62b56e.nq.gz
│   ├── 54b309f892371b8341bb458bb618f8c839d51964.nq.gz
│   ├── 56ba4c1567c2aae914afcf0ca3ad11c731a3dd96.nq.gz
│   ├── 5785f6164bb83f26b49673bcb57d33e6e0578ee0.nq.gz
│   ├── 5ae25ca4a4a06fff8b5e6502cd87ebaf5fe6ec96.nq.gz
│   ├── 5bcfe6a39e7f51320c783a35fa8f075261d25c7c.nq.gz
│   ├── 64ea1f75492439cc88e0526df24940d4406717db.nq.gz
│   ├── 66c97ced83d5a9aa8404b84b73bcb6f3ae84ee1e.nq.gz
│   ├── 681de06906e91a868309c85207fb8fdd4f9eb522.nq.gz
│   ├── 6a872b193c41cc69e7bb26d7b6ab9238c5fda8d5.nq.gz
│   ├── 6aa0d81df5f4fd2b9e459f850cfb9b0a6a1ae91c.nq.gz
│   ├── 6b7483ed13689dcb57de61e14d5cacbdd7866878.nq.gz
│   ├── 6c6d8c6aae93ac1563bb66ca311eeab2240a391f.nq.gz
│   ├── 6ddd7073a2b55cdd7e2c8e42b2806f0c5fdc1f8b.nq.gz
│   ├── 7004ed760916c06cbf9540416fb0559a19ac1b54.nq.gz
│   ├── 7156eda027c87bcb004379d4d52cbea0a9138e06.nq.gz
│   ├── 74ce15eca89976b1db39e7da29ab204536790b5c.nq.gz
│   ├── 7655a10ceceb4664c6bba9e216e1e1acc1c36521.nq.gz
│   ├── 76a72591dadb2d39491995bb3d18f9f421f8e64c.nq.gz
│   ├── 7852731ce475c92160d1b8dab974509ae59f323b.nq.gz
│   ├── 79aaba46c5defab5c3505284acdc4bf9a7f4eb75.nq.gz
│   ├── 7a0b8683011e9003d0ae56cf9a90b3c70352eb4b.nq.gz
│   ├── 7a5d2242b3728fb9d8416c50eb40d98d894476ec.nq.gz
│   ├── 7cac5fb23bd752f1ca057ad3e5d7aa4f08bb18d2.nq.gz
│   ├── 80bad1b4f6c2e668d80e0b313df04f5c62e76903.nq.gz
│   ├── 83b9b9e9617e1e99ea4fe1eff11be9390b5cfdcd.nq.gz
│   ├── 83df7abd819c466e3928a134bb2296ea4274c465.nq.gz
│   ├── 844f661061d4a7c4945ec66b79169ddda737652b.nq.gz
│   ├── 849ae38792684b2f81b770c8f3e101c57b4d2094.nq.gz
│   ├── 882ccae33fe07bfd2cb3934765f13d3d66cf47ea.nq.gz
│   ├── 88b5c70a0f818a6a67892ae37b98232eee81eddb.nq.gz
│   ├── 8a2874a4ed8f43375af57e6e62d3851d96940137.nq.gz
│   ├── 8c1693a25ba69633d7a312e8fc02cff801e6cb2f.nq.gz
│   ├── 8c2c48921b1511411490a5ef4497620e71c5d7f0.nq.gz
│   ├── 8ed23b456fcef18f700edec53791c6e9272fc913.nq.gz
│   ├── 8f193ef1e793774265a56c305ceb45efc5210f0d.nq.gz
│   ├── 8fa0e3c6ea639e656b866f9fd98af5ec715c0393.nq.gz
│   ├── 9293f2af3699ca365299050746a4ba448828851e.nq.gz
│   ├── 938ef7c2b7f4d1bd0d78e248d17adcf137cfd193.nq.gz
│   ├── 97ab20fd8861f5168c1e12fc74e70b945534bd79.nq.gz
│   ├── 98eba71cccb34f307e0be40e40e14a90e6e429ab.nq.gz
│   ├── 9990ab2e5f345706ad693cbc36ae54e07bee0b27.nq.gz
│   ├── 9a11b82ddd29c194773f0a2ad4888940d312cf2b.nq.gz
│   ├── 9b270ce0988df5148d1f4c37b8de3042d28133d4.nq.gz
│   ├── 9b3c1722e93ef1b7fc60762b85fc5345e2627e72.nq.gz
│   ├── 9be857074ba61d28a29524157a29b3f0c86d3b45.nq.gz
│   ├── 9c98ec594b0451a7431fd9b60f0e428081e81f3a.nq.gz
│   ├── 9d2dfdd05d699854a482d4037b11d4c43f2862bf.nq.gz
│   ├── 9da8d5a1c66a5f09b6488a5b76e1e6945a80b60d.nq.gz
│   ├── a05a0e8bebc804dad4714e93898e83eac61decf7.nq.gz
│   ├── a2efe7404658555ca75dbbaccc10c395963f46d1.nq.gz
│   ├── a6e6751b5afe9614d0689528cf5700b3bd63fd0e.nq.gz
│   ├── a7af72bbc1c2f4ce9b5f46d6dff73d75455b53e8.nq.gz
│   ├── ab08d511e379325149c4d5b0d391ecbc921ae3fb.nq.gz
│   ├── ab574923048b46627c24811863555d759860bb77.nq.gz
│   ├── ac2ee620df3e6f3e1afe8fb27b41e2ca8d94a02d.nq.gz
│   ├── ae5049a543a6198b633bd91c3b1594d848981f86.nq.gz
│   ├── aeb4d7c8ceacf80cd208300c236d5754935b72c7.nq.gz
│   ├── aeb9473e8587ca03c66800c672f5c3952c16a74d.nq.gz
│   ├── b02f2dd0e1c09e61eb911f2c4be8d91092f13379.nq.gz
│   ├── b28440aacb04c02b085764fa018a1a70ccdea0d0.nq.gz
│   ├── b4945180a6236a51fe21ac5bcae3e58405799252.nq.gz
│   ├── b56841f495b83ac1b12851734968385b3b5c9eb8.nq.gz
│   ├── b804bfb94c1f4db009a3f6a9bcbe4a7ed1e28c79.nq.gz
│   ├── b8e76c206cdb93169af296eaaba551966ed4cd69.nq.gz
│   ├── b92d0ecd669ad86a929d15d3d6d6447b91dc6c0c.nq.gz
│   ├── baa515a9595e7bca8c35178be4217016944a1277.nq.gz
│   ├── bb11bc629be4753033cfe386ba917b4b49ff722e.nq.gz
│   ├── bc7089c1429783c1616d1e3a0518f802c610e424.nq.gz
│   ├── bef1a6c8a602e732becc2809510c62059e5c9b79.nq.gz
│   ├── bfa22559b8abd3888520011ec3f60a90cc73b00f.nq.gz
│   ├── c055c9705c1a8364f89bce0b595b2ab9472ff8ee.nq.gz
│   ├── c093354a8994a25b306e45d0c9f5d42b6a04ea7e.nq.gz
│   ├── c170c9070c3660cb8b1d14a111e6f1024e34ad5a.nq.gz
│   ├── c413a1569e64c6b5c66a31b0330e57d035f7164f.nq.gz
│   ├── c42c1084b965dc1eadbe737b736056c993a21bcd.nq.gz
│   ├── c473745d0acb2498ca76cc67e460424eafe8856d.nq.gz
│   ├── c4c5741db97c12b134ceedf43da3b1b7914ce421.nq.gz
│   ├── c53751ce27edc7db104f40b988f47de1757f0ab2.nq.gz
│   ├── c5730302599ac8fa88d31b215e1f1c3f819c2e77.nq.gz
│   ├── c642876344d5a23b0cf863b473fd2b7bf7bd698b.nq.gz
│   ├── c6c7b9b81091725e9dc5964008f71e1094355e7c.nq.gz
│   ├── cb55e87e8003137a70953dea16025422e41f7048.nq.gz
│   ├── cc36f912de8af2937224d4d94bcc69c3307749c0.nq.gz
│   ├── cd04a4f57261c54d703d099f3adea2e703114a7e.nq.gz
│   ├── ce96ebb0c5f8c4b186987a89afbb55f12f0d8403.nq.gz
│   ├── d0945bfce6d622e904cb42e7202c3e105515c040.nq.gz
│   ├── d0fb8c543044f33c180faf6b21db23e9c5f96f72.nq.gz
│   ├── d135f61f79a88a2364d92f80500f6ac181925d50.nq.gz
│   ├── d391382c6b671468b31089999f4c68cde098a231.nq.gz
│   ├── d4561b3780da3c077eee7ee28da1c2b030222db2.nq.gz
│   ├── d458b1c50adc8826a0b99bc77554cafd79c99f89.nq.gz
│   ├── d461b5d7c47d97143da95cdc7372e54c8d8077b9.nq.gz
│   ├── d57b488a7a779d003de4035fedcfebd695ce08e2.nq.gz
│   ├── d6784892da3b42bb8709655b58c8ae714f766f4c.nq.gz
│   ├── d7374a0084329f52c0f2df5be44855db86725799.nq.gz
│   ├── d76bc3c18f14ff7de357c9ba41bce012b3f9a7c9.nq.gz
│   ├── d9479227a8e2a77b7e7bf0a4d8c24d8d4a6f1b21.nq.gz
│   ├── d9818ccbba68b46ce987bb02ecd0ccafe088742c.nq.gz
│   ├── d9a9882d323521fa57c53997c623ff8a51dc2876.nq.gz
│   ├── da178903f33bf6448f4025eac0f82351366b162e.nq.gz
│   ├── dc6875ea7d411f83855fac59957a720810d22772.nq.gz
│   ├── dc7c351a660b23343a5bee6209404366cef2c5e5.nq.gz
│   ├── dfcfbe96a90d3beef058ad79d163f9e92d720cfa.nq.gz
│   ├── dff73cab7899cbe07688a63d8e2b5b69fc53b117.nq.gz
│   ├── e0b8194b33b3d4072a90b5778a2347c92a2cf69b.nq.gz
│   ├── e1885fb46e690db1f433f1f112782632654531a4.nq.gz
│   ├── e3ef8522f9726dc61d94d99e4b5c0e992d990a7f.nq.gz
│   ├── e58cd8f8ddff5d581bc65015321a99c8d769ef11.nq.gz
│   ├── e60c9a57c8892108dbf4d736fa8693009f074618.nq.gz
│   ├── e611a11b4095c213c981a5a05e785dcd1217568c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6b10129fc63dd4a7d2839bdc2f8c91b295daeb2.nq.gz
│   ├── e94bb741be4a4e837ce42900a3991e5f2c9060ac.nq.gz
│   ├── ea348886b44a29d93eb27634e20527bb6157bfc3.nq.gz
│   ├── eb74f1980c1ed10cac952c36c8de213c70cc494b.nq.gz
│   ├── efef0d6b92484d81ad02c9f249da97c1930baa30.nq.gz
│   ├── f00d605b63aa82cb05a80bbbe65c3b2d961b8ad6.nq.gz
│   ├── f519ed5cf4172c4542e87c6c2462289dc4a4c5a2.nq.gz
│   ├── f5ec75a44d812d813e79afe26a9c33f6e5bd62ca.nq.gz
│   ├── f8051303ecdb8ab6f6c92019190d2772181b2924.nq.gz
│   ├── f8e70934db1d3daa8c8b6eae8abc35b9e8f407e5.nq.gz
│   ├── f9d9b24f268e3941ee3b65982076c454aef685ce.nq.gz
│   ├── fcd43401c50c4dbb8360042e6f8ae1f8684c02ff.nq.gz
│   ├── fd17f5ac22254e30cc157b0aa5f30a3d4a3f16b4.nq.gz
│   ├── feb09b39579edad2a7856378d5cae826d9860945.nq.gz
│   ├── fec901296d284512bc4aca800e0ddab10a9bf8c5.nq.gz
│   └── ffc070de2146fdd905bf61b2e6fec4b05806b807.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── af059c05e8ba9bb2c3ec000cb94b326bfdaecf50.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 195 files
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

[deepset-ai/deepset-mcp-server](https://github.com/deepset-ai/deepset-mcp-server)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
