# About
This is a collection of tutorials useful for helping new students to get up and running in computational science.

Most resources here are freely available online, but in some cases a good book is also listed. The advanced material provided at the end is almost entirely books available for purchase.

# Getting Started

## Running a UNIX-like Operating System
For the most part, research software is written for UNIX-like operating systems. Mac users are already good to go, but it isn't a bad idea to be familiar with a Linux distribution too. If you're a Windows user, you will likely find it easiest to install Ubuntu, but any popular Linux distribution is fine. Below are two ways to set up Ubuntu.

- [Dual-Boot Ubuntu and Windows 10](http://www.everydaylinuxuser.com/2015/11/how-to-install-ubuntu-linux-alongside.html) (Recommended if you expect to use Ubuntu long-term)
- [Install Ubuntu on Oracle VirtualBox](http://linus.nci.nih.gov/bdge/installUbuntu.html)

## Installing Software
- [Apt](https://help.ubuntu.com/lts/serverguide/apt.html) for Ubuntu (installed by default)
- [Homebrew](http://brew.sh/) for Mac

# Using the Terminal
- [Learn Enough Command Line to Be Dangerous by Hartl](https://www.learnenough.com/command-line-tutorial)

# Text Editors
If you expect to be spending some time on a computer cluster through SSH, some familiarity with a terminal-based text editor is a must even if it isn't your primary tool for development.

## Emacs
- `C-h t` within Emacs or `$ emacs --eval "(help-with-tutor)"`
- [Absolute Beginner's Guide to Emacs by Hamrick](http://www.jesshamrick.com/2012/09/10/absolute-beginners-guide-to-emacs/)
- [Beginner's Guide to Emacs by Petersen](https://www.masteringemacs.org/article/beginners-guide-to-emacs)

## Vim
- `$ vimtutor`
- [A Vim Tutorial and Primer by Miessler](https://danielmiessler.com/study/vim/)

# Compilation and Build Systems
- [Beginners Guide to GCC by Pakrashi](https://phoxis.org/2009/12/01/beginners-guide-to-gcc/)

# Coding Best Practices
- https://github.com/thomasdavis/best-practices

Some particularly important practices:

- Write for cleanliness first and optimize later (after profiling). A priori performance predictions are often wrong, so starting off with complicated optimizations isn't worth the trouble.
- Avoid non-const global variables. They make debugging more difficult and obscure data flow.
- Write many short functions instead of a few large ones. This makes it easier to follow complex logic.
- Comment well, avoiding obvious comments.

# Version Control
- [Learn Enough Git to Be Dangerous by Hartl](https://www.learnenough.com/git-tutorial)
- `$ man gittutorial`
- [How to Write a Git Commit Message by Beams](http://chris.beams.io/posts/git-commit/)

# Unit Tests
TODO

# Debugging & Profiling Tools
TODO: gdb+ddd, valgrind, and gprof

# Visualization
TODO: matplotlib and paraview

# LaTeX
- https://www.latex-tutorial.com/tutorials/
- [LaTeX Mini-Tutorial by Corral](http://mecmath.net/latex-tutorial.pdf)

# Programming Languages

## C
- [The C Programming Language by Kernighan & Ritchie](https://archive.org/details/the_c_programming_language_2)

## C++
- [A Tour of C++ by Stroustrup](https://isocpp.org/tour)
- [C++ Tutorial for C Users by Brasseur](http://www.4p8.com/eric.brasseur/cppcen.html)
- [C++ Primer by Lippman, Lajoie, & Moo](https://www.amazon.com/Primer-5th-Stanley-B-Lippman/dp/0321714113)
- [Accelerated C++ by Koenig & Moo](https://www.amazon.com/Accelerated-C-Practical-Programming-Example/dp/020170353X)

## (Modern) Fortran
- [Modern Fortran](https://bitbucket.org/eric_t/modern-fortran/wiki/Home)
- [Modern Programming Languages: Fortran 90/95/2003/2008 by Koesterke](https://www.tacc.utexas.edu/documents/13601/162125/fortran_class.pdf)

## Python
- [Scipy Lecture Notes](http://www.scipy-lectures.org/)

# Parallel Computing
- [MPI Tutorial by Kendall, Nath, & Bland](http://mpitutorial.com/)
- [OpenMP by Barney](https://computing.llnl.gov/tutorials/openMP/)

# Miscellaneous
- http://choosealicense.com/

# Beyond the Basics
- [The C++ Programming Language by Stroustrup](https://www.amazon.com/C-Programming-Language-4th/dp/0321563840)
- [Modern Fortran Explained by Metcalf, Reid, & Cohen](https://www.amazon.com/Explained-Numerical-Mathematics-Scientific-Computation/dp/0199601429)
- [The Quick Python Book by Ceder](https://www.amazon.com/Quick-Python-Book-Second/dp/193518220X)
- [Fluent Python by Ramalho](https://www.amazon.com/Fluent-Python-Luciano-Ramalho/dp/1491946008)
- [Pro Git by Chacon & Straub](https://git-scm.com/book/en/v2)
- [Mastering Emacs by Petersen](https://www.masteringemacs.org/)
- [Practical Vim by Neil](https://pragprog.com/book/dnvim2/practical-vim-second-edition)
- [The Not So Short Introduction to LaTeX by Oetiker et al](https://tobi.oetiker.ch/lshort/lshort.pdf)
- [LaTeX Wikibook](https://en.wikibooks.org/wiki/LaTeX)
