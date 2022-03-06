# Life science complexity PhD thesis - 2018

This repository contains the files used to generate my thesis for obtaining the PhD degree in Genomics from the Sorbonne University.

The main source files are written in LaTeX, but this repository also includes PDF files of a published article related to this work, as well as, PDF files of an article that was in preparation at the time of submission. Only the files related to the Bitetti et al. 2018 article and the images that are part of the introduction are not included in this repository, however, the permissions obtained to reproduce the images on my thesis can be found in the 'figures' folder.

## Author

Yuvia Alhelí PÉREZ-RICO

Affiliations: Sorbonne Université, Institut Curie

## Required Software

To compile the source files and generate the final PDF file, you would need to install the pdflatex tool and pdfpages package.

When the setup is ready, you would just need to run the following lines to get the PDF file including the list of abbreviations:

`pdflatex phd_thesis_Perez-Rico.tex`

`makeindex phd_thesis_Perez-Rico.nlo -s nomencl.ist -o phd_thesis_Perez-Rico.nls`

`pdflatex phd_thesis_Perez-Rico.tex`

## Citation

Please cite the thesis or research articles as follows:

- *Yuvia Alhelí Pérez Rico. Zebraﬁsh as a model to determine conserved gene regulatory mechanisms in vertebrates. Biochemistry, Molecular Biology. Sorbonne Université, 2018. English. ⟨NNT : 2018SORUS535⟩. ⟨tel-02892255⟩*
- *Pérez-Rico YA, Boeva V, Mallory AC, et al. Comparative analyses of super-enhancers reveal conserved elements in vertebrate genomes. Genome Research. 2017 Feb;27(2):259-268. DOI: 10.1101/gr.203679.115. PMID: 27965291; PMCID: PMC5287231.*
- *Pérez-Rico YA, Barillot E, Shkumatava A. Demarcation of Topologically Associating Domains Is Uncoupled from Enriched CTCF Binding in Developing Zebrafish. Iscience. 2020 May;23(5):101046. DOI: 10.1016/j.isci.2020.101046. PMID: 32334414; PMCID: PMC7182764.*
- *Bitetti A, Mallory AC, Golini E, et al. MicroRNA degradation by a conserved target RNA regulates animal behavior. Nature Structural & Molecular Biology. 2018 Mar;25(3):244-251. DOI: 10.1038/s41594-018-0032-x. PMID: 29483647.*

## Links to thesis repositories

You can find the PDF output of this repository in:

- [Theses.fr](http://theses.fr/2018SORUS535)
- [Hal open archive](https://tel.archives-ouvertes.fr/tel-02892255)

## License

Licenced under the MIT License.
