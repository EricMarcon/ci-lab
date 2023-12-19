[![R-CMD-check](https://github.com/EricMarcon/ci_package/actions/workflows/check.yml/badge.svg)](https://github.com/EricMarcon/ci_package/actions/workflows/check.yml)
[![codecov](https://codecov.io/github/EricMarcon/ci_package/branch/master/graphs/badge.svg)](https://app.codecov.io/github/EricMarcon/ci_package)

# multiple

A dummy R package to test CI on Gitub.

The target files are the YAML scripts in `.github/workflows`:

- `check.yml` roxygenizes the package, checks it, tests its code coverage and publishes its documentation to Github pages.
- `pr.yml` checks the package on pull requests to detect possible errors.

See [Working with R, chapter 6](https://ericmarcon.github.io/WorkingWithR/chap-ci.html) for details.

