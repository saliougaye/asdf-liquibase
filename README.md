<div align="center">

# asdf-liquibase [![Build](https://github.com/saliougaye/asdf-liquibase/actions/workflows/build.yml/badge.svg)](https://github.com/saliougaye/asdf-liquibase/actions/workflows/build.yml) [![Lint](https://github.com/saliougaye/asdf-liquibase/actions/workflows/lint.yml/badge.svg)](https://github.com/saliougaye/asdf-liquibase/actions/workflows/lint.yml)

[liquibase](https://github.com/liquibase/liquibase) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add liquibase
# or
asdf plugin add liquibase https://github.com/saliougaye/asdf-liquibase.git
```

liquibase:

```shell
# Show all installable versions
asdf list-all liquibase

# Install specific version
asdf install liquibase latest

# Set a version globally (on your ~/.tool-versions file)
asdf global liquibase latest

# Now liquibase commands are available
liquibase --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/saliougaye/asdf-liquibase/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Saliou Gaye](https://github.com/saliougaye/)
