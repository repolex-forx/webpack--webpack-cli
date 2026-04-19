# Repolex Knowledge Graph of webpack/webpack-cli

RDF knowledge graph data for [webpack/webpack-cli](https://github.com/webpack/webpack-cli), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download webpack/webpack-cli
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a515b76434a5031aada10f660975ea03d2a66218
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── a515b76434a5031aada10f660975ea03d2a66218.nq.gz
│   └── repolex
│       └── a515b76434a5031aada10f660975ea03d2a66218
│           └── chunk-001.nq.gz
└── blob
    ├── 0029ad8473fa413ff875798f0881173138105c83.nq.gz
    ├── 003bcf30c7ea1d81e2e32650822511a71d41283c.nq.gz
    ├── 013ab0a133b8bf72ddd154c5863e4045020d6378.nq.gz
    ├── 01b3bfd47326c107683cde522fb885e774c18ee5.nq.gz
    ├── 01cc27eade889ebed2d9d8f2cd4776f11d9ef576.nq.gz
    ├── 01feb8afb948064d9abc4764601d0d4a3ae3e94d.nq.gz
    ├── 028523bb0d940b102b4b20ad48279c809714ae30.nq.gz
    ├── 029c385cac3ff667e5736ad45c3ec8d85b8738ad.nq.gz
    ├── 02f1f878be7d1fca4e751cd0d6ed73b1e54b69c5.nq.gz
    ├── 032f15de88628ed2d100783ff365b674858b2276.nq.gz
    ├── 042520fc4a4fd540041b4ceaf5f2c6298cab5456.nq.gz
    ├── 0483dbadb45f274776af43a2fa071321c1cfa1d8.nq.gz
    ├── 0568da7e1367fad7027592fec427b2fb4653f8a9.nq.gz
    ├── 061bdc9278592ffc744ec27a9c84f888c9eab6f8.nq.gz
    ├── 06498c156f5faf832b9c0ad70cf8564e614665d2.nq.gz
    ├── 0662abea05ecc0c89b5e6ab93dae0b1f85ada743.nq.gz
    ├── 06bd536ce9edd15a6fddd46286dec66e14f37284.nq.gz
    ├── 071620eafbaa16a791957d34ea6fc891b3dfa96a.nq.gz
    ├── 07d46e38cc0aa91a34bb16d314a92173823469f6.nq.gz
    ├── 07f2099cec02797b4775d94a27299e4e7132ac33.nq.gz
    ├── 08aaaa26cf7d2b67874d00c8b48de9c9bf8bdfbf.nq.gz
    ├── 0919ec3db8f0f5f8f1ff2a933ec48623c8ff7e52.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 0980f54d44293d37823b789e21998a817a63cabe.nq.gz
    ├── 0a41cfe5c6ecc821303632f4426f3bfe9316082e.nq.gz
    ├── 0a42e3093529d105d09a731a1b63290999583296.nq.gz
    ├── 0bdcdf81ba063250f732750dafcf7b2a0cae662f.nq.gz
    ├── 0c4289d629016f4236dffb290561129dd369f3c4.nq.gz
    ├── 0c53dea3259654679ddf5a83a532c1b70e8b76b1.nq.gz
    ├── 0d16e54022b3c23282249d839f3db567199aab2b.nq.gz
    ├── 0d233bacae45cbb8aa4925b9c2cff4c4e14ada31.nq.gz
    ├── 0d66b9de1ac81aa36190f998c84747db786907a2.nq.gz
    ├── 0d920cb4dcf6e08c245e902e43b2390ffd9ef1fb.nq.gz
    ├── 0e3c85e4189fdb7ba31b438d737accd0e7b011d9.nq.gz
    ├── 0e3eab43eb3bb0d86e2228f565266e0874cde67b.nq.gz
    ├── 0e6a5847211474b84cf220bcf884f87aafa7f35e.nq.gz
    ├── 0e7762f97209767dcb2d19543bfd7228d793d23b.nq.gz
    ├── 0e8c35c932f52b72191885ff7b0eb0b9ab9ca64b.nq.gz
    ├── 0f1dc70d1a22a81c8b4acc12e71369b1b2e91e07.nq.gz
    ├── 0fb810f469e083ec2ab393d0bddfcb4165cab77f.nq.gz
    ├── 1047ae56bdc297b781da1a3b07223058446f739f.nq.gz
    ├── 106e6afb8b054206ef43881b978286d03bcce1e8.nq.gz
    ├── 106f5af725f4cd74e5053f289d7105ceb998df51.nq.gz
    ├── 11023920c9ea8cf464aab58168c3461b5c5d718f.nq.gz
    ├── 11079b0f90eb70f7ce528bce29c68a12b53bfcac.nq.gz
    ├── 112d94387a1c9bb3b22c631989be6426cc3e1924.nq.gz
    ├── 11f95cf10fc99af9de400c40d5eb1dfd85dd32d7.nq.gz
    ├── 124aadc5b0423a4aa950245ff8d521f96b2626a6.nq.gz
    ├── 130fd973c0385f6ca4f649effb29d315fbcb23e5.nq.gz
    ├── 133fc6944be37aeea9bebce6614f8141a9424c54.nq.gz
    ├── 13c919daf16f7add2020ccb5b688cff8d8e85a55.nq.gz
    ├── 13d2f962fb047abc2472d82b64732065377c3a53.nq.gz
    ├── 14801125031a13603fd091734be8f7215bff759a.nq.gz
    ├── 14ac10bb082cdfce64b0bc961b17310de9aeba19.nq.gz
    ├── 150418dfc62260fb2668e9f8f084731c99f27c7c.nq.gz
    ├── 151e9d6f0c896364f6ed26944ca1517f84125296.nq.gz
    ├── 1569271cadd50b11ef72615a3b4e4d07c96cda3a.nq.gz
    ├── 1570b2835b6c3f1e59e4f1f4888ec38f49811e49.nq.gz
    ├── 15c0f734c34af7c891a1b3a44df0bcddd76bfef9.nq.gz
    ├── 15e1934891b5d9e4c989846e116afcfccdf43d7b.nq.gz
    ├── 1632a73dd4c2c297ec2386a4094baf96bc56c1dd.nq.gz
    ├── 167d7bee322f73f48b7910981f817a9887ca5946.nq.gz
    ├── 17c51d85f5267e517c7a1b6a1b8aaec97fe55445.nq.gz
    ├── 18e3d927d8fdcb48f60a0d711bac1e698ef54824.nq.gz
    ├── 198fec4135a85c9ce8260192829cc591bb32b94f.nq.gz
    ├── 1b8d983f3bdc3bffb0d824f29b94ef6f59bbd347.nq.gz
    ├── 1bdbdda74c1f8679c98c5c6c0e154a4ab8bd9762.nq.gz
    ├── 1be3161d4b7087bd9d353dca8e814967c0fcd23b.nq.gz
    ├── 1cae8402ad0bd7f6cacbf38554204761a3b89919.nq.gz
    ├── 1cfc9bd23b1118e94674be5c0a76f975fe7b2662.nq.gz
    ├── 1d521a624c9827806d06fea03157ae70a3658e89.nq.gz
    ├── 1d86780adbc9103b3a6b88b2910f54d6eca8fcf7.nq.gz
    ├── 1f23f48394dbfd368f53cd3ad2107b52f75e70d7.nq.gz
    ├── 204550782b437fa100b609fb28220d78451bbb7e.nq.gz
    ├── 20499cef4058e0ffdf58eca781db60c1b3f17140.nq.gz
    ├── 20774ddbe9e3c6aef271b2163b1359797daa5d28.nq.gz
    ├── 20a7806a1649ace956f155f2bce8a307ad202834.nq.gz
    ├── 21ae0aed3ae2985c74b25396a4237abdf8b71836.nq.gz
    ├── 21d29717d940e9f779a36250cda464a262289dee.nq.gz
    ├── 224e2af730db8ce1dbe2fb267cf549db75d63df1.nq.gz
    ├── 22ba3e0ed639aa7cea5468f130fefdeb7077e4b3.nq.gz
    ├── 24ad636a546825457d33638ebf0483bead0a674c.nq.gz
    ├── 2513c3e70c21c0a1ae580728a02ddfb6403406d6.nq.gz
    ├── 251a60f7352536951f7abe68f472eb0ffc199adf.nq.gz
    ├── 251c6f51bf30404db8386f12ef39ee40c4fef19f.nq.gz
    ├── 2531ba2dd3da8afb3ff9c9bcb521e61c7da0de4e.nq.gz
    ├── 2590063db8d53322ec94165624afb0a338ece395.nq.gz
    ├── 259fc8ee21d24bd5227da0f20963964d92929e02.nq.gz
    ├── 26e5cb5929d93ef9c7003af2d87e0130a3c11325.nq.gz
    ├── 270e0f8a94df39eb7b87f8c5858167a13d2d779b.nq.gz
    ├── 2739fba8db4a367bd33a4a6b0ec66896872df3d1.nq.gz
    ├── 278b015b7f7e30063a9686348c1da2bf18feba51.nq.gz
    ├── 278b258163919642278a660a2fbbbd52c5bf67c3.nq.gz
    ├── 279b3e923cc7e90c11d72b3dcb654c0b14998e40.nq.gz
    ├── 281e4cdd2b2045f793b4bbb604627bfd15dc7d9d.nq.gz
    ├── 28605e4b3ba41151927b7e3ac87674f27d6c6b03.nq.gz
    ├── 2955029a9f39a8efba08999737e6f84217cb3366.nq.gz
    ├── 295b1df5e78e3af5413aae46a3fd5c4f52798f78.nq.gz
    ├── 2a17159d94a7bfa3dd22a534d8e46328867b501d.nq.gz
    ├── 2a38661d3c02b561ddef376be059691f3a84ce22.nq.gz
    ├── 2a3baa56d23c71980f3d2895a21eb5b072a6e928.nq.gz
    ├── 2ad8f10589e6ebce5d2bb707b7aa7b7f8bb37334.nq.gz
    ├── 2b5516318ded31f220ce0bdf42168e898cb67bba.nq.gz
    ├── 2ba4d1169b2034256bb7f8646b21ea5ddbe6337c.nq.gz
    ├── 2c49d36640813f5673afcd7abf4168e34661aef6.nq.gz
    ├── 2c794ff0941691a59ba22d7fb59dd1db69c5948a.nq.gz
    ├── 2c99fa4d4b766c1167c107aaa4644313a6a117fb.nq.gz
    ├── 2cd6603170407019f028dd7b61d71423161d7ea7.nq.gz
    ├── 2ddfa5b1c12c2bc1dcd18c9550c828268ed0f897.nq.gz
    ├── 2df1e567e0268e26fbfb9af05d5e1dca7ee06402.nq.gz
    ├── 2e85a918786d0372b6770469ca41bb306f3c1e51.nq.gz
    ├── 2eb604b20627cddb973df3e475c7f0cb98632103.nq.gz
    ├── 2f5a73e568ba3eb49a9086dc293fefd688e60522.nq.gz
    ├── 2f8599051160a330bdd4e8696c41585ed988781f.nq.gz
    ├── 308c4c11be1fe78001000658f79c577864f04eff.nq.gz
    ├── 308cca172502dd559e191470bf046e2e267ed562.nq.gz
    ├── 30d5fa154216cc8f81521116762e077f1e2814c1.nq.gz
    ├── 30fb429bbc17b467b19e497a279e982ea69419e0.nq.gz
    ├── 3121fcb10ad6b886dabf1cf0adb2edc9013c620d.nq.gz
    ├── 31de0e6dd6603de7494a2a3d534f852d717d1654.nq.gz
    ├── 3233a8027bb35e58c306b15bc14be12cb462949b.nq.gz
    ├── 32f35d14cd0daab4b7fd5e96588a5adbec7fa5a3.nq.gz
    ├── 341ece87484ffbec07d2348b900cd56a41efb2a6.nq.gz
    ├── 3451e9b7ed77c5e234c85ef85b155e809842a78f.nq.gz
    ├── 3508558d7849dbdab2efa252d0bd063af365ba2c.nq.gz
    ├── 35c7fe8ecc2a5dcf809c9a74114aeb10afb54af1.nq.gz
    ├── 35efedbbb0dd96f8779cffe9c96597ac03a957f5.nq.gz
    ├── 364ec6bc84b230ddf56f57647adc08ea1540b3bc.nq.gz
    ├── 36a31eed43e02b76d32925bb8f97979ec222b813.nq.gz
    ├── 36c25512e7c0cb7dbf1e0e08c579419df8384ea0.nq.gz
    ├── 37c48e745b2aa93b39b5d2d5767c1121b79683d1.nq.gz
    ├── 385cb2ac035bfa0abc4df43540c4911aea2880dd.nq.gz
    ├── 3880b9e4ce2a23fed22d03d9bddcbe1271223ad8.nq.gz
    ├── 388182d1d9eb33debb3c44a2a72fdea67bcd0dc0.nq.gz
    ├── 38d0ab29eef2d5f8532c91f6d9f25bf0dcf57edc.nq.gz
    ├── 38e922d012b43fc8b5d26dc66216075a66e19f3b.nq.gz
    ├── 39967926fa2ddc9c308f91dbfeb20fac03928f5e.nq.gz
    ├── 39d4aff51972bf1fda5530312176ba5ff17881df.nq.gz
    ├── 39fa8289066ef15616f0fb9ec4ccadfa8bda0bdc.nq.gz
    ├── 3a7539c21bce29fe703be2bc72abdfd16a38a8bf.nq.gz
    ├── 3a7bdd6b788838e0b992b031a3cb4678cbfadbdc.nq.gz
    ├── 3aa5786cc6e5e2e7f89bf5409ed08668154ca1f5.nq.gz
    ├── 3b8ac854d126ebabab5d31c44ec24ec6add4eb79.nq.gz
    ├── 3c1456ce5c9f378ab458230fe85c1b15a41f581e.nq.gz
    ├── 3c14f1d33d72977880c52673ca03bad96555aae6.nq.gz
    ├── 3c16bb63d135808cdb11c0677c2e11ae59280921.nq.gz
    ├── 3c34c1ca3209c090714adb131d5c6d6e801fa67a.nq.gz
    ├── 3ce4e5a7356032410c263b3f971614e5921a107b.nq.gz
    ├── 3d075bd0fe06c5e831fe364b652542e1b987f7f5.nq.gz
    ├── 3d5322e6f081cd72bf506c9c1114980a4463dc96.nq.gz
    ├── 3d5fa7325883ae8cb5373d031c5685efb8cbca59.nq.gz
    ├── 3dfd0a1def05f826e62d7d1bd6fc64fa92e9413f.nq.gz
    ├── 3e94f4d5bcd88669afbea48bd04a1f0d79e9a3cb.nq.gz
    ├── 3e97a576042e90f118996b862b37d5746f822794.nq.gz
    ├── 3ee5d55b0b89908ce6d2a330c40ac42fc25c4c31.nq.gz
    ├── 3f23534a8cd3559794d15c94cdf3e9117d7477f3.nq.gz
    ├── 4051958bb202bdc50f8d2121cd299f6fd2575780.nq.gz
    ├── 405e508e2d7042d77ed47865aa70fab6ecdba4bc.nq.gz
    ├── 40a24444f7ee7c71957b67d542a9d5f2f5712b4d.nq.gz
    ├── 40c46492632e8b7095adf10a4b9d85220f813851.nq.gz
    ├── 41adf2fc9a397aef1223a3e9584a2a4f680033a3.nq.gz
    ├── 4202b6ccc01d00b267d82c7718af78132f6c163f.nq.gz
    ├── 43237a25bed856e6996f42aba89f7d15ad40c6a9.nq.gz
    ├── 43d58cd3dded3b3d4c6db1421d77407df93bfa69.nq.gz
    ├── 43e2888a655cbf7f023c3a0070c6ee0513bf35a0.nq.gz
    ├── 447742e431291b687ad2f47413c6f648ca674315.nq.gz
    ├── 458b8dc3316e87c479aae9fdae1256ec80084dd4.nq.gz
    ├── 45933841849ab6d24806b38cf42c323436bf26dd.nq.gz
    ├── 462320690d9e26f60f498edbe7a132ed507ac603.nq.gz
    ├── 4681fe01cb87dd47a4bbc22c3ccd5f540cc00e94.nq.gz
    ├── 47630dfc2e821055c35ba450f7599989815a7d55.nq.gz
    ├── 4812f07e68b0007a0d1ed914c75dd15c1af39fd6.nq.gz
    ├── 48587933155f1b4ac58e333bebc9ab0ea9dd8595.nq.gz
    ├── 4863dd276dbc9588806b66b5bf6116e62af2151f.nq.gz
    ├── 4864771e5546f1adde3cf541c7c5c610ae177c53.nq.gz
    ├── 488b493e4725a4b631b11ad466da3fd91c81248b.nq.gz
    ├── 489650530ccb211f825202c877fc2492b4b9477c.nq.gz
    ├── 49c66d34d44976159bcb0390577cbeac1d98bac2.nq.gz
    ├── 4a17fa148c693bd92d9e95271e8b935c75eb8154.nq.gz
    ├── 4a3fd9f33823fbebc92d1235c064e4665dbb1b53.nq.gz
    ├── 4a8150f94673f93511d88467adbc529b3f573cf4.nq.gz
    ├── 4ac4c12bd645d37238ff6d0ef48aa51785d5da37.nq.gz
    ├── 4ada05f138f3da3c45f9035d670f999493cf724e.nq.gz
    ├── 4b5e8e433e3beb7a360fc69b058afb3f23a2cb0e.nq.gz
    ├── 4b6d7f38605d5f1e8e7de41f616fd9ef0b423fef.nq.gz
    ├── 4bbb3fc9d09868dbda98892fc7bd60e64e464c56.nq.gz
    ├── 4bedd16bc017a8808af8022d2fd83229d31bc217.nq.gz
    ├── 4ca6d0c1030f16bb77379e260ff3008b7303be03.nq.gz
    ├── 4e2ee40db6cc8b26c4deb2f1254123d09afd0a53.nq.gz
    ├── 4eb2d45c855a365b4ae51eca6e4eda20aacbcaa9.nq.gz
    ├── 4f104918915992a86e22db6b20cf6939199ae7df.nq.gz
    ├── 4f5f4b6a718c5c1651c39ab4d7ef5129d45fb271.nq.gz
    ├── 4f7f5db3d4c29e3c4eb61e5c92aeb8217d1b4571.nq.gz
    ├── 500b88d8caf3a73561c5aca5697359228142fa65.nq.gz
    ├── 5051ea4b9d9690d613f020b35830dab05f3f0920.nq.gz
    ├── 505a46a2c7d6c0986c70bcbd6acd3639100e4444.nq.gz
    └── 5105ea40c01bdb5679d69b2efa55cb5714b238bd.nq.gz

8 directories, 200 files
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

## Source repository

[webpack/webpack-cli](https://github.com/webpack/webpack-cli)

---
*Parsed on 2026-04-19 by [repolex](https://repolex.ai)*
