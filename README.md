git-ignore
==========

`git-ignore` provides a command line interface for adding entries to a project's .gitignore file. 

Usage
-----

`cd` anywhere within the working tree of the repository whose .gitignore you'd like to modify and run

    git-ignore "pattern1" [pattern2] [pattern3] ... [-m "Optional message"]

Each specified pattern is appended to .gitignore. For example,

    git-ignore *.o *.a *.so -m "Ignore build files"

adds the following to .gitignore:

    # Ignore build files
    *.o
    *.a
    *.so

Installation
------------

If you move `git-ignore` to some directory in your `$PATH` (perhaps `/usr/bin`), you can use `git ignore` in place of `git-ignore`:

    git ignore *.o *.a *.so -m "Ignore build files"


