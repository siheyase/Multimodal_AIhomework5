# Multimodal_AIhomework5
## 多模态拟合情感分析模型
**目录结构**  
| 文件 | 内容 |
|----- | ------|
| data文件夹 | 原始数据 |
| processed_data文件夹 | 处理后的文本数据 |
| data.py | 数据处理的代码|
|model.py | 定义模型和训练、测试函数的代码 |
| main.py | 执行命令的主代码，解析命令行调用对应方法 |
| test_with_label.txt | 预测的测试标签 |
| train.txt/test_with_label.txt | 训练/测试数据 |
| word2vec.model | 训练好的Word2Vec模型 |

**执行流程**  

1. python ./data.py  
   运行data.py文件，训练获得Word2Vec模型并保存，仓库里上传了训练好的Word2Vec模型，这一步可以忽略  
2. python ./main.py --train --model 3 --test  
   运行main.py文件，其中选择--train选项开启训练，--model设置使用的模型类别，--test使用训练后保存的模型预测测试集的tag

