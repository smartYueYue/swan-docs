---
title: 设置页面基础信息
header: introduction
nav: book
sidebar: rank_page
---


**1.为什么要进行页面基础信息设置？**
智能小程序被搜索引擎正常收录的前提是Web化，Web化后小程序将以普通网页的形式被爬虫发现和抓取，因此页面基础信息的设置至关重要，能够提升小程序在搜索中的收录和展现结果。
**2. 页面基础信息都包含什么？**
页面基础信息包括标题、摘要、Keywords等信息。这些页面基础信息内容，会影响到小程序在搜索结果页中的呈现方式，需要开发者进行符合搜索要求的设置。
**（1）标题**：能够更加快速洞察页面内容，了解该结果与需求的相关性，通常是用来决定用户点击哪个结果的主要信息。所以，使用高质量的页面标题对小程序来说至关重要。
**（2）摘要**：小程序首页、栏目页、分类页的摘要非常重要，因为有可能在搜索结果中直接被用户看到，影响到用户是否选择点击查看详情：
**（3）Keywords**：小程序开发者给网站某个页面设定的词汇，以便让搜索引擎更好地理解页面价值。keywords代表了小程序主题内容，无论是首页、内页还是栏目页，关键词一般都代表的是当前页面或者栏目内容的主体。开发者根据实际情况设置即可。
开发者可点击并了解[页面基础信息配置方法](https://smartprogram.baidu.com/docs/develop/api/pageinfo/)
> 由于每个页面基础信息和页面内容强相关，建议先通过 swan.request 请求开发者 server ，由开发者 server 返回相关信息，再通过页面基础信息的 API 设置到页面中。