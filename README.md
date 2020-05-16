## Text-classification 电影评论情感分类
使用LSTM和LSTM+Attention来进行文本二分类  

## 环境
* python3
* python 1.4.0

## 数据集
训练集：包含2W条左右中文电影评论，其中正负向评论各1W条左右；  
验证集：包含6K条左右中文电影评论，其中正负向评论各3K条左右；  
测试集：包含360条左右中文电影评论，其中正负向评论各180条左右。  
具体例子如下：  
0	拍摄 出发点 挺 好 但是 其中 人物 几种 死法 与 书 内容 这种 关联性 没有 体现 结局 也 有点 突兀 如果 这些 细节 能 处理 好 会 一部 非常 棒 电影

## 结果
 模型  | 表头  
 ---- | ----- 
 单元格内容  | 单元格内容 
 单元格内容  | 单元格内容 
 
｜模型 ｜ Acc｜
｜----｜----｜
｜LSTM｜0.847｜
｜LSTM+Attention｜0.856｜

