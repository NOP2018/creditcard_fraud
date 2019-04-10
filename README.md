# 使用逻辑回归对信用卡欺诈进行分类
数据来自[Kaggle数据集](https://www.kaggle.com/jacklizhi/creditcard) 。

对不平衡的数据使用过采样方法，使用的是 imblearn 库包中的 SMOTE 生成新的平衡数据。

使用逻辑回归进行分类，并计算精确率、召回率、F1得分，召回率可达0.913.
