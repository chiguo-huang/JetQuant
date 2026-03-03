# JetQuant – Quant Module (MVP-Quant)

本模块专注于 **模型量化**，位于 `quant/` 文件夹。  
开发分支：`mvp-quant`  
目标：完成从浮点模型到量化模型的闭环流程。

---

文件结构如下：
```
Root
    quant/  # 量化工作区域
        __init__.py
        core/         # 入口API
        examples/     # 具体量化的模型
        nn_models/    # 量化的模块
        quantization/ # 量化方法
        scripts/      # 功能脚本
        utils/        # 工具函数
```