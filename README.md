# GitHub Pages 个人简历

这是一个可直接部署到 GitHub Pages 的静态个人简历网站。

## 你需要修改的内容

打开 `index.html`，把下面这些占位内容替换成你自己的信息：

- `你的名字`
- `前端开发 / 后端开发 / 产品设计 / 你要应聘的方向`
- 自我介绍
- 所在地、电话、邮箱、GitHub
- 技能清单
- 项目经历
- 工作经历
- 教育背景

## 如何部署到 GitHub

1. 登录 GitHub。
2. 新建一个仓库，建议仓库名使用：
   - `resume`
   - 或者 `你的用户名.github.io`
3. 点击 `Add file` -> `Upload files`。
4. 把当前目录里的 `index.html`、`style.css`、`README.md` 上传到仓库根目录。
5. 进入仓库的 `Settings` -> `Pages`。
6. 在 `Build and deployment` 中选择：
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`
7. 保存后等待几十秒，再刷新页面。

如果你的仓库名是 `你的用户名.github.io`，访问地址通常是：

`https://你的用户名.github.io/`

如果你的仓库名是 `resume`，访问地址通常是：

`https://你的用户名.github.io/resume/`

## 后续可选优化

- 增加头像
- 增加中英文切换
- 增加 PDF 下载按钮
- 接入项目作品链接
