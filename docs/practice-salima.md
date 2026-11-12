# Salima's Git practice

## Interactive rebase

## Cherry-pick

## Stash

Cherry-pick copies a selected commit to another branch.

Work in progress: practicing git stash.

## Git log before rebase

bd03fed practice: add stash section
a5b76d6 practice: add cherry-pick section
01f55c4 practice: add rebase section
40d4345 practice: create Git practice notes
6423c33 chore: integrate all features using final\_version
464773c Merge pull request #22 from thomas-more-devops/feature/task-categories
920bc2c Resolve task input placeholder for category feature
f7d1435 feat: add task category management
00d5da3 Resolve merge conflict in task input placeholder
5e4979a Update task input placeholder for better UX
d52704d feat: add task priority system
602c914 last update: 2024-06-19 15:00:00s end of file
7d92821 Merge pull request #18 from Raja798990/docs/features
5ea97a2 Merge pull request #19 from Raja798990/docs/js-comments
eb95fa6 Merge pull request #20 from Raja798990/chore/pr-template
e551048 Create pull\_request\_template.md
20b4a4b Create pull\_request\_template.md
d50d54a Update app.js
65e6b04 Create FEATURES.md
c737cab Merge pull request #14 from Raja798990/docs/license
dc2e763 Merge pull request #17 from Raja798990/docs/css-comments
6813975 Merge pull request #16 from Raja798990/docs/setup-guide
6f1522f Merge pull request #15 from Raja798990/docs/architecture
4e75db6 Merge pull request #13 from Raja798990/docs/contributing
ce027d8 docs: add CSS comments explaining design choices
2617c2d docs: add setup guide
fa1b203 docs: add architecture documentation
846700c docs: add MIT license
cfd165c docs: add contributing guidelines
1fd4ade docs: add architecture documentation
b46cc29 docs: add MIT license
cc526ed Merge pull request #2 from Raja798990/docs/html-comments
0588f74 docs: add comments to index.html
db3232f Merge pull request #1 from Raja798990/docs/readme-update
dc7ce0d docs: enhance README.md with additional sections
3807250 Add README.md
5237c93 Add scripts/app.js
68c8adf Add styles/main.css
67f867e Add index.html
38ab305 Add .gitignore

## Git log after rebase

df5270e practice: document stash exercise
a5b76d6 practice: add cherry-pick section
01f55c4 practice: add rebase section
40d4345 practice: create Git practice notes
6423c33 chore: integrate all features using final\_version
464773c Merge pull request #22 from thomas-more-devops/feature/task-categories
920bc2c Resolve task input placeholder for category feature
f7d1435 feat: add task category management
00d5da3 Resolve merge conflict in task input placeholder
5e4979a Update task input placeholder for better UX
d52704d feat: add task priority system
602c914 last update: 2024-06-19 15:00:00s end of file
7d92821 Merge pull request #18 from Raja798990/docs/features
5ea97a2 Merge pull request #19 from Raja798990/docs/js-comments
eb95fa6 Merge pull request #20 from Raja798990/chore/pr-template
e551048 Create pull\_request\_template.md
20b4a4b Create pull\_request\_template.md
d50d54a Update app.js
65e6b04 Create FEATURES.md
c737cab Merge pull request #14 from Raja798990/docs/license
dc2e763 Merge pull request #17 from Raja798990/docs/css-comments
6813975 Merge pull request #16 from Raja798990/docs/setup-guide
6f1522f Merge pull request #15 from Raja798990/docs/architecture
4e75db6 Merge pull request #13 from Raja798990/docs/contributing
ce027d8 docs: add CSS comments explaining design choices
2617c2d docs: add setup guide
fa1b203 docs: add architecture documentation
846700c docs: add MIT license
cfd165c docs: add contributing guidelines
1fd4ade docs: add architecture documentation
b46cc29 docs: add MIT license
cc526ed Merge pull request #2 from Raja798990/docs/html-comments
0588f74 docs: add comments to index.html
db3232f Merge pull request #1 from Raja798990/docs/readme-update
dc7ce0d docs: enhance README.md with additional sections
3807250 Add README.md
5237c93 Add scripts/app.js
68c8adf Add styles/main.css
67f867e Add index.html
38ab305 Add .gitignore

