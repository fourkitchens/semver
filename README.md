Semantic Versioning
===================

Introduction
------------

This package is published on:

```
Drupal.org (git@git.drupal.org:project/semver.git)
GitHub (git@github.com:fourkitchens/semver.git)
```

Setup
-----

  1. Fork this project or copy the files into your existing repository.
  2. Create the desired branches you wish to publish on.  This repo has:
```
stable
rc
beta
alpha
dev
x.x.x
```
  3. Protect these branches on GitHub
  4. Create a personal access token associated with your use and grant it access
  to repositories.
  5. Setup CircleCI to run on your project
  6. Commit at least one change following the [Angular commit guidelines](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines)
  7. Push your change up and verify CircleCI passes and has run on your desired branch.

Troubleshooting
---------------

  1. Your branch must have a named stable release branch.  See release.config.js
  2. Use the semantic-release/github not the semantic-release/git package.
