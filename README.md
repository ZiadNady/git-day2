##git-day2

`git status`
##created a new file on main 
`touch file1`

##push it
`git add .`
`git commit -m "hello from main"`
`git push`

##create branches
`git branch dev`
`git branch test`
`git push origin dev`
`git push origin test`

##add files to each branch
`git checkout dev`
`touch file2`
`git commit -m "hello from dev"`
`git push`

`git checkout test`
`touch file3`
`git commit -m "hello from test"`
`git push`

##merge
`git checkout main`
`git merge dev`
`git merge test`
`git push`

##create a tag 
`git tag -a v1.7 -m "version 1.7"`
`git push origin v1.7`

##add another tag
git add .
`git commit -m "last commit form main"`
`git tag -a v2.0 -m "version 2.0"`
`git push origin v2.0`

##list all tags 
`git tag`

##image
![saba7 saba7](https://gate.ahram.org.eg/Media/News/2022/7/8/2022-637929147043649338-364.jpg)

##hidden file
`touch .gitignore`
