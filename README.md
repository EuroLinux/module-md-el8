# module-md-el8

Public repository with EuroLinux 8 modular metadata.

## How to: new beta version

For a new beta:

1. Pull changes `git pull origin master`
2. Remove everything from beta `rm -rf ./beta/*`
3. Copy appstream and powertools `cp -r appstream ./beta && cp -r powertools ./beta`
4. Commit and push
