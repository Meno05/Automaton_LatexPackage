# Automaton Package

**Version**: 1.0 2024/11/11  
**Author**: [Tomke Quintus Pfoch, Matthias Wagner]

## Overview
The `automaton` package is a custom LaTeX package designed for creating TikZ-based automatons and Turing machine graphs. It simplifies the process of creating nodes, start states, end states, and transitions.

## Features
- Environment for automaton diagrams.
- Easy-to-use commands for defining states and transitions.
- Customizable node sizes.


## Requirements
This package requires the following LaTeX packages:
- `tikz` (with various TikZ libraries)
- `xstring`
- `etoolbox`
- `expl3`
- `ifthen`

## Installation
Place the `automaton.sty` file in your working directory or in a directory where LaTeX can find it (e.g., `~/texmf/tex/latex/`).

## Usage
Include the package in your LaTeX document with:
```latex
\usepackage{automaton}

