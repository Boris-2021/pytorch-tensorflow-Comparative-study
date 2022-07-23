# pytorch-tensorflow-Comparative-study
## 前言

人工智能、机器学习、深度学习已经成为当下最热门的前端科技之一。这三者其实是子-子集的关系。随着技术发展和应用的深入，深度学习越来越重要，成为AI的金字塔。相应的最近年资本和政策都对这个新型的技术方向汇聚，这一方面的程序员工资水平也水涨船高。

<img src=".\梗图\热门方向.png" alt="image-20220723135947199" style="zoom: 25%;" />

随着技术的发展，现在有了一些成熟的工具包，深度学习框架，大大降低了新手入门学习人工智能，深度学习的难度。

<img src="C:\Users\boris\Desktop\pytorch-tensorflow-Comparative-study\梗图\入门学习吧.png" alt="image-20220723141212546" style="zoom:67%;" />

深度学习工程师日常工作是，负责深度学习框架搭建、机器学习、图像处理等的算法和系统研发，支持公司相关产品在深度学习领域的研究。想要入门深度学习编程，我们需要首先选取一个合适深度学习框架进行学习。

常见的深度学习框架有Tensorflow、MXnet、Keras、Caffe 、 Pytorch 、PaddlePaddle等。最流行的框架还是要数Pytorch 、Tensorflow这两种。



## 框架选择

**PyTorch** 是一个开源的机器学习的框架，前身是Torch，其底层和Torch框架一样，但是使用Python重新写了很多内容，不仅更加灵活，支持动态图，而且提供了Python接口。它是由Torch7团队开发，是一个以Python优先的深度学习框架，不仅能够实现强大的GPU加速，同时还支持动态神经网络。PyTorch既可以看作加入了GPU支持的numpy，同时也可以看成一个拥有自动求导功能的强大的深度神经网络。

<img src=".\梗图\学习toech.png" alt="image-20220723153248281" style="zoom: 25%;" />

PyTorch 核心思想是尽量找一种，最好是唯一一种直观易懂的实现方案；用户使用起来写代码快速；它拥有强大的社区支持；代码简单易懂；可以快速实现新的想法。

pytorch虽然发展时间没有tensorflow时间长，但是发展迅猛。在学术界和学生党中备受钦赖，流行度近年大有赶超tensorflow的式态。

<img src=".\梗图\娜美.png" alt="image-20220723145409296" style="zoom:50%;" />



**TensorFlow**也是一个开源的机器学习的框架，我们可以使用 TensorFlow 来快速地构建神经网络，同时快捷地进行网络的训练、评估与保存。

<img src=".\梗图\应用面.png" alt="image-20220723135350390" style="zoom: 33%;" />

tensorflow由谷歌开发、维护，因此可以保障支持、开发的持续性；它的发展时间更长，因此沉淀了巨大、活跃的社区，git上有大量开源项目；提供高阶API高级接口，在你不想要关注模型内部结构的情况下也可以很好的训练起你的模型；他还有一款量身定制的「TensorBoard」可视化套件，旨在跟踪网络拓扑和性能，使调试更加简单；用 Python 编写（尽管某些对性能有重要影响的部分是用 C++实现的），这是一种颇具可读性的开发语言；TensorFlow 不仅支持深度学习，还有支持强化学习和其他算法的工具。

tensorflow在深度学习框架中基本上还是一种老大哥的地位的存在，鉴于它更长时间的发展沉淀，稳定性的表现，部署的轻量化，在工程界受到工程师的钦赖。

<img src=".\梗图\罗宾看书.png" alt="image-20220723151245449" style="zoom:50%;" />



## 写作目的

现在要你选择一个框架去学习，一定会很纠结了，感觉pytroch,和tensorflow各有个的好处，就像两个都很喜欢的妹子，那个都不想放弃。

那么不妨大胆一点，两个都要！哈哈，这不是谈恋爱，没人会说你是渣男，但是也和谈恋爱差不多，都需要用心的去了解学习里边的细节。

<img src="C:\Users\boris\Desktop\pytorch-tensorflow-Comparative-study\梗图\全都要.png" alt="image-20220723153653735" style="zoom: 25%;" />

这就是项目的题目pytorch-tensorflow-Comparative study，pytorch和tensorflow对比学习笔记。

虽然说这两个框架在语法和接口的命名上有很多地方是不同的，但是深度学习的建模过程确实基本上都是一个套路的。

所以该笔记的记录思路是：在使用相同的处理功能模块上，对比记录pytorch和tensorflow两者的API接口，和语法。

**1，有利于深入理解深度学习建模过程流程。**

**2，有利于理解pytorch，和tensorflow设计上的不同，更加灵活的使用在自己的项目中。**

**3，有利于深入理解各个功能模块的使用。**

<img src=".\梗图\全拥有.png" alt="image-20220723160551772" style="zoom:80%;" />



## 说明

笔记中很多代码案例来自于：


**《20天吃掉那只Pytorch》**
* 🚀 github项目地址: https://github.com/lyhue1991/eat_pytorch_in_20_days

**《30天吃掉那只TensorFlow2》**
* 🚀 github项目地址: https://github.com/lyhue1991/eat_tensorflow2_in_30_days

感兴趣的同学可以进入学习。

===========================================================================

我的笔记一部分是将这两项目中内容整理归纳，一部分是相应功能的内容自己找资料整理归纳。

笔记以MD格式存入我的git仓库，另外代码案例所需要数据集文件也在其中：可以clone下来学习使用。

**《pytorch-tensorflow对比学习笔记》**

🚀 github项目地址: https://github.com/Boris-2021/pytorch-tensorflow-Comparative-study

===========================================================================

笔记中增加了很多趣味性的图片，增加阅读乐趣。