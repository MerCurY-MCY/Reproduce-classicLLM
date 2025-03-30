# Reproduce-classicLLM


## Introduction

本仓库主要用于学习LLM知识以及锻炼编程能力，欢迎有志于学习大模型知识的朋友们follow，共同学习交流，一起进步。

本仓库会**从头复现GPT、Bert两个经典的LLM模型**，并在**本地机器消费卡上进行训练和推理**。同时，会将所有代码涉及到的**经典论文详细解读**同步上传，在实践中**学习LLM领域的基础知识**。

主要将实现：1.BPE、WordPiece分词模型；2.LayerNorm、MultiHeadAttention、TransformerBlock；3.完整的Bert和GPT1/2分词器、模型搭建，并加载完成推理；4.MSELoss、CrossEntropy等Loss，SGD、AdamW等Optimizer，并训练一个自己的小型类ChatGPT模型；5.Linux多进程、Pytorch分布式通信以及混合精度和分布式训练；6.全功能trainer开发。


## Todo List

- [ ] 分词模型
- [ ] LayerNorm、MultiHeadAttention、TransformerBlock（自注意力中的核心木块哦）
- [ ] Bert以及GPT1/2结构搭建
- [ ] 类ChatGPT模型训练
- [ ] 混合精度和分布式训练
- [ ] 全功能trainer开发


## References

### Academic Papers

1. Mikolov, T., Chen, K., Corrado, G., & Dean, J. (2013). Efficient estimation of word representations in vector space. arXiv preprint arXiv:1301.3781.


### GitHub Repositories

1. https://github.com/firechecking/CleanTransformer
