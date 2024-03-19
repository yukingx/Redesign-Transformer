# NLP Tasks
- Q&A
- Machine Translation
- Summary

# NLP Datasets - Metric: Zero-Shot (%)
- CoLA
- MRPC
- SST2 (SST-2)
- QNLI
- QQP
- RTE
- WMT'14 En-De
- WMT'14 EN-Fr
- WMT'19 En-De

# NLP Datasets - Metric: ?
- C4 (Crawled Corpus)
- Alpaca dataset
- GPT4-Alpaca dataset (Peng et al., 2023): including 52K GPT-4 generated instruction-following data in English.
- [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation- harness/pull/531)
- MRPC
- RTE
- GLUE benchmark: MNLI-(m/mm) - Acc, SST-2 - Acc, QNLI - Acc, MRPC - F1/Acc, QQP - F1/Acc, RTE - Acc, STS-B - Pear/Spear
<img src="GLUE benchmark.png">
- MNLI
- STS-B

# NLP Datasets - Metric: Perplexity
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
- 인공지능 모델이 획득한 지식을 측정하는 벤치마크이다. 약 57개의 주제(STEM, the humanities, the social sciences 등)에 대해 다지선다 문제를 푸는 테스트이다. 특히 zero-shot 환경이나 few-shot 환경에 맞게 되어있다고 한다.
- [Papers with Code - MMLU Benchmark (Multi-task Language Understanding)](https://paperswithcode.com/sota/multi-task-language-understanding-on-mmlu)
- [GitHub - hendrycks/test: Measuring Massive Multitask Language Understanding | ICLR 2021](https://github.com/hendrycks/test)


# NLP Metrics
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