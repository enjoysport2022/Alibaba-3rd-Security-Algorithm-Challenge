# 第三届阿里云安全算法挑战赛冠军代码
## 比赛链接：https://tianchi.aliyun.com/competition/introduction.htm?spm=5176.100066.0.0.6acd33afwZ9hM7&raceId=231668

## ppt: 上地西二旗人民.pptx

## 代码按照以下运行顺序
* main_train.ipynb:生成train数据集特征
* main_test.ipynb:生成test数据集特征
* gene_npy.ipynb:将特征数据转换为npy文件
* lgb_meta_features.ipynb:生成lgb元特征
* CNN_metafeature.ipynb:生成cnn元特征
* CNN_metafeature_dilated.ipynb:生成cnn_dilated元特征
* pickle_pre.ipynb:解决py2和py3中.pkl文件不兼容的问题
* submit.ipynb:stacking生成最终结果
