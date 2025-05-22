# Pandoc-based publishing workflow for academic papers

This is the repository of my thesis publication at https://utaschulz1.github.io/TCLocThesis/

It serves to demonstrate a Pandoc-based publishing framework for Markdown files on GitHub using GitHub Actions.

## What can you do with this repository

You can use this repository online in your GitHub account with GitHub Actions. You can upload Markdown files and will get a website and a PDF file for download, published on GitHub Pages.

The repository takes Markdown files that are intended to be chapters of a book and converts them into HTML files and a single PDF file. Then, it publishes the HTML to a home page and several chapter pages and provides a download button for the PDF file.

As soon as you save any file in the repository, the build process will start using GitHub Actions. The actions basically consist of installing Linux, Pandoc, and TinyTeX, as well as executing a bash script.

The bash script (`lantern.sh`) orchestrates the conversion of the files and the build of the website and the PDF using the templates in the repository.

## Credits

This repository uses [Lantern](https://github.com/nulib-oer/lantern/wiki) with a few changes:
- It uses Pandoc with TinyTeX for PDF creation using `pdf-template.tex`, not PagedJS.
- I added `lantern-debug.sh` and the corresponding GitHub Actions. For debugging the PDF creation, in `.github/workflows`, change `lantern.sh` to `lantern-debug.sh` and uncomment the `intermediate.tex` action. You can find the `.tex` file in the Actions tab in the action you ran under artifacts.
- I added an image slider on top for a presentation.
- Various changes to the layout:
  - Moved the theme switcher to the top.
  - Added a hamburger menu in the chapter view.
  - Added a table of contents in the chapter view.

## Getting started (TODO)