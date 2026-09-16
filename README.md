# omegapaopao.github.io

个人主页，收录 GitHub 上全部四个仓库的索引。

**线上地址：** https://omegapaopao.github.io/

## 内容

| 项目 | 语言 | 体量 | 说明 |
|---|---|---|---|
| [made in heaven](https://github.com/omegapaopao/made-in-heaven) | JavaScript · HTML | 70 KB | 网页视频倍速引擎，突破 16 倍上限到 50 倍 |
| [阿伟的智能龟缸](https://github.com/omegapaopao/aweis-smart-turtle-tank) | JavaScript · Python · C++ | 92 KB | BLE 物联网与边缘云协同的水温监控 |
| [铁记](https://github.com/omegapaopao/tieji-miniprogram) | JavaScript | 107 KB | 力量训练日志微信小程序 |
| [dsh-open-design](https://github.com/omegapaopao/dsh-open-design) | HTML · JavaScript · CSS | 1.49 MB | 把 OpenDesign 的 52 个技能桥接进 DeepSeek Harness |

## 技术形态

单文件 HTML，零外部请求，零构建步骤。

- 背景是逐帧绘制的透视网格画布，含地平线辉光、粒子视差与暗角
- 四个项目各分配一个专属色相，色相不跨模块，页面骨架保持碳黑加单色
- 长动效走 `animation`，交互动效走 `transition`，视差与滚动进度条包在 `@supports (animation-timeline)` 里做渐进增强
- 两处画布与全部动效都响应 `prefers-reduced-motion`，并在标签页隐藏时暂停
- 无障碍：正文与控件对比度均达 WCAG AA

## 门禁

本页通过 [dsh-open-design](https://github.com/omegapaopao/dsh-open-design) 自带的 `od-check.mjs` 全部 14 项检查（裸 hex、强调色配额、字形绑定、动效纪律、移动端回流、自包含、隐藏态门控等）。

## 许可

MIT
