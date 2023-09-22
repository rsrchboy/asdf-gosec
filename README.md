<div align="center">

# asdf-gosec [![Build](https://github.com/rsrchboy/asdf-gosec/actions/workflows/build.yml/badge.svg)](https://github.com/rsrchboy/asdf-gosec/actions/workflows/build.yml) [![Lint](https://github.com/rsrchboy/asdf-gosec/actions/workflows/lint.yml/badge.svg)](https://github.com/rsrchboy/asdf-gosec/actions/workflows/lint.yml)

[gosec](https://securego.io) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add gosec
# or
asdf plugin add gosec https://github.com/rsrchboy/asdf-gosec.git
```

gosec:

```shell
# Show all installable versions
asdf list-all gosec

# Install specific version
asdf install gosec latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gosec latest

# Now gosec commands are available
gosec --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rsrchboy/asdf-gosec/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Chris Weyl](https://github.com/rsrchboy/)
