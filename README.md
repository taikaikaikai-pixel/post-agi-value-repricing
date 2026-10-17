# 两万亿美元的“双向死局”

[![Deploy GitHub Pages](https://github.com/taikaikaikai-pixel/post-agi-value-repricing/actions/workflows/pages.yml/badge.svg)](https://github.com/taikaikaikai-pixel/post-agi-value-repricing/actions/workflows/pages.yml)

从大模型估值幻觉看后 AGI 时代的价值重定价与制度锚漂移。仓库提供一篇完整、自包含的中文网页长文，以及文章配套的原创结构化矢量图。

**[在线阅读](https://taikaikaikai-pixel.github.io/post-agi-value-repricing/)** · **[单文件版本](index.html)**

## 内容框架

- 一张撕裂的资产负债表与两万亿美元估值公投
- 最短路径、自我瓦解与“体感收费”的窗口幻觉
- 任务产出的负值坍塌，以及物理与法律之墙
- 超级智能的意图控制失效与财产权终值问题
- 人类不可替代性六存量，以及货币、债务与权利制度的重锚
- 四项可持续跟踪的可证伪观察指标

## 页面特性

- 单个 `index.html` 包含全部 HTML、CSS、JavaScript 与 SVG
- 6 张内嵌矢量图：导读图及图 1–5
- 桌面固定目录、移动端折叠目录与阅读进度提示
- 响应式布局，复杂图表在窄屏设备上支持横向浏览
- 内置打印样式，可直接打印或保存为 PDF
- 无外部图片、字体、脚本、样式或构建依赖

## 本地阅读

直接用浏览器打开 `index.html` 即可。也可以在仓库根目录启动本地静态服务器：

```bash
python -m http.server 8000
```

然后访问 `http://localhost:8000/`。

## 仓库结构

```text
.
├── .github/workflows/pages.yml  # GitHub Pages 自动部署
├── .gitignore
├── CONTRIBUTING.md              # 修订与纠错约定
├── LICENSE                      # MIT License
├── README.md
└── index.html                   # 完整文章与全部图表
```

## 发布方式

推送到 `main` 分支后，GitHub Actions 会自动将静态站点部署到 GitHub Pages。无需安装依赖或执行构建。

## 参与修订

错别字、断链、排版问题和数据纠错均欢迎通过 Issue 或 Pull Request 提交。涉及数据或论断的修订，请附可核验的来源与统计口径，详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 内容说明

文中数据、观点与表述按原稿呈现，配图用于解释逻辑关系；除特别注明外，示意图不代表比例尺。本文不构成投资建议。

## 许可证

仓库中的代码、文章与图表均以 [MIT License](LICENSE) 发布。转载或二次发布时请保留许可证与来源说明。
