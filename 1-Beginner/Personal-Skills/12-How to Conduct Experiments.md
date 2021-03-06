# 如何进行实验

已故的伟大的Edsger Dijkstra曾经充分解释过：计算机科学不是一门实验科学[ExpCS],并且不依赖于电子计算机。当他提出这个观点时，他指的是19世纪60年代。[Knife]

> ...危害已经出现：主题现在已经变成了“计算机科学” - 这实际上，像是把外科手术引用为“手术刀科学” - 这在人们心中深深植入了这样一个概念：计算机科学是关于机器和它们的外围设备的。

编程不应该是一门实验科学，但大多数职业程序员并没有保卫Dijkstra对于计算机科学的解释的荣耀。我们必须在实验的领域里工作，正如一部分，但非所有的，物理学家做的。如果三十年后，编程可以在不进行任何实验的前提下进行，这将是计算机科学的一个巨大成就。

你需要进行的实验包括：
- 用小的例子测试系统以验证它们遵循文档，或者在没有文档时，理解它们的反应；
- 测试一些小的代码修改去验证它们是否确实修复了一个bug；
- 由于对一个系统不完全的理解，需要在两种不同情况下测量它们的性能表现；
- 检查数据的完整性；
- 对困难的或者难以重现的bug，收集解决方案中可能提示的统计数据。

我不认为在这篇文章里我可以讲述实验的设计，你会在实践中学习到这方面的知识。然而，我可以提供两点建议：

第一，对你的假设或者你要测试的断言要非常清楚。把假设写下来也是很有用的，尤其是如果你有点迷惑或者与其他人合作时。

第二，你会经常发现你必须设计一系列的实验，它们中的每个都基于对最后一个实验的理解。所以，你应该设计你的实验去提供大部分可能的信息。不幸的是，这会影响保持实验简单的目的 - 你必须通过经验来发展这种权衡的能力。

Next [团队技能 - 为什么评估很重要](../Team-Skills/01-Why Estimation is Important.md)
