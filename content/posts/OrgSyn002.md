+++
date = '2025-02-04T16:55:51+08:00'
draft = false
title = 'OrgSyn002'
author = 'Argon'
+++

本篇策略为钯催化下连烯的 Pauson-Khand 反应。原文：*Org. Synth.*  **2023** ,  *100* , 29-47.

<!--more-->

## 简述

![002-1](https://ooo.0x0.ooo/2025/02/04/OGL97S.png)

连烯的分子内 Pauson-Khand 反应（allenic Pauson-Khand reaction, 简称为APKR）从1985年被报导以来发展了不少新的催化策略，今天这篇文章则是介绍了连烯在Rh(Ⅰ)的催化下借助 APKR 完成[5,7]-并环体系的构建[^1]，以及 APKR 反应的发展和应用。

**步骤A**用碳酸钾作碱夺取胺上活泼氢，然后以氮负离子作亲核试剂亲核取代炔基溴化物的溴原子，在体系中引入氮原子。接着在酸性条件下（TFA）脱除Boc基的保护。

**步骤B**先用NaH夺胺的活泼氢，然后与加入的连烯化合物发生亲核取代连接起来。

**步骤C**则是本文重点，即 APKR，同时，用Rh(Ⅰ)催化剂控制双键的反应性以生成七元环。下文的讨论中将详细分析该反应的细节。

## 讨论

### 不对称 APKR

Burrows 等人通过实验和理论共同验证了外消旋的连烯底物可以在手性Rh(Ⅰ)催化剂存在下发生 APKR，并以79%产率和82:18的er（enantiomeric ratio）值获得产物[^2]。

![002-2](https://ooo.0x0.ooo/2025/02/04/OGL8zL.png)

计算结果表明催化过程包含一个动态动力学不对称转化（DyKAT）过程，这意味着底物需要能够实现快速外消旋化，图中表示二者能差为4.4kcal/mol，即18.42kJ/mol，作为参考，乙烷的C-C键旋转能垒稍小于14kJ/mol[^3]，可见其能差之小。

Deihl 与 Brummond 进一步扩展了该方法，他们将不对称 APKR 应用到连有呋喃的连烯化合物上，并以此构建了天然产物 thapsigargin 的核心骨架[^4]。

![002-3](https://ooo.0x0.ooo/2025/02/04/OGEOOp.png)

有趣的是，酯基的R1基团为Cl时，反应获得了很好的ee值，其他基团则都表现平平。同时，炔基的R2基团如果为苯基则有良好对映选择性，如果只是普通端炔，ee值掉落至54%。DFT计算表明呋喃环和磷酸酰胺配体之间存在π-π相互作用，可以降低过渡态能量，而不合适的配体会缺乏这种π-π相互作用，从而使对映选择性下降。

### 连烯化合物在 APKR 中的轴手性转换

Grillet 和 Brummond 探索了连烯化合物在发生 APKR 时轴手性转换的机制[^5]。

![002-4](https://ooo.0x0.ooo/2025/02/04/OGEaNU.png)

上图中**A**和**B**展示了不同取代的连烯化合物轴手性转化的程度，**C**则说明了产生这种转化的原因，分子内的杂原子可能会对Rh(Ⅰ)络合物发生分子内亲核进攻，形成的金属络合物绕轴旋转导致了手性变化。

### Rh(Ⅰ)催化 APKR 的选择性、机理和优化

Rh和Mo配合物是分子内 APKR 最常见的过渡金属催化剂选择，但是不同的金属也会导致不同的反应结果，如下例[^6]：

![002-5](https://ooo.0x0.ooo/2025/02/04/OGEoLY.png)

DFT计算表明，氧化环化过渡态（OxCycl TS）中的金属几何构型是关键要素[^7]。

![002-6](https://ooo.0x0.ooo/2025/02/04/OGEquv.png)

在不对称Rh(Ⅰ)催化的 APKR 中，氧化环化过程控制立体构型，但不是决速步骤（如上图**B**）。

对反应条件进行实验优化，发现当Rh(Ⅰ)配合物浓度在1mol%时产率较高，使用该条件进行了6g级别的合成测试，得到88%收率[^8]。

![002-7](https://ooo.0x0.ooo/2025/02/04/OGEBFq.png)

### APKR 在天然产物合成中的应用

Jackson 和 Brummond 等人利用 APKR 合成了多种 guaianolide 的同系物，并且具有可调节活性的硫醇基团，以调控其生物活性[^9]。

![002-8](https://ooo.0x0.ooo/2025/02/04/OGETPc.png)

Yang 课题组使用烯基连烯底物在Rh(Ⅰ)催化下构建三环骨架，被用于 perforanoid A 的全合成中[^10]。

![002-9](https://ooo.0x0.ooo/2025/02/04/OGEU9r.png)

Li 课题组运用 APKR 构建了5,7,6,5-四元环骨架，被用于 bufospirostenin A 的全合成中[^11]。

![002-10](https://ooo.0x0.ooo/2025/02/04/OGEbUM.png)

总之，APKR 在有机合成中发挥着重要作用，在各种催化剂中，Rh配合物又是最重要，最有潜力的一种，该反应也将在未来的合成工作中继续发挥作用。

## 参考

[^1]: Mukai, C.; Nomura, I.; Yamanishi, K.; Hanaoka, M. Rh(I)-catalyzed intramolecular allenic Pauson−Khand reaction:  construction of a bicyclo[5.3.0]dec-1,7-dien-9-one skeleton. Org. Lett. 2002, 4, 1755-1758. doi.org/10.1021/ol020051w
    
[^2]: Burrows, L. C.; Jesikiewicz, L. T.; Lu, G.; Geib, S. J.; Liu, P.; Brummond, K. M. Computationally guided catalyst design in the Type I dynamic kinetic asymmetric Pauson-Khand reaction of allenyl acetates. J. Am. Chem. Soc. 2017, 139, 15022-15032. doi.org/10.1021/jacs.7b07121
    
[^3]: Zhang Qi-Yuan; Yan Ji-Min. Ab initio Calculation and Energy Partition of the Potential Barrier to Internal Rotation in Ethane[J]. Acta Phys. -Chim. Sin. 1991, 7(03), 337-341. doi: 10.3866/PKU.WHXB19910315
    
[^4]: Deihl, E. D.; Jesikiewicz, L. T.; Newman, L. J.; Liu, P.; Brummond, K. M., Rh(I)-catalyzed allenic Pauson-Khand reaction to access the thapsigargin core: Influence of furan and allenyl chloroacetate groups on enantioselectivity. Org. Lett. 2022, 24, 995-999. doi.org/10.1021/acs.orglett.1c03951
    
[^5]: Grillet, F.; Brummond, K. M. Enantioselective synthesis of 5,7-bicyclic ring systems from axially chiral allenes using a Rh(I)-catalyzed cyclocarbonylation reaction. J. Org. Chem. 2013, 78, 3737-3754. doi.org/10.1021/jo4002432
    
[^6]: (a) Brummond, K.M.; Rickards, B.; Sill, P.C.; Geib, S.J. A silicon-tethered allenic Pauson-Khand reaction. Tetrahedron Lett. 2002, 43, 3735-3738. doi.org/10.1016/S0040-4039(02)00633-0; (b) Brummond, K. M.; Chen, H.; Fisher, K. D.; Kerekes, A. D.; Rickards, B.; Sill, P. C; Geib, S.J . An allenic Pauson−Khand-type reaction:  A reversal in π-bond selectivity and the formation of seven-membered rings. Org. Lett. 2002, 4, 1931-1934. doi.org/10.1021/ol025955w
    
[^7]: Bayden, A. S.; Brummond, K. M.; Jordan, K. D. Computational insight concerning catalytic decision points of the transition metal catalyzed [2 + 2 + 1] cyclocarbonylation reaction of allenes. Organometallics 2006, 25, 5204-5206. doi.org/10.1021/om0607503
    
[^8]: Burchick. Jr., J. E.; Wells, S. M.; Brummond, K. M. Rh(I)-Catalyzed Allenic Pauson-Khand Reaction. Org. Synth. 2017, 94, 123-135. doi: 10.15227/orgsyn.094.0123
    
[^9]: Jackson, P. A.; Schares, H. A. M.; Jones, K. F. M.; Widen, J. F.; Dempe, D. P.; Cuellar, M. E.; Walters, M. A.; Harki, D. A.; Brummond, K. M. Synthesis of guaianolide analogues with a tunable α-methylene-γ-lactam electrophile and correlating bioactivity with thiol reactivity. J. Med. Chem. 2020, 63, 14951-14978. doi.org/10.1021/acs.jmedchem.0c01464
    
[^10]: Lv, C.; Tu, Q.; Gong, J.; Hao, X.; Yang, Z. Asymmetric total synthesis of (−)-perforanoid A. Tetrahedron 2017, 73, 3612-3621. doi.org/10.1016/j.tet.2017.03.072; Lv, C.; Yan, X.; Tu, Q.; Di, Y.; Yuan, C.; Fang, X.; Ben-David, Y.; Xia, L.; Gong, J.; Shen, Y.; Yang, Z.; Hao, X. Isolation and asymmetric total synthesis of perforanoid A. Angew. Chem., Int. Ed. 2016, 55, 7539-7543. doi.org/10.1002/anie.201602783
    
[^11]: Cheng, M.-J.; Zhong, L.-P.; Gu, C.-C.; Zhu, X.-J.; Chen, B.; Liu, J.-S.; Wang, L.; Ye, W.-C.; Li, C.-C. Asymmetric total synthesis of bufospirostenin A. J. Am. Chem. Soc. 2020, 142, 12602-12607. doi.org/10.1021/jacs.0c05479
