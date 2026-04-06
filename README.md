# 📚 洛谷词典 (Luogu Dictionary)

洛谷社区缩写/术语词典，支持多词典切换与实时搜索。  
项目旨在帮助新手快速理解 OI/ACM 竞赛圈以及洛谷社区的黑话、梗和专业术语。

**在线访问**：[https://luogu-dict.pages.dev](https://luogu-dict.pages.dev)
GitHub Pages：[https://mengtian1120.github.io/luogu-dict/](https://mengtian1120.github.io/luogu-dict/)

## ✨ 功能特点

- 📖 **多词典支持**：可同时管理多个词典文件（如“OI语言”、“算法结构”、“社区文化”等）
- 🔍 **实时搜索**：按缩写或含义快速过滤，高亮匹配内容
- 📱 **响应式设计**：在桌面和移动端均有良好的浏览体验
- 🤝 **社区驱动**：任何人都可以通过 Pull Request 贡献词条

## 🗂️ 词典文件格式

项目通过 `dicts.txt` 定义词典列表，每行一个文件名（如 `OI语言.txt`）。  
每个词典文件为纯文本格式，编码 **UTF-8**，位于 `dicts/` 文件夹下：

```
缩写|解释说明
AC|Accepted / 答案正确，通过题目
WA|Wrong Answer / 答案错误
TLE|Time Limit Exceeded / 运行超时
```

> 注意：每行必须包含且仅一个竖线 `|`，左侧为缩写，右侧为含义。

## 🚀 本地运行

1. 克隆本仓库：
 ```bash
   git clone https://github.com/MengTian1120/luogu-dict.git
   cd luogu-dict
```
2. 使用任意 HTTP 服务器运行（例如 VS Code Live Server、Python HTTP Server）
3. 编辑 `dicts/` 下的 `.txt` 文件或新增词典，同步修改 `dicts.txt` 列表即可生效

## 🤝 如何贡献

欢迎补充词条！流程非常简单：

1. **Fork** 本仓库
2. 在 `dicts/` 文件夹下找到或创建合适的词典文件（格式见上方说明）
3. 按 `缩写|解释` 格式添加新词条
4. 提交 Pull Request，描述你新增的内容

> 不确定词条属于哪个分类？可以新建一个 `.txt` 文件，并在 `dicts.txt` 中添加文件名。

## 📄 许可证

本项目采用 **MIT License** 开源协议，使用、修改、分发时请保留原始版权声明。

## 🙏 致谢

- 所有贡献词条的洛谷社区成员
- 灵感来源于 OI 圈内各种术语整理项目

---

**维护者**：[MengTian1120](https://www.luogu.com.cn/user/2119974)  
欢迎在 [Issues](https://github.com/MengTian1120/luogu-dict/issues) 中提出建议或报告问题。
