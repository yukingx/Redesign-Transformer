# Redesign of Efficient Transformers

[![Hits](https://hits.sh/github.com/silentsoft/hits.svg)](https://hits.sh/github.com/silentsoft/hits/)

### ** Transformer **
<!--
![](original_transformer.png)
-->
<img src="original_transformer.png" height="600">

### ** Papers📄 **  

Hand Crafted Transformers:  
☑️ [Attention is All You Need](https://arxiv.org/pdf/1706.03762.pdf)  
☑️ [ViT]()  
☑️ [Mobile ViT]()  
☑️ [Swin-T]()  
☑️ [TinyViT]()  
☑️ [MinViT]()  
☑️ [EfficientViT]()  

Block-level Efficient Transformers:  
✅ [Simplifying Transformer Blocks](https://arxiv.org/pdf/2311.01906.pdf)  
☑️ [Rethinking Spatial Dimensions of Vision Transformers](https://arxiv.org/pdf/2103.16302.pdf)  
☑️ [The Shaped Transformer: Attention Models in the Infinite Depth-and-Width Limit](https://arxiv.org/pdf/2306.17759.pdf)  
☑️ [Pale Transformer: A General Vision Transformer Backbone with Pale-Shaped Attention](https://arxiv.org/pdf/2112.14000.pdf)  
☑️ [Training-free Transformer Architecture Search](https://arxiv.org/pdf/2203.12217.pdf)    
☑️ [Blockwise-Parallel-Transformer-for-Long-Context-Large-Models](https://arxiv.org/pdf/2305.19370.pdf)  
☑️ [BI-DIRECTIONAL BLOCK SELF-ATTENTION FOR FAST AND MEMORY-EFFICIENT SEQUENCE MODELING](https://arxiv.org/pdf/1804.00857.pdf)  

NAS for Efficient Transformers:  
☑️ [The Evolved Transformer](https://arxiv.org/pdf/1901.11117.pdf)  
☑️ [AutoFormer: Searching Transformers for Visual Recognition](https://arxiv.org/pdf/2107.00651.pdf)  
☑️ [COSFORMER : RETHINKING SOFTMAX IN ATTENTION](https://arxiv.org/pdf/2202.08791.pdf)  
☑️ [NAR-Former V2: Rethinking Transformer for Universal Neural Network Representation Learning](https://arxiv.org/pdf/2306.10792.pdf)  

Trainging-Free NAS
[]()

### ** Goals 🚀 **
✅ Understand the concept of Attention, Self-Attention, and Multi-Head Attention.  
☑️ Understand the concpet of Key, Query, and Value.  
☑️ Understand the concpet of Positional Encoding.  
☑️ Understand the concpet of Encoder and Decoder.  
☑️ Test and Understand a training process of the original transformer at the code level.  
☑️ Design and Implement a parallelized transformer block of the encoder.  
☑️ Design and Implement a simplified transformer block of the encoder.  

### ** Related GitHub Works: **
🌐 [MS Cream](https://github.com/microsoft/Cream/tree/main) - A Collection of NAS and Vision Transformer Work: ('20) Cream, ('21) AutoFormer, AutoFormerV2, ('22) TinyViT, MinViT, CDARTS, and ('23) TinyCLIP, EfficientViT 
🌐 [NAS-With-Code](https://github.com/xiaoiker/NAS-With-Code)
🌐 [Neural-Architecture-Search-PaperAndCode-Sunmary](https://github.com/LiuTingWed/Neural-Architecture-Search-PaperAndCode-Sunmary)
🌐 [Neural Tangent Kernel Papers](https://github.com/kwignb/NeuralTangentKernel-Papers)
☑️ Add more repositories. 

### ** Articles: **
☑️ [The Annotated Transformer](https://nlp.seas.harvard.edu/2018/04/03/attention.html) - Code Based Explanation (So Good for Newbies!)  
☑️ Vision Transformer (ViT)  
☑️ GPT 2  
☑️ [Transformer Details Not Described in The Paper](https://tunz.kr/post/4)  
☑️ [Transformer, GPT-3,GPT-J, T5 and BERT.](https://aliissa99.medium.com/transformer-gpt-3-gpt-j-t5-and-bert-4cf8915dd86f)  
☑️ [Beyond Token Prediction: the post-Pretraining journey of modern LLMs](https://amatriain.net/blog/postpretraining)  
☑️ [Understanding the Neural Tangent Kernel](https://rajatvd.github.io/NTK/)
☑️ Add more articles.  

Korean:  
☑️ [셀프 어텐션 동작 원리](https://ratsgo.github.io/nlpbook/docs/language_model/tr_self_attention/)
<!-- 
- https://github.com/ndb796/Deep-Learning-Paper-Review-and-Practice?tab=readme-ov-file 
-->

### ** Videos: **
Korean:  
☑️ [[딥러닝 기계 번역] Transformer: Attention Is All You Need (꼼꼼한 딥러닝 논문 리뷰와 코드 실습)](https://www.youtube.com/watch?v=AA621UofTUA)

### ** Free Books: **
☑️ [딥 러닝을 이용한 자연어 처리 입문](https://wikidocs.net/book/2155) - Transformer Fundamentals for NLP (Korean Only)
<!--
- (TensorFlow) https://github.com/ukairia777/tensorflow-nlp-tutorial
- (PyTorch) https://wikidocs.net/book/2788
- (Slides) https://www.slideshare.net/wonjoonyoo/ss-188835227
-->
☑️ [PyTorch로 시작하는 딥 러닝 입문](https://wikidocs.net/book/2788) - See the parts of NLP (Korean Only)

### ** Implementation **
I plan to apply these tools for my implementation:  
✅ PyTorch, Conda, GPU Server with A5000 x 8, tmux for session management  
☑️ [WandB 를 활용하여 모델의 학습을 추적하는 방법](https://teddylee777.github.io/machine-learning/wandb/)  
