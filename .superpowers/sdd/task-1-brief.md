### Task 1: Scaffold repo + copy assets

**Files:**
- Create: `C:\Users\lenovo\github-projects\tongguan-cangwu-guide\.gitignore`
- Copy: `C:\Users\lenovo\songtiao-guide\wanju.jpg` → `...\tongguan-cangwu-guide\`
- Copy: `C:\Users\lenovo\songtiao-guide\contact-qr.jpg` → `...\tongguan-cangwu-guide\`
- Create: `C:\Users\lenovo\github-projects\tongguan-cangwu-guide\README.md`

- [ ] **Step 1: Create GitHub repo**

Run:
```bash
cd /c/Users/lenovo/github-projects
gh repo create tongguan-cangwu-guide --public --clone
```
Expected: Repo created and cloned to `C:\Users\lenovo\github-projects\tongguan-cangwu-guide\`

- [ ] **Step 2: Create .gitignore**

Write `C:\Users\lenovo\github-projects\tongguan-cangwu-guide\.gitignore`:
```
# System
.DS_Store
Thumbs.db

# IDE
.vscode/
.idea/
*.swp
*.swo
```

- [ ] **Step 3: Copy asset files from Songtiao**

Run:
```bash
cp /c/Users/lenovo/songtiao-guide/wanju.jpg /c/Users/lenovo/github-projects/tongguan-cangwu-guide/
cp /c/Users/lenovo/songtiao-guide/contact-qr.jpg /c/Users/lenovo/github-projects/tongguan-cangwu-guide/
```
Expected: Both JPG files copied.

- [ ] **Step 4: Create README.md**

Write `C:\Users\lenovo\github-projects\tongguan-cangwu-guide\README.md`:
```markdown
# 江苏海洋大学通灌校区·苍梧校区 新生指南

面向2025/2026级新生的校园指南网站，涵盖两校区信息，支持一键切换。

👉 [通灌校区](https://sevennnnnn-rong.github.io/tongguan-cangwu-guide/)

## 功能

- 顶部Tab切换通灌/苍梧校区
- 入学指南、学习指南、生活指南、常见问题
- 深色模式
- 响应式设计（移动端+桌面端）

## 技术

纯静态HTML SPA，Tailwind CSS CDN，Lucide Icons，系统字体，零构建。
```

- [ ] **Step 5: Create empty index.html scaffold**

Write initial `C:\Users\lenovo\github-projects\tongguan-cangwu-guide\index.html`:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>江苏海洋大学新生指南 · 通灌校区 · 苍梧校区</title>
  <meta name="description" content="江苏海洋大学通灌校区和苍梧校区新生指南，涵盖报到流程、宿舍、食堂、交通等全方位信息">
</head>
<body>
  <p>Loading...</p>
</body>
</html>
```

- [ ] **Step 6: Initial commit + push**

```bash
cd /c/Users/lenovo/github-projects/tongguan-cangwu-guide
git add .
git commit -m "chore: scaffold repo with assets and README"
git push -u origin master
```

---

