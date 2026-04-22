# 云影视

一个简单的影视播放网站，支持搜索和播放功能。

## 功能特点

- 支持搜索电影/剧集
- 支持播放 M3U8 格式的视频
- 支持多线路切换
- 响应式设计，适配不同屏幕尺寸

## 如何部署到 Pages

### GitHub Pages

1. 将此仓库推送到 GitHub
2. 在仓库设置中，找到 "Pages" 选项
3. 选择 "main" 分支作为源，点击 "Save"
4. 等待部署完成后，即可通过生成的 URL 访问

### Cloudflare Pages

1. 将此仓库推送到 GitHub 或 GitLab
2. 登录 Cloudflare 账号，进入 "Pages" 页面
3. 点击 "Create a project"，选择你的仓库
4. 配置构建设置：
   - Framework preset: `None`
   - Build command: `echo "Build completed"`
   - Build output directory: `./`
5. 点击 "Save and Deploy"
6. 等待部署完成后，即可通过生成的 URL 访问

## 技术栈

- HTML5
- CSS3
- JavaScript
- HLS.js (用于播放 M3U8 格式的视频)

## API 说明

本项目使用了外部 API 接口：
- 搜索接口：`https://api.splayer.top/api/search?wd={关键词}`
- 详情接口：`https://api.splayer.top/api/detail?ids={资源ID}`

## 注意事项

- 本项目仅用于学习和研究目的
- 请确保遵守相关法律法规，不要用于非法用途
- API 接口可能会随时失效，请自行替换为可用的接口
