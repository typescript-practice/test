# tp-test

当前项目用于整个Lib项目最佳发布流程.

## GIT

- 基线分支 master 和 develop 两个分支. master 用于记录稳定版, 可用直接用于发布. develop 记录开发版本, 包括稳定版和beta版本.
- 正常开发从develop分支拉取代码（特殊情况从master上拉取分支，比如hotfix），
- 开发分支命名：dev/xxx，修复分支命名：fix/xxx
- 开发分支开发完通过PR合并到develop分支上，这一步必须做，用于告知同伴+CodeReview，此操作之前需要：
  - 

