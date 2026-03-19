# Gitnexus - Landing Page

> 生成时间：2026-03-19 22:03:15
> 项目类型：Landing Page（营销落地页）

---

## 📄 文件结构

```
GitNexus/
├── index.html          # 主页面
├── assets/
│   ├── css/
│   │   └── style.css  # 样式文件
│   └── images/         # 图片资源（占位符）
└── README.md          # 本文件
```

---

## 🚀 本地预览

### 方法 1：直接打开
在浏览器中打开 `index.html` 文件

### 方法 2：使用 Python 简易服务器
```bash
cd GitNexus
python3 -m http.server 8000
```
然后访问：http://localhost:8000

### 方法 3：使用 VS Code Live Server
安装 Live Server 插件，右键 `index.html` 选择 "Open with Live Server"

---

## 📤 部署到 GitHub Pages

### 1. 创建 GitHub 仓库
```bash
git init
git add .
git commit -m "Initial Landing Page"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/zoe-landing-pages.git
git push -u origin main
```

### 2. 配置 GitHub Pages
1. 进入仓库设置（Settings）
2. 选择 "Pages"
3. Source 选择 "Deploy from a branch"
4. Branch 选择 `main`，文件夹选择 `/root`（如果项目在子目录）
5. 点击 Save

### 3. 访问 Landing Page
等待 1-2 分钟后，访问：
```
https://YOUR_USERNAME.github.io/zoe-landing-pages/GitNexus/
```

---

## 📤 部署到 Vercel（推荐）

### 1. 安装 Vercel CLI
```bash
npm i -g vercel
```

### 2. 部署
```bash
cd GitNexus
vercel
```

### 3. 访问 Landing Page
Vercel 会提供一个 `.vercel.app` 域名

---

## 🎨 自定义样式

### 修改颜色
编辑 `assets/css/style.css`，搜索以下变量并修改：
- 主色：`#4F46E5`
- 渐变色：`#667eea` 和 `#764ba2`

### 修改内容
编辑 `index.html`，修改以下部分：
- Hero 区域的标题和副标题
- 功能卡片的内容
- 定价方案的价格和功能
- CTA 按钮的文字

---

## 💡 商业信息

### 商业模式
- **推荐模式：** Freemium
- **定价策略：** 免费+增值

### MVP 功能

### 技术栈
- **前端：** HTML5 + CSS3 + JavaScript
- **样式：** 自定义 CSS
- **响应式：** 移动端友好设计

---

## 📞 联系方式

- Email：support@example.com
- Website：https://example.com

---

*本页面由 Zoe Agent System 自动生成*
*生成时间：2026-03-19T22:03:15.970906*
