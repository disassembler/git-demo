# Git Concepts
* DVCS - Distributed Version Control System

## File Storage
* Work
* Index (cache/stage)
* Object Store

# Git Commands

## Getting help
* help

## Creating a project
* init
* init --bare
* clone
* clone --orphan

## Modifying files/index
* add
* add -A
* add --patch
* rm
* mv
* commit

## Branches
* branch
* checkout -b
* checkout <branch>

## Comparing and patches
* diff <branch|commit|tag>
* diff --cached
* diff HEAD~
* apply -v --index
* apply -v

## Cleaning up
* reset
* reset --hard
* clean -fd
* rebase -i

## Working with others
* push
* pull
* merge
* rebase
* cherry-pick

## Releasing
* tag
* push --tags
* archive

# Strategies
* Commit large blocks of unrelated code (BAD)
* Commit small changes frequently (GOOD)
* Work on multiple tasks and tease apart commits (GOOD)
* Commit large blocks of code in fixed time intervals and tease apart into
  organized commits (GOOD)

All of the above strategies aside from the top one are valid strategies to use
with git. If you prefer to commit small changes frequently, make a change and
commit. If you prefer to Work on lots of things at once and deal with
committing later, that strategy works too, but become really good friends with
git add --patch if this is your style. Or, if you commit in blocks of code in
time intervals and break things apart later, that can be done as well. Your
tool of choice in that scenario is rebase -i. Remember, you can always alter
history until you push.

# Github Flavor
* Fork
* Pull Request (PR)

## Basic config:
<https://drupal.org/documentation/git/configure>

## Advanced config:
<https://github.com/disassembler/dotfiles/tree/master/git/gitconfig>
