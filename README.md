# 嗨，我是捣鼓熊 (aiwren) 👋

平时喜欢做一些**顺手、安静、本地优先（Local-First）**的软件工具：能放在设备端本地跑通的计算与模型推理，就不依赖云端上传；没有多余的账号墙，数据始终留在用户自己手里。

🏠 **个人网站（窗边工作间）**：[https://tinkerai.cn](https://tinkerai.cn)  
✨ **惊鸿 FleetingGleam 官网**：[https://gleam.tinkerai.cn/zh/](https://gleam.tinkerai.cn/zh/)

[![窗边工作间 · tinkerai.cn](https://tinkerai.cn/studio/window-room.webp)](https://tinkerai.cn)

---

### 🛠️ 正在捣鼓的作品 / Projects

- **[惊鸿 · FleetingGleam](https://github.com/aiwren/FleetingGleam)** · [官网](https://gleam.tinkerai.cn/zh/) · [下载 Release](https://github.com/aiwren/FleetingGleam/releases/latest)  
  运行在 **macOS (Apple Silicon)** 与 **Android** 上的开源本地照片筛选软件。把几千张照片里同一瞬间的连拍自动分组、多维可解释评分并标出最佳候选；支持 RAW+JPG 同步整理、中英文自然语言搜图、学习个人选片口味以及直连家庭 NAS（SMB / Cloudflare R2 偏好备份）。照片全程不离开你自己的设备。  
  `Rust` · `Tauri 2` · `React` · `Swift` · `Kotlin` · `AGPL-3.0`

- **[老师工作台 · ClassDesk](https://tinkerai.cn/works/classdesk/)**  
  面向班主任日常高频事务打磨的多端个人工作台：手机端随手点名考勤、记作业与小组积分，服务端用纯 JS 表格线检测 + 40×40 轻量卷积网络识别纸质作业登记表，手机端集成 PP-OCRv6 离线识别教务课表截图，配合电脑端成绩临界生分析、教室大屏通知客户端与扫码授权 MCP 助手。  
  `Flutter` · `Hono` · `PostgreSQL` · `Drizzle ORM` · `Electron` · `On-Device OCR`

- **[把一间小屋，做成网站 · tinkerai.cn](https://tinkerai.cn/works/window-room/)**  
  用 Blender 搭一间等轴测窗边工作间，从固定相机向场景发射射线提取可见表面的精确 SVG 轮廓，并烘焙局部 WebP 动作图条——把 26 MB 的 3D 场景浓缩成几十 KB 的静态首屏与可点击交互桌面。  
  `Next.js` · `Blender` · `Cycles` · `SVG` · `Canvas`

---

### 📓 桌边技术手记 / Notes

- [不靠大模型，用纯 JS 认一张纸质作业登记表](https://tinkerai.cn/notes/homework-sheet-ocr/) — 在 DCT 域缩放切格，配合轻量 40×40 卷积网络与彩色墨水分离，在普通 Node 服务端几百毫秒完成整表识别。
- [沿着显示器找边界](https://tinkerai.cn/notes/visible-outline/) — 为什么不用矩形框做点击热区，而是从 Blender 相机发射射线拾取真正可见的物体轮廓。
- [为什么首屏不搬来整个 3D 模型](https://tinkerai.cn/notes/light-first-frame/) — 26 MB 压缩模型与 49 KB 首屏 WebP + 局部图条之间的工程取舍。
- [抽屉里的文章，也要有门牌号](https://tinkerai.cn/notes/real-links/) — 左侧液态玻璃阅读抽屉、独立静态页面与浏览器后退栈的渐进增强。
- [一批照片判错了，怎么撤回？](https://tinkerai.cn/notes/gleam-batch-undo/) — 惊鸿 Android 端长按多选批量判定与按批撤销的交互细节。

---

### 🧰 常用技术栈 / Tech Stack

- **桌面与系统层**：`Rust` · `Tauri 2` · `Swift` · `Electron`
- **移动与跨端**：`Kotlin (Jetpack Compose)` · `Flutter`
- **Web 与服务端**：`TypeScript` · `React` · `Next.js` · `Hono` · `Node.js` · `PostgreSQL` · `Redis`
- **端侧推理与图形**：`ONNX Runtime` · `Apple Vision` · `PP-OCRv6` · `OpenCV` · `Blender Python API`

---

*Built with care in the window studio · [tinkerai.cn](https://tinkerai.cn)*
