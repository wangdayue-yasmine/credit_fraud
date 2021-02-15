# 信用卡欺诈分析

数据集包括了 2013 年 9 月份两天时间内的信用卡交易数据，284807 笔交易中，一共有 492 笔是欺诈行为。输入数据一共包括了 28 个特征 V1，V2，……V28 对应的取值，以及交易时间 Time 和交易金额 Amount。


链接：https://pan.baidu.com/s/14F8WuX0ZJntdB_r1EC08HA 提取码：58gp


为了保护数据隐私，我们不知道 V1 到 V28 这些特征代表的具体含义，只知道这 28 个特征值是通过 PCA 变换得到的结果。另外字段 Class 代表该笔交易的分类，Class=0 为正常（非欺诈），Class=1 代表欺诈。


对比两个模型 LogisticRegressionClassifier VS LinearSVC


评估方式 f1score & precision_recall_curve & roc_curve
