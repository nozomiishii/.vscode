# Nozomi's VSCode Setup

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
