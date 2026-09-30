# First_Web_project

娜娜的第一个项目 —— 一个用原生 HTML + CSS 写的个人主页。

## 在线访问

启用 GitHub Pages 后，地址为：

**https://muyuna77.github.io/First_Web_project/**

> 首次启用：打开仓库 → **Settings** → 左侧 **Pages** → Source 选择
> `Deploy from a branch`，Branch 选 `main`、目录选 `/ (root)`，保存后等 1～2 分钟即可访问。

## 文件说明

| 文件 | 作用 |
| --- | --- |
| `index.html` | 主页内容（标题、个人介绍、照片） |
| `style.css` | 页面样式（卡片布局、圆形头像、响应式适配） |
| `images/` | 存放照片，详见 `images/README.md` |
| `.nojekyll` | 关闭 GitHub Pages 的 Jekyll 处理，避免静态文件被忽略 |
| `.gitignore` | 排除 IDE 与系统产生的临时文件 |

## 怎么换自己的照片

1. 把照片文件重命名为 `photo.jpg`（全小写）
2. 放进 `images/` 目录，覆盖或新增都可以
3. 提交并推送，等 Pages 重新构建后刷新页面

照片没放之前，页面上会显示一个虚线的占位提示，不会出现裂图。

## 本地预览

直接双击 `index.html` 即可，或者在项目目录下起一个本地服务：

```bash
python3 -m http.server 8000
```

然后浏览器打开 <http://localhost:8000>。
