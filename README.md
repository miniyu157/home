<img src="./assets/favicon.png" align="right" alt="Logo" width="120" />

# Yumeka's Home

简约可爱的个人主页 🐰✨ [点此预览](https://yumeka.blog/)

[![MIT License](https://img.shields.io/badge/License-MIT-pink.svg?style=flat-square)](./LICENSE)
![Vanilla JS](https://img.shields.io/badge/JavaScript-Vanilla-yellow?logo=javascript&style=flat-square)
![No Build](https://img.shields.io/badge/Build-None-success.svg?style=flat-square)

## ✨ 快速开始

1. 下载本仓库
2. 修改 index.html 中的 siteData 内容
3. 通过 GitHub Pages 或任何静态托管平台发布
4. 图标库由 Font Awesome 驱动, 可以使用 fa-xxx 使用图标

**个人化信息分离到 siteData 中, 以下为数据结构概览**

```javascript
const siteData = {
    // 标题、头像与 ID 等基础信息
    profile: {
        title: "Yumeka の 主页",
        avatar: "./assets/avatar.jpg",
        aliases: [
            { label: "@ID", tooltip: "详细说明", copy: "复制内容" }
        ]
    },
    // MBTI/特质标签 bio
    about: {
        heading: "关于我",
        headingIcon: "fa-solid fa-address-card text-purple-400",
        traits: [
            { icon: "fa-solid fa-heart", color: "bg-pink-400", tooltip: "特质描述" }
        ],
        bio: "支持 内嵌 HTML 的自我介绍...",
        tags: [
            { text: "标签名", copy: "点击复制的内容", color: "Tailwind 颜色类" }
        ]
    },
    // 传送门
    portals: {
        heading: "传送门",
        headingIcon: "fa-solid fa-door-open text-pink-400",
        items: [
            { title: "项目名", desc: "简介", url: "链接", icon: "图标类", bg: "背景渐变" }
        ]
    },
    // 底部图标按钮
    contact: {
        heading: "找到我",
        headingIcon: "fa-solid fa-paper-plane text-sky-400",
        links: [
            { icon: "fa-brands fa-github", url: "链接", isCopy: false }
        ]
    }
};
```
