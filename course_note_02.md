# 书生·浦语大模型实战营第二期培训笔记
# 第二课：轻松玩转书生·浦语大模型趣味 Demo


## 官方相关课件：
- 课程文档：https://github.com/InternLM/Tutorial/blob/camp2/helloworld/hello_world.md
- 课程视频：https://www.bilibili.com/video/BV1AH4y1H78d/

## 课程概述
- **课程目标**: 掌握书生·浦语大模型的基础知识，学习如何搭建环境、下载模型以及进行模型推理。
- **主要内容**:
  - 介绍书生·浦语大模型的背景和特点。
  - 演示如何搭建适合大模型运行的环境。
  - 指导如何下载和使用书生·浦语大模型。
  - 通过实际操作演示模型推理过程。

## 环境搭建
- **环境配置**:
  - 使用`studio-conda`命令快速配置环境，或手动通过`conda`安装所需库。
  - 配置环境变量，如`HF_ENDPOINT`，以使用镜像站点加速下载。

## 模型下载
- **官方教程**:
  - 通过`modelscope.hub.snapshot_download`或`huggingface_hub`库下载模型。
  - 设置环境变量`HF_ENDPOINT`以使用huggingface镜像站点。
- **注意事项**:
  - 确认模型下载路径，避免下载到默认的缓存目录。
  - 使用`ln -s`创建软链接，指向模型的实际存储位置。

## 模型推理
- **代码示例**:
  - 使用`transformers`库中的`AutoTokenizer`和`AutoModelForCausalLM`进行模型加载和推理。
  - 设置模型的`device_map`以使用GPU资源。
  - 通过循环调用`stream_chat`方法进行交互式对话。

## 避坑指南
- **环境配置**:
  - 确保`studio-conda`命令正确执行，避免环境变量配置错误。
- **模型下载**:
  - 检查模型文件是否存在于指定路径，避免因路径错误导致推理失败。
- **模型推理**:
  - 确保输入文本格式正确，避免因格式问题导致模型输出异常。
