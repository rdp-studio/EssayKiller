
# EssayKiller



<a href="https://colab.research.google.com/github/rdp-studio/EssayKiller/blob/master/lab.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>![image](https://img.shields.io/badge/License-Apache--2.0-green) ![image](https://img.shields.io/badge/License-MIT-orange)  ![image](https://img.shields.io/badge/License-Anti--996-red)  ![image](https://img.shields.io/badge/pypi-v0.0.1a4-yellowgreen) ![image](https://img.shields.io/badge/stars-%3C%201k-blue) ![image](https://img.shields.io/badge/issues-1%20open-brightgreen)  

通用型议论文创作人工智能框架，仅限交流与科普。

## 项目简介
EssayKiller是基于OCR、NLP领域的最新模型所构建的生成式文本创作AI框架，目前第一版finetune模型针对高考作文（主要是议论文），可以有效生成符合人类认知的文章，多数文章经过测试可以达到正常高中生及格作文水平。

| 项目作者        | 主页1           | 主页2  | 主页3 |
| ------------- |:-------------:|:----:|:---:|
| 图灵的猫（原作者）       | [知乎](https://www.zhihu.com/people/dong-xi-97-29) |[B站](https://space.bilibili.com/371846699) | [Youtube](https://www.youtube.com/channel/UCoEVP6iTw5sfozUGLLWJyDg/featured) |
| 启动台Start（修改者）       | [B站](https://space.bilibili.com/392383363) |


## Q&A
* **我能否用EssayKiller来帮自己写作业？**  
  不能。所以有下一个问题：  
  
* **为什么缺少一些关键文件？**  
项目在一开始是完全开源的，经过慎重考虑我认为完全开源会被部分别有用心的人用以牟利，甚至用作不法用途。参考咸鱼和淘宝上一些魔改的开源框架应用。部分懂技术又不想动笔的小同志可能会让Essaykiller帮自己写作业，比如读后感、课后作文、思修小论文。我想说，这样不好。  

* **为什么不直接加密？**  
本来打算用混淆加密，但一些模块本就是开源的，所以我开源了整体的模型文件，只隐藏了关键的，包括pipeline、输入输出在内的文件，另外有些文件里也加了盐。  

* **有哪些模组可用？**  
目前完全开源，可以独立复用的部分包括：
  - [x] 检测网络
  - [x] 文本摘要网络
  - [x] 文本生成网络
  - [x] 判分网络与排版脚本  

* **为什么不用GPT-3**  
训练一个中文GPT-3的价格至少为1200万美元，折合人民币将近1亿。要是真有人训练出来一个中文GPT-3还开源模型文件了，我愿称之为最强。  

* **训练EssayKiller需要多少钱？**  
从头到尾训练完pipeline的话在1K～100K人民币不等，取决于你有无分布式集群可用  

<br>

## Citation
```
@misc{EssayKillerBrain,
  author = {Turing's Cat},
  title = {Autowritting Ai Framework},
  year = {2020},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/rdp-studio/EssayKiller}},
}
```

<br>


## 参考资料  
[1] BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding  
[2] ERNIE: Enhanced Representation through Knowledge Integration  
[3] Fine-tune BERT for Extractive Summarization  
[4] EAST: An Efficient and Accurate Scene Text Detector  
[5] An End-to-End Trainable Neural Network for Image-based Sequence Recognition and Its Application to Scene Text Recognition  
[6] Language Models are Unsupervised Multitask Learners  
[7] https://github.com/Morizeyao/GPT2-Chinese  
[8] https://github.com/argman/EAST  
[9] https://github.com/bgshih/crnn  
[10] https://github.com/zhiyou720/chinese_summarizer  
[11] https://zhuanlan.zhihu.com/p/64737915  
[12] https://github.com/ouyanghuiyu/chineseocr_lite  
[13] https://github.com/google-research/bert  
[14] https://github.com/rowanz/grover  
[15] https://github.com/wind91725/gpt2-ml-finetune-  
[16] https://github.com/guodongxiaren/README  
[17] https://www.jianshu.com/p/55560d3e0e8a  
[18] https://github.com/YCG09/chinese_ocr  
[19] https://github.com/xiaomaxiao/keras_ocr  
[20] https://github.com/nghuyong/ERNIE-Pytorch  
[21] https://zhuanlan.zhihu.com/p/43534801  
[22] https://blog.csdn.net/xuxunjie147/article/details/87178774/  
[23] https://github.com/JiangYanting/Pre-modern_Chinese_corpus_dataset  
[24] https://github.com/brightmart/nlp_chinese_corpus  
[25] https://github.com/SophonPlus/ChineseNlpCorpus  
[26] https://github.com/THUNLP-AIPoet/Resources  
[27] https://github.com/OYE93/Chinese-NLP-Corpus  
[28] https://github.com/CLUEbenchmark/CLUECorpus2020  
[29] https://github.com/zhiyou720/chinese_summarizer  


## 免责声明
该项目中的内容仅供技术研究与科普，不作为任何结论性依据，不提供任何商业化应用授权
