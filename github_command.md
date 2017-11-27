# Create a new repository
`git init`

# See the status of the repository that was created
`git status`
# Track the repository
`git add <file>`

# Make a branch
`git checkout -b <branch name>`

# Show all the commits
`git log`

# Switch to a different branch
`git checkout <branch>`

# To see what branches you have 
`git branch`

# To merge
`git checkout <branch that I want the SECOND branch to be merged into>`
`git merge <SECOND branch>`

## Example
If I want to merge `dev` branch into `master` branch I would do
`git checkout master`
`git merge dev`


# To commit
`git commit -m "<message>"`

# Changes to tracked files
`git diff`

# To push to github
`git push -u origin master`
