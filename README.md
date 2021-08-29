# SublimeLinter-contrib-proselint

This linter plugin for [SublimeLinter][docs] provides an interface to
[proselint](http://proselint.com) when using “markdown”, “text”, or “plain text”
syntaxes.

## Installation

This plugin requires the latest SublimeLinter version. If SublimeLinter is not
yet installed, please follow the [instructions][installation].

### Linter installation

Before using this plugin, please make sure that `proselint` is available on your
system. To install `proselint`, do the following:

1. Install [Python](http://python.org/download/) and
   [pip](http://www.pip-installer.org/en/latest/installing).

2. Install `proselint` by typing the following in a terminal:

```text
[sudo] pip install proselint
```

**Note:** This plugin requires `proselint` 0.3.4 or later.

### Linter configuration

You must ensure that proselint is available to SublimeLinter. Please read and
follow the steps in
[“Finding a linter executable”](http://sublimelinter.readthedocs.org/en/latest/troubleshooting.html#finding-a-linter-executable)
through “Validating your PATH” in the documentation.

Once you have installed and configured `proselint`, you can proceed to install
the SublimeLinter-contrib-proselint plugin.

### Plugin installation

This plugin is available via <https://sublime.fnando.com>.

## Settings

For general information on how SublimeLinter works with settings, please see
[Settings][settings]. For information on generic linter settings, please see
[Linter Settings][linter-settings].

SublimeLinter-contrib-proselint also provides its own settings through a config
file, `.proselintrc`.

[docs]: http://sublimelinter.readthedocs.org
[installation]: http://sublimelinter.readthedocs.org/en/latest/installation.html
[locating-executables]:
  http://sublimelinter.readthedocs.org/en/latest/usage.html#how-linter-executables-are-located
[pc]: https://sublime.wbond.net/installation
[cmd]:
  http://docs.sublimetext.info/en/sublime-text-3/extensibility/command_palette.html
[settings]: http://sublimelinter.readthedocs.org/en/latest/settings.html
[linter-settings]:
  http://sublimelinter.readthedocs.org/en/latest/linter_settings.html
[inline-settings]:
  http://sublimelinter.readthedocs.org/en/latest/settings.html#inline-settings
