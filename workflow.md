#Group Five Rocks GIT!

<h6>Practice GIT branches and group workflows in this directory</h6>
**never ever push to master**


`Git Clone https://.....git`

*in master branch* 

`Git Pull`

`Git Checkout -b <branch name>`

`Git Add -A`

`Git Commit -m "I rule!"`

`Git push origin <branch name>`

**never ever push to master**

*go to github.com and in the repo, create a pull request with a comment. Communicate with the group on your changes and make sure not to be a dick and merge without a confirmation from someone....*

*Once the merge is accepted and you have communicated your changes, everyone must go to their master branch and git pull and then checkout to the branch you are working on and git merge master while you are in your working branch*


<h6>Git Branch Commands to know:</h6>

`Git Branch` 

*lists all the branches in your repo*

`Git Branch <branch>`

*Creates a new branch called <branch>, but does not check out into that new branch!!!*

Use this instead:

`Git checkout -b <branch>`

*Git checkout takes you to that branch specified*


`Git Branch -d <branch>`

*Deletes the specified branch. This is the safe operation in that Git prevents you from deleting the branch if it has unmerged changes*

`Git Branch -D <branch>`

*UNSAFE, its a forced delete with the capital D, but if you know for sure you want to throw away unmerged changes, use it*

`Git Branch -m <branch>`

*Rename the current branch*

<h4>never ever push to master</h4>

Please see this link for more info:

[Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)
