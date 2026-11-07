# Repolex Knowledge Graph of allenai/olmoearth_projects

RDF knowledge graph data for [allenai/olmoearth_projects](https://github.com/allenai/olmoearth_projects), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/olmoearth_projects
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a628d1a5fa7586402451d169d0ef73680486e209
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a628d1a5fa7586402451d169d0ef73680486e209
│           └── chunk-001.nq.gz
├── blob
│   ├── 01cd44c4e4d5b48529ebfdb378f9acdc66cf88de.nq.gz
│   ├── 02910ade70e75691143ff98896cbef106a64908a.nq.gz
│   ├── 03760c3d2667d5628e9412999b7f8b01ff75d438.nq.gz
│   ├── 0400c8786786d60646f3d60e3eb27fdad1dd9044.nq.gz
│   ├── 0536f87c60aad4db793d4632519669c66ace44b3.nq.gz
│   ├── 0705d481c546ffe5aa39f8434d5466af8bb40592.nq.gz
│   ├── 0708c5a0e2ff78624b417fc46008a2485a2b2c13.nq.gz
│   ├── 07b9846f7c3e08478877b76981901f4fc97fd3ba.nq.gz
│   ├── 096b965847c9022cbc2f3264b4e5ecc9fe6034d8.nq.gz
│   ├── 0a6ccd6b9143c97647bc987ac3872b9b4b7a5c7b.nq.gz
│   ├── 0b461de2ffb1ae06fb78a2042671363baa1d957d.nq.gz
│   ├── 0ba193f295b52ee4e01124482a702a145e4c6a47.nq.gz
│   ├── 129f22107325d83021ea3e666e335ecfd369b5e7.nq.gz
│   ├── 13701ab1eff613ae184302bc0630a05628075b8f.nq.gz
│   ├── 177da2b554379063a5b833e4a04c9e82126084b6.nq.gz
│   ├── 1902811549c8e09d3ae425f9999a3fbdc25d5392.nq.gz
│   ├── 1ad8ebd5df46c231480fd8ef2a61547c98473e2b.nq.gz
│   ├── 1d8c16f41980facd310700efd2c04a00c386bdb3.nq.gz
│   ├── 1dc0dc8c01cf7dbc5035b0493859cbf7ef88ba15.nq.gz
│   ├── 1df766deba21275377d8aaf429fae674462a859c.nq.gz
│   ├── 1e62be7265d6d4888ca7513ed755a900017e9c5a.nq.gz
│   ├── 1ff00aab36bc57f25d7d7d9ad1acd4c2092215d3.nq.gz
│   ├── 206c17a970e8086742b29efa7cb2826730988fc0.nq.gz
│   ├── 2151a7e1c96fb827ac126fa924f1724c438725ca.nq.gz
│   ├── 21cdab443be94cd0ebc18a0aa8add0f4c05daf46.nq.gz
│   ├── 22be3d4193f37cdf63d2b10eb996f6846861e6f2.nq.gz
│   ├── 245610082195be75d6011ac3abce12efa1021dda.nq.gz
│   ├── 25ac8217a8cc9e9a4c5f721a2f884d248911a606.nq.gz
│   ├── 2904a43bf68259b0dde46a41bcc2bb1596a029e3.nq.gz
│   ├── 2a0285f1509629b48bd60e8d7079274b0235329c.nq.gz
│   ├── 2b26db0730f0e23149eed9d3cd5413b5590c4368.nq.gz
│   ├── 2f61453154dcfa41436f017927b49f8ba8d142c9.nq.gz
│   ├── 2fe4005d00564dd3a558c25ba34f72a1bb8f18eb.nq.gz
│   ├── 3338b182d7ab67fe4d011c24731f9bbc45463ebd.nq.gz
│   ├── 33ed49a24c7474971041e3cd7144344350a8bdf7.nq.gz
│   ├── 35fbe387ca751f86ef1421dfdf18a52bc98937b2.nq.gz
│   ├── 36c2c5d12ab7604a78fa27d9d5d8872bac3d8ed4.nq.gz
│   ├── 37fffc8aed7f37674f32f1e60bae5c36799025bf.nq.gz
│   ├── 3894fad38587f23e0a8ed509b4fe69f4cc880051.nq.gz
│   ├── 395ce6c2b4514656cd20741b09aad3a8cc2da6cb.nq.gz
│   ├── 3e40574755ffeca085b56850fd692cdc99c04af2.nq.gz
│   ├── 3f0f2ead868a426b8bc346c40f9f19b26551733b.nq.gz
│   ├── 3f6bc819b944da55768248cf22ec85ab80eadc4f.nq.gz
│   ├── 3fd99262c5fadfcf3283fccc523ec7679484ae9c.nq.gz
│   ├── 4226d392537b97afca5c269c35621169ba73d552.nq.gz
│   ├── 441516628d7a4b05d9db344f035e046b78715f84.nq.gz
│   ├── 4ab513adeb7864920f1d7b53f1043bd4f42d9e9e.nq.gz
│   ├── 4bf23c89655a9833786eb2ccfbef5cafa611b805.nq.gz
│   ├── 5077631e27d76ff4338db9f9f4cb8d17a22e6c7d.nq.gz
│   ├── 5301b75cd713f87cc2de8bfd5ac82775a6342c79.nq.gz
│   ├── 5658767134178f526ab8a248b44816e6f5ef76c4.nq.gz
│   ├── 599018a0be195ac15f0f0052047148ac4bde925e.nq.gz
│   ├── 5c0eb9b2838311b6cc91c066a8e9456c6083e855.nq.gz
│   ├── 5c46aa0e560d65444bf15360536859295d096513.nq.gz
│   ├── 5c6ec785b3c597ff38b30893101abaa5b74dd6da.nq.gz
│   ├── 5cb1158e64bf2e1ef364a6c121f404c29257c0cc.nq.gz
│   ├── 5d3169c197aa32b5bfaec6747cf7809bd776ed6f.nq.gz
│   ├── 5fa2593630f072d3126f25303bd8d83c971f9431.nq.gz
│   ├── 60d4106cd7544ea4481ac7a2ea515b09296b8f6b.nq.gz
│   ├── 61ee3f37fff928d4756b4a1696bae163a0ea0ef9.nq.gz
│   ├── 63828b5333488a08efe57431495b682f728cf96b.nq.gz
│   ├── 67a9f071b7685c6bde9d40c09faa74ea66b9f7cf.nq.gz
│   ├── 6922ed03ec1706064fdab147e2867baf52fbc889.nq.gz
│   ├── 6ae52972b20ebb9a8655da9d8c9748fd9e5f7309.nq.gz
│   ├── 6b7096180cbbaa6e90ab4ecdc3e3aa20dbc25f84.nq.gz
│   ├── 6b78abed72099f287547f29c04a833993658e2bb.nq.gz
│   ├── 6ba0e6caccc23c8883c726ba65fd85a4337d99ee.nq.gz
│   ├── 6c77a29c1761d63c3c6e85ef06584603cc9c76f0.nq.gz
│   ├── 6dc3ead8a311565af368dff0b87afa618bf2a861.nq.gz
│   ├── 6e6019005dbf8433e19ff21120ea56a9799b9fa3.nq.gz
│   ├── 6f544a01f023398954b364ba175db59735ea7b53.nq.gz
│   ├── 700b15f8f5f7ff46ad7bf44711c8d99eb082ba02.nq.gz
│   ├── 718db1b04c3dfab1c6365da415f7cc1468e95611.nq.gz
│   ├── 71ad75dcc45f7c429966a6bbb50cb497a36921f2.nq.gz
│   ├── 71fb3ad0bf8cce985869b2d514ebff566de4e568.nq.gz
│   ├── 7457cb35cf87e363e9f9fd2185035e6226060e14.nq.gz
│   ├── 754ddba8d77aac886510a6074394c28e8f806fed.nq.gz
│   ├── 783ce7227d0a714b7bdf5515004c242de06b1bff.nq.gz
│   ├── 786cdef571fd9b730e96693c2857486f33d51e98.nq.gz
│   ├── 7b436fbd4597a59652739db7911d02959aef1774.nq.gz
│   ├── 7b4b22da0eb8c8466e90cf7b70de1f28b26d254d.nq.gz
│   ├── 7b88a535f113e96f6fee52ee6a7cea822a37d9f1.nq.gz
│   ├── 7ba461a2153b82cf66e33a456adfd079f188f852.nq.gz
│   ├── 7c60bd1c4f422aae6119899932d59badb7d22186.nq.gz
│   ├── 7c6ba4f451eeb3e4b8777bb995c5077da0dcd0f2.nq.gz
│   ├── 7dbb3919dfc06e16088f709b25a3a6532a3fbecb.nq.gz
│   ├── 7dcd5beee8b0d5cadde1d9273319960ed77f0e5d.nq.gz
│   ├── 7eb3fdef40485b7201c01c1fb3411bba542a22ad.nq.gz
│   ├── 7f07308c73b3ec120c46ff554a0dc984582c3236.nq.gz
│   ├── 7f55ac22c55a930b789bbe3c366cb7a6431a48b0.nq.gz
│   ├── 7fade8bf2ad4076706760e35ca96540fed4f70d1.nq.gz
│   ├── 80168c0e13933497de497185a7b1ca6813f5fd29.nq.gz
│   ├── 8049b7ba476db616987ad050490f73d734c43bd7.nq.gz
│   ├── 80621728d8e05b89c9c318a0a254ad27ad675033.nq.gz
│   ├── 8109310ffbb6be387d4960155221f6f19338e595.nq.gz
│   ├── 813178b69dd52f4d89444292e20d27da2f9b92fb.nq.gz
│   ├── 81c72f19d0c6a0709ee16e9cf3b3cc6fbf517644.nq.gz
│   ├── 81d870415e662fa319f655cd14eccdf62640eb29.nq.gz
│   ├── 821424a9a3da5addc29c29508fcbaea1c65cf9fa.nq.gz
│   ├── 843db5a2d32227179672d59f8e5cf690857f2d7b.nq.gz
│   ├── 847e403effae81c0f6722e3617c62ff26b682256.nq.gz
│   ├── 858f5a32b7b5e153b753fdf965740c98f9d2ae32.nq.gz
│   ├── 86933c30e07cec815e1c53cc6862509bfed72dc8.nq.gz
│   ├── 8b8b9f8d810300c26e0aed63760e735c9d684219.nq.gz
│   ├── 8c46b7e765068fd689fba5fe99705a89f2464744.nq.gz
│   ├── 8ec1eca27214113e200fc178cbecf23d423870d7.nq.gz
│   ├── 8fdedfe42421078e7dbc67a619595168916f8cea.nq.gz
│   ├── 901a4086cae11164b21deaac414823f17c483a5a.nq.gz
│   ├── 91a569bab510499764543c32552eed85a32fb878.nq.gz
│   ├── 91b1cf7e8734c80dc3c7e34d95995bfaebf5a69b.nq.gz
│   ├── 91e15b74865814d297565ccb51e9bd1dbca6f769.nq.gz
│   ├── 935796ec1cb46d8155302831a3689989372c0d6f.nq.gz
│   ├── 95a2d0ddb2fd93e45f46316737b724dc67781770.nq.gz
│   ├── 964bec75f9aa0b24a8ef3ef3f897472fa9cf2352.nq.gz
│   ├── 96b9e542cce7ee3d82f5e1bae083181b99710d86.nq.gz
│   ├── 971bbfc0d0a0c7f43ba9ddab0410fcc5fd0becbb.nq.gz
│   ├── 98d714613795995ecd12680932d822eea5755004.nq.gz
│   ├── 9bc21e3af3197c771a5451dbc2a90aa356ab31b7.nq.gz
│   ├── 9e908c7ff8857cf8cd9d595e74683083d0ad081d.nq.gz
│   ├── a2158d2887298aa191e47ba2b25557b040c12a13.nq.gz
│   ├── a2ae0fbe3feabb6fedaaa15739752a39d2268df6.nq.gz
│   ├── a4205564f3de8e6e0b80e1d5bf7e63b2847594ba.nq.gz
│   ├── a610d339a540b4cfdf2d3ca87680141d7adf9864.nq.gz
│   ├── a6f779785c56d6c0b93a32d59fcd8f54ec0ff590.nq.gz
│   ├── a7896f41b433747ba768eb96ae66b3a2747f9b20.nq.gz
│   ├── a83841d2e8ca566a4d3fd731df0de61338536c5b.nq.gz
│   ├── a8c8517c6b51e5aae3745f0ef923fd3d55ed072b.nq.gz
│   ├── a9dc24f391f71f64b24ecba1cbfa35e384c7467a.nq.gz
│   ├── a9fd882064d393c635d92dde73a5c9388d5c713a.nq.gz
│   ├── aa3a34e434838e649d448e5dc8836540073cf018.nq.gz
│   ├── ae37d9804e2e6529ae57053e8ee28794c47f96a5.nq.gz
│   ├── ae7b83179d7b0e5bfed1be41ac510fb1cac25c92.nq.gz
│   ├── b09591eaf51c791134f47c394cc684c1a8cccb71.nq.gz
│   ├── b11c0af5b003bb1f1ff612df1465fc349660607a.nq.gz
│   ├── b266b67a6a05c03e84f091411549cf046caa2b04.nq.gz
│   ├── b2a58e1cda45da9562a4941c544036824999a8fa.nq.gz
│   ├── b40094e174e15c96d316f14273f8d4b35ca10905.nq.gz
│   ├── b45252c58e5f3b5b3ddfb629bd0eaf2d722fb1bb.nq.gz
│   ├── b6606ef9ddfcfb651496e4f9463d38ab7089d2d3.nq.gz
│   ├── b7e3d5a8533e1f902e3bdf649b0ecc36eb47faf5.nq.gz
│   ├── b92201a17f5c3de7c505cdc854d037c278a03854.nq.gz
│   ├── bbeaca0816d629b17e1fbfe93b4be3f099e43e76.nq.gz
│   ├── bd13a7beb2d1dcc399fa601a7e635539075e76ca.nq.gz
│   ├── bf4cc33a68d9bcc22f22561b470234ddd8fcffd9.nq.gz
│   ├── c22f30cbf485492713a0612f5b0110ee822fd9f0.nq.gz
│   ├── c329d0f883a5b89534d0197a1905f267240441de.nq.gz
│   ├── c329f97263f6a17f9ca291f263210343b16c0e5f.nq.gz
│   ├── c3999d98758dad0dab37dba614220b0364d00398.nq.gz
│   ├── c3c3882847a5413c99c24ae478359a2eb306269e.nq.gz
│   ├── c401362e3d4891b6e63d3c8f1a89f75f247f1a2d.nq.gz
│   ├── c403d8122f40975175314809c9429f40a033f23f.nq.gz
│   ├── c4982085d82c084e24f05963341b274873317dca.nq.gz
│   ├── c686438934d74acba174ef18e3a296821add10f6.nq.gz
│   ├── c6e96fa817f0f02bdacfc1f5f019ac3299d1ac41.nq.gz
│   ├── c767ab3ba171cada65bbe13fd5b0451ab4e3f792.nq.gz
│   ├── c768608d5782984f9ea4b25d87da86ddfb10b412.nq.gz
│   ├── c7809aaad7cf65172e50e7e3d895f2a96e742933.nq.gz
│   ├── c79d7639a2c01ca0602f6a463d884fdb0ff99f86.nq.gz
│   ├── c9317f0580c61db9fdb354a9bbdd73633b4925ed.nq.gz
│   ├── cd25634fe98c1b15f951a16aea0c5362c8ceb876.nq.gz
│   ├── cfdc4905d83c24e9a0816f5fa98f3d69dd978252.nq.gz
│   ├── d1e01b4674777bcf9d5005314878df9414329464.nq.gz
│   ├── d31f078b497dd5ad8f3ae2bceb76cdb0f904afe1.nq.gz
│   ├── d393b4d9efed1304f25d86d7f735d88bbede7129.nq.gz
│   ├── d3a9cfe67a0f0b077c05570825cfdfd2413ae5c3.nq.gz
│   ├── d5235338aa83a208bd639d3284914b9e4f9b3644.nq.gz
│   ├── d64940981357c2d5f755e6da114960d39957f3f4.nq.gz
│   ├── d88781dc5dba8e1b819b72204cc0ee39f4462045.nq.gz
│   ├── d8ce55ff5e3de406d28352d4a00242f81acaad59.nq.gz
│   ├── d8cf3c310a3066ca2539e7cc91c0e237e542c088.nq.gz
│   ├── da23886fd2c012883b39f84012d0ee67bb9c41ce.nq.gz
│   ├── dbdf874d399a7f699198b63f76d78abc67c6c7b1.nq.gz
│   ├── de7377641532aaabdaeb0209036ece91dfc5d7c2.nq.gz
│   ├── df186e68d48d2be881ff012fb777eccd392c94a9.nq.gz
│   ├── e068b9827e7b85daec26914dd725c3ac400ffb96.nq.gz
│   ├── e207b96bd196e9bfead3f7aa315fb18a7d1dbcd1.nq.gz
│   ├── e2e5ac3aa3d8692037199f332472db4c744c1cd3.nq.gz
│   ├── e39a4cde31f2cbe32999ed3e1bd179279a8e45d6.nq.gz
│   ├── e3d724e80a1cb6c397f5948c9b710982d2511a55.nq.gz
│   ├── e5e571e6bfe820bb2eb42c53d72320d3836f037e.nq.gz
│   ├── e65d1089facd2ee8dae479539f672b8f27bb9ebf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6bfe570c1574ef32d2c2b15d34a534ccf8ef87f.nq.gz
│   ├── eb33df8a43272224b9f11cb5d4e3a38e1edcf15d.nq.gz
│   ├── eec8f12fe420611941913b08e13146aa74d48b75.nq.gz
│   ├── f0d9216c2baf7c47d84525e70ab627c39879e6d8.nq.gz
│   ├── f12102e2e0f1381ddf8565da33a32b95973b1455.nq.gz
│   ├── f17321728f94b35be5010258f7ba9396b117205d.nq.gz
│   ├── f484a7179bca73df18be562bae0598084f9ddfc2.nq.gz
│   ├── f764333f593fbb8103a98875d9eb17b534614eb0.nq.gz
│   ├── fa4e0676668c64229b3e6c816f919da4f50f3e02.nq.gz
│   ├── fb0bbb8c2e10e257cad1cfa8d05dd7ba4fb71798.nq.gz
│   ├── fb232bd6118f3c9b31e65e676c6cad1a110ff26c.nq.gz
│   ├── fdebeabe81a86d592b82c8554be823f1f74a7379.nq.gz
│   ├── fe0c616209ba3cf0d915724d0be604ac0f386f26.nq.gz
│   └── ffbb4e5982a8b6169295f35ead2d3aa64155be84.nq.gz
├── branch
│   └── branch.nq.gz
└── commit
    └── commit.nq.gz

9 directories, 200 files
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

[allenai/olmoearth_projects](https://github.com/allenai/olmoearth_projects)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
