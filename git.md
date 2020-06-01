## Basics

`git clone [url]` makes a copy of the repository (from `url`) in your system.

`git fork [url]` makes a copy of the repository (from `url`) to your Github
account.

`git pull` updates your local copy with the changes pushed to the Github repo.

`git push` updates the Github repo with the changes made on your local copy.

`git checkout [branch]` allows you to switch to a `branch`.

`git remote set-url [remote] [url]` changes an existing repository `url` (eg
`git remote set-url origin git@github.com:_USERNAME/REPOSITORY_.git` for SSH)
for the `remote` repo.

## Advanced

`git rebase [branch]` prepend commits from `branch` to the current branch.

`git reset [commit]` move the current HEAD to `commit` (often specified as
`HEAD~i` where `i` is the number of commits backwards you'd like to move). 

## Submodules

`git submodule add [url] [folder]` adds a submodule from `url` to `folder`.

`git submodule init` creates the (necessary) local configuration file for all
submodules in a repo.

`git submodule update` updates registered submodules (ie `submodule add`) by
fetching any missing commits.

## Miscellaneous 

`git hash-object` computes the object ID value for an object
