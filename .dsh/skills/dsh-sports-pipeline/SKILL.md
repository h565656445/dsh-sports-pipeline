---
name: dsh-sports-pipeline
description: 维护与使用运动内容制作管线（当前为占位索引仓）时加载。 / Load when maintaining or using the sports content production pipeline (currently a placeholder index repo).
---

# 运动内容管线

运动内容管线的开源索引仓：源适配器当前只承载媒体资产与成品输出目录（assets/audio/out/ref_frames），不含可开源脚本或配置。本技能用于在补充脚本/配置、或需要说明管线资产布局与排除范围时提供上下文。

An open-source index repo for the sports content pipeline: the source adapter currently holds only media asset/output directories (assets/audio/out/ref_frames) with no open-sourceable scripts or configs. This skill provides context when supplementing scripts/configs or documenting the pipeline's asset layout and exclusions.

## When to use / 何时使用

需要了解运动内容管线资产布局与排除范围、或向本仓库补充可开源脚本/配置时。

## Workflow / 工作流

1. 确认源适配器 adapters/sports_pipeline/ 中是否存在可开源脚本/配置（排除 assets/、audio/、out/、ref_frames/ 与成品视频）。
2. 若有，按清单复制进本仓库并更新 README 与 docs/PIPELINE-NOTES.md。
3. 若没有，保持占位索引状态并在回报中说明。

## References / 参考

- 项目 README: 见仓库根目录
- 作者: h565656445 (GitHub)