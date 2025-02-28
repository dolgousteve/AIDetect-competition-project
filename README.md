# AIDetect-competition-project
kaggle平台比赛 Detect AI vs. Human-Generated Images 参赛项目

比赛要求对AI生成图像进行识别检测。给定带标签训练集和不带标签测试集。

该项目有两个版本的代码

V2版本使用efficientnet进行训练与生成。要求配置：torch、transformers、timm、tqdm等

V3版本调用qwen2.5-VL-7b多模态模型API。