# blog.x7peeps.com

博客**源**不在这个仓库。文章源在 `x7peeps/x7peeps.github.io` 的 `hugo-src/`，
本仓库只做一件事：把它按 `baseURL = https://blog.x7peeps.com/` 构建出来，发布到这个域名。

- 定时：每 3 小时拉一次源仓库最新提交重新构建（源仓库每日写作产线会自动提交，无需人工触发）
- 手动：Actions → Build blog → Run workflow
- 想看改动生效：`gh run list -R x7peeps/blog`

不要在这里放文章。写进这个仓库的内容会在下一次构建中被源仓库覆盖。
