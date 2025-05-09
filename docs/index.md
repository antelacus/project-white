# 英国礼品销售公司客户与商品分析：数据驱动的运营改进策略

这是一个完整的数据分析项目，基于英国一家礼品销售公司两年内的真实交易数据，旨在通过探索性分析、客户建模和销售预测，为业务运营提出改进建议。

📊 **技术栈：**
- 数据存储：PostgreSQL
- 分析工具：Python, Jupyter Notebook
- 可视化：Matplotlib, Seaborn
- 模型方法：RFM 模型、Cohort 留存分析、SARIMAX 时间序列预测

---

## 📘 报告导航

### 📑 报告目录
- [分析方法与数据准备](methodology.md)
- [建模方法](modeling.md)
- [客户分析](customer-analysis.md)
- [商品分析](product-analysis.md)
- [结论与建议](conclusion.md)

### 📁 附件下载

- [在 GitHub 上查看源代码](https://github.com/antelacus/project-white/blob/main/Project_White.ipynb)
- [通过 nbviewer 在线阅读](https://nbviewer.org/github/antelacus/project-white/blob/main/Project_White.ipynb)
- [PDF报告](https://github.com/antelacus/project-white/blob/main/Project_White.pdf)
- [SQL语句](https://github.com/antelacus/project-white/blob/main/SQL_statements.pdf)

---

## 🔍 项目亮点

### 📦 客户分析（Customer Analysis）
- 利用 RFM 模型对客户价值进行评分
- 使用 Cohort 分析预测客户流失
- 挖掘“潜力客户”、“忠诚客户”和“需要唤醒客户”群体

### 🛍 商品分析（Product Analysis）
- 分析商品销售集中度、价格结构与趋势
- 构建 SARIMAX 模型进行季节性销售预测
- 提出库存优化与促销策略建议

---

## 📁 项目结构

```
project-white/
├── docs/                      # GitHub Pages 页面内容
├── Project_White.ipynb        # 分析用 Jupyter Notebook
├── Project_White.pdf          # 分析报告 PDF 版本
├── SQL_statements.pdf         # 数据处理用 SQL 语句
├── .gitignore                 # Git 忽略文件配置
├── requirements.txt           # Python 依赖说明
└── README.md                  # 项目说明（当前文件）
```

---

## 🛠 快速启动

如需在本地运行分析：

```bash
# 克隆仓库
git clone https://github.com/antelacus/project-white.git
cd project-white

# 安装依赖
pip install -r requirements.txt

# 启动 Jupyter
jupyter notebook
```

---

## 📜 数据来源与授权

- 数据集来自 [UCI Machine Learning Repository - Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii)
- 本项目遵循 MIT License 许可协议

---

## 🙋‍♂️ 作者

项目由 [@antelacus](https://github.com/antelacus) 制作，用于数据分析能力展示与公开分享。如有建议欢迎反馈或交流！

---
