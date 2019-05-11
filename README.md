<!--
https://pypi.org/project/readme-generator/
https://pypi.org/project/python-readme-generator/
-->

[![](https://img.shields.io/badge/OS-macOS-blue.svg?longCache=True)]()
[![](https://img.shields.io/pypi/v/mac-dock.svg?maxAge=3600)](https://pypi.org/project/mac-dock/)
[![](https://img.shields.io/npm/v/mac-dock.svg?maxAge=3600)](https://www.npmjs.com/package/mac-dock)
[![Travis](https://api.travis-ci.org/looking-for-a-job/mac-dock.svg?branch=master)](https://travis-ci.org/looking-for-a-job/mac-dock/)

#### Installation
```bash
$ [sudo] npm i -g mac-dock
```
```bash
$ [sudo] pip install mac-dock
```

#### Scripts usage
command|`usage`
-|-
`dock` |`usage: dock command [args]`
`dock-add-app` |`usage: dock-add-app app ...`
`dock-add-folder` |`usage: dock-add-folder [--arrangement=X][--displayas=Y][--showas=Z] path`
`dock-apps` |`usage: dock-apps`
`dock-folders` |`usage: dock-folders`
`dock-rm` |`usage: dock-rm item ...`

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
    <a href="https://pypi.org/project/python-readme-generator/">python-readme-generator</a>
</p>