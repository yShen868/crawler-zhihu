# 知乎热榜分析系统

哈工大19年信息内容安全大实验-B类题目



### 环境

* 系统：Windows10 x64
* 语言：python3.7
* 数据库：MongoDB
* 若干库



### 功能

​		爬取即时热榜问题，以及问题下的若干回答，并进行简单的分析



### 运行

* 须在zhihu_hot.py中填入登录知乎后的cookie，否则无法正常运行
​		执行GUI.py



### 文件说明

*   GUI是用eric6写的，导出代码见ui目录下
*   情感分析用了lstm，是找隔壁猛男要的轮子，我也不知道写的啥；训练语料见lstm/train.txt
*   具体爬虫代码见zhihu_hot.py，代码很简单，没写注释



---

实验最后得分：96.0
