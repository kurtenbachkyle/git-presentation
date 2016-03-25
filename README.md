# How I use Git

  All my aliases are in my my [gitconfig](./gitconfig).

  The scripts directory contains some of the scripts I used to make the presentation run.


## Resources for further learning
### General
  * `man 1 git`
  * `man 7 giteveryday`
  * `man 1 git-config`
  * [git book](https://git-scm.com/book/en/v2)
  * [git commit best practices](http://goo.gl/xwWq)

### difftools
  * vim, see my [gitconfig](./gitconfig)
  * [sublime](http://www.sublimerge.com/docs/vcs-integration.html)
  * [emacs](https://whatworks4me.wordpress.com/2011/04/13/view-git-diffs-in-emacs-using-ediff/)
  * [intellij](https://coderwall.com/p/gc_hqw/use-intellij-or-webstorm-as-your-git-diff-tool-even-on-windows)
  * eclipse doesn't seem to support this use case.  I'd recommend using a tool like [winmerge](http://winmerge.org/)

### the commands you might not have known
  * `[commitid]~1` refers to the commit ahead of a commit id
    * `HEAD~1` for the commit before the current `HEAD`
    * `master~3` for 3 commits before master
  * `git rebase -i HEAD~3` to modify or squash your last 3 commits 
  * `git rebase master` to make it seem like your branch happened after the current master
  * `git pull --rebase` to do the above and avoid a branch conflict
