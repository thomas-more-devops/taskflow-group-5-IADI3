# Practice – Raja (Assignment 10)

## git log --oneline (before interactive rebase)
```
a450ebb docs: add practice step 4
2a9f017 docs: add practice step 3
df11dc7 docs: add practice step 2
9c62dd9 docs: add practice step 1
6423c33 chore: integrate all features using final_version
464773c Merge pull request #22 from thomas-more-devops/feature/task-categories
```

## git log --oneline (after interactive rebase – step 2 squashed into step 1)
```
662a2e3 docs: add practice step 4
4836a68 docs: add practice step 3
0099582 docs: add practice step 1
6423c33 chore: integrate all features using final_version
464773c Merge pull request #22 from thomas-more-devops/feature/task-categories
```

## git reflog
```
a252e67 HEAD@{0}: commit: docs: finish WIP notes
137632a HEAD@{1}: checkout: moving from hotfix/urgent-bug-raja to practice/raja
cb62c11 HEAD@{2}: commit: fix: urgent hotfix practice
6423c33 HEAD@{3}: checkout: moving from main to hotfix/urgent-bug-raja
6423c33 HEAD@{4}: checkout: moving from practice/raja to main
137632a HEAD@{5}: reset: moving to HEAD
137632a HEAD@{6}: cherry-pick: docs: add extra tip
662a2e3 HEAD@{7}: checkout: moving from practice/raja-extra to practice/raja
137632a HEAD@{8}: commit: docs: add extra tip
662a2e3 HEAD@{9}: checkout: moving from practice/raja to practice/raja-extra
662a2e3 HEAD@{10}: rebase (finish): returning to refs/heads/practice/raja
662a2e3 HEAD@{11}: rebase (pick): docs: add practice step 4
4836a68 HEAD@{12}: rebase (pick): docs: add practice step 3
0099582 HEAD@{13}: rebase (squash): docs: add practice step 1
9c62dd9 HEAD@{14}: rebase (start): checkout HEAD~4
a450ebb HEAD@{15}: commit: docs: add practice step 4
2a9f017 HEAD@{16}: commit: docs: add practice step 3
df11dc7 HEAD@{17}: commit: docs: add practice step 2
9c62dd9 HEAD@{18}: commit: docs: add practice step 1
6423c33 HEAD@{19}: checkout: moving from main to practice/raja
6423c33 HEAD@{20}: checkout: moving from setup/professional-repo to main
7b341e0 HEAD@{21}: commit: feat: add professional repository structure
6423c33 HEAD@{22}: checkout: moving from main to setup/professional-repo
6423c33 HEAD@{23}: commit: chore: integrate all features using final_version
464773c HEAD@{24}: pull origin main: Fast-forward
00d5da3 HEAD@{25}: checkout: moving from main to main
00d5da3 HEAD@{26}: merge feature/task-priorities: Fast-forward
5e4979a HEAD@{27}: checkout: moving from feature/task-priorities to main
00d5da3 HEAD@{28}: commit (merge): Resolve merge conflict in task input placeholder
d52704d HEAD@{29}: checkout: moving from main to feature/task-priorities
```

## git stash list (while work was stashed)
```
stash@{0}: On practice/raja: WIP: working on search feature
```
