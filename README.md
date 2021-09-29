# LoveTrade_douban

```
在贝叶斯框架(Bayesian framework)下建模并预测不同人群在相亲活动(Love Trade)中对对方的要求 (e.g., 身高)。
```

This repository ~~***will***~~ contain:
* Code for getting observed data from [douban](https://www.douban.com/), based on python
* **Code for Bayesian model**
* Observed data & Result



## Intro:
不知为什么被豆瓣的算法选中，总是推我一些【相亲】相关的话题。豆瓣的话题类似于论坛，每个人都可以在相亲话题下发帖来找寻自己理想的相亲对象。

通过对话题的观察，发现相亲的过程和交易很像，当对方手里有筹码的时候才能进行更平等的交易。这是可以理解的，当面对一个毫无感情基础的人毋庸置疑需要足够的耐心才能完成整个相亲活动，对方外貌、工作、家庭、性格等诸多因素决定着耐心的tolerance。尽管有人提出了对方的内在品质应该比外在条件更重要，但毫无疑问的是，当通过网络进行筛选潜在约会对象时，外在条件作为最基本的准则是双方接触的关键。

这些以自身条件为相亲活动前提的硬性要求是情感的表象还是形式的解决？如果是前者，相亲披着情感的外衣，是否类似的人群有相似的要求？例如身高、年龄等可以量化的外在条件，是否特定身高的人群期望特定身高的相亲对象？作为一个X年龄 & X身高的个体，选择哪个年龄段 & 身高范围的异性个体能更顺利完成相亲活动？

这项工作基于这些问题，利用贝叶斯框架来进行建模和预测参加相亲活动的个体对另一方条件的期望。

## Method
1. 利用Python获得观察数据
* 基于python[requests包](https://docs.python-requests.org/en/latest/)和[BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)对[豆瓣相亲大会](https://www.douban.com/gallery/topic/51644/)进行检索：以“身高”、“年龄”、“体重”、“年龄”、“学历”、“经济”等关键词为线索进行筛选，保留提供自身条件和对方条件的数据。

2. 贝叶斯框架
* 


**Note.** 此研究仅使用网络上被本人公开的信息，并忽略任何可能指向个人的信息。此工作不发表、不作任何商业用途。

## Reference

Grahl, A., Onat, S., & Büchel, C. (2018). The periaqueductal gray and Bayesian integration in placebo analgesia. Elife, 7, e32930.
[DOI: 10.7554/eLife.32930](https://elifesciences.org/articles/32930)
