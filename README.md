# dsh-sports-pipeline

<!-- DeepSeek Harness 衍生声明 -->
> **DeepSeek Harness 个人适配声明（Personal Adaptation Notice）**
>
> 本项目是 [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) 的**个人适配产物（personal adaptation）**，**并非 DeepSeek Harness 官方文件（not an official DeepSeek Harness file）**，随附功能、使用说明与个人产物（bundled with features, documentation, and personal artifacts），可与 DeepSeek Harness 搭配使用，也可独立使用。
>
> This project is a **personal adaptation** for DeepSeek Harness, and is **NOT an official DeepSeek Harness file**, bundled with features, documentation, and personal artifacts. It can be used alongside DeepSeek Harness or standalone.

**作者 / Author**: [h565656445](https://github.com/h565656445)

**合作 / Collaboration**: 如有项目可以一起合作，欢迎联系。微信：`wohaishihenshuaide`。If you have projects, let's collaborate. WeChat: `wohaishihenshuaide`.

---

## 用途 / What this is for

视频内容管线索引：说明视频内容管线资产布局与排除范围的占位索引仓。

Video content pipeline index: a placeholder index documenting the pipeline asset layout and exclusion scope.

---
## Football Pipeline (Index) / 运动内容管线（索引仓）

运动内容制作管线的开源索引仓。源适配器 `adapters/sports_pipeline/` 当前只承载媒体资产与成品输出目录（assets/、audio/、out/、ref_frames/），不含可开源的脚本或配置：assets/ 含版权球队队徽，out/ 为成品视频，均按排除清单不进入本仓库。后续源目录出现可开源脚本与配置后，将在此仓库补充。

An open-source index repo for the sports content production pipeline. The source adapter `adapters/sports_pipeline/` currently holds only media asset and output directories (assets/, audio/, out/, ref_frames/) with no open-sourceable scripts or configs: assets/ contains copyrighted team crests and out/ holds finished videos, both excluded per the exclusion list. Scripts and configs will be added here when they become available upstream.

## Features / 功能

- 占位索引：说明运动内容管线资产布局与排除范围 / Placeholder index: documents the pipeline's asset layout and exclusions
- 待补充：源目录出现脚本/配置后按清单迁入 / To be added: scripts/configs migrated here per the manifest once they exist upstream

## What's inside / 目录结构

```
README.md   双语说明与排除范围
docs/       管线说明（当前为现状说明，后续补充）
（源码暂缺：源目录仅含被排除的媒体目录 assets/ audio/ out/ ref_frames/）
```

## Quick start / 快速开始

```powershell
# 本仓库暂无可运行源码；请先阅读 README.md 与 docs/PIPELINE-NOTES.md
```

## DeepSeek Harness 衍生 / DSH Derivative

本项目附带 DeepSeek Harness 衍生包，位于 `.dsh/` 目录：

- `preset.yml` — Agent 预设元数据
- `agent.cordis.yml` — Cordis 组装（基于 standard 预设，persona 已定制）
- `skills/dsh-sports-pipeline/SKILL.md` — 项目专属技能（skill）

安装与接入方式见 [`.dsh/README.md`](.dsh/README.md)（双语）。

## License / 许可证

[MIT](LICENSE)