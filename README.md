# homebrew-qt4

This Homebrew tap allows you to install Qt4/PySide (and various packages that depend on it) on macOS Sierra and newer. You can install it like this:

    brew install nzanepro/qt4/qt@4

    or

    brew install nzanepro/qt4/pyside@1.2

Feel free to submit an issue or pull request if you run into any problems or have any suggestions for improvements to the packages.

**Please note:** Qt4 is unsupported by its creators, so there are likely security/usability problems with it that will never be resolved. If you can, please consider migrating your projects to Qt5.

**Please note:** Including the deprecated openssl@1.0 allows this to all build, but qt4 projects really need to start being ported to python@3/qt@5/openssl@1.1 for security reasons
