# 📚 生物医学 论文周报（知识解读版）

> **生成日期**: 2026-07-26  
> **收录论文数**: **26** 篇  
> **期号**: 第1期-年度回顾 / 第2期-每周执行  
> **领域**: 生物医学

> 本文档为「知识解读」版本：每篇论文在结构化结论之外，补充研究背景、核心思路、领域意义与局限启发，目标是帮你真正理解而非仅获知新闻。

---

## 🏆 Top 3 必读（精选推荐）

| 排名 | 论文 | 推荐理由 |
|------|------|----------|
| 1 | [Systematic discovery of CRISPR-boosted CAR T cell immunotherapies](https://www.nature.com/articles/s41586-025-09507-9) | CRISPR增强CAR-T的系统性发现 |
| 2 | [Why promising dementia treatments work in mice but fail in people](https://brainresilience.stanford.edu/news/why-promising-dementia-treatments-work-mice-fail-people) | 解释痴呆症治疗小鼠到人类的转化失败 |
| 3 | [AlphaFold 3: predicts structure and interactions of all life's molecules](https://www.isomorphiclabs.com/articles/alphafold-3-predicts-the-structure-and-interactions-of-all-of-lifes-molecules) | 生命分子结构与互作预测革命 |
| 4 | [Foundation-model-guided radiogenomic discovery linking cancer genomes to cancer scans](https://arxiv.org/abs/2607.20583) | 基础模型连接癌症基因组与影像表型，本周医学AI最亮点 |
| 5 | [HierarchicalDAEW: Domain-Aware Edge-Weighted Graph Convolution with Evidential Uncertainty for Multi-Section Spatial Gene Expression Prediction from H&E Histology](https://arxiv.org/abs/2607.20896) | 从H&E病理切片预测空间基因表达，本周病理AI亮点 |

## 📚 全部论文（按主题分类，含知识解读）

### 免疫疗法

#### [Systematic discovery of CRISPR-boosted CAR T cell immunotherapies](https://www.nature.com/articles/s41586-025-09507-9) ⭐

- **作者/机构**: 多机构合作 · **来源**: Nature/2025-09 · **推荐理由**: CRISPR增强CAR-T的系统性发现
- **一句话结论**: 发现并验证CRISPR增强的CAR-T细胞优于传统方案

**📖 知识解读**

**为什么值得关心**：CAR-T 是一种能治愈部分血癌的"活细胞药"，但贵、难做、细胞还容易"累垮"。能不能用基因编辑系统性地把它"增强"？

**先搞懂两个词**：①"CAR-T"=抽取病人免疫细胞(T细胞)，改造成能识别癌细胞的"特种兵"，再回输体内杀癌。②"CRISPR"=一种精准的"基因剪刀"，能改动细胞里的特定基因。

**这篇做了什么**：研究者用系统化的基因编辑筛选，发现并验证了若干"CRISPR 增强版 CAR-T"改造方案，效果优于传统，把"增强"变成可搜索的空间。

**意味着什么**：这是基因编辑与细胞疗法的系统性结合，从个案走向"可设计"，对实体瘤和通用型疗法都是关键一步。

**还差什么**：仍需临床验证安全与长期效果；编辑哪些靶点组合、会不会有脱靶和排斥反应，是必须盯紧的红线。

- 原文链接: [https://www.nature.com/articles/s41586-025-09507-9](https://www.nature.com/articles/s41586-025-09507-9)


#### [CAR-T基因编辑驱动即用型疗法新突破](https://lifescience.sinh.ac.cn/webadmin/upload/20250909134422_4010_6267.pdf)

- **作者/机构**: 学术合作 · **来源**: 2025-09
- **一句话结论**: 基因编辑驱动即用型(allogeneic)CAR-T疗法

**📖 知识解读**

**为什么值得关心**：现在的 CAR-T 大多用病人自己的细胞现做，慢、贵、质量还参差。能不能像普通药一样"现货供应"？

**先搞懂一个词**："异体/通用型(allogeneic)"——用健康供体的细胞批量生产，谁都能用，像输血一样；相对的是"自体"（只用你自己的）。

**这篇做了什么**：通过基因编辑敲掉会引发免疫排斥的靶点，让供体细胞不被病人免疫系统攻击，迈向"现货型"疗法。

**意味着什么**：若通用型 CAR-T 成熟，将像成药一样标准化生产，极大扩大可及性、降成本。

**还差什么**：临床数据仍有限，异体细胞的持久性和安全性是核心未知数。

- 原文链接: [https://lifescience.sinh.ac.cn/webadmin/upload/20250909134422_4010_6267.pdf](https://lifescience.sinh.ac.cn/webadmin/upload/20250909134422_4010_6267.pdf)


---

### 神经科学

#### [How to rewire a fruit fly brain](https://neuroscience.stanford.edu/news/how-rewire-fruit-fly-brain)

- **作者/机构**: Stanford Wu Tsai Neuro · **来源**: 2025-11
- **一句话结论**: 发现吸引/排斥分子如何构建神经回路

**📖 知识解读**

**为什么值得关心**：神经系统怎么"接线"决定了生物的行为。果蝇虽小，却是研究神经回路的经典模型。

**这篇做了什么**：斯坦福团队发现吸引/排斥类的分子如何引导神经正确连接，并演示了如何重编程果蝇脑的发育，从而改变其行为。

**意味着什么**：揭示了神经"接线规则"的可塑性，为理解发育、再生和神经疾病提供底层机制。

**还差什么**：果蝇回路相对简单，能不能推广到哺乳动物复杂大脑仍存疑；但机制层面很有启发。

- 原文链接: [https://neuroscience.stanford.edu/news/how-rewire-fruit-fly-brain](https://neuroscience.stanford.edu/news/how-rewire-fruit-fly-brain)


#### [A key protein may point toward new diagnostics and treatments for ALS and dementia](https://brainresilience.stanford.edu/news/qa-key-protein-may-point-toward-new-diagnostics-and-treatments-als-and-dementia)

- **作者/机构**: Stanford Knight Initiative · **来源**: 2025-11
- **一句话结论**: 发现ALS和FTD共同关键蛋白可能指向新诊疗

**📖 知识解读**

**为什么值得关心**：渐冻症(ALS)和额颞叶痴呆(FTD)常被当作两种病，但是否有共同的"病根"？

**这篇做了什么**：发现一种关键蛋白在 ALS 与 FTD 中共同出现异常，可能成为统一的生物标志物和治靶点。

**意味着什么**：若共同机制成立，一套诊疗思路可覆盖两种病，加速药物和早筛开发。

**还差什么**：从"发现相关蛋白"到"确认它是病因、能拿来下药"，还有距离。

- 原文链接: [https://brainresilience.stanford.edu/news/qa-key-protein-may-point-toward-new-diagnostics-and-treatments-als-and-dementia](https://brainresilience.stanford.edu/news/qa-key-protein-may-point-toward-new-diagnostics-and-treatments-als-and-dementia)


#### [A new ultrasound technique could help aging and injured brains](https://brainresilience.stanford.edu/news/new-ultrasound-technique-could-help-aging-and-injured-brains)

- **作者/机构**: Stanford Knight Initiative · **来源**: 2025-11
- **一句话结论**: 无药物无创方法清理大脑减少炎症

**📖 知识解读**

**为什么值得关心**：衰老和脑损伤常伴随慢性炎症、代谢废物堆积，传统药物很难无创地清理。

**这篇做了什么**：提出一种非药物、无创的超声方法，帮助清理脑内废物、减轻炎症，作为神经保护的新工具。

**意味着什么**：若无创"洗脑"可行，对延缓认知衰退、辅助脑损伤康复都有广阔前景。

**还差什么**：尚处早期，人体试验还没开始；超声参数、长期安全性是要回答的问题。

- 原文链接: [https://brainresilience.stanford.edu/news/new-ultrasound-technique-could-help-aging-and-injured-brains](https://brainresilience.stanford.edu/news/new-ultrasound-technique-could-help-aging-and-injured-brains)


#### [Music supercharges brain stimulation](https://neuroscience.stanford.edu/news/groove-brain-music-supercharges-brain-stimulation)

- **作者/机构**: Stanford Wu Tsai Neuro · **来源**: 2025-09
- **一句话结论**: 音乐节奏显著增强神经调控疗效

**📖 知识解读**

**为什么值得关心**：脑刺激（如经颅电刺激）对某些神经/精神症状有效，但怎么让它效果更好？

**这篇做了什么**：发现让被试跟着音乐节奏活动，能显著增强脑刺激的疗效，揭示"音乐+节律"与神经调控的协同效应。

**意味着什么**：把"愉悦的多感官体验"变成治疗增益因子，对抑郁、运动障碍等的非药物辅助疗法有启发。

**还差什么**：机制理解尚不完整，最优音乐和刺激参数怎么配，需系统研究。

- 原文链接: [https://neuroscience.stanford.edu/news/groove-brain-music-supercharges-brain-stimulation](https://neuroscience.stanford.edu/news/groove-brain-music-supercharges-brain-stimulation)


#### [Rethinking how we learn to move in the world](https://brainresilience.stanford.edu/news/rethinking-how-we-learn-move-world)

- **作者/机构**: Stanford Knight Initiative · **来源**: 2025-09
- **一句话结论**: 揭示大脑学习运动的精细机制可能改善帕金森治疗

**📖 知识解读**

**为什么值得关心**：我们怎么学会控制身体运动？其神经机制对帕金森等运动障碍的治疗至关重要。

**这篇做了什么**：揭示大脑学习运动的精细机制（不只是"发指令"，还包括误差校准与预测），为运动康复提供新靶点。

**意味着什么**：把"运动学习"机制讲清楚，可能改写神经康复训练的设计。

**还差什么**：离临床应用仍远，机制到人脑的映射需谨慎。

- 原文链接: [https://brainresilience.stanford.edu/news/rethinking-how-we-learn-move-world](https://brainresilience.stanford.edu/news/rethinking-how-we-learn-move-world)


#### [Myelin matters](https://neuroscience.stanford.edu/news/myelin-matters)

- **作者/机构**: Stanford Wu Tsai Neuro · **来源**: 2025-06
- **一句话结论**: 十年里程碑研究发现髓鞘影响几乎所有神经健康方面

**📖 知识解读**

**为什么值得关心**：髓鞘（神经外层的"绝缘皮"）长期被认为只是让信号传得快。它真的只干这一件事吗？

**先搞懂一个词**："髓鞘"——包裹在神经纤维外的脂质层，像电线外皮，绝缘并加速信号传导。

**这篇做了什么**：十年里程碑研究指出，髓鞘影响几乎神经健康的各个方面——从发育、可塑性到衰老与疾病。

**意味着什么**：提升对髓鞘在多种神经疾病中角色的全局认识，拓宽了干预靶点。

**还差什么**：偏综述性质，具体因果机制仍待厘清。

- 原文链接: [https://neuroscience.stanford.edu/news/myelin-matters](https://neuroscience.stanford.edu/news/myelin-matters)


#### [Locations of treats are stored in specialized neural maps](https://neuroscience.stanford.edu/news/locations-treats-are-stored-specialized-neural-maps)

- **作者/机构**: Stanford Wu Tsai Neuro · **来源**: 2025-06
- **一句话结论**: 小鼠创建区别于空间地图的奖励位置神经地图

**📖 知识解读**

**为什么值得关心**：大脑的海马体以"认知地图"著称（记住地点在哪），但它是否也记"奖励在哪"？

**这篇做了什么**：发现小鼠脑中存在区别于空间地图的"奖励位置神经地图"，揭示动机与空间记忆的专门化表征。

**意味着什么**：刷新对海马体功能的认识，把"价值地图"与"空间地图"分开，对决策与成瘾研究有启发。

**还差什么**：小鼠特定，是否适用于人类需进一步研究。

- 原文链接: [https://neuroscience.stanford.edu/news/locations-treats-are-stored-specialized-neural-maps](https://neuroscience.stanford.edu/news/locations-treats-are-stored-specialized-neural-maps)


#### [Non-invasive brain stimulation opens new ways to study and treat the brain](https://neuroscience.stanford.edu/news/non-invasive-brain-stimulation-opens-new-ways-study-and-treat-brain)

- **作者/机构**: Stanford Wu Tsai Neuro · **来源**: 2025-01
- **一句话结论**: 新一代无创脑调控工具用于研究和临床

**📖 知识解读**

**为什么值得关心**：传统深脑刺激要开颅，风险高。不开颅的脑调控能不能既用于研究又用于治疗？

**先搞懂一个词**："无创脑刺激"——从头皮外加磁场/电流来调节脑活动，不用手术。

**这篇做了什么**：综述新一代无创脑刺激工具，可在不开颅下研究和调节脑活动。

**意味着什么**：降低脑干预门槛，对抑郁、慢性疼痛、康复等的可及性意义重大。

**还差什么**：临床转化仍需时间，作用深度与精准性有限。

- 原文链接: [https://neuroscience.stanford.edu/news/non-invasive-brain-stimulation-opens-new-ways-study-and-treat-brain](https://neuroscience.stanford.edu/news/non-invasive-brain-stimulation-opens-new-ways-study-and-treat-brain)


---

### 阿尔茨海默

#### [Building bridges between Alzheimer's theories](https://brainresilience.stanford.edu/news/building-bridges-between-alzheimers-theories)

- **作者/机构**: Stanford Knight Initiative · **来源**: 2025-09
- **一句话结论**: 发现两大AD流行模型之间的联系可能改变治疗思路

**📖 知识解读**

**为什么值得关心**：阿尔茨海默病有两大主流解释——"淀粉样蛋白斑块"派和"突触/神经环路"派，长期各说各话。

**这篇做了什么**：发现两大理论之间的联系，提示它们可能并非互斥，而是同一病理过程的不同侧面。

**意味着什么**：统一框架能避免研究力量分散，重新指向"多靶点联合干预"的思路。

**还差什么**：属理论整合，需更多实证；但范式层面的桥梁很有价值。

- 原文链接: [https://brainresilience.stanford.edu/news/building-bridges-between-alzheimers-theories](https://brainresilience.stanford.edu/news/building-bridges-between-alzheimers-theories)


#### [Alzheimer's may stem from breakdown of recycling centers in aging cells](https://brainresilience.stanford.edu/news/alzheimers-may-stem-breakdown-recycling-centers-aging-cells)

- **作者/机构**: Stanford Knight Initiative · **来源**: 2025-08
- **一句话结论**: 衰老神经元溶酶体故障导致废物堆积引发AD

**📖 知识解读**

**为什么值得关心**：细胞靠"回收中心"清理代谢垃圾。衰老时回收失灵、垃圾堆积——这和阿尔茨海默有无因果？

**先搞懂一个词**："溶酶体"——细胞里的"回收站/清洁工"，负责分解废物。它出故障，垃圾就堆起来。

**这篇做了什么**：提出新机制：衰老神经元里溶酶体功能故障导致蛋白废物堆积，进而触发阿尔茨海默病理。

**意味着什么**：把阿尔茨海默与细胞"衰老-自噬"轴心相连，打开了"延缓衰老相关清理失灵"的干预思路。

**还差什么**：新模型可能不完全模拟人脑，需在人体组织中验证因果链。

- 原文链接: [https://brainresilience.stanford.edu/news/alzheimers-may-stem-breakdown-recycling-centers-aging-cells](https://brainresilience.stanford.edu/news/alzheimers-may-stem-breakdown-recycling-centers-aging-cells)


---

### 痴呆症

#### [Why promising dementia treatments work in mice but fail in people](https://brainresilience.stanford.edu/news/why-promising-dementia-treatments-work-mice-fail-people) ⭐

- **作者/机构**: Stanford Knight Initiative · **来源**: 2025-08 · **推荐理由**: 解释痴呆症治疗小鼠到人类的转化失败
- **一句话结论**: 发现小鼠研究测预防而人类试验测治疗导致转化失败

**📖 知识解读**

**为什么值得关心**：超过 400 种痴呆症疗法在小鼠身上有效、到人身上失败——这是整个领域的"转化之痛"。根因到底是什么？

**先搞懂背景**：动物实验多在"预防/早中期"测效果，而人类临床试验多在"已发病晚期"测。阶段和评判标准错位，导致看似矛盾的结果。

**这篇做了什么**：斯坦福指出这个根本性偏差：不是药无效，而是"在错误阶段、用错标准"测的。

**意味着什么**：直指转化失败的方法论根源，提示应更早介入、用更贴合的终点指标，可能重塑整个新药试验设计。

**还差什么**：结论可能略简化，但"阶段/终点错配"这个视角极具操作性，值得成为试验设计的默认检查项。

- 原文链接: [https://brainresilience.stanford.edu/news/why-promising-dementia-treatments-work-mice-fail-people](https://brainresilience.stanford.edu/news/why-promising-dementia-treatments-work-mice-fail-people)


---

### 帕金森

#### [Parkinson's comes in many forms. New biomarkers may explain why.](https://brainresilience.stanford.edu/news/parkinsons-comes-many-forms-new-biomarkers-may-explain-why)

- **作者/机构**: Stanford Knight Initiative · **来源**: 2025-08
- **一句话结论**: 血液/脑脊液标志物将帕金森患者分为亚组

**📖 知识解读**

**为什么值得关心**：帕金森常被当一种病，但病人病程和症状差别巨大。为什么？

**先搞懂一个词**："生物标志物"——血液中可检测、提示疾病状态的分子信号，像体检指标。

**这篇做了什么**：通过血液/脑脊液中的炎症与代谢标志物，把病人分成不同亚型，解释临床差异。

**意味着什么**：分型是精准医疗的前提——不同亚型可能对应不同疗法与预后，推动帕金森进入"分而治之"时代。

**还差什么**：需更大规模验证，且标志物和可干预靶点之间的衔接仍需工作。

- 原文链接: [https://brainresilience.stanford.edu/news/parkinsons-comes-many-forms-new-biomarkers-may-explain-why](https://brainresilience.stanford.edu/news/parkinsons-comes-many-forms-new-biomarkers-may-explain-why)


---

### 神经退行

#### [New consortium opens unexpected windows into neurodegenerative disease](https://brainresilience.stanford.edu/news/new-consortium-opens-unexpected-windows-neurodegenerative-disease)

- **作者/机构**: Stanford Knight Initiative · **来源**: 2025-07
- **一句话结论**: 大规模蛋白质组学数据揭示神经退行性疾病新线索

**📖 知识解读**

**为什么值得关心**：神经退行病机制复杂，单团队小样本难突破，需要大规模蛋白质数据协同。

**这篇做了什么**：新的全球联盟整合海量蛋白质组学数据，揭示此前未被注意的分子线索。

**意味着什么**：大数据+开放联盟的模式，可能像人类基因组计划一样加速机制发现。

**还差什么**：数据仍在初步分析，从"相关性"到"机制"还有长路。

- 原文链接: [https://brainresilience.stanford.edu/news/new-consortium-opens-unexpected-windows-neurodegenerative-disease](https://brainresilience.stanford.edu/news/new-consortium-opens-unexpected-windows-neurodegenerative-disease)


---

### 类器官

#### [A common food additive solves a sticky neuroscience problem](https://neuroscience.stanford.edu/news/common-food-additive-solves-sticky-neuroscience-problem)

- **作者/机构**: Stanford Wu Tsai Neuro · **来源**: 2025-07
- **一句话结论**: 常见食品添加剂使脑器官oid大规模培养成为可能

**📖 知识解读**

**为什么值得关心**：人脑类器官（微型人脑组织）培养时细胞爱结团、难规模化，限制了对人脑的研究。

**先搞懂一个词**："类器官"——在培养皿里用干细胞长出的、模拟真实器官的小组织，用于研究。

**这篇做了什么**：发现一种常见食品添加剂能解决结团问题，使脑类器官可大规模、均一化培养。

**意味着什么**：低成本突破让更多人能稳定培养人脑类器官，加速发育神经科学与药物测试。

**还差什么**：添加剂长期影响未知，类器官和真实脑的差距仍需警惕。

- 原文链接: [https://neuroscience.stanford.edu/news/common-food-additive-solves-sticky-neuroscience-problem](https://neuroscience.stanford.edu/news/common-food-additive-solves-sticky-neuroscience-problem)


---

### 记忆

#### [Two roads to memory](https://brainresilience.stanford.edu/news/two-roads-memory)

- **作者/机构**: Stanford Knight Initiative · **来源**: 2025-06
- **一句话结论**: 揭示AD和注意力如何共同塑造记忆能力

**📖 知识解读**

**为什么值得关心**：记忆怎么形成？阿尔茨海默又怎么破坏它？注意力在里面扮演什么角色？

**这篇做了什么**：揭示阿尔茨海默病理与注意力系统如何共同塑造记忆能力，提示记忆失败可能部分源于注意调控受损。

**意味着什么**：把"记忆"与"注意"在病理中联系起来，为早期干预提供新切入点。

**还差什么**：机制需更多验证，临床转化路径尚不明确。

- 原文链接: [https://brainresilience.stanford.edu/news/two-roads-memory](https://brainresilience.stanford.edu/news/two-roads-memory)


---

### 脑韧性

#### [Alzheimer's resilience signature predicts who will develop dementia](https://brainresilience.stanford.edu/news/alzheimers-resilience-signature-predicts-who-will-develop-dementia-and-how-fast)

- **作者/机构**: Stanford Knight Initiative · **来源**: 2025-05
- **一句话结论**: 脑脊液生物标志物可预测AD进展速度

**📖 知识解读**

**为什么值得关心**：同样有病理沉积，为何有人发病有人不发病？这种"韧性"能测量吗？

**先搞懂一个词**："韧性(resilience)"——这里指大脑即使有病理，也能维持功能不发病的能力。

**这篇做了什么**：用脑脊液生物标志物提炼出"韧性特征"，可预测谁会发展痴呆、以及进展多快。

**意味着什么**：从"有没有病理"转向"能不能扛住病理"，为风险分层与干预时机提供依据。

**还差什么**：需临床试验验证其预测效用与可干预性。

- 原文链接: [https://brainresilience.stanford.edu/news/alzheimers-resilience-signature-predicts-who-will-develop-dementia-and-how-fast](https://brainresilience.stanford.edu/news/alzheimers-resilience-signature-predicts-who-will-develop-dementia-and-how-fast)


---

### 脑机接口

#### [Groundbreaking robotic surgery 7000 miles away & Alzheimer's blood test](https://abcnews.com/Health/groundbreaking-robotic-surgery-alzheimers-blood-test-7-biggest/story?id=128654798)

- **作者/机构**: ABC News/医学界 · **来源**: 2025-12
- **一句话结论**: 2025年医学突破:远程机器人手术和首个AD血液诊断

**📖 知识解读**

**为什么值得关心**：2025 年医学有两件普通人该关注的突破：远程手术，和阿尔茨海默的血液检测。

**这篇做了什么**：一是医生在数千公里外远程操控机器人完成手术，突破地理限制；二是首个实用的阿尔茨海默血液检测，把诊断从昂贵影像/腰穿降到一次抽血。

**意味着什么**：远程手术扩大优质医疗资源覆盖；血液检测让早期筛查成为可能，是阿尔茨海默诊疗的范式转变。

**还差什么**：属新闻汇总而非论文，需看具体临床证据与监管批准；但方向清晰。

- 原文链接: [https://abcnews.com/Health/groundbreaking-robotic-surgery-alzheimers-blood-test-7-biggest/story?id=128654798](https://abcnews.com/Health/groundbreaking-robotic-surgery-alzheimers-blood-test-7-biggest/story?id=128654798)


#### [Enabling Rapid Calibration of BCI Systems that Detect Movement-Related Cortical Potentials in Children with Cerebral Palsy](https://arxiv.org/abs/2607.19417)

- **作者/机构**: R. Saadatyar, D. Damiano, A. Behboodi · **来源**: arXiv/2026-07
- **一句话结论**: 实现脑瘫儿童运动相关皮质电位BCI系统的快速校准。

**📖 知识解读**

**为什么值得关心**：脑机接口(BCI)能帮脑瘫儿童用意念控制外骨骼/轮椅，但传统校准要长时间配合，对孩子极不友好。

**先搞懂一个词**："BCI（脑机接口）"——在大脑和外部设备间建直连通道，让人用意念（脑电信号）控制机器。

**这篇做了什么**：提出面向儿童的快速校准方法，缩短 BCI 检测"运动相关脑电位"所需的训练时间，让系统更快可用。

**意味着什么**：把 BCI 从"实验室长校准"推向"临床可用的快部署"，对神经康复的公平性很有意义。

**还差什么**：样本量较小，跨个体泛化和长期稳定性需更大规模研究。

- 原文链接: [https://arxiv.org/abs/2607.19417](https://arxiv.org/abs/2607.19417)


---

### AI医疗

#### [AlphaFold 3: predicts structure and interactions of all life's molecules](https://www.isomorphiclabs.com/articles/alphafold-3-predicts-the-structure-and-interactions-of-all-of-lifes-molecules) ⭐

- **作者/机构**: Google DeepMind/Isomorphic Labs · **来源**: Nature/2024-05 · **推荐理由**: 生命分子结构与互作预测革命
- **一句话结论**: 预测所有生命分子结构及相互作用开启AI药物发现新纪元

**📖 知识解读**

**为什么值得关心**：知道蛋白质"长什么样、怎么互相结合"，是设计新药的基础。AlphaFold 3 在这上面迈出一大步。

**先搞懂背景**：AlphaFold 2 解决了"单个蛋白质长什么样"。但生命是蛋白质、核酸、小分子、离子互相作用的网络，单看一个蛋白不够。

**这篇做了什么**：AlphaFold 3 用一个统一模型，直接预测蛋白质与核酸、小分子、离子、抗原等的复合结构和相互作用——从"预测形状"升级到"预测怎么结合"，像预测两块拼图怎么咬合。

**意味着什么**：把结构生物学从"逐个解析"推进到"系统预测互作"，极大加速药物靶点发现和蛋白设计，被视为 AI for Science 的里程碑。

**还差什么**：对全新或不稳定复合物的精度仍有限，药物发现最终要靠实验室验证；它给的是假设，不替代实验。

- 原文链接: [https://www.isomorphiclabs.com/articles/alphafold-3-predicts-the-structure-and-interactions-of-all-of-lifes-molecules](https://www.isomorphiclabs.com/articles/alphafold-3-predicts-the-structure-and-interactions-of-all-of-lifes-molecules)


#### [AlphaFold is running out of data — drug firms are creating new AI tool](https://www.nature.com/articles/d41586-025-00868-9)

- **作者/机构**: Nature报道/Big Pharma · **来源**: Nature/2025-03
- **一句话结论**: 大药厂用锁定的3D蛋白质结构创建新AI工具

**📖 知识解读**

**为什么值得关心**：AlphaFold 用公开蛋白质结构训练，这类数据快被"用尽"了。药企想要更专、更准的预测，怎么办？

**这篇做了什么**：大药厂开始用自己锁定的 3D 蛋白质与结合数据训练专有 AI 工具，形成"数据壁垒 + 定制模型"的新模式。

**意味着什么**：标志结构预测从"公共模型普适"转向"企业私域数据驱动"，重塑制药 AI 的竞争壁垒。

**还差什么**：具体技术细节未公开，外部难评估；也引发"数据越来越集中在少数巨头"对开放科学的隐忧。

- 原文链接: [https://www.nature.com/articles/d41586-025-00868-9](https://www.nature.com/articles/d41586-025-00868-9)


#### [Foundation-model-guided radiogenomic discovery linking cancer genomes to cancer scans](https://arxiv.org/abs/2607.20583) ⭐

- **作者/机构**: F. Hauke, J. Krause, J.N. Kather 等 · **来源**: arXiv/2026-07 · **推荐理由**: 基础模型连接癌症基因组与影像表型，本周医学AI最亮点
- **一句话结论**: 用AI基础模型将癌症基因组分型与影像表型（放射基因组学）关联起来。

**📖 知识解读**

**为什么值得关心**：同一种癌，基因层面不同，影像表现也不同。能不能用 AI 把"基因分型"和"影像片子"连起来？

**先搞懂两个词**：①"放射组学"=从医学影像里提取大量量化特征。②"基因组学"=研究基因层面特征。两者结合叫放射基因组学。

**这篇做了什么**：用基础模型从病理/影像提取表示，与癌症基因组关联，发现"影像里能读出基因特征"的规律。

**意味着什么**：若影像能无损推测基因分型，精准医疗会更便宜（少做测序）、更早（一次扫描即提示），是 AI 桥接多组学的范例。

**还差什么**：需多中心临床验证，模型可解释性和泛化是落地前提。

- 原文链接: [https://arxiv.org/abs/2607.20583](https://arxiv.org/abs/2607.20583)


---

### AI药物设计

#### [Antigen-specific Antibody Multi-modal Foundation Model for Functional Antibody Design](https://arxiv.org/abs/2607.20057)

- **作者/机构**: X. Shi, Z. Wang, R. Ma 等 · **来源**: arXiv/2026-07
- **一句话结论**: 提出抗原特异性抗体的多模态基础模型，用于功能性抗体设计。

**📖 知识解读**

**为什么值得关心**：抗体药要找到"能精准结合某抗原且功能好"的序列，传统靠高通量实验试错，慢且贵。

**先搞懂一个词**："抗原"——能引发免疫反应的外来物（如病毒表面蛋白）；抗体是身体造来结合并清除它的"钥匙"。

**这篇做了什么**：构建"抗原条件化"的多模态抗体基础模型，把序列、结构、抗原信息联合建模，直接生成功能性抗体设计方案。

**意味着什么**：把生成式 AI 引入抗体工程，有望大幅压缩候选抗体发现周期，是 AI 制药的高价值方向。

**还差什么**：尚缺湿实验验证，设计出的抗体能否在真实生物体系里保持功能和安全，是关键关卡。

- 原文链接: [https://arxiv.org/abs/2607.20057](https://arxiv.org/abs/2607.20057)


---

### 单细胞组学

#### [Predictive single cell foundation model for gene regulation and aging with privacy-preserving tabular learning](https://arxiv.org/abs/2607.19400)

- **作者/机构**: J. Ding, J. Lin, Z. Miao 等 · **来源**: arXiv/2026-07
- **一句话结论**: 隐私保护表格学习驱动的单细胞基础模型，用于基因调控与衰老预测。

**📖 知识解读**

**为什么值得关心**：单细胞数据极敏感（能识别个人），又极有价值（揭示基因调控与衰老）。怎么在保护隐私下训练模型？

**先搞懂一个词**："隐私保护学习"——训练时原始数据不出本地/不被还原，模型只学到规律，像多人各自算完再汇总结果。

**这篇做了什么**：用隐私保护表格学习训练单细胞基础模型，在不上传原始数据的前提下，学到基因调控与衰老的预测表示。

**意味着什么**：示范了"隐私-效用"可兼顾，对医疗 AI 的合规落地（联邦/隐私学习）很有示范性。

**还差什么**：隐私与效用的权衡仍需优化，跨机构协作的激励与标准也待建立。

- 原文链接: [https://arxiv.org/abs/2607.19400](https://arxiv.org/abs/2607.19400)


---

### 病理AI

#### [HierarchicalDAEW: Domain-Aware Edge-Weighted Graph Convolution with Evidential Uncertainty for Multi-Section Spatial Gene Expression Prediction from H&E Histology](https://arxiv.org/abs/2607.20896) ⭐

- **作者/机构**: K. Chattopadhyay, S. Chatterjee, O. Krejcar 等 · **来源**: arXiv/2026-07 · **推荐理由**: 从H&E病理切片预测空间基因表达，本周病理AI亮点
- **一句话结论**: 用不确定性感知图卷积从H&E组织学切片预测多切片空间基因表达。

**📖 知识解读**

**为什么值得关心**：病理医生看 H&E 染色切片判断病情，但它不含"基因在空间上怎么表达"的信息。能否从普通切片"读出"空间基因表达？

**先搞懂两个词**：①"H&E 切片"=医院最常见的病理染色片，肉眼/镜下看组织形态。②"空间基因表达"=知道某个基因在组织里的具体位置表达量，信息更丰富但检测贵。

**这篇做了什么**：用"域感知 + 边加权图卷积"建模组织内细胞/区域的拓扑关系，并用"证据不确定性"给出可信预测，从多张 H&E 切片推断空间基因表达。

**意味着什么**：把"普通病理切片"升级为"带空间组学信息的决策依据"，无需昂贵原位测序就能获得空间基因表达，对精准病理和标志物发现价值大。

**还差什么**：模型复杂、计算量大；不确定性校准和跨医院泛化需严谨验证，避免"高置信的错误"。

- 原文链接: [https://arxiv.org/abs/2607.20896](https://arxiv.org/abs/2607.20896)


---
