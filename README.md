# Data science with Julia

## What is Julia and why is it particularly suitable for data science?

___"Walks like Python, runs like C"___ - it has been said about Julia, a modern programming language, focused on scientific computing, and having an ever increasing base of followers and developers.

Julia, a general purpose programming language is made specifically for scientific computing. It is a flexible dynamic language with performance comparable to traditional statically-typed languages. Julia tries to provide a single environment productive enough for prototyping and efficient for industry grade applications.

It is a multi-paradigm ([dynamically-typed](https://android.jlelse.eu/magic-lies-here-statically-typed-vs-dynamically-typed-languages-d151c7f95e2b), partially [functional](https://en.wikipedia.org/wiki/Functional_programming), and partially [object-oriented](https://en.wikipedia.org/wiki/Object-oriented_programming)) programming language designed for scientific and technical computing. It provides significant performance benefits over Python (when used without optimization and vector computing using Cython and NumPy).

### A (very) short history and the open-source nature

The inception of this programming language can be traced back to 2009. The lead developers Alan Edelman, Jeff Bezanson, Stefan Karpinski and Viral Shah started working on creating a language that can be used for better and faster numerical computing. The developers were able to launch a commercial release on February 2012.

Since then, the language has become very popular among the programmers as it provides the ease of many high-level languages with a better performance. The language was launched under a liberal MIT license. This means that Julia is an open source language which can be used and/or modified without any right infringement.

[See this article](https://www.cleverism.com/skills-and-tools/julia/)

### Why is it awesome?

(Read more [here](https://www.quora.com/What-is-so-special-about-the-Julia-programming-language))

- **Smooth learning curve**, and extensive underlying functionality. Especially, if you are already familiar with the more popular data science languages like Python and R, picking up Julia will be a walk in the park.

- **Performance**: Originally, Julia is a compiled language, while Python and R are interpreted. This means that the Julia code is executed on the processor as a direct executable code. There are customizations that can be made for compiler output which can not be done with an interpreter.

- **GPU Support**: It is directly related to performance. GPU support is transparently controlled by some packages such as `TensorFlow.jl` and `MXNet.jl`.

- **Distributed and Parallel Computing Support**: Julia supports parallel and distributed computing transparently using many topologies. And there is also support for coroutines, like in Go programming language, which are helper functions that work in parallel on the Multicore architecture. Extensive support for threads and synchronization is primarily designed to maximize performance and reduce the risk of race conditions.

- **Rich data science and visualization libraries**: Julia community understands that it was conceived as a go-to language for data scientists and statisticians. Therefore, high-performance libraries focusing on data science and analytics are always in development.

- **Teamwork (with other languages/frameworks)**: Julia plays really really well with other established languages and frameworks for data science and machine learning. Using `PyCall` or `RCall` one can use native Python or R code isnide a Julia script. The `Plots` package works with various backend including `Matplotlib` and `Plotly`. Popular machine learning libraries like `Scikit-learn` or `TensorFlow` already have Julia equivalent or wrappers.

## The Julia Community: Who is a user?¶

There is a [fantastic intro to Julia and its features here](http://ucidatascienceinitiative.github.io/IntroToJulia/Html/JuliaMentalModel). As per this article,

- Julia, being high performance and equipped with heavy "CS" features, all while a scripting language, has attracted a diverse audience.
- A large group of Julia users are ex-MATLAB users interested in using Julia for faster numerical linear algebra applications.
- Another significant group are the machine learning and statistics users from R/Python looking to solve the "two-language" problem.
- Another group (a lot of Base contributors) are C/Fortran developers who are looking to increase productivity without sacrificing speed.
- Another group are "general-purpose" users: using Julia to develop faster web frameworks, compilers, and anyting else you can think of!
- Another group is from functional programming languages (Haskell) and Lisps (Clojure, Femtolisp) interested in Julia's metaprogramming and parallelism.

**Julia combines the interests, features, and libraries of all of these groups.** 

_"We want a language that’s **open source**, with a liberal license. We want the **speed** of C with the **dynamism** of Ruby. We want a language that’s **homoiconic**, with true macros like Lisp, but with obvious, **familiar mathematical notation** like Matlab. We want something as usable for **general programming** as Python, as **easy for statistics** as R, as **natural for string** processing as Perl, as **powerful for linear algebra** as Matlab, as good at gluing programs together as the shell. Something that is dirt **simple to learn**, yet keeps the most serious hackers happy. We want it **interactive** and we want it **compiled**."_

---

## Official Julia docs

Julia docs are pretty detailed and helpful. They can be found here: [Official Julia docs](https://docs.julialang.org/en/v1/)

## Installation

Julia installation is straightforward, whether using precompiled binaries or compiling from source. Download and install Julia by following the instructions at https://julialang.org/downloads/.

## Console

The easiest way to learn and experiment with Julia is by starting an interactive session (also known as a read-eval-print loop or "REPL") by double-clicking the Julia executable or running julia from the command line. But we prefer to install IJulia and launch a Jupyter notebook.

## What is `IJulia`?
IJulia is a Julia-language backend combined with the Jupyter interactive environment (also used by IPython). This combination allows you to interact with the Julia language using Jupyter/IPython's powerful graphical notebook, which combines code, formatted text, math, and multimedia in a single document. It also works with [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/), a Jupyter-based integrated development environment for notebooks and code.

First, download Julia version 0.7 or later and run the installer. Then run the Julia application (double-click on it); a window with a julia> prompt will appear. At the prompt, type:

    using Pkg
    Pkg.add("IJulia")

to install IJulia.

This process installs a kernel specification that tells Jupyter (or JupyterLab) how to launch Julia. If you already had Jupyter (notebook or lab) on your system (e.g. for your Python work), then you can just launch it and expect the Julia kernel to show up i.e. you can spin up a new notebook with a Julia kernel and start programming!

---
## Our focus
We are focused on learning Julia for data science and machine learning tasks. A series of Jupyter notebooks will cover the necessary topics - fundamentals, data structures, language features, functions, arrays, linear algebra, statistics, plots, DataFrames, etc.

Go to the [Notebooks](https://github.com/tirthajyoti/Julia-basics/tree/master/Notebooks) section to find exciting Jupyter notebooks covering fundamentals of Julia data structures, syntax, arrays, linear algebra, and statistics.
