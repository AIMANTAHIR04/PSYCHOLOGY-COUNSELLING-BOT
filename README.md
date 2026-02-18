# GIT TEST


# RULES:
1. only use terminal
2. clone the repository
3. create your own branch, and your own directory having your name on it, and only use these.
4. document your every command(with reason) in process.md
5. final result must be pushed to origin

## Phase 1
1. create another branch from your branch
2. modify/add file process.md differently in both branches
3. commit
4. now integrate the second branch into your branch using rebase
5. resolve conflicts 
6. show compact visual history of commits

## Phase 2
1. create .env
2. commit it(not supposed to happen)
3. remove it from the Git tracking
4. only keep it locally
5. add it to .gitignore
6. amend previous commit properly

## Phase 3
1. squash last 3 commits in 1.
2. reword a commit that is not the latest
3. completely remove one commit from history

## Phase 4
1. push branch
2. make a new commit locally
3. others might also be doing their work and change something
4. update your branch properly
5. resolve conflicts if needed
6. no force push allowed


## Phase 5
1. Delete a branch
2. recover it 

## Phase 6
1. create 5 sequential commits modifying a file
2. add a bug in one commit
3. identify exact commit using *git bisect* and mark it
4. fix bug in new commit(do not rewrite history)

## Phase 7
1. before pushing the final results, perform:
    1. check the integrity of the repo
    2. check the current state
    3. display a visual commit tree of the entire repository
