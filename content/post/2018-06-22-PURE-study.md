---
title: 柳叶刀PURE研究
author: Hellen
date: '2018-06-22'
slug: PURE-Study
categories:
  - reading-notes
tags:
  - literature
---

## 什么是PURE

- The Prospective Urban Rural Epidemiology (PURE),前瞻性城乡流行病学研究。
纳入186790名35-70岁来自于5大洲、24个国家、639个社区、低中高收入国家的人口。
主要调查心血管疾病方面的死亡率和饮食之间的关系。
- 相关研究结果包括：

    Yusuf S, Rangarajan S, Teo K, et al. Cardiovascular risk and events in 17 low-, middle-, and high-income countries. N Engl J Med 2014; 371: 818–27.

    Yusuf S, Islam S, Chow CK, et al. Use of secondary prevention drugs for cardiovascular disease in the community in high-income, middle-income, and low-income countries (the PURE Study): a prospective epidemiological survey. Lancet 2011; 378: 1231–43.

    **Dehghan M, Mente A, Zhang X, et al. Associations of fats and carbohydrate intake with cardiovascular disease and mortality in 18 countries from five continents (PURE): a prospective cohort study. Lancet (London, England). 2017;390(10107):2050-62.**（本文涉及）

    **Miller V, Mente A, Dehghan M, et al. Fruit, vegetable, and legume intake, and cardiovascular disease and deaths in 18 countries (Prospective Urban Rural Epidemiology [PURE]): a prospective cohort study. Lancet 2017; published online Aug 29. http://dx.doi.org/10.1016/ S0140-6736(17)32253-5.**（本文涉及）

    Corsi DJ, Subramanian SV, Chow CK, et al. Prospective Urban Rural Epidemiology (PURE) study: baseline characteristics of the household sample and comparative analyses with national data in 17 countries. Am Heart J 2013; 166: 636–46.

---

## 碳水化合物和脂肪摄入量对死亡率和心血管疾病的影响

这是一个在医学界、营养学界、健康界、媒体中炸开了锅的研究。颠覆认知和指南。

### 背景

宏量营养素和心血管疾病及死亡率的关系仍有争议。大多数据来自于营养过剩的欧洲和南美人群，其他人群中的适用性并不清楚。

### 方法

从2003年到2013年，针对35岁到70岁的成年人，5大洲18个低中高收入国家，平均随访时间7.4年（IQR 5.3-9.3）。

标准问卷收集了人口学特征、社会经济地位（教育、收入、职业）、健康史、用药、活动量、糖尿病史等。记录CVD危险因素、结局时间。用食物频率问卷记录了135335人的baseline进食情况。其中143934人能量摄入数据可信（在500-5000kcal）并且没有年龄和性别数据缺失。1230人随访数据丢失，7369人已有心血管疾病，都被排除。剩下135335人被纳入。

主要终点是总死亡率和重大心血管事件（致死性心血管疾病、非致死性心梗、中风、心衰）。次要终点为所有的心梗、中风、心血管病死亡和非心血管病死亡。

根据不同营养物质(包括碳水化合物、脂肪、蛋白质)提供能量的占比，研究对象被分为5个等级(1为最少、5为最多)。以Q1作为对照，计算Q2、Q3、Q4、Q5的HR和P trend。衡量了碳水化合物、总脂肪、每种脂肪(饱和脂肪、不饱和脂肪)、总蛋白的摄入量和总死亡率、重大心血管事件、心梗、中风、心血管疾病死亡和非心血管疾病死亡的相关性。

用 **多因素Cox脆弱模型** 计算危险比HR。所有模型校正年龄和性别。

**敏感分析：**因为碳水化合物在亚洲人群中摄入最多，并且为了避免分得过细样本量小，所以分别在亚洲和非亚洲人群中分析看结论是否一致。

**替代分析：**碳水化合物来源的5%能量用饱和或不饱和脂肪酸替代分析采用multivariable nutrient density models（饱和脂肪酸、不饱和脂肪酸、蛋白质来源的能量占比被当做暴露因素，总能量作为协变量。该模型的系数就表示结果的改变。

统计用SAS，**样条曲线（spline curve）**用SAS LGTPHCURV9 Macro。

