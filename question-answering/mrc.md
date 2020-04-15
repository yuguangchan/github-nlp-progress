## 阅读理解

### DuReader
- 数据集简介：<br>DuReader是一个面向真实应用的、开放域的、最大规模的中文问答阅读理解数据集。与以前的阅读理解数据集相比，DuReader的优势是（1）数据来源真实：DuReader的问题是百度搜索中用户提出的真实问题，文档来自于百度搜索和百度知道，并且答案都是人工标注的。（2）问题类型丰富：DuReader提供了更加丰富的问题类型标注，每个问题的类型标注属于两个维度：第一个维度包括了实体类、描述类和是非类，第二个维度包括了事实类和观点类。（3）数据规模大：DuReader包含了30万问题，72万答案和150万文档，它是迄今为止最大的中文阅读理解数据集。基于DuReader的2018机器阅读理解技术竞赛获得了学术界和工业界的高度关注，共有1062个队伍报名，累计提交结果1489次。评测期间，最好系统的性能大幅提高，Rouge-L值从35.92提高至63.62，推动了中文阅读理解技术的整体发展。

- 数据集详情：

|  名称 | 规模 | 创建日期 | 作者 | 单位 | 论文 | 下载 | 评测 |
| :---: | :---:| :---: | :---: | :---: | :---: | :---: | :---: |
| DuReader | 30万问题<br>140万文档<br>66万答案 | 2017年 | He et al. | 百度 | [链接](https://www.aclweb.org/anthology/W18-2605.pdf) | [链接](https://ai.baidu.com/broad/introduction?dataset=dureader)| [2018 NLP Challenge on MRC](http://mrc2018.cipsc.org.cn/)<br> [2019 Language and Intelligence Challenge on MRC](http://lic2019.ccf.org.cn/) |

- 基于该数据集发表的相关论文
    * Yan, M., Xia, J., Wu, C., Bi, B., Zhao, Z., Zhang, J., Si, L., Wang, R., Wang, W. and Chen, H., 2019, July. A deep cascade model for multi-document reading comprehension. In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 33, pp. 7354-7361).
    * Wang, Y., Liu, K., Liu, J., He, W., Lyu, Y., Wu, H., Li, S. and Wang, H., 2018, July. Multi-Passage Machine Reading Comprehension with Cross-Passage Answer Verification. In Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) (pp. 1918-1927).


### DuReader<sub>robust</sub>
- 数据集简介：<br>随着技术的进步，当前的一些模型已经能够在一些阅读理解测试集上取得较好的性能。但在实际应用中，这些模型所表现出的鲁棒性仍然较差。因此，DuReader<sub>robust</sub>数据集重点关注阅读理解模型在真实应用场景中的鲁棒性，挑战模型的过敏感性、过稳定性以及泛化能力等。该数据集共包含约21K问题，其中包括15K训练集，约1.4K领域内开发集和5K测试集。测试集包含了领域内测试集和鲁棒性测试集，其中鲁棒性测试集包括了过敏感测试集、过稳定测试集以及泛化能力测试集。基于DuReader<sub>robust</sub>数据集的2020语言与智能技术竞赛机器阅读理解任务的评测，已经吸引了超过1000支队伍的报名。

- 数据集详情：

|  名称 | 规模 | 创建日期 | 作者 | 单位 | 论文 | 下载 | 评测 |
| :---: | :---:| :---: | :---: | :---: | :---: | :---: | :---: |
| DuReader<sub>robust</sub> | 2.2万问题 | 2020年 | Tang et al. | 百度 | [链接](#) | [链接](https://github.com/PaddlePaddle/Research/tree/master/NLP/DuReader-Robust-BASELINE)| [2020 Language and Intelligence Challenge on MRC](http://lic2020.cipsc.org.cn/) |


### CMRC 2018
- 数据集简介：CMRC 2018数据集是哈工大讯飞联合实验室发布的中文机器阅读理解数据。 根据给定问题，系统需要从篇章中抽取出片段作为答案，形式与SQuAD相同。 

|  名称 | 规模 | 创建日期 | 作者 | 单位 | 论文 | 下载 | 评测 |
| :---: | :---:| :---: | :---: | :---: | :---: | :---: | :---: |
| DuReader | 30万问题<br>140万文档<br>66万答案 | 2017年 | Wei He et al. | 百度 | [链接](https://www.aclweb.org/anthology/W18-2605.pdf) | [链接](https://ai.baidu.com/broad/introduction?dataset=dureader)| [2018 NLP Challenge on MRC](http://mrc2018.cipsc.org.cn/)<br> [第二届“讯飞杯”中文机器阅读理解评测](https://hfl-rc.github.io/cmrc2018/) |


### DRCD
- 数据集简介：DRCD数据集由中国台湾台达研究院发布，其形式与SQuAD相同，是基于繁体中文的抽取式阅读理解数据集。 由于ERNIE中去除了繁体中文字符，故不建议在繁体中文数据上使用ERNIE（或转换成简体中文后再处理）。 

|  名称 | 规模 | 创建日期 | 作者 | 单位 | 论文 | 下载 | 评测 |
| :---: | :---:| :---: | :---: | :---: | :---: | :---: | :---: |
| DuReader | 30万问题<br>140万文档<br>66万答案 | 2017年 | Wei He et al. | 百度 | [链接](https://www.aclweb.org/anthology/W18-2605.pdf) | [链接](https://ai.baidu.com/broad/introduction?dataset=dureader)| [2018 NLP Challenge on MRC](http://mrc2018.cipsc.org.cn/)<br> [2019 Language and Intelligence Challenge on MRC](http://lic2019.ccf.org.cn/) |


### CJRC
- 数据集简介：CJRC数据集是哈工大讯飞联合实验室发布的面向司法领域的中文机器阅读理解数据。 需要注意的是实验中使用的数据并非官方发布的最终数据，结果仅供参考。 

|  名称 | 规模 | 创建日期 | 作者 | 单位 | 论文 | 下载 | 评测 |
| :---: | :---:| :---: | :---: | :---: | :---: | :---: | :---: |
| DuReader | 30万问题<br>140万文档<br>66万答案 | 2017年 | Wei He et al. | 百度 | [链接](https://www.aclweb.org/anthology/W18-2605.pdf) | [链接](https://ai.baidu.com/broad/introduction?dataset=dureader)| [2018 NLP Challenge on MRC](http://mrc2018.cipsc.org.cn/)<br> [2019 Language and Intelligence Challenge on MRC](http://lic2019.ccf.org.cn/) |
