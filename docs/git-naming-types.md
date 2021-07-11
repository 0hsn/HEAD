## Type

#### Branch types `brach_type`

- **feature**: A new feature, or a sub feature or a CR consumed by the branch

- **bugfix**: Branch contains a fix

- **refactor**: A code change that neither fixes a bug nor adds a feature, rather improve one or more of: code quality, performance, readability, etc

- **topic**:  A large epic branch. Sometime we work on a large feature, that we expect to be not merged to `develop` for couple of weeks. We create this branch for that purpose.

- **release**: A new release branch. Rarely used, but when we set milestone for release with not going via normal flow `develop > staging > master`, but merge some issues to be deliverale on a release, then we use this branch.

#### Commit message types `commit_type`

> this combines both backend and frontend commit message format.

- **feature**: A new feature, or a sub feature

- **fix**: A bug fix

- **docs**: Documentation only changes

- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing
  semi-colons, etc)

- **refactor**: A code change that neither fixes a bug nor adds a feature

- **perf**: A code change that improves performance

- **test**: Adding missing tests or correcting existing tests

- **build**: Changes that affect the build system, CI configuration or external dependencies (example scopes: gulp, broccoli, npm)

- **ci**: Any changes to our CI configuration files and scripts (Travis, Circle CI, BrowserStack, SauceLabs)

- **chore**: Other changes that don't modify `src` or `test` files
