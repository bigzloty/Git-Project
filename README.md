PS C:\Users\SCONZY\OneDrive\Desktop\learn_git> git init
Initialized empty Git repository in C:/Users/SCONZY/OneDrive/Desktop/learn_git/.git/
PS C:\Users\SCONZY\OneDrive\Desktop\learn_git> git add Third.txt
PS C:\Users\SCONZY\OneDrive\Desktop\learn_git> git commit -m adding Third.txt
[master (root-commit) 8ee5d1d] adding
1 file changed, 0 insertions(+), 0 deletions(-)
create mode 100644 Third.txt
PS C:\Users\SCONZY\OneDrive\Desktop\learn_git> git log
commit 8ee5d1d0559cf3b360a3ff30a3879fbce526b6bf (HEAD -> master)
Author: Alimaonu Emmanuel <bigzloty@gmail.com>
Date:

adding
PS C:\Users\SCONZY\OneDrive\Desktop\learn_git> git add Fourth.txt
PS C:\Users\SCONZY\OneDrive\Desktop\learn_git> git commit -m adding Fourth.txt
[master 32f31d9] adding
1 file changed, 0 insertions(+), 0 deletions(-)
create mode 100644 Fourth.txt
PS C:\Users\SCONZY\OneDrive\Desktop\learn_git> git rm Third.txt
rm 'Third.txt'
PS C:\Users\SCONZY\OneDrive\Desktop\learn_git> git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config advice.addEmptyPathspec false"
PS C:\Users\SCONZY\OneDrive\Desktop\learn_git> git commit -m removing Third.txt
[master 51ea992] removing
1 file changed, 0 insertions(+), 0 deletions(-)
delete mode 100644 Third.txt
PS C:\Users\SCONZY\OneDrive\Desktop\learn_git> git log
commit 51ea99215ea60db7dfe5cfa8cb5c13583303cbfb (HEAD -> master)
Author: Alimaonu Emmanuel <bigzloty@gmail.com>
Sun Jun 30 23:48:52 2024 +0100

removing

commit 32f31d9f97bc0bb87bd369425604affa40320b7b
Author: Alimaonu Emmanuel <bigzloty@gmail.com>
Date:

adding
commit 8ee5d1d0559cf3b360a3ff30a3879fbce526b6bf
Author: Alimaonu Emmanuel <bigzloty@gmail.com>
Date:

adding
PS C:\Users\SCONZY\OneDrive\Desktop\learn_git> git config -- global core.pager cat
PS C:\Users\SCONZY\OneDrive\Desktop\learn_git> git config -- global -- list
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
user.name=Alimaonu Emmanuel
user.email=bigzloty@gmail.com
core.pager=cat
