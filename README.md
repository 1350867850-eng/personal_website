# JunKai Chen Personal Website

这是一个用于通用求职展示的个人网站，使用纯 HTML、CSS 和 JavaScript 编写，不需要安装依赖，也不需要构建步骤。

线上地址：

https://1350867850-eng.github.io/personal_website/

## 本地启动

进入项目目录：

```bash
cd /Users/chenjunkai/Documents/Codex/personal_website
```

启动本地服务器：

```bash
python3 -m http.server 4173
```

然后在浏览器打开：

```text
http://127.0.0.1:4173
```

停止本地服务器时，在终端按：

```bash
Control + C
```

## 文件说明

- `index.html`：网站主要内容
- `styles.css`：页面样式和移动端适配
- `script.js`：移动端导航菜单
- `assets/junkai-chen-resume.pdf`：网站上的简历 PDF
- `.nojekyll`：让 GitHub Pages 按普通静态站点发布

## 修改网站内容

常见修改位置：

- 改名字、介绍、经历、联系方式：编辑 `index.html`
- 改颜色、字体、布局：编辑 `styles.css`
- 替换简历：把新的 PDF 放到 `assets/`，并命名为 `junkai-chen-resume.pdf`

修改后可以先用本地启动方式预览。

## 提交并推送到 GitHub

查看修改：

```bash
git status
```

提交修改：

```bash
git add .
git commit -m "Update website"
```

推送到 GitHub：

```bash
git push
```

推送后 GitHub Pages 会自动更新，通常需要几十秒到几分钟。

## GitHub Pages 设置

如果需要重新检查发布设置：

1. 打开 GitHub 仓库 `personal_website`
2. 进入 `Settings`
3. 点击 `Pages`
4. Source 选择 `Deploy from a branch`
5. Branch 选择 `main`
6. Folder 选择 `/ (root)`

发布地址是：

```text
https://1350867850-eng.github.io/personal_website/
```
