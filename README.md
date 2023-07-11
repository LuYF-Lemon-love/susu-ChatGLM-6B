# susu-ChatGLM2-6B

如何对 ChatGLM2-6B 进行微调。

## 介绍

[ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B) 是一个开源的、支持中英双语的对话语言模型，基于 General Language Model (GLM) 架构，具有 62 亿参数。结合模型量化技术，用户可以在消费级的显卡上进行本地部署（INT4 量化级别下最低只需 6GB 显存）。 ChatGLM-6B 使用了和 ChatGPT 相似的技术，针对中文问答和对话进行了优化。经过约 1T 标识符的中英双语训练，辅以监督微调、反馈自助、人类反馈强化学习等技术的加持，62 亿参数的 ChatGLM-6B 已经能生成相当符合人类偏好的回答。

[2023.06.25]二代模型 ChatGLM2-6B 模型开源，更强大的性能（MMLU [+23%]、C-Eval [+33%]、GSM8K [+571%] ）、更长的上下文（2K扩展到8K）、更高效的推理（推理速度提升42%）、更开放的开源协议。

## 参考

[1] [ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B)

[2] [ChatGLM-6B博客](https://chatglm.cn/blog)

[3] [ChatGLM2-6B](https://github.com/THUDM/ChatGLM2-6B)