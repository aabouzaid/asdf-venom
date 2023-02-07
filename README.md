<div align="center">

# asdf-venom [![Build](https://github.com/aabouzaid/asdf-venom/actions/workflows/build.yml/badge.svg)](https://github.com/aabouzaid/asdf-venom/actions/workflows/build.yml) [![Lint](https://github.com/aabouzaid/asdf-venom/actions/workflows/lint.yml/badge.svg)](https://github.com/aabouzaid/asdf-venom/actions/workflows/lint.yml)


[venom](https://github.com/ovh/venom) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add venom
# or
asdf plugin add venom https://github.com/aabouzaid/asdf-venom.git
```

venom:

```shell
# Show all installable versions
asdf list-all venom

# Install specific version
asdf install venom latest

# Set a version globally (on your ~/.tool-versions file)
asdf global venom latest

# Now venom commands are available
venom help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/aabouzaid/asdf-venom/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ahmed AbouZaid](https://github.com/aabouzaid/)
