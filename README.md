# 奶小蛙手势桌宠 Nailoong

基于 Three.js 开发的手势交互 3D 桌面宠物项目。

## ✨ 项目介绍

奶小蛙手势桌宠是一个桌面端 3D 互动宠物应用，通过摄像头手势识别与用户进行交互。项目使用 Three.js 构建 3D 角色模型，支持手势追踪和实时动画反馈。

> ⚠️ 本仓库仅存放项目源码与模型配置，打包好的桌面端 exe 程序未上传至仓库。

## 📁 项目结构

```
Nailoong/
├── index.html              # 主页面，包含 3D 渲染与手势识别逻辑
├── object-sculpt-spec.json # 3D 模型参数配置
├── reference-analysis.md   # 模型参考图分析说明
└── README.md               # 项目说明文档
```

## 🚀 本地运行

1. 克隆仓库
```bash
git clone https://github.com/Snowball0312/Nailoong.git
```

2. 打开项目目录
```bash
cd Nailoong
```

3. 使用本地服务器运行（推荐 VS Code Live Server 插件，或执行以下命令）
```bash
# 如果你安装了 Python
python -m http.server 8000
```

4. 浏览器访问 `http://localhost:8000`

## 🛠️ 技术栈

- **Three.js** — 3D 图形渲染
- **MediaPipe Hands** — 手势识别与追踪
- **HTML5 / JavaScript** — 前端交互
- **Electron** — 桌面端打包

## 📝 开发笔记

- 3D 角色模型通过程序化生成，参数配置见 `object-sculpt-spec.json`
- 手势识别基于 MediaPipe Hands 实现
- 桌面端使用 Electron 打包为 exe 可执行文件

---

*本项目为个人学习与练习作品。*
