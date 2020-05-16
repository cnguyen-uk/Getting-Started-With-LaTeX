# Getting Started With LaTeX
*A friendly beginner's guide to getting started with LaTeX.*

LaTeX is made for editorial purposes, so you don't need to be a programmer to use it at all!

## Table of Contents

- [Why Should I Even Care About LaTeX?](#why-should-i-even-care-about-latex)
- [Setting Things Up](#setting-things-up)
  * [Distributions](#distributions)
  * [Editors](#editors)
- [Getting Started](#getting-started)

## Why Should I Even Care About LaTeX?

At some point in your mathematics career, you will need to produce mathematics to be read by someone else. LaTeX is a high-quality typesetting system made precisely for this.

Initially you may be content with just using Microsoft Word, but in the long-term **not** using LaTeX is extremely slow, frustrating, and error-prone. Once you get over the initial learning curve, LaTeX will automate a lot of the manual efforts that you previously put into typesetting your work, and produce significantly more beautiful documents.

If you're an undergraduate student (or anyone really), LaTeX will be great for helping you clean up your mathematics assignments. Instead of wasting time rewriting your assignments neatly for submission, LaTeX will accelerate this process since it will (eventually) depend on your typing speed. In particular, it is easier to notice and fix any errors in work which is produced cleanly in LaTeX, rather than work which is (potentially messily) handwritten.

It's also quite common to just type raw LaTeX when typing emails to your tutor, supervisor, lecturers, or colleagues.

## Setting Things Up

This section is only required if you wish to create LaTeX documents *locally*. If you want to skip this set up process, then you may instead use an online LaTeX editor such as [Overleaf](https://www.overleaf.com/).

### Distributions

Before we can do anything, we need to download a **distribution**. When using LaTeX itself, there are many symbols and commands available to use, but to use them in the first place we need to specify the **packages** that we wish to use. For example, if you want to create a matrix, then you'll need to use a package called `amsmath`.

It's the job of the distribution to deal with downloading these packages for you (you'll notice this when you first try to compile a LaTeX document for the first time). There are many out there, but the recommended one for Windows is [MiKTeX](https://miktex.org/download). For Mac, you can still use MiKTeX, but you may instead prefer to use [MacTeX](https://tug.org/mactex/mactex-download.html).

### Editors

The next step is to download an actual LaTeX editor, where you will create your documents. Once again, there are many to choose from, but I personally recommend [Texmaker](https://www.xm1math.net/texmaker/).

Texmaker is very beginner friendly, and without much effort, you'll have accidentally memorised many LaTeX commands within a couple of days. It features autocomplete suggestions, so if you only remember part of a command, it will help you out. I started using LaTeX in 2016, and I'm still using Texmaker now!

Finally, to make life easier for yourself, we can simplify the compilation process. First launch Texmaker and then, at the top, click on *Options*, then *Configure Texmaker*. On the left side, click *Quick Build*, then under *Quick Build Command*, select *PdfLaTeX + View PDF*, then click *OK*. So now to compile your document (when you make one), all you have to do is hit the F1 key. Alternatively, near the top, there are two blue arrows pointing right. To the right of the first one is a dropdown menu - select *Quick Build*. Now all you have to do is click the first blue arrow to compile your document (when you make one).

## Getting Started

With all of the installation business out of the way, you can start working on producing documents!

Whenever you want to make a new document, you should give it a separate folder on your computer, since compiling a LaTeX document produces four other files, so things can get messy quite quickly.

The [template.tex](https://github.com/cnguyen-uk/Getting-Started-With-LaTeX/blob/master/template.tex) can be used to get yourself started quickly so that you don't need to spend time searching for which packages you need to use. Put this into its own folder and experiment with it (if you're using LaTeX locally, then it is normal for the first compilation to take some time since the distribution needs to download packages). If at the bottom you have the *Structure* menu open, then on the very left you can use the small boxes to help you find some common symbols.

Here are some more common pieces of LaTeX that will be useful (just refer to these when you need to - you absolutely do not need to memorise the pages):

- [Mathematical Expressions](https://www.overleaf.com/learn/latex/Mathematical_expressions)
- [Subscripts and Superscripts](https://www.overleaf.com/learn/latex/Subscripts_and_superscripts)
- [Brackets and Parentheses](https://www.overleaf.com/learn/latex/Brackets_and_Parentheses)
- [Fractions and Binomials](https://www.overleaf.com/learn/latex/Fractions_and_Binomials)
- [Aligning Equations With amsmath](https://www.overleaf.com/learn/latex/Aligning_equations_with_amsmath)
- [Operators](https://www.overleaf.com/learn/latex/Operators)
- [Spacing in math mode](https://www.overleaf.com/learn/latex/Spacing_in_math_mode)
- [Integrals, Sums and Limits](https://www.overleaf.com/learn/latex/Integrals,_sums_and_limits)
- [Display Style in math mode](https://www.overleaf.com/learn/latex/Display_style_in_math_mode)
- [List of Greek Letters and Math Symbols](https://www.overleaf.com/learn/latex/List_of_Greek_letters_and_math_symbols)
- [Mathematical Fonts](https://www.overleaf.com/learn/latex/Mathematical_fonts)

You can also use [Detexify](http://detexify.kirelabs.org/classify.html) to find the code for symbols. Finally, Google is always useful when you add "latex" to your search.
