# garrafitapet
A tiny LaTeX package for drawing a Klein bottle


garrafitapet

A tiny LaTeX package for drawing a Klein bottle.

garrafitapet is a lightweight LaTeX package that provides a miniature TikZ illustration of the Klein bottle.

With a single command, you can insert a representation of this fascinating mathematical object into your LaTeX documents.

Installation

Place garrafitapet.sty in the same directory as your main .tex file.

Then load the package in your document preamble:

latex
\usepackage{garrafitapet}


The package automatically loads TikZ.

Usage

Simply type:

latex
\garrafaklein


That's it!

Example
latex
\documentclass{article}

\usepackage{garrafitapet}

\begin{document}

Here is a Klein bottle:

\garrafaklein

\end{document}

Requirements
A working LaTeX distribution.
TikZ/PGF.
License

This package is distributed under the LaTeX Project Public License (LPPL), version 1.3c or later.

See the LICENSE file for details.

Author

Copyright (C) 2026 [YOUR FULL NAME]

Repository

GitHub repository

A small bottle for a big mathematical idea.
