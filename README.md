# chenjia-q.github.io

> 我的个人技术博客 – 记录数据分析、MySQL 与机器学习的学习与实践

本站基于 [Hexo](https://hexo.io/) 搭建，主题为自定义风格，主要用于整理和分享我在数据科学领域的学习笔记、项目复盘以及踩坑经验。

## 📚 主要内容

- **数据分析**  
  - Python 数据分析（Pandas、NumPy、Matplotlib）  
  - 数据可视化案例（Tableau、Seaborn）  
  - 数据清洗与特征工程实战

- **MySQL**  
  - SQL 基础与进阶查询优化  
  - 索引设计、事务隔离级别  
  - 数据库设计范式与实战建模

- **机器学习**  
  - 监督/无监督学习算法原理与实现  
  - Scikit‑learn 与 XGBoost 应用  
  - 模型评估、调参与部署实践

## 🛠 技术栈

- 静态站点生成器：[Hexo](https://hexo.io/)
- 主题：自定义（基于 [NexT](https://github.com/next-theme/hexo-theme-next) 修改）
- 部署：GitHub Pages
- 评论系统：Giscus / Disqus

## 🚀 本地运行

```bash
# 克隆仓库
git clone https://github.com/chenjia-q/chenjia-q.github.io.git

# 安装依赖
npm install hexo-cli -g
npm install

# 启动本地服务器
hexo clean && hexo generate && hexo server

# 访问 https://chenjia-q.github.io/
