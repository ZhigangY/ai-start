## 第一周
## 第二周
1.使用完整的 YelpReviewFull 数据集训练，时间会比较长，如果有条件建议使用完整的YelpReviewFull 数据集进行训练。如果条件有限，可以根据自己的情况适量减少训练的数据量。
2.如果使用完整的 YelpReviewFull 数据集训练，默认产生的checkpoints文件一共需要300G多一点的磁盘空间。如果磁盘空间不够，需要在训练参数里加上：save_total_limit=5，避免磁盘被撑满。

https://github.com/ZhigangY/ai-start/blob/main/transformers/fine-tune-quickstart-tf4.52.4.ipynb

https://github.com/ZhigangY/ai-start/blob/main/transformers/fine-tune-QA-tf4.52.4.ipynb

第二周作业二：
学习重点：
了解如何使用init8量化加载模型，了解LoRA微调的整体流程。

