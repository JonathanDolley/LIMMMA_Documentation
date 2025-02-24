# Readme

## How to suggest edits

If you have a github account you can suggest edits to any part of the documentation book by editing the source files (those with the extension .qmd) in this repository.

The chapters are all at the top of the file list from '01-key-features.qmd' to '06-use-ai.qmd' while the files 'index.qmd' and 'intro.qmd' are where you can edit the text for the "About this book" section and the "Introduction" section respectively.

In the 'demo' folder you will find all of the slideshow walkthroughs of specific operations that are included in each of the use case chapters. You can suggest text edits to each of these by editing the 'index.qmd' files in each of the sub-folders (e.g. '03-01-open-model-view').

When you click on one of the qmd files it will show you the contents of the file. Click on edit to enter the file and start to suggest changes which you will then need to submit for approval by the owner of the repository.

## Technical notes

How to render revealjs slides to embed in a book project:
https://github.com/quarto-dev/quarto-cli/discussions/1433

Using this method it is possible to render the entire project and publish to netlify by uploading the _book folder directly.

Publishing to quarto.pub doesn't work properly because the revealjs slides don't render properly and are displayed as if they are pure markdown rather than converted into revealjs html slides.