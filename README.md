# Flura Support Pages

觉流 (Flura) 官方支持页面

## 包含页面

- `index.html` - 技术支持主页
- `privacy.html` - 隐私政策
- `terms.html` - 服务条款

## 部署到 GitHub Pages

### 步骤 1: 创建公开仓库

1. 访问 https://github.com/new
2. 仓库名称: `flura-support`
3. 选择 **Public** (公开)
4. 点击 "Create repository"

### 步骤 2: 推送代码

```bash
cd /Users/xiaoyangjiang/flura-support
git add .
git commit -m "Initial commit: Support pages for Flura app"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/flura-support.git
git push -u origin main
```

### 步骤 3: 启用 GitHub Pages

1. 进入仓库 Settings
2. 左侧菜单选择 "Pages"
3. Source 选择 "Deploy from a branch"
4. Branch 选择 "main" 和 "/ (root)"
5. 点击 "Save"

### 步骤 4: 等待部署

几分钟后，你的页面将发布在：
```
https://YOUR_USERNAME.github.io/flura-support/
```

## App Store Connect 填写

完成部署后，在 App Store Connect 中填写：

- **技术支持网址**: `https://YOUR_USERNAME.github.io/flura-support/`
- **隐私政策网址**: `https://YOUR_USERNAME.github.io/flura-support/privacy.html`

## License

© 2024 Flura. All rights reserved.
