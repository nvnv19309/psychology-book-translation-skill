# 心理学书籍精翻 Skill

供 Codex 用户翻译自己提供的英文心理学书籍 PDF。它按章建立术语表、生成中文 Markdown 阅读稿，并要求逐页对照原文；对扫描不清、图表缺损或无法确认的译名，留下明确记录。适用于理论、研究方法、临床及大众心理学书籍，但每本书都要依其语境决定最终译法。

核心文件：[翻译 Skill](skills/psychology-book-translation/SKILL.md) · [精选术语参考](skills/psychology-book-translation/references/seed-glossary.md) · [审校指南](skills/psychology-book-translation/references/psychology-translation-guide.md)。

## 安装

在 Codex 对话中调用 `$skill-installer`，并提供以下信息：

> 请从 GitHub 仓库 `nvnv19309/psychology-book-translation-skill` 的 `skills/psychology-book-translation` 路径安装 Skill。

安装器会把该目录中的 `SKILL.md` 和参考文件安装到个人 skills 目录；如没有立即出现在 Skill 列表中，请开始下一轮对话或重启 Codex。已有同名 Skill 的安装器不会直接覆盖，请先自行备份旧版，再更新。也可下载仓库并把 `skills/psychology-book-translation` 整个文件夹放入 Codex 的个人 skills 目录。

## 使用

向 Codex 提供英文 PDF 或可读取的文件路径，例如：

> 使用 `$psychology-book-translation` 翻译这本英文心理学书。请先识别目录和主要理论，建立本书术语表，按章输出中文 Markdown，逐页对照原文并记录问题。图片处理方式请先问我。

默认生成 `中文阅读稿.md`、`全书术语表.md`、`翻译进度.md` 和 `逐页审校记录.md`。用户可指定不同文件名或输出目录。对于长书，逐章完成和续译；「已翻译」不等于「已核对」。精选术语表只是候选参考，不能批量套用到每本书。

## 范围与来源

仓库只有 Skill 指令、精选术语参考和说明；不提供任何书籍 PDF、原书图片、完整译文或从特定教材逐项翻译的 Glossary。Skill 不会自动公开用户的阅读稿。公开传播完整译文或原书图表前，请先确认相应授权；这不妨碍个人阅读用途的翻译。

本项目受 [Cuimao Translator](https://github.com/Cuimao777/cuimao-translator) 的长篇 PDF 分章翻译思路启发，面向心理学概念、研究证据、图表与逐页核对重新编写。仓库内容按 [MIT License](LICENSE) 提供。
