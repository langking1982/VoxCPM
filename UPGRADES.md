# 本衍生仓库升级记录 (UPGRADES)

> 本文件只记录本衍生仓库相对上游 [OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM) 的增量改动。

## v1 (2026-10-23) — 合规与工程化基线

**鸣谢**：本仓库基于 [OpenBMB](https://github.com/OpenBMB) 的 [VoxCPM](https://github.com/OpenBMB/VoxCPM) 衍生开发，谨此致谢。

### 合规修复
- ✅ 新增 `NOTICE.md`：完整出处链与原版权保留（Apache-2.0 要求再分发时保留 LICENSE 与 NOTICE）。
- ✅ 新增 `CITATION.cff`：机器可读引用元数据。
- ✅ README 顶部新增衍生声明横幅。

### 工程化升级
- ✅ 新增 CI（GitHub Actions）：Python 3.10/3.12 矩阵，pip install + 冒烟检查。

### 后续规划（欢迎 PR）
- [ ] CI 中加入模型下载与单句合成冒烟（显存需求允许时）
- [ ] README_EN
