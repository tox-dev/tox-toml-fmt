# tox-toml-fmt mirror

[![Mirror](https://github.com/tox-dev/tox-toml-fmt/actions/workflows/main.yaml/badge.svg)](https://github.com/tox-dev/tox-toml-fmt/actions/workflows/main.yaml)
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/tox-dev/tox-toml-fmt/badge)](https://scorecard.dev/viewer/?uri=github.com/tox-dev/tox-toml-fmt)
[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/16259/badge)](https://www.bestpractices.dev/projects/16259)

Mirror of [`tox-toml-fmt`](https://github.com/tox-dev/toml-fmt/tree/main/tox-toml-fmt) for
[pre-commit](https://github.com/pre-commit/pre-commit).

### Using `tox-toml-fmt` with pre-commit

Add it to your `.pre-commit-config.yaml`:

```yaml
  - repo: https://github.com/tox-dev/tox-toml-fmt
    rev: v1.11.3
    hooks:
      - id: tox-toml-fmt
```
