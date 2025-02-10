+++
date = '2025-02-06T16:54:05+08:00'
draft = false
title = 'OrgSyn004'
author = 'Argon'
+++

本篇策略为通过阴离子重排制备 N-Boc-吡咯。原文：*Org. Synth.*  **2023** ,  *100* , 61-83.

<!--more-->

## 简述

![004-1](https://img.z4a.net/images/2025/02/10/004-1.png)

**步骤A**是利用 N-Boc-羟胺在 PIDA （二乙酸碘苯，有机碘氧化剂）氧化下和异戊二烯（isoprene）发生 [4+2] 环加成反应，生成两种产物的混合物**2**，尽管反应区域选择性较差，但并不影响下一步的合成。

**步骤B**用 LDA/t-BuOK 的组合在乙醚中处理混合物**2**，发生阴离子重排得到3-甲基吡咯。

## 讨论

吡咯环在许多天然产物，聚合物，染料等分子中都广泛出现[^1]，同时具有良好的反应性，能够参与许多的碳碳键偶联反应，因此有着巨大的研究价值。

Komine, Wood 等人在研究天然产物 longeracemine 的合成过程中[^2]，发现 N-Boc-3-甲基吡咯（下图化合物**3**）是一个有潜力的底物，但是其商业售价又太贵（$800/g），因此开始探索该化合物的合成。

![004-2](https://img.z4a.net/images/2025/02/10/004-2.png)

作者发现以往的文献虽然有报导该化合物的合成，但是存在种种不足。如 Castagnolo 和合作者曾报导过利用烯-炔复分解/环化串联的一步合成法制备化合物**3**[^3]，但是反应需要用到高用量的 Grubbs 2nd 催化剂（$549/2g），价格仍然十分高昂。

Lash 等人也报导过化合物**3**的合成方法[^4]，但是需要4步才能完成合成，步骤繁复。

综合考虑价格和合成步骤后，作者对 Kouklovsky 等人的方法产生了兴趣，准备在其基础上加以改进。Kouklovsky 等人的策略如下[^5]：

![004-3](https://img.z4a.net/images/2025/02/10/004-3.png)

Kouklovsky 等人的方法可以概括为亚硝基[4+2]环加成-还原开环-氧化关环三步，作者对其进行了优化。

首先，作者发现，在第一步中，使用 PIDA 作为氧化剂的效果比其他常见氧化剂（如高碘酸钠）效果更好。

其次，为了避免使用高毒性的六羰基合钼，作者尝试了别的试剂来还原N-O键，作者尝试了 SmI2 等试剂，但产率不佳。最终发现可以直接用强碱配合还原剂（如 LAH）来实现还原。

![004-4](https://img.z4a.net/images/2025/02/10/004-4.png)

有趣的是，当使用乙醚作为溶剂时，产物中出现了痕量的化合物**3**，作者推测有可能在该条件下，中间体直接发生了阴离子亲核取代关环，最后在后处理时芳构化。根据这一思路，作者除去了还原剂和氧化剂，重新探索了碱条件，最终发现 LDA/t-BuOK 的组合（LIDAKOR reagent）在乙醚中可以直接以良好产率得到化合物**3**，因此得到了开头所示的策略。

这种合成方法价格低廉且无需使用高毒试剂，有着很好的应用前景。

## 参考

[^1]: (a) Singh, N.; Singh, S.; Kohli, S.; Singh, A.; Asiki, H.; Rathee, G.; Chandra, R.; Anderson, E. A. Recent Progress in the Total Synthesis of Pyrrole-containing Natural Products (2011-2020). Org. Chem. Front. 2021, 8, 5550-5573 (doi.org/10.1039/D0QO01574A). (b) Bakhanovich, O.; Khutorianskyi, V.; Motornov, V.; Beier, P. Synthesis of N-Perfuoroalkyl-3,4-disubstituted Pyrroles by Rhodium-catalyzed Transannulation of N-Fluoroalkyl-1,2,3-triazoles with Terminal Alkynes. Beilstein J. Org. Chem. 2021, 17, 504-510 (doi.org/10.3762/bjoc.17.44).
    
[^2]: Komine, K.; Lambert, K. M.; Savage, Q. R.; Cox, J. B.; Wood, J. L. Synthetic Studies toward Longeracemine: a SmI2-Mediated Spirocyclization and Rearrangement Cascade to Construct the 2-Azabicyclo[2.2.1]heptane Framework. Chem. Sci. 2020, 11, 9488-9493 (doi.org/10.1039/DOSC03422C).
    
[^3]: Chachignon, H.; Scalacci, N.; Petricci, E.; Castagnolo, D. Synthesis of 1,2,3-Substituted Pyrroles from Propargylamines via a One-Pot Tandem Enyne Cross Metathesis-Cyclization Reaction. J. Org. Chem. 2015, 80, 5287-5295 (doi.org/10.1021/acs.joc.5b00222).
    
[^4]: Lash, T. D.; Hoehner, M. C. An Improved Synthesis of Pyrroles from N-p-Toluenesulfonylglycine Esters and α,β-Unsaturated Aldehydes and Ketones. J. Heterocycl. Chem. 1991, 28, 1671-1676 (doi.org/10.1002/jhet.5570280705).
    
[^5]: Calvet, G.; Blanchard, N.; Kouklovsky, C. Synthesis of Polysubstituted Pyrroles via Dihydro-1,2-oxazines. Synthesis 2005, 3346-3354 (doi.org/10.1055/s-2006-931969).
