<div align="center">

# asdf-kubefwd [![Build](https://github.com/nklmilojevic/asdf-kubefwd/actions/workflows/build.yml/badge.svg)](https://github.com/nklmilojevic/asdf-kubefwd/actions/workflows/build.yml) [![Lint](https://github.com/nklmilojevic/asdf-kubefwd/actions/workflows/lint.yml/badge.svg)](https://github.com/nklmilojevic/asdf-kubefwd/actions/workflows/lint.yml)


[kubefwd](https://github.com/txn2/kubefwd) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add kubefwd
# or
asdf plugin add kubefwd https://github.com/nklmilojevic/asdf-kubefwd.git
```

kubefwd:

```shell
# Show all installable versions
asdf list-all kubefwd

# Install specific version
asdf install kubefwd latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kubefwd latest

# Now kubefwd commands are available
kubefwd version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nklmilojevic/asdf-kubefwd/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nikola Milojević](https://github.com/nklmilojevic/)
