# 一次快乐的世界文化之旅

作者： [@小星喵](http://bbs.chongbuluo.com/space-uid-5417.html) 

~ 此为信息分析报告（完全版）示范，卡包原始素材借鉴自 [虫部落题目第十四期：地球上最神奇的一条线-虫部落](http://bbs.chongbuluo.com/thread-2804-1-1.html) 特此鸣谢！

## 目录

0. 摘要


1. 背景

2. 分析过程

   2.1 三种思路

   2.2 具体步骤

3. 结论

4. 讨论

   4.1 对结论的讨论

   4.2 可优化的环节

   4.3 收获：建立工具思维

   4.4 收获：把问题推向无穷

5. 参考文献



## 0. 摘要

这是开智学堂「信息分析」课程第 x 周任务报告，包含分析背景、思路与分析步骤、主要结论、进一步讨论、参考文献等内容，完整重现我获取此题目答案的过程。

本次题目我共找到 3 个分析思路，最终采取思路三 —— 借助批量经纬度查询标记工具，批量获取。主要运用的工具是 [xgeocoding 软件](http://www.gpsspg.com/xgeocoding/download/) ，详细步骤参见正文。

最后，我找到 11 项满足条件的、中国的世界遗产。它们是：安徽黄山，湖南武陵源国家级名胜区，西藏布达拉宫，四川峨眉山-乐山风景名胜区，江西庐山风景名胜区，重庆大足石刻，安徽古村落，四川大熊猫栖息地，杭州西湖，中国大运河，土司遗址。如果考虑误差，还有其它 4 项也包括在内。

在进一步讨论中，我提出了一些有意思的思考，可能对大家有启发。期待与大家多交流！





## 1. 背景说明

这是来自虫部落的一道「信息分析」题目 —— 寻找北纬 30° 穿过的世界遗产。

![](http://file.chongbuluo.com/attachment/forum/201708/03/225836ul2ejxefelxxlffe.jpg)

北纬 30° 主要是指北纬三十度上下波动五度所覆盖的范围,北纬30°线贯穿四大文明古国，经过地球上最高的山峰，最深的海沟，最奇怪的湖泊，最瑰丽的山脉，最壮观的大潮，最汹涌的海流.....百慕大三角洲，金字塔之谜......等等数不尽的未解之谜，是一条神奇的纬线。

![img](http://www.51643.com/userfiles/image/2014-4/201441511392513.jpg)

而在中国，318国道几乎就是沿着北纬30度线前行的，途中绝世美景数不胜数。图片分辨率5141*969，有兴趣的话建议下载收藏

关于北纬30°的专题纪录片也有不少，其中以 YouTube 上的发现北纬30度尤为出色，这里搬运B站的另一个系列供各位虫友欣赏！

本期的题目也算是部分继承上一期有关世界遗产的主题，虽然可能看似简单，但是问题里面包含的信源搜集、信息整合以及可能见识到的诸多新鲜姿势都会出乎你的意料！

**那么请问在整个地球上，北纬30°所穿过的世界遗产有___________________（至少列出10项，方能更深切地体会其神奇所在）。**



## 2. 分析过程

### 2.1 三种思路

**思路一：**

>  北纬 30°主要是指北纬三十度上下波动五度所覆盖的范围,北纬 30°线贯穿四大文明古国，经过地球上最高的山峰，最深的海沟，最奇怪的湖泊，最瑰丽的山脉，最壮观的大潮，最汹涌的海流.....百慕大三角洲，金字塔之谜......等等数不尽的未解之谜，是一条神奇的纬线。
>
>  关于北纬 30°的专题纪录片也有不少，其中以 YouTube 上的发现北纬 30 度尤为出色，这里搬运 B 站的另一个系列供各位虫友欣赏！

思路：根据这些描述的提示，进行关键词检索世界遗产行列，并利用谷歌地图等进行经纬度检验，并结合北纬 30 的纪录片，利用视频截图（对建筑，景观等关注）进行图像识别（虫部落汇集了很多搜图方式）以及解说词提示，获取满足题意的答案，虽然不全面，但超过 10 个是可以的。

**思路二：**

> 本期的题目也算是部分继承上一期有关世界遗产的主题，虽然可能看似简单，但是问题里面包含的信源搜集、信息整合以及可能见识到的诸多新鲜姿势都会出乎你的意料！ 
>
> 那么请问在整个地球上，北纬 30°所穿过的世界遗产有___________________（至少列出 10 项，方能更深切地体会其神奇在）。

思路：根据这个描述中提到的看似简单这 4 个词，以及题目给的 318 国道的提示，有理由猜测在中国就有足够多的满足这些的世界遗产，这样作者的看似简单性得以体现。所以可以检索中国所拥有的世界遗产（工程量不大），然后逐个验证经纬度即可，便可给出解答。


**思路三：**

根据脑海中的想法认为应该有批量查询经纬度的工具，于是诞生了思路三 —— 借助批量经纬度查询标记工具，批量获取。

**最终我采取了思路三，下面是具体步骤。**

### 2.2 具体步骤

1. [Google 关键词「经纬度查询」 ](https://www.google.com/search?ei=L6TiWt31MoKSjwOdtZ6QDw&q=%E7%BB%8F%E7%BA%AC%E5%BA%A6%E6%9F%A5%E8%AF%A2&oq=%E7%BB%8F%E7%BA%AC%E5%BA%A6%E6%9F%A5%E8%AF%A2&gs_l=psy-ab.3...1218.1218.0.1465.1.1.0.0.0.0.0.0..0.0....0...1c.1.64.psy-ab..1.0.0....0.dc2HOg142d0&search_plus_one=form) ，获得 [网站 gpsspg.com](http://www.gpsspg.com/maps.htm) 。


![ia01reportpic1.jpg](http://cardstatic.openmindclub.com/InfoAnalysis/ia01reportpic1.jpg)
![ia01reportpic4.png](http://cardstatic.openmindclub.com/InfoAnalysis/ia01reportpic4.png)




2. 点击「批量查询」，按提示找到软件 [**XGeocoding**](http://www.gpsspg.com/xgeocoding/download/) 。

![ia01reportpic5.jpg](http://cardstatic.openmindclub.com/InfoAnalysis/ia01reportpic5.jpg)



3. 下载及安装  [**XGeocoding**](http://www.gpsspg.com/xgeocoding/download/) 。

![ia01reportpic6.jpg](http://cardstatic.openmindclub.com/InfoAnalysis/ia01reportpic6.jpg)



4. 安装完成后，注册软件，根据提示配置地图 API 。

![ia01reportpic7.jpg](http://cardstatic.openmindclub.com/InfoAnalysis/ia01reportpic7.jpg)



5. [Google 关键词「世界遗产」](https://www.google.com/search?ei=D6fiWv_fMtDQjwO-yp2gDQ&q=%E4%B8%96%E7%95%8C%E9%81%97%E4%BA%A7&search_plus_one=form&oq=%E4%B8%96%E7%95%8C%E9%81%97%E4%BA%A7&gs_l=psy-ab.3...33374.33525.0.33712.2.2.0.0.0.0.0.0..0.0....0...1c.1.64.psy-ab..2.0.0....0.m2v2oxNWbSU)  ，获取[「世界遗产」维基列表](https://zh.wikipedia.org/wiki/%E4%B8%96%E7%95%8C%E9%81%97%E4%BA%A7) 。

![ia01reportpic8.jpg](http://cardstatic.openmindclub.com/InfoAnalysis/ia01reportpic8.jpg)

![ia01reportpic9.jpg](http://cardstatic.openmindclub.com/InfoAnalysis/ia01reportpic9.jpg)

6. 将列表内容整理到 excel 中；导入 Excel 表格数据到软件 XGeocoding 中。

![ia01reportpic10.jpg](http://cardstatic.openmindclub.com/InfoAnalysis/ia01reportpic10.jpg)

![ia01reportpic11.jpg](http://cardstatic.openmindclub.com/InfoAnalysis/ia01reportpic11.jpg)

7. 导出结果到 Excel 表格中，即可查找满足条件的世界遗产。

![ia01reportpic12.jpg](http://cardstatic.openmindclub.com/InfoAnalysis/ia01reportpic12.jpg)



## 3. 主要结论

~ 此组块重点：呈现明确、清晰的结论。

以下给出满足条件、中国的世界遗产，共 11 项：

安徽黄山，湖南武陵源国家级名胜区，西藏布达拉宫，四川峨眉山-乐山风景名胜区，江西庐山风景名胜区，重庆大足石刻，安徽古村落，四川大熊猫栖息地，杭州西湖，中国大运河，土司遗址。

中国还有 4 项世界遗产接近北纬 30，均为北纬 31 点几，考虑各种误差，可以将它们列入北纬 30，分别是湖北神农架，四川青城山和都江堰，苏州古典园林，明显陵。



## 4. 进一步讨论



### 4.1 对结论的讨论

- 上述求解答案是客观事实，除非依赖的软件 XGeocoding 数据库存在问题，答案才可能有误。


- 根据表格导出结果，可以轻松、批量获取世界各地符合条件的世界遗产。

### 4.2 可优化的环节

思路三检索过程：整理世界遗产 Excel 花了不少时间。

考虑更多可能优化方案：

- 在世界遗产评选查看是否可批量下载。
- 在 Google 中用检索式检索是否有前人整理好的资料。检索式为`filetype:xls 世界遗产` 、`filetype:csv 世界遗产`、`filetype:xls World Heritage data` 、`filetype:csv World Heritage data` 
- 在 GitHub 中检索是否有开放数据集、API 、开源库。

### 4.3 收获：建立工具思维

前述思路一、二显然也能找到相应遗产，但思路三与思路一，二相比，无论是信息获取效率、获取精度都高很多。

反思获取思路三最关键因素 —— 想到有批量标记经纬度的工具，最终也找到合适工具。未来求解类似问题时，也可以多想想能否找到合适的工具。

工具最重要的作用：批量解决问题、获取精确解。工具可以批量解决问题，帮助人节省大量体力活；工具没有记忆负担，能储存、计算海量数据，即使大批量处理，也不容易失误。如果希望获得更精确、细致的答案，可以寻找工具帮助。

编程正有这样的好处，因此又推演出一个思路：GitHub 上是否存在开放库，可以直接调用。

### 4.4 收获：把问题推向无穷

这里可能有一个比较巧妙的思考方式（反常识点），把问题推向无穷。例如，本次分析只要求找到 10 项符合条件的遗产，但如果要精确找到世界上所有符合条件的遗产，应该怎么找？

当问题定位到这里时，很容易想到：

- 世界文化遗产有严格审核标准，数量有限，可以穷尽。
- 如何找到所有遗产的经纬度呢？是否有批量标记的网站？此时很容易推理：世界遗产作为重要景点，大型地图软件应该都有标识。如果能找到标记软件，那就太棒了。



## 5. 参考文献

- [xGeocoding 下载 — GPSspg](http://www.gpsspg.com/xgeocoding/download/)
- [世界遗产 - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/%E4%B8%96%E7%95%8C%E9%81%97%E4%BA%A7)
- 阳老师也曾提到「批量解决问题」的方法 [行动派 - 阳志平的网志](http://www.yangzhiping.com/psy/YangQ&A-Implementation-intention.html) 

## changelog

- 180427 xx 起草，完成初稿


