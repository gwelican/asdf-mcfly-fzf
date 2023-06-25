<div align="center">

# asdf-mcfly-fzf [![Build](https://github.com/gwelican/asdf-mcfly-fzf/actions/workflows/build.yml/badge.svg)](https://github.com/gwelican/asdf-mcfly-fzf/actions/workflows/build.yml) [![Lint](https://github.com/gwelican/asdf-mcfly-fzf/actions/workflows/lint.yml/badge.svg)](https://github.com/gwelican/asdf-mcfly-fzf/actions/workflows/lint.yml)

[mcfly-fzf](https://github.com/bnprks/mcfly-fzf) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add mcfly-fzf
# or
asdf plugin add mcfly-fzf https://github.com/gwelican/asdf-mcfly-fzf.git
```

mcfly-fzf:

```shell
# Show all installable versions
asdf list-all mcfly-fzf

# Install specific version
asdf install mcfly-fzf latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mcfly-fzf latest

# Now mcfly-fzf commands are available
mcfly-fzf --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gwelican/asdf-mcfly-fzf/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Peter Varsanyi](https://github.com/gwelican/)
