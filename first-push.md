# VIM

1. unstaged work (n)
2. staged work (n)
3. commit work (v)
4. push work (v)

`vim {FILENAME}`

{content}

1. ESC
2. Different ways to exit VIM
:q to quit (short for :quit)
:q! to quit without saving (short for :quit!)
:wq to write and quit
:wq! to write and quit, attempting to force the write if the file lacks write permission
:x to write and quit; like :wq but writes only if modified (short for :exit)
:qa to quit all (short for :quitall)
:cq to quit, without saving, with a nonzero exit code to indicate failure (short for :cquit)

NOTE: `nano FILENAME` is pretty much the same

`:set number` shows the file line number

--

# Git

`git reset HEAD {FILENAME}`
to unstage ('undo') a
`git add {FILENAME}`

`git checkout -- {FILENAME}`
to bring back deleted files in local that were once comitted

`git checkout -b {BRANCHNAME}`
to create a new branch

`git checkout {BRANCHNAME}`
to move among branches

1. Go to master
2. `git pull origin master`
3. `git merge new-branch`
4. `git push origin master`

******