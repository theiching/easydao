# 🤝 贡献指南 | Contribution Guide

感谢你对本项目的兴趣！我们欢迎任何形式的贡献，包括添加新书籍、改进元数据、优化工具脚本等。

Thank you for your interest in this project! We welcome all forms of contributions, including adding new books, improving metadata, and enhancing tool scripts.

---

## 📘 如何贡献书籍 | How to Contribute Books

1. 请将书籍放入对应语言目录（如 `zh/`、`en/`）
2. 按照分类结构创建子目录（如 `哲学/道德经/`）
3. 在书籍目录下按格式分类（如 `epub/`, `pdf/`）
4. 文件命名建议统一格式：`bookname_v1.0.epub`

---

## 🧾 元数据更新 | Metadata Updates

请在 `metadata/booklist.json` 中添加新书的信息，格式如下：

```json
{
  "zh": {
    "哲学": {
      "道德经": {
        "author": "老子",
        "tags": ["道家", "哲学"],
        "formats": ["epub", "pdf"],
        "cover": "assets/covers/daodejing.jpg"
      }
    }
  }
}