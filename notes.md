# The beginning

## Create empty repo
git init

## Add README.md
git commit -m "Added the README.md file" or "enything in quotes"

## Add without -m opens editor
git commit

## After created repository on GitHub ##
# Branches
## Create new branch
git checkout -b new_feature

git add .
git commit -m "New feature changes"
git checkout master
git merge new_feature

##########################################################################

# Gitflow
brew install git-low-avh

git-flow feature start new_docs

git add .
git commit -m "Added new documents"

git-flow feature finish new_docs

# Making release
git-flow release start 2.0
git-flow release finish 2.0

# Making new feature branch
git-flow feature start NewFeature
# Send pull request
git-flow feature publsh NewFeature
