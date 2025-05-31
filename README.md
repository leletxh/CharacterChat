# 智械 - 使用说明与协议文档

> 在使用本软件或进行二次开发前，请认真阅读以下内容。

---

## 🖊软件简介

**智械**是一款AI与真实或虚拟角色聊天的软件。支持语音输入、AI生成回答、声线克隆音频输出，并允许角色切换和模型替换。

---

## 💻使用的开源技术栈

| 项目名称       |      功能用途      | 许可证类型           |
| -------------- | :----------------: | -------------------- |
| GPT-SoVITS     |  语音合成（TTS）   | MIT                  |
| FFmpeg         | 音频格式转换与处理 | LGPL-3.0（动态调用） |
| ReaLTaiizor    |   UI界面美化组件   | MIT                  |
| OpenAI-whisper |      语音识别      | MIT                  |

---

## 📄本软件使用的许可证

本项目中由我编写的所有代码均采用 [MIT License](https://opensource.org/licenses/MIT)，你可以自由地使用、修改和分发代码，只要你保留原始的版权声明和许可声明。 

---

## ⚠️ 使用限制条款

1. ✅ 允许二次开发，允许商业用途  
2. ❌ 不允许以任何形式售卖、收费服务、收费课程等盈利性行为  
3. ❌ 不得用于血腥、暴力、色情、18+等内容  
4. ✅ 鼓励学习、研究和非盈利使用  

---

## 📄 第三方依赖许可证说明

本项目依赖以下开源项目，请遵守其原始许可条款：

- **GPT-SoVITS**: [MIT License](https://github.com/fishaudio/GPT-SoVITS/blob/main/LICENSE) 
- **FFmpeg**: [LGPL-3.0 License](https://www.ffmpeg.org/legal.html)（仅动态调用） 
- **ReaLTaiizor**: [MIT License](https://github.com/taizixiong/ReaLTaiizor/blob/master/LICENSE) 
- **OpenAI-whisper**: [MIT License](https://github.com/taizixiong/ReaLTaiizor/blob/master/LICENSE) 

---

## 📝 使用说明

### 基础说明

#### 启动程序📁

双击启动`启动器.exe`这个程序集成了许多功能

当然你也可以直接双击`run.exe`打开主程序或`run2.exe`打开模型管理

但是如果你手动启动，请你手动打开页面

#### 填入密钥🔑

本程序默认使用了[API Keys | OpenRouter](https://openrouter.ai/settings/keys)作为AI提供，免费用户允许每天调用免费模型50次，充值10学分即可调用1000次

请你跟着程序的指引步骤一步一步获取密钥（你可以注册多个账号）

### 进阶说明

在`config.json`你可以手动编辑主程序的配置文件

在`/model/config.json`你可以手动编辑角色，可以参考`//<number>`里面的注释

文件夹`model`内文件全部压缩成zip即可在主程序的模型管理快速导入

## 📄 版权声明

© 2025 leletxh | 保留所有权利
