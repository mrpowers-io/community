# mrpowers-io

This website explains the software engineering philosophy behind the projects in the mrpowers-io GitHib organization.  It explains how to build a small community of contributors and collaborate on code repos with a focus on best practices.

The mrpowers-io projects offer a wonderful user onboarding experience with an easy to follow quickstart.  The documentation clearly oulines the project functionality and all projects are marketed on social media to get more users and contributors.

Metrics for all projects are gathered on a monthly basis to make sure they're growing.  The maintainer efforts should be optimized based on the metrics.  Maintainers should focus on getting new contributors if the number of new committers is lacking.  They should focus on getting more downloads if there are not enough users.

## How to acquire open source contributors

Building a cool project with a welcoming community and clear steps for making pull requests can help you acquire contributors. Remember to always be welcoming to the community, as both contributors and our competitors are watching.

* The repo should have many issues with the “good first issue” label, with a variety of easy and medium-difficulty tasks. Some tasks should be code contributions, and others should be documentation tasks / trivial fixes.  We always want an easy on-ramp for someone that's making their first OSS contribution.

* Whenever a new contributor creates and issue or submits a pull request, we should respond quickly, be collaborative, and help them get their PR merged.

* We need to constantly reach out on LinkedIn, Slack, Reddit, and X to let the community know that we’re open for contributions.  We should always be actively recruiting new contributors.

## How to manage open source GitHub Issues

We should respond to all GitHub issues in a timely manner (generally within a few days).  There are a variety of actions that can take place after reviewing a GitHub issue:

* Convert it to a GitHub Discussion  
* Answer and close it
* Ask for more details  
* Ask the issue creator if they would like to build the feature  

It's best to link PRs to GitHub issues so the work is more trackable.

Close issues older than 6 months with a GitHub action.  Let the PR author know they can re-open if the PR should still be open.

Assign issues to team/community members, so it’s clear who is responsible for driving the issue to completion.

Be extra kind and supportive of any community member who’s brave enough to open an issue. The issue creator should feel that our community is welcoming and supportive.

## GitHub Pull Requests

GitHub pull requests should have an assignee (who wrote the code), a reviewer (team member who’s reviewing the PR), and a description with “Fixes \#issue\_numer” that auto-closes the issue when the PR is merged.

If the comments become extensive, we should offer to help and push commits to get the PR over the finish line. In general, we don’t want to give open source contributors many rounds of comments.

## GitHub Milestones

GitHub issues should be assigned to milestones.  The upcoming milestone should have a date.  We can set the date to whatever we’d like and change it at any time.

The GitHub milestones serve as the open source roadmap.  It's cumbersome to manage the roadmap with a external Google Doc or a giant issue.

Milestones offer the flexibility that’s necessary for open source project management.   You can easily move issues to different milestones when the situation changes.

## GitHub Discussions

GitHub discussions are better for Q\&A, Ideas, announcements, ideas, polls, and show & tell.

It’s easy to convert GitHub issues to GitHub discussions and it’s a really nice tool when triaging issues.

GitHub discussions have features that are not available in GitHub issues, so they are an important tool for managing community interactions.

## Slack conversations

We should aim to respond to all Slack conversations.  Lots of answers should be to just encourage the users to create a GitHub discussion or send them a link to a blog post.  Slack conversations are more work than GitHub discussions because they’re not indexed by Google and disappear after a month (so the same question keeps getting asked).

It’s best to encourage community members to answer Slack questions, so we don’t have to do this work.  We should monitor Slack stats via CommonRoom, identify the top community contributors, and directly encourage them to keep answering questions / give them OSS care packages to say thank you.

## Contributor meetings

Projects should have contributor meetings on a monthly basis with the main OSS committers.

The contributor meetings give the valued OSS contributors direct access to the core developers, motivating and encouraging them to continue contributing.

## Community meetings

Projects should hold community meetings periodically to highlight external project contributions, and new features, and discuss the roadmap.

The meeting frequency should depend on the project's maturity.  A project that’s rapidly incubating may have community meetings on a biweekly basis and a project that’s rather mature may just have the meetings on a quarterly basis.

The community meetings should be recorded and posted on YouTube so they’re available to people who can’t attend live.

Community meetings will only appeal to a small set of overall users (only the users that have free time and are super interested in the latest developments, even the ones that are not relevant to their job).  Attendance for a community meeting will never be super-high, but they’re still an important component of community building.

## Code Best Practices

Proeject repositories should be exemplary of software engineering best practices.

For example, Python repos should be PEP8 compliant, use best linting practices, have a release process built into the CI, have a deterministic build lock file, etc.  

The community should be able to look at our repos as an example of all modern best practices for Java, Scala, Python, and Rust.

## Code formatting

Code should use programatic formatting tools like black or scalafmt.

PR comments with "code formatting nits" have gone out of style ever since Golang shipped gofmt.

Machines should format code, not humans.

## Documentation

Each project should have documentation that answers all user questions, is SEO optimized, and is fundamentally enlightening for the domain.

The Delta Lake docs should clearly explain how to add a column constraint but also educate users on ACID transactions and the Lakehouse category.

The Unity Catalog docs should educate users about volumes, why catalogs are important, and the importance of the AI catalog category.

Our docs should be world-class.

## Project metrics

Here are the project metrics that should be tracked on a monthly basis:

* Number of new contributors  
* GitHub stars  
* LinkedIn followers  
* PyPI downloads  
* Number of open isses/PRs

Some folks claim that these metrics are easy to game and I disagree.  For exmaple, it’s quite hard to get 10,000 GitHub stars without triggering a [fake stars algorithm](https://dagster.io/blog/fake-stars).

Tracking metrics is a great way to fine-tune focus areas. If a project isn’t getting enough new contributors, focus on creating more issues with the “good first issue” label and responding to new contributors faster on GitHub.

If the LinkedIn community isn’t growing fast enough, then focus on making more social content.
