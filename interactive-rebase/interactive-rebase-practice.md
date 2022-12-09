# 인터렉티브 리베이스 실습

## 명령어
- `git rebase -i` 또는 `git rebase --interactive`

## 사용 가능한 커멘드
1. pick: use commit
2. reword: use commit, but edit the commit message
3. edit: use commit, but stop for amending
4. squash: use commit, but meld into previous commit
5. fixup: like "squash", but discard this commit's log message
6. exec: run command (the rest of the line) using shell
7. break: stop here (continue rebase later with 'git rebase --continue')
8. drop: remove commit
9. label: label current HEAD with a name
10. reset: reset HEAD to a label
11. merge: create a merge commit using the original merge commit's message (or the oneline, if no original merge commit was specified)