# PROJECT: UET CLASS

*A complex university project.*

## Introduction

Contributors:
- thai-nm
- QuanVo308
- Minh0511

## Environments
There are 2 environments:
- `Production`: To show the product
- `Develop`: used for development and bug fixing puposes
## Github workflow

| Branch     | Status             | Purpose                            | Source branch | Note                                                                           |
| ---------- | ------------------ | ---------------------------------- | ------------- | ------------------------------------------------------------------------------ |
| `master`   | __stable__         | Only for production environment    | ORIGIN BRANCH | Only approve pull requests from `develop` branch with at least 1approver       |
|            |                    |                                    |               | Approvers: `QuanVo308`, `thai-nm`, `Minh0511`                                  |
|            |                    |                                    |               | DO NOT PUSH directly to this branch                                            |
| `develop`  | __unstable__       | Only for developing application    | `master`      | Free to push and merge, with the responsibility of resolving issues if happens |
|            |                    |                                    |               | SHOULD NOT PUSH directly to this branch, create a `feature` branch instead     |
|            |                    |                                    |               | DO NOT DELETE this branch after merging to branch `master`                     |
| `features` | __self-developed__ | Features developed by contributors | `develop`     | Free to pull and push                                                          |
|            |                    |                                    |               | Naming convention: `feature/feature_name`, e.g: `feature/signup`               |
