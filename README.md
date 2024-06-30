# oss2024_intro
## Task-1: Checkout your branch. 
Note that, there are 7 branches (4 students per branch).
The branch assignment is as follows:\
intro1 --> 기진근, 김동규, 김미리, 김성준\
intro2 --> 김예지, 김정주, 김주영, 김진희\
intro3 --> 박민재, 박진영, 박진우, 백제민\
intro4 --> 서지원, 석민지, 심재성, 심훈\
intro5 --> 오정빈, 유지희, 이규민, 이영진\
intro6 --> 이웅, 이유진, 이은진, 이준열\
intro7 --> 이환석, 주선양, 홍수지, 홍승현\ 
(command: `$ git checkout intro<N>`)\

## Task-2: Open the intro.txt file, and write your name and department in it.
(format: 이름, 학과)\
Commit the changes.\
[Therefore, intro<N> branch is updated while origin/intro<N> is still in the previous commit]

## Task-3: Now push your branch to origin.\
command: `git push origin intro<N>`\
[With a successful push, We expect that origin/intro<N> would be updated.\
However, the push will be unsuccessful if your friend has pushed to the same branch first. If so, do the following]

## Task-3.1: Do the following only if the push was unsuccessful.
Fetch-Merge-Push\

Fetch the updated origin\
`git fetch origin`\

Merge the remote branch into your branch\
`git merge origin/intro<N>`\

Push again.
`git push origin intro<N>`\
