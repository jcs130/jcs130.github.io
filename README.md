# GitHub Pages 个人主页

## 项目结构
```
jcs130.github.io/
├── _config.yml          # Jekyll 配置文件
├── index.md            # 首页
├── writing.md          # 文章作品集
├── journey.md          # 成长轨迹
├── publications.md     # 出版物
├── evidence.md         # 证据库
└── contact.md          # 联系方式
```

## 下一步操作

### 1. 在 GitHub 上创建仓库
1. 访问 https://github.com/new
2. 仓库名必须是: `jcs130.github.io`
3. 设置为 Public
4. 不要勾选 "Add a README file"
5. 点击 "Create repository"

### 2. 推送代码到 GitHub
在当前目录执行以下命令:

```bash
cd /Users/lizhongli/workspace/jcs130.github.io
git init
git add .
git commit -m "Initial commit: Personal homepage"
git branch -M main
git remote add origin https://github.com/jcs130/jcs130.github.io.git
git push -u origin main
```

### 3. 启用 GitHub Pages
1. 进入仓库页面 https://github.com/jcs130/jcs130.github.io
2. 点击 Settings
3. 左侧菜单找到 Pages
4. 在 "Source" 下选择:
   - Branch: main
   - Folder: / (root)
5. 点击 Save

### 4. 访问你的主页
等待 2-3 分钟后访问: https://jcs130.github.io

## 后续优化建议

### 如果需要更精致的排版
可以考虑:
1. 添加自定义 CSS 样式
2. 使用更现代的 Jekyll 主题(如 minimal, slate)
3. 添加文章摘要和标签
4. 在 Journey 页面添加时间线可视化

### 如果要更换用户名
1. GitHub Settings → Account → Change username
2. 从 `jcs130` 改为 `zhonglili`
3. 仓库会自动重定向,但建议同步更新仓库名

### 绑定自定义域名(可选)
如果有自己的域名(如 zhonglili.com):
1. 在域名 DNS 设置中添加 CNAME 记录
2. 在仓库 Settings → Pages → Custom domain 填入域名
