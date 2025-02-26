<div align="center">

# asdf-nyx [![Build](https://github.com/simpe00/asdf-nyx/actions/workflows/build.yml/badge.svg)](https://github.com/simpe00/asdf-nyx/actions/workflows/build.yml) [![Lint](https://github.com/simpe00/asdf-nyx/actions/workflows/lint.yml/badge.svg)](https://github.com/simpe00/asdf-nyx/actions/workflows/lint.yml)

[nyx](https://github.com/mooltiverse/nyx) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add nyx
# or
asdf plugin add nyx https://github.com/simpe00/asdf-nyx.git
```

nyx:

```shell
# Show all installable versions
asdf list-all nyx

# Install specific version
asdf install nyx latest

# Set a version globally (on your ~/.tool-versions file)
asdf global nyx latest

# Now nyx commands are available
nyx --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/simpe00/asdf-nyx/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Simon Peppel](https://github.com/simpe00/)
