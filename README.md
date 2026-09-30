# OmniBuddy-Plugins

OmniBuddy / OmniDeck 的**运行时组件分发仓库**（按需懒加载方案）。

- `runtime-manifest.json`：组件清单（版本 / sha256 / 多源下载 URL），应用首启或功能按需时读取
- Release 附件：私有组件包（`python-env-*` Python 解释器+预装数据栈、`node-tools-*` sharp/docx 等预装库）
- 公共组件（node / chrome-headless-shell / ffmpeg / pandoc）直接使用官方源与国内镜像，不入库

组件内软件版权归上游各自所有（node MIT、pandoc GPL-2.0+、Chromium/ffmpeg 见上游许可）。
