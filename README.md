# Git check useless merge

Deny push if first parent of last merge commit is not remote branch.

To preserve a clean git history.

## Usage

```
cp update /path/to/repository/.git/hooks
chmod +x /path/to/repository/.git/hooks/update
```

## Environment

- Git
- Ruby

## Reference

- [Git - An Example Git-Enforced Policy](https://git-scm.com/book/en/v2/Customizing-Git-An-Example-Git-Enforced-Policy)
- [git push - Git receive/update hooks and new branches - Stack Overflow](http://stackoverflow.com/questions/3511057/git-receive-update-hooks-and-new-branches)
