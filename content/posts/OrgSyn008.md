+++
date = '2025-02-12T10:11:57+08:00'
draft = false
title = 'OrgSyn008'
author = 'Argon'
+++

本篇策略为通过亲电活化实现的酰胺α-氧化。原文：*Org. Synth.*  **2023** ,  *100* , 136-158.

<!--more-->

## 简述

![008-1](https://img.z4a.net/images/2025/02/12/008-1.png)

步骤**A**较为基础，将酰氯转化为酰胺以便继续反应。

步骤**B**则是该策略的核心反应，利用 Tf2O 活化酰胺，并用 TEMPO 氧化，得到α-TMPO-酰胺化合物**2**。作者推测该步骤的机理是 Tf2O 活化酰胺，后通过自由基机理完成α位取代。

化合物**2**可以通过不同的条件选择性氧化，如步骤**C**和**D**，如果使用氧化剂（如单过氧邻苯二甲酸镁，MMPP）则得α-酮酰胺；如果使用还原剂（如 Zn 粉）则得α-羟基酰胺。

## 讨论

选择性氧化在有机合成中是非常有价值的反应，酰胺的α-氧化近年来又尤其受关注[^1]，不管是α-酮酰胺还是α-羟基酰胺都对有机合成方法的发展起重要作用。

然而，能够直接得到α-酮酰胺的合成策略不仅稀少，而且对底物有要求[^2]，这显著限制了从酰胺开始转化的合成流程。

一般来说，酰胺活化的常规做法是使用三氟甲磺酸酐（Tf2O），然后进行环加成或者亲核加成等反应[^3]。活化产生的 enolonium 物种还可能在酰胺α位发生极性反转反应[^4]，如下例：

![008-2](https://img.z4a.net/images/2025/02/12/008-2.png)

作者团队研发了酰胺的α位氧化方法[^5]，使用 TEMPO 作氧化剂并结合 Tf2O 活化酰胺得到 α-TMPO-酰胺产物（如下图方案**A**），该产物可以配合不同条件得到所需产物。

如下图方案**B**，如果直接还原，那么TMPO基团被还原为羟基，则得α-羟基酰胺，此时四甲基哌啶（TMP）可以当成是保护基；如果氧化，则得α-酮酰胺。

![008-3](https://img.z4a.net/images/2025/02/12/008-3.png)

据此，我们就能做到选择性的氧化酰胺α位，根据我们的需要获得不同的氧化产物。该反应对底物的兼容性也毕竟良好，具有广泛的应用前景。

## 参考

[^1]: (a) De Risi, C.; Pollini, G. P.; Zanirato, V. Recent Developments in General Methodologies for the Synthesis of α-Ketoamides. Chem. Rev. 2016, 116, 3241−3305; (b) Kumar, D.; Vemula, S. R.; Cook, G. R. Recent Advances in the Catalytic Synthesis of α-Ketoamides. ACS Catal. 2016, 6, 4920−4945; (c) Du, Y.; Yu, A.; Jia, J.; Zhang, Y.; Meng, X. Direct N-H/α,α,β,β-C(sp3)-H functionalization of piperidine via an azomethine ylide route: synthesis of spirooxindoles bearing 3-substituted oxindoles. Chem. Commun. 2017, 53, 1684−1687.
    
[^2]: (a) Song, B.; Wang, S.; Sun, C.; Deng, H.; Xu, B. Cesium carbonate promoted aerobic oxidation of arylacetamides: an efficient access to N-substituted α-keto amides. Tetrahedron Lett. 2007, 48, 8982−8986; (b) Shao, J.; Huang, X.; Wang, S.; Liu, B.; Xu, B. A straightforward synthesis of N-monosubstituted α-keto amides via aerobic benzylic oxidation of amides. Tetrahedron 2012, 68, 573−579.
    
[^3]: Kaiser, D.; Bauer, A.; Lemmerer, M.; Maulide, N. Amide activation: an emerging tool for chemoselective synthesis. Chem. Soc. Rev. 2018, 47, 7899-7925.
    
[^4]: Chen, X.; Ruider, S. A.; Hartmann, R. W.; González, L.; Maulide, N. Metal-Free meta-Selective Alkyne Oxyarylation with Pyridine N-Oxides: Rapid Assembly of Metyrapone Analogues. Angew. Chem. Int. Ed. 2016, 55, 15424−15428.
    
[^5]: de la Torre, A.; Kaiser, D.; Maulide, N. Flexible and Chemoselective Oxidation of Amides to α-Keto Amides and α-Hydroxy Amides. J. Am. Chem. Soc. 2017, 139, 6578−6581.
