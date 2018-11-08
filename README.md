# tp-test

当前项目用于整个Lib项目最佳发布流程.

## GIT

### 基础

- 基线分支 master 和 develop 两个分支。master 用于记录稳定版，可用直接用于发布 develop 记录开发版本, 包括稳定版和beta版本。
- 正常开发从develop分支拉取代码（特殊情况从master上拉取分支，比如hotfix），
- 开发分支命名：dev/xxx，修复分支命名：fix/xxx
- 开发分支开发完通过PR合并到develop分支上，这一步必须做，用于告知同伴+CodeReview，此操作之前需要：
  - 切换到develop分支上，更新你本地的develop分支代码（这样做比在线上PR好点）
  - 切换到自己分支，进行test/lint测试
  - 进行合并操作，两个方法：
    - merge：切换到本地 develop 分支上，选择branch-to-merge分支合并，解决冲突
    - rebase：切换到brance-to-merge分支上，改变基线（修改起始点）到最新develop分支上。可以修改brance-to-merge上以前的commit记录
  - 完成后提交MR
- 提解决冲突
- 提交结束后删除本地分支和线上分支

### 工作流

- 1
- 2
- 3
- 4
- 5
- 6

### 如何提交
