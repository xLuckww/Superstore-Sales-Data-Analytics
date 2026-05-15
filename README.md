# 🛒 Superstore Sales — Exploratory Data Analysis

基于零售超市销售数据，从销售趋势、品类表现、区域分布、客户价值到时间序列预测，进行系统性探索分析。

> 本项目为 [Superstore Sales Analysis](https://github.com/SmridhVarma/Superstore-Sales-Analysis) 的个人 EDA 贡献，在原始数据集基础上进行了独立分析和扩展。

---

## 分析维度

| 章节 | 内容 |
|------|------|
| 销售趋势 | 月度趋势 · 年度季节性对比 · 12个月滚动均值 · YoY同比增速 |
| 时间序列分解 | STL 分解（趋势 / 季节性 / 残差）· ADF 平稳性检验 |
| 销售预测 | Prophet 模型整体预测 · 三大品类分别建模 · 误差评估（MAE / RMSE / MAPE） |
| 品类与区域 | 子品类利润排名 · 销售额占比 · 区域热力图 |
| 产品分析 | Top 10 销售额产品 · Top 10 销量产品 · 配送方式分布 |
| 客户分层 | RFM 模型打分 · 六级客户分层 · 各层级品类偏好分析 |
| 相关性分析 | 折扣 vs 利润 · 销售额 vs 利润 · Pearson 显著性检验 |

---

## 技术栈

| 类别 | 工具 |
|------|------|
| 语言 | Python 3 |
| 数据处理 | pandas, numpy |
| 可视化 | matplotlib, seaborn |
| 时间序列 | statsmodels, prophet |
| 统计分析 | scipy |
| 模型评估 | scikit-learn |

---

## 如何运行

**1. 安装依赖**

```bash
pip install pandas numpy matplotlib seaborn statsmodels prophet scikit-learn scipy openpyxl
```

**2. 准备数据**

将 `superstore_sales.xlsx` 放置于项目根目录。

**3. 运行 Notebook**

```bash
jupyter notebook my_EDA.ipynb
```

按顺序执行所有单元格即可。运行后会在当前目录生成 `相关性分析结果.csv`。

---

## 文件结构

```
├── my_EDA.ipynb            # 主分析 Notebook
├── superstore_sales.xlsx   # 原始数据（需自行准备）
└── 相关性分析结果.csv       # 运行后自动生成
```

---

## 作者

xLuck · [GitHub](https://github.com/xLuckww)
