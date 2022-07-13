# VSCode base rules
To use this repository, add it as a submodule in your project.

## Install
- `cd` into the root directory of your local `git` project.
- run `git submodule add git@github.com:tabbify/tabbify-vscode-settings.git ./.vscode`.

## Update
- `cd` into your cloned `./.vscode` folder.
- run `git pull`.
- run `git checkout origin/main`.
- `cd` back out, into your root project.
- run `git submodule update`.

## Remove
- run `git submodule rm ./.vscode` from your project's root.
