---
title: 如何以 SRE 角度改善既有系統
description: "July 20, 2019"
layout: default_zh
---

![cover](Integrating-EKS-with-API-Gateway-and-Performance-Tuning/cover.png)

要改善既有系統（Legacy System）一直以來都不是一件容易的事情，尤其是當面臨要改動整體架構時，需要耗費的時間和人力成本往往讓老闆無法輕易買單。因此，如何評估既有系統並明確指出為什麼要進行改善，以及新的系統架構要如何設計才能面對更大的挑戰，是非常重要的。本篇文章將以 [SRE 課程](https://www.coursera.org/learn/site-reliability-engineering-slos/) 中的評估方法作為主軸進行系統評估，結合 [從零開始學架構](https://www.tenlong.com.tw/products/9787121347917) 和 [大規模數據處理實戰](https://time.geekbang.org/column/intro/167) 兩本書中的知識，總結出一套通用且不會過於複雜的系統改善技巧。

## 摘要

* 學習案例
* 系統評估方法
    - 標示出現有系統的數據流，工作流
    - 標示批處理，流處理
    - 標示 SLI Menu，Request / Response or Data Processing or Data Store
* 系統改善設計
