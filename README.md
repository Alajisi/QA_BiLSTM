# QA_BiLSTM
A QA System based by BiLSTM. 一个基于双向LSTM的智能问答系统，有交互界面、详细注释、多版本、能运行、文件齐全，极易上手。
> # 基于BiLSTM的中文问答系统 #
> 
> **本项目通过建立双向长短期记忆网络模型，实现了在多个句子中找到给定问题的答案所在的句子这一功能。**
> 
> # 如何运行 #
>
> ## 相关文件 ##
>
> 模型、语料、词向量文件：https://pan.baidu.com/s/127rM4g8bHvYDQt7XG1nwhw   
> 提取码：7g7p
>
> ## 环境依赖 ##
> 
> | 程序 | 版本 |
> |---|---|
> | python | 3.5.2 |
> | TensorFlow | 1.2.1 |
> | jieba | 0.38 |
> 
> ## 运行程序 ##
> 
> 装好了依赖库之后，直接执行main.py即可。如果有已经训练好的模型，程序会提示您是直接加载这个模型，还是重新开始训练。
> 
> main.py不接收参数，如果需要修改配置，请直接修改代码。文件中有详细中文注释，据此修改即可
> 
> taevaluation.py是一个评估脚本，可以提供MRR，MAP，ACC@1的评估

