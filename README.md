# Repolex Knowledge Graph of google-deepmind/mujoco_warp

RDF knowledge graph data for [google-deepmind/mujoco_warp](https://github.com/google-deepmind/mujoco_warp), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/mujoco_warp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4d1c64bc077d725247e9bf5e2ac3f357749ff804
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4d1c64bc077d725247e9bf5e2ac3f357749ff804
│           └── chunk-001.nq.gz
└── blob
    ├── 00892cca5b3ab422fb802aee49e18b35c2a8e9d6.nq.gz
    ├── 0099abf6cef778d90e002dbb5b3103051dc9aae6.nq.gz
    ├── 009e0f350d80297871b1807f77f87f80ba2a7cb3.nq.gz
    ├── 00c5abf81b40680ce4f8607880030393065964e7.nq.gz
    ├── 03008eddefa7e7cb294f9bfe40867e960c876e79.nq.gz
    ├── 039b35cf9c7b203c7aafc3641a101e53be887fb6.nq.gz
    ├── 04bfc5d9f20a727270cad7011870e579f1c9ec1b.nq.gz
    ├── 05cf56a316535e5581c9a58cf3d4c45e5d7ed105.nq.gz
    ├── 061787d392ce08fd9c0b67a042c0be81c96b79da.nq.gz
    ├── 07551d7b2964013beb3e6735f4928b5b70362768.nq.gz
    ├── 0a38320b0837b183919663fd056e2e0a3d6ece53.nq.gz
    ├── 0a92e94122d6d5651c83ba9c05706071ba369bde.nq.gz
    ├── 0aa56262bd52cd14c46d4c0c7201d0478e15c63f.nq.gz
    ├── 0b4b351cc7c286283622a96d4d40a08d69620b82.nq.gz
    ├── 0b4f51f992d7c4c19e416d7e70447e5bfb0e8fd9.nq.gz
    ├── 0b660f83ed12a117ee973de59a88904f44b094f2.nq.gz
    ├── 0ba0e833b3ccebdc3f8fc8a24d12c4dcf80434f9.nq.gz
    ├── 0d40c3f1bfaf705b832af1ebcf096d7a9d45ab5f.nq.gz
    ├── 0d7eafe8999d53a03e62010a53e6a424ced77f82.nq.gz
    ├── 0e3608f967c31dae330a2189ec85b704efe8f057.nq.gz
    ├── 0f7e666f49641b73ebf502227b48411a722cff92.nq.gz
    ├── 0f801a049158b2d1006eae0e3045effd9a094168.nq.gz
    ├── 0ff51b18be73c83051d9c423743c5cf5a519e1d5.nq.gz
    ├── 10c9fb1d0d2174637ff2b705e6d250261959e725.nq.gz
    ├── 120588cdca96c830bf1ca0a3844f13c819dc84fa.nq.gz
    ├── 13566550c57c48cf6d800b1d8013d218826364cd.nq.gz
    ├── 1463c24ddb3d2f2981412b9424a1ce898e387d55.nq.gz
    ├── 14f5b669a4e84bae5dffdaf6de4c735cb05ad97d.nq.gz
    ├── 151b1227dc0008a6410c7fa81e65ba6ae1a921dd.nq.gz
    ├── 155bd6527d57c3d7d864c6184eb31e4273b4ab97.nq.gz
    ├── 1591519ec515c69fbc0a44087f1b8f3dbf276158.nq.gz
    ├── 15c2090f1290f260301d5f76b309bd935b60d364.nq.gz
    ├── 165391a65f457a928357ee9ff2f3e18d34b4e959.nq.gz
    ├── 16e9d7a63a4aca01cc49af1011270bfea3c2f1f8.nq.gz
    ├── 18079c298a71a1ae9bcad05ffdb41a3f2fabf795.nq.gz
    ├── 180d64e410341958c6bbd2f46fccee7ee24c5f87.nq.gz
    ├── 181474857d98d42a78a86d1fb4f5d1f5ba8745e7.nq.gz
    ├── 18586f5711423f8dd536ed30073b6a697f590d41.nq.gz
    ├── 196aa5c96e3c8a874ba930562cbc71dbbccf6f18.nq.gz
    ├── 198745fd41e27ecbfd4dbbf10e6eea06da9c3be7.nq.gz
    ├── 1a3f9f69a16a7e61769680a8489d155d6f456f67.nq.gz
    ├── 1a530d5f744ab0e5117577e068b4520312e77a8d.nq.gz
    ├── 1c0902727b50c4d42adefab5025a2c7b53472efe.nq.gz
    ├── 1cc82aedd620930b26df4b960c6e33c68f5925f9.nq.gz
    ├── 1d3be64fbae956c4bb936e33754cdca98fdee426.nq.gz
    ├── 1d743e0b14a46c74c51491c72ad49e700dbd11af.nq.gz
    ├── 1dcc0ed757f523ab7b7928764949aaba70bb6263.nq.gz
    ├── 1dff6600f073843aa8e36f77d8caaec79709d2dd.nq.gz
    ├── 1efc62a07a5c5cb8a980d6216bb4d019cb4fe2b4.nq.gz
    ├── 1f417569ed47c3055bb142edf140c7da6fde7949.nq.gz
    ├── 210fb3e3316b1bd17760abacb8fb16922d977381.nq.gz
    ├── 2205df86a546d524d1ead65231eb7abdf4b27f35.nq.gz
    ├── 223b0ccc08b0b1cda0dbf94439c2f0ce2391fd95.nq.gz
    ├── 229a8b733df150bca87cd5853a9521cecf9390dc.nq.gz
    ├── 22b94436f97f5fba9a6e17db54168550e8dea1f0.nq.gz
    ├── 24ab58f77b3f4c18ee33dda0f16b11d5c9d2936a.nq.gz
    ├── 24c86ae9f9c4fced1338a03ebe95755b809b4554.nq.gz
    ├── 25b3cab539504ccf0169c3eb298575a8c2e6ba26.nq.gz
    ├── 25d890016a5f912237d8c52e5b3affb4bf25430c.nq.gz
    ├── 2614daf48b927278461b493a562b7e3bf932b790.nq.gz
    ├── 261b900b4123bcdbede83cd2da70351d141c2762.nq.gz
    ├── 27d179ee8f7eab5c2d44a9da03e41218c395666a.nq.gz
    ├── 27e9f8dedebbb136cb64463fb7e78e8429df0526.nq.gz
    ├── 282cab02dc41d0faaf57e5e22fff0c05654a3c0a.nq.gz
    ├── 288fe9573905640a050f9ee2a3fe4f64edf4c95b.nq.gz
    ├── 28eebd63c91919f9e51195496ed048f2045115df.nq.gz
    ├── 28ffe389311bd964e7997b5795520e48ef55de21.nq.gz
    ├── 2a0fcad550fcbe0024386e55cf952f656b2e7e42.nq.gz
    ├── 2b276bebd6cb7c1edb7a5785dfa307f5b747d392.nq.gz
    ├── 2b592ae52f8a075b2323ffccde9ed77f02a191ea.nq.gz
    ├── 2bc3e38adc110716229bb5be6f0bf1dcd0548e8e.nq.gz
    ├── 2bc8c55f19b2b49eeec3e84a47c003a850be5999.nq.gz
    ├── 2cf987bb234ab8bead9e31f66ebc5ce87f78ca77.nq.gz
    ├── 2d030588fbf05c704e8d339429f663e23af8c037.nq.gz
    ├── 2e41f044464c43e639531b3eb53dedd774b3d706.nq.gz
    ├── 2e532171ec5d337776bb4d8e4c00cce4c6f113ce.nq.gz
    ├── 2ecdfbb00ed278288d152c9b04799fb2c66fe489.nq.gz
    ├── 2f9e93e81cba28159fa78f6bd6295f49ad7bc9dd.nq.gz
    ├── 301a380f5ebc6b50d319181a786f3e4b3d9726f9.nq.gz
    ├── 307a2565ce3015c49723a895c4b9da391ab76e79.nq.gz
    ├── 30c341e251f1c32d292c4f149cd9a00aba6a7214.nq.gz
    ├── 31832d594414e84b2ab18dc401451338a0ee66d8.nq.gz
    ├── 3185b250b1522f3c1512d37612484fcad1dbc65b.nq.gz
    ├── 328abcd0c1fa3a64cfca8146c36ba4ef8bf12462.nq.gz
    ├── 334a351830d1def0d388b8bf2b61385be56df926.nq.gz
    ├── 33b2cc9eef2a6fce39b3807e0555208682c65565.nq.gz
    ├── 3514a7dde60d15edf7f7b9da414f81d6386b1b68.nq.gz
    ├── 353d4426fafee440caca573f862d1764259f0156.nq.gz
    ├── 35ec4a4a70d4f1b3e54b5ada73d0a5e95592a8df.nq.gz
    ├── 35f9da2122d4d4d3a50ca5010354611cab2a8a19.nq.gz
    ├── 37e2cb850446e8f53ff3979965cb2b75d02936a2.nq.gz
    ├── 384bb0ad12ceeab3134759e6b8bc9ee1e7140cd4.nq.gz
    ├── 38a128d7372b3e1feece8dc2fec60ec361d100b1.nq.gz
    ├── 390133cc030af8372d11a295518d98dfd07bc3e7.nq.gz
    ├── 391274a9954d6895debe421f8a16475dc58ed0b4.nq.gz
    ├── 3925047cc0c8352840ea1f011fab40f0532a7ebc.nq.gz
    ├── 3a599d2ecf98fea2f12dcfddd7711aac3a7506b7.nq.gz
    ├── 3ad2e546570fea605a692824a01b9ba79c4569a4.nq.gz
    ├── 3b72b2cfb582dcf69a24451217cbe89f75820730.nq.gz
    ├── 3bf83db9fcfb9f96a8ec677f40c4d612279e7197.nq.gz
    ├── 3c70fa72e20eb56ef04a2c39065885cf839f9f06.nq.gz
    ├── 3ce885e02f49c716fd2e2e0bcd9327b33f9561e8.nq.gz
    ├── 3ead0c9738a392bf75eb2ec5e12129af25e906ee.nq.gz
    ├── 3f7b23e7e898533fc72c343aa969b0ccfa197d59.nq.gz
    ├── 3fa86ea8fd08d333d5c2eeb224a36c49848c7595.nq.gz
    ├── 3fb26753b8df1c740dd064d02daa7f7b9426cc51.nq.gz
    ├── 3fbc270712437fce7d67f274d29e0429ae3cd718.nq.gz
    ├── 402e1fa7f0fbb8ca4041d6934b81f83a43d37baa.nq.gz
    ├── 412971a8a91171e155648bbbe472a648b00bff09.nq.gz
    ├── 4170ed466758af672ff7e0d1ecba57885ac7a113.nq.gz
    ├── 41e4cfc0b74e8619e5286906cfed8c2334ca2431.nq.gz
    ├── 41e9fcf1f2e97d6aa4f620bf1832bc96c02b37c0.nq.gz
    ├── 41f01eafd99351f29c929e1e3b6cee412f9c17f9.nq.gz
    ├── 41fac441d54e457627388f628f2b989c0ba1a9cb.nq.gz
    ├── 4218700fa3e6fae392fa4837243278836cd2087c.nq.gz
    ├── 42b6a164bfa32db6e6796d0e64cd5e73f212abd4.nq.gz
    ├── 42e2c0e7a351575105072a7f4faabe47272087c4.nq.gz
    ├── 43a5af9b00264dbf6a608e6d3868649bd6f3aecd.nq.gz
    ├── 43cce5a35951aff0e94eb5be0857e8a9b8385e2d.nq.gz
    ├── 452842ae0006d3e4abb4d34cde227bdcbf0c3611.nq.gz
    ├── 46bc3070079c6f5e3530666d1dfbd4695cf8f0d3.nq.gz
    ├── 46e9a8f923bd1e9de08f2043f396d15e87df3fcb.nq.gz
    ├── 470611a913869d2fa2541bd01c65dcac5fbc02ed.nq.gz
    ├── 475e6635bcc989f37bb95dd96c7e5b2ac76d3743.nq.gz
    ├── 47a6d5c69817c003edc337f4cbc38664622879d3.nq.gz
    ├── 47ab8398b6f70dfdb0e3d401a49447c6037faa72.nq.gz
    ├── 49138747443cdbb2a3405e21423ddeae99a2ea3c.nq.gz
    ├── 492b6913e2e28659149baf2564ce70b315b23c2f.nq.gz
    ├── 49a4b3da8a3ddd5741c1f6bbede1306ff8e510b0.nq.gz
    ├── 4a5491f9f4a1e26ee2d2ba8304c5d5f34efe4195.nq.gz
    ├── 4aa23db051d13bbb43cbe57601a86f0ce89a5a42.nq.gz
    ├── 4ba97686edab1049d4c15b2cdb6c4c818fc13d49.nq.gz
    ├── 4dcf05cd2abadea8fa16e270b2481df9a34cca96.nq.gz
    ├── 4dd895fc5be4723e81f970e0394aa23b47beddc2.nq.gz
    ├── 4ff6b2a003a4ab195034b5a4128b5f6684521594.nq.gz
    ├── 5091d08b0bccedbf5904423b1477831105e9a09f.nq.gz
    ├── 5091f7056581db45200b2d6d4014baeda14287ec.nq.gz
    ├── 509f87e2084189bd3805324edfb5dadd91bdb224.nq.gz
    ├── 52a20bfaff75cdf97744ae76652da6a9bd089476.nq.gz
    ├── 534eae9ee7babcd51cc391f3070d03f786f47b88.nq.gz
    ├── 53ad6b0b5ac8bcb98ecaff7723c26a131d73071c.nq.gz
    ├── 5444a8bd7aeee6351f8639640ce47938936bbb62.nq.gz
    ├── 5514387317a2a00b1b95cebc930a2e1d948444d2.nq.gz
    ├── 55f09459f66160f49d885ea2d2ccfabc257a9656.nq.gz
    ├── 578f4cb23033d3b7e3c376cff60073e099fee656.nq.gz
    ├── 57c289108668ba3dd4579d502a552acc5f3c1ad6.nq.gz
    ├── 58d71dee9fd17040a81ad1ac222867b2ea4d49e4.nq.gz
    ├── 5a380649a1f58ba430054c36671231734e9ceb2c.nq.gz
    ├── 5b2ad851734aa8e6e259c6834b3ffad8d54d43a5.nq.gz
    ├── 5b931e3e2a25150d830e306acada9700e68aabea.nq.gz
    ├── 5caadbf0d9f54650707c051e948a457ccdaf30f6.nq.gz
    ├── 5cc041e27a7e8dc9bd463028f416e3a452e5a29a.nq.gz
    ├── 5cc8d9001c09f1c2eb1aa3c8fdf9de9ebdf25b9d.nq.gz
    ├── 5e41a2aa50d74684c8bc0c224a0b7aa6c0dba015.nq.gz
    ├── 5e50519a7663d0b3350baa6788a6f1ff5e7265bc.nq.gz
    ├── 5f2aa042105e40d30f26489d28ab3b4572bb7e13.nq.gz
    ├── 60324f14884204689f573d407292e994cb7fabc2.nq.gz
    ├── 60fb2c342b3f918b8be8d2d32137d1a940b9d471.nq.gz
    ├── 627417433aacd4120af74c953cd7a64142ec4055.nq.gz
    ├── 630944877af378f0816781a41f0a8f1020c123aa.nq.gz
    ├── 6422138e3de18d0205d5540c00f8b77656e3c2c7.nq.gz
    ├── 645cf095b0e04d77b6b4858b4374fe5a8cfb53bf.nq.gz
    ├── 6493cc0ff187a7b93658acd67d97ae2854151c33.nq.gz
    ├── 64dc727e10dc9875970e4bef695789a98ffef4a5.nq.gz
    ├── 64ddf7552f5b603a98225f7c0e344e01970dded3.nq.gz
    ├── 661736cf4794e4971de4e204d8ad072d56b1a1a4.nq.gz
    ├── 6632cfb717937a3d00ec4ab1d25496551aa1950e.nq.gz
    ├── 66ee7b37332d2a735c50c424cc5cb2ca8b5ad838.nq.gz
    ├── 674c2b896f5784b4f741a4cbf3ef3e87f7072c4f.nq.gz
    ├── 67f039eae22b0d1448824884d588be8cb36f5fb8.nq.gz
    ├── 683099a46065a59e13c2c38dd635f36242e31fc5.nq.gz
    ├── 68b656f20f609c4f4410842b113c8040ebc59184.nq.gz
    ├── 68c597d94641011328d471f0e98c56dca4e0b2d6.nq.gz
    ├── 68edb4ee26bccabe182e94279b05c459f81bc809.nq.gz
    ├── 68fed6b855a9e18a2535f742c8fbca17f0288d35.nq.gz
    ├── 69d91cf3919cb0c77c61ef0f14bd6b5830ed83d3.nq.gz
    ├── 6a02a2ec0463a52949173794dec33ea91d96f61d.nq.gz
    ├── 6a19d6926821b79d9ed661b6bde68984364cb675.nq.gz
    ├── 6ab99fdaa691a753da55a13e0968c5be04571835.nq.gz
    ├── 6b1a8fac816b91e1c2b24d434abaf67a42febb0f.nq.gz
    ├── 6cb2279035aab425a1a284d679d977585682a7e6.nq.gz
    ├── 6d0080039f7a58119019fdf52767b5aab720f291.nq.gz
    ├── 6d98386d3d29a8d3f642c1f0b4f4b0cb810e8f63.nq.gz
    ├── 6e10676a60b2dac4c5c8d3a8ed8c35e909c126c3.nq.gz
    ├── 703f967e86adb0b588be7caa2219e5d39bd2d0b2.nq.gz
    ├── 705c7eeda9a815df533a89b0f6c933aa8c162a1b.nq.gz
    ├── 706b92094b1bf3eb8874456a03618a6cc72f9dc4.nq.gz
    ├── 710d762328f801dfbbe39794ecd3f22107e6349f.nq.gz
    ├── 711ce79766645fe87050c21af70b00a6e651ed2a.nq.gz
    ├── 71298db31a85297c0ed9c90ecac25ff3bafea6b7.nq.gz
    ├── 716f5a5b0af82b408368603dd72e803a9c977bba.nq.gz
    ├── 71f2e0505083d0759a5c8d07101df96102a1265a.nq.gz
    ├── 724ef2ad447e226bd1fc4db645922d5fe03d6e48.nq.gz
    ├── 737bc0ad9f86abb89877f3272aa767571614ed0f.nq.gz
    ├── 7393ead53c4115c080c94a19ab08e302f17308eb.nq.gz
    ├── 73f9b26782103d59d430941ad9406e008c361223.nq.gz
    ├── 73ff3a73ed4b675d6b95dc2b7f08b0ed08ac3983.nq.gz
    └── 7407010ffedf50ada0153e73a327b39eb99f8f9d.nq.gz

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

[google-deepmind/mujoco_warp](https://github.com/google-deepmind/mujoco_warp)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
