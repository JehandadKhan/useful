Guide to Faster, Less Frustrating Debugging
link: http://heather.cs.ucdavis.edu/~matloff/UnixAndC/CLanguage/Debug.html


cscope:
Vim Tutorial: http://cscope.sourceforge.net/cscope_vim_tutorial.html

Large Projects: http://cscope.sourceforge.net/cscope_vim_tutorial.html

SSH Without password: http://www.linuxproblem.org/art_9.html
Debug Boost Shared Pointers: http://tools.proteomecenter.org/wiki/index.php?title=Debugging:Working_with_boost::shared_ptr
ctags and vim:

[Dumping out all the preprocessor defines in gcc]
ref: https://stackoverflow.com/questions/2224334/gcc-dump-preprocessor-defines
```
gcc -dM -E - < /dev/null
```

Useful C++ Constants to test type limits etc

http://en.cppreference.com/w/c/types/limits

## 8 Useful GDB Tricks
[gdb tricks][https://blogs.oracle.com/ksplice/8-gdb-tricks-you-should-know]

## Merging development to Master
https://stackoverflow.com/questions/14168677/merge-development-branch-with-master

(on branch development)$ git merge master
(resolve any merge conflicts if there are any)
git checkout master
git merge development (there won't be any conflicts now)
