# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test git-lfs https://github.com/DanieleIsoni/asdf-git-lfs.git "git lfs --version"
```

Tests are automatically run in GitHub Actions on push and PR.
