# push-to-other-repo
Our first GitHub Action: Push commits from one repo to another


## Inputs
#### `source-directory` (argument)
#### `destination-github-username` (argument)
#### `destination-repository-name` (argument)
#### `user-email` (argument)
#### `destination-repository-username` (argument) [optional]
#### `target-branch` (argument) [optional]
#### `API_TOKEN_GITHUB` (environment)
E.g.: 
  `API_TOKEN_GITHUB: ${{ secrets.API_TOKEN_GITHUB }}`