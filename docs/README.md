# Kashgari4j

kashgari for Java.

Kashgari 是一个极简且强大的 `NLP` 框架，可用于文本分类和标注的学习，研究及部署上线。 

方便易用 `Kashgari` 提供了简洁统一的 API 和完善的文档，使其非常方便易用。 
内置迁移学习模块 `Kashgari` 通过提供 `BertEmbedding`, `GPT2Embedding`，`WordEmbedding` 等特征提取类，方便利用预训练语言模型实现迁移学习。 
易扩展 `Kashgari` 提供简便的接口和继承关系，自行扩展新的模型结构非常方便。  
可用于生产 通过把 `Kashgari` 模型导出为 `SavedModel` 格式，可以使用 `TensorFlow Serving` 模块提供服务，直接在线上环境使用。 

- 为 学术研究者 提供易于实验的环境，可快速验证理论。  
- 为 NLP初学者 提供易于学习模仿的生产级别工程。 
- 为 NLP工作者 提供快速搭建文本分类、文本标注的框架，简化日常工作流程。 

### 参考
[kashgari](https://github.com/BrikerMan/Kashgari/) Python SDK.  
[kashgari 中文文档 ](https://kashgari-zh.bmio.net/) 