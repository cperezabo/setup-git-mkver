[![GitHub Actions CI](https://github.com/cperezabo/setup-git-mkver/actions/workflows/ci.yml/badge.svg)](https://github.com/cperezabo/setup-git-mkver/actions/workflows/ci.yml)

# Setup git-mkver for GitHub Actions

This action downloads and installs [git-mkver](https://idc101.github.io/git-mkver).

# Usage

```yaml
- uses: cperezabo/setup-git-mkver@v1
  with:
    # Force specific git-mkver version. Default: latest
    version: "1.2.0"
```
