# 你好，欢迎来到我的 GitHub 👋

我正在学习 GitHub，希望把优秀的开源项目用到自己的项目中，也欢迎大家教我如何使用 GitHub。如果你有适合初学者的项目或建议，欢迎通过 Issue 留言。

## 怎样寻找可以使用的开源项目

1. 打开 [GitHub 项目搜索](https://github.com/search?type=repositories)，输入项目用途或技术关键词，例如 `image editor`、`python game`，也可以加上语言筛选，如 `language:python`。
2. 查看项目的 README，确认它的功能、安装方式和使用要求；再看看最近是否仍有更新，以及 Issues 中有没有未解决的问题。星标数可以作为参考，但不代表项目一定适合你。
3. **先检查许可证（License）**。许可证会说明是否可以复制、修改或商用，以及需要保留哪些声明。没有许可证的项目默认不能随意复用；不确定时先询问作者。
4. 按项目 README 的说明安装或引用它。若要修改项目，可以点击 **Fork** 将它复制到自己的 GitHub 账号；若只想下载到电脑，可点击 **Code** 复制 HTTPS 地址，再用下面的命令：

```bash
git clone https://github.com/OWNER/REPOSITORY.git
cd REPOSITORY
```

把 `OWNER/REPOSITORY` 换成项目页面上的所有者和仓库名。复用代码时遵守许可证，并保留要求的版权和许可证声明。
直接克隆别人的仓库通常只有读取权限，不能把修改推送回去；想上传自己的修改，请先 Fork，再克隆并推送到自己账号下的 Fork。

## GitHub 入门：保存并分享一次修改

GitHub 是托管和协作平台；Git 是在电脑上记录代码修改的工具。安装 Git 并配置好账号后，可以这样开始：

1. 在 GitHub 上创建仓库（repository），或者先 Fork 一个你想尝试的项目。
2. 在仓库页面点击 **Code**，复制 HTTPS 地址，在终端运行 `git clone 仓库地址`，把仓库下载到电脑。
3. 修改文件后，在仓库目录的终端运行以下命令（把文件名换成你修改的文件）：

```bash
git status
git add 文件名
git commit -m "说明这次修改"
git push
```

`status` 查看改动，`add` 选择要提交的文件，`commit` 在本地记录改动，`push` 将记录上传到 GitHub。首次推送时，Git 可能会提示配置账号或认证方式；按提示操作即可。不要把密码、访问令牌或密钥写进仓库。

想把修改贡献回别人的项目时，先 Fork，再修改并推送到自己的 Fork，最后在 GitHub 上点击 **Contribute / Open pull request** 发起 Pull Request，请原项目维护者审核。遇到问题时可以在仓库的 **Issues** 中搜索已有问题，或礼貌地提交新问题。

## 新手可以从这里开始

- 先搜索一个感兴趣的小项目，读 README 和 License。
- Fork 项目，尝试按说明运行；不确定时先不要直接覆盖原项目。
- 记录遇到的问题或学习笔记，再逐步尝试修改和提交。

如果你愿意帮助我，欢迎推荐项目，并告诉我它适合做什么、使用什么语言，以及应该从哪一步开始。
