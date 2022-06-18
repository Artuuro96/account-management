# Summary
Enter a brief description of what has been changed/added.

# Self review
- [x] I reviewed my PR changes and left comments/questions when necessary
- [x] My code follows the style guidelines of this project.
- [x] I have ran the formatter locally.
- [ ] I have ran added and ran the tests locally.
- [ ] I have ran the test coverage reports locally.
- [ ] I have made corresponding changes to the documentation (README and API).
- [ ] I have tested the application locally.
- [ ] I have updated the future release log if the code changes apply.

# Type of change

- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] Hot fix (fixes an issue in master branch)
- [ ] Docs (Documentation only changes)
- [ ] Style (Changes that do not affect the meaning of the code, formatting, missing semi-colons, etc)
- [ ] Refactor (Changes that neither fixes a bug or adds a feature)
- [ ] Performance (Changes that improve performance)
- [ ] Chore (Changes to the build process or auxiliary tools and libraries)

# Squash and merge
We are following [Angular commit messages guidelines](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines)

```
<type>(<scope>): <Jira-Issue subject>
<BLANK LINE>
<optional body>
<BLANK LINE>
<optional footer>
```

Types

```
feat: A new feature
fix: A bug fix
docs: Documentation only changes
style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
refactor: A code change that neither fixes a bug nor adds a feature
perf: A code change that improves performance
test: Adding missing or correcting existing tests
chore: Changes to the build process or auxiliary tools and libraries such as documentation generation
```

Make sure you squash and merge your feature/bugfix branches into develop/release/hotfix branches using the suggested format.

Some examples.

```
feat: DP-1234 Edit assessment information

Frontend changes for editing an assessment:
- improve assign modal to receive an existing assessment
- integrate the reasign end point.
- couple of warnings removed

BREAKING CHANGE: the assign modal now receives 3 required parameters
```

More examples [here](https://www.conventionalcommits.org/en/v1.0.0-beta.2/#summary)
