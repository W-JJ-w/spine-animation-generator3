# 🎬 Spine动画段代码转换器

一个专业的Spine动画项目文件生成工具，根据输入的动画段名称快速生成对应的JSON文件，支持导入Spine中使用。

## 🌟 功能特点

- ✅ **批量处理**：支持多个动画段名称同时输入
- ✅ **标准格式**：生成符合Spine官方标准的JSON格式
- ✅ **版本兼容**：支持Spine 4.1.24+版本
- ✅ **离线使用**：无需网络连接，纯前端实现
- ✅ **跨平台**：支持所有现代浏览器
- ✅ **响应式设计**：完美适配手机和电脑

## 🚀 在线访问

**部署后的访问地址：**
- GitHub Pages: `https://用户名.github.io/仓库名`
- Netlify: `https://项目名.netlify.app`
- Vercel: `https://项目名.vercel.app`

## 📁 文件结构

```
项目根目录/
├── index.html                    # 主页（分享链接页面）
├── spine_animation_generator.html # 转换器主程序
├── avatar.png                    # 作者头像
└── README.md                     # 项目说明文档
```

## 🛠️ 部署指南

### 方法1：Netlify（推荐，最简单）

1. 访问 [netlify.com](https://netlify.com)
2. 将整个项目文件夹拖拽到页面上
3. 等待几秒钟自动部署完成
4. 获得免费的访问网址

### 方法2：GitHub Pages

1. 创建GitHub仓库
2. 上传所有文件到仓库
3. 进入仓库Settings → Pages
4. 选择分支（main或master）
5. 等待5-10分钟生效

### 方法3：Vercel

1. 访问 [vercel.com](https://vercel.com)
2. 连接GitHub仓库或直接上传
3. 自动部署并获得访问地址

## 📋 使用说明

### 基本使用流程

1. **打开转换器**：访问部署后的网址
2. **输入动画段名称**：每行一个名称
3. **设置项目名称**：自定义Spine项目名称
4. **选择输出格式**：JSON格式（推荐）
5. **生成文件**：点击生成按钮
6. **下载使用**：下载生成的文件在Spine中导入

### 输入示例

```
track1_dumplings_highlight
track1_dumplings_highlight_loop
track1_dumplings_cancel
track1_dumplings_cancel_loop
idle_animation
walk_animation
jump_animation
```

### 在Spine中导入

1. 打开Spine软件（版本4.1.24或更高）
2. 选择 File → Import Data...
3. 导入生成的JSON文件
4. 开始编辑各个动画段的具体内容

## 🔧 技术规格

- **前端技术**：HTML5 + CSS3 + JavaScript
- **兼容性**：所有现代浏览器
- **文件大小**：< 100KB
- **依赖**：无外部依赖
- **编码**：UTF-8

## 🎨 界面特色

- 现代化渐变背景设计
- 响应式布局，适配各种屏幕
- 直观的操作界面
- 实时预览功能
- 优雅的动画效果

## 📞 技术支持

- **Spine官方文档**：[http://esotericsoftware.com/spine-json-format](http://esotericsoftware.com/spine-json-format)
- **作者**：@W-JJ-w
- **版本**：1.0.0

## 📄 许可证

本项目采用MIT许可证，可自由使用和修改。

## 🔄 更新日志

### v1.0.0 (2024)
- ✨ 初始版本发布
- ✅ 支持批量动画段名称输入
- ✅ 生成标准Spine JSON格式
- ✅ 响应式设计
- ✅ 离线使用支持

---

**享受创作！** 🎮✨