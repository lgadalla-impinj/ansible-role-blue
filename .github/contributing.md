## Contributing

Hi there! We're thrilled that you'd like to contribute to this project. Your help is essential for keeping it great.

## Branching strategy

In general, contributors should develop on branches based off of `main` and pull requests should be to `main`.

See [Understanding the GitHub flow](https://guides.github.com/introduction/flow/) for more information.

## Submitting a pull request

1. Clone the repository on GitHub.
2. Create a named feature branch. (i.e. `add-new-module`)
3. Write your change.
4. Push to your branch and submit a pull request from your branch to `main`.

## Building

Builds happen with each push to a pull request.  If you want to start building right away but you aren't ready for
code review you can open a _Draft Pull Request_.  This will not notify any Reviewers that may be configured in
the [`CODEOWNERS`](CODEOWNERS) file until you change it to _Ready for Review_.

All builds for this repo can be found under the **Actions** tab and are also located
under the **Checks** tab of the pull request.  You may want to consider using the
[GitHub Slack Integration](https://github.com/integrations/slack) to get
Slack notifications of your build status.

## Releasing

Deployments are executed automatically when a pull request is merged into the `main` branch.
