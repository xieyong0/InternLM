# 书生·浦语大模型实战营第二期培训笔记
# 第一课：书生·浦语大模型全链路开源开放体系

## 课程概览
- **讲师**: 陈恺，上海人工智能实验室青年科学家
- **主题**: 书生·浦语大模型全链路开源体系
- **视频录屏**: [Bilibili视频链接](https://www.bilibili.com/video/BV1Vx421X72D/)
![image](https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/349bd9a3-03fd-4229-b94b-ae594444af10)


## 书生·浦语大模型介绍
- **发展历史**: 介绍了InternLM2的发展历程，从23年6月份发布1.0版本，不断完善不同量级的LLM模型。
- **全链路开源体系**: 包含数据准备（书生·万卷）、预训练（InternLM-Train）、微调（XTuner）、部署（LMDeploy）、评测（OpenCompass）、应用（LagentAgentLego）等环节。
![image](https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/fe45c67e-ffac-4130-9eee-1080479c03b4)
![image](https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/07577558-263e-4688-88de-f20656b50b74)


## 大模型的发展趋势
- **专用模型**: 针对特定任务设计。
- **通用大模型**: 一个模型应对多种任务、多种模态，如文本、语音、图像等。
  ![image](https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/78214ed0-7978-4447-af0c-b59e84502a2e)


## InternLM2的主要亮点
- **超长上下文支持**: 能够处理长达200k的上下文。
- **综合性能提升**: 在多个维度和基准评估中表现优异。
- **对话和创作体验**: 提供优秀的对话和创作体验。
- **工具调用能力**: 整体升级，支持上传表格进行数据分析和画图展示。
- **数理能力和数据分析**: 实用的数据功能，支持机器学习建模。

## 模型到应用的典型流程
1. **模型选型**: 根据业务需求选择合适的模型。
2. **业务场景分析**: 评估算力和环境交互需求。
3. **参数微调**: 根据场景选择微调形式。
4. **环境交互类型选择**: 构建智能体（agent）。
5. **构建智能体**: 根据需求构建。
6. **模型评测**: 使用OpenCompass等工具进行评测。
7. **模型部署**: 将模型部署到实际应用中。
![image](https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/4d6c3f24-a395-4a64-8027-90b64b48cad0)


## InternLM2技术报告要点
- **预训练**: 包括高质量的32k文本和位置编码外推。
- **监督微调（SFT）**: 提升模型在特定任务上的表现。
- **强化学习（RLHF）**: 基于人类反馈进行优化。
- **条件在线RLHF（COOL RLHF）**: 解决偏好冲突，减少奖励作弊。
- **模型结构**: 在Transformer架构基础上进行改进，提高训练效率和性能。
![image](https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/49c19bb9-31a6-428c-8c9f-8214dec97426)


## 总结
培训第一课详细介绍了书生·浦语大模型的全链路开源体系，强调了大模型在多任务、多模态处理上的能力，以及InternLM2的主要特点和技术亮点。通过这次学习，我们可以更好地理解大模型的应用流程和优化策略，为未来的科技创新和应用打下坚实的基础。
