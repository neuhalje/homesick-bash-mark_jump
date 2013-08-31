h1. mark/jump for bash

* Plugin for https://github.com/neuhalje/homesick-bash (install for autmoatic acitivation)
* Install with ```homesick clone git@github.com:neuhalje/homesick-bash-mark_jump.git```
* Based on http://jeroenjanssens.com/2013/08/16/quickly-navigate-your-filesystem-from-the-command-line.html
* supported OS: MacOS, Ubuntu. Others untested.

h1. Usage

```
$ cd ~/some/very/deep/often-used/directory
$ mark deep
```

This adds a symbolic link named deep to the directory ~/.marks. To jump to this directory, type the following from any place in the filesystem:

```
$ jump deep
```

To remove the bookmark (i.e., the symbolic link), type:

```
$ unmark deep
```

You can view all marks by typing:

```
$ marks

deep    -> /home/johndoe/some/very/deep/often-used/directory
foo     -> /usr/bin/foo/bar
```


h1.Install

```
homesick clone git@github.com:neuhalje/homesick-bash-mark_jump.git
echo Please restart your bash now.
```

