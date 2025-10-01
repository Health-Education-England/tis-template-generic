# tis-template-generic
A generic template for TIS repositories.

## TODO
 1. Add `.gitignore`, generated using [gitignore.io].
 2. Update year in [license] file.
 3. Set up [Sonarcloud] project, if applicable.
 4. Enable "Require status checks to pass..." in branch protection rules if
    adding a workflow with checks.
 5. Update the `CODEOWNERS` file to reflect the correct owning teams for the new service.

## CODEOWNERS Examples

Below are example teams and patterns you can use when updating the `CODEOWNERS` file.
Replace the placeholders with the appropriate backend and DevOps teams.

- Backend teams:
  - @Health-Education-England/external-admin-backend
  - @Health-Education-England/internal-admin-backend
  - @Health-Education-England/trainee-backend
  - @Health-Education-England/trainee
- DevOps teams:
  - @Health-Education-England/external-admin-devops
  - @Health-Education-England/internal-admin-devops
  - @Health-Education-England/trainee-devops
  - @Health-Education-England/ops


[gitignore.io]: http://gitignore.io/
[license]: LICENSE
[Sonarcloud]: https://sonarcloud.io/projects/create
