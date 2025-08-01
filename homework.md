## 第一周
## 第二周
1.使用完整的 YelpReviewFull 数据集训练，时间会比较长，如果有条件建议使用完整的YelpReviewFull 数据集进行训练。如果条件有限，可以根据自己的情况适量减少训练的数据量。
2.如果使用完整的 YelpReviewFull 数据集训练，默认产生的checkpoints文件一共需要300G多一点的磁盘空间。如果磁盘空间不够，需要在训练参数里加上：save_total_limit=5，避免磁盘被撑满。

https://github.com/ZhigangY/ai-start/blob/main/transformers/fine-tune-quickstart-tf4.52.4.ipynb

https://github.com/ZhigangY/ai-start/blob/main/transformers/fine-tune-QA-tf4.52.4.ipynb

第二周作业二：
学习重点：
了解如何使用init8量化加载模型，了解LoRA微调的整体流程。

facebook/opt-6.7b

zai-org/chatglm3-6b

huggingface-cli download --resume-download facebook/opt-6.7b

| Epoch	| Training Loss | Validation Loss|
|------|-------------|-------------|
| 1  |	0.345100 |	0.403887 |
| 2 | 	0.315200 | 	0.385204| 
| 3 | 	0.245900 | 	0.388408| 

有条件的用最好的 claude
有工作流agent 类似研究院的实现思路的 用 cozy
直接用continue等插件的 用 qwen3 coder

Week02-作业安排 

温馨提示：自备算力条件的同学可以先行完成作业练习和作业的提交，助教老师会根据提交时间先后进行批改，不具备算力条件的同学可以先行继续学习路径中的其他课程，作业可以安排在8月份提交。

第二周作业一:
1、使用完整的 YelpReviewFull 数据集训练，对比看 Acc 最高能到多少。课程代码（ https://github.com/DjangoPeng/LLM-quickstart/blob/main/transformers/fine-tune-quickstart.ipynb ）
2、加载本地保存的模型，进行评估和再训练更高的 F1 Score。课程代码（ https://github.com/DjangoPeng/LLM-quickstart/blob/main/transformers/fine-tune-QA.ipynb ） 
第二周作业二: 
1、在“LoRA 低秩适配 OpenAI Whisper-Large-V2 语音识别任务”中，为中文语料的训练过程增加过程评估，观察 Train Loss 和 Validation Loss 变化。课程代码（ https://github.com/DjangoPeng/LLM-quickstart/blob/main/peft/peft_lora_whisper-large-v2.ipynb ） 
2、在“LoRA 低秩适配 OpenAI Whisper-Large-V2 语音识别任务”中，当 LoRA 模型训练完成后，使用测试集进行完整的模型评估。课程代码（ https://github.com/DjangoPeng/LLM-quickstart/blob/main/peft/peft_lora_whisper-large-v2.ipynb ） 

【作业提交方式】 

将执行完的 ipynb 文件（有运行结果）上传至 GitHub，然后将相关 ipynb 的 GitHub 链接（比如： https://github.com/DjangoPeng/LLM-quickstart/blob/main/transformers/pipelines.ipynb ） 复制到调查问卷https://jinshuju.com/f/RfrLKa中，填写并“提交”即可。

https://github.com/ZhigangY/ai-start/blob/main/week2/1.ipynb , 
https://github.com/ZhigangY/ai-start/blob/main/week2/2.ipynb , 
https://github.com/ZhigangY/ai-start/blob/main/week2/3.ipynb , 
https://github.com/ZhigangY/ai-start/blob/main/week2/4.ipynb

huggingface-cli download --resume-download facebook/opt-6.7b


