# Contributing to gliff.ai

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

gliff.ai is a small company aiming to help get healthcare and life science AI products regulated with a focus on privacy and security; fairness, accountability and transparency; all by keeping experts in the loop to ensure high quality outputs for real people across the world.
Because we're small, we need the help of volunteer developers like you to ensure we can have the best and biggest impact possible.

Here are some important resources:

- [gliff.ai](https://gliff.ai) tells you who we are
- [Our roadmap](https://github.com/gliff-ai/roadmaplist) tells you what we're thinking about right now and in the future
- [gliff.ai Projects](https://github.com/orgs/gliff-ai/projects) is where we keep our day-to-day project management
- Bugs or vulnerabilities? [Issues](https://github.com/gliff-ai/gliff-ai/issues) is where to report them
  - We have some [guidelines](https://github.com/gliff-ai/.github/SECURITY.md) for reporting vulnerabilities
  - And some templates for issues that we'd appreciate you using

## Linting, Formatting and Testing

We are using flake8 and black for linting and auto-formatting our python code and eslint and prettier.io for linting and autoformatting our TypeScript.
Configuration files can be found in our repos.

We are using pytest for our Python tests and jest with react-testing-library for our TypeScript testing.
Configuration files can be found in our repos.

We use Pre-commit for running lints, tests and other checks locally on commit and push.
To use pre-commit on your own machine just run:

    sudo pip install pre-commit
    pre-commit install --hook-type pre-commit
    pre-commit install --hook-type commit-msg
    pre-commit install --hook-type pre-push

If you create a pull request your contributed code will automatically be linted, formatted and tested by the GitHub Actions we have set up.

If you write new code, we'd appreciate it if you used the same linters and formatters.
We'd also like new code to come with new tests, where appropriate, and to be run against all existing tests.

## Submitting changes

Please send a GitHub Pull Request to gliff.ai with a clear list of what you've done (read more about [pull requests](http://help.github.com/pull-requests/)).
When you send a pull request, we will love you forever if you include tests and documentation.
We can always use more test coverage.

Always write a clear log message for your commits.
One-line messages are fine for small changes, but bigger changes should look like this:

    $ git commit -m "feat: Add new feature
    >
    > A paragraph describing what changed and its impact."

Thanks,
The gliff.ai team
