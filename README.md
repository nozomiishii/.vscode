# Nozomi's VSCode Setup

## Get Started

```sh
  git submodule add git@github.com:nozomiishii/.vscode.git
```

## Git Submodules

追加

```sh
  git submodule add <submoduleのgit_URL>　
```

更新

```sh
  git submodule foreach git pull
  ## or
  git submodule <app_name> git pull
  ## or
  git submodule update --recursive --remote
```

## vscode の拡張機能の書き出し

[VSCode の extension を一括で Export/Import する - Qiita](https://qiita.com/kent-u/items/0f6de3f7526a1ec7eb7e)
