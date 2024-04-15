A template for managing LaTeX files.

# Structure

The Makefile assumes a certain structure to the directories:

```latexfiles/```  contains the "mnras-paper.tex", "references.bib", and aux files

```assets/```      contains the .png, .eps files to be included

# Commands

```make pdf``` generates a "mnras-paper.pdf" in the Makefile directory.
Generating the pdf requires latexmk.

```make edit``` opens the "mnras-paper.tex" file using the editor.

```make clean``` removes the aux generated files in ```latexfiles/``` and the "mnras-paper.pdf".

# Info

The default editor being used is helix (hx).

The mnras-paper.tex is the main file to edit.
