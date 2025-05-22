# Pandoc-based publishing workflow for academic papers

This is the repository of my Thesis publication at https://utaschulz1.github.io/TCLocThesis/

This repository uses [Lantern](https://github.com/nulib-oer/lantern/wiki) with a few changes:
- It uses Pandoc with TinyTeX for PDF creation using the pdf-template.tex, not PagedJS.
- I added lantern-debug.sh and the corresponding github actions. For debugging the pdf creation, in .github/workflows, change lantern.sh to lantern-debug.sh and uncomment the intermediate.tex action. You can find the tex file in the actions tab in the ation you ran under artefacts.
- I added an image slider on top for a presentation.
- Moved the theme switcher to the top and enlarged it for usability.
- Changed the home.css, work in progress: improve mobile responsiveness
