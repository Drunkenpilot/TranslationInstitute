<!--
@Author: Matthew Ge <geyuanjun>
@Date:   2017-01-14 21:31:45
@Email:  geyuanjun.sh@superjia.com
@Last modified by:   geyuanjun
@Last modified time: 2017-01-15 22:00:30
-->

# 全栈JS工程师的崛起

### [原文地址](http://thefullstack.xyz/full-stack-javascript-developer/)

翻译：野草  校对：墨白

Javascript无处不在。

过去，Javascript工程师的头衔仅仅意味着你是一个前端工程师，永远只和浏览器打交道。

如今，那个时代已经过去。

NodeJS的崛起开辟了一个新的时代，一个Javascript工程师不仅仅是前端工程师的时代。

现在，作为一个Javascript工程师，相对于其他的高级程序语言，你可以针对更多的平台进行开发。

不过现在，让我们聚焦于这两个主要的平台： 浏览器和服务器。

为何我们一定要二者选一呢？

## 全栈工程师的挑战

俗话说： “样样通，样样松”。正如大多数的俗语一样，它还是有些许道理的。

每当你决定要拓展你的核心竞争力范围的时候，其实你是在变相地占用了提升核心竞争力的时间。

> “如果我被困在一个海岛，唯一出去的办法是设计一个漂亮的UI，那么，我会死在那儿。”——  Linus Torvalds, Linux之父

往全栈发展最大的担忧是你可能会在前后端两个领域的能力都很一般，这比起只在一个领域精通要糟糕得多。

有些工程师经常嘲讽全栈工程师，认为全栈工程师只是那类在软件栈各个领域制造bug的人。

那是因为技术栈总是在不断变化发展。 我们尝试解决的问题也变得越来越复杂。自然而然 ，我们开发中使用到的技术栈也随之变多了。

几年前，学习 JavaScript 只意味着学习经典的ES3。如今如果谁要从头开始学 JavaScript，那他不得不同时学习 ES3 和 ES2015（ES6）。

学习最新最酷的语言特性不能免去你学习最基本的知识的环节。

## 两个技术栈的故事

每个开发技术栈都有自己的一片小天地。

每个语言有自己的开发框架，比如Python有Django，Ruby有Ruby on Rails。

而且，每个技术栈都有自己的包管理器，功能库，以及一些独一无二的语言结构。它们背后都有一群热情的追随者，从博主，专业开发者，到开源代码贡献者。

当然，每个技术栈都各有优缺点。

> 技术栈之间的对比根本就没有意义。

但当你决定发展成全栈的时候，不可避免地，你要在两个技术栈之间徘徊。

一个是你选择的、你喜爱的、你充满热情的技术栈。

另外一个，就是 JavaScript。

> 为什么有些人那么反感JavaScript，部分原因是JavaScript选择了他们，而不是他们选择了JavaScript。对此，他们无能为力。

当网页开发者不想用那些满是坑的插件去写前端代码时，他们不得不用JavaScript。

一些人甚至尝试过去创造一个新的语言，唯一目的就是为了取代JavaScript。但这些语言编译成JavaScript后，其最终结果往往不像它的开发者当初想象地那样完美。

CoffeeScript就是其中之一，但我不会去具体说它。 目前71%的开发者碰也不想碰它。71%！这简直比WordPress还要糟糕。

