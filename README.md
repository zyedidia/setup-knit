# setup-knit
GitHub Action for installing [Knit](https://github.com/zyedidia/knit).

Usage:

```yaml
jobs:
  test:
    steps:
    - uses: zyedidia/setup-knit@v1
```

Optional arguments:

* `go-version`: go version to install (default is `1.19.x`).
* `knit-version`: knit version to install (default is `latest`).
