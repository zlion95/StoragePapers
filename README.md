# 存储论文归档

## Key-Value 分离
1. HashKV: Enabling Efficient Updates in KV Storage via Hashing,  USENIX ATC'18
2. Flashield: a Hybrid Key-value Cache that Controls Flash Write Amplification, NSDI '19
3. WiscKey: Separating Keys from Values in SSD-conscious Storage, FAST '16

## 冷热数据识别
1. Efficient Identification of Hot Data for Flash Memory Storage Systems, ACM Transactions on Storage, Feb 2006

## 数据索引
1. The Case for Learned Index Structures, SIGMOD '18
2. SuRF: Practical Range Query Filtering with Fast Succinct Tries, SIGMOD 2018

## 降低写放大
1. The Log-Structured Merge-Bush & the Wacky Continuum, SIGMOD 2019


## 持久化内存（PM）
1. Revisiting the Design of LSM-tree Based OLTP Storage Engine with Persistent Memory, VLDB 2021

## 列存
1. Column-stores vs. row-stores: how different are they really, SIGMOD '08

## Pipeline && 向量化
1. MonetDB/X100: Hyper-Pipelining Query Execution
2. Efficiently Compiling Efficient Query Plans for Modern Hardware, VLDB 2011
    * 消除物化，减小cache和memory的交互，尽可能保存在cache中
