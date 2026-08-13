# 运动内容管线现状说明 / Football Pipeline Status Notes

源适配器 `adapters/sports_pipeline/` 当前目录布局（仅媒体目录，均为空或成品输出）：

```
assets/      媒体资产（含版权球队队徽，不进入开源包）
audio/       音频资产
out/         成品视频输出（不进入开源包）
ref_frames/  参考帧
```

排除依据：PLAN.md 排除清单（版权队徽 assets/、成品 out/、ref_frames/、audio/）。源目录暂无可开源脚本或配置文件；一旦上游出现，按清单迁入本仓库并更新 README。
