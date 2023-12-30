# gitAllOneHours

# 查看所有分支

git branch -a

# 合并的三种方式
# 默认--快进 --fast-forward !important 得先理解什么时候会发生快速合并，并不是每次 merge 都会发生快速合并
git merge 

# 禁止快进合并 !important 会生成一个新的提交
git merge --no-ff

# 不会生成新的提交
git merge --squash

# git stash 记住一点就是 必须添加到暂存区才可以

# git tag 就是常用于发布版本  !important 创建带有说明的标签，用 -a 指定标签名，-m 指定说明文字

# 将当前分支的指针指向为指定 commit（!NOTICE 该提交之后的提交都会被移除），同时重置暂存区，但工作区不变

git reset <commit_hashId>
# 等价于 git reset --mixed  <commit_hashId> 保留前者；如果保留双方则采用 --soft

# git Hooks的常用配置及回调

