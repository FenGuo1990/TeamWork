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
