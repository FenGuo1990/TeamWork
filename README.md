# TeamWork
 Branch-Pull-Rebase-Merge-Push, Pull Request
# Repositories 的目的
熟悉团队工作流程
## 个人一般流程
- 建立仓库-不断修改、完善代码【Commit】
- 建立分支，完成子功能【branch】
- Pull 从Web 同步到 PC
- Rebase 将整个分支步骤，定位到Master最后的位置（如果Master没有增加的内容，就省略）
- Merge 将分支合并到主干
- Push、Publish 将PC同步到Web
- Pull Requset 提出请求，将分支合并到Master（会有讨论区等）

## 普通的Merge
Commit的时间顺序不改变，会讲所有commit直接合并到Master内，并且所有Commit按照时间顺序排序
## Rebase
Rebase 是把整个分支 放到Master最后的部分
- Master分支无法使用
- 如果指针指在 Master最后部分，就没法Rebase
- Rebase后，会把Master的新加内容，添加到分支上，并重新排序

## Pull Requst
一般发出新功能请求，并添加一定的代码，请求加入主分支。经过代码审查后，加入主分支，成为新版本
- 融合三种方式：Merge Squash Rebase
- Merge Rebase 已经解释过了
- Squash 就是将分支压缩，并加入Master
- Draft 是先不进行代码审查，经过同意后，再进行代码审查
- Merge: 产生一个merge的commit，Rebase 不会产生