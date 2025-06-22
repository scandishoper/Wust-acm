# WUST ACM Club Website

![](https://img.shields.io/website?url=https%3A%2F%2Fwustacm.scandidreams.top%2F)
![](https://img.shields.io/github/license/wust-acm/club-website)

这是武汉科技大学 ACM 俱乐部的官方网站，用于发布技术博文、俱乐部动态以及维护《武科大 ACMer 生存指北》知识库。

**访问地址**: https://wustacm.scandidreams.top/

## 🚀 项目功能

- **技术博客**：分享算法、编程、竞赛经验等计算机知识
- **俱乐部动态**：发布招新、比赛、讲座等最新活动信息
- **生存指北**：维护面向 Wust ACMer 的实用信息差(Wiki)
- **资源中心**：整理学习路线、竞赛题库、工具推荐等资源

## 🛠️ 技术栈

| 组件     | 技术                                                  |
| :------- | :---------------------------------------------------- |
| 前端框架 | [Vue.js](https://vuejs.org/)                          |
| UI 框架  | [Element Plus](https://element-plus.org/)             |
| 静态生成 | [Vite](https://vitejs.dev/)                           |
| 部署平台 | [GitHub Pages](https://pages.github.com/)             |
| 域名服务 | [Cloudflare](https://www.cloudflare.com/)             |
| 持续集成 | [GitHub Actions](https://github.com/features/actions) |

## 📝 内容贡献

我们欢迎以下类型的贡献：

- 新增/修改技术博文
- 更新俱乐部动态
- 完善《生存指北》内容
- 修复网站问题

### 贡献流程

1. Fork 本仓库
2. 创建新分支 (`git checkout -b feature/new-post`)
3. 添加/修改内容：
   - 博文存放于 `src/posts/`
   - Wiki 内容存放于 `src/wiki/`
   - 动态消息存放于 `src/trends/`
4. 提交变更 (`git commit -m 'Add new post'`)
5. 推送到分支 (`git push origin feature/new-post`)
6. 创建 Pull Request

### 内容规范

- 使用 Markdown 格式编写
- 文件名使用英文短横线分隔
- 包含必要的 Front Matter 元数据：

```markdown
---
title: "文章标题"
author: "作者名"
tags: ["标签1", "标签2"]
---
```

## 🌐 部署流程

网站通过 GitHub Actions 自动部署：

1. 推送到 `main` 分支触发构建
2. 生成静态文件 (`npm run build`)
3. 自动部署到 GitHub Pages
4. 自定义域名通过 CNAME 配置

## 📜 许可证

本项目采用 [MIT 许可证](https://license/)

## 🤝 加入我们

欢迎武汉科技大学同学加入 ACM 俱乐部！通过以下方式联系我们：

- QQ 群：`963401049`
- 线下办公室：计算机学院教三 512 室

## 🙏 致谢

感谢所有为项目做出贡献的俱乐部成员：23，24 级成员

---

**让知识传承，让智慧接力**
WUST ACM Club © 2025
