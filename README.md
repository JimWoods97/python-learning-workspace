# Python Learning Workspace
> 学习路线：Python基础语法 → FastAPI后端开发 → Docker容器化 → RAG私有知识库（LLM应用作品集项目）

## 📁 仓库目录说明
python-learning-workspace/
├── day100_exercises/         # Python-100-Days 基础练习（Day1~Day20）
│   ├── week1/                # 第 1 周：Day01 ~ Day10 基础语法练习
│   │   ├── data/             # 练习所用 txt 等数据文件
│   │   └── week1_final/      # 第 1 周综合项目：黑名单校验脚本
│   └── week2/                # 第 2 周：Day11 ~ Day20 Python 进阶练习
│       ├── data/             # 练习数据文件
│       └── week2_final/      # 第 2 周综合项目：文本预处理脚本
├── fastapi_demo/             # 第 3、4 周 FastAPI 接口 Demo + Docker 容器化项目
├── rag_kb/                   # 第 5~8 周 核心作品集项目：RAG 私有文档问答系统
├── notes/                    # 学习笔记、面试复习 Markdown 文档
├── .gitignore                # Git 忽略配置
└── README.md                 # 仓库说明文档

## 🎯 学习目标
1. 夯实Python基础语法、工程编码习惯
2. 掌握FastAPI搭建API服务，学会Docker打包部署
3. 完成RAG私有知识库项目（LLM应用方向作品集，可用于面试展示）

## 🛠️ 环境准备
- Python版本：`3.10+`
- 包管理：使用 `venv` 虚拟环境
- 工具：Git、PyCharm、Docker

## 📌 提交规范（Git Commit）

遵循简易规范，方便后续查看版本记录

- `feat:` 新增练习 / 功能代码
- `fix:` 修复代码 bug
- `docs:` 修改 README、笔记等文档
- `refactor:` 代码重构，不改动功能

## 📚 学习资源

- 基础练习：jackfrued/Python-100-Days
- Web 框架：FastAPI 官方文档
- RAG 项目：LangChain、Chroma、Ollama

## 📝 项目进度

- 初始化仓库目录结构
- 第 1 周：Day01~Day10 Python 基础
- 第 2 周：Day11~Day20 Python 进阶
- 第 3 周：FastAPI 基础
- 第 4 周：Docker 容器化
- 第 5~8 周：RAG 知识库项目开发

### 创建虚拟环境
```bash
# 创建虚拟环境
python -m venv venv

# Windows激活
venv\Scripts\activate

# Mac/Linux激活
source venv/bin/activate

# 安装依赖
pip install -r requirements.txt

