# Open source easy onboarding

Open-source projects should have an easy onboarding process.

Users should be able to get set up locally and use your software in a few minutes.

You should spend a lot of time building a seamless onboarding process.  You should continuously refine it and learn how to set up all users in a few minutes.  Make sure that all users have an easy onboarding process, regardless of the operating system.

## Great examples

The [Polars user guide](https://docs.pola.rs/) is a great example of a site that teaches you how to use the DataFrame library quickly.

This video on [how to build a blog engine in 15 minutes](https://www.youtube.com/watch?v=Gzj723LkRJY&ab_channel=tenthconcept) is a great example of how to acquire users with a compelling demo. It propelled Rails as a popular web development framework.

## README

Your project README should explain the commands a user can run to use your project locally.  It should just be a few steps.  Make sure the setup is standard for whatever programming language you're using.

In the [how to get thousands of stars on your GitHub project](https://blog.cwrichardkim.com/how-to-get-hundreds-of-stars-on-your-github-project-345b065e20a2) article, the author gives some great advice:

> For every hour of code you write, spend an hour writing your README

Spend a lot of time building amazing READMEs.

## Docker

You should also have a Docker image ready for users who don't want to install software locally.

Some users will want to download your library from a package manager (like PyPI, Bundler, or Maven), but others will want to simply grab a pre-built Docker image on Dockerhub.

Make multiple easy onramps to try out your project.

## Example Python quickstart

Here's an example of a quickstart for the quinn project.

Quinn is [uploaded to PyPI](https://pypi.org/project/quinn/) and can be installed with this command:

```
pip install quinn
```

Here's how you can use quinn to validate the presence of columns in a DataFrame:

```python
import quinn

quinn.validate_presence_of_columns(source_df, ["name", "age", "fun"])
```

The `validate_presence_of_columns` will throw an error if the DataFrame does not contain the specified columns.

## Conclusion

Prospective users will often glance at a README when considering an open source project.

If the setup is simple enough, many will be enticed to try your project.

If the setup is complicated or the value proposition is not clear, many will click the back button.

Make sure to convert README viewers to actual users with compelling localhost setup instructions!

