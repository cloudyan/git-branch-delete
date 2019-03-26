# git-branch-delete

Interactive command line tool that makes it comfortable to delete several local Git branches at once.

功能支持

1. [x] 支持在分支列表中选择要删除的分支，并删除
2. [ ] 支持删除时询问是否删除远程的对应分支
3. [ ] 对于未合并到 master 的分支，进行删除提示
4. [ ] 支持输入要删除的分支，远程还是本地

Demo:

![Demo](https://raw.githubusercontent.com/stefanwille/git-branch-delete/master/demo.gif "Demo")

## Installation

```bash
npm i -g git-branch-delete
```

## Usage

```bash
git-branch-delete
```

This starts a command line UI that helps you to select and delete local Git branches.
