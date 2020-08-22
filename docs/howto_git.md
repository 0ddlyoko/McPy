- [How do we work with Git, PR & Github](#how-do-we-work-with-git-pr--github)

# How do we work with Git, PR & Github
- Master branch is only used for new versions. DO NOT MAKE A PULL REQUEST ON THIS BRANCH !
- Develop branch is used when there is a new feature
- For bug fix, there is two kind of bugs:
  - Important bugs:
    - These bugs will have "Important" tag on GitHub
    - When fixed, you should create 2 PR: One targetting master & one targetting develop
  - Other bugs:
    - These bugs will have "Non-Important" tag on GitHub
    - When fixed, PR should target "develop" branch

## Pull Request
- Use minimal commit ! Squash & rebase your changes whenever you edit your PR before submitting ! Don't do like [this](https://github.com/tazz4843/McPy/pull/20) guy !
- When you fix a bug, prefix your PR with [FIX]
- When you add a new feature, prefix your PR with [ADD]
- When you improve something, prefix your PR with [IMP]
- More informations about Squash & rebase [here](https://git-scm.com/book/fr/v2/Utilitaires-Git-Réécrire-l’historique) or [here (french)](https://www.ekino.com/articles/comment-squasher-efficacement-ses-commits-avec-git)