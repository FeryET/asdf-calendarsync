<div align="center">

# asdf-calendarsync [![Build](https://github.com/FeryET/asdf-calendarsync/actions/workflows/build.yml/badge.svg)](https://github.com/FeryET/asdf-calendarsync/actions/workflows/build.yml) [![Lint](https://github.com/FeryET/asdf-calendarsync/actions/workflows/lint.yml/badge.svg)](https://github.com/FeryET/asdf-calendarsync/actions/workflows/lint.yml)

[calendarsync](https://github.com/inovex/CalendarSync) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add calendarsync
# or
asdf plugin add calendarsync https://github.com/FeryET/asdf-calendarsync.git
```

calendarsync:

```shell
# Show all installable versions
asdf list-all calendarsync

# Install specific version
asdf install calendarsync latest

# Set a version globally (on your ~/.tool-versions file)
asdf global calendarsync latest

# Now calendarsync commands are available
calendarsync --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/FeryET/asdf-calendarsync/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Farhood Etaati](https://github.com/FeryET/)
