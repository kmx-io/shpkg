# shpkg

## Usage

```
Usage: shpkg OPERATION PKG ...

Source directory operations :
 clone          shortcut for git clone
 fetch          shortcut for git fetch
 pull           shortcut for git pull
 remove | rm    shortcut for uninstall and rm -rf repo

Compilation operations :
 autogen        shortcut for ./autogen
 configure      shortcut for ./configure
 clean          shortcut for make clean
 build          shortcut for make

Package operations :
 fake           install compiled sources into fake directory
 package        build package from sources
 install        install package
 upgrade        pull sources, build package and install
 uninstall      uninstall package
```

To install a package, for example "c3" :
```
$ shpkg install c3
Cloning into 'c3' ...
```

Upgrading a package :
```
$ shpkg upgrade c3
Counting remote objects ...
```

Updating sources for a package :
```
$ shpkg pull c3
Counting remote objects ...
```
