## Open Source Code Best Practices

Project repositories should be exemplary of software engineering best practices.

For example, Python repos should be PEP8 compliant, use best linting practices, have a release process built into the CI, have a deterministic build lock file, etc.

Your repos should be viewed by the community as an example of modern best practices for Java, Scala, Python, and Rust.

## Code formatting

Code should use programmatic formatting tools like black for Python or scalafmt for Scala.

PR comments with "code formatting nits" have gone out of style ever since Golang shipped gofmt.

Machines should format code, not humans.

## Code versioning

Code should be versioned with [Semantic Versioning 2.0](https://semver.org/) ("SemVer") or [Calendar Versioning](https://calver.org/) ("CalVer").

Make sure to document the code versioning scheme that's used and follow it strictly.

Users depend on libraries to avoid breaking changes that are inconsistent with the selected versioning scheme. You need to be a reliable dependency for users, or they'll look for other libraries as options.

## Continuous integration (CI)

Continuous integration refers to automated build systems that run unit tests, code linting, and other checks on code branches.  These checks increase the likelihood of only high-quality code being merged with the main branch.



## Continuous deployment (CD)

TODO

## Production release process

TODO

## Code linters

TODO

## Conventional commits

TODO

## Language-specific code best practices

TODO

## Code performance

TODO

## Code longevity

TODO

## Avoid breaking changes

TODO


