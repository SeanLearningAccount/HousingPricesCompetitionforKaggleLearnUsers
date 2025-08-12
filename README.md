# Housing Prices Competition for Kaggle Learn Users

# 房价预测项目

## 项目简介：

本项目基于 Kaggle 平台的 Home Data for ML Course 竞赛，旨在通过机器学习模型预测爱荷华州艾姆斯市（Ames, Iowa）房屋的销售价格。该数据集包含多种描述房屋特征的变量（如房间数量、建筑年份、地块面积等），需要根据这些特征构建回归模型进行价格预测。

## 实现步骤
1. 导入库与加载数据：
* 使用 Pandas 读取数据
* 检查缺失值并统计每个特征的缺失数量
2. 数据探索：
* 输出数据类型与基本信息
* 使用 matplotlib 和 seaborn 可视化分布
3. 数据清洗：
* 处理缺失值（填充或删除）
* 转换数据类型
4. 特征工程：
* 选择与目标高度相关的特征
* 对类别特征进行独热编码（One-Hot Encoding）
5. 模型训练：
* 使用随机森林回归模型（RandomForestRegressor）
* 通过交叉验证优化超参数
6. 预测与提交：
* 对 test.csv 进行预测
* 生成 submission.csv 提交至 Kaggle

   
##### 项目最高得分：14518.32534
