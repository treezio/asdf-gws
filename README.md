<div align="center">

# asdf-gws [![Build](https://github.com/treezio/asdf-googleworkspace-cli/actions/workflows/build.yml/badge.svg)](https://github.com/treezio/asdf-googleworkspace-cli/actions/workflows/build.yml) [![Lint](https://github.com/treezio/asdf-googleworkspace-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/treezio/asdf-googleworkspace-cli/actions/workflows/lint.yml)

[Google Workspace CLI (`gws`)](https://github.com/googleworkspace/cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add gws https://github.com/treezio/asdf-googleworkspace-cli.git
```

gws:

```shell
# Show all installable versions
asdf list-all gws

# Install specific version
asdf install gws latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gws latest

# Now gws commands are available
gws --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/treezio/asdf-googleworkspace-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Treezio](https://github.com/treezio/)
