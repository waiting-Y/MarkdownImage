# MarkdownImage
Github+picGo搭建图床
1. GitHub创建仓库，必须是public的
2. 右上角账号头像 → setting → Developer Settings → Personal access tokens (classic) → Generate new token (classic)
3. 设置名字、有效期
4. 勾选repo
5. picGo,设置仓库名（如https://github.com/waiting-Y/MarkdownImage）
6. 设置分支名，必须为 main（否则默认使用master分支，而现在github创建的默认分支名为main）
7. 设置自定义域名：https://cdn.jsdelivr.net/gh/[github用户名]/[仓库名]@main（如 https://cdn.jsdelivr.net/gh/waiting-Y/MarkdownImage@main）
