## Creating a virtual environment
```
$ cd my_project_folder
$ virtualenv my_project
```
[Hitch Hikers guide to Python](http://docs.python-guide.org/en/latest/dev/virtualenvs)

## cscope:
[Vim Tutorial] (http://cscope.sourceforge.net/cscope_vim_tutorial.html)

[Large Projects] (http://cscope.sourceforge.net/cscope_vim_tutorial.html)

## Debugging
[8 Useful GDB Tricks](https://blogs.oracle.com/ksplice/8-gdb-tricks-you-should-know)
[Guide to Faster, Less Frustrating Debugging] (http://heather.cs.ucdavis.edu/~matloff/UnixAndC/CLanguage/Debug.html)

## Merging development to Master
```
(on branch development)$ git merge master
```
(resolve any merge conflicts if there are any)
```
$ git checkout master
$ git merge development (there won't be any conflicts now)
```
[reference](https://stackoverflow.com/questions/14168677/merge-development-branch-with-master)

## Using VIM like an IDE
[reference](http://vim.wikia.com/wiki/Use_Vim_like_an_IDE)

## Miscellaneous

[SSH Without password] (http://www.linuxproblem.org/art_9.html)

[Debug Boost Shared Pointers] (http://tools.proteomecenter.org/wiki/index.php?title=Debugging:Working_with_boost::shared_ptr)

[Dumping out all the preprocessor defines in gcc] (https://stackoverflow.com/questions/2224334/gcc-dump-preprocessor-defines)
```
gcc -dM -E - < /dev/null
```
[Useful C++ Constants to test type limits etc] (http://en.cppreference.com/w/c/types/limits)
