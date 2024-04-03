<div align="center">

# asdf-zls [![Build](https://github.com/m1ome/asdf-zls/actions/workflows/build.yml/badge.svg)](https://github.com/m1ome/asdf-zls/actions/workflows/build.yml) [![Lint](https://github.com/m1ome/asdf-zls/actions/workflows/lint.yml/badge.svg)](https://github.com/m1ome/asdf-zls/actions/workflows/lint.yml)

[zls](https://github.com/zigtools/zls) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `zig`: you can download it [here](https://ziglang.org/download/)

# Install

Plugin:

```shell
asdf plugin add zls https://github.com/m1ome/asdf-zls
```

zls:

```shell
# Show all installable versions
asdf list-all zls

# Install specific version
asdf install zls latest

# Set a version globally (on your ~/.tool-versions file)
asdf global zls latest

# Now zls commands are available
zls
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/m1ome/asdf-zls/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Pavel Makarenko](https://github.com/m1ome/)
