# Git

## Local:

- `init`: initialize the repository
- `status`: looks at the state of the respository
- `add`: puts file(s) into the "staging area"
- `commit`: the "save" message
  - `commit -m ""`: allows for a quick oneline commit message
- `diff`: differences between states/files
- `log`: our history
    - `log --oneline`: to see the simple oneline log
    - `log --oneline --decorate --all --graph`: shows you all the branches, labled, and grpah nodes 

## Remotes:

- `remote add <name> <URL>`: sets a URL to the <name>
- `push origin master`: sends master branch to origin
- `pull origin master`: sends master branch to local computer
