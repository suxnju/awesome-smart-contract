
# Ethereum Papers

Paper list on Ethereum with special attention to smart contracts.

Related Repositories:
- https://github.com/jianyu-niu/blockchain_conference_paper
- https://github.com/hzysvilla/Academic_Smart_Contract_Papers

## Table of Listed Conferences
- [IEEE Security and Privacy(S&P)](#s&p)
- [USENIX Security(Security)](#security)
- [ACM Conference on Computer and Communications Security(CCS)](#ccs)
- [Network and Distributed System Security(NDSS)](#ndss)
- [International Conference on Software Engineering(ICSE)](#icse)
- [ACM SIGPLAN International Conference on Object-Oriented Programming Systems,Languages,and Applications(OOPSLA)](#oopsla)
- [International Conference on Automated Software Engineering(ASE)](#ase)
- [ACM SIGSOFT Symposium on the Foundation of Software Engineering/ European Software Engineering Conference(FSE/ESEC)](#fse)
- [International Symposium on Software Testing and Analysis(ISSTA)](#issta)
- [ACM SIGPLAN Conference on Programming Language Design & Implementation(PLDI)](#pldi)
- [USENIX Symposium on Operating Systems Design and Implementations(OSDI)](#osdi)
- [other papers](#other)

## Table of Listed Journals
- [IEEE Transactions on Information Forensics and Security(TIFS)](#tifs)
- [IEEE Transactions on Software Engineering(TSE)](#tse)

*Key Words*: Smart Contracts,DApps,Vulnerability Detection,Attack Detection.

*Output*: Paper[link], authors, conference/journal, year, shortname/tool

## Conferences

### s&p
- [VeriSmart: A Highly Precise Safety Verifier for Ethereum Smart Contracts](http://arxiv.org/abs/1908.11227). "So, Sunbeom;Lee, Myungho;Park, Jisu;Lee, Heejo;Oh, Hakjoo". s&p. 2019. [VeriSmart].
- [Flash Boys 2.0: Frontrunning in Decentralized Exchanges, Miner Extractable Value, and Consensus Instability](). "Daian, Philip;Goldfeder, Steven;Kell, Tyler;Li, Yunqi;Zhao, Xueyuan;Bentov, Iddo;Breidenbach, Lorenz;Juels, Ari". s&p. 2020. [Flash Boys 2.0].
- [Semantic Understanding of Smart Contracts: Executable Operational Semantics of Solidity](). "Jiao, Jiao;Kan, Shuanglong;Lin, Shang-Wei;Sanan, David;Liu, Yang;Sun, Jun". s&p. 2020. [Semantic Understanding of Smart Contracts].
- [VerX: Safety Verification of Smart Contracts](). "Permenev, Anton;Dimitrov, Dimitar;Tsankov, Petar;Drachsler-Cohen, Dana;Vechev, Martin". s&p. 2020. [VerX].
- [Compositional Security for Reentrant Applications](http://arxiv.org/abs/2103.08577). "Cecchetti, Ethan;Yao, Siqiu;Ni, Haobin;Myers, Andrew C.". s&p. 2021.
- [MAD-HTLC: Because HTLC is Crazy-Cheap to Attack](http://arxiv.org/abs/2006.12031). "Tsabary, Itay;Yechieli, Matan;Manuskin, Alex;Eyal, Ittay". s&p. 2021. [MAD-HTLC].
- [On the Just-In-Time Discovery of Profit-Generating Transactions in DeFi Protocols](http://arxiv.org/abs/2103.02228). "Zhou, Liyi;Qin, Kaihua;Cully, Antoine;Livshits, Benjamin;Gervais, Arthur". s&p. 2021.
- [SmartPulse: Automated Checking of Temporal Properties in Smart Contracts](https://ieeexplore.ieee.org/document/9519387/). "Stephens, Jon;Ferles, Kostas;Mariano, Benjamin;Lahiri, Shuvendu;Dillig, Isil". s&p. 2021. [SmartPulse].
- [sGUARD: Towards Fixing Vulnerable Smart Contracts Automatically](http://arxiv.org/abs/2101.01917). "Nguyen, Tai D.;Pham, Long H.;Sun, Jun". s&p. 2021. [sGUARD].

### security
- [Enter the Hydra: Towards Principled Bug Bounties and Exploit-Resistant Smart Contracts](https://www.usenix.org/conference/usenixsecurity18/presentation/breindenbach). "Breidenbach, Lorenz;Daian, Phil;Tramer, Florian;Juels, Ari". security. 2018. [Enter the Hydra].
- [Erays: Reverse Engineering Ethereum's Opaque Smart Contracts](https://www.usenix.org/conference/usenixsecurity18/presentation/zhou). "Zhou, Yi;Kumar, Deepak;Bakshi, Surya;Mason, Joshua;Miller, Andrew;Bailey, Michael". security. 2018. [Erays].
- [teEther: Gnawing at Ethereum to Automatically Exploit Smart Contracts](https://www.usenix.org/conference/usenixsecurity18/presentation/krupp). "Krupp, Johannes;Rossow, Christian". security. 2018. [teEther].
- [The Art of The Scam: Demystifying Honeypots in Ethereum Smart Contracts](). "Torres, Christof Ferreira;Steichen, Mathis". security. 2019.
- [An Ever-evolving Game: Evaluation of Real-world Attacks and Defenses in Ethereum Ecosystem](https://www.usenix.org/conference/usenixsecurity20/presentation/zhou-shunfan). "Zhou, Shunfan;Yang, Zhemin;Xiang, Jie;Cao, Yinzhi;Yang, Zhemin;Zhang, Yuan". security. 2020. [An Ever-evolving Game].
- [{EOSAFE}: Security Analysis of {EOSIO} Smart Contracts](https://www.usenix.org/conference/usenixsecurity21/presentation/he-ningyu). "He, Ningyu;Zhang, Ruiyi;Wang, Haoyu;Wu, Lei;Luo, Xiapu;Guo, Yao;Yu, Ting;Jiang, Xuxian". security. 2020. [{EOSAFE}].
- [{ETHBMC}: A Bounded Model Checker for Smart Contracts](https://www.usenix.org/conference/usenixsecurity20/presentation/frank). "Frank, Joel;Aschermann, Cornelius;Holz, Thorsten". security. 2020. [{ETHBMC}].
- [{TXSPECTOR}: Uncovering Attacks in Ethereum from Transactions](https://www.usenix.org/conference/usenixsecurity20/presentation/zhang-mengya). "Zhang, Mengya;Zhang, Xiaokuan;Zhang, Yinqian;Lin, Zhiqiang". security. 2020. [{TXSPECTOR}].
- [EVMPatch: Timely and Automated Patching of Ethereum Smart Contracts](http://arxiv.org/abs/2010.00341). "Rodler, Michael;Li, Wenting;Karame, Ghassan O.;Davi, Lucas". security. 2021. [EVMPatch].
- [Evil Under the Sun: Understanding and Discovering Attacks on Ethereum Decentralized Applications](https://www.usenix.org/conference/usenixsecurity21/presentation/su). "Su, Liya;Shen, Xinyue;Du, Xiangyu;Liao, Xiaojing;Wang, XiaoFeng;Xing, Luyi;Liu, Baoxu". security. 2021. [Evil Under the Sun].
- [Frontrunner Jones and the Raiders of the Dark Forest: An Empirical Study of Frontrunning on the Ethereum Blockchain](https://arxiv.org/abs/2102.03347v2). "Torres, Christof Ferreira;Camino, Ramiro;State, Radu". security. 2021. [Frontrunner Jones and the Raiders of the Dark Forest].
- [SMARTEST: Effectively Hunting Vulnerable Transaction Sequences in Smart Contracts through Language Model-Guided Symbolic Execution](). "So, Sunbeom;Hong, Seongjoon;Oh, Hakjoo". security. 2021.
- [Smart Contract Vulnerabilities: Vulnerable Does Not Imply Exploited](http://arxiv.org/abs/1902.06710). "Perez, Daniel;Livshits, Benjamin". security. 2021. [Smart Contract Vulnerabilities].

### ccs
- [Making Smart Contracts Smarter](http://eprint.iacr.org/2016/633). "Luu, Loi;Chu, Duc-Hiep;Olickel, Hrishi;Saxena, Prateek;Hobor, Aquinas". ccs. 2016.
- [Town Crier: An Authenticated Data Feed for Smart Contracts](http://eprint.iacr.org/2016/168). "Zhang, Fan;Cecchetti, Ethan;Croman, Kyle;Juels, Ari;Shi, Elaine". ccs. 2016. [Town Crier].
- [Securify: Practical Security Analysis of Smart Contracts](https://doi.org/10.1145/3243734.3243780). "Tsankov, Petar;Dan, Andrei;Drachsler-Cohen, Dana;Gervais, Arthur;B??nzli, Florian;Vechev, Martin". ccs. 2018. [Securify].
- [Learning to Fuzz from Symbolic Execution with Application to Smart Contracts](https://dl.acm.org/doi/10.1145/3319535.3363230). "He, Jingxuan;Balunovi??, Mislav;Ambroladze, Nodar;Tsankov, Petar;Vechev, Martin". ccs. 2019.
- [TokenScope: Automatically Detecting Inconsistent Behaviors of Cryptocurrency Tokens in Ethereum](https://dl.acm.org/doi/10.1145/3319535.3345664). "Chen, Ting;Zhang, Yufei;Li, Zihao;Luo, Xiapu;Wang, Ting;Cao, Rong;Xiao, Xiuzhuo;Zhang, Xiaosong". ccs. 2019. [TokenScope].
- [BDoS: Blockchain Denial of Service](http://arxiv.org/abs/1912.07497). "Mirkin, Michael;Ji, Yan;Pang, Jonathan;Klages-Mundt, Ariah;Eyal, Ittay;Juels, Ari". ccs. 2020. [BDoS].
- [eThor: Practical and Provably Sound Static Analysis of Ethereum Smart Contracts](https://arxiv.org/abs/2005.06227v1). "Schneidewind, Clara;Grishchenko, Ilya;Scherer, Markus;Maffei, Matteo". ccs. 2020. [eThor].

### ndss
- [ZEUS: Analyzing Safety of Smart Contracts](https://www.ndss-symposium.org/wp-content/uploads/2018/02/ndss2018_09-1_Kalra_paper.pdf). "Kalra, Sukrit;Goel, Seep;Dhawan, Mohan;Sharma, Subodh". ndss. 2018. [ZEUS].
- [Sereum: Protecting Existing Smart Contracts Against Re-Entrancy Attacks](). "Rodler, Michael;Li, Wenting;Karame, Ghassan O;Davi, Lucas". ndss. 2019.
- [SODA: A Generic Online Detection Framework for Smart Contracts](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24449.pdf). "Chen, Ting;Cao, Rong;Li, Ting;Luo, Xiapu;Gu, Guofei;Zhang, Yufei;Liao, Zhou;Zhu, Hang;Chen, Gang;He, Zheyuan;Tang, Yuxing;Lin, Xiaodong;Zhang, Xiaosong". ndss. 2020. [SODA].

### icse
- [ReGuard: Finding Reentrancy Bugs in Smart Contracts](). "Liu, Chao;Liu, Han;Cao, Zhao;Chen, Zhong;Chen, Bangdao;Roscoe, Bill". icse. 2018. [ReGuard].
- [Towards Saving Money in Using Smart Contracts](). "Chen, Ting;Li, Zihao;Zhou, Hao;Chen, Jiachi;Luo, Xiapu;Li, Xiaoqi;Zhang, Xiaosong". icse. 2018.
- [EASYFLOW: Keep Ethereum Away from Overflow](). "Gao, Jianbo;Liu, Han;Liu, Chao;Li, Qingshan;Guan, Zhi;Chen, Zhong". icse. 2019. [EASYFLOW].
- [Gigahorse: Thorough, Declarative Decompilation of Smart Contracts](). "Grech, N.;Brent, L.;Scholz, B.;Smaragdakis, Y.". icse. 2019. [Gigahorse].
- [VULTRON: Catching Vulnerable Smart Contracts Once and for All](). "Wang, Haijun;Li, Yi;Lin, Shang-Wei;Ma, Lei;Liu, Yang". icse. 2019. [VULTRON].
- [ADF-GA: Data Flow Criterion Based Test Case Generation for Ethereum Smart Contracts](http://arxiv.org/abs/2003.00257). "Zhang, Pengcheng;Yu, Jianan;Ji, Shunhui". icse. 2020. [ADF-GA].
- [Empirical review of automated analysis tools on 47,587 Ethereum smart contracts](https://doi.org/10.1145/3377811.3380364). "Durieux, Thomas;Ferreira, Jo??o F.;Abreu, Rui;Cruz, Pedro". icse. 2020.
- [Finding Concurrency Exploits on Smart Contracts](). "Li, Yue". icse. 2020.
- [Gap between theory and practice: an empirical study of security patches in solidity](https://doi.org/10.1145/3377811.3380424). "Hwang, Sungjae;Ryu, Sukyoung". icse. 2020. [Gap between theory and practice].
- [Seraph: enabling cross-platform security analysis for EVM and WASM smart contracts](https://doi.org/10.1145/3377812.3382157). "Yang, Zhiqiang;Liu, Han;Li, Yue;Zheng, Huixuan;Wang, Lei;Chen, Bangdao". icse. 2020. [Seraph].
- [Smart Contract Development: Challenges and Opportunities](). "Zou, Weiqin;Lo, David;Kochhar, Pavneet Singh;Le, Xuan-Bach D.;Xia, Xin;Feng, Yang;Chen, Zhenyu;Xu, Baowen". icse. 2020. [Smart Contract Development].
- [Targeted greybox fuzzing with static lookahead analysis](https://dl.acm.org/doi/10.1145/3377811.3380388). "W??stholz, Valentin;Christakis, Maria". icse. 2020.
- [sFuzz: An Efficient Adaptive Fuzzer for Solidity Smart Contracts](http://arxiv.org/abs/2004.08563). "Nguyen, Tai D.;Pham, Long H.;Sun, Jun;Lin, Yun;Minh, Quang Tran". icse. 2020. [sFuzz].
- [EtherSolve: Computing an Accurate Control-Flow Graph from Ethereum Bytecode](http://arxiv.org/abs/2103.09113). "Contro, Filippo;Crosara, Marco;Ceccato, Mariano;Preda, Mila Dalla". icse. 2021. [EtherSolve].
- [Smart Contract Security: a Practitioners' Perspective](http://arxiv.org/abs/2102.10963). "Wan, Zhiyuan;Xia, Xin;Lo, David;Chen, Jiachi;Luo, Xiapu;Yang, Xiaohu". icse. 2021. [Smart Contract Security].

### oopsla
- [MadMax: surviving out-of-gas conditions in Ethereum smart contracts](https://doi.org/10.1145/3276486). "Grech, Neville;Kong, Michael;Jurisevic, Anton;Brent, Lexi;Scholz, Bernhard;Smaragdakis, Yannis". oopsla. 2018. [MadMax].
- [Automatic and scalable detection of logical errors in functional programming assignments](https://doi.org/10.1145/3360614). "Song, Dowon;Lee, Myungho;Oh, Hakjoo". oopsla. 2019.
- [Detecting nondeterministic payment bugs in Ethereum smart contracts](https://dl.acm.org/doi/10.1145/3360615). "Wang, Shuai;Zhang, Chengyu;Su, Zhendong". oopsla. 2019.
- [Safer smart contract programming with Scilla](https://dl.acm.org/doi/10.1145/3360611). "Sergey, Ilya;Nagaraj, Vaivaswatha;Johannsen, Jacob;Kumar, Amrit;Trunov, Anton;Hao, Ken Chan Guan". oopsla. 2019.
- [Precise static modeling of Ethereum ???memory???](https://doi.org/10.1145/3428258). "Lagouvardos, Sifis;Grech, Neville;Tsatiris, Ilias;Smaragdakis, Yannis". oopsla. 2020.
- [Rich Specifications for Ethereum Smart Contract Verification](http://arxiv.org/abs/2104.10274). "Br??m, Christian;Eilers, Marco;M??ller, Peter;Sierra, Robin;Summers, Alexander J.". oopsla. 2021.
- [Symbolic Value-Flow Static Analysis: Deep, Precise, Complete Modeling of Ethereum Smart Contracts](). "Smaragdakis, Yannis;Grech, Neville;Lagouvardos, Sifis;Triantafyllou, Konstantinos;Tsatiris, Ilias". oopsla. 2021.

### ase
- [ContractFuzzer: fuzzing smart contracts for vulnerability detection](https://doi.org/10.1145/3238147.3238177). "Jiang, Bo;Liu, Ye;Chan, W. K.". ase. 2018. [ContractFuzzer].
- [S-gram: towards semantic-aware security auditing for Ethereum smart contracts](https://doi.org/10.1145/3238147.3240728). "Liu, Han;Liu, Chao;Zhao, Wenqi;Jiang, Yu;Sun, Jiaguang". ase. 2018. [S-gram].
- [Manticore: A User-Friendly Symbolic Execution Framework for Binaries and Smart Contracts](). "Mossberg, Mark;Manzano, Felipe;Hennenfent, Eric;Groce, Alex;Grieco, Gustavo;Feist, Josselin;Brunson, Trent;Dinaburg, Artem". ase. 2019. [Manticore].
- [MuSC: A Tool for Mutation Testing of Ethereum Smart Contract](). "Li, Zixin;Wu, Haoran;Xu, Jiehui;Wang, Xingya;Zhang, Lingming;Chen, Zhenyu". ase. 2019. [MuSC].
- [Cross-contract static analysis for detecting practical reentrancy vulnerabilities in smart contracts](https://dl.acm.org/doi/10.1145/3324884.3416553). "Xue, Yinxing;Ma, Mingliang;Lin, Yun;Sui, Yulei;Ye, Jiaming;Peng, Tianyong". ase. 2020.
- [Demystifying loops in smart contracts](https://dl.acm.org/doi/10.1145/3324884.3416626). "Mariano, Benjamin;Chen, Yanju;Feng, Yu;Lahiri, Shuvendu K.;Dillig, Isil". ase. 2020.
- [SmartBugs: a framework to analyze solidity smart contracts](https://dl.acm.org/doi/10.1145/3324884.3415298). "Ferreira, Jo??o F.;Cruz, Pedro;Durieux, Thomas;Abreu, Rui". ase. 2020. [SmartBugs].
- [Summary-based symbolic evaluation for smart contracts](https://doi.org/10.1145/3324884.3416646). "Feng, Yu;Torlak, Emina;Bodik, Rastislav". ase. 2020.
- [When deep learning meets smart contracts](https://doi.org/10.1145/3324884.3418918). "Gao, Zhipeng". ase. 2020.
- [Characterizing Transaction-Reverting Statements in Ethereum Smart Contracts](http://arxiv.org/abs/2108.10799). "Liu, Lu;Wei, Lili;Zhang, Wuqi;Wen, Ming;Liu, Yepang;Cheung, Shing-Chi". ase. 2021.
- [SMARTIAN: Enhancing Smart Contract Fuzzing with Static and Dynamic Data-Flow Analyses](). "Choi, Jaeseung;Grieco, Gustavo;Kim, Doyeon;Groce, Alex;Kim, Soomin;Cha, Sang Kil". ase. 2021.

### fse
- [A formal verification tool for Ethereum VM bytecode](https://dl.acm.org/doi/10.1145/3236024.3264591). "Park, Daejun;Zhang, Yi;Saxena, Manasvi;Daian, Philip;Ro??u, Grigore". fse. 2018.
- [A graph-based framework for analysing the design of smart contracts](https://doi.org/10.1145/3338906.3342495). "Vandenbogaerde, Bram". fse. 2019.
- [EVMFuzzer: detect EVM vulnerabilities via fuzz testing](https://dl.acm.org/doi/10.1145/3338906.3341175). "Fu, Ying;Ren, Meng;Ma, Fuchen;Shi, Heyuan;Yang, Xin;Jiang, Yu;Li, Huizhong;Shi, Xiang". fse. 2019. [EVMFuzzer].
- [Harvey: a greybox fuzzer for smart contracts](https://dl.acm.org/doi/10.1145/3368089.3417064). "W??stholz, Valentin;Christakis, Maria". fse. 2020. [Harvey].
- [ModCon: a model-based testing platform for smart contracts](https://doi.org/10.1145/3368089.3417939). "Liu, Ye;Li, Yi;Lin, Shang-Wei;Yan, Qiang". fse. 2020. [ModCon].
- [Towards automated verification of smart contract fairness](https://dl.acm.org/doi/10.1145/3368089.3409740). "Liu, Ye;Li, Yi;Lin, Shang-Wei;Zhao, Rong". fse. 2020.
- [iBatch: saving Ethereum fees via secure and cost-effective batching of smart-contract invocations](https://dl.acm.org/doi/10.1145/3468264.3468568). "Wang, Yibo;Zhang, Qi;Li, Kai;Tang, Yuzhe;Chen, Jiaqi;Luo, Xiapu;Chen, Ting". fse. 2021. [iBatch].

### issta
- [Exploiting The Laws of Order in Smart Contracts](http://arxiv.org/abs/1810.11605). "Kolluri, Aashish;Nikolic, Ivica;Sergey, Ilya;Hobor, Aquinas;Saxena, Prateek". issta. 2019.
- [SAFEVM: a safety verifier for Ethereum smart contracts](https://doi.org/10.1145/3293882.3338999). "Albert, Elvira;Correas, Jes??s;Gordillo, Pablo;Rom??n-D??ez, Guillermo;Rubio, Albert". issta. 2019. [SAFEVM].
- [EShield: protect smart contracts against reverse engineering](https://doi.org/10.1145/3395363.3404365). "Yan, Wentian;Gao, Jianbo;Wu, Zhenhao;Li, Yue;Guan, Zhi;Li, Qingshan;Chen, Zhong". issta. 2020. [EShield].
- [Echidna: effective, usable, and fast fuzzing for smart contracts](https://doi.org/10.1145/3395363.3404366). "Grieco, Gustavo;Song, Will;Cygan, Artur;Feist, Josselin;Groce, Alex". issta. 2020. [Echidna].
- [How effective are smart contract analysis tools? evaluating smart contract static analysis tools using bug injection](https://doi.org/10.1145/3395363.3397385). "Ghaleb, Asem;Pattabiraman, Karthik". issta. 2020. [How effective are smart contract analysis tools?].
- [echidna-parade: a tool for diverse multicore smart contract fuzzing](https://doi.org/10.1145/3460319.3469076). "Groce, Alex;Grieco, Gustavo". issta. 2021. [echidna-parade].

### pldi
- [Behavioral simulation for smart contracts](https://doi.org/10.1145/3385412.3386022). "Beillahi, Sidi Mohamed;Ciocarlie, Gabriela;Emmi, Michael;Enea, Constantin". pldi. 2020.
- [Ethainter: a smart contract security analyzer for composite vulnerabilities](https://doi.org/10.1145/3385412.3385990). "Brent, Lexi;Grech, Neville;Lagouvardos, Sifis;Scholz, Bernhard;Smaragdakis, Yannis". pldi. 2020. [Ethainter].
- [Securing smart contract with runtime validation](https://doi.org/10.1145/3385412.3385982). "Li, Ao;Choi, Jemin Andrew;Long, Fan". pldi. 2020.
- [Practical smart contract sharding with ownership and commutativity analysis](https://dl.acm.org/doi/10.1145/3453483.3454112). "P??rlea, George;Kumar, Amrit;Sergey, Ilya". pldi. 2021.

### osdi
- [EVMFuzz: Differential Fuzz Testing of Ethereum Virtual Machine](http://arxiv.org/abs/1903.08483). "Fu, Ying;Ren, Meng;Ma, Fuchen;Jiang, Yu;Shi, Heyuan;Sun, Jiaguang". osdi. 2021. [EVMFuzz].
- [Finding Consensus Bugs in Ethereum via Multi-transaction Differential Fuzzing](). "Yang, Youngseok". osdi. 2021.

### other
- [Finding The Greedy, Prodigal, and Suicidal Contracts at Scale](https://doi.org/10.1145/3274694.3274743). "Nikoli??, Ivica;Kolluri, Aashish;Sergey, Ilya;Saxena, Prateek;Hobor, Aquinas". acsac. 2018.
- [Online detection of effectively callback free objects with applications to smart contracts](https://doi.org/10.1145/3158136). "Grossman, Shelly;Abraham, Ittai;Golan-Gueta, Guy;Michalevsky, Yan;Rinetzky, Noam;Sagiv, Mooly;Zohar, Yoni". popl. 2018.
- [Osiris: Hunting for Integer Bugs in Ethereum Smart Contracts](https://doi.org/10.1145/3274694.3274737). "Torres, Christof Ferreira;Sch??tte, Julian;State, Radu". acsac. 2018. [Osiris].
- [Oracle-Supported Dynamic Exploit Generation for Smart Contracts](). "Wang, Haijun;Li, Y.;Lin, Shang-Wei;Artho, Cyrille;Ma, L.;Liu, Yang". tdsc. 2020.
- [A Multi-Modal Transformer-based Code Summarization Approach for Smart Contracts](http://arxiv.org/abs/2103.07164). "Yang, Zhen;Keung, Jacky;Yu, Xiao;Gu, Xiaodong;Wei, Zhengyuan;Ma, Xiaoxue;Zhang, Miao". icpc. 2021.
- [Peculiar: Smart Contract Vulnerability Detection Based on Crucial Data Flow Graph and Pre-training Techniques](). "Wu, Hongjun;Zhang, Zhuo;Wang, Shangwen;Lei, Yan;Lin, Bo;Qin, Yihao;Zhang, Haoyu;Mao, Xiaoguang". issre. 2021.


## Journals

### tifs
- [Hunting Vulnerable Smart Contracts via Graph Embedding Based Bytecode Matching](). "Huang, Jianjun;Han, Songming;You, Wei;Shi, Wenchang;Liang, Bin;Wu, Jingzheng;Wu, Yanjun". tifs. 2021.

### tse
- [Checking Smart Contracts with Structural Code Embedding](). "Gao, Zhipeng;Jiang, Lingxiao;Xia, Xin;Lo, David;Grundy, John". tse. 2020.
- [DEFECTCHECKER: Automated Smart Contract Defect Detection by Analyzing EVM Bytecode](http://arxiv.org/abs/2009.02663). "Chen, Jiachi;Xia, Xin;Lo, David;Grundy, John;Luo, Xiapu;Chen, Ting". tse. 2021. [DEFECTCHECKER].
- [SigRec: Automatic Recovery of Function Signatures in Smart Contracts](). "Chen, Ting;Li, Zihao;Luo, Xiapu;Wang, Xiaofeng;Wang, Ting;He, Zheyuan;Fang, Kezhao;Zhang, Yufei;Zhu, Hang;Li, Hongwei;Cheng, Yan;Zhang, Xiao-song". tse. 2021. [SigRec].


