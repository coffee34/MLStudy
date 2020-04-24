Sparkify 流失用户预测

项目动机  
本项目是对音乐服务网站Sparkify的流失用户进行预测。如果能提前得知哪些用户即将流失，就能提前
有针对性地开展优惠或激励手段留住这些用户。

数据集  
本项目使用的是Sparkify的用户操作log。数据集记录了用户的姓名，性别，歌曲艺术家，时长，
所处地区，访问页面，注册时间，歌曲名字，当前时间，使用浏览器等数据。我们将对这些数据
进行分析，寻找注销的用户和留存的用户的差别，并使用机器学习预测哪些用户容易流失。

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
1数据清洗
2数据探索性分析
3特征值选定
4建模
5总结

使用到的模型  
-Logistic Regression

-Gradient Boosted Trees

-Random Forest

评价指标  
F1-score

结论  
最终选定maxDepth为10，numTrees为50的随机森林模型进行预测，
准确度为81.25%，F1- score为0.7836。
首要特征为用户平均每天访问次数，其次为注册天数。


最后，感谢大家查看我的项目，也欢迎提出改进的意见或建议，谢谢！
