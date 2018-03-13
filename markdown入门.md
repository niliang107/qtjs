[转载](https://www.jianshu.com/p/1e402922ee32/)

# MarkDown -- 从入门到精通
#### 导语：
> [Markdown](http://zh.wikipedia.org/wiki/Markdown) 是一种轻量级的「标记语言」，它的优点很多，目前被越来越多的写作爱好者，撰稿者广泛使用。
看到这里请不要被「标记」、「语言」所迷惑，Markdown 的语法十分简单。常用的标记符号也不超过十个，这种相对于更为复杂的HTML 标记语言来说，Markdown 可谓是十分轻量级的，
学习成本也不需要太多，且一旦数据这种语法规则，会有一劳永逸的效果。

## 一、认识Markdown
在刚才的导语里提到，Markdown 是一种用来写作的轻量级「标记语言」，它用简洁的语法代替排版，而不像一般我们用的字处理软件 Word 或 Pages 有大量的排版、
字体设置。它使我们专心于码字，用「标记」语法，来代替常见的排版格式。例如此文从内容到格式，甚至插图，键盘就可以通通搞定了。目前来看，支持Markdown 语法的
编辑器有很多，包括很多网站（例如[简书](http://jianshu.io)）也支持了Markdown 的文字录入。Markdown 从写作到完成，导出格式随心所欲，你可以导出HTML格
式的文件用来网站发布，用Markdown 写出的简历也是十分方便的导出PDF格式更能得到HR的好感。本文所有的格式、内容也是用Markdown 写成。

### Markdown 官方文档
> 这里可以看到官方的Markdown 语法规则文档，当然，后文我也会用自己的方式阐述这些语法的具体用法。

* [*创始人John Gruber的Markdown 语法说明*](http://daringfireball.net/projects/markdown/syntax)
* [*Markdown 中文版语法说明*](http://wowubuntu.com/markdown/#list)

### 使用Markdown 的优点
* 专注你的文字内容而不是排版
* 轻松的导出HTML、PDF和本身的.md文件
* 纯文本内容，兼容所有的文本编辑器与字处理软件
* 可读，直观。适合所有人的写作语言

### 我们该用什么工具
![Mou icon](http://mouapp.com/Mou_128.png)

在Mac OS X上，我们强烈的建议你使用[Mou](http://mouapp.com)这款免费且十分好用的Markdown 编辑器，它支持实时预览，既左边是你编辑Markdown语言，右边会实时
预览效果，笔者文章就是Mou这款软件写出来的。不仅如此，Mou 还有一些有趣的偏好设置（Preference），例如主题（Themes）与样式（CSS），它们可以配置出定制化的文
本编辑效果与导出效果，如果你对自带的主题与样式不满意还可以到 GitHub 上搜索其它爱好者为 Mou 编写的更多主题样式，导入的方式可以在偏好设置的 Themes 或
CSS 选项中 选择 reload。

![image](http://ww1.sinaimg.cn/large/6aee7dbbgw1effcq2gx92j210j0ustj7.jpg)

如果你从事文字工作，我强烈建议你购买 Ulysses for Mac，这款软件入围了苹果 Mac App Store 的 The Best of 2013。它支持更多的写作格式、多文档的支持。
Mou，iA writer 这些软件都是基于单文档的管理方式，而 Ulysses 支持 Folder、Filter 的管理，一个 Folder 里面可以创建多个 Sheet，Sheet 之间也可以进行 Combine 处理。

![image](http://ww1.sinaimg.cn/large/6aee7dbbjw1eqgrj7suqoj217a0aiq4u.jpg)

* 由于笔者很少接触 Windows，Windows 下的 Markdown 没有过多涉猎，经朋友介绍，有两款还算不错，一款叫做 MarkdownPad ，另一款叫做 MarkPad。
* iOS 端很多 app 早已经支持了 Markdown 录入，例如 Drafts，Day One，iA writer 等，另外 Ulysses for iPad 现在已经上架，可以说是 iOS 平台最好的编辑器了。
* 在 Web端，我强烈推荐简书这款产品，上面有无数热爱文字的人在不停的创造，分享。在 Web 端使用 Markdown 没有比简书更舒服的地方了，同样支持左右两栏的实时预览，字体优雅，简洁。

## 二、Markdown 语法的简要规则
### 标题
![image](http://ww1.sinaimg.cn/large/6aee7dbbgw1effeaclhiyj20eh09cwez.jpg)

标题是每篇文章都需要也是最常用的格式，在 Markdown 中，如果一段文字被定义为标题，只要在这段文字前加 # 号即可。

`# 一级标题`

`## 二级标题`

`### 三级标题`

以此类推，总共六级标题，建议在井号后加一个空格，这是最标准的 Markdown 语法。

### 列表
熟悉 HTML 的同学肯定知道有序列表与无序列表的区别，在 Markdown 下，列表的显示只需要在文字前加上 - 或 * 即可变为无序列表，有序列表则直接在文字前加1. 2. 3. 符号要
和文字之间加上一个字符的空格。

![image](http://ww4.sinaimg.cn/large/6aee7dbbgw1effew5aftij20d80bz3yw.jpg)

### 引用
如果你需要引用一小段别处的句子，那么就要用引用的格式。

> 例如这样

只需要在文本前加入 > 这种尖括号（大于号）即可

![image](http://ww3.sinaimg.cn/large/6aee7dbbgw1effezhonxlj20e009c3yu.jpg)

### 图片与链接
插入链接与插入图片的语法很像，区别在一个 !号

`图片为：![]()`

`链接为：[]()`

插入图片的地址需要图床，这里推荐围脖图床修复计划 与 CloudApp 的服务，生成URL地址即可。

![image](http://ww2.sinaimg.cn/large/6aee7dbbgw1efffa67voyj20ix0ctq3n.jpg)

### 粗体与斜体
Markdown 的粗体和斜体也非常简单，用两个 * 包含一段文本就是粗体的语法，用一个 * 包含一段文本就是斜体的语法。

例如：**这里是粗体** *这里是斜体*

### 表格
表格是我觉得 Markdown 比较累人的地方，例子如下：

    | Tables        | Are           | Cool  |

    | ------------- |:-------------:| -----:|

    | col 3 is      | right-aligned | $1600 |

    | col 2 is      | centered      |   $12 |

    | zebra stripes | are neat      |    $1 |

这种语法生成的表格如下：                       

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

### 代码框
如果你是个程序猿，需要在文章里优雅的引用代码框，在 Markdown下实现也非常简单，只需要用两个 ` 把中间的代码包裹起来。
图例：

![image](http://ww3.sinaimg.cn/large/6aee7dbbgw1effg1lsa97j20lt0a8dgs.jpg)

使用 tab 键即可缩进。

### 分割线
分割线的语法只需要三个 * 号，例如：

> 到这里，Markdown 的基本语法在日常的使用中基本就没什么大问题了，只要多加练习，配合好用的工具，写起东西来肯定会行
云流水。更多的语法规则，其实 Mou 的 Help 文档栗子很好，当你第一次使用 Mou 时，就会显示该文档。可以用来对用的查找和学习。

![image](http://ww3.sinaimg.cn/large/6aee7dbbgw1effgmnpgqlj210j0us44j.jpg)

## 三、相关推荐
### 工具
*图床工具用来上传图片获取 URL 地址*
* [Droplr](https://link.jianshu.com/?t=http://droplr.com)
* [Cloudapp](https://link.jianshu.com/?t=http://www.getcloudapp.com)
* [ezShare for Mac](https://link.jianshu.com/?t=https://itunes.apple.com/cn/app/yi-xiang/id672522335?mt=12&uo=4)
* [D围脖图床修复计划](https://link.jianshu.com/?t=http://weibotuchuang.sinaapp.com)

*在线好用的Markdown工具，为印象笔记而生*

* [马克飞象，专为印象笔记打造的Markdown编辑器，非常推荐](https://link.jianshu.com/?t=http://maxiang.info)

### 相关文章阅读：
* [为什么作家应该用 Markdown 保存自己的文稿](https://www.jianshu.com/p/qqgjln)
* [Markdown写作浅谈](https://link.jianshu.com/?t=http://www.yangzhiping.com/tech/r-markdown-knitr.html)
* [Markdown 工具补完](https://link.jianshu.com/?t=http://www.appinn.com/markdown-tools/)
* [Drafts + Scriptogr.am + Dropbox 打造移动端 Markdown 风格博客](https://www.jianshu.com/p/63HYZ6)
* [图灵社区，怎样使用Markdown](https://link.jianshu.com/?t=http://www.ituring.com.cn/article/23)
* [为什么我们要学习Markdown的三个理由](https://link.jianshu.com/?t=http://news.cnblogs.com/n/139649/)
* [Markdown 语法写作入门指南 by ibuick](https://link.jianshu.com/?t=http://ibuick.me/?p=4093)

本文首发在[少数派](https://link.jianshu.com/?t=http://sspai.com/25137)转载请注明原作者，如果你觉得这篇文章对你有帮助或启发，
也可以来请我[喝咖啡](https://link.jianshu.com/?t=http://ww2.sinaimg.cn/large/6aee7dbbjw1eiixgkex2ij21kw0t7wn5.jpg)。