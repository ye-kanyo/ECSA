# ECSA
Crawl specific content from txts document and store them in Excel by openpyxl
客户（就是我技己啦）需求：哎呀，我平时工作需要将txt文件中特定部分机械化复制，粘贴汇总在一个Excel中，然后再进行统一的数据的处理（加减乘除之类的），
有时候txt文件比较多，这样的工作就很枯燥，一点没有创造性，有没有什么办法可以制作个机器人来帮我完成我的工作呀？

我（小菜鸡）：制作一个机器人那你不就下岗了吗摔，还是帮你写个小程序吧！

客户：得嘞！那就拜托您嘞~

大过年的，说干就干

编译环境

python3.6

Excel：2010

思路

都说程序员的工作效率，其实分为A、B两个部分，就是A（get the point）知道怎么做，和B（reach the point）将想法落实成真正能够实现的代码
这两个部分用的时间越少，你的工作效率越高

PART A

实现的话很简单，主要分两步，第一步，循环txt，在其中找到需要的内容；第二步，将需要的内容提取出来，写入excel中

就是这么简单

第一步实现方法，可以用正则表达式，也可以直接用条件语句，各显神通了

第二步就涉及到了一个工具，这个工具很有意思，也是这篇文章最主要的重点了，就是openpyxl，用python读取写入或者各种txt提取数据到excel的方法有很多，这里选择的这种有持续的更新，并且可以适用excel2010版本，关于openpyxl，还有篇外国友人写的文章挺实用的，比较基础全面，可以学习一下。

PART B

具体在代码里面有注释，比较简单，show me the code
代码请移驾，欢迎大家讨论
