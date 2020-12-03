<!--
https://readme42.com
-->



[![](https://img.shields.io/badge/OS-macOS-blue.svg?longCache=True)]()
[![](https://img.shields.io/pypi/v/mac-dock.svg?maxAge=3600)](https://pypi.org/project/mac-dock/)
[![](https://img.shields.io/npm/v/mac-dock.svg?maxAge=3600)](https://www.npmjs.com/package/mac-dock)[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/mac-dock/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/mac-dock/actions)

### Installation
```bash
$ [sudo] pip install mac-dock
```

```bash
$ [sudo] npm i -g mac-dock
```

#### Examples
```bash
$ dock add-app /Applications/iTunes.app; killall Dock
```

```bash
# arrangement:  1 - name (default), 2 - added, 3 - modification, 4 - creation, 5 - kind
# displayas:    1 - folder, 2 - stack (default)
# showas:       1 - beep, 2 - grid, 3 - list, 4 - auto (default)
$ dock add-folder --arrangement=2 --displayas=1 --showas=1 ~/Downloads; killall Dock
```

```bash
$ dock apps
/Users/username/Applications/Google Chrome.app
/Users/username/Applications/Sublime Text.app
/Applications/Utilities/Terminal.app
/Applications/iTunes.app
```

```bash
$ dock folders
/Users/username/Downloads
```


```bash
$ dock rm /Applications/iTunes.app ~/Downloads; killall Dock
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
