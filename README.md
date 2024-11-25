# tox-toml-fmt mirror

[![Mirror](https://github.com/tox-dev/tox-toml-fmt/actions/workflows/main.yaml/badge.svg)](https://github.com/tox-dev/tox-toml-fmt/actions/workflows/main.yaml)

Mirror of [`tox-toml-fmt`](https://github.com/tox-dev/toml-fmt/tree/main/tox-toml-fmt) for
[pre-commit](https://github.com/pre-commit/pre-commit).

### Using `tox-toml-fmt` with pre-commit

Add it to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/pre-commit/tox-toml-fmt
  rev: "" # Use the sha / tag you want to point at
  hooks:
    - id: tox-toml-fmt
```
