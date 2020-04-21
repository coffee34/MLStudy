Sparkify 项目

我们使用的是音乐服务网站的数据集。数据集记录了用户的姓名，性别，歌曲艺术家，时长，
所处地区，访问页面，注册时间，歌曲名字，当前时间，使用浏览器等数据。我们将对这些数据
进行分析，寻找注销的用户和留存的用户的差别，并使用机器学习预测哪些用户容易流失。
博客地址：https://blog.csdn.net/chfcb930828/article/details/105665287

运行环境
Python3.7

PySpark 2.4.5

Jupyter notebook

依赖库
pandas

numpy

pyspark

matplotlib

seaborn

工程目录
Sparkify-zh.ipynb:ipynb格式文件，详细记录了数据集的处理，分析，特征工程和模型建立

Sparkify-zh.html:html格式文件，详细记录了数据集的处理，分析，特征工程和模型建立

分析流程
-数据探索

-定义客户流失

-建模

使用到的模型
-Logistic Regression

-Gradient Boosted Trees

-Random Forest

评价指标
F1 score：分数

结论
使用F1 score作为指标，得到使用逻辑回归模型比较好


最后，感谢大家查看我的项目，也欢迎提出质疑，谢谢！
