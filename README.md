<div align="center">

# asdf-cook [![Build](https://github.com/TheHackdes/asdf-cook/actions/workflows/build.yml/badge.svg)](https://github.com/TheHackdes/asdf-cook/actions/workflows/build.yml) [![Lint](https://github.com/TheHackdes/asdf-cook/actions/workflows/lint.yml/badge.svg)](https://github.com/TheHackdes/asdf-cook/actions/workflows/lint.yml)

[cook](https://github.com/glitchedgitz/cook) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add cook
# or
asdf plugin add cook https://github.com/TheHackdes/asdf-cook.git
```

cook:

```shell
# Show all installable versions
asdf list-all cook

# Install specific version
asdf install cook latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cook latest

# Now cook commands are available
cook --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/TheHackdes/asdf-cook/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Guillaume DENIS](https://github.com/TheHackdes/)
