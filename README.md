# githooks

Several hooks I am using together with [lefthook](https://github.com/evilmartians/lefthook).
Feel free to use them in your projects.

## Usage

To use all of the checks, use the following snippet in your `lefthook.yml`:

```yaml
remotes:
  git_url: git@github.com:nachtjasmin/githooks
  configs:
    - ensure-no-fixup-commits.yml
    # ...

```
