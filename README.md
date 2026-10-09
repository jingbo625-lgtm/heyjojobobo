# JOJOBOBO

AI 作品集静态网站。部署至 GitHub Pages，不依赖 ChatGPT Sites。

## 更新内容

修改 public/content.json 中的文字和 projects 项目列表；数组顺序就是展示顺序。图片和视频放入 public/media，再使用 media/文件名 引用。每次提交 main 分支会自动部署。

首页视频 heroVideo，封面 heroPoster。视频建议 MP4，封面图片建议 WebP/JPG。请勿上传单个超过 100 MB 的文件。删除项目时可同时清理不再引用的素材。

## 首次部署

仓库 Settings → Pages → Source 选择 GitHub Actions。等待 Publish portfolio 工作流完成后，先检查测试地址。通过验收后再设置 www.heyjojobobo.com 自定义域名、修改 GoDaddy DNS 并开启 HTTPS。

## 本地运行

Node.js 22.13 或更新版本。npm install，然后 npm run dev；npm run build 生成 dist。

此版本没有在线编辑或登录后台，修改均通过仓库完成。
