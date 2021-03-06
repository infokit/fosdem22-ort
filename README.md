## Open Research Toolkit: A Design Proposal

Towards a Software Architecture for Scientific Research Methods

## Abstract

Research software embody paradigms and methods of scientific research and mediate their - more or less - rigorous application. This means, open research software engineers are not only contributing to the tools of scientific enquiry but also work on advancing the latest scientific instruments and methods.

Reflecting on my deep-dive into scientific work I would like to bright up the spirits through outlining a futuristic systems architecture spanning 
different methods and phases of a scientific research process. In my example, the research process involved two trans-disciplinary literature reviews, 
multiple text and image analyses, categorization and clustering tasks, conceptual modeling, construct mapping, designing the research processes, but 
most of all, it involved reading. 

The interoperability of the existing dekstop tools supporting so called active reading of data stemming from a variety of sources is still quite wild.
Second hand data sources are especially diverse but also primary data, gathered through e.g. observation, interviewing, or analyzing various types of 
media seems still hard to get straight. Most recent scientific articles are stored directly next to screenshots capturing key messages from online conferences. 

Starting from this scenery, I want to share and discuss some design principles and an architecture draft, following which a future open research toolkit could 
be developed in coordination with a wide variety of open science software & data projects.


I would like to conclude with three slides outlining an architecture to systematize these functionalities along research methods, and integrate these 
along concurrent phases in research projects. These architecture drafts may help to systematically reflect on our common uses cases, research methods, 
design principles, digital standards and therewith would facilitate the continious and systematic integration of a wide range of open research 
software projects into highly individual personal processes of research.

## Objective

Facilitate the pooling of coding efforts on (often poorly funded) open research software tools.  At best, this is a conversation starter and facilitates 
the creation of interest and networks which would like to participate in the construction of an open source research software stack on a bauhaus scale.

## FLOSS Research Software Tools & Relevant Data Formats

Utilizing a mixed set of research methods for creating the framework, I want to share 11 slides representing one software application, each representing 
a category of research software applications:

| Software Categorry | F/L/OSS Applications | Proprietary (Web) Services | Research Data Formats |
| --------------- | --------------- | --------------- | --------------- |
| Web Browser | [Firefox](https://firefox.org) |   |   |
| Text/Markdown Editor | [Joplin](https://joplinapp.org/)  |   |   |
| Document Editor | [LibreOffice](https://libreoffice.org)  |   |   |
| Document Viewer | [Evince](https://wiki.gnome.org/Apps/Evince), [Okular](https://okular.kde.org/) |   |   |
| Document Search |   |   |   |
| Optical Character Recognition |   |   |   |
| Textification | [Apache Tika](https://tika.apache.org/) |  |  |
| Text Classification & Indexing |  | [Scite.ai](https://scite.ai) |   |
| Text Tokenization & Lemmatization | [spaCy](https://spacy.io/), [NLTK](https://www.nltk.org/)  |   |   |
| Named Entity Recognition Tools | [spaCy](https://spacy.io/), [NLTK](https://www.nltk.org/) |   |   |
| Bibliography Management |  |  | [.bib](https://en.wikipedia.org/wiki/BibTeX), [.ris](https://en.wikipedia.org/wiki/RIS_(file_format))  |
| Bibliographic Databases |  [OpenAlex](https://openalex.org/) (Formerly MAG)  | [WoS](https://en.wikipedia.org/wiki/Web_of_Science), [Scopus](https://www.scopus.com/search/form.uri?display=basic), [Google Scholar](scholar.google.de/) | [.bib](https://en.wikipedia.org/wiki/BibTeX), [.ris](https://en.wikipedia.org/wiki/RIS_(file_format)) |
| Graph Data Representation |   |   |   |
| Network Analysis |   |   |   |
| Concept Mapping  |   |   |   |
| Vocabulary & Taxonomy Management  |   |   |  [SKOS](https://www.w3.org/2004/02/skos/)  |
| Ordinary Data Capture  |   |   |   |
| Archival |   |   |   |
| Data Cleanup/Wrangling |   |   |   |
| Workflow Engines / Processing Pipelines | [KNIME](https://github.com/knime/knime-core) |   | [CommonWL](https://www.commonwl.org/user_guide/)  |
| Data Analysis |   |   |   |
| Date/Time Recognition & Time Queries |   |   |   |

## Current prototype environment

The [DMX Platform](/dmx-systems/dmx-platform) with its standard plugins: Notes, Contacts, Events, Files, Bookmarks and Topicmaps. Here is a [short introduction on DMX design fundamentals](https://dmx.readthedocs.io/en/latest/intro.html). It's [plugin architecture is described here](https://dmx.readthedocs.io/en/latest/devel.html) and its [source code is available here](/dmx-systems/dmx-platform). The platform is mostly developed in Java (Backend) and JavaScript (Frontend).

Adding to the platform there are plugins available which I either started to develop by myself or contributed to. Namely, [CSV](/mukil/dmx-csv), [Stableviews](/mukil/stableviews), [Littlehelpers](/mukil/dmx-littlehelpers), [Import-Export](https://github.com/mukil/dmx-import-export), [Images](https://github.com/mukil/dmx-images) and [Webpages](/mukil/dmx-webpages).

## Supplementary information

### Research Data Management

_"The goal of research data management is to produce self-describing data sets."_ ([Strasser et al, 2010, p.1](https://escholarship.org/uc/item/7tf5q7n3))

As stated, for example, in the [Data Readiness Roadmap, GeoNODE 2018](https://dataservices.gfz-potsdam.de/portal/drr.html): _"Research data management (RDM) is a process which begins before the data is collected and in most cases should conclude with data being shared publicly. This process is termed the Data Life Cycle. According to each stage of the data life cycle, handling research data may require different RDM practices, although some are common to all."_

### Methodologies and Methods

- Grounded Theory: ...
- Content Analysis: ...
- Comparative Analysis: ...
-
### Activities & Phases in Research Processes

- Reading
- Active Reading
- Searching
- Finding
- Observing
- Listening
- Seeing
- Asking
- Summarizing
- Analysing
- Writing
- Sharing
- Discussing
- Reflecting

## Copyright

Malte Rei??ig, (C) 2021

## Funding

The Junior Research Group ???ProMUT??? (grant number: 01UU1705A) is funded by the German Federal Ministry of Education and Research as part of its funding initiative ???Social-Ecological Research???. 
