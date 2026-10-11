# tech-notes

技术书精读笔记：性能 · 分布式 · 网络。用 Obsidian 打开本文件夹即可。

## 目录结构

```
books/      每本书一个文件夹，README 是章节索引（读到哪、每章核心结论、链接到概念笔记）
concepts/   概念笔记，一个概念一个文件，跨书共享（例：Little 定律、EWMA）
interview/  面试题自测，按主题归类，答案链接到概念笔记
templates/  笔记模板
```

## 约定

- **一个概念一条笔记**，放 `concepts/`，文件名用「中文名 英文名」，例如 `负载 load average.md`
- **中英文术语都写**，方便以后用任意一个词搜索
- **用自己的话写**，不抄原文
- 每条笔记带标签：`#书名` `#主题` `#面试`
- 概念之间用 `[[双链]]` 关联；章节索引也用双链指向概念笔记
- 新建概念笔记时从 `templates/概念笔记.md` 复制

## 书单

- [性能之巅（第2版）](books/性能之巅/README.md)
- [DDIA（第1版）](books/DDIA/README.md)
- [TCP/IP 详解 卷1](books/TCP-IP详解卷1/README.md)
