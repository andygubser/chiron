##  Awesome Data Science

> A curated list of awesome things related to data science.
> This mainly serves myself as a list of technologies and methods I used or intend to use.
> See [the list of awesome lists](https://github.com/sindresorhus/awesome) for more general data science listings.


## Contents
* [Notebooks](#notebooks)
* [Integrated Development Environments (IDEs)](#integrated-development-environments-ides)


## Notebooks

### Run By Yourself
* [JupyterLab](https://jupyter.org)
  * ✅ R supported
  * 🢂 IDE with support for notebooks
* [Visual Studio Code](https://code.visualstudio.com)
  * 🢂 IDE with support for notebooks
* [PyCharm](https://www.jetbrains.com/help/pycharm/jupyter-notebook-support.html)
  * ✅ Great refactoring utilities
  * ❌ Rather cumbersome to work with (output to the right in a separate tab instead of below the code cell)
  
### Hosted Solutions
* [Binder](https://mybinder.org)
  * ✅ Interactive execution 
  * ✅ R is supported, incl. R Studio (web version)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    (see the [Docs](https://mybinder.readthedocs.io/en/latest/howto/languages.html#the-r-language) 
    and how to define packages using
    [R](https://github.com/binder-examples/r)
    or
    [conda](https://github.com/binder-examples/r-conda))
  * ✅ No account required
  * 🢂 Notebook needs to be hosted on GitHub (or similar)
  * ❌ Takes some time to rebuild after commits to the notebook
* [Deepnote](https://www.deepnote.com)
  * ✅ Interactive execution 
  * ✅ Real-time collaboration
  * ✅ Commit changes to GitHub
  * 🢂 In Beta
  * ❌ Requires account
* [Colaboratory](https://colab.research.google.com)
  * ✅ Interactive execution 
  * ✅ Notebook import from GitHub without account possible
  * ✅ Save output to Google Drive
  * ✅ GPU available
  * ❌ Requires account for interactive execution
* [nbviewer](https://nbviewer.jupyter.org)
  * ✅ Any public URL works as notebook location
  * ✅ Faster than GitHub's notebook renderer
  * ❌ No interactive execution
* [GitHub](https://github.com)
  * 🢂 Renders notebooks from repositories automatically
  * ❌ No interactive execution


##  Integrated Development Environments (IDEs)

### Run By Yourself
* [JupyterLab](https://jupyter.org)
  * ✅ Supports Python & R kernels in the same project
  * ❌ Lacks good linting
  * ❌ No search/replace function (refactoring in general) across multiple files
* [Visual Studio Code](https://code.visualstudio.com)
  * ✅ Good blend between Notebook capabilities and traditional IDE
* [PyCharm](https://www.jetbrains.com/pycharm/)
  * ✅ Database & SQL support
  * ❌ Only rudimentary Markdown editor
 
### Hosted Solutions
* [Codespaces](https://github.com/features/codespaces/)
  * ✅ Multiple programming languages supported
  * ✅ Based on Visual Studio Code
  * 🢂 In Beta
* [RStudio Cloud](https://rstudio.cloud)
  * 🢂 Targeted at R users
  * 🢂 In Beta
