欢迎来到本关! 

本关任务为进阶任务，目标是让你学会如何定位提交中引入bug的记录并进行版本回退。


本关设计到一个针对某个shell脚本的系列修改提交，其中在某次修改时不慎破坏了脚本中的"if-then"致使脚本无法运行。

现确保第一次的提交中代码是正确的，而最后一次提交中代码是错误的。

具体任务：

1. 使用 `git log` 查看提交演化历史 
2. 利用 `git bisect` 自动定位首次引入 bug 的提交 
