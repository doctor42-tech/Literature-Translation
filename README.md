# Literature-Translation
利用DeepSeek翻译英文文献摘要（会计学顶刊）

## 项目描述
科研文献浩如烟海，阅读英文顶刊文献对于了解学术界前沿动态，把握研究方向具有重要意义。本项目旨在为会计学研究者提供一个便利的文献翻译工具，方便研究者对英文文献进行阅读。该项目以Python为平台，以API的形式对DeepSeek进行调用，能够实现对学术期刊论文摘要的批量化快速翻译与导出。

## 功能特性
1.目前版本支持对doc以及docx文件的读取，后续版本会更新对txt,PDF以及Markdown等格式的支持  
2.基于DeepSeek-v3模型的精准文献翻译  
3.支持多种格式译文导出  
4.支持通过提示词（Prompt）微调实现其他领域批量化文本翻译  

## 使用指南
### 准备工作
1.确保在本地计算机正确安装了python程序  
2.在python终端对"docx"以及"openai"两个模组进行安装, 其中"docx"确保程序能够对word文档进行处理；"openai"是调用DeepSeek的必要组件      
3.点击本项目主页右上角绿色"code"按钮，将本项目克隆至本地   
4.注册DeepSeek账户，并通过官方链接(https://platform.deepseek.com/api_keys) 申请API key.  

### 操作指引
本项目是核心是函数translate_abstra。


