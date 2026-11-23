<div align="center">

# 捣鼓熊 · aiwren

**做一些顺手、安静、本地优先的工具 · Building quiet, local-first tools that run on your device**

[**🏠 窗边工作间 (tinkerai.cn)**](https://tinkerai.cn) · [**✨ 惊鸿 FleetingGleam**](https://gleam.tinkerai.cn/) · [**中文**](#-嗨我是捣鼓熊-aiwren) · [**English**](#-hi-im-aiwren-tinkerbear)

[![TinkerAI Studio · 窗边工作间](https://tinkerai.cn/studio/window-room.webp)](https://tinkerai.cn)

</div>

---

## 🇨🇳 嗨，我是捣鼓熊 (aiwren)

平时喜欢做一些**顺手、安静、本地优先（Local-First & On-Device）**的软件工具：能放在设备端本地跑通的计算与模型推理，就不依赖云端上传；没有多余的账号墙，数据始终留在用户自己手里。

- 🏠 **个人主页（窗边工作间）**：[https://tinkerai.cn](https://tinkerai.cn)
- ✨ **惊鸿 FleetingGleam 官网**：[https://gleam.tinkerai.cn/zh/](https://gleam.tinkerai.cn/zh/)

### 🛠️ 正在维护的作品

- **[惊鸿 · FleetingGleam](https://github.com/aiwren/FleetingGleam)** · [中文官网](https://gleam.tinkerai.cn/zh/) · [下载 Release](https://github.com/aiwren/FleetingGleam/releases/latest)  
  运行在 **macOS (Apple Silicon)** 与 **Android** 上的开源本地照片筛选软件。把几千张照片里同一瞬间的连拍自动分组、多维可解释评分并标出最佳候选；支持 RAW+JPG 同步整理、中英文自然语言搜图、学习个人选片口味以及直连家庭 NAS（SMB / Cloudflare R2 偏好备份）。照片全程不离开你自己的设备。  
  `Rust` · `Tauri 2` · `React` · `Swift` · `Kotlin` · `AGPL-3.0`

- **[老师工作台 · ClassDesk](https://tinkerai.cn/works/classdesk/)**  
  面向班主任日常高频事务打磨的多端个人工作台：手机端随手点名考勤、记作业与小组积分，服务端用纯 JS 表格线检测 + 40×40 轻量卷积网络识别纸质作业登记表，手机端集成 PP-OCRv6 离线识别教务课表截图，配合电脑端成绩临界生分析、教室大屏通知客户端与扫码授权 MCP 助手。  
  `Flutter` · `Hono` · `PostgreSQL` · `Drizzle ORM` · `Electron` · `On-Device OCR`

- **[把一间小屋，做成网站 · tinkerai.cn](https://tinkerai.cn/works/window-room/)**  
  用 Blender 搭一间等轴测窗边工作间，从固定相机向场景发射射线提取可见表面的精确 SVG 轮廓，并烘焙局部 WebP 动作图条——把 26 MB 的 3D 场景浓缩成几十 KB 的静态首屏与可点击交互桌面。  
  `Next.js` · `Blender` · `Cycles` · `SVG` · `Canvas`

### 📓 桌边技术手记

- [不靠大模型，用纯 JS 认一张纸质作业登记表](https://tinkerai.cn/notes/homework-sheet-ocr/) — 在 DCT 域缩放切格，配合轻量 40×40 卷积网络与彩色墨水分离，在普通 Node 服务端几百毫秒完成整表识别。
- [沿着显示器找边界](https://tinkerai.cn/notes/visible-outline/) — 为什么不用矩形框做点击热区，而是从 Blender 相机发射射线拾取真正可见的物体轮廓。
- [为什么首屏不搬来整个 3D 模型](https://tinkerai.cn/notes/light-first-frame/) — 26 MB 压缩模型与 49 KB 首屏 WebP + 局部图条之间的工程取舍。
- [抽屉里的文章，也要有门牌号](https://tinkerai.cn/notes/real-links/) — 左侧液态玻璃阅读抽屉、独立静态页面与浏览器后退栈的渐进增强。
- [一批照片判错了，怎么撤回？](https://tinkerai.cn/notes/gleam-batch-undo/) — 惊鸿 Android 端长按多选批量判定与按批撤销的交互细节。

---

## 🌐 Hi, I'm aiwren (TinkerBear)

I build **quiet, tactile, local-first software** — tools where computation and AI inference run directly on your own device rather than in someone else's cloud. No mandatory accounts, no telemetry walls, and your data stays yours.

- 🏠 **Personal Studio & Notes**: [https://tinkerai.cn](https://tinkerai.cn)
- ✨ **FleetingGleam Official Site**: [https://gleam.tinkerai.cn/](https://gleam.tinkerai.cn/)

### 🛠️ Projects

- **[FleetingGleam (惊鸿)](https://github.com/aiwren/FleetingGleam)** · [Website](https://gleam.tinkerai.cn/) · [Latest Release](https://github.com/aiwren/FleetingGleam/releases/latest)  
  An open-source, on-device photo culling app for **macOS (Apple Silicon)** and **Android**. Automatically groups burst shots from the same moment, ranks candidates with explainable multi-metric scoring (sharpness, exposure, eyes/face, aesthetics), pairs RAW + JPEG files seamlessly, supports natural-language photo search, learns your personal culling taste, and connects directly to home NAS shares over SMB. Nothing is ever uploaded.  
  `Rust` · `Tauri 2` · `React` · `Swift` · `Kotlin` · `AGPL-3.0`

- **[ClassDesk (老师工作台)](https://tinkerai.cn/works/classdesk/)**  
  A multi-platform workspace tailored for homeroom teachers' daily workflows: mobile attendance, homework and group-point tracking in Flutter; a pure-JS grid detector + lightweight 40×40 CNN that reads hand-marked paper homework sheets in milliseconds; on-device PP-OCRv6 timetable screenshot parsing; exam analytics; an Electron classroom display client; and QR-authorized MCP assistant integration.  
  `Flutter` · `Hono` · `PostgreSQL` · `Drizzle ORM` · `Electron` · `On-Device OCR`

- **[TinkerAI Window Studio (把一间小屋，做成网站)](https://tinkerai.cn/works/window-room/)**  
  An interactive isometric 3D studio built in Blender and distilled from a 26 MB scene into a ~49 KB static first frame with ray-cast SVG hit contours and localized WebP pose strips — clicking the monitor, notebook, photo frame, mechanical keyboard, or chair interacts directly with the room.  
  `Next.js` · `Blender` · `Cycles` · `SVG` · `Canvas`

### 📓 Engineering Notes

- [Reading Paper Homework Sheets in Pure JS Without LLMs](https://tinkerai.cn/notes/homework-sheet-ocr/) — DCT-domain downsampling, perspective grid slicing, and a tiny 40×40 CNN running on a standard Node.js server.
- [Tracing Visible Outlines Along the Monitor](https://tinkerai.cn/notes/visible-outline/) — Generating exact occlusion-aware SVG hit paths via camera ray-casting in Blender.
- [Why the First Frame Doesn't Ship a 26 MB 3D Model](https://tinkerai.cn/notes/light-first-frame/) — Trade-offs between full WebGL scenes and pre-baked orthographic WebP sprite strips.
- [Every Drawer Article Deserves Its Own URL](https://tinkerai.cn/notes/real-links/) — Progressive enhancement between the floating Liquid Glass drawer, standalone pages, and browser history.
- [Batch Culling and Batch Undo in FleetingGleam](https://tinkerai.cn/notes/gleam-batch-undo/) — Designing multi-select decisions and atomic batch undo on Android.

---

## 🧰 常用技术栈 / Tech Stack

- **Desktop & Systems / 桌面与系统层**：`Rust` · `Tauri 2` · `Swift` · `Electron`
- **Mobile & Cross-Platform / 移动与跨端**：`Kotlin (Jetpack Compose)` · `Flutter`
- **Web & Backend / 前端与服务端**：`TypeScript` · `React` · `Next.js` · `Hono` · `Node.js` · `PostgreSQL` · `Redis`
- **On-Device AI & Graphics / 端侧推理与图形**：`ONNX Runtime` · `Apple Vision` · `PP-OCRv6` · `OpenCV` · `Blender Python API`

---

<div align="center">

*Built with care in the window studio · [tinkerai.cn](https://tinkerai.cn)*

</div>
