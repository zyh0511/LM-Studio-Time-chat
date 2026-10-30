# LM-Studio-Time-chat
A Python CLI chat script for LM Studio with real-time clock injection and conversation memory.

# 本地大模型·时间感知与长期记忆聊天脚本

这是一个基于 Python 的轻量级脚本，专为 [LM Studio](https://lmstudio.ai/) 本地大模型打造。
它解决了本地 AI 没有时间观念和长期记忆的痛点。

## 特性
- 实时时间感知：每次对话都会自动注入当前的系统时间（北京时间）。
- 长期上下文记忆：自带 Context 列表，能记住你们之前的聊天内容。
- 沉浸式 CLI 聊天：就像玩文字游戏一样，在终端里直接对话。

## 🚀 使用方法
1. 确保已安装 Python (推荐 3.10+)。
2. 安装依赖：`pip install requests`
3. 打开 LM Studio，加载你的模型，开启 Local Server (端口 1234)。
4. 修改脚本中的 `MODEL_NAME` 为你 LM Studio 里的模型 ID。
5. 运行脚本：`python TimeChat.py`

## ⚠️ 注意事项
- 如果显存不够，聊太久可能会卡顿。你可以关闭程序重新运行，这样上下文就会被清空。
- 输入 `quit` 或 `exit` 可以退出。