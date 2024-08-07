# Awesome LLM functions

<p align="center"><small><b><a href="README-zh.md">English</a> | 中文</b></small></p>

## 目标

大语言模型的函数调用机制（Function calling）对于开发AI Agents来说非常重要，但函数的开发和调试都比较麻烦，互联网也缺少这方面的工具和资源。

本项目旨在创建一个“开箱即用”的共享函数集，并提供一些函数开发相关的资源和技术框架，让开发者可以更容易地将外部函数与大语言模型的API集成起来，实现自己想要的功能。

## 函数列表

点击以下函数查看详情，并复制函数的定义，就可以通过 [ConsoleX.ai](https://console.evalsone.com/)轻松测试函数的调用。

* [天气查询 (get_current_weather)](info/get_current_weather.md)
* [汇率查询 (get_exchange_rate)](info/get_exchange_rate.md)
* [获取Hacker news最新内容 (get_top_hacker_news)](info/get_top_hacker_news.md)
* [生成MidJourney提示语]((info/midjourney_prompt_generator.md)** )
* [快速获取视频内容摘要](info/get_video_summary_transcribe.md)
* [读取PDF文档信息 (get_read_url)](info/read_url.md)
* [查找语言老师 (get_find_teachers)](info/find_teachers.md)
* [获取地理位置坐标 (get_get_coordinates)](info/get_coordinates.md)
* [睡前故事 (get_create_story)](info/create_story.md)

> **Note**
> 以上函数部分通过[Plug2Func](https://consolex.ai/plugins)生成

## 函数开发
* [OpenAI function boilerplate](https://github.com/quentinzhang/OpenAI-function-boilerplate)

## 社区讨论
如果你喜欢OpenFunction项目，并希望为它贡献一份力量，丰富OpenFunction的函数库，可以 [加入Discord服务器](https://discord.gg/z9KtFM62F2) 一起讨论。