# time_series_recent_report

时间序列预测方向的近期综述文献，以及相关的稿件资料、行情数据和教程。

## 内容

- [`TimeSeries_Reviews_2026/`](TimeSeries_Reviews_2026/)：50 篇 2025–2026 年的综述、观点和评测论文，按领域分为 6 类。入口是 `INDEX.html`，说明见 [`README_zh.md`](TimeSeries_Reviews_2026/README_zh.md)。45 篇是 PDF；5 篇没有明确的再分发许可，是指向来源的同名 `.url` 文件。
- [`papers/`](papers/)：两份稿件资料包，`ACS Omega.rar` 和 `Molecules.rar`，含正文、补充材料、数据、代码和图片。另一份资料包 `Fengyang.zip`（约 156 MB）超过 GitHub 单文件 100 MB 的限制，放在 [Release `feng`](https://github.com/yuriev315/time_series_recent_report/releases/tag/feng)，下载后放到 `papers/` 下即可。
- `volume_data/`：27 个币种的 1 分钟成交量 CSV（字段 `asset, coin, time, volume, volume_usd, trade_count, close`，2026-01-01 至 2026-09-23）。
- `haystack-tutorials-main.zip`：[deepset-ai/haystack-tutorials](https://github.com/deepset-ai/haystack-tutorials) 的教程快照，Apache-2.0 许可。
- Release [`bayesian_optimization`](https://github.com/yuriev315/time_series_recent_report/releases/tag/bayesian_optimization)：贝叶斯优化与高斯过程参考文献，以及在 Windows x64 上离线运行 ISLP（Python）实验和 R keras 专题脚本的完整环境。先解压 `bayesian_optimization.zip`，用法见其中的 `README.md`。

论文版权归作者和出版方所有，使用时以各篇 PDF 中的许可声明为准。
