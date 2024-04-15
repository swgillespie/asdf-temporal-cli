<div align="center">

# asdf-temporal-cli [![Build](https://github.com/swgillespie/asdf-temporal-cli/actions/workflows/build.yml/badge.svg)](https://github.com/swgillespie/asdf-temporal-cli/actions/workflows/build.yml) [![Lint](https://github.com/swgillespie/asdf-temporal-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/swgillespie/asdf-temporal-cli/actions/workflows/lint.yml)

[temporal-cli](https://docs.temporal.io/cli) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add temporal-cli
# or
asdf plugin add temporal-cli https://github.com/swgillespie/asdf-temporal-cli.git
```

temporal-cli:

```shell
# Show all installable versions
asdf list-all temporal-cli

# Install specific version
asdf install temporal-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global temporal-cli latest

# Now temporal-cli commands are available
temporal --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/swgillespie/asdf-temporal-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Sean Gillespie](https://github.com/swgillespie/)
