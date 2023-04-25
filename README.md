# GitHub Flow - An example

An example implementation of GitHub Flow with CI & CD

## Repository Settings

The following settings are considered essential to achieve maximum workflow results:

### General

#### Pull Requests

- [x] Always suggest updating pull request branches
- [x] Allow auto-merge
- [x] Automatically delete head branches

##### Pushes

- [x] Limit how many branches and tags can be updated in a single push
  Up to `5` branches and tags can be updated in a push

### Branches

#### Branch protection rules

#### Default Branch

- `main`

##### Branch protection rules

- `main`
  - [x] Require a pull request before merging
    - [x] Require approvals `1`
  - [x] Require status checks to pass before merging
    - test
    - lint
  - [x] Require deployments to succeed before merging
    - [x] review
