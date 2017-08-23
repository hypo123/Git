# Git
>git reset HEAD <file>... 取消暂存
  如 git reset HEAD read.txt 取消暂存的read.txt文件
>git checkout -- [file] 撤销修改，将它还原成上次提交时的样子
  如 git checkout -- read.txt 撤销对read.txt文件的修改
>master是当你运行git init时默认的起始分支名字
>origin是当你运行git clone时默认的远程仓库的名字.
  
>如果在不同的两个分支中，对同一文件的同一部分进行了不同的修改，进行合并的时候会产生冲突.

>HEAD是特殊指针，指向当前所在的本地分支；如果需要切换到别的分支工作，可以使用[git checkout 分支名],这样HEAD指针会指向新的分支.

>[变基]使用rebase命令可以将提交到某一个分支上的所有修改都移至另一个分支上.
>git checkout develop//将当前分支切换为develop
>git rebase master//将develop分支上的修改，变基到master分支上.
