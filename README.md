## Git Study
[Git Community Book](http://gitbook.liuhui998.com/)</br>
[Git 文档](http://git-scm.com/book/en)</br>
[Git 最佳实践](https://www.atlassian.com/git/)</br>
[Git 快速开始](http://rogerdudler.github.io/git-guide/)</br>
[Git Interactive Learning](http://pcottle.github.io/learnGitBranching/?demo)</br>
[Git revert用法](http://www.cnblogs.com/0616--ataozhijia/p/3709917.html)</br>
[Github 参考工作流](https://github.com/vincenthou/vincenthou.github.io/issues/1)</br>

### Issue Resolved
[You have not concluded your merge (MERGE_HEAD exists) git拉取失败](http://yijiebuyi.com/blog/5b55eb51ad49ce41e2de9c85dd4513ca.html)</br>

#### 小贴士
删除远程分支: git push origin :branch-name</br>
切换到远程develop分支并在本地新建关联分支develop: git checkout -t origin/develop -b develop</br>
提交记录: C0 -> C1 -> C2 ->C3</br>
  产生一次新提交,抵消掉C1,C2,C3三次提交: git revert C1</br>
  撤消C2,C3两次提交(--hard不仅仅撤消提交历史): git reset --hard C1</br>
