# Cabal Stack Awesome Init

## What problem does this solve?
Saves having to go through the tedious `cabal init` and adding a .ghci file to show all warnings.

Has a useful .gitignore file as well.

## Instructions
Just git clone this project and then `cp dir/* newAwesomeProject/`, and then run `ghcid.sh` and wooooo!

Git clone this project, and run the following command (you'll need to modify the source and destination):

`rsync -av --progress ~/Projects/Haskell/CabalInit/ /path/To/Directory --exclude .git`
