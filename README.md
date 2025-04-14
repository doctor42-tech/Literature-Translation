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
### 组件安装
本项目的运行前需要安装"docx"以及"openai"两个模组，其中"docx"确保程序能够对word文档进行处理；"openai"是调用DeepSeek的必要组件。若要安装这两个组件，请在python终端输入如下命令： 
pip install pip install python-docx   
pip install openai  

