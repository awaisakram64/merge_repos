- creating git branch

option 1.

create branch
`git branch <branch name>`
list branch
`git branch`

option 2.

create branch and move HEAD to branch
`git checkout -b <branch name>`

`git branch`

Option 3. Creating a Branch from a Commit

use git log to find the commit sha
`git log`
use that sha to create a branch 
`git branch <branch name> <identifier>`


Option 4: Creating a Branch from Another Branch

creating feature4 from develop branch
`git checkout -b feature4 develop`


Merging Branches in a Local Repository

using fast forward

checkout to the main branch in which you want to merge other branch
`git checkout main`
merge this `awaisakram64/feature1` feature into main branch
`git merge awaisakram64/feature1`
