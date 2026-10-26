# 学习日志

每条 3 行以内，写完就提交。写不出来的地方，就是没学懂的地方。

## W1（10.12–10.18）

> 实际完成日期：2026-10-26（补做）

- 本周唯一交付物：GitHub 仓库 agent-roadmap 已上线，掌握了 add/commit/push + 分支→PR→合并完整流程
- 今日学到：
  - `git add .` = 购物车、`commit -m` = 结账、`push` = 上传云端，三步走
  - 分支（branch）就是草稿纸，随便改不影响正文
  - PR（Pull Request）= 申请把草稿合入正文，merge = 批准合并
  - GitHub 被墙时 curl API 绕过 + PAT token 替代密码
- 卡住：
  - `gh auth login` 网络超时，改用 PAT 手动认证
  - `git push` 被 Credential Manager 卡住，用 `-c credential.helper=` 绕过
  - 简体中文路径在 MSYS 下编码乱码，Git Bash 需手动打开
