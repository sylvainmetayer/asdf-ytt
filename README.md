<div align="center">

# asdf-ytt [![Build](https://github.com/sylvainmetayer/asdf-ytt/actions/workflows/build.yml/badge.svg)](https://github.com/sylvainmetayer/asdf-ytt/actions/workflows/build.yml) [![Lint](https://github.com/sylvainmetayer/asdf-ytt/actions/workflows/lint.yml/badge.svg)](https://github.com/sylvainmetayer/asdf-ytt/actions/workflows/lint.yml)

[ytt](https://github.com/carvel-dev/ytt) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-ytt  ](#asdf-ytt--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add ytt https://github.com/sylvainmetayer/asdf-ytt.git
```

ytt:

```shell
# Show all installable versions
asdf list-all ytt

# Install specific version
asdf install ytt latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ytt latest

# Now ytt commands are available
ytt --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/sylvainmetayer/asdf-ytt/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Sylvain METAYER](https://github.com/sylvainmetayer/)
