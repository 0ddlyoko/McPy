- [How do we work with Git, PR & Github](#how-we-use-git)

# How we use Git
- The main branch is only used for the currently stable versions. DO NOT MAKE A PULL REQUEST ON THIS BRANCH !
- Develop branch is used when there is a new feature
- For bug fix, there is two kind of bugs:
  - Important bugs:
    - These bugs may be severe - fixing them is a high priority
    - These bugs will have "Important" tag on GitHub
    - When fixed, you should create 2 PRs: One targetting the main branch & one targetting the development branch
    - Make sure to test rigorously - the changes could be applied in production code fairly soon, buggy code would be disastrous
  - Other bugs:
    - These bugs will have "Non-Important" tag on GitHub
    - When fixed, PR should target the development branch
- Use a minimal amount of commits ! Squash & rebase your changes whenever you edit your PR before submitting ! Don't do like [this](https://github.com/tazz4843/McPy/pull/20) guy !
- More informations about Squash & rebase [here](https://www.ekino.com/articles/comment-squasher-efficacement-ses-commits-avec-git), [here](https://git-scm.com/book/fr/v2/Utilitaires-Git-Réécrire-l’historique) & [here](https://lmgtfy.com/?q=how+to+squash+commits)
