{\rtf1\ansi\ansicpg936\deff0\nouicompat\deflang1033\deflangfe2052{\fonttbl{\f0\fswiss\fprq2\fcharset0 Calibri;}{\f1\froman\fprq2\fcharset0 Times New Roman;}{\f2\fnil\fprq2\fcharset134 \'cb\'ce\'cc\'e5;}{\f3\fnil\fcharset134 \'cb\'ce\'cc\'e5;}{\f4\fswiss\fprq2\fcharset134 \'ce\'a2\'c8\'ed\'d1\'c5\'ba\'da;}{\f5\fmodern\fprq1\fcharset0 DejaVu Sans Mono;}{\f6\fswiss\fprq2\fcharset0 Microsoft YaHei Western;}{\f7\fswiss\fprq2\fcharset0 Arial;}{\f8\fmodern\fprq1\fcharset0 Consolas;}}
{\colortbl ;\red0\green0\blue255;\red79\green79\blue79;\red0\green0\blue0;\red246\green248\blue250;\red43\green145\blue175;\red192\green0\blue0;\red51\green51\blue51;\red255\green255\blue255;\red255\green255\blue0;\red255\green0\blue0;\red0\green176\blue80;\red100\green100\blue100;\red127\green0\blue85;\red192\green192\blue192;\red63\green127\blue95;\red106\green62\blue62;\red42\green0\blue255;\red0\green0\blue192;\red0\green128\blue128;\red63\green127\blue127;\red127\green0\blue127;\red63\green95\blue191;}
{\stylesheet{ Normal;}{\s1 heading 1;}{\s2 heading 2;}{\s3 heading 3;}}
{\*\generator Riched20 10.0.14393}\viewkind4\uc1 
\pard\nowidctlpar\qc\kerning2\f0\fs21\par
\b\f1\fs44\par

\pard\nowidctlpar\qj\tx840\b0\fs21\par

\pard\keep\keepn\nowidctlpar\s1\fi-425\li425\sb340\sa330\sl576\slmult1\qj\tx425\kerning44\b\f0\fs44 1.\tab Redis\f2\'b5\'c4\'b0\'b2\'d7\'b0\f0\par

\pard\nowidctlpar\qj\kerning2\b0\f1\fs21\par

\pard\nowidctlpar\s2\fi-567\li567\qj\tx567\fs36 1.1.\tab Redis\f2\'b5\'c4\'b0\'b2\'d7\'b0\f1\par

\pard\nowidctlpar\qj\fs21 Redis\f2\'ca\'c7\f1 c\f2\'d3\'ef\'d1\'d4\'bf\'aa\'b7\'a2\'b5\'c4\'a1\'a3\f1\par
\f2\'b0\'b2\'d7\'b0\f1 redis\f2\'d0\'e8\'d2\'aa\f1 c\f2\'d3\'ef\'d1\'d4\'b5\'c4\'b1\'e0\'d2\'eb\'bb\'b7\'be\'b3\'a1\'a3\'c8\'e7\'b9\'fb\'c3\'bb\'d3\'d0\f1 gcc\f2\'d0\'e8\'d2\'aa\'d4\'da\'cf\'df\'b0\'b2\'d7\'b0\'a1\'a3\f1 yum install gcc-c++\par
\par
\f2\'b0\'b2\'d7\'b0\'b2\'bd\'d6\'e8\'a3\'ba\f1\par
\f2\'b5\'da\'d2\'bb\'b2\'bd\'a3\'ba\f1 redis\f2\'b5\'c4\'d4\'b4\'c2\'eb\'b0\'fc\'c9\'cf\'b4\'ab\'b5\'bd\f1 linux\f2\'cf\'b5\'cd\'b3\'a1\'a3\f1\par
\f2\'b5\'da\'b6\'fe\'b2\'bd\'a3\'ba\'bd\'e2\'d1\'b9\'cb\'f5\f1 redis\f2\'a1\'a3\f1\par
\f2\'b5\'da\'c8\'fd\'b2\'bd\'a3\'ba\'b1\'e0\'d2\'eb\'a1\'a3\'bd\'f8\'c8\'eb\f1 redis\f2\'d4\'b4\'c2\'eb\'c4\'bf\'c2\'bc\'a1\'a3\f1 make \par
\f2\'b5\'da\'cb\'c4\'b2\'bd\'a3\'ba\'b0\'b2\'d7\'b0\'a1\'a3\f1 make install PREFIX=/usr/local/redis\par
PREFIX\f2\'b2\'ce\'ca\'fd\'d6\'b8\'b6\'a8\f1 redis\f2\'b5\'c4\'b0\'b2\'d7\'b0\'c4\'bf\'c2\'bc\'a1\'a3\'d2\'bb\'b0\'e3\'c8\'ed\'bc\'fe\'b0\'b2\'d7\'b0\'b5\'bd\f1 /usr\f2\'c4\'bf\'c2\'bc\'cf\'c2\f1\par

\pard\nowidctlpar\s2\fi-567\li567\qj\tx567\fs36 1.2.\tab\f2\'c1\'ac\'bd\'d3\f1 redis\par

\pard\nowidctlpar\s3\fi-709\li709\qj\tx709\fs32 1.2.1.\tab redis\f2\'b5\'c4\'c6\'f4\'b6\'af\'a3\'ba\f1\par

\pard\nowidctlpar\qj\f2\fs21\'c7\'b0\'b6\'cb\'c6\'f4\'b6\'af\'a3\'ba\'d4\'da\f1 redis\f2\'b5\'c4\'b0\'b2\'d7\'b0\'c4\'bf\'c2\'bc\'cf\'c2\'d6\'b1\'bd\'d3\'c6\'f4\'b6\'af\f1 redis-server\par
[root@localhost bin]# ./redis-server \par
\par
\f2\'ba\'f3\'cc\'a8\'c6\'f4\'b6\'af\'a3\'ba\f1\par
\f2\'b0\'d1\f1 /root/redis-3.0.0/redis.conf\f2\'b8\'b4\'d6\'c6\'b5\'bd\f1 /usr/local/redis/bin\f2\'c4\'bf\'c2\'bc\'cf\'c2\f1\par
[root@localhost redis-3.0.0]# cp redis.conf /usr/local/redis/bin/\par
\f2\'d0\'de\'b8\'c4\'c5\'e4\'d6\'c3\'ce\'c4\'bc\'fe\'a3\'ba\f1\par
\kerning0\f3\fs22\lang0{\pict{\*\picprop{\sp{\sn wzDescription}{\sv Image}}{\sp{\sn posv}{\sv 1}}
}\pngblip\picw12328\pich4974\picwgoal6989\pichgoal2820 
89504e470d0a1a0a0000000d49484452000001d2000000bc0802000000438bb8ff000000017352
474200aece1ce90000000467414d410000b18f0bfc6105000000097048597300000ec400000ec4
01952b0e1b0000240249444154785eed9dcf6b1cc7b6c76bdebfa1041290b488bd17197341594a
163c2f8c1f790167375ac4202d6c02c10b2d42c0d80b199c85b54b20eff28c177e608f9609042b
78f1f2ee05cbf75e8f2081c47f87dea93a55ddf5abbbab7b6a7a46d2f7938adcdd535d55a77e9c
3a75ba665aecededfdf3f5ff52a083f5f57551301a8bd3d3ea3011431db1132395c8589f9544af
0fc544653ad2e7b12b2954dd9598a910fb1379651ce43ab6639a1be32114b90ddc2811a92bea73
b81fbf1e69dc6883b22c556d9d5c6f36952214d4675a9d3ea73cd9d7a7369599b64d2d4b85982b
f110bd7dcae146544bea501dcda990b64d9f4b8a73c2bfe97f5b331147fa681e5c16cbfaa85756
55ae6f5fab932a6657b6a1b8b3214e1e8a037dde0935001e6fe8b3bec922425be692690d73e9bd
731a322046b5da3dd814832be24488c36d3118b8c7143675b4f9f05a16665eac5ed60771b86c27
e20a579417a6a8b7d15d3972eeefead36e8c5faae177681549b56c3f6411a12d73c9b48e99f590
3ae63a64804badb53bbc21fb2b1b77f6f1fc39226b5b7227b6a2ecc88ab302e2b1eaf156f5dc95
8fd449c1906eb5e0b22d8b1b7917549d4cb61b57e5dfc367ea84180969e692ce9dcbac99c5eaac
6efa6bca849fbc512705f599b64d2d0b33ea21f5240e99b954c885a356ed5e5e9573f213e54db0
8f1781af1fcabfcb3b1107d37e83fb2a800d016b18ec4fe2cbf0272fe45fca74dfc494ce53b61f
2d9e1dcabf3b2f635ee0aeeead24936dc3719f8dc6624795ec59a17258d28db2fc84b67fa31805
71b76d95c648b53a9b322d9adeaedef1a99a514ec4d7ae7e6dccb4556ab92a64163d846e63d76a
950b3571c8b4ab10d0097ea4f6afe35ffd476a847c52645a483e4df25a6b1a2a1e01b572d5f303
ae30845d5953edf20f931aefc723f3d3333b4cf6f5453b6655d93a3e5550258f3e2cd270bdc582
571bd1824dccc5308b687c9d64abe72a8d2258d465aaa8aa5e7b3a91a4659a9a9a2257855465ea
f710be3da5db988c6a2257659ad249289415d2aae98974292e04d2da1d0c067ce2a2d6ce7a7d3a
145797c5c95b75bc30ecae44fc92b49cdc6c3f215352cafed06c0fc4e6137decb139100fad2c0f
b7c54acc928a964daeee57c8606a4daa9da83cb6be206e6d50c1b6ad18545d74cbca7d7dba4c6b
1a178a6fcbdb995411148d99caeaddd6c71ae52add752b3731d3c4d4985c152233cdd743128966
1a0e995615023a40462e99ba716b172c04cab26830d9a2d6c7e290224276e6922900cd74de4006
fa62ff8efc9b68272e267311e11cd41b38a740ed2e3823f958ec707b61f69c76602e229c837a03
e716a8dd05e740fa5e3b78ab1788b988700eea0d9c5ba076cf074acbccf93b2c008024a0760100
a057a0760100a057a0760100a057a0760100a057a0760100a057a0760100a057a0760100a057a0
760100a057a0760100a057a0760100a057a0760100a057a0760100a057a0760100a057a0760100
a057a0760100a057a0760100a057a0760100a057a0760100a057a0760100a057a0760100a057a0
760100a057a0760100a057d2d4ee705f9c9e8a9175bc3f54272e88e681681e88e681681e7389d6
3f7b7b7bff3afe95021dacafafebab1efb13713a115c60fbd803d13c10cd03d13c10cd632ed1fa
2741ed0ec5e4544cf6f5d9d83a7640340f44f340340f44f3984bb47446d25eb6839360f06919c6
3a8a8993e264b82c968578f1441d8fc44671ec81681e88e681681e88e631976829280d7efa589f
152cef8831bb305a5267ed8ec696c20e83b1d8114d0744f302a27901d1bc30d768a9b0ce55c1d3
b19451a976d9922d0cdb2829d6ee472bfa20ce441ca97f114d83681e88e681681e738d96c8fe77
d26a1687623010077cc970b02936bd4b099c9c34fa766dff88eb2b7140340f44f340340f44f398
4bb446d4bda19d1b21d9da2503b941ed863b30a2d9239a07a279209a07a279cc255a3329ca94d1
0e8420d8f736aadd4576ca209a0e88e60544f302a279c1444b8455b667298fad04cb8f5aa8ddce
df524bf48f209a07a279209a07a279cc259acbf2aa3e6846b9809db0a93fb1a9753228bf867e54
671f7b209a07a279209a07a279cc255a0aea763251c3047c4338c51d9162ed0e6fc847786f5ffb
c71e88e681681e88e681681e738996c491787122ff7ddcd23b518b51bb03fdafc36532ad4fc413
6594dbc71e88e681681e88e681681e738996c8eee7948020e5fd721aabd9453a19defc4a21e264
909e636333cb6f3457d8cf88e681681e88e681681e7389d602e36a0843f3233515f44ff0343b19
86624588c367faf8eab23879ab8e3d10cd03d13c10cd03d13ce612ad154762652006dbfacce6fe
ae3e68459db50b000020379d3790010000e802d42e0000f40ad42e0000f40ad42e0000f40ad42e
0000f40ad42e0000f40ad42e0000f40ad42e0000f40ad42e0000f40ad42e0000f40ad42e0000f4
0ad42e0000f40ad42e0000f40ad42e0000f40ad42e0000f40ad42e0000f40ad42e0000f40ad42e
0000f40ad42e0000f40ad42e0000f40ad42e0000f40ad42e0000f40ad42e0000f40ad42e0000f4
0ad42e58484663717a2ac3485f00e0dc7051d5ee78ea213ddcd77aa108e3196988919f1185f3a1
8ca66f85d9b1c86503679c34b5cb2a86bb201fef0fd5c945856cb1973bfab860e39a3e0000806a
d2d4ee8dab429c88d7d6f19323757251b9b621ff1e6e8bc1a00c57be569f65e7c0cae50ad5fd85
e060538b7ca02f00706e4851bb437175599cbc10ac6957ade316c456ca14cea4d53c142bf4f744
7cedaa84a345988a866242153ba17fa7a0a2b1b0e2be4064e948204e8adabd2c968578f1441d8f
04d979fa38073b2f67e61205b9797ce19d4b00e4a056edeaa7c98fe531e947ffb8c34c7868ad97
0762fb505e735ca23cc74687b732c126fbfaac1db6f956536cd7caf3f32a3e7d29e721faffa515
998257667e265384786a637da631e27798897476d1b279b924e236966a2bb17357fde3515f6f05
8dade0a6234375c98bad0e45e8d83798c6b2315e09ab62a655481e11382f5551ce63deaaaa6b12
217f47b20d673777ddcf2d114ac2b1d056d2341ac6a9216b7fab55bb1fc9b5743593f6ae069783
67faa0e448dc57e3fbea0d756ab17f47febdbfab4eda205b48cd161ad593946fd64156ab1d8d22
eed48ec01a54fff0b2a0d4a6d20bf3e6eb87fac023b1de125b2191fd89781cdc4cf9765b382596
8d32f524e598de749b5821794520285fe731ef46a4bf258a30232e7bf5dc95144993481ea7391b
4b65bab7b7f7af37bf52a083f5f575fd51899a737439ece3b684139a99cdfc260f6739822f7698
d64c6a65b1cd153b0b3d79ba6383a7c1880f8453a8d1c824acfba94edf2e7f58214454769bc408
35654b215636a94d82d64fad3753ecfa567088d60f5325e3a8ba5a6a482b9b96d4954b1b4a5649
da55481611b8a254284488162351044d55093b60d567d1a05c185d90c4b1902c692a9460b48aa2
2509b3e8d6df54a60d6ad7ae1da7a6da625559192a2a4bcec9ee08e731df614ee61bc3d1cbbdad
90c53b65585ebb189a0e3d32bc25b1ab7924466855b690a06cba1a2b1c298df596d80a0ed1fa61
1a2ba10dad7a48d819f87aa1c8122b24a708666435aaf5441134593a126384f5b328481c0bc992
76279a5a589269a9763270776463feb1cad53ece23e7b2f82e546a42ecde977f97af9a2c86e20e
59f88762b7bd5383fd2487a137c386772614a299c0f22eafaacfda53a82a19d85376b6d828cbcf
2bacc36db70992eb2da915d2319e28ce37322fb6a1550f097d5ccf5449563e5227e91d29ab0892
43b1196eb55b1697f551b208b323d8f9d39146495bd23c4eb3379651bb83c1800f92e9e6d8b59f
d26ccb0b51b79738100f4f6455de55f3cbe8aeac8b6e837655d5e25bde725c85daaa9113353d86
cea033cc89b83208ba7b72bd25b5421be4ae5ed57f08d985d478e8e6a0cc59b6361d29a308a023
c9e3346763c94cabad5d9993da9cafbf14601f53d8d4d1baa3be05206711a35e6d9ebc907f37ee
88219bbad34d95abf553e16b291a6b162d9d1dda4b3ae639d39e63cee2d71c4cf9e5869365f132
9c1d5bd65b432bb4a5f81689a9db693623e6295bdb8e945504d09676e3345363a94ca5daad3475
873764b1d810b08f3352b5c039da351a994dddfb9d8c6b2ab0aa213f7db3e0d21c91ed2ef3ba91
c5d6505b9b655ba6e8eb154797b15dbf68d004cc8b0f5ff326d75b522b74e648ac0cc415b5d1a2
c34ab9450f11e24eb0c0e4ef2b4edea893ce1d693a11924814618ef43c165a8d539b691a4b675a
bb81ecf2aa9cbaf97bc0f67136d892ad6872deb1b4a1223ceb6aeab2d54ceb826245209f6f041e
1cd6fed1e96bdcd68bcd26cf86b306d1f3aa0d47b3866874934a6bccc80f1710d3b0bb6234affb
dc23b1de125b2111796fd028f23beb9d482c1bf7468a664b3ae6ed47d6522cb142f28a9048a208
9ad974a438331a0bf5248ed3bc8d6532dddbdb7bfb8fffa310d9c9201f719a61267717441f2b27
629e4246422092c63c409cd287cd0f6aed4009f245bb47f1f68948088bc705ab2a7645521373b1
10278c36ded72257767553273563219a7bbbb153b18b40a7ec5e4facb7c45628a9280321878195
8e1dda896998b287d8e39648a9909c22246e0350248ac0442377a9e1a6f142847945c6421b4953
880a188ed3bcfd8d33ad56bb4a1e3d31aae3a21c5da852bbb17155c00f19bbb4b48b5dbf2c517c
c09b262c43b47809ddc87e3caaebada8012b4d7bc0cbc234f6a1c6088ab03fd5c7f7a956794581
9d04d3ea2db51598ea324882ee3455e74c2f9b976f551f48a9905c22442baaa69f248aa098b623
315c98da8c88e6b1d056d20412c76979d18469fa1b655a67edce99682d0300c0d9a6d6b73b5fc6
ea7b840f67f46b8a0000301f164fed1666bf74a977fa8a0400002c300b6ced9e3cecb267160000
169bc553bbf26b1a6a5bf24afb1f1b038b4fb19ae9f60c64a62c72d9f27271244da4df0a59606b
f7ac822781f55b14ce28c1b36c0a110113a381b3cf149d3c4dedf2ce35ce808fa31bfd00000034
91a676f10a4b908bc28934c56f6ccc8abab2155fc9a790f2cdfdfa68f366915b612ef45b21296a
37eb2b2c439b5cdaea9d97e4693bb1337376338d2d812960150c7ce6d2c92f0a296a37eb2b2c1f
e3eb0f8bc763788d00e88f5ab5ab9feea9af2dec64798525b1e1fc1247259e5d16e4a5bf4ac83f
5da1de0755460e35bb9b5ae72ff6b5cb942c06fbdbdc15f38d4ed384b06c6d336dc6fea5bb73f9
6eca464b4d45d0c9b6295b7fb41281b0e3bb1295a32d4dd2b98c2ca6712c24c1455245b5076024
b5564d6f47ae69977a7422b56a37fb2b2c4f94af4bfe8aae3aad427e133cdf8bf6e43076535b8e
feb67a6e285f7ead80267cd19e6a03ef8796a86c53f6ddb69cc377539a5fcf2a7e44977f5ba0ac
58b5809bff4f1dd6d055845caf894c21e7c89ac158a01ab307a02c5bd709356f27279a7e93c19e
54bd09b615aa5ac9cef57b0f4f7156751413946d14eb69306cd126a340a7e646e0d4928cee28f5
995ab3622166b41832a67b45478b768e264993e0b2b9e9b375e9356b6abd71a9ecdbcd150af10a
8e9541532563fb7705b2507a9e2e8a643265e92269d694cdc624d850aac46815b413a1885013c7
a651524eb0babfa5f690445a8d857a5834154a43cd5cac2c5b4d8598ba6dd1c91b68f2edf2af9b
f3fb97ece3ceec7e2e1fefd2cc5365bade5513d4c943e715329bd5efa1a88753db5e710c73b6ef
66f57bd286c3edf21b1f474f620fb50fc4c02d988ee6fedef34ca1b1cdd6a5e7af4fac37fd5bd4
87d6775bd48f40b3e3a223e17bb10e5a3f5f7efd56fed5ef8c5086e12195c9542cff7874ee9fec
cf4c3711e4fb5fcc773b8f7667f8683ef3c89ac158d81e583f2d70a05e92426bce6beab40d33e8
e4d56a97275bb6d2f9dd6df671cd34d8c091f85cb5cdce77b114f2be68cfa4a6cb6c42e49582d9
497ed11ed7b30eb15f59cecf057837e5915a7d736f19d148a3e6a0429a1fd296c5eef632c01ee9
2242aed74436329b9195732c1cfaf30d4f631dc8dcc925293b19a24cd16b6912e65715445f1b9c
1365232c2e6aa932f35fd1afe7bcbe9b52fd8c3f8fff6b1be284869cbac2c6a3dc04d97510f6c7
228b907d642dc258a8207b27af53bb7200a8fddeb3788565a3ab210ffc0a8d7cefa6cc8bfb06bd
d332ac9c1e8953e185a3d395aa8fd2c381950b87688261343b6c963137d595dda3f28a7dfdc0bd
a803275e261290e55d81fc488a96a8ca2e932e9423f1e244ad31a7de04d9138b2c42ee91d5ee6d
92f320cf4b4e35b5d6ee0c5f616996933bdfe9d58a86bb5aae17ed99c7c1ad5f29d8039137e80d
c47030391d9c4e06433af642cd47e9613438a544c6e595fd89ba12243ba68ba783fda173310c7c
fb64dfbdce453d1d8cec8b4570ca50cbf4efa6a4a6a77e6bbe54f9867ac38a18a9a4de2cb88b41
b1b822e41d5991b1901f7efb59075fc10c5ec05aab7667fa0a4bb2a6a5e25da6ff1cf2be682fe7
bb290b9a324d82ed858437e869b2641a708edf4d2935941057e976e3103b50bed13bd637dd179c
798ad0e7c86a3b1652d870fad2682c7654721d5e869bb79333751bc8e47610331ae5c6af0e9b39
0ad4fe0cbf858aad1e6ecabcc92c0c518f4434b29d4f556add9f0ad6671add8962769c54174c2e
b7e94ff806bd8246499ba9d825a3534e6b05afde78cf901da8e47c315e36a70c8e9341ef198a85
766232a67795bdaed8f713d480a6a27e7c62ad1921315a0de922f0f5f42e9d2069637f4bec2129
4493aa190b75984a0b43384394d45648eb4ede408db5abac686d93f3cf326477e19b5d1d1e6482
15cf5534ca8b147dd384b6d7aa91a9857e225ad1b81b565ad198690a948827fe602056eeebe3f0
7170964ca350cab2206a8743d18d12eb6d73e094cade36d716b9e1c96b776af987b25aba3c9f67
1bca3670946f94c8fa547a96cc5584c6fe96d84352a0a4ecb1c08d5e33169aa162b87bbcb6c347
c7c964ece44cd3d725404fc41e2e9d7f2ea6d46096242e59e649e70d64000000ba00b50b0000bd
02b50b0000bd02b51bb075ef27c5bd2d7d01007076e0afdbccfbcb50b57451bbac97a0950000a0
03b0760100a057a076039e7fb9aef8f2b9be0000001981da0500805e81da0500805e19ecededfd
e77ffc3b1dfdd77fff8f7a80ff137f60b175efa7db6bfaf8ddd32f3efbfda63c7ff5c05986db91
2432e2a3637d62e346f4a3a94fe5c51f3ff9e1dbeb4be6737393976990ad971c7faa6eba744ba5
c704c9f8e910619c48248ba6342b2b44731aff452e5deed8dd2a7dff83b44c43499a8a37232aa4
06e03cd364edd2a87706e8d2f56ffd01ab0671709122fe70eb923e318411657a61bcf76f1a1db9
74fdab5b5bb77e3037ad7d5ac69545f3b38d2727f32d752eb1763b12292ba9923672fce8afafe8
9fa58f3ff16ebd74eb534affd55f2d5d9996a9dfa4ccd2f59bd89a02402fd4abdd4bb7be52da8a
4c217eccb4fec5d377fc91471943c2b196deff903f6468b8cbd1eec47ca0548a3fe297d6d696c8
78e46496aedfbe6e9d99344dd1a4956950a9d10d5fb98a66ed36e55b64abcbe6a931f31c4dc2c9
44b0231974e4774fbf2f4ddd74495378fe3d57837beba54f3e26f15ffd5ce49a9a29dfe8b697e4
c1cf3a020060b6d4aaddad9b4ab3bd7a502e3f8f1f7d16aa255247ee02f5f8c75fa46e7bef034b
b57162765a04ab143722414a412ed88f7fffd33a73d045733fa272c4b51ba9e6225b5db62c9079
a9559d2d551b4953d025b62d7dcec3d6f52d33f5a644e2f973bf8e01003341abdd41ccc376e983
f7e43f964555875ce116384b7a854e6cedb68ea1e1889e1278f7cb8f96ee70cf1853347b89ad78
feb39a131c45f3ea41a0b5637aa72d5ae7da2a5dd146d234024743e86048cf5427a663cedad902
0008a8b3763f7c5f8ed9777ffcc6a7d5c4bcac3e9cd879c1f84749e7062a7d1692ba8e066dd9da
d3619b4ca5afc4ac58a4f317ea17805e916a376aea1634da675bf7d8a6b29cac1117f06f7fc82b
a14b918998a38b0be95c25714ce7123391d47234b0a9eb3893db675ab8a9754b49f58baf7b03d0
0b75d62e0fe5c033a8d7b386adbf4833b7420595b09f367c20df0dedf575dc9d0a2e8df8f3f7c0
2f91892dbd29a25ae0bc921a0a47c3cd9bea599ae75ee99ca974d66bdddbc5ef0c00684d9ddad5
1696bd33402eaed9b62d60e5ec3eefd1f6af037b5da356d5d6bdd66b5cfdb08892b352d3de56df
12cc87c9a07e92c92b69817634acad49ad1bf8db5333952de8978137370000faa14eed1a0b4b0d
6686d4e9bba74fd54543a19c4d1ce5e67df74eaa0879ad18e3cfbfd40b5affb94f935b38caf1a3
6f82d4389d774fbff11fb4e561eb9e296820016169bbbc9216147b30a2d34a8b4cedb692f02419
3e9f0400cc825ab52bc7b2eba62533efb347bfeb138dbfa74c39183ffb8c35368df1d2376c2d68
6d54a2ed47bc4acddbcc26f3ee92566ef24a6ad0d360957e4ccad46f2d856ab28e5e6700405bf6
f6f626fff81b05bcc272be24bccc91f7e8054e84b30c5e61092e200dd62e581cd8c73133bf3500
a027a076171eb671b58b160e5800ce3c50bb6707e98185031680330fd4eec2537cb361119e1502
00a6066a1700007a056a1700007a056a778138bd7801800b08d4eea230b8a801808b06d42e0000
f40ad42e0000f40ad42e0000f40ad42e0000f40ad42e0000f40ad42e0000f40ad42e0000f40ad4
2e0000f40ad42e0000f40ad42e0000f40ad42e0000f40ad42e0000f40ad42e0000f40ad42e0000
f40ad42e0000f40ad42e0000f40ad4ee79643416a7a7328cf4053007d00a33e52c57efa2a9dd91
aacab13e03e79b31b4d22c3907d57b4e7b489ada1dee97c2f3f1fe509d00000068479adabd7155
8813f1da3a7e72a44ec04272b0290603190ef4053007d00a33e52c576f8ada1d8aabcbe2e48560
4dbb6a1da723170b35ae83a1989c8ac9be3e03002c34ec0c0c02fc4569a4a8ddcb625988174fd4
f1486c14c76d787b22c40a69d70a54169337fa0c007016790cf76312b56a573f2b7c2c8f775e06
c7936a351a6599b46b9ce147f2ef5bf66218d889ac4395a5eccebabebd6c3da04b4a2d0565986b
d9dddcf5541f7d2ac877d9e64062d9d245700b5317272535c64e53893cd5238e20b5289c45112a
d740aebcd1a697174dcdb33aa87cfceda6e6178f3fcdd50a818c4e684a33a942da8ecd6e1cea65
3e8743756de7aefac723970869d5cb146d5d84ca7cabb0077b146f99dea81c0879bd56ed7eb4a2
0fe24c5ab81ade4ce4df8f4cf1f727b228635396cbabbebf98aaece58e3e966c44aa4c56ab9a06
0a9677e27594925a5b2ed3f07373ef4662d9f28ad0a57a97c5cb538ad811a9ad1a53533dd5bb48
6ddabde957c5e4a55c48113bdf89d1be786c52bf63a5297ba3d794aa78a1e196b71552489434a9
7a67ccd70ff581c75c44a0362ddaba80f26d67311c9192932529ec45565c65a3572cd31b95c3de
dedee41f7f9bfcf3ef74b0bebeaeaf96d8eadc53ed6d601b41eb599e132898994a0ac3c7d61451
64a4ed0bb79da217d98828b4797a6a2d280a4fc1949fd3d4d972a6de246cee2a5b3db16cdd4488
9681484fcdc42c2bd312bc942211736f91693c35cad42d862e9b2b48b4c0954dafeee5d1a22370
d66edbe98f0cda1a2db248af371bbe2b6c8528260b5bd727494a24566f4662a249f56a97413143
116aaa97ef0d9b66d4ba365828dd284591dcce53a66995b9328ea241eddaf744ef4f45d591ae53
d3c38a7aa166f03e8a3449ace5bcc27009cb964b4ead05a6669d346da2bdc1dc55de9458b66e22
44cb4024a7c6bd2d4c215aed8d744f2d56b6164d6f6e743402a7690ac3a995371af8baaea8bcad
1062d2f7eceb24498d74b91a2b8940345d863e45a8a95e6e9a1cb27351ed6e30a6a2dafdcaee00
265fa79f44504e86c1401dbb7045f092eab14acb3eaeeb6d515e8b13b2d657e5e1e89a74293c3c
94d6fb0d4a6528563c43fd506c86bb426cd7b0ba85d08531814bc8b99434a6d68113f175967d2b
8965cb2b42426ad7d402edf0993a991af65625a6560c60198c8ba0a44dd37b5b6e228f824d6af7
77d53f16cf94ab72453d75d0cca223113498d582747b2076ede2264bdaaa7a73b251968a57f487
db8b21c291b8af9a8ff30de7d4748e945ee26e201517f5012a242b2e2e76e86b6d560e293b19a2
b471ec4ad84ba23633c8213d11bbaa8a57a9cf2aff88f73cad01750b9835ed1aa59a55d55acda9
29632174c9399cafa697c694d1b9fe504d9634b57a67ca89b83208a6a5f9892077f56eeb63e94a
56fa3774d63763d98ba4b84edeea2b5271a962cb2bada956bbb2dc5764063483c92795f631854d
1d2d1db9878c5013a09cd654e937aee96d0c6f5a6971752ffd4f2dadcb6387f665033dc03db586
31dbb6f6f371d5eb1cce51d393ce65bb2fa27389969236566f7e4c4b6dab95ebcb70053c5f110e
4c46a617edbc6c5cfe0714f6a2525c72c174245e9c48c545cb14b2103aeca66db0768737e430e0
29c83eee86dccc40c679918e2a3d8972836612f315b854cc134636f517117793f2e8ae94fa0cc1
73e4d51beaa440f5b30e706ace829d302b500d274e23b95e75e66d7a4ecdddd8c0b09b65767bc9
476653445ce712c9922655ef2c2113ed219521d4bc0b22c2915819882b6aa3859f4502b26cacb8
cc6e2ba9ca56c4a883bda8a955bbf6beae708f575b5e2b6bfcaaf5dd6256c43bd4bfdbba2c8ceb
2d3a7d8ddbfa9df3c233bcd5d5a27b59169c272fe45f5a9d15ebb26239dc81786a9edf96eb6dc3
59096afbd7256fd3f3b6272a9b9dda98b72ee5f2e00790cee52e51a9731589922655af8d798297
f4b82f8ddd15a379dd346725422df2dea027c85f35e8046f7e958acba8a903e5debd63fd64424b
6ad52e3b6139a7b8f3b80dec9c5ea68ab44bafe8e01fd1132c8dd3c7a60f99306715c756bcea6a
5c9e9d6571f850e994b3c3d12ed99d92420a32cd4e1eea8b6d494a2da8370ad494273c98ad0723
799b9eca16a6c6e93cfc7caa0e5fc9a89c86bd674d32586a2b51d2bc8dd519ad7937164304d567
8abc28d03024c267a78db09a22c5553ef1532682adca5a52a3760b27ac3a963fcbd0c5796cc1e6
4c912661ae745bca5133477c7fb44a5d99cd6849860a667717b26836bb3880e6cce6400f18e670
5bac3c518bbe4e337c24b5600050bd492fa18146dd602056eeeb53fbc177dea697a999c72f1ae5
8e741ecacf89444953aab70774cf573b1c0aebb67f114889fb0d6aba5397d58b5153cf8a9b8d89
d079eb85dcb7fbcfbf577f5d02800277c72b38c3a8a69c66671598825a2703b8c8ec8f7def187b
5a3bcff06071e027e49d9ec283e981da0515ac6ef8de31e98c8b7e65009c2d46d2734aabf845f0
a25c48a07641059b81778c062af6449f07d486564c9ff3e35ca8ddad7b3f29ee6de90b2007c56e
73133050c134609c1a9ad4aeaea91f6e5d52a7976efda0cefbaf382ec8456f3053ff25768d2c4c
6301006a6852bbbffdf14e1f298e7fff531f81de21adfaedf5257d6258fb4ba954733796abe48d
360f30468ca12aa237672ce66ca00b5929ac46cadc1487684acda9bac60a492c1b5878129d0c7f
fe7eac8f14effef84d1f2d04cfbf5c577cf95c5f38976cfd654dfef3ea010babf9e2fba029f234
56a0e497ae7f1b1bf15bf76eab7295c888be0a911ac39b33d66e2f9e02b974ebab6062b328b5a4
2f7394fad464624e32542175aab7a16c67808b314e536852bbbec5e41954a0372e7df01efd7df7
f47bb7cf1e1f973a365f639196541ac1d2f10f5ed1f9d2f5af424df9eee9173a8e44c5136b9f3a
f1b66e4a8d6145fce2a92cdad2c79f38a9b15a9b9b195cabd8e4c461ea844bdf4093d255899555
c269aeddae903e4de93ad6b3e48c59c66ccf37163a31dae29266edfa0693674f81452243635dfa
e463d692965df2fc4ba5187c4d49d73f7b6467f0fcfb5027e929e3971f8b88c78fbe49515d7dc2
8aedd5d38a721d3ffa8cf5639aad569fdaa55b9fb2d2fda6a83b4a5fcd58de84c534944da2346e
6084d3ca636eb318a8a451ed26fa0bedf9c7997283467727e4ca19cb8e168d144cec3556521877
aa999285b58966ede5ea65c99faa1b9df4bca48a4478892e17f0366ea2b99cbb1fbe2ff3f2f5f5
f18fbf50f281de8de3dccc0571ef54792ccefcad149b9c687ed417a6a221359ed6c4abbf3a1396
78feb35a510415dc5c36ea255ae37a3e285e7ba4d26845aa08e5e729a3de1b054464b09848d14e
5ec64f8c6670b3f6c5e24fd55d7503702634aa5d35c95bf68cf2cf544ff81f9200c1945b202575
3f95551734b3ac053b9a8c549d68037e62ccd2f59b9d6a573590e7a4247c134545f3728d8aaaea
c4496fed762452222d1bab1256dff6d33a056be3a5f73fe4d31824b894e6d50337573681650d70
a7a668b7d75c6b7aae68c556da9e53d1981a5764e874e77af72ab8b96cc6bd2e55ae57a3d4035a
d4b19e1e8bfc5537b61556c55c593feae742a2aa21720ec054121fa925b274fdb61a736aa2f53d
606aa8a9a52b7f2cd10e434705aa6e46ff9611a3ae34e39f97d4cce9c57a5947353cf859476883
299a9fde174f1db3b288e6bb464954cf37ba769beaa4488d0575cc9d424cfecc17c45de0e7429b
c94e07d4cd17850d0709756059c460a8d384c002c8e74632da9f0f6654f60e342bb63634a7c63e
9788fad2f5fede0765fb2794ad78d63afd24c6f6b6c95f1be5a51e56057ff5b3974deda84f1ba7
2652b49397622546337dd58910533544e3009c0142fc3f7bf51fbcbc3b03560000000049454e44
ae426082
}\kerning2\f1\fs21\lang1033\par
[root@localhost bin]# ./redis-server redis.conf\par
\f2\'b2\'e9\'bf\'b4\f1 redis\f2\'bd\'f8\'b3\'cc\'a3\'ba\f1\par
[root@localhost bin]# ps aux|grep redis\par
root      5190  0.1  0.3  33936  1712 ?        Ssl  18:23   0:00 ./redis-server *:6379    \par
root      5196  0.0  0.1   4356   728 pts/0    S+   18:24   0:00 grep redis\par
[root@localhost bin]# \par
\par

\pard\nowidctlpar\s3\fi-709\li709\qj\tx709\fs32 1.2.2.\tab Redis-cli\par

\pard\nowidctlpar\qj\fs21 [root@localhost bin]# ./redis-cli \par
\f2\'c4\'ac\'c8\'cf\'c1\'ac\'bd\'d3\f1 localhost\f2\'d4\'cb\'d0\'d0\'d4\'da\f1 6379\f2\'b6\'cb\'bf\'da\'b5\'c4\f1 redis\f2\'b7\'fe\'ce\'f1\'a1\'a3\f1\par
[root@localhost bin]# ./redis-cli -h 192.168.25.153 -p 6379\par
-h\f2\'a3\'ba\'c1\'ac\'bd\'d3\'b5\'c4\'b7\'fe\'ce\'f1\'c6\'f7\'b5\'c4\'b5\'d8\'d6\'b7\f1\par
-p\f2\'a3\'ba\'b7\'fe\'ce\'f1\'b5\'c4\'b6\'cb\'bf\'da\'ba\'c5\f1\par
\par
\f2\'b9\'d8\'b1\'d5\f1 redis\f2\'a3\'ba\f1 [root@localhost bin]# ./redis-cli shutdown\par
\par

\pard\nowidctlpar\s2\fi-567\li567\qj\tx567\fs36 1.3.\tab Redis\f2\'ce\'e5\'d6\'d6\'ca\'fd\'be\'dd\'c0\'e0\'d0\'cd\f1\par

\pard\nowidctlpar\qj\fs21 String\f2\'a3\'ba\f1 key-value\f2\'a3\'a8\'d7\'f6\'bb\'ba\'b4\'e6\'a3\'a9\f1\par
Redis\f2\'d6\'d0\'cb\'f9\'d3\'d0\'b5\'c4\'ca\'fd\'be\'dd\'b6\'bc\'ca\'c7\'d7\'d6\'b7\'fb\'b4\'ae\'a1\'a3\'c3\'fc\'c1\'ee\'b2\'bb\'c7\'f8\'b7\'d6\'b4\'f3\'d0\'a1\'d0\'b4\'a3\'ac\f1 key\f2\'ca\'c7\'c7\'f8\'b7\'d6\'b4\'f3\'d0\'a1\'d0\'b4\'b5\'c4\'a1\'a3\f1 Redis\f2\'ca\'c7\'b5\'a5\'cf\'df\'b3\'cc\'b5\'c4\'a1\'a3\f1 Redis\f2\'d6\'d0\'b2\'bb\'ca\'ca\'ba\'cf\'b1\'a3\'b4\'e6\'c4\'da\'c8\'dd\'b4\'f3\'b5\'c4\'ca\'fd\'be\'dd\'a1\'a3\f1\par
get\f2\'a1\'a2\f1 set\f2\'a1\'a2\f1\par
incr\f2\'a3\'ba\'bc\'d3\'d2\'bb\'a3\'a8\'c9\'fa\'b3\'c9\f1 id\f2\'a3\'a9\f1\par
Decr\f2\'a3\'ba\'bc\'f5\'d2\'bb\f1\par
\par
Hash\f2\'a3\'ba\f1 key-fields-values\f2\'a3\'a8\'d7\'f6\'bb\'ba\'b4\'e6\'a3\'a9\f1\par
\f2\'cf\'e0\'b5\'b1\'d3\'da\'d2\'bb\'b8\'f6\f1 key\f2\'b6\'d4\'d3\'da\'d2\'bb\'b8\'f6\f1 map\f2\'a3\'ac\f1 map\f2\'d6\'d0\'bb\'b9\'d3\'d0\f1 key-value\par
\f2\'ca\'b9\'d3\'c3\f1 hash\f2\'b6\'d4\f1 key\f2\'bd\'f8\'d0\'d0\'b9\'e9\'c0\'e0\'a1\'a3\f1\par
Hset\f2\'a3\'ba\'cf\'f2\f1 hash\f2\'d6\'d0\'cc\'ed\'bc\'d3\'c4\'da\'c8\'dd\f1\par
Hget\f2\'a3\'ba\'b4\'d3\f1 hash\f2\'d6\'d0\'c8\'a1\'c4\'da\'c8\'dd\f1\par
\par
List\f2\'a3\'ba\'d3\'d0\'cb\'b3\'d0\'f2\'bf\'c9\'d6\'d8\'b8\'b4\f1\par
192.168.25.153:6379> lpush list1 a b c d\par
(integer) 4\par
192.168.25.153:6379> lrange list1 0 -1\par
1) "d"\par
2) "c"\par
3) "b"\par
4) "a"\par
192.168.25.153:6379> rpush list1 1 2 3 4\par
(integer) 8\par
192.168.25.153:6379> lrange list1 0 -1\par
1) "d"\par
2) "c"\par
3) "b"\par
4) "a"\par
5) "1"\par
6) "2"\par
7) "3"\par
8) "4"\par
192.168.25.153:6379> \par
192.168.25.153:6379> lpop list1 \par
"d"\par
192.168.25.153:6379> lrange list1 0 -1\par
1) "c"\par
2) "b"\par
3) "a"\par
4) "1"\par
5) "2"\par
6) "3"\par
7) "4"\par
192.168.25.153:6379> rpop list1\par
"4"\par
192.168.25.153:6379> lrange list1 0 -1\par
1) "c"\par
2) "b"\par
3) "a"\par
4) "1"\par
5) "2"\par
6) "3"\par
192.168.25.153:6379> \par
\par
Set\f2\'a3\'ba\'d4\'aa\'cb\'d8\'ce\'de\'cb\'b3\'d0\'f2\'a3\'ac\'b2\'bb\'c4\'dc\'d6\'d8\'b8\'b4\f1\par
192.168.25.153:6379> sadd set1 a b c c c d\par
(integer) 4\par
192.168.25.153:6379> smembers set1\par
1) "b"\par
2) "c"\par
3) "d"\par
4) "a"\par
192.168.25.153:6379> srem set1 a\par
(integer) 1\par
192.168.25.153:6379> smembers set1\par
1) "b"\par
2) "c"\par
3) "d"\par
192.168.25.153:6379> \par
\f2\'bb\'b9\'d3\'d0\'bc\'af\'ba\'cf\'d4\'cb\'cb\'e3\'c3\'fc\'c1\'ee\'a3\'ac\'d7\'d4\'d1\'a7\'a1\'a3\f1\par
\par
SortedSet\f2\'a3\'a8\f1 zset\f2\'a3\'a9\'a3\'ba\'d3\'d0\'cb\'b3\'d0\'f2\'a3\'ac\'b2\'bb\'c4\'dc\'d6\'d8\'b8\'b4\f1\par
192.168.25.153:6379> zadd zset1 2 a 5 b 1 c 6 d\par
(integer) 4\par
192.168.25.153:6379> zrange zset1 0 -1\par
1) "c"\par
2) "a"\par
3) "b"\par
4) "d"\par
192.168.25.153:6379> zrem zset1 a\par
(integer) 1\par
192.168.25.153:6379> zrange zset1 0 -1\par
1) "c"\par
2) "b"\par
3) "d"\par
192.168.25.153:6379> zrevrange zset1 0 -1\par
1) "d"\par
2) "b"\par
3) "c"\par
192.168.25.153:6379> zrange zset1 0 -1 withscores\par
1) "c"\par
2) "1"\par
3) "b"\par
4) "5"\par
5) "d"\par
6) "6"\par
192.168.25.153:6379> zrevrange zset1 0 -1 withscores\par
1) "d"\par
2) "6"\par
3) "b"\par
4) "5"\par
5) "c"\par
6) "1"\par
192.168.25.153:6379> \par
\par

\pard\nowidctlpar\s2\fi-567\li567\qj\tx567\fs36 1.4.\tab Key\f2\'c3\'fc\'c1\'ee\f1\par

\pard\nowidctlpar\qj\f2\fs21\'c9\'e8\'d6\'c3\f1 key\f2\'b5\'c4\'b9\'fd\'c6\'da\'ca\'b1\'bc\'e4\'a1\'a3\f1\par
Expire key second\f2\'a3\'ba\'c9\'e8\'d6\'c3\f1 key\f2\'b5\'c4\'b9\'fd\'c6\'da\'ca\'b1\'bc\'e4\f1\par
Ttl key\f2\'a3\'ba\'b2\'e9\'bf\'b4\f1 key\f2\'b5\'c4\'d3\'d0\'d0\'a7\'c6\'da\f1\par
Persist key\f2\'a3\'ba\'c7\'e5\'b3\'fd\f1 key\f2\'b5\'c4\'b9\'fd\'c6\'da\'ca\'b1\'bc\'e4\'a1\'a3\f1 Key\f2\'b3\'d6\'be\'c3\'bb\'af\'a1\'a3\f1\par
\par
192.168.25.153:6379> expire Hello 100\par
(integer) 1\par
192.168.25.153:6379> ttl Hello\par
(integer) 77\par

\pard\nowidctlpar\s2\fi-567\li567\qj\tx567\fs36 1.5.\tab Redis\f2\'c9\'e8\'d6\'c3\'b9\'fd\'c6\'da\'cd\'a8\'d6\'aa\'bb\'fa\'d6\'c6\f1\par

\pard\nowidctlpar\qj\f2\fs21\'a2\'d9\'b7\'a2\'b2\'bc\f1 key\f2\'b9\'fd\'c6\'da\'cf\'fb\'cf\'a2\'cd\'a8\'b5\'c0\f1\par
\par
key\f2\'b5\'c4\'b9\'fd\'c6\'da\'bc\'e0\'cc\'fd\'a3\'ac\'c6\'e4\'ca\'b5\'be\'cd\'ca\'c7\'b7\'a2\'b2\'bc\'c1\'cb\'d2\'bb\'b8\'f6\'cf\'fb\'cf\'a2\'cd\'a8\'b5\'c0\'a3\'ac\'d2\'bb\'b5\'a9\'d3\'d0\f1 key\f2\'b9\'fd\'c6\'da\'c1\'cb\'a3\'ac\'be\'cd\'bb\'e1\'b0\'d1\'b8\'c3\f1 key\f2\'cd\'c6\'cb\'cd\'b3\'f6\'c8\'a5\'a1\'a3\'b5\'b1\'c8\'bb\'a3\'ac\'d4\'da\'b8\'c3\'cd\'a8\'b5\'c0\'b7\'a2\'b2\'bc\'d6\'ae\'c7\'b0\'a3\'ac\'ce\'d2\'c3\'c7\'be\'cd\'b1\'d8\'d0\'eb\'bd\'f8\'d0\'d0\'b6\'a9\'d4\'c4\'a1\'a3\f1\par
\par
\f2\'d5\'e2\'b8\'f6\f1 key\f2\'b9\'fd\'c6\'da\'b7\'a2\'b2\'bc\'b5\'c4\'cd\'a8\'b5\'c0\'a3\'ac\f1 redis\f2\'d3\'d0\'cc\'e1\'b9\'a9\'d2\'bb\'b8\'f6\'d7\'a8\'c3\'c5\'b4\'f2\'bf\'aa\'b5\'c4\'bf\'aa\'b9\'d8\'a3\'ac\'d4\'da\f1 redis.conf\f2\'c0\'ef\'bd\'f8\'d0\'d0\'c5\'e4\'d6\'c3\'a3\'ba\f1\par
\par
\f2\'a3\'a8\'b5\'b1\'c8\'bb\'a3\'ac\'ce\'d2\'c3\'c7\'d2\'b2\'bf\'c9\'d2\'d4\'d7\'d4\'bc\'ba\'b7\'a2\'b2\'bc\'c6\'e4\'cb\'fb\'cf\'fb\'cf\'a2\'cd\'a8\'b5\'c0\'a3\'a9\f1\par
\par
\f2\'c4\'ac\'c8\'cf\'ca\'c7\'b2\'bb\'b4\'f2\'bf\'aa\'a3\'a8\'b4\'f2\'bf\'aa\'b6\'d4\f1 CUP\f2\'d3\'d0\'cf\'fb\'ba\'c4\'a3\'a9\'a3\'ba\f1\par
\par
notify-keyspace-events ""\par
\f2\'b4\'f2\'bf\'aa\'ba\'f3\'a3\'ba\f1\par
\par
notify-keyspace-events "Ex"\par
\f2\'c8\'bb\'ba\'f3\'d6\'d8\'c6\'f4\f1 redis\f2\'b7\'fe\'ce\'f1\'a3\'ac\'be\'cd\'bf\'c9\'d2\'d4\'c9\'fa\'d0\'a7\'a1\'a3\f1\par
\par
\f2\'b4\'f2\'bf\'aa\'d5\'e2\'b8\'f6\f1 key\f2\'b9\'fd\'c6\'da\'b7\'a2\'b2\'bc\'b5\'c4\'cf\'fb\'cf\'a2\'cd\'a8\'b5\'c0\'ba\'f3\'a3\'ac\'ce\'d2\'c3\'c7\'be\'cd\'b1\'e0\'d0\'b4\'b3\'cc\'d0\'f2\'b8\'c3\'cd\'a8\'b5\'c0\'bd\'f8\'d0\'d0\'b6\'a9\'d4\'c4\f1\par
\par
\par
\f2\'a2\'da\'b6\'a9\'d4\'c4\f1 key\f2\'b9\'fd\'c6\'da\'cf\'fb\'cf\'a2\'cd\'a8\'b5\'c0\f1\par
\par
\f2\'bb\'f9\'d3\'da\f1 springBoot\f2\'a3\'ac\'d2\'bb\'c6\'f4\'b6\'af\'be\'cd\'bd\'f8\'d0\'d0\'b6\'a9\'d4\'c4\f1 key\f2\'b9\'fd\'c6\'da\'cf\'fb\'cf\'a2\'cd\'a8\'b5\'c0\'a3\'ac\'d0\'c2\'bd\'a8\'d2\'bb\'b8\'f6\'c0\'e0\'a3\'ac\'b2\'a2\'d7\'a2\'bd\'e2\f1 @Component\f2\'a3\'ac\'b2\'a2\'c7\'d2\'ca\'b5\'cf\'d6\f1 CommandLineRunner\f2\'bd\'d3\'bf\'da\'a3\'ac\'d5\'e2\'d1\'f9\'b5\'b1\f1 spring\f2\'c8\'dd\'c6\'f7\'bc\'d3\'d4\'d8\'cd\'ea\'d6\'ae\'ba\'f3\'a3\'ac\'be\'cd\'bb\'e1\'c2\'ed\'c9\'cf\'d6\'b4\'d0\'d0\'b8\'c3\'d7\'e9\'bc\'fe\f1\par
\par
package com.appscomm.device.common;\par
 \par
 \par
import org.springframework.beans.factory.annotation.Autowired;\par
import org.springframework.boot.CommandLineRunner;\par
import org.springframework.dao.DataAccessException;\par
import org.springframework.data.redis.connection.Message;\par
import org.springframework.data.redis.connection.MessageListener;\par
import org.springframework.data.redis.connection.RedisConnection;\par
import org.springframework.data.redis.connection.jedis.JedisConnection;\par
import org.springframework.data.redis.connection.jedis.JedisConnectionFactory;\par
import org.springframework.data.redis.core.RedisCallback;\par
import org.springframework.data.redis.core.RedisTemplate;\par
import org.springframework.stereotype.Component;\par
 \par
 \par
 \par
@Component\par
public class RedisSubscribeThread implements CommandLineRunner \{\par
 \par
    @Autowired\par
    private RedisTemplate<String, String> redisTemplate;\par
 \par
    @Override\par
    public void run(String... strings) throws Exception \{\par
        redisTemplate.execute(new RedisCallback() \{\par
            @Override\par
            public Object doInRedis(RedisConnection connection) throws DataAccessException \{\par
                connection.pSubscribe(new MessageListener() \{\par
                    @Override\par
                    public void onMessage(Message message, byte[] pattern) \{\par
 \par
                     System.out.println("message:"+message);                \par
 \par
                    //\f2\'d2\'b5\'ce\'f1\'b4\'a6\'c0\'ed\f1\par
 \par
 \par
                    \}\par
                \},"*@0*".getBytes());\par
                return null;\par
            \}\par
        \});\par
    \}\par
 \par
\}\par
\par
\f2\'b5\'d8\'d6\'b7\'d6\'b8\'cf\'f2\'a3\'ba{\f1{\field{\*\fldinst{HYPERLINK https://blog.csdn.net/Ouyzc/article/details/82752303 }}{\fldrslt{https://blog.csdn.net/Ouyzc/article/details/82752303\ul0\cf0}}}}\f1\fs21\par
\par

\pard\nowidctlpar\s2\fi-567\li567\qj\tx567\fs36 1.6.\tab Redis\f2\'c9\'e8\'d6\'c3\'ba\'f3\'cc\'a8\'c6\'f4\'b6\'af\f1\par

\pard\nowidctlpar\qj\fs21\par

\pard\cbpat8\widctlpar\sa217\sl353\slmult0\cf2\kerning0\f4\fs22 1\'a1\'a2\'c9\'e8\'d6\'c3redis.conf\'d6\'d0daemonize\'ce\'aayes,\'c8\'b7\'b1\'a3\'ca\'d8\'bb\'a4\'bd\'f8\'b3\'cc\'bf\'aa\'c6\'f4\'a1\'a3\par
2\'a1\'a2\'b1\'e0\'d0\'b4\'bf\'aa\'bb\'fa\'d7\'d4\'c6\'f4\'b6\'af\'bd\'c5\'b1\'be\par

\pard\widctlpar\sa326\sl299\slmult0\tx916\tx1832\tx2748\tx3664\tx4580\tx5496\tx6412\tx7328\tx8244\tx9160\tx10076\tx10992\tx11908\tx12824\tx13740\tx14656\cf3\highlight4\f5\fs19 vi /etc/init\f4 .d\f5 /redis\highlight0\par

\pard\widctlpar\li720\f6\fs18 #!/bin/bash\~\~\f4\par
\f6 #chkconfig:\~2345\~80\~90\~\~\par
#\~Simple\~Redis\~init.d\~script\~conceived\~to\~work\~on\~Linux\~systems\~\~\par
#\~as\~it\~does\~use\~of\~the\~/proc\~filesystem.\~\~\par

\pard\widctlpar\cf2\highlight4\f5\fs19\par
PATH=/usr/local/redis/bin:/sbin:/usr/bin:/bin   \par
REDISPORT=\cf0\highlight0\f4 6379\cf2\highlight4\f5   \par
\cf0\highlight0\i\f4 # \'d7\'d4\'bc\'ba\'b5\'c4redis-server\'c2\'b7\'be\'b6(\'d0\'e8\'d2\'aa\'d7\'d4\'bc\'ba\'b8\'fc\'b8\'c4)\cf2\highlight4\i0\f5\par
EXEC=/usr/local/redis/bin/redis-server   \par
REDIS_CLI=/usr/local/redis/bin/redis-cli   \par
\par
PIDFILE=/var/run/redis.pid\par
\cf0\highlight0\i\f4 # \'d7\'d4\'bc\'ba\'b5\'c4redis.conf \'c2\'b7\'be\'b6(\'d0\'e8\'d2\'aa\'d7\'d4\'bc\'ba\'b8\'fc\'b8\'c4)\cf2\highlight4\i0\f5\par
CONF=\cf0\highlight0\f4 "/usr/local/redis/bin/redis.conf"\cf2\highlight4\f5   \par
AUTH=\cf0\highlight0\f4 ""\cf2\highlight4\f5   \par
\par
\cf0\highlight0\f4 case\cf2\highlight4\f5  \cf0\highlight0\f4 "$1"\cf2\highlight4\f5  \cf0\highlight0\f4 in\cf2\highlight4\f5    \par
        start)   \par
                \cf0\highlight0\f4 if\cf2\highlight4\f5  [ \highlight0\f4 -f\highlight4\f5  \cf0\highlight0\f4 $PIDFILE\cf2\highlight4\f5  ]   \par
                \cf0\highlight0\f4 then\cf2\highlight4\f5    \par
                        \highlight0\f4 echo\highlight4\f5  \cf0\highlight0\f4 "$PIDFILE exists, process is already running or crashed."\cf2\highlight4\f5   \par
                \cf0\highlight0\f4 else\cf2\highlight4\f5   \par
                        \highlight0\f4 echo\highlight4\f5  \cf0\highlight0\f4 "Starting Redis server..."\cf2\highlight4\f5   \par
                        \cf0\highlight0\f4 $EXEC\cf2\highlight4\f5  \cf0\highlight0\f4 $CONF\cf2\highlight4\f5    \par
                \cf0\highlight0\f4 fi\cf2\highlight4\f5    \par
                \cf0\highlight0\f4 if\cf2\highlight4\f5  [ \cf0\highlight0\f4 "$?"\cf2\highlight4\f5 =\cf0\highlight0\f4 "0"\cf2\highlight4\f5  ]   \par
                \cf0\highlight0\f4 then\cf2\highlight4\f5    \par
                        \highlight0\f4 echo\highlight4\f5  \cf0\highlight0\f4 "Redis is running..."\cf2\highlight4\f5   \par
                \cf0\highlight0\f4 fi\cf2\highlight4\f5    \par
                ;;   \par
        stop)   \par
                \cf0\highlight0\f4 if\cf2\highlight4\f5  [ ! \highlight0\f4 -f\highlight4\f5  \cf0\highlight0\f4 $PIDFILE\cf2\highlight4\f5  ]   \par
                \cf0\highlight0\f4 then\cf2\highlight4\f5    \par
                        \highlight0\f4 echo\highlight4\f5  \cf0\highlight0\f4 "$PIDFILE exists, process is not running."\cf2\highlight4\f5   \par
                \cf0\highlight0\f4 else\cf2\highlight4\f5   \par
                        PID=$(cat \cf0\highlight0\f4 $PIDFILE\cf2\highlight4\f5 )   \par
                        \highlight0\f4 echo\highlight4\f5  \cf0\highlight0\f4 "Stopping..."\cf2\highlight4\f5   \par
                       \cf0\highlight0\f4 $REDIS_CLI\cf2\highlight4\f5  -p \cf0\highlight0\f4 $REDISPORT\cf2\highlight4\f5   SHUTDOWN    \par
                        sleep \cf0\highlight0\f4 2\cf2\highlight4\f5   \par
                       \cf0\highlight0\f4 while\cf2\highlight4\f5  [ -x \cf0\highlight0\f4 $PIDFILE\cf2\highlight4\f5  ]   \par
                       \cf0\highlight0\f4 do\cf2\highlight4\f5   \par
                                \highlight0\f4 echo\highlight4\f5  \cf0\highlight0\f4 "Waiting for Redis to shutdown..."\cf2\highlight4\f5   \par
                               sleep \cf0\highlight0\f4 1\cf2\highlight4\f5   \par
                        \cf0\highlight0\f4 done\cf2\highlight4\f5    \par
                        \highlight0\f4 echo\highlight4\f5  \cf0\highlight0\f4 "Redis stopped"\cf2\highlight4\f5   \par
                \cf0\highlight0\f4 fi\cf2\highlight4\f5    \par
                ;;   \par
        restart|force-reload)   \par
                \cf0\highlight0\f4 $\{0\}\cf2\highlight4\f5  stop   \par
                \cf0\highlight0\f4 $\{0\}\cf2\highlight4\f5  start   \par
                ;;   \par
        *)   \par
               \highlight0\f4 echo\highlight4\f5  \cf0\highlight0\f4 "Usage: /etc/init.d/redis \{start|stop|restart|force-reload\}"\cf2\highlight4\f5  >&\cf0\highlight0\f4 2\cf2\highlight4\f5   \par
                \cf0\highlight0\f4 exit\cf2\highlight4\f5  \cf0\highlight0\f4 1\cf2\highlight4\f5   \par

\pard\nowidctlpar\qj\cf0\highlight0\f4 esac\par
\par

\pard\cbpat8\widctlpar\sa240\sl390\slmult0\cf2\fs24 3\'a1\'a2\'d0\'b4\'cd\'ea\'ba\'f3\'b1\'a3\'b4\'e6\'cd\'cb\'b3\'f6VI\par
4\'a1\'a2\'c9\'e8\'d6\'c3\'c8\'a8\'cf\'de\par

\pard\widctlpar\sa360\sl330\slmult0\tx916\tx1832\tx2748\tx3664\tx4580\tx5496\tx6412\tx7328\tx8244\tx9160\tx10076\tx10992\tx11908\tx12824\tx13740\tx14656\cf3\highlight4\fs21 cd\f5  /etc/init.d/\par
\par
chmod \f4 755\f5  redis\highlight0\par

\pard\cbpat8\widctlpar\sa217\sl353\slmult0\cf2\f4\fs22 5\'a1\'a2\'c6\'f4\'b6\'af\'b2\'e2\'ca\'d4\par

\pard\widctlpar\sa326\sl299\slmult0\tx916\tx1832\tx2748\tx3664\tx4580\tx5496\tx6412\tx7328\tx8244\tx9160\tx10076\tx10992\tx11908\tx12824\tx13740\tx14656\cf3\highlight4\f5\fs19 /etc/init.d/redis \f4 start\highlight0\f5\par

\pard\cbpat8\widctlpar\sa217\sl353\slmult0\cf2\f4\fs22\'c9\'e8\'d6\'c3\'bf\'aa\'bb\'fa\'d7\'d4\'c6\'f4\'b6\'af\par

\pard\widctlpar\sa326\sl299\slmult0\tx916\tx1832\tx2748\tx3664\tx4580\tx5496\tx6412\tx7328\tx8244\tx9160\tx10076\tx10992\tx11908\tx12824\tx13740\tx14656\cf3\highlight4\fs19 chkconfig redis on\highlight0\f5\par

\pard\nowidctlpar\qj\cf0\kerning2\f2\fs21\'ba\'f3\'c3\'e6\'b3\'f6\'cf\'d6\'c1\'cb\'b7\'fe\'ce\'f1\f1 redis\f2\'b2\'bb\'d6\'a7\'b3\'d6\f1 checkconfig\par
\f2\'b2\'e9\'c1\'cb\'b0\'d9\'b6\'c8\'a3\'ac\'b0\'d1\'bf\'aa\'cd\'b7\'cc\'e6\'bb\'bb\'b3\'c9\'be\'cd\'d0\'d0\'c1\'cb\f1\par

\pard\brdrl\brdrs\brdrw15\brsp160 \brdrt\brdrs\brdrw15\brsp40 \brdrr\brdrs\brdrw15 \brdrb\brdrs\brdrw15\brsp40 {\pntext\f4 1.\tab}{\*\pn\pnlvlbody\pnf4\pnindent510\pnstart1\pndec{\pntxta.}}
\widctlpar\fi-360\li570\sl270\slmult0\cf3\kerning0\f6\fs18 #!/bin/bash\~\~\cf5\f4\par
{\pntext\f4 2.\tab}\cf3\f6 #chkconfig:\~\cf6\f4 2345\cf3\f6\~\cf6\f4 80\cf3\f6\~\cf6\f4 90\cf3\f6\~\~\cf5\f4\par
{\pntext\f4 3.\tab}\cf3\f6 #\~Simple\~Redis\~init.d\~script\~conceived\~to\~work\~on\~Linux\~systems\~\~\cf5\f4\par
{\pntext\f4 4.\tab}\cf3\f6 #\~as\~it\~does\~use\~of\~the\~/proc\~filesystem.\~\~\cf5\f4\par

\pard\nowidctlpar\qj\cf0\kerning2\f1\fs21\par
\par

\pard\keep\keepn\nowidctlpar\s1\fi-425\li425\sb340\sa330\sl576\slmult1\qj\tx425\kerning44\b\f0\fs44 2.\tab Redis\f2\'b5\'c4\'b3\'d6\'be\'c3\'bb\'af\'b7\'bd\'b0\'b8\f0\par

\pard\nowidctlpar\qj\kerning2\b0\f1\fs21 Redis\f2\'b5\'c4\'cb\'f9\'d3\'d0\'ca\'fd\'be\'dd\'b6\'bc\'ca\'c7\'b1\'a3\'b4\'e6\'b5\'bd\'c4\'da\'b4\'e6\'d6\'d0\'b5\'c4\'a1\'a3\f1\par
Rdb\f2\'a3\'ba\'bf\'ec\'d5\'d5\'d0\'ce\'ca\'bd\'a3\'ac\'b6\'a8\'c6\'da\'b0\'d1\'c4\'da\'b4\'e6\'d6\'d0\'b5\'b1\'c7\'b0\'ca\'b1\'bf\'cc\'b5\'c4\'ca\'fd\'be\'dd\'b1\'a3\'b4\'e6\'b5\'bd\'b4\'c5\'c5\'cc\'a1\'a3\f1 Redis\f2\'c4\'ac\'c8\'cf\'d6\'a7\'b3\'d6\'b5\'c4\'b3\'d6\'be\'c3\'bb\'af\'b7\'bd\'b0\'b8\'a1\'a3\f1\par
aof\f2\'d0\'ce\'ca\'bd\'a3\'ba\f1 append only file\f2\'a1\'a3\'b0\'d1\'cb\'f9\'d3\'d0\'b6\'d4\f1 redis\f2\'ca\'fd\'be\'dd\'bf\'e2\'b2\'d9\'d7\'f7\'b5\'c4\'c3\'fc\'c1\'ee\'a3\'ac\'d4\'f6\'c9\'be\'b8\'c4\'b2\'d9\'d7\'f7\'b5\'c4\'c3\'fc\'c1\'ee\'a1\'a3\'b1\'a3\'b4\'e6\'b5\'bd\'ce\'c4\'bc\'fe\'d6\'d0\'a1\'a3\'ca\'fd\'be\'dd\'bf\'e2\'bb\'d6\'b8\'b4\'ca\'b1\'b0\'d1\'cb\'f9\'d3\'d0\'b5\'c4\'c3\'fc\'c1\'ee\'d6\'b4\'d0\'d0\'d2\'bb\'b1\'e9\'bc\'b4\'bf\'c9\'a1\'a3\f1\par
\par
\f2\'d4\'da\f1 redis.conf\f2\'c5\'e4\'d6\'c3\'ce\'c4\'bc\'fe\'d6\'d0\'c5\'e4\'d6\'c3\'a1\'a3\f1\par
Rdb\f2\'a3\'ba\f1\par
\kerning0\f3\fs22\lang0{\pict{\*\picprop{\sp{\sn wzDescription}{\sv Image}}{\sp{\sn posv}{\sv 1}}
}\pngblip\picw14444\pich7407\picwgoal8189\pichgoal4199 
89504e470d0a1a0a0000000d49484452000003cf000001f408020000008ccb88d3000000017352
474200aece1ce90000000467414d410000b18f0bfc6105000000097048597300000ec400000ec4
01952b0e1b0000797549444154785eeddd3b9aeb389ae07d9e5942af20bde927182b18ebeca09d
a32837dbcc15b41992d92b28ef9b743314c6d40ed29a1584f2a9f17205b585fc00bc24883b40f1
2229e2ff4b3e55272488c48de42b0824bb5f7ef9a503000000b081ff31fc3f00000080b5116d03
0000005b21da06000000b642b40d0000006c85681b000000d80ad136000000b015a26d00000060
2b44db000000c05688b601000080ad106d030000005b21da06000000b642b40d0000006c85681b
000000d80ad136000000b0955cb4dd771f7f75c75efff3f8d1fdf5665e749140904090407c9104
f8521ea24f924090409040ec90004d72d1f693aae1ee7231ffecbbf3d9bce8228120812081f822
09f0a53c449f248120812081d821019a64a2edc341d56ef787fa57afaabafb43ffcb4302410241
02f1451294e9f18fbfa6e54dadcd3a9817fdd191fea85f745309598ff77145d6e02f619a863c04
1f91f45eaab7e9e37f7da89a1899919ee9ad68793bd612a8cda44aa1175b33ed1515e5274cb0d8
43f4491208120812881d12a04d26daee75a5aa1af6bed6b8482048204820be48820215b6beaacf
3854d82abf424e0ed12bb1c3b01e7dacaf519bf8380eff569af250f41684e326a26dc8c8da6a15
a5bf24b8df048cb7b57fea7d883e490241024102b14302b4c944dbf6f7825ed7aeaaea10090409
0409c41749902521f2b9fbf66d5a5eccaa02afbfe90377810ca89cd591fd900873cf2fce265ef4
2bfd8f7185cd79c851a1b9dee2a57bf63f3e44b1ceebf6ad17f795632d817ac566cf64fe72f2fe
74152a4ae553be549c9ec78fabe5596570650fd12749204820482076488046bffcf2cbf02ff1e6
ff28e92e327a440212c8420259be54820a33ffa1945212f85344921324544ed47ae4adea3c109d
6d3bc4db9687600dee4c12a984203f92201e6956216f9cd8554990cb6db5a2c60924854d2fb7bc
c3908004b2904096cf9400b384d1b6a28fe972ea3207f4e0b4a49040904090407c910465c3015a
d6103341a48a592599ac5b6f31881ac76492076f6d51ac2ce1ac3bc5b9250f41b9a668dbbc1b5f
772f998c6b63d368bb5051f2ef1dce79d5fe400241024102f14512a0596a26c9933f4d477e4470
9140904090407c9104652f3293c11c9a0be1e0e9a4fff735f3eef155ff64a9a7915cba93ca40df
1d54561c43846d163901bc3873305af2e0ae412dc13cef4bf473a9cc567cf293ed205751ba99ba
eeddb68e7c499045ce8e2bb9872e470241024102710f09d02c156d1f0ec3c926374d8704820482
04e28b24a818a735cb61b97fd5f15f3c22723976a78b7e37711560dffde8bbcbbb5a9326c7f71f
f9311599f4ec9d05daf2f0104a15b58b87e8932410241024103b24403b6f264930dee32d66bc84
0424181612c8f295125c41ff1069d630c4bae30409fbefbfde86343618b61ff1169b01f3a959a1
73320fc11aee762689fd775051f2eff8837ae6c9b58d15d8a147918004c34202591e2701e60ae7
6deb83b854e566137d4820482048201e22c115e4a8ed068e769856de926b01eda68659d7d13264
c6ac616ec6e23c046bb8cfab244b15651ac84d23568cb69587e8932410241024103b24c02c61b4
ad4f2a32ae630ef771f59240904090407c910415e6535efc670ed3d3aa8204e3bb4182f0b06e5e
7433563aeeb7e52158832ef8984042dbe134630caf48067cfb44db898ab2b9f23fbe6eb47d0f5d
8e0482048204e21e12608e68deb6bdb7e241556d6a9a0e0904090409c41749d0e2551da3c7d050
22bfcbc99f576d5dbabf99ab002dd9aebe32d275d67397d5c15ebdd968461e22e71793d2097025
34772fc45cca9cbdf4624e6632b3dcfe99105594a2f2a9abc5fdf8da67c487e893241024102410
3b24c01c41b46dce67f264cefe69ba5069420241024102f14512549d134f57393d77cff1d8ede8
72f4826075584f6ef7fcaeff571ff4abe6e721f6323e9566602ebb745fd85f5051e2f89c7820ce
f934bfe1921ea24f924090409040ec90003325eeb70d000000600d9927b703000000588c681b00
0000d80ad136000000b015a26d000000602bb968dbdcfd4aeef63add7311000000c00cb968fbc9
dca1d6dcf1c5de7311000000c01c99687bba9979af02efe19e8b00000000e6c844dbbd0eb1cdcd
cc9d416e000000007364a26d3b7ba4d7b1364fec04000000ae113e4bf2edafeeafccf231e7d1c7
000000c097178d6dbf7ceb9e4f7a3cfbf95bf7ed594f2639bf74dfd4bfd5eb44db000000c00ca9
99244ffea46d6e48020000005c25156d1f0eddc5ccd466d236000000b084376ffbf016ced59e96
0f3dce0d000000a0993fb67d7ec94eda963f01000000348b66921c7e30691b0000005845146ddb
3b6d4f8f9304000000708d20da3ea8ff86e7b4f74fdde59dd923000000c0f5c2a7db0000000058
49ea0e8000000000d640b40d0000006c85681b000000d80ad176d2413fd0e7ed30fc8559fae3aa
b5475b00008007968bb6fbeee3afee689e1e79fce8fe7a332f020b0c4f2aa52f0100802f24176d
9b47db5cccfdffec1db801000000cc9189b6a747dbf42af01eeec0dd4e0f87ff352df7390d60e5
090f73990912def2a1bfe14ce2047fe9bba13faef34bf7ed5bf7ed65f8130000e00bc844dbbd0e
b1a7e7b7cb207723156abf7a61a39e42209352506266ef94a3ffb7070fb8010000be984cb46d67
8ff43ad69ef3fcf68309b5cf6614735c5ea2892832ae6c1737c494d9bd71d029afbb2fabd0d3ae
6156342f1ffc78d5ff1e2613cb128c2e1bee56e248f7ea3c8861b8d7a925951f772b6e8293f9ce
a37f7698c504f136935ec53a1720968b59653ffe711c5eb1dc352713687e26d552a84c59619cc0
762abeda010080fb113e4b32888ddc251d27054c00574e1984dab24c1192045ec1b574e6c569b5
5170e6ada1265b461b6d4b187a8cb6e286e3cbf2e046ba96f74d234a70cdd417b39270b175db52
ccaa543da8c5e6b31e6da7d63025f3eb41262925eb80681b0000dca1c493db75d422f1960983e6
857736baca476c6afdee3ae3c1ec38a29240ca46519260fa88c494336f76510a5e6d90ea9442ca
65932fcd831f440edc95040924249d15078f798ebfa50c35d950cc2a69be2038564ba262cd5b71
b49d6c08fda38a70ea41b6950ba6653d8504000000fb4b44db3aa67102bef6c06be00f5526c632
7d89602b0acb7408680359b3fe60b53af69d1989d6a36d3f74f642bde5797082c889549d53f9de
e2e7a72e550a29f590f36a311be8a6f14b9dad58b3b9447f184b9adea87957ad4d564b240d0000
1e4a6adef6e1d05dcc4cedd993b6c5a57b36f38c65b676ff3a444b9e31c0528bcc9ff69cf567fb
1f630c7750ff39772134176eca6aeda2278b9bdba7aca874dfc3bdf2e03964be1b1449535a97b3
bef8555f053b5a747b4729af5c507bb5f33067fdd5fc5c90fec672d0fde4f4dc1d176d09000060
677eb42de39a2aa2933852c7c176a07ae6c8b1f26262eee793feb75ab30d1465ec5c454e72f19f
2408e810b0ef5ecd67e47684a72541e1a3903bc038f1b17b95a4aa00557589b1e1c7e7dd1cd01d
e01fa92ea08aafc271c6b60100c043f1a36d15f4e8d85706a79ff580e514ed993faf70390e2397
c34c5c3340ab565b1ea43c9ff4e6749c6d62eecb7bb8f5cb69cc98b3ec1c90af9e07b9dfc81f99
9a51df5ed4caa721ff36ee30b6d21fc280fe8e8cb7b2d175687ed0b0d4b7af17d30309b80100c0
438966921c7e7877da9e3dcdc04c11f1e2a17188dabd69f7741bbbbefbcdcc24790a42a84bf7ae
d21fbaa3890e4fee80aecc33790da755f4472f3e6b34e5649655f3208e1f666d85517c3f00ad33
99549f9986c3c7da7e9fdbac396333d97a503590981a5474780bab31fd7d437d091c03ee643dc8
c4eeb0fb010000dc54e20e8012fae8f91ef3678fa83848229e607103be616a4a6af1a228bbaaf8
eac0cc56924158562a27c31accfa83105057881bc92dcc43f5e39904f36692245762ebb3a59835
36c6b5cb9b5943b05acd6c2ecebf6c315c72991c4b14af9e681b0000dc9f606cdb8c9eca73dafb
a7c4fc8dba7362cec9e9b97bb631d6384229643246fcf81b4d8666d5c7e389dd66ca41f021b595
7923b62a274b9e22be4a1e5ca91506f4549f59d176d41c7a6ad0aacf4ebf1cbd99f7aa064e33a7
a9a82c051d40f78a5c26cfc3e6d4d742a26a000070ff12770004000000b086d41d0001000000ac
81681b000000d80ad136000000b015a26d000000602bb968dbdc1d4feef970fc48dd830f000000
40452eda9647889b5bc73df5f39f710300000020176deb272c5e3a7ddfe45e05dec31db8010000
00cc9189b67b1d629ba7a23883dc00000000e6c844db76f648af636d33c80d00000060a6f05992
6f7f757f65968f59cf0c07000000beba686cfbe55bf77cd2e3d9cfdfba6fcf7a32c9f9a5fba6fe
ad5e27da060000006648cd2479f2276d734312000000e02aa968fb70e82e66a63693b601000080
25bc79db87b770aef6b47ce8716e00000000cdfcb1edf34b76d2b6fc09000000a0593493e4f083
49db000000c02aa268dbde697b7a9c24000000806b04d1f641fd373ca7bd7fea2eefcc1e010000
00ae173edd06000000c04a52770004000000b006a26d000000602b44db000000c05688b6e1eb8f
fa61466f87e1cf077078b40c0300802f24176df7ddc75fddd13c3df2f8d1fdf5665e0400000030
432eda368fb6b998fbffd93b70030000009823136d4f8fb6e955e03ddc811b000000c01c9968bb
d721f6f4fc7619e406000000304726dab6b3477a1d6bdfe2f9ed66e2f85fce2293c82db998cf2e
ee457287b7f01521afbb2fbf396b08d67f2595ed0ffdfd64502b8552cd839e37efa409e7d0fb9b
f04aed5c3ee86e25aa98e9dd8fe3f08a275f0ad50a5b5d9e18d464b51e8c42310b1de68a8ad25b
4f5d9de97e3cd19a37a94900007053e1b324dd702158d2a1d816a2a024d87a1039c9320537f2f1
54543aad24b58964b0db6ea83a1b23d64a51cf432a815aa63426e00b175b7009078fd14a8adf07
649922bf62296c43ac1b29b6d4a45a867a682866a5c36c5651d5d6dcba260100c0cd259edcae4f
fc126798f860ffd3bf441ec176f528fb482570df8d07b3651cd45d81acd3463f9260fa8884ada9
e1d216d3b06b14e1154a51cdc3b05a37e6530e5329242a8dbf42b86168b006f9c8b44d5375d31a
c68fd85cb5b4857c442d5e707995644d56eaa1a198950ed3b006c943a1a2aaadb9734d0200803b
9188b6752c2251828918fcf060176328d3187324e218b386293692e0c9863e262a75df5574b414
c4730d246ed34b1ca9974b51cd8384ce852c45f19c225531ac369540326cb3a4abc5df4458998d
6d312653cb751d265b9357d54350cc40ba8c8535a4f2e0ada4a547ed55930000e0ae24a26d1581
49dca0e3894294b3a529f6524b320f4e50224b306ae8c59126711c41c64b7b7c637318c458ae52
29aa7930090a2b4f2790b85002c7a0d4462288f4a3cc30121d3f322ce5fe202bac26f3556ab2ad
1e4ac5142699bb04fda1b486541ebc8a8a566e1777ad5bd7240000b83ffe5592120da8f8a07fd5
fff878bdd959fffcd27dfbd67d7b317f4441a1cee75b777a3669be75cfa7e17597becab3ef5e4d
b02337343cad78d7f043189c25954bf128ae29854ad658d2b69a5ca8a5c3ec60db9a040000f7c8
8fb65534a003914bf7ac6282677d07c0213e18ffdcdb79d8ba8e930fe330a189cf54c68ec50c9d
4f3ac33ace3631f7e53dccffe53416cd595a03f231632fe7e19b49296c4a96c228e5c1dc81b1ff
a1b25fa2efd5e8e80f3afd658b9bc8e44ba1c9e0aef94af622059198b2aa5a936df550d2d6614a
240f7e553ff97f2aad3d6aa39a040000f728ba03e0e18777a7ed9b3c45f2f0168e77fe11c5493a
8c167df7dbabfeffa7201cbb74efea5387ee6802d0933b0de0ac031d15db055be98f51e85323df
464e6643c12f00955254f320f9efc31be12943d9cd1a54ea6986c35815ef8dad365691cd83daba
fe41c3516d0b99502121b20c1e5fd765b23559ad8736f50e532037c1742a2aac96861eb55b4d02
0080bb92b803a0c4042a38d879f688a537adc28e60b1439ef2137c66f1e2193b9b361e78b66ff9
8b1f0ecda3678aab65acb44a29946a1e32259d82b6e41aec26ccbb418427b9b2139a8708cf59de
4c02fba97229ecc783ad2c14d464a51eaac5ac7698352a2add164e6bdea4260100c0cdf9d1b689
1824c2387e142f4ddb58109a843971e22779cba60f621589db6ccc1418a2ba71c9259b4165ccf9
8a52298551cd4318a505df1cfc50d28bd51a8248c58d23d5ebf2a7fba9422954e2ada243bf2695
6c3db414b3dc6156aa28a5dc9ab7a94900007053897b9200a88ac37100008048e6c9ed003cce43
853499c37de9cefedc6b0000001fd136d0e6d53c2d7258cc3c16b9ef0d0000401ed136d0e26cee
97e2383debbb1602000094316f1b000000d8486e6cdbdcc34126aa1e3fa2fb6000000000a8cb45
dbe6d13617f3d3f9537f9b67dc000000000f2e136deb07efc9f3f37a1578777f6cf12470000000
e093cb44dbbd0eb1cdfd169c416e000000007364a26d3b7ba4d7b1b619e4060000003053784f92
e0d1d3ee927cf038000000808c686cfbe55bf77cd2e3d9cfdfba6fcf7a32c9f9a5fba6fead5e27
da060000006648cd2479f2276d734312000000e02aa968fb70e82e66a63693b60100008025bc79
db87b770aef6b47ce8716e00000000cdfcb1edf34b76d2b6fc09000000a0593493e4f08349db00
0000c02aa268dbde697b7a9c24000000806b04d1f641fd373ca7bd7fea2eefcc1e01000000ae17
3edd06000000c04a52770004000000b006a26d000000602b44db000000c0563e69b4fd163c9ae7
6d78ddaa26f8120ebaec6f87e1af2f2268faa6e2ef50519f631368f4806d71cd8ef3b0fae30394
71e54c727c0036948bb6fbeee3afee689e1e79fcb8df607478f8e5d78c9511a9f6071531046793
271e917a23ecbc0f841d073be3f880cf25176d9b47db5cccfdffec1db81fc88b3cff32ff08cc6a
027c42e60697aabdf5a352c7e5f928ef01c860c701804532d1f6f4689b5e05dec31db8f7f196ff
312b7e6b78b0fccbf0276237fe49d4fc3ae92d1ffa8bdc244e108da2b52bf787de6cf87cbad9f7
ab1ddae2217e0117ecbc8fe2e63b0ed6c2f101b8914cb4ddeb10db1c5b9d41eedd147ea3dc33ee
c726cc24a5f2e13efed91a0000e03165a26d3b7b448f6aecfbfcf63f2e26d68f99517689fb5534
2683a0b27cdcea374d1338ba399199ee960c24d8c50d3165525a1c74caebeecb6e6183f597c907
3f5ef5bf873970b204a3cb86bb9538d2bd3a0f6218a530cb8be9572a3fee56dc0427d3c4fad795
6695fe300e9f27aa626e719c164f7c61f0fb839b60c5b6c8597113eebb5734b732ade16da87f5b
1beecad5123496e47cd17ee16cae5cccacea1afc1269e6155b16d9f155aef4452ffeaac2a2957b
54a198e3564af96c91efb45228b52cdd716ac749a5504c2135392dc174de5a295a6ac9be9b3ea1
3494a2ac703a582d9379f2418e0fed550dac2b7c9664d0d7dd65eeee7d1dbddb8cfbbfec42c3ae
627612d925ca3ba4470e91852b2daa0972a2836f9093e0d82acbb4db27b76b5e9c5692da44fbd1
2ddb94f6f02ac79d63b415f7f8bb2c0feea1cdf28e98510237866854e90f6613b9a5a92c998af2
3e9bdccad8beebb445d15d34b7925a835a6c83561a4b3ebe64bf585c93f5354802b78b9a576c0e
a50f7fd800f1a33b9a3e2fffd62bc96cc2abea5a5b0c7b4ab49219bb8ec946b8d8ca4fbe3b2ead
bd22550aafd16bc54c26504bd0e2e1e297e28a6eaf96a989aba5a8a99c0e56c96411c787414b31
810d249edcae8f0bd2f34caf6ddc99d7224725d9a6ec78b2174db972993da774d44bee9cae6a82
8ce154e7578e4c70142a81fb6efca55c466bdc15c83aed71c11d18d34c61e7663599cf81ac502d
4ec54a9ddbe44bf32087b660ebee4a8204d21c571ff8ccda72fda1541565926167cdb22ab71edc
beaa8d477cf754b4b02d5adcb8b9c7354cf5306e349125f356dc584bf78b86625654d760127825
f2cb32740f935e767c5995ceb9ac73dc44a14755dbc26e65caa749d35accb64eab943a554df2b3
ee71b25a4c49e0b6857698325929c558d5d9d654494c1b4d6b183f6273552d45955a83fbf1f074
b046265b949ab2210fd5c6aa92353495c2bc35a51cc91adce452a8fd8e0fc05512d1b6deaba56b
9a7eb97717341bd57bce78d094cc4cb9726576c889aca47038a826c81977dae0cc949338cc4599
d7fbbccd89c95850347d1c09ce3a35f5c3ab5f7639a60f855a9e07b38970eb6e9d8fd5382d57b4
851555a9ab541565a9d57a07e8544dcae6dc4f2d6a8b36376e6e69593f7d364bb9c68a5e9fb75f
2cafc9ea1a4c02af447e9edd22cb07a77f4b3ea3322a5e8f6a680bd94a90cf1952c5947506db2d
75aa2ad94aaef2abc54cf5284fb514a904417fd035ef6f222c72b914f3a5d7bf30930d4a1fa9e6
a1a14f56a45a339b25939f60735af4fadec707e01aa979db8743773133b5f79fb4adc9d599ca53
d75fba97d370a566ff34e4ea5e9c8729c8af6a4f8e8e2003d9b1cd2213e63c67f55fd7ff988e02
ea8033dd6c514afd3aad412daffa253d7f7d45a5db3bee9507cf61def963377ff8d70a077f2a41
ffbc9c754f4e5f8490b1c3ad36b76d6eb386cbfbb80b5f678dfd62794d2e5f837b4977726da51e
d5dc160bf3b9bcd356948f93d562b6f5a86a294ab524dbb2e79da496a37d55f974b03c936b28e5
a1b94f66b5b566c57d1c1f8099fc685bbee1a9be2b9d551f11e4cba85aae3bbe5cc1c4f74f6a9f
51dbfba33beba3667750bb4a9f886f6ecbbb45915494f38d5957e65b777a1e2efe7b565f1b227a
9fefbb57135cca5d174f5fe12820c75c371671ae925415a0aa2e31a4812fe38bee179f54f938f9
281696a2e57480461c1ff080fc685b1d50f451409e62601efb328541fb3e0546c5d6871f66a732
dfe69f0efa8be99ddefeef3c5491dedfe53110e61f6f075d7bc762adc92d6cf5f1c21c3be22ffd
97d358ffceb2f38165f53ce8f2aad6ccd4cc8b59f9347471aff47d2afd5f7e8211c1fea08b705f
3fc83458d4dc666f0dea417d739eeb21f60bf746a5b3a6f0e6c43d6a8762eed76993c749a3544c
e951b5a3c13d94a2a4ed74f010383e0057896692a8185776091980bcc90f2e2a0e533ba41ecc56
87cb4bf77e1976c89d6ffb5d76780b273cc4e1a384955adffd667e3a74cfd09a299d3a161fcde9
e1e40ee8caef65afe156fa63f321de31e5649655f3208e1f666d85d188f673d8be548bdb897daa
14ba10f6286f2a4abd340dc98f2dfe1e15f3cab698e366cd2dc1a2331728de4d9aecb55f2c6183
06fd534c6a624055b5476d5bcc399df66a95e364b598d2137a7d8397e0d83974f2e5a5183b9bcd
83da7ad0a09552b4a99f0e0a1a32d98ee303b0bfc41d00a59baadd60bfd9233ebd6967ee4af0a7
2777218555fdc9efda5f36875c058b5d8fac36b378bbbd9dcc17e7c199e7e72ef38e1aa99c0c6b
30eb0f8e4a52aee97a918579a87e3c93e0ca9924666db9cfaa03ae7af79a837b4b2524d3046dba
b02d5adcb6b9c74a769737b38944b59b6d651bdae664ee7ed152ccb2ea1aa24a3e9a52dbb24825
4862f9a0ac4cff5b8e63e522885a9aebfbb395dc4454e14b3624c50f177713d5aac81c4ba7fc94
4b61de2df7876aa7ad97a22c530459f446d6c864138e0f2dc504d6178c6d9b614599b0d13f257e
a0d9c730634486d8d5975519a218ffbc13e797e1ba194bff7a651f337be99e9db937f2c356907e
206333ea0b7a3c93cffc6a197ce8f41cbe52a172b2e4e1b7abe4c1955a6140cf68ba2edade922a
f5d48266b695570a552e7fb6959e8515d4fcc2b66871ebe6be1cbd39a9eab327d99de7da7abf58
c2af64b5e9eb6608d47bd4d6c56ce9b4cb548e934ab598a666c283e778d9a2b6b814d54e5b2f45
992a42e3e9206f9d3d8be3037023893b0002c05a18370290c3f1015f04d13680f5388f1dd1e457
dd1bcd4903705f383ee0ab22da06b09ed4a4c979534b017c561c1ff055116d0358937e729b732a
e537620016c7077c4d5f32da4e5d957ce7e4a9ce76613000b899073c80c0b5c2ed5c006086d493
db35739f20f9d2a9bf89b6dfea081b50a176705e9871a3d695c8b52cf484e5a849413d0000be86
5cb42dcfd636b72c5281dd4d9e7183813cedc5dc06ebdbb8dce10df200000010c944dbfa5953f2
d8a7fe8e1f99fe35c843a1e559b537a46f61ab02fdd4bd5af9595634d643a126bf944deb61799f
bc71af8e2f260beedb90badaeccbef8200709f32d1b67e28b1f3fcf6bb7a643a007c3966765f39
fa8fa79c0100ee41fa2a49fbfc763dc0b3f3bd309d2b90dc4b03a7b3487c899279257e6cb25cfb
ecae6af8945d83f3185b6f85233703c1a5d3eed0573a9f2dfce7e87a79488d5dd9a57e1db75973
eeb1b7aa66e4ad6a29dc17d512ac3078775aa23e53a8c926b58ad2af6cdc9a92c62eee265aea21
48936e9a9662e673a8f96b50cbdcda2e14d39a32f0e6654c94d750a987c5c50cd63f2dcdc7b1fa
1a1a33e9bf3baf21a25a1da6b9dbad4409dcc3dd0c852e370a6e22114fb5cf26883229afb88d5e
ddf55af64da55ad53681dababb4e00d85e34b62d872475149283fbc7eb74384ec7071b311b750f
866f3383fe1fbf75afe60387d7eef836ac4afd7b5a89da84b34e555eef181d65e0f52375108f92
cda04e3c7ea1749daf75d1989908a47fa330a4356dfe9ffaeedd9d8bbfa414558d3559d052517e
9ad55b539d9ef5bee00837b15c4b31a31c7afb857ad75f83f2634ebbd68b196440e5d9cfe13a15
b57131d751cda4ffeeec6eefb30f0fd7d3fc52ceefc33f66a87639530a39904edc07945413348a
aa2b544850ad6a3f41ff1a765100d85a626c5b7fef9743b03948ed3d00a04e003208e19c06ec77
00cd24288c97c8b885a4d7278f71557a0046d6396e22fc88739a09078ae4234e02bb95299f264d
7b6d49a1a6ef30a6b6d52bc1894a3674452b4ce50db6e59c7b6694c2af64573987d59aacaa5494
ac70e3d65409dc024abf0a8a5cae8749a6261b8b39e530d82f32199079ff8daac5949a9c3239e6
caa669a9a841b21e562a666b5be495d6d090c9a5dddea40fb7eeae244820bdc5c94f8b4a971b4b
11aed609a62b09e2529857dc46977af65662d24c25ab25a856b574c242a70580ad25a26d7d6c72
0ee87b1f91a263a52287cbc623b87b9a744ff6fadf72bcf6d30bef6469ce3a41027d4c774e2ac3
39a0fdf419481553d6196cd72dce2c5276fd39539c37b759c782cc2845aad24429870d355951ad
a85bb466b2c8a57a70256bb2ad9841026fbf50248dfbca326189241af3dbae5cead2bbcdf57045
315bdb22af9af3522657eaf6e1d6a5fe65bb63254c8b9f9fba5429a4d443ce53cdeda926884b61
5e716b46b658c87c25414355eba3c19c4e0b006b4b5d25793874177313123d5c247726d9ddf27b
0ebaf75149aeed0fffd24fef4f736d68ff6a8ef2e3a27f2d357768712dcca7d4b37539eb2b53ed
f48f85246faa11fb43d79fcdcfd0e66682fa9768b90476b4e11d1e9b6bb2ac5a517bb4a613df6c
f44b74b598951c4a2b9b5fd2753edb633b57a19872cdf4bbd779121657d41ec55cac94c995bafd
3c876bc2c75297ab3677637f68503d04651354ab5afee11ff100605f7eb46d4743e5e0a5cf9432
7aa1961b9dd2703d7382797ad28b3ea79a3f75f02d7f620ebd6bbc75a7e7f17ee7a7e1f57be3dd
56cf1d0a6db3bc98fb54d4c2623e2a896e9d9d77a807b3a87054557ef85b0100e0f6fc685b1dbb
f5d9511ea4f2ac83b3e9686efebc1feec31467cd4ccdd12bf407f22fa7e94c6697da10cc3cc130
b61e84f6cfa68b98e2a8721d0ee69ac84bf77e31c1771f8e046f6d794dceada8955bd38c1aaa7d
e1b871bdadd61fce4e01e5e9482daac5942f6c7e26558f9aec555183eb8ab997d50f20727d646e
e77d312bef7fe83ed3aed4e5a4b90b2bac2630563f56c776385603c002d14c92c38fe1182ae328
d51ff86ec59e24f470ce55bf56ab0fda799fc70f7daa9e7e123d9bf3d66bf8cb6c7f5cef8c6e36
a156378d45f5dd6fa620dedd4296512766752e545525774c5727d1c3abfe738bc715a56f95b0bc
26db2a6a87d69c0a3866c00d23ac743d54add11f54250465bce26b55a998f205c699b1106f5169
aca8abb517f3cab6702c69cd750f20aa57ebb55dba53ae3fccfdbe51ed72e6fbb97a31be03cc50
2dd504c6f2637549b5aa25934ea7556f25b3a15e97892885eb0100e03ae155926fe3b523eac878
9bd923f185359219ff0a24392cca7274afec190f9a92583e282b9b4ae4cc2b75176f9bb534b295
209ff3243711fd20be6443527cbbcee174e234eb8c959bdc4e276657d4226a9956d952db65e58a
6a597f2d4da51e5205b4cbf4a1723d58b99a6c286669bf18ff0c97f629160dc51cba90b3e8ab6f
6dc61a2b4a24eb61ad6236b64541610d0d999434f1d29a87eac73309d27b684e72256e4d661a74
2a7b3941f46e70ac56aa87a0fa31aa5657954e3bb2c9a6460480750463db667444063efba7752e
7f59dfa57b769ef67c7abef2676bf541b9d64a339367bc3123f323b5f78af948f0ca226a13fefc
1c3d6f67d507594b53daa9087209d4f0dbc58afc16092dafc9868a52af6cd89a6a854e06e467eb
697356b91eaa16f707af120c9dd5f6353414f372f4a662ab3a3cb9bf933456d4324dc55cd816ca
f2d65cf700925a6140d5ccf3ac68bbdae55425c42d385ea5aa9513f875a88abfc914a35a55573a
2d006c2ffd2c49e0619891add2d017b6148ee90200004fea0e800090163c2650a6c35ebaf31663
9600007c0644db00e618ee722d8b99e37b3e79b31100008083681b40bb7377f223eb937bfd0300
0088306f1b000000d8486e6cdbdcb94926681e3fe6dc440c000000c020176dcb2382cd4fc64ffd
fd3ee306000000b86399685b3f094c9e1bd76ff5e841000000e0b3cb44dbfa59bbcef3db65901b
000000c01c9968dbce1ee975ac6d06b901000000cc14de93e4cdde49375a3e663d1318000000f8
eaa2b1ed976fddf3498f673f7febbe3debc924e797ee9bfab77a9d681b00000098213593e4c99f
b4cd0d4900000080aba4a2edc3a1bb9899da4cda0600000096f0e66d1fdec2b9dad3f2a1c7b901
00000034f3c7b6cf2fd949dbf2270000008066d14c92c30f266d03000000ab88a26d7ba7ede971
9200000000ae1144db07f5dff09cf6fea9bbbc337b04000000b85ef8741b000000002b49dd0110
000000c01a88b601000080ad106d030000005b21da4e3ae807fabc1d86bfbeb2b7e021476fc3eb
ab59a3aa37cfe4723bf4a8e59ba0dbafa7da2797765a1a0b001e462edaeebb8fbfbaa3797ae4f1
e32ec317008f6c7872ed831f5b3e472900005bca45dbe6d1361773ff3f7b076e7c412ff224d1fb
7e98e84364125f4ab54fd26901e0cbc844dbd3a36d7a15780f77e0de89f98534b1ac3d7ad41ff5
6af929166ba147cd727e31b1e6cbf0e783fa1ca528a05703c0629968bbd721b619717106b90100
0000cc9189b6edec915ec7dafb3ebffd3cfec06a868b2e27ef4fcdb93cc8bdd2a87df0453ef5f1
aaff3d4cbb94e5437fb5089437e1be2bd3dce7caae611ce3775f9471a68fe3f0a722afd8c51d82
92b7d4c7f5cc7bbfc68664b626cd347df5efe9ad9996d743350f4b37e1ac5f2dd326cceb6e95ba
54d5e5de7249deeea447ad5293854c16ba9c943ddea8bc2e2fbb6b564bba7a738da5c457079a57
e29d42d2946b3ba1ad3f3495621f6b3477927cb0deab0b8dd5c85f835a827c2eec72a25a0f762b
57ee770090173e4b32388bb8cbde6794e8243a90d3ed313c4027239ba46c19ed1a5a36119d21d4
32ef305d5bc370f4b71b95f4ce8c9ae024248b5d83bcfb61426dbd7c74477bca94754a31ddf3a8
59d2a588b63e58580f99aaf6d6d0be895c26cd56c2654ca6fbc3f86f3949db95abb75aca72173d
6a794d3664b2dce586f507f56f5eb43b725057b91d3c5cec3a25936e18655e71d723998c0bd218
07b6f4877a29ac5c9fb4aa09929637774dbd572be5c66a91ca64dc9ac132abcb35d683dd507b15
0140a3c493dbf541478ea7e62075cd58c52aa293e8c01edf9d83be9c1866e5743825273fd3b009
77c058938fcc39cdb4ac414ef652093abd7b9e334570f31f0cf3d893877a41de928f4feb198b69
2b79f848b214c9b3daf27a68c8c38c4d6432296d179f7de5b4ea56ac97d224732ab8e2c63d6a79
4d366452add32d60d0e514d984f3c2908d440463363735caa8dc58f229af92a3f50c05770b62d2
b81f2a98d71f32a59864fae4a49a20c96cd7ddf4ece66e23abf52adc5169ac06c9f5ebdf54472a
81fbee155daeb11e860a9c937900689488b6f5e14c8e44734e51ebcb9dc652c74a3904cf3a4a96
ce22d54d98934a9037f7245dd7bc06399fc90874b9804189dc3fdd5394feb76c2555c341743549
c604cbeba19a87599b486632d59a5239b25aa91cbd39f3715dd592587db0bd20e33a6fd6a396d7
643593914491a36ce83c042d2252194ee6c16d2c4950dea2a44f6fb4c1bcfe902c852bd9275dd5
0449a9ed5ebfe3e4cdedd55e63b59095341fbd6777b995ea01001648cddb3e1cba8b99a97d8349
dbcd76b829616913e6e2d1fe75384fc8f2aa5fd2b77069d2bc8617738330dd28a7ee185fae3a9e
abd422332c03eefd649225fac35f67f067c5f27a304a79586913d2a5adcb59d7aabe1a78ac16d5
dbfb43d79fbb17f5e741fd67eecc23d70aaf64db1e652cafc9fa9e55ee7267f55fd7ffd0dbd24c
4dd6d7e92b3456bbb91bb576eb0fcbedb0e3542d6d2ca9e1ae7b5511b0ca6432085ed2e5f6aa07
00c8f3a36d3ba823c7267d5c937117b53012702be66ca1c42730dd5e6fdde979b890f4f934bc8e
794c08f5f4a4171d3a983f75b0257fc2d1d2e574a0d377afea38a2d2abffbd74271bfa3c04fac3
bebcbb284623fd5fa2cb01f8e4fc685b1df5f4b1ecd23dabe39a19521d8e83e39f704df74b7196
5907f99635bca913cfa53babda3f84bf9faa3f55032506bc177852a1fdcc1f3496d74320cec3f2
4d04df55f4b0a55aad6cc36c4b6d549da7dfd54a2fddfbc5045b7d3876b8b57bafc9b62e773ea9
6d9aa0c704409777fde72ca5c63274b946fa27b875dd4d7f986be5e66e536dac56e3dda874f6cc
f8b4b65297dba11e00202f9a4972f8318ce5c890ead5bfc63e0a7d80be82fc76f9ea87bfea95e3
7892a86a5bc3e14dfff9f2ac17955efd19cc6e9cf2df77bf99df58dd40a485bbcee387dedc8cf0
68793d18a53cac54d52af5347773ac2b1d4b192a8aea7fe85f96e5d6f22a5638bcea3faf78aed3
cd7a94b16d4d1af52e67c253b5d2a309bc4eed53789586c6526c84a7ca9b9c40b5d08afd61533b
34b748f7eab6c62a53450872187fa559d4e59aeb41bd22f34c82632c002c97b803a01c95d441f0
36b3479c297ade627f5b34098243a7ceeddca3a49d24e32cc35a5b3691c96770042fa9ae21c886
a4b78d92cabf5dd487e4e4211996cccb9aa6969d5584e817dec1c27a68f978fb26666532f8b5da
796538efceedffb7ed51cb6bb29ac95a979bd80dc56d619934c1e56b5a3293763d511e8ed16579
d27c41416699d11f72a5b0727dd2aa26484ad6d2ace66e54e8d54ab9b11a0c551d2cf9e67697d6
2ed7560f44db0036138c6d9bdfef64fc464f526c1fe37c4497ee79c9f396cdef9ec108cec98c40
b72aaf419d21d46963bc8448937fabd38f9cf555fe9de93df253e994b8d9f9c5f9949944346f1d
cbebc1a42fe56195aaf6a742e929524eeb4b9fb73f7fcb955ec38f3ced6edea3b6aec9f62e27a3
9e6ae5575c4b506e2cbf9255e6d79d4925d6e90fdbdbb6b945b957d7f6ac2aeff863e87ee536f7
f22eb74a3d00c002893b00e2ab30433e4b86000100005094ba03200000008035106d030000005b
21da06000000b6f2f8d1b63cacd82ecc429ec15c3c94bee4685366be78e9360e0f476e7a30f7b6
120bdc6db70f32b6679ddc9187b822e2612fdb587ecf1900d8572eda36f75d921b211d3feef794
a94eedc12177eedda6b7e5debe2a5387ba7ac734c9d34735c163d1d158ae3b99d37f7cfb2d7b67
ae69d9ac4306b77e9b67a5f0a59a877beff69f49a64f0200d02c176d9b47dbc8931dd489fc4e9f
7123cf1b33f7bdfa362ecff73362aaced3ee0d7a833f0d1549bf3a2fa9282a38af57133c161b26
be382d3505d39bc5d09b737e2550b1f2b6a36ef7dded55cb0eb9f26f0cf7583e439f0400dc8df4
1d00f5e89a8486ce20f7bd29ff9e78f35f1bf520ae53753244ede66738a38fa7f3e04fa59ae0b1
480d8413489cf1602960dcd972afdfa3f1d78ced722bb5b15dc75e6dfd521537eaae8b4ad1d027
2b9c35dcaf87c864cad6bb0000ac2d33b6ad1f8cec3cbf5d06b931831980bc9ca6476f1cffa6eb
f3f06abec318fa21f95df7323ec7e172ec4e3ac5746aaf2678240733487f8e46616f35777c23e3
a3405e37789c3876f2c9fa2400e0c632d1b69d3dd2eb585b05de7b93d10bbb78c3186648462d1f
26a0091efcab225119544ebc1b4de49094b20421ac3b7ce2269b359ef287fb2d45aab157df5f8c
befb61a24ff79c7e7ed7fffb2429aa091ab973c7cd1207eb857a10eedc71bdcc1fb03c9ae6b8e6
c9828bd9e149f7e70529b2ed576e0da8a530005fef0ce72bbf14b5e441bf9ee9f68d0a7b9664a0
65c759ce2d6c9cf9d2ee2ff2bd7acf52b4935cc525cdd643e69701957eeee5c52d3baf9b8da0b2
ab87e296fd627a576d3d35a69ead87914df0a9aeae06f065843349dca35eb0ec76980b8eefb24c
87e031ec482e2a59b608eee9363a5babc53dca4b1ede8e61b2f84492663219d498646c58432a81
f76235418b5431bd8fd7ea2199402dc93362812e7b2ddc913a8fd7ecf587f981be7cfcc3c61c1f
ddd106616396823e93acf6b833e44a34749ed6be3268c9436e696c0eaf26a3cf36ed38ed32f1e2
f0babfb8f92f67522bf6ea754b219969acde897498b10348bc1b76875a3dc8a7e29a99d1adca3b
6f43afaeb445cb7e91c9c3b477d4eaa1be0600b87b8979dbfa082b874b7398dbffa0a632e06e54
06a8e26cc8992097bdf2bbee30a726a18c13194ca7197be6306932eb8b8c6708bb093bcce69eea
c2884a3e25d9a8266890ac04fd7bc5a85a0fc3c05810a9cc1db86dcbb6e4365ef3d416e3d2da0a
86fdb8fad4d00aa638ba6841b99464b54bb58c1f1412d5a573925c49bbe2c7936dda487dd6fd60
72cf5ab27e4fa6d15b76bd72269339747bb5b25629643df37abb620a255b97fcc76b683c04b9dd
407fa4b613b92a3baf6cd14f10f4ea4a5b34ac41f2309562fc885d49b51e64a3853500c0dd4bcd
24d113159c49dbfbdf90e472f4264dfeb1fa44163349e37272b622bffe9bf27acecead15cc6cce
d6cab8747f33b326e454a1cf0d4fdd69ff9a34595779704ff6d32cfc6a3dc86c964bf71cdc5fe2
3ccd476f22b3ffaf6d47d51f86db5c8cf5ff3627e610e797a9edce275d9cd9f9713b83facbac2e
08f20666f7d1173fdc99cdf7acaa865daf9ac94aafbe2712ad9e9ea3fda5ad1ed49bfd8ff11573
e5c38ca371e3ce5becd54d1da6b086310f7fb3b1f2b97b76a79335d4c34145d5853500c0034845
dbeae82681883e62de62d2b666474dfe1aa660aec91ccafbd769136ad1d7f0d949d5a325df34d4
896a3a2b98739eacbd141654a3d26a82c079388dbd2647b9aaf5209b7b9f4ea537f72201b7dc05
6f0e3750b8ae599774863bb2e99e55d5b8eb953359eed5f7e3a0339f08b595b67ad05daeef0ea6
781274cef8c6deb6f3d67b75adc394d650cd43b51ee41f32fa03008fca8fb66520561dd5e5f0a7
8fade38c883d4f693a1b6ffa2c25c3998f3b92a102ee6150f6b9bb8cc33c43d4971afe9401a1e1
daca6a8236e7179301b9b1c9cc8928ab5975ac7756f16f43828cdb7c4f2d79883dab259377d1ab
6bd4815405a2ea2bc1ec8928230964e5fe367a1064f7efbd9fe6500c0037e547dbea1ca68fa7f2
e00cf3e3e070561bffdcc341fff6aab63b6faec27c97d3583467691f399aab3f9808cc9e2f2fdd
bbfa973f462bb7fc1b4661ab096631d3608602faeb2cd58344c9f6b7ecabc9770c13832e77ffcf
4dbce24bd11ef6dab3aa4a5d6e5626f3bdfa1ea858f9c51c36730177fd1024d32a0eddf1a84bf7
eebd57b37ce75dde61525fb3e35b2aed7c280680dd453349743c670e91121bd57f67dc86fed954
f4dd6f6668e7ba186b5a8fcbdc56af7fd5e712576f4e696b391ca7f39c5ab3fc087b72ae7992db
f9d929c82a8dfe09d59955594d5075889e6be88580d57a9088bfd737f408aa3f5db1797abbe36f
e273b9db5225d27ff93746bc37d77f29da5ee39e35b77d5bb5ed7ae54c567ab563ab52b41ba74d
ab80dbcb4bf321480e027a787beec5122bedbc8d1d264dbe669ba85d846dd7780872d6a0de4a4e
6801807b96b803a01cd7f46f8837991069e7aea416f798ac0ebbea95e0303d49ad674aeb4c4674
179ba0b2f206ba02fd95c76b1b6e1ae02cc118583541599c07bdb8bfb9d7ea21d71cb36b463614
ffdc9fc9802cb291b814b3362e4d29f526ab9a561bf770939ff07e20e6c5a0c8b2aa4473e44ada
2e9987d1f53db371cf2aef38ed643dcd2d3e6ca22193f55ead2c29452687b234ad24e830e30abd
cf96ebc11a0bb2628b0fab0a326978bdbada16d535a87598eeea2e6f26415c39c162dfafaf0100
ee5d30b66d7e8d9531b9fee94697c7f917d1cb8f8cee75f1add47ac6a7302698dfa083b59e9ec3
5796901b5f586ae571298efe8b2fdfc2e1ab6a82b2f34bb8515d9f6eb554ebc14c2b0a733e5ea6
36c3f89b782e882cf006894d7ee66e7c3f2a403161df4d9ee353d1b86795779ce5ca5dae2193f5
5ead6c5d8a59c6db68bcb95fcf1a0f4132b8ab92876f34303bcbf53b6f638729f22e1637053c05
bff9d4eaa1be0600b87b89fb6d031b917bf1aae5530e4bd9315746ddb022b5d75cf11df56e657f
140280cf8b681bbbb201f7670a20d4b70729945a08b5b1a2878f4d832761c99e7293398a00703b
44dbd89d39e37ec2687bc95c6dc0375db3f1d0fd2a352d9b6fa400be1aa26d00b83b43b4fdf8c3
c0c1a5decc2101f0053d7cb46d6726c8c2a8c90378b8b1eddd87aeefb657071963383fcd749887
3f163d6c2996df510a0056957a72bb66eefd2483107a64e25ecfa9eadc1f1c51efebd127feafa8
c9a3bf3bf0933c3b54133c161daef9dd29bec3d776fd6db890f1baf5af147c54f370efbdfa3331
6d9a1b6dfd64bb1e00e04672d1b63c7adadcfc499de96ff58c9b0a797a9cb9cbd5b77179bea711
53fb601aa1c2ac205653a773fdc09a910ab382137f35c163b171e4cb9db55485b94999dcfb2c6e
c495dd77af560d37e4cab937dcc399bee0e5bff37cb25d0f007043e999247af84de60b3a83dcf7
a6fc73e13dfc98787482a4e104ef9cdd8357ae48f05864a4309e4022e57a8c50667cdec776b995
dad8aedfaeb67ea98a1bf5c645a5707ea3c8f53d79fdfa5def61e760781eb614ab757200584766
6cbb7feadce7b7cb2037e672a3edcb59d7e7c5792e833cdffb657c06c7e5383cffc59efbab091e
c96178ecfc230d69c7c667a6e82769e34139bf54e47caa5d0f00706be9b1ed3777ece71617c50f
8349e3e28d52981197dca24e872af3c18bc31215c44d199c47ddd11137d9d5c32532b23b7d3c35
34e80dc95413341a8763ed12470c857a1092f969993fa2296b48ae5c0a957cab85fdb86cc26d32
5b51419708c7d79d31bc96b62e94a5a0250fb9a57d5b521b7671bb4a908169b96e072f8e6dbbdb
8a335fc8e420df69d72d45baef2ddff5a25161c9765c15d98aca54af4aeff59c86bdbb2abb77b7
ed17a5d66cdeb3a677d5d6a3da53b21535b20954fdcc6b2c00d85e186dbb07b56089e7006c2438
7ccb321d616b7149b608eef9383a4ba9c53d880fc7eb63986cee017cca4c100d98522443aee1c5
6a8216a9627a1fafd54332815a9227bc025d0f9978c86bee4cf456201fffb011c3477794cb10cd
bf658b419748d66adcd6e50ccf3d97b7e421b734d67679c769da2fda49c788dbab6dcf0a966a97
b3d5b56e29243361f52edff5a4478d3d44c2d9b0bfd42a2afe5227b99dd653aca826a935a865d8
68c37e5169cd8635e4f230ed5fb58aaaaf01006e2d31b6ad0fa072343447b1fd8f592a03ee46e5
1e0e7136e4409fcb5ef95d771c54336705377498ce22f6c460d264d697e50607de89d0ac2d3c35
ca6943b2514dd0205909bd73a2aad6c330ee158432737f522f667baaea719955c9f6e3ea53c3ed
3e4c6e75ce836c2bc95a95528f1f14d270e99c2457d2aef8f172bf2d539f753f98dc7196acdf93
69d3963dab9cc9640edd4eabac550a594fd899930d346bd7336b90ec4901e3fda5f110e466437f
244a50aea8b2cade2d59f21304fb85ca839b81b0351bd62079988a397ec4aea45a51b2d1c21a00
e0d652f3b69ffc49dbfbdf90e472f46655fee1cc755e47dffde8bbcbc9d9cad9cccb34e5f59c9d
7b2f98e99e732bc3dec3417db07fddfb042013eed5d9c83dd94fb3f0abf56012e8c9cac10d28ce
ddd1fbbb4666ff67da5135b75491addee05e2e2dce2f53d39c4f3ab7b9cd65b96dadfe32ab4bc7
2e66efd0d736dc99cd779caa863dab9ac94aa77d28128c9e9ea3fda5ada2d49bfd8ff11573e583
7b345e5a518d7b7771bf68ea7285358c79f89b8d95cfddf369f8a7d650510775502dac01006e2f
156dab8397442afa807851a1c52dd84191bfba8fd5af4833476a15fbda4da8455fc3d7ab773c2b
7ed35061b75ad9e1753a492414a352ad9a20701ece52afc941ac6a3dc8e6dea733e5d6a49654eb
cffd56e29ee6af6bb515dbfa9636dd71aa1af7ac7226cb9df656e6ee7aca41972e116a2b6d15a5
fb64df1d4cf925a63cb9bd746145b5edddf5fda2d6e54a6ba8e6a15a51f20f191e02803be547db
f2939c3aaacbd14d1f3ae5f753b5ec78ced3d978d3672919effc3403157fa813823d49a4c64765
bc4727d3ff574bd0e6fc62aa51eeae307322ca6ae60c06cf2add6d5c1178ede221769c964cdeb8
d3aeb4eba903a98a3355281c4f23692471aadc00470f824451e9cdf7eecf7aac068055f9d1b63a
76ebc3a53c59c3fcf6371ccdc73ff770d0bfbdaaedce9bab30dfe53416cd59aae3384be82702da
df0a2eddbb2aa03f882bf71d1b8669ab096631d3608602faeb2cd583841df6b7ecab49a94d905a
75ffcf4dbc22f0dac35e3b4e55a947cdca64bed36e6ba55d4fc5ca2fe6b0990bb8eb8720993571
d0f712559979f7de735c5751cbf7eee55d2ef5c5464f65f4ed7fac068055453349f449c51c0125
36aaff8cb80dfdb3a9e8bbdfccd0ce7541d8b41ed7591fa9fb6816756f4e69abe9bba3b3bae387
59b9d4ad717ed7ff6be728abadeb5f489d4993d5045587e8c1875e8c58ad07093b7a7dc78fa0fa
d3159ba7b73bfe261e7057a532acff3219bb5bd77fe7d95ee38e33b7f95ab5ed59e54c563aad63
ab52acb1eb0dc659d12ae0f632db7c08929ce8e1ed68ebed1595b6d2deddd8e5d2e47bb889da45
58a8c66394b306f5d60de650014051e20e8072d85247bddbcc9894df43338b7bc8554755f54a70
149ea4d633a575e61aba8b4d5059798b72068ce19e00ce128c81551394e946f43fae17f7b7e65a
3de49a6376cdc886523f73c7999cb56e6929a91659957c3cdd814d36c2db4d98178312c9aa12b5
9d2f48ab641e46d777bcc61da7a15b3691f5c4f520f5132dc3261a3259efb4ca92526472288b5d
c9a25d2fe851e316bd1c962bca1a4b1a7789a68a2acb34c7b0ada01486b75f545bb3ba06b50ed3
e1dd457dc9d1ff6b3f55aba8fa1a00e0c682b16df32ba40cdaf54fbb5e1e37f1af9197df10ddcb
de5ba9f58c8f824b30bfbd066b3d3d87af2c125c606ae6e704eb3f3e7b457bf9160e5f5513949d
5fc2aad3f5e9564bb51e4cb6c3fa1f2fcf9a61fc4d3c8e32bd41e2542ddd11155e9868e67487f3
531b779cf27eb15cb9473564b2de6995ad4bb178d7f38c77c9787343f6c643908cddaae4e11b6d
15556676b7b093b4efdd8d5daee872f4667bab1a3805bf1ad52aaabe0600b8b5f4b324812dc8ad
76d5f288a34e7628913133ec49ed35b95f423ea560f01b003e01a26decca06dc8f144038bf6513
6a634f9f3ff40c1e9525fbda4d263102c06688b6b13b73427dbc687bc95c6d60a669e2f8e7ee78
a969d97ca705f0c9106d03c0dd19a2ed2f30ca1b5c90ca1c12009fcfc347db7666822c0c8adcb3
bb6dac20630c63df8c19e97cf8bdf8614bb1c2bd980000a1d493db35736b271963d0030ff71a7c
a82029382fdcddb351dcdf4953c354eeb8ce439fe3868b08f35de5011aebd330bd2e374658ed72
3b240000e0ebc88c6d9bb3b59c26559074a7431d12c8def12fadf62e167609262bbb41892c8ffb
2b6a25dabefbc61ac82d841f736c3bb8f170b22f55bbdc0e094a4c3f616cfb5618db06802da4a3
6d1d394960e40c72df9bf289e1f6a70d892ffdda3b3ad1f6101b8d815df0e727b37573acb6fe9b
46db8b4ae14478b29e78b70dfa58f0a7b243820aa2ed9b92f67af8fa0780fb929949d23f75eef3
db2f573fd6e10b3b9aa7079f5fbc8762b8d1b63c00fc657c1ac5e5383cffe53ebfdbe0de998780
949f2d52ed723b240000e0ab498f6ddbd9237aa8e316bffe0f4362e3e28db58c63c6c9459dd4c3
2bdeec1215c44d194403ee188f9bac75d04786480b55971a43bd666049d6e32c71585328a6087f
fa6f1f89f457ae96f0be7eb5c66a54e80fedcddda438b65daec952a715f9c65ab71492933087d5
2eb74382aa6854586a26aeed6c5ba4f2a0a8f45ee79464b995b4c9ee384e29dc7c067520356317
af8adad6a04cefaaad47b5a7642b6a6413a8fa99d75800803661b4ed1e9a8365b71b2407272159
a6f3442d80cb16c10d5ca273ad5adc53d170d63986c95a4f432693bac69c0dc567d3646c3aa39e
53a5f03e5e2b6632815a9267e5a4a0b69325ca2d8d5b29f787a6e66e271512c56ad59aac745aa5
d858eb96423213566fb5cbed90a0ca24b67b8a84b3e14e576b0bf954dc3ad37a8a6dd124b506b5
0c1b955244470fb7352b1da6610db93c4cc7995a45d5d7000058413493e4e55bf77ceaba4bf7fc
adfbf6ac27939c5ff42fd46a799e75365ac66ed4fe38fef464de50cc2fe63a3f2a9f7e4ab51c2f
ba08e9774d71c4f1377dd29ade353f7cbf9ab91faec36bd74b558c69e67a73ce8e87b7da69cccc
ded1d378daf407bf1466f99b3397a05a4c493034b75de694546a3bfba95a6335723f18f48796e6
5eaea5c31432a9941b6b9f522454bbdc0e0932d4fef2da77a767d5893cd5b638bfebfffde1ec6b
7a7ecb795a4f75c7a96ad971bca3c737b3f5be73aba1dc6194f21a240f97d3b8926807ac56945e
7f710d008035a4e66deb23be3941caa4edf39c93d02a2e476ffae91f7f0cff584ddffde8f53966
dacad9cc2e35e5f5a860d1863b26709c5519bd3ab18da73a09a4e4f4b616994faf821277bc6a9a
645f2da649a0238620a43bcf888377b0797fa86ae830d54c561a0bbefea8bf9aaa503bec8a6d6d
a1deec7f8caf1c74d4ee1ec796b645e38ee31e3dd45f2603fdb8c5a65e5d58c39887bfd94190f3
7090193454d4417d2129ac0100b08e54b4ad0ec11773e8d787f58b0abc6fc1fc902acb873f82b8
0273be51a1b0dd845ad4f958bd1a0cc02dfda6719e4e75eae4aa4f757d77b0e7ba98c998547e93
71fdaf327f349875502da66cee7d3a9ddfaf4dfb435563872967b2dc58b752ed723b24881d7405
26426da5ad2df49e3bee6b12539edc7d79615b48896a3b4efde851ebd5a53554f350ad28f9870c
ac000036e447db0773cb64756e9263b43e01d8897d3b06073a1b6ffa5ceb8e0a7f025ec091fa79
5d46adfe9873f61b7e26969f80a5b1e239c70fee21fa434b266fdc58d52eb7438236ea10a4e24c
150a7b938ce7903855664de8e183282abdf98ef3598f720080881f6dab33903ee8cb4c41f30be6
34e72ff8cd743b07fd0bb2daeed693192e76b6a2b35447a35ac9245133bc64491432fc607de9de
d53f0e3ab0b0e4ee69d7cc9418a747eb8dfaeb2c15536223fb83fb7ddaab3f54956a725626f38d
b5ad6a97db21411b152bbf98034e2ee0aeefbc326be2a0efb9a932f3eebde7b8ae2d96ef38cb7b
75ea8b4d30ed5bd9f62807006813de93445fce2f633ce657ced6d3cf8ae4d7553bce340eaec777
0c908bfad5492b69b8e43f335e25b780083eab3e625f28afbc85fc5030653b285794c3728693d4
26821c06f770a81673b88559f4c385fef17d2e53c0dc8d1daeafcfb6fe7045eda56586392b35d9
90c96a63296b9542d613c7a9c1fae3cded90a0c2d4e450516335fad556efd562d8746aeb2d6d51
56d971dc528ce48030344ab5c354d710d583bcebbed2b8fbdb04b6c6828f0000164adc01500eb5
fad87d93a9a5e38927b9b867013937644f0ca9f54c69e56c172d364165e52d52190802a0e19c9d
4f5066cfafdee2c616b562e66afb9a829b6dad1f6d37f6877273b793f5c4d161b9261b32596f2c
654929323994c5aea4dae5764850624a31f593b1505e2594dbc21a2b33ee754d6d519669f1615b
41290cd9e85015d50e535d835a87fd3a312e6f26415c7bc162dfafaf0100b0063fda364767399a
ab53662e72da9c732a923cd8b3a37b16a80770d1c926482b633f7671638215a26dc3dd447265ee
89ff8aad057143b2c90ac514c14ae6851d96a9edf5a36da5ad3f4806dce59aadc9b6323550aac9
864cb634d6f5a5883ee82eee4adc6c2457be43822c530ab79fd88830e8b7d55ead48dc5fcda15a
72fdb62c58c9d46da252289278ca67b9c3b4acc1a91c793db997952baa650d008085d2cf920480
47a702cdebc2e8071587e300807b40b40de013fafca1e7c12f9dfcb87193e97f008022a26d009f
ca3471fcba39518f22357788492000707f524fb701808777e99e3ff7a3c8e52e878ed3b3f3e448
00c0dd606c1b000000d8486e6cdb5c2f2f9302f5cfb29ffb07590000006013b968db3c04519e7a
f8d40f8f4106000000304726dad64f44bb74fa59cbbd0abcaf7a9638000000f0d565a2ed5e87d8
2adef606b901000000cc9189b6edec915ec7da66901b000000c04ce13d4982c7fcbacb977a2a1b
000000b05834b6fdf2ad7b3e995bd57eebbe3debc924e797ee9bfab77a9d681b00000098213593
e4c99fb4cd0d4900000080aba4a2edc3a1bb9899da4cda0600000096f0e66d1fdec2b9dad3f2a1
c7b90100000034f3c7b6cf2fd949dbf2270000008066d14c92c30f266d03000000ab88a26d7ba7
ede9719200000000ae1144db07f5dff09cf6fea9bbbc337b04000000b85ef8741b000000002b49
dd0110000000c01a88b601000080ad106d030000005b21dac6eefaa37e5ed2db61f8737387fae6
de826739bd0dafe311dd436b6e9e87865e0dacabdaab57e8f67df7613e7b348fd39327ee7d1ccd
5bf763712639e37c3db968db7426e949c70fba02f6303cca94ceb61835095c811de7f6c6fb0e5f
9c1ba2fd716f3747db3193f4c9cf22176d9b47db484fb277e0063eab1779602acf4cfd14eea135
e951f87caabd7af56e2ff723be73576492e3c3d79389b6a747dbf42af0deb7c79b5f48836f7232
f760d6afa67b4f57c062e71773f47919fec4d5a8c9e538807c268dadf9e83bcee7e8b47a90d87f
b2de1dc6dcbb659283f9679189b67b1d629baf5cce20f7ae0ec33c160000f0455c54d82ae1c74d
628f360f9149dc934cb46d678ff43ad6f6bec0ede6f5371de8678d9729c8e27e9b97eb0f3e5ef5
bf87394fb27c842b74af544806f73254907bb744b217cdb5525bf4aea5c8972271159479e58aeb
45f4cc7b672bc9df0dec92cb835b576e9246f6e371fedd352713687e45a925689152292c6725e9
0435d50e53b1a014d293e36ccbebf272a5269b5b737a577595b81f362877b942b7971a50d5226b
70733b24b3f9d9ac35e5f5550e205992f9eaf1a145ae1ed6dbc476ad596fee51b6aa6bbd5a5e2c
b7a6fb41b5dc6cc7c9d764626de6159bd59662b6683a906e4c8fe6daa1dcb31ed93d06e1ac5f51
6a09f6be850752e1b675bc77d733b9ccfa7d32558a6a4d6245e1b32483367697d9a781ebc841c4
39f82ab2f34c3dc9a40997f11c902d827bdc893a995ae27e6677da2bbaa09c3fdc0fce2a85bceb
1d14a46666b542aa986ab1b90a8e4ab24c79963c1ca395cc3a8267f2608b5639ac28a935b8c9ae
2b45ba4d655b518c92cc437a0d390b4b91cc9879d1aea452932dad99caa45ae2935356660d4173
84cb582ea904d9fdf5f2d11d6de820f99452b8f18459566ccd150f205a260ff5e3435943af5eba
0965e3d6ac37b75e4bb1aa6bbdbaa535ef62c729d6e49007776de695dcbe3f2d6e266ba43982c5
ed3f934caf9e54135c2d55d5eb1e48939b48d7c372998adaa84f7aa54825083784f5249edcae3b
abb499698c19c78b55986ea4fa84f436d9b8ec3f3623f256bc6fb83d493e92cbbc3b94a2c9912e
eaf176bfbd624f93cfba7d576fd4d944a514b5c36b0b296678c07566e9a84cba9b08bff74bb5f8
6b70dba585ac73caf6b8ce44d3640a986c4afdabcba8b11476cd43b326cf04d20ad15b8d1da660
6929c63cb82b9075263a67b226c77a28b4a66ca2a9b132aa5daedced87a63159921a9055e9d5ca
3af76acd647b592d6b1864f220eb77db48af33b986a4867a58ba89b198dbb56635812279c856f5
580f6e26e363946ca8de8dcddadc1ad31a3621999c3e387ea4bec551b9266585deda52596d2d66
86fab8fbd9f81034c9f4ea4935c1b592655cf7405ae972ebaa5654aaa1872ca9a5d6270ba5a8d6
24d69588b675ef942631cde3b7c5f6cc4655bf97ae209d4cfe3de424ea348a9b58247bd2c0f4ef
a0fbeaaee974dc55e8de6fd769b25dde81bd5204e915f34ab8d715c86e3ca75061a5a53229072f
7b60aaf22ac1c8364dae80928de68d264b11ac3638304d92c7be553accc252285141742982ac8a
644d4a060aad99ea30d9c64aaa76b9541e6413925b7773ee6952ff5b569b2ada16ad592af8acfe
90cc83513a3e54b5d5c3a24d6cdf9af5e6ae56752a0fb22a77472bb5a62b55abf54da42aaa758b
a2569392c05b5b2aabf3365a535a5bbe570faa09ae2675b5dd81b4dae5d655ada854430f95e07f
2aee939552ccac492c939ab77d38982b00547ba936b8d1a46de572ec4e97ae7f4d7705c9a17539
ebeb15f4c59d2dcca59f6acdd2d56479d52fe91bb0ac48cf7defbb83c9bfdce6e5e4df4b715129
aae40ad777bdce927197538b4cfb0b2cbaffa354e97835c995cedd8bc9c3ab3a58a87c268f7ab5
520437439d776fd4553accf2529cd57f5dff63fce041fd37bb754ae91b3b4c41db1aaadddebdba
3f99e11bb7e62afd418a563c3e5455eb61d126766bcd4282b6aa4eae765da54db45554d5b6a783
46b503e9ed6d7d205d69efde41b54f564ad15293588d1f6dcb7723d5f3a4917437952f5e376a89
e349ffefeb7deef30d646790fcebef308b0fc7abd32dfed69d9ecd3d86be75cfa6c2ef907717a4
6830e0eb9442f7a8be7b55bba8e951aa3fcd8dcf703f76383edcff2108f78303e95753ae49acca
8fb655d5ebae79e99e5503989bae0f8d31feb937f9ee75e87efb31bc6005dff8fb83ea2ae1d840
d9e53416cd5956dee3ce7a785ee5ff78d4df61dea3b5574bf1e47cc5993da1ca8c284fdfe06307
fdfb9a6ae2752fa6de90b9f47b68263320a15d550a5db1337fb759adc32c28c5f9a4db549f1ecc
a962e5e0493a8cdf279f668de754bb9cb17ce70ddca43557e80fb5e3c35c897a58b2891bb5666c
8f63f512cb771c63dbd341d5573a1d540fa4f7dee5dab49622599358593493e4a0e25a73ec905f
226468e48664aff08e2ce66720d523a639497df79b19bc89cf257a778ac90f49af7ab774f5e684
e492295f6ab97a62d3f95dffaf1e5b3afbfb7f5b29ecf1577d5f9ffdbbdea57bd775a72ff90fb2
ef56cbf4ef3103ee317d29c98339020a55a5730ba2ca1eb454fc8b79b5146a25b6118f1fbaa167
84aacd1da6609552d8fa3c9a33f12998ccb790046a4e63c579aea876b9393b6fc16eade9ee2993
35fa83c81e1fdab4d4c3f59bd8ab354bd6ab6a25dd9acb2ddf71da6ab2f174b0a498d3677387a0
5b8beb76e503e9aa5dee661a4ad152938afac8c22808227107406900d512b799c763665cb9ed6a
1b7bea18ceacac69097e01919f45fca5b286e842ab15fad9988da05b6be55244f93f9acc4c87e3
16a94a50cb9099ccbbb2e824268741ce75c7985321b60eed22b76fcb55485c40d962b8e42bca5d
6c29e225debe266b8b7f4d9bb59294a5a5b06c4ee24c5ac99a342f965b734663e594bb9c92acc9
b12c9201c98fe44d3ea7ff2d87a3590db1a43553059912b467239707316e65460d8bb919b86213
4aaa12d4b2566bd69b5bff61d6192d4316ccbb41d16455de31aadc9a9659db6d769c624dc6f94f
9f0e1a8b9994696b59c29548e25caf56aa09ae25351f2ef98a7217af14b6c2e34c26dba2bd2667
a956d4b57db25a8a4a4d8e6cdff67628cc168c6d9b1f11e49a15f5357ae5dfa9af75399aeffdae
7338b3e5fce2dc6a5e5cbae7e01597f9e92458ede939dad072f21d5a6d305e75b9147efe55deae
f981cf4c0a922b2126e3b511fa5d2703f2ab53987831d57ceecc395590d3cc5f9955b504b9d259
752baaa1146abbd38ba65ae61574718759a5149a0c83a9ad6f30ab72796349dd8639b75d4e69d9
796bbccadca835d56a0bb95aeb0052383e3468ead54b36b14b6b56ac52d5e5d65c6c851da75c93
7efed5fad3a78325c5549f6d3c04ddd41e07d2b5f6eedbaa95a25293585be20e8058d75b6abc16
78088961c2db4a0dea3cb41d8e0f1c82f677773b0e809b22dade16c75c3c9283df57e5b7c89bcc
28cbf95cd1f60ec7070e417bb8ff1d07c04d116d6f45df493e33110ab853a9a97ef715da7e9668
7b87e30387a0fddcff8e03e096524fb7c19a369e2f08ac496e18e738b93383b1ba1d8e0f1c8276
c08e03a088b16d0000006023b9b16d73571a9988a67f8ee4874800000060b65cb46d1e6d73313f
8d3df5b77fc60d000000f08032d1b67e14933c1fab5781f770076e000000007364a26dfd8458e7
f9ed32c80d000000608e4cb46d678ff43ad63683dc00000000660aef49f216dd34d42e3c8d0c00
000098231adb7ef9d63d9fcc2d5abf75df9ef56492f38b7edabe5a9e89b601000080195233499e
fc49dbdc9004000000b84a2ada3e1cba8b99a9cda46d00000060096fdef6e12d9cab3d2d1f7a9c
1b00000040337f6cfbfc929db42d7f020000006816cd2439fc60d236000000b08a28dab677da9e
1e2709000000e01a41b47d50ff0dcf69ef9fbacb3bb34700000080eb854fb701000000b092d41d
0001000000ac81681b000000d80ad136000000b015a2eddb790b9e1ff436bc0ecf4157cedb61f8
2b899afc4caaadb97973377439ace5f3edbc41891eba23f5c7872f02701f72d176df7dfcd51dcd
d3238f1f9f397c191e9f497c7607680be026d8f5d6a242ed20347df21fc24c55035f522eda368f
b6b998fbffd93b70635d2ff2904e9ed3b91835f999545b93e6fe4c3e556b9a5be8aa62e887318f
cbf351de03f09565a2ede9d136bd0abc873b70efc4fc8c9b58fcc180b57ee11a1e4dff32fc891b
baf3b6e047d5cf84d67471185c456f86b1cfa7d2d706aa1af89232d176af436c73c87006b90100
0000cc9189b6edec11fd657de7e7b79fcd57fff1dbffe5e4fda9c835281faffadfc31c38593ef4
178346c1852c1fc91ffbcce47537994c646f27e36776b96620ad9a073fc1bc4dd8abc19c9524d6
50ddc4cc4c06099ada422967b281bba1594dd9dae5aa1555e48eb6ba590d56932b857c5cbda22f
b4f0d7e3e5249f49295a9c6d79dd7df9ea9a142bec170bb4b6a6516808e5fa7a68d8f516f68796
d6743fab9696c3a0b7c2f87252f34ab81e7f0d6a995157f2d96896b3ca79f6409121fbc5b404eb
6c2b66ba214c02b5243ad558d8a6aa7693a9ecb9d5db50d50b3b8c6513ccade141adb90bbb7f4b
a715d55200f7267c96a4db8983e5ca7def6ad1d1446473b86eb41d1d32d2c9f282638a2ce9e342
e68c52cfc37894f796783d397204f7cf0d6af13259dd443593b50495b6904c1ec3952cafc9f663
7453975bd8162a8f72b28c4a3a9d638aa5908f7fd890e2a33bda96b5f92c6732597be6c5a95196
d5a4b2c27e615513a4d45b33d3e5bce65e580fb289e2aeb7b03fa42bc7bc685bb37e182c771829
851b049957bcf5a43299d89092ccf01825c73513856479a93ca8655a674b310bfd21f9f17191ad
5c77c651cb50bd0d55bdb4c328e53cb448ad21ce64b0cceab4f552007729f1e476bd3fc871c474
eb197bdabaa2a3896b38b22ccf5b662bc9f5cbb4bc466a0deec773dfdab5e421a6210f72048f0f
43ad879ef12461d7205b747352dd443593336a32d9160d999c646ad21deed5649dc935e4250b62
2d6d0b5b2eb5f86771bbc17229ecc7d5fbc3e89a598ffed4b8c26a2665136e1165b541822535a9
56e8d6e115fbc5a49a20afd49a63979b1a62ac3a9b7c693d8c9b28f46adba0d7f507a5da9a13f3
d970d7ab7618f329af0ea3f524eb39bdfb675a53d6e0ae53976b4ea34b3db8ada91da67a682966
b086a03f8864614399aa964c4eaf8f1b1dd6d65cd57ab9b6c3c8ce98cd43836a73ab04eebbf1ee
5fedb4d55200f729116deb1d40faaebfafeecd6c3d3e2a89a6e35a8bdc56c6034de2cc74955286
734143390ff2aeff29d94aaed242a9b27b6791964d542baa9ac04ae527f962f254a7256bd2bc18
ac411fb283b36f4da9055b2aaa46d227ba81a895c2cd9e7b0ed3ff96342d998c6a5b57b5fdc84a
35e92ad56a6ebfb0aa09f24adb4d559454e9d08797d74343af5ed81fb4726bba52f949d683d761
4c02af0ee3f5c84a5a76ff7c6bea6cdb72c51b2d93d5169aa6ad984102af3f8c4a9dca8aab4849
65d25b5b5cea683dcb3b8c57cf4653895c52572dcd6d24d61f956beb4310b08bd4bcedc3a1bb98
99dafa2be9ce93b6efc7b97b3133d75fd59e1c1d835a8d871e7df83053fae669c883b4947539eb
6b5bf545aecdfef02f810dfe542a9ba866728d9aac66b2c45ce9dbbf0e0d21cbab7e49df6f6745
cbdb42c9de6db3ad14eeed8392abaab6a6fa50ff636c237347b3693d6bd5e4c2fd6217a5db9eae
540f2dbd7a517f28b7669ba5bd7a8ddd5fe7b9ef0ee69372bfac537b294c455dde75b60baac59c
5b6ff3b465b2c5f51d46fe217747b85a4b739777ff7d0e41c0defc685bbeafabce2dbd59ef09f2
9d5b2d571d251f9a77ab26a987dcb0418aaeccb7eef43c5ce5f97c1a5e9f65611ef651cde44394
0242229b577514b822b269b0ca7e81465bb7668be5bbbf045baf720de2619da8141b293777cbee
7f0f9d16589b1f6dabfd44f77eb939bf79d6c0b0e78c7f7e45e33d52f4fe2e0f2f6871d0bf8ea9
da3bae526bf93c04834cfd411da6c2719a59f493cffc1f345a3751ada8eb6a3225ce64d574731b
6759f718be7a5bc49697a29a49b95bb03ec999135e1cd92ccac3bafbc54daddea3b6e8d5d5d6ac
aa76189ded517a42b658b2fb9fbb932e46773cea0fbecfaa6533583b8d9566ecb0f3964826fd3c
3cf97f2aad559db7c36170906ceeb6dd7fdb4310701bd14c92c38ff1b724f393cdf40bce5dd23b
e436d457f060b2dabcd90bc694bdbefbcd0cccb887cbaa4a1ecc2f6eeaf8354d621bb732eb6ca4
b662e7d81d3ff461713aba356ca25a51ebd464219355f2d3e46b988dde9cb9e74a77b995daa264
79291a3379e9de55cdaac8c6041c27778ae44a35b970bf58d1950790b5ea61875e5d68cdaab60e
636344559c7862c02abbbf727ed7ffab87b7cf33bfaa490df4fa763d412f1b5abf71bfd8947ccb
32c1a888eb4d29577545b5c38c5dc526506fcddd4a4b73d777ffed0f41c0fe127700947eac769b
dbcc1e712675794bf0e3a3fc44e52fd7ec6fd1351942173f5aff8c1f4053d9b34b98cfccafabf5
3c24ebaa3d9399aaf6b257db443593336a32d9162d99b43235396f2539e52e57aba82a75c2501f
09ce229e6229e4e312bd499dcbebfadf76476ecca44db67a4daeb15f4caa090a0aad69ca183484
54e974edd7c27a68f8f8c2fe30b1c90a1565d2c487c1f426ec7aa23a3c9a3cbbeb99b1fb975b73
dc56a94272526dad966955e5629a772bfdc1a8379992a96af9acbbc80d2287b53554f5f20e53c9
43834a73671a42166f2336ab717fa89502b84bc1d8b6f9c5472eb4525fa3aff8d9713f97ee5966
866de3fc325ced61e95fafdab7a8b2e7ccbd915fbe821556d5f3700e67f8a88fccc8a4e16dc54c
22f2b659db443593f55234383d173359657ed60c3ea2d6396f25e52eb7465b542c2f45632665b4
4fad3c9e55b9300f6bec17eb28b766d51a3dcadb35b6ebd585d6ac2a7718bf0ed5a6e351e75576
7f4dc63bd50ae7d59161ea36ec66e3f57c5ae37eb1a5cbd19bc4ac2af3e4ce6369a8eaba5a87a9
e4a141a5b955291a77ffed0e41c08d24ee0088af223566036073ec7af3bd2547df3fafe4f03980
c794ba03200000f743859eeabbc97e13a9f7e73c6d4793f9d397ee7cc5183680bb43b40d00b857
fad925f23bc0dceb231fcd708f6a59cc7c65b93b0780c747b40d00b873fec4e54f48ee72e838b9
17ab007870ccdbbe917b9db859bdb0bde9ba7bec82b6b8534ccb1ee9c76ebb4bee962300f099e5
c6b6cd9d7a641a99fe21ef610f91c30d8938c46f8faabe1f0fd11664f27eb0f37e293437b0bb5c
b46d1e6d73313f6c3df5f7fe8c1b00c01d7ab14ffbf36fb107005f4926dad64f7b92a75bf52af0
1eeec0fd88f46d53d581feaa097ffc4c3fcb92aac6ba6edb168d3bce43749842263fd3f1819db7
ea1e9a7bad3cd0dc3b207e802f136deb27c43acf6f97416e000000007364a26d3b7ba4d7b1b619
e4de8dbdc0c879ca6be20ba2ff0cd8204170694ef84c04e71a2637a55d87bcf8f1aaff3d4c7193
2578947dfc345defed36b962caebd1d4bab98f78906fd87649d4a45309b9351712b815984850ab
6a6b7a571579fe45662dc5aca8b5666113d249e28dcaebeecb6e255cf7dc8aebdb622c42b539aa
99949bb24dcbd84be583e51da79cc9cd6bd2b4725c3342954bde2a67b2a59896bbaaa858155bf7
ea7231ddddb05c8ae9ddab765ec55dffc2fd225883d4a17a65ba93e09878c8a4cd70e6502c894b
cdbdd2b1bad058f53c8c25750b288b2d8afba25a6ed5dce55e3dfb1815e421ce8f79c516b6de1f
46eed6bd3e59ab2879b1f1f880af23bc2789db7b8265de81e36ad295dd3e6a96b8bb878b73b00b
4a913eac1cc3439bdd19b295e0ee2dd191512d33aa289307b7987238705f9123857f4c28098e6b
b27835992a855aa6e34e2dc1c2aad6aa79a8a917b3aad69a954dc8c783d3ad79715a496a13cb33
a996d6b6184b1137c754d3d54c66f220695a769c4a2665fd5bd6a4cec0b87e3917dacfaab79205
0932592f664bb7afd9a15757da62dd9d37d9b2cab2d6d48a6b906afcb0df0f3fbaa33db94841a4
98f9334ebdb9d73856274b615ba4250fd5bd7bd7e6cea8f6ea6a292a799052b8f931afd8c2d6fb
834e94d8c494c95a45b53416bea0c41d007577946e61fa5cfb8eb40ed395d512ec1e71303d1d2c
c67dc3dd6907fe9e361837e1f67e59a75bd661b7cf143ff9aefe29a0514331e51537f3fa981e9f
aef2d41adc1c4a6c11bf326d62cc954d534d30b9b6aae544d5b4898c6a31abaaad59dd8494c25d
81acd3f64949307d448a39a73597b6c59825bdd8e63029ed0aaa999404e169c37f0c5eb2321332
99dcba26f5c7c7fc7b4712731809739dc9a4522aa664c9afa8f80853a6d6efae7c8b5e3d4916b3
a114d216d307c78f24f22947e9a89916b6a6525e8354825ad4fb5287529ca91b8c79b6a5183ee2
e7a1d4dce3bb6e05eaf5cf29454b63b5e4412fb6bd4cd112c9cdebdb367786caa49b38eed5d552
54f260fef4f2635e091bb7d01fc64d4c2b914dd8d61cb758a828a5dc58f88212d1b6ee82d2b14c
afdabbb7f8fb86f0ba72d0f50de9d9e1e14349ad2db906d9f166040db2926488dfa25a4c43bfe2
1f7496ecbd7189bcf51b419a6a82c975552de7e0c64db4b9e6e3335b33b189a8f8baea6cc14d31
83ca718fef2d96b6c5983e688e493593a9c68ab5d67f26935bd7a4743f9d3bb32a3da8292b57db
8d5792cb64b998e653a56e3f5f6badba241b2d1b4d16b35a8a547fc8e65312077d6f716b56d7e0
e647323ffd5bd2a4caaebbdccce0c9db3dcd3a576fac721ee4ddb086937668ee36f1c72ba5a8e6
21ae79bfb06ee2747fa8f6c96a45190b6b069f4e6adef6e1d05dcc4ced1b4cda1efde15f9719fc
a9480eadcb595fd3a92fee6cb6f4b686e7e1415fc3e376fdfdbf51b5983a937d7730ab961bc59c
e6665b0e0d669199641373c399e172d8a46a8236a5aa96cb70df976ea254cc162dad59dec459fd
d7f53fc60f1ed47f4ec14d31fbd7690d6a79d52f991a6eb1525b28d9e6a86672adc62adbb82665
55eae0d61fba5edadd6c42ef5f6b54af55eaf68d76e8d535a5522cef0fcbf78bb635b8b7d54a96
a87a28aed2ab5d72ac5ea3b19485bd6edbe6160dbd3a9b8d95f250ea0f6d3d6a613de3ebf1a36d
f97ea60e14d2d5f49e205f25d572edceff8979f751928a6a1957984376e9577348d2df82661e65
7483bee92700eb7c7eeb9e4fc3eb9fcc2ac52cb766cb267463f5ddabda7f4c63cd3edd62b46d4d
9a90fae9492ffa4bbbf95307dff2e7ddd8a15763450b8fd5ca5768ac2f724a02227eb4adf676dd
fb2fddb3da13ccc30886fd7ffcf3569ef4f759755a9c04c3d87a984a25b9c9c9f23c54913ed89a
41b2abc5c5542b3da97a3f74c7a35ef3fbac98e3a07fc6522d78bc61cb5549ace3b7a60a836658
b798c9d66cdbc4f9a4cba2a3431329c6a7dbcb6958b9bbac1846aea29449692c3beabc996d6bd2
ec626a5f53ebd73bd4a57bbf98e0bbbf6644732b3bf4eae596efbcc6f2fd62f53d2b7128ae5a72
ac766dd458cbddc3b1ba2d0fbaf946e90b156a1ee2588d8712cd2439fc183ab4fc9e72ab9f4bd4
37603b05eaf8a18f38d319d7fcd0ac5e9a6656f5dd6f6644e1fa035c9e3ee5a7a81caa0387eb8a
5375a998a3f3bbfe5f3d6472bee62035e57faca5e94864e20c39028afee8ffb4574db09c9cd29c
4dc415dba254cc062dad59dfc4585d47f3ddefe4cefc93d911afe156547db6967587b6a86652f2
d0eb2bfa83a2c7bb496ec769b2694d9ac655df19d4395a9e24a0bea51f5ef59f573cc66b51316b
76e8d58b2cdf7997b7e61afd416939142be5e65e72ac6e6fac4dbb5cc93d1cabdbf260c371f5ee
ec83e44a3d4adcacb1707f127700944ea6bae96d668f3893badcc5ebb4c934c91fdd4ccae4e520
c1bea4cb1b5ca122bfe5f98bfd90a40f97f61ffe5a8a29c66cc4c7948a54feed222b534790e075
b91396dd5635c1e4daaa9eb189a4866256555ab37d13b659e39ed0dee2194bdb625c43a962ab99
cc5485b7ce549ac43633991c6c599343738f6b1e2a3679b82b64b2504cf3a972b7afd8a157bb92
c56c28c58c3e2925daa035cb6b901c4a8625f3f2bafeb7b47863065a7af598a6b48b6534355631
0ff5bddbdaa1b9931a7a75b514953c449b389af4b6b0f5fea0ff183e1b2c43a61a2a4a6be930f8
4282b16df3bb950cf0a86f87c92ff7fb38bf0c978c6866668bfd4b3b87335b54faf59f43abb69b
5fa7974343fff634330fa7e76231858cf3a92d26de2b522b746a497e1a0bf37cf466cea9fc9cfc
e1bd6a82e5966ea2a1985595d66cdf841917514ef17c44f30371f02155d8f69ceed016f54c9a5e
1a967dbcc06ba0d22cdf19b7ac4939c4d98967728df5f09b5ebb558a99b343af5ec30a7d72716b
aeb086a0ae4c270f3fded2dc571fab1b1b6bd32ed7e01e8ed5953cf855a4debd66d6ca1a3deae6
8d857b93b803e08da5be387e716f8521c0cf28314e00e0113cdecebbea198763f5fe385fe02110
6ddfbbcf7f28f19f8d221d807be0000fe013ecbceb9d713856ef81f3051e13d1f6fdd277d43793
bdd2532d3f0d395cfa0b1d0078009f60e75de38cc3b17a3f9c2ff090524fb7c17df9f4d3bfe4ce
598e933b9d1dc0dd62e77571acde015d0e8fe9fec6b6c7a7e64ecbdcd18235c62a1ec0eec50cda
a571d3d5d65cdadc580f6d0100c0da7263dbe6e635323b4aff4676af275d992777dbecdd431e76
a0e2b020ba9e75ebdf3bf1451a0b0000dc8d5cb46d1e6d238f7e5041d5cecfb879b14f6f72ee16
845b92479a5dcc4346c7e5b9edd2fb6a6bd2dcf783b60000606d99685b3f00491edad45ff988b5
7d9ce5c1f2379d2ab7691e663cb0604bf2f05b799ef643bb870e030000be924cb4ad1f7cea3cbf
5d06b901000000cc9189b6edec113da82983dcf724b896abfa3401491fdf06d55dcfdc9ba456f2
e05cc2e8a66c1fa4964f7dbcea7f0fb38d6549dd58b4bc89eb8b39de6b29910d7755fe236a3719
89cf6dc2bc9eeb00c78fe1adb51a6b7af7cdfb54bb6c5b8c55edbe28bf6cb8b90d9e5aec6edd3e
91586e46e61667486633ec54e6dcfc8b6c2946369fc9770100f852c27b92b8e7d160c9c5341b92
b020baa62dc86421785224f808830a3f7a93655664d0948763b495e69bf0671bc2aea165130b8b
398680c965584f324df232c44c6b4e72098a9bd01535fe5bbe0fd802aab7e4df2b3456aa26d532
235aadb5c510a1da8d46b51184dab2d835c8bb1ff6bebf1fddd17e3b92754a31fdaf4c6a71f330
c9b545ad1482681b00002b7107407da694d3b339b35e37fab58edc29df32014421da0ec22fcb1d
ffd3249e2b6ca8209f07bd38119bc47cb3aa53a2967413346c62ad6216b2215b9c8a3f46638930
abda9a9904e54de8328e35e0a534c9c22c5fdb585293d307c78fa49b26a5a52da4bbca56dc7209
d50aeee624b17dc506b8ea85e15708f3f1693d639e6d29868f245b24d3162da5506c6688b60100
4844dbfa542da74f732a75ceefbbabc6672687c9e049050472cacf857dc1a7e2e0a6553e0f41ce
73a17f8114c18db126d54dac57cc6c36527990c4618528d5d64c26a86d428aacb3663eaec76e25
b1fa605c52b3b6d98d2519f3d7566a9a58735b48942f23d0e5ae1264c0fd53323ffd5bb6922a7b
f0a562926c8be652000080516adef6e1d05dcc4cedfb9cb4ddeaa0671b9f9ebb637c89a7b9f4b3
7fd571865d5ef54bfa062c2bdae1ce89a54dec554ce92dd6e5acafafd517daaea7b0097b8141af
be5f9dcd43c5ccfd0af57d75e44adf36d59abcbccf585ba8b92d5eccadf7f43e784a755df96260
16994c1f706f1f942cd11ffe3a833f2bf6ea5100007c227eb46d8709e584aa4fe732c4a596471b
be52a550c1c6ebc7bcb1643c1e13523f3de94507e5e64f1d7ccb9f0fc744b44afc7545ef9e6ffa
0ba4dc12fbf934bc0e0000ee981f6d9f5fcc295c1e6262c6d886fb138f7f3e90f3791826cc05dc
97d3583467298c6f3ea81d8a19c4857a8c596d77d548b7b409f3f3cb53afc783df55c12eddfbc5
04dffdcc81db0289e0fd3ca84dccd5d2166f6fba0867b5bd833f4dc5fca9f6c7c480f702fa81a0
337fbffa223b0e00002b8966921c7e0cb1858cb1957e5ebf7fea6bc31870bb718b0a0d54b1fa57
3f9a51af1cfd6477434f8ab8c20ec5349b50ab9be6f2f6dd6f6686830e7c57d1b0091555f73ff4
6406b931bc8ac20faffacfd59eca24f1a813fe1edec25aad686b0bb55af5a7fa96a816955efd19
7c519c7ac258093a5c9ec35de7d1ec173366c834f7289944ae167e5902007c7951b46defb4adcf
eb8f3b69db5201b77970e09b7f29d88b7951ff343f4e3f554b7222ec6dc904659575379f416453
b04331651332f5482f32e3e8bce6106c75137a90bbd793b625fcd641b6fa534688577232d3366c
4daa7073ee17d17a5b8ca3d7b26249fffa9b29ac22df816d4f18677649b5b47709457df99495e8
29d7aa68fe558f653bf42800003e9720da369797c988a09ef6bae4b2b0fb711e66b8aa807b1a69
3b277efe3e9901c5fb327e5bb8d20ec5549bf06719e9d9474bf21cab6d427aac9dbb327c4591f0
742597a3374f5ad5e169dc5cab725ba830fa4da7d157790af977af6fa1adbbedf8438d90e91c53
e266aaeaa64f993963f3d6f1283b0e00007723710740005532befb483325ccb8f8bc0930000060
a96826098084831f58cb1cee5527ab000080cf88681b6863a73bebc53cf6e57c5a73b20a0000f8
8c88b68116e7eee447d6a7e76ba64d030080af8679db000000c0467263dbe611923251f5f831fc
6e0e000000608e5cb46d1e6d23cf0ab177e006000000304726da9e1e6dd3affa4c3e000000e00b
c944dbbd0eb1cdfd169c416e000000007364a26d3b7ba4d7b1f6e33fbf1d000000b885f09e246f
f68ec2d1f2711cd20000000068108d6dbf7ceb9e4f7a3cfbf95bf7ed594f2639bf74dfd4bfd5eb
44db000000c00ca999244ffea46d6e48020000005c25156d1f0eddc5ccd466d236000000b08437
6ffbf016ced59e960f3dce0d000000a0993fb67d7ec94eda963f01000000348b66921c7e30691b
0000005845146ddb3b6d4f8f9304000000708d20da3ea8ff86e7b4f74fdde59dd923000000c0f5
c2a7db000000005849ea0e8000000000d640b40d0000006c85681b000000d80ad1f6d5faeec33c
f7e7689efa230f06fa389ab74435010000003eb95cb46d224509138f1fdd5f6fe645b8c6db235e
9cfbb6fce1dec3a59a000000009f5c2eda368fb69130d1de811b0572dbc4826a020000007c3a99
687b7ab44daf026f22c5343d50ed3f0028a8a86a020000007c6a9968bbd721b60a14bd416e042e
2a74965aca545135010000003eb7f4d36ddefeeade0efa1ffdb1fbeb4307dc7b1b2f31b48b4c22
b774c69c7725b742ae47745f11f2bafbb22aa65d43b07e00000060b930da7603d060d9ef7e1a51
a81d6c3d08b56599c265f9787065a779715a496a1304dc0000005857626c7b1acf3621693c48bc
3509a683edf64e28ac129407b3f57d54fc616c59a78da725c1f49183fe935baf000000605d8968
5b07af12779a18d40f7a7721b16ff36073223a376b7087c3f598bd0da683716e43c7df37993303
000080cf2b116dabc05422d169907b77325c3d2cc93c8c11b95d82b1701d5edb0f9ac4e148766a
b9c1570b0000007c5e5eb4edc5b8c17293b0db0d8b9d691e924f3bf29d9c79e24e2fd1ff76f34f
b40d0000805d8463dbd378f68d266d27c9b59b435e8281ea4cb42df9d7317a3c6fc4ac21984902
000000ac2e8cb6a7e7b49b90f426c1f6e12d0c9dbdab1e6564da9f849d8c9ee55347138b070591
f03dd88a8ada6f525e0000007c5661b4adc2508941c3d9173b924920e11285d7c9c50b97ed8c11
6716cac0bee52f44db00000058911f6d9b1854e6431f3f6e39d72208b8c39c3801b7bc65d307e1
b28c61e7ee6d22efdaa5f1162800000040a3706c1b000000c04afec7f0ff00000000d646b40d00
00006c85681b000000d80ad136000000b015a26d000000602b44db000000c05688b601000080ad
106d030000005b21da06000000b642b40d0000006c85681b000000d80ad136000000b015a26d00
0000602b44db000000c05688b601000080ad106d030000005b21da06000000b642b40d0000006c
85681b000000d80ad136000000b015a26d000000602b44db000000c0561e2fdafe57cd900e0000
00b8b5c71ddbfee77fffaf7f1bfde73f86173d3ffdfcebefa3e3f7e1455735419befc7df7ffff5
e79f86bf00000080d18346dbfff8cf7ffb5ffffdcfe18fe84f4d45d26e04ac22e22020ae26a898
42f505813a0000003eb75f7ef965f8d783f8d7bffef5bfff43ffe3dfffebffcad491fffb5fffae
fffe8fff2d7fea7f0fa1f01807077f2ad504157a3c7b486e3ecbd836000000628f38b6fd8ffff3
0f1d6bff7f1264db7ffee3bfedf0f64fdfbfabe0f7f7e3f177f9fbcf5f8fbffea942e49fc798b8
9aa04645dadf55c43dfc05000000a424a3ed61a4d70a076e83f7dd116133e69b182376c6828524
14d70c0cffcf7f1f626deddffffd7faafffde73fff9ffc39c4d2bf3bc1f09fbfffaea2e99f7e92
0d5513000000002b88a36d154a47d1b5094e07f1fbdf8fd30bbfff6ac688bffbe1f64f3ffffcbd
fbf3d75f87e85647eb6ee49dd864d5fffba73f4fdb6562e63fff541999c89f43345d4d00000000
ac208ab6c739162a609e045326dc77cd5b4e8c2a63c4ea8de16fcdac53ded07ffd7cd4a1f5b412
bd0a138f3732c3dafffcefff65ef44f28fff947f96227089a64bc1743501000000304f146dcb10
af3b5cadb8c3c07ffefab31b7cbb6f193284edce8036ff96416f45426f7725f2567b9c3b4ed9fe
c77f8e3700fc7ffff55fe6c249000000e09ec43349864b07c7b9d9c9291ecea4ebc4fbead521a8
36beeb716ef39a61a2ea71edc2ac63cea8f2bfffd7ff1d6e4432fcf11f9d9eb2edcde50e99f547
df0d1cd504000000c03ca9ab2487391e32f82c71b133cb5a47dac79f7efdd9a4f9fefde761c8da
a53ea03f287343541a67caf66aecfdfff40d00fff98f7ffc73bc565231217310bdcb9f43305d4d
00000000ac20156d0fdca05b87ccc6f7a30abc7f3fa6626cc774ada45c1f394ed9b6feb4d1fac4
9d9f32cf106cffc77f0c43db89b9e332d43ec6d2d504000000c00aa2685b05bdfefdfb1201e814
a60e573c86e3c4369c5531b53365db1806be7ff5b76287c29b38b7d6d6974b9ae748fec77fd9b9
25e3e6f5370363bc30d366a49a0000000058eedb2fbffcf2f7bfff7df84b89a26d43bd66279664
6fd66713197645fecb5a651b65fffad7bff4f591f68624e23ffef7f084c9aefbb77ffb37f5bf71
46fffcf5677748be9aa0285d04d158100000007c7ad1d8761c2aea591ff6253f22950921e9d0d2
8c61eb24f1946db58dc4466644a8ee38b64ce11e436dcbcbb5d96410495713000000000b4563db
774f8f6d17c9d836000000707385ab24010000002c42b40d0000006c85681b000000d8cc2fbffc
32fc0b000000c0aa1e776cfbfbf4f47825753b3e790ca648deaeaf9aa08dce49eeb6882b6d0200
00000fe951a3ede9c1344245bcfe0bc1edb4d5fb41405c4d5031c5d1d9287ae926000000f0e81e
7426c9f79f9db875087c9da83778e58a04157a3c7b486e3e9b08a3976e020000000fef51c7b6bd
67accb73d89d47ccffa41f18dffd7e1c9f5ef3e7af479d7c0ad1ab096a54d49c7baccf60f12600
0000f0f092d1f6300c6b8503b7c1fbee70ad19f34d0ce03a63c142128a85f32b7efaf9a856e0c4
df43a02b0fb3141290fff4936ca89a60b91d36010000807b1747db2a948ea26b13390ee2f7bf1f
a71724e6fdfedd0fb77ffaf9e7efddf40c771dadbb917762930d6cbcfeebcf9dff147613d03a43
dd9afc3984bad504cbedb009000000dcbb28da1e2740a88079124c9970df356f3901a40ce0aa37
86bf35b34e7943ff6586a29d95e8559878fc6ac32a8b4ca85b8a74ab0996db6113000000b82351
b42de3afee70b5222f8a3f7ffdd90dbeddb70c19c276a7279b7fdb891e127abb2b91b76607a136
5c9768fd57ae3f040000c09d8967920cd7f5e9d91e324d231104ab007794785fbd3a04d5868a87
87d70c13558f6b17661dd70ff9aab05b67b972fda1597ff4ddc0514db0dc0e9b000000c01d495d
25390c1acbe0b3c4c5ceb8b18eb48f3ffdfab349f3fdfbcff6dac489fa80fea0cc0d51699c29db
1b3111ac8dd7fdbf84fc3944bad504cbedb009000000dcbb54b43d70836e1d321be6a932bf1f53
31b663ba5652ae8f1ca76c5b7fda687d22d1fd754c1c6bc3d8c4dc71196a1f5354132cb7c32600
000070efa2685b05bdfe04e8447438c590e3e589c120ae8d35554ceddd9b4f1906bec369d6f32e
93f4528f2b9b723a6cde3e6f72bc30d366a49a60b91d36010000803bf7ed975f7ef9fbdfff3efc
a544d1b6a15eb3134bb237ebb3890cbb22ff65adb28d06896c041f8f53fcf9ebcfee907c354151
ba08c2e664d926000000f0f0a2b1ed38e6d5b33eec4b7eb8a8dfca4d013163d83a493c655b6d23
b191f46ad28201772f8b2278496d320873ab0996db6113000000b86bbffcf2cbf02f00000000ab
2a5c25090000006011a26d000000602b44db000000c05688b601000080ad3c74b4fd7d7a807cea
09f23f398f87cfdeaeaf4e6f25b176a3ba891d12000000e06e3d6cb4ad636037f81c9fb3335241
aa1b22abe4b988396d0a72b3216e75133b24000000c05d7bcc3b00aab053f322d19f9d3f865879
0c94833febccfa25b9f96c22c6ad6e628704000000b8738f186d57c34e49e0be2faf5c33306c3e
197fb0ba891d12000000e0ce25679248503709c3bbe07d371e944167f715e10c168b6174da9819
3efef4fdbb4a9f7a48e54012a8150f7f2b7ffefefb9fea8d9fd68a53ab9bd82101000000ee5d1c
6dab503a8aae4ddc3788dfff7e9c5ef8fd57fd6cf2efdffd70fba79f7ffeee84c73a5a0f866ce7
04dc26dad481a713f57bf1bd24081eee6efe5c2d50ad6e628704000000b87751b43d8ca81e55c0
3c393ae3ab8afbae79cb09ff64f855bd31fcad9975ca1bfa2fb99e715a895e8589c7e771837c3d
541e0fa87b4ca0ba6d9c5addc40e090000007047a268db84737e243bbe28fefcf56737f876df32
6408dbbd66d1fc5b06bd1509bddd95c85b334348159e7763bcfeb359b5779924000000707bf14c
92df8f325c3dccd2484ef170265d27de57af0e41b5a1c2e1e135c344d5ce1c10c5ac63ee80ed90
4fedcf5f8f265e7727bc44ccfaa3ef06abaa6e628704000000b823a9ab2487391e12cc4a5ceccc
d2d091f6f1a75f7f3669c671659ffa80fea0cc0d51699c29db1bf1e34ff397894b27f2e76a716a
75133b24000000c0bd4b45db0337e8d621b3f1fda802efdf8fa918db315d2b29d7478e53b6ad3f
6db43e99a696549860de8f43fd283431775cc6bdd70b53ab9bd82101000000ee5d146daba0d7bf
dc3011db4d11e0f804c76008d6468a2aa676a66c1bc3c0f7afc1458d732e931c56313d3c52a66c
4b14ae0d9bd7df0c8cf1c24c2f23cb5437b14302000000dcb96fbffcf2cbdffffef7e12f258ab6
0df59a9d58929cc9add944865d91ffb256d946834436fefcf56777c43d4e1124284ae750d87c56
37b14302000000dcb3686c3b8e79557c37bde4077bfaaddc149061a43935655b6d23b191f46ad2
bc3c296a8d410c1aa488132c57ddc40e0900000070d71ef1c9ed000000c043285c250900000060
11a26d000000602b44db000000c05688b601000080ad106d030000005b21da06000000b642b40d
0000006c85681b000000d80ad136000000b015a26d000000602b44db000000c05688b601000080
ad106d030000005b21da06000000b6d175ff3fe4bfe311751b9aa70000000049454e44ae426082
}\kerning2\f1\fs21\lang1033\par
Aof\f2\'b5\'c4\'c5\'e4\'d6\'c3\'a3\'ba\f1\par
\kerning0\f3\fs22\lang0{\pict{\*\picprop{\sp{\sn wzDescription}{\sv Image}}{\sp{\sn posv}{\sv 1}}
}\pngblip\picw14547\pich8696\picwgoal8247\pichgoal4930 
89504e470d0a1a0a0000000d49484452000003930000022308020000001130d81f000000017352
474200aece1ce90000000467414d410000b18f0bfc6105000000097048597300000ec400000ec4
01952b0e1b0000a3e649444154785eedbdbf9aeb36b2afcdb59e6776f04d3289773289e3665f84
2f62a977eafcc4276ee92276eed4adbe085f446bc54e26d94e269913ec09fc15aa481000415491
a0284afd7b8d67b9258140fd03088220d800000000000000000000000000000000000000000000
000000000000000000000000000000000000000000000000000000000000000000000000000000
000000000000000000000000000000000000000000000000000000000000000088689b8f3f9b63
ebfe3c7e347fbef19721c8202083800cc25d6400605dee22ec91414006011984fa0c37e66bf77f
c71349db5c2efc67db9ccffc65083208c8202083701719005897bb087b641090414006a13ec38d
0946ae870349da7ca7bf5a12bbf9eefe8a40060119046410ee228305776dfd67f34645851cdc97
498af2a81948a8639aa14b72292f25c497f5724857ccb88a0f52743687b7e9125419fa8fa97d7a
f2d623b8e48f63f7a944af665886379dff52d7224c234329be307317618f0c023208c820d467b8
35c1c8b5750292b4d1703b04190464109041b88b0c3a87e6958e943e4b83064fe5a1989a21c3a1
bb3965826f664d0d22b3bc25f9b984b4805932c41cffcbd9fff0eaec1ff24623c273f33cc71aa1
0b0edfba3f04931621f30d65e42ec21e190464109041a8cf706b8291ab9f136e9da424760a3208
c820208370171954e422fb4c3dd42133123abf345fbef4e9c57dd37e733d9a47cd404479829c9e
d75fd34342c2c35f58591a1f1b87645dce4bf31c97e086953165194a5c9aff3a91dacdafc12055
ea7d89d52cc12e1846ae6df3adf72c61d4c26228d5172a7711f6c8202083800c427d865d40d7f1
e99da33ec9c4093220832464907447198c5039943f73439c6f40279376ae527f1b5acd40dd5ff1
3ebb94f011df6d9743ba4fb92a6834562a3346ac94e495fbfbdd24ab2a83aa05332ed328a183f2
7f3487a0525763f08d518bb2a12c5a941131b269b3a846066490840c9236cbb02fa48b74bddfc4
dd25641090414006e12e32e8f088c78d7eb884ae346134189291d0b02c52cd20121604eb6b974e
5372c921dd11b901997c695a9d399133924a9541d54208ea724559c4f3d0b164f9c089342aa5b3
452786598bb2a14c5a68b842ae1cb4c8202083800cc21e32ec807eb5c053bcac41268a43904140
06011984bbc8a0727c75b784dc52814b73a2c3dbe64005057483514ed2912577c0d50c4498c7a5
d120ec7472ffbe1aafec45653397d11d2f59bcf5146b3a4f863167be41cf8345328394368f4bf3
2e0b0678a9c07bec4da316113943a9be287317618f0c023208c820d467d801fdc8953a4ae913a7
96352083800c02320877914181474897773ad421fdd4b7e9ebeccbc92d8b2cf4666a86292ec7e6
7469dad7fedef72da897e17cea2c497638ca5f3339bf93539be3a169e572627fdc45d82383800c
023208f51976417af11d269e31460664e8123248ba9f0c16dcbda1e4584afef0ec0de81035435f
c5641e2ea11b29f6b7b6e590ee886c15fca569e9555f664224952a83aa4580f8c5903186ea15b3
f34d3a2a41b4ebc4306b5136945d8b2c7b886a6440862e2183a4ad32ec0bd7978958b75b39810c
023208c820d46750995a92df15951d0c85a81944c8421e2ec1cf714aef290f4b7547e4aa906ce5
7a3de1ea55cff8d9a6920caa160172b84db40092415cd9cb262548bdf4b7518bb2a1ec5a4ca186
1c3208c8202083f018197684ebfbe4529e3bbeb1a8c8202083800cc25d6450e0a3d2ee89bf0c8b
2df55f6a06e90d0b79b8043f6a941ed309e0d51955e1b4a60cd2c31a90d15b98bffb4674245419
542d02ea47ae21522f9566d4a26c28bb16536c10b4c8202083800cc21e32ec035ee7eaf7ee3a90
98b9650dc8202083800cc25d64282347b9a7b242ce6ead27755af4e38a74c3ac3865aa908d5147
8487cb4b135e9e29af89f30bafbb0dc6a332749bdc6975420622a38579005d89510b8ba1acbec8
7117618f0c023208c820d467d8073472e5f393bcddab7d1a1ed41840060119046410ee22830675
4fd9a3dc4342fceb4db81cb507bcceb31f027be9b7e5efe0fdfc0b25e832dc82b95a2c3094c25d
843d3208c8202083509f0100000000000000000000000000000000000000000000000000000000
000000000000000000000000000000000000000000000000000000000000000000000000000000
000000000000000000000000000000000000000000000000000000000000000000000000000000
000000000000000000000000000000000000000000000000000000000000000000000000000000
000000000000000088698fcd9f7f366f87eee32cdefe74c7fab4ac903149b17fbe75dfef9c1a4b
3e2c87cf62939b04ed0386dc8d02068d77335636f51e7a98c7ede5d02e1e9aafddff1d6df3f167
736cdd9fc78fbb19752d804ed5493c3fb1d620e1f0e61aff034702000054f249fa499c0e04d861
078423d7271abb36970bffd936e7337ff9781c78d87a699ebf345ffaf47c94df6a79f1653e530d
00dc01085a000000f74330723dd080eed27ca7bf5a1ac436dfdd5f36f88e4392763b49dff2f4ea
f974b39374d55d8cb1a93fdcf5c69538bff080e6a5fb08c027e7316e41ee418b47ba99bbd37e92
6fa276a7895c9a6b7c9c0e04d861070423d7d60d57793c174cbe2e667c471e5c05ea9eae397805
00000000d80dc1c8d5af1070b39232f93a87ee4284d38947bd6e1257908bbfd1ba101add7eccbc
4def9f26993a307cdc44d6ec76f4b3951faffc4996aa8c72ca4c804fd155e978313b7f63574164
cb083073e8199ada79ac6d0ea3e327edd053b064786c36836374419fada540c9d442a10a35a202
6785ea8c2b714bba830cd9d54b532584f34693b5c45a4c455449485b091dd998ac71966a6a335e
c7f4404d0bb133c92cce0a2dd61de54b08348d0a142aec20d5191b6fc99bf1af735b8d306949a6
d0b28c5a54b5cd9e29358d32e8c43244420611158a31d643a560eab0e46c06c79c909302978544
867845dc0b9fdc87a541fd379e2943adae6682deba8582bb7bbca87921635de6daf9da7600b349
5c12a6a90888189d78c233ba2041197a51f2e4c26f82514c481a6ac965186a6421a792644bfa6b
4949095183e16f4a111c9fef27ed6cefb2473248d71f358fb21d08cd927a13cd95600a951ec5d4
845685125162a8e3a890d0d41376e8ca3494d0c5f928cfe01f2e244d3e2a2c425a4a28c7a4dd59
92733448bd7ae3d5b490ea3e580c973e9aa31ff188ada4847018c469564495d11bafc8303fe422
2155ca96ec6d95245f85a50b2a97e0502d595473856e90606ba76956cb52d14c5ddb4f8a907d69
d2cac246b02e72a648cb3718eadaa703bd75136577139ab3b2196635bd6bdb012cc1458f44095b
3f3a8ba8c42db0f35fdc4774d11978d135d4d139b28034bca1843e9493963f8821194655882459
05e9a7f07ba93129303a90bfc987a61821a76041009d4406d13136b56a07d59203130a66559005
c44614531baa900c9311d52b151a47ba1e5fa4182ab11efddc756786124486280f1fe53348fe41
c8be6bb357612921b2127f139a6586b326825631b50125e4342dbc9d298b142516736288e9fa02
d343022167d8619a6c211dbd0c056faa6d53456dbc246128deb86511252d0c25a896b4a8599641
a5be65a9a8a61ee09f869c3d8aa1f828f955ea9a35909a8b5491ca3ecb50cbd4d490c3a5461132
6dddaabbfb030bceaa6f7a03d7b103588273bc7891bd121b5fa38f9221e502c2059f6f1e7c48e2
e332d1e14c14281cca493085a1efc986579634e758e68908764c0c0208bb0019c6a64e8a32d841
b164c89482bd186b75b519010c5594224a0e8fed1f9d1ec441a3f018504be8c5ce7ad9912b410e
e94caa56612b616cb7c8655288c559d3417bddc6ab69116616fb0c7f4bb163ada5d2b02bb3db61
9a48ec0429bfe04d731f556046e365b2bf960f49c8642e5bd2a6e62c195272a69602bb7a555f18
98616aae2e51d9513614ff4aa549b135616941d44f659f65a8656a6a845695aa87bf83d65d72b7
eaac359adec075ec00e6d0af733d1c9a0baf6c759708f317b9a61c32cddb2da2ed5764ca3e06a7
789d4d09deeea07b802c0b3f55d6be76a123e9d57dc507dae9838f92acc4da392fc97225d50eaa
252d9cbb4a5fa9f1531515ed5f52c6d4862ad4882aedec268f21be2b76b0ec0d57ce23cdca7339
bb1addd3903d6a156a090a6b384b35758955422edeed246bb4ef7105c9c7758256a3e4cdfa3eca
68c9fa4eaca66daed5156bd4b7ac129bf5930767e1d37373acaaa98a2a43116bb42cb57597dcad
3a6b9b98dca48701ccd7e1524cfceafa29997a9969fae4b1212a36b92891707ce57ed00d94b541
c3f63853bcb94e44b4783e75dfef0d31b588f776a3e611ed0c323d573785c5d46a15fb8fa89d50
e92ce2314c5d6f87fd53df89add23681a01a8acebcd4b668ac73d7137588070176d88aafced6ae
6f92e710792bf2cefafdc705bcf0e0b5fd46be0b38f39e0387e67874cdf59dcf85eb7239f59207
c95a0fcf1393eee56bdff06d5bb75dc27239f2155edbfc3aba6d516587599c83c2e5150f166ca6
ee28545113517c819e86e815482647db83ab31993f28a396608dc965ce12aedf78576f59aec0ec
eda31a3b5473ddb639ab656559a96d6ed005d5b7aced9836145d13bef079f6de07af8e6bb6ac7a
77effdb40866c0ab050edffa99769e54cfced5cf63c25be777f7af9bb939cfec5b2fcd3be50f16
21b4c7f836d6d94549fb3a641028dbacb8717742051a1172f9e10995f0edc74d2a8702cc64a8a8
023ac1d07822d25ab5836a4903a47b527e7a67d640d9d4c62a6a238a2e8b4793d6abb8c6c1be20
530f371f7a4dad233f5b09e5985cc559c4151b2f53dfb2e8407fee3f7eb8800fe786d7b203b130
42eafb289b25d54e4c286851d536e7a85963492a6e79cb52d9b29fbc34cffde0356b0faadadd02
ddeb02ca155b561ed5ddaab3ea9b9e81abdb0124bc8dd744cf22581415a664b58043e6cffdbae9
39f8d6eb936c8233143521465295949311a0972d9b5cf6518663bc483ca270a7205791d51eac63
247c5fdad0a96976d02de9e1a2c60aba38894b70c97e5b4435b5bd8abea854f8b1a1fa3207434d
88d11d65286132963c595f782d2c42964b18a9308ec919ce92d2a6fc38656a034ac8695ac8e162
1351478e737f4b7f95b552dcac66d8a1402e66ba5a167b3396b3cc5c4b8669a8a5a085a104dd92
16350b325828b70b8b2f34aede4f2642f61a8d8bf792d8851f23c2a485cf32d4323535f4d6ed3e
0425fb1454a13b2b5bc2ac90f35cc70e600e5f9d1bc879b23eba7d5a6d05dbf9a5791eb9b6bb36
a25fe75f195f8ed18aabd373734aee14f0147d523065b356d55ff80a726741165c77500659bfc2
50c90b6fc9c5e5d4d29736dc6cd2eca05b52839c1b5946cc65574a35b5bd8a8a8872628cea2533
a5dfd440be8897dc905e330c45944b30c464adb33cd76bbc062d2c449ab2734349d7b1432cea6c
2afb288b25b596e52868612841b7a445cd7a4b56b62c8dadfbc97357dd5bdd08757bd669596534
775f7d7860600b3b805b41cd727cb102c06210519bb15f53e7a68e0000003c22c1db5f37e0f0e6
e677aff17807f89c20a23603a6060000f08970bbfe62d907580f44d466dc81a931e70a00009f85
6de75c6bd73601908088da0c981a000000a8411e277ca889164c1ddd156f3213e913667faf04da
0508d9201eee36e41ef0b408404a38e7cadb94c8538deefe204ec3774eb74907fcb803f6e00bc4
c31df1499c8598dc0c981a3c10e1c855dee4ce3b4f3cb56bbc8f008087e6c5bf8b25deb1050000
0000d72118b9bad799c8cb125b1ac4763bbc82fbc5ed7847832aac4ddc0157f585f1fe20e2e18e
6ea47e126715d4dcc059378e075e9010a505af013283e60f1e8860e4eadebe18bc0356265f0100
00007075dacccba80100238291ab5f21d0ba712b4fbece647860e5adbba08c2e67e3d7fd65ae74
d50c41158b77440f9faa895e5512081ce649a52808395699bf198baa188a29c950243c90525abb
51cd6964a2824c279b258545855a48369fc66629c920461e2dc9a2ccb3fc6e922170e8bc0c0614
5ff40cdb4e498a152f6821e5cb1bbabb756c9282f39f49065b54e79d25c42550baca7b80546779
f81bafacc55016aaa2dac00267514a4d5dc8a019ca134a32c3955c7521cee5a7b29ab39cb5ccd4
2b5611feba20e6bba9504eeef4db368751216a153e43d98fd90c8e9ac6eb236aaa6dd22fdc6a94
a611cb90942094fb49423194aa668d1d84a216263b003b49708769aa0f4a19b95cd2e0398eef34
8591a76650ab50c9953084a6b4c0e3284fd8979585f46dd8c3df44362c6b61914143e9aaaaab90
e6f7e13b918fe6e8bbfebe90e4042f6996a9a5930a3b0e297386b72d328427adb91942c4adc59e
9452a6354dc483afa5acc564cb0d2ca9cbc09aa62989ea72c0e4b4b0761d162664489d35ddf42c
8652a98f6a95650113652b67d00ce5c895900ffb1c4e853e7864501886abfc5d56537756b5a9d7
a9a2ce50635f24e672a855e43250f2c5964ded28078c8a6851ec27a5e18c8d39a8ce85a4c970f6
1f6a59642835ec67d881d0b4d0ed00e6e26c2a6d92fd17756d06649c31b8b97761d27e860c7d94
f8d8523348ab2e54a122420ef9a584f80ced52d0378954fe0845482e219287bf19f2ab8632c830
8351ed8eea2afcf99bf277d3155c9453ad2f93f28476906ca9e58b32482da9e9c2be4cc32883af
a2d36b140f93194224120ae2657dd1c7436807c761087b450b46044bbecc30218325aa5dd29c95
4a15a95487cd5991003965ad869a40f185c15033c8c94fa8a65632180ca5f4931a613f108516c7
556a8a09358992b344a46a535756516928c99f1e1e5447a85548100e06ecc5ce28c53f2d882885
be465fb214180ad97d43c96bc747f93aa3382146677fb59f540da5aa596b078316aa1dc06c5c03
10372f30a578288eaa280e4661444886cecd6a06098b42152a2ce410554cd8c96665907e213a85
6b5a44f2f0376928cf345424c32c92da85ea2a4281e5c0e1ef58354fea299b0c91c7f990c8b633
c9ca9018273a33a91942c4b3b14611b9d2b2f15026d582c97e99212b037fa946b5e22cc9b32c4a
2de4241f3b2bb240ee10aba16c6423aaa66545e4e477482d8532cb19f8d792a1d47e5243547635
70516e364e6c42158d0b496a0f28394b74ac36755515d586eaaa8853248ca18a19a7c52953f762
2c895222576cd24f8a4889310772a69643ba62d57ed2e20b55cd35ec50d242b5039841bfcef570
682ebcb2d55d64cc5de42a4f74bd2b1b0349f99ecbd9e5778f85f59432f07607dd0364cb6021db
d72e3a25bdbaafb8e41e752f30558b1236436db01f597d15e1d613f9d2fa8e8092ac274b506570
19fa555fb2f1c569aed89a0cdf634f241f09354315b67850b5a8478d6ac559e7e68533bcd2d982
e4b49fbce7705d5f18a98eea5a545357fac2d64f16100bd079a43d34ad0873a0ffb809d774e023
ae6eea7215d5861af3f2a5f35d875a45fd699158a3f15ada66d95fa52e48ed272dbeb876c3612c
c3830de2f613f075b84416c7bbee582e71963a0f0017546fcde9b97bf2e0f9d47d3f0b69e1af3c
3e705756ea082f6615196ecebd6811edb9231dc8c34d2decc417aaa96fec0b1e483d3db9e44ee4
fcd10d64e523881167492cbddde884fb191a2fb1f7860366f0d579cb359b4bf34c3ee30dd53bff
f51f75a46f8a2f2ca8db4a4832b82bf2f81a45cd50cfe5d4ab16a4599740aa904f41df93ae92b1
19eaee39b87b5514454753f44c736e4e54c2a1391edd95d5fb2c3f2d92c1f9ae78c341cd300f89
876f2e84f2ac65498dd59ade3968533cd3763dc6be2835bd7ab6f28515d5d4d319544355f593ec
14aa82ae365d9bbd34ef171ec8b6379a26bf26f52714e172e409bfb6f97574377fad2a74d66bbc
e3b6a952ea82d47e92b11aaaa2e1a86c3086010caf16387ceb824366dd67cf664b8c72cf2e1cde
86bf1de72e08869528d444792ead1b8ea819b8fb0bab688f33ef9c7215ed6b2c1897630d4d5548
c6c72e1921955035d403e16e0e0abd95c2f3a591f3bbfbd74dbb9e978c185419c8fe7e55d3f1c3
454232b3ab66a842a29a2eee47732d83e4664b8687ccc016d565c6619c1fa3c834c69f415d7350
7d516a7a010b0dc5187d713d54535b7c5132547d3fc935d238832a914dc1e9cc7d78751f17bcdd
a6c659466a1a4ea5a142e8a2882ed4a302d52aea4f8bb68051a14296f7936a17a4f693065facd2
704aa85a80d579eb177493f396ad10a01071ab0b8224db640ca110ac0f1b523815af65d0ab50c9
565178c8430c122ed92e0bd99f987d3ac60bb409450b8b0c76b8b47494505d85a82099e5c04e76
fa5b8267648730b9cc7619faa292cc3a3619c669a847cd1022d5156e2d657d414cc8d9e9ab6a21
e4b265e49c9221aba9d7857f2d3b4b3ea6696c8d5ece8c0c65545f8c2c306e7a0ea3a1b2a8be30
186a0613ce524dad64b0184ab5b64627435f69d7e965cf2c136a3a0ace5acbd49555541a6a5c45
2f8fbd8a19a7452e6a414429188c20426644f2640b096598687d43999a18aa9ab57620342d743b
002b5f9db9c99272354cd7e2cba6942ec768d5d7e9b9392597d7e774ed015d62760b4a042d835e
850adf0548ae7fa89c19574465212fcd732030953c9e265c418bfd437608ac243771a2270fecc8
d536d979eee13619c87dc397bc6026c9a266a885cb4c05eb9f15306ae1b2854d692e6adbd488ac
c438516b44ca418d65d217b105b24dcf516328a32fae8c6a6a2583c550d5fda49c4dfc4d52794e
a5bbad67a7c659462aaba83fa124f4f2bc7ef48357ad8afa13ca2a8d372a84b498db4faa5d1097
993637df4f129aa16a1b8e05550bb07f965c017f4a60a8326f53533295f0f5b13a0d80ebe395e1
b9135815800701fd24b801c1db5fab08f60476c8ca9b4b739e7795fd0980a1e640c37a320fd609
3d0cf2c802f685010000706b722b3c701d960186b2e1f69116fbcc5a69640773aedb830957001e
0cf493e006ac35e72a1b18059cc24569c00343cd6283b56e6033b28bd50000000000c006c84b0e
8774a5e9e14f4662554ce7ec1938abc0bdf60f3c8d5a78bae02e9e91c783fc0f4d38e7caf7f264
15a6bb578bd33000bba1dbb4e5d15b259dec9373cdc61ba65af824be50d983b3e08b7571a3ed87
362602e6210847aef27660be974d1d109ea200a0cc8b7f594bbc190a5888bcb18617157486fdd2
3c5f636709500f9ca57177fd83bf1421c9e14a701fb86b91602779ecd3742b709be3fe908db273
d7f17bf0e6bd4414229f80b3d66247124ef70ff5aca5a63c146bd982f02e42f45eda11584430e7
ea5e0918bc0356265f01000000f0c81c9a573aeb9f31d50aee8db7fe02c55daccc7f07ac5ce2f8
34ef5ac7efac21d7a6532504bf4619f8fba98b45ba940c7f72eb78fa94cc2b87576961b659aa4c
0a498c371089d7c2879546297687c5d4435174a19fdbb8a4608732523b1d22d7e8a1b9c22a4a42
4ecc405021962b7ec1e82c45cdd859511ecd5911398dc2aaa334a7712585a4b50742668d6095a1
10b4362c3139096b319542afe5bdc9c24f454ed2fca7b04475a52fc20c1d7144599d3565074f21
aa8d14e2c1ecac3c3667a9adbbec8b1d59529072b273ae05530bd332d8d55491b02f68e7eb2253
87def14c5ad2877da048464d4b09719e71190521c3032543c4fc2aa64eac0a05779b65001d8953
c3943a7882e4bc25694623179fc9d2e9a912384f9afabec0a9d0ff2d4bb0fdb1f453f7f7a80b08
b3115dac1fd36c3342a72864a7e62858bd91271d11f444baa9736a521aead5ec504604f8e09ece
a58fe6e81dd7cba90a39ee28e510bba97567a96ae6320c01af392b428a8acf4c166faa2485e43b
dc91117c152619b89034c5ba94d163b24c56803e75e514bde9d4549b7f114b5457faa2cb50d7fc
cb767094a3da42391e2cce2a627196dabacbbed88b253d52d4b84d954d4d146530a969c3153575
544e064ad6138a84bd6f4de30c84a58442cb223421cb01b34a153a65775b640009aea71003b17b
663883a1c3c343a43f5ae0511f4fddb93068c3127943c0f56124f1ed4642bd83a39c9c4d040967
531c526950455729251f2b9cc7ae475948292d320b7f93b4a2aed79ea85535b5a83994d9dbd6e7
51ed50c65b890a90dac55ca10b5421a590507177b85906c28b31e52ca3bb43a988b62babcb1ffd
cadf24ceea1047e7e4cfd6b2846ceda25468843e08c30acb3228416b80ca0f0b9fddfc7b0a7296
bd19c6de54f32f235553a2cc53513db0cc179c21d22e574ed959b5516dc0180f65390b589ce5dd
31189335cdd496b3a170734b0e4cf40faaa92d322c76c4c084788234874148315450a362c93ebf
2fa1736e509db184c9964559342107f8a734600c558890a62a2650dc6d9001a438c74ba0b0f92a
2d35bb2de58229f29938356e5a528b1c2581eb327334b82b3caf8ec4017f9f5411f6a1c4b845cd
431352324466c9293ecb7a6966690c81524494c7608732616962f6e1ef8942b21a39fffafc63cb
68489993ceb2a829fe9a1aa2d99cd52166cf0993d57d09d9da4585b85e714aa85449865c09923f
afa981c52a4f1ea879536ffe1a61d57a542ff3056788b4cb9553b25e7d54abe4b4c8c6c3622f5b
9c25852762e4c9d950b8b12543b8ba541d8ba90d322c76c4c0b40d89a8a366a21a554be60a8f4e
eeb6121243452d4b153224abac5a8578d05845965c1591bb0d6a829efe09adc3a1b97c777fb8eb
b94bc37fce44eccee9e3b5fb6e16dfe367c2928f8448e8b99cddf364eec1b2fe4de824bc7b31fa
99dfd3c39bb6905ee16367edeb202425b726bda55f222ab7032b08b91a0553cbd375efac7216b3
1dca7c0fd4cc5b4c8b077754db1ca86a71d3a539cdb7fca4b32c6a4a9c34cd2bf5929421ee95ee
88ca88255608daeae65f42f3a658a0d4fc6de851ad51ef8b125b45f5553b31bbb3ae68ccddf40f
8aa96fde4789410a8dc87642299ddc6d2594824115d246a90a16b27462b5a1b6aceb76208fc3d7
e10a5842c79d75e4f28292b99db842dedc8b4cbb5dfd4eddf7dbc151fbf4e4920b0efee83a47f9
f840dcded4062c424a137de5518ebb70aaee1416707e6109e505b3d979116000cd7f57ec3daaef
c7597bb0e41632880bc2712200bbe6ab6b18ee4c231b4af386c95d53e93fea1cdc84391d7534e5
b6e25ec712cffe264dcb5db2fb8b18ce4987d018e89d864497e6fdc29d631b5dde5d4ebd6a415a
f722a7242413be6686faeb79a8a6cef541648784ebdac1180fe7e644190ecdf1e82e9c9cd7d6c6
aae639f849f657efa972d6fda0066d89eb34ff31256fda9aff1ea88fa8faa856a98a0795dd386b
034baa584d7d4d19c42332adb88cb92714d70ae293fbdc12b6c6766255b96ecbfa44f06a81c3b7
ce3112bbcbe6abddbd1ea16d7ee589b4b08fb670781bd6731c3f5ce31ce6e1ce5d8b1d96a7f4b5
f8110ff57aed3777d74076a2a56838bcba8fdd1d402ea17d4d57a5b43c6c5a078390848f5dd2b7
705f75b0e78892a9a53be0c18440b5442a6f6007c6120fe777f7af9b763daf3dee31a8995a8643
28c1e82c95823737232f832d68552cee5e8ec19b4af3df0d55cd7fa5a82eb1523c94d9d25937b3
a48ac1d476192a7b18576cbf762b82af2b48482f0699288a5b83250952a47c72574b28a10a598f
7a6255d9a4657d2edefa55c6e48c252b69fcea825c323937582417a6e8d86c9ee0be89133ef886
62d77d0cd5d16a9143e685634259c891a18ee1026d4fce9e9d500653778a0749762419f4b2587b
1a295fba21b1b91c38048f3d1efa9c0b6cae3b4b53b30b9824cd75962099b377f172d698af6ea7
4e5a3b7f991841f48a16f597652807ad4aae709f66695af2a9d19b85e65f448fea9065be3046d4
02678ded9024bb37095b3ce80d701ad559330acffa42b8b9253d22c9f858cdd42619ca6a1a1149
72da75de09d2bc138a666787a18452cbb208e9e1d21674a433aa9822aba6b7b94106d0f3d5d98b
6c2517bbedd3a2e58697e639585720d3feb2ae7c16e797e0285ebd1095714e572f50fe6ef50f23
2af8897759fbdccd250b7cc32591ebf49c7e53455948522a1098aace4f34c6d9220ca6be1ca385
8654cb2999c9b8b61decf120d7ca24d19a3ee8d1d48ce28d71a2ce75964ac19b9b5196416b590a
7677d7a079536ffe37c71851aab36aa2da42653c18d8c85937b7a48a666a930c65358df46bb7c6
d700ab9c50224548e024bfa18432ba90d5ac50c5f55b16d896dcd506588b3d5fb7bd4dcd970000
00d810d9ac8ad29aa7e2c73db96342f4d38391eb8a1ce2b6247728ccb74db7042d1f0000f6831f
bcae36a1f03027f7fb39b182adc0c87545a445c5696fb6751b4d8b6cb995550000006e039f4130
724db987132bd8168c5c5765181772dae1a46627212e580100e08179a093fbfe4fac60551e7160
eaefaa48ba6bed663cc90bb644aef2312d0d00000074f46f7f75f0e61a7219e1ae2d70be9c8686
adc9302fd9bd525670c2868fc18dbd893b12000000404738729537f3f29e0d340ec3fb73279157
98f0d61e5ffaf48c07e4c1eaf06631b29b0c8d9e31780500000006dcc492ac3b0c265fed94ee38
3fd6a4d1e3dd5bc76a81ebb18e6dfbcdc6b1b20a0000c0e726987375af250cde012b93af0080db
d36f36eede940b00000000e2ad9f1972b344731efa4e9e551a922f2498730d338fe7a1c25f974d
2f254fffa56b13e317e5453361aa90f2b8cc44126913534c6d2c326423f1c209e9f1e4347f1396
13cee1158ca95ad267a0c297cc0b8e5e3998d42265fa14162ecb46c7d5c9f7e1d7aa1693784b06
7266142cc4435c3ba5d49b81b3b28e480e1f52d2b8344b7a24b6e7d901000000783c264fb1b64d
ddf433b49ce38fe9193a3a858fcedf94e69da47325501a0a6131d2e487b6aa90d9c3fb24b52863
1d6242c86ecc140c863af89bccc87524e770906ac9b20c1672258c854cd220831c9ebba8180a51
b52823969427aba64ac83a34904af1a654311d30a691ab66c990251718000000c043e24e8a7242
e553e982b363e9b4ea8708c1395bceeb3ebbcc270d87cb21c9e0a64837db1a0e0b88e0bd1752e3
786cd4653008299806105cda780822420edff79576a5f1c7a8e45139c3a0d0cbc979fc41aa2565
6a73520603590bb481dd2943f8eb789255840c0b9032bdb36ae3a157caabd9d96d34301dec90c4
430897167ac1d157510e98acad3caa2523b262000000009f1037b690933a9f1d27ceb3254a6768
39c7c7c30e19cd74a3041e3424a76437764986a10564d851c89f934164eeea5585ec298f453ab2
838c9c9051697c5454f2a81cc99fc83960b0a41b5d1564b020b6ca0ef27264ca1fe9e5a4f24ad5
c743cefed1b0525428c44348aeb46c09e380516c2b85182d29f133e57a000000e0f1e99fd03a1c
9acb77f7879befb934fce7ca94b6d9e267c2dad7ee2c2ee9d57d45bfd890a7cadef909b3694447
cfe5ecf2bb47d37aaebb17984d480b9372aa96943fe451bcc59cbbad9a5e7966343fa0ecc76494
3ec6cf159de9bfa6fdd61fc81b8d0d4ad5c703f33d5632f948a8f1a0521b30164b02000000a0e3
6b374b44e3061928b841864cede03c0aa639bff046b6fcc07b1730c15ca04ce19f9efbcd6e4fdd
f7216eccd736af3c1949174e34663c558e02ef93b22523e4cae71a9795000000c07df0d59d38dd
c042f6d57f76734edda9b4ffb81997535f6f90ac83199e441ce6f02648a6d3dac3b64301113296
e16934c317be8e6b72c963912a4bce82b7caef0a971734f01f6f071745c762f49c4fce1a6eccca
e3d7f154f4ea5a38c3c6f7136e1c0f21594bc648308c678e010000804f03af16387ceb065532a9
537303d40d441620f78e5fd3e580ed317f0acf7069de4981b6f918cd137722711554dcb05ab16d
7ee5bbd8ef35a3a159c8b0890776c221f762243f9ca25f33f7d9cba89614430532d04f736b198b
3d1e4e0d91d0db397941ae97e4c8e3c553b88ab43e1e1892d3af1f3d7eb86387f1f1b6f130d52e
2c96f4b8764a1972036b594d4bc9b8f218000000b863defa2748e83cba7c85805f6310a4eea4cc
4b1e9333b4ab2b3cd106cb22c33471c6cf911380d2506fb60a7f67d6222423a38424670a97367e
d6c78f307c929d9bbad2462a1c47cf0ce9b56b9654643020664993b7e484232445957851c7f7c7
352d142c8767f364efd473ceec135a7ac014da459f3f4dd332e47f0a7c8a912b00008087e6ab3b
23d279542672daa78ae787fad7fc2c84ef9626b35da7e7f49b12bce0419e7719e89f80715015f1
fa07b72ea246e6f95c8ed1a24f52f0144ea1c536a45fcb37dcf3689654643040764bececeeec7b
c9498bc0ce72d33ff58b20139f24c378216c7d3c2472727844876f130fc576a158d243c35f1eb3
660c0500000000b019d9695d504b6e42f44ef1f3b28fa10e00000000ee87e0cd080eb9058c3d1c
56e73146ae121e18b602000000e0360463119f3028599f471ab94eac6d0500000000b83af25e53
9fb04ee02a3cc6c81500000000000000000000dc39bc7d8f4c01ba7941dca30400000000003b82
df44d021ef96e45d829edaea17b2030000000000b026c1c8d5bde6475ef2d4d22036ffaa1e0000
000000006e443072752f1d0dde012b93af000000000000ec8360e4ea5708b46edcca93af000000
000000ec8ab76093a6248ddfbc0f0000000000c02d698ffd9b9c7887016c840900000000007646
bf5ae0295ee48a8d050000000000c0cee847ae874373e195ad58e40a000000000076cae12d5ddb
3a24593f000000000000c04ec022570000000000701f0cef7a3db8a9560c5c0100000000c0fee0
75ae7e27d7e1355a000000000000ec0b1ab91edc24abbcebb57d6a2eefbcc30000000000000000
00000000000000000000000000000000000000000000000000807dc09b6d619bd82c6e33dd6d8d
f396bc6f423644db197721e45d004b02b00a5bf7d5386f56b0fd89156c48fff65707bf86e0c86f
cd1a767805e09a74af70bb69b0ed4106b016f0a6003b80c703510d9870e4fae45ea375e13db1fc
0eafe0f178f9d27c91f4bcdf1dd0ee42c8bb0096040000f0400423d7e135042d0d62bb1d5e7578
a6d65d064da4eda7ebdd84f143df26e8ae3b25c96b7b7786dca9c9a6c42de7171e54bd741f6fc2
1e64b82d777167cd2824bc29d4d801775a376303533f9237d1ba01138c5c5b375ce5599960f2f5
fe3834af3c947303f147e42de983f8ca01a718000000007c028291ab5f21d0ba71abf91db097e6
99ae81faf4c2250c3728fb6f3ce1f322e3f156f8abacb89d8bcc1c9f69d8cdef061bf0abdd8349
e26808a866e899143258506f54f3e3d87d63e4f0c6a5053617f3bef9753f66192611f5470b89a8
b4b9d276d7c77192700865a334b7644f58cedc8031c930baa530b71699f0f0291f728b9dc594aa
d0907a3f5edddfe5b9fc82a9c3499d8c2236350b5a58840c4ba69478538e1a5b46be0fbf2ea8a9
50df81a896148a3159b643c774097278553c98a35a6e8e0d29d7e7f85f67f942cc488784f7dfa4
b4c823b11dcace9aeaa3160b29075a4c4d84b5246256361c0543542f08dab0044bdb0c8ba5a4fa
62a1b38a2d0bec8e242cc23415015384d13620d17f4cc3226a3fa3a0a1b4206e481792396c4b1d
2243d87a932ad40c4459c8a56a521ab7db2ce2a924aff4ce9d1816193c22cce8841115c8883d6d
323a32f68f4942ae14661342662d19394b43972157c5ac16919c5424cd0b180da58a909c2527db
fe9cb6d9b97ba448e77f839a652d2c422adecc46117f39e4d4d454a8ef407a3b4c5a92c895102a
5b19d52bc44345373814a219aa8c98f1c38f8c3f9aa3f78b1783e54c53182113420edd5a9d90ba
a93769380a86a8d683b66c6a3163b16d2e8b6a4a339c95cb90a908ec0a177c12cdec3fe3406a4c
61e4ea52d06024167dce7471aa1c9244b30a1fe5c251a2306c9fbd0c3e16bb36efab5033a842f6
2514d414fb0ceda13fc464f0a4ba9eaee390120c320c8895260a0c1bad537c94ad4024521916b8
d4414c08b94ec008133264b5707724cc5009e1e1e9ecc22c674da05411326149a2ec2fd5d472b8
4b5e11ced31d6150d3a24559c881096f8a16e1d152a03f7bd54654afa6afba334b5042ad25278c
908fc9093b584ac8e6f1285af47628b85b4a0833380eabf9c29b910a905892ba5cb17da522d260
1f691d413ca87d75a59042c9d4064bd2e1e1b1550d274b2f4321aabdb50739f9285fa16a6ab164
28a094e9330c70c9e3a8ae7756d64ab37a7b70039ce3c58b71cccd4502283d7c142584e4ec4293
433909c7b09731121e12954fe4223eea05d40caa90aa9a5260acd48c6e2527a123fcde20c3c0f4
50269293cb9cd5f10d7d599c32654c29e5c90ab952c074140d4b2963ba45a4be9ee52c1ba5709a
76b77a54d9d49dbb73253be6ab9995a7246448d19be1f72ec8bd54f51195ab775e07a25a921063
5a22a46887720955f120e517dc2d7158306cb52f42f9a5eae16f292427a41ce5eb55faeafa8061
4aa6562d39225b5aa90a955c144551dd973f19b406538f6b89da66484e1e620567899c9696056e
4fbfcef570682ebcb275de22d73994b6d9e267c2dad72e7424b907ad7897032b6df3ad6d2eef24
be43aafb1637d7eff16367c947a294c12664494dc9298fc15d93fa1dcd5c096d7320ed383648e2
5375996bb24ac0a89cbb65c4afd4c7511533cf491d7d874849169c25d43b4bada20ab3a9cb8ae8
6a5e550be2ecd658b7df7a27f23af841aa9522aabe03214ab6aa8fc9ca12eabb412ec177d419d6
f245701acbca23a73ccfe5ec44724f2a135257a1af5e494895db379c7254f794e52c999a28b74d
95559cb54a6f0f36e26b770d4781227e75a12fd7c4f7e6bcf61047275fb10d8de151185a7b8fdc
d1c8f6268b915ee395fb4177555338cd4c337e42cbde17ed84681316691753530b395ce37a6b4e
cf9dfacfa7eefb15d9a08a0dd8460b17d56df3ca57b37bbc1eb3511993447d0960273c46f327f6
d036d12eee87afce5b2edce57175deabbcf35fff71332ea7bede20d9a3578659297d63c8f24463
bee204f33843a59055f085a95c8f861cbeb97fadfbef1a393727f2fda1391e5d75ef9b772216b6
f3c539287c64ff490eee5e15b5a6e3f55ad1065530d735f5565a9c4fae4373e745ee16c6d763ab
ab79c50e64594c86549450a505cf8da9730a1bb4ee641640e63e92d9c1321b085962ab8693a09e
37c7a8a656db663d5667d5b72c707578b5801bfa043bb9ce98a55f0bb959f0daaf4ae96979d864
82236c18734be28b27d7187ae80ad5af62397eb843921652ca502fe4a57977ad7328818e9d757f
475cf316cc8593c0eeaec779fdceebfceefe75d7035728bc967a5f1820db26e52f98d81ec2af6d
7e655fbb7e7f55d6aa226c29039b989a306a9117d248df008f7ce23c85ebde5652f3ba1d08975f
1993f612ae150fe285d63dfb9f78b8ab718390e32aa8b861ed631f75dd55bada57af2a644d546f
d0704a51ada29a5a28b44d95359cb54a6f0f36e5ad5fc84cceab5c21e04a183f88c30b7192b090
9cc36ae860b14e98d2a2269892dcadc29642d4f22d0294f318d4a4a6e28f92241b8e24471590d5
f1494ab4504ced29df10915fe7c8e611354d07b2c0e315f70353425afc65644206b15b9aecf78f
7a036693937396b3b2a8558414dc9d2b67385c33b5e26e554da31665213d13deecf0baac1e5196
c3b53c6ac39911931376309550130ffcab12d5131e1f8eb218731a31a3542755cb81ee6f7f9ac8
5611d841efabeb84ec28985ab5e4ba0d278b4147bdb7d74cdde1b365e359e03ce3a8ae7796a95d
80bdf0d579949c27f79adba7abccd29be029faf01a8c383da7df4c41179459c965e2d05f6e9e5f
ba55d80e5e209194af64a81392b81ca3a54874ec69d64d177ecbc3202191d3621de4429694be4a
e9d554fb42250a06c6dd6f92555016c835c17a1bb957951458cb5a55503905bdae6d6aa3166521
8dc80c10c93f5e11b8869ad7ee406a63d258c2b5e3812d93bab87f44c671fdd6edaa8897c39165
423be87df52a42d644351dbb49c351a25a45337547a16d6ad43babbe65017005f8924bbd2e2c65
f87cbc95674301001e7420e0f14054833d12bcfd15809003bf69769fcf6601000000e05382912b
18218b83dd75f60e9fcd02000000c0e70523573045f5ea2800000000804f49fd6a9b4fbc5e477f
f6735dd63075ba85029ef104a09e1b7583355d50d215ac25fc4d7a98adbbe2995cc9d47701ce38
774538e7ca7b67c8761bee7e313c07ae4fb7174945b0d597f04980a13603a65e0b1a4f24c3a7d5
b74306024c6d04ad7b07842357799d34af6ba490dde95e48e073f0e25f27116fa70200f82cc81b
8c781ba6ae37f8d23cafb4db097a98886b9afa2e403cdc15c1c8d56d7a2aaf746b6910bbf6db44
1f05f576cfceef07ed0db7b11f7516150b6a0b25dcdc172240366d2f54bda90b20ec43ae6a6a95
87f145cb737ef25ed09bb0074b6e23c3cd4d7d47dcb675032618b9ba370b07ef8095c957000000
00000076c75b7f61e72ef2e6bc03562e0a8f6db09b52bfdeb9bb521c3f16c0df8c77b9971286e4
97920425842ba9c322157c09c1abf022917ac2f287d715c6df47a9b7959ac1335505115e612fd4
94f1c79291a3ab76832f2c32481e9fc605ba6fa64d9dd8aaf4be032964b4a8a85c42f2eb90bc2f
a68b2d093393c8f25304561a67ae8f07c5d4c696150b49c9c7ad6e6ac614309a8e93fd434f7878
d2b2140cedc2316d07621d5387bf928263c1a649041892f7c50219e65ab2c7974076c83684c92a
58c8a9e4731a23aa83bfc937ed5c57a05bd24cd90e052d8c3294eca062337529ec73d62348f8ce
dae690535bf724be8a40ce8c1d622d260d35ad913f96523e960a5aa8860233e039577109f95196
1e7fbc0e3eb6dbf4dbafcd2b47f3e1b539f226f6f2b7b59d738d52c2c021eed1384f186f6f73fb
112a213884f42d97fffa1167a8c758c528db0ce263db5776e802a665a0be322933b5244187174c
7d73e4ddb67180915ea4ef69cb7e84fadc38865d1b1c77d935f16061547ed4b262570adfe64863
0d98b20ce5fe6174f8551a6f9d1d1c0635875f293cece76f3bb3645860c9b8844c17545d8529a2
6e8e66877a2db6b0036951087b63473af2f8bcd66d21ee4b533b187bda1aca5aece48cf3609005
3bbfb2f5675db7b963e3b1af14e52e3ea44c7f49e4e16fc2617177a512c7d6e066ce9f64f0036e
137d09bed24eec20764586414e39240e6e39aa609f7206b50a6fcc4153ce635593b2cbe587b76d
af7857297f8cc4e36f425fa8325086b004a93155aa68ea8151ed291c90a52e66ba84b22fe4d7f0
40e79d4245f3290b40480c0f3288b2d989a5a5f130903554efac42cbca6a210be33caaa9c39fa6
02a62083d23fd81a6f09ce1fc93f3297c50e1da3631d66358703fb43924acb947c619661b925e9
88721764aea2a08825a2a203f99bd423c2740f53b2a401d50e8a164c59064b09160ab5647f0ac3
5e3284b675fef5f6ecb5ae69dd0a7d155e061129f4a9d4380839ea6907969e71542d14438105b8
88170bb25766457e18d961cb717f8b17b9cc28f413df4bac242e0f91d08c7d2c75cd0aee24daa2
f6c33224195c60c552659b71482983a18a71939b8b53aa20b3ea8bf932a42aaba60ec9658e58da
8f10255f3091adc696a9a6b3e4287595708d896a72885767ae2f4a640d9593216d5992a7d8d654
5387a4995519d4fec1d6784bb00c91fc637319ecd0313e9658a4e62cc30aa5436c32545952ed82
cc55d875cf46547460d62382983dd7c416183f44b1c388ecafb364582c70e940899962d8973a52
5bc8cd0ab0949c73a3334e4e0651391312d3f1d091abcea8c5b5cf389f86fe09adc3a1b9f06602
ee5a4a76189849b817c1ec1db5e499b0777e3e6c9afa8dbabec715441f5986f69543bc4f6ee69f
775a58077315cb3595a2e449bb3a1419a42fe094de0a644aa6de0d4ec7b639900bb80990d54ed5
31361769779ecbd9f9ce3d2e19501ff96594f2cfcd0b6778a5e105797cd939460b98920c6affb0
41e325d6b043959a2ba1ca506549b50b5acb595a44dd1863575cafc5b5ed60087b1751c58e7483
b057cf38969e7639362d5443011b5fbbab1fb2a174252ef4e5ea612246017031f3d69c9e797390
2fcdf3a9fbfeee90fef495bb7b77f1769d4143b78b4a90eeaeb38a368251e724463c4ec0d4d901
acc5634454bd16dbd8410dfb6d3ad20700865a89af2e285db8cb16c4bc07ef70a25d754bdef085
1ce9e230be306dbf6d3d507622c513cc9753af7b90d61d676c50854ac9172a0777838382e43827
38c6a6de05e7e6445a1c9a23af947fbfc58832b9e86f0fae1524d3037be11c84ab6c5d6e6151c0
44d8fa87fa96656d17cbeca0226ac6f1f0b4d69cd01cf6de0dda22aaaa97db80fa76515fc22c0a
615fd3915ee7ec3f3ee35cb7a7356ab18333ce43c0ab050edf3abbcb8c776962bf021f37749998
ded490c7eee8626e34cbeb66d4d783aaf68b758e1f2e74868b9eb36b90edabeb0b425a8eb00455
aa7c8639552ca47f80d15741858f6f21957c616350b06d7ee512c2f3045132f5b6949d757e77ff
ba8be073fe0420cba1281596792d84e3814c332c99ea8db9ab1e8d5c9944ecd4da8f82a9d58029
a1f60f2bb5ac72bbb0db612172a20d1aefb8463be5b09fa4de926a17b492b3d488aaefe5848596
b475c5c6765190c158c2628c61af76a493ac74f62739cb2777faea8a3dad598be58602096ffd32
61f2fd821502d420fd79dd95d02f8b1e4a93fb0b41a20b0efa375ae33cca23a96b33bc9427693f
5297753c112c060a5354a4254f4ece1919b42ac49889a6b39012c2f4c686eaca34f8429161c253
92dc4116337a3873bada3d44aa9bbb5e5e509d45f479a6f4f5f65c3072d5bd99b555a06c7d3c0c
640dc55f26e5272d4b3ea629f148c1d4b68029cb3055c87054d6925351376654feb85d98ec202c
35b5d2788d147c613175a5252d5ad8aa980c7e35a20cde1c90cc593f162c6940b183aa855090c1
588281423f630dfb5e98b4104bc84d2892952783259cb2790a4ecffe2470519958326a31652830
83afce0d644079be8a2e52af323176699e8357a59d9e73971abc5c4156820ff46bc3d782aa1e0a
e41aa3e2f96e4852211d127d13eb92a19cc152451d9763b4da890a3f8537442cbe28432504cb48
e4aedfd84d8aa9b741751621d7cae4991bc8c7f110afc939bfeceebd822452e25fe7f444c882a9
6d01a3c021941e15f60f952d2b963fdb2e4c76a84369bc462c615fa0ba8fd2b5a8775639a20cde
34516749bd2bb6b48b820cc612eab0867d4d474a8a945bb781484e2e303a7a839ed6a8c56dcf38
0080c7e06d6a3206805b93ce4e01b0576ed691e6a675f70cce3800802a3032003b22d97d5d6e71
ce5fc105c0c6dcb223bdab912bce380080e5b8cdcf652952614913005b925b8d87f57060cfdcbe
23bd93912bce38ebd1bf8900804f4a611919001b239be6049cc2f5e200ec1674a44660a85dc397
41bb5acce15ebc16265cf72ce3ae6ecd184962e326da2d93a136aa65926f7f6da1f0b0f303833e
0adc9cab36bd3df4b4e0fe09e75c79b306597ee1a6b52b3a4d179de873af8c2c97819deba1704d
facff1deb4d736f58d65b89fab1184fdae803b801db597db80bb8858342b8d70e42a2fdee57b55
144f8bb76cf0d1f9f2a579ded39c2bc9f34552bc3b06f8d4c8cb607843932e3cb68fdb0a196aa3
9af72792fbd1d45d620ae4b6a08f020fcb1e7a5af078b8617ef0e28065cfbec91ae4bdeff8a06e
353ccd27b9895952f3b1560becc1a1ebc85011d58e7e7fecd90d5fd61b84698d67e13f49439ba4
d29bf7cf670f80db7125cbefdfa108b9fb21987375efca0bde012b93aff33834af74e419175200
dc1bfd7303eeb58495d0a80b1b39010000b8366ffdd586bbf25874e29109d7c9399b7e52c7a771
4e92a1f02ba16630313d9f21575d3e85975f61d5511ad9aa206478551766b35fe62562a4d3dbc1
84e82ae50fc9ab69ae22fc7599b3866d4424252e8b232a74962ee478a63048226d628aa93b0943
36122fa857673d191cc5593aa32f94269c65a4b2d4352e4495c167203593f90f931d0c3d8c4a39
e40afd436887505a632ca414bc59087bc16007d517051223508adc316e02fc4deab26921135f0f
69ee59a96028b3b36a0ce558c31757ec067bfcafe3a6674293612ae926e592f3ed9d2d233fa927
d6f04b4a4981c9af439a73727718dc5da02ca4dd9b654a9dd87d31e9b6e988c9e2ca99ea5c461e
4d0bcf6588bcae66b023458dce0ae31e9992af62d24aa1ca9a905d033ba6d9ecc1630aee51f9f6
4e5f57d35245bdb37225501a0ac97688dea7aa90d9c3fb24b528a6262684b4f605abc8e09988ea
59be5872d212530787c8e3055115aa0c9a2597f9a264ae3113327839cbfd831e72b31061c6decc
c64c984db5432ec3543c6419db212a7f140ff28d2a83cfa0774116ca86b238abda5065351d6a15
b90c9492a84b53b59a946674020619a692c59e2e1efad292be857e92bfd5136bb9033185dc2267
251595290b69f2a686d289dd1d4e1fd19fad3fefd42588dbc23e34a00bacb8d836b0975c560e19
24dc83d2d40c33981095840c25944692ca9c53c4a30a39c48d8f36ce33515e113e301bdc51f97d
7b985545494d4315f5ce9212d23619bc61486a1cd4ef7b8d2e83d90e658776644ddd0b397cdf57
aa9436a246868189a89ee70bb596317c485a7eec385506696b264b4e4898b561d8c3a8a8214755
84e5a7fd432fb31a722626bca984bdc10ef3e24165ec0efe26126094c7e22c53a398a6be7fa837
54bd2fd498ac577346d39b408d4961b1439d117af9a3bab822294f0a77c96bca8a646ae3ef0769
03ca12aace52dd3d83ac90bd6b0ade5421214309b3839c7bc229203e98f2b7ca7440387aa327d1
dcc121981c1bc6ab9e6116d2b4b43e281f8885e036082987cfeafe262904775cbe4467def21394
d454aba8779638a8903f2783c8dcd56bb64349534fd6d439214da58d582e434836aae7fa225b48
1931759c225d0c32b8fed768c9293bf462cc8af3819c37cba4128a00869033917544ae0a116330
48d90e73e34165ec0efe2672dc449e492199654da943ca2f182a9761e54e8c28aba956a1c664bd
9ab39a5e1655869ec50e1581dd716c9037fa28d551d5bde4527822461e1638914d284968890731
4531aaad6485cc997a790fc32c76caade99fd03a1c9acb77f787bb44b834fce7aa9cbb9d775ec9
d9a3a622cf84b5affc539fdcc35e2dfd62cbb0167df051fa98fba88a59c8c53b8e19b976f944a9
8a7a67c93382efcac64012b19ecbd9e5770f1af65cd70e36216fcc660d27e0a5df66ab439541fe
90c7431753ee61548cded4fa870d9a9e12f6953ded36543acb4655ffb08aa1d638eb5db71b5ca5
e91964a841e4a791497b685a31296fb045839644f22bb63e4b3c6c12d52be85833c8d90b5f870b
1af18ad3442ef5e69a9e63a810ace717dec24dde7b265558ae9036c499e2cdbd6eb1db6aeed47d
0fc067414e96f179c882b46e69326fd7e9b255aeddc3dc4bffb0ff9e96b80b21ebf9246a5e171e
5a3c3db9e4ba261969d040563eee89fdbbfb5106395f9dad9df4b23f306f7fdd59bfff6845666a
f9cc5782773ea7e4ae1c646be29ecba9af3748e105869aa18a839b3327dd8f3374ce705d21ef87
2a3b48dff44d89a5e432c95d9153bd9bf565b94b35ea5b7788dd17b22aebfbd2267039f2ac43db
fc3aba19b75dbb98ee614aa821b752ff508f35ec2b7ada7ac277239596fa2d73968dfafe613543
2df3c55d7483cc7565e0a10545d4e1d0bc93692ecdfb8507b2edf29e6a19d678b8665457b19b4e
ac1a5e2d70f8d6351219772e9e8e766144e1956b6734d24fd652443177763e6e5fd33cedb1f7ba
9a6125dc0d0881cebe3c919e7d3ddd902d642b213723afa64abd1db86f22178cb705ed44e22aa8
b8612550ef2fd7b56d835caa715f208c83fcf6ccf485eb0aa86d569c72a85b3c5de21a5519c4dd
8125e9a7b9b7b1941e46450d39c6d83f5c0b43d8d7f6b42be1873224cfd8957667d57441654329
ac61a85a5f6cd00dd637bd7a190c90dd68044f3125dbccd398f8f0ea3ed6f45453e443ce100fb5
5dd056dcb8135b91b77e892e99be6a71466e05b1e04aa69f9214e60cd65e8469880435839dec34
be7c3991865a72d9ec4252a0d3c724be17c2750dfd85c05f26e58bf1e72de22ea869a9a2de5913
ee18eacd56e17d6ab683c9235c5a6aeafed830b9a707d4d246d4c830908d6ac2ee0bc9996bbf25
c6a6ee7d678f8719969cb083dec3a894436ee257492ecbd80ebd544b9e9f98e5cd209b6e07cd17
f318bb6364a8233b37cc637256cee033842c1bcae2ac6a43ade08b724c12d56aaed0899565e831
f572137496eccbec640ec62a330a6769f31d6939e4346799a2da48564883371526c249d222cfdc
8aafce1c24b15cbbd08572d513276737dd42c58dc3e2fcd22d5ef6b88977590e22f0047b729176
7a0ebe51335472699e83d511725f2091d9d1bf6a28cfb585dc8cb29a2af576e0e52ba9fdfb25f0
0eaa225ecd42311645d4f5b91ca37542a4e0e90a7300b5187d419d1a77b2a7fa954f7df0bc7ef4
5daa2643bd25f51e46a51c72f4aba57fb8365ad8afd0d35612771d54f2f8d6a4c9597139b3a9ef
1faa0db5822fca314954abb94227566f6a0d199ff8e507f2045877a37845ca21a739cb14d5b765
279dd83e910dc6ee6d080fc00accbb02de0d7eb660d98c08f8b4d44ca40100c08ef083d7fc9c3c
008f41b025b8436e27d5acb7d99ee01618c61f40277e92c16d697987976a00009023bb50038047
2218f6f97467e33f5161d9622cf009192f95bbaf4b35000000e03323734e3e61f2093c3c51cc63
d80a007818b0fee981f1ab41ba3477c68ee7f9101b00805b51db89811c89551fa793c7396b5ff4
6f7f75f06d2099347257d59fb825277b7080c5c0920080c5a00311f6600755061ab62643bb7bdd
28b40e04edf50947aef2e247de328102ee8aaf000677ce8b7f8348bc190a0000dc05e8c456465e
16c5db787586fdd23ce34117706ddc85822c5a0a265f17b3cfd50258c320ac6607795c63eec525
eebc805d82fee133b2ac13db0d3b09da07683b251570ceda17c19cab7b5f5ff00e58997c050000
0000006077bcf59714eeca63d113a37e75f6c731bd7c093f868bb8c36b18c9e353787d233f1ddb
eeb1d6b09c71369fc29fc24aa314689ae499dad22b799c7cc1c57a585138b72deb6342b105f93e
fc7aaa84f0d230cce38fb5d8610613d3158a2547d7af927f3ccd3fa9a68d423c58110583344bc8
72d8afe06ead0a1def8b40d38ca1623b0c19f8fb424b097fbaa216c29490c478ca84bff1e28595
46296e1796881a8aa27631aeb768877528d86125535beca0100b49293445e28e4207525641f585
432499e8c6173acbd62e545f94ed90fc3aa45167be500ba62c8358752acdb558e9d8e9a8163352
fef2f08098b2836e4943c8590c552e41187e2d042d2026dd36ddf652466127c95bbc6ba2c7349b
f748d2154af2b125bf7ef821e34773e4b3bbfc2db9ca254cea18347225f2880935d336562057c2
70b8fc9af4a1fce5204cb90409f4919dbd9a163bcc202bb06ac9b8354a7793b6cdb29a06caf160
222743a48b26a412f659ebf1975677ab55a8882f7c6bea536428ce93a65e6ce7ebfe6f1973fb63
e9a7eeef6b6b411485ecd40c8be36fbc9d2ded428fa89c9a94867a353bac40d90e6b985ab7834a
ce0e61cb327520d3bd9c43f585477226cd90a87396a55da8be28dbc112b4955a10165f4c256b45
5a3c94a35acc581e1e94eda05bd210721643ad16b44070be170bb2ede65a4a5ae6e0aa3ece7c39
4367178782af8732849526d351fe70fa427e9272dca0a72fb05c8220e5245f6660d9d2c8f3b3ad
61a811c98b948a8417850e3154d0698e877122b3af4229a1b77c28a4b4a87199ba1d54a4a58d3b
7d4fd692fca5d49ef4e91ed5502a96782893b5521b88aa0a2925b83411f6b5ee3654a12005063e
ea0a0caa90f8199cd877af22a493b0af3acac9d9448cab6ba10929a545aee46f92c81431128f7b
e8d7f0a77144899a4399bd6d7d1ed50ef5287658c3d4aa1d54b2760e5bd640ce4ddeb0830aa35e
4ef5c5c0442756e92c77b8d62e66f8226b07266b4ccf9a21372d035116a38c1a0fe5a8f666a402
241ac59ea10b2c7628a920f9fb928524e406b286329420420e07f6872cb3eaa7c0f95bbcc8c69a
6b28e780c01f4412045d6c991b4cf670f9187694eeefb85e4f360ab35f66c8469eb49689ea4c70
0949b161eb728caa76b6f576534b90588fed2c16f3a72ec26a0715b149c1ad594bf29754bb8811
0ad66131d44c96a82cc6cc4a481884944a67d9679ebb2d5594c93928ea4fc50871f952a91c25d1
e532b3b46efa5632d38122e7565a1484940c91f7738acb21c6204933b39a498846790c76a845b5
43ff71b9a947cc325a87c839d5b242726ecaaa19f572aa2f42247362906a67e9eda217c9e48bac
1d9892fdd70db96919882561e011874ec543cedd529d0813562d661ffe164d6d7628a99093210a
b990aca1d412240eed227d6afa27b40e87e6f2ddfde12e742e0dff69a66d9ee85f79baab88b2d3
561fbe943e5ebbef42be0762e58bd24aa8421e5c7bafd842854b685f072129bdbaafd880c299fe
6bda6f7df8f2562383b29612543bef8483f3d1e9b9398e0d6a5353a7321ececd0b5bf295fa382a
24e9eecd4296dcb186bb894a8f7f8f5d907c24a473f05cceae15b8673afbaaa9df68e952442cc6
5a5097123ef1b98116052157a31051ac66a97f582baa352c76a83475c90e16ca2dcb464905d517
2ad5ced2db454fad2f0a6c1572b518e2418dead2f060253bd47beaba41fb89f83a5c1a8a5f5d37
2463ff8900ba124e8c37378ee9f6813b75dfdba92f6127b8e06e9b577289747397e654dd607608
69466a5157a5cfbb2c62957838bff0e12ffc41da856582640e77ef6e3e0d3f3db9e4ce2efcd19d
b0e5e303f1303d4c25f7d2b26ecca76917abf0f8f100d6e4ab8b18d7f5c806c2bc27731743fdc7
2d38b8f970aa3733fd66a4be0415e97afcf4d8522ea7debc410ac72ae793abc80d62784033be08
534bb80b68c4f6c201363578ad5273dd783807b5cb86db3df5bed8a1bbdd9b6fe21b2fc98c9d9b
46a22c928373d221a4c23b897569de2f7cc26ea3b9db0db42809c9846ff471379766a14694f40f
b10c6487843dd8a18aad5a5615365fa85439cbd62e3660fb0e6439d3f1501fd57bb7c34a41fb39
e0d502876f9dd564be7af69438b749e9d184f6b8e416923b790b6df32b1f1e9e692c184b18b2cd
42d4a4cbc1d154b4b540b935fc3a184a2073455ff4f63c72e33c85cb658c25d858688715a1eba5
7ef01ac9b2929a951175784b05884e396bf9622b7717204dfdc5c3917d310ca05906fa6a58b6d5
1bd39d8f19320b5dd1511f2b9b40d3e9e4f0ea3e76f7ef36d0c22024e1cf0aa46fa1832ab48b52
44c9583fe806d3f8b1dba1bfeb952e9553b1d9a19eebb6ac7a545fa8ac11b44abb58957cd06ed0
f4d6408987faa89e638742f3bf2ef541fbd9781baf689e0945805b5d1024d967c7db5d324cbaa1
efa9b3890e92c3e5e4ea84ec1f1f1904d64ae8c865cb08c5abb832a78d895a668457b03e2c4c69
013edbf88e49b904fe3591472c16cd6b1aeda022e5146eeb642d9908d96b1409505653c5180f45
c46e690a95d58454c2dee3cb99eb6e7b155358ec9ccd1388da19aaffa6eb0dc29ee4da5a106521
47f170e41ad3c82cb40b4344758a0729e906553b74f47565ba2015cd59b5a6dea66579581da503
61925e4ef78547341ad76e74d6346abb98e18bac1d8442d012d55a0c146498a5cb88853d6d6cd8
d2f0c07d080e0c52246fc1927c7839e406b28632943023683f3b5f9d41c92c7215d83e2d5c207c
3946ab9d4ecfcd69d665653ff726c8acbe2cd9b6622c81b2c94a9a65f09a8ab4d87e75b909be1b
92642773a505c85526fd345e43662ca14ca51dd6e5dc050f5d410dbd40a59af5114522bca487b8
7242bbade20be2daeed68834e5208fca2719026312943fb483f41efece9d3c3cd1ddc61136d0a2
2c641cf05475fe6677a15d18224aef066f6e877ab66959d5d49e92886a67e9ed62150a414b6c10
72d5e8f1501fd5163b942d797d56085a0000787c723301602d2667655478fa077e5991e5be00e0
4620680100600446ae2b92bc94846d5bb3fe0a6e59ce7abe00602310b40000a08391eb8ac89926
4e4b6c8b09d77ad6f205009b81a00500001d8c5c57c5bd982738ebe036df0d812fc0dd81a005fb
638351c2dd0e446a1e4d05f78ebc6f7648d9c7cc7b92cca698c100ddc85d180ade04e053d3bffd
d5c1b7a8648cef06fec593c72747d64dc3441b00536fc65d989a86adc98865eeaecf007c42d091
6e064c7d7dc291abbc3697779ea093c1ecf7110000c0225efc5b6de2bd6f52e4b53a177ee15f9f
9e176c7a0a0000e05e0946aeeed511f21687f65aeff97818dc667274d6ccedfdb6c15def1bdf58
e75b7551bae6c38f05538375b96d545b9057b6cafb72c19ea90f182c1f326234d4c377a4fb0918
9cb3ae4f307275af460cde012b93af00e8b49937e202000000005c11ff0e5877ed621f88f0ead8
a937c21d3fba9fc2eba1f0018be802898bf23f45174fc192fcc9c399e1d7b7e828059b1661d594
92fcc9af43f2c6346b31c58a5584bfce7b80716455296a5c885a85cf40964cae98c36325438638
6028cd50c46b1114122a45d4066d4ff2b8e878fd93622855cd1a3b68a64e7e1d52d245186450d4
14a49cc444ecaca96452d6d62ec4e33e45de5403c61051c2a41d6c425a4cbd1cbb9a1efec6878d
3560a6d14b301aaa606a23b1a9f37658ec6e3ad4d0c314625237d4284fda912eb0e4ac13aba710
b4f253ae578ca49d2ec1620721cc19fa428c4cdf485f1d1ac4ae6622c6fae72c9030e9f829ebc7
b8c3fbb093b5c96148c9df5d133da66e1ba2821b439a7c344b53191d1e85e62826241923cfa245
62a8c438c9af434a3adcb21645d6a92267a819ed67d46d25e672a85568ce2a9bda912bc112ae1d
a2852ca50f5228646dd012136a0eb52c3254a466a51deaa39a582464a4a6477226a7b1ac9dfb94
2f27c1d02e922182a4a17035600c11a5d8c12064b68459ee569890211532ec54f91b2f8329608a
eca29723b8963425a7a41a77f72157e861ca31693175b9752fb62425fb902e5b4228898c17c796
196a2896b0b88ff2354a751f7e8ae1a3397acf868514514c4d687600b3719e130fb1716704a584
5def5d715ee70c2e4a4a1a5aa08f036e33be9ee840a2f771175bbe1309c2480ef12548f40f25f4
871875b16831c08567634e34cd576ad0c2426515e165a5430e49c60a05387f7a78501da1562183
5d93b3f8a7b1a9b34690759026fa1a7dc95d880642d6066d6f87c438747c92a1602855cd5a3b84
4c989ac8d6e2516598117262c389682c8b51a27777a15d50e161c912a2a9cc85805133a876b009
1995c02c7477169b9a9100fc4d1236593967512ac160a819213781d2ba5543995bb74b133d0c65
082d90c624633535979cb8c96ba15a7238b03f44afb1272be1b8130b6573958e0c55288128dba1
ec0b399612fd2e461683b8a302cb58c99adaa6059887f39678918d3ee1fd3ce2697708b76d7719
ea8beabdde4546108b117118097248e7fe5c06a9b7eb47a45b8983ac1cca09162d06589e716812
a54a552d6c5455c1da2592cf6b9f52459c22610c55b8ced1e8ac2953f762cc32dd40aed8ec2821
31e640ced47248576c2e26232cbe50d5acb44348ce264229e488b20cb3424e8c366173458c0239
67959b5e5a57ce3851c0a819543b58842c9bba1e9b9a910b72872cf7544fa904d550b3422e4bae
0a11a92b563594410629702adac7646d6235754e60a32513bb596bf4482dc5a075a68b1b4254be
a18492549a2fc26345fde16f7bcc78b2a6260c5a001bfd135a874373e1cd04dc1580ec306046f6
cfa203db43d39e9b17fac89bd7b8cd0ae491af9ef24e5b2280e77276c7bae7c67a4a87cb5365ef
cb1f3ab66b51c906db8da9866a5fbb2624e9d57de5369458c6cb17369747ad42fea8b4aaf8a869
5ea903a22a16f42f24422c41f251581eb46a4c5a7ca1aab9861d6a29cb7085905b86def4fa530b
a58fd7eebb1035604a196c765084dcc4ddaa9a7b60835e4e3d25d5bb9b503caec5643daa256b4e
ac0e43d03a19dae6c03fc83647a750aacab0b7f922dc4f4971ca32f6d0573f085fbb2b0c0a15f1
ab6b1b729965b72c0f419e9e5c724d9d3fba21a07cbc171e438bad908d3f9e4feeefb71bb5c068
f311095af3ecc51da1aab9073b3c802f5c4ff8d69c9e59913eb677c827097b40dc4b4caae89d98
0ce97868eee6d14663e5c7087b34de95f8ea4ce9da836ceecddb8077c6ed3feaf01ced135d301d
9a778abf4bf37ee121603bef623dbc9625dcdc2715661c35ca40332e816498c14a5adc059753ef
e2202db8c8bc1cf922b26d7e1ddd1959ab0a9d7350b8ec54bf14f2b584819d52d04a4c7e73df14
b01a4a55733d3b2c675a86ede2611907777f90babee39cc6ae06cc38c36a76d8d0dd632ddc373d
ee36dd2ea937f5dc53d2caee5e14932b537f620d2904edb939514d87e67874dfbb5370968ab0df
5117b487befabee1d502876f5d80caa4fa8279721adbd1199ae2597681a5b67d78751fadaf3338
772e1c9686d060882fbf26233841fa0b6eea025dadfabf8dd46a11e0ee775c998555b0a9dbd7d4
382df7170ba08e957a9ca840b50abe2a089d453fcdbd1136f6ef820b0c2ac42f393a7e38f166dc
17538356d4a40bebd19c74e73b832f543557b18391a9905364583be4aec7a060efca708846a801
53cab0861dacee96e99cec623b03aa9a7e2843390b2db7be1bbc592fa7b66ee6daee26d49814ea
4d9d678d13ab3168cfefee5f37ed7a4e07ebc61288bc1df6d105d9b50026de2ad723cb81c1bc37
0544b2d840be49dc1611ace619929f48e75f93c3a552df7174950649b62c29551aa36a31c0f2e4
cf0afd39234c9d08062d4c54569135b52f41655c452f8fbd8a19cee2a2c6a6ee9c9524fb9d1783
116a8396c8798ad250a62686aa66ad1d42264ced28849c450683b53ba4a209f9758f4cc1022407
46ed62c25392dc71aa0a161dcb795421fb8f691a9bab5767f6c855d56264a8233b25ada8183026
0a25180ca52ba2922dc19bda52be96478967352605a3a95998d44dfc65d99233faea09e606edb8
645309653b147d213a8aca52977ceffe5e3022ca9adaa80530f1d559999c24d38a74253d63ce29
400ef7b75164257b378f6be49c2e4e708b166439888dcb315a06747a6e4e33e74a57d082b834cf
73c45e4265157cab2298387090b9926f66d0cbf3fad1f7775a15f5cea2f090d5ee1e773368a659
a24278c1cc3c23a841cb652672d251c3379aa1543557b1834e31e47419560fb9d521050357ca8d
c5d47189a6b980513254db611b779348935ac4914039f3f7b2e36c4ba82ca13ee4d4d69db86375
7753818698ac3594c6767db5dca4a2fc231d4d2594edb0832e689bc60bee1eb9c419aec201f0e4
261b0098440d98bd45144f4121c2afc527ee40ae77627d5b7097007c46fa5db11e81608377872c
cdb934e7ec940000003c2ef238d15536f7019f8aad4eac3420a682ad4fb600f020f045709230e5
00f260ce15cce2bee65c31e17a6d3e4f0772fd13eb51f637a584459fc0c423cdb9cab61a01a770
b51600007c1278cd257a3fb0029b9d58afbc6017801b202fd61bd2e8e24ccd0040080206000000
b837c23957bec1242b5adcecfd8d4ee4ddce119f7e18013b0000000000c4842357794331df1778
6a77b7b4ffc5bff722dea9c4a3660020040103000000dc1bc1c8d5bd7c425e98d12e7c715419e3
2ee26ecf3c1a4c7cfaf52eb0433dcb37ae07000000c01e0946aeee857ec13b6065f21500000000
0080dde1df01eb66aa16bcf16cf4ee35bf095cfa288c4f412d499ed276c452516101a89a618270
8a2e94a79bb31b6f83c2df0ca206193287136a06d50e861284e157b2c3587203c34e25be9c90d8
dd49e18a250d1984f0a7ecc6d75342860746291bd8d9809988222a197b65030000003782e75ce5
344f8306792ae8e3751897584fd2947f3426f8960c43ee05d67db9eca3c3df12cba81954ca2524
bfd2b07534fc52e0125e1399c2fda8a9cc58661739e35a4672a614328c7e1a5e2d2ba8425622af
228c0ba401378974c2c815000000b82dc33c2b0f08e6cecf8553689e361e4364f364e009c21bce
b9bae487652c4c27f278e63211953f46870757050e35434852b8602841a621c752d97dda4d6406
553882319cd4385421060fa645154b1a32880c83cca245e0535548c21a7213012387872e7095ce
8f2b00000000accc3067160f20acf4c3a3c28c977518c145a523b6906b8f5ca70e64c1f4916b7c
b84c63776651338464eda09620bac7e339abe5855c0911391992419e62493503cb90e8ee468d5e
2a5548c6aaf874c0b831baaf8515b79a1100000000ebd33fa175383417de4cc04d94ca0e03b338
772fd578cdce84dd1595db81a987d76f37562a419eae7bafd8e6c95682448be77276f9dd437e01
cb4dc132b4af1c4b7d720b0378d70b9fa14a4d1b4ec2b6395065dc46a8be53b5fb00000000b094
afdd8c1d9d9465a0102e729d35008d76719a9ec402e08e90b1f52b350ab9babbfe581900000000
d37c7523cee7939b4c7aeeb764efc6a0fdc7799cbb63dd19ffe006c40fc65330964f16f2ee02de
d72c99fb7c8a3f2a4809df948b96a48af6e0f22713b1955c4e7d1c06a99bf1b409b902f2ceee43
73e467b3de31e10a000000dc125e2d70f816ede4aadee41d73784bd7ff7d77c56570b75cef193f
622395ddfcf4de90951e87c11d63d728c833f56d66b388ce77e7eeb2645887da36bfb229561bd8
7115ed6b2a79cbc347872a644065c89ddfddbf6edaf5dc1c7351ddadd92d2ef206000000c01af0
c8d5bfebd59de3172c726564d5814f6e55a20c717a6429240d3dc26c75838a6d91c17d2f3f0daa
4e27f9615f8854de1d24e7dc4b91e37fb1a67ed1489fbcb35e784dc8b00e55868f1303bb654815
495085970aaa90c42a21d71542faad352e07000000c04268e4caf7f4e55dafedd3c2957ce797ee
092d8fbbd59bbcb9f4d23cdff5bb4c63f94fcf6b0ed456e472e4e51f3d24e769eeb5082f1d491c
4a03d3e19b73ba92c4ad3059d7b9bcec2411817419be51852456093999dfa5b293ba0000000000
c0eac8cc25ee652fe66dbc3d1900000000005881e43d5272affc9ef729bb2d18f703000000005c
8d7859a7a4790f6901a67b4d1725ecef0600000000702586211727cc172e23ff82590000000000
000000000000ccf00643323fe7669b7087140000000000ec08decfb543de05cf1b00f91d5e0100
00000000d807c1c875780d414b83d86e8757000000000000f641307275ef350dde012b93af0000
00000000ec8360e4ea5708b46edcbaf01db00000000000005c91b76007a524e1d5410000000000
605fb4c77edf4ade61001bd70300000000809dd1af16788a17b96263010000000000b033fa91eb
e1d05c78652b16b90200000000809d72784bd7b60e09efbd040000000000bb028b5c0100000000
c07d30bcebf5e0a65a3170050000000000fb83d7b9fa9d5c87d768010000000000b02f68e47a70
93acf2aed7f6a9b9bcf30e03000000000000000000000000000000000000000000000000000000
00000000000040156ea75b6c700bee17dee7eeee03d8a0c55bf21615d9e6af8efb6bfe8fe16eb0
168807e1461d08b81afddb5f1dfc1a8223bf356bd8e115800aba37b421960000bbe42efa2874a4
00048423d727f71aad0bef89e57778050080fdf3f2a5f922e919fbfa0100e6810ee4ae0846aec3
6b085a1ac4763bbccec54dd64e4ccb77578d92e465b30172632e9beee65e07df928852a2e6820c
77fe4ab3f30bf7052fddc75960a906783ceaa31aedc288d150357dd4661484dc433c2026c1b604
23d7d60d57f96a23987c9dc7a179e581981b04c7bc2561cd2b131e3fce49cdd1183d82ed506ef0
643a74080000000000d1c8d5af1068ddb875c93b6065d6f64c435e7e2f97e7f0c61f2fcdb3ccc6
7f695eb8a2b7d1aa9deeca324ef6650b72e5e75334220cd668876bb1c32c82fff5e3d87d338b50
052779db1ce2a16b9841ecd0d9a727cc70e2eb87f195c0245e4d1e138b22d99171680459dcec09
2fa0276d15942f292c243c8a52de92d325c8e11fafeeeff254fda4166677cb5d82218d6272b20a
33e52a56095a9d8a783052e98b921d3c9a162aaa9a3ec3b2e65fd0424ab644f514b34a28989a50
eda0506cfe44c10ef213e50f6fd0893c894f170b6931545838a5c4dd5717920d38156354a9fc54
16d2a2a6272c2ad620f566a460d0783bf81b2fc92c19f2f82aa65bb7b843be9c54a4a08567ba0a
2361eda1bbad01130b496956608388d019499a6a5a59a81cca1f069920e52771220ef66e1b1f35
17292149435848f338a6711335b0515449b24a356ae4d2925319e2d2244ff7e528c36cb3480961
0fc2296a1e3935c30c5da5235b0d52e44a08432589a84c14154b980c48cd59abb87b284433948e
56c50a415b66a284488beba8394b8b6576c80b29c28c9f6551d59c7096bdf595b530457511bd84
a5619fb7e414b912c2365eb683fcfae12fe73e9aa3efafbc9c75425a4c5deea33612b28fd2e44c
413fc9df652175352df1c079d2e49b8f94103601fe665e5f5d46aa289eb3c41d634506b92c5a5c
b303591c30894fc13c9cddc5be6cdc1943250f078773a4b8276e3ce338e862b1af28f9b8002a21
3c3c1a11123eb2831625ad6ec8c2870c91d41f62954a9a475263d880930c826413fb2419124b5a
90d2022dc4b0a1fdc38b42472800d31d1256cd7906b972ce7253f563f8c071e3b49490cde351b4
e8ed5070b794909af7307446aaa154d42a48c750c10541abd09750130f2af5be30daa1a0c580b4
9ad14faa9ab5cd5fd58211c9ed658e2995603075bdbbb302848db76c07399c127d213f89b44eb0
5eec7a2109aba9b9f0a48fda40c8b028f151270307702a754e48a1a4a688d40b2f24f110554d48
f3f163322e212a7cda5cbaa9b3f442fa323be30796f4ee1814e1a366691166185731b0a803f112
d2ef530193b552febc098c385b8b0fe280b0137a483c17064d12e88ef8fb2134e3b44012218d92
38ce84484e89fea08513d9509b44aa8853742c67484b0bdbc9b88451fb5188ad2a445d15579764
087d4774be2854ddcbe94d37494e1e87a18492f1552da4fc82bbc5ecb1bb230c865250ab18b120
681572f69f1b0f0af5be1891b543498b10317b12bd06356b9bff88ece1956512a5126c615fe56e
426a3107612270f851641bfe16315611b26ca8905c746d20a414eb4ae5a2dca4a3388ee4191792
1352a88a875c0629b0ab8b334485e724b19a3a4baec0a4754bf969a3f6d8b4285731c0ee48ebd2
dc1d5a201f30ee83fb9e92b5f70693f4eb5c0f87e6c22b5b172e726d9b6f6d7379e707bc9a6ebd
ecb765715c431f199464e54d4269ab2fde51a17b466d255efa95accb392ce90ebec73a441ff9f1
bbf675301425f75c9da81f50b2d5b9d3eb959a2e9560eeac072a4bb0695152411e43ec233683d9
5093a8550835416b63957898a4de1782668792162aaa90f2477df3d7b4d80035ecabdc4d581aaf
eacde01c930abc8a906b705521a5403ae1b687a61593f2f321eea986554f436ad39353bfe77276
b5bb27b637c4d2bacb8aa85a5cb703614a0143d49f3741c7d7e1ca4fbce27a19b9e6986359d7f6
42bff2f54afb6d387cdc0c64923c899ef1135a5aa31b708abc35a7e7eec0e753f7fdc6880a52fb
9bc580dc24c256973ce3457a25977a7ba013527669c95ea46ad497f000ec24686fce63d8e1f378
b3dc7811d5267878faf4e492ebfff9a31bc8ca47f088e0acb7125f9d295dcf220ffef31ebc9d71
fb8f165eb3b30b6df34a23e2338f3ee3dd0688c337f7efb25d6333f0dc24497e344a7c652e47be
ba6a9b5fb541a7ec1b3075fdf7c283d7f01a60014f6e684c1de3c0e5d4bb3848f68b84817370ec
c8c5262a4aa8d242ce139a61af5bc58d82f61af15055c2223b8cb550592decb3ecac0b2ab09a1d
b28d77253b5cd7592b512524472f85319d02dee9984bf37ee1816c3b733ab09a645e49e6a1c2d1
b36b6b3ddbaccb5cd0ba552d126ed981d49f373f3bbc5ac00d22e5f604cfffa9371752d8f4d455
795fbac45715322c9302c30948ba287733ede7957b79a9ce4143461e4c874d4e813b0ee97685f6
5875bf8f0c72bab879685fe098e307ff7a694e53365f14d6645ebf9286aa7035f87bd67c213196
8a94b55744e52787cfed6aed250c3e0da9d742dc4d57bda379f1aec60daa60aa82d6c675e3618d
8822543b94b45051855ca9f91bbd1906c0321696b086b32c8db72aaa578a28a1ded479d61092ec
4657b634e292ddd369987578751f174ce8d4c403493cdcd6ebfde506d33d7e5048ae2f348a1a53
d7b76e558beb7620062c0d87a032e5deb59716e479cbae26363375140507595f3c25aba193143a
51bc95f8750632f13e915ca9bcee2a29df491ec4878f189f64ab0eab54e32a7aa9ba2a82b55f61
1a8e98c83063b5805a05a1e5517d21764b53f6ae07d73596df5442cea7aaadba0cfc6bd9dd5331
331c6531669972156b04ad8245857a35cb25a85ad8ec304e7909a5b471346a85d4367f550b2197
cd584347a104d5d4c42c63e6501aaf6607b1b3c8234549d5ee6f7f1ea916d2613435d795f451db
08d959b2375d1781d953704ec88e6bc4c3b4378f2c642a89d1d4590c66544f498a16862a064497
991d8825603a77276954511706a18f40ca57e70f32b15ce4b91536f6ab901ebad2ca1e757e77ff
ca7558faac122f4e08bfa8850a0cd636c8ac7e54a381cb315a92757a6e4ef3af7d23482a9e7b7e
fd988842be6b5016f3fcd23cdb47ae0c1d32e83e3675ae5252d66eada87cc6195cd6eed83095d0
5b2f4fb51662993448fa45f48e6b5741bf5607ad05927928f60af1505b82cd0e8a162a9a90b5cd
dfe84dca36a7a564a82ca1dadd4ae335daa14c7d4c12f5a62e532da49c76fd1d6d79a8a8bbff69
a73e1e027f11e4dfc89b41e1a45dfe3669b5a99573964a590b8684bf6a07a2623aeb01f019e1eb
42eb2c11000000704370ce02b309defe0a0000000000c08ec1c8150000000000dc0718b9020000
0000003045b2cfc03a0b5cb056e68e30382bdd8c62fca4e77cf40754c103718fee56c3bebe5d5c
a365a9acec0bf4f646602861733b2c1be4dca46dde27e19c2b6f06218fc0bb0dadae6335f24de2
c4d577affc24243baa00002ceca1e1a0f1824fc827097b759083e65f4d387295d790f2c61264e8
d9ef23b020fbeaf386145ffa3477cb27f01978f11112ef7502c003a3867d7dbb40cb02e08a540c
72d036cd042357b7f1aabc0cad9df91a0f9e8acfa4d12585bc38ee7c5ae895fddcfe93972c6425
e92ea7248df694f69b0c8fd35cb5dc7e7514e2d80deed1d920ec6fdcb2c61d487633f695d843c3
41e355416f6fe48efa87ab86fd4e02c632c841f3af2618b9ba37bc05ef8095c95790e1c0afaea5
ff8f1ac95bd2727801c6ad9b1200f706359c6b0e5e01b082de1e803de3dba1bb765976dae0b993
cc1beaa6266539595e7146b2254775c9cb192cc10e338ffb91f0d7656f5773d7d91fcd5bf06e5b
a1bbfe0e4c375ece527f5d9898c2f83ec0059a4e1aca666ad1d4a748655f4220e7a44d24cfc492
20d59b3e03196a89f1634be6b528da4167da5961b1518a9b67c9d4fdaf5372ea55046a76f03743
e0cdf26696511522d5d8a1a1b473dd9d68ba72c3e103f365f2a49dfc64924110490a2be1d40c2a
8512623b8cbd590e39a1e08b32899586f4f97afb326b19aae04dbd0a0349212b37bdf5ec4084bf
ce0b18ae622a4951263b08c5d6bd5cc8c781e75cc510e445697b1faf4318958cbb4358ec301ca9
c7193c3bfa75f2a5ac45e46db7a7e0ddb682fcfd12ac5039bf3427fa70d836bc48cd51b7f22d54
5bc562a8a2a9a92b74511440a1952921382493a18c2a649ca17d4d45d2a1ce28b6a46b20496f52
b4834e6c046196b34ca6264672ae4c6cabd9de8cc92cb2dfc0dd35bee07556eeb615e3e22438a9
3cb5cdfb351e1bb8125ad8eb2157ef0b0ba390f88cbdbd85a2a1ac1dc855a9697a76360998eb72
17426e89bbea122fb269165e26f2654761b0eb6aa9b8062d1deeaf788258f42372215dae24874c
5cd64cc247b95861430dd54d9496c85c698188096b67ab90c537461443c9c750f791a949865000
3991a70506c28bcc795f889d473fa9de944a07fbf495269629204a0d2588247e4462b0838ac559
e598514cdd1fee521cab6179a52a3873f4137f3336acc99b59922aa4c0c0aac49aeee69f869c3d
5923d81b8e93b097398a9cd1c9c63121c3c044d80fa81954264a50c29ebed042aebee9116a4cba
34ddf41eadb79fa6d250aa3789d5146179566f7a42a51dd60918a3ad26ec3030d136d712f2fee9
d7b93ec58b5cafb2b1c0069ca387f2448bae01b4cdb7b6b99c9a17afda992f91595f3b47ba3cbd
34673af0d29ca8a8b63904c75f468fb5f9bd1a42a477085339ce6721355215e1a5d88c55cb4643
154c4dd51d83c3279ef6a32afc139794df6597a7322d188474932297e6bf7cef706e9e4fdd9f26
44183aca9740a57109d16440d10e2ab5ce62d3a9a6768472d2df5fe89f35a9f22633340aee88a3
471c3670776ff6c5be706d9f9f6d957f2912ba295812529e7cbd0b0c61af865cbd2f4ca0b73752
dd575f9bfa6ed0c4f503e6badc85901bd18f5ca9af9176e81c7947fd6c8cc4621ef66efb1af520
6ee9bd9c6c8c48e8bc77d12fd5ad7f53a3927317d9af7c7d165e659ab019aa646ac15fe6d2c565
ee5ee1f7b8634a3e2aa842ca1f723156417272ba9c5d81fea630a1dba14ca5b304cdd444ad9c1a
55de1cf1f2253a9b6ee4ee3a5f8885a9ff6c0f4d2b45f128d00de3aae37063d4b02f85dc4a4d4f
a514d29fa7b737a0b77d4307725d56e90635ae1e30d7e62e84dc88afdd1521b547b1880bdcfef6
d09502e87e71e7a430747872a8fd365829eadc19b9a44b4ee4dda6184152fb9659449b6e4cdc77
b82a2ea8de9ad373a7dd55665c1e854a673d8ca9c50e22ffbcb5c2eb51e50b1eab3d3db9e4467e
fcd10d64e5e303f1495af7bdf4f695ecc49b373f6781bbe2ab8b1817acb2712ecfa50f2d2d985a
7f0c2ea75eb520d9fb91d7ecf568dbbcd2c0ffcce58cee901ebeb97f6f720b86041a149c79ebb6
ca5007b71087a2e838277adc2db69993fd95deb4909c9ce464769581c832672d32f502c21ba072
7a2eb3c09b4277efb26d7ef5f79a7b367077c7325fb0bea4f8e1c0cf635d9af70b0f64dbda19e8
ed2985fd562157cfe7eaed97b1376f569cb3ead9ae87a9e02e84bc3ebc5ac0b537b9b9c3d3d1fa
cd859be2eebe2d80fb1aba801e563733edd1dc3cb8210dc37a497c8d282289ddc2e922ba9c7593
f9e74dfb05aa34d171de89b3de50cce0261a85f039201cfd1024a75fd574fc7085fb1b733aaa90
3c6ea00f3e03fd34ef46587f720a1f551145567c4edceeac42d8aba63652a8c20f6548e0ac19ab
bc19434dec74899dbb81bb5905a32fa6a0fced3777e74e96e8d150eff0ea3eded350c616f6a590
5bc3179e424c96a8efc4b6ecedfb9b9ca5477634161a8a297933a0a68a32f54dcf73b380d980bb
10724bdefaa7d5288096ac100856c9446934db4f26a6ef13bbcfa06fe161ea0a631992929d3ac1
23b153721ac599328e3cee2785c8e38a490acbafb54008ab33eeec44eb34cdbaf35236946aea9c
9b7c72c7cd72c4d49d23ad10317598de58c819c6cf56e12551ed60c0e4ac42d8aba6eeeda0683d
a78a23173804de2c6f66195bb2afd4de7867b89b8bba46c3e94ae80fe944caf6a813320c88050a
b5ab1954a64ac89ada671bc54398c4d82b343d22575157c038607ae3df656fdf6bba70e45a6328
83371d852a663111f6f54dcf71d380f1989c3e618701d1c5d83697f9e2bef9ea6c416acbac805b
92b574a6640b2ecdb3ac835906df8908260e1ca7e7f49b29e8622e6b9c73b0d55ffa6409afc130
96bf16e797580692e2d4af1f32526728a775b0ce44ee6e24221154e0f0e5024369425e8ed19a2d
fae93477ea8baa8817ccb839989a081c61725621ec6da6d6295711fc4466cc4e29458a2cf06642
5fe9b05be1f5dd5ddf70a417f58b49e4c1a6ee76d61d510e7b43c8add0f488424c5aa8ebc4eea5
b777d418cae04d47a52f34ea9b9ee3a601b3117721240000ec9ddc7c060060063cc7864604808d
7e572c000000006c8f3c03b7f3274c00d80d18b902000000b7829f8b3abfe09e2f000000b00158
2d00000000a46c70767c8c2af68af531dbb558c3d4e9b3c335cf71030000006005c2d502bc485c
9ee4757b7f5ce73cdded7f814100d80df53189a80600000036211cb9f26b08640feda716abc5c1
67e7c5ef401e6f1204000000801b118c5cdd1e75f2c2c6f68aef7d715b03f62f2349d8e086f2d6
f7acaf83aac563a8b91985983472dba87e0c6028000000068291ab7bc163f00e58997c05000000
00006077f877c0bac90ffb3b607975ecd47bcc8e1fdd4fc9c32e49feec6bf45cf262040fdc8499
ed13342b5611fe3abc3bce82af22784f5d769269aa0a550b5dcd9e8216e1ec57982d2769097f2c
b93b9a511b3f3ec5df8451619141f2f8342ed07d336deac4565331ec904246cb58cb2524bf0ec9
fb62bad892303986baa8b4d0bc065313254bf6bfca97a152612e932f260ed70dd513e6cc363d25
43100c9379000000ec1a9e7395ee9e4e24f2a0c9c7ebd0c5eb67505e60e0e66b99e45dc04f6df3
bee27a59962a3c27be8dce6db594ab18fd3abc9dd20e15129449168b4a58a58a32c62a46d96610
1fdbbe72502d605a061a2a2565a69624e8f082a96fcea579bf90589154a417e97bb28f5c1313d1
3071e68362264b12f5be880f9fd7784787a7416bc930aaf15b561f000000fbc74d9948b7ce2780
64d2a58cdb88a03f25c820b81bef8ece258edc948fe06498aa9a8f722938f7f801b79dca2a9ca6
e1e172887da0d057e1d51779c2122c5594b460ca19d42a3aa9287953709ee90a5368e042f9072f
f78a7795f2c7483cfe268c0a5506ca10962035a64a154d3d30aa3d8523b9e4e8e912cabe905fc3
039d770a158d106f0e25f48acf3275c992de7494ea7c516ebc6543a9416b8ceaa4fcd60b040000
e03ee8d7b93ec58b5c676d2c707193aeeea12ef9978eeda660a92879e46b2dced153de22e4cae7
9e42156df3ad6d2ea7e6c51be7dc9c282b5bcc0e95f0dc8f1b2e477e6fcaa13f85af5445097b15
a129e8ef2f2caa0d79daefbffcf0e8dc3c9fba3fe7312d03996e5061e281c292a9f78148d57eeb
8d7f685e676debc1deac34b5c5928e3a5f4487d327ce6f6dbc6ad01aa25a16ee2793c158cd0f00
00f7463f72a5a1861b80cab964e670d39f84dccb97cf7cf2e0f1811bbec8687825669cd19752aa
82cf82ed2bcfe5f489c619f46dbf56c2c4f7d822d1c795aa2861ae62b9b5a5a8355cafc8e027f3
feccaf4628997a37381ddbe6402e902673694e76cbb3372fefd5a6d62c4954fa627938116ad05a
a25aba265e45e0320413c0000000ee87afddad3d3a634abfefce3a726fd4deb9f318e5e9c92537
fce58f6e202b1f01b8022e6edf9ad3336f47f565e99cee0e9021dd2b8ff6dc0564fd307426f596
bc175f449b97a92b40000000ec91afae3777679a4bf34c7d3adfceebfaf7fea30ecfd13eb5eebc
eb9ec7e2e74edc40b6dde92c570d97536f9c20554d27d1c5413cc9bd7a156336a842c529de63bd
6bec39b8058b14a8c739013636f52e90fbda87e6c8cf66cd7ba251ae12e3d972b7f227a664ea45
968ca82fc1861ab4d6a8e6a50edd4f3b5b3d0200004083570b1cbe75a740b9e9b6e0be1e8d50db
6feec69cac1bbb7c6f0eafeee382d719b81ba6576661156777aa6b5f470f79f080c34eb8d2eef8
e18e1da6d9e654a16a91cfb0921625fa47e67d1554f8f80e72b81fc5d41dea3283826df32b9710
0ed18892a9b7a5ecacf3bbfbd74dbb9e678eff64201e989a544e3c4ba8a6562da9525f82b03068
0d513db64cf6ba9a0e71b79bb061160000ec99b7fe915beadc972dff720706b7debade3f5b14af
87cb3fc7ed572904a93bd7f051c989472a9d7782a9ac2258cc17a6f8a0692c875bf214b410ca19
b42ac47d892966e14fff3ebdb125bb3247e21d397ff2c03b7d3329434e419fdc41b33cc599f331
294875853bcb85125467117d9e0536af35b56ac9be8a4a5f2487671a6fd950aa43b50c5d1f95a4
914fbd3d31720500805df2d5f5f8d4b9cbe4a85b99ba68524a0ef7ab5a2f672e64ee333a97e6b9
e20d9c262aab881fa9164ecfe9376528fff004342fd2880eb754a16a51ceb08616652ec768b123
157e0a67df63f1e8d7d9379aa98460298bdc261eacdaa3987a1b546711324b4d9e992f5fada96d
962c515f825036941ab45a86f34b2a951355750d000000000048782b4fface61c9bd0800000000
00002c548d35e357707537cdb1e5130000000000581779f3934b8bb767caadef5cb05e16000000
00008012ddc8b56e8a7418fe72c23a0100000000000000000080fdc0bbd2c8848d9bc5c1db6500
00000000c08ee0371174c83bd0797b9ba7b6ee3de3000000000000ac4c3072756faf9157f2b40b
5f7f050000000000c0d50846aeee1591c13b6065f2150000000000807d108c5cfd0a81d68d5b79
f2150000000000805df1166ca993a4b5deeb030000000000c03ab4c77e5349de61003b99030000
0000809dd1af16788a17b96263010000000000b033fa91ebe1d05c78652b16b90200000000809d
72784bd7b60ea9eea594000000000000ac0c16b9020000000080fb6078d7ebc14db562e00a0000
000000f607af73f53bb90eafd1020000000000605fd0c8f5e02659e55dafed537379e71d060000
00000000000000000000000000000000000000000000000000000000000000ec85b7e41d07b209
d783c17b8a5d7737dcfa2a3610f26ab8eddb8a6fc7503354e2763e7e880d8faf6da89df049d4bc
6b9253037613bf1e30357814fab7bf3af8350447eee6871d5e01d8096df3ad6dcea7e9bd2fd40c
57a37b11dd359bcc9a553cb4a1066ea7a6caa676d83134964a864f4fb8cec8511f308f616a341c
c08423d727eaea9b0b77f37e87d7b578f9d27c91f48c5db7c0120eaf4d7b694ed361a96600c227
3114e261eff0868c743e78f667872fcdf3517e03ab02538347c55dcd04ef8095c957137c033a49
937722b8f0c7bc667aa0d502ea6df1adef9b73d87c14ba5a35c31a3cc26a819ca11e6615c4c026
f170131ec6590f18757b65ffa6463080390473aeed53d37ce709d160f27531340e7ec8d306b809
edc1c5e4693aa2d40c40f82486423c0000c0e3f3d65ff1b8ab9f598f358ca7f16416365b4871ce
355c423e9ef495cb329f32d767527890c68594abb0e0160107850cba0476086b198ba9ca60a942
90a2e64e9017840cbf8c52ef4d35c35045e08e8cb30287aaf253a5e50ba17186f0223eaba910fe
9415c367a0f2938981f058c990c110930516549135b5870a0c0b49ca1f52d2780b5518dc6dd2a2
10f6c21c4b266ada6332143529df145145214d76982e21397c48a39e76520badf97b145f14aa50
6119a6d250546c87c459c6d63d851c4e75899a613951456bc8b0dc50f1b194d28051bd797d531b
2d29d97c0a7f4a741c5210d58a1d848216e6b007f7c464e84c9f632282b0f0b83247fda943c26b
3c728dc34e52d8ce93d097147504b91222f9b52a74722550ea0a113b1c4779423ba83258aae84d
2d9dc5bce6a709a9f6236a86ae0a594a1fa4b1a9bd4fcb5e906c0535b319e4cbb1a643b6a5bef0
f64f4c91692cb9124c6daa47af82ad9da671fb62c686d2bd4994ab30b87b99a1280d85ccb16426
1e2c31a9c5c3b2880a85ac0c1893b3ca5a881de6f75194cabe882c59261b4e7deaca29871c89a0
faa2881cfee147e71fcdd1c746dc8fa569960c9586520346f5e6f54d6db1a4e44992b78325aaf5
8653d6423514b8535c6c8917b9b125c35005098be090d20380d298473f85576c0e09c4b8fd8cab
08bfe91a582c791b04a65a858a949086fb61d4058c9a9caf5395c152851c2e1698d50f3a0c4212
5963869432f455f8fe45328f4ddd7daf69e1c42bba299bc1173e68ca827991555f8885875eb2d7
2ba335ff34ee4fb3560a637206135588ef86effb9365d6a453962c7953ada2378bcf30e56ec784
164ad84f483865c98c9a0621d578e80ea134115133849cb083a5846c1e8fa2456f8742f3577da1
1aca48411135aa555f94f18753feee6cc5e538d5fa02eb6558cb500e3e360d1829301460e44de1
7aa6b65892f284558fcfdd4441c288ac1d542dcc860277860b26695141505af16111a77c211252
49ebe52f93700c437f4c26d07b317c938b985f458a485ec82f02c4aa492bed445265b055415a8b
fa794dcba842326a3f52cac055246a2eef26b8b492a6131944c2c9f384211e9cccb12f26b5cea9
ec106b2ff35442b60a293fd651849c12262b89eacd521539c126dd9dd5420d7b42c4b05832aba6
2aa4211e948822660a99da813094507296aa85945f68feaa2f0c863232a9484ec828e4fa8f255f
1409ab0e0752ee6f51a45e86f50ce5c8068ceacd9e50df886a35c392f3961c91156652c204b31d
222dcc86027742ff84d6e1d05cbebb3fdcf5fda5e13f977339b94d37666c47c3cf84b5af1c5e7d
7a755fd12f01127f9c3e5ebbef06cecd0b57f94abd03e5499a8db18a02f2e0dabbb2ab57693731
55065b15640752fff4dc1c973e45b7ee966759bec7b2251fed1cc9d1e792a6e50c939aaabe903f
e499c5c594637225a4e57a2e6727b37be03246b56401b58a2a775bc2de6cc9829a2521d578e829
b59d7a77579660d342eda34abe301baa124b5457f663df832ab24555c9b095a12a8d40d49b5ab5
a472ee5e03558b7a4381ddf0b5bbf2a04b1d69632eaae4b29bd29c7ef3fc72dd8de29c9c6f6eb8
d65571eabe0fe96478e10fa2c5c495e25d43cea23648e7b6c7bf5e3cb8bebed4e3a8196ecd5e62
72f786523159f2d66ad6bbfb937462e0f3603977033087afaea37491247b14f36b02baaeb3ffb8
1932539ba4ee1c7470f7114830d38cd13938567660ee2955a1c2d36fed373a9b545192c156059d
985fd83577347875ef6b993f97efe6cf8a9bc9ab19ca54c5c32ca663b29e64764436844a66202a
0d65a922649ebb67b5aca22567a9391672b578a8777745091bf4721b349cb921770dea65d8ae87
a9e0baa69e75eeae600f0103b682570b1cbe751d96dce0b8c18cc5d935e6f635b3f625fce2e03f
b4cdaf748a92734f0f5dd825874777036d5594b834efae5377cf5106d53a06c1caa832d8aba02b
8d7ef06a957f3eaa5e850ce40e3faa3eb290e35b90b21489527efc7dd5d7bd1a7dc1ddae403fcd
bdcfa5c4648f628702ac0509392cfcea9bc6bbfba1c766a8bc376d5558dc3d8921ec4d96d4d42c
0959df3f18852c622fa1e0acebf6726b184ac118d557a55e860d0c55cf56a61ec2b52f3f3c777b
f251adb29e16cbbb62b03d6f8655d52578094bd23e2799baff15ac83095357aa1c3591248f137e
f4535451b90a0b136274bae7ec20520dcd40956156157d69719d452c42123931a2830a19541d7b
cadd841a8de50c5278a2698426a717cf27d9562953261735f49b3d7a4c32a6ee72a28abc167115
aa25157797abd0cc1831a54539ec4585d1af33d4b408a9e55123cae86ec7841d4c252c7096cfc0
bf2acd5ff385528599923db3550476d05b7711395c5416f5a5a42884ea6558c9500e2e2a0d18fe
52f126733d53eb969c08274943a9e5a8f664ed4094b59869a8f1f760677c754e2587ca0aebf669
ce4cc9baf0ddb1e402e9f4dc7fd34f310a720b461e65f09c5fd26f5c36592e2694abb0c06b2a92
5ae8f8f49b02aa0cb3aa38776b86e8da63e596466284a61ba36588dcc14a653598a46d5e0fc568
5433a868beb81ca32559f4d369e6bd273d26eb212de2553d54695485c550656faa55249a2e7037
1f52087bdd9206351521abfb075d480d5309aab3eab4507db142152a8690bb3af5326c60a87aae
6d6a0aa7a07c17cfe3e822ca51adb287800100dc31b90bdcb9c8b56fa10c350310ae6ea835dc5d
8fa2e63e8404000000c0fe586394f096bd2514a06600c2d50db58f41a1a22646ae00000000c853
3d4ac084eb5a6c61a81d0c0a7535317205000000401e8c123e1577e16ec4240000000000000000
000000000000000000000000000000000000000000000000000000000000000000000000000000
000000000000000000000000000000000000000000000000000000000000000000000000000000
000000000000000000000000000000000000000000000000000000000000000000000000000000
000000f0e9f9d2fdff1ef9f1e75f7ef9f9c7df8e3f1d7febbea983ca39fed4fdcdac5734000000
0000a8e66bf77f000000000000f60d46ae03bf1d7feaf9f997dfbb2f0100000000c04ec0c81500
00000000dc0718b9020000000080fba01fb9fef8f32fbf05444f2afd74ecbe0932cdcbd0c1f93a
7ef9f9c7ee5b872f21ca332e63f8353ebe2756232fa452c53452787a842b2d2fcc186b09a184b9
b26335edf50300000000dc333c72a5815032f6f9e9381a0cd1682af86e760637d80a876ce33ac7
79e232e25f33c7c702106e00980c13cb5594f9fdb7df7ea7237e0e0ff8f1e79f7f6a7efbc5b82c
d652422ae148d18ce63ffef49355090000000080bba59f73a5c192877782faf1c7782c44dffffe
cbcf92819f5fe211574031c38f3f1fdd606ba8c5d5312a814674be88911432de4b7e0ff8e9c8e3
bd21833c65150f13cb5568c8c0331c26f2dfbffd9688328d5a826e283938f417911a0300000000
e001e1912b8de5c2a1cfefbfbb215f02e5f10fdcfffecb2f2e3b8d98e43353cac0a3ada8169964
4c468d341cf34574a3399f83cbfafd97e3f0fb71c84b485de1975de6709858ae4247f41a4ae461
f18c81ab5a82c150e29d64ae38eb320000000080c7c23fa1f5d3b0b4327bff3c1e1b65464aa50c
3cf072b7c107b89278d048df767f8d919cda002df9bd9be10c2a295561820be8079e6eb4dc0dd2
ed144bb018eab7238f6bfb5c596f01000000003c203c7275a3d6e38fc96d769085c68a6ed4e86e
df93a9bac1f12c562841960ac8c4ac8c6093e5bc00000000000f088d5c79816872ef5d83e7004b
33a0990cbffba1f140b8486105c2a949426636b589da99c8ed7b1adfbbb1e78261a75e82d550e1
0096fe2f5f02000000003c2cfd6a8161e4d33d23948e028385953ffefc8b9be24bc65ca50cdd34
237f1b903ea25540caea9ec2725069d17d72ae22148272b0228b0697253a517881eab025c01ca6
4b30188a46aaf1af2b8fcc0100000000f60a8d5c65e4430322a11ffad1f829be09cd5f0c39c6a3
b642866e6da6af4488869e0add003410938679a100c9f2cf6931abf16361aa84ff3f9be9124c86
8a7fe51fe9ffdd8f00000000008f8a1bb9069b02f0a7fe0e74040d62872f5da6348b92c1ddda4e
0ea14c69210546628e96375015f177993a57a11b78568c160b2568868aeccc8c8d0d00000000f0
59a16151f9112035c3a3e1149e33613ca6be040000000080cf46bfce15d8e1d5b6fe86ff12ea4b
0000000000f87c60e43a836e0dad9b5d5eb87cb6be0400000000804f0b46ae0b98b74037477d09
000000000000000000000000000000000000000000000000000000000000000000000000000000
000000000000000000000000000000000000000000000000000000000000000000000000000000
000000000000000000000000000000000000000000000000000000000000000000000000000000
000000000000000000000000000000335fbaff5f9743f3e75b737e695ecedd17c0c2db9f64b981
750c085f4cd31e9b8fd74d8d93b8b839375f5eba3fafc1b288da58c80e0ed4cba9793e765f24d4
38eb2a2deb56864a689b8f0ffaa7393d37c74b73786bde0e2533de0babb7cd2b3beb975fba3fd6
e25f7f1cfff857f7b7e3afe7e3ffbd68eee646749b3804e08a7cedfeefa036f06773a446d034c7
0f8e78703bd28eb5699ed835002c438d283aedfdf9e72e1a3e897a3d311ebc655d9aeff27f1ad6
f47c0ffe0677483a6c25fef707fe9fc5dd347efdd38d68017814c291eb93bb749306405df979ab
692790e1c027d74bf3fca5f9d2a77b9f3501635ebc7f9fc9dbd7a422a2b61392f1234baa77fd98
bf66cbdad85016becbb8068cd8a1b32669ff9f1bb6fef1b7bf1f7ffcb14f7fff4d7e8b48dd7d76
0aca2cb54cc702f0100423d70385b55cc0b534883577793c53eba66a26125acb025a9e043a9f16
76a9ed1196071196883abff089fca637168f1f6e6479393949ae71ed5cd9b2ead9a06dba29b77e
2a4ec0f8f5aef9f70fff4bfffef5b7bffd453ec7a8ee76ed9a47e73478957baa00dc39c1c8b575
c355eed083c9570000d88843f34a5dcf19b717aab8d0c0457a7274e39f0093bb2fcd335f91bebe
f24700ee9b60e4ea5708b86989f81aae447cdf4d6e4c0c3762fa6f3c6e055b9fc6f30ee1aff3ae
0e83a53c852a64c2c3a770e6437ea24add1adfb8a8648264b990423c4b1d15ce5a50fae0fea55b
77d8274b5d225be6705ec59f50301451a966c1d483b30253cccbd03329a42d1e08ffebc7b2d192
e64d8b0c9348e1a3159f549a555a434485b2515a6887b89c25eda2698e2ce4e9c41f72a8ce9a94
c16007c214b41efec66e2e91cdd236bd18cbcce8e6d8fcc439df2f3ec6039a07699b3b6f7accbf
7ffac7efc7df7dfa63ecd01ffef98fa90ced1ff2e53f7efa377dfad761c8f6fbf11fff9475ae06
77779c9b137d7f58185400ec091eb94adba6562dfda9eb5bfb4e61f1692c039719f61d6f61973d
faf5f5637e1b2b5641fdb59c363ca46f52c5b75f79d6877e7a6d8e6f5d51f47797ab5e48ea52e3
1395b3f9f6cfc45cd917165327a6989dc122e41c35dbd754661d8b37cb3294b934efa3930dd996
4a3badd830eba90e18c13d297569ced9f3aeeaac6a194c417bff3c48dbbc87a647c35619747afe
7518469c0e1a9bfe9f7f8639dcf0f4903c8bb51ae777f7efd3137f00e08ee191ab7b12e2d4cf9e
f282986ec5dbaa4f48b8f15f3041eba6627941ad70fcd5f529be5eb9889c7b6ba35c053194df4f
0627cdb86d9d35dc4f6df3fae48a72d7a93df542be71df2acbf85c9287037cffc857cc949c3b62
6929e5afa46364b63b7378fc14c206be504d7de0dd5b2483089c5451ce6011b2aca65c900cbef0
f31666146f326a4c969193cdb7e0f47bf846df7239160c1135dc21996f01619580e9ccd2dff74c
509da5c8606b59e1f7d9a0adc1d83637405573ff6df30e9a1ef3d7f3f04cd50f4ec47ffffb3fe5
17e25f7ff020f52fbffdbdcbf3dfbc92b5fd6737babdfc20dffffd37f77558d48fc7bfffed0fce
3307fff83500774ebf5ac0f55cc122d7ab6c2c40278fa08f1e5626b8ff35df5ad70d4937ea905b
1b2ccc0c0a5550bb3d06e593bab9f510d4db0e22f0631c6e1591502fa43cd71c2ee3bb34ffc5fd
7ed83f6ec1957d61313555e1ed40f95d76b14f4f298351c8623cc82389ffe57d417e615f58317a
b328838a28de7eebf5e295a052c85e58abf172fea1b9c528ceda2a68b7812491c196e562752e16
35f7de36efa4e9d1909447ab1dfff147fc8495ec1870f94106a68e3ffef69feeef7fffab8d666a
57834ff1ee811600ee9b7ee4eaaea1b90b730ddbbec8750ea536cf9d5afbdaad4692e4eedacfb9
4426f46ee530949fbd351cf6e369692b09999c9b2fe71bf4261bf8423775d0a713e32d274b196c
4296d4949c13337c76546fea31a9e14a689b0369c7ed942a385597b9266b054c01d5595b05ed83
f0106df33e9a5ebf569552b27240f8cb1fffd1fdc5fce5f2573774e5cd040000137ce5e541bc18
48fa1ad791f1f220d7e3d85705dd03b210eaf4dccd67cc9b60037380a957444ec072b3d55d61be
2b67f47be5d613429f2468d136ed54363d5eb4fabf7ffbefee16ff30b77a2bf8a262eab60600f7
c357777fdc755eb21e88efad0ceb93825b2d1b70f18b9682547dd9dc73708f9a926a9537e0ea85
4ccecded618fbd49959a8b4c2d4fe714cc30ce70dd80b1b18537e566eba139f20322ef1b6b6863
055f8873f9e4ba8c0d82365c2368bfefbc231ea86deebde9b57ffcd1367f3d2b0b5293e9d57fb7
fffaf76822762d2462c733e800dc1bbc5ac02d3c975b337cdaa8bfc9321b5ef6debe76fb9878e4
59ce1571777c84b6f995afa4c3539142bd90b2baff10ecd8d08b718de1c8a0ec2c56f2856aea43
f03c72b7ff7c3ca551ca502f64ffecb02f818e9d778378436fcac3226eeee77c95b58f55ac1430
843ba7f637672354676d15b47eb444c159b39ca0dc36496cb9c91e3e6fb42277df36f7d4f4cace
fad753bf51c00ffffc1f5e2df0bf3ff46b062effdf5fe9dff68f61154197e72f7fbd5c6576d69d
e8a995ad3bb807e006f0c895ba2d19adba1ead786d7d3d5ef8e951ea10a5179054736e4891a1b9
5fe0d52f84a01e963e1abbd47a21a504a9d4251163ede1882cf91a94e5643d6dd4ab6936f52b6f
9d4bc92d83cb6d3753c850ef0b3927f912e8d8b9d76cdb7893e81c4a65af7d625e857a5f0847be
739d3c842ea8ceba7ad0c619685055d877b64065dbace551dae61d34bdfff98b1b7efa75aefdee
57bcc3eb1f3c9efdeb0f6737761df67c953c97bf2dd83740a77fcdc7ee2e7d01980d8d5cf9394d
b90e6b9f662fe5598d73e676d2e939fd663997e63958fc2037b3c2676c4dd40b193fee4ab8b519
dc0baf09295b5366a59a365393e2c397bc5825c9a264a8f6c5e5182df2a3634f732fdab6f12621
b35054be5dbd2da96f17427f7376bc8db4eeac6b076ddca6a8e4852380b89cad51d564eea06dee
bfe9fdf1b7bfcb2e578c6c7d156e35e0b8fcd0ed84d5e3b6bee2e1eccab4cd07ef23b6ec720b80
9df1a5fb3f00db7170cf884427bf0435c3e7e3edcfe629d88ae881214d65f2ef6534fa0157076d
73c4a2a6f7cb2fdd1fd7e3e79fbb3f140e6fddba0bf4a8e051e877c50200ec163af7d0a9679fcf
66ad8e1fb0ce7dd32600ab73df4d8f978560d80a1e0e8c5c01d831475e4de8ce3d9f69819a7bdd
d40d6fa903f0484d8f176f60d80a1e088c5c01d83fb75d1c7913f874fb195647805d73d74d8f1b
112e02010000000000000000000000000000000000000000000000000000000000000000000000
000000000000000000000000000000000000000000000000000000000000000000000000000000
000000000000000000000000000000000000000000000000000000000000000000000000000000
00000000000000000000000000c0f3a5fbff3df2e3cfbffcf2f38fbf1d7f3afed67dd343df1c7f
eafe76e4f28c498f321e767fb4c7e6e3b5692ecdf333fdd3bcfdd91c9ae6f4dc1ce9c33d73fc68
5edbe6e54b73eebea8e3d0fcf9d6fd299c5f9a97758a667ef9a5fb632dfef5c7f18f7f757f3bfe
7a3efe5f72e9a3ba1b0000c067e46bf7ff07623400a531ee8f3f767f3194c391e6fa345c64c8f2
dd8d633cdd97e04e4987adc4fffec0ff83bb0100003c0e8f3772fde9273720fdfd979fe98f9e9f
7ff95d7e2c4243d91edb010fc2770c62b29c9b2f5fbaf47ceabedb2dedff73c3d63ffef6f7e38f
3ff6e9efd91b0670370000803be6e146ae32bdfadb2fa5a16737447dc895002678faedf2bdfbe4
b8d077e07ef9f70fff4bfffef5b7bffd453e47c0dd0000001e86075c2d005478e0e2e7dea2310d
783ce06e0000000f433f72fdf1e75f78ed6747b404949785ba6f824cf3327474eb4b995f7e0e97
9efa12a23ce332865fe3e3875fe4fbb094fc77e312ac84e52cd1a2606afe89caecb28445c5a54c
cb60e4e5cbf0b0d1f9a5f9c2cfee841c3f9a3fff1cd2a1fbda7178ebbe698f0b33741c865ffffc
68daee5b872f21ca133f2fe5087e3d86c7f7840250ca0aa954318d14fe9628c6a5658599e0df3f
fde3f7e3ef3efd313ef4877ffe632a43fb877cf98f9ffe4d9ffe7518b2fd7efcc73f659d2ba1ba
1b000000b80f78e44a03a564f8f3d371341ea2c152f0ddec0c6e30960cd24625a479e232e25f73
c75f9f6a2dc6078c2de9bff9e9e79f7f3e7645d1df5d2e8b0c95c843fa216ff1c892a0919f7b62
bd676e0637ec0b87896df3312a21cd73683e8edd9f44f2ebeb48e64400e26d34d02c5751e67276
e3bfc36b24f6916a3cdb1fdba761ab0c3a3dff3a04234e82c6a6ffe79f610e373c3d24cf620100
00009f847ece95c6421e5eff993c8eef1e7cf24f3df1f34b3ffefc73307c5232fcf8f3d10dae86
5a5c1da3126870363c59954a2143b7e4f781be6879b62a5427f3ddc215ae2b684184b2657e761f
5d96aeec1fa9a8f07931930c2bf0d23f9c44c9cdd6b5cd93fcd07338b89d9524c389066a6df31a
0f0a4b19dae6571e53fa5adc8ce0a884d7d7e672ea327c7971dfb48110f42be1ab48f7ab3a7483
549f419eb24a069ae52a142ecd3beb75f025b6cdb7b639279228fcf53c3c53f5831bf1fefbdfff
29bf10fffa8307a97ff9edef5d9effe695aced3fbbd1ede507f9feefbfb9afc3a27e3cfefd6f7f
701e000000e071e0912b0db47808d5f1fbefc340c94379fc00eaf75f7e71d969d8249f9952861f
7ffae9c7b81679842a19b3d1706c18a4fdf69bcbec737059bfff721c7e3f8603ba2d58418bf870
fa9833f56fc7a486209751864a8ecfd196a8d9a7d1c30d418f32288cc79d850cedc10d1f2983af
e57c72f3974ff1a4e9f9a579f633a067cefcd48f3b0ff49f1b74fa2a28b31b1ff7485df4a5cf70
397603e861a059aec280e8f5add74b86c57346ae3424e5d16ac77ffc113f61253b065c7e9081a9
e38fbffda7fbfbdfff6aa3995a000000e073e09fd0fa69583999bdf71c8fb13223ae52061e57b9
bbdc035c493cdea26fbbbfc648ce4cb51b52af85a0983a5492b2747f75d864580159062a29b90b
2f441b82c67b850a850c4f3caff91a2ea5e5a502c97c676108d8b248ea064fdfe3a791ceefee5f
a95d98393f3a8207bbedb76eb04bc3651a4ccf2db25fab4a29593920fce58fffe8fe62fe72f9ab
1bbaf26602000000c0278347ae6e287574b7a585ade7323f13f7616ab71ef4a979967be872af1f
4ce0c6beb2ce81a781dfe78d5b79d1eafffeedbfbb5bfcc3dc2a0000000032d0c8f527f710d0cc
7bef3cc5579a01cd64f8dd8fd706c23be7f74195164b4c9de1ba963cbcb911d8cbacc7cff90e7b
69bba55c06bf027548bcd27445c2e955e2f0cdfd9b4cc45622eb1c0e077e36ebd29ce78cf2db3f
fe689bbf9e9505a9c9f4eabfdb7ffd7b34110b0000007c0efad50234f6e9feea1e014aef3f078f
c0fff8f32feed9f6df7ffb2d1c809532fce66e7a77df06cc78b048cae2919f40a5e56eb55f937a
2d18d5d4255692416758937aec560bc80d7acfb05740db7cf0e3f9c974632183dca37ffd7043e4
90e3dce7fa79902d24fb21481594c16f50d529327370a923cf691d5ce1328a1dd36d3136da3c81
f9d753bf51c00ffffc1f5e2df0bf3ff46b062effdf5fe9dff68f61154197e72f7fbd6076160000
c0278446ae3233ea6e6333fd7890864799cd46871ce3d7541532740f1df94a843943cf6e181c88
49a3b844806b53ad85d5d405ea2da92153927e9dabdf58ca2d4b0d3790a2f168b044b5196f0555
c870eeb60278930c7d7a9dfb5c7f5082db8d2a14a0afc2afa61545a6069735c8f259f7473f3437
f23f7f71c34fbfceb5dffd8a7778fd83c7b37ffde1ecc6aec39eaf92e7f237ec1b000000e053e2
46aec1a600fc297bef994656c3972e539a45c9403fa78750a6b4900223316fb146b4528b910e4b
6ef3575b52e1728c5ed32ff7f4c743b297e04bb7b1d4e8467f3983db0f3f39e4d23ccf592d707c
0e16e0d2b1cfe91b4dddbe01812244b821ff8ac80430693bb7ec3ffef677d9e58a91adafc2ad06
1c971fba9db07adcd6573c9c050000003e1f5fbaff97a071d2f1a768609aa066008fc4e1cd6d95
1a0e4c13d40c8fc6c1cd4687bb8099f8e597ee8febf1f3cfdd1f000000c063d0af7305002ce4ed
cd4dfaaebc7c1600000000633072056021fd42de437395e5b30000000048c1c815804a2ea7ab2c
9f0500000000000000000000000000000000000000000000000000000000000000000000000000
000000000000000000000000000000000000000000000000000000000000000000000000000000
000000000000000000000000000000000000000000000000000000000000000000000000000000
000000000000000000000000000000f7c6a1f9f3cfe6edd07dda80b73f5d8d3e6d59f56cd8381f
c7e1ef3fdff8efdb91586f2c8f9a6103ee40c8cdc31e0060e42e7ab93ba53d3a8ba1eb5bd90e38
a10c7cedfeef689b8f3f9b63ebfe3c7edc7143a51e2771ee132bb5435ce738b63302147c560e6f
182500301b349c3b02ceaa261cb93ed1d8b5b95cf8cfb6399ff9cbbbe3c0c3d64bf3fca5f9d2a7
6799d1dc197e84fde2253c3b695fd8f214dcb71abc923c9de99ec99019d40c1b7017420200f609
3a1000ee9660e47aa071d2a5f94e7fb534886dbebbbf0cf04cadbb8098481b0fbf5a9e5e3d9ff6
ded71c3fdcb0f572723d63728d707ee9fa4a1abcca14f843f2187794f6a04577052fe9c35d7fee
10a3a15cf0d358e1a5fbb831ee5e93b7e475dcba8780b98ba6f718fdc366141a0edcbd376edbcb
3d04c1c8b575c3551ef00593afe02a1c9a5732f1797a32f8d23c7358bfbef2470026784bba7bbe
92c4e97e01346c75ad32e0b12f1d0100e0eef1a74077f5b374e646a67fd21367b070d3adececd3
f8fc1afe3aef9c21cf364da4a1a8d10c71fad368e90989143e3e65d12299b91997291954058dd9
b29465900b5c9f26af74276c32a066c8115a2f4aa3a833c5438d90f25390ecd6d6b5b87ed877b3
ad81ddba6fbcb25e8640d3acbb0b3284d321538a14224a37d4284fd7e23c0b2c4916088ed2e1cc
49904423d78928a21a2369a723ca620721cc19fa428c4cdf48eb0e0d6254d32a43ac85d5860196
1e66aa8fd2851c7b96bf49c2e6babd9c311ea6e0c3a7729265e427b5e925b64a0ab4ba3bce9934
7f23be049221145b28f8c228a4d59b050a516dee61540a764834cd7b3f1692d2e08e51d84b81cb
fcf5084c86ce74d39aa234723da62e894273e4304a335cc2554ca5ae9c5c15a182e391a2445ea7
ce522d28258a38838ffa8e31e3f66f429321e90224e54d2d45cdedd33526e36d593c2c16325785
3de0752dae1ff62243122051188b0ce1728271159a0c5d1c8e14f1f59623cae2ee244fea858aa6
676d3e5c45d9fb4aff401423aa3eeca5ba0f3fe0fb688edeb36121d398646053a4694e1bd77b98
0967491e5d488987d0b323f7e932784498f91d881e0f459c9a7d9972def445d14ff2b71458687a
89ad920036b9bb18722626bce91d54f68545c819de9ca21cd51251e51e4645b343d9598e5c0943
b638ec25fc8cc1f6b0b8c81027b1edacddfd88c2c8d5a5200ec48b3ea7b861a8570e99d35d0a5d
53cfc99ffd49d6c50a92218c2727551cdc2e695aa4e17e88db9844a74535ae3113df45541948cd
d008e2b2bcc75551edba8c28788a98110f4b8554e3c142498b6b87fd44e648a45e061f45f26b78
942a43770825af08e7f1475086d002d9882a192a844b4e63bed742b564d2cb53d26bece9ce2b49
c309101526fb87091d93882adba1ec0b399612fd2e461669dd51d3628f29cb207618d494e63367
a040e587858fe341d44c658efbc992906c96e8a751d8a8320cd47520857828137a2db239572792
4a152e795bb1a6193d4616f0942ca9859c05b1ed50b594109469f14559484b096594a8ee650e63
32e96154543b0c4c382b6b84a103e1a3e457a9cbde241f1667080956b6ce9c90881083a6878b0b
e3c610999ec32871e4dcee582835803e920afe76c11af7114351362d7499b99c71d46698e8314b
18650828594c156081843d6abdd678582ca4211e54f4788beb5d33eca70229fc3e9727ea910d32
888e762f676d5232544856299b2513bb596bf448217dca18b6dc3f10226731a24a5269be088f15
f587bf8d31c39464c8995af2670d6221ad2ee7ac31aa90d14ffc4d41c25269224f21bca73328f1
50443ce8b273f9eec6885441e5c41e2fc9e699b680aa7b21e42c4446604a354efc5a3e24615666
071ba714d5b90c510f6360861da69c25624c55cabf526952ac5db047a47f42eb70682ebc99801b
e0cb0e036b53da668b9f096b5f3bb749724f4bf02e07ab71ee369c7aa596390a32c109d93607fe
41365b38c562ab5a5cdef929b75b6194a16f21943e76f810d86ee2a19edb877dd37c8fa321fa68
9641d926effa1175f5a6d76fa527f5884d92b38ed23f544694cd17e1ae2f8a539622e702cfe5ec
0ceb1ee1b5538887559c65619b982c9e2f0a88efe884dbd258442287b77474e5c8a3d23d57f2b2
a3be0b929cb1c019ea7d515d821ad5557636daa18ca5033938f54fcfcdf1eaed67cf7c1daefc24
7c5d4cc825e694e1ee9968378adc95b4c4ae3cd1ef46f3d7e85e39b84da701e9e2d7be8c701e7f
73a1ef4cf1a5793e75df7f42d478d83fe34092bb4bc968f5aa3c5844c9469ea205a9467da347ed
1f1e20a2ead9433c6c2343d5f9824f044f4f2eb94e5ece0b3490958f0f44bd2f1eac8729a07620
d41d51d0d1d0f6b3cfb992a55c1cc87c036f23dad9aeffb819b2b96992b867581bdef0bf2b5cde
5ce0393727d2f9d01c8feefbf759d54bd7f3cd0d374bc894368f4acb2c1982a8321cdc3412b978
ff576cbb8887ebb35ccd735ee0c337f76f613f66f74ab9f8be4a95a9f71051b9ab411a10d47039
76f31fd20c3b8cfd4345446d17f6d3249674938224987138a5c683b19fd408df8c18f988d82c26
6bce17dc06490b1af2ba032fcdfb8507b2eda6979dc47543aede172b79b32aaa3766ba03a18ba5
171e987deec12baf1670a73aee4d6438553567be0c3e07b7af2e40435aee0ed682aedb92f2b31d
c4f9ddfdeb2ea3cf339b0a773d64c18fd15cb5bb0114e0eaedef3115508720196c320c7fb7cdaf
3c61109e06b624b14cc79ee2c1425e0b956a35a5a9be05be26a5dccdbe3874e94bdfc71de51518
7e726825531b236aa1a1546420ce673861ec5c05be17199d09dae6954b4876b62ef40ff688ba61
d87b0a32507dc322bcdea1b38665a57830f793442160fc4084cc9ebd7d5c92613d969f2f383c68
044f7a488cd128eaf0ea3eceebf36d14dc5d1572e2cda0e9d1b16377187d5170779537578aea12
363b94b1762097e6b91fbc4e1bec13f0d62fe722c355ae1070254c3ca195b844720ea78a60154b
98e63a86c2858e4aea12a4c6348defe5c914fdb8108b16fdb149ca1695a93ac492274b5986895f
25a56693cc0519d40c0572920c02d8e361a990d6782853d0c21230763527708f058cd23c336a79
0a6dca91b3804fc34165777b5898f4d905832545c830c95e609362274c1821f31445afc8b86453
4495ed50f485e8282a4b5df2bdfb7b56bfbd40067bbbb0c4c3449ec8a40521473f1dd932e1b844
97c12399e777201d7d5dd6480be802a62fb98be1c0954ad30bc9361c21678da1c862c859509a9e
d11705218d2594294735ff9ad839e9615466744113ce523a9044c85e23ab051e8aaf4e7fd25c2e
f2dc0a9b0d16ce67e1e9f1e4fae7f49c7e53c3f9a5bbfde7717749644149885c3c51fe0575f3a2
8ba416d261fc8ddc63ca773404b5558ed7d382053d6519facb3541ee13a599b78124191bdfb39f
782853d642a55acd97c47decfde4f048d371864a198c115569288dcb315afd46f29f664d5c9111
468ba3a890cc5beea6fb07534495ed70fdb077a832c4a620bd66b40b4b3c509e421f2514848c7f
22fba4939d1619d6a2e27c21a75d7fc35a9e19eaee7fae48c1924475c8294dcfe88bb2bbebbd59
19d5066abb201629d12bd38178ce5d756f7386d7e091a150981c53ae879f2d4bae99fc8597e952
1b8002b9b9844fc2dc29133bdbf40fe05e403c00006eccf54e7863fce0b5ebf8faf97f4a18b682
15f83c23d7781ffbae29d5ad7dcab265ff00f60fe20100704bdc0ecc32709c5ad2740df8141b8d
5cb7ac1d3c369f69e4da35de20adabf86dfa07b057100f0080dbd3f5445798a701e0367c9e916b
3892e0b4fa3418fa07108278000000000000000000000000000000000000000000000000000000
000000000000000000000000000000000000000000000000000000000000000000000000000000
000000000000000000000000000000000000000000000000000000000000000000000000000000
0000000000000000000000000000000000000000000000000000000000000000000000009f96a6
f9ff01610dcd226db06ab30000000049454e44ae426082
}\kerning2\f1\fs21\lang1033\par
\f2\'c1\'bd\'d6\'d6\'b3\'d6\'be\'c3\'bb\'af\'b7\'bd\'b0\'b8\'cd\'ac\'ca\'b1\'bf\'aa\'c6\'f4\'ca\'b9\'d3\'c3\f1 aof\f2\'ce\'c4\'bc\'fe\'c0\'b4\'bb\'d6\'b8\'b4\'ca\'fd\'be\'dd\'bf\'e2\'a1\'a3\f1\par
\par

\pard\keep\keepn\nowidctlpar\s1\fi-425\li425\sb340\sa330\sl576\slmult1\qj\tx425\kerning44\b\f0\fs44 3.\tab Redis\f2\'bc\'af\'c8\'ba\'b5\'c4\'b4\'ee\'bd\'a8\f0\par

\pard\nowidctlpar\s2\fi-567\li567\qj\tx567\kerning2\b0\f1\fs36 3.1.\tab redis-cluster\f2\'bc\'dc\'b9\'b9\'cd\'bc\f1\par

\pard\nowidctlpar\qj\kerning0\f3\fs22\lang0{\pict{\*\picprop{\sp{\sn wzDescription}{\sv Image}}{\sp{\sn posv}{\sv 1}}
}\jpegblip\picw13099\pich15083\picwgoal7426\pichgoal8551 
ffd8ffe000104a46494600010101006000600000ffdb0043000302020302020303030304030304
050805050404050a070706080c0a0c0c0b0a0b0b0d0e12100d0e110e0b0b101610111314151515
0c0f171816141812141514ffdb00430103040405040509050509140d0b0d141414141414141414
141414141414141414141414141414141414141414141414141414141414141414141414141414
1414ffc0001108023a01ef03012200021101031101ffc4001f0000010501010101010100000000
000000000102030405060708090a0bffc400b5100002010303020403050504040000017d010203
00041105122131410613516107227114328191a1082342b1c11552d1f02433627282090a161718
191a25262728292a3435363738393a434445464748494a535455565758595a636465666768696a
737475767778797a838485868788898a92939495969798999aa2a3a4a5a6a7a8a9aab2b3b4b5b6
b7b8b9bac2c3c4c5c6c7c8c9cad2d3d4d5d6d7d8d9dae1e2e3e4e5e6e7e8e9eaf1f2f3f4f5f6f7
f8f9faffc4001f0100030101010101010101010000000000000102030405060708090a0bffc400
b51100020102040403040705040400010277000102031104052131061241510761711322328108
144291a1b1c109233352f0156272d10a162434e125f11718191a262728292a35363738393a4344
45464748494a535455565758595a636465666768696a737475767778797a82838485868788898a
92939495969798999aa2a3a4a5a6a7a8a9aab2b3b4b5b6b7b8b9bac2c3c4c5c6c7c8c9cad2d3d4
d5d6d7d8d9dae2e3e4e5e6e7e8e9eaf2f3f4f5f6f7f8f9faffda000c03010002110311003f00fd
53a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a
2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a2a39e78ad61796691
62890659dce001ea4d7857c44fdb6be147c3c965b693c429ad5fc79ff46d254dc73dc175ca83ec
48a3703de68af807c5ff00f053b9ccadff0008af872358fb1d5e02c7ff0021ce2b91b6ff00829c
fc43f3dbed1e1ff0c987231e55a5c6ec77eb715d91c1e264af1a72fb99c8f17878bb3a8bef47e9
6515f13f827fe0a67e1abb68e1f1468b7b64edf7ae2ce00625fc3cc663f957d29f0d7f682f007c
5b545f0cf896cef6e986efb13bf9770077cc6d86c7be2b9a709d3769ab3f33a2138cd5e0ee8f44
a28a2a0b0a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2
800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28
a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800af1cfda07f69ff0a7
c01d218ea130d435e95736ba4c0dfbc73eac7f857dea8fed57fb4858fc00f05ef88adcf8935056
4b0b4cf20f791bd1457e4b78afc57ab78df5fbbd6b5bbd96ff0051ba72f24d29c9fa0f403d2bd8
cbb2dab9854b4748addff5d4f2730cc69e021796b27b2feba1e91f1abf6a4f1dfc6fbc99755d52
4b2d1d89d9a459318edd47fb433f39f76cd79062968afd37099761b04ad4a3af77b9f9c62b1f88
c63fdecb4edd028a28af4cf3c2a4b6b99acae63b8b795e09e360c9246c55948e8411d0d4745635
68d3af1e4ab14d799ad2ad528cb9a9c9a7e47d6ffb3ffedffe28f024f6ba4f8da497c4da16427d
aa539bb807aef3cb8f66c9f7afd1af0478eb43f88de1db5d73c3f7f16a3a75c2e5648cf2a7bab0
ec47a57e1757b17ecdbfb48eb7fb3ff8b62b986492f3c3b72e16ff004d2dc32ff7d07671d7dfa7
b8f81cd722f61175f0bac56ebb7a791f7396675eda4a8e2777b3efea7ec75158be0df18697e3df
0ce9faf68d74977a75f44258a543d88e87d08f4adaaf8b3ebc28a28a0028a28a0028a28a0028a2
8a0028a28a0028a28a0028a28a0028a28a0028a28a0028a28a0028a28a0028a28a0028a28a0028
a28a0028a28a0028a28a0028a28a0028a28a0028a28a0028a28a0028a28a0028a28a0028a28a00
28a28a002b37c49afd97853c3fa8eb3a8ca21b1b0b77b999cf655049fc78ad2af917fe0a41f139
fc29f09f4ef0bdaca63bbf115c9126d38cdbc58671ff007db45f866ae1173928c7764ca4a11729
6c8f823e39fc5ad47e34fc47d53c497eec23964296b0672b0c238551f862b80a28afd9f05858e0
e8468c7a6fe6fa9f90633132c5d7955975dbc90514515dc718514514005145140051451401f66f
fc13c3e3dcbe18f14b7c3ed56e09d2b5462f63bdb8867eea33d037a7ae4d7e91d7e0ee83acdc78
775bb1d52d2468ae6ce6599190e0820e7ad7edd7c30f1945f107e1ef87fc450b061a8d9c7336de
81f1871f83061f857e499ce0d60f14d417bb2d57f91fa96518b78bc3272f8a3a33a8a28a2bc23d
b0a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a
2800a28a2800a28a2800a28af17fda47f69df0f7ecf7a0a9b964d47c457484d9e931b8dec3a6f7
feea67b9ebce33834d26dd909b495d9ea7e25f15691e0fd2e5d475bd46df4cb28c12d35c3851f8
7a9f615f27fc50ff008291f847c3734d67e11d2e7f125ca12bf6a95bcab707d47761f957c29f17
3e39f8bbe356b72dff0088b5292484b13158c6c44108ec02ff00535e7f5f6182e1dab5929e25f2
aedd7fe01f278ccfe9d26e1875ccfbf4ff00827d41e28ff828a7c59d6e573a75c69ba0467a25a5
9a4981f59431fd6b8d93f6d3f8cb2c9bcf8d6e81f458a303f20b5e23457d2c320c04559c5bf56f
f43e7a79ee3a4eea497c97ea7d15a17edf9f19346954cfaf5bea90839315dd94383ff020a1bf5a
f73f877ff053a8e696383c6be185814901af34973851ea636249fcc57c054573d6e1cc24d7eedb
8bfbff00337a3c418a83fde5a4beefc8fdbaf86df19bc1ff0016b4f5bbf0ceb56f7f91968376d9
53d8a9e7f2e2bb6afc25f0bf8b359f056ad16a7a1ea371a65f444159addca9fc7d47b1afd17fd9
4bf6e6b3f88f3da7853c6ef169be236023b6bf276c3787b29cfdd73e9dfb73c57c563f2aaf8077
9abc7bafd7b1f6181cce86395a3a4bb3feb53ec3a2901c8a5af18f5c28a28a0028ac4b5f1b6837
de27b8f0edbeaf673eb96d109e6b08e656962427019941c8e7d6b6e9b4d6e24d3d828a4240ea40
fad67eabe22d2b4287cdd4751b5b08baefb899507e64d095f606ec68d15e5baefed47f093c39b8
5f7c44f0eac8bd628f518a4907fc054935e7bac7fc1433e09e98e62b7f11dc6a9719c2c565a7cf
26efa36cc7eb5bc70f5a7f0c1fdccc655e947e29afbcfa528af95ffe1bb175af97c2df097c7de2
32df765b6d24f967ea739fd28ff8681f8ffe2225740f80d2daa37dd935ad492d197eaadfe357f5
5aabe2497ab4bf523eb54ba36fd137fa1f5457e607fc1497c4afab7c72d3f4b1216b7d374b4c27
f7647772df9854fcabf463e1bdef8a350f07584fe32d3adf49f10baffa4da5accb2c687d98706b
f2ebf6f3676fda57c41bfa08600bcf6d9ffebaedcaa09e3e945f47f91c799cdc703524bb7e67cf
7451457ec07e501451450014514500145145001451450021afd56ff8279789a4d7ff00677b6b59
5cb1d2b509ecd01ec985907eaed5f9555fa55ff04c82ff00f0a8fc440e7cb1ab7cbe99f2d73fd2
be1b8a22b9694faebfa1f67c3727cd563e87d8d451457c01f74145145001451450014514500145
145001451450014514500145145001451450014514500145145001451450014514848504938039
24d00796fed17f1d34df80df0faeb5ab92936a52831585a13ccb2e38fc07535f8ffe39f1b6b1f1
1bc55a878875ebb7bdd4ef64df248e781e8aa3b2818007b57adfed93f1b25f8c3f16ef96dae0c9
a0e92ed69648a7e56c1c33fe26bc1ebf40e1fcb62a3f5caab57f0ff99f0b9ee60dcbea94de8b7f
f20a28a2bee0f8c0a28a2800a28a2800a58dda27574628ea772b29c107d6928acea538d58b84d5
d32e13953929c1d9a3f4d3f61afda9a4f89ba40f06f89eec3f892c63ff0045b894fcd77101dcf7
615f5e57e16781bc65a8fc3ff16e97e20d2a6682fac27599197be0f20fb1afdabf863e3bb2f89b
e01d0fc4f60c0dbea56cb36d073b1fa3affc05830fc2bf22cd302f018874d7c2f55e9ff00fd572
dc6ac750537f12d1faff00c13675dd4e5d1f48babc86c6e35296142cb696a019253fdd5c9c57e6
c7ed4ffb55fc7fd4a5b9d22c7c23abfc3dd10e559ed6267ba917fda9973b7fe03b7af39afd36a8
ae2da1bb85a29e249a26e192450ca7ea0d71e1abc684b9a5052f53af114655a3cb19b8fa1f8c3f
b17eb1f1164f8d73e9fe07d52d2c3c4baa5aca25b9d5e3f346d5f99890dd5beb5f7dff00c28bfd
a27c4633ae7c734b046eb0e91a4c76eca3d9d71fcabdfadbe15f842cbc456faf5af8734eb4d5ed
c111dddbc02275c8c1fbb8ce7debaaaeac4e3bdb4f9e114b4ea93fd0e5c3e0bd94392726fd1b47
cb1ff0c3d7bae0dde29f8cbe3fd733f7a16d50ac47db18c8fceaf695ff0004eef831692f9f7fa2
df6b375d4cd7da94ec5bea03e0fe55f4cd15cbf5bafb29b5e9a7e4757d568f58a7ebafe6792e85
fb277c1ff0eed369f0efc3ecebd24b9b08e671ff0002704d7a268de12d13c391f97a569165a726
31b6d6dd631fa0ad6a2b09549cfe26d9b469c21f0a4840a074007d296bc37c65fb68fc27f87be3
3bff000b788fc432e95acd93ec9629ac67d9ec4384da41fad69e8dfb5d7c1bd702f91f11bc3f11
6e8b757d1c04fe0e455fb0ab6e6e476f4647b7a57b732bfa9ebf5f973ff051ff000ebe93f1eada
fc21106a3a5c4e1cf42eaee187e00a7e75fa79a66a967ade9f05f69f750ded94ea1e2b8b770f1c
8a7a1561c115f207fc14b3e1abebff000db45f17db465e6d0ae8c371b474826c02c7e8eb18ff00
8156f82adf57c4d3aafa357fd4c7194beb1869d35d57fc31f9b1451457ed29dd5d1f8fb56d028a
28a6014514500145145001451450015fa9dff04e8f0ebe8bfb3daddc8855b52d4a6b9563fc4815
107eaad5f975a669f36afa95ad8dba979ee65589140cf24e2bf6dbe0f78217e1c7c30f0d786d54
23d859a24a074f30fccfff008f3357e79c4d5d4aad3a2ba2bbf99f79c3945c69ceb3eaedf71d8d
14515f147d88514514005145140051451400514514005145140051451400514514005145140051
451400514514005145140057967ed41e3c6f871f02bc5bac44e12ebec86da0e7077ca4271ee031
6fc2bd4ebe42ff0082986b4d65f05b45d3918a9bdd6119b07aaa452647e6e3f2ab8479e4a2ba93
297245c9f43f336491a591a47259dc96627b93494515fb852a6a9538d38ec958fc62a54756729c
b76ee1451456a6614514500145145001451450015fa37ff04caf882fab7817c4be11b897736937
49776e18f3e5cc08651ec1a3cffc0ebf392beadff826deb6fa77c7bbcb2c9f26fb47990a8e9b96
48d81fcb77e75f23c4b454f0d1abd62ff07fd23eab87aab8e2654fa497e5fd33f50e8a4e95cbf8
cbe28f843e1e5bf9de26f12e97a1478c8fb7dda445be8188cfe15f9b24e4ec91fa136a2aecea68
af9975bff82807c3917cda7f84ad75bf1f6a83816ba0e9f24849f6620023e86b38fc5bfda43e23
f1e15f85b69e0bb263f2dff89ee9564507fbd070df966babeab556b25cbeba7e7a9cdf59a7b45f
37a6a7d544e2b93f167c5af06781a0925d7bc4fa669ab1fde596e5778ff80825bf4af003fb2f7c
5bf88396f883f192e61b77e5f4df0dc06387dc076c30fd6bacf0a7ec33f09bc393a5d5ee8d71e2
7bf5e45debb74f70e0fa8e9fae68f67461f14efe8bf5760f695a5f0c2deaff004573275dfdbdfe
1fc7335af856c75bf1c5e6708347b266858fbc87a7e22b247c62fda33e241dbe13f861a6f836ca
41f2de7896e4c9201fde50bf2e7d88afa5742f09689e188562d2348b2d3100da05adbac7c7d40e
6b5e8f6b4a3f043ef77fcac85ecaacbe39fdcadfe67e44fed6bfb397c5bd43e2de8936b93c7e34
f14788edc65f4ab1582388a1d810ede3803ef1c57d27fb2f7fc137f44f03fd8fc47f11d61d7f5d
5c4b169446eb4b66edb87fcb461efc7b6466bedf6b689e7599a24332021642a37007a806a4aea9
e655a549528e8bcbfad0e7865f46355d57abf319142904691c48b1c6802aa28c003d00ac8f1a78
52c7c73e13d5bc3fa94624b1d4ad9eda5040380c3008f707047b815b5457947a67e1f7c5af86ba
97c24f1f6ade19d510acd692911c98f9658ff8587b115c857eb2fed85fb30c3f1d7c29fda3a4c6
9178b34e42d6ef8c7da17af96c7f957e52eafa45ee81aa5d69ba95acb657f6d218a6b7994aba30
ea0835fa56459a46bd3586aafdf5b79aff00347e799d65b2a351e2292f75efe4ff00c99528a28a
fae3e5428a28a0028a28a0028a2bd2be027c09d7fe3df8d60d174985a3b18c87bfd4597f776d16
7924f763d00ee7db38e0c6e32960693ab51fa2eecedc2612a632aaa74d7abec8f6bff827e7c099
7c75f1017c67a8db9fec4d0df7425c7135c76c7b0ff1afd3bae63e1c7c3dd23e17783f4ef0e689
6eb05959c610103e691bbb31ee4f5ae9ebf1fc4579e2aacab54dd9fac61e8430d4a34a1b20a28a
2b98e80a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28aaf7d7f6fa65
abdcddcc96f6e98dd248d855c9c0c9fa91401628a28a0028a28a0028a28a002be2cff829fc0edf
0e7c213027626a5229f4c98c63f91afb4ebe67ff008285f8524f11feced777712ee6d22fe0be62
3aecf9a23facabf956b4a5c952327d1a32ab1e7a728aea99f94f451457ee49a6ae8fc61ab3b30a
28a298828a28a0028a28a0028a28a002be96ff00827ac0d37ed1f6457a47a7dc3b7d3e41fd6be6
9afb47fe0989e1292fbe2278afc465330e9fa7a59063fde99f771f8427f3af97e239a8e0b95f56
bfccfa4e1f8396339bb27fe47de7f147e1fafc4ef075e787df59d53414b92bbaf748b830cea076
0de87b8af25f077ec1df07bc2b702f2ebc39ff000926a24ee92eb5d99eefcc3ea51c94fd2be86a
2bf35856a908f2c24d23f43951a739734a37666685e1ad23c2f62967a3e9969a5da27dd82ce158
907d02802b4e8a2b26efab354ada20a28a290c28a28a0028a28a0028af36f8bbfb447807e07d89
9fc59e21b6b1b82bba3b146f32e65ff7635cb1fae31567e087c553f1a3c0b178b21d26e348d2ef
667160976479b342a76f9840ce32c18019e82b5f65350f68d69dccfda41cb913d4f40af9fbf698
fd90bc39f1eed1f52802e8fe2d89310ea312f1301d1251fc43d0f51ebd73f40d159a6e2ee9ea5b
4a4acf63f137e2afc0cf18fc1bd5a5b2f11e932c31a93b2f2252f0483d4363f9d7019cd7eb1fed
0bf1eac53c4b65f0c3c2fe1cb6f1ff008cefdd7cfd36450f05945fc4f3360ece3fc8ac7f1cff00
c13dfe1d78d22175651dc7853529101912c1fcdb747239c2b609e7be6becb0d9fe270d08ac4c79
93d9eccf91c4e4787c44a4f0f2e56b7ea8fcb5a2bedfd7bfe097be208e43fd8be31d36e13b7dbe
29223ff8eab56227fc1317e2134987f12f86d50756f327e7e9fbafe78af663c49836b58c97c97f
99e43e1ec5a7a35f7bff0023e3ba555691d5554b3b1c0551924fa57df3e16ff825ea8911fc43e3
30547de874fb62c1bdb7315c7e55f46fc31fd907e197c2c68e7b0d09351d4139179a991338fa0c
63f4ae1c471346d6c3d3d7bbff0025fe676d0e1c95ef5e7a765fe6cf817e00fec4de31f8bf7105
fea90c9e1cf0e6e05ee6e5089655ee114ff33f957e9a7c2ef857e1df83fe14b7d03c3562967671
fcd23e3324cfddddbab13ffd6a97e26f88355f06fc3ed6f58d034a4d5f52b0b569a0d3cbec12ed
19da08071c7b567fc11f8a763f19fe18e87e2cb1da82f61fdfc20e4c332f1221fa107af623d6be
3f135f118c7edeb3bf4f4f9743eb30f4286117b1a4add7d4eeabe77d6ff6b5d2fe1f7ed1d75f0d
3c63e5e9d677b6f05ce95aa1e103396531cbe8095386f5e0fb7d115f961ff055ad10d9fc65f0c6
ac015379a4f92187731484ff00ed4abc0d18622afb29f54c9c6d59d0a5ed21d1a3f53639165457
460e8c32194e4114eaf867fe09c3f187e25f8bfc3ffd87e20d0efb53f0a5aa15b2f124df2aa6de
3ca2cc47998e995c91debee6ae6c451787a8e9b77b1d142b2af4d544ad70a28a2b9cdc28a28a00
28a28a0028a28a0028a28a0028a28a0028a28a002b3f5fd0ad3c4ba4cfa6dfa3496936ddeaac54
9c3061c8f702b428a0028a28a0028a28a0028a28a002b03c7de12b7f1e782b5bf0f5d0060d4ad2
4b72586769653b5bf0383f856fd1401f84fe30f0c5e7833c53aa6877f1343776170f03a375041c
563d7de9ff000511fd9e24132fc4ad0ed4ba1023d5a388676fa4b8f4f5fcebe0bafd5723c72c56
195393f7a1a3f4e8cfcc739c13c3621cd2f765aaf5ea828a28afa33c00a28a2800a28a2800a28a
2800009e00c9afd18f809ad3fec91fb3cf8735ad4bc23ab6b87c4d76f7ba8cda6461dec61da044
597ab02a3701c7de6e6be5bfd913e015cfc70f8976c2e2171e1cd31d67bf9f18040391183ea6bf
5da2b3821b44b548516d91044b16df9420180b8f4c715f99e7b8f862312a9c758c3f17d7ee3f45
c97033a187751e929fe0ba1e7ff0c3f684f00fc5fb657f0df886dae2e4f0d65337957087fba50f
39fa66bd1abc3be277ec77f0efe245cb6a315849e17d7c731eada1bfd9e556ec485e08f6e2bce8
695fb467ecf833613db7c64f0a43ff002eee7c8d4e341e83f8bd95724d7cff00b2a753f872b3ec
ff00cf6fc8f77da54a7fc48dd775fe5bfe67d6d457cfff000d3f6d6f87be39d4868babdccfe08f
13ab049348f1127d9640ff00dd0cdf293ec0e6bdfa39165457460e8c32194e4115cf529ce93b4d
58de1521515e0ee3a8a28accd028a28a002bc3ff006c8d43c41a2fc08d7754f0df8cd7c157d66b
e69ba6daa6e170730abe372bb1c60ae0e47a66bd3fc7be3cd13e1a7856ff00c45e21be8b4fd2ec
d0bc92c8719f4503b93d80af96bc15e09f10fed99e30b4f1ef8eada7d23e1869f2f99e1ff0d4b9
56bf20f17130feefa0fcbb9aecc3c2cfdb4f48afc7c8e4af3baf651f89fe1e67e70fc2ff00879e
20f8ddf19748f0eddbdddcea5a9dd2b5d4f7859a4d99cbbb16e7a77f7afdd1f0cf876cbc23e1dd
3344d3a210d869f6f1db4083b222851f8f15cfd87c1df08697e3d1e32b3d12dad75f16bf631730
a05fddfd077c719f4aec89c56f8dc6fd6dc6cac97430c1e0feaaa57776c3a57ccdf1d3f68ad6f5
8f147fc2acf8411aeabe37b91b6fb565f9adf4788f5763d37e3a0edf5e99df187e3b7887e2b78c
6e3e147c1b7171aa0fddeb5e254e6db4c8cf0c03f42fd463d6bd87e067c07f0f7c08f0bff66e92
86eb51b83e6ea1aadc733de4a7ab3375c67a0ac6308d05cf555df45fabff002ea6d29cab3e4a6e
cbabfd17f9f433bf67cfd9df45f815a0cbe5bb6ade27d44f9daaeb972774f7529e4fcc790b9e82
bd6ea2b9b98ace079a79121850659dc80aa3dcd3e391658d5d1832300411d08ae59ce5524e5277
674c211a69462ac875709f0efe31e85f133c45e2ed1b484bafb4f866ea3b3bd79a30b1b3ba9236
1cf38da73d3b576b7770b696934edf7624673f40335f317ec136e6fbc31f123c46f92fabf8c2f8
a31fe28936ecff00d0c8fc2b58413a739be96fc4ce736aa460badff03ea3a28a2b9cdc6491acd1
b23a87460559586411e95f26fc2598fece3fb4ff00887e1bdd3187c25e36dfade80cdc245763fd
7c23b723e6fc1057d6b5e07fb647c2bbcf1e7c305f10787c18fc63e109d75bd26541f33345f349
1fa90c80f1dcaa8aebc3c9733a72da5a7f93fbce5c445d9548ef1d7fcd7dc7be5705e3ef81be09
f8a3e23d0f5bf156836daddde8ab2ad9a5d8df12f9850b168cfcac7e45c641c76a3e06fc51b2f8
c9f0bf42f14d91c7db200278b39314cbc4887dc3022bbdac3dfa526b668dbddab14f74cf90fe00
48dfb3a7ed05e26f84174c62f0d6b4edabf86cb9f95031cbc2bf4391ee735f5e57ce7fb69fc36b
fd7bc11a7f8e3c388c3c59e0db81a8dab443e7922073227bf1d07b9af5af841f122c3e2e7c36d0
7c59a73ab43a8db2c8eaa7fd5c83874fc18115d15bf79155975d1faffc15fa9851fddc9d1edaaf
4ff80ff43b2a28a2b8ceb0a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800
a28a2800a28a2800a28a2800a28a2802a6ada55a6b9a6dce9f7f6f1dd59dcc66296195432ba9ea
0835f961fb5a7ec87a9fc15d6ae35dd06de4bef05dd4859190167b263cf96ffecfa37e07a64fea
d555d4f4bb4d66c27b1bfb68aeece75292c132865707b106bab0d89ab84aaaad27668e6c461e9e
2a9ba5555d33f06339a5afd05fda03fe09d51ea73dc6b3f0da68ede6725df45ba7da84f5fddb9e
07d0e3eb5f0ef8dfe1c789fe1c6a6d61e26d0ef746b904802ea16557c7756e8c3dc6457e9382cf
70d894a355f24bcf6fbffccfcf719926230edba6b9a3e5bfdc739452020d2d7d1c6519abc5dd1f
3f28b8bb49598514956f4bd26fb5cbe8acb4eb39efef253b63b7b68cc8ee7d028e4d615b13470e
af56697ab36a587ad5dda945bf42ad7a0fc15f821e24f8e7e2b8746d06d5bc90435d5f3a9f2ada
3cf2cc7d7d077af79f81dff04f4f16f8d27b7d47c6dbbc2fa370c6d5f9bb947a6dfe0ff8160fb5
7e867c39f863e1cf853e1d8745f0d69b169f67181b8a8cc929fef3b7527fc6be1f33e20f691747
09a27bbff23ecf2ec8bd9c955c56afb7f999df067e0fe87f04fc1369e1ed1210aa8035c5c30fde
5c49ddd8ff009c576b2ddc104b14524d1c72cc488d1d80672064803bf1e95357cf1fb627c3ed7b
51f0d691f10bc1f3cebe2bf044e7518ad5246d9776f8fdfc457a13b4673e81877af8da705526a2
ddae7d75493a70724af63e87a2b89f837f1474cf8c7f0ef48f14e94e0c37910f3633f7a19470e8
c3b1073c576d5128b8b7196e8a8c949292d99c37c4df825e08f8c5a71b3f16f876cb57014aa4f2
4604d17fb920f997f035e0727eccdf143e0731b9f833e3fb8bad2233b8784fc4adf68b6c75db1b
9e631f4e4fad7d6b456d0af529ae54eebb3d5194e8426f99ab3eeb467cb5a07edad2784afe3d1b
e30f83750f01ea39087518e33358487fbdbbaa8fa926be8cf0bf8c743f1ae991ea1a0eab69ab59
c803096d650e307a64751f8d4faff86b4af1569f258eb1a75b6a766e30d0dd441d7f5e95f3978a
7f620d3b49d49f5cf853e27d47e1c6b792e20b690c96521f43193c67b9e4d69fb8abfdc7f7aff3
5f899fefa9ff00797dcffc9fe07d3f5cff008f3c79a1fc34f0adff0088bc457d1e9fa5d9a17925
90f24f6551dd8f402be5fd47f68ff8b7fb385b8ff85c1e0d5d7bc3b1b08c78a3c38c197d019232
72b9f7c67d2b93f85fac5afede1f13e4f10789f59b3b5f04f87e7ce95e0a5ba437372e3a5c5cc6
0e42fa67e83a135a4708d27526fdc5d56b7f25ff0007633962936a105efbe8f4fbce97c1be0cf1
07ed99e32b5f1c78ead66d2be1969d2f99a1f86a4c8fb610789a61df3d79afb0e0823b58238618
d6286350891a0c2aa8e0003b0a4b5b586cada282de24860894224718c2a81d00028b8b88ad2de5
9e7912182252ef23b615540c924f60057355aaeab4ad64b65d8e9a549534deedeec74b2a411b49
232a46a373331c003d4d7c93f13be31f8a3f68df165dfc30f83f72f67a442de57887c671e42409
fc50c0ddd8f2091fcbad2f18fc45f137ed85e2abcf037c36ba974af87b672795ae78b1015171eb
0c07be7d47f2afa6be197c31f0f7c23f095a7877c3762965616ebc903e795bbbbb7f131f5ae851
5865cd3579f45dbcdf9f65f798393c43e583b47abefe4bfcfee287c1bf833e1bf81fe0eb7f0ff8
72d1618d7e7b8ba6199aea5ef248dd4935ddd1487a7ad714a4e6dca4eed9d718a82518ab23e2af
f82947ed0aff000ffc0f6be06d1aebcbd675ac497451be68ad81e87fde2315f4b7ecff00e2c4f1
bfc13f056b48fe61b9d2e00ef9ce5d17639ffbe95abf30bf6c1f81df16b5bf8e30ea3e20b082ea
ff00c557ad6da3dad9dda484a8fb91819c8c0c0c902bef6fd84bc3fe2bf077c01b2f0e78bf46bb
d1352d26f6782282ed0a968490e197d46e77191e95ece268d2a783a7c8d377bbf9ff0095ac7918
7ad5278b9f32695b4f97fc39ec1f13f584d03e1d78935090ed4834f9989f4f908feb5e47fb05e8
eda5fecbde129a518b8d40dc5ecb91c96699c67f2515affb66eb8742fd9abc712236d9ae2c8db4
441fe363815d77c02d117c39f04bc0da7aaecf2f47b6665f4668c3b0fcd8d79fb61df9bfc97fc1
3bf7c42f25f9bff8077d45145721d414846460f20d2d1401f247c2727f66ff00da6f5ff87537ee
3c23e3066d5b42cf090ce7fd642bf8e401f8d7d6f5e09fb62fc2dbdf1d7c368f5ed01597c5be16
986a9a6c91fdf629cba0fa81fcebbcf811f152cfe337c2ad03c5768cbbeee00b7318eb14ebc48a
476e4647b115d95bf7b055baecfd7bfcd7ea71d1fddcdd1e9baf4ff80ceeae6de3bcb796099049
0ca851d1ba3291820fe15f25fecff7327ecf7fb43f8abe0fdfb98fc3daf97d77c34efc2863feba
15fc0671d820f5afae6be72fdb5fe1a6a1af780ec7c7be1952be30f02dc8d62cd93ef4b0a733c4
71d8a0dc477db8ef4b0ed36e94b6969f3e8ffae85621349548ef1fcbaafeba9f46d15c6fc21f89
1a7fc5bf873a1f8ab4d70d06a16eb232e798df1f321f420e4115d95734a2e2dc5ee8e98b5249ad
98514515230a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28
a2800a28a2800a28a28039df881e3bd27e1af83f53f126b772b6ba75842d2c8ec7ae07007a935e
53fb337c4cb7fda8fe0f5e6bbe22d32d2f2de7d56e6dfec3710ac91ac4a418d4823048465c9f5c
d7c5dff052bfda1eff00c53e2f1f0f34e5b8b4d0f4b7dd75232b20bb9bdb3d557f226bdaff00e0
943ad7da7e0af89f4b272d6bae34e3d8490443ff00699af62582f6783f6d2ddb5f71e4c719ed31
9ec63b24fef3d97c53fb0ffc1df14caf33f8522d3a66e874e99edd57e88842fe95c54bff0004dd
f85cf28659b568d47f00b9c8fd6beaea2bc9526b667a8e29ee8fcf0f8f7fb29780be1ef8c3e19f
853c31693c9ad788b5848a79aea779765b0fbc7613b719e338afba7c1bf0cfc29f0f6dcc3e1bf0
f69da2a3001bec56c9197ff788193f8d7cf3167e25fedf123644d61e07d1303fba269b83f8ab1a
fab2ba6ba518c23d6d77f3ff0081639e8b7294e5d2f65f2ff8370a28a2b90ea0a4650ea55802a4
6083debc4fe317ed3da2fc09f889e1ed17c596ed69a0eb709316b2bca41286c6c907618e722bd8
f4cd4ed35ad3edefec2e62bcb2b84124371038749148c86523820d692a728c549ad1ec6719c652
714f547c8da0b9fd917f68e9b44949b7f869e3c9ccb64c7fd5d85e9ea9ec0935f60c88258d9724
0604654e0fe06bce7f680f83d63f1bbe1aea5e1eb9c457857ceb1ba1f7a0b85e5181fae2b8bfd9
0fe315f7c40f06df785fc4f9b7f1df8426feccd5ade4fbd205c88e71ea1c03cf7209ee2ba6a7ef
a9fb55bad1fe8ff4673d3fdccfd93d9eabf55faa3e71fdad3c57fb45fece5ac4dabe85e34bbd5b
c1370e4c3712d9c333dae4fdc93287a7ad7937c1cfdbe3e32f8b7e24f87344d6fc69a7db6977b7
891dd5d5d69b6b1aa459cb7ccb18c120100fa915faa9aee83a7f89f48bad2f54b48afac2e50c73
4132ee5753ed5f317c3bff008279fc3df05f8d7c617f7d6916bba0eaf0a4563a6dda9cd902c5a5
01875e447b4f50011f5efa38bc3ba4e35a9ae65b3496bff04e1ad85c42aaa5466f95ee9b7a1f51
69ba85aea96515cd9ddc57d6eea0acf038747f70471593e3cf1e687f0d7c2b7fe22f10df47a7e9
76685e495cf24f6551dd8f402be52f895fb3e6a3fb34685a8f8cfe1cfc509bc25a4d929965d1fc
40ed3d93fa2291c8cf40a07e35e1537c68d73e29f8bbc25e2dfda0340d734bf86504625b01a7e9
d2ff0066dcdc6702698e3241ec003fd4f352c1aabefc6578fe3e96ee7454c5ba7ee4a3697e1eb7
ec7bdf83bc17e20fdb37c636be37f1dda4da5fc32d3a5f3343f0d4b91f6c20f134c3be7debd4be
27fec65f0d3e24dc2ea31691ff0008bf8822c18358f0f9fb24f1b0e8c76e0311eac0d7a47c38f8
8de0ff00887a0c375e0ed6b4fd574e8d02aad84aade50c70a5472a47a1c56df88fc47a6784742b
dd6759bd874ed32ca332cf733b054451dc9358cebd553b42f1b6891b468d270bcad2bead9f29ea
52fed01fb33594d7b26ab67f163c1566bbe43a93083508631d7f784fcc71dd89fa5794ebbfb4fa
7ed97e30d2bc06dacafc32f014f1acda97dae6db73aa10798124c050991cf4cfbf18f4546f13fe
dd9e22dc9f6bf0dfc12b29b1bc831cfadb29edff004cff00cfb57d07e24fd9b3e1af8b3c296de1
ed43c23a73e9d6b188adfcb882491003821c739efce6bb7dad3a2d3ab1f7fbae9f2daff97a9c9e
cea554fd94bdcf3ebf3dec755f0ffc1fa0780fc23a6e89e18b5b7b4d16d620b025b60a91fdec8e
a4f527bd7455f26cff00b337c4ff0082f70f7bf07bc7925f69ca777fc233e26632c447f7525f5f
4ce00ab7a2fedb2de0ad4e1d0fe34783b53f875a9bb7969a8bc4d3e9d39f549547e39e83d6b89e
1e553dea52e6fcfeeff2b9d6abc69a51a8b97f2fbffe18fa9e8ac8f0c78b745f1ae930ea7a0eab
69ac69f28ca5cd94cb2c6df8a922b5eb8da69d99d69a7aa3e54f8b4078abf6e4f855a303be2d2b
4c9f5371fdd915891fa57d575f2af8171e2bfdbebc7d7d9df0e83a25b5b4448e8cca15c7e75f55
5756234e48f64bf1d7f539a86bcf2eedfe1a7e87cc1ff0506bf6ff008539a4e8f167cfd575db38
428eaca241b87e46be94d274f4d274bb3b18ff00d5db4290afd15401fcabe60fdaf71e21f8c3f0
2bc3001659f5e3733a8ff9e600193f422beaaa2a69469af57fa7e814f5ab37e8bf5fd428a28ae4
3a828a28a006491acd1b23a87460559586411e95f247c2698fecddfb51f883e1bdd3187c23e37d
face82cc70915d8e668476048c9fc1057d755e03fb667c29bcf1f7c2f1aff87c18fc63e109d75b
d26641f3968be6923f70ca09c772aa2baf0f25cce9cb6969f3e8fef397111765523bc75ff35f71
efd4c96249a378e45578dc1565619041ea0d707f027e29d97c66f85ba178aacc856bb800b88b39
314cbc4887dc3022bbfae6945c24e32dd1d11929a525b33e46f808effb3afed05e25f84578ec9e
1ad6d9b58f0db39f95431cbc23e873f539afae6be77fdb3be1b5ff00883c0d63e35f0e230f1678
3ae06a568d10f9e48d4e648fdf23fad7abfc20f89161f16fe1b683e2bd3dd5a1d46d9647553fea
e41c3afe0c08aeaadfbc8aaddf47ebff00057ea7351fddc9d1f9af4ff81fe476345145719d6145
145001451450014514500145145001451450014514500145145001451450014514500145145001
45145007c99fb6059dbfc48f8bdf07fe1ac9047736f7ba91d4b508594307b64e1811e9c57d03f0
ff00e10783fe154baa3f84b41b4d057527492e61b24f2e2665ced2107cabf78f402bc13e1f9ff8
593fb7478db5d3fbcb1f0869cba5dbb75093b7cb2aff00335f56d76d694a108524f4b6bf3d7fc8
e3a318ca72aad6b7d3e5a7f9854573711da5bcb3cce238a252eee7a2a81926a5af27fdab3c703e
1e7ecf3e38d677ec9469ef6b173cef9888863dc6fcfe15cb08b9c945753a672508b93e8797fec3
76f278a9fe247c47ba4fdf78975e9bc973d4471b152a3db201afaa2bcb3f65ff000337c3cf811e
10d1a58fcbbb4b2496e73d5a571963f8d7a9d6b88929d5935b7e8b4465878b8528a7bfeac28a28
ae73a0f8dbfe0a87e06ff8487e0559ebb1c7ba6d12fd2425473b1fe53f80e4d7ca9fb02fc6bf8a
da278fad3c1de1481fc4be1e99bcdbbd26ee5c456b1ee01a6463cc78c8ce383919078c7ea7fc46
f87fa4fc51f05ea9e17d6e37934cd462314a2338700f753d8d7cc5f1dfe0245f006dbc37f14be1
3695f61bbf0847e4ea9a55b7fcc434e27326ef565396cfbe7f86bdcc2e2a0e83c2cd5dbbdafb79
7e278b89c34d5758983b256bdb7feac7d811966452ea15c819507383e99af93bf69df0edff00c0
df89ba2fc7bf0c40ef6f16dd33c576508ff8f8b36202cc40ea5081cfb27615f46fc37f881a4fc5
0f05695e26d16e16e2c350856552a7952472a7d083c60d6bebda1d9789b45bed2752816eac2f61
7b79e17190e8c3047eb5e5d29ba33f797935e5d4f4ea415687bafcd3fc88fc37e21b0f1668361a
c69970975617b0acd0cb19c8652322a978efc77a27c35f0adff88bc437d1e9fa5d9a1792590f24
f6551dd8f402be4df845f13edbf642f15f8a3e177c40d4fecbe1bb28e4d53c3ba95c1e25b6ea61
1eac3a051f4ab9e0bf05f88bf6cdf17da78f3c736d3e8ff0bb4f97ccd03c352e55b5020f17130f
eefa0fcbb93d0f0ca32729bf73bf7ed6f3fc8e7589728a8c57bfdbb77bf97e62783bc19e20fdb3
3c656be37f1d5acda57c32d3a6f3343f0d4b91f6c20f134c3be7d0d7d7afa65a4ba7fd85ed616b
2f2fcafb394063d98c6ddbd318e3152dadac3656d15bdbc490c1128448d061540e800ae6be26fc
4df0f7c22f075f7897c4d7f1d86996abf798fcd2b9fbb1a0eacc71c015cf3a92ad2518ad3a25fd
6e6f0a71a317293d7ab3e7df8e7fb2a7c2ff000958df78f74ad5ee7e12eab66a65fed5d06736c8
4f5c7943e5393d94026be60b8d43e36fc61f0ee81aef8f349d6bc7ff0009f4cbc790dad9aa594f
a8c6870934c8065d7d8e4f5f526be86f05fc3cf147ed83e27b4f1d7c45b59f45f8776d279ba278
5a4255aec0fbb34c3d0f5c77fd6bebfb3b3834fb58adada14b7b7894247146a1551474000e82bd
0789961d28cbde979f4f24f7bfe470fd5d621b947dd8fe7e6d6d6fccf15f833fb507c2df1b58da
e87a2dfc5e1abcb58c42ba16a718b496100602853c63fce2bdbd583a86521948c823a1af2ff8a3
fb34fc3cf8bb1336bde1f816ff00aa6a364041731b7f783af7f739af1b6f825f1c7e04319be19f
8ca3f1c68119dc3c3be246db301fdd8e52704f1d588f615c7c94aafc12e57d9ff9ff0099d7cf56
9e938dd775fe5fe47d6b5435cd074df136993e9dabd85b6a7613aed96d6ee2592371e854820d7c
e1e15fdb9344d3b568b40f8a7e1fd4fe1878818edc6ab0b0b490faa4d8c6dff68e057d21a36b7a
7f88b4e8350d2efadf51b19d7745736b2892371ea181c1158ce954a2ef256febb9ac2ad3aabdd7
7febb1f36f897f61fd3742d566d7fe12789753f865ae31de62d3e666b298fa3c24e36ffb2303da
b322fda03e31fc0d716df15bc0ff00f09468a876ff00c24be184cb63fbd24238ce39c2818f5afa
cea86bd7f0e95a1ea37b70aaf6f6d6d24d22b8c82aaa49cfe02b658894bddaab9bd77fbf732787
51d693e5f4dbeed8f90bf624f1fe81f103e2a7c63f14c5a8c31dc6afad1fb0db5cb849dedb195f
949cf1d2beccaf80ff0065cfd933c25f18fe06c5e26d53ed9a3789eef51bb920d634b98c3322f9
a7674e0ae31c715e8a34afda33f67b04e9f35b7c64f0a43ff2c243e46a71a0f41fc5feeae49ae9
c4d2a752ab54e566b4b3d36d347b7df639b0f5274e92738dd3d6eb5df5d56ff75cbbe3dc78a3f6
f9f00d87de8745d067b971d96424b29fc8d7d555f03fc0cfda0bc35e37fdb2bc5be24f123b7826
e64d2adb4fb3d375f65b79967501648f93d7dbad7ded1c8b2a2ba30746190ca7208ac317095370
8496c97f9fea6f869c6a294e2f76ff00cbf41d45145709da1451450014846460f20d2d1401f227
c2827f66bfda7f5ef87531f23c21e3163aae859e1219cfdf847a73c01f8d7d676ba85adec93476
f730cf240db6558e40c636f46c743f5afcd8ff008297f8e3e2169be31d12dae3438b49d02c2633
e8fafda31696472391bf03630eebf95769ff0004a2f175e6bda4fc47b4d46f26bcba4b9b3b9f32
790bbbef1286393feeafe75ed56c2ca78758b6f5b2bfe57ff33c7a38950aef0a97576fcec7def7
16f1dd41241320922914a3a30c860460835f277c04b87fd9f3f687f157c22be731f877c425f5ef
0d3b9c2873febe05f7c0ce3b051eb5f5ad780fed79f08759f1e785b46f14783613278f7c257f1e
a3a5843869d77012c24fa32f38efb71deb830f25774e5b4bf07d1ff5d0eeaf1765522b58fe5d57
f5d4f7ea2b3f40babcbdd0ec27d46d0d8dfc90a34f6ccc18c4e47ccb9048383e86a9f8afc73e1e
f02d87db7c43ad5868b6bd04b7d70b1293e80b1193ed5c8756e6e515f38789bf6fef843e1f9648
a0d66e357990e08b2b59194fd1c8da7f035c837fc14cbe1d09820d135c643ff2d0471e3f2dd9ab
5094be15721ce31ddd8fafa8af99bc3bff00050af847ad4891ddea37ba3bb7005dda4840fab282
07e26bdc7c17f13bc27f116d8cfe1af10e9dad22805c59dc2c8c9fef00723f1a969ad1949a7aa3
a8a28a290c28a28a0028a28a0028a28a0028a28a0028a28a0028a28a0028a28a002a96b7ab41a0
68b7fa9dd1db6d656f25cca7d1114b37e80d5daf0cfdb5fc672782ff0066ff0016496c4fdbf528
d34bb541d5de670a547fc037d694e0ea4d4175667527ece0e6fa1c97ec0fa4cf77f0f7c49e35bd
04dff8ab5a9ef1dcff00122b1546fc4115f50570bf037c191fc3ef845e13f0fc600165a7c48481
d4edc9cfe75dd55d79aa956525b13461c94e31615f2cfedc572fe28bcf851f0de0f9e4f12f8923
b8b88d7ab5b5b0dd2a9f621c1ff80d7d4d5f28a7fc5cdff82824a7064d3bc03e1d54f511de5c36
73ed989bff001dad70ba4dcff9537fe5f8d8cb13ac143f99a5fe7f81f545a5b259dac36f18c471
22c6a3d00181535145719d614514500151dc411dd41243346b2c3229478dc655948c1047718a92
8a00f8e3c1d752fec75f1ea4f085e3b27c2ff195c34fa4cce494d3eed8f3164f4527fc6bea7f1d
78ef43f86de15bef117886fa3d3f4ab38cbc92b9ebe8aa3bb1e80579e7ed65e16f08f8a3e096bc
be30bf8b48b2b58cdc5bea4ff7ade75e5193b9390381d6be46fd977fb5bf6c5f1358d8fc4dd784
fa5781ed6ddedfc37868df5166cecba941fbcbb42fe63a679f555358887b79e9cbf179f6b79f47
f79e63a8f0f3f610d6fb7977bf9755f7173e25fc38f887fb67e9ba87c4b6b45d0f44d12332f863
44b884192f554ee2d2e474602bec1fd9cbe2ee9ff19fe15693add9c4967770afd8efec146d3697
1180ae9b7f847703d08f4af49b6b486ced63b6822486de3508912280aaa38000f4af88fe2ef89c
fec35f1d67f1858dbbdef81bc730ca6ef47b7601e2d46319574527a36e0091fde6cf4194a5f5c5
ec52b35f0afcd7ebea371faa3f6addd3f89fe4ff0043ea8f8c1f18fc39f04fc253ebbe21ba11a0
1b60b54e66b993b222f726be7ef86ff07bc4bfb4b78c2cbe27fc5fb76b6d0ed5bcdf0e7831cfee
6052789a753f79ce01e7fa002ffc1df815e22f8b5e2bb6f8adf18d04b7cd89745f0c139834f8cf
2acebd0be31fd7d2beab0028000000e00158b92c3ae4a6ef2eafb792fd59aa8bc43e6a8ad1e8bb
f9bff21238d6245445088a0055518007a53a8a2b84ed0a28a280317c59e0cd0bc75a44ba5f8874
8b3d674f9061adef605950fe0c0d7ce3ac7ec513781b519b5af82de35d53e1edfbb798da6095ae
34e9cfa3c4c4e7f1e07a57d51456f4eb54a5a45e9dba7dc63528c2a6b25af7ebf79f26c1fb4d7c
51f8333259fc60f00497ba721da7c49e19532c647f79a3fe78c015d5fc4cfda4bc0de36fd9cbc7
fac785fc47697d20d16e61f237ec9e37923318050e0e416ed9afa0e7b78aea178a68d2689c6192
450cac3d083d6be21fdbff00f67ef0168df0ba6f1368da1c7a3f8a6f750b6d3e1974f630a4ed23
f2ae838236ab7031cf35d741d1ad562a51e5775b6df77f5e872565568d3938caeadd77fbff00af
53e84fd923c3ff00f08dfece5e02b464d93369914b28ff006d865bf5af5eaf8ef42b5fda23f675
d16c63b5b5b3f8b5e108214db0c1fb9d4608f0380bfc581d02e7eb5def81bf6e2f871e2d4bbb2d
4ef26f07f896d23669744f10a1b5983a8cec52df2b138e8093ed59d5a139ca5521ef27dbf55ba3
4a55a108aa73f75aeffd58f29f80df077c1dfb4278b7e386abe2fd0adb59b6b9f134b0da4b327e
f22403ac720f997d3822ba87fd99fe28fc0e6373f06bc7f3dd6908770f09f895bed16d8ebb6373
cc63e9c9f5ad7ff8279e9ec9f015f569726e355d5af2e1d8ff0010f35b69fcb15f4f56b5f113a7
56504ef15a59eab4d0ce8d0854a519b566f5bad1eba9f2d681fb6b49e12bf8f46f8c3e0dd43c07
a90214ea31c6d358487fbc1864a8f6249afa33c2fe31d0fc6ba647a8683aada6ad66e03096d650
e307a640e47e353ebde1bd2bc53a7c963ac69d6da9da38c343751075fd7a57ce9e28fd8874ed27
51935bf853e27d4be1c6b592e21b590c965237a3464f19ee793587ee2aff0071fdebfcd7e26dfb
ea7fde5f73ff0027f81f4ed15f257fc2fbf8cbf01b10fc55f033f89f418b83e27f0b032a851fc5
245d547724e3e95ee1f0a7f682f00fc69b412f84fc4767a8ce17749645f65cc7fef44d861f5c62
b39e1e705cdbaeeb545c2bc26f9767d9e8cf45a29924890a33bb0445192cc7000a58e459a35746
0e8c32aca72083d0d739d0737f11be1ce81f157c257de1cf125845a86997685592419287b329ec
c3b115f2efec91fb35eb9fb32fc7df18e92ccf7fe13d5b4a371a7ea247531cd18f2dfd1c090fd4
026bec8a2ba215e7084a927eeb39e742139c6a35aa0acbf12789b4af07e8d73ab6b57f0e9ba75b
a9796e276daaa3fa9f615178bfc5ba5f817c377faeeb372969a7594465965738c01dbeb5f92ffb
4dfed3dadfc7ef12488b24963e17b6722cf4f562030ff9e8fea4fe95a61309571b5552a4b5fcbd
48c562a96129bab55e9f99ee5f1eff00e0a2fa9ea53dc691f0de1fecdb404a1d62e1034d27ba29
e147e66be31f11f8a358f17ea726a3ae6a777ab5f4872d71793348e7f126b328afd2f05926170a
939ae79777fa23f3bc667389c4b6a2f963d97eac28a28afa049455923c26db776156b4bd56fb43
be86f74ebc9ec2f216dd1dc5b4863743ea18722aad15cf5b0d4710b96ac13f536a388ab41de949
af43ec0f815ff050cf1478427b7d33c741bc4ba4709f6d3817510f52dfc7f8f3ef5fa19e01f889
e1ff0089be1e835af0e6a516a3632807287e643fdd61d41afc33af4cf811f1f7c47f013c5916a9
a3cc66b09182dee9aedfbbb88f3c8f66f435f0b99e41eca2eb61354b75fe47dae5b9e7b592a58a
d1bd9ff99fb4945721f0afe28689f17fc1963e24d06e3ceb4b95f991befc4ffc48c3b1078aebeb
e28fb10a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800af953f6bc90f8efe2efc12f
86d136f4bcd65f5cbd4eca96cb98c9f624c82beabaf943e1ff00fc5cdfdbcfc7baf1fdf58782b4
4b6d1206fe1f366265247b8c3a9aecc37bb2954fe54dfe8bf1672623551a7fccd2fd5fe08fab51
1634545015546001d853a8a2b8ceb21bcb94b2b49ee24e1224691be8064d7cbffb0cdab7898fc5
2f8933e5a5f14f89258ede43fc7696e36c273ff0361f8537f6a0fdb1fc19e01d03c73e0cfed09e
cfc6d0d8bc76b6ef6efb24775f948900da07d4d777fb1cc5e1fd27f67bf0668fa1eaf61aa3db58
24b75f62b8494c734a4c8eadb4f043395e7d2bbd539d2c3ca5256e6b7ddbff0091c2e70ab888c5
3bf2dfefdbfccf6da28a2b80ee0a28a2800ae7fc77e3ad13e1af85affc43e21be8f4fd2ec90bc9
2c8793e8aa3bb1e8051e3bf1d689f0dbc2b7fe21f10df45a76956519792694e3e8a07727b015f2
c782fc19e22fdb3fc5f69e3bf1c5b4fa3fc2dd3e5f3340f0dcb956d4083c5c4c3fbbe83f2f5ae9
a5494939cf48afeacbcce7ab55c5a843593feaefc83c21e0cf107ed9be32b5f1b78e6d66d2be18
e9d3799a2786a4cafdb483c4d30ef9f435bdfb557c32d47c05ade87f1bbe1fda08b5ef0c4620d5
74fb75dab7fa6ff12151c128391edcff0008afa8ed6d61b2b68adede248608942246830aa07400
578bfed25fb44e97f08b4c8340b1b3ff00849bc73ae29b7d33c3900f3249b70237c8a3a47d7af5
c1f438de9d6a952aa505a6d6e96ebff05984e8c2149b9bd77bf5bf4ff808cdf1afed91e0ff000f
fc2dd1bc4da4b9d7757d762034bd16d4ee9e698ff0b28e5403d4d79df86bf63cbff8dda6ebbe2f
f8d772d7fe2fd72cda0d3ec558f91a146725046bd3783827f11dc93e4bf037e1a5cfeca9f1efc3
b77f13f4bb1783c55095d3b50425a0d26ed8ee308cf0a79c67f1afd1ead6b3584d283df5e6fd17
ebdcce9278ad6badba7eaff43e6bfd903e276aaf6bab7c2bf19c857c65e117fb36f94fcd776a0e
239467af18e7bf5afa52be5bfdae3c0fa9f82b5bd1be37f84202dae787085d56da307fd32cb386
040ea547e95f427803c6fa5fc48f0668fe26d1a613e9ba9dbacf13039c67aa9f704107dc1ae5af
1524ab4767bf93feb5474516e2dd196eb6f35fd68ce828a28ae43ac28a28a0028a28a002be56fd
b7a43aef893e08f8457e6fed1f185bdf3a7f7a3b704b7e1892bea9af953e2e7fc555fb767c1dd2
0fcf1683a5ea1aac89e8254f2d49ff008128aecc2e9539bb26ff0006726275a7cbdda5f8a3ea94
411a2a2f0aa302bc37f6c1f00f83b5ff0081de32d6bc45a0586a17da6e953c96779342be7412ed
22328fd47ce578079af74af9d3fe0a01ac3e9bfb2df8a6d61245d6a72da58c201e4b35c4648fc5
5585461aeeb4127d5178869519b6ba33c67e04fc08f8c5f0f7e0ff0084bc49f0cfc76d32df5845
7973e14d7944969bd86e658ce3f7633e9cfbd7a5e87fb6bcde0fbf8f47f8c5e0ad47c097f9d9fd
a70c6d3e9ee7fbdbbaa0fa926be88f01e909a0782b42d3a2188edaca28c0f4c28abdadf87f4cf1
2d84965ab585b6a36920c3437510914fe07f9d6d3c446ac9bab1bf9ad1ff005ea8c61879528a54
a56f27aafebd0a7e13f1be81e3ad352ffc3fabda6af68e03092d650f807d4751f8d6e57ccbe2bf
d87f46b2d464d6be18f88b52f86fade4baad8c85ed1dbfda889fd79fa5618f8d1f1c7e018f2be2
4f821bc73e1d8b83e23f0a8f324441fc5245d47a9638f6cd47b08d4fe0cafe4f47fe4cbf6d287f
1636f35aaff347d6a5430208041ec6bc37e2afec6ff0dfe28de9d57fb2dbc37e2456f323d6f426
fb2dc2bff7cede18fbb035d17c27fda5be1dfc698947867c476b3df1197d3a76f26e90f7cc4d86
fc40c57a8d649d5c3cb4bc59ab54ebc7a491f9bffb5678a3e32fecd1f0fa7f0aeabe3bb6f18f87
7c431bd9db5e5ec78d4add4727e7072dc7f11ac1fd893f6f49bc16f63e04f88778f73a13110e9f
abca4b3d993802390f78fd0f51f4e2bef9f8a7fb3ef80be345c5a5c78c3418b579ed10c703c8ec
0c6a4e48001c7535e5f7dff04f0f8277b9c787a7b6cffcf0b9231f9835eac317869d0f675a3abe
a92dcf2e785c4c6b7b4a32d1746d9f47da5dc17f6d15cdb4a93dbcaa1e396360caca7a107b8a9a
b90f861f0cb4cf84be188b40d1eef50b9d3613fb94d427f38c4bfdd5381c7b556f8ddf10a3f857
f0a3c4fe28760af6166cd06ee8666c2443f1765af16564df2ec7b11bb5aee7c1bff0506fda0e5f
17f8b4f80747ba61a3692ffe9a636f967b81d41f50bd3eb9f5af8e6ac6a3a84fab5fdcdedd48d3
5cdc48d2c8ee725989c924d57afd6326c0ac1e1936bde96aff00cbe47e5f9b631e2f10d27eec74
5fe7f30a28a2bde3c40a28a2800a28a2800a28a2803e8cfd8a7f6819fe0efc46874abfb86ff846
75a9161b88c9f96294f0b201f903ebc57eb123ac88aca432b0c823a115f8248ed1baba12aea720
8ea0d7ec1fec79f141be2a7c0ad12fae25f3751b0ce9f744f5df181b4ffdf2579f506bf2ccfb02
b0988e782f767afcfa9fa5e498d78aa1c937ef474f9743db28a28af9a3e882b1fc5a9ab3f87aed
74228baa9d9e49908dbf7c6eebc7dddd5b145001451450014514500145145001451505ededbe9d
6b25cdd4f1db5bc6bb9e59582aa8f524f4a00835cd4e3d1746bebf9582476d03ccccdd06d04d7c
dffb02696f7ff0d3c4be3bba43f6bf19f886f354576ebe407d88bf40564c7d6b1bf6aefdad3c03
ff000aafc55e17f0f78a6db50f115fdabda43f61dd32216e09f3101518fad798fc31ff008280f8
3be157c31f0cf84f4ef0aead73fd956115bc929312a3cb8cc8cbf3e705cb1e477aeea7194a8c94
15db6b6ec8e3a928c6b45cdd924f7eecfd05a2be24b1ff0082a0f85da402f3c21aba267930b44c
7f5715e9be0cfdbebe1278b25486e7579b41b872004d4a16441f5900d83f135cd3a5529fc716bd
51d10ab0a9f0493f99f0bffc14abc3932fed412bdbc4d249a9595b08a345c9660a178f524d7dcb
fb0f7ecd317c00f8611dcea302ff00c25badaa5cea121fbd0a63f7700ff74124fbb1f415b1abfc
0ef0c7c60f8e7e1af8a42fecb5ad2b4ab02b6c96f22ca92dc6fcab923208039fad7bcd7a35f18e
7878508f45a9e7d0c22862275e5d5e81451457927a815cff008ebc75a27c36f0b5ff00887c437d
1e9fa5d9465e49643c9f4551dd8f4028f1df8eb44f86de15bff117886fa2d3b4bb28cbcb34a71f
4007727a002be58f067837c45fb67f8bed3c77e38b69f47f859a7cbe6681e1b972ada81078b898
7f74e381f97ad74d2a4a49ce7a457f565e67355aae2d421ac9ff00577e41e10f06f883f6cef18d
af8d7c736b3695f0c34d9bccd13c372e57edac0f134c3b83e95f61dbdbc56b0470431ac50c6a11
23418555030001d8536d2d21b1b68adede24820894224718c2a81d0015f3d7ed09fb495ee87af4
1f0d3e1a5a8f11fc4dd4970228be68b4c88f59a66e8a47500fb13d466db9e266a30564b65d12fe
b764a50c345ca4eedf5eadff005b2347f685fda53fe15ddd5bf83fc1d67ff092fc47d53f7767a6
43f32dbe7fe5a4b8e8075c537f676fd9affe15ddede78dbc6779ff00093fc4dd63e7bdd56e3e61
6c0ffcb1833f7547038eb81d800347f679fd9bec7e0f5acfaceaf747c43e3bd4ff0079a96b571f
33163c948f3f75474af6ba275234e2e952dbabefff0000214e5397b4abbf45dbfe09e77f1e3e0f
69bf1bfe1c6a5e1bbf012675f36cee87dfb79d794753db0715e7bfb23fc62d4bc53a3ea7f0ff00
c64de4fc40f07b8b3bc493837700e22b85cf5c8c027e84f5afa1abe5cfdac7e1deade0cd7749f8
e7e07819bc45e1b1b358b2878fed1d3b3fbc040ea53afd39fe1a28b5523ec25d76f27ff042b274
dfb68f4dfcd7fc03e9dbcb38750b49ad6e2312c13218e446e8ca4608af917e0edfcdfb2bfc7dd4
3e136a8e53c0fe2a91f53f0b5c39f92de627f7b6b9eddb03d97bb1afa67e1afc41d27e2978274a
f13e8b70b7161a842b2a953ca1c72a7d083c60d70ffb507c131f1afe1a4f6960df65f14e9520d4
744bd43b5e1ba8f9500f60dd3eb83da95192849d2aba27a3f27dfe43ab1738aab4f75aaf35dbe6
7afd15e33fb2c7c6cff85cbf0de293505fb2f8a3487fb06b166c30d14e9c1383d9b191f5af66ae
79c254e4e12dd1bc26aa454a3b30a28a2a0b0a28a2800af95bc03ff1557fc1407e206a8dfbc4f0
f7862df4904ff03492acc3f4ddf9d7d535f2bfec739f107c52f8f7e2c61bbedde218b4f573ff00
4ec8e847fe3c3f2aeba1a42a4bcadf7b47256d674e3e77fb933ea8af963f6f09bfb56cfe12785d
796d5fc6d60645f58537efff00d081fc2bea7af94ff682ff008a9ff6c5f807e1f1f34565fda5a9
dc2fa6211e59ff00be948fc69e134abcdd937f72618ad6972f7697ded1f5441108208e35e88a14
7e02a4a28ae33ac2908cf5a5a2803c63e2cfec8ff0dbe2f4ed7fa86889a66bb9de9ace95fe8d74
afd98b2e3711fed66bcc8f837f688f802777867c410fc5af0bc5d34cd778bf8d3d125072e71ea4
01e95f5a515d51c44e2b965ef2ecf5ff0086f91cd2c3c1be68e8fbafeb5f99f39f80bf6def066b
9a9268be2fb3bef87be22ddb1acf5a8cac4cde892e30df963debe83b0d46d755b48eeacae61bbb
690652681c3a30f6238ae77c79f0afc25f1374e7b2f13e8165abc2e36e67886f1f461c8fcebe7c
befd90bc5bf0beea4d4fe0b7c40bbd130771d035c6371652639da1baa8ec0003dcd572d0a9f0be
57e7aafbf75f8937ad4f75ccbcb47f76c7d5d5f1effc14c3c592695f08745d1219369d5353532a
ff007a28d19b1ff7d6c3f857b87c0af14fc4af1069da95b7c49f0adbf87b52b194451dc5a5c2cb
15e0c03bd31d057ca9ff00054b9dc5c7c3c8403e532deb93db20c207f334a8d2be2214a5d5a5f7
b1d6ab6c3cea47a26ff03e0ca28a2bf6d3f1c0a28a2800a28a2800a28a2800a28a2800afbd7fe0
977e2a713f8d7c38ef94290df44a4fddda4a363ebbd7f215f0557d7bff0004c995a3f8e1afa004
abe81283e83fd22039fd3f5af93e2582961232ed2ff33ea387a6d62a51eebfc8fd33a28a2bf333
f450a28a2800a28a2800a28a2800a28af903f6dafdae7fe158dacbe09f0a5c86f145cc60dddca1
cfd8a361c0ff007d8738ec39ee337084aa49420aed9139c69c5ce6ec91d6fed21fb6a786fe09ac
ba4e94b1f883c51823ecc8ff00bab73d8c847f21f9d7e737c59fda07c73f1a6fda6f12eb73cf69
b8b45a742de5db45feec638cfb9e4f735e7f79773dfdd4b737333cf712b1779646cb313d493515
7e8d97e414a8a53c52e6976e8bfccfcff1f9ed5aadc30cf963dfabff0021318a5a28afac8c2305
cb15647cbca529be693bb0a4c52d14dc5495a4ae849b8bba7a9d5fc3df8abe2cf857aa8d43c2da
e5de933e41748643e5cb8ece9f7587b106bf40ff00671fdbf748f88135ae81e398e2d0f5d7c245
7e9c5b5cb74e47f037e9f4afcd1a0120820e08e4115f318fc86862139d05c92fc1fcbfc8fa4c0e
775b0ed46b3e68fe28fdee4759515d183a30c86539047ad43a85e2e9f617374d1c92ac1134a638
9773b0504e1477271c0af807f624fdb0e6b6beb3f00f8daf8c96f311169ba94edf71bb46e4f63d
8d7e8357e6d568ce85474ea2b347e854aac2bc154a6ee99f1ef86bc09e25fdb0bc75178b7c7f63
71a2fc36d26e09d1fc2f3e55af1d4ffad9c77e9d0d7d27f133c79a57c1ef86dac7892f8476fa7e
91685e3846155980c471a8f76daa31eb5d72a850000001d857c21fb7e6a1e36f8e1e25d2fe10fc
3bd16fb5a4b365bdd6a6b642208e561fb98e490e1530a4b1dc47de5aeaa7fed756307a457dc97f
5d7b9cd53fd9694a6b593fbdb390f007edfbf103e326870780743b0b4b7f881aadd35bc1acc8cb
1c30c07fe5a6de9bc0ff00f557d89fb3e7ecefa2fc08d06e3ca91b57f146a6de7eafaf5d7cd717
929e4e58f21412703f1ea49af933e037fc1302fb44d4b4fd7bc73e256b2bbb775992c3457f9d18
7233374047fb208afd0ab687ecd6f145bda4f2d42ef73966c0c649f5adf1b528a7ecf0cfdd7bff
005d8c7074eb35cf895ef2dbfaee49451457907aa151cf047730c90ca8b2c52294747190c0f041
1e95251401f1cf83e793f63bf8f72f84eedda3f85fe32b833e952b9ca69f76c798b27a2927fad7
d8a0e4579efc77f83da6fc6ef875a87872fbf753b2f9b6774a3e7b79d794753f5c579e7ec8df18
351f1468daa7c3ef18936ff107c1ce2cefa290e1aea01feaae173d4118c9fa1fe215db53f7f0f6
abe25bfe8ff4671c3f733f64f67b7eabfc8e1fe35d8dc7ecc5f1e2c3e2e6930b7fc223e22916c7
c4f6d10f951d8e167c7ae79cfaf5afadac2fedf54b1b7bcb4992e2d6e235962950e55d1864107d
083591e3cf05699f113c23aa787758816e34fd42068645619c647047b8af9e3f649f1aea5e01f1
26bdf027c613b36b7e1dcdce897531ff008fed358fca54f7284807ea47f09a1fefe9737da8efe6
bfe07e40bf735397eccbf07ff07f33ea6a28a2b88ec0a28a28033bc4579fd9de1fd4eeb38f22da
4933f4526be79ff827e5913f026ef5c607778875ebed5771eac1dc2ffec86bd2ff00696f111f0a
7c05f1ceaa1b6b5be972b29cf39c638fceb3bf64af0e7fc22bfb37f8034fdbb48d3567c7fd7566
97ff0067aeb8e98793eed7e099caf5ae9764ff00168f5daf956cc0f15ffc1452edfef41e1ef066
077db33dc01faabfe95f5557caff00b35e3c4dfb547ed01e233cc504fa7e9b6ec79e046c5c0ff8
120fce8a1a46a4bb2fcda42afaca9c7cff0024d9f54514515c8758514514005145140051451400
57c39ff0544d05a6f0a782b590094b7bd96d091d8c89b87fe8aafb8b39af0efdb43e1e3fc45fd9
efc4b6f6f1f997ba722ea76e31de23b9f1efe5f983f1ad694fd9d48cd7469fdc67561ed21283ea
9a3f2068a3041c11823b515fb8426aa454e3b33f189c5c24e32dd0514515648514514005145140
05145140057dabff0004bed09e6f887e2fd6803e5dbe96b664f6cc92a38ffd146be2aafd43ff00
82737c3d7f0afc16b9d76e22f2ee35fbb32a9c7de863caa1ff00be8c9f957c67135651a30a3d5b
bfddff000e7d770e5172ad3abd12b7dfff000c7d5b451457e747df851451400514514005145140
1e5ffb467c64b5f81ff0bf53f1049b5ef8af9365013feb263c2fe03bd7e36ebbaedf789b5abed5
b53b87bbd42f6669e79a4392ecc724d7d65ff0520f89efe22f89763e12b7949b2d1a1124aa0fca
d338ebf50322be3fafbee1bc12b3c5cd6bb2fd5fe87c3f10e31dd6160f4ddfe8bf50a28a2bee8f
8a0a28a2800a28a2800a28a2801d1c8d1489246c5244219594e0823a1afd62fd88fe3d9f8cdf0b
d6c7539fcdf12683b6d6ecb1f9a68c83e54bee48041f75cf7afc9baf74fd8bbe27c9f0cbe3ce88
cf318f4ed5dbfb36e973c36f23cb38f5de147e26be3b88b04aa5158a8ad63bfa7fc03eb320c63a
757ead27a4b6f5ff00827ebe5312248f76c455dc727031934e072296bf383f410a28a2800a28a2
800a28a2800af96ff6b1f879ab7833c41a3fc74f03c27fe123f0e0f2b57b38bfe623a713f3ab0e
e57a8fcff8457d4951dc411dd41243346b2c3229478dc6432918208f422b6a551d29f32ff875d8
caad35563caffe199ce7c36f883a4fc52f05697e26d16713d85fc2245c7543dd4fa1078c5784fe
db3e0592c741d1be2df87eea0d33c65e099c5cc32c9208c5e5b1e25b763c6723240f4dc07deae5
fc213cbfb1e7c7c7f09dec8c9f0c7c677066d26e243fbbb0bb2726127a004ff8d7acfed4dfb33d
87ed29e094d324d4ee349d52d0b49673a3b7925cff000ca83ef2f039ea3a8aeb828d0af195fdc7
d7cbaa7f933966e55a8ca36f7974f3effaa3cffe097edf1a07c71f8afa4783748d227b54bab279
e6bdbb60a7ce55c98d5476cf19ef5f5657e2e7c3cf0578a7f655fdaa3c21078b2c65d39adf528c
19fac573096c1647e8c0d7ed1d5e61429d09c5d1f85a33c057a95a12557e24c28a28af2cf4cf9c
3f6fcd5bfb3ff678beb356c3ea97f6b61b7bb2c8fb4ff3af75f0568fff0008ef83741d280da2c6
c2ded71e9b2355fe95f387edb83fe121f10fc1ef08821bfb5fc488248ffd950181fcc57d535d73
d284177bbfc97e872c35ad37dacbf5fd4f03fdaebf68dd5bf66af0be8baf586876fadd9dd5d35b
dd2ccec863181b4820f7271cd7ca7fb0d7ed676b1f8ff5bf0d3f85ef6fb5cf1aebf25f8b9b7986
c8232090ac36f211771ce6bea1fdbdbc15ff0009afecc9e29454df2e9caba8260727cb39c0fceb
c2bfe0977f00bfb1f40d43e27ead6d8bbd44359694245e56107f7920ff007980507fd96f5af468
aa0b0339cd7bd7b7ea8f3eb3aef1b08c1e96bff99f7e514515e19ed0514514005154f56d5ec741
d3a7bfd46ee1b1b2b74324b7170e1111475249e057cbfe25fdae75cf8a1acdcf85be0378764f16
5f46de5dcf896e54c7a659ff00b5bce039f41dfb13d2b6a746757e15a2ebd17ccc6a55852f89ea
fa752e7edcdf1f7c71f003c29a56afe126d23c8b894c3702f537ce84fdd6452d823f035f0b786f
f6a3fda2ff00685f1a58785b44f175f477d7f26c55d2e34b45853f89d9a255215473926bee2f0f
fec3d69e278ef357f8b7e21baf1e78a2f21640ceecb6966cc3fe59277c1efc74e95d4feca9fb24
685fb356937ee9226abe21be9184ba895c158031d91ae7a71827d4fd2bd7a588c2e1e8b5caa535
d6dfd6df23caab43135eaa7cce307d2ffd6e7a1fc1af86b2fc2ef04da69379acdff88b5561e65e
ea9a95c3cd35c4a7ef1cb1240f41d8576f3431dcc32452a2c9148a51d18643023041152515e24a
4e4dc9eecf6631514a28fc6efda9be0bdc7c13f8b3aa698b130d22edcdd69f2f66898e42e7d474
3f4af20afd8bfda7ff0067db2f8fbe0192c06c835db4065d3ee987dd7fee13e86bf22bc57e15d5
3c11e22bfd0f5ab492cb52b290c534320c10477fa11820f706bf41c83328ce0b0955eab6f35dbe
47c267b97384de2a9ad1efe4fb993451457da9f1e1451450014514500145153d8585cea97d6f65
6704975777122c50c31296791d8e15401d492718acaad585083a951d9235a54a75a6a9d3576ceb
7e0efc33d43e2e7c43d23c35a7c65daea51e73f68e207e6627b715fb4fe16f0e59f843c39a6e8b
a7c622b3b0812de25031c28c67ea7a9fad781fec6dfb3127c0df09ff006a6b3123f8b75340d704
60fd993b460fafae3bd7d235f8fe638d963f10eabdb65e87ead97e0d60a82a4b7ddfa8514515e6
1e905145140051451400514556d49da3d3ae99065d6272a07ae0e2803f143e3878a1fc67f173c5
7acbbeff00b55fcac3d86ec62b87ad0f1112de21d54b70c6ee5247fc0cd67d7ec594c14303492e
d7fbf53f26cd24e78daadf7fcb40a28a2bd63cb0a28a2800a28a2800a28a2800a9f4fbf9b4ad42
d6f6ddb65c5b4a9346de8ca4107f3150521e95c58d82a986a917d62ff23af07270c4d392eebf33
f753c0baca7883c19a26a48dbd6e6d239377afca335bb5e6bfb3648f2fc06f03bc80ab9d322c82
735e955f8a1fb1051451400514514005145140051451401e77f1e7e0ee9bf1bfe1c6a5e1bbf023
9dd7cdb3ba1f7ede75e51d4f6e715e7dfb23fc62d4bc55a36a7e00f193793f103c20e2cef524e1
aee01c4770bea08c027e84f5afa16be7bf8e5f052fbfe1687853e2bf84353b1d035cd2a516dad4
97f2f956f77a79fbe1cff797b7d47a575d29c65074a6f4dd3ecffe0ff91cb52328c95582d767e6
bfe01ea3f147e11f863e30e82ba5f8974e8ef238a459ade7c625b7901c8646eaa78ed5d6da406d
ad6185a4699a3408647fbcd818c9f735f3cf8fbf6f3f855e07692de1d59fc477d1f0d169086542
7da4fb87f3af19d6ff00e0a896c929fec8f04cd2c7d8df5c043ff8eeea8853ad5972c22da5d936
5cea51a2f9a7249befa1f79515f9f369ff000547d44c9fe95e03b558f3d62be6271f8a8af43f09
7fc14bfc07aaca916b9a3ea9a213f7a7f2c4d18fc1096fd29cf0b5e92bce0d7aa64c31346a3b42
69fa347bcf8ebe095878f3e27f837c6777a85cc53f86999e0b340be548c4e771c8ce47b1af4aae
2fe1efc65f05fc54b513785fc4563aa9dbb9a08a51e720ff00690fccbf88aed2b07272493e86ea
2a2db5d4cdf12787ecfc55a0dfe8fa847e6d95ec2d0cc9eaa47351784bc3161e0af0ce97a0e970
8834fd3add2da18d4630aa3193ee7a9f726b5e8a5776b741d95efd428a2bc9fe35fed35e06f817
6cb1ebba90b9d6a7005ae89623cebcb86270008c72013c64e076cd54212a92e582bb26738c1734
9d91eaceeb1a33bb0555192cc7000af9efe2afed8fa0785b566f0c78234fb8f885e3573b23d374
af9a1898f432c8380338fafa8ae153c29f1aff006aa759bc4d3cdf0a3e1f4a772e9501ff008995
da76dfd0a67df047bd7d09f0abe087837e0c690b61e16d1e1b3623f7b76e37dc4c7b9773c9cfe5
5d5c94a8ff0011f33ecb6f9bff002fbce6e7a95bf87eeaeef7f92ff3fb8f05d2bf665f1d7c7abf
835cf8ede217934d57135bf8334890c567177024239723f3f735f50f863c2ba3f82f45b6d2342d
36db49d36dd76c56b69108d147d077ad5a2b1a95a75747b2e8b636a74634f55bf7ea14515c17c5
6f8e7e08f82ba4fdbfc5dafdae96181315b33ee9e6c7648c659bf015946329be58abb34949455e
4ec8ef6b81f8a3f1d3c13f0734d6baf146bb6f64f8fddd9a36fb894f65541ce4f6ce05782b7c55
f8d5fb49662f877e1f7f879e0f9b8ff84975f4d971327f7a18baf23907915defc2efd8e3c1be06
d4575dd7dee3c75e2c6f9a4d5b5b3e66d6efb23390a3db9fc2babd8c297f19ebd96ff3e8bf3f23
9bdacaa7f0969ddedfe6ff00ad4c4f017c75f8a5f1a7c69a6dcf863c10be1cf8791cc1ae751d7b
2b75771ffd334fe1fc7f3ae8bf696fd953c3dfb41692276dba5f8a2d908b5d52351961ff003ce4
1fc4b9fc47623273ee491ac48a88a1114602a8c0029d58cea2724e0b96dd8da306a2d4ddee7e24
fc55f829e2df837adcba7f8934b96d943111dda02d0cc3b156ff001ae16bf767c4de13d1bc65a6
49a7eb7a6db6a766e08315cc6187e1e87e95f28fc4cff826d783fc472cd77e14d5ae3c3970e4b0
b6957ce833e83a151f9d7d5e0b88ead24a1895ccbbf5ff00827cbe3387e9d56e7877cafb74ff00
807e6a515f54789bfe09c7f1534791ff00b30e95af20fba6daed6227fefeedae4dbf614f8d6b20
43e10193dc5fdb91f9efc57d1c788301257726be4ff43e7e5916362eca29fcd7ea781d15f4f787
7fe09d9f17357915750b4d374342796babd8e4c7fdfa2d5ef3f0e3fe099ba06952c773e32f104d
ac38e4d9d82f951e7fdf3c91edb457357e24c2c17eea2e4fee5fd7c8e9a3c3d899bfdeb515f79f
06f807e1bf88fe276b71695e1bd2a7d4ae9d803e529d89eecdd00afd30fd95ff00633d23e08c71
6bfaef95abf8c1d3e594ae63b304722307f8bb16ebe98c9af77f047c39f0d7c38d2d34ff000de8
f6ba55b28db88130cdf56ea7f1ae92be2b1d99d7c7cbf78ed1e896c7d860b2ea1815fbb577ddee
1451457927a814514500145145001451450014d650ea5586548c114ea2803f0d7e276852f867e2
2788f4b9c112db5f4a8c1860e7713fd6b99afa67fe0a03f0edfc19f1d2e7548e3db65aec42f11b
1d64e8ff00ad7ccd5fad6475956c0c1758e9f77fc03f2dce68ba58d9f696bfd7cc28a28af78f10
28a28a0028a28a0028a28a0029511a4654452cec70147524d257a6fecd7e0197e247c6df0b6908
b9812e96eee588caac517cedbbd8e02ffc0abcacd2b2a183a937dadf7e87a596d175f174e2bbdf
eed4fd77f851a18f0d7c35f0d6983a5b58449d3fd9cff5aeb2b33c3dae693e20d2e2b9d1750b5d
4ac07c89359cab2c7c71805491c62b4ebf1d6ada33f5a4efaa388f887f1abc13f09ded97c5bafc
1a1fda413135c472156c7fb4aa467db35cc5bfed73f07aec8f2bc7fa53646464b8fe6b5d97c4df
85fe1df8bbe13bbf0f7896c12fac2e1480587cf1b76653d88afc80fda9ff0063ff00137ecebe23
5923865d5fc277b36cb0d4e24270c7a45201f75fd3fbddba1c7a983c3d0c4be49c9a97e679b8cc
457c32e78c538fe47ec5f833c7fe1df887a7497fe1bd5adf58b38df634d6c4950de9d2ba0af81f
e0278ffc6dfb1c7c3bb1d0bc6df0b7507f0bb66edbc43a19175b77fcdba655fb8067bf3ed5f59f
c2cfda13e1f7c66b6593c29e26b2d46e36ee7b2327977318ff006a26c301ee457356c3ca9b6e3a
c7beff0091d147111a8929692edff0e7a2d14515c675851457ccbfb65fed5517c10d00681a148b
2f8c7528898f1822ce23c79adee790a3d413daaa3173928c55db2652504e527648d7fda43f6c2f
0d7c09b7974eb6d9ad78a597e4b08dbe488f63211d3e9d7e95f9b1f173f681f1bfc6bd45e7f126
b53cd67bf745a6c2c52d61f4db18e33ee727deb83d5355bcd7351b8bfd42e64bbbcb872f2cd336
e6663dc9aab5fa365b9053a5155314b9a5dba2ff003fc8f80cc33ca955ba7867cb1efd5ff90514
515f5d18c60b962ac8f94949c9de4eec28a28aa116b4ad5efb42d421bed3af27b0bc85b747716f
214743ea08e457d9ff00b3bffc143755d127b5d0fe2496d574e388d35a51fe9117a193fbe3dfaf
7c9af89a8af031d92e1b189b8ae59775faa3dcc166f88c234a4f9a3d9fe8cfddff000ff8874ef1
568f6baa6937915f585ca078a785b2ac0d68d7e4cfec97fb556a3f037c450e97aacd2ddf83eedc
2cd013936c4ffcb44f4f715fab9a5ea76bad69b6b7f633a5cd9dcc6b34334672ae8c32083f435f
98e2b0d530955d2aaacd1fa3e1b134f154d55a4f467ccde39f1a7c6cf8c3e2ed57c25e04d20f80
3c3b653bda5df8a75101e7970704c0bdbd8f5f435dc7c16fd93fc19f07aedb5a30c9e24f184e4b
dcf88b586f3ee9dcfde2a5bee67db04f7cd7b5d1532af2e5e482e55e5d7d594a8479b9e5abf3e9
e8145729e31f8a5e18f00eaba1e9baeead0585f6b5722d6c6191be695cff0021ee78acaf8b3f1d
fc0ff04f4a37be2dd7ed74d2ca4c5685b75c4fec918cb37e038ef58aa7393492df6357384536de
c7a05705f147e39f827e0e69cd75e28d72dec9f1fbbb446df7129ecaa839c9ed9c0af006f8a7f1
b7f695261f879e1f7f875e0e9b8ff84935e4db73321fe28a3ebc8e846457a07c2dfd8dfc1be05d
4175dd7e4b8f1d78b0fccfab6b67ccdaddfcb8ce428f6e7f0ae9f630a5fc67af65bfcfa2feb439
fdacea7f0969ddedfe6ce124f8b7f1abf68c76b7f871a17fc2bbf0a48769f126b71eebb917d628
8f0bfcfdebbaf855fb1b7833c05ab8f11ebc6e3c77e33761249ae7881fed122bfac6adc2e3b103
3ef5ef691ac48a88a1114602a8c0029d532c44adcb4d72af2fd5effa151a11bf3547ccfcff0044
2050a0000003a014b4515ca74851451400514514005145140051499c52d0014514500145145001
45145001451450014514500145145007cf9fb6b7c106f8c5f096e1f4f8449aee8e4ddda600dce0
0f993f119afc9374689d91d4a3a9219586083e86bf7b98065208041e0835f9c9fb747ec9971e18
d52f3e21f84ecccba2dd3799a9d9c0b936b29eb2803f81bbfa1fa8afa2c9732581adcb53e096fe
5e67819be5ef1b4b9a9fc71dbcfc8f8ae8a28afd5232524a51774cfcc9a71767b8514515420a28
a2800a28a28db50dc43c57e907fc13cbe00af87fc15a978db5db356baf10446d6d2199395b3e77
920f690e38f441eb5f367ec81fb2edf7c70f1443abea90496fe0fb09434f330c7da587fcb343df
dcf6afd5db1b1b7d32ca0b3b4852ded60458a28a318545030001e8057e639ee66b175151a4fdc8
fe2ffe01fa364b973c2c1d6aabde97e08f97fc4dfb1a5ef81f59b9f12fc12f155e781357918cb2
e94ce65d3ae9bae1a36c819fc87a545a17ed81e20f869a945a0fc71f084fe19b8cec4f1169a865
d3e7edb8f74fafe42beacacfd77c3fa6789f4d974fd5ac2df52b29461e0b98c3a9fc0ff3af0562
39d5ab2e6f3ebf7ff9dcf71d0e4d68be5f2e9f77f9107863c5ba2f8d34b8b52d0b53b6d56c6500
acd6b2071cfae3a1f6356f55d22c75cb26b3d46d20beb56656686e230e84ab065383c641008f70
2be65f13fec6779e0cd565f10fc15f155c781f5424bb6913bb49a74e7fbbb792a0fe3f5aada37e
d83aff00c2cd4edf41f8ede10baf09ceede5c3e24b28ccfa6dc9f5deb9da7db9c0ea453f61cfad
077f2ebf775f90bdbf269595bcfa7dfd3e67d5be5a797b368d98c6dc718f4af0ff008a5fb1b7c3
2f8a37675297451e1fd7c37989ac6867ecb70aff00df257019bdd81af5df0cf8a747f1969106ab
a1ea76bab69d38dd1dd59cab246c3d8838ad5ae784e74a578bb33a2508555692ba3e4a3e10fda3
3e0365bc3de21b7f8b3e1b87a69fae022fd53d1651cbb63d4e3daba3f067edc9e10bdd45346f1c
e99a97c38d7cb6c36fac447c866e984940c1fcb03d6be92ae6fc69f0e7c31f1134f7b2f12e8565
acdbb2ed22ea20cc07a06ea3f035bfb6854fe2c7e6b47fe461ec670fe14be4f55fe6657c40f8b7
a17827e19eabe325beb6bed3ed2069227b7955d657c7caa083c927b57e3478ff00c71a9fc48f18
eabe24d5e669afb5098cac58e762f4541eca3007d2beb2fdba9343f83de13f0dfc29f0843258e9
2d249a9dc41e6970373709cf607040f7af8b6beb78770519ce58a7aa5a2ff33e5b3fc64a308e19
68deaffc828a28afbf3e1828a28a0028a28a0028a28a004c66bf423fe09c9f1f24d4eceefe1a6b
3705e5b546bbd25e46e4c79fde423e84ee03fdeafcf8aea7e16f8e6e7e1afc43f0ff0089ad5d91
f4ebb8e6709d5a3ce245fc54b0fc6be673ec12c4e19d58af7a1afcbaff0099f4592631e1f12a93
7eecf4f9f4ff0023f71ebccfe3ff00c7bf0efecf9e04b9f106bb3079c831d958237ef6ea6c70a0
7a7727b0af40d1f53875ad26cefe060f0dcc4b2ab29c8208cd60f8a3e16f84fc6da9dbea1af683
69abdddba6c89eed4b8419cf0a4e3f4afcc69b8292735a1fa3cd49c5a86e7e237c52f8bbe34f8e
bf1127f16dfc97771a87980dac766ae56d141caac607ddc7e79afd20fd8b3e067827c57e0ad3be
24f8834cbff10f8f2e6461797be28dd34d04ca7ac624181c152180cf38cd7d4761f0fbc2fa585f
b1f87349b62bc0315946a7f30b5bb1431c08122458d074541802bd5c4e61eda9aa74e3ca979f4e
c79987c07b2a8ea5497337e5d7b8e0a14000600e8052d14578c7ae145145001451450014514500
14514500145145007c87fb7ffed0b7bf05e0f015b69371e55f4baa25fceaa79f2633dc77072c3f
0afa8fc1be29b2f1bf85349d7f4f712596a36c9731907380c338fa83907e95f945ff000517d5b5
ef1c7c7bd4a58f4abf6d0b4548f4c82e8dbbf945ff008c06c6397dd8afafff00e09c3ad78ba2f8
4575e17f16787f57d20e91307d3ee351b392149ede4c9da8cc003b5813ff000315ed57c2c6183a
7516fd7e7fe478f431329e2e74dedd3e5fe67d6f4514578a7b014514500145145001599e23d7ed
7c2fa2dc6a779bbecd06ddfb064fccc1471f522b4ea1bbb382fedde0b9852785f1ba3914329c1c
8c83ee28026a28a2800a28a2800a8ae6da2bdb796dee2249a0954a491c8b95652304107a822a5a
2803e00fda6bfe09fd32dc5d788fe1ac5e6239324fa1938dbdc988ff00eca6be19d5f47bed0750
96c752b49ac6f223b5e1b8428ca7e86bf796bcfbe26fc04f037c5db568bc49a0dbdccc73b6f225
11cea7d430ea7eb9af77019c62303ee2f7a3d9fe9d8f171d94d0c6fbcfdd9775faf73f1428afd0
5f1cff00c130ec6e24966f0978adad413f25aea711655fac8b927fef9af26d53fe09b9f14ac656
5b6b8d1b5151d1e1ba2a0ffdf614d7d752e24c2c97ef22e2fef3e52a70f62a2fdc926bee3e53a2
bea6b0ff008271fc56ba91567fec9b252705e4bb0c07fdf3935e97e0cff825fdcef57f1578c204
507261d2a169030f4dcfb71f91aaa9c49848af7136fd2c2a7c3d8b93f7da5f3b9f08dbdbcb793a
43044f3cce76ac71a96663e800afae3f66dfd8275cf1f5c5aeb9e3a8e5d13c3dc3a58fddb9ba1d
707fb8a7f3ebd2bed9f857fb2c7c3af844a9268fa1c7737ca306faff00134a7f3181f957adf4af
93c7e7788c6a705eec7b2ebeacfa7c0e4f4306d4dfbd2eefa7a2333c35e1ad33c1fa1da691a3d9
c561a75aa08e282150aaa07b56a51457cf1ef851451400550d6f42d3bc49a65c69baad8dbea561
70bb25b6ba8c491c8be854f06afd14d3b6a837dcf95bc47fb19de7813579fc47f043c5377e02d5
5cf9926905ccba75c9f4689b207f21e95f2ffed29fb6cfc5df0c6afa1f84b52b5b6f0bf8b3c397
c2f2fee74c98b437bf2623057fba4339653c1caf0302bf526be52f89dff04e7f87bf13bc53aaf8
8eef57d760d5f5299a79e56b8591431e815768c00000067a0af5b0b8aa7cf7c52bdb676bbfebd6
e79589c354e4b619dafbeba1df7ecb5fb4fe87fb47f8323bb8192cbc456aa1750d34b728dfde5f
5535edf5f147813fe09d179f07bc6569e27f03fc4bbbb2bfb77cf9173603cb953ba390fc83f4af
b4adbcd16d179fb7cfd83ccd9f777639c67b66b8f131a2a77a12bc5fe075e1e559c2d5959afc4f
c8efdb87c4ade24fda3fc4c77964b265b355cf0be58da71f95782d7a6fed3a58fed0df10f79cb7
f6d5cfe1fbc35e655fa7e45151c042dd6ff99f9be75272c74efd2df90514515ef1e20514514005
145140051451400521e94b4567522a70945f545d39384d497467ec4fec7be266f14fecefe10b89
2432c905a8b5772724b270735ecf5f35ff00c13d4b9fd9a349df9ff8febbc67d3cce2be94afc31
e8cfda56c145145218514514005145140051451400514514005145140051451401f3a7edf16a25
fd9cf55940e6daf2dae33feeb57b67c3fb8fb6780fc373f5f374db67cfd62535e53fb6f5a7dabf
65ef1e37782cbce07dc30ff1af41f82d742f7e0ff82260776745b319f5221507f515d72d70f1f5
7f923957fbc4bd17e6ced28a28ae43a828a28a0028a28a0028a28a0028a28a0028a28a0028a28a
0028a28a0028a6c922c485dd8228e4b31c014ea0028a28a0028a28a0028a2909c0c9a005a2a2b7
b88aea159619125898655d0e41fc6a5a0028a28a0028a28a0028a28a00fc83fdb63c38de1bfda3
fc56a54a8bc945e827bf98377f5af0bafbbbfe0a6df0e1e3bff0ef8d6de3cc5221b1ba2abd1872
ac4fd302be11afd43876baa983f67d62ff003d4fcdb3fa2e9e2f9fa497e5a0514515f507cd8514
514005145140051451400521a5adef00f842ebc7fe36d0fc3966ac67d4eee3b7054676827e66fa
0193f8571636bac361aa557d13fbfa7e27660e8bc462214d757f8753f593f630f0e3786bf673f0
942ca51ae60fb610460e64f9abdbab3bc39a2c3e1dd074fd2edd4243690242aa3a00062b46bf14
3f610a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2803c9bf6aeb1fed2fd9c
fc7f6d8cf99a63f1f420ff004ab1fb2fdf7f68fecfbe039f39ce991ae7fddcaff4ad9f8df63fda
5f087c5f6d8ddbf4d9b8fa2e7fa570dfb125e9bffd963e1f4c7a9b29179f69e41fd2baff00e61f
fedefd0e5ff988f97ea7b8d14515c8750514514005145140051451400514514005145140051451
40051451401f287fc1467e324bf0cbe0b2697a7dc18755d76e16dd0a360889797cfb11915edbfb
3f7c4a8be2efc1bf0a78a924124d7d64a2e4fa4e9f24bf4f9d58fd08afcf8ff8296691e3cf17fc
4a3a99f0d6aa9e0bd0e14b583527b6616ef239f9886c60e5ba1af77ff8269699e3bf05f8275ef0
bf8b7c37aa691a679d1ea5a55d5edbba472acab875562318f91187fbe6bdba9878470319a6b9af
7fbfa7e478d4f11396365069f2dadf77f4cfb4a8a28af10f6428a28a0028a28a00fcbffda0be25
fc44fd8abf683d453c2baa49ff000886b0dfda36fa3ddfef2cc863974543f7307232b835f4f7ec
cbfb79785fe3fea56de1ebbd3ae342f15c88585b0532c12e07255c72bf43f9d4ff00b747ecd37f
fb42780f4b5f0fc1149e25d3aed7c96918203131c382c7b01935e27f0e3e1f5f7fc13bbc7767a8
f88adedf5ff03f892286ceefc490418934bbae7e563d444493cf19c67b62bdfbd0c561d5d7ef7f
176febe67856af86c43b3fddfe573f41e8aada7ea16dabd8dbded9ce9736b3a09229a26dcaea46
4106acd7807ba145145001451450070df1abe18d9fc5ff0086bacf862f00ff004b889864233e5c
a39461ee0d7e2ef8b3c2fa8782bc4ba8e85aac0d6fa8584cd0ca8c31c83d47b11823d8d7eedd7c
8ffb6e7ec9adf1574d6f19785adf3e29b18b171691af37d10e78f575e703b8e3ae01f672ac7bcb
ebf3bf85e8ff00cfe479399e0563a8722f896abfaf33f31e8a7cf6f25acf243346d14b1b157471
82a47504532bf5ba75215a0aa53774cfcb2a539d29b84d59a0a28a2b4330a28a2800a28a2800af
bbff00e09c1f021e4bfbbf899ab5b958e256b4d25645eac789251f41f20ff79abe7dfd97ff0066
ad5fe3ff008b5018e4b4f0cd9b86bebf2bf2e3af96beac7d3b57eb8f86fc3ba7f84b41b1d1b4ab
75b4d3eca2586185070aa07f3afcdf3ecce38997d5a8bbc56efbbff247e859265af0f1fac555ef
3d9765ff0004d2a28a2be3cfab0a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28
a280303c7d0fda3c0be228f19dda75c000faf96d5e29fb00ce64fd97fc316e4e4da49716e7f095
8ff5af79f11c5e7f87b548bfbf6b2afe686be78ff827e4dbbe076a36dff3e7e22bfb6c7a6194ff
005aeb8ffbbcfd57ea72cbf8f17e4ff43e98a28a2b90ea0a28a2800a28a2800a28a2800a28a280
0a28a2800a28a2800a28a2803e72fdbfff00e4dab59ffafbb5ff00d182bdbfc03ff222f873fec1
b6dffa296bc43f6fff00f936ad67febeed7ff460af6ff00ffc88be1cff00b06db7fe8a5aeb97fb
bc7fc4ff002472c7fde25e8bf366f514515c87505145140051451400564f8abc2da578dbc3ba86
85add945a86957d1186e2de6195753fc88ea0f6201ad6a29a6d3ba1349ab33e35f06f88f59fd8a
3c730782bc53733ea5f09f559b6e8bad4b963a63b1e2190ff77b0ff22bec68278eea18e6864596
2914323a1cab03c820f715cffc42f87da27c50f09df7877c416697ba75da146461ca9ecca7b11e
b5f31fc2ef881af7eca5e3eb3f853f11aea4bcf06ea2e57c2be299b3b473c5acadd9864633ea3d
457735f5a4e4be35bf9f9faf7fbce24feacd45fc0f6f2f2f4ec7d814522b0750ca432919047434
b5c07705145798fc66fda3bc05f01f4d371e2ad720b6bb642d0e9d11f32ea6ff007631ce33c6e3
c0ee6ae1094df2c55d9329c60b9a4ec8f4ea2b92f857e379be2478134bf12cba64ba447a947f68
82d6720c8b11fb85c0e8c4751dabada969c5b4c69a92ba3e59fda83f624d1fe313dcf887c3663d
17c56c0b4985c43767fdb1d98ff7bf3cd7e707c44f857e29f857ac4ba6f89747b8d3e646da2564
26293dd5fa1fe75fb8b58de29f07689e36d324d3f5ed2edb55b370418ae630d8fa1ea3f0af5305
9962300ff74f4ecf63cdc665d431cbf78b5eeb73f0a28afd3ef1f7fc138fe1e789e696e343bcbd
f0cccfcf971626857e8a7047e66bc675bff825ff008a6394ff006478bf489e3ec6f96588fe4a8d
5f614789a8497ef60d3f2d7fc8f93abc39593fdd4d35e7a7f99f13d15f62dbff00c1313e203ca3
cef13787238fb90f393f80f2abd07c25ff0004bfd3e19124f1278c25b951f7adec2df00ffc0d88
23f2ad67c4b858af722dbf9233870ee264fdf925f7b3f3f6dada5bc9d20b789e799ced48e352cc
c7d001d6beabfd9dff0060bf127c48b8b5d63c6292f87bc3790fe437173723d00fe007d7af5e9d
6beeaf863fb2f7c39f84c239345d02296f9063edd7b89a63ef92300fb815eadd2be5f1d9e62718
9c17bb1ecbf567d260b26c3e11a9bf7a5ddfe88c4f05f82b46f87de1cb3d0b40b08b4ed32d536c
70c4b8fa93ea4f524f5adca28af9d3df0a28a2800a28a2800a28a2800a28a2800a28a2800a28a2
800a28a2800a28a280239e213412467a3a95fcc57cbffb00ca23f057c44b1191f67f1a6a4707ae
18a81ffa0d7d495f2bfec43fe85e22f8d3a6f4fb3f89ccbb7d3cc0c7fa575d3d68d45e9f99cb53
f8d4dfafe47d5145145721d4145145001451450014514500145145001451450014514500145145
007ce5fb7fff00c9b56b3ff5f76bff00a3057b7f807fe445f0e7fd836dbff452d7887edfff00f2
6d5acffd7ddaff00e8c15edfe01ff9117c39ff0060db6ffd14b5d72ff778ff0089fe48e58ffbc4
bd17e6cdea28a2b90ea0a28a2800a28a2800a28a2800ae37e2dfc28f0ffc68f03dff0085fc4968
b736372329263f790483eec887b30f5fa83c135d951551938b528bd51328a92e592d0f93be08fc
57f107c0ff001ac3f07be29ddb4c09dbe1df12cd9097b17f0c7231fe3038e6beb1af3bf8e1f04b
42f8e7e0d9f44d5d3c9b85fde596a118c4b6b28fbaea7af5ed5e29f05bf687d43e156b37df0b3e
34dec7a66bba45bb5c69baf5cb6d8354b2404ee0e7ab80a723a9c1ee0d764a2b1117520bde5baf
d57ea8e48c9d07c937eef47fa3fd0ebbf6d9f11f8f3c1ff06350d6bc0fafd9e8325a02d792cea0
4cf1e3a44c7eeb7d067d08afcabf81be03d5ff00685f8f9a0e8daa4f75a9cfa85e0b8d4ae6edd9
e46853e690b31c9e546dc9eec2bf41f43d3f57fdb97c7d1ebdaa4371a77c19d12e09b0b37ca1d6
2553feb18774c8afa3fc3ff027c15e14f88b71e36d1f44834ed76e2c469f23dba8543182a73b47
01be5519f402bd1a38a581a4e935efb5f7793feb4382ae19e36a2a89fb8bf1f3476fa7d8c3a658
dbd9dba048208d62451d940c0ab14515e01ee05145140051451400514514005145140051451401
e6b77fb44f80f49f1ddd783b57d6e3d135f80802df511e509548c86473f2953ea48af44b5bb82f
add27b69a3b881c652589c32b0f50475af8fbfe0a39fb3b1f895f0f17c69a35b6ff10787d0b4ab
18f9a6b6eac3dcaf515f0a7ecbdf183e2369bf12fc3de1cd0fc78fa0596a3769048faa4fbad517
ae0873d4e3014119240ef5ecd2c0471143dad3959add33c8ab8d961eb7b2a91ba7b347ed95150d
a075b5844b289a4083748a3018e3a8153578c7ae14514500145145001451450014514500145145
001451450015f2c7ec9ea6c3f680fda2b4e3c08f56d3e555ff007a1909fe62bea7af95fe0266c3
f6cbf8f36a78fb52595d63e8a17fad75d1d69d45e5faa396b693a6fcff00467d5145145721d414
5145001451450014514500145145001451450014514500145145007ce5fb7fff00c9b56b3ff5f7
6bff00a3057b7f807fe445f0e7fd836dbff452d7887edfff00f26d5acffd7ddaff00e8c15edfe0
1ff9117c39ff0060db6ffd14b5d72ff778ff0089fe48e58ffbc4bd17e6cdea28a2b90ea0a28a28
00a28a2800a28a2800a28a4660aa59880a06493da8021bcbd834eb49aeaea6482de152f24b21c2
aa8ea49af84fe27f87b52ff8285f8ce7d3b4158b47f873e1633243e2192dc34b7f7a571b632464
440819c75c7ae36f5ff113c61acfed7ff106e7e1bf81ef24b3f87ba54a17c47e2280fcb7041e6d
e26fe2cf4e3f9735f547827c15a37c3cf0bd8787f40b28ec34bb28c4714318fcc93dc9ea4d7a11
7f544a7f6dede5ff0004e092fadb71fb0b7f3ff80780fecb7f19eeb4cb9ff853fe3ab1b7d03c69
a14620b55863115bea102f0af10000ce3b0afa6abc63f68ffd9e2d7e3468d6f7fa65cff6278db4
93e7695ac45f2ba38e42311c95358ffb34fed0d73e3c96ff00c09e37b7fec4f89be1f1e5df58cd
f2fdae31802e22fef29e09c74c83d08a8a915562eb535eabb79fa7e45d393a5254a7f27dfcbd7f
33dfe8a28ae23b028a28a0028a28a0028a28a0028a28a0028a28a008ae6de3bbb79609904914aa
51d1ba3291822bc36cff0062af85769e00d7bc27ff0008fc52d96b176f7b2dcb81e7c529cec31b
f54d9b885038c123b9cfbbd15a42a4e9fc0ec672a709fc4ae7c75e1df88be34fd8ef5ab6f0b7c4
59ae7c4ff0da5711697e2a0a5e6b25fe18e7f503d4ff00f5abeb9d2358b1d7f4cb6d474dba8af6
c6e50490dc42c191d4f420d41e24f0d697e30d12eb48d66c61d474eb94292dbcea19587f9ef5f2
3eabe19f1bfec45ab4fadf85e2bbf18fc1d9a432dfe8a0992eb4704f3245ea83f218e71d4f5fbb
8adb49fe0ffc9fe0ce6f7b0dbeb0fc57f9afc8fb2e8ae5fe1c7c4af0efc58f0ada7887c31a945a
969b72b90f19f990f7561d5587420f35d4570b4e2ecf73b1352575b05145148614514500145145
00145145001451450015f2bfc38ff40fdbff00e235af4fb5f85a1bbc7ae2e235cfeb5f5457caf6
affd9bff00051cbb0385bef02aa7d48b90c7ff004115d787daa2feebfd0e5afbc1ff00797ea7d5
145145721d4145145001451450014514500145145001451450014514500145145007ce5fb7ff00
fc9b56b3ff005f76bffa3057b7f807fe445f0e7fd836dbff00452d7887edff00ff0026d5acff00
d7ddaffe8c15edfe01ff009117c39ff60db6ff00d14b5d72ff00778ff89fe48e58ff00bc4bd17e
6cdea28a2b90ea0a28a2800a28a2800a28a28010900124e00ef5f267c6ef8a9aff00c7af1b5c7c
18f85d72f05bae078a3c4d01f92ce0270d046dfdf6e87f2e99ad5fda23e356b9e29f1647f073e1
6b8b8f175f2e354d523398b4980fde6661d1f1dbb57ae7c0ef829a17c0bf0441a0e8e9e6cec7ce
bed425199af273f7a473d7af41dbf3aee84561e2aa4fe27b2fd5fe8714dbaf274e1f0addfe8bf5
353e157c2ed07e0ff82ec3c33e1eb45b5b1b54f9980f9a57fe2773d4b13c926bafa28ae3949c9d
dee7624a2acb60af07fda5bf6777f89b1d878bfc2573fd83f12fc3f99b4bd5613b4cc07260971f
791b91cf4c9ec483ef145553a92a52e68ee454846a47964789fecdff00b4347f17b4dbad175db6
fec3f1ee8c7c8d574897e56dc3832203d54d7b657cebfb48fecf7a8ebfa95b7c47f87528d2be23
68e3cc409f2a6a28393149ea48e0135d7fece9fb40e9bf1dbc2d348623a5f8a34a716bad68b3fc
b35a4e320e54f3b490707d88ea0d6f529c651f6b4b6eabb3ff002ec634e728cbd954dfa3efff00
07b9eb745145721d4145145001451450014514500145145001451450014d74595191d43230c152
3208a751401f267c45f803e26f817e2bbbf88df0442c4931f3758f071ff8f5bd5eacd1af456fa7
e18af63f815fb417873e3b68525c698cd61acda1f2f50d1aefe5b8b493b82a79233debd42be76f
8e7fb2ecbafeba9e3ff8697e3c25f11ecff78b2c5f2db6a20758a751c73fdefcfd476aa91aeb96
b3b3e8ff00cffcfa1c6e9ca8be6a4aebaaff002ff23e89a2bc0be007ed3f0fc41d4e7f0578cec5
bc25f12b4ef92eb48bbf905c63fe5a424fde53d78fe55efb5cd529ca94b9648e88548d48f34428
a28accd028a28a0028a28a0028a28a002be57f181fb07fc1427c07274fb7f86ef20faec567afaa
2be57f8d44699fb737c03bb3f2add5aeb101f7c5b103f5615d786d6525fdd97e4ce4c4e918bfef
47f347d5145145721d6145145001451450014514500145145001451450014514500145145007ce
5fb7ff00fc9b56b3ff005f76bffa3057b7f807fe445f0e7fd836dbff00452d7887edff00ff0026
d5acff00d7ddaffe8c15edfe01ff009117c39ff60db6ff00d14b5d72ff00778ff89fe48e58ff00
bc4bd17e6cdea28a2b90ea0a28a2800a28a2800af9dff695fda0751f0e5fd9fc36f87718d53e25
eb836441394d3213c35c4a7b103a03f5f40757f696fda18fc29b3b1f0e786ad7fb73e216bade46
95a545f330278f35c0e8a29ffb357ecf1ff0a974fbdf10788ee46b9f1135d6fb46afaac8771527
9f2633d917dbafd00aeca708d38fb6a8bd177ff81f99c95272a92f654dfabedff07f2357f676fd
9ff4cf815e1578848753f12ea27cfd5b589b996ea63c9e4f3b41e82bd6e8a2b9a7395493949eac
e884234e2a31d905145150585145140057cc9fb457c0bd6f45f1545f18fe15e2cbc75a6a7fc4c7
4f4188b59b518dd1c8bddf0060fb0ee148fa6e8ad695595297347fe1ccaa538d58f2bff863cd7e
047c74d0fe3af83e3d574d26d75187f75a869731c4d6930e19587a67a1af4aaf953e3afc1cd7be
1478c64f8c5f0a6dcb6a11fcfaf787a1188f518472cc8a3f8f1938af72f837f183c3ff001bfc0d
67e26f0f5c896097e49edd8fef6da61f7a3907661fa820f435ad5a6aded69fc2ff0007d9fe8674
aa3bfb3a9f12fc7cff00ccee68a28ae53a428a28a0028a28a0028a28a0028a28a0028a28a0028a
28a00f20f8ff00fb37e83f1cf4c82e1d9f46f15e9ffbcd335eb3f92e2ddc7206e1c95cf635e73f
0abf690f107c3df15dbfc34f8db1ae9daf1222d2fc4c062d3545e8bb9ba2bfafebea7ea5ae2fe2
bfc22f0c7c67f0acfa0f89f4f4bcb6704c530e26b77ecf1b75522bae9d64e3eceaeb1fc57a7f91
cb3a4d4bda52d25f83f5ff0033b24659103290ca46410720d3abe38d03e22f8cbf636d76d7c31f
1226b8f11fc349e410e97e2d542ef6609f963b8ee31d33fcebebcd2756b3d774db6d434eba8af6
c6e6312c371038749148e0823822b3ab45d3b3dd3d9ff5f91a53aaaa5d6cd6e8b745145606c145
145001451450015f2afed47fe83fb4bfecf1a974dba9dddae7feba46a31fa57d555f2a7edaa0d9
78f3e016a207dcf1b59db6effae871fd2baf09fc54bc9fe4ce4c57f09bf35f9a3eaba28a2b90eb
0a28a2800a28a2800a28ac6f1759ea7a8787aeedf46b9167a93ecf2a6271b70ea5bb1fe1047e34
01b345145001451450014514500145145007ce5fb7ff00fc9b56b3ff005f76bffa3057b7f807fe
445f0e7fd836dbff00452d7887edff00ff0026d5acff00d7ddaffe8c15edfe01ff009117c39ff6
0db6ff00d14b5d72ff00778ff89fe48e58ff00bc4bd17e6cdea28a2b90ea0a28a2800af25fda27
f680d3be06785a39121fed6f14ea4df67d1f4587996e663c0240e420ea4fe1f4d4f8ebf1bb43f8
11e079f5ed61fcc9dcf9565611f32ddcc7eea20eff00d2bca3f676f81dae7887c4f2fc61f8ab1f
9fe33d4973a669320cc7a3db1e55403ff2d08ebe9f5381d74a9c547dad5f87f37dbfcd9cb56a49
cbd953f8bf25dffc8d5fd9a3e00ea3e1bd42f3e247c40986aff1275c5df34d20cad8447a4317f7
401c1c57d1145158d4a92ab2e691b53a71a71e58851451591a0514514005145140051451400840
60411907820d7c8bf17be1bebffb33f8f6ebe2ff00c33b57b9d02f181f15f8561cf973a6726e63
51c075c9271ea4f76cfd774c96249e278e445923705591c64303d411e95b52aae93ee9eebb98d5
a6aa2ecd6cfb1cc7c34f897a0fc59f0858f88fc3b78b776174a0f1f7e36ee8c3b115d557c71f10
3c21ad7ec6fe39b9f887e0ab49b50f86ba8ca1bc41a04193f6124f33c43fbbdcfa57d59e0cf196
91f103c31a7788741bd8f50d2afe212c13c47208f43e841c823b106aead251b4e1ac5ff567e64d
2aae5ee4f492feaebc8dba28a2b98e80a28a2800a28a2800a28a2800a28a2800a28a2800a28a28
0337c47e1bd33c5da2dde91acd943a8e9b77198a6b6b840c8ea7b106be47bef0cf8dbf620d5a6d
53c2b15df8c3e0e4f2992f7422c64b9d1f2799213d4a0ee3f3ec47d954c9a18ee2178a54592275
2ac8e32181ea08ee2ba295674ef16af17bafebaf99854a4aa7bcb492d9ff005d0e67e1c7c4bf0e
fc57f0bdaebfe1ad463d42c275ce50fcd19eeac3b115d4d7c9bf11ff0067ff00147c10f13dd7c4
5f827f7646f3757f07b1fdc5e2f56688766f6af61f80ff00b41f86fe3d787e4bad2a46b3d62ccf
95a968d75f25cd9cbd08653ce320e0f4fc41aaa94572fb4a7ac7f15ebfe64c2abe6f6753497e0f
d3fc8f51a28a2b94e90a28a2800af963f6fc5fb3f877e14ea238363e3cd3262de80799fd48afa9
ebe5dff82892f93f02ac2fff00e7c35fb0b9cfa625c7fecd5d984fe3c3d4e4c57f025e87d3d6ed
be08dbd541fd2a4aada6b6fd3ad5bd6243fa0ab35c675851451400514514005145140051451400
514514005145140051451401f397edff00ff0026d5acff00d7ddaffe8c15edfe01ff009117c39f
f60db6ff00d14b5e21fb7fff00c9b56b3ff5f76bff00a3057b7f807fe445f0e7fd836dbff452d7
5cbfdde3fe27f923963fef12f45f9b37a8a28ae43a82b90f8adf14b41f83be0abff12f886e96de
ced97e48c1f9e790fdd8d077626b47c71e36d1be1d785eff00c41afdec761a5d9466496694e071
d87a93e95f2cfc34f05eb9fb5f78fadbe2878ead25b0f87ba6ca4f85fc3738c7da483ff1f532f7
ce38ff000193d34a92927527a457e3e48e6ab55c5a843593fc3cd9a5f043e176bff1d3c7707c65
f8a16c6258fe6f0d787651fbbb18b3959594ff0019ebcd7d654d44589151142a28c0503000a754
55aaeacafb2e8bb22e95354a36ebd5f76145145626c14514500145145001451450014514500145
1450043796706a16935b5cc493dbcc85248dc65594f04115f1b6b1a66b3fb0a78ee6d7347827d4
fe09ebb739d474d8fe66d16e18ff00ad8c7643dc74edd971f67d52d6746b1f10e9577a66a56b15
ed85d46629ede65dc9229ea08ae8a357d9b69abc5eebfaebd8c2ad2f68934ed25b3feba11f87bc
43a778af45b4d5b49bb8efb4fbb8c4b0cf136e56522b46be30b6b9d5ff00614f1d25a5dbdc6a5f
0535ab9db05c9cbb68b331fbadfec67bff00faabec7d3f50b6d56c2def6ce78eead2e2359629e2
60c8e84643023a8228ab4bd9da51778bd9ff005d42955e7ba92b496ebfae858a28a2b9cdc28a28
a0028a28a0028a28a0028a28a0028a28a0028a28a002be75f8effb2fcdaff8863f889f0d350ff8
447e25d90dcb7307cb0ea2a3ac53af46040c648fae40c57d15456b4ea4a94b9a267529c6aae591
e07f017f69f8be206a52f83bc69a79f097c45b1f92e74cb8f952e08eaf093d41eb8fe75ef95e43
f1eff66fd07e37e9f15c991f44f15597cfa7ebb67f2cd038e9923ef2fb579afc27fda3b5ef873e
2eb6f861f1b635d2b5e73e5e91e233c59eaaa0e00dfd15cf1c1ee71c1201e89538d64e7477eabf
cbbafc51cf1a92a4f92aedd1ff009f9fe67d514520219410720f208a5ae23b02be6bff00828a59
9b9fd92fc6120ceeb796ca418ffafb857fad7d295cafc4ff0086da37c5df02ea9e12f102ccda46
a2a8b38b77d8ff002bab8c1c1c7cca3b56f426a9558cdec9a6635a0ea52941754cd5f0add8bff0
ce95723a4b6b1b0fc5456ad52d17488341d22cf4db62e6ded225863f30e5b6a8c0c9f5abb58bdf
4355b6a145145218514514005145140051451400515f28fc7cff00828f7c32f827e23b8f0c59c7
a878e3c51012b3e9de1f884de437f764724283ea01247a578c37fc15aef4b1d9f063c41b3b6e95
41c7bd652ab4e0ed2925f32255211d24ec7e8ad15f9d3ff0f6bbff00fa231af7fdfd5a3fe1ed77
ff00f44635effbfab51f58a3fcebef447b6a7fccbef3f45a8afce9ff0087b5dfff00d118d7bfef
ead1ff000f6bbfff00a231af7fdfd5a3eb147f9d7de83db53fe65f79f677ed03f08cfc70f8697b
e141a80d2cdc4d14bf6931efc6c6ce31ef5dce81a67f62685a6e9dbfcdfb25b476fbf18ddb142e
7f4afcf8ff0087b5dfff00d118d7bfefead1ff000f6bbfff00a231af7fdfd5abfad527150e756f
544f3d1e6e6e657f53f45a8afce9ff0087b5dfff00d118d7bfefead1ff000f6bbfff00a231af7f
dfd5a8fac51fe75f7a2bdb53fe65f79f547c68fd9de7f8e1e3ef0dcfafeb6efe05d2ff007f3787
635da2eae01f94bb03cafb57b4dadac3636d15b5bc4905bc28238e28d42aa28180001d0015f9dd
ff000f6bbfff00a231af7fdfd5a3fe1ed77fff0044635eff00bfab5a4b194e515173565e6888ca
8c5b9292bbf33f45a8afce9ff87b5dff00fd118d7bfefead2c7ff056bbc0e0cbf067c4023fe2d9
22938f6159fd628ff3afbd1a7b6a7fccbef3f4568af967f67dff0082897c32f8efe2187c3320bf
f06f8ae63b61d275f8842d3b7a46e09527d17393e95f5356e9a6ae8d13bea828a28a630a28a280
0a28af27fda07f69ff0087dfb34787e1d4bc6bacada4d724ad9e9b0032ddddb0ea238c7240c8cb
1e06464f22803d628afcf1beff0082b8c33cecda3fc1ff00145cd913f24b75b23661d8e01355ff
00e1ed77ff00f44635effbfab583af4568e6bef465ed69afb4bef3f45a8afce9ff0087b5dfff00
d118d7bfefead1ff000f6bbfff00a231af7fdfd5a5f58a3fcebef42f6d4ff997de7e8b515f9d3f
f0f6bbff00fa231af7fdfd5a3fe1ed77ff00f44635effbfab47d628ff3afbd07b6a7fccbef3eff
00f1678534af1c7876fb43d6ece2bfd32f62314d04ca195948af3afd9d7e0c6aff0003345d6bc3
d3f8925d73c362f0c9a25aceb992c20232d197272c371e076c7a935f22ff00c3daefff00e88c6b
dff7f568ff0087b5dfff00d118d7bfefead68b194d45c39d59f9a21ca8b929f32baf33f45a8afc
e9ff0087b5dfff00d118d7bfefead1ff000f6bbfff00a231af7fdfd5acfeb147f9d7de8bf6d4ff
00997de7e8b515f9d3ff000f6bbfff00a231af7fdfd5a3fe1ed77fff0044635eff00bfab47d628
ff003afbd07b6a7fccbef3f45a8afce9ff0087b5dfff00d118d7bfefead74be0bff82b6781aeb5
6b7b2f1cf83bc47e06827608352bab712daa13fde284b0faedc7ad546b5293b4649bf52954849d
9491f78d159de1ef11699e2dd12cf58d1afedf53d2ef23135bdddac8248e542320ab0e08ad1ad8
d028a28a0028a28a0028ac9f14f8ab48f04f87efb5cd7b51b7d2b49b28ccb7177752048e351d49
26be21f17ffc15b7c190ea73daf81fc11e24f1adac2c57fb4e0b710db391fdd2c437e6054ca518
2bc9d897251576cfbd28afce9ff87b5dff00fd118d7bfefead1ff0f6bbff00fa231af7fdfd5ac7
eb147f9d7de8cfdb53fe65f79fa2d5c5fc58f845e18f8d5e10b9f0ef8a74e8efaca5198e42312d
bc98e248dbaab0f51ee0f04d7c3bff000f6bbfff00a231af7fdfd5a3fe1ed77fff0044635eff00
bfab551c5528b528cd27ea852a94a4b9652563ec4fd9fbe1a78a3e147852e7c3fe22f1549e2ab4
b6b865d2e6b84c4d15b7f0a3b75623d7f0af52afce9ff87b5dff00fd118d7bfefead1ff0f6bbff
00fa231af7fdfd5a73c5529c9c9cd5df9a14274a1151525f79fa2d457e74ff00c3daefff00e88c
6bdff7f568ff0087b5dfff00d118d7bfefead47d628ff3afbd15eda9ff0032fbcfd16a2bf3a7fe
1ed77fff0044635eff00bfab47fc3daeff00fe88c6bdff007f568fac51fe75f7a0f6d4ff00997d
e7e8b515f9d3ff000f6bbfff00a231af7fdfd5a3fe1ed77fff0044635eff00bfab47d628ff003a
fbd07b6a7fccbef3f45a8afcf2b0ff0082b95bc13ab6b7f087c5169620fcf35a8494a0f520915f
5e7c03fda4fc05fb497869f58f04eb297de410b77652031dcdab1e8248cf23a1c1e870706b58ce
13f81dcd2328cbe1773d468a28ab282be6aff8284fc71d47e047ecdbaa6a3a2cad6faeeb777168
5a7dc29c18a5995d8b83d8848e4c1ec707b57d2b5f097fc1613fe4df7c01ff0063f69fff00a497
b532768b6293b26cf847c17e15b6f0be928883ccbc9bf7b7372fcc9348792cc7a9e4d741488308
3e94b5f954e72a927393bb67c14a4e727296ec28a28acc90a28a2800a28a2800a28a2800a28a28
00a28a28039cf1b785a1f11e96cea4c1a8db7efad2ee3e248645e4107ea2bf57bf614f8d37ff00
1dff00669f0c78875990cdaedb799a66a32b1c992685b6ef27b9642849f526bf302e3fe3de5ff7
4ff2afbabfe0925ff26b9a8ffd8d17ff00fa0435f639154938ce0de8ac7d16553935283d91f6ad
14515f547bc1451450056d46f534dd3eeaee4e52089a561eca093fcabf0df5ef19de7ed01f173c
53f13fc4129be96e2f64b4d22290e52d2ce36223080f03209271dcb1ee6bf6dfc6bff226ebdff5
e13ffe8b6afc20f81873f0db4d27aee93ff4335e16735254f0d68bb5dd8f2f319ca143ddeacefa
8a28af813e4c28a28a0028a28a0028a28a0028a28a0028a28a002a1bbb38350b692dee6249e091
76bc6e32ac3d08a9a8a69db541b1f44ffc12e7e266a1e0ff00893e29f83d737325c682f07f6b68
f1c8c5bece49cca8b9e8bdfeb5fa655f91dfb071c7edd9a77bf876eff90afd71afd3705525570f
09cb768fb7c34dce8c652dec145145769d2145145007e607fc14f3e24dff008f3e31f87fe11457
3243e1cd36d5755d56046205ccadcc6ad8eaa171c1ef9af9fad6d61b2b78e082248618c0548d06
028f402bd1bf6ddff93f2f157fd816c7ff0044ad79f57c26755252c4f237a247cae65393adcaf6
41451457cf9e485145140051451400514514005145140051451400551f04f8faf3f671f8dde12f
891a1486d2ddefe2d3f5db68ce23bbb39582c9b97a1207233fc414f6abd5c27c68e7c14dff005f
76ff00fa356bd2cbaa4a9e2a1caf776fbcedc1ce50af1b75763f773c17e28b6f1bf83b41f11598
2b69abd841a8421ba849635917f4615b55e69fb327fc9b6fc28ffb14b49ffd238abd2ebf493ecc
2be12ff82c27fc9bef803fec7ed3ff00f492f6beedaf84bfe0b09ff26fbe00ff00b1fb4fff00d2
4bda89fc0fd0997c2cf8c17ee8fa52d22fdd1f4a5afc9cf811f04125d4c90c31b4b2b9daa8832c
c7d00af409bf67af88f068e3547f07ea6b62577799e58271feee73fa57a97ec25e13b0d77e26ea
baadf40972da269ed7704720c8df9c038f6eb59abfb6dfc49b7f1c49ac1d484da679cc468ce804
3e5e785ce320e3bfad7a54e8518d28d4af26b99bb5bcbab3b614a92a6a755bd76b791e33e16f03
6bfe35f102e85a26973dfeae4330b34015f0a32dc123a0acbd4f4db9d1b52bbd3ef616b7bcb599
e09e16ea92292aca7dc10457d43fb2e78ea5f891fb5d43e219ec2db4d9af2d6e99aded17080f94
79fa9af03f8bff00f256bc6dff0061bbdffd1ef5954a108d15562ef7935f256339d28aa6a69f56
8a83e1d7891bc127c5e3499ffe11a12f90751f97cbdfbb6edeb9ce78e95d0785ff0067bf88be34
d06d75ad13c297ba8e977418c373114dae158a9c6581e0a91f857b6c5ff28f19bfec37ff00b702
bd8fe11f867c69e2bfd8fbc0967e05f1143e19d65679a57bc9c90ad089ee43270adc9250f4fe1a
f428e021526a2eefdc52d2d7bdf63ae9e1633925afc37d0f8b7c55f003e2178274a3a9eb9e16bc
d36c0489119e529b77b9daa3863d49c562f8e7e18f8a7e1a5c5b41e27d16e74696e54bc2b7007c
e01c1c104f4afa2bf684f0cfc5ef01e8fa041e38f1ec1e25d1f53d4a2885a5b9270e843866cc6b
e9d8d7b67ed5ba4d8fc59bfd4be1f88917c4ba6e8d1f8874793f8a7fde4a93c23eaa8840ee7e94
3c0424aa28dd38dac9db56efdbc9680f0916a76ba6ada3b75bff0048f82355f869e27d0f40d1f5
bbed1e7b6d2b58216c2e9caedb824646de73d3d6bb2ff8652f8b5ff423ea3f9c7ffc557af7ed10
66b0fd947e0a9198a784afd558447fa8aec3f656f8d1e36f1bfc3ff8bd7daef88aeb52bbd234a4
9ec65942e607315c92cb803ba21e7d2953c1d075fd8cdbd526ad6ed77ff0050c3d2f6bece4dec9
f4ed767c7fe39f869e27f869776b6be27d1ee347b8ba432431dc15cba83824609ef5ccd74de39f
897e27f897776b75e27d62e358b8b5431c325c05ca293920600ef5ccd78f539399fb3bdbcf73cf
9f2f33e4dbcc8ee3fe3de5ff0074ff002afbabfe0925ff0026b9a8ff00d8d17fff00a0435f0adc
7fc7bcbfee9fe55f757fc124bfe4d7351ffb1a2fff00f4086bea321dea7cbf53dccab79fc8fb56
8a28afaf3e8428a28a00c5f1affc89baf7fd784fff00a2dabf083e05ff00c935d33fde93ff0043
35fbbfe35ff91375effaf09fff0045b57e107c0bff00926ba67fbd27fe866be7b3cff765ebfa33
c7cd3f82bd4efa8a28af853e5ceabc19f0afc5bf10f79f0e68179ab2a70cf027ca0ffbc702a9f8
b3c05e22f025d8b6d7f47bbd2a63d05c46406fa1e87f3afaebf684f88dacfecdfe06f02783bc0f
32e8c2e34f175717b0a03248dd0f27b93c935e1be3ff00da93c4bf13be1ac1e14f1159d9ea1345
3097fb5a45fdff001d318e01ea09ee0f4af52b61f0f453a7293e74bb697eddceea946952bc1c9f
32fbbd0f3cd77e1d7893c35e1cd275fd53499ecf47d546eb2bb936ec9c6377cb839e9cf34df047
c3ff0010fc48d5a5d33c35a54dabdfc509b87820c6e1186552dc91c65947e35f47fed21ff269ff
0004bfeb82ff00e88154ff00e09d9ff25b758ffb004fff00a516f4fea90fad4285dd9dbf1571fd
5e3ede34afa3b7e28f04f05fc2ef157c45d42f6cbc37a2dc6ad7764bbae2280ae6319c73923bf1
5d7ffc3297c5affa11f51fce3ffe2abdc3f6078e69be207c498ede4115c3d96d8e43fc2c656c1f
c0d75de26f863fb45785fc37ab6b371f16aca6834eb496f248e266decb1a1720661c64815d3470
14e741556a4ef7dada5bd4da9e1612a4aa34defb5ba7a9f1ac7f0a3c5d2f83e6f15268574fe1f8
5de392fd76945656dac0f39e08c74aafe16f871e25f1a697ac6a3a26913ea363a3c5e75fcf16dc
5ba6d66dcd923b239e3d2bed5f81be2fd3bc37fb2069971afc4b73a56a5ac4b617a5c670934eca
cd8f519cd67fc18f87171f0afc39fb46e81365e08f49596d27ea26b76b7bc31b83df8e3ea0d28e
5f093a6d37692bbf2766d7df605838be4b3d1abbf2d2e7ca9e10f80bf103c7ba245ac787fc2f79
aa6992b3225cc2536b153861cb03c1a97c53fb3e7c44f0568375ad6b9e14bdd3b4bb50a66b994a
6d4dcc14670c4f2cc07e35dd7eca9f173c61a57c4af05f846d35eb983c373ea4164d3942f96c1c
92c3a6793ef5abfb617c5df183fc56f1af831b5eb93e17f3604feccc2f97811c5201d33f7fe6eb
5cea8e1beadedaf2bedd2d7b5fee30f6747d87b4d6fb74dedf91f36d14515e51c27a57ec1dff00
27d9a77fd8bb77fc857eb8d7e477ec1dff0027d9a77fd8bb77fc857eb8d7e95977fba53f43ed30
7feef0f40a28a2bd13b028a28a00fc85fdb77fe4fcbc55ff00605b1ffd12b5e7d5e83fb6effc9f
978abfec0b63ff00a256bcfabe0339ff007b7e88f92cc7fde1fa20ad0d0fc3fa9789b528b4fd2a
ca7d42f6538486dd0b31acfafaf3f66cba8fe157eccbe3ff0089b616d14fe218ae16c6de495771
886e8d723db33027d768af3b0d45579f2c9d924dbf4471d0a6aacecdd92d5fc8f9f3c4ff00037c
7be0db0fb6eb3e15d42c6d71932b461801ea76938fc6b2bc33f0e7c49e32d2758d5345d227d42c
3478bcebf9e2dbb6dd36b36e6c91d918f1e95eb5e18fdb57e21692ba945ad5c43e28b4bd89a3fb
3dfa80b193dc60723d8fe75de7ec9573f6cf837fb415c79690f9ba5349e5c630ab9b7bb381ec2b
aa9d0c3d7ab185393b34f7df457f43a214a8d59a8c1bebf823e49b5b696f2e62b7850c934ae234
41d5989c01f9d74baffc2ff157857c5763e19d5b45b8b1d76f8c42dac642bbe4323ec4c60e3960
475accf087fc8d9a2ffd7ec1ff00a316beb6fda7ff00e4f67e1cff00d74d23ff004b1ab1a3878d
4a4e6decd2fbcca9d2538393e8d2fbcf0bff008652f8b5ff00423ea3f9c7ff00c556427c00f885
2f8ae4f0d2f85af0ebb1da0bf6b10537880b6c127dec63771d6befaf8bbf0cfe33f897c73777fe
0df88967e1ed01e38d61b098b6e4608039e226ead93d7bd79a7eccbff095db7ed63e33d33c67ae
0f10eb7a66806d1ef93eeb279d6eea17e55e06f3d47ad7ad3cb6946ac69da4aeed776b1e84b050
8cd42d2d5dafa1f1458783b5ad4fc531f86edb4e9a5d7249cdb2d8e0090c83aaf3df835b9a67c1
7f1b6b3e2fd47c2d65e1dbab8f1069d1f9b7560a577c4bf2f279c7f1af7ef5f50da68769e35f8d
df0bfe2be8702c769ac6a42df548231c5bde2860d9f4dd8ce7b9cd7957ed03f10fc47f0dbf69ff
001eea3e19d5a6d1ef66912de49a0db968cc51315e41e32aa7f0ae09e129d287b49b6d735b4eaa
d74ce49508538f3c9bb5eda76b5ce5bfe194be2d7fd08fa8fe71ff00f155e5d7f633e997d71677
51986e6de468658dbaa3a92181fa106bedef8fdf1a3c6de16fd9ff00e116b9a5788aeacb56d5ad
164beba8c2ee9dbc946cb6463a9278f5af886fefa7d4efae2f2ea4335cdc48d34b237577624b13
f524d658ca3468494295efa3d6dd55c8c4d3a749a8c2ff003f320ae13e347fc892dff5f76fff00
a356bbbae13e347fc892dff5f76fff00a356b3c17fbcd3f55f99185fe3c3d51fb57fb327fc9b6f
c28ffb14b49ffd238abd2ebcd3f664ff00936df851ff00629693ff00a47157a5d7e9c7db857c25
ff000584ff00937df007fd8fda7ffe925ed7ddb5f097fc1613fe4df7c01ff63f69ff00fa497b51
3f81fa132f859f182fdd1f4a5a45fba3e94b5f939f027a9fece7f193fe14afc418f56b881aeb4a
b98cdb5ec0bd5a33dc7b8eb5ee4743fd986db5e7f17bebf777914921b9ff0084759772063ced29
b738c9fba5b1f857c754577d1c5ca94391c5492d55fa1d54f10e11e5714d2dafd0fa4be077c4ff
0003687fb519f1343041e0ff00097937290a4858aa66321738ce093d8715d8f89be177ece5e28f
126adacdc7c59bc8ae351bb96f248e22bb15a472e40cc39c0278cd7c79455c31b68724e0a4aede
b7ebe8ca8e26d1e59453d6e7d2977f103c2b07ec6b7be0cb7d6a1975d5d69a58ac8e7cc7844f90
fd31f7466bbcf057883e1378f7f65bf07f817c63e391e1ebbd3ee24bb963b6c8951c4d3ed53946
182b2e7f2af8be8a218e94657714d72f2db5d871c538bbb8a7a5be47d13f123e1cfc16f08f87e2
d53c21f112ef5fd6a1bc836d94e54a98fcc1bdb8894f0327ad6dfed31f1d74b6fda3bc2fe36f05
6af16ab0e99a6c11b4d6fb8296134e5e33903aa381ff0002af96e8a9962dd9c69c546f67a5fa5f
fcc9788766a114af6dbc8fae7f6c5f8bfe09f88ff0cfc1967e15d4eda69edae5a69ac2152a6dd4
c58c118c7538e2b94fd95be22f86fc11f0ff00e2f58ebbab41a6ddeafa52416314dbb370e22b90
55700f774ebeb5f38d14e58d9cb11f58695ed6f2dac378993abedadaff00c0b0514515e71c6477
1ff1ef2ffba7f957dd5ff0492ff935cd47fec68bff00fd021af856e3fe3de5ff0074ff002afbab
fe0925ff0026b9a8ff00d8d17fff00a0435f5990ef53e5fa9efe55bcfe47dab451457d79f42145
1450062f8d7fe44dd7bfebc27ffd16d5f841f02ffe49ae99fef49ffa19afddff001aff00c89baf
7fd784ff00fa2dabf083e05ffc935d33fde93ff4335f3d9e7fbb2f5fd19e3e69fc15ea77d45145
7c29f2e7d79a67c4ef857fb40fc3ed0b46f89ba8dcf873c41a2c4218f5387a4aa063ae08e7d08a
e1fe36eb1f05f44f015b785fc03a6b6b3acacdbe4f10ce0870bdfe6e376700608c0e78c9af9ee8
af4678d95483528abb56bdb5febccec9625ca367157dafd4fb6ffb53e0dfc56f80ff000efc37e2
cf1fff0061de6876719921b5e1d64f2c2b2b6e8d871ed49f06aebe0b7c05f8b76fa9685f108ea5
a75ee8b796f75717dcac3209ed5a251b635e58094f7fb9dabe25a2b65983528cfd9ae656d75e9f
334fadbba9722bab6baf43e9ff00d8f3e22f84fc17e30f1e3f89f5c8347b2d52d0c10cf2eef9f3
23676e01e7073cd69ffc294fd9b88ff92bda8ffdf49ffc62be4da2b286312a71a73a6a495ed7bf
5f999c71368284a09dbbdfa9f49dff00c43f0bc7fb188f0741acc3278823d65a65b1f9bcc3179e
c43f4c7ddc1eb5e97f0bbf695f0b6a3fb38788f46f12eab6f61e2c4d1ae34a88cca7ccbd8c4320
80640ec642b83fd6be21a29c31f529c94925f0f2fcbfcc71c5ce0ee974b1df7c03d7b4ff000b7c
66f086adaadd25969d69a8472cf712676c6a3a938ad1fda67c4fa5f8cbe39f8af59d16f63d434c
ba9a2686e62ced70218d491900f5047e15e6145727b67ec7d8f4bdff000b1cfed1fb3f67d2f70a
28a2b9cc8f4afd83bfe4fb34effb176eff0090afd71afc8efd83bfe4fb34effb176eff0090afd7
1afd2b2eff0074a7e87da60ffdde1e81451457a276051451401f90bfb6effc9f978abfec0b63ff
00a256bcfabd07f6ddff0093f2f157fd816c7ff44ad79f57c0673fef6fd11f2598ff00bc3f4415
f427ecd7f1bbc39e16f0ef887c03e3bb7927f08eba32d2c40936f274ce07638539ea0a835f3dd1
5e551ad2a13e789c34ea4a94b9a27d6ed65fb35fc30d3352bdb6beb8f1f5edc42c96f6772372c4
4f4e76aedff7b9354bf647f1ff0081b45f0bfc52d17c57adc3e18b4f11451db42a4b1658992e11
f61c372a241d7dbad7cab4575c71ae152338c12b5f4b77efd4e858a719a946295aff0089f516b7
f0bbe01f8634e6d5b42f89d79a96af6724735bda4a576c8c1d4e0e210718cf714ef8ff00f143c2
be2afdabbc0fe26d275ab7bdd0ac5f4d3737d186d9188ee99df3919e1483d2be5ba294b1978f2c
20a2ae9e97e9f313c4e9cb18a5b3fb8fb97e2e689fb3f7c61f1c5df8a353f8a93d95e5cc71c6d0
d99023011028c6e889e83d6b07e046bbf0abe05fc7ed5a4d2fc6c2fbc3171e1dd8ba9df739b96b
88c9886d41d1533d3d79af8e28ad5e61fbc555538a95ef7d7fccd1e2fdff0068a0af7bf5ff0033
e96fd913e39e91f0efc61a8e93e26ba8e1f0ddecc6ee29e704a5bdc2e76b800771c66bcd7f694f
12e99e30f8e1e2bd6346bc8eff004cbbb84782e62ced70224048c8f5047e15e674572cb1539d05
41ec9dce795794a92a4f64ee7d1bf1fbe22786fc53fb3ffc22d0f4ad5a0bdd5b48b458efad63dd
ba06f25170d918ea08e3d2be72a28acab5675e7cf2ec97dcac454a8eacb99ff560ae13e347fc89
2dff005f76ff00fa356bbbae13e347fc892dff005f76ff00fa356b6c17fbcd3f55f99a617f8f0f
547ed5fecc9ff26dbf0a3fec52d27ff48e2af4baf34fd993fe4db7e147fd8a5a4ffe91c55e975f
a71f6e15f0affc160a177fd9dbc112aa168edfc75612cac070882d6f064fb6481f8d7dd55e69fb
467c13d3bf685f83de20f046a2c21fb7c39b6b92326dee1798dff03c1f626a64b993426aeac7e4
6c6c1e3561c820114eae77c4f17887e017881fc19f13f4cb9d0f53b5252df5092326daf6307024
49070411508f8a1e14c7fc87ec7feff0afcd2b60abd19b8383fb8f8aa986ab4e4e2e2cea28ae5f
fe167f853fe83f61ff007f968ff859fe14ff00a0fd87fdfe5ac7eaf5bf91fdcccbd8d4fe57f71d
4515cbff00c2cff0a7fd07ec3feff2d1ff000b3fc29ff41fb0ff00bfcb47d5eb7f23fb987b1a9f
cafee3a8a2b97ff859fe14ff00a0fd87fdfe5a3fe167f853fe83f61ff7f968fabd6fe47f730f63
53f95fdc7514572fff000b3fc29ff41fb0ff00bfcb47fc2cff000a7fd07ec3feff002d1f57adfc
8fee61ec6a7f2bfb8ea28ae5ff00e167f853fe83f61ff7f968ff00859fe14ffa0fd87fdfe5a3ea
f5bf91fdcc3d8d4fe57f71d4515cbffc2cff000a7fd07ec3feff002d07e2878500ff0090fd8ffd
fe147d5eb7f23fb987b1a9fcafee3a3ba216da5278010f3f857dddff00049681e2fd95ae656522
3b8f125fcb137665c44323f153f957e7bf84b4cf12fed19e214f067c31d36e355b9b9223bcd5c4
6cb6b6311fbceee46071d3d7b57ecdfc06f843a6fc07f847e1af02e94de65b6916c2379b18334a
496924ff00813b31f61815f6193616a5084a7515af63e8b2da13a5194a6ad73bfa28a2be8cf642
8a28a00c7f18a34be11d7114659ac67007bf96d5f841f04e26b6f005adb4836cd6f34d0c8bfdd6
0e722bf7d648d658d91c065604107b8afc7ffdadff00671f127ecb3f1335ff001569ba4dd6adf0
abc4176d7ed75651990e9370e72e9201f75493907a7207515e4669879e270fcb4d5da773cec751
956a3686eb5386a2b93b7f8ade13b8895c6bb6880ff0c8fb187d41e6a4ff00859fe14ffa0fd87f
dfe5af83fabd65f61fdccf96f6353f95fdc7514572ff00f0b3fc29ff0041fb0ffbfcb47fc2cff0
a7fd07ec3feff2d1f57adfc8fee62f6353f95fdc7514572fff000b3fc29ff41fb0ff00bfcb47fc
2cff000a7fd07ec3feff002d1f57adfc8fee61ec6a7f2bfb8ea28ae5ff00e167f853fe83f61ff7
f968ff00859fe14ffa0fd87fdfe5a3eaf5bf91fdcc3d8d4fe57f71d4515cbffc2cff000a7fd07e
c3feff002d1ff0b3fc29ff0041fb0ffbfcb47d5eb7f23fb987b1a9fcafee3a8a2b97ff00859fe1
4ffa0fd87fdfe5a3fe167f853fe83f61ff007f968fabd6fe47f730f6353f95fdc7514572ff00f0
b3fc29ff0041fb0ffbfcb552ebe2ae8d2cd0d968ad2f88b57b96115ae9fa646d3493487a28da0d
5470b5e6f9541fdc52a1564eca2fee3e81fd81addee7f6e68258c6e4b5f0f5c0948fe1dc06dafd
6daf8c7fe09dff00b2a6bbf07748d67c7be3bb716be36f132a8362793616c3958cfa37723b74af
b3abf47c2d27428429cb748fb2a14dd2a5183e8828a28aea370a28a2803f223f6e385edff6eff1
13c8a556e344b23113fc4044a0e3f1af3bafb83fe0a29fb2aebff1421d1fe25780ad3edde2ff00
0f44d0dc69a9f7efad7392abeac39e3a9afcecb3f8afa16f96db5599f42d4e06f2ee2c752430c9
138eaa4301cd7c667184ab2adeda11ba6ba1f3798e1ea3a9ed22ae99d9d15cbffc2cff000a7fd0
7ec3feff002d1ff0b3fc29ff0041fb0ffbfcb5f3ff0057adfc8fee6791ec6a7f2bfb8ea28ae5ff
00e167f853fe83f61ff7f968ff00859fe14ffa0fd87fdfe5a3eaf5bf91fdcc3d8d4fe57f71d451
5cbffc2cff000a7fd07ec3feff002d1ff0b3fc29ff0041fb0ffbfcb47d5eb7f23fb987b1a9fcaf
ee3a8a2b97ff00859fe14ffa0fd87fdfe5a3fe167f853fe83f61ff007f968fabd6fe47f730f635
3f95fdc7514572ff00f0b3fc29ff0041fb0ffbfcb47fc2cff0a7fd07ec3feff2d1f57adfc8fee6
1ec6a7f2bfb8ea28ae5ffe167f853fe83f61ff007f968ff859fe14ff00a0fd87fdfe5a3eaf5bf9
1fdcc3d8d4fe57f71d4570bf1915a6f09c36d1a979ee2fada28917abb1957007e5576e3e2bf84e
da2690eb96b201fc313ef63f80e6bdd3f636fd9abc43fb4a7c53f0f78eb5dd22e748f861e1bba5
d42d5af6331b6ad7487318453c940d824f4c023a9af532ec1569e22337169277d4eec1e1aa4ab4
64d592d4fd2dfd9b6de4b4fd9d7e16413218e58bc2ba523a30c1561691020d7a3d456b6b0d8db4
36d6f1ac30428238e34180aa06001ec054b5f7e7d6851451401ca7c48f859e17f8bbe1e9342f16
e96356d2e439683cf961cffc0a3656fd6bc064ff00825e7ecc7248cedf0cf2cc4927fb7b53ebff
008135f54d1401f2affc3ae3f662ff00a265ff0095fd53ff009268ff00875c7ecc5ff44cbff2bf
aa7ff24d7d5545007cabff000eb8fd98bfe8997fe57f54ff00e49a3fe1d71fb317fd132ffcafea
9ffc935f5551401f2aff00c3ae3f662ffa265ff95fd53ff9268ff875c7ecc5ff0044cbff002bfa
a7ff0024d7d5545007cabff0eb8fd98bfe8997fe57f54ffe49a3fe1d71fb317fd132ff00cafea9
ff00c935f5551401f2affc3ae3f662ff00a265ff0095fd53ff009268ff00875c7ecc5ff44cbff2
bfaa7ff24d7d5545007cabff000eb8fd98bfe8997fe57f54ff00e49a747ff04bcfd9922915d3e1
9e1948607fb7b53e08ff00b79afaa28a00e63e1efc35f0dfc2af0f43a1f85b4d1a5e9717dc83ce
925c7fc0a4666fd6ba7a28a0028a28a0028a28a002a2bab68af6da5b79937c32a1475271904608
a968a00f9a7c4bff0004e0fd9d7c5fab4da96aff000f3ed77b3316797fb6f514c93c9e16e001f9
565ffc3ae3f662ff00a265ff0095fd53ff00926beaaa2803e55ff875c7ecc5ff0044cbff002bfa
a7ff0024d1ff000eb8fd98bfe8997fe57f54ff00e49afaaa8a00f957fe1d71fb317fd132ff00ca
fea9ff00c9347fc3ae3f662ffa265ff95fd53ff926beaaa2803e55ff00875c7ecc5ff44cbff2bf
aa7ff24d1ff0eb8fd98bfe8997fe57f54ffe49afaaa8a00f957fe1d71fb317fd132ffcafea9ffc
9347fc3ae3f662ff00a265ff0095fd53ff00926beaaa2803e55ff875c7ecc5ff0044cbff002bfa
a7ff0024d1ff000eb8fd98bfe8997fe57f54ff00e49afaaa8a00f957fe1d71fb317fd132ff00ca
fea9ff00c935e9bf07bf64df853f00af24bbf01f85468570ea519cea1757391e989a5715ebb450
014514500145145001451450015e39f183f642f849f1ef515bff001df8486b976a368906a3776d
c71da19507615ec745007cabff000eb8fd98bfe8997fe57f54ff00e49a3fe1d71fb317fd132ffc
afea9ffc935f5551401f2aff00c3ae3f662ffa265ff95fd53ff9268ff875c7ecc5ff0044cbff00
2bfaa7ff0024d7d5545007cabff0eb8fd98bfe8997fe57f54ffe49a3fe1d71fb317fd132ff00ca
fea9ff00c935f5551401f2affc3ae3f662ff00a265ff0095fd53ff009268ff00875c7ecc5ff44c
bff2bfaa7ff24d7d5545007cabff000eb8fd98bfe8997fe57f54ff00e49a3fe1d71fb317fd132f
fcafea9ffc935f5551401f2aff00c3ae3f662ffa265ff95fd53ff9268ff875c7ecc5ff0044cbff
002bfaa7ff0024d7d5545007cdbe14ff0082737ecf1e09d620d5745f87bf62bf8183c72ff6d6a3
26d23a70f7041fcabe8eb7823b58238625d91c6a1557d00e054945001451450014514500145145
001451450014514500145145001451450014514500145145001451450014514500145145001451
450014514500145145001451450014514500145145001451450014514500145145001451450014
514500145145001451450014514500145145001451450014514500145145001451450014514500
7fffd9
}\kerning2\f1\fs21\lang1033\line\par
\f0\page\f1 redis-cluster\f2\'cd\'b6\'c6\'b1\f1 :\f2\'c8\'dd\'b4\'ed\f1\par
\cf7\highlight8\f7\~\cf0\highlight0\kerning0\f3\fs22\lang0{\pict{\*\picprop{\sp{\sn wzDescription}{\sv Image}}{\sp{\sn posv}{\sv 1}}
}\jpegblip\picw12039\pich9843\picwgoal6825\pichgoal5580 
ffd8ffe000104a46494600010101006000600000ffdb0043000302020302020303030304030304
050805050404050a070706080c0a0c0c0b0a0b0b0d0e12100d0e110e0b0b101610111314151515
0c0f171816141812141514ffdb00430103040405040509050509140d0b0d141414141414141414
141414141414141414141414141414141414141414141414141414141414141414141414141414
1414ffc0001108017401c703012200021101031101ffc4001f0000010501010101010100000000
000000000102030405060708090a0bffc400b5100002010303020403050504040000017d010203
00041105122131410613516107227114328191a1082342b1c11552d1f02433627282090a161718
191a25262728292a3435363738393a434445464748494a535455565758595a636465666768696a
737475767778797a838485868788898a92939495969798999aa2a3a4a5a6a7a8a9aab2b3b4b5b6
b7b8b9bac2c3c4c5c6c7c8c9cad2d3d4d5d6d7d8d9dae1e2e3e4e5e6e7e8e9eaf1f2f3f4f5f6f7
f8f9faffc4001f0100030101010101010101010000000000000102030405060708090a0bffc400
b51100020102040403040705040400010277000102031104052131061241510761711322328108
144291a1b1c109233352f0156272d10a162434e125f11718191a262728292a35363738393a4344
45464748494a535455565758595a636465666768696a737475767778797a82838485868788898a
92939495969798999aa2a3a4a5a6a7a8a9aab2b3b4b5b6b7b8b9bac2c3c4c5c6c7c8c9cad2d3d4
d5d6d7d8d9dae2e3e4e5e6e7e8e9eaf2f3f4f5f6f7f8f9faffda000c03010002110311003f00fd
53a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a
2800a28a2800a28a2800a28a2800a28a2800a28a2800a28af3ef8bff001cfc27f04b4517de23bf
db712f16da75b8df7372de8899fd4e07bd1b01e835ca78b7e2a7847c0b6ed36bde22d3f4c45e0f
9f3a839f4c57c61e2ff8e5f15fe36c92259cebf0ebc2d21f922b7f9efe64ff0069cfddfc3047bd
729a7fc1df0e5b5c9bbbe867d73516397bcd52769e473ef9e0fe22bf3acdb8ef27cae4e9464eac
d7486a97ab765f75cfaec070be618e8a9b8f245f597f96ff007d8fa4bc41fb7efc2ed0e768e1fe
d6d640ff00969a6430caa7e84cc2b334cff828bfc33d465547d27c4f6009c6fbbb4b7451ee7139
af28b6d034bb25db6fa6da40be91c0abfc854d2e95653a91259c1203d9e2523f957c53f14e1cda
611dbfc7ff00da9f48b81e56d6bebfe1ff00827d59e0bfda3fe1d78f4a47a578a6c1ae5bfe5da4
9d448bf50091fad7a4453473c6b244eb246dc8643907f1afce9d67e15f8535d07ed3a2db23f692
dd7ca607d7e5c734ff000ede7c4af84138b9f0378b67d4ac53ef687afb19e2751fc2afd57d80c7
b9afa7cb7c45ca31d254f117a327fcdac7ef5faa478b8ce11c7e1939d2b545e5bfdcff004b9fa2
d457807c12fdaf340f8977b1f87fc4368fe0ff00178186b0bd61e54e7d629380df438f6cd7bfd7
ea109c2ac54e0ee9ecd6a99f1328ca127192b34145145592145145001451450014514500145145
001451450014514500145145001451450014514500145145001451450014514500145145001451
450014514500145145001451450014514500145145001451450014514500145145001451583e3b
f1a69bf0efc21aaf88f57944361a740d34873cb7f7547b92401ee6803cebf68dfda12cbe09787e
38ada35d4bc55a8663d3b4d5392cdd37b0eca2be42d17c27a86b7af4de2df1a5d9d6bc53767796
9798ed81e8918e831d29be1c9f54f897e29bff0088de27cbea5a8b1fb0db30f96d2dff008428ec
48aed2bf9bf8e78c2a626b4f2bc04ed4e3a49afb4faabf65f8fa1fb0f0cf0fc28d38e37151bcde
b14fa2efebf90514515f8a1fa385145140051451401cf78bfc11a778c6cc25ca18aea3f9a0bb8b
e59226ec41af54fd9abf690d4745d76dbe1afc45b90d7acbb346d6a43f2dda8e9139fef63a7e5e
95c65739e3bf06c1e34d11ed4b9b7be8889acef10e1e0997956047239afd238478b6b6455e3431
1272c3c9eabf97fbcbf55d7d4f8fcff21a799d275692b555b3efe4ff00467e8875a5af07fd923e
36dcfc54f03cba5eba447e2ed05bec9a846460c98e165ff8101cf6cd7bc57f584271a915383ba7
aa3f09945c5b8c959a0a28a2ac90a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a2
8a2800a28a2800a28a2800a28a2800a28a2800a2992ca9044f248eb1c680b33b1c0503a926bc43
e237eda1f0a7e1bbc905c78806b37a9d6d7464170dff007de427fe3d4d2be88363dca8af84fc45
ff000546d3e1919343f01dc5d479f966bed416238f7458dbff0042ae697fe0a89af0972de06b13
1ff745f303f9ecfe95d71c162a6af1a527f2671cb19868bb4aa457cd1fa23457c3be18ff0082a1
e87732c69e20f04df69f1f479ac2f16e0fd42b2a7f3afa0be1bfed67f0bfe283470e97e2486d2f
9f00596a63ecf2e4f4193f293ec18d6152954a4ed522d7aab1d10ab0a8af0927e8ee7b05148ac1
94329041e411de96b2340a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800af8fbf6e5
f1749e23f11783be17d9ca44578e756d5554ff00cb042446a7d9983fe42bec1afcf4f11ea87c69
fb4d7c49d71cee8b4f68349b5efb5557320ffbec13f8d7cc7136632cab28c462a0ed24acbd65a2
fbaf73dbc9708b1d9852a12d9bbbf45abfc8da8614b785228d42a200aa076029f4515fc58db6ee
cfe8ddb40a2abea3a85b693633de5e4e96d690219259a46c2a28ea49ae6fc03f15bc29f1412fdf
c2fac47aba58bac770d1c6e8119b381f328ce769e99e95bc70f5a74e55a306e11ddd9d95f6bbd9
5cc9d5a719aa7292527b2beafd11d651457123e34782cd9a5d0d723fb3beb5ff0008f2bf932f37
ff00f3c3eef5ff006beefbd14b0f5abdfd941cadd937f904ead3a5fc4925eaec76d45727e3cf8b
1e11f8630c32f89f5db6d244dfead64dccedee15416c7be2a7f037c4af0c7c4ab192f3c33acdb6
af0444090c24864cf4dcac030cfb8ad1e0f12a87d65d297b3fe6b3e5fbf623eb145d4f63ceb9fb
5d5feedce968a28ae33a0c0f0b7899be107c7ef0df89524f2349d6dc69ba98e8bcfdd73ee33c7b
d7e8603915f9bbf18ac1aefc057d3c7febec8addc47fda43915f7afc23f119f177c30f0b6aecfe
64975a742f23fab84018ff00df40d7f57787b98cb1d932a551de549b8fcb75f83b7c8fc2b8b306
b0b98b9c569357f9ecff00cceba8a28afd34f8c0a28a2800a28a2800a28a2800a28a2800a28a28
00a28a2800a28a2800a28a2800a28a2800a28a2800af2ef8ebfb42f85fe03787daf75ab912ea12
a9fb2e9d137ef666fa761ef4dfda23e3d68ffb3ff80e7d6af82dd6a53662d3f4f0d86b8988e33e
8a3a93e9ee457e42fc40f885aefc4ff145e6bfe21be92fb50b972c4b1f96319e1547603d057ab9
7e5f5730a9c90d12ddf6ff00827998fc7d3c053e69eadecbb9e93f1bff006b6f1cfc6bbc962b8b
f9349d0f77eef4cb372a98ec588e58fd6bc4cf24924927a934515fa7e0f2dc360a36a71d7bbdcf
cdf1798e2318ff00792d3b2d828a28af50f3429637689c3a3323a9c8653822928acea538558f2d
449af32e15274a5cd0767e47d13f017f6d7f1a7c1eb8b7b1d42793c45e1c0407b3ba7cc91aff00
d3363d3e9d2bf4bfe127c63f0cfc69f0c45ad786ef96e233f2cd6ec712c0fdd5d7a8afc47aeefe
0d7c64f107c12f18db6bba15cb2a8602eacd98f97731e79561f9e0f6af85cd721508baf845b6f1
ff002ff23ed72ccf1ca4a8e29efb3ff3ff0033f6d68ae27e107c57d17e33781ac7c49a2cb98a75
db340c7e78241f791be95db57c29f6a14573be3cf885e1ef863e1cb8d77c4daa43a4e9700cbcd2
e4fe0140249f602bf3f3e3effc1522eef7ed1a4fc2dd30d9c3ca1d6f5440643ef1c40e17d8b13f
ee8aecc3e12b625da9ad3bf4392be2a961d7ef1fcba9fa4619589008247500f4a757e657ec6ffb
5b7c43b6d33c530378435df8a9acdddda5c79e97ab12c1c302a599485049180001c57d16df18bf
699f12f3a47c19d23c368df75f5bd605c01f5f2b69fd2b4ab82a94a6e326b4f34bf5b99d2c653a
b05249fdcdff00c03eaaa2be54ff00846ff6b6f13f379e28f02785237ffa065acd3bafe12023f5
a3fe196be32788be6f137ed0daabab7de874ad1e2b5c7b0756fe959fb082f8aa2fc5fe48d3dbc9
fc34dfe0bf53ea4b8bdb7b4199e78a11ff004d1c2ff3ac1d67e25f853c3d1f99a8f88b4db44c67
325ca7f8d780dbfec07e1dbdc3788be227c41f11bff125d6b7888ffc076123f3adfd1bf607f81f
a448257f068d4ae01c99afafae2463f501c29fca97261d6f36fd17f9b1f3d77b412f57fe48ddd6
ff006c6f839a116597c79a55c4abc186d66123fe42b8ad47fe0a13f0ba29045a6a6b9ac4e4e02d
b6972ed3f46c62bd6745fd9e7e18f87954587807c3d115e8efa745230ff813827f5aedb4dd174f
d1e3f2ec2c2dac63e9b2da158c7e400a39b0eb68b7f34bf40e5aef7925f26ff51d657eb7fa6417
b1ab2a4d0acaaac30c0119c11eb5f9cbf0eff7de23f88f727efc9e2abf073d701c63f9d7e92101
8107a1afce1f0adabe8bf12fe28e8f2f12c3e219ee88f4598965fd057e55e21c652c82a38f4946
fe97ff003b1f79c24d2cd609f552fc8ec68a28afe4e3f763c5bf6b9b3f11dcfc16d7e4d0f52b5b
1b386d267d4a3b8877bdc41b7ee467f85b3deb92f05c3f137c1bf057c2a9a54fe1a0d7b0c73c9a
c4e8b6f1d85a1823312ba70657c97c9af5cf8e7e1ed43c59f07fc5da3e936c6f352bdd3a586de0
560a5dc8e0658803f135e45f173e1478b75bf87ff0aa3b5d053c496fe1fb68d757f0b4b79f6717
6ff67445cb83b7e4656ef8e7b8afd0f27c4d1a981a383ad2825ed24df328f485d5eee3bbd13935
1bd93d11f279851a90c4d4c453526f912d1bfe6b3b68f65abb2bef6d49be127c6cf13ddfc6187c
11af788741f16c5776525d477fa226c10b2725180ee7deb84f1678df52f1cf853c3f3ea7f67125
87c62874e87ecf0ac43ca8f76ddc0756e4e49e4d6d7c34f85fe34d2fe397877c5d2fc3bd37c21a
0476d3589b0d36e63925b70e3fd64cdc6fe7bae4fb5469f05fc683c2f696a74393ed09f15ffe12
164f3a2e2c39fdff00dee9fecfdef6afa24b2bc3e2d55a72845f2c3670d25fbc52f85f2ad396f6
d0f23fdb6ae1f926a4d5e5ba96deeb5babef7b5f53debc4de00f07e9fe22bef881ae5bacd776b6
9b1e6bb7df1431a8e4aa1e149ee7bd79c7c02f0f49e26f899e21f89f67a50f0ef87754b15b0b1b
20bb1aec09031ba65ec4edc0f635ebbf1334ff00ed5f00ebb67fd847c4fe75ab27f638b9fb31bb
ff00a67e6ff067d6b47c276a2c7c2fa45bae9dfd9022b4893fb3fccf33ecd8403cbdff00c5b7a6
7be335f9f53cc2a53cbe71726e53f7356aca0aceca37beafab564b677bdbeae78484f151692518
fbda2d5c9dd5dbb5b6e97bf7d0d5a28a2be6cf60c8f1844b3f8575546c6d36cfd7e95f4dfec657
2f77fb327812490e58db4a339cf4b8940fe55f2cfc44be5d3bc0fad5c31c04b66fe58afae7f655
d11fc3bfb3d781ec641865b1326318e1e4671fa357f46785b192c262a4f6728fe5afe68fc8b8dd
af6f4575b3fccf57a28a2bf6f3f340a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800
a28a2800a28a2800a28a2800a82f6f21d3ace7bab8711c10a191dcf40a0649a9ebe75fdbb7e253
fc3ef813a85bdb4a62d435971651153860a79720fb0c5349b76426d25767e7c7ed4bf1b2ebe377
c54d4352f349d1ec99ad74f881f9446a7eff00d58f39f4c5790520e296bf65cbb071c161e3496f
d7d4fc8f1f8b9633112aaf6e9e81451457a479e1451450014514500145145007d25fb0e7c7897e
13fc52b6d1efee0af8775e916d67566f922949c249ed83c13e84d7eaf57e07ab32306538653904
7635fb37fb2ffc497f8adf03fc2daf4f2196fcdb0b6bb663cb4d11f2dd8ffbc549fc6bf2bcf706
b0b89e782f767afcfa9fa66498b789c3f2cdfbd1d3e5d0f4cbed3ad75380c3796d0dd447f82640
ebf91af24f1bfec83f093c7e246d4fc19a7c771272d756882297fefa15ec9457cfc2a4e9bbc1d8
f7a508cd5a4ae78bfc07fd957c29fb3beb5acdef856e2f56db538d524b4b993cc5520e410c79f6
fc6bda28a294e72a92e69bbb084234e3cb0564145148582a9248007249a82c5a4240049e95cf6a
df10fc37a229377ac5aa90705637f3181f70b922b98b9f8d76775f268da26a3abb31daafe5f970
b7fc0ce7f515e362739cbf0b2e4ab5973765acbff01577f81e8d1cbb175d73429bb777a2fbdd97
e277635cd399ca7dbed838fe032a83f966adc534730cc6eae3d54835f186aba6ea561e229ad12d
2e2ceed9fe5b64937b8cf6caf535ed3f0d3e146b2520bff106ad7a917df8ec12e1faf62fcfe83f
3af88ca38c7179be2e585a58097baed2973592f5bc55bd37f23e9730e1ea197d055e78a5aaba56
d5fa59bbfaec7b4d7c1dfb40680df0ff00f6ab96f8a6cd3bc63a7248b20e14dcc3f215fc1029ff
008157dde8a11428ce00c0c9cd7837ed95f0a6e7e22fc2d1aa68f196f12786a6fed3b12a3e6751
feb63fa1500fbec03bd7dc67197c735cbeb60a5f6e2d2f5dd3f93b1f3397e2de07174f12becbfc
3afe078651589e0df13c1e2ef0f5aea301c33aed9633d51c70ca7dc1adbafe23af42a61aaca8d5
56945b4d79a3fa4e954856846a53774d5d051451581a8514514005145140051452332c6a598855
032493800530386f8a514fe20fec2f09d92196fb5dbf8edd625ea501cb7e95fa31e1fd1e1f0f68
3a6e956e31058db476d1ff00ba8a147f2af8c3f649f0737c53f8b7a97c43bb859b41d101b2d24b
8f965973f3c83e87a1fa8afb7ebfb0b83729964f93d3a5555a72f7a5e4df4f92b2f53f9f388b1e
b30cc27383bc63eeaf975f9bb8514515f707cd0514514005145140051451400514514005145140
05145140051451400514514005145140057e7a7fc1507c48f2788fc1da0063e5476af7bb7b6e66
29fc9457e85d7e667fc14c3cc3f19745dff70696bb3e9bce7f5af432e8a9e32945ff0032fcce0c
7c9c309564bb33e42a28a2bf683f210a28a2800a28a2800a28a2800a28a2800afd1aff00826278
91aebc01e29d11dcb1b4d405c2293f755d14607e218fe35f9cb5f777fc12df7ff68f8f7af97e55
b63d3397ff00eb57c6f13453c3d39754ff0035ff0000fade1c9355e71e8d7ebff04fd02a64b347
021796458d075673815cef8d2d7c49796f047e1eb9b6b5666c4b24ea4b28e795e719e9d6b998fe
115eeaae64f1078a750be67e5a3b5c5ba1f620641afc7b138ec553aae8e1b0b29b5f69b8c63f7b
6e5f7459fa951c3509c3da56aca3e566e5f75adf7b3a8d67e21787f42dcb77a942b201911ab64b
7d3b1fceb93b8f8dd05e4e60d0f47bdd56529b8058c820ff00bb8e475e86ba2d27e14f85747e61
d1e199cf56b9ccb9fc1b23f4aea60b78ad6258a189218d460246a140fc05737b2ce311fc4ab0a4
bb4539bffc0a565ff921b7b4cbe97c109547fde6a2bee577ff00931e5e97ff0012bc44d198ad2d
b438181cbc8067f156f981fa52c5f07f52d60c4fe21f125cde9524b411bb14ff0080b1c11debd4
e8a7fd8542aeb8ba93abfe293b7fe031e58fe01fda7561fc08c69fa257fbdddfe271da3fc26f0d
68c5192c45c4ca72269db2ff008918cfe35d55b595bd9a916f045002724468173f954f457b187c
261f091e4c3d3505e492fc8f3aad7ab5df3559b93f37731d3c25a5a6bb36ae6d524bf9001e6b8c
edc0c71e95b14515bc29c29dd42295ddddbbbddfab3394e53b733bdb40a4650ca410083c107bd2
d15a107c17f1fbe15ddfecf5e38b8f1668d6af2f80b589775ec10ae4584c4fdec76534595ec1a8
da45736d2acf04aa19244390c0f7afb9f59d1ac7c43a5dce9ba95ac57b63728639a099432ba9ea
08af87be29fece7e2af803a8dceb5e06826f13780e590c93e8792d75a7e7a988ff001afb75f63c
b57e43c65c17fdaede3f0092add56ca5fe52fccfbfe1de23fa82585c57f0fa3fe5ff0081f90515
cff857c77a378c20dda7dd0f3d7892d65f9268cf7054f35d057f356230f5b0b51d1af07192dd35
667ec94ab53af05529494a2faa0a28a2b9cd428a2aa6a7ab5968b68f737f7515a40bd6499c28ff
00ebfd2ae10954928415dbe889949453949d916eb8d9ec759f8d5e2f8fe1ef840b66420eafaa27
fabb3b7cfcc33fde3d31ef8ef53785f4af197ed0da81d2fc0d6b2695e1eddb6efc4b791954dbd0
8847f11f7fe55f6e7c1bf82fe1df823e158f47d0adf32be1eeefe5e67bb93bbbb7e2703a0fcc9f
deb83b81aa42a4731cd636b6b183defd1cbd3a2fbfb1f97710f1342509613032bdf472fd17f9fd
c6dfc3cf01e95f0d3c21a6f8774680416365108d7039638e58fa9279cd7474579ffc2bf8dbe1bf
8b52eb567a55c795abe8d7725a5f69b3102688ab150f8eead80411eb8afe80516d369688fca1c9
2693ea7a0514515250514514005145140051451400514514005145140051451400514514005145
14005145140057e797fc1503c39247e27f07eba148864b47b3ddd8b2bb37f2615fa1b5f37fede9
f0d9bc7bf02af6f2da2325fe8920bc8f03276747007a9e2ba30f57d856855ecd330c453f6d4a74
fba68fc9fa290734b5fb7464a71528eccfc6e51706e32dd0514515448514514005145140051451
40057e8bff00c130bc38d6de05f15eb6e857ed57e2dd188fbca88a723f1623f0afce8552cc028c
927007ad7ebefecc9a2e93f05fe107853c29aa5ec563ae4b682faea19cec2b24c4b9524f1905b6
e339e057e7bc578ca54952a33925af576d5e897abd4fbae19c2d49ba956316fa69f7bfd0f73a29
15830054820f208ef4b5f127d9851451400514514005145140051457cc7fb70fed03f107e01783
ed350f087876d2eec2eb315c6b970e64fb1487a030803a8e439623390474ceb4a94ab4d538eecc
aad48d1839cb647d03e2bf1a685e06d2a5d4b5fd56d349b289773cd75284007e353f867c4565e2
dd02c759d35da5b0bd8c4d048ca577a1e8c07a11c8f622bf1afe105af8dbf6c6f8f9a169be2ad7
2fb5a81a717378f33feee0814e5f620f957818180335fb436565069d6705a5b44b05b411ac5144
830a88a3000f600015d98bc2ac272c1caf27bf6472e1712f1579a568ad89e9080c0820107820d2
d7ce7fb40fed277fa46b917c35f85f6a9e23f899a88dbf2fcd6fa4c67acd3b74c8ecbf89ecadc7
4e9caacb96275d4a91a51e691c97ed03e05f839e28f8aba378536dc699f107567cadd680997b7f
47982f18fad729ad7ecb9f197c14edfd83ac69be32b052764578c219f6ff00b4c71cfd2bdebf67
8fd9bb4ff835673eafaa5d3788fc79aa7ef754d7aefe691dcf25133f753dabdaabcbccf2acb731
5ecf1149544bab5f9755f79d981c763709efd29b837d13fcfa33f3c2f34ff8b9a3398efbe156ab
74e3ab69a8d329fa102a18a5f8a178db2dfe12789118f01ae2d99573f5c57e894b2a4113c92304
8d14b3331c00075354340f11e97e29d35350d1f51b6d52c5d8aadc5a4ab2212382323b8f4af8e7
c05c3f27cdf57ffc9a56fccfa35c539aa5cbed7f05fe47c39a57c12f8ede3170a749d2fc236ac3
1f68bb9848e3fe01d7f4af53f017ec2ba0da5ec3aa78f758b9f1aea0986fb3ce4adaa37a05fe21
ec457d45457d1e5f9165995eb83a118bef6d7ef777f89e3e2b33c6e374c455725dba7dcb43cfbc
7bf11bc23f007c3ba53ea50ff65e9371731d8c02d2dff771bb1c2eec7dd1ee6bbe8e459a349118
3a300cac0e4107a1ae2be357c31b2f8bff000cf5cf0b5ea8c5e407c993bc530194707b107bfbd7
9afec65f13ef3c61f0eae7c29e20629e2ff065c1d23518df86745c88a503d19463fe039ef5f4aa
9a952e78ee9ebe8f63c57371abc8f67b7ea7d055f8cff1dfc75e22fd9f7f6caf186b3e17bd7b0b
cb5d404a00fb9323468cc8e3ba9c915fb315f247c72ff827ee85f19fc79e2bf19deeb9750ea77f
6263d3ece05548a2b90842492b1c975cedf946de9d4d76e5f5e9d0a92f6bf0b5638f1f46a56847
d96e9dcf4efd977f697d1ff691f050d46d616b1d66d42a5fd8b0388dfd54f753d8d7b4d7ce7fb0
c78c2c75af8391680da5dae89e23f0d4cda56af656f02c24cd1fcbe6300064b00093ea4d7d195c
5888a8559462acae75e1e4e74a3293bbb0514515ce740514514005145140051451400514514005
1451400514514005145140051451400557d42c61d4ec6e2cee50496f3c6d14887a152306ac5140
1f8d1fb4e7c17bbf821f15352d25a33fd9772c6eb4f982e15a2639da3dd7a7e55e4d5fb2dfb497
ecfda5fed05e029b49b82969ac5b666d37502b930cb8e87b946e847e3d40afc88f1d78135bf86f
e26bcd075fb192c751b572ac8e3861d994f707b115fa16439a4650584acf55b79f91f079e65b28
c9e2a92d1efe5e660514515f6c7c7051451400514514005145769f093e12ebff00197c616ba068
16ad24923033dc953e5dba77763fc877ae3c5e2e960e93ab55e9f9f923af0b85a98ba8a9525afe
5e67aa7ec4bf0264f8bff156d6fef6dcbf8734375bbbb665f9247072917be4e323d01afd48f13f
81b47f17228d42d83caa309321c3afd2b0fe0b7c21d1be09f812cbc39a3c6088c6fb9b961f3dc4
a47ccedfd076aef2bf18cc671cd27396262a4a5d1abab76d4fd73034de5f08c68369c7aad1dfb9
e512780fc59e0c9449e19d58ded983936572defd06ec8e9dfafa55cd3be32a59de2d8f8974d9b4
5bb38f99c6139cf3cf41d39fd2bd2eaa6a5a559eb16e60beb58aee13fc132061f867a57caff64d
6c26b96d6705fc92bca1f2bbe68ffdbaede47bff005fa788d3194d49ff0032f765fe4fe6afe62d
86a969aac225b4b88ee232320a1cf156abcdb50f83e34db8379e14d52e343b90770833e6404ffb
adebf5aaf17c44f11f84641078ab446b88178fed0d372ca40ee50f3f53c54ff6c54c23e5cce8ba
6bf9e3efc3ef4af1ff00b7a29798ff00b3e15f5c15453feebf765f73d1fc9b7e47a8d1585e1df1
b689e2a4074dd4229e423261276c83fe0279addafa1a35a96220aa5192945ecd3bafbd1e4d4a73
a5270a89a6ba3d028a2b17c63e32d1fc01e1bbed7b5ebe8b4ed2eca3324d3ca7000f41ea4f4007
5add26dd9193692bb0f1878c747f017876f35cd76fa1d3b4cb44324b3ccc14003fad7c97a27877
5ffdb9fc571788bc4b05c68df0674d989d2f48932926b0ea71e7483fb9e9f97ad45e1cf0e7883f
6e6f1a41e27f14c173a2fc1cd2e7dfa5e88c4a49abba9e2597fd8ff23d47d9963636fa659c1696
90476d6b0208e286250a91a8180a00e0003b57736b0aacbe3fcbfe0fe4712be25ddfc1f9ff00c0
fccf0ffd9ebf64af0d7ecefe28f156ada2c8d38d5dd45baca3e6b587a98c1ee338e6bdd89c5048
50492001c926be54f8c3f1e3c45f173c5d71f09be0bc824d487c9af78b40cdb69511c8648c8fbd
29f63c76e725724aa62a6dc9fab7d11ab74f0d04a2bd12ea5ef8e9fb42eb7e21f151f857f08917
53f185c7c97faa47f341a546782ccdd3701f957a37c00fd9e744f817a0cab0bb6ade25d41bced5
75cb9f9a7ba94f2793c85049c0ad0f81df023c39f023c2aba5e8b134f7b37ef2fb54b8f9ae2f25
3d59dbebdbb57a453a9562a3eca97c3f8bfebb0a9d36e5ed2afc5f82febb8515f24fed6bfb56af
c2bf8a7f0fbc1da65d049a4d4a0bbd60a37ddb7ddf2c47d376727dabeb50722b29d29538c672da
5b1a42ac6729423f67738ff8c5af2f863e15f8af546202db69d33927fdd23fad79bfec33a11d07
f65bf03c722e27b8825b9909ee5e6720ff00df3b69dfb6feb4747fd99fc628adb5efa0162a7fda
90e057a1fc16d18787be10782b4e0bb1adf47b4571fedf94a5bf526b5db0feb2fc97fc133df11e
8bf37ff00ed28a28ae43a82be43f8d51bfecddfb4c7867e29daa98bc27e2c65d07c46abc2472b7
30cedd872064fa29f5afaf2b88f8d5f0bf4ff8cbf0bfc41e10d4557cbd4ad992295867c9987cd1
483fdd70a7dc023bd7450a8a9cfded9e8fd1ff005730af07387bbbad57aff5a1da452a4f12491b
0647019587420d3ebe79fd8bbe28dff8bfe1d5c7857c46cc9e30f084eda4ea31ca7e76d876a487
d7200c9f5afa1ab3a94dd29b83e85d39aa90535d4f917e23a9fd9b3f6a9d27c7108f23c1fe3adb
a7eae178486ec7dc90fd720fb926beb9560ea19482a46411debceff681f8536df19be14eb7e1a9
86db9962f3ace61f7a2b84e5187be78fc6b8efd8efe2b5cfc47f8549a6eb47cbf15f86263a3eab
0b7dedf1f08f8f4651c1efb49ae99fef692a9d63a3f4e8ff004fb8e787eeaab87496abd7aafd7e
f3dda8a28ae23b028a28a0028a28a0028a28a0028a28a0028a28a0028a28a0028a28a0028a28a0
028a28a002bc97e3efecdbe17f8fba218755845aead0a116ba9c2b89233d81f51ed5eb54534eda
a1357d19f8ddf1b3f65af1c7c10bd90ea5a73dfe905bf75aa5a29789876dd8fba7d8d7907b57ee
2fc53f1de81f0d7c01ad788bc4cf18d1acadd9e68e450de771811853c12c48500f735e1773fb23
fc23fda03c1ba378ae0d065f0bdc6b1671de87d16611801d4301b0a94efd9457d660f3ec4e1e09
565cf1dafd7efea7cbe2f23c3579bf64f925bdba7dc7e57515f79f88ff00e09732895df42f1e0f
2b3f2c17da7e580f7759003ff7cd734bff0004c3f1919886f1669223ecc21727f2cff5af763c4b
846bde8c97ddfe67892e1dc527a4a2feff00f23e31a14166000249e001d6bea5b3fd8ae1d37f68
bf0dfc32d53c4726a62fac26d4350b8d3e010359c68a4a637170dbc8c67031ef5f6e7c35fd8d7e
15fc3068e7b3f0f8d5efd0822f7597fb43e477db8080fb85ae7c4f122825ec69eeaeaffe4bfcce
8c370f39b7edaa6ddbfcdff91f9f3f023f637f1bfc68ba82ea4b59341f0e9605f51bb42bb97bf9
6a79635fa6bf073e087863e08786a3d27c3b66118806e2f241996e1fbb31fe9dabbe4458915114
2a28c055180053abe27158cad8c9f3d695dfe0bd0fb1c36168e121c946360af9bbe2b7c58f147c
13fda1bc3f79ae5e19fe18789614d393e4c2e9f783a163fed93d7df1dabe91ae1fe347c2bd33e3
37c38d63c2ba9a8d9771e609bf8a098729203d883fa13595194633f7d68f47fe66b5632947dc7a
a3b68dd65457460c8c010c3a11eb4eaf9cbf63df8a9a96ada36a7f0dfc5ee63f1bf83dfec93093
86bab61c4730f5e300e3dabdefc4726a9168778fa2476d36aab196b78aec9589d8745623900f4c
d4d4a6e9cdc18e9d45521ce8d2a649124c852445910f5561906be00f187fc14d7c57f0c3c5177e
1ff16fc264b4d4ed1b6c910d59a30c33c329309ca9ec6bd23f66efdbf1ff0068bf88707856cfe1
ecfa5130bdc5c5e9d544e9022e0648f2573c91c6477f4aea9e03110839b8fbbdeebfcce68e3a84
e7c8a5af6b3ff23e80f10fc20d175999ee6dbccd2ef58e7ceb638e7d48ff0023dab091fc7de046
26503c4da68eea774aa324e7b3138fc057abd62f8c3c61a3f807c377daf6bd7d169da5d946649a
794e001e83d49e8057c8d5c9284aa3ab856e8d47d61a5df9c758cbe6afe67d1c332ab1872574aa
417496b6f47baf933908be3df8620d1ef6ff00559ce91f6388cb34771d70064edee7f2af9f7c3d
e18f10fedbfe2e87c51e2bb6b9d17e0fe99396d2344932926acea7fd74a3fb9c700fd3d6ad7c3d
d37c4ffb5afc471e3cd4a29bc2bf0cac7747a658246a975ab7fd349588c84ef8fcbd47b63780bc
4fe041bfc2bab1bdb15c7fc4bafd436001d15860fd00e2b678acd3276e388a4ab7f7a9e928fac1
bb37e71937da260a86073349d29ba7fdd9fc2fd24ba79492f367a669da7db69363059d9c11db5a
c08238e18942aaa8e0002a6965482379246088a373331c003d4d79ce9df1960b3905b789f4db9d
0ae41c190a99213f420673ed835e13f103c67e31fdad7c6379f0fbc046f7c33f0eec24f2bc41e2
a92268a5bce99b7b60403820f2ddf3e980ddb9763b0b9a37ec2a2f77e24f4947d62ed24fc9a39f
1987af814bdac1ebb5b54fd1ad3f124f895f177c4dfb4a78baebe1a7c25b87b5d0e06f2b5ef16a
644712e70d1c4ddce3238afa0fe107c1df0e7c13f07db787fc396821853e79ee5c666b994fde92
46ea49fd2af7c35f867e1ef84be13b3f0ef86b4f8ec34eb75030a32f2377776eacc7d4d7555ead
5aa9af674f48fe7e6ffad0e0a749a7ed2a6b2fcbc90564f8b35e1e16f0c6a9ab9b796efec56cf3
8b7817749295048551dc9381f8d6b515ceb7d4e867e0a7c5bf14f8a7c65f16356f11ebf67770eb
173746e8c12c6c1a350d9500760062bf6e7e0df89ffe133f851e11d6cb9792f34bb792527fe7a7
9603ff00e3c1abe7ff0003e9f69e3dfdbafe24ddde5b457b65a468d6d6691cf1891049c2b8c1e3
debeaab0b0b5d2ed23b5b2b686d2d631848608c222f39e14703935ec63f12ab4610e5b592fc56c
79381c3ba529cf9af76ff067cc5ff0504ba7bbf869e18f0f447f7dac6bf691aafaec70c7f435f4
fda5b2595ac36f10db1c482351e800c0af96ff006a8ff8a8ff00683f80fe1bc0648f576d4654f5
8c7ca7f957d555c3534a34e3eaff001b7e876d3d6ad497a2fc2ffa8514515c875051451401f227
c698dff673fda5fc3df13ed54c5e17f1515d275f541f224bd1253fa7d4e6beb88a449e3492360e
8ea19581c820f435c47c6df86165f187e18ebbe16bd51fe9901f224ef14c065181ec41efef5e6b
fb177c4ebdf187c37b8f0af8818af8bbc1d70748d4237e19d17222931e85463fe039ef5d92fded
253eb1d1fa74ff002fb8e48feeaab87496abd7aff9fde7d095f227c41ff8c67fdabb44f1ac63c8
f05f8fcae91ac6388e0bdff96329ec324004f601bd6bebbaf39fda0be1159fc70f84daff0084ee
42a4f75017b29dbfe585cafcd13e7ae03019c75191dea30f3509da7f0bd1fa7fc0dcbaf07385e3
f12d57affc1d8f45560ca083904641a5af08fd8f3e2dddfc4cf8551586bbba3f17787253a46af0
4bfeb3cd8fe5dec3d58004fb922bddeb2a9074a6e12e8694e6aa414d750a28a2b3340a28a2800a
28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a46608a59880a06493da96a
2b8b78eeede582650f14aa51d4f7523045007e4f7fc1443f69e3f153c69ff084e83765bc31a24a
7cf68dbe5b9ba1c13ee17903dc9f4afbeff631d606b7fb31fc3e9776ef274c8adb3ff5cc6cfe95
f2cfc4afd927e1d7c4bfdafed3c05a1e99378734ab6d0e6d5b5a9f4a9d8bbc8c76c58f337aa90f
b7200e413f5afb3be02fc1fb7f815f0d34ff0006da6a536ad6b6524cd15cdc20572aee5829038e
338cfb57b98ba943eab4e953d1eff7dcf17094eb7d66a55a9aadbeeb1e874515cdfc47f1347e0c
f00f8835c964112d8d8cb3063d9829dbfae2bc449b7647b2dd95d9f3bfece67fe161fed4df187c
78dfbcb5d3843e1fb190f20a03bdf1f464c7e35f5657cebfb0778664d1fe0159eb1749b2fbc497
d71ac4d91f30323e003ff7c93f8d7d155d3896bdab8ad969f76873e197ee937d75fbf50a28a2b9
4e9390d07e2af86fc43e31d67c2b6fa82278834a7027b197e590a9e8ea0fde5f715d7d7e617fc1
4b74ed5fe1a7c77f0bf8f7c3f7b71a55f5f59ed4bbb4628c92447d475c863c1ea0735edbfb17fe
ddd37c69bab6f0778bf4e957c5489fbbd4ec606682e40fe291547ee9bdfee93fdde057a93c0cbd
847114f556d7cbb9e6c31b1f6ee854d1f4f33a6fdacbc1fa9fc35f1468bf1dbc236ed26a3a0111
eb967171f6cb0270f9c752a0939ec326be8ff0578c74bf881e14d2bc45a2dcadd699a95ba5c412
2f75619c1f423a11d88ad3bfb1b7d52ca7b3bb852e2d67431cb148a195d48c1041ea315f24fc0c
bd9ff65cf8dfaa7c1ad5a67ff84375c91f53f08ddccc76c4189325a927b839c7d093f780ac17ef
e972fda8fe2bfe07e46cff007356ff00665f83ff0083f99e99fb4ffeca9e1bfda43c30f15ca269
fe23b7426c75545f991bfbafeaa7d2be63fd9e3fe09f5e2ef0c786b50d6a7f145ff81fc7b0df4d
0d9cd64dba278170abbfd558866c8ec457e8756378bfc61a3f80bc397daeebb7d169da5d9c6649
a795b0001d87a93d853a58baf0a7ec60f47f3154c2519cfdac96a7cb1a8fc7af8cbfb375a349f1
4fc310f8b7c31010ade24d0d82b22f40644edf8f26b88f0778dac7f6eef8ad24be21d6adb47f87
fa04c1ac7c2925c04b9d464182259933f73d3f2f5aeb3c3de1cd7bf6e0f1941e26f145bdce8df0
734b9b7e99a2392926b0ea78965ff63be3f2f51ec7f12ff641f85ff13638e4b8f0ec5a16a90281
6faae818b2b88703820a0da48e3ef03d2bb1ce8d1d24ad3ead74f977ef6d8e450ab5758bbc3b3e
bf3edebb9ec161636da6d9416b670a5bdac281238a2185551d00151eafabd9683a65cea1a8dcc5
67656c8649a79982a228e4924d7c85e22d27e3a7eca1a45d6b3a778bf4ff00893e04b15324b65e
26616f7b0c63b2cf9c3b7bb1ff0080d7916a3fb495a7ed7de3fd1340f1d6a6df0b3e1a79697274
d99e4f335b973f74dc6c55110231d87d491b79e183954f7e32bc7ab5fe5bdce89e2d43dd71b4ba
27fe7b58f59d4bc41e25fdb63c68961e1779fc3bf0ab48b9cdcebc136cfa8ba9fbb113c85af789
be08ff00606c9fc25aacfa5dc2280cb2b9225231cb30fa0edcf735ddf8374cd0b47f0ce9f65e1a
8ece2d0e18825aad8953104038da5783f5adaaf0b31c0e13316bdad3f8766b492ffb7959dfe67a
d82c4e23069f24efcdbade2fe4f4b1e4e9f113c4de0a6483c53a4c97300e3edf6ebc1e7a92a319
f6eb5dd787bc6da378a20592c6f237638cc4cc03a93d88f5e3a56e322c8a5594329e082320d715
e21f845a0eb729bab689f48bfc605c583797f9af4fd2bc5f619a6075c3d455a1fcb3d25f29a567
ff006f47fede3d3f6b82c4ff00163ece5de3ac7e717aaf93f91dbd15e57f69f1df805b12a47e28
d2907df51e54c17f51fe35a23e35e81268fa94f24b269b7f676d2ced697e9e5b6510b63278edec
7dab6a19d61aa54543109d1a8feccd5aff00e196b197fdbad99d5cb6b420ead26aa41758eb6f55
baf9a478c7ec678f117c43f8dbe2c20b2df788de281fb18c761f422beaaaf99bfe09f3a51b4f80
4ba8c80f9faa6a977745cff12990943f91afa66bea715fc692eda7dda1e061bf8317df5fbf53e5
5f1291e28ff8282785edc8df1681e1d99dc7f75a40594feb5f5557ca9f06bfe2a6fdb73e306b4c
37c7a7d95b69887fbae9853fa57d574f11a38c7b25f8ebfa861f5529776ff0d3f40a28a2b90ea0
a28a2800af90fe32a37ecd9fb4df86be285b2987c25e2d65d0bc4417848a56ff00533b7a72064f
a29f5afaf2b86f8d9f0b34ff008cff000bbc41e10d455766a36cc90ccc33e4cc3e68a4ff0080b8
53ee011deba285454e7ef7c2f47e9fd6a73d7839c3dddd6abd7fad0ede391668d64460c8c032b0
ee29d5f3dfec61f146ff00c65f0e26f0bf890b47e31f08ceda4ea514a7f78de59c2c87d7200c9e
99cd7d0959d4a6e94dc1f434a735520a6ba9f24fc4553fb37fed4fa4f8da11e4783fc77b74fd5c
2f090de0fb921f4ce47d4935f5aab060082083c822bcf3e3f7c2ab6f8cbf0ab5bf0d4c36dccb17
9b6730fbd0dc2731b2fa1cf1f8d719fb1dfc58baf88ff0b8697ad9f2fc57e1898e91aa42786dc9
c23e3d180fc7693deba67fbda4aa758e8fd3a3fd3ee39e1fbaaae1d25aaf5eabf53dde8a28ae23
b028a28a0028a28a0028a28a0028a28a0028a28a0028a28a0028a28a0028a28a0029acc114b31c
281924f6a75709f1d7c671fc3ef83fe2dd7e56da2cf4f9581efb88da31f89aa8c5c9a8aea29351
4db3c3ff0064453e3af8bdf19fe23ca0b4777aa2e8d64e7f863847ef147b6e086beabaf0bfd8a7
c1b2f837f674f0cadd295d4353126a97648e5e49589ddf8a85af74adf1324eab4b65a7dda1cf87
4d5257ddebf7ea15f37fedebe237d3be063e816ce45e789b50b7d25154fcc51dfe623e985fcebe
90af947e3d7fc5c6fdaebe12f8257135a68b0cdafde47d8f3b42b7e0aa453c32fdea93d96bf76a
2c4bfddb8aeba7dfa1f48780fc391f843c15a16891a045b0b28adc85e9954009fc4e4d6f514573
37777674a56564145145219e0dfb58fecc30fed35a1f8774d7d457493a76a02e25ba09b9cc254a
b2afbf3df8e2bc67e15f862cff00620f8f87c25751ac9e05f18856d2b5ab851e65bdcaa80d0bbf
bf1fa7ad7dbf5e71f1f7e0de9df1cbe1b6a3e1cbcfdcdde3cfd3ef070f6d72bca3a9edcf07d8fd
2bba9621a8fb1a8fdc7f879fc8e2ab874e5eda0bdf5fd58f460410083907bd78cfed51f059fe2f
fc3b2fa5936fe2cd0e4fed1d1aed07ce93273b33e8d8c63d40ac1fd91be31ea3e2dd0b50f02f8b
ff00d1bc7de136fb25ec6fc1b9881c24cbea08c03f51ef5edbe2ef17691e04f0edf6bbaedf45a7
69767199269e538000ec3d49ec2b1b4f0f5525bafc7fe1cd6f0af4b5d9ff005f81e41f043f699d
17c5df0526f13f89ef22d1eff4156b6d723b86da619a3182483fdec71ebcd795f87741d7ff006e
1f1741e27f11dbdce8bf0774c9cb693a449947d5dd4ffae907f738fe9eb5f3a78bededbc63f166
0f8b5adf84f51d23e06eb5adc10dedaa5c3c6b78c090b752c607dc2d8e38cf4046723f5334a8ec
a1d32d134e58134f58505badb002211e06dd8071b718c638c577d68c70befd35ef4bff0025eebd
7f238a8b962bdd9bd23ff93767e9f98eb0b0b6d2eca0b4b4812dad60411c7146bb551470001591
e39f1d689f0e3c317de20f105fc5a7e996885e496438cfa003b93d00aa3f13fe287877e107846f
3c47e26bf4b2d3edd781d6495bb222ff00131f4af99fc13f0ebc51fb60f8b2d3c7ff00132d25d1
be1d59c9e6f87fc1cc4837201f96e2ebd73d40fe433bb8a952e65ed2a3b457e3e4bcceca95795f
2415e4ff000f37e457d13c31e26fdb7fc4b07883c530dce81f086c66f334ed19b292ea8474924f
f66be9af13fc1bf04f8c7c391685abf8674ebcd2e18c45140f02e235030029ed8aebadada1b2b6
8adede2486089422471801540e800ed52d2a95e526b9744b65dbfe0f98e146314f9b56f77fd74f
23e51befd907c55f0beee5d4fe0c78f6f341e779d0b56733d9c9edcf4fe429b65fb5df8bbe145c
c5a6fc6bf00dee869908be20d250dc59487d4edefec3815f5854179656fa8dacb6d77045756d2a
ed9219903a38f420f0455fd639f4ad1e6f3d9fdffe7723d8726b4a5cbe5bafbbfcac735e02f8ab
e12f89fa625ff8635eb2d5eddbafd9e50594fa11d41aeb2be74f1ffec3fe07d7b527d73c1d717f
f0dbc4ff0079750f0e4e618d9bb6f87ee95f65db9ae4d7c6bfb457ecfa7678a344b3f8c1e168bf
e62ba38fb36a51a0e32f160ab71d94127bb51ec6153f852d7b3d1fdfb3fc03db4e9ff163f35aaf
f347d6f5e29fb59e9fa2e97f017c73ad5cd9422e20d36511cc17690f2623078ea72c39a97e177e
d6ff000dbe2a4df62b4d64e89ada9db2691ae27d92e51bfbb86e09f6049ae47fe0a0ba8b2fece1
79a444f8935fd4ecb4b8f1dcb4a1c63fefdd63f548d5ab1a38885d36b46bcfccd258970a52ab46
5ad9ea9957f672f877e32f02fc12f06cba26a2b701f4e8a4974f9ce006232700f1f8f5f6af52d2
7e32c76d75f62f1369d3689743037ba10879c679e83dc9e7d2bb6f09d82e95e17d22cd1046b05a
451ed1db082abf8ea4b2b5f086b37b7f6d0dd41656735d159d0301b119b3cfd2be6ebe5d888559
56c05771726df2cbdf836df9be68ff00dbaede47b54b1745d38d2c5524d256bc7dd969f83f9abf
99f38fec412c7e22f11fc64f15865946ade2695e2914e728320e3db22beacaf8d3f628f85ba84b
f022cfc41a4eb371a56a97f7d7573b000d048a64253287be0e335ef50fc44f11f844887c55a13d
c42bff002ffa77cc31ea50ff003c815be3f37fa9e2aa431b4a508276535ef41a5a6ad6b1ff00b7
925e66382cbfeb18784b0d352935771da5aeba5f497c9dfc8f51a2b0fc3be35d17c55107d36fe2
9d8ffcb2276b8ff809e6b72bd1a35a96220aa5192945ecd3bafbd1cd529ce949c2a45a6ba3d028
a28ad8cc29aedb14b609c0ce00c934ea2803f287e3e7ed74de03fda3bc45e24f8616d75a3df5d5
a9d3f555d4edf62cd321c0904679040f5efcd7dd1fb14fc48d57e2a7ecfba26b7ae5f3ea3ab19a
686e6e65396660f9fd0301f85711fb65fec55a5fc7ad2a6f1178762874cf1c5b21224036c77c00
fb927fb5e8df9e6a8ffc1352d753f0e7c20f11f85b5ab49ac755d1f5d9566b69d70d1ef44007d3
e4241ef9af72bca856c1a9535ef2b5fbff00c31e2d18d6a58b71a8fdd77b76ff00873ebbaf927c
75673fecedfb5a681e32b2864ff8447c7ecba3eae91292b15e1ff532903a648193d806f5afadaa
9ea935859dab5eea2f6f0db5ae6637172542c581f7b71fbbc679af26954f66ddd5d35667a9569f
b44acecd3b96c1c8cd365952142f23ac683ab31c015f1afc6fff00828a68be1996e349f87d62be
21bf4ca1d4eeb296b1b7fb2bc33fe6bf8d7c65e3dfda1fe247c4bb87935cf16dff0092d902d2c6
4fb34207a6d4c6e1fef66bc6c566585c1e9567af65ab3ef722e0bcf388fdfc061db87f34bdd8fd
ef7f95cfd6ed77e2c7837c3271aa789b4cb23e92dc28ac18ff00693f85b2c9e5a78ef4567fee8b
a15f8d06042c5882cc79258e49a3c88ffba2bc39712e1d3d212fc3fccfd4e978279c4a37a989a6
9f65ccff001e547ee2e8de39f0f788a21269bad58dea1e8629d4e7f5adb041191c8f5afc25b29a
6d32e56e2cae26b2b84fbb35bc851c7d0839af6af865fb64fc52f86534289ae1f1169887e6b1d6
419b70f69321c1ff008163dabba867b83aeecdb8bf3ff3d4f98cdbc28e24cb20ea53a71ad15ff3
edddff00e02d45bf9267eb8d15f3bfc08fdb67c15f191a1d36f09f0bf88df0bf60bd9018e56ffa
6726003f4201fad7d0fd6be81352574ee8fc82a539d19ba7522d4968d3d1af542d14514ccc28a2
8a0028a28a0028a28a0028a28a002be5efdbe75796ebe1f7867c176849bdf14eb50da88d7abc4a
41907e4c3f2afa86be50f887ff001727f6ebf046820f9963e10d31b549d7a84b87f9933f5523f2
aebc2e9539ff0096efeeff008272e275a7cbfcd65f7ffc03ea0d034887c3fa169da5db8020b2b6
8eda31feca2851fcaafd145721d415f297ecf63fe162fed5df193c72c04b69a65c47e1eb390721
4c2bb5f1f51835f4778fbc5907813c0fe20f11dce3c8d26c27be70c7a88e32f8fc715e1ffb02f8
527d0bf67ad3356bd04ea5e22b89b57b895bac9e63928c7fe01b6bb29fb94673ef65fabfc8e4a9
ef56847b5dfe8bf33e8fa28a2b8ceb0a28a2800a28ac5f18f8cb47f00786efb5ed7afa2d3f4bb3
8cc92cf29c0fa0f527b0a6936ec84da4aecf9a7f6bff000b5dfc2bd7349f8f1e1531c1abe84cb1
6af685822ea1664e194fa900d735e0eb1d77f6f2f125bf8abc410cba37c1dd32e1bfb3747df87d
5254620c92e3f841047e18f5a7e81e17f10fedcde3387c49e2cb7bad13e0de9936fd3343726393
587078925efb3fc8f5177c0f2bfec75f1f67f045dbb27c2df1a4ed77a14ce729a6ddb1f9edf27a
29278ff80f524d7b4bdca7c89deac57dcbb7aafc0f1dfbf3e76ad4dbfbdf7f47f89f4d78d3e1a6
83e37f87d7fe0ebdb189745bab536a20450046b8c295f423a835f29fc22fda522fd9a7c35e27f8
6bf146ea56d67c1ac22d2242099355b47c9b7118ee7181ec31e95f467c73f8f5e1df811e163a9e
aced79a85c1f2f4fd26d7e6b8bd94f0aa8be99c64f6af8dfe20fc0df8abe2cd2c7ed0de2a16efe
31d2a786facbc2020578adb4d4258c4d9073261b773d393d700638582941aadf0bdbd7cbf26cdb
133719a747e25bfa79fe87adfc33f83be26fda33c5d69f133e2e5bb5b6910379ba0f845f3e5c29
d564957bb77e6beb68e358a35445088a0055518007a0ae47e137c4ad2be2df80348f1468f206b5
be843320eb138fbc847620d7615c55a729cad256b696ec765184611bc5defadfb8514515ce6e14
514500149d6968a00f2ff8a1fb35fc3df8bb113af787e0fb68fb9a85a0f26e233eaaebce6be26f
da4be0c78e3e11789be18f84f42f16de78df48d435c1a8e93e1ed5e4f9a39ad007dbbffba56423
3d79afd29af953e29b7fc253fb7afc28d23efa787f44bdd6197a81e7661cfe6a3f215e9e0eb4e3
2b377493767e879d8ba30946e959b695fe65df097edbda3e99a947a07c50f0f6a1f0df5b184dda
844df6473eab2740bf5aef3f688f1fe99ff0cd1e3cd734bd46deface5d1a68a39ede40ea44abe5
0208ff007ebd27c55e0dd0bc71a5c9a6f88348b2d66c5fac17b02cabf5191c1f71cd7c1dfb677e
ca7e1ff847f0c6eb54f016b5acf876db59d42df4e9fc34978f269f74d23e57e46e4105339c9e98
0052a11a15aac57c2eebcd7f9afc42b3ad4a9c9fc4ade8ff00c9fe07d67fb2ae827c37fb3bf80a
c59364a9a54264f772bc9af549a18ee2268e58d658d86191c0208f706be40f0c7ed17f12be02e8
fa6e93f157e1bc975a15bc291c5e22f09667884600c1785b91c753951ed5f42fc33f8ede04f8bf
6693f853c4965a9bb0c9b50fb2e13d731b61b8f5c63deb0af4aa293a8d5d37bad51bd1ab069413
b35d1e8c7788fe0fe8bacb3cf681b4abe3cacd06719f5233cfe78ac31278f7c031e1d078974d43
f7972f328cfe678fc066bd5e8af95ad92e1dcdd6c33746a3eb0d2ffe28eb197cd5fccf7e9e6555
4553ac9548f696b6f47baf93387f0d7c5cd0f5f290cd2ff675e9e1ade7e307d012067ebd2bb68e
449903c6c1d1b90ca720d61f88fc0da1f8ae32ba969f14d2769946d907fc08735c649e08f15782
dbcdf0ceb2da85a2f5d3f52f9f03d030e7e82b0face6781ff79a5eda1fcd4f497ce0debff6ec9b
fee9afb1c162bf833f672ed2d57ca4bf54bd4f51a2bc23c75f1af58b0b082cce972e8baca4a1e4
de43c6ca3ae0fa1e78fd6bd07e1bfc4eb1f1ed805045bea71afefad89ebfed2fa8fe55960f89f2
cc7635e5f4a7fbc4af669c6fdd6b6775d535fa9788c971b86c32c5ce3ee5fa34fe7a6967d19db5
55b7d2ed2d2f2e6ee0b68e2b9b9dbe7488b8326dcedcfae327f3ab5457d59e1193e2af14699e0b
f0fdeeb5ac5d4765a759c66496690e0003fad7e59fed37fb58eb9f1d756974ed3a69b4bf07c2e5
62b4462ad7383f7e4f5f615d77edd9fb45cbf11fc673782b44b923c35a34a52e2489f8bbb81f78
f1c1553c0fcfbd7caa06057c8e759b3c37fb3d07ef757dbfe09fd13e1a787d4f394b38cd637a09
fb91fe76babfeeadadd5f92d515428c01814b4515f9e36e4eef73fb1a9d385282a74d2515a24b4
4828a28a9340a28a2801559a391248dda3950ee57438653ea0d7dbdfb207edab736d7d63e08f1f
de19a094886c75899b943d15243e9db35f10523a87183c7a11dabdecb335a9819a8c9de0f75dbc
d1f93f1c70160f8a70f2ad462a18a8af765b737f765dd767baf4d0fdde560ea194820f208ef4b5
f227ec13fb474df10fc32fe08f115cf9be20d1a202d6e246f9eead87033eac9c027b8dbd4e6beb
bafd4a138d48a9c1dd33f8331387ab84ad3c3d78b8ce0da69ee9ad1a0a28a2ace70a28a2800a28
a2800a28a2800af943f646ff008aff00e327c65f890ffbc86ef563a558c879dd6f0f0847e1c7e1
5ef3f1b7c6cbf0e3e1178c3c4a6411c9a7697713424ffcf5d84463f172a3f1af3ffd897c127c11
fb38784e2963d975a8427529b70f9b74c4c983f4dd8aeb87bb4272ef65fabfd0e59fbd5a31ed77
fa2fd4f76a4240049e00ef4b4846463a8f4ae43a8f973f6ebf8896b77fb3e5e685e1ed420bdd4f
c4da8dbe8500b79431def28de840f55571f8d7d11e07f0d5b7833c1da268568bb6d74eb38ad630
0630a8a147f2afc39f8bda5ea7e1ef8fbe26d3f497ba8f528f5d792d05a330944cd26e8ca6390d
9618239cd7ec77ecd1e0bf16f81fe12e8f67e37d7aef5ff124a827ba92e9c3984b72220d8c90a3
8c9272467dabdac661961e8534a57bebe7adbf23c7c2621d7af36e3b69f75ff33d528a28af14f6
028a2b17c63e31d1fc03e1cbed775ebe8b4fd2ece3324b3ca7007b0f527b0a6936ec84da5ab0f1
8f8c747f00f872fb5dd76fa2d3b4bb38ccb34f3360003f99f6af93bc33e1ed7ff6ddf175bf8b3c
4d6f71a37c20d366dda468d2e51f55653feba41fdde28f0ef86b5efdb7fc636fe27f15dbdc68df
0734b9f7e97a1312926b0ea78966ff0063dbf2f51f62da5a41a7dac36d6b0c76d6d0a08e286250
a88a06028038000ec2bb9b585565f1ff00e93ff07f23895f12eefe0fcffe07e636c6c6df4cb386
d2d214b6b6850247146b85451c00057cdbfb77788fc1c3e159f0d6b292dff8a351954e85636037
5d8b907e59107500773ef5d7fed0dfb49d8fc1db6b6d1747b36f1378fb55fdd697a0db7ccece78
0f263eea0ebef8fc4607ecf7fb365fe81ad4df11fe275eaf89be276a437b4ae33069887a4302f4
18e8587e1dc95463ecad5ea3b765d5ff00c0eec7565ed2f469abf7ecbfe0f91e31fb13f85a2f88
1f1035ad5be28dd5dea7f13fc3612de1d2b551c5942000b2221ea7a027b66beee9a14b885e2950
491ba95646190c0f041af96bf6aef006b1e01f12e93f1d3c0b6fbf5dd038d66c23e9a8d8ff0018
23b9033cf5c671ce2be85f879e3ed1fe27f83349f14683722e74bd4a059e26fe25cf5461d994e5
48f5069e25fb5b565b3d2dd9f6fd50b0cbd95e8bdd6b7eebbfe8cf983c17349fb25fed1b37842e
9da2f875e3898cda4cae7f77677a4f3167b06271f8e7b57d855e5ffb477c16b3f8e9f0c351f0fc
ac2df5241f69d36f07deb7b95e5181f4cf07d4122b99fd923e35de7c51f024da378954da78f3c2
f29d2b5bb593efb489f2acdee1c0ce7a643638c54d4fdf53f6ab75a3fd1fe8fcfd4aa7fb99fb27
b3d57eabfafd0f76a28a2b88ec0a28a2800a28a2800af94fe1c7fc555fb7ff00c4cd53efa7873c
3d69a403d42f9cc26c7e86beab240049e00ef5f2c7ec60875ff885f1e3c5ec371bff00147f6687
f516aa547e920aeca1a53a92f2b7ded1c95b59d38f9dfee4cfaa2be57fdb8e53aceadf05bc2aa7
3fda3e31b6bc74fef240096fd24afaa2be53f8da7fe128fdb7be07e8a7e78b47b3d4b54953d9e3
08a4ff00c0905185d2a73764dfdc9862b5a7cbdda5f7b47d4cf690cb6df679224961dbb4a3a82a
47a106bc33e267ec63f0f7e20debeab656b3f84bc444ef5d57437f25f7fab28e1be878af79a2b9
e15274dde0ec6f3a70a8ad3573e49f2ff68bfd9fc92861f8c1e178bb1f935144fe6e71d8715dcf
c33fdb4be1f78f6fd748d4ae66f07f88c36c7d2b5d4f21f7ff007558f0c7e95efb5c37c4bf821e
05f8c162d6be2ef0cd8eb195dab71247b274ff007655c38fa038ae8f6b4ea7f163af75a7e1b7e4
61ecaa53fe1cbe4f5fc77fcced609e2b9896586449636195746c83f8d495f25dc7ecc5f143e0ac
c6f3e0cfc45b8bad31391e16f161fb4db91fdd4947cc83d0003dcd5ed17f6d79fc177d1e8ff19f
c11a9f802ff210eab021bad3643fdedebca03d87cc6878672d68be6fcfeeff002b82c428e95572
fe5f7ff9d8f55f1dfc143e36d7a6d4e6d5dd0b00b1c223c04006319c9cfe95cdd97ecf9ab6897f
15e697ad4715c4672aecccbfc96bd67c27e37f0ff8ef4c4d43c3dac596b366c01f36ce65900cf6
20720fb1c1adcaf85c470964f88c4cb17568fef5bbb7cd24efdf47a1f55473ecc2951542153dc4
ad6b45ab7dc53d252f63d3a04d41e292f028123c39da4faf207f2af2bfdab7e2c9f83bf0535dd6
2de411eab711fd8ac39e7ce93e50c3dd412dff0001af60afcfcff829b78c5ee75cf07f85a373e4
c292dfce9eafc2a1fc8bd7d355a8b0f46551ed157fb8e4cb3033cd31f47054fe2ab38c7ff0276f
c0f8901662ceec5a47259989e493d68a28afc66a549559ba937abd4ff4cb0583a397e1a9e130f1
b4209452f24ac1451556e755b2b2904771796f0487a24b2aa93f813509393b247454a90a4b9aa4
925e6ec5aa28a827bfb6b59a28a6b98a1965388d2470ace7d81eb4926f4454e71a6b9a6ecbcc9e
8a805fdb35db5a8b888dd28dc610e3781ebb7af714457f6d35cc96f1dcc525c47cbc4ae0bafd47
514f965d88f6d49bb732dedbadfb7af913d1451526c753f0b7c7d77f0bbe21e87e27b29191ec6e
14ca07f1444e1c1f5e3f5c57ed2f87f5983c45a1d86a96ac1edef2049d0a9cf0c335f860ebb948
f515fab1fb0878d1bc5dfb3de8f14afbe7d2e47b2209cb6d53c13f5c9fcabf46e1dc4ba9425465
f65e9e8cfe31f19725860b36a599525655e3aff8a3657f9a6bee3e87a28a2beb4fe7a0a28a2800
a28a2800a4270327a578e7c76fdaa7c15f01ad5e2d4ee4ea5aeb2e62d22c981949ec5cf441d393
cfa035f9f5f173f6e6f895f136e2686cb51ff8457476c85b3d2c9590affb529f989ff74a8f6aed
c360ebe325cb4637fcbef38f118ba1848f35695bf3fb8fae7fe0a13e2fb49be11e97e108b51822
ff0084935bb3b0bc944a316f6e240ef239cf0a0a2e49f5aef2d7f6b2f839e16d32d34e8bc63a73
456b12c2ab6d2075000c718fa57e44dedf5cea572f7179712dddc39cb4b3b97763ee4f26a0c57d
543877113a5184e695aefabdede9d8f98967f4215253841bbdbb2dbef3f64b4afdadbe126af204
8fc71a5c4e7a09e6084fe75e95a278af46f125ba4fa5ea9697f138cab41286cd7e11e2b53c3fe2
8d67c297ab79a2eab79a4dd29c896ce7689bf12a466b9eaf0d6262af4e6a5f81d14b88b0f276a9
16bf13f48be1b7ec96b37ed73e3bf89fe20b35feccb7bd56d16de45c892531a83363d179c7b9f6
afaeebf327e0bffc144fc63e0d9a0b0f1a409e2bd2010ad72008af235f5047caf8f42327fbc2bf
403e167c64f09fc65d09754f0bea91de4600f36ddbe59a13e8e9dbebc8f435f3f8c86229cd4711
169a497dc7bb849e1e7072c3bba6eff79db51456378bfc5da47813c397daeeb97b1e9fa5d9c664
9a794e0003b0f527b0ae149b76476b696ac3c61e30d23c07e1cbed775dbe8b4ed2ece332cd7133
602803f9fb57c9be1bf0febffb6ff8ba0f14f896dee746f841a6cfbb49d1e5ca3eaaca7fd7483f
bbc51e1ff0debdfb7178ca0f12f8a6dee746f835a54fbf4cd0dc949359914f12cddfcbf6fcbd47
d15f187e28687fb3f7c2dbef125e5b469a7e9b1a456d6106221237448938c0e071c7415e8457b0
6a10d6a3fc3cbd7f2381bf6eb9e7a535f8ff00c0fccee6c6c6df4bb282d2d214b6b6850471c51a
e1514700015e17fb43fed247e1fdedb782bc1767ff000927c48d546cb4d3a0f985b03ff2d65c7d
d03af3e95c178abf6dc5f88fe1dd1b42f8316326bbe3df1043c473211168e0f0d24c48c12bd874
3c7d0fa87ecedfb3669ff05ac6eb55d52f1fc4de3dd58f9dab7886efe696573c944cfdd41e9dfb
f602552543dfaeb5e8bbfaf97e653aaeb7b941e9d5f6f4f3fc8cff00d9e3f66c1f0eae6e3c61e2
fbbff848fe236a9f3de6a73fcc2df3ff002ca2cf403a71e95ef34515c952a4aa4b9a4754211a71
e58915c5bc57704904c8b2452294746190c0f506be3ff054b2fec77f1ee6f05ddbb27c2ff1a4ed
75a24f21fdde9f764fef20cf4009231ff01f5afb16bcebe3e7c1cd3be38fc36d47c3779886ec8f
3f4fbc5e1ed6e5794914f6e783ec4d6b42a28b709fc2f7ff003f919d6a6e494e1f12dbfcbe67a2
0390083907bd7c95fb48e8977f003e2ce91f1d3c3d039d2a729a6f8b2d211c49092025c103baf0
09f61eb5d9fec91f19350f17e87a8781bc5ffe8fe3df09bfd8efa3718371129c24cbea08c67f0f
7af70f1378734ff17f87f50d1755b75bad3afe06b79e17190cac307f1ee0f638aa8b786aae32d5
6cfcd3feae8992588a69c747baf27fd6e49a0eb767e24d1acb55d3e65b8b2bc89668654390cac3
22afd7c9bfb2f788f50f82bf10f58f811e28b8674b62d79e18bd98e05c5a1e7ca19eea3b7b7a9a
facab2ad4fd94adbae8fba34a553da46fd7afa851451589b05145140199e26be5d33c39aa5db30
410dacb264f6c2935f3e7fc13e2c5bfe19e22d6e452b2788758bed5989eac5a5d99ffc875e85fb
527884f85ff67cf1e6a28fb258b4b9bcbe7ab15e0537f655f0e8f0b7ece7f0fb4f0a131a545718
ff00aeb997ff0067aeb5eee1e4fbb5f827fe672bd710bc93fc5aff0023d5abe53f0f0ff84abfe0
a25e23bb6f9e2f0f783e3b21fecc924e241ff8eb357d595f2bfecadff1527ed13fb42f8a5be659
353b1d3a161d079313ab8fcc2d3a1a42a4bcbf3690abeb3a71f3fc933ea8a28a2b8ceb0a28a280
0aa1ad683a6f88ec64b3d52c6df50b5901568ae230ea41ebd6afd146c1b9f3278b7f61fd12d354
935df867af6a1f0e35d04ba8d3e43f6563e863e801ef8ac41f19fe38fc05cc7f11fc1c3c6fe1d8
786f10f870664451fc5247d87a93c9afada8aeb5889356aab9979eff007ee72bc3a5ad37cafcb6
fbb6393f85ff0012f46f8b9e0db3f136826e0e9b75b827da61689c152558153cf041afce0ff828
45f1bcfda3654272b0695046067a1dcfff00d6afd46b7b686d23f2e089218f24ec8d428c9ebc0a
fcbfff008287e9af65fb4389ca911dce950b2b1ee433e7f98af0337d7075b97b1fa4787ee31e27
c07b4fe75f7d9dbf13e66a28a2bf203fd15193b48b0486250f28525149c0271c0af0dd16d751f1
07c54bf5d4b49b6ba990a99e0926cadba6541643dc807a7bd7bad79b7852c2e61f8bde25b992da
64b7921c24cc8423731f43d0f435ee65d57d953aed257e5d3beebccfcbb8cf2f78fc5e55094a5c
9edbde4926be093bb4e2fb5b5d357a5ecd58d6be216b5a719e68f46820b38c900df5c08a4703b8
5ebcd64dc7c42b0f106a7e12b83a3c1712dd5cf94249c9df6ee1d012bf983f856069fa6dcdadce
b316b7e1ebcd635c99d85bdcb296880231d49c0e79accf0ee8da8c3a8f84e1934fbb46b5d499a5
2606da80c91f24e318e0f35ef53c1e16316ecaebaa7ba717e6defe9e87e498be24cf2bd58c1ca4
e151abc2504dc1c6b4159feee314f96ef9539596bcd7b33b9d3ffe4be6a7ff005e63ff0045c753
f842cda3f8b9e2994fdd68863f12bfe1458d85cafc71d46e8dbca2d5ad02898a1d84ec8f8ddd3b
56bf87ee03fc40d790699756e7cb506ee46cc52e08fba368c75f53d2bcdad3b41a8ebfba8afc51
f6f96e154b130955f75acc2bc968f5f7676d93fbdd9799d9514515f2e7eea15f7fff00c1307539
27f0ef8eac19898ad67b47407a02ff0068cffe822be00afd07ff0082636892da783bc65aa32622
bdb8b68d1bd4c7e767ff004315f67c337f6b53b597e67f34f8dee3f50c127bf3cbeee5d7f43ed7
a28a2bf403f90828a28a002be4ff00db17f6c18be115b4be15f0bcb1dc78ae78ff007b3039164a
4753fed7a0af52fda83e3a5b7c05f85f7bac2b23eb775fe8ba65bbf3be661f788feea8cb1fa01d
ebf1e75ad66f7c45ab5dea7a95cc9777d77234b34f2b166762724926bdbcab2e96615acf48addf
e878f99e611c052bad64f65fa86b3ad5f788753b8d4752bb96f6fae18bcb3ccdb9989f7aa74515
fabd1a34f0f054e92b247e5f56b54af3752a3bb61451456c641451450015d57c36f89de21f84fe
25b7d6fc3b7f259dd44c0b22b1d92af7561dc572b45726270b4b174dd3acaebf2f43ab0d89ab85
a8aa527667ec6fecd5fb4668ff00b40f8405dc252d75db4016fec33f321fefaffb26bd43c47e1a
d2fc5fa3dc695acd8c3a969d700096dae177238073c8afc5af831f16f58f829e3fd3bc4da3b92d
0385b8b52d84b9849f9e36f623a1ec707b57ecd781bc69a67c43f09e99e22d1e7171a76a10acd1
377008e87d08e8457e4b8fc154cbebba72f54fba3f52c0e3218ea2aa2f46bb335ac2c2db4bb282
cece04b6b5810471431aed5451d0015f993ff0522f8bba8fc4df89963f0bfc3314fa8dbe8c435d
4368a5ccb76c3eee075da303d8eeafd3d3cd727e0ef84fe12f00dcdddde87a15a5a6a17923cd75
a814f32e67763966795b2ed9249e4e2b1c2d78e1ea7b592bb5b7a9ae268cabc3d9c5d93dcf84ff
0060efd96fe30fc30f1cdb78b7508adfc37a1dc47e5de586a0333dc447b041ca374209c74afd19
a28a8c46225899fb49ad7c8bc3d08e1a1ece2f40a28a2b94e90a28a2803e58fdab7c07ab7803c4
9a5fc72f04dbb3eb5a0e1759b28b8fb758ff001ee03a9033f866be84f879e3dd23e27f82f49f13
e8570b73a66a502cd1303cae7aab7a329c823d41adeb9b78aee09209a35961914a3a38c8607a83
5f1f7815e5fd8e3e3e4fe09bc9197e16f8d6e1aef4299cfc9a6de1fbf6d9eca4e31ff01ea4b1ae
e8ff00b453e4fb51dbcd76f96e8e297ee2a737d996fe4fbfcfa9e8dfb5d7c1ed43c6fe15b3f177
853741e3bf0a48350d366887cf285e5a2f70403c7ad777f00be3169df1cbe18e93e28b12239e54
f2af6d73f35b5caf1246476e791ec41af44e1d7b3291f506be3cd617fe18f7f693fed78ff71f0b
7e224d8bc5e9169ba9ff007fd155fafe27a041453fdfd3f65f696abf55faa1d4fdcd4f69d1e8ff
0047fa33ec4a2b84f879f1bbc1bf15757d6f4ef0b6b11eaf2e8eeb1dd4908fdde587f0b7f163d4
715ddd71ca2e2ed256675464a4af1770a28a2a4a3e69ff0082826aed63fb3e5c58c67f7da9ea36
96817fbcad200c3f235f41785b471e1ef0c691a528016c6ce1b6007fb0817fa57cd3fb69e3c45e
36f82be135391a9789636993fe998c609fa115f55575d4d284177bbfc97e872c35ad37dacbf5fd
4afa8dc8b2d3eeae0f02189a4fc8135f33fec036df6af875e36f10b0cbebbe2fd42f15fd63ca05
fd7756f7ed27fb577837e0c45a9f8675a92f6db5bbcd36492d185bee864dca401bb39ea7d2b8ff
00f827dfc51f044ff047c29e09d3fc416f75e2c821b8b8bdd3d5241229333b6492b838564e41ad
634a71c34a7caecdafbb53295484b1118dd5d27f7e87d654514579e7785145140051451400515e
73f103e32c1e03d4bec2fa4cf753150cae5c468c0fa1c1cfe55c55a7c7bf1178a356874fd1346b
48e599b6813169368f52411d3e95f1d8ce2dca705887839d472ab7b72c6326efdb6b7e27d0e1f2
1c7e2697d62304a16bf33692b77dcf7baf83ff00e0a6fe086307843c5d0c47645249a7dc381fdf
01909fa6c23f1afb974b86e61b0856f2613dced1e6385da0b77c0ec2b86fda03e1643f193e12f8
83c2ef85b9b980c96921fe0b843be339f4dca01f626beaa7055e938495b996dea79d81c5d4cb71
94b1745fbd4e4a4bd62eebf23f1968a9af2c2e74abeb9b0bd85edef2d6468668a418647538208a
86bf1aad46542a4a94f74ec7fa61966614335c152c7619de15126be7d3d56cfcc28a28ac0f4c28
a28a0028a28a0028a28a00491b6a31f6afd6bfd8b3c0afe04fd9f7c3f0cd118aeafc35f4c8c305
59cf4fd33f8d7e6afc03f85d75f187e2be89e1d8232d6a651717af8caa42a416cfd781f8d7ecb6
9f630e99636f676ebb20b78d628d7d154600fc857e93c3d867470eeacb79fe48fe27f1833c8663
9cc32fa2ef1c3ab3ff001cb57f72497adcb1451457d51f82051456078f7c451784fc1babead33f
9696d6ecc1fd18fcabfa91401f981fb79fc5993e237c6bb9d2ade7f3348f0f2fd92155395694e0
c8df5ced5ff80d7cdb5735ad566d7b59bfd4ee0e67bdb892e2439fe2762c7f5354ebf5dc9b0cb0
d8282eb2d5fcff00e01f9566f88788c5cdf48e8be5ff000428a28af6cf1c28a28a0028a28a0028
a28a002befeff8268fc5979ed75af005ecfb841fe9b60ac79da4fef147b03cff00c0abe01af5ef
d92fc6127827e3ff00852f44863826b8fb2cf83f7a37ea3f302be5f8870caae13daf583fc1e8cf
a4c8710e962bd9f497e6b547ec9514515f979fa48514514005145140051451400579d7c7bf83ba
7fc70f86fa87872f3f7374479f6176386b6b85e51c1edcf07d8d7a2d1551938494a3ba2651538b
8cb667cf9fb257c62d43c5da2ea3e07f1766dfc79e147fb25f45270d3c6384980ee08c66bc7ffe
0a41f0abe29f8d7c3f0ea3e1ebe7d57c196604d75a1db4404b13a83fbd38e5c609f71cf6aef7f6
adf026ade00f12e93f1cbc116e5f5bd070bacd8c79c6a163fc6180ea5467f0e9cd7d09f0ff00c7
5a3fc4ef05e93e26d0ee16eb4bd4a059a36eeb9fbc8c3b329ca91ea0d7a2aa7b19c7154d2b3e9d
9f55fe479ee9fb684b0d51eabaf75fd6e7e657fc12cfc5c743f8ddac787e6664fed5d39d5236e3
0f19de4e3d70a6bf55ebe7cd67f645d0b4ff008e7e1ff8a1e0ef2fc3fab5b5c83a95944b8b7bb8
5b890851f71f04f4e0f71debe83a8c7568622afb58755afa9782a33c3d3f653e8f4f40a28a2bcf
3bcf957e27e3c55fb767c30d281dd0e91a55cdf4a3b2c832c87f2afaaabc3743f839af45fb5878
87e236a0d6a7429b4786c74f58e42d2ac8387dca540008f426bdcaba6b493508ae8bfe0fea73d1
8b4e6df57ff03f43f3cffe0acde0b1269be0bf154719678de4b09180fbabf7c67f135d9ffc132f
e010f03fc3cbaf1feab6db358f10feeecfcc5f9a2b453d47a6f6c9fa2ad7d0ff00b457c10b4f8f
be05b7f0d5e4c2da25bf82e5e6c658223e580f72062bd1f49d2ed343d2ecf4eb1816dacad21482
085061511405551f400575bc63faa2c3aefafa1cab08beb6ebbeda7a96e8a28af2cf4828a2b95f
15fc49d17c26de4cd335ddfb709676a37c8c7d0e3a751d79f6ae5c4e2a860e9bad889a8c57566f
46854c44d53a51726fa23a87916352cec1540c924e00ae03c49f172d6caf0e99a25b49aceac7e5
58a119507be71cf183ff00d7ac95d27c59f135d65d4e66f0f686dc8b4b76fdf48a7fbcd5dff86f
c27a5784ed05be99671dbae3e67032eff563c9af03eb38fccf4c247d8d2fe792f79ff860f6f59f
fe02cf57d8e1705ae21fb49ff2c5fbabfc52ebe91fbcf1ff0016fc2bf1578b74c9b57d5af04ba9
20fdd584437607a0c703af6f7aed7e11fc348bc15a4adcdd44adab5c2e5d987318fee8f4f7af43
a2a70bc3397e171cb3149caadadcd27777fe6d7adb4ec968921d7ceb175f0df536d2a77bd92b7c
bd3afaee1451593e26f1668de0cd2a5d4f5dd52d349b08812f7177288d477c0cf53ec39afac49b
d11e0b696acf85bf6fafd9a67b4d466f895e1bb4325bcd8fed7b6857251bfe7b60763dfdfeb5f0
fab06190722bf5c7e1cfed31e16f8efe2fd43c33e1dd1353d5f404b77f3b5e9ed4a584c7a18d4b
72d9fc3e95f27fed57fb0fea3e0cbcbcf15fc3fb47bfd064265b9d22305a5b53d498c7f127b751
db3dbe6b3bc9a588fde415aa2e9dd7f99fb9786de224787e5fd9f8f9736164f46b5e47d5f9c5f5
4bd5753e3fa2901f999482aea70cac3041f42296bf349c254e4e135668fed8c2e2a86368c71186
9a9c25b34ee9fcd051451599d41451450014f8209af2e62b6b689e7b999824714632cec78000ab
3a268ba8f89f56b7d2b47b29b52d4ae1b6c56d6ebb998ff41ef5fa39fb22fec6307c2e6b7f1778
ca38ef7c5646eb6b5e1a2b0f71eb27bf6edcf35f4d95e4f53172552b2b43f3f4ff0033f10e3bf1
1b09c3f46782cba6a78a7a69aa879cba5fb47eff003eb3f634fd9c3fe147f81cdfeb110ff84b35
85596f33d6dd3f8611f4cf3ee4d7d154515fa5c62a29463b23f87ead59d69caad477949ddb7bb6
f76c28a28aa330af0dfdb6f529749fd983c6b750b15910598041c1e6f2053fa1af72af20fdadfc
392f8b7f678f17e9702ef9658eddc0c67ee5cc4e7f453401f8da3a52d20e94b5fb7e19a7420d6d
65f91f8d621355a69f77f98514515d273851451400514514005145140056ef80e636fe39f0ec8a
c54aea36fca9e7fd62e6b0aba6f861a6cdabfc47f0cda4033349a8c054633d1c1fe95e4e6cd2c0
d5bf63d4cad378da56ee7ee35bcbe7dbc527f7d437e62a4a6a2044551c051814eafc74fd6428a4
041ce083f4a5a0028a28a0028a28a0028a28a008ae6da2bdb696099165865528e8c32181e0835f
2efc1df067897f672f8f7abf822c34ebbd47e17f89049ab69b7112168f4a9f23cd898f4552718f
f80fa9af4bf8e9fb4e783be02e9f9d62e4deeaf22930695684195cf6ddfdc1ee7f235f9dff0018
ff006dff0088ff00156e2682d3506f0a68a490965a539472bfedcbf789fa6d1ed5e960b0f88c4b
953a30e64f7ecbb3b9e7632bd0c3a8d4ad3e56b6eefcac7e9c78c3e33f81fc02a4ebfe27d374d6
c70935c2863f419af2bd4ff6f8f839a5ccd1b6bd717041c6eb6b37917f315f935713cb773bcd3c
8f34ce773492316663ea49eb51e2be8e970c5592bd5a897a2bff0091e054e23a49feee9b7eaedf
e67eb369ff00b7e7c1bd42611aebb7501271ba7b278d7f335e9fe0ef8ebe01f1f32a685e2bd32f
e6232618ee1778fa8cf15f8958a723b4522ba31475395653820fa8a753862aa5fbba89faab7f98
a9f12526ff00794daf477ff23f7b55d6450ca4329e410720d3abf20be117ed95f12be135c451a6
b0fe20d25480da7eaec6618f4572772fe78f6afd0ff803fb5a7837e3cdba5b5a4a747f112ae65d
26edc6e3ea636e8e3f23eddebe5f1582c460e5cb5a36fcbef3e930d8ca18b8f35195ff003fb8f6
ea28a8ee2e23b4b796799c47144a5ddcf40a0649ae06edab3b7724ac8f10f8af4bf0b5a1b8d4ae
9205e817ab13ec3f035c3ea9f14750f115d369de0dd3daedcb6c6d46752214fa0eff008d5df0ff
00c26b7174baa7896e1f5fd54f39b8ff00531e7b2a74fe62be6659ad5c64bd9e550e7ef37a535e
8f79bf28e9de48f696021875cf8e972ff756b37fa47e7af64cc597c47e2df893308b41b77d1b47
279be97e52e3a1c679fc87d6babf09fc2fd23c2e44ec86ff005023e7b9b8e4939cf00f03a0fcb8
c575ea8a8a15542a8e00030053aba70d94c2151627172756aafb4f65fe18ed1fcfbb6635b1f294
1d1a11f674df45bbff0013ddfe5d909d2968ac8f13f8b745f056932ea7af6a96ba45844096b8bb
9446bd33819ea7d8735efa4de88f29b4b566bd6478a3c5da2f82b499f54d7754b5d274f8177497
175284551f535f356b9fb5ff0088be27ea12e87f02fc1d3789a6dc637f12eacad069b0f62cbd1a
4c7d41f63537857f62f9fc65ac41e25f8dfe2abcf889aca37991e921cc1a5dab7a2c4b8dd8f5e0
1ee0d762c3aa7ad77cbe5bbfbba7cce4f6ee7a5157f3e9f7f5f9106adfb5e7887e2a6a33e87f03
fc2573e24955bcb93c457e862b080fa827aff23573c31fb1bdc78c7568bc45f1a3c4d71e3ad581
de9a52b14d3e03d7684fe21ec7f0afa4f46d134ff0ee9d0e9fa558db69b6300db15b5a44b14683
d02a80055ea4f11c9a515cbe7d7eff00f21aa1cfad67cde5d3eeff0032868ba169de1cb08ac74b
b282c2d2250a90dbc611401d381578a865208041e0834b4571ee75ec7cf5f1bbf629f037c5f966
d46084f8775e704fdb2c940576f574e87eb5f19fc42fd82be28f82a4964d32ce1f14d8af224d3d
b321f6f2cfcc4fe15faa34571e23074314ad5a09ff005dcfa3ca388f36c865cd9762254fba4f47
eb1774fee3f0ff005ff0078a7c2aec9acf87353d31d4e08b8b665c1fcab185a5d1207d8ee727a7
ee5b9fd2bf766a35823472eb1aab9eac00c9af1a5c3d826eeaebe67e994bc61e26a71e593a727d
dc35fc1a5f81f8b1e18f82fe3ef19c88ba2f84356be57ff96896cdb07b938e057d09f0cffe09cd
e34f11cb0dc78befedfc3762482f6f0b09ae0afb6381f8e2bf49e8aeca19460f0ef9a30bbf3d4f
99cd7c44e25ce20e956c4b8c1f48251fc56bf89e65f07ff676f04fc13b111787b4b4178c079b7f
71f3cf21ff0078f4efc57a6d1457b27e6edb6eec28a28a0414514500154f58d35357d26f2c6500
a5cc2f11cfb8c55ca2803f0cfe24f84e6f02f8ff00c41a04d1b44d617b2c2aadd766eca1fc54a9
fc6b9bafb5ff00e0a47f05e4d1bc55a7fc43d3add8d8ea405a6a2547093a8fddb9ff0079723fe0
03d6be28afd5b22c52c461230bfbd0d1fe9f81f98e7585787c5392da5aafd7f10a28a2be88f002
8a28a0028a28a0028a28a002be85fd853c08fe34fda0747b868b7da690ad7b2b1195040c283f5c
9fcabe79ce2bf47ff63cfd9aefa0fd9f359bb9754bef0bebfe2d8d5e1d46c709716b0020c5827d
7ef7638622be4788b1518508e193d64f5f45ff0004faac830d29d6788b6915a7abff00807da545
7c8517c41f8ebfb33116fe35d207c58f05c47035dd213cbd4604f59231c3e3d00c9eec2bdd7e13
7ed0de03f8d56425f0c6b90cf7407ef34eb8fdd5d447b868cf3c77c647bd7e7d3a1382e65ac7ba
feb4f99f770af19be57a3ecffad7e4792fed79fb235c7c64b097c45e0ed52e746f19dba65512e5
a386f00fe06e701bd0d7e5a6a5af7c49f08f89a6f0edeea3aed86b56f3985ec5e6904ab26718db
d6bf7b6bcebc63f007c15e39f881e1ef1aea7a4c67c47a2c9e641791e14ca3040594747033c679
1d8d7a183c7fb08f2548dd74febb1c18bc0fb6973d3959f53cc3f662fda47e1dea7e0bd07c21ff
00092c96fe24b2b75827b5d7330dccb2ff001637e37724f23d2be928e449503a30743c8653906b
ce7e297ecebf0efe325bc8be2af0b595f5cb0c0be8d3c9b953d889530dc7a1247b578949fb38fc
60f823235cfc24f89136bba3c6723c31e311f684da3f852618651d80017dcd71b8d1acdb8cb95f
67b7debf5475a955a49294799775bfdcff00ccfad68af96747fdb667f06df2695f18fc09aaf806
f0108daa4086eb4e63fdedebca03e9f31afa1bc1fe3ff0dfc41d356ffc37add8eb36ac01df6930
72b9fef2f553ec40358d4a35296b25a77e9f79b42b42a6917af6ebf71d057cdbfb5efed5d6bf02
b451a368cf15d78c2f63cc716722d633c798c3d7d07b57ab7c6ef8b1a7fc17f873aaf89eff000e
6de3c5bc19c19a53c228fa9c57e32f8d7c63ab7c41f156a5e22d72e9aef53d426334d237419e8a
076503000ec00af432ccbe59856e4da2b77fd756706638e8e028f3ef27b2febb15fc45e24d4fc5
bacdceababde4b7f7f72e5e49a66c924d66d1457eb542853c34153a4ac91f96d6ad53113752abb
b61451456e6214514500156b4bd56f344d46deff004fb996cef2070f14f0b6d6461d0835568ac6
b51a75e0e9d5574cd69559d09aa94dd9a3f4fbf636fdafa3f8b7691f857c513470f8aa04fdccc7
8178a3b8ff006abeb0923596364750c8c08653d08ef5f83fa0ebb7de19d66cf55d32e5ed2fed25
59a19a36c32b0391cd7ec6fecd7f1aed7e3afc2dd3b5e5644d5221f66d4605fe09d40c9c7a30c3
0fa91dabf27cd72e797d6e55ac1edfe47ea196660b1d4b99e925bff99e97a7e9969a54021b4812
08c7f0a0ebf5f5ab54579efc70f8dfe1bf807e06bbf12788ae0054056d6c91809aee5ec883f99e
c3f23e353a776a9d35e4923d79cd24e73677a6e621702032a098aee11ee1b88f5c567789bc59a3
7833499f53d7353b6d2ac205dd25c5d4a11147d4d7e379fdb57e235ffc793f10a1bfb78afa50d6
76f637418d9dbc0e70136820e06739eb9e6bef6f037ec807e265c69fe32f8cbe31baf893793225
d5ae970c860d2600c32a5235c6ee08e78c8ea0d7ab5b01f56b3ad2b27db7f4ff0082799471bf59
baa31d577dbd476b5fb5ef887e296a53e83f03bc2771e25994f9727886f50c56101f50c783fc8d
59f0bfec6773e32d5e2f11fc69f13dc78eb56077a6948e534f839ced09fc43d8fe06be97d1743d
3bc39a6c3a7e95616da6d84236c56d6912c51a0f40aa00157ab95e23934a2b97cfafdffe474aa1
cfad67cde5d3eeff00328689a0e9be1bd3a2b1d2ac60d3ece250a90dbc611401c74157e8a2b8f7
3af60a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a28039
bf889e03d2be26f83355f0d6b31096c35084c6dc7287aabafb82011f4afc71f8d9f0775af823e3
abdf0feaf0b6c462d6b758f92e22cfcaca7e95fb655e6bf1d7e037873e3d784e4d235b83cbba8c
16b3d4221fbdb77f507b8f5078af47018ea980acaac3e6bba3cfc6e0e9e3a93a73f93eccfc59a2
bd3be377ecf1e2df813ae4969add9bcfa7337fa3eab021304abdb9fe16f63f866bcc6bf57c1e3a
863a1cf49faaea8fcc31782ad839f2555f3e8c28a28af40e10a28a2800a29338afa3bf66afd8d3
c49f1aafadf54d5e29b43f0923867b89576cb723aed8d4f63fde3f866bc9c7e6543010bcdde5d1
75ff00807a981cbab63a7682b47abe847fb1d7eccb73f1c7c6916a5aadbbc7e0fd324125d4a460
5c30e442beb9efe8335fac76f6f1da411c30a2c7146a1511460281d00ac7f05782b46f879e1ab2
d0741b18f4fd32d136c71463a9eecc7b93dc9adcafca31589a98baaeb547abfeac7e9f86c353c2
d254a9ad108ca1d4ab00ca460823835e15f167f63df047c4abd3acd8472f847c52a7745ac68c7c
a7dc3a165180c2bdda8ac215254dde0ec6f3846a2b4d5cf9197c77f1cbf6691e5f8c3496f8a1e0
c87fe633a50cdec083bc89d4e075278af71f84dfb427817e34d889fc33ae437170a3f7b6331f2e
e223e8d19e457a3919af0ef8b7fb20f817e285f1d6ece09fc1fe2e425e2f10787dfecb387f570b
f2be7b92327d6ba39e955fe22e57dd7eabfcbee39f92ad2f81dd767fa3ff003fbcf72a2be438fc
7bf1dff667220f196943e2d782e2381ade949e5ea5027ac918c87c7b024ff78572fe21ff00829c
7862cbe2ee8161a6dacb73e099ed55751ba9e231dcdadc337f77246106030f5ce0f1cd2c1d59ff
000fde5dd7f5f8325e2e943f89eebeccfb5b57d134fd7ecded352b282fad9c10d15c461d483f5a
f9e7c63fb0e78566d45b59f00ea9a87c39d7812eb3691291016f78f38ebd4d7d0da26b761e24d2
6d753d32ea2bdb0ba8c4b0dc42db95d4f420d5c7711ab33101546493d8573c2ad4a4fdd763a274
e1557bcae7e647edf3f10f517d5fc3bf0f27d5a4d58e876ab25fddb1e6e2e08c6e3ee0678af922
bb5f8d5e2b9bc6ff00163c53ad4e4efb9bf94e3d0038c7e95c557ea190e1d51c1a9f59eaff0043
f36ceebbab8b70e91d3fcc28a28afa23c00a28a2800a28a2800a28a2800afa9ffe09e7f1624f04
7c636f0d5c4db74af11c462d8c7e55b8405a36fcb7affc0857cb15b3e0bf10c9e12f18687adc44
87d3af61ba18efb1c311f8818af073bc32c460a6fac755f2dff03dbc9b10e86322ba4b47f3dbf1
3f75ebc03e30fec6de16f8f3e2d1adf8cf57d5efe2893cbb6b0b79fc98add7bed033c93d4d7b9e
917bfda5a4d9dd820f9f0a49c7ba83572bf29a752749f341d99fa74e9c6a2e59aba3e72d0bfe09
fbf04f430bff0014b9d431ff003fd31973f5e057bf683a158786347b3d2b4bb64b3d3ed2311416
f1fdd8d07403daafd14e756a54f8e4dfab142953a7f0452f40a28a2b2350a28a2800a28a2800a2
8a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a280337c43e1b
d2fc59a54fa6eb16106a3633295782e1032907eb5f1f7c5bff00826d681afcf35f7823553a0cef
93f61ba05e0cfb11c8fa62bed3a2b48549d297341d9f9113846a47966aebccfc88f18fec43f177
c2123e3c332eb108242c9a5b0b82c3d76ae48fc6bcdefbe0d78ef4d90c775e11d62ddc1c1592cd
c107f2afdbfa2bdba79ee3e9ab73dfd523c5a992e0aa3bf25bd1b3f1274bf813f1135a9152c7c1
5addd31ff9e564edfc857adf813fe09fff00153c5d2c4fa85841e1cb37eb2dfca038ff00b663e6
fd2bf56e8a9ab9de3aaab39dbd158ba59360a93ba85fd753e5df835fb01f817e1c4b06a1ae16f1
4eaf190ea6e571046dec9df07a135f4edbdbc569024304490c2836ac71a85551e800e952d15e24
a4e6f9a4eecf623151568ab20a28a2a4a0a28a2800a28a2802aea714f369d751da98c5cbc6cb19
9bee06238cfb66bf303c6bff0004c0f8a3a8eb1a86aabe22d0f57bcbd9e4b994c65e2dceec589f
98003935fa93457661f15570adba7d4e4c46169e252553a1f14fec7bf0ff00e3b7ecf7a9a785fc
57a1a6ade07b87c473dbdf472bd8b1fe20a189dbea2bebef18ccd6de11d7265c868ec67718f511
b1ad8aa5ad589d4f47bfb30706e20921cfa6e523fad655ab3af3e79249f91a51a4a8c7922db5e6
7e13eb3219758bf73d5ae2463ff7d1aa95a7e29b56b1f136ad6ec08315dca9c8f4735995fafe5a
d3c1d26bf951f94e609ac5d54fbb0a28a2bd23cf0a28a2800a28a2800a28a2800a43d296952369
5d63452cec42a81d493dab8b1cd2c2d56ff95fe47660d3789a697f32fccfdbcf83376f7df0a7c2
b70f92f269f113bbafddaeceb9df877a57f62781340b1ce7c8b28973ff000115d157e287ec2145
145001451450014514500145145001451450014514500145145001451450014514500145145001
451450014514500145145001451450014514500145145001451450014514500145145001451450
014514500145145007e3e7ed91e0093e1ffc7ef11c022f2ad2fa417b6fb471b1fb7f9f5af12afd
32ff008288fc147f1af802dbc63a65b99753d0b3e7841cbdb1fbdc77c707e82bf330735fa5f0ee
2d55c3ba0deb1fc99f9d67f8574b11edd2d25f9a168a28afad3e5c28a28a0028a28a0028a28a00
2bd23f671f02cdf11be377847468e3f32337a9733e4702288f98d9f62171f88af37afd0dff0082
6d7c137d2348d53e22ea96e52e2fd7ec5a6071c8841cc927fc098281fee1f5af97e20c5aa185f6
29fbd3fcbaff0091f4991615d6c4fb57b43f3e9fe67dc1144b04491a0c2228503d00a7d1457e5e
7e9214514500145145001451450014514500145145001451450014514500145145001451450014
514500145145001451450014514500145145001451450014514500145145001451450014514500
145145001451450014514500417b670ea16935adcc6b341321478dc643291820d7e4dfed7ffb31
de7c0af194ba869b03cde0fd4a42f69381916ec7930b7a63b7a8fa1afd6bac4f19783346f1ff00
872f342d7ac62d474cbb42924328cfd181ec47622baf0b89a983aaab527aafc7c8e5c4e1a9e2e9
3a55168cfc2aa2be98fda53f628f11fc1ebdb8d5bc3f14faff0085598b2bc485a7b51e8ea3a81f
de1f8d7ccd9e6bf56c0667431f1f71da5d575ff827e638ecb6b6065ef2bc7a3e9ff005a28a2bd7
3ca0a28a2800a292bdff00f676fd8f3c59f1c6fe1bcba865d07c2aac0cba8cf1e1e55f4894f527
fbc7819efd2bcac766543010bd4779745d4f4b0597d7c6cad0565d5f4323f660fd9db53f8f9e37
860f29e0f0ed9babea17b8e02ff717d58fa57ebd683a1d9786745b1d274e816dac2ca158218907
0aaa300562fc37f86ba07c29f0b5a681e1db18ec6c60500ed1f3caddd9dba927d4d7535f94e331
7531b59d6a9bfe4bb1fa7e130b4f074952a7ff000e145145711d81451450014514500145145001
451450014514500145145001451450014514500145145001451450014514500145145001451450
014514500145145001451450014514500145145001451450014514500145145001451450014514
500326852e2268e54592371864619047a115f3a7c62fd85be1efc52926beb381bc31ac484b35cd
828d8ec7a964e84fbd7d1d4534dc5dd3d44d292b33f2ff00c71ff04e2f88fa04923e853d8788ad
c1254472889c0f70f8c9fa5790eaff00b2dfc58d16678e4f00ebd7057f8acf4f9a753f428a41af
d9ea2bd8a59c63a92b46a37ebafe67935329c1557774d2f4d0fc5dd2bf662f8afab4a91c7f0ffc
436e5ba35d69934207d4b28c57ac782bfe09d5f13bc472236aff0061f0edb1c1dd73309188ff00
753241fa8afd4aa29d4ce71d5559d46bd2c854f28c1537754efeb767cbff00087f602f00fc3b9a
2bed6b7f8ab53421835d2ed850fb277fad7d376d6b0d95bc705bc4904318da91c6a15547a002a5
a2bc7949c9de4eecf5a3151568ab20a28a2a4a0a28a2800a28a2800a28a2800a28a2800a28a280
0a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2
800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28
a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a
28a2800a28a2800a28a2800a28a2800a28a2800a28a2800a28a2803fffd9
}\cf7\highlight8\kerning2\f7\fs21\lang1033\par
\par
\par
\par
\par
\par
\par
\par
\par
\par

\pard\cbpat8\widctlpar\sb150\sl300\slmult0\kerning0\f2\'bc\'dc\'b9\'b9\'cf\'b8\'bd\'da\f7 :\highlight0\par
\highlight8 (1)\f2\'cb\'f9\'d3\'d0\'b5\'c4\f7 redis\f2\'bd\'da\'b5\'e3\'b1\'cb\'b4\'cb\'bb\'a5\'c1\'aa\f7 (PING-PONG\f2\'bb\'fa\'d6\'c6\f7 ),\f2\'c4\'da\'b2\'bf\'ca\'b9\'d3\'c3\'b6\'fe\'bd\'f8\'d6\'c6\'d0\'ad\'d2\'e9\'d3\'c5\'bb\'af\'b4\'ab\'ca\'e4\'cb\'d9\'b6\'c8\'ba\'cd\'b4\'f8\'bf\'ed\f7 .\highlight0\par
\highlight8 (2)\f2\'bd\'da\'b5\'e3\'b5\'c4\f7 fail\f2\'ca\'c7\'cd\'a8\'b9\'fd\'bc\'af\'c8\'ba\'d6\'d0\'b3\'ac\'b9\'fd\'b0\'eb\'ca\'fd\'b5\'c4\'bd\'da\'b5\'e3\'bc\'ec\'b2\'e2\'ca\'a7\'d0\'a7\'ca\'b1\'b2\'c5\'c9\'fa\'d0\'a7\f7 .\highlight0\par
\highlight8 (3)\f2\'bf\'cd\'bb\'a7\'b6\'cb\'d3\'eb\f7 redis\f2\'bd\'da\'b5\'e3\'d6\'b1\'c1\'ac\f7 ,\f2\'b2\'bb\'d0\'e8\'d2\'aa\'d6\'d0\'bc\'e4\f7 proxy\f2\'b2\'e3\f7 .\f2\'bf\'cd\'bb\'a7\'b6\'cb\'b2\'bb\'d0\'e8\'d2\'aa\'c1\'ac\'bd\'d3\'bc\'af\'c8\'ba\'cb\'f9\'d3\'d0\'bd\'da\'b5\'e3\f7 ,\f2\'c1\'ac\'bd\'d3\'bc\'af\'c8\'ba\'d6\'d0\'c8\'ce\'ba\'ce\'d2\'bb\'b8\'f6\'bf\'c9\'d3\'c3\'bd\'da\'b5\'e3\'bc\'b4\'bf\'c9\highlight0\f7\par
\highlight8 (4)redis-cluster\f2\'b0\'d1\'cb\'f9\'d3\'d0\'b5\'c4\'ce\'ef\'c0\'ed\'bd\'da\'b5\'e3\'d3\'b3\'c9\'e4\'b5\'bd\f7 [0-16383]slot\f2\'c9\'cf\f7 ,cluster \f2\'b8\'ba\'d4\'f0\'ce\'ac\'bb\'a4\f7 node<->slot<->value\par

\pard\widctlpar\sb150\sl300\slmult0 Redis \f2\'bc\'af\'c8\'ba\'d6\'d0\'c4\'da\'d6\'c3\'c1\'cb\f7  16384 \f2\'b8\'f6\'b9\'fe\'cf\'a3\'b2\'db\'a3\'ac\'b5\'b1\'d0\'e8\'d2\'aa\'d4\'da\f7  Redis \f2\'bc\'af\'c8\'ba\'d6\'d0\'b7\'c5\'d6\'c3\'d2\'bb\'b8\'f6\f7  key-value \f2\'ca\'b1\'a3\'ac\f7 redis \f2\'cf\'c8\'b6\'d4\f7  key \f2\'ca\'b9\'d3\'c3\f7  crc16 \f2\'cb\'e3\'b7\'a8\'cb\'e3\'b3\'f6\'d2\'bb\'b8\'f6\'bd\'e1\'b9\'fb\'a3\'ac\'c8\'bb\'ba\'f3\'b0\'d1\'bd\'e1\'b9\'fb\'b6\'d4\f7  16384 \f2\'c7\'f3\'d3\'e0\'ca\'fd\'a3\'ac\'d5\'e2\'d1\'f9\'c3\'bf\'b8\'f6\f7  key \f2\'b6\'bc\'bb\'e1\'b6\'d4\'d3\'a6\'d2\'bb\'b8\'f6\'b1\'e0\'ba\'c5\'d4\'da\f7  0-16383 \f2\'d6\'ae\'bc\'e4\'b5\'c4\'b9\'fe\'cf\'a3\'b2\'db\'a3\'ac\f7 redis \f2\'bb\'e1\'b8\'f9\'be\'dd\'bd\'da\'b5\'e3\'ca\'fd\'c1\'bf\'b4\'f3\'d6\'c2\'be\'f9\'b5\'c8\'b5\'c4\'bd\'ab\'b9\'fe\'cf\'a3\'b2\'db\'d3\'b3\'c9\'e4\'b5\'bd\'b2\'bb\'cd\'ac\'b5\'c4\'bd\'da\'b5\'e3\f7\par

\pard\nowidctlpar\qj\cf0\highlight0\kerning2\f1\par
\par
Server1\par
0-5000\par
\par
\highlight9\fs11 Hello1  1500\par
\highlight0\fs21\par
\par
\highlight9\fs11 Hello  500\par
\highlight0\fs21\par
\par
\par
\par
Server3\par
10001-16383\par
Server2\par
5001-10000\par
\par
\par
\par
\highlight9\fs11 Hello3  7500\par
Hello2  11500\par
\highlight0\fs21\par
\par
\par
\par
\par

\pard\nowidctlpar\s2\fi-567\li567\qj\tx567\fs36 3.2.\tab Redis\f2\'bc\'af\'c8\'ba\'b5\'c4\'b4\'ee\'bd\'a8\f1\par

\pard\nowidctlpar\qj\fs21 Redis\f2\'bc\'af\'c8\'ba\'d6\'d0\'d6\'c1\'c9\'d9\'d3\'a6\'b8\'c3\'d3\'d0\'c8\'fd\'b8\'f6\'bd\'da\'b5\'e3\'a1\'a3\'d2\'aa\'b1\'a3\'d6\'a4\'bc\'af\'c8\'ba\'b5\'c4\'b8\'df\'bf\'c9\'d3\'c3\'a3\'ac\'d0\'e8\'d2\'aa\'c3\'bf\'b8\'f6\'bd\'da\'b5\'e3\'d3\'d0\'d2\'bb\'b8\'f6\'b1\'b8\'b7\'dd\'bb\'fa\'a1\'a3\f1\par
Redis\f2\'bc\'af\'c8\'ba\'d6\'c1\'c9\'d9\'d0\'e8\'d2\'aa\f1 6\f2\'cc\'a8\'b7\'fe\'ce\'f1\'c6\'f7\'a1\'a3\f1\par
\f2\'b4\'ee\'bd\'a8\'ce\'b1\'b7\'d6\'b2\'bc\'ca\'bd\'a1\'a3\'bf\'c9\'d2\'d4\'ca\'b9\'d3\'c3\'d2\'bb\'cc\'a8\'d0\'e9\'c4\'e2\'bb\'fa\'d4\'cb\'d0\'d0\f1 6\f2\'b8\'f6\f1 redis\f2\'ca\'b5\'c0\'fd\'a1\'a3\'d0\'e8\'d2\'aa\'d0\'de\'b8\'c4\f1 redis\f2\'b5\'c4\'b6\'cb\'bf\'da\'ba\'c5\f1 7001-7006\par

\pard\nowidctlpar\s3\fi-709\li709\qj\tx709\fs32 3.2.1.\tab\f2\'bc\'af\'c8\'ba\'b4\'ee\'bd\'a8\'bb\'b7\'be\'b3\f1\par

\pard\nowidctlpar\qj\fs21 1\f2\'a1\'a2\'ca\'b9\'d3\'c3\f1 ruby\f2\'bd\'c5\'b1\'be\'b4\'ee\'bd\'a8\'bc\'af\'c8\'ba\'a1\'a3\'d0\'e8\'d2\'aa\f1 ruby\f2\'b5\'c4\'d4\'cb\'d0\'d0\'bb\'b7\'be\'b3\'a1\'a3\f1\par
\f2\'b0\'b2\'d7\'b0\f1 ruby\par
yum install ruby\par
yum install rubygems\par
\par

\pard 
{\pntext\f1 2\tab}{\*\pn\pnlvlbody\pnf1\pnindent360\pnstart2\pndec }
\nowidctlpar\qj\f2\'b0\'b2\'d7\'b0\f1 ruby\f2\'bd\'c5\'b1\'be\'d4\'cb\'d0\'d0\'ca\'b9\'d3\'c3\'b5\'c4\'b0\'fc\'a1\'a3\f1\par

\pard\nowidctlpar\qj [root@localhost ~]# \highlight10 gem install redis-3.0.0.gem \highlight0\par
Successfully installed redis-3.0.0\par
1 gem installed\par
Installing ri documentation for redis-3.0.0...\par
Installing RDoc documentation for redis-3.0.0...\par
[root@localhost ~]# \par
\par
[root@localhost ~]# cd redis-3.0.0/src\par
[root@localhost src]# ll *.rb\par
-rwxrwxr-x. 1 root root 48141 Apr  1  2015 \cf11 redis-trib.rb\par
\par

\pard\nowidctlpar\s3\fi-709\li709\qj\tx709\cf0\fs32 3.2.2.\tab\f2\'b4\'ee\'bd\'a8\'b2\'bd\'d6\'e8\f1\par

\pard\nowidctlpar\qj\f2\fs21\'d0\'e8\'d2\'aa\f1 6\f2\'cc\'a8\f1 redis\f2\'b7\'fe\'ce\'f1\'c6\'f7\'a1\'a3\'b4\'ee\'bd\'a8\'ce\'b1\'b7\'d6\'b2\'bc\'ca\'bd\'a1\'a3\f1\par
\f2\'d0\'e8\'d2\'aa\f1 6\f2\'b8\'f6\f1 redis\f2\'ca\'b5\'c0\'fd\'a1\'a3\f1\par
\f2\'d0\'e8\'d2\'aa\'d4\'cb\'d0\'d0\'d4\'da\'b2\'bb\'cd\'ac\'b5\'c4\'b6\'cb\'bf\'da\f1 7001-7006\par
\par
\f2\'b5\'da\'d2\'bb\'b2\'bd\'a3\'ba\'b4\'b4\'bd\'a8\f1 6\f2\'b8\'f6\f1 redis\f2\'ca\'b5\'c0\'fd\'a3\'ac\'c3\'bf\'b8\'f6\'ca\'b5\'c0\'fd\'d4\'cb\'d0\'d0\'d4\'da\'b2\'bb\'cd\'ac\'b5\'c4\'b6\'cb\'bf\'da\'a1\'a3\'d0\'e8\'d2\'aa\'d0\'de\'b8\'c4\f1 redis.conf\f2\'c5\'e4\'d6\'c3\'ce\'c4\'bc\'fe\'a1\'a3\'c5\'e4\'d6\'c3\'ce\'c4\'bc\'fe\'d6\'d0\'bb\'b9\'d0\'e8\'d2\'aa\'b0\'d1\f1 cluster-enabled yes\f2\'c7\'b0\'b5\'c4\'d7\'a2\'ca\'cd\'c8\'a5\'b5\'f4\'a1\'a3\f1\par
\kerning0\f3\fs22\lang0{\pict{\*\picprop{\sp{\sn wzDescription}{\sv Image}}{\sp{\sn posv}{\sv 1}}
}\pngblip\picw12381\pich3334\picwgoal7019\pichgoal1890 
89504e470d0a1a0a0000000d49484452000001d40000007e080200000012b57707000000017352
474200aece1ce90000000467414d410000b18f0bfc6105000000097048597300000ec400000ec4
01952b0e1b0000174d49444154785eed9ddf8b16c9b9c7eb3d7f84e460161298f1228a909b48c6
1be7461857422e44880bead578918511c9ee42980b2fe6467791113617ce95066238e201093a03
de1858c6e02670f618dd1c9c812c18c9e23f31a7aa9eea7eabeb573fd56ff5dbafe3f7b3b563bd
ef5b5d55cff3543d5d5d5ddd25ae5ebdfaf27f9fc92023274e9c10360beb626f4fac2fb8f12e2c
abc33797cd27c9f2a6fa666f47ecc8bf9be64bc9a6fcb82776d6cdc71afadece412ce86377e4bf
1174a1755654a211818ea5727532bb0e8ad6cc29c19e3cba135ea1eb3bfa1baf4412bc55f374b8
abb774258382c7a136e09b268f58a1092b30941cad5bda8e4cd3b3eb166bbd0e4c9b06e96c0556
dd4a2b248fb4b19804eb567510db814c62051766a18d64ff41ff84397248885d71efa91b2fc2c6
29b125ff9993ff3558bba9feceadb86a5a92ffec8ab50dfaa2282f64c64216609b6173dbad58df
5c9e1737653de6c476d3840f949ac4ca76f3c4a3d9b49ae9bd47eaafd45b2d85eaa55da550c77a
7de0ec8726322c79757b2a76e4df39b11a7409a54d5fb75edf31ad5b1560dab4ac1558751bb62f
a48d95c552437572e0b5a26578603910a61532682db4a9ded4c8579d192a3b2917eed82c0bedf2
5d21e93ce09d31cc18d00b768350b49e2775fef5a93e3af28d94b8537d191e2c4c789e4f9e2a99
0a7164a733b91d64cde9cb7025237590d0f02a1826ed17b14283df87949c5bb7a0f6ea942cd3b3
eb268919cb69fc1c9b16b702a76ec5159245b0f4bc0ca96ea1e03b598e1558b00bb54a4c8c7c17
c4bc105b0f4cfcc339b1fb4ac70bb2212ee9938f831c038e2e99b861571c1f89cbe5c6dd0eb244
bb26bb37c56824e63f371fe7e4a87f5ac89aa88ac853a8d5e694428eeb73a6cd9618cdcbb1c298
53233d76aed8ba24e62f9b782e4f2f7b26a8d4d2c7b54716b975339714118a9b3e682c99eda966
e538362d6e054edd8a2b240b597ac2587c64e37724bd34724d20e158210379e048f7df0abf505b
bda9912f000080768297022d24e77c010000f4039c2f00000c009c2f00000c009c2f00004cc886
bad5363a653ef180f39d22a9555fef28a11536fb4ac099641f36a4f711e37c47d26d27a0f58664
6c8abb4b6e01000064a09c6f8be795a8876a76c50b2b5ef05137f00e43575b14fcf5920080289c
69077ac2e29159757cc88af7083d2d93fb9cc9840c5228e8068c052624fe589a0cfdcfea709cef
11f564f7a37b3abe2c96ea380000808e249daf79f1d82d155fd9f6e29d061d264f2b386f4e302f
28a07779cc896d2ba5ff0089f33683d44b18a8b6cd735d7d72cb2ad4c9245ca8c44e36f1008d25
2943bd79544feb8f43de333c1ad203fb3d00655b08cb588c16c2c292b4f15a8698d29a65451b89
9d2cd1903892ca5443b49096d69babb752589366f4c8af7a28b9fac63c15dc53dd74b657af5efd
f6f9d732041e2f8ebe7582427ef1b10ced26eed8a911ec129b4dad0e81965475ad655b773ab8ce
37189a62fa6d5705af4b34ecd40c79fd59c29694a35e3eb1dca2f75a63fed46abe6322894bb610
b6b1382d84452529c7c131d5cb6c484c490768219cd69ba3b79ea0a2fd37eff451b75a6f29e7ab
d0edd21463c73b503571b7e92f876c1f4b5c2395d2fcd53453ff94405951a87ea5c46eb96d859a
229a09c81734cc569538d6955587ec86ce943456f9a07adba8fbbc636ef97d8fce374b8458e20a
aeb1245565ec7ad2e179aa234975a8f516ac46ad5ebb26e6a462a7ac2a966e485c49b3d4db462d
424b0be1b45eb6defaa3c5f996ab5bad3759568bf3a5a454253bde85aaddb07288359404b143aa
72039a75682b941ab4930da9c56e82e624e9b89bc8e15d08d6b312b340fe55559d7ed542ac02b9
ce9729425009164c6329aa72db5b489aaaa3b6babc987ae9fbfa706643e24a9aa5de366222b4e3
2b84adb7fe6875bea5ea66e92d3ee74bb5d95e51f15bfa003bdea5e0a7e2733db1423974319b87
699d14d2af7c9efc45ecfa1d9b12a3812a905aec57edfd44a7336fe32c44bba405d55b49fa79d7
375276a407115a8d35a6d4abfab702af2e94063b626229f5d2ebbde77fa23f301b125fd2e15a08
ab9fb6ea6d404ad5ada137ce6a87203b5d569b6d9c1abf9f54bd515f1b237a199b469f7c6ea9fd
2da6855ef5c1e1904ef78ad6454f0e5bd262ea654b5a9c7d204241580d2947d201d43bfd7eface
1077beca4e7ad9bcb90368c765c87b8ad9a2bec358adc90f6ee3d18ad9da44bfbdd8c9b02f680b
10fd5af771a175f01472a8d0293b4fd222ea254987a2a0086c63cd322d0d2957d2e9b69001fae9
3b4372e4bb7056298e4ebc76bc0c4fc5fc481cd7fb4ad5d7595cf4726365d169f6a26a83a9b36d
238557ba71b94255571c7974967412f592a4427c52626ac8302f1530667955f7c934938bc030d6
00c4d5fb4b3d42dcf9567f6036a4ce924ea1850cd24f679986de92ceb7ec069aea0e8037533c23
fb1e1ad285b277dc2bb997255bd23cf5b6c1dc08920589607987f59df07568c916d2c7f688e560
ee12cb6c48efdd769c74bf4b86a1edd801dbf4a9d50eeac65ca559b536cdbbeb9a85b23da9cc0b
c1ee135c4558a70cfe1adef232e7d664ba504930810acdfce99ea61d6495e8cba0b0099892e6aa
b79598a47e0f37545dc2ffddcf6a733d90b86c0b91308d95d54252f0d775c4eb66fb2909b32171
241da48504d34cba1d67f5d3a426ab563204832937b76e0c6a9dc49daf2ec0e851c71b1ead1b9e
b4e93c7dcbd9d2dab7501b5694c15616698a6da774a18adaf675089d96ec7c488ddd9caf842b69
a67adbf1244d6558250e0a683b11952096b8680b51708c4569a6eb7c158eb0910a701b1247d221
5a487bebcdd55b5de8bbe97c153adbd4c8170000403f745e6a060000a03b70be0000300070be00
00300070be0000300033e87c43b720bbdf55043c3aafc498518237a983cc6c7be38b3008e8a793
c273beb44290344b716735220000801c78ce9736cd9cd2069ad6ebe5f11838e81db4b76e406f93
c271be836ca03908b4767af2c5f60070407bebc63ed11bc7f9ead7c761034d00002847d2f99ae7
028b6ea069ce5a76e8704b21782f22fecc5fe35dce3a380f419a875fe9951fd893b18623299f74
6e9992dacf2bcb90a89b9d5bbf22b0c96b6f9d4c3fa9a4e8a794209316111a0a493a5f7a917e94
fcf7a9aba7d4fd771a355f7a541c59a8ff0eadb9950994abcf4035eac54e71ff7544769b66fa6e
c872696f02c352a03129f53a65e906eaa857f5643b994ee3bf652c57d234fcdcda25d52dd8a9b0
cc2dd8bb9cdc54a11d9c88a6ac42f8b42ba474ddd04fbb912b42dbbb1df499c118db8ee7539fbd
9d1ce4f751a3c64e92fc33aa7d66b3c19e8cb515acaad6876648ca80951b5b52953228bbdd1eac
dcc6adabfa322a42a50afff7b20a31a4db5baee90bd5cde4867e6a3eb1e188d054488bf3b5ebd1
b14e1524bc63d116827692e41a9559ed98fa2a4804272b528b2b57556ef79e4904fd45a89e31f5
3a6d4e8d08e4378eea3cd1322465c0ca8d2d69003f59959b53684c7c436535e72849598518d2d2
659abe54dd28b7bc03637a7b7ffaa98423424321f169076aa674bd433beed9f1f6fee090b9e35e
31b027a316bfdeaaa0f09e8c1cb27263ef5468dc2805ff1a99d8124e662f5e99481e65159205db
f4658d857e9a4db6089cd50e4172277cb127e36c507c4fc6768aeb4d0f31a6ba27e32c9b7ec68d
c5e6fddbfe35ee7c0b6fa0c9de71af17b0276393c27b32a629adb701f6649c65d3f761aca1d807
fd344384e4c8b7e4069acc1df7b2c09e8c3571f54e754fc62065739b6c4f46dab2ac65d6c567f6
4d5fd658e8a7939310c12824e97ccb6ea0893d197b65903d199994cc8d4ccfdc9371a961fde54d
b1a2d33dc89fe0ebc5f46ded8d49d9baa19f768325425321a9d50eeaa6616500b5f4cf31463e2a
133d0fe2045f4786f80d443f2becc918ab9b33eb44f782edb0d3754f463eedb9b1250d6615de93
3114a28d4d126f6f92b20a2182799ad24b98beacb1d04f133045b02b1677beba5a46dd3a3ed12d
c89aca4e7548651b37aac476222a412cb1d70fd382f8667333f444089c9628cde446cde9810a47
d848056c19c9c4bef3557024e593ce2d47527ba983eb6d2907fd5189d62c34a0319b846289b20a
d144db5baee9cbd6cdcb0dfdb41d9e08b54252235f000000fdd079a919000080eec0f90200c000
54ce77343211000000fd83912f00000c8076be18f60200c074e18d7c69091bade4a0789767ae01
00001878ce9736cd9cd2069a0000b0ffe138dff767034d00009812a33d13010004c0fd10d017d2
f97efbf7bfca1078c2adf1be6a3f947a260f8019054313d01fc96987e21b68020000d0249defe5
79f34ae0dd9be3d7039bf8145e4b0c0000fb96b61b6ef40e75dad0c98e0300009880b8f32dbc81
26000080319ca5664130e10b0000dd893bdfc21b6802000018931cf996dc40130000c098a4f32d
bb81260000808aa4f355bb8e5773bb6acd2fe6790100a00c09e7bb20a4bfdd7a60e2eaf50eaf74
1c0000c0a4249cef53313f12a736c6f179acf00500803224a71d000000f4039c2f00000c009c2f
00000c807a9fef3ffefe5719bbf7df8ffeaca11f6edfa67f010873f1a289ec6364efc0fb7c414f
9419f9deb9a8baa21dee3c373f81e94026e0687d0ac63a7d4d9dc5af9d361f01003e9876000080
0128e37c2fdc56d31414cecd992fc16c026301300bbcf323dfc76beac2f9f15bf3110000de0930
ed00000003c05aed20479777774d9cb8725b1c3551174abc78455c68a6b873513cf10e8c2516cf
c5c51b266a9813d757c501f3413cbf236ec8ec22f8d5a3d20dcdac6aa832e7ae8b93071ae903d5
e3912e74ac90b762ed53f5c24e22a85b575e666e11496ba2faaf4888202f382a4e5ffbf36f8e99
f89bfbbffee8bbf3eaf3b32f4e7cf6d07ccbe0f0c77ff8dd9983faf82f5f9aef0c3a7ff707bb50
2ad63d4cd14ca588a50c81d50ea03f5a46be6f1fab3ee6785ec99f1e9b481fa8421dcf2bd9155b
dd6eca4b3f6e7b10c9aef8343153f1bd5873d277805fa84c69795ec98d35e1a4921ed03dd3c8dc
bc640a27375d68c7b50c4c11a4cf6cb8b783677ee7ba3b1e2fbffce333f9cfc19f2f1ea62f2a0e
7ffc2b99dfb33f5a1e532da76816a28afdc3c7cd23ddaa1107cf9cc7320c3003249def5bb17157
47e490c7ba4b73fbbaf8407fdd13df7cadfeca11e8b8441d7eaa7f258e5e305fd22d2327f17818
278781da8fdb09ae2caa6fee6ea9bf3e776f28e72587902af175297a3e3985de90296bf55271bb
e21bcfad3604ac927d4fbf59c8dce6ce8d53ea32c58d3bfa9f2cb8221cfef8b772b4aa87932788
5fdf7f433fe5f3f0f7ea58d7391e5efcb92ce1d957f5205afa54e552c7454abed07ebb79241dd8
48a6f9e22b930080214939dfe75bca0d29d7e05cba1e10174e9a687ffcdb732d47f3affd490479
597dd212e0e892765eaf432347c9a27234a6a80362f576e3925c5ea7cbf1602058e3d0bc426571
b57a0f889f859cfd85db8dacea64df7b02c842572dd35cb8a2ff79923df8e58a70fabc76bdcfbe
185fc8bffcf22372851d78f9e42fca731ffb953584d545bcb9fffbdaf75299769112f2dbe2873f
7246cdd2237ff06313ab78f83063320480be4839dfef5fabbf8bbfa85cc3b438f90bf5f7c90dd7
a97580443059d5812ecc432347c9b92513e94c56a1572e98888d7fe2a149803af81341c44f9df3
d30fb4bbcc8729c2e11ffd50fd638d4a27c49b7af0a71c4c99c77e4377282ad474b1e3694d6626
a53b2701c0c0a49cefbf233dbc778e8e2f996557ff54f7fcb54eb3ccc54538b93abe0c6f04ebe2
a078a16ab8ed4f82f70953841f7fa03cde9bd7ffa48f25684e3d9851aeeddca94c1e0f3f331312
1235290c270c668894f3fdcf6ea3a642d4cf02d0aceeee5d71317fee9244706684eb903f8dc1a2
6ca1cfef9871ae9986d6a1ef8723b244f02fec27c19a7aa061af3de520f9e76bf5b33f934bf8cb
2b9403d698c968e584f1e033980152cef707fab6da933f4d74e1efd098a67c1ebd7cb651834dba
c5149ba58d43227cfd8dfe302dca16fa3f7ac14170fd592b6fbfd113058bd9c732452047e8cdb4
9a99818ed4530fe7cfeb3b6df62a07c9cbeffe25fffa6b225a5193d1c60307a68601983629e76b
6eb084962b3dce9f04a0c154dd9fc3ebc9246fd54a2f673d93712221c84dc4962e1cd52b2482a3
6639a2ece9b9b8b28592deecb57df558d8e786adbae7e253bd5865d15e26c283298219a51e3cf3
dbfa5a5e2defa2f9d7ee98a98763c7dc2907cdc3afb46f0e0d604f5fb32615544dbcc5677a0104
00b340cb4316d2455207765914b743778a24b175fb81ac16c5b9d75e62fb1981267e9e92600ded
945111f465b57d37df7ec8624238858e1f8bd0df13bef68259cdcd895dd251b516a5f134844ddc
529298b124ad225cd40f59f80f318837f7efffebcc99ec872c6ca4e3d41e3cf24044f5b38f7540
3c11bf6278c802f4476ae42b397052796177865176f8787f8e21b3a285a284ecf061a7a0577759
09357a25acef202432dbebe74c3c485804edf52677b2310a16aab2a215638456c5ea6aa5227bf9
845e2467171a553203a6080f3f6baeec958eeda32fbf331f3a63a61edc29870a6b06c146975d1f
105cf3a6e78abb9e120028095ea60e3a4223df7ea0f1f40443e74260e40bfaa365e40bc0f4397d
8d9e606bac7200609f619cef6884133c181af5c606859e448e4d3900b04fc0c817cc1e6a661613
b3609fa3e67cffefc5df64ecbfee3fa47107fd0000c09c2fe80f8c7c01006000e07c01006000e0
7c01006000e07c01006000e07c01006000e07c01006000d4523300400c2c35037d71f5ead57fbc
f89b0c3272e2c409f32d0000803ec1b40300000c009c2f00000c009c2f00000c009c2f00000c00
9c2f00000c009c2f00000c009c2f00000c009c2f00000c009c2f00000c009c2f00000c009c2f00
000c009c2f00000c009c2f00000c009cef802c8bbd3d372c9bdf405f6cf6a76732e8a6f9041468
e45178ce77617dac328aaf2fe80f000000bac073be673f146257bcb0e2f79eea0f601236c46854
85e352a900ec3bd0c8a3709cef82f8704eec3e12e46f0f59f13c42172026e04a6dca2c881da9f6
1df92f00fb94596fe41ce77b44cc09f1e89e8e2f8ba53a0e0000a02349e7bbbca987a5b7547c65
db8b773ba56c5997217538657ea409e5f04038781e6b8ea677d6cdd70dec039be9cdc43f25084e
64ebf4e16c5ba9b21d870e037caab0736095b37fe3c298cc0a4ee5e976d3deb63aa1caffb7ad94
81ea15512f134b52d30c28c494d62c2bda1aed648916cb9134078e08c616558815da6ad32c9885
724123a704b9e80c537bb8adef348a7143ae96832af620c5f97e905af3a625ab6f0315fc0e5629
6ed9ee0f3ad4995156bede49031df41b535df44665aca9e5b4cb58a17632a7ef3542b39482ea65
5149caf1354cf5363c6033d875e34ada0a5f846607ae035fd23cdd12ec4299a091cbd0c110b508
6d1b68ea528d79ec7807822af62075f8a590426b514dbf6aaa89d2d80e5a51595185aa743a7c9c
306869fab2adc23e759f77a490dff7d82ee94bbfdd2c7b794a62892b0aab9783e51a6abd05ab51
abd7ae89e96f76caaa62632b5855ad0fcd90b415b6082a6550a8a0a19d6325419bb6c22c94476d
0534f22c6cbdb5385fbb806e858db19a662330944e45db66261db92af29229aa0cd37d894e47f6
b1741a88b6a4385437b71a6942522b72db25d3409438de2e8babb79daa7934f209d533a65ea7db
98418de7591cd132246d852d428060b24ab74ef58ac1ac5b88981552c4c4797f1a79536f51e71b
1e90d7a183c198ceb72ada96933ce3f88b4a17e110b4626b85a97a75323acaab5b3b55ddf2cc14
3b8adf2e9b266be915699d54f9874337f5b6c2943422bb84c4af05a736e3f7964697cb92b4951c
6349025dcc5363864d79700a6d272e548ad851ef4f236f08c55be71b60a7d36a33897fc3adbadb
56b3f140fd5dfaa4127559accca90337e8a3442fc028cc86b8b9aba6e757b562965755115bba26
79f451371e1ba7c4e89289cfad9866d461e43ea0080539a4657845abd3630c25a9ee84b796cca7
04c56c2a6117da0e1a79371a85c69daf12522f8adebaa45da41d0f79cc92547ef0acd6e9f22fd5
df9b6beaafe1855eadbd2b8e53659cd0b56ef71ea9bfcae92f884f641bdd156b637fcf86ea3614
f59af66a41fbca76feb5523fea1d8443474c24cc40926ed28d787b20927800a1884d730b4d8346
de0d4b6f42fc3f29361b4166c4bfa60000000049454e44ae426082
}\kerning2\f1\fs21\lang1033\par
\f2\'b5\'da\'b6\'fe\'b2\'bd\'a3\'ba\'c6\'f4\'b6\'af\'c3\'bf\'b8\'f6\f1 redis\f2\'ca\'b5\'c0\'fd\'a1\'a3\f1\par
\f2\'b5\'da\'c8\'fd\'b2\'bd\'a3\'ba\'ca\'b9\'d3\'c3\f1 ruby\f2\'bd\'c5\'b1\'be\'b4\'ee\'bd\'a8\'bc\'af\'c8\'ba\'a1\'a3\f1\par
\trowd\trgaph10\trleft-118\trbrdrl\brdrs\brdrw10 \trbrdrt\brdrs\brdrw10 \trbrdrr\brdrs\brdrw10 \trbrdrb\brdrs\brdrw10 \trpaddl10\trpaddr10\trpaddfl3\trpaddfr3
\clbrdrl\brdrw10\brdrs\clbrdrt\brdrw10\brdrs\clbrdrr\brdrw10\brdrs\clbrdrb\brdrw10\brdrs \cellx8404 
\pard\intbl\nowidctlpar\qj ./redis-trib.rb create --replicas 1 192.168.25.153:7001 192.168.25.153:7002 192.168.25.153:7003 192.168.25.153:7004 192.168.25.153:7005 192.168.25.153:7006\cell\row 
\pard\nowidctlpar\qj\par
\f2\'b4\'b4\'bd\'a8\'b9\'d8\'b1\'d5\'bc\'af\'c8\'ba\'b5\'c4\'bd\'c5\'b1\'be\'a3\'ba\f1\par
[root@localhost redis-cluster]# vim shutdow-all.sh\par
redis01/redis-cli -p 7001 shutdown\par
redis01/redis-cli -p 7002 shutdown\par
redis01/redis-cli -p 7003 shutdown\par
redis01/redis-cli -p 7004 shutdown\par
redis01/redis-cli -p 7005 shutdown\par
redis01/redis-cli -p 7006 shutdown\par
[root@localhost redis-cluster]# chmod u+x shutdow-all.sh \par
\par
\trowd\trgaph10\trleft-118\trbrdrl\brdrs\brdrw10 \trbrdrt\brdrs\brdrw10 \trbrdrr\brdrs\brdrw10 \trbrdrb\brdrs\brdrw10 \trpaddl10\trpaddr10\trpaddfl3\trpaddfr3
\clbrdrl\brdrw10\brdrs\clbrdrt\brdrw10\brdrs\clbrdrr\brdrw10\brdrs\clbrdrb\brdrw10\brdrs \cellx8404 
\pard\intbl\nowidctlpar\qj [root@localhost redis-cluster]# \highlight10 ./redis-trib.rb create --replicas 1 192.168.25.153:7001 192.168.25.153:7002 192.168.25.153:7003 192.168.25.153:7004 192.168.25.153:7005  192.168.25.153:7006\par
\highlight0 >>> Creating cluster\par
Connecting to node 192.168.25.153:7001: OK\par
Connecting to node 192.168.25.153:7002: OK\par
Connecting to node 192.168.25.153:7003: OK\par
Connecting to node 192.168.25.153:7004: OK\par
Connecting to node 192.168.25.153:7005: OK\par
Connecting to node 192.168.25.153:7006: OK\par
>>> Performing hash slots allocation on 6 nodes...\par
Using 3 masters:\par
192.168.25.153:7001\par
192.168.25.153:7002\par
192.168.25.153:7003\par
Adding replica 192.168.25.153:7004 to 192.168.25.153:7001\par
Adding replica 192.168.25.153:7005 to 192.168.25.153:7002\par
Adding replica 192.168.25.153:7006 to 192.168.25.153:7003\par
M: 2e48ae301e9c32b04a7d4d92e15e98e78de8c1f3 192.168.25.153:7001\par
   slots:0-5460 (5461 slots) master\par
M: 8cd93a9a943b4ef851af6a03edd699a6061ace01 192.168.25.153:7002\par
   slots:5461-10922 (5462 slots) master\par
M: 2935007902d83f20b1253d7f43dae32aab9744e6 192.168.25.153:7003\par
   slots:10923-16383 (5461 slots) master\par
S: 74f9d9706f848471583929fc8bbde3c8e99e211b 192.168.25.153:7004\par
   replicates 2e48ae301e9c32b04a7d4d92e15e98e78de8c1f3\par
S: 42cc9e25ebb19dda92591364c1df4b3a518b795b 192.168.25.153:7005\par
   replicates 8cd93a9a943b4ef851af6a03edd699a6061ace01\par
S: 8b1b11d509d29659c2831e7a9f6469c060dfcd39 192.168.25.153:7006\par
   replicates 2935007902d83f20b1253d7f43dae32aab9744e6\par
Can I set the above configuration? (type 'yes' to accept):\highlight10  yes\highlight0\par
>>> Nodes configuration updated\par
>>> Assign a different config epoch to each node\par
>>> Sending CLUSTER MEET messages to join the cluster\par
Waiting for the cluster to join.....\par
>>> Performing Cluster Check (using node 192.168.25.153:7001)\par
M: 2e48ae301e9c32b04a7d4d92e15e98e78de8c1f3 192.168.25.153:7001\par
   slots:0-5460 (5461 slots) master\par
M: 8cd93a9a943b4ef851af6a03edd699a6061ace01 192.168.25.153:7002\par
   slots:5461-10922 (5462 slots) master\par
M: 2935007902d83f20b1253d7f43dae32aab9744e6 192.168.25.153:7003\par
   slots:10923-16383 (5461 slots) master\par
M: 74f9d9706f848471583929fc8bbde3c8e99e211b 192.168.25.153:7004\par
   slots: (0 slots) master\par
   replicates 2e48ae301e9c32b04a7d4d92e15e98e78de8c1f3\par
M: 42cc9e25ebb19dda92591364c1df4b3a518b795b 192.168.25.153:7005\par
   slots: (0 slots) master\par
   replicates 8cd93a9a943b4ef851af6a03edd699a6061ace01\par
M: 8b1b11d509d29659c2831e7a9f6469c060dfcd39 192.168.25.153:7006\par
   slots: (0 slots) master\par
   replicates 2935007902d83f20b1253d7f43dae32aab9744e6\par
[OK] All nodes agree about slots configuration.\par
>>> Check for open slots...\par
>>> Check slots coverage...\par
[OK] All 16384 slots covered.\par
[root@localhost redis-cluster]# \cell\row 
\pard\nowidctlpar\qj\par

\pard\nowidctlpar\s2\fi-567\li567\qj\tx567\fs36 3.3.\tab\f2\'bc\'af\'c8\'ba\'b5\'c4\'ca\'b9\'d3\'c3\'b7\'bd\'b7\'a8\f1\par

\pard\nowidctlpar\qj\fs21 Redis-cli\f2\'c1\'ac\'bd\'d3\'bc\'af\'c8\'ba\'a1\'a3\f1\par
[root@localhost redis-cluster]# redis01/redis-cli -p 7002 \highlight10 -c\par
\highlight0 -c\f2\'a3\'ba\'b4\'fa\'b1\'ed\'c1\'ac\'bd\'d3\'b5\'c4\'ca\'c7\f1 redis\f2\'bc\'af\'c8\'ba\f1\par
\par

\pard\keep\keepn\nowidctlpar\s1\fi-425\li425\sb340\sa330\sl576\slmult1\qj\tx425\kerning44\b\f0\fs44 4.\tab Jedis\par

\pard\nowidctlpar\qj\kerning2\b0\f2\fs21\'d0\'e8\'d2\'aa\'b0\'d1\f1 jedis\f2\'d2\'c0\'c0\'b5\'b5\'c4\f1 jar\f2\'b0\'fc\'cc\'ed\'bc\'d3\'b5\'bd\'b9\'a4\'b3\'cc\'d6\'d0\'a1\'a3\f1 Maven\f2\'b9\'a4\'b3\'cc\'d6\'d0\'d0\'e8\'d2\'aa\'b0\'d1\f1 jedis\f2\'b5\'c4\'d7\'f8\'b1\'ea\'cc\'ed\'bc\'d3\'b5\'bd\'d2\'c0\'c0\'b5\'a1\'a3\f1\par
\par
\f2\'cd\'c6\'bc\'f6\'cc\'ed\'bc\'d3\'b5\'bd\'b7\'fe\'ce\'f1\'b2\'e3\'a1\'a3\f1 E3-content-Service\f2\'b9\'a4\'b3\'cc\'d6\'d0\'a1\'a3\f1\par
\par

\pard\nowidctlpar\s2\fi-567\li567\qj\tx567\fs36 4.1.\tab\f2\'c1\'ac\'bd\'d3\'b5\'a5\'bb\'fa\'b0\'e6\f1\par

\pard\nowidctlpar\qj\f2\fs21\'b5\'da\'d2\'bb\'b2\'bd\'a3\'ba\'b4\'b4\'bd\'a8\'d2\'bb\'b8\'f6\f1 Jedis\f2\'b6\'d4\'cf\'f3\'a1\'a3\'d0\'e8\'d2\'aa\'d6\'b8\'b6\'a8\'b7\'fe\'ce\'f1\'b6\'cb\'b5\'c4\f1 ip\f2\'bc\'b0\'b6\'cb\'bf\'da\'a1\'a3\f1\par
\f2\'b5\'da\'b6\'fe\'b2\'bd\'a3\'ba\'ca\'b9\'d3\'c3\f1 Jedis\f2\'b6\'d4\'cf\'f3\'b2\'d9\'d7\'f7\'ca\'fd\'be\'dd\'bf\'e2\'a3\'ac\'c3\'bf\'b8\'f6\f1 redis\f2\'c3\'fc\'c1\'ee\'b6\'d4\'d3\'a6\'d2\'bb\'b8\'f6\'b7\'bd\'b7\'a8\'a1\'a3\f1\par
\f2\'b5\'da\'c8\'fd\'b2\'bd\'a3\'ba\'b4\'f2\'d3\'a1\'bd\'e1\'b9\'fb\'a1\'a3\f1\par
\f2\'b5\'da\'cb\'c4\'b2\'bd\'a3\'ba\'b9\'d8\'b1\'d5\f1 Jedis\par
\trowd\trgaph10\trleft-118\trbrdrl\brdrs\brdrw10 \trbrdrt\brdrs\brdrw10 \trbrdrr\brdrs\brdrw10 \trbrdrb\brdrs\brdrw10 \trpaddl10\trpaddr10\trpaddfl3\trpaddfr3
\clbrdrl\brdrw10\brdrs\clbrdrt\brdrw10\brdrs\clbrdrr\brdrw10\brdrs\clbrdrb\brdrw10\brdrs \cellx8404 
\pard\intbl\nowidctlpar\cf12\f8\fs15 @Test\cf0\par
\cf3\tab\cf13\b public\cf3\b0  \cf13\b void\cf3\b0  \highlight14 testJedis\highlight0 () \cf13\b throws\cf3\b0  Exception \{\cf0\par
\cf3\tab\tab\cf15 // \f2\'b5\'da\'d2\'bb\'b2\'bd\'a3\'ba\'b4\'b4\'bd\'a8\'d2\'bb\'b8\'f6\ul\f8 Jedis\ulnone\f2\'b6\'d4\'cf\'f3\'a1\'a3\'d0\'e8\'d2\'aa\'d6\'b8\'b6\'a8\'b7\'fe\'ce\'f1\'b6\'cb\'b5\'c4\ul\f8 ip\ulnone\f2\'bc\'b0\'b6\'cb\'bf\'da\'a1\'a3\cf0\f8\par
\cf3\tab\tab Jedis \cf16 jedis\cf3  = \cf13\b new\cf3\b0  Jedis(\cf17 "192.168.25.153"\cf3 , 6379);\cf0\par
\cf3\tab\tab\cf15 // \f2\'b5\'da\'b6\'fe\'b2\'bd\'a3\'ba\'ca\'b9\'d3\'c3\ul\f8 Jedis\ulnone\f2\'b6\'d4\'cf\'f3\'b2\'d9\'d7\'f7\'ca\'fd\'be\'dd\'bf\'e2\'a3\'ac\'c3\'bf\'b8\'f6\ul\f8 redis\ulnone\f2\'c3\'fc\'c1\'ee\'b6\'d4\'d3\'a6\'d2\'bb\'b8\'f6\'b7\'bd\'b7\'a8\'a1\'a3\cf0\f8\par
\cf3\tab\tab String \cf16 result\cf3  = \cf16 jedis\cf3 .get(\cf17 "hello"\cf3 );\cf0\par
\cf3\tab\tab\cf15 // \f2\'b5\'da\'c8\'fd\'b2\'bd\'a3\'ba\'b4\'f2\'d3\'a1\'bd\'e1\'b9\'fb\'a1\'a3\cf0\f8\par
\cf3\tab\tab System.\cf18\b\i out\cf3\b0\i0 .println(\cf16 result\cf3 );\cf0\par
\cf3\tab\tab\cf15 // \f2\'b5\'da\'cb\'c4\'b2\'bd\'a3\'ba\'b9\'d8\'b1\'d5\ul\f8 Jedis\cf0\ulnone\par
\cf3\tab\tab\cf16 jedis\cf3 .close();\cf0\par

\pard\intbl\nowidctlpar\qj\cf3\tab\}\cf0\f1\cell\row 
\pard\nowidctlpar\qj\fs21\par

\pard\nowidctlpar\s2\fi-567\li567\qj\tx567\fs36 4.2.\tab\f2\'c1\'ac\'bd\'d3\'b5\'a5\'bb\'fa\'b0\'e6\'ca\'b9\'d3\'c3\'c1\'ac\'bd\'d3\'b3\'d8\f1\par

\pard\nowidctlpar\qj\f2\fs21\'b5\'da\'d2\'bb\'b2\'bd\'a3\'ba\'b4\'b4\'bd\'a8\'d2\'bb\'b8\'f6\f1 JedisPool\f2\'b6\'d4\'cf\'f3\'a1\'a3\'d0\'e8\'d2\'aa\'d6\'b8\'b6\'a8\'b7\'fe\'ce\'f1\'b6\'cb\'b5\'c4\f1 ip\f2\'bc\'b0\'b6\'cb\'bf\'da\'a1\'a3\f1\par
\f2\'b5\'da\'b6\'fe\'b2\'bd\'a3\'ba\'b4\'d3\f1 JedisPool\f2\'d6\'d0\'bb\'f1\'b5\'c3\f1 Jedis\f2\'b6\'d4\'cf\'f3\'a1\'a3\f1\par
\f2\'b5\'da\'c8\'fd\'b2\'bd\'a3\'ba\'ca\'b9\'d3\'c3\f1 Jedis\f2\'b2\'d9\'d7\'f7\f1 redis\f2\'b7\'fe\'ce\'f1\'c6\'f7\'a1\'a3\f1\par
\f2\'b5\'da\'cb\'c4\'b2\'bd\'a3\'ba\'b2\'d9\'d7\'f7\'cd\'ea\'b1\'cf\'ba\'f3\'b9\'d8\'b1\'d5\f1 jedis\f2\'b6\'d4\'cf\'f3\'a3\'ac\'c1\'ac\'bd\'d3\'b3\'d8\'bb\'d8\'ca\'d5\'d7\'ca\'d4\'b4\'a1\'a3\f1\par
\f2\'b5\'da\'ce\'e5\'b2\'bd\'a3\'ba\'b9\'d8\'b1\'d5\f1 JedisPool\f2\'b6\'d4\'cf\'f3\'a1\'a3\f1\par
\trowd\trgaph10\trleft-118\trbrdrl\brdrs\brdrw10 \trbrdrt\brdrs\brdrw10 \trbrdrr\brdrs\brdrw10 \trbrdrb\brdrs\brdrw10 \trpaddl10\trpaddr10\trpaddfl3\trpaddfr3
\clbrdrl\brdrw10\brdrs\clbrdrt\brdrw10\brdrs\clbrdrr\brdrw10\brdrs\clbrdrb\brdrw10\brdrs \cellx8404 
\pard\intbl\nowidctlpar\cf12\f8\fs15 @Test\cf0\par
\cf3\tab\cf13\b public\cf3\b0  \cf13\b void\cf3\b0  \highlight14 testJedisPool\highlight0 () \cf13\b throws\cf3\b0  Exception \{\cf0\par
\cf3\tab\tab\cf15 // \f2\'b5\'da\'d2\'bb\'b2\'bd\'a3\'ba\'b4\'b4\'bd\'a8\'d2\'bb\'b8\'f6\f8 JedisPool\f2\'b6\'d4\'cf\'f3\'a1\'a3\'d0\'e8\'d2\'aa\'d6\'b8\'b6\'a8\'b7\'fe\'ce\'f1\'b6\'cb\'b5\'c4\ul\f8 ip\ulnone\f2\'bc\'b0\'b6\'cb\'bf\'da\'a1\'a3\cf0\f8\par
\cf3\tab\tab JedisPool \cf16 jedisPool\cf3  = \cf13\b new\cf3\b0  JedisPool(\cf17 "192.168.25.153"\cf3 , 6379);\cf0\par
\cf3\tab\tab\cf15 // \f2\'b5\'da\'b6\'fe\'b2\'bd\'a3\'ba\'b4\'d3\f8 JedisPool\f2\'d6\'d0\'bb\'f1\'b5\'c3\ul\f8 Jedis\ulnone\f2\'b6\'d4\'cf\'f3\'a1\'a3\cf0\f8\par
\cf3\tab\tab Jedis \cf16 jedis\cf3  = \cf16 jedisPool\cf3 .getResource();\cf0\par
\cf3\tab\tab\cf15 // \f2\'b5\'da\'c8\'fd\'b2\'bd\'a3\'ba\'ca\'b9\'d3\'c3\ul\f8 Jedis\ulnone\f2\'b2\'d9\'d7\'f7\ul\f8 redis\ulnone\f2\'b7\'fe\'ce\'f1\'c6\'f7\'a1\'a3\cf0\f8\par
\cf3\tab\tab\cf16 jedis\cf3 .set(\cf17 "jedis"\cf3 , \cf17 "test"\cf3 );\cf0\par
\cf3\tab\tab String \cf16 result\cf3  = \cf16 jedis\cf3 .get(\cf17 "jedis"\cf3 );\cf0\par
\cf3\tab\tab System.\cf18\b\i out\cf3\b0\i0 .println(\cf16 result\cf3 );\cf0\par
\cf3\tab\tab\cf15 // \f2\'b5\'da\'cb\'c4\'b2\'bd\'a3\'ba\'b2\'d9\'d7\'f7\'cd\'ea\'b1\'cf\'ba\'f3\'b9\'d8\'b1\'d5\ul\f8 jedis\ulnone\f2\'b6\'d4\'cf\'f3\'a3\'ac\'c1\'ac\'bd\'d3\'b3\'d8\'bb\'d8\'ca\'d5\'d7\'ca\'d4\'b4\'a1\'a3\cf0\f8\par
\cf3\tab\tab\cf16 jedis\cf3 .close();\cf0\par
\cf3\tab\tab\cf15 // \f2\'b5\'da\'ce\'e5\'b2\'bd\'a3\'ba\'b9\'d8\'b1\'d5\f8 JedisPool\f2\'b6\'d4\'cf\'f3\'a1\'a3\cf0\f8\par
\cf3\tab\tab\cf16 jedisPool\cf3 .close();\cf0\par

\pard\intbl\nowidctlpar\qj\cf3\tab\}\cf0\f1\cell\row 
\pard\nowidctlpar\qj\fs21\par

\pard\nowidctlpar\s2\fi-567\li567\qj\tx567\fs36 4.3.\tab\f2\'c1\'ac\'bd\'d3\'bc\'af\'c8\'ba\'b0\'e6\f1\par

\pard\nowidctlpar\qj\f2\fs21\'b5\'da\'d2\'bb\'b2\'bd\'a3\'ba\'ca\'b9\'d3\'c3\f1 JedisCluster\f2\'b6\'d4\'cf\'f3\'a1\'a3\'d0\'e8\'d2\'aa\'d2\'bb\'b8\'f6\f1 Set<HostAndPort>\f2\'b2\'ce\'ca\'fd\'a1\'a3\f1 Redis\f2\'bd\'da\'b5\'e3\'b5\'c4\'c1\'d0\'b1\'ed\'a1\'a3\f1\par
\f2\'b5\'da\'b6\'fe\'b2\'bd\'a3\'ba\'d6\'b1\'bd\'d3\'ca\'b9\'d3\'c3\f1 JedisCluster\f2\'b6\'d4\'cf\'f3\'b2\'d9\'d7\'f7\f1 redis\f2\'a1\'a3\'d4\'da\'cf\'b5\'cd\'b3\'d6\'d0\'b5\'a5\'c0\'fd\'b4\'e6\'d4\'da\'a1\'a3\f1\par
\f2\'b5\'da\'c8\'fd\'b2\'bd\'a3\'ba\'b4\'f2\'d3\'a1\'bd\'e1\'b9\'fb\f1\par
\f2\'b5\'da\'cb\'c4\'b2\'bd\'a3\'ba\'cf\'b5\'cd\'b3\'b9\'d8\'b1\'d5\'c7\'b0\'a3\'ac\'b9\'d8\'b1\'d5\f1 JedisCluster\f2\'b6\'d4\'cf\'f3\'a1\'a3\f1\par
\par
\trowd\trgaph10\trleft-118\trbrdrl\brdrs\brdrw10 \trbrdrt\brdrs\brdrw10 \trbrdrr\brdrs\brdrw10 \trbrdrb\brdrs\brdrw10 \trpaddl10\trpaddr10\trpaddfl3\trpaddfr3
\clbrdrl\brdrw10\brdrs\clbrdrt\brdrw10\brdrs\clbrdrr\brdrw10\brdrs\clbrdrb\brdrw10\brdrs \cellx8404 
\pard\intbl\nowidctlpar\cf12\f8\fs15 @Test\cf0\par
\cf3\tab\cf13\b public\cf3\b0  \cf13\b void\cf3\b0  \highlight14 testJedisCluster\highlight0 () \cf13\b throws\cf3\b0  Exception \{\cf0\par
\cf3\tab\tab\cf15 // \f2\'b5\'da\'d2\'bb\'b2\'bd\'a3\'ba\'ca\'b9\'d3\'c3\f8 JedisCluster\f2\'b6\'d4\'cf\'f3\'a1\'a3\'d0\'e8\'d2\'aa\'d2\'bb\'b8\'f6\f8 Set<HostAndPort>\f2\'b2\'ce\'ca\'fd\'a1\'a3\ul\f8 Redis\ulnone\f2\'bd\'da\'b5\'e3\'b5\'c4\'c1\'d0\'b1\'ed\'a1\'a3\cf0\f8\par
\cf3\tab\tab Set<HostAndPort> \cf16 nodes\cf3  = \cf13\b new\cf3\b0  HashSet<>();\cf0\par
\cf3\tab\tab\cf16 nodes\cf3 .add(\cf13\b new\cf3\b0  HostAndPort(\cf17 "192.168.25.153"\cf3 , 7001));\cf0\par
\cf3\tab\tab\cf16 nodes\cf3 .add(\cf13\b new\cf3\b0  HostAndPort(\cf17 "192.168.25.153"\cf3 , 7002));\cf0\par
\cf3\tab\tab\cf16 nodes\cf3 .add(\cf13\b new\cf3\b0  HostAndPort(\cf17 "192.168.25.153"\cf3 , 7003));\cf0\par
\cf3\tab\tab\cf16 nodes\cf3 .add(\cf13\b new\cf3\b0  HostAndPort(\cf17 "192.168.25.153"\cf3 , 7004));\cf0\par
\cf3\tab\tab\cf16 nodes\cf3 .add(\cf13\b new\cf3\b0  HostAndPort(\cf17 "192.168.25.153"\cf3 , 7005));\cf0\par
\cf3\tab\tab\cf16 nodes\cf3 .add(\cf13\b new\cf3\b0  HostAndPort(\cf17 "192.168.25.153"\cf3 , 7006));\cf0\par
\cf3\tab\tab JedisCluster \cf16 jedisCluster\cf3  = \cf13\b new\cf3\b0  JedisCluster(\cf16 nodes\cf3 );\cf0\par
\cf3\tab\tab\cf15 // \f2\'b5\'da\'b6\'fe\'b2\'bd\'a3\'ba\'d6\'b1\'bd\'d3\'ca\'b9\'d3\'c3\f8 JedisCluster\f2\'b6\'d4\'cf\'f3\'b2\'d9\'d7\'f7\ul\f8 redis\ulnone\f2\'a1\'a3\'d4\'da\'cf\'b5\'cd\'b3\'d6\'d0\'b5\'a5\'c0\'fd\'b4\'e6\'d4\'da\'a1\'a3\cf0\f8\par
\cf3\tab\tab\cf16 jedisCluster\cf3 .set(\cf17 "hello"\cf3 , \cf17 "100"\cf3 );\cf0\par
\cf3\tab\tab String \cf16 result\cf3  = \cf16 jedisCluster\cf3 .get(\cf17 "hello"\cf3 );\cf0\par
\cf3\tab\tab\cf15 // \f2\'b5\'da\'c8\'fd\'b2\'bd\'a3\'ba\'b4\'f2\'d3\'a1\'bd\'e1\'b9\'fb\cf0\f8\par
\cf3\tab\tab System.\cf18\b\i out\cf3\b0\i0 .println(\cf16 result\cf3 );\cf0\par
\cf3\tab\tab\cf15 // \f2\'b5\'da\'cb\'c4\'b2\'bd\'a3\'ba\'cf\'b5\'cd\'b3\'b9\'d8\'b1\'d5\'c7\'b0\'a3\'ac\'b9\'d8\'b1\'d5\f8 JedisCluster\f2\'b6\'d4\'cf\'f3\'a1\'a3\cf0\f8\par
\cf3\tab\tab\cf16 jedisCluster\cf3 .close();\cf0\par

\pard\intbl\nowidctlpar\qj\cf3\tab\}\cf0\f1\cell\row 
\pard\nowidctlpar\qj\fs21\par

\pard\keep\keepn\nowidctlpar\s1\fi-425\li425\sb340\sa330\sl576\slmult1\qj\tx425\kerning44\b\f0\fs44 5.\tab\f2\'cf\'f2\'d2\'b5\'ce\'f1\'c2\'df\'bc\'ad\'d6\'d0\'cc\'ed\'bc\'d3\'bb\'ba\'b4\'e6\f0\par

\pard\nowidctlpar\s2\fi-567\li567\qj\tx567\kerning2\b0\f1\fs36 5.1.\tab\f2\'bd\'d3\'bf\'da\'b7\'e2\'d7\'b0\f1\par

\pard\nowidctlpar\qj\f2\fs21\'b3\'a3\'d3\'c3\'b5\'c4\'b2\'d9\'d7\'f7\f1 redis\f2\'b5\'c4\'b7\'bd\'b7\'a8\'cc\'e1\'c8\'a1\'b3\'f6\'d2\'bb\'b8\'f6\'bd\'d3\'bf\'da\'a3\'ac\'b7\'d6\'b1\'f0\'b6\'d4\'d3\'a6\'b5\'a5\'bb\'fa\'b0\'e6\'ba\'cd\'bc\'af\'c8\'ba\'b0\'e6\'b4\'b4\'bd\'a8\'c1\'bd\'b8\'f6\'ca\'b5\'cf\'d6\'c0\'e0\'a1\'a3\f1\par
\par

\pard\nowidctlpar\s3\fi-709\li709\qj\tx709\fs32 5.1.1.\tab\f2\'bd\'d3\'bf\'da\'b6\'a8\'d2\'e5\f1\par
\trowd\trgaph10\trleft-118\trbrdrl\brdrs\brdrw10 \trbrdrt\brdrs\brdrw10 \trbrdrr\brdrs\brdrw10 \trbrdrb\brdrs\brdrw10 \trpaddl10\trpaddr10\trpaddfl3\trpaddfr3
\clbrdrl\brdrw10\brdrs\clbrdrt\brdrw10\brdrs\clbrdrr\brdrw10\brdrs\clbrdrb\brdrw10\brdrs \cellx8404 
\pard\intbl\nowidctlpar\cf13\b\f8\fs15 public\cf3\b0  \cf13\b interface\cf3\b0  JedisClient \{\cf0\par
\par
\cf3\tab String set(String \cf16 key\cf3 , String \cf16 value\cf3 );\cf0\par
\cf3\tab String get(String \cf16 key\cf3 );\cf0\par
\cf3\tab Boolean exists(String \cf16 key\cf3 );\cf0\par
\cf3\tab Long expire(String \cf16 key\cf3 , \cf13\b int\cf3\b0  \cf16 seconds\cf3 );\cf0\par
\cf3\tab Long ttl(String \cf16 key\cf3 );\cf0\par
\cf3\tab Long incr(String \cf16 key\cf3 );\cf0\par
\cf3\tab Long hset(String \cf16 key\cf3 , String \cf16 field\cf3 , String \cf16 value\cf3 );\cf0\par
\cf3\tab String hget(String \cf16 key\cf3 , String \cf16 field\cf3 );\cf0\par
\cf3\tab Long hdel(String \cf16 key\cf3 , String... \cf16 field\cf3 );\cf0\par

\pard\intbl\nowidctlpar\qj\cf3\}\cf0\f1\cell\row 
\pard\nowidctlpar\qj\fs21\par

\pard\nowidctlpar\s3\fi-709\li709\qj\tx709\fs32 5.1.2.\tab\f2\'b5\'a5\'bb\'fa\'b0\'e6\'ca\'b5\'cf\'d6\'c0\'e0\f1\par
\trowd\trgaph10\trleft-118\trbrdrl\brdrs\brdrw10 \trbrdrt\brdrs\brdrw10 \trbrdrr\brdrs\brdrw10 \trbrdrb\brdrs\brdrw10 \trpaddl10\trpaddr10\trpaddfl3\trpaddfr3
\clbrdrl\brdrw10\brdrs\clbrdrt\brdrw10\brdrs\clbrdrr\brdrw10\brdrs\clbrdrb\brdrw10\brdrs \cellx8404 
\pard\intbl\nowidctlpar\cf13\b\f8\fs15 public\cf3\b0  \cf13\b class\cf3\b0  JedisClientPool \cf13\b implements\cf3\b0  JedisClient \{\cf0\par
\cf3\tab\cf0\par
\cf3\tab\cf12 @Autowired\cf0\par
\cf3\tab\cf13\b private\cf3\b0  JedisPool \cf18\highlight14 jedisPool\cf3\highlight0 ;\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  String set(String \cf16 key\cf3 , String \cf16 value\cf3 ) \{\cf0\par
\cf3\tab\tab Jedis \cf16 jedis\cf3  = \cf18\highlight14 jedisPool\cf3\highlight0 .getResource();\cf0\par
\cf3\tab\tab String \cf16 result\cf3  = \cf16 jedis\cf3 .set(\cf16 key\cf3 , \cf16 value\cf3 );\cf0\par
\cf3\tab\tab\cf16 jedis\cf3 .close();\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf16 result\cf3 ;\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  String get(String \cf16 key\cf3 ) \{\cf0\par
\cf3\tab\tab Jedis \cf16 jedis\cf3  = \cf18\highlight14 jedisPool\cf3\highlight0 .getResource();\cf0\par
\cf3\tab\tab String \cf16 result\cf3  = \cf16 jedis\cf3 .get(\cf16 key\cf3 );\cf0\par
\cf3\tab\tab\cf16 jedis\cf3 .close();\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf16 result\cf3 ;\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  Boolean exists(String \cf16 key\cf3 ) \{\cf0\par
\cf3\tab\tab Jedis \cf16 jedis\cf3  = \cf18\highlight14 jedisPool\cf3\highlight0 .getResource();\cf0\par
\cf3\tab\tab Boolean \cf16 result\cf3  = \cf16 jedis\cf3 .exists(\cf16 key\cf3 );\cf0\par
\cf3\tab\tab\cf16 jedis\cf3 .close();\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf16 result\cf3 ;\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  Long expire(String \cf16 key\cf3 , \cf13\b int\cf3\b0  \cf16 seconds\cf3 ) \{\cf0\par
\cf3\tab\tab Jedis \cf16 jedis\cf3  = \cf18\highlight14 jedisPool\cf3\highlight0 .getResource();\cf0\par
\cf3\tab\tab Long \cf16 result\cf3  = \cf16 jedis\cf3 .expire(\cf16 key\cf3 , \cf16 seconds\cf3 );\cf0\par
\cf3\tab\tab\cf16 jedis\cf3 .close();\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf16 result\cf3 ;\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  Long ttl(String \cf16 key\cf3 ) \{\cf0\par
\cf3\tab\tab Jedis \cf16 jedis\cf3  = \cf18\highlight14 jedisPool\cf3\highlight0 .getResource();\cf0\par
\cf3\tab\tab Long \cf16 result\cf3  = \cf16 jedis\cf3 .ttl(\cf16 key\cf3 );\cf0\par
\cf3\tab\tab\cf16 jedis\cf3 .close();\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf16 result\cf3 ;\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  Long incr(String \cf16 key\cf3 ) \{\cf0\par
\cf3\tab\tab Jedis \cf16 jedis\cf3  = \cf18\highlight14 jedisPool\cf3\highlight0 .getResource();\cf0\par
\cf3\tab\tab Long \cf16 result\cf3  = \cf16 jedis\cf3 .incr(\cf16 key\cf3 );\cf0\par
\cf3\tab\tab\cf16 jedis\cf3 .close();\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf16 result\cf3 ;\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  Long hset(String \cf16 key\cf3 , String \cf16 field\cf3 , String \cf16 value\cf3 ) \{\cf0\par
\cf3\tab\tab Jedis \cf16 jedis\cf3  = \cf18\highlight14 jedisPool\cf3\highlight0 .getResource();\cf0\par
\cf3\tab\tab Long \cf16 result\cf3  = \cf16 jedis\cf3 .hset(\cf16 key\cf3 , \cf16 field\cf3 , \cf16 value\cf3 );\cf0\par
\cf3\tab\tab\cf16 jedis\cf3 .close();\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf16 result\cf3 ;\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  String hget(String \cf16 key\cf3 , String \cf16 field\cf3 ) \{\cf0\par
\cf3\tab\tab Jedis \cf16 jedis\cf3  = \cf18\highlight14 jedisPool\cf3\highlight0 .getResource();\cf0\par
\cf3\tab\tab String \cf16 result\cf3  = \cf16 jedis\cf3 .hget(\cf16 key\cf3 , \cf16 field\cf3 );\cf0\par
\cf3\tab\tab\cf16 jedis\cf3 .close();\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf16 result\cf3 ;\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  Long hdel(String \cf16 key\cf3 , String... \cf16 field\cf3 ) \{\cf0\par
\cf3\tab\tab Jedis \cf16 jedis\cf3  = \cf18\highlight14 jedisPool\cf3\highlight0 .getResource();\cf0\par
\cf3\tab\tab Long \cf16 result\cf3  = \cf16 jedis\cf3 .hdel(\cf16 key\cf3 , \cf16 field\cf3 );\cf0\par
\cf3\tab\tab\cf16 jedis\cf3 .close();\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf16 result\cf3 ;\cf0\par
\cf3\tab\}\cf0\par
\par

\pard\intbl\nowidctlpar\qj\cf3\}\cf0\f1\cell\row 
\pard\nowidctlpar\qj\fs21\par
\f2\'c5\'e4\'d6\'c3\'a3\'ba\f1 applicationContext-redis.xml\par
\trowd\trgaph10\trleft-118\trbrdrl\brdrs\brdrw10 \trbrdrt\brdrs\brdrw10 \trbrdrr\brdrs\brdrw10 \trbrdrb\brdrs\brdrw10 \trpaddl10\trpaddr10\trpaddfl3\trpaddfr3
\clbrdrl\brdrw10\brdrs\clbrdrt\brdrw10\brdrs\clbrdrr\brdrw10\brdrs\clbrdrb\brdrw10\brdrs \cellx8404 
\pard\intbl\nowidctlpar\cf19\f8\fs15 <?\cf20 xml\cf0  \cf21 version\cf3 =\cf17\i "1.0"\cf0\i0  \cf21 encoding\cf3 =\cf17\i "UTF-8"\cf19\i0 ?>\cf0\par
\cf19 <\cf20 beans\cf0  \cf21 xmlns\cf3 =\cf17\i "http://www.springframework.org/schema/beans"\cf0\i0\par
\tab\cf21 xmlns:context\cf3 =\cf17\i "http://www.springframework.org/schema/context"\cf0\i0  \cf21 xmlns:p\cf3 =\cf17\i "http://www.springframework.org/schema/p"\cf0\i0\par
\tab\cf21 xmlns:aop\cf3 =\cf17\i "http://www.springframework.org/schema/aop"\cf0\i0  \cf21 xmlns:tx\cf3 =\cf17\i "http://www.springframework.org/schema/tx"\cf0\i0\par
\tab\cf21 xmlns:xsi\cf3 =\cf17\i "http://www.w3.org/2001/XMLSchema-instance"\cf0\i0\par
\tab\cf21 xsi:schemaLocation\cf3 =\cf17\i "http://www.springframework.org/schema/beans {{\field{\*\fldinst{HYPERLINK http://www.springframework.org/schema/beans/spring-beans4.2.xsd }}{\fldrslt{http://www.springframework.org/schema/beans/spring-beans4.2.xsd\ul0\cf0}}}}\cf0\i0\f8\fs15\par
\cf17\i\tab {{\field{\*\fldinst{HYPERLINK http://www.springframework.org/schema/context }}{\fldrslt{http://www.springframework.org/schema/context\ul0\cf0}}}}\f8\fs15  {{\field{\*\fldinst{HYPERLINK http://www.springframework.org/schema/context/spring-context4.2.xsd }}{\fldrslt{http://www.springframework.org/schema/context/spring-context4.2.xsd\ul0\cf0}}}}\cf0\i0\f8\fs15\par
\cf17\i\tab {{\field{\*\fldinst{HYPERLINK http://www.springframework.org/schema/aop }}{\fldrslt{http://www.springframework.org/schema/aop\ul0\cf0}}}}\f8\fs15  {{\field{\*\fldinst{HYPERLINK http://www.springframework.org/schema/aop/spring-aop4.2.xsd }}{\fldrslt{http://www.springframework.org/schema/aop/spring-aop4.2.xsd\ul0\cf0}}}}\f8\fs15  {{\field{\*\fldinst{HYPERLINK http://www.springframework.org/schema/tx }}{\fldrslt{http://www.springframework.org/schema/tx\ul0\cf0}}}}\f8\fs15  {{\field{\*\fldinst{HYPERLINK http://www.springframework.org/schema/tx/spring-tx4.2.xsd }}{\fldrslt{http://www.springframework.org/schema/tx/spring-tx4.2.xsd\ul0\cf0}}}}\cf0\i0\f8\fs15\par
\cf17\i\tab {{\field{\*\fldinst{HYPERLINK http://www.springframework.org/schema/util }}{\fldrslt{http://www.springframework.org/schema/util\ul0\cf0}}}}\f8\fs15  {{\field{\*\fldinst{HYPERLINK http://www.springframework.org/schema/util/spring-util4.2.xsd }}{\fldrslt{http://www.springframework.org/schema/util/spring-util4.2.xsd\ul0\cf0}}}}\f8\fs15 "\cf19\i0 >\cf0\par
\par
\cf3\tab\cf22 <!-- \f2\'c5\'e4\'d6\'c3\'b5\'a5\'bb\'fa\'b0\'e6\'b5\'c4\'c1\'ac\'bd\'d3\f8  -->\cf0\par
\cf3\tab\cf19 <\cf20 bean\cf0  \cf21 id\cf3 =\cf17\i "jedisPool"\cf0\i0  \cf21 class\cf3 =\cf17\i "redis.clients.jedis.JedisPool"\cf19\i0 >\cf0\par
\cf3\tab\tab\cf19 <\cf20 constructor-arg\cf0  \cf21 name\cf3 =\cf17\i "host"\cf0\i0  \cf21 value\cf3 =\cf17\i "192.168.25.153"\cf19\i0 ></\cf20 constructor-arg\cf19 >\cf0\par
\cf3\tab\tab\cf19 <\cf20 constructor-arg\cf0  \cf21 name\cf3 =\cf17\i "port"\cf0\i0  \cf21 value\cf3 =\cf17\i "6379"\cf19\i0 ></\cf20 constructor-arg\cf19 >\cf0\par
\cf3\tab\cf19 </\cf20 bean\cf19 >\cf0\par
\cf3\tab\cf19 <\cf20 bean\cf0  \cf21 id\cf3 =\cf17\i "jedisClientPool"\cf0\i0  \cf21 class\cf3 =\cf17\i "cn.e3mall.jedis.JedisClientPool"\cf19\i0 />\cf0\par
\cf3\tab\cf0\par

\pard\intbl\nowidctlpar\qj\cf19\highlight14 <\highlight0 /\cf20 beans\cf19 >\cf0\f1\cell\row 
\pard\nowidctlpar\qj\fs21\par

\pard\nowidctlpar\s3\fi-709\li709\qj\tx709\fs32 5.1.3.\tab\f2\'bc\'af\'c8\'ba\'b0\'e6\'ca\'b5\'cf\'d6\'c0\'e0\f1\par
\trowd\trgaph10\trleft-118\trbrdrl\brdrs\brdrw10 \trbrdrt\brdrs\brdrw10 \trbrdrr\brdrs\brdrw10 \trbrdrb\brdrs\brdrw10 \trpaddl10\trpaddr10\trpaddfl3\trpaddfr3
\clbrdrl\brdrw10\brdrs\clbrdrt\brdrw10\brdrs\clbrdrr\brdrw10\brdrs\clbrdrb\brdrw10\brdrs \cellx8404 
\pard\intbl\nowidctlpar\cf13\b\f8\fs15 package\cf3\b0  cn.e3mall.jedis;\cf0\par
\par
\cf13\b import\cf3\b0  org.springframework.beans.factory.annotation.Autowired;\cf0\par
\par
\cf13\b import\cf3\b0  redis.clients.jedis.JedisCluster;\cf0\par
\par
\cf13\b public\cf3\b0  \cf13\b class\cf3\b0  JedisClientCluster \cf13\b implements\cf3\b0  JedisClient \{\cf0\par
\cf3\tab\cf0\par
\cf3\tab\cf12 @Autowired\cf0\par
\cf3\tab\cf13\b private\cf3\b0  JedisCluster \cf18 jedisCluster\cf3 ;\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  String set(String \cf16 key\cf3 , String \cf16 value\cf3 ) \{\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf18 jedisCluster\cf3 .set(\cf16 key\cf3 , \cf16 value\cf3 );\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  String get(String \cf16 key\cf3 ) \{\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf18 jedisCluster\cf3 .get(\cf16 key\cf3 );\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  Boolean exists(String \cf16 key\cf3 ) \{\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf18 jedisCluster\cf3 .exists(\cf16 key\cf3 );\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  Long expire(String \cf16 key\cf3 , \cf13\b int\cf3\b0  \cf16 seconds\cf3 ) \{\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf18 jedisCluster\cf3 .expire(\cf16 key\cf3 , \cf16 seconds\cf3 );\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  Long ttl(String \cf16 key\cf3 ) \{\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf18 jedisCluster\cf3 .ttl(\cf16 key\cf3 );\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  Long incr(String \cf16 key\cf3 ) \{\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf18 jedisCluster\cf3 .incr(\cf16 key\cf3 );\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  Long hset(String \cf16 key\cf3 , String \cf16 field\cf3 , String \cf16 value\cf3 ) \{\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf18 jedisCluster\cf3 .hset(\cf16 key\cf3 , \cf16 field\cf3 , \cf16 value\cf3 );\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  String hget(String \cf16 key\cf3 , String \cf16 field\cf3 ) \{\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf18 jedisCluster\cf3 .hget(\cf16 key\cf3 , \cf16 field\cf3 );\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\tab\cf12 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  Long hdel(String \cf16 key\cf3 , String... \cf16 field\cf3 ) \{\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  \cf18 jedisCluster\cf3 .hdel(\cf16 key\cf3 , \cf16 field\cf3 );\cf0\par
\cf3\tab\}\cf0\par
\par
\cf3\}\cf0\par

\pard\intbl\nowidctlpar\qj\f1\cell\row 
\pard\nowidctlpar\qj\fs21\par
Spring\f2\'b5\'c4\'c5\'e4\'d6\'c3\'a3\'ba\f1\par
\trowd\trgaph10\trleft-118\trbrdrl\brdrs\brdrw10 \trbrdrt\brdrs\brdrw10 \trbrdrr\brdrs\brdrw10 \trbrdrb\brdrs\brdrw10 \trpaddl10\trpaddr10\trpaddfl3\trpaddfr3
\clbrdrl\brdrw10\brdrs\clbrdrt\brdrw10\brdrs\clbrdrr\brdrw10\brdrs\clbrdrb\brdrw10\brdrs \cellx8404 
\pard\intbl\nowidctlpar\cf22\f8\fs15 <!-- \f2\'bc\'af\'c8\'ba\'b0\'e6\'b5\'c4\'c5\'e4\'d6\'c3\f8  -->\cf0\par
\cf3\tab\cf19 <\cf20 bean\cf0  \cf21 id\cf3 =\cf17\i "jedisCluster"\cf0\i0  \cf21 class\cf3 =\cf17\i "redis.clients.jedis.JedisCluster"\cf19\i0 >\cf0\par
\cf3\tab\tab\cf19 <\cf20 constructor-arg\cf19 >\cf0\par
\cf3\tab\tab\tab\cf19 <\cf20 set\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\cf19 <\cf20 bean\cf0  \cf21 class\cf3 =\cf17\i "redis.clients.jedis.HostAndPort"\cf19\i0 >\cf0\par
\cf3\tab\tab\tab\tab\tab\cf19 <\cf20 constructor-arg\cf0  \cf21 name\cf3 =\cf17\i "host"\cf0\i0  \cf21 value\cf3 =\cf17\i "192.168.25.153"\cf19\i0 ></\cf20 constructor-arg\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\tab\cf19 <\cf20 constructor-arg\cf0  \cf21 name\cf3 =\cf17\i "port"\cf0\i0  \cf21 value\cf3 =\cf17\i "7001"\cf19\i0 ></\cf20 constructor-arg\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\cf19 </\cf20 bean\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\cf19 <\cf20 bean\cf0  \cf21 class\cf3 =\cf17\i "redis.clients.jedis.HostAndPort"\cf19\i0 >\cf0\par
\cf3\tab\tab\tab\tab\tab\cf19 <\cf20 constructor-arg\cf0  \cf21 name\cf3 =\cf17\i "host"\cf0\i0  \cf21 value\cf3 =\cf17\i "192.168.25.153"\cf19\i0 ></\cf20 constructor-arg\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\tab\cf19 <\cf20 constructor-arg\cf0  \cf21 name\cf3 =\cf17\i "port"\cf0\i0  \cf21 value\cf3 =\cf17\i "7002"\cf19\i0 ></\cf20 constructor-arg\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\cf19 </\cf20 bean\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\cf19 <\cf20 bean\cf0  \cf21 class\cf3 =\cf17\i "redis.clients.jedis.HostAndPort"\cf19\i0 >\cf0\par
\cf3\tab\tab\tab\tab\tab\cf19 <\cf20 constructor-arg\cf0  \cf21 name\cf3 =\cf17\i "host"\cf0\i0  \cf21 value\cf3 =\cf17\i "192.168.25.153"\cf19\i0 ></\cf20 constructor-arg\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\tab\cf19 <\cf20 constructor-arg\cf0  \cf21 name\cf3 =\cf17\i "port"\cf0\i0  \cf21 value\cf3 =\cf17\i "7003"\cf19\i0 ></\cf20 constructor-arg\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\cf19 </\cf20 bean\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\cf19 <\cf20 bean\cf0  \cf21 class\cf3 =\cf17\i "redis.clients.jedis.HostAndPort"\cf19\i0 >\cf0\par
\cf3\tab\tab\tab\tab\tab\cf19 <\cf20 constructor-arg\cf0  \cf21 name\cf3 =\cf17\i "host"\cf0\i0  \cf21 value\cf3 =\cf17\i "192.168.25.153"\cf19\i0 ></\cf20 constructor-arg\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\tab\cf19 <\cf20 constructor-arg\cf0  \cf21 name\cf3 =\cf17\i "port"\cf0\i0  \cf21 value\cf3 =\cf17\i "7004"\cf19\i0 ></\cf20 constructor-arg\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\cf19 </\cf20 bean\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\cf19 <\cf20 bean\cf0  \cf21 class\cf3 =\cf17\i "redis.clients.jedis.HostAndPort"\cf19\i0 >\cf0\par
\cf3\tab\tab\tab\tab\tab\cf19 <\cf20 constructor-arg\cf0  \cf21 name\cf3 =\cf17\i "host"\cf0\i0  \cf21 value\cf3 =\cf17\i "192.168.25.153"\cf19\i0 ></\cf20 constructor-arg\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\tab\cf19 <\cf20 constructor-arg\cf0  \cf21 name\cf3 =\cf17\i "port"\cf0\i0  \cf21 value\cf3 =\cf17\i "7005"\cf19\i0 ></\cf20 constructor-arg\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\cf19 </\cf20 bean\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\cf19 <\cf20 bean\cf0  \cf21 class\cf3 =\cf17\i "redis.clients.jedis.HostAndPort"\cf19\i0 >\cf0\par
\cf3\tab\tab\tab\tab\tab\cf19 <\cf20 constructor-arg\cf0  \cf21 name\cf3 =\cf17\i "host"\cf0\i0  \cf21 value\cf3 =\cf17\i "192.168.25.153"\cf19\i0 ></\cf20 constructor-arg\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\tab\cf19 <\cf20 constructor-arg\cf0  \cf21 name\cf3 =\cf17\i "port"\cf0\i0  \cf21 value\cf3 =\cf17\i "7006"\cf19\i0 ></\cf20 constructor-arg\cf19 >\cf0\par
\cf3\tab\tab\tab\tab\cf19 </\cf20 bean\cf19 >\cf0\par
\cf3\tab\tab\tab\cf19 </\cf20 set\cf19 >\cf0\par
\cf3\tab\tab\cf19 </\cf20 constructor-arg\cf19 >\cf0\par
\cf3\tab\cf19 </\cf20 bean\cf19 >\cf0\par

\pard\intbl\nowidctlpar\qj\cf3\tab\cf19 <\cf20 bean\cf0  \cf21 id\cf3 =\cf17\i "jedisClientCluster"\cf0\i0  \cf21 class\cf3 =\cf17\i "cn.e3mall.jedis.JedisClientCluster"\cf19\i0 />\cf0\f1\cell\row 
\pard\nowidctlpar\qj\fs21\par
\highlight10\f2\'d7\'a2\'d2\'e2\'a3\'ba\'b5\'a5\'bb\'fa\'b0\'e6\'ba\'cd\'bc\'af\'c8\'ba\'b0\'e6\'b2\'bb\'c4\'dc\'b9\'b2\'b4\'e6\'a3\'ac\'ca\'b9\'d3\'c3\'b5\'a5\'bb\'fa\'b0\'e6\'ca\'b1\'d7\'a2\'ca\'cd\'bc\'af\'c8\'ba\'b0\'e6\'b5\'c4\'c5\'e4\'d6\'c3\'a1\'a3\'ca\'b9\'d3\'c3\'bc\'af\'c8\'ba\'b0\'e6\'a3\'ac\'b0\'d1\'b5\'a5\'bb\'fa\'b0\'e6\'d7\'a2\'ca\'cd\'a1\'a3\f1\par
\highlight0\par
\par

\pard\nowidctlpar\s2\fi-567\li567\qj\tx567\fs36 5.2.\tab\f2\'b7\'e2\'d7\'b0\'b4\'fa\'c2\'eb\'b2\'e2\'ca\'d4\f1\par
\trowd\trgaph10\trleft-118\trbrdrl\brdrs\brdrw10 \trbrdrt\brdrs\brdrw10 \trbrdrr\brdrs\brdrw10 \trbrdrb\brdrs\brdrw10 \trpaddl10\trpaddr10\trpaddfl3\trpaddfr3
\clbrdrl\brdrw10\brdrs\clbrdrt\brdrw10\brdrs\clbrdrr\brdrw10\brdrs\clbrdrb\brdrw10\brdrs \cellx8404 
\pard\intbl\nowidctlpar\cf12\f8\fs15 @Test\cf0\par
\cf3\tab\cf13\b public\cf3\b0  \cf13\b void\cf3\b0  \highlight14 testJedisClient\highlight0 () \cf13\b throws\cf3\b0  Exception \{\cf0\par
\cf3\tab\tab\cf15 //\f2\'b3\'f5\'ca\'bc\'bb\'af\f8 Spring\f2\'c8\'dd\'c6\'f7\cf0\f8\par
\cf3\tab\tab ApplicationContext \cf16\ul applicationContext\cf3\ulnone  = \cf13\b new\cf3\b0  ClassPathXmlApplicationContext(\cf17 "classpath:spring/applicationContext-redis.xml"\cf3 );\cf0\par
\cf3\tab\tab\cf15 //\f2\'b4\'d3\'c8\'dd\'c6\'f7\'d6\'d0\'bb\'f1\'b5\'c3\f8 JedisClient\f2\'b6\'d4\'cf\'f3\cf0\f8\par
\cf3\tab\tab JedisClient \cf16 jedisClient\cf3  = \cf16 applicationContext\cf3 .getBean(JedisClient.\cf13\b class\cf3\b0 );\cf0\par
\cf3\tab\tab\cf16 jedisClient\cf3 .set(\cf17 "first"\cf3 , \cf17 "100"\cf3 );\cf0\par
\cf3\tab\tab String \cf16 result\cf3  = \cf16 jedisClient\cf3 .get(\cf17 "first"\cf3 );\cf0\par
\cf3\tab\tab System.\cf18\b\i out\cf3\b0\i0 .println(\cf16 result\cf3 );\cf0\par
\cf3\tab\tab\cf0\par
\cf3\tab\tab\tab\tab\cf0\par

\pard\intbl\nowidctlpar\qj\cf3\tab\}\cf0\f1\cell\row 
\pard\nowidctlpar\qj\fs21\par

\pard\nowidctlpar\s2\fi-567\li567\qj\tx567\fs36 5.3.\tab\f2\'cc\'ed\'bc\'d3\'bb\'ba\'b4\'e6\f1\par

\pard\nowidctlpar\s3\fi-709\li709\qj\tx709\fs32 5.3.1.\tab\f2\'b9\'a6\'c4\'dc\'b7\'d6\'ce\'f6\f1\par

\pard\nowidctlpar\qj\f2\fs21\'b2\'e9\'d1\'af\'c4\'da\'c8\'dd\'c1\'d0\'b1\'ed\'ca\'b1\'cc\'ed\'bc\'d3\'bb\'ba\'b4\'e6\'a1\'a3\f1\par

\pard 
{\pntext\f1 1\tab}{\*\pn\pnlvlbody\pnf1\pnindent360\pnstart1\pndec }
\nowidctlpar\qj\f2\'b2\'e9\'d1\'af\'ca\'fd\'be\'dd\'bf\'e2\'d6\'ae\'c7\'b0\'cf\'c8\'b2\'e9\'d1\'af\'bb\'ba\'b4\'e6\'a1\'a3\f1\par
{\pntext\f1 2\tab}\f2\'b2\'e9\'d1\'af\'b5\'bd\'bd\'e1\'b9\'fb\'a3\'ac\'d6\'b1\'bd\'d3\'cf\'ec\'d3\'a6\'bd\'e1\'b9\'fb\'a1\'a3\f1\par
{\pntext\f1 3\tab}\f2\'b2\'e9\'d1\'af\'b2\'bb\'b5\'bd\'a3\'ac\'bb\'ba\'b4\'e6\'d6\'d0\'c3\'bb\'d3\'d0\'d0\'e8\'d2\'aa\'b2\'e9\'d1\'af\'ca\'fd\'be\'dd\'bf\'e2\'a1\'a3\f1\par
{\pntext\f1 4\tab}\f2\'b0\'d1\'b2\'e9\'d1\'af\'bd\'e1\'b9\'fb\'cc\'ed\'bc\'d3\'b5\'bd\'bb\'ba\'b4\'e6\'d6\'d0\'a1\'a3\f1\par
{\pntext\f1 5\tab}\f2\'b7\'b5\'bb\'d8\'bd\'e1\'b9\'fb\'a1\'a3\f1\par

\pard\nowidctlpar\qj\par
\f2\'cf\'f2\f1 redis\f2\'d6\'d0\'cc\'ed\'bc\'d3\'bb\'ba\'b4\'e6\'a3\'ba\f1\par
Key\f2\'a3\'ba\f1 cid\par
Value\f2\'a3\'ba\'c4\'da\'c8\'dd\'c1\'d0\'b1\'ed\'a1\'a3\'d0\'e8\'d2\'aa\'b0\'d1\f1 java\f2\'b6\'d4\'cf\'f3\'d7\'aa\'bb\'bb\'b3\'c9\f1 json\f2\'a1\'a3\f1\par
\par
\f2\'ca\'b9\'d3\'c3\f1 hash\f2\'b6\'d4\f1 key\f2\'bd\'f8\'d0\'d0\'b9\'e9\'c0\'e0\'a1\'a3\f1\par
HASH_KEY:HASH\par
            |--KEY:VALUE\par
            |--KEY:VALUE\par
            |--KEY:VALUE\par
            |--KEY:VALUE\par
\par
\par
\highlight10\b\f2\'d7\'a2\'d2\'e2\'a3\'ba\'cc\'ed\'bc\'d3\'bb\'ba\'b4\'e6\'b2\'bb\'c4\'dc\'d3\'b0\'cf\'ec\'d5\'fd\'b3\'a3\'d2\'b5\'ce\'f1\'c2\'df\'bc\'ad\'a1\'a3\highlight0\b0\f1\par
\par

\pard\nowidctlpar\s3\fi-709\li709\qj\tx709\fs32 5.3.2.\tab\f2\'b4\'fa\'c2\'eb\'ca\'b5\'cf\'d6\f1\par
\trowd\trgaph10\trleft-118\trbrdrl\brdrs\brdrw10 \trbrdrt\brdrs\brdrw10 \trbrdrr\brdrs\brdrw10 \trbrdrb\brdrs\brdrw10 \trpaddl10\trpaddr10\trpaddfl3\trpaddfr3
\clbrdrl\brdrw10\brdrs\clbrdrt\brdrw10\brdrs\clbrdrr\brdrw10\brdrs\clbrdrb\brdrw10\brdrs \cellx8404 
\pard\intbl\nowidctlpar\cf12\f8\fs15 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  \highlight14 List<TbContent>\highlight0  getContentList(\cf13\b long\cf3\b0  \cf16 cid\cf3 ) \{\cf0\par
\cf3\tab\tab\cf15 //\f2\'b2\'e9\'d1\'af\'bb\'ba\'b4\'e6\cf0\f8\par
\cf3\tab\tab\cf13\b try\cf3\b0  \{\cf0\par
\cf3\tab\tab\tab String \cf16 json\cf3  = \cf18 jedisClient\cf3 .hget(\cf18 CONTENT_KEY\cf3 , \cf16 cid\cf3  + \cf17 ""\cf3 );\cf0\par
\cf3\tab\tab\tab\cf15 //\f2\'c5\'d0\'b6\'cf\ul\f8 json\ulnone\f2\'ca\'c7\'b7\'f1\'ce\'aa\'bf\'d5\cf0\f8\par
\cf3\tab\tab\tab\cf13\b if\cf3\b0  (StringUtils.\i isNotBlank\i0 (\cf16 json\cf3 )) \{\cf0\par
\cf3\tab\tab\tab\tab\cf15 //\f2\'b0\'d1\ul\f8 json\ulnone\f2\'d7\'aa\'bb\'bb\'b3\'c9\f8 list\cf0\par
\cf3\tab\tab\tab\tab List<TbContent> \cf16 list\cf3  = JsonUtils.\i jsonToList\i0 (\cf16 json\cf3 , TbContent.\cf13\b class\cf3\b0 );\cf0\par
\cf3\tab\tab\tab\tab\cf13\highlight14\b return\cf3\b0  \cf16 list\cf3 ;\cf0\highlight0\par
\cf3\tab\tab\tab\}\cf0\par
\cf3\tab\tab\} \cf13\b catch\cf3\b0  (Exception \cf16 e\cf3 ) \{\cf0\par
\cf3\tab\tab\tab\cf16 e\cf3 .printStackTrace();\cf0\par
\cf3\tab\tab\}\cf0\par
\cf3\tab\tab\cf15 //\f2\'b8\'f9\'be\'dd\ul\f8 cid\ulnone\f2\'b2\'e9\'d1\'af\'c4\'da\'c8\'dd\'c1\'d0\'b1\'ed\cf0\f8\par
\cf3\tab\tab TbContentExample \cf16 example\cf3  = \cf13\b new\cf3\b0  TbContentExample();\cf0\par
\cf3\tab\tab\cf15 //\f2\'c9\'e8\'d6\'c3\'b2\'e9\'d1\'af\'cc\'f5\'bc\'fe\cf0\f8\par
\cf3\tab\tab Criteria \cf16 criteria\cf3  = \cf16 example\cf3 .createCriteria();\cf0\par
\cf3\tab\tab\cf16 criteria\cf3 .andCategoryIdEqualTo(\cf16 cid\cf3 );\cf0\par
\cf3\tab\tab\cf15 //\f2\'d6\'b4\'d0\'d0\'b2\'e9\'d1\'af\cf0\f8\par
\cf3\tab\tab List<TbContent> \cf16 list\cf3  = \cf18 contentMapper\cf3 .selectByExample(\cf16 example\cf3 );\cf0\par
\cf3\tab\tab\cf15 //\f2\'cf\'f2\'bb\'ba\'b4\'e6\'d6\'d0\'cc\'ed\'bc\'d3\'ca\'fd\'be\'dd\cf0\f8\par
\cf3\tab\tab\cf13\b try\cf3\b0  \{\cf0\par
\cf3\tab\tab\tab\cf18 jedisClient\cf3 .hset(\cf18 CONTENT_KEY\cf3 , \cf16 cid\cf3  + \cf17 ""\cf3 , JsonUtils.\i objectToJson\i0 (\cf16 list\cf3 ));\cf0\par
\cf3\tab\tab\} \cf13\b catch\cf3\b0  (Exception \cf16 e\cf3 ) \{\cf0\par
\cf3\tab\tab\tab\cf16 e\cf3 .printStackTrace();\cf0\par
\cf3\tab\tab\}\cf0\par
\cf3\tab\tab\cf13\highlight14\b return\cf3\b0  \cf16 list\cf3 ;\cf0\highlight0\par

\pard\intbl\nowidctlpar\qj\cf3\tab\}\cf0\f1\cell\row 
\pard\nowidctlpar\qj\fs21\par

\pard\nowidctlpar\s2\fi-567\li567\qj\tx567\fs36 5.4.\tab\f2\'bb\'ba\'b4\'e6\'cd\'ac\'b2\'bd\f1\par

\pard\nowidctlpar\qj\f2\fs21\'b6\'d4\'c4\'da\'c8\'dd\'d0\'c5\'cf\'a2\'d7\'f6\'d4\'f6\'c9\'be\'b8\'c4\'b2\'d9\'d7\'f7\'ba\'f3\'d6\'bb\'d0\'e8\'d2\'aa\'b0\'d1\'b6\'d4\'d3\'a6\'bb\'ba\'b4\'e6\'c9\'be\'b3\'fd\'bc\'b4\'bf\'c9\'a1\'a3\f1\par
\f2\'bf\'c9\'d2\'d4\'b8\'f9\'be\'dd\f1 cid\f2\'c9\'be\'b3\'fd\'a1\'a3\f1\par
\trowd\trgaph10\trleft-118\trbrdrl\brdrs\brdrw10 \trbrdrt\brdrs\brdrw10 \trbrdrr\brdrs\brdrw10 \trbrdrb\brdrs\brdrw10 \trpaddl10\trpaddr10\trpaddfl3\trpaddfr3
\clbrdrl\brdrw10\brdrs\clbrdrt\brdrw10\brdrs\clbrdrr\brdrw10\brdrs\clbrdrb\brdrw10\brdrs \cellx8404 
\pard\intbl\nowidctlpar\cf12\f8\fs15 @Override\cf0\par
\cf3\tab\cf13\b public\cf3\b0  E3Result addContent(TbContent \cf16 content\cf3 ) \{\cf0\par
\cf3\tab\tab\cf15 //\f2\'b2\'b9\'c8\'ab\'ca\'f4\'d0\'d4\cf0\f8\par
\cf3\tab\tab\cf16 content\cf3 .setCreated(\cf13\b new\cf3\b0  Date());\cf0\par
\cf3\tab\tab\cf16 content\cf3 .setUpdated(\cf13\b new\cf3\b0  Date());\cf0\par
\cf3\tab\tab\cf15 //\f2\'b2\'e5\'c8\'eb\'ca\'fd\'be\'dd\cf0\f8\par
\cf3\tab\tab\cf18 contentMapper\cf3 .insert(\cf16 content\cf3 );\cf0\par
\cf3\tab\tab\cf15 //\f2\'bb\'ba\'b4\'e6\'cd\'ac\'b2\'bd\cf0\f8\par
\cf3\tab\tab\cf18 jedisClient\cf3 .hdel(\cf18 CONTENT_KEY\cf3 , \cf16 content\cf3 .getCategoryId().toString());\cf0\par
\cf3\tab\tab\cf0\par
\cf3\tab\tab\cf13\b return\cf3\b0  E3Result.\i ok\i0 ();\cf0\par

\pard\intbl\nowidctlpar\qj\cf3\tab\}\cf0\f1\cell\row 
\pard\nowidctlpar\qj\f0\fs21\par

\pard\kerning0\f3\fs22\lang0\par
}
 