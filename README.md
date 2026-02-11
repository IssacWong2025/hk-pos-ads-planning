# 香港餐饮 POS Meta 投放规划（静态站点）

- 最新版入口：docs/index.html（GitHub Pages 发布）
- 历史版本：docs/versions/
- 项目协作规则：AGENTS.md

## 用途

- 内部协作：市场、销售、运营多轮迭代同一份投放策略
- 会话延续：不同 Codex 会话可直接在该仓库继续更新
- 对外查看：通过 GitHub Pages 提供只读链接

## 更新流程

1. 编辑 docs/index.html
2. 可选：在 docs/versions/ 保存快照版本
3. 运行：./scripts/publish.ps1 -Message "publish: <note>"

## 自动发布（可选）

`powershell
cd "C:\Users\Administrator\Desktop\hk-pos-ads-planning"
.\scripts\watch-publish.ps1
`
"@
Set-Content -Path (C:\Users\Administrator\Desktop\hk-pos-ads-planning+'\CHANGELOG.md') -Encoding UTF8 -Value @"
# Changelog

## v1.0.0 - 2026-02-11
- 初始化项目结构
- 发布《首月 HKD 6,000 的香港餐饮 POS Meta 投放策略 v1》HTML版