![image](https://i2.wp.com/thefullstack.xyz/wp-content/uploads/2016/05/CoffeeScript-most-dreaded.jpg?resize=500%2C389)

最后，无论怎么变化，JavaScript始终主宰着网页开发领域，因为它是唯一一个浏览器愿意与外界沟通交流的语言。

很多聪明的开发者，都曾经尝试让浏览器学会说另一句语言，但，他（她）们都一一失败了。

你看多么顽固不化的浏览器啊。

你懂得，如果你不能打败他们的话...（译者话：那就加入他们）

## JavaScript的优势

让我们尝试换个角度去看待事物。

要是，你选择的、你喜爱的、你充满热情的技术栈正好就是JavaScript呢？

> 要是，你选择了它而不是被逼迫着使用它呢?

如果你选择了Node.js作为你后端的语言，你将会体会到一些其他技术栈不能带来的独特的优势，那就是你能一直使用 JavaScript 。

你将不需要搞清楚Lodash在Ruby或者Python中相当于什么，你用就行了。

用pip install或者bundle install你可能用得还挺得心应手的，但是你仍然需要处理JavaScript的依赖。

如果你选择了Node.js， 只要npm install，你就可以搞定客户端和服务端的所有东西。

![image](https://i1.wp.com/thefullstack.xyz/wp-content/uploads/2016/05/13fcit.jpg?resize=500%2C355)

代码复用程度将飙升。就算你的代码发生了[“left-pad”](https://www.zhihu.com/question/41694868)(译者注：大名鼎鼎的left-pad事件，大家都还记得吧？)，你也只需要用一种语言，自己写一次，就可以完美搞定！

如果你走的是JavaScript“大一统”路线，你可以无缝开发一个同时能在浏览器和服务端渲染的web应用。

如你所见，选择 JavaScript 全栈有巨大的好处。很多时候，你会发现你自己从事客户端的开发，同时也获取了适用于服务端的知识。反之亦然。

全栈JavaScript工程师的世界会比其他的全栈工程师轻松很多。但要想成为全栈，不论是客户端还是服务端，需要大量的专业领域知识。

利用 JavaScript，可以分别进行Node.js开发和浏览器开发。

但写跑在浏览器的前端代码和跑在服务器的后端代码仍然是两种截然不同的事情。

那么，成为一个全栈JavaScript工程师是否意味着你必须不断地同时做这两件事情？

## 70/30法则

一些人说没有所谓的全栈工程师，要么是前端为主的，要么就是后端为主的，你必须做个选择。

我也理解这些看法是怎么来的。

找一个同时精通前后端技术的人不亚于找传说中的生物——小精灵。

你以为小精灵能帮你实现所有愿望，给你一堆金币。但是，总有一天你会意识到小精灵是不存在的。你只是喝醉了，正在和一个绿油油的不知名的小东西喃喃自语罢了。真的。

> 真相就是，所有的全栈工程师要么是以前端为主，要么是以后端为主的。

从你的自身出发，选择一个更适合自己的方向。

你要意识到精通前端并没有让你离后端更远。 这仅仅意味着你更倾向于前端方向。

这是为什么我要抛出我的拙见70/30准则：

> 如果给你一年的时间去实现一些功能，技术栈可以有所选择，你要试图将70%的时间花费在你擅长的领域，而剩余的30%搞点其他的花样。

可能你现在工作的公司并不提倡全栈。比如，如果你发现自己只能做后端相关的东西，那你为什么不自己开发一个前端的JavaScript小项目呢？

没有什么事情是板上钉钉的。今年你是一个后端工程师，说不定明年你就转到前端开发了呢？

这仅仅意味着你需要更加努力地提升自己的前端技术，直到你的前端技术变得和后端技术一样厉害。当然，不要忘记花30%的时间保持你对后端技术的精通。

事实是，你可以并且能够精通前后两端，只要你愿意。

## 全栈JavaScript工程师的乐趣

最近StackOverflow的一个调查显示，大多数工程师把自己定义为全栈工程师。调查也显示85.3%的工程师至少知道一些 JavaScript 。

但是，为什么成为一个全栈工程师会如此流行呢？

市场原因吗？不愿意在前后端中做选择吗？还是因为全栈开发者有着不可阻挡的诱惑？

我想，答案远比上述的简单。

> 做一个全栈工程师更加有趣。

当开发一个功能的时候，从前端到后端全部包揽所带来的满足感，是成为一个开发者最大的乐趣之一。

从你亲手创造的UI界面上发送那些小巧可爱的数据，用你亲手创造的API接受这些数据，然后你可以随心所欲地保存或者操作它们。

看到人们使用你前后端一条龙开发的功能，是一件非常奇妙，无法用言语来描述的感觉。你会情不自禁地想：“这是我开发的，要是在以前根本就不可能，而现在人们因为我的付出而正在使用这些功能”。

## 全栈JavaScript工程师的黎明曙光

JavaScript生态系统一直在不断完善。我们从浏览器扩展到了服务器。如今，我们将深入更多的领域。

移动应用，机器人框架，物联网设备，3D游戏，甚至虚拟现实都可以用JavaScript来开发了。

作为全栈JavaScript工程师，我们必须保持在一个领域的精通，使得有那么一件事我们知道自己可以做得非常出色。

软件开发的大门一直向我们敞开着。用你的JavaScript技术，你可以选择探索各种各样新奇刺激的高科技。

成为全栈工程师的关键优势在于，你能不断地学习，不断地内化新事物，然后彻底掌握它们。

JavaScript是你的画布，尽情地用它创造美好的东西吧。