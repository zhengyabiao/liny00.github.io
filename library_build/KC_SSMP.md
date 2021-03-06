---
layout: page
title: "KC-SSMP建库技术"
permalink: /library_build/KC_SSMP/
sidebar: true
medicine: true
---

## 背景介绍

液体活检是对肿瘤患者外周血中的cfDNA进行检测，从而判断患者体内是否有肿瘤基因突变的一种新型检测技术。肿瘤患者外周血中的cfDNA含有多种与肿瘤相关的突变基因，称之为ctDNA。ctDNA作为一种新的肿瘤标志物，在用药指导、疗效监测和复发监控等癌症诊疗过程中表现出很大的潜力。

目前，ctDNA检测的常规方法有ARMS-PCR，BEAMing和ddPCR等，但是这些方法存在检测敏感性不足或者检测位点过少等缺陷，导致在科研和临床上的使用受到了一定的限制。NGS技术能够一次性的对多个靶向基因和位点进行平行检测，可准确检出突变丰度在0.01-0.1%以上的突变，是一种检测ctDNA更为有效的方法。

---

## KC-SSMP技术

0.01%突变精准测出的保障。KC-SSMP技术主要是利用NGS对ctDNA进行检测的高精准度检测分析技术，通过高精准度靶向富集方案及分子标签DNA序列比对确认的信息分析纠错方法，可将测序背景误差下降了1000倍，有效实现超高测序深度（>10000X）下低频变检（检出限0.01%）的精准检出。下图为KC-SSMP技术原理图。

---

## KC-SSMP技术原理图
<img class="fig30" src="/image/library_build/SSMP/KC-SSMP建库原理.jpg">

---

## 技术优势

KC-SSMP技术同时具备CAPP-seq和多重PCR的技术优势，同时避开了上述两种技术的缺陷。其主要优势如下：

* 超高灵敏度。KC-SSMP的检测灵敏度下限为0.01%，达到与基于捕获的技术相同水平，这是第一项利用多重PCR原理达到该检测灵敏度的技术。
* 建库时间短。KC-SSMP基于多重PCR原理，避开了耗时的捕获步骤，整个文库构建可以在6h内完成，较CAPP-seq 2-3天的建库时间有了大幅度缩短。
* 流程简单。KC-SSMP的流程只有1步连接反应和2步PCR扩增反应，真正hands on的时间不超过2h，流程非常简单。
* 节约样本。由于是基于PCR的扩增技术，避开了损失很大的捕获步骤，因此KC-SSMP对模板起始量的要求很低，更利于检测珍贵的临床样本。

KC-SSMP与CAPP-seq和多重PCR的技术对比如下：

<img src="/image/library_build/SSMP/KC-SSMP-2.png">

---

## 建库质量

### 1.测序深度
<img  class="fig40" src="/image/library_build/SSMP/KC-SSMP-3.png">


上图为靶向外显子区域reads的平均覆盖度，当平均测序深度在7000X时，约50%的区域的测序深度在6000-8000X。

### 2.基因上靶率

<img  class="fig70" src="/image/library_build/SSMP/KC-SSMP-4.png">


<img  class="fig70" src="/image/library_build/SSMP/KC-SSMP-5.png">

上图为EGFR和TP53基因测序结果，利用不同起始量DNA建库，目标区域均上靶。

---

## 产品服务

### ctDNA检测服务

* 客户提供外周血/血浆和待检测的目标区域信息，公司据此设计多重PCR引物；
* 使用客户提供的样本，进行建库、测序和分析，返回客户原始的测序结果，并形成结题报告，鉴定客户样本中的基因变异；
* 本产品检测灵敏度0.01%，起始DNA量低至10ng。

### ctDNA定制服务

* 提供专利保护的建库试剂盒以及根据客户提供目的区域定制的多重PCR引物，客户可自行进行实验操作；
* 本试剂盒在Life/illumina平台均适用；
* 本产品检测灵敏度0.01%，起始DNA量低至10ng。
