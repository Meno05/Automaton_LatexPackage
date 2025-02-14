# Automaton Package

**Version**: 1.0 2024/11/11  
**Author**: [Tomke Quintus Pfoch, Matthias Wagner]

## Overview
The `automaton` package is a custom LaTeX package designed for creating TikZ-based automatons, Turing machine and omidirectional graphs graphs. It simplifies the process of creating nodes, start states, end states, and transitions.

## Features
- Environment for automaton diagrams.
- Easy-to-use commands for defining states and transitions.
- EEnvironment for omnidirectional graphs
- Easy-to-use commands for defining vertexes and edges.
- Customizable node sizes in both graphs and automatons

## Requirements
This package requires the following LaTeX packages:
- `tikz` (with various TikZ libraries)
- `expl3`
- `ifthen`

## Installation
Place the `automaton.sty` file in your working directory or in a directory where LaTeX can find it (e.g., `~/texmf/tex/latex/`).

## Usage
Include the package in your LaTeX document with:
```latex
\usepackage{automaton}

