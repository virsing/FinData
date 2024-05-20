# FinData
Record financial LLM datasets

## Pretrain Data
1. [TigerBot](https://github.com/TigerResearch/TigerBot)

|data|language|num|time|link|comment
|:-:|:-:|:-:|:-:|:-:|:-:|
|金融-研报|zh|20000|2022-09-30 至 2023-05-19|[hf](https://huggingface.co/datasets/TigerResearch/tigerbot-research-plugin)|TigerBot外部数据源，抽取后按段落保存
|金融-财报|zh|2500|2022-02-28 至 2023-05-10|[hf](https://huggingface.co/datasets/TigerResearch/tigerbot-earning-plugin)|TigerBot外部数据源，抽取后按段落保存


2. [BBT-FinCorpus](https://github.com/ssymmetry/BBT-FinCUGE-Applications)  
目前开源了该语料库的base版和large版，分别包含每种语料各4GB和16GB，如需使用，请发送邮件至model@ssymmetry.com 标题为BBT-FinCorpus-{base or large}申请，内容中说明身份、所属机构和用途

|data|language|raw size|size|comment
|:-:|:-:|:-:|:-:|:-:|
|上市公司公告|zh|2TB|105GB|过去二十年,中国所有上市公司公告，原始数据为 PDF 格式
|研究报告|zh|1TB|11GB|由券商、投行等投资机构发布的针对宏观经济、板块、行业和个股的研究报告，分析研究对象的现状并展望其未来发展趋势
|财经新闻|zh|-|20GB|财经新闻 从新浪财经，腾讯财经，凤凰财经，36Kr 和虎嗅等网站爬取的过去五年内的财经新闻。
|社交媒体|zh|-|120GB|股吧和雪球网过去二十年内的所有股民和博主发表的帖子


3. [Duxiaoman-DI/XuanYuan](https://github.com/Duxiaoman-DI/XuanYuan)  
本次开源高质量中文金融数据集FinCorpus，语料大小约60G，主要构成如下：

|文件名|数据类别|大小|link|comment
|:-:|:-:|:-:|:-:|:-:|	
announcement_data.jsonl|	上市公司公告|	20G|[hf](https://huggingface.co/datasets/Duxiaoman-DI/FinCorpus)|上市公司公告
fin_news_data.jsonl|	金融资讯/新闻	|30G|[hf](https://huggingface.co/datasets/Duxiaoman-DI/FinCorpus)|金融资讯/新闻
fin_articles_data.jsonl	|金融资讯/新闻	|10G|[hf](https://huggingface.co/datasets/Duxiaoman-DI/FinCorpus)|金融资讯/新闻
fin_exam.jsonl|	金融试题	|370M|[hf](https://huggingface.co/datasets/Duxiaoman-DI/FinCorpus)|金融试题

4. [Tushare数据开放社区][官网](https://tushare.pro/)  [github](https://github.com/waditu/tushare)
免费提供各类金融数据api, 助力行业和量化研究, 如股票、基金、期货、数字货币等行情数据，公司财务、基金经理等基本面数据。是一个全面的金融大数据平台。
    - 资讯类：包括新浪财经、东方财富、同花顺、云财经、华尔街见闻。
    - 专业类：包含股票、基金、期货、债券、外汇、行业大数据等，同时包括了数字货币行情等区块链数据的全数据品类。

5. [FinNLP](https://github.com/AI4Finance-Foundation/FinNLP)、[Doc](https://ai4finance-foundation.github.io/FinNLP/zh/)  
  AI4Finance开源的金融数据api平台，类别非常全面，包括新闻、社交媒体、公司公告、趋势、数据集。

## Finetune Data
1. [Yayi](https://huggingface.co/datasets/wenge-research/yayi_domain_subset)

|data|language|num|size|link|comment
|:-:|:-:|:-:|:-:|:-:|:-:|
|雅意-金融sft数据|zh|99,420|95.1MB|[hf](https://huggingface.co/datasets/wenge-research/yayi_domain_subset)|根据金融新闻事件构造而成

2. [PIXIU](https://github.com/The-FinAI/PIXIU/tree/main)（本项目收集了大量开源金融sft数据）

|data|language|num|link|comment
|:-:|:-:|:-:|:-:|:-:|
|PIXIU-金融sft数据|zh & en|-|[hf](https://huggingface.co/TheFinAI)|各种开源金融sft数据


## RLHF Data
