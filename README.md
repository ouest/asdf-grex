<div align="center">

# asdf-grex [![Build](https://github.com/ouest/asdf-grex/actions/workflows/build.yml/badge.svg)](https://github.com/ouest/asdf-grex/actions/workflows/build.yml) [![Lint](https://github.com/ouest/asdf-grex/actions/workflows/lint.yml/badge.svg)](https://github.com/ouest/asdf-grex/actions/workflows/lint.yml)


[grex](https://github.com/pemistahl/grex) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add grex
# or
asdf plugin add grex https://github.com/ouest/asdf-grex.git
```

grex:

```shell
# Show all installable versions
asdf list-all grex

# Install specific version
asdf install grex latest

# Set a version globally (on your ~/.tool-versions file)
asdf global grex latest

# Now grex commands are available
grex --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ouest/asdf-grex/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [ouest](https://github.com/ouest/)
