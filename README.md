# KrdWrd

The KrdWrd Project ran from 2008 to 2011. The mission statement was
> Provide tools and infrastructure for acquisition, visual annotation, merging and storage of web pages as parts of bigger corpora.
>
> Develop a classification engine that learns to automatically annotate pages, and provide visual tools for inspection of results.

Basically, it was an infrastructure for research into web page cleaning. A good
overview can be found in the paper and an extensive description in the master's thesis (both, see [further down](#cite-work)).

## Remnants

1. The **annotation guidelines** and the **Firefox add-on manual** are still
available [online](/manual) and as [pdf
file](https://github.com/krdwrd/manual/releases/download/20100831/manual.pdf).

2. The **CANOLA Corpus**


## System Components

The system consisted of
- Firefox Add-On for interactive visual annotation and retrieval of tagging results
- XulRunner application for batch processing of web pages
- WebProxy and additional server-side infrastructure for providing access to
  corpora and storing annotation results
- Server-side Machine Learning infrastructure for experiments with cleaning models


## Cite Work

### Paper (WAC5)
<!-- {% raw %} -->
```
@inproceedings{StegerStemle2009,
  abstract = {Algorithmic processing of Web content mostly works on textual contents, neglecting visual information. Annotation tools largely share this deficit as well. We specify requirements for an architecture to overcome both problems and propose an implementation, the KrdWrd system. It uses the Gecko rendering engine for both annotation and feature extraction, providing unified data access in every processing step. Stable data storage and collaboration control scripts for group annotations of massive corpora are provided via a Web interface coupled with a HTTP proxy. A modular interface allows for linguistic and visual data feature extractor plugins. The implementation is suitable for many tasks in theWeb as corpus domain and beyond.},
  author = {Steger, Johannes and Stemle, Egon},
  booktitle = {Proceedings of the {Fifth Web} as {Corpus Workshop} ({WAC5})},
  date = {2009-09},
  editor = {Alegria, Iñaki and Leturia, Igor and Sharoff, Serge},
  location = {{Donostia-San Sebastian, Basque Country, Spain}},
  pages = {63-70},
  publisher = {{Elhuyar Fundazioa}},
  title = {{KrdWrd}: {Architecture} for {Unified Processing} of {Web Content}},
  url = {https://www.sigwac.org.uk/raw-attachment/wiki/WAC5/WAC5_proceedings.pdf}
}
```
<!-- {% endraw  %} -->

#### Annotation Guidelines and Firefox Add-On Manual
<!-- {% raw %} -->
```
@report{krdwrd.org/manual,
  abstract = {"The availability of large text corpora has changed the scientific approach to language in linguistics and cognitive science" [M\&S]. Today, the by far richest source for authentic natural language data is the World Wide Web, and making it useful as a data source for scientific research is imperative. Web pages, however, can not be used for computational linguistic processing without filtering: They contain code for processing by the Web browser, there are menus, headers, footers, form fields, teasers, out-links, spam-text – all of which needs to be stripped.
The dimension of this task calls for an automated solution, the broadness of the problem for machine learning based approaches. Part of the KrdWrd project deals with the development of appropriate methods, but they require hand-annotated pages for training.
The KrdWrd Add-on aims at making this kind of tagging of Web pages possible. For users, we provide accurate Web page presentation and annotation utilities in a typical browsing environment, while preserving the original document and all the additional information contained therein.},
  author = {{The KrdWrd Team (krdwrd.org)}},
  date = {2010},
  publisher = {{The KrdWrd Project}},
  title = {Add-on manual},
  url = {https://krdwrd.org/manual/manual.pdf}
}

```
<!-- {% endraw  %} -->

### Master's Thesis
<!-- {% raw %} -->
```
@thesis{Stemle2009,
  abstract = {This thesis discusses the KrdWrd Project. The Project goals are to provide tools and infrastructure for acquisition, visual annotation, merging and storage of Web pages as parts of bigger corpora, and to develop a classification engine that learns to automatically annotate pages, operate on the visual rendering of pages, and provide visual tools for inspection of results.},
  author = {Stemle, Egon W.},
  date = {2009-04},
  institution = {{University of Osnabrück}},
  pubstate = {Unpublished},
  title = {Hybrid {{Sweeping}}: {{Streamlined Perceptual Structured}}-{{Text Refinement}}},
  type = {Master's thesis},
  url = {https://files.zotero.net/2482122318/stemle_2009_hybrid_sweeping.pdf}
}

```
<!-- {% endraw  %} -->
