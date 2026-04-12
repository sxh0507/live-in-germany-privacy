# 隐私政策公开仓库使用说明

这个文件夹用于单独创建一个 **公开 GitHub 仓库**，只放隐私政策页面，供 Google Play 审核使用。

这样做的好处：

- 不需要把主项目 `live_in_germany_app` 改成公开
- 不影响你现在的主仓库代码管理
- 可以快速得到一个稳定、公开可访问的隐私政策链接

## 文件说明

- `index.html`
  公开首页
- `privacy-policy.html`
  隐私政策正式页面
- `privacy-policy.md`
  隐私政策 Markdown 备份

## 推荐的新仓库名称

建议你在 GitHub 新建一个 **公开仓库**，仓库名可以用下面任意一个：

- `live-in-germany-privacy`
- `de-quiz-privacy-policy`
- `germany-exam-privacy-policy`

我更推荐：

- `live-in-germany-privacy`

## GitHub 上具体怎么做

1. 打开 GitHub
2. 点击右上角 `+`
3. 选择 `New repository`
4. Repository name 填：
   `live-in-germany-privacy`
5. 选择：
   `Public`
6. 不需要勾选复杂模板
7. 点击 `Create repository`

## 上传文件

仓库创建后：

1. 进入新仓库主页
2. 点击 `Add file`
3. 选择 `Upload files`
4. 把这个文件夹里的 3 个文件一起拖进去：
   - `index.html`
   - `privacy-policy.html`
   - `privacy-policy.md`
5. 点击 `Commit changes`

## 开启 GitHub Pages

1. 进入新仓库
2. 点击 `Settings`
3. 左侧点击 `Pages`
4. 在 `Build and deployment` 下找到：
   `Source`
5. 选择：
   `Deploy from a branch`
6. Branch 选择：
   `main`
7. Folder 选择：
   `/ (root)`
8. 点击 `Save`

等待 1 到 5 分钟后，GitHub Pages 会生成公开链接。

## 你的隐私政策链接会是什么

如果仓库名是：

- `live-in-germany-privacy`

那么公开地址通常会是：

- 首页：
  `https://sxh0507.github.io/live-in-germany-privacy/`
- 隐私政策页：
  `https://sxh0507.github.io/live-in-germany-privacy/privacy-policy.html`

## Google Play 里填哪个链接

在 Google Play Console 的“隐私政策”字段里，建议填写：

- `https://sxh0507.github.io/live-in-germany-privacy/privacy-policy.html`

## 如果页面刚开还是 404

这是正常的，通常是因为 GitHub Pages 还没发布完成。

可以这样检查：

1. 回到仓库 `Settings > Pages`
2. 看有没有出现绿色提示：
   `Your site is live at ...`
3. 如果没有，等几分钟刷新一次

## 当前应用信息

- App name: 德国永居考试助手
- Support email: bandeshi.app@gmail.com
- Use case: Google Play 隐私政策公开链接
