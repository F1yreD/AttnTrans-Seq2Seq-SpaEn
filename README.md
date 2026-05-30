# AttnTrans-Seq2Seq-SpaEn
基于pytorch框架实现的Seq2Seq模型，加入Bahdanau Attention机制，用于西班牙语-英语翻译任务，使用https://www.manythings.org/anki/ 的英语西班牙语数据集训练模型（约100,000条数据），模型效果如下：

CrossEntropy: 
- 4-layer GRU model(encode padding first):2.36
- 1-layer GRU model(encode padding first):1.18
- 1-layer GRU model(encode padding last):1.16

BLEU-1: 
- 1-layer GRU model(encode padding first):0.7242
- 1-layer GRU model(encode padding last):0.7180

BLEU-4: 
- 1-layer GRU model(encode padding first):0.3747
- 1-layer GRU model(encode padding last):0.3712
