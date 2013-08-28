Plugin for https://github.com/neuhalje/homesick-bash

Based on http://jeroenjanssens.com/2013/08/16/quickly-navigate-your-filesystem-from-the-command-line.html

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

