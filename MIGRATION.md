# 永延君成站点入口迁移

将 yyphic.github.io 首页替换为现有永延君成站点入口，两秒后跳转到 https://jiaoyi-structure-journal.yyphic.chatgpt.site/ 。无脚本环境仍可点击链接或通过 meta refresh 跳转。

现有 `/2023/`、`/archives/`、图片和资源保留，避免旧文章链接失效。新站的后台、文章、身份验证和权限继续由现有站点处理。

这次迁移不把新站的后台或受访问权限控制的内容复制到公开 GitHub Pages。GitHub Pages 为静态托管，不能直接承载现有后台。若未来需要把完整应用迁离 ChatGPT Sites，应另行迁移服务端、数据库和认证。

验证：解析首页 HTML，核对跳转和手动入口均为指定站点；检查旧归档路径仍存在。发布后需核对 GitHub Pages 实际发布源和部署结果。
