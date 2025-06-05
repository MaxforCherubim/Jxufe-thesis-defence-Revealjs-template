[![jxufe](imgs/logos/江西财经大学-logo.svg)](https://www.jxufe.edu.cn/)

# 江西财经大学答辩Revealjs模板

![License](https://img.shields.io/github/license/MaxforCherubim/Jxufe-thesis-defence-Revealjs-template) [![Revealjs](https://img.shields.io/badge/Revealjs-html?logo=revealdotjs&logoColor=%23F2E142)](https://revealjs.com/) [![Quarto](https://img.shields.io/badge/Quarto-Revealjs?logo=quarto&logoColor=%2339729E)](https://quarto.org/)

为酱菜学子提供方便好用的答辩Revealjs形式Quarto模板

## 目录

- [项目概述​](#项目概述)
- [使用方法​](#使用方法)
- [注意事项​](#注意事项)
- [贡献指南​](#贡献指南)
- [联系方式​](#联系方式)
- [许可证信息​](#许可证信息)

## 项目概述​

- 本项目为[江西财经大学硕士毕业论文全流程]的子项目
- 项目起初源于预答辩，使用的是Revealjs形式的幻灯片进行预答辩
- 本项目在[Github](https://github.com/MaxforCherubim/Jxufe-thesis-defence-Revealjs-template)和[Gitee](https://gitee.com/maxforcherubim/Jxufe-thesis-defence-Revealjs-template)上同步更新，欢迎各位学弟学妹提交反馈，共同完善此模板

> [!TIP]
> <a href="https://revealjs.com/"><img src="imgs/logos/reveal_logo.svg" style="vertical-align: middle; margin-top: -2px" width="80"></a>是一款基于JavaScript构建的幻灯片制作工具
>   1. Revealjs优势是输出格式为HTML，即网页；Revealjs本质上是一个网页形式的幻灯片
>   2. 因此可以展示包括但不限于文本、图片、视频、音频、图表、代码等多种媒体内容
>   3. Revealjs能实现的展示能力绝对远超你的想象，包括但不限于多设备同步展示（老师与学生福音）；3D图形展示等
>   4. 但也正因为其网页特性，很多功能默认需要联网（其实直接把所以资源都保存在本地也可以，但这样对使用者要求较高），在遇到没有网络的展示环境时，弊端很大

- 本项目特别之处在于使用[Quarto]来输出[Revealjs]幻灯片
    1. 这样无需学习语法或者少量学习，甚至AI输出部分，就可以轻松得到所需的Revealjs幻灯片
    2. 本质是使用Quarto来驾驭Revealjs输出，所以只需一个Quarto模版即可

> [!TIP]
> <a href="https://quarto.org/"><img src="imgs/logos/quarto.png" style="vertical-align: middle; margin-top: -2px" width="80"></a>是一款优秀的排版系统，可以输出HTML，PDF，Word等多种格式的文档
>   1. Quarto最大的优势是可以在一个文档中同时数学文字和代码，而且代码可以直接运行，其运行结果直接嵌入文档中，这就使得文档本身是可以自动化的。比如根据不同客户的数据输出各自的报告，只需要准备好Quarto模版和数据，就可以直接生成成百上千的客户报告，还是精排的。
>   2. 劣势是学习曲线较陡峭，且自定义程度不算高，有些个性化需求需要自己写代码实现。

## 使用方法​

1. 下载并安装Quarto，具体教程请参考[Get Started](https://quarto.org/docs/get-started/)

> [!TIP]
> MacOS的可以使用brew安装

2. 在Vscode（建议）中安装Quarto插件
3. Git clone本项目到本地
4. 在Vscode中打开本项目，修改Quarto模版文件内容为你自己的内容，运行后即可输出你的Revealjs幻灯片

## 注意事项​

1. 强烈建议先仔细学习一下Quarto的[Get Started](https://quarto.org/docs/get-started/)章节，熟悉Quarto的基本用法
2. 再强烈建议先学习一下Quarto[有关Revealjs的介绍](https://quarto.org/docs/presentations/revealjs/presenting.html)，了解Revealjs的基本用法，包括但不限于**画板**、**演讲者视图**等
3. 本项目较为傻瓜，安装好Quarto和Vscode对应的Quarto插件后，就可以运行本项目了，排版自己的Revealjs幻灯片了。如果在使用过程中产生了多种问题，请在[讨论区]创建相关讨论，我都会尽力解答的
4. 由于Quarto的不断更新，可能会导致本项目产生Bug，除此之外还可能会有其他Bug，请在Github上提交[issues]，我会及时修复
5. 本项目模版使用的字体是楷体，由于对前端的不了解，无法做到在HTML中嵌入自己喜欢的[霞鹜文楷]字体，非常欢迎使用者能够解决这个问题并分享给我
6. 本项目充分利用了Revealjs的特性，加入了根据[Plotly](https://plotly.com/)制作的可交互式表格，可以展示超长表格
7. 本项目还充分利用了开源开发者开发的关于Revealjs的[Quarto拓展](https://quarto.org/docs/extensions/listing-revealjs.html)，实现了一些高级功能，比如[按下Q可以更改鼠标指针](https://github.com/quarto-ext/pointer)；[多Logo设置](https://github.com/shafayetShafee/reveal-header)；[插入特殊图标](https://github.com/quarto-ext/fontawesome)等，如果还有其他高级功能需要，可以先浏览一下Quarto的拓展列表，或者在讨论区创建讨论

## 贡献指南​

- 本项目强烈呼吁各位使用者即各位学弟学妹提交反馈，包括但不限于在使用过程中遇到的问题、想到的建议，甚至是小白问题都可以在讨论区创建讨论，我会及时参与讨论的！**我们的所有互动都会成为后来者的学习资料，请积极参加！**
- 如果对本项目感兴趣，甚至想要进一步开发，欢迎提交PR！

## 联系方式​

- 本项目作者是章迎潭，本科17级经济统计1班，硕士23级应用统计2班
- 导师为数理统计系马海强教授
- 邮件：<EMAIL><bay237580157@outlook.com>

## 许可证信息​

本项目开源许可证为[MIT license](https://opensource.org/license/mit/)

[回到顶部](#目录)

<!-- 引用链接 -->
[江西财经大学硕士毕业论文全流程]: https://github.com/MaxforCherubim/Jxufe-master-thesis-process
[Github]: https://github.com/MaxforCherubim/Jxufe-thesis-defence-Revealjs-template
[Gitee]: https://gitee.com/MaxforCherubim/Jxufe-thesis-defence-Revealjs-template
[Revealjs]: https://revealjs.com/
[Quarto]: https://quarto.org/
[Get Started]: https://quarto.org/docs/get-started/
[讨论区]: https://github.com/MaxforCherubim/Jxufe-thesis-defence-Revealjs-template/discussions
[issues]: https://github.com/MaxforCherubim/Jxufe-thesis-defence-Revealjs-template/issues
[霞鹜文楷]: https://github.com/lxgw/LxgwWenKai
[章迎潭]: https://github.com/MaxforCherubim
[马海强教授]: https://stat.jxufe.edu.cn/news-show-7166.html
[MIT license]: https://opensource.org/licenses/MIT
