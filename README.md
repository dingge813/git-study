## Git Study
[Git Community Book](http://gitbook.liuhui998.com/)</br>
[Git Book EN](http://git-scm.com/book/en/v2)</br>
[Git Book ZH](https://git-scm.com/book/zh/v2)</br>
[Git 最佳实践](https://www.atlassian.com/git/)</br>
[Git 快速开始](http://rogerdudler.github.io/git-guide/)</br>
[Git Interactive Learning](http://pcottle.github.io/learnGitBranching/?demo)</br>
[Git revert用法](http://www.cnblogs.com/0616--ataozhijia/p/3709917.html)</br>
[Github 参考工作流](https://github.com/vincenthou/vincenthou.github.io/issues/1)</br>
[Git 分支最佳实践](https://segmentfault.com/a/1190000000434973) & [如何正确使用Git Flow](http://www.cnblogs.com/cnblogsfans/p/5075073.html)<br/>
[Git P4Merge](http://blog.csdn.net/xiaojia1100/article/details/50778987)</br>

### Issue Resolved
[You have not concluded your merge (MERGE_HEAD exists) git拉取失败](http://yijiebuyi.com/blog/5b55eb51ad49ce41e2de9c85dd4513ca.html)</br>

### Tips:
Staged工作空间某文件的修改: `git add <file>...`<br/>
Unstage工作空间某文件的修改: `git reset HEAD <file>...`<br/>
放弃工作空间某文件上的修改: `git checkout -- <file_name>...`</br>
提交Staged的文件到本地仓库: `git commit -m 'comment_info'`</br>
查看git提交记录日志: `git log` | `git log --oneline [-3]`</br>
删除本地分支: `git branch -D local_branch_name`</br>
删除远程分支: `git push origin :origin_branch_name`</br>
切换到远程develop分支并在本地新建关联分支develop: `git checkout -t origin/develop -b develop`</br>
拉取远程分支到本地: `git fetch origin origin_branch_name:local_branch_name`<br/>
提交记录: C0 -> C1 -> C2 ->C3</br>
&nbsp;&nbsp;产生一次新提交,抵消掉C1提交: `git revert C1`</br>
&nbsp;&nbsp;撤消C2,C3两次提交(--hard不仅仅撤消提交历史): `git reset --hard C1`</br>
拉取另一个分支的提交: `git cherry-pick other_branch_commit`<br/>
合并另一个分支所有提交并丢弃其提交历史: `git merge --squash other_branch_name`</br>
修改最后一次提交并改写comment后强制提交到远程: `git commit --amend` & `git push origin origin_branch_name -f`</br>