![FS1](http://47.96.102.241/images/2018-06-22-PURE-study/FS1.png)

### 结果

- 随访中，发生了5796死亡和4784重大心血管事件，2143心梗，2234中风，1649心血管死亡、3809非心血管死亡。描述结局、描述饮食在各地区各国的差异。
- 较高的碳水化合物摄入量，会增加总死亡率的风险，但和心血管病、心血管病死亡，没有相关性；
- 总脂肪及各种脂肪的摄入量，可能降低总死亡率的风险，但和心肌梗死、心血管病死亡，没有相关性；
- 高饱和脂肪的摄入量，可能降低中风的风险。
- 5%碳水化合物能量用多不饱和脂肪酸替代后总死亡率下降11%，而用饱和脂肪酸、单不饱和、蛋白质替代没有显著差异。用饱和脂肪酸替代后中风下降20%，用多不饱和脂肪酸替代后非心血管死亡下降16%。

### 解释

不支持目前的饮食指南：总脂肪酸<30%，饱和脂肪酸<10%。高碳水化合物摄食者可能从降低碳水化合物摄入增加脂肪摄入中获益。

### 亮点、技巧、不足解读

- 表1：观察性研究，描述特征，包括基本特征、社会经济情况、生活方式、疾病史、能量来源占比。一般是按照暴露因素分组，但本研究暴露因素太多了，所以按地区分组描述。

    性别和城乡占比表示方法，用二分类变量中的一个就可以提供两个变量的信息，如通过男性占比就能知道另一半就是女性占比。

    数据表示方法上，用n/N，就能知道本项目多少人数据缺失，也避免了加起来与总数不一致的尴尬。

![T1](http://47.96.102.241/images/2018-06-22-PURE-study/T1.png)

- 生存分析：COX frailty model（脆弱模型）

    经典的生存分析方法是COX比例风险模型，它的理论假设之一是样本之间相互独立。

    如果样本之间不独立，表现出组内相关的特性，经典的生存分析不再适合。如同一个个体反复发生某一事件，例如恶性肿瘤的反复复发，肾透析患者的反复感染；或者多中心试验、家族性疾病的生存资料，因为组内的个体生存时间具有相关性。

    frailty模型是在经典的生存分析的基础上加入了一个随机效应，以控制研究对象个体间或组别见存在的异质性。在SAS 9.3版本的PROC PHREG过程中加入了分析frailty模型的语句——Random语句。

    多变量COX脆弱模型适用于：多中心队列研究（以中心为随机效应）；多中心RCT（以中心为随机效应）；双眼生存数据（以ID为随机效应）；每个个体在随访期间出现多次结局（以ID为随机效应）。可以作为敏感性分析。

- 样条曲线：探索非线性剂量-反应关系图。找到转折点，而不是仅限于相关。

当碳水化合物占比超过60%时曲线上升。70%时HR置信区间下限>1.0。

![F1](http://47.96.102.241/images/2018-06-22-PURE-study/F1.png)

- 亚组分析（森林图）和趋势检验（p for trend）：

![F2](http://47.96.102.241/images/2018-06-22-PURE-study/F2.png)

- 替代分析：

![F3](http://47.96.102.241/images/2018-06-22-PURE-study/F3.png)

- 敏感性分析：分人群，校正不同混杂因素

- 作者总结的研究局限性有技巧

        1. FFQs调查食物摄入不够好 ———— 但是分分类足够了
        2. 只在基线测量食物摄入而食物摄入是会变的 ———— 但只会减弱关联
        3. social desirability bias，研究对象可能会偏向于回答健康的生活方式 ————如果真是这样，那就看不到这么多关联了，因此该影响不大
        4. 观察性队列研究的共同问题：虽然已经校正，但仍存在残余混杂 ———— 我们做了社会经济因素敏感性分析，没有改变结果
        5. 没有区分碳水化合物类型
        6. 没有测反式脂肪酸摄入

- 混杂因素校正：校正吸烟，未校正饮酒？校正糖尿病，未校正高血压高血脂？

    校正社会经济地位：家庭财富、收入、教育、国家经济。挨个校正后仍有相关，结果放在附录。为何不同时校正？为何不放主图而放在附录？可能是回避全校正后出现阴性结果？国家？收入水平？医保？

    可能混杂：穷地区死亡率高且买不起脂肪蛋白质而高碳水化合物。所以，经济水平是个可能混杂。

    哪些因素应该校正：

        1. 文献角度：同类研究中（同X同Y的），都调整的变量需要调整
        1. 临床经验角度：临床意义考虑，影响x和y关系的变量应该调整
        2. 常规调整：年龄、性别、种族、国家、地区......
        3. 统计分析角度：本研究中发现对效应值影响超多10%的因素（不能依据P值选择校正因素）

- 结果上：与总死亡率都相关，与重大心血管事件、心梗、中风、心血管死亡都不相关。说明这个总死亡率都是非心血管病死亡如癌症、感染等引起？

- 专业评价

    该研究将所有碳水化合物混合在一起分析不妥

    中国人群的数据不可靠：中国人群样本量占了三分之一，但调查地点不具有全国代表性，该研究中国人群42.2%为重体力劳动者，中学以上受教育程度只有14.4%

    没有正确反映中国的营养摄入现状，本研究中膳食数据与中国其他研究相差甚远

    未考虑睡眠习惯、饮酒、药物等影响

- 研究设计问题

    样本人群合并不当：经济发展水平和饮食习惯差异很大，把数据简单合并会引起生态谬误和混杂偏倚

    随访期较短：中位随访期7.4年（IQR 5.3-9.3），对营养学研究远远不够

    随访头两年发生结局时间的数据没有排除：可能导致因果倒置，如有些病人在头两年内没有发生终点事件但是在基线调查时已有疾病并且遵医嘱改变了饮食习惯

- 缺点小结

    校正混杂不够

    次要终点没有采用竞争分析模型：competing risk是指对研究对象出现感兴趣的事件的同时还会出现其他结局事件，这些结局事件将阻止感兴趣事件的发生或使其发生的概率降低，各结局事件间形成竞争关系。本研究中，中风和死亡形成竞争，心血管死亡和非心血管死亡形成竞争

    没有提及缺失值的处理

    交互作用分析不够

    剂量反应关系没有做阈值分析

---

## 水果、蔬菜、豆类食物摄入量对死亡率和心血管疾病的影响

本节内容[来源于网络](http://www.medsci.cn/article/show_article.do?id=2466121685fc)

### 背景

水果、蔬菜和豆类食物与心血管疾病、死亡的相关性已在欧洲、美国、日本和中国进行了广泛研究，但几乎没有来自中东、南美、非洲和南亚的数据资料。

### 方法

我们在18个低收入、中等收入和高收入国家中的613个社区年龄35-70岁、无心血管疾病的135335名个体中进行了一项前瞻性队列研究（“前瞻性城乡流行病学研究[PURE研究]”），这18个国家位于7个地理区域：北美和欧洲、南美、中东、南亚、中国、东南亚、非洲。我们采用特定国家食物频率调查问卷，在入组时记录了他们的饮食情况。采用标准化调查问卷收集人口因素、社会经济状况（教育、收入、受雇情况）、生活方式（吸烟、体育活动、饮酒情况）、健康病史和药物使用情况、心血管疾病家族史的信息。根据每个研究点或国家开始招募的日期随访期间不同。主要临床结果为严重心血管疾病（心血管原因引起的死亡、非致命性心肌梗死、脑卒中和心衰）、致命性和非致命性心肌梗死、致命性和非致命性脑卒中、心血管源性死亡率、非心血管源性死亡率以及总死亡率。采用随机效应的Cox脆弱模型评价水果、蔬菜和豆类食物消耗量与心血管疾病事件、死亡率的相关性。

### 结果

2003年1月1日至2013年3月31日进行参试者入组研究，对于现在的分析，我们纳入了PURE研究数据库中截止到2017年3月31日的所有确认的终点事件，总体上，水果、蔬菜和豆类食物平均摄入量为每天3.91份（SD 2.77）。在中位随访7.4年期间，记录到4784个严重心血管疾病事件、1649名心血管性死亡、5796名总死亡。在对年龄、性别、研究中心（随机效应）进行校正后的模型中发现，水果、蔬菜和豆类食物摄入总量越高，严重心血管疾病、心肌梗死、心血管源性死亡、非心血管源性死亡和总死亡越低，呈负相关。在对严重心血管疾病（风险比[HR]0.90，95%CI，0.74-1.10，趋势性P=0.1301）、心肌梗死（0.99，0.74–1.31，趋势性p=0.2033）、脑卒中（0.92，0.67–1.25，趋势性p=0.7092）、心血管源性死亡（0.73，0.53–1.02，趋势性p=0.0568）、非心血管源性死亡（0.84，0.68–1.04，趋势性p=0.0038）和总死亡（0.81，0.68–0.96，趋势性p<0.0001）的多变量校正后的模型中，这些估测值大幅衰减。与参照组相比，每日吃3-4份水果、蔬菜和豆类食物（0.78，95%CI，0.69–0.88）总死亡的风险比最低，再增加摄入量并没有进一步降低总死亡风险比。当分开来研究时发现，摄入水果可降低心血管源性死亡、非心血管源性死亡和总死亡率，而摄入豆类食物降低非心血管源性死亡和总死亡（在全校正模型中）。对于蔬菜，生吃蔬菜可明显降低总死亡率，而吃煮（炒）熟的蔬菜对降低死亡率仅轻微获益。

### 解释

水果、蔬菜和豆类食物消耗越多，非心血管源性死亡和总死亡的风险越低。每日3-4份（相当于每日375-500g）的消耗量可使非心血管源性死亡和总死亡风险降低获益最大。

