# AI 课程作品集 · AI Course Portfolio

记录我在学校 AI 课程里完成的每一次构建。把「想法」变成「能点开看的页面」——用 AI 辅助创作，用代码构建表达。

> 🌐 在线访问：<https://zhanfoguang.github.io/ai-course-portfolio/>

---

## 📁 作品目录

| 编号 | 作品 | 内容 | 入口 |
|------|------|------|------|
| 01 | 《欢迎来龙餐馆》电影宣传页 | 电影主题 · 单页沉浸式 HTML（开场动能标题 / 弹性剧照墙 / 3D 角色卡 / 核心意象锚点 / 胶片致谢名单），可离线单文件 | [`works/dragon-restaurant/`](./works/dragon-restaurant/index.html) |
| 02 | V-TWIN 1103 摩托车发动机三维爆炸图 | 机械结构 · 交互式三维爆炸图（27 个零件沿装配轴连续拆解 / 拆解过程中曲柄连杆机构仍实时运转 / 工程标注自动避让与遮挡淡出 / 单文件发布，three.js 由 CDN 加载） | [`works/v-twin-1103-engine/`](./works/v-twin-1103-engine/index.html) |
| 03 | — | 敬请期待 | — |

## 🧭 目录结构

```
ai-course-portfolio/
├── index.html                    # 主页：作品集门户（GitHub Pages 入口）
├── works/                        # 课程作业归档
│   ├── dragon-restaurant/
│   │   └── index.html            # 作业 01：沉浸式电影宣传页（自包含单文件）
│   └── v-twin-1103-engine/
│       └── index.html            # 作业 02：90° V 型双缸发动机三维爆炸图（WebGL 实时）
└── README.md
```

## 🛠 创作方法

1. **看懂参考** —— 先判断类型、情绪、信息层级、视觉母题，只提取「视觉基因」；
2. **转译基因** —— 把抽象符号拆成曲线、节奏、色彩与肌理，不机械复刻；
3. **构建降级** —— 纯原生 HTML/CSS/JS，IntersectionObserver 驱动滚动动效，尊重 `prefers-reduced-motion`，保证移动端可用。

## ✍️ 如何新增作业

1. 在 `works/` 下新建目录，例如 `works/my-new-work/`；
2. 将作品单文件命名为 `index.html` 放入；
3. 更新主页 `index.html` 的作品卡片区与本 README 的作品目录。

---

© zhanfoguang · AI Course Portfolio · 2026
