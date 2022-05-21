# OOD检测与异常检测
## 工程内容说明
1. origin_data 目录：
   1. .log文件为mininet生成性能数据
   2. csv.tag包含针对.log文件中各字段的说明
2. work 目录：
    1. Dataset 包含所有训练集、测试集数据
    2. model 包含训练结果——模型文件
    3. ood_dataset.csv, tagged_dataset_csv为增加了标签的性能数据
3. model_training.ipynb 包含数据清洗、模型训练、模型测试、模型导出全流程