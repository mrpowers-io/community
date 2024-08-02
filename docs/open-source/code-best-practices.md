## Open Source Code Best Practices

Project repositories should be exemplary of software engineering best practices.

For example, Python repos should be PEP8 compliant, use best linting practices, have a release process built into the CI, have a deterministic build lock file, etc.  

The community should be able to look at our repos as an example of all modern best practices for Java, Scala, Python, and Rust.

## Code formatting

Code should use programatic formatting tools like black or scalafmt.

PR comments with "code formatting nits" have gone out of style ever since Golang shipped gofmt.

Machines should format code, not humans.
