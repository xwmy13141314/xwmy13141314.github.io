# 个人网站 · xwmy13141314

独立开发者作品集单页网站。纯静态零依赖：一个 `index.html` + 一个 `assets/` 图片目录。

**线上地址：** https://xwmy13141314.github.io/

## 内容结构

| 区块 | 内容 |
|---|---|
| Hero | 构建流程自动演示卡（想法 → 验证 → 构建 → 开源） |
| 01 关于我 | 数据统计（数字滚动）+ 开发者画像 |
| 02 项目作品 | 6 个精选项目轮播（3 张真实产品截图 + 3 张 AI 生成插图） |
| 03 方法论 | 3 个 Claude Skills 卡片 |
| 04 技术栈 | 6 组技术标签 |
| 05 全部项目 | 15 个开源仓库完整清单 |
| 06 联系 | GitHub CTA + 页脚导航 |

## 技术点

- 单文件站点，原生 CSS transition + IntersectionObserver，无任何框架与构建步骤
- 动效：顶部滚动进度条、Hero 自动演示（悬停暂停/手动暂停）、项目轮播（scroll-snap 吸附 + 分页计数）、数字滚动、卡片交错入场
- 响应式适配桌面 / 平板 / 手机，尊重 `prefers-reduced-motion`
- 视觉风格参考：志亚科技官网（白底 + 宝蓝主色 + 编号章节 + 卡片化布局）

## 本地预览

双击 `index.html` 即可，或：

```bash
python3 -m http.server 8000
# 打开 http://localhost:8000
```

## License

MIT
