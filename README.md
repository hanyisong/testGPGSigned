sign to GPG encrypt

### 如果没有GPG签名commit就不能确定是否为本人提交

例如：
修改本地邮箱为别人的并push到仓库后，github中的commit会显示那个人的头像
git --config user.email ‘别人的邮箱'
经典乌龙（模仿Linus Torvalds）：https://github.com/slimsag/linux
