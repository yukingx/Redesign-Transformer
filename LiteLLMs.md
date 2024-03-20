# LLMs for Resource-constrained Hardware
- Training/Fine-Tuning Time/Cost
- Memory (Storage) Efficiency
- Inference Latency

## Compression / Lite LLMs
### Representatives
- TinyBERT, MobileBERT, DistillBERT...
### Pruning for LLMs
- [COMPRESSO: STRUCTURED PRUNING WITH COLLABORATIVE PROMPTING LEARNS COMPACT LARGE LANGUAGE MODELS](https://arxiv.org/pdf/2310.05015.pdf)  
### KD for LLMs
#### KD original papers
- Cristian Buciluundefined, Rich Caruana, and Alexan- 659 dru Niculescu-Mizil. 2006. Model compression. In Proceedings of the 12th ACM SIGKDD International 661 Conference on Knowledge Discovery and Data Mining, KDD ’06, page 535–541, New York, NY, USA. 663 Association for Computing Machinery.
- Geoffrey Hinton, Oriol Vinyals, and Jeff Dean. 2015. Distilling the knowledge in a neural network. (arXiv:1503.02531arXiv:1503.02531). ArXiv:1503.02531 [cs, stat].
#### Widely-used KD techniques
- 
#### LLM Distillation 
##### 2020
- Victor Sanh, Lysandre Debut, Julien Chaumond, and Thomas Wolf. 2020. Distilbert, a distilled version of bert: smaller, faster, cheaper and lighter.
- Xiaoqi Jiao, Yichun Yin, Lifeng Shang, Xin Jiang, Xiao Chen, Linlin Li, Fang Wang, and Qun Liu. 2020 Tinybert: Distilling bert for natural language understanding.
- Victor Sanh, Lysandre Debut, Julien Chaumond, and Thomas Wolf. 2020. Distilbert, a distilled version of bert: smaller, faster, cheaper and lighter.
- Zhiqing Sun, Hongkun Yu, Xiaodan Song, Renjie Liu, Yiming Yang, and Denny Zhou. 2020. Mobilebert: a compact task-agnostic bert for resource-limited devices.
##### 2021
- [EMNLP 2021, CKD, Distilling Linguistic Context for Language Model Compression](https://aclanthology.org/2021.emnlp-main.30.pdf)
##### 2022
- Alireza Mohammadshahi, Vassilina Nikoulina, Alexandre Berard, Caroline Brun, James Henderson, and Laurent Besacier. 2022. Small- 790 100: Introducing shallow multilingual ma- 791 chine translation model for low-resource languages. (arXiv:2210.11621arXiv:2210.11621). ArXiv:2210.11621 [cs].
##### 2023
- Nan He, Hanyu Lai, Chenyang Zhao, Zirui Cheng, Junt- ing Pan, Ruoyu Qin, Ruofan Lu, Rui Lu, Yunchen Zhang, Gangming Zhao, Zhaohui Hou, Zhiyuan Huang, Shaoqing Lu, Ding Liang, and Mingjie Zhan. 2023. Teacherlm: Teaching to fish rather than giving the fish, language modeling likewise. (arXiv:2310.19019). ArXiv:2310.19019 [cs]
- Mrigank Raman, Pranav Mani, Davis Liang, and Zachary Lipton. 2023. For distillation, tokens are not all you need. In NeurIPS 2023 Workshop on Instruction Tuning and Instruction Following.
- Sayantan Dasgupta, Trevor Cohn, and Timothy Baldwin. 2023. Cost-effective distillation of large language 679 models. In Findings of the Association for Computational Linguistics: ACL 2023, pages 7346–7354.
##### 2024
- [MiniLLM: Knowledge Distillation of Large Language Models](https://arxiv.org/pdf/2306.08543.pdf)  

### Quantization for LLMs
### Etc.
#### Effiicient decoding
- Yaniv Leviathan, Matan Kalman, and Yossi Matias. 773 2023. Fast inference from transformers via speculative decoding. In International Conference on 775 Machine Learning, pages 19274–19286. PMLR.
- Qinyuan Ye, Iz Beltagy, Matthew Peters, Xiang Ren, and Hannaneh Hajishirzi. 2023. FiD-ICL: A fusion- in-decoder approach for efficient in-context learning. In Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers), pages 8158–8185, Toronto, Canada. Association for Computational Linguistics.
#### Model recycling
- Brian Lester, Joshua Yurtsever, Siamak Shakeri, and 770 Noah Constant. 2022. Reducing retraining by recycling parameter-efficient prompts.
#### Size reduction
- Tim Dettmers, Artidoro Pagnoni, Ari Holtzman, and Luke Zettlemoyer. 2023. Qlora: Efficient finetuning of quantized llms.
- Xinyin Ma, Gongfan Fang, and Xinchao Wang. 2023. Llm-pruner: On the structural pruning of large language models.
## Fast Fine-Tuning for Downstream Tasks (Deployment)
### Adaptor for LLMs
- 

## Architecture Search
#### Supernet Based
- 

## Representative LLMs
☑️ BERT Families  
☑️ LLaMa  
☑️ Mistral  
☑️ Falcon  
☑️ GPT-NeoX  
☑️ Mixtral  

## NLP Tasks
- Question and Answering
- Extractive Q&A
- Generative Q&A
- Machine Translation
- Summary
- Text Generation
- Text Recognition
- Document Retrieval
- Multimodal
- RAG

## NLP Datasets - Metric: Zero-Shot (%)
- CoLA
- MRPC
- SST2 (SST-2)
- QNLI
- QQP
- RTE
- WMT'14 En-De
- WMT'14 EN-Fr
- WMT'19 En-De

## NLP Datasets - Metric: ?
- SQuAD (Stanford Question Answer Dataset)  
- C4 (Crawled Corpus)
- Alpaca dataset
- GPT4-Alpaca dataset (Peng et al., 2023): including 52K GPT-4 generated instruction-following data in English.
- [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation- harness/pull/531)
- MRPC
- RTE
- GLUE(General Language
Understanding Evaluation) benchmark: MNLI-(m/mm) - Acc, SST-2 - Acc, QNLI - Acc, MRPC - F1/Acc, QQP - F1/Acc, RTE - Acc, STS-B - Pear/Spear  
<img src="GLUE benchmark.png">
- MNLI
- STS-B

## NLP Datasets - Metric: Perplexity
- WikiText2
- PTB

## Zero-shot classification task on commonsense reasoning benmarks::
- BoolQ
- PIQA
- HellaSwag
- WinoGrande
- ARC-e
- ARC-c
- OBQA
## 57 tasks covering STEM, humanities, social science, etc. 
- MMLU (Massive Multitask Language Understanding)
<!--
- 인공지능 모델이 획득한 지식을 측정하는 벤치마크이다. 약 57개의 주제(STEM, the humanities, the social sciences 등)에 대해 다지선다 문제를 푸는 테스트이다. 특히 zero-shot 환경이나 few-shot 환경에 맞게 되어있다고 한다.
-->
- [Papers with Code - MMLU Benchmark (Multi-task Language Understanding)](https://paperswithcode.com/sota/multi-task-language-understanding-on-mmlu)
- [GitHub - hendrycks/test: Measuring Massive Multitask Language Understanding | ICLR 2021](https://github.com/hendrycks/test)

## NLP Metrics
- F1
- Accuracy?
- Zero-Shot (%)
- Perplexity (PPL)
- Average GLUE
- BLEU
- SacreBLEU
- k-shot MMLU
- Training Time
- Search Time
- Memory
- #Params

## Etc.
- AIC (Akaike information criterion)
- BIC (Bayes Information Criteria)
