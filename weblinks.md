## Code like a Pythonista
[Idiomatic Python](http://python.net/~goodger/projects/pycon/2007/idiomatic/handout.html)

## Creating a virtual environment
```
$ cd my_project_folder
$ virtualenv my_project
```
Creating a virtualenv with python3
```
virtualenv -p python3 envname
```
[Hitch Hikers guide to Python](http://docs.python-guide.org/en/latest/dev/virtualenvs)

## Using VIM like an IDE
[reference](http://vim.wikia.com/wiki/Use_Vim_like_an_IDE)

[Compiling vim from source with python support and other goodies](https://github.com/Valloric/YouCompleteMe/wiki/Building-Vim-from-source)

[List functions in a file](https://github.com/majutsushi/tagbar)

[File browser in vim](https://github.com/scrooloose/nerdtree)

[Code Query: A merge of ctags and cscope](https://github.com/ruben2020/codequery/blob/master/doc/HOWTO-LINUX.md)
Make sure to build with GUI support

[Vim interface to codequery above](https://github.com/devjoe/vim-codequery) 

Another Interesting Project is CQuery which claims support for Vim, but I have not tested it yet. More details can be found on the [Github repo](https://github.com/cquery-project) 

(Vim gdb integration)[https://github.com/vim-scripts/Conque-GDB]

Vim Color Schemes

[Demo of Vim Color Schemes](http://vimcolors.com/)

With the above plugins using the quickfix list to display results, the quickfix list also becomes part of the buffer which is annoying. [The following entry](https://stackoverflow.com/questions/28613190/exclude-quickfix-buffer-from-bnext-bprevious) in .vimrc addresses that problem:
```
augroup qf
    autocmd!
    autocmd FileType qf set nobuflisted
augroup END
```
# Change git difftool to vim
```
git config --global diff.tool vimdiff
git config --global difftool.prompt false
```
## cscope:
[Vim Tutorial](http://cscope.sourceforge.net/cscope_vim_tutorial.html)

[Large Projects](http://cscope.sourceforge.net/cscope_vim_tutorial.html)

## Debugging
[8 Useful GDB Tricks](https://blogs.oracle.com/ksplice/8-gdb-tricks-you-should-know)
[Guide to Faster, Less Frustrating Debugging](http://heather.cs.ucdavis.edu/~matloff/UnixAndC/CLanguage/Debug.html)

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


## Miscellaneous

[SSH Without password](http://www.linuxproblem.org/art_9.html)

[Debug Boost Shared Pointers](http://tools.proteomecenter.org/wiki/index.php?title=Debugging:Working_with_boost::shared_ptr)

[Dumping out all the preprocessor defines in gcc](https://stackoverflow.com/questions/2224334/gcc-dump-preprocessor-defines)
```
gcc -dM -E - < /dev/null
```
[Useful C++ Constants to test type limits etc](http://en.cppreference.com/w/c/types/limits)


### FPGA Stuff

[Good FPGA Tutorial](https://embeddedmicro.com/tutorials/mojo)


### Machine Learning
[Theoretical Machine Learning Lecture Series](https://www.ias.edu/idea-tags/machine-learning)
