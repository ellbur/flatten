
Moves all of `<dir>/*` to `<dir>/..` and then deletes `<dir>`.

    $ mkdir a
    $ touch a/b
    $ touch a/c
    $ flatten a
    $ ls
    b  c


