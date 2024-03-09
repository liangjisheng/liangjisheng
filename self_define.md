# self define

打造自定义的 github 主页格式，在账号下新建一个同名的仓库，新建 github action 工作流，参考本项目的 profile-summary-cards.yml 文件，编辑 README.md 文件，将代码 push 到远程仓库。

新建 Personal access tokens (classic), [教程参考](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens)

将创建好的 token 作为变量添加到当前仓库的 actions 下面的 Repository secrets 中。当工作流执行成功后，再次编辑 README.md 文件，把想要展示的图表添加进来，这样就能在个人主页看到了。

[整个配置教程](https://github.com/vn7n24fzkq/github-profile-summary-cards)