## Git reflog

17599e1 HEAD@{0}: checkout: moving from practice/salima-hotfix to practice/salima
46d0c37 HEAD@{1}: commit: practice: simulate an urgent fix
17599e1 HEAD@{2}: checkout: moving from practice/salima to practice/salima-hotfix
17599e1 HEAD@{3}: reset: moving to HEAD
17599e1 HEAD@{4}: cherry-pick: practice: explain cherry-pick
df5270e HEAD@{5}: checkout: moving from practice/salima-cherry-source to practice/salima
95f8257 HEAD@{6}: commit: practice: explain cherry-pick
df5270e HEAD@{7}: checkout: moving from practice/salima to practice/salima-cherry-source
df5270e HEAD@{8}: rebase (finish): returning to refs/heads/practice/salima
df5270e HEAD@{9}: rebase (reword): practice: document stash exercise
bd03fed HEAD@{10}: rebase: fast-forward
a5b76d6 HEAD@{11}: rebase (start): checkout HEAD\~4
bd03fed HEAD@{12}: rebase (finish): returning to refs/heads/practice/salima
bd03fed HEAD@{13}: rebase (start): checkout HEAD\~4
bd03fed HEAD@{14}: rebase (finish): returning to refs/heads/practice/salima
bd03fed HEAD@{15}: rebase (start): checkout HEAD\~4
bd03fed HEAD@{16}: rebase (finish): returning to refs/heads/practice/salima
bd03fed HEAD@{17}: rebase (start): checkout HEAD\~4
bd03fed HEAD@{18}: commit: practice: add stash section
a5b76d6 HEAD@{19}: commit: practice: add cherry-pick section
01f55c4 HEAD@{20}: commit: practice: add rebase section
40d4345 HEAD@{21}: commit: practice: create Git practice notes
6423c33 HEAD@{22}: checkout: moving from main to practice/salima
6423c33 HEAD@{23}: pull origin main: Fast-forward
00d5da3 HEAD@{24}: checkout: moving from feature/task-categories to main
920bc2c HEAD@{25}: commit: Resolve task input placeholder for category feature
f7d1435 HEAD@{26}: checkout: moving from practice/category-conflict to feature/task-categories
5fc13f8 HEAD@{27}: commit (merge): Resolve merge conflict in task input placeholder
f7a8940 HEAD@{28}: checkout: moving from practice/conflict-other-side to practice/category-conflict
c290fe4 HEAD@{29}: commit: Practice: use alternative task placeholder
f7d1435 HEAD@{30}: checkout: moving from practice/other-placeholder to practice/conflict-other-side
f7a8940 HEAD@{31}: checkout: moving from practice/category-conflict to practice/other-placeholder
f7a8940 HEAD@{32}: merge practice/other-placeholder: Fast-forward
dfb9225 HEAD@{33}: checkout: moving from practice/other-placeholder to practice/category-conflict
f7a8940 HEAD@{34}: commit: Practice: change task input placeholder differently
dfb9225 HEAD@{35}: checkout: moving from practice/category-conflict to practice/other-placeholder
dfb9225 HEAD@{36}: commit: Practice: update task input placeholder
f7d1435 HEAD@{37}: checkout: moving from feature/task-categories to practice/category-conflict
f7d1435 HEAD@{38}: commit: feat: add task category management
00d5da3 HEAD@{39}: checkout: moving from main to feature/task-categories
00d5da3 HEAD@{40}: pull origin main: Fast-forward
c737cab HEAD@{41}: checkout: moving from docs/css-comments to main
ce027d8 HEAD@{42}: commit: docs: add CSS comments explaining design choices
cc526ed HEAD@{43}: checkout: moving from main to docs/css-comments
cc526ed HEAD@{44}: checkout: moving from docs/setup-guide to main
2617c2d HEAD@{45}: commit: docs: add setup guide
cc526ed HEAD@{46}: checkout: moving from main to docs/setup-guide
cc526ed HEAD@{47}: clone: from https://github.com/Raja798990/taskflow-group-5-IADI3.git

## Git stash list before pop

stash@{0}: On practice/salima: WIP: practicing git stash

