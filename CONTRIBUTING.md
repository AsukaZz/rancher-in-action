## 如何贡献项目

领取或创建新的 [Issue](https://github.com/dclingcloud/rancher-in-action/issues)，如 [issue 1](https://github.com/dclingcloud/rancher-in-action/issues/1)，添加自己为 `Assignee`。

在 [GitHub](https://github.com/dclingcloud/rancher-in-action/fork) 上 `fork` 到自己的仓库，如 `awesomedpm/rancher-in-action`，然后 `clone` 到本地，并设置用户信息。

```bash
$ git clone https://github.com/awesomedpm/rancher-in-action.git
$ cd rancher-in-action
```

修改代码后提交，并推送到自己的仓库，如果是修改Issue，注意修改提交消息为对应 Issue 号和描述。

```bash
# Update the content

$ git commit -a -s

# In commit msg dialog, add content like "Fix issue #1111: describe your change"

$ git push
```

在 [GitHub](https://github.com/dclingcloud/rancher-in-action/pulls) 上提交 `Pull Request`，添加标签，并邀请维护者进行 `Review`。

定期使用项目仓库内容更新自己仓库内容。

```bash
$ git remote add upstream https://github.com/dclingcloud/rancher-in-action

$ git fetch upstream

$ git rebase upstream/master

$ git push -f origin master
```

## 排版规范

本开源书籍遵循 [中文排版指南](https://github.com/mzlogin/chinese-copywriting-guidelines) 规范。
