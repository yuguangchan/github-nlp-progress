# 词法分析
## 分词
### 1. SIGHAN 2005数据集
- **数据集简介：**

    SIGHAN 2005数据集国际中文自动分词评测（简称SIGHAN评测）整合多个机构的分词数据集构成。该数据集由中国微软研究所、北京大学、香港城市大学、台湾中央研究院联合发布，用以进行中文分词模型的训练与评测。其中 AS 和 CityU 为繁体中文数据集，PKU 和 MSR 为简体中文数据集。

- **数据集详情：**

    | 名称  | 规模      | 创建日期           | 单位           | 论文 | 下载                                                     | 评测                                                         |
    | ----- | -------------------- | ---- | -------------- | ---- | -------------------------------------------------------- | ------------------------------------------------------------ |
    | MSR   | 2368391词，4050469字 | 2005年 | 微软亚洲研究院 | [链接](https://www.aclweb.org/anthology/I05-3017.pdf)  | [SIGHAN2005](http://sighan.cs.uchicago.edu/bakeoff2005/) | [icwb2 result summary](http://sighan.cs.uchicago.edu/bakeoff2005/data/results.php.htm) |
    | PKU   | 1109947词，1826448字  | 2005年  | 北京大学       | [链接](https://www.aclweb.org/anthology/I05-3017.pdf)  | [SIGHAN2005](http://sighan.cs.uchicago.edu/bakeoff2005/) | [icwb2 result summary](http://sighan.cs.uchicago.edu/bakeoff2005/data/results.php.htm) |
    | AS    | 5449698词，8368050字  | 2005年  | 台湾中央研究院 | [链接](https://www.aclweb.org/anthology/I05-3017.pdf)  | [SIGHAN2005](http://sighan.cs.uchicago.edu/bakeoff2005/) | [icwb2 result summary](http://sighan.cs.uchicago.edu/bakeoff2005/data/results.php.htm) |
    | CityU | 1455629词，2403355字 | 2005年  | 香港城市大学   | [链接](https://www.aclweb.org/anthology/I05-3017.pdf)  | [SIGHAN2005](http://sighan.cs.uchicago.edu/bakeoff2005/) | [icwb2 result summary](http://sighan.cs.uchicago.edu/bakeoff2005/data/results.php.htm) |
- **基于该数据集发表的论文**：
    - Chen X , Xipeng Qiu∗,  Zhu C , et al. Long Short-Term Memory Neural Networks for Chinese Word Segmentation[C]// Proceedings of the 2015 Conference on Empirical Methods in Natural Language Processing. 2015.
    Cai D ,  Zhao H . Neural Word Segmentation Learning for Chinese[J].  2016.

    - Chen X ,  Shi Z ,  Qiu X , et al. Adversarial Multi-Criteria Learning for Chinese Word Segmentation[J].  2017.
    - Jie Yang, Yue Zhang, Fei Dong. Neural Word Segmentation with Rich Pretraining[C]// The 55th Annual Meeting of the Association for Computational Linguistics (ACL). 2017.
    
    - Ma J ,  Ganchev K ,  Weiss D . State-of-the-art Chinese Word Segmentation with Bi-LSTMs[J].  2018.
    - Huang W ,  Cheng X ,  Chen K , et al. Toward Fast and Accurate Neural Chinese Word Segmentation with Multi-Criteria Learning[J].  2019.


## 词性标注

### 1. Chinese Treebank X.0 (CTBX)
- **数据集简介：**

    由LDC构建的中文树库。CTBX中X表示版本，随着版本数据规模扩大，以及部分标准修正。CTB1标注数据来自新华日报；CTB2对CTB1进行部分纠正以及进行发布；CTB4标注数据来自新华日报、香港政府新闻处发布的新闻、以及台湾Sinorama magazine；CTB5标注数据来源同CTB4，对规模进行扩大；CTB6增加了来自广播节目的标注数据；CTB7增加了广播新闻、微博数据、以及广播电视谈话类节目数据；CTB8标注数据来源新闻数据、新闻杂志、广播新闻、广播谈话节目、微博、以及网页数据；CTB9标注数据来自新闻数据、新闻杂志、广播新闻、广播谈话节目、微博、论坛、聊天对话、电话数据。

- **数据集详情：**

    |  名称 | 规模 | 创建日期 | 作者 | 单位 | 论文 | 下载 | 评测 |
    | :---: | :---:| :---: | :---: | :---: | :---: | :---: | :---: |
    | CTB1 | 100000个词，325篇文章 | 2000年 | -- | LDC | [链接](https://pdfs.semanticscholar.org/2c72/257ae7a4a32dc60569f4e1fe4504b2678112.pdf) | 未发布 | N/A |
    | CTB2 | 100000个词，325篇文章 | 2001年 | Martha Palmer, et al. | LDC | [链接](https://arxiv.org/abs/cs/0204007) |[会员下载](https://catalog.ldc.upenn.edu/LDC2001T11) | N/A |
    | CTB4 | 404156词，664663个汉字，15162个句子，838个文件 | 2004年 | Martha Palmer, et al. | LDC | N/A |[会员下载](https://catalog.ldc.upenn.edu/LDC2004T05) | N/A |
    | CTB5 | 507222词，824983个汉字，18782个句子，890个文件 | 2005年 | Martha Palmer, et al. | LDC | [链接](https://www.ldc.upenn.edu/sites/www.ldc.upenn.edu/files/acl2005-parallel-entity-treebank-annotation.pdf) |[会员下载](https://www.ldc.upenn.edu/language-resources/data/obtaining) |N/A |
    | CTB6 | 781351词，1285149个汉字，28295个句子，2036个文件 | 2007年 | Martha Palmer, et al. | LDC | N/A |[会员下载](https://catalog.ldc.upenn.edu/LDC2007T36) | N/A |
    | CTB7 | 1196329词，1931381个汉字，51447个句子，2448个文件 | 2010年 | Nianwen Xue, et al. | LDC | [链接](https://www.ldc.upenn.edu/sites/www.ldc.upenn.edu/files/tlt9-parallel-aligned-treebank-corpora-at-ldc.pdf) |[会员下载](https://catalog.ldc.upenn.edu/LDC2010T07) | N/A |
    | CTB8 | 1620561词，2589848个汉字，71369个句子，3007个文件 | 2013年 | Nianwen Xue, et al. | LDC | N/A |[会员下载](https://catalog.ldc.upenn.edu/LDC2013T21) | N/A |
    | CTB9 | 2084387词，3247331个汉字，132076个句子，3726个文件 | 2016年 | Nianwen Xue, et al. | LDC | N/A |[会员下载](https://catalog.ldc.upenn.edu/LDC2016T13) | N/A |

- **基于该数据集发表的相关论文：**
    - Chen, Xinchi, Xipeng Qiu, and Xuanjing Huang. "A feature-enriched neural model for joint Chinese word segmentation and part-of-speech tagging." arXiv preprint arXiv:1611.05384 (2016).
    - Diao, Shizhe, et al. "ZEN: Pre-training Chinese Text Encoder Enhanced by N-gram Representations." arXiv preprint arXiv:1911.00720 (2019).

## 命名实体识别

### 1. 微软实体数据集
- **数据集简介：**

    MSRANER是由微软亚洲研究院标注的新闻领域的实体识别数据集，也是SIGNAN backoff 2006的实体识别任务的数据集之一。该数据集包含5 万多条中文实体识别标注数据，实体类别分为人物、地点、机构三类。
- **数据集详情：**

    | 名称      | 规模 | 创建日期 | 单位 | 论文 | 下载 | 评测 |
    | --------- | ---- |  --- | ---- | ---- | ---- | ---- |
    | MSRANER |  训练集46364个句子，验证集4365个句子  |   2006年   |微软亚洲研究院 |    [链接](https://www.aclweb.org/anthology/W06-0115.pdf)   |   [链接](https://github.com/InsaneLife/ChineseNLPCorpus/tree/master/NER/MSRA) | [链接](https://www.aclweb.org/anthology/W06-0115.pdf)|

- **基于该数据集发表的论文**：
    - Zhang, Yue , and  J. Yang . "Chinese NER Using Lattice LSTM." (2018).
    - Li, Xiaoya , et al. "Dice Loss for Data-imbalanced NLP Tasks." (2019).
    - Li, Xiaoya , et al. "A Unified MRC Framework for Named Entity Recognition." (2019).
    - Diao, Shizhe, et al. "ZEN: Pre-training Chinese Text Encoder Enhanced by N-gram Representations." arXiv preprint arXiv:1911.00720 (2019).
    - Yan, Hang , et al. "TENER: Adapting Transformer Encoder for Named Entity Recognition." (2019).


### 2. 微博实体数据集
- **数据集简介：**

    WeiboNER是根据新浪微博2013年11月至2014年12月间历史数据筛选过滤生成，包含1890条微博消息，基于[LDC2014的DEFT ERE的标注标准](https://tac.nist.gov/2016/KBP/guidelines/DEFT_ERE_Entities_IndividualGroup_Guidelines_V2.6.pdf)
    进行标注。该数据集实体类别分为人物，机构组织，地址和地缘政治实体4个类别，并且每个类别可细分为特指（NAM，如“张三”标签为“PER.NAM”）和泛指（NOM，如“男人”标签为“PER.NOM”）。

- **数据集详情：**

    | 名称      | 规模 | 创建日期| 作者 | 论文 | 下载 | 评测 |
    | --------- | ---- |  --- | ---- | ---- | ---- | ---- |
    | WeiboNER | 1890条微博消息 | 2015  |   Nanyun Peng | [original](https://www.aclweb.org/anthology/D15-1064.pdf)<br>[revised](https://arxiv.org/abs/1611.04234)    |     [链接](https://github.com/hltcoe/golden-horse)  |[链接](http://www.cs.jhu.edu/~npeng/papers/golden_horse_supplement.pdf) |
- **基于该数据集发表的论文**：
    - Peng, Nanyun, and Mark Dredze. "Named entity recognition for chinese social media with jointly trained embeddings." Proceedings of the 2015 Conference on Empirical Methods in Natural Language Processing. 2015.
    - He, Hangfeng, and Xu Sun. "F-score driven max margin neural network for named entity recognition in chinese social media." arXiv preprint arXiv:1611.04234 (2016).
    - Zhang, Yue , and  J. Yang . "Chinese NER Using Lattice LSTM." (2018).
    - Cao, Pengfei , et al. "Adversarial Transfer Learning for Chinese Named Entity Recognition with Self-Attention Mechanism." Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing 2018.
    - Yan, Hang , et al. "TENER: Adapting Transformer Encoder for  Named Entity Recognition." (2019).

### 3. 简历实体数据集
- **数据集简介：**

    Resume NER是根据新浪财经网关于上市公司的高级经理人的简历摘要数据，进行筛选过滤和人工标注生成的。该数据集包含1027份简历摘要，实体标注分为人名、国籍、籍贯、种族、专业、学位、机构、职称等8个类别。

- **数据集详情：**

    | 名称      | 规模 | 创建日期 | 作者 | 论文 | 下载 | 评测 |
    | --------- | ---- | --- | ---- | ---- | ---- | ---- |
    | Resume NER | 1027份简历  |  2018年 | Yue Zhang | [链接](https://arxiv.org/abs/1805.02023) | [链接](https://github.com/jiesutd/LatticeLSTM)  | N/A|

- **基于该数据集发表的论文**：
    - Zhang, Yue, and Jie Yang. "Chinese NER Using Lattice LSTM." Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers). 2018.
    - Yan, Hang , et al. "TENER: Adapting Transformer Encoder for  Named Entity Recognition." (2019).

### 4. 细粒度实体数据集
- **数据集简介：**

    CLUENER2020是根据清华大学开源的文本分类数据集THUCNEWS，进行筛选过滤、实体标注生成的。该数据集包含组织、人名、地址、公司、政府、书籍、游戏、电影、职位、景点等10个实体类别，且实体类别分布较为均衡。
- **数据集详情：**

    | 名称      | 规模 | 创建日期 | 单位 | 论文 | 下载 | 评测 |
    | --------- | ---- | ---- | ---- | ---- | ---- | ---- |
    | CLUENER2020 | 训练集10748个句子，验证集1343个句子 | 2020年 | CLUEbenchmark  | [链接](https://arxiv.org/abs/2001.04351)  | [链接](https://www.cluebenchmarks.com/introduce.html)    |      [链接](https://github.com/CLUEbenchmark/CLUENER2020)|