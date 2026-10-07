# 徐子墨 · 个人主页

> Zimo Xu — Personal Archive · AI × 全栈开发 × 视觉艺术

工业废土（Industrial Wasteland）风格的现代化个人主页，以橙蓝撞色与硬核科幻质感，集中展示个人履历、技术能力与影像作品。

## 特性

- **工业废土视觉**：橙蓝撞色、网格背景、噪点纹理、HUD 取景框与四角装饰，营造硬核科技氛围
- **中英双语**：右上角一键切换，默认英文，语言偏好自动记忆
- **深浅色主题**：右上角一键切换，默认深色，主题偏好自动记忆
- **全设备适配**：桌面、平板、手机全覆盖，自适应横屏与竖屏
- **影像内嵌**：B 站影像作品保留播放控件，可暂停、可全屏
- **资源本地化**：所有照片本地存储，无第三方图床依赖，加载快速稳定
- **零构建**：单文件 HTML，双击即可离线预览

## 页面结构

| 区块 | 内容 |
| --- | --- |
| 01 个人档案 | 关于我、成长时间轴 |
| 02 技能矩阵 | 核心能力、AI 模型、技术栈与软件基建 |
| 03 代码项目 | 开源项目与工程实践 |
| 04 视觉档案 | 专业摄影视界 · 视觉中国签约摄影师 |
| 05 作品集 2026 | 画册式影像作品集入口 |
| 06 影像档案 | B 站影像作品 |
| 07 联系方式 | 社交与联络方式 |

## 技术栈

- 纯 HTML5 + CSS3 + 原生 JavaScript，无框架、无构建
- CSS 变量驱动的主题系统（深色 / 浅色）
- `data-lang` 属性驱动的中英双语切换
- IntersectionObserver 入场动画与懒加载
- Flexbox + CSS Grid 响应式布局
- 字体：Archivo Black / Chakra Petch / JetBrains Mono（Google Fonts）
- 图标：Font Awesome 6.5.1

## 目录结构

```
.
├── index.html          # 单文件主页（含全部样式与脚本）
├── images/             # 本地图片资源
│   ├── avatar_01.jpg   # 个人形象照
│   ├── vcg_card.jpg    # 视觉中国签约名片
│   ├── city_20.jpg     # 摄影作品 · 云上都市
│   ├── nature_01.jpg   # 摄影作品 · 山谷村落
│   └── cover_01.jpg    # 作品集封面
└── README.md
```

## 本地预览

直接双击 `index.html` 即可打开。

如需本地服务器（内嵌视频体验更佳）：

```bash
python -m http.server 8000
# 访问 http://localhost:8000/
```

## 部署

纯静态站点，可部署至 Vercel、GitHub Pages、Netlify 等任意静态托管平台。

> 部署时请连同 `images/` 目录一起上传，否则图片将无法显示。

## 相关链接

- 作品集 2026：https://portfolio-2026-five-blond-35.vercel.app/
- GitHub：https://github.com/Jimmy-xuzimo
- Bilibili：https://space.bilibili.com/1504211198
- 500px：https://500px.com.cn/Jimmyzimo
- 邮箱：xuzimojimmy@163.com

## 版权

© 2026 徐子墨 Zimo Xu. 保留所有权利。未经许可请勿转载或商用。
