# release-drafter-example

![](https://media.giphy.com/media/CDZwopbecAbIc/giphy-downsized.gif)

This repository demonstrates how to use [release-drafter](https://github.com/marketplace/actions/release-drafter) github action.

Also, there is another [github action](./.github/workflows/release_slack_notification.yml) added for sending notification to a slack channel at every new release creation.

## Labels

The draft change note is constructed based on the available github labels:

### Change related labels

- bug - Something isn't working
- chore - Changes that do not relate to a bug or feature
- feature - New feature or improvement

it captures conventional commits too

### Semantic versioning labels

- major - Following change needs a major version update
- minor - Following change needs a minor version update
- patch - Following change needs a patch version update

### Other

- skip-changelog - Won't be included in the changelog
