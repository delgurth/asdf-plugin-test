# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test delgurth-tests https://github.com/delgurth/asdf-delgurth-tests.git "delgurth-test --version"
```

Tests are automatically run in GitHub Actions on push and PR.
