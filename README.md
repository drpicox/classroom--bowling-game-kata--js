# Repository for the BowlingKata in JS

- Your name:
- Your email:
- Your GitHub username:
- Your NIU:

This is a base repository to do the UncleBob Bowling Game Kata
( http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata )
in Javascript.

Please, follow the instructions at https://david-rodenas.com/BowlingGameKata
or, in the case that you are from the university, follow the instructions
on your course board.

### Setup

Setup:

```zsh
$ yarn
```

Run:

```zsh
$ yarn test
```

### Commits

Commits must follow the same exact names that the Kata requires.
Commits must be in the right order.
There cannot be extra commits.

### Some useful git commands

Tips from:

- https://www.atlassian.com/git/tutorials/rewriting-history

Change the last commit:

```zsh
$ git commit --amend -m "New commit name"
```

Back to the previous commit:

```zsh
$ git reset --hard HEAD~1
```

Back to any commit:

```zsh
$ git reset --hard <commit-hash>
```

Push changes in history:

```zsh
$ git push --force-with-lease
```

List lost commits:

```zsh
$ git reflog
```
