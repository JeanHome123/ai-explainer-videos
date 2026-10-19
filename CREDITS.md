# 《常见的 AI token 到底是什么》

60 秒中文科普短片，2026-10-19。

事实来源：
- OpenAI Key concepts / Tokens：https://developers.openai.com/api/docs/concepts#tokens
- OpenAI Tokenizer：https://platform.openai.com/tokenizer
- OpenAI tiktoken：https://github.com/openai/tiktoken
- 分词实测结果保存在 tokenization.json，分别使用 cl100k_base 和 o200k_base。英文块中的前置空格属于该 token 的一部分。

画面：本项目原创 Canvas 动态图解；积木、输入法、书桌都是解释概念的示意，并非真实模型界面或硬件结构。全片聚焦文本 token。多模态输入也可能使用 token 等计量方式，但未在本片展开。

配音：Microsoft Edge TTS，zh-CN-YunxiNeural，合成男声，未克隆真人声音。

声音：本项目用正弦合成与程序噪声制作的原创背景音乐、转场声和低频强调声，没有引用第三方音乐。

字体：Microsoft YaHei 与 Bahnschrift，调用本机 Windows 字体渲染。字体文件只用于本机工程，不作为单独字体产品分发。

制作工具：HeyChengC/wallstreet-explainer，MIT 许可，源版本 920ed1d3b3ecb5997d861902e2719dda6688c0b1；Playwright；FFmpeg；Python；NumPy。

补充说明：输入/输出 token 的价格及细分项目因服务、模型而异；某些模型的输出用量包括不可见的推理 token。实际输入也可能包括系统指令与历史信息。上下文容量不等同于智力或回答质量。本片不列具体价格与窗口数值。
