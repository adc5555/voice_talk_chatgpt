# 前言

基于Gradio开发的ChatGPT聊天应用，可以文字 或 语音对话，发送的音频通过OpenAI的STT转文本后，再通过ChatGPT生成回复，回复的内容通过OpenAI TTS合成后返回并自动播放，实现语音聊天功能。  

# 使用

在线体验：[https://huggingface.co/spaces/Ikaros521/voice_talk_chatgpt](https://huggingface.co/spaces/Ikaros521/voice_talk_chatgpt)  

安装Python，个人推荐3.10  
安装依赖：`pip install -r requirements.txt`  
运行程序：`python app.py`  
浏览器访问（端口不一定固定，看具体日志输出）：`http://localhost:7860/`  
打开页面后，进入`配置页`完成基础配置后，即可返回`对话页`进行聊天。  

# 效果图
![0 0_}Y(6FS6NE5WZ64T2L L](https://github.com/Ikaros-521/voice_talk_chatgpt/assets/40910637/1f8620a6-5575-4694-83a2-556f118da6df)

![image](https://github.com/Ikaros-521/voice_talk_chatgpt/assets/40910637/e3a72719-863f-4622-a102-5afd643f5c40)
