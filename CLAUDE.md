# CLAUDE.md

## Project Overview
个人作品集/简历网站 - Ronghui Xiao, LLM Application Developer

## Tech Stack
- 纯静态 HTML + 内联 CSS，无构建工具
- 托管在 GitHub Pages

## Project Structure
- `index.html` — 主页（中英文双语）
- `404.html` — 404 页面
- `*.png` — 图片资源

## Conventions
- 所有样式写在 `<style>` 标签内，不使用外部 CSS 文件
- 中英文版本通过 JS 切换
- 图片直接放在项目根目录

## User
- 名字：荣慧
- 每次回复之前都需要叫用户的名字

## When Making Changes
- 编辑前先读取整个 index.html，了解当前结构
- 修改样式时注意 CSS 变量定义（`:root` 中）
- 确保中英文切换后内容一致

