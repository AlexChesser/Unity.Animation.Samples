# Contributions

## If you are interested in contributing, here are some ground rules:

* Follow the naming and style conventions for [code](CONVENTIONS.md) and [documentation](DOCUMENTING.md) in the project.
* Everything must have test coverage. PR's with insufficient test coverage will be rejected.
* Add appropriate release notes in the unreleased section of `CHANGELOG.md`. We only have a `CHANGELOG.md` for com.unity.animation package, all changes for samples are currently not tracked.
* Pull requests must be made against `master`.

Once you have a change ready following these ground rules, simply make a pull request in GitHub.

## All contributions are subject to the Unity Contribution Agreement

By making a pull request, you are confirming agreement to the terms and conditions of the [Unity Contribution Agreement](https://unity3d.com/legal/licenses/Unity_Contribution_Agreement), including that your Contributions are your original creation and that you have complete right and authority to make your Contributions.

## Rules for PR's

* If a PR shall not be merged (yet), the author should create a draft PR instead. As soon as the PR is considered ready to land, it should be turned into a usual PR by the author.

* If there were significant changes to the code after a reviewer approved, a re-review must be requested. For smaller changes (like fixing typos) this is not required.

* A Code owner is expected to merge the PR.

* A reviewer should not feel nitpicky about requesting (small) changes in a PR, this guideline explicitly encourages this -- also this kind of feedback adds to the quality of our product and it should not be taken personally. Here is a suggestion for a "fast path" though: the reviewer should suggest a solution (like a different phrasing, name or hinting a typo). If the author resolves those exactly as the reviewer suggested, he or she can assume the approval of the reviewer without awaiting another explicit re-review/approval.   


### Adding Reviewers

* Each request needs **at least 1 reviewer**. Each reviewer needs to approve the PR before it is merged. People from the team can add themselves if they would also like to review the changes. Reviewers can be removed if they have not yet started a review, but do not remove people who have added themselves.

* For each reviewer added, **reach out to that person on Slack** so that they are made aware of the request.

* As a Reviewer, please **comment on or approve a PR in a timely manner**. If you’re unable to do so, reach out to the author and let them know. 

* As the PR author you are responsible for landing your PR swiftly. Reach out to devs who do not review in a timely manner on slack and remind them.

## Stale PRs

PRs without activity for several days should be **updated with comments or closed**. If the PR is waiting on something (e.g. another merge), close the PR and reopen it later. If the PR has yet to be reviewed by the reviewer(s), double check that they are the best person to review this PR.

## Guidelines

* Aim for not more than 200 to 400 lines of changes in a PR. Beyond that, reviewers often stop trying to fully understand the code.
* Try to separate large automated-refactoring resulting in massive code changes from actual changes in separate PRs.
* Release Notes must be updated when behaviour is changed.

### Resolving comments guidelines
* Comments that were simply fixed exactly as the reviewer requested can be resolved by both author and reviewer
* Comments that the author has either disagreed with or solved in an unexpected way, should be resolved by the reviewer only (not the the author)

## Merging PRs

It’s preferred to **squash commits and merge** when completing a PR. To do so, click the dropdown arrow next to the merge button and select "Squash and merge". This will allow you to preview the new commit message and edit it.

Select another merge option if it’s required to preserve valuable information. For more information about the different merge options, see [GitHub’s documentation](https://help.github.com/articles/about-merge-methods-on-github/).

**Replace the merge commit message** with something meaningful instead of using the default “merge pull request #123”.

Merged branches will automatically be deleted through GitHub (you can restore them if required).
