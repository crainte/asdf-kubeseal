<div align="center">

# asdf-kubeseal [![Build](https://github.com/crainte/asdf-kubeseal/actions/workflows/build.yml/badge.svg)](https://github.com/crainte/asdf-kubeseal/actions/workflows/build.yml) [![Lint](https://github.com/crainte/asdf-kubeseal/actions/workflows/lint.yml/badge.svg)](https://github.com/crainte/asdf-kubeseal/actions/workflows/lint.yml)


[kubeseal](https://github.com/bitnami-labs/sealed-secrets) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add kubeseal
# or
asdf plugin add kubeseal https://github.com/crainte/asdf-kubeseal.git
```

kubeseal:

```shell
# Show all installable versions
asdf list-all kubeseal

# Install specific version
asdf install kubeseal latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kubeseal latest

# Now kubeseal commands are available
kubeseal --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/crainte/asdf-kubeseal/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Chris Alexander](https://github.com/crainte/)
