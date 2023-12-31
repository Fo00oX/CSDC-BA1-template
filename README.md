# LaTeX Template for FH Campus Wien Thesis

This repository contains a LaTeX template designed for university theses, providing a structured format with robust version control.

## Features

- Clean and professional layout.
- Integrated support for citations and bibliographies.
- Chapters, figures, tables, and appendices are well organized.

## Usage

### Compiling the Thesis with Citations

To generate a PDF of your thesis with updated citations, navigate to the thesis directory and run the following commands in your terminal:

    cd /thesis
    pdflatex thesis-main
    bibtex thesis-main
    pdflatex thesis-main
    pdflatex thesis-main

### Compiling the Thesis without Citations

To generate a PDF of your thesis without citations, navigate to the thesis directory and run the following commands in your terminal:

    cd /thesis
    pdflatex thesis-main

Template Structure

    thesis-main.tex: The main LaTeX file which you should compile.
    chapters/: Directory containing individual chapters of the thesis.
    common/: Common components like declaration of authorship, abstract, abbreviations, and appendix.
    images/: Directory for storing images used in the thesis.
    testBib.bib: BibTeX file for bibliography.# CSDC-BA1-template

### Viel Glück bei der Bachelor Arbeit !
