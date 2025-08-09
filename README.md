# chongqing_translator
由四川话微调而成的重庆话（永川区），可翻译成其他现有方言或语言ASR/TTS。

# 项目背景
截止2025年8月9日，由人工及GPT-5证实，已并行检索 Hugging Face、ModelScope、GitHub、OpenSLR、论文与主流开源项目；未找到“标准重庆话”专用的开源 ASR、TTS 或 SpeechLLM 编解码器可直接下载使用。没有发现开源的“重庆话专用”ASR、TTS，或针对重庆话训练的 SpeechLLM encoder/decoder。现有最接近的是“四川话/西南官话”与多方言通用模型，可作为重庆话的微调起点。

最接近、可用与可微调资源的是TeleSpeech-ASR（多方言ASR），覆盖30+方言，明确含四川话；重庆话未单列，但可测试/再训练。Qwen-TTS：已支持四川话音色（未标注重庆话）。可先用四川话音色评估贴近度。

本人是土生土长广东人，精通粤语及四种五邑片区方言，曾在重庆居住，顺便考察重庆话，学习历程达5个月，是本人学习的第6个方言。

# 项目目前进度
如图所示，正在做数据预处理。
![Image text]([https://raw.github.com/yourName/repositpry/master/yourprojectName/img-folder/test.jpg](https://github.com/Chen-Jieteng/chongqing_translator/blob/main/%E6%88%AA%E5%B1%8F2025-08-09%2023.14.36.png))
