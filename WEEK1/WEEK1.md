Lecture 1
====
环境设定:

使用VirtualBox + Vagrant．
+ 透过Vagrant设定好Spark之后，可以透过Jupyter Notebook来操作．

Tranditional Machine Learning(以下简称: Machine Learning) 与 Data Science的差异:
+ Machine Learning为了建立有效的Model而Data Science使用建立好的models来分析资料
+ Data Science的产出会是一个BI (Business Intellegence)而Machine Learning 产生是一个数据良好的模型．

Data Science 流程:
+ 取得资料
+ 整理资料 (ETL: Extract-Transform-Load)
+ 分析资料

Data Science实际上可能由于突变因子造成数据不可信任
+ 例子: 新闻与事件造成Google Search string 分析失误
+ 解决方式： 移除该因子所造成的髒资料(Dirty Data)，重新跑运算
