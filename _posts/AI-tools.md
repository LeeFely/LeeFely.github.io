---
title: AI_tools
date: 2025-03-24
permalink: /posts/2025/03/ai-tools/
tags:
  - Guidance
  - AI
  - Deep Learning
  - Machine Learning
---
# AI模型概览及工具汇总
阅读完这篇文章后，你应该浏览一下[指导](https://alllink-official.github.io/2024/10/24/Guidance/)，了解我们博客的主要方面。

## AI天花板
1. [OpenAI ChatGPT](https://chatgpt.com/) https://chatgpt.com/
2. [Anthropic Claude](https://claude.ai/) https://claude.ai/
3. [Google Gemini](https://gemini.google.com/app) https://gemini.google.com/app
4. [MetaAI llama](https://www.meta.ai/) https://www.meta.ai/
5. [Microsoft Copilot](https://copilot.microsoft.com/) https://copilot.microsoft.com/
6. [xAI Grok](https://x.ai/) https://x.ai/
7. [Mistral Le Chat](https://chat.mistral.ai/chat) https://chat.mistral.ai/chat
8. [ChatGLM（知谱清言）](https://chatglm.cn/?lang=zh) https://chatglm.cn/?lang=zh
9. [讯飞星火](https://xinghuo.xfyun.cn/) https://xinghuo.xfyun.cn/
10. [天工AI](https://www.tiangong.cn/) https://www.tiangong.cn/
11. [文心一言](https://yiyan.baidu.com/) https://yiyan.baidu.com/
12. [Deepseek](https://www.deepseek.com/) https://www.deepseek.com/

## AI集合工具

> 所有工具均免费开源，无需考虑安全问题

1. ChatAll <br>
   下载链接直达: <br>
   1.1. [Windows](https://github.com/ai-shifu/ChatALL/releases/download/v1.83.108/ChatALL-1.83.108-win-x64.exe) <br>
   1.2. [Mac](https://github.com/ai-shifu/ChatALL/releases/download/v1.83.108/ChatALL-1.83.108-mac-arm64.dmg) <br>
   1.3. [Linux](https://github.com/ai-shifu/ChatALL/releases/download/v1.83.108/ChatALL-1.83.108-linux-amd64.deb)

ChatAll, Chatbox, lobechat, cherry studio功能一样，都是集成各个AI于一体的软件，ChatAll最有用的功能就是可以同时和多个模型一起对话，不需要
每个模型分别对话，一次提问多模型同时作答。还有一个优点就是国内模型只需要登录即可使用，国外模型需要API调用。注意软件都支持中文，如果不适应英语，安装
时请选择简体中文。
![ChatAll](/source/_posts/AITSum/AI1.png)
内置模型如下，根据需要选择自己需要的（不适应安装时请选择中文）
![ChatAll](/source/_posts/AITSum/AI2.png)

2. Chatbox <br>
   下载链接直达 <br>
   2.1. [Windows](https://github.com/Bin-Huang/chatbox/releases/download/v0.10.2/Chatbox.CE-0.10.2-Setup.exe) <br>
   2.2. [Mac](https://github.com/Bin-Huang/chatbox/releases/download/v0.10.2/Chatbox.CE-0.10.2-arm64.dmg) <br>
   2.3. [Linux](https://github.com/Bin-Huang/chatbox/releases/download/v0.10.2/Chatbox.CE-0.10.2-amd64.deb)



3. lobechat（Docker部署）<br>
```bash
docker pull lobehub/lobe-chat
```

4. cherry studio <br>
   下载链接直达 <br>
   4.1. [Windows](https://github.com/kangfenmao/cherry-studio/releases/download/v0.8.23/Cherry-Studio-0.8.23-setup.exe) <br>
   4.2. [Mac](https://github.com/kangfenmao/cherry-studio/releases/download/v0.8.23/Cherry-Studio-0.8.23-arm64.dmg) <br>

5. LM studio <br>
   下载链接直达 <br>
   5.1. [Windows](https://releases.lmstudio.ai/win32/x86/0.3.5/2/LM-Studio-0.3.5-Setup.exe) <br>
   5.2. [Mac](https://releases.lmstudio.ai/darwin/arm64/0.3.5/2/LM-Studio-0.3.5-arm64.dmg) <br>
   5.3. [Linux](https://releases.lmstudio.ai/linux/x86/0.3.5/2/LM_Studio-0.3.5.AppImage)

LM studio, Ollama, AnythingLM, Chat with RTX均是下载开源模型，安装后，载入模型问答无需网络，全部在本地运行，所以对电脑性能有要求，其中
Ollama仅需CPU即可运行，Chat with RTX要求显存（GPU内存）≥8G才能使用。

6. Ollama <br>
   下载链接直达 <br>
   6.1. [Windows](https://ollama.com/download/OllamaSetup.exe) <br>
   6.2. [Mac](https://ollama.com/download/Ollama-darwin.zip) <br>
   6.3. Linux:
```bash
curl -fsSL https://ollama.com/install.sh | sh
```

Ollama安装后在终端运行，没有用户界面（GUI），因为其他软件均在软件本体下载模型，而Ollama需要在[官网](https://ollama.com/search)查看模型，
使用:
```bash 
ollama run 模型名
```
才能安装，例如安装llama3.3：
```bash
ollama run llama3.3
```

7. AnythingLLM <br>
   下载链接直达 <br>
   7.1. [Windows](https://s3.us-west-1.amazonaws.com/public.useanything.com/latest/AnythingLLMDesktop.exe) <br>
   7.2. [Mac](https://s3.us-west-1.amazonaws.com/public.useanything.com/latest/AnythingLLMDesktop-Silicon.dmg) <br>
   7.3. [Linux](https://docs.anythingllm.com/installation-desktop/linux#install-using-the-installer-script)

8. NextChat
   下载链接直达 <br>
   [Windows/Mac](https://github.com/ThinkInAIXYZ/deepchat/releases)
9. Chat with RTX（Nvidia英伟达显卡专属） [下载链接直达](https://us.download.nvidia.com/RTX/ChatWithRTX_Installer_9_24.zip)

