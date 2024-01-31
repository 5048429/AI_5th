# AI_5th

# 多模态情感分析



## 环境配置

在命令行使用
> pip install -r requirements.txt

安装配置环境

## 仓库结构
```
|-- code.ipynb # 代码与运行结果文件
    |-- 多模态模型训练代码
    |-- 消融实验一次epoch训练代码
    |-- 消融实验训练代码

|-- requirements.txt # 项目依赖文件
|-- test_without_label # 测试集结果文件
|-- error_analysis.txt # 多模态验证集错误记录
|-- 第五次实验实验报告 # 实验报告
```

## 代码运行

打开code.ipynb直接运行

## 调用的主要库
### PyTorch (torch):
使用了torch.nn来定义模型类别和层，torch.optim来进行优化，以及torch.utils.data中的Dataset和DataLoader类来加载和批处理数据。

### TorchVision (torchvision):
使用了torchvision.models来获取预训练的ResNet50模型，以及torchvision.transforms来进行图像的预处理。

### Transformers (transformers):
使用了BertTokenizer来对文本数据进行分词，以及BertModel来从文本中提取特征。

### Pillow (PIL):
使用了Pillow来加载和处理图像数据。

### Scikit-learn (sklearn):
使用了train_test_split函数来将数据集分割为训练集和验证集。

### OS (os) 和 CSV (csv):
使用os.path.join来构建文件路径，csv.reader来读取标签数据。

