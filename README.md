# WOJ Problem Box

This is the official problem box for the WOJ system.

**Work in Progress**

Force push may happen at any time.

## For Contributors

### How to add a problem

Add a new file at `problem/<problem-id-and-name>/problem.toml`, that is, the problem id and name separated by a dash.

> For example, `problem/a0001-hello/problem.toml`.

You may also add some test cases in the same directory. And reference them in the `problem.toml` file.

> Since it is a git repository, large files are not recommended. Notice: `stdout_file` can also be a http link, but it should be always available and not change. We are still researching a way to serve large test cases using IPFS or other immutable file systems.

**index.json** and **spec** directory will be generated automatically. Do not modify them manually.
