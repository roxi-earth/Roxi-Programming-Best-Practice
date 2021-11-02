## Issue & PR Templates

### Prerequisites

- [Git](https://git-scm.com/downloads)

### Table Of Contents

- [Issue Templates](#issue-templates)
- [PR Templates](#pr-templates)

### Issue Templates

You can add manually from the repository or using `git` command (recommended).

1. Open `Settings` in your repository.
2. Scroll to the `Features` section below and click `Set up templates` button.
3. Click `Add template` button and choose template you want, you can choose between standard template or custom template then you can also customize it.
4. After completing the templates, you can click `Propose changes` then click `Commit changes`.
5. Finally, now you can see your templates works when submit an issue into the github repository.

### PR Templates

You can add manually from the repository or using `git` command (recommended).

1. Click new folder `.github` in your repository.
2. Add new file into the `.github` folder and create new file named `PULL_REQUEST_TEMPLATE.md`.
3. Fill the template with contents you want in the pull request, e.g:

```md
<!--
Thanks for wanting to fix something on Sequelize - we already love you!
Please fill in the template below.
If unsure about something, just do as best as you're able.

If your PR only contains changes to documentation, you may skip the template below.
-->

### Pull Request check-list

_Please make sure to review and check all of these items:_

- [ ] Does `npm run test` or `npm run test-DIALECT` pass with this change (including linting)?
- [ ] Does the description below contain a link to an existing issue (Closes #[issue]) or a description of the issue you are solving?
- [ ] Have you added new tests to prevent regressions?
- [ ] Is a documentation update included (if this change modifies existing APIs, or introduces new ones)?
- [ ] Did you update the typescript typings accordingly (if applicable)?
- [ ] Did you follow the commit message conventions explained in [CONTRIBUTING.md](https://github.com/sequelize/sequelize/blob/main/CONTRIBUTING.md)?

<!-- NOTE: these things are not required to open a PR and can be done afterwards / while the PR is open. -->

### Description of change

<!-- Please provide a description of the change here. -->
```

4. Finally, commit and push the file with the folder.
