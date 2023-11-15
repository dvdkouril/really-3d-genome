# The role of 3D visualization in genomics: A survey
This folder contains source text for a research paper summarizing the efforts in modeling genome structures in 3D. The intended audience is primarily data visualization community. There are many open problems and related opportunities stemming from somewhat recent (2017-2019) advances in generating 3D models of chromatin folding from single cell Hi-C data. Data visualization can play an important role in exploring 3D chromatin data but for many datavis researchers getting solid understanding on the domain from biological perspective is challenging. We therefore aim at giving data visualization researchers the necessary insight into the source of the 3D data, its limitations, and potential utility in biological analysis.

## Exporting
The document is written in org-mode, native to the Emacs editor. Using org-mode, we can export into various formats: Latex->PDF, HTML, Markdown etc.

Step-by-step:
1. open `index.org` in Emacs
2. export bibliography from Zotero into `star3dgenome.bib` (TODO: set up bib file autosync)
3. `C-c C-e h h` for web export

## Web version
On push, Github Actions uploads whatever ends up exported in index.html to Github Pages: [dvdkouril.github.io/really-3d-genome](https://dvdkouril.github.io/really-3d-genome/). Make sure to export (see above) from the org file into index.html before pushing; in the future I might be able to automatize the exporting step, too.
