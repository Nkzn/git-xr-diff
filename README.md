# git-xr-diff

(Pull | Merge) Request Diff Viewer.

Snippets for showing diff as (pull | merge) request list between commits.

* `gir-pr-diff`: Pull Request Diff Viewer for GitHub
* `git-mr-diff`: Merge Request Diff Viewer for GitLab

## Usage

1. Copy `git-pr-diff` (for GitHub) or `git-mr-diff` (for GitLab) into your PATH-ed directory
2. Run `$ git pr-diff [COMMIT-A] [COMMIT-B]` or `$ git mr-diff [COMMIT-A] [COMMIT-B]`
3. Diff is shown like below

```
$ git pr-diff TagA TagB
List pull requests for range: `TagA...TagB`

* #3606 feat(ui): foo
* #3608 fix(api): bar
* #3609 chore(deps): pin dependencies
```

## Requirements

* Ruby

## Article

https://qiita.com/Nkzn/items/60b30f1c9d0e33dfc424 (Written in Japanese)
