# How to spray in GitHub's activity log

Use the following tool:
[![](https://img.shields.io/badge/Made%20With-Github%20Spray-lightgrey.svg?style=for-the-badge&logo=github)](https://github.com/Annihil/github-spray)  
[![](https://i.imgur.com/2DrTn0Z.gif)](https://github.com/Annihil/github-spray)

The tool pushes to `master` branch of a different repo, in this case `github-spray-commits`.
Open a workspace and use the following code to replicate:

``` bash
npm i -g github-spray
github-spray -t "./abot\." --multiplier 10 --push --force --origin https://github.com/andreasbotsikas/github-spray-commits.git
```
