# super-duper-chainsaw
> 数学建模竞赛机器学习/深度学习工具库

## 项目定位
为数学建模竞赛提供可复用的 ML/DL baseline 模型与工具函数，实现快速特征工程、模型训练与结果可视化，助力竞赛中智能算法类问题的高效求解。

## 技术栈
- 机器学习：Scikit-learn, XGBoost, LightGBM, CatBoost
- 深度学习：PyTorch / TensorFlow/Keras
- 数据处理：Pandas, NumPy
- 可视化：Matplotlib, Seaborn, Plotly
- 工具：Optuna（超参数搜索）, SHAP（特征解释）

## 目录结构
﻿├── data/          # 示例数据与数据加载脚本
├── models/        # 分类/回归/聚类/时序预测等模型实现
├── features/      # 特征工程、特征选择工具
├── utils/         # 通用工具函数（评价指标、画图、日志等）
├── examples/      # 完整使用示例（以数模赛题为例）
└── README.md


## 当前进度
- ✅ 仓库初始化
- 🔄 待完成：基础数据预处理脚本
- 🔄 待完成：随机森林/线性回归 baseline 模型
- 🔄 待完成：CNN/LSTM 时序预测模板
- 🔄 待完成：结果可视化与模型解释工具
