# NLP-TupleExtraction
A final project for AI-Fundamental in UCAS 2018 Winter

# Description about the file
1. pretrain_data.py  
预训练数据，输入为训练的.json文件，输出为处理过的.npy文件，将句子处理为
训练输入
2. train.py  
网络，输入为.npy文件，然后训练之后保存.ckpt
3. RuleMatch.py  
规则匹配，可用于检查验证集的F1
4. model.py  
输入为测试数据.json文件，输出为.json文件，给每个sentence的dict加了一个
'results'域，'results'里面为预测的正确三元组