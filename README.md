# Targeted-ad-push-system(定向广告推送系统)

## 1. 简介
本课题主要研究如何通过对网络社区的用户进行行为分析，借助数据挖掘技术实现网络广告的定向投放，增强网络广告的传播效果。课题要求编写网络爬虫从百度贴吧收集用户相关数据并进行相应预处理工作，设计相关模型，借助自然语言处理的算法，对用户进行聚类分析，进而对各类用户的兴趣点进行分析；设计有效算法对新用户进行分类；实现根据用户上网的活跃时段及关注内容自动定向投放网络广告的功能。

## 2. 创建scrapy爬虫
![scrapy爬虫框架图](https://images2015.cnblogs.com/blog/931154/201703/931154-20170314141524729-978666187.png "scrapy爬虫框架图")

* **创建名为CrawlTieba的爬虫**
```
D:\> cd D:\mfiles\Python_files\Targeted-ad-push-system
D:\mfiles\Python_files\Targeted-ad-push-system> python -m scrapy startproject CrawlTieba
D:\mfiles\Python_files\Targeted-ad-push-system> cd .\CrawlTieba
D:\mfiles\Python_files\Targeted-ad-push-system\CrawlTieba> python -m scrapy genspider Tieba tieba.baidu.com
```


