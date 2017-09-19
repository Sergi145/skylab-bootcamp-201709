![Skylab Coders Academy](http://www.skylabcoders.com/images/403/default.png "Skylab Coders Academy")

Skylab FullStack WebDevelopment Bootcamp 201709
===============================================

![calendaro del curso][calendar]

# Basic Tools

## Console

*Emulators*:

[Commander](http://cmder.net)
[Cygwin](http://cygwin.com)

### Useful how-to's

- see path to working directory

```bash
$ pwd
```

- list files in directory

```bash
$ ls
```

- list files in list mode

```bash
$ ls -l
```

- list hidden files

```bash
$ ls -a
```

- combine listing modes (ex: hidden and list mode)

```bash
$ ls -la
```

- create an empty file

```bash
$ touch <file>
```

- create a file with content in one command

```bash
$ echo "<content with spaces>" > <file>
```

- see the content of a text file

```bash
$ cat <file>
```

vim-like

```bash
$ less <file>
```

- create a directory

```bash
$ mkdir <directory>
```

- copy a file

```bash
$ cp <from-file> <to-file>
```

- copy a directory

```bash
$ cp -r <from-directory> <to-directory>
```

- move or rename a file or directory

```bash
$ mv <from-file-or-directory> <to-file-or-directory>
```

- move a directory with content

```bash
$ mv -r <from-directory> <to-directory>
```

- remove a file

```bash
$ rm <file>
```

- remove a directory

```bash
$ rm -d <directory>
```

- remove a directory recursively

```bash
$ rm -r <directory>
```

## Markdown

### Links

[Google](http://www.google.com "Google!")

### References

This is [an example][id] reference-style link.
This is [an example][id] reference-style link.

[id]: http://example.com/  "Optional Title Here"

### Tables

<table>
    <tr>
        <td>Hellow</td><td>World</td>
    </tr>
</table>

### Code block

<code>
    This is a code block.
</code>

### Lists

* One
* Two
* Three

- A
- B
- C

<ul>
    <li>a</li>
    <li>b</li>
    <li>c</li>
</ul>

1.  Bird
1.  McHale
3.  Parish

<ol>
    <li>a</li>
    <li>b</li>
    <li>c</li>
</ol>


a. 1
b. 2
c. 3

### Emphazises

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

### Blockquotes

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

> ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
>     return shell_exec("echo $input | $markdown_script");

### Comments

```html
<!-- this is a comment -->
```

## Git

* Init a bare repo ("remote")

```bash
$ git init --bare
```

* Init a local repo (to be connected to remote repo)

```bash
$ git init
```

* Add file or directory to stage

```bash
$ git add <file-or-directory>
```

* Remove file or directory from stage

```bash
$ git rm --cached <file-or-directory>
```

* Commit a the changes in stage

```bash
$ git commit -m '<a short message that describes  the commit>'
```

* Push changes from local to remote repo

```bash
$ git push
```

* Pull changes from remote to local repo

```bash
$ git pull
```

[calendar]: images/calendar.jpg

<<<<<<< HEAD
#Staff

kevinros1992@hotmail.com
github.com/kevinrosmusic


# Staff

manuelbarzi@gmail.com
github.com/manuelbarzi
github.com/marcrg
ricardo.martinez.monje@gmail.com
github.com/mtzfactory

<<<<<<< HEAD
=======

escolano_garnica@hotmail.com
github.com/micheloncio


>>>>>>> 1e0a49b0c092c3806d842396f92a5e25c7e2e34d
