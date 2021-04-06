<div align="center">

# asdf-delgurth-tests ![Build](https://github.com/delgurth/asdf-delgurth-tests/workflows/Build/badge.svg) ![Lint](https://github.com/delgurth/asdf-delgurth-tests/workflows/Lint/badge.svg)

[delgurth-tests](https://github.com/delgurth/delgurth-tests) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add delgurth-tests
# or
asdf plugin add delgurth-tests https://github.com/delgurth/asdf-delgurth-tests.git
```

delgurth-tests:

```shell
# Show all installable versions
asdf list-all delgurth-tests

# Install specific version
asdf install delgurth-tests latest

# Set a version globally (on your ~/.tool-versions file)
asdf global delgurth-tests latest

# Now delgurth-tests commands are available
delgurth-test --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/delgurth/asdf-delgurth-tests/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Wessel van Norel](https://github.com/delgurth/)
