<div align="center">

# asdf-melange [![Build](https://github.com/omissis/asdf-melange/actions/workflows/build.yml/badge.svg)](https://github.com/omissis/asdf-melange/actions/workflows/build.yml) [![Lint](https://github.com/omissis/asdf-melange/actions/workflows/lint.yml/badge.svg)](https://github.com/omissis/asdf-melange/actions/workflows/lint.yml)

[melange](https://github.com/chainguard-dev/melange/tree/main/docs) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `docker`: to build the images

# Install

Plugin:

```shell
asdf plugin add melange
# or
asdf plugin add melange https://github.com/omissis/asdf-melange.git
```

melange:

```shell
# Show all installable versions
asdf list-all melange

# Install specific version
asdf install melange latest

# Set a version globally (on your ~/.tool-versions file)
asdf global melange latest

# Now melange commands are available
melange --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/omissis/asdf-melange/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Claudio Beatrice](https://github.com/omissis/)
