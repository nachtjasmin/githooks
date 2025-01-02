# githooks

> [!WARNING]
> This project is no longer maintained as I stopped using pre-commit hooks completely.

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

## License

As part of the archival process, all of the code in this repository is now dedicated under the public domain.
