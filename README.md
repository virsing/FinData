# FinData
Record financial LLM datasets

## Pretrain Data
1. [TigerBot](https://github.com/TigerResearch/TigerBot)

|data|language|num|time|link|comment
|:-:|:-:|:-:|:-:|:-:|:-:|
|金融-研报|zh|20000|2022-09-30 至 2023-05-19|[hf](https://huggingface.co/datasets/TigerResearch/tigerbot-research-plugin)|TigerBot外部数据源，抽取后按段落保存
|金融-财报|zh|2500|2022-02-28 至 2023-05-10|[hf](https://huggingface.co/datasets/TigerResearch/tigerbot-earning-plugin)|TigerBot外部数据源，抽取后按段落保存

2. [BBT-FinCorpus](https://github.com/ssymmetry/BBT-FinCUGE-Applications)

|data|language|raw size|size|link|comment
|:-:|:-:|:-:|:-:|:-:|:-:|
|上市公司公告|zh|2TB|105GB||过去二十年,中国所有上市公司公告，原始数据为 PDF 格式
|研究报告|zh|1TB|11GB||由券商、投行等投资机构发布的针对宏观经济、板块、行业和个股的研究报告，分析研究对象的现状并展望其未来发展趋势
|财经新闻|zh|-|20GB||财经新闻 从新浪财经，腾讯财经，凤凰财经，36Kr 和虎嗅等网站爬取的过去五年内的财经新闻。
|社交媒体|zh|-|120GB||股吧和雪球网过去二十年内的所有股民和博主发表的帖子

目前开源了该语料库的base版和large版，分别包含每种语料各4GB和16GB，如需使用，请发送邮件至model@ssymmetry.com 标题为BBT-FinCorpus-{base or large}申请，内容中说明身份、所属机构和用途

## Finetune Data

