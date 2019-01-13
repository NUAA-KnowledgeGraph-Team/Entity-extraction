# 实体识别方案

使用python调用开源的结巴分词库对语句进行分词。将我们的数据库作为训练集，对分词得到的所有词汇进行贝叶斯概率估计，返回可能的与主题相关的实体。

C++调用Python，确保计算机内有python.h文件。
准备将文件封装为一个.h文件，

定义原型：
vector<wstring> Entity-extraction(DataBase &,wstring);
