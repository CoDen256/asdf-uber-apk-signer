<div align="center">

# asdf-apk-editor [![Build](https://github.com/coden256/asdf-apk-editor/actions/workflows/build.yml/badge.svg)](https://github.com/coden256/asdf-apk-editor/actions/workflows/build.yml) [![Lint](https://github.com/coden256/asdf-apk-editor/actions/workflows/lint.yml/badge.svg)](https://github.com/coden256/asdf-apk-editor/actions/workflows/lint.yml)

[apk-editor](https://github.com/coden256/apk-editor) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add apk-editor
# or
asdf plugin add apk-editor https://github.com/coden256/asdf-apk-editor.git
```

apk-editor:

```shell
# Show all installable versions
asdf list-all apk-editor

# Install specific version
asdf install apk-editor latest

# Set a version globally (on your ~/.tool-versions file)
asdf global apk-editor latest

# Now apk-editor commands are available
apk-editor --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/coden256/asdf-apk-editor/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Denys Chernyshov](https://github.com/coden256/)
