# Open Source Documentation best practices

SemVer 2.0 says it well:

> It is your responsibility as a professional developer to properly document software that is intended for use by others. Managing software complexity is a hugely important part of keeping a project efficient, and that’s hard to do if nobody knows how to use your software, or what methods are safe to call.

Your project should have documentation that provides a user guide and shows how to use the public interface.

## User guide

Your docs can include a user guide that provide an overview of how to use your project.  This is especially useful for frameworks or complicated projects with a large API surface area.

For example, suppose your project is a Java testing framework.  You could create a user guide that explains why testing Java code is important and the basics for testing Java.  You could provide high-level examples for the different types of tests and how to structure a test suite.

User guides are a great way to demonstrate how to use a project in real-world applications.

## API docs

The API docs should be programatically generated directly from the codebase.

The codebase should contain docstrings with examples that show how to use each public function.

Your project should have a single command that generates the programatic API docs for all the public functions of the project.  You don't need to document private functions.

Spend time to make sure that the programatic API docs are easy to follow and provide extensive minimal examples.

## Versioning docs

It can be useful to generate seperate versions of docs for each release (e.g. one version of the API docs for v0.12.0 and another version of the API docs for v0.13.1).

Here are two URLs for Apache Iceberg table maintenance documentation for example:

* https://iceberg.apache.org/docs/1.5.1/maintenance/
* https://iceberg.apache.org/docs/1.4.0/maintenance/

One page is for the v1.5.1 release and another page is for the v1.4.0 release.

Versioned docs can be great in theory:

* they can provide a great user experience for users that want the exact documentation for a specific release

Versioned docs can also be really dangerous:

* canonical links: versioned docs create duplicate pages, which is confusing for search engines.  You must add canonical links to let search engines know what page they should rank.  This is critical.
* maintenance burden: It's hard to maintain multiple versions of doc sites.  If you notice a typo for example, you need to fix the latest version and update all the existing pages with the typo as well.
* hiding new features: The v1.4.0 docs intentionally exclude new features that were added in v1.5.0.  It may be better for v1.4.0 users to see the v1.5.0 docs, so they are aware of the new features and are motivated to upgrade.  OSS library maintainers generally don't want users stuck on old versions.
* users must manually specify the right version: Most users end up on docs from Google seraches and don't play close attention to the version.  They don't usually search for the exact version they're using, go to the docs, click the dropdown to the exact version, and then start exploring.  They just go to the first docs page they find from a Google search and immediately look for an answer.

Versioning docs may be a good idea, but versioning the user guide is almost always a bad idea.  There are very few open source software teams with the bandwidth to maintain multiple versions of a user guide and provide customizations for each release.

## Website best practices

Software documentation is deployed as a website and needs to follow web best practices, just like any other website.  Some examples:

* descriptive h1s, h2s, and URLs
* HTML structure that's easy for search engines to navigate
* canonical links for any duplicate pages (especially critical for versioned docs)

You need to follow website conventions to have the right pages rank in searches and to give your users documentation that is easy to navigate.

## Deploying docs

You should have a command to deploy the docs in production.

You will also ideally have a release process that automatically releases the docs whenever you release a new package.  The documentation deployment process should be part of your continuous integration / continuous deployment process.

## Don't change URLs

Your documentation URLs should not change.  If you ever need to change the URL for a page, make sure you setup the proper redirects.

Search engines don't like when URLs are changed.  You should only change URLs in rare instances.

## Importance of documentation

Documentation can make or break a project.

Good documentation convinces users to try out a library and then depend on it in production code.

Bad docs drive away potential users.

You should spend lots and lots of time making beautiful documentation that attracts users.

