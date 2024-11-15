My config files under `~/.config/` for Python that exactly match yapf styles for Google open source projects.

**The yapf config file `style` is under `~/.config/yapf/`**

You could modify these files, or use it in your project instead of use it globally.

## Pylint configuration file paths [^pylintconf]
[^pylintconf]: [Where does Pylint look for configuration files?](https://www.doc.ic.ac.uk/~nuric/sysadmin/where-does-pylint-look-for-configuration-files.html).

Pylint will search it's configuration in the following manner:

1. `pylintrc` in the current working directory
2. `.pylintrc` in the current working directory. 
3. If the current working directory is in a Python module, Pylint searches up the hierarchy of Python modules until it finds a `pylintrc` file.
4. The file named by environment variable `PYLINTRC`.
5. if you have a home directory which isn’t /root: 
   1. `.pylintrc` in your home directory 
   2. `.config/pylintrc` in your home directory
6. `/etc/pylintrc` for global configuration of machines.

## Yapf formatting style search manner[^yapfstyle]
[^yapfstyle]: [google/yapf README.md](https://github.com/google/yapf)

YAPF will search for the formatting style in the following manner:

1. Specified on the command line
2. In the `[style]` section of a `.style.yapf` file in either the current directory or one of its parent directories.
3. In the `[yapf]` section of a setup.cfg file in either the current directory or one of its parent directories.
4. In the `[tool.yapf]` section of a `pyproject.toml` file in either the current directory or one of its parent directories.
5. In the `[style]` section of a `~/.config/yapf/style` file in your home directory.
6. If none of those files are found, the default style is used (PEP8).

## Some addition

- Configuring yapf with VSCode settings.json is as same as specify it on the command line.
- The `pylintrc` file is exactly the same file as [pylintrc on google style guide](https://google.github.io/styleguide/pylintrc).
- For more project specification and team cooperation, you would be better to use config files in your project, instead of 
  global config under `~/.config/`
- You could use these files with [my VSCode setting file for Python](https://gist.github.com/RyoJerryYu/abab633f9aa876fb6947dfca869695d3) for whole automatic Google open source project experience in Python.