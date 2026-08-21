# 个人作品集网站

## 项目简介
这是一个基于纯前端技术构建的个人作品集网站，用于展示个人信息、教育背景、荣誉奖项、校园/实习经历等项目。网站采用响应式设计，适配桌面与移动设备。

## 项目结构
├── index.html # 作品集首页（含项目卡片轮播）
├── tianqianzhu-shu.html # 项目详情页：天堑筑蜀
├── he-ming.html # 项目详情页：和鸣
├── xuewuya.html # 项目详情页：《学无涯》
├── restaurant.html # 项目详情页：餐厅管理系统
├── residents.html # 项目详情页：杭州市居民幸福感调研
├── README.txt # 本文件
│
├── documents/ # 项目文档（PDF）
│ ├── Resume.pdf # 个人简历
│ ├── tianqianzhu-shu.pdf
│ ├── he-ming.pdf
│ ├── xuewuya.pdf
│ ├── restaurant.pdf
│ └── residents.pdf
│
├── images/ # 图片资源
│ ├── tianqianzhu-shu_.jpg # 天堑筑蜀截图（1-8）及证书
│ ├── he-ming_.jpg # 和鸣截图（1-4）及证书
│ ├── xuewuya_.jpg # 学无涯截图（1-5）
│ ├── restaurant_.jpg # 餐厅管理系统截图（1-6）
│ ├── residents_*.jpg # 幸福感调研证书（1-3）
│ ├── singer_Certificate.jpg # 十佳歌手证书
│ └── ...
│
└── videos/ # 演示视频
├── tianqianzhu-shu/
│ └── tianqianzhu-shu_video.mp4
├── he-ming/
│ ├── he-ming_video1_project_defense.mp4
│ ├── he-ming_video2_dance_performance.mp4
│ ├── he-ming_video3_dance_sound_effects.mp4
│ ├── he-ming_video4_tai_chi_performance.mp4
│ └── he-ming_video5_tai_chi_sound_effects.mp4
└── xuewuya.mp4


## 功能说明

### 首页
- 个人信息卡片、教育背景、个人荣誉（带证书图片）、校园/实习经历
- **项目卡片轮播**：五个项目卡片各自独立轮播展示截图，鼠标悬停暂停，移出继续
- 一键打开简历 PDF（`documents/Resume.pdf`）

### 项目详情页
每个项目详情页包含：
- **项目简介与技术路径**：展示项目背景、技术栈、个人负责内容
- **多媒体展示区**：
  - 演示视频
  - 获奖证书
  - 作品展示截图
- **项目文件预览**：PDF 文档嵌入 iframe 直接预览

## 浏览器兼容性
- 推荐使用 Chrome / Edge / Firefox 最新版本
- 移动端适配：宽度 ≤ 900px 时自动折叠侧边栏，≤ 560px 时进一步优化排版