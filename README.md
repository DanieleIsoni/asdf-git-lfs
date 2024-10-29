<div align="center">

# asdf-git-lfs [![Build](https://github.com/DanieleIsoni/asdf-git-lfs/actions/workflows/build.yml/badge.svg)](https://github.com/DanieleIsoni/asdf-git-lfs/actions/workflows/build.yml) [![Lint](https://github.com/DanieleIsoni/asdf-git-lfs/actions/workflows/lint.yml/badge.svg)](https://github.com/DanieleIsoni/asdf-git-lfs/actions/workflows/lint.yml)

[git-lfs](https://git-lfs.com/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `git`, `bash`, `curl`, `tar`, `zip` and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add git-lfs
# or
asdf plugin add git-lfs https://github.com/DanieleIsoni/asdf-git-lfs.git
```

git-lfs:

```shell
# Show all installable versions
asdf list-all git-lfs

# Install specific version
asdf install git-lfs latest

# Set a version globally (on your ~/.tool-versions file)
asdf global git-lfs latest

# Now git-lfs commands are available
git lfs --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/DanieleIsoni/asdf-git-lfs/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Daniele Isoni](https://github.com/DanieleIsoni/)
