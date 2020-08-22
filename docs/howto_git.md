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
- Use minimal commit ! Squash & rebase your changes whenever you edit your PR before submitting ! Don't do like [this](https://github.com/tazz4843/McPy/pull/20) guy !
- More informations about Squash & rebase [here](https://www.ekino.com/articles/comment-squasher-efficacement-ses-commits-avec-git), [here](https://git-scm.com/book/fr/v2/Utilitaires-Git-Réécrire-l’historique) & [here](https://lmgtfy.com/?q=how+to+squash+commits)