# Minmao Wang's Personal Academic Homepage

这是我的个人学术主页，使用 Jekyll 构建，基于 [academic-homepage](https://github.com/luost26/academic-homepage) 模板。

## 🚀 快速开始

### 本地预览

1. 安装 Jekyll（首次使用）：
```bash
gem install jekyll bundler
```

2. 安装依赖：
```bash
bundle install
```

3. 启动本地服务器：
```bash
bundle exec jekyll serve
```

4. 在浏览器访问：`http://localhost:4000`

### 部署到 GitHub Pages

这个仓库已经配置好可以直接部署到 GitHub Pages：

1. 确保仓库名为 `minmaowang.github.io`
2. 进入仓库 Settings → Pages
3. Source 选择 `Deploy from a branch`
4. Branch 选择 `main` 或 `master`
5. 点击 Save

几分钟后，网站将在 https://minmaowang.github.io 上线。

## 📝 更新内容

### 修改个人信息
编辑 `_data/profile.yml` 文件，包括：
- 姓名、职位、单位
- 邮箱和社交媒体链接
- 个人简介
- 教育背景
- 获奖情况

### 添加论文
在 `_publications/年份/` 目录下创建新的 Markdown 文件，参考现有文件格式。

### 添加新闻动态
在 `_news/` 目录下创建新的 Markdown 文件，参考现有文件格式。

### 更换照片
将新照片放在 `assets/images/` 目录，并在 `_data/profile.yml` 中更新路径。

## 📂 项目结构

```
.
├── _config.yml          # Jekyll 配置文件
├── _data/              # 数据文件
│   ├── profile.yml     # 个人信息（最重要）
│   ├── display.yml     # 显示设置
│   └── navigation.yml  # 导航菜单
├── _includes/          # 可复用的组件
├── _layouts/           # 页面布局
├── _publications/      # 论文发表
├── _news/             # 新闻动态
├── assets/            # 静态资源（图片、CSS、JS）
├── index.html         # 主页
└── publications.html  # 论文列表页
```

## 🔗 链接

- 网站地址：https://minmaowang.github.io
- GitHub：https://github.com/minmaowang
- Google Scholar：https://scholar.google.com/citations?user=vdJsnhIAAAAJ

## 📧 联系方式

如有问题，请联系：wmmmm@tju.edu.cn
