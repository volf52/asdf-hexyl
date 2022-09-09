<div align="center">

# asdf-hexyl [![Build](https://github.com/volf52/asdf-hexyl/actions/workflows/build.yml/badge.svg)](https://github.com/volf52/asdf-hexyl/actions/workflows/build.yml) [![Lint](https://github.com/volf52/asdf-hexyl/actions/workflows/lint.yml/badge.svg)](https://github.com/volf52/asdf-hexyl/actions/workflows/lint.yml)

[hexyl](https://github.com/sharkdp/hexyl) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities

# Install

Plugin:

```shell
asdf plugin add hexyl

# or

asdf plugin add hexyl https://github.com/volf52/asdf-hexyl.git
```

hexyl:

```shell
# Show all installable versions
asdf list-all hexyl

# Install specific version
asdf install hexyl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global hexyl latest

# Now hexyl commands are available
hexyl --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/volf52/asdf-hexyl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Arslan](https://github.com/volf52/)
