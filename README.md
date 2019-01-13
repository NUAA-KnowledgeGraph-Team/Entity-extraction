# 实体识别方案

###编译环境:
1. Clone项目
2. 安装有SPARQL

直接调用JIEBA分词，我进行封装之后提供一个entityExtension.h文件，提供实体识别的一些函数

定义原型：
```
vector<wstring> Entity-extraction(DataBase &,wstring);
```

SPARQL有待学习，目前原型的DataBase类型暂未确定。