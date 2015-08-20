# Note #

Development moved to https://codereview.qt-project.org/

# Utils library (it's part of `QtCreator`) #
`NewClassPage` patched to be able to use it as Python class wizard.

# Python library #
Library with python language utils.

Already works:
  * Lexical analyzer (ignores comments/doxygen comments)

# `PyEditor` plugin #
Implements python source editor, file wizard and class wizard.

Already works:
  * File wizard
  * Class wizard (similar to C++ non-GUI class wizard)
  * Syntax highlighter (semantic highlight not implemented, but lexical highlight has good quality)
  * Smart indentation (semantic indentation not implemented, e.g. back indent always equal 4 spaces)

# `PythonProjectManager` plugin #
Nokia plugin created by PySide developers.
  * It uses QML (qbs) file with own extension ".pysideproject" to keep project settings
  * It supports Run action (Ctrl+R) when pysideproject opened

# Plugin repository on gitorious #
[repository](https://qt.gitorious.org/~sergey-shambir/qt-creator/qt-creator-py-reborn)