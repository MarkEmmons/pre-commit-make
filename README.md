# pre-commit-make

Run [GNU Make](https://www.gnu.org/software/make/) as a [pre-commit](https://pre-commit.com/) hook.

## Usage

Add to your `pre-commit-config.yaml` like any other hook.

The example below runs the `test` target before committing.

```yaml
-   repo: https://github.com/MarkEmmons/pre-commit-make
    rev: v1.0.0
    hooks:
    -   id: gnu-make
        args:
          - test
```

## License

[MIT LICENSE](LICENSE)
