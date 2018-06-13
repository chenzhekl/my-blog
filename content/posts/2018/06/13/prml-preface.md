---
title: "[PRML翻译] 序言"
date: 2018-06-13T12:38:08+09:00
draft: false
---

## 序言

模式识别发源于工程界，而机器学习来自计算机科学。但是，它们可以看作同一领域的两面，在过去的十年共同经历了高速发展。其中，贝叶斯方法从小众逐渐走向主流，各种图模型也作为通用框架被用于描述和应用概率模型。除此之外，得益于一系列近似推断算法（例如变分贝叶斯和期望传播）的发展，贝叶斯方法的实用性得到增强。类似的，基于核方法的新模型也在算法和应用领域产生了重要影响。

本书全面介绍了模式识别与机器学习领域的基础与最新发展。它的目标读者是高年级研究生或博士第一年的学生，当然同样适合研究者与实践者。本书假设读者没有模式识别或机器学习相关领域的概念，如果读者了解多变量微积分、基础的线性代数和一点点概率论的话是在好不过了。不了解也不要紧，我们在书中提供了自成一体的基础概率论介绍。

本书涵盖甚广，因此很难提供完整的参考文献列表，也无意提供准确的相关历史。相反，我们的目标是作为一个入口，为读者指出拥有更深入细节的参考文献。基于这个原因，本书的参考文献大多是最近的教科书或综述性质的文章，而非最初的起源。

本书拥有大量的支持资料，包括课堂用幻灯片、完整的图表集，我们鼓励读者访问网站获取最新信息：[http://research.microsoft/~cmbishop/PRML](http://research.microsoft/~cmbishop/PRML)[^1]

[^1]: 译注：最新网址：[https://www.microsoft.com/en-us/research/people/cmbishop/#!prml-book](https://www.microsoft.com/en-us/research/people/cmbishop/#!prml-book)

### 习题

每章末尾的习题是本书重要的一部分。每道习题都经过精心挑选，用于增强对正文相关概念的理解。每道习题标注有难度，（\*）代表花费几分钟就能解决，（\*\*\*）代表习题相对会复杂的多。

很难说该多大程度公开习题的答案。对自学的人来说，参考答案会很有帮助；而许多课程的助教则希望解答只能通过出版社获取。为了满足这些冲突的需求，那些涉及关键概念或提供重要补充细节的习题，我们在网站上以 PDF 文件的形式提供解答。这些习题被标注有 **WWW**。剩余习题的解答对课程助教开放，请联系出版社获取（联系细节公布在网站上）。我们强烈建议读者独自解答习题，只在必要时求助参考答案。

虽然本书专注于概念和原理，在课堂教学中，学生最好使用合适的数据集自己实验相关算法。我们会提供一卷支持材料（Bishop and Nabney, 2018）介绍模式识别与机器学习的实际应用，并会提供大多数算法的 Matlab 实现。

### 致谢

首先我要对 Markus Svensén 表达诚挚的谢意，感谢他在图表准备以及 `$ \LaTeX $` 排版上给予的巨大帮助。

我很感激微软研究院提供了令人兴奋的研究环境，以及我写作这本书的自由（但是本书中表达的观点仅代表个人看法，与微软及关其联实体没有任何关系）。

Springer 为本书最终阶段的准备提供了大量支持，我想感谢我的委托编辑 John Kimmel 的专业与支持，并且感谢 Joseph Piliero 在封面设计与文字排版上提供的帮助，还有 MaryAnn Brickner 在印刷阶段做出的贡献。封面设计的灵感来自与 Antonio Criminisi 的一次讨论。

我还想感谢牛津大学出版社允许我摘录更早的一本教科书：模式识别中的神经网络（Neural Networks for Pattern Recognition）（Bishop, 1995a）。Mark 1 感知器以及 Frank Rosenblatt 的图片得到了 Arvin Calspan 高级科技中心的许可。我还想感谢 Asela Gunawardana 绘制了图 13.1 的光谱图，以及 Bernhard Scholköpf 允许我使用它的核 PCA 代码绘制图 12.17。

还有许多人在本书写作阶段提供了帮助与建议，他们包括 Shivani Agarwal, Cédric Archambeau, Arik Azran, Andrew Blake, Hakan Cevikalp, Michael Fourman, Brendan Frey, Zoubin Ghahra- mani, Thore Graepel, Katherine Heller, Ralf Herbrich, Geoffrey Hinton, Adam Jo- hansen, Matthew Johnson, Michael Jordan, Eva Kalyvianaki, Anitha Kannan, Julia Lasserre, David Liu, Tom Minka, Ian Nabney, Tonatiuh Pena, Yuan Qi, Sam Roweis, Balaji Sanjiya, Toby Sharp, Ana Costa e Silva, David Spiegelhalter, Jay Stokes, Tara Symeonides, Martin Szummer, Marshall Tappen, Ilkay Ulusoy, Chris Williams, John Winn, and Andrew Zisserman。

最后，我想感谢我的妻子 Jenna 在写作本书数年中提供的全力支持。

Chris Bishop  
剑桥  
2006 年 2 月
