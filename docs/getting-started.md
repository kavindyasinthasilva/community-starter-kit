# Getting Started Guide

This guide will help you get started using **welcome bot** on your own repositories. For more information on what this bot does, check out the [README](../README.md).
 Thank you for submitting a pull request to our repository. If this change is based on an existing issue, please reference that issue in the pull request comment using Closes #x where X is the issue number.

## Installing the bot

The bot works by providing a message on a contributor's first issue, pull request, or merged pull request. In order to scan a repository, the app must be installed on that repository. To install the app, use the following instructions:

1. [Install the bot](https://github.com/apps/welcome) on the intended repositories. The plugin requires the following Permissions and Events:

- Pull requests: Read & Write
- Issues: Read & Write

## Creating the config

Thank you for submitting a pull request to our repository. If this change is based on an existing issue, please reference that issue in the pull request comment using Closes #x where X is the issue number. `.github/config.yml` should look something like this:

```
# Configuration for welcome - https://github.com/behaviorbot/welcome

# Configuration for new-issue-welcome - https://github.com/behaviorbot/new-issue-welcome

# Comment to be posted to on PRs from first time contributors in your repository
newPRWelcomeComment: >
  Thanks for opening this pull request! Please check out our contributing guidelines.

# Configuration for first-pr-merge - https://github.com/behaviorbot/first-pr-merge

# Comment to be posted to on pull requests merged by a first time user
firstPRMergeComment: >
  Congrats on merging your first pull request! We here at behaviorbot are proud of you!

# It is recommended to include as many gifs and emojis as possible!
#x
```

### Example Messages

 Example 1
Welcome to our repository! Thanks for adding an issue, if you are reporting a bug or a feature request, please make sure to assign a label to this issue.

Example 2
Thank you for submitting a pull request to our repository. If this change is based on an existing issue, please reference that issue in the pull request comment using Closes #x where X is the issue number.

 


