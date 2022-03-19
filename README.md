# WhetherTheIncomeGreaterThan50K
# 薪资是否大于5万美元预测
# 一、项目背景
员工在一个企业中扮演着极其重要的角色，员工与企业之间构成的聘用与被聘用关系是建立在双方在各自的立场上达成一致的前提下形成的，而企业给予员工发放的薪水应当保持在合理的范围内，过高或者过低的薪资都会造成公平的失衡。不同人的各项基本信息，例如年龄、工作类别等等都有可能直接或间接的影响到其薪资水平，而分析这些基本信息与薪水高低之间的关系是一个非常有创新性且值得探究的问题，因此，在本次大作业中就是要使用Kaggle网站提供的数据集，借助机器学习的各种的算法在各项基本信息与薪资时候大于5万美元之间建立模型，从而比较不同模型间的表现水平、使用范围，以及对样本数据中隐含的特征进行探究和分析。
# 二、数据集说明
本次实验中使用到的数据集来源于在数据科学业内享有盛名的数据科学竞赛平台Kaggle中的一个数据集Income Dataset，该数据集是Mustafa Fatakdawala在一年前上传的最新版。该数据集提供了诸如教育、就业状况、婚姻状况等预测特征，以预测工资是否大于 5 万美元。该数据集包含训练集train.csv和测试集test.csv，其中训练集共包含43958行，15列特征信息（包括标签列income_>50k），测试集共包含899行，14列特征信息（不包括标签列），以下表格对不同字段进行了解释。

|属性	|含义	|类型|
|:---|:---|:---|
age	|年龄	|Int
workclass	|工作类别|	Object
fnlwgt	|最终分析权重|	Int
education	|受教育程度|	Object
educational-num	|受教育时间|	Int
marital-status|	婚姻状况|	Object
occupation|	职业	|Object
relationship	|社会角色|	Object
race	|种族	|Object
gender|	性别	|Object
capital-gain|	资本收益|	Int
capital-loss	|资本支出	|Int
hours-per-week	|每周工作时间|	Int
native-country|	国籍	|Object
income_>50K	|薪水是否大于5万美元|	Int
# 三、实验目的
使用Python数据分析的相关技术和机器学习的相关算法，针对Kaggle中的一个数据集Income Dataset，从不同角度分析员工的各种特征以及对是否薪水是否大于5万美元的影响，并且根据这些特征使用决策树、随机森林、逻辑回归、支持向量机、朴素贝叶斯、XGBoost、KMeans聚类、LightGBM、神经网络等算法进行建模，并针对随机森林、逻辑回归、朴素贝叶斯算法使用Boosting以及排序平均法进行模型融合，并对比不同模型的表现效果，从而对测试集中的样本数据的薪水是否大于5万美元进行预测。
# 四、实验环境
操作系统：Windows 10

编译器：Jupyter Notebook 6.3.0

Python：3.8.8

CPU：intell 11st i7

显卡：NVIDIA GeForce RTX 3070

其他模块：sklearn、scipy、numpy、missingno、random、warnings、operator、pandas、seaborn等
# 五、实验流程设计
该实验的具体的流程设计如以下思维导图所示：
![image](https://user-images.githubusercontent.com/68093996/159116454-e0886a63-3782-4e34-a484-b7f91c71b32a.png)
