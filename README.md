# About
This is a collection of tutorials useful for helping new students to get up and running in computational science. I try to limit to one good link for a given subject, so there is a lot of good material out on the web not listed here.

Most resources here are freely available online, but in some cases a good book is also listed. Much of the intermediate-advanced material at the end are books.

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
- [Makefiles by Lin](https://www.cs.umd.edu/class/fall2002/cmsc214/Tutorial/makefile.html)
- [CMake Tutorial by Lamp](https://www.johnlamp.net/cmake-tutorial-1-getting-started.html)

# Coding Best Practices
- https://github.com/thomasdavis/best-practices
- [Beginner's Guide to Unit Testing](https://www.codementor.io/development-process/tutorial/unit-testing-foundations-programming-beginners)

Some particularly important practices:

- Write for cleanliness first and optimize later (after profiling). A priori performance predictions are often wrong, so starting off with complicated optimizations isn't worth the trouble.
- Write testable code and unit tests.
- Avoid non-const global variables. They make debugging more difficult and obscure data flow.
- Write more short functions rather than fewer large ones. This makes it easier to follow complex logic.
- Comment well, avoiding obvious comments.

# Version Control
- [Learn Enough Git to Be Dangerous by Hartl](https://www.learnenough.com/git-tutorial)
- `$ man gittutorial`
- [How to Write a Git Commit Message by Beams](http://chris.beams.io/posts/git-commit/)

# Debugging
- [A Sample DDD Session](https://www.gnu.org/software/ddd/manual/html_mono/ddd.html#Sample%20Session)
- [The Valgrind Quick Start Guide](http://valgrind.org/docs/manual/quick-start.html)

# Profiling
- [GPROF Tutorial -- How to use Linux GNU GCC Profiling Tool by Arora](http://www.thegeekstuff.com/2012/08/gprof-tutorial/)
- [How to profile C++ application with Callgrind / KCacheGrind by Wicht](http://baptiste-wicht.com/posts/2011/09/profile-c-application-with-callgrind-kcachegrind.html) (also applicable to C and Fortran programs)

# Visualization
- http://www.scipy-lectures.org/intro/matplotlib/matplotlib.html
- [Using Paraview to Visualize Scientific Data](http://www.bu.edu/tech/support/research/training-consulting/online-tutorials/paraview/)
- [Sandia National Laboratories Paraview Tutorials](http://www.paraview.org/Wiki/SNL_ParaView_4_Tutorials)
- [Gnuplot Tutorial by Lindebaum](http://physicspmb.ukzn.ac.za/index.php/Gnuplot_tutorial)

# LaTeX
- https://www.latex-tutorial.com/tutorials/

# Programming Languages

## C
- [The C Programming Language by Kernighan & Ritchie](https://archive.org/details/the_c_programming_language_2)

## C++
- [A Tour of C++ by Stroustrup](https://isocpp.org/tour)
- [C++ Tutorial for C Users by Brasseur](http://www.4p8.com/eric.brasseur/cppcen.html)
- [C++ Primer by Lippman, Lajoie, & Moo](https://www.amazon.com/Primer-5th-Stanley-B-Lippman/dp/0321714113)
- [Accelerated C++ by Koenig & Moo](https://www.amazon.com/Accelerated-C-Practical-Programming-Example/dp/020170353X)

## Modern Fortran
- [Modern Programming Languages: Fortran 90/95/2003/2008 by Koesterke](https://www.tacc.utexas.edu/documents/13601/162125/fortran_class.pdf)

## Python
- [Scipy Lecture Notes](http://www.scipy-lectures.org/)
- [The Python Tutorial](https://docs.python.org/3.5/tutorial/)

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
