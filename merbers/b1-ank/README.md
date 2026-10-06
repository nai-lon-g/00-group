# 我的 Git 学习笔记
git add：把工作区的改动放入暂存区（staging area），告诉 Git "这些改动我要提交"。

git commit：把暂存区的内容保存为一次版本快照，记录到本地仓库历史中。

git restore notes.md：丢弃工作区中未暂存的修改，让文件回到最后一次提交（或暂存）的状态。本次实验中它把追加的那句话删掉了。

commit vs push：

commit 只提交到本地仓库，不影响远程。

push 把本地提交上传到远程仓库，别人才能看到。