This repository contains a [GitHub action workflow](https://help.github.com/en/articles/workflow-syntax-for-github-actions) 
that sends a [`repository_dispatch` event](https://developer.github.com/v3/repos/#create-a-repository-dispatch-event) to 
another repo when a push to this repo occurs.

see [./.github/workflows/push-to-experimental.yml](./.github/workflows/push-to-experimental.yml)

The idea is that the remote repo can then start a build that integrates the updated version of this repo. 
