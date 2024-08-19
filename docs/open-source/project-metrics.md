# Open Source Project metrics

Metrics for all projects should be gathered periodically to ensure their growth. Based on these metrics, the maintainer's efforts should be optimized.

It's generally best to track project metrics on a monthly basis but quarterly is fine for less active projects.

Maintainers should focus on getting new contributors if the number of new committers is lacking.  They should focus on getting more downloads if there are not enough users.

## Specific metrics

Here are the project metrics that should be tracked on a monthly basis:

* Number of new contributors
* GitHub stars
* LinkedIn followers
* Project downloads
* Number of open issues/PRs
* Documentation pageviews

Let's start by talking about why "gaming" project metrics are a common objection to collecting them in the first place.

## Gaming project metrics

Some open source maintainers argue that it's futile to monitor metrics because it is easy to fudge the numbers, but we disagree.

Fudging an individual metric in an undetectable manner is actually hard.  It's easy to buy GitHub stars, but hard to do so without triggering a [fake stars algorithm](https://dagster.io/blog/fake-stars).

Gaming a whole basket of metrics would be quite challenging.  It would also be so obvious.  Each platform actively monitors fake activity and you'd likely get banned.

You don't need to game your project metrics of course.  You should let your project metrics grow organically, so they give you an accurate reading on the state of your project.

## Number of new contributors

GitHub shows the total number of contributors and you can track the delta on a periodic basis.

Although it's generally better to have more contributors, great projects can also be built with one or just a few developers.

Many projects are written by 1-3 developers but have many contributors because of small PRs from the community. That's fine, too.

A growing contributor base generally indicates 1. interest in the project, 2. engaged users, and 3. project maintainers that are merging community PRs.  More contributors are highly correlated with project health.

## GitHub stars

The number of GitHub stars is correlated with project interest and usage.

Developers star repos they find interesting or that they depend on.

Projects with growing star counts are generally also growing.

## LinkedIn followers

Large projects should have a LinkedIn page where users can follow them and learn about new features. To build a following, you need to post regularly to the page.

Don't start a LinkedIn page if your library is small or if you're not ready to post frequently.

If you do have a LinkedIn page, tracking the number of followers is a good way to measure project growth.

## Project downloads

Project downloads are also a good way to measure project growth, although they are a flawed metric because most software downloads are bots.

Some software artifact repositories, like PyPI, provide download numbers by operating system, which provide a more realistic number on how many individuals install a software project on a local laptop every day.

Other software artifact repositories like Maven don't provide download information, so these metrics are not easily accessible.

## Number of open issues/PRs

Projects with lots of new issues and PRs are generally growing.

Respond to issues/PRs quickly and help contributors merge their PRs to keep the project momentum high.

It's good to track how many issues/PRs are created and closed to monitor the project growth and the quality of maintenance for the open source contributors.

## Documentation page views

The number of documentation page views and time spent on the page are correlated with a project's actual usage.

If users spend a lot of time on your documentation pages, they are likely also using your software library a lot.

It's best to use privacy-friendly analytics-gathering tools to measure user traffic. You don't need to collect any private user data; just gather the data necessary to provide your users with a great documentation experience.

## Conclusion

Tracking metrics is a great way for the development team to fine-tune focus areas. If a project isn’t getting enough new contributors, focus on creating more issues with the “good first issue” label and responding to new contributors faster on GitHub.  If a project isn't getting enough downloads, focus on writing blog posts to highlight the cool features.

Stay disiplined and track project metrics on a monthly or quarterly business.  Software engineers are generally interested in writing code and don't spend enough time community building and marketing cool features of their projects.  Metrics encourage you to focus on the weak parts of your project.

