<div align="center">

# 💕 情侣纪念日倒计时

### ✨ Glassmorphism Edition ✨

![Version](https://img.shields.io/badge/version-3.2.2-pink)
![License](https://img.shields.io/badge/license-MIT-red)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

**一个浪漫的毛玻璃风格情侣纪念日网站 💝**

*记录你们在一起的每一秒，每一个重要时刻*

[🔥 在线预览](#) · [📦 下载](https://github.com/yourusername/your-repo/archive/refs/heads/main.zip) · [🐛 反馈问题](https://github.com/yourusername/your-repo/issues)

</div>

---

## 🌟 项目预览

<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│    ┌─────────┐    💕    ┌─────────┐                        │
│    │  👦 他  │  ──────  │  👧 她  │                        │
│    └─────────┘         └─────────┘                        │
│                                                             │
│              这是我们一起走过的                               │
│         365 天 12 时 30 分 45 秒                             │
│                                                             │
│  ┌─────────────────────┐  ┌─────────────────────┐          │
│  │ 🎉 周年纪念日        │  │ 💝 第一次相遇        │          │
│  │ 2024-07-29          │  │ 2024-07-29          │          │
│  │ 距那一天还有 xx 天   │  │ 已走过 xx 天         │          │
│  │ ████████░░░ 75.5%   │  │                     │          │
│  └─────────────────────┘  └─────────────────────┘          │
│                                                             │
│  ┌─────────────────────┐  ┌─────────────────────┐          │
│  │ 🎂 他的生日          │  │ 🎁 她的生日          │          │
│  │ 2000-01-01          │  │ 2000-01-01          │          │
│  │ 距那一天还有 xx 天   │  │ 距那一天还有 xx 天   │          │
│  └─────────────────────┘  └─────────────────────┘          │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

</div>

---

## ✨ 特色功能

### 🎨 毛玻璃设计
- **Glassmorphism 风格**：半透明背景 + 模糊效果 + 精美光影
- **心跳动画**：爱心图标带有浪漫的心跳效果
- **悬停特效**：卡片悬停时优雅放大
- **响应式布局**：完美适配各种屏幕尺寸

### ⏰ 实时计时
- **在一起时长**：精确到秒的实时计时器
- **纪念日倒计时**：自动计算下一个纪念日
- **生日提醒**：重要的人的生日不会忘记
- **进度可视化**：周年进度条一目了然

### 🛠️ 简单配置
- **JSON 配置**：只需修改一个文件即可定制
- **本地缓存**：支持 LocalStorage 缓存数据
- **即改即用**：无需重新部署，刷新即生效

---

## 📦 项目结构

```
倒计时3.2.2（毛玻璃版）/
├── 📄 index.html          # 主页面
├── 📄 data.json           # 配置文件 ⭐
├── 📁 css/
│   └── 🎨 styles.css      # 样式文件
├── 📁 js/
│   ├── ⚡ effects.js       # 特效脚本
│   ├── 💌 greeting-card.js # 贺卡功能
│   └── 📸 photo-gallery.js # 相册功能
├── 📁 image/
│   ├── 👦 nan.jpg          # 男生头像
│   ├── 👧 nv.jpg           # 女生头像
│   ├── 💝 xin.png          # 爱心图标
│   ├── 🖼️ gua.png          # 头像边框
│   └── 🌄 beijing-1.webp   # 背景图片
└── 📄 README.md           # 项目说明
```

---

## 🚀 快速开始

### 1️⃣ 下载项目

```bash
# 方式一：克隆仓库
git clone https://github.com/yourusername/love-countdown.git

# 方式二：直接下载
# 点击页面上方的 "Code" -> "Download ZIP"
```

### 2️⃣ 修改配置

编辑 `data.json` 文件，填入你们的信息：

```json
{
  "maleAvatarName": "他的名字",
  "femaleAvatarName": "她的名字",
  "maleBirthdayTitleName": "他的名字",
  "femaleBirthdayTitleName": "她的昵称",
  "acquaintanceDateDay": "2024-01-01",
  "acquaintanceDateTime": "2024-01-01 00:00:00",
  "maleBirthday": "2000-01-01",
  "femaleBirthday": "2000-01-01"
}
```

### 3️⃣ 替换图片

将你们的照片放入 `image/` 文件夹：

| 文件 | 说明 | 建议尺寸 |
|------|------|----------|
| `nan.jpg` | 男生头像 | 200×200px |
| `nv.jpg` | 女生头像 | 200×200px |
| `beijing-1.webp` | 背景图片 | 1920×1080px |

### 4️⃣ 部署上线

**方式一：GitHub Pages（免费）**

1. 上传代码到 GitHub 仓库
2. 进入仓库 Settings -> Pages
3. 选择 `main` 分支，点击 Save
4. 等待几分钟，访问 `https://yourusername.github.io/love-countdown/`

**方式二：Netlify（免费）**

1. 访问 [netlify.com](https://www.netlify.com/)
2. 拖拽项目文件夹到页面
3. 自动生成链接，可绑定自定义域名

**方式三：Vercel（免费）**

1. 访问 [vercel.com](https://vercel.com/)
2. 导入 GitHub 仓库
3. 自动部署，支持自动更新

---

## ⚙️ 配置说明

### data.json 字段详解

| 字段 | 类型 | 说明 | 示例 |
|------|------|------|------|
| `maleAvatarName` | string | 男生头像下方显示的名字 | `"小明"` |
| `femaleAvatarName` | string | 女生头像下方显示的名字 | `"小红"` |
| `maleBirthdayTitleName` | string | 男生生日卡片标题中的名字 | `"小明"` |
| `femaleBirthdayTitleName` | string | 女生生日卡片标题中的名字 | `"小红"` |
| `acquaintanceDateDay` | string | 纪念日日期（YYYY-MM-DD） | `"2024-01-01"` |
| `acquaintanceDateTime` | string | 在一起的精确时间 | `"2024-01-01 12:00:00"` |
| `maleBirthday` | string | 男生生日 | `"2000-01-01"` |
| `femaleBirthday` | string | 女生生日 | `"2000-01-01"` |

### 自定义样式

如需修改颜色、字体等样式，编辑 `css/styles.css` 文件：

```css
:root {
  --normal-text: #111b2d;        /* 主要文字颜色 */
  --glass-border: 1px double rgba(255, 255, 255, 0.36);
  --glass-bg: rgba(255, 255, 255, 0.08);
  --glass-radius: 15px;          /* 圆角大小 */
}
```

---

## 🎯 版本历史

### v3.2.2 (2026-06-08)
- ✅ 名字显示改为分开配置
- ✅ 倒计时说明文字颜色优化为黑色
- ✅ 移除多余旧名字字段

### v3.2.0
- ✅ 新增毛玻璃效果
- ✅ 新增进度条显示
- ✅ 响应式布局优化

### v3.0.0
- ✅ 全新 UI 设计
- ✅ 多纪念日支持
- ✅ 本地缓存功能

---

## 🤝 参与贡献

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 创建功能分支：`git checkout -b feature/your-feature`
3. 提交更改：`git commit -m 'Add some feature'`
4. 推送分支：`git push origin feature/your-feature`
5. 提交 Pull Request

---

## 📝 开源协议

本项目基于 [MIT License](LICENSE) 开源。

---

## 💖 致谢

感谢所有使用和喜欢这个项目的情侣们！

如果这个项目对你有帮助，请给一个 ⭐ Star 支持一下！

---

<div align="center">

**用代码记录爱情 💕**

Made with ❤️ by [Your Name]

![Visitors](https://api.visitorbadge.io/api/visitors?path=yourusername/love-countdown&countColor=%2337d67a&style=flat)

</div>
