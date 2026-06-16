# Historical Figures & Educational Institutions in China (1872?951)

# 中国教育人物与机构分布图（1872--1951）

---

## English

An interactive map visualizing the activity records of key historical figures and educational institutions in China from 1872 to 1951, during the late Qing Dynasty and early Republic era.

### Features

- **Interactive map** of China with activity density heatmap
- **School-level nodes** — each educational institution plotted at its geographic coordinates
- **Trajectory lines** — animated arrows showing a person's movement between institutions
- **Bilingual interface** (EN / 中文) — one-click language toggle
- **Responsive sidebar** — click any person to highlight their trajectory on the map
- **Tooltips** — hover over provinces or institutions for detailed records

### Data

24 activity records covering 11 historical figures and 14 educational institutions across 7 provinces:

| Person | Institutions | Province |
|--------|-------------|----------|
| 容闳 (Yung Wing) | Chinese Educational Mission | Beijing |
| 唐景星 (Tong King-sing) | Kwang Chau Public School, Gezhi Academy, Shanghai Telegraph School | Shanghai |
| 唐绍仪 (Tang Shao-yi) | Shandong University, Tianjin University, Fudan University | Shandong, Tianjin, Shanghai |
| 梁如浩 (Liang Ju-hao) | Tangshan Engineering College, Tianjin University | Hebei, Tianjin |
| 唐有恒 (Tang Yu-heng) | South China Agricultural University | Guangdong |
| 唐国安 (Tong Kwo On) | Tsinghua University | Beijing |
| 孙中山 (Sun Yat-sen) | Sun Yat-sen University, Whampoa Military Academy | Guangdong |
| 钟荣光 (Chung Wing-kwong) | Lingnan University, Lingnan College, Lingnan Agricultural College | Guangdong |
| 魏畴民 (Wei Chou-min) | Central China Normal University | Hubei |
| 萧友梅 (Siao Yu-mei) | Peking University, Shanghai Conservatory of Music | Beijing, Shanghai |

### Tech Stack

- **ECharts 5** — map rendering, scatter plots, line series with animated effects
- **Pure HTML/CSS/JS** — no build tools, no frameworks
- **Embedded GeoJSON** — China map data loaded directly, no external API calls

### Usage

Open `index_bilingual.html` in any modern browser. No server required.

- **Hover** over a province to see all activity records in that region
- **Click** a person's name in the sidebar to highlight their institutional trajectory
- **Click** the same person again to deselect
- **Use the EN / 中文 buttons** to switch languages
- **Drag and scroll** to pan and zoom the map

### Deployment

This project is hosted on GitHub Pages:

```
https://github.com/zixu-zhao154/web
```

To deploy locally or to your own Pages:

```bash
git clone https://github.com/zixu-zhao154/web.git
# Simply serve the directory with any static server
npx serve .
# or
python -m http.server 8000
```

### License

MIT

---

## 中文

一张交互式地图，可视化展示 1872 至 1951 年（晚清至民国时期）中国教育领域关键人物的活动轨迹与教育机构分布。

### 功能特性

- **交互式中国地图** — 活动密度热力图
- **机构节点** — 每个教育机构按地理坐标标注在地图上
- **轨迹动画** — 带箭头的流动线条，展示人物在不同机构间的流转
- **中英双语界面** — 一键切换语言
- **响应式侧边栏** — 点击人物姓名高亮其求学/任职轨迹
- **悬浮提示** — 悬停省份或机构查看详细信息

### 数据

24 条活动记录，涵盖 11 位历史人物、14 所教育机构、7 个省份：

| 人物 | 机构 | 省份 |
|------|------|------|
| 容闳 | 出洋肄业局 | 北京 |
| 唐景星 | 广方言馆、格致书院、上海电报学堂 | 上海 |
| 唐绍仪 | 山东大学堂、北洋大学堂、复旦公学 | 山东、天津、上海 |
| 梁如浩 | 唐山路矿学堂、北洋大学堂 | 河北、天津 |
| 唐有恒 | 岭南农科大学 | 广东 |
| 唐国安 | 清华学堂 | 北京 |
| 孙中山 | 中山大学、黄埔军校 | 广东 |
| 钟荣光 | 岭南大学、岭南学院、岭南农学院 | 广东 |
| 魏畴民 | 华中师范大学 | 湖北 |
| 萧友梅 | 北京大学、上海音乐学院 | 北京、上海 |

### 技术栈

- **ECharts 5** — 地图渲染、散点图、带动画的轨迹线
- **纯 HTML/CSS/JS** — 无需构建工具，无需框架
- **内嵌 GeoJSON** — 中国地图数据直接嵌入，无外部 API 请求

### 使用方法

用浏览器直接打开 `index_bilingual.html`，无需服务器。

- **悬停**省份查看该区域所有活动记录
- **点击**侧边栏中的人物姓名，高亮其机构轨迹
- **再次点击**取消选中
- **使用 EN / 中文 按钮**切换语言
- **拖拽和滚轮**平移缩放地图

### 部署

本项目托管在 GitHub Pages：

```
https://github.com/zixu-zhao154/web
```

本地部署或部署到自己的 Pages：

```bash
git clone https://github.com/zixu-zhao154/web.git
# 使用任意静态服务器托管目录即可
npx serve .
# 或
python -m http.server 8000
```

### 许可

MIT
