---
title: Manuscript Title
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2022-06-20'
author-meta:
- John Doe
- Jane Roe
header-includes: |-
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta name="dc.title" content="Manuscript Title" />
  <meta name="citation_title" content="Manuscript Title" />
  <meta property="og:title" content="Manuscript Title" />
  <meta property="twitter:title" content="Manuscript Title" />
  <meta name="dc.date" content="2022-06-20" />
  <meta name="citation_publication_date" content="2022-06-20" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="John Doe" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="twitter:creator" content="@johndoe" />
  <meta name="citation_author" content="Jane Roe" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <link rel="canonical" href="https://lubianat.github.io/fapesp_report_2/" />
  <meta property="og:url" content="https://lubianat.github.io/fapesp_report_2/" />
  <meta property="twitter:url" content="https://lubianat.github.io/fapesp_report_2/" />
  <meta name="citation_fulltext_html_url" content="https://lubianat.github.io/fapesp_report_2/" />
  <meta name="citation_pdf_url" content="https://lubianat.github.io/fapesp_report_2/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://lubianat.github.io/fapesp_report_2/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://lubianat.github.io/fapesp_report_2/v/702304ef9b3847e59e6e50313265c1a8f56af618/" />
  <meta name="manubot_html_url_versioned" content="https://lubianat.github.io/fapesp_report_2/v/702304ef9b3847e59e6e50313265c1a8f56af618/" />
  <meta name="manubot_pdf_url_versioned" content="https://lubianat.github.io/fapesp_report_2/v/702304ef9b3847e59e6e50313265c1a8f56af618/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://lubianat.github.io/fapesp_report_2/v/702304ef9b3847e59e6e50313265c1a8f56af618/))
was automatically generated
from [lubianat/fapesp_report_2@702304e](https://github.com/lubianat/fapesp_report_2/tree/702304ef9b3847e59e6e50313265c1a8f56af618)
on June 20, 2022.
</em></small>

## Authors



+ **John Doe**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [johndoe](https://github.com/johndoe)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [johndoe](https://twitter.com/johndoe)<br>
  <small>
     Department of Something, University of Whatever
     · Funded by Grant XXXXXXXX
  </small>

+ **Jane Roe**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [janeroe](https://github.com/janeroe)<br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>



UNIVERSIDADE DE SÃO PAULO
FACULDADE DE CIÊNCIAS FARMACÊUTICAS
Departamento de Análises Clínicas e Toxicológicas








Doctorate Project - Report 2
FAPESP process number: #2019/26284-1
Project term: 01/08/2020 to 31/07/2024
Period of Scientific report: 10/07/2021 to 10/07/2022


Scholarship Holder: Tiago Lubiana

Responsible Researcher: Prof. Dr. Helder Takashi Imoto Nakaya

São Paulo - SP
July 2022


# Project summary  {.page_break_before}

The advent of single-cell technologies has deepened the interest of the scientific community in the building blocks of life, the cells [@wikidata:Q99418649]. 
The Human Cell Atlas (HCA) project, has been a major player in the cell knowledge ecosystem, running since 2017 towards the task to characterize every cell type in the human body [@wikidata:Q46368626]. The HCA consortium recruited people from all over the world to tackle different parts of the project. In Brazil, Prof. Helder Nakaya (supervisor of this PhD project) is leading the national effort to contribute to HCA, with a focus on the roles of different cell types in the pathological processes of infectious and inflammatory diseases.

HCA is set to revolutionize the biomedical sciences, by creating tools and standards for basic research, as well as allowing better characterization of disease, and thus, ultimately, improving diagnostics and therapy. 
Its products (data, information, knowledge and wisdom) need to be FAIR: findable, accessible, interoperable and reusable.
Data stewardship and data management are growing as core demands of the scientific community, ranging from data management plans [@wikidata:Q56524391] to specialized personnel [@wikidata:Q56524391].

The Human Cell Atlas has a dedicated team for organizing data: the Data Coordination Platform (DCP) [@url:https://data.humancellatlas.org/about] [@wikidata:Q104450645].
The DCP is responsible for tracing the plan for computational interoperability, from the data generators to the consumers.[@wikidata:Q104450645].
The Human Cell Atlas  has its portal for data (<https://data.humancellatlas.org/>) which composes the data repository landscape with other resources, like the Broad Institute Single Cell Portal (<https://singlecell.broadinstitute.org/single_cell>) and the Chan-Zuckerberg Biohub Tabula Sapiens (<https://tabula-sapiens-portal.ds.czbiohub.org/>). 
In addition to its core team, the HCA is poised to grow by community interaction, and states in its opening paper that "As with the Human Genome Project, a robust plan will best emerge from wide-ranging scientific discussions and careful planning".[@wikidata:Q46368626]  
Thus, this project inserts itself among the wide-ranging scientific discussions to improve data - and knowledge - interoperability. 

The large amount of information generated by HCA creates the need for innovative knowledge management approaches.
For the Human Cell Atlas Project to maximize its benefit for society,  its knowledge products will need to be inserted into the main route of automated knowledge discovery .  
The field of Literature Based Discovery dedicates itself to this challenge: making actual discoveries (or at least very strong hypothesis) using as material plainly the existing literature. [@wikidata:Q38371706]
The textbook example of Literature Based Discovery is described by Don Swanson's so-called ABC model: If A is related do B, and B is related to C, then A and C are indirectly related [@wikidata:Q36280460]
In a seminal paper, Swanson showed an hypothesis about using fish oil (A) to treat Raynauld's disease (C), demonstrating that even though the specialized fish-oil (A) literature had shown its association (AB) with a set of blood parameters (B), and the specialized Raynauld's disease literature had show its association (BC) with the same set of parameters (B), the AC link was never made in the literature, despite its seeming obviousness [@wikidata:Q36280460].

Modern advancements of literature-based discovery rely on Natural Language Processing, Machine Learning and Knowledge graphs to make inferences on literature knowledge.
Word embeddings, for example, are leading inference of properties of compounds based on their shared neighbourhood of words (the words before and after their mentiongs) with known compounds, thus making use of latent knowledge in the body of knowledge. [@wikidata:Q91595456]
Other, more explicit approaches, rely on extracted relations embedded in knowledge graphs,fo example, the discovery of new RNA-binding proteins related to Amyotrophic Lateral Sclerosis by analysis of the Watson Drug Discovery gene-disease network. [@wikidata:Q47406275]
Knowledge graphs have a set of characteristics that make then useful for Literature Based Discovery: the power of representing multiple relations, the power of making inferences on top of those relations, and provide human understandability at every step, allowing for a dialog between expert humans and computing systems.
The field of biomedical ontologies explores that direction in depth, and the community is building many solutions, widely applicable for the biomedical sciences.

An ontology, as used here, is a formal computational representation of reality, which tries to represent each concept (and their relations) as precisely as possible.  [@wikidata:Q105870680]  
Constructing an ontology is a process of selecting and defining terms and relationships of interest and making statements about reality using terms and relationships. 
The Gene Ontology is probably the most well known biomedical ontology; it describes (among other things) different classes of biological process, related to each_other by "is_a" and "part_of relations. [@wikidata:Q104130127] [@wikidata:Q23781406].

The Gene Ontology is part of a much larger effort to formalize concepts across biology: the Open Biomedical and Biological Ontologies (OBO) Foundry. [@wikidata:Q19671692]
Created in 2007, the OBO Foundry is a hub of biomedical ontologies that sets guidelines for the design and construction of high-quality ontologies. 
The initial OBO Foundry united several independent ontologies, like the Cell Ontology (CL), the Disease Ontology (DO) and the Protein Ontology (PRO) under a common framework, a great progress towards interoperability. 
At the same time, the creation of the Relation Ontology (RO) provided a go-to point for relations in biology that could them be reused by different ontologies.


Ontologies are powerful, but require a high degree of tecnichal expertise to get started. 
Recently, a new approach for formal knowledge representation arose with the dawn of collaborative knowledge graphs.
Wikidata, the collaborative knowledge graph of the Wikimedia foundation, allows users to contribute with classes and statements, in the same spirit of Wikipedia and share its "epistemic virtues, like power, speed and availability. [@wikidata:Q101955295]
It is powerful because of its large community of contributors. With a community of more than 25,000 active editors (https://www.wikidata.org/wiki/Wikidata:Statistics) and growing, it is able to cover a much wider number of concepts than any user individually. 
It is fast, because one does not need to install any software or ask for permissions to update it: any user can simply do it via a web interface. 
That speed makes it easier for newcomers to join and contribute, in contrast to OBO Foundry ontologies, which require extensive training on semantics and knowledge of Git/GitHub for contributions. 
Finally, the information on Wikidata is available via an user interface, via a SPARQL query service and as large, full-size database dumps, providing full extent reusability. 
The Wikidata model has been so sucessfull that Google decided to migrate its own knowledge base, Freebase, fully into Wikidata.[@wikidata:Q24074986]

Several advances towards biological data integration and biological data analysis in Wikidata have been made before, yielding positive results [@doi:10.1101/031971] [@wikidata:Q87830400] and showcasing its potential for bioinformatics-related analyses, such as drug repurposing and ID conversion [@doi:10.7554/eLife.52614]. 
Wikidata has been proposed as a unified base to gather and distribute biomedical knowledge, with more than 50 000 human gene items indexed and hundreds of biomedical-related properties [@doi:10.1016/j.jbi.2019.103292].


The aim of this project is to to study current understanding of cell types for development a comprehensive ontological model in Wikidata for cell types. 
We are reviewing the single-cell literature, refining and formalizing concepts for cell type delimitation and exploring their application in the Wikidata database.
At the same time, we are exploring the use of Natural Language Processing tools, in combination with expert annotations 
tools to automate knowledge extraction from scientific articles in the scope of the Human Cell Atlas. 
The specific goals outlined in the approved project were:

- Build a data model to capture the main properties to describe a human cell. Provide working definitions of cell types and states and their characteristics.
- Extract and add to Wikidata pieces of information regarding Human Cell Atlas publications to build gold standards. Use this information to develop machine learning tools to extract knowledge from publications.
- Create tools to make data from the underlying knowledge graph accessible employing tools from network theory.


# Achievements {.page_break_before}

In the second year of the project, we addressed 2 different facets of the project. 

The first facet was the development of guidelines for describing new cell types in published research in partnership with the Cell Ontology. 

The second facet was the formalization of a biocuration routine to curate new cell types on Wikidata, an effort with 2 main products: the consolidation of Wikidata as a database for cell types and Wikidata Bib, a software and workflow for reading large amounts of scientific literature.

Additionally, we collaborated in several different projects related to organizing biomedical knowledge on Wikidata, which are also detailed in this session. 
## Biocuration of cell classes with Wikidata Bib  {.page_break_before}
### Introduction 

Reading scientific articles is an integral part of the routine of modern scientists.
Although several literature-management software are available [@url:https://en.wikipedia.org/wiki/Comparison_of_reference_management_software], the process of reading is mainly artisanal. 
There are no standard guidelines on how to probe the literature organize notes for biomedical researchers. 
Thus, while reading and studying is a core activity, there are few (if any) protocols for the efficient screening of scientific articles. 

Other professional traditions have dealt with similar issues in the past. 
Notetaking is vital to keep track of financial balances and avoid costly problems in accounting.
Double-entry bookkeeping was developed in the 13th century as a professional solution for notetaking in accounting where "every entry to an account requires a corresponding and opposite entry to a different account." [@url:https://en.wikipedia.org/w/index.php?title=Double-entry_bookkeeping&oldid=1055066428]
In software development, Test-Driven Development (TDD) is a popular methodology where tests for code snippets are written before the code itself, therefore ensuring that written software passes minimum quality standards.
The similarities of Double-entry bookkeeping and TDD are diverse [@url:https://blog.cleancoder.com/uncle-bob/2017/12/18/Excuses.html], but for our purpose, here suffices to see both as professionalized systems that promote better quality and accountability of works. 


In the humanities, there is a well-established practice of annotations of readings. 
The annotation skills are part of standard academic training in the humanities [@url:https://bibliotecadaeca.wordpress.com/2019/09/30/como-fazer-um-fichamento][@url:"https://www.youtube.com/playlist?list=PLAudUnJeNg4vWJhEJ_da26C-QW5qiS7uZ"]. 
An influential work in presenting methods for academic reading in the humanities is Umberto Eco's book "How to Write a Thesis" [@wikidata:Q3684178], which outlines not only _how_ to annotate the literature that basis an academic thesis, but also _why_ to do so. 
The book, written originally in 1977, is still influential today. 
Still, its theoretical scope (roughly the humanities) and its date preceding the digital era limits the extent to which it applies to the biomedical sciences. 


Notably, the need for an organized reading system for biocuration studies stems from a difference in methodology. 
In humanities, the main (if not sole) research material is the written text, the books and articles from which research stems—[@url:"https://www.youtube.com/playlist?list=PLAudUnJeNg4vWJhEJ_da26C-QW5qiS7uZ"].
In the biomedical sciences, including a large part of bioinformatics, the object of study is the natural world, observed via experimentation. 
Thus, naturally, scientific training focuses on experimentation and data analysis's theoretical and practical basis. 
With the boom of scientific articles, however, the scientific literature (and accompanying public datasets) already provide a strong material for sculpting scientific projects.
Thus, developing a methodology for academic reading tailored to the digital environment is a need. 

To address this gap, we are developing Wikidata Bib, a framework for large scale reading of scientific articles. 
It is presented in three parts, each with a technical overview alongside the theoretical foundations. 
First, Wikidata Bib is presented as a reading system for managing references and notes using a GitHub repository and plain text notes.
Then, we present how the system ensures accountability, allowing users to get personalized analytics on their reading patterns.
Finally, we demonstrate how Wikidata Bib fits an active curation environment, connecting the framework with the larger goal of this project of curating information about cell types on Wikidata.  

## Wikidata Bib as a reading system 

The reading framework of Wikidata bib is built upon a git repository integrated with GitHub, Python 3 scripts and SPARQL queries. The code is packaged into a python module to facilitate usage. It also uses the Click library to implement a professional Command Line Interface for end users (https://github.com/pallets/click).
It has a standard file structure, summarized as the following:

* `docs/`
    * `index.html`
* `downloads/`
    * `10.7554_ELIFE.52614.pdf`
* `src/`
    * `data/`
      * `config.yaml`
      * `index.yaml`
      * `read.csv`
      * `read.ttl`
      * `toread.yaml`
    * `notes/`
        * `Q87830400.md`
    * `wikidata_bib/`   
      * `get_pdf.py`
      * `read_paper.py`
      * `update_dashboard.py`
      * ...
* `LICENSE`
* `pyproject.toml`
* `README.md`
* `setup.cfg`

The `docs/` directory contains the live dashboard from the readings, which will be discussed in the following sessions.
The `downloads/` directory hosts the pdfs of the articles read with the system. 
These are not committed to the repository and are only stored locally. 
The `src/` directory contains a `data/` subfolder with the configuration files and the local database of what is read, a `notes` subfolder with the notes on the read articles and a `wikidata_bib` directory containing the actualpython code with the system's mechanics. 

After installing the package using the `pip` utility (<https://pypi.org/>), the user is able to use Wikidata Bib from the terminal as any other command line utility. 
The basic commands available are described below:
    - `bib read`  receives a Wikidata QID for an article and opens the article web page on a browser and opens a personalized notes document. It also updates the static files for the analytics dashboard, stored in the `docs/` directory.
    - `bib pop`, which "pops" an article from the reading stash at `toread.yaml` and runs `bib read` for it
    - `bib log` updates the git repository and adds, commits and pushes notes and the dashboard to  to GitHub

To customize the system, a new user would need to update 3 `yaml` files in the `src/data` folder: 
`toread.yaml`, `index.yaml`and `config.yaml`. 
The `toread.yaml` stores in a plain text format the QIDs to be read. The file can be edited either manually or via automatic queries (not discussed in this report for conciseness).
The `index.yaml` file holds an hierarchy of topics of interest for the researcher, to be used for indexing/tagging the notes in the way required by the topic of research. This file plays the role of  Umberto Eco's "work plan", with the topics of interest for the academic. [@wikidata:Q3684178]
Finally, the `config.yaml` contains options to customize the system for advanced use. For example, the user can configure shortcuts for different reading lists. 
For example, in my `to read.yaml` file there are two reading lists, one entitled `Cell types` header and another entitled `Biocuration`. 
My `config.yaml` contains the following snippet: 
```yaml
lists:
# - shortcut: Title of header in toread.md  
  ct: Cell types
  bioc: Biocuration
```
The `config.yaml` shortcuts are used as arguments by the `bib pop` command, where `$ bib pop ct` retrieves an article from the "Cell types" list, while `$ bib pop bioc` retrieves an article from the "Biocuration" list.  

The Wikidata bib framework is coupled with a discipline of daily reading.
The discipline is inspired by Robert Cecil Martin's description of Test Driven Development in the book "Clean Code", which includes not only a technical description but a _school of thought_ of how software development might be approached.  [@wikidata:Q109996684]
Every day, I read one article of each list, using the notetaking station displayed in Figure @fig: notetaking.
The constancy of reading allows steady coverage of the relevant literature. 
While the discipline has worked for this research project, it is not required to use the Wikidata Bib system.

The notetaking station of Wikidata Bib, opened in Virtual Studio Code, is depicted on Figure @fig: notetaking A.
The title and publication dates are displayed, and the reading process entails copying snippets from the text to the "Highlights" session. 
Copying the highlights into plain text makes the sections of interest searchable via command line using `grep` (https://en.wikipedia.org/w/wiki/Grep).
Comments can be added either in the comment section or inline, alongside the highlights. 
Even though there is no enforcement, our recommendation is to use HTML comment syntax `<!-- Comment goes here -->` to differentiate from highlights.
Visual Studio offers a default shortcut (CTRL + /) for adding comments, making the process seamless.

The Wikidata Bib framework also includes, whenever possible, an improvement of the metadata about the article on Wikidata. 
In @fig: notetaking B are shown the links included in the dashboard. 
A link to a Scholia [@wikidata:Q41799194] profile allows identification of related articles from a series of pre-made SPARQL queries probing bibliography data on Wikidata.
While Scholia provides an overview of a given article, it does not allow direct curation of the metadata.
For that, two links are provided, one to Wikidata and one to Author Disambiguator [@url:https://www.wikidata.org/wiki/Wikidata:Tools/Author_Disambiguator].
By accessing the Wikidata page for the entity, one can add new triples, for example, curating authors and topics of the article, which are then used by Scholia and by Wikidata Bib's dashboard. 
Author Disambiguator is a wrapper of an Wikimedia API that facilitates disambiguating author names to unique identifiers on Wikidata, thus feeding the public knowledge graph of publication and authors.  
Finally, a link to the article's DOI or full-text URL is provided and serves as a fallback when the automatic download fails. 
Of note, while the metadata curation has a technical benefit to Wikidata and the dashboard, it also plays a theoretical role. 
By curating metadata on authors, the user of Wikidata Bib can better understand the people they read, and expand their metascientific perspective on their domain of interest. 
Furthermore, by embedding the metascientific curation in the reading process WikidataBib directs the user to get acquainted with the people producing the science they read, thus contributing to a more complete perspective of the research process.

![Wikidata Bib's platform for note taking](images/note_taking_station_annotated_with_links.png){#fig:notetaking}

The source code for Wikidata Bib is available at <https://github.com/lubianat/wikidata_bib>. 


## Wikidata Bib as a dashboard 

The Wikidata Bib system also enables the reader to get statistics on their readings. 
Two simple databases are stored on the GitHub repository:
 * `read.ttl` - An RDF document recording the dates in which each article was read. 
 * `read.csv` - An simple, human-readable index connecting QIDs with article titles. 
The CSV file is only stored for accountability and as a quick way to glance at the titles read. 
The .ttl file, on the other hand, is processed by the `update_dashboard.py` script to render 4 different HTML files under the `docs/` folder: 
 - `index.html`
 - `last_day.html`
 - `past_week.html`
 - `past_month.html`
All files are displayed in a GitHub pages static website. 
In the case of this work, they are displayed at <https://lubianat.github.io/wikidata_bib/>. 

To organize the code for rendering the dashboard, we created a python package, wbib, and deposited it in PyPi, making it available via `pip`. [@url:https://pypi.org/project/wbib].
The package implements the logic for rendering complex Wikidata-based academic dashboards and is available in GitHub at <https://github.com/lubianat/wbib>. 
It allows the user to build dashboards based on Wikidata records of information such as gender of authors, the region of author's institutions, topics of articles and similar metascientific information. 
The dashboard is composed of SPARQL queries written for the Wikidata Query Service [@url:https://query.wikidata.org] 
It also allows users to feed an arbitrary list of articles and obtain a custom dashboard. 
Wikidata Bib obtains the HTML dashboards after feeding wbib the lists of articles read in total (`index.html`) or in pre-determined time spans (`last_day.html`, `past_week.html` and `past_month.html` )

![Wikidata Bib queries for institutions of authors and most-read venues](images/wikidata_bib_display.png){#fig:dashboard width="85%"}

The dashboard includes not only a basic list of read articles, but also statistics on most read authors and most-read venues. 
It also displays an interactive map of the institutions of articles read, permitting a glance at geographic biases in activities. 
An example of queries is shown in @fig:dashboard.
As the queries are rendered live, they evolve in quality with the growth of Wikidata. 
Finally, the clean 5-star-open data format enables users to adapt the queries to include different aspects of Wikidata. 
For example, table @tbl:articles_read_hca showcases 10 articles that (1) I have read in the past year and (2) were authored by a speaker of the 1st Human Cell Atlas Latin America Single Cell RNA-seqData Analysis Workshop [@url:https://www.humancellatlas.org/hca-latin-america-2021-workshop]. 
One practical application that the dashboard enables, thus, is to identify people in an event, institution or location that the user has read before, therefore catalyzing the possibility of collaborations. 
Anecdotally, this strategy was tested successfully at Biohackathon Europe 2021 [@url:https://biohackathon-europe.org], where we used the system both to identify possible collaborators and as a conversation starter. 

|workLabel                                                                                        |authors                                                                   |
|-------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|
|A promoter-level mammalian expression atlas                                                      |Jay W Shin                                                                |
|Single-cell RNA-seq reveals new types of human blood dendritic cells, monocytes, and progenitors.|Muzlifah Haniffa                                                          |
|The Human Cell Atlas.                                                                            |Musa Mhlanga, Jay W Shin, Muzlifah Haniffa, Menna R Clatworthy, Dana Pe'er|
|The Human Cell Atlas: Technical approaches and challenges.                                       |Jay W Shin                                                                |
|Innate Immune Landscape in Early Lung Adenocarcinoma by Paired Single-Cell Analyses.             |Dana Pe'er |
|Single cell RNA sequencing of human liver reveals distinct intrahepatic macrophage populations   |Sonya A MacParland                                                        |
|Single-cell reconstruction of the early maternal-fetal interface in humans                       |Muzlifah Haniffa                                                          |
|Distinct microbial and immune niches of the human colon                                          |Rasa Elmentaite, Menna R Clatworthy                                       |
|A cell atlas of human thymic development defines T cell repertoire formation                     |Muzlifah Haniffa, Menna R Clatworthy                                      |
|Decoding human fetal liver haematopoiesis                                                        |Muzlifah Haniffa                                                          |

Table: Articles read by Tiago Lubiana before 8 December 2021 in which an author was a speaker at HCA Latin America
{#tbl:articles_read_hca}                                                        |

## Wikidata Bib for curation of cells to Wikidata

The Wikidata Bib system was devised originally to allow an overview of the fields of cell classification and biocuration. 
However, during the process, it was also repurposed for biocuration of new cell classes in Wikidata.
By fast-tracking the reading of new articles, Wikidata Bib enables an efficient parsing of the literature and, thus, the identification of previously uncatalogued cell types. 

Articles read with Wikidata Bib were screened to mention cell types absent from Wikidata. 
As discussed in the chapter about the concept of cell type, we considered a "cell type" as any class of cells described by a domain expert with evidence of the reality of its instances.
When a mention of such a class appears in an article, I first verify Wikidata for the existence of a related class. 
If it is absent from the platform, I enter a class name, alongside a superclass, and a QID in a Google Spreadsheet, as shown in Figure @fig:biocuration_of_cells.

The information from the spreadsheet is pulled by a python script and processed locally with a series of dictionaries that match common terms to Wikidata IDs. 
In the example shown in Figure @fig:biocuration_of_cells, the string "endothelial cell" was matched against a manually curated dictionary to the Wikidata entry [Q11394395](https://www.wikidata.org/wiki/Q11394395), the representation of that concept on Wikidata. 
After reconciling the data, the script uses the Wikidata Integrator python package [@url:https://github.com/SuLab/WikidataIntegrator] to insert the new entries on the Wikidata database. 
The code for integrating a Google Spreadsheet to Wikidata is available at <https://github.com/lubianat/wikidata_cell_curation>. 

![Wikidata Bib was coupled with a biocuration framework for cell types](images/biocuration_of_cells.png){#fig:biocuration_of_cells width="85%"}

<!-- UPDATE THE STATISTICS 
Jupyter Notebook: https://colab.research.google.com/drive/1GvQXOs51_U8icdGMtKXMeLOXKM8pXWet
-->

Wikidata contains 4075 subclasses of "cell ([Q7868](https://www.wikidata.org/wiki/Q7868))" as of 16 of June of 2022. 
From those, 550 cell classes are specific for humans, and 318 are specific for mice.  
Currently Wikidata has more cell classes than the Cell Ontology, which lists 2577 classes. 
It is worth noticing that classes on the Cell Ontology are added after careful consideration by ontologists and domain experts and should be considered of higher quality than the ones on Wikidata. 

From the 4075 cell classes on Wikidata, 3946 (96.8%) have been edited somehow by User:TiagoLubiana, and 2737 (67.2%) have been created by User:TiagoLubiana. 
Edits included adding multilanguage labels, connecting a dangling Wikipedia page to the cell subclass hierarchy, adding identifiers, images, markers, and other pieces of information. 
Approximatedly 430 hundred terms were added via manual curation based on PanglaoDB entries, while the remaining 2307 entries were created either via Wikidata's web interface or via the curation workflow described in this chapter. 
These statistics are demonstration of how the curation system efficiently contributes to the status of cell type information on Wikidata.

<!-- UPDATE THE STATISTICS -->

As mentioned by Aviv Regev in the Human Cell Atlas General Meeting 2021, "it's everyone's collective
responsibility to participate in the annotation efforts, because that relies on domain expertise. To really tease apart things and give
them names. Until we have names, people will have really a hard time working with things in biology. "[@url:"https://youtu.be/orbqAqV9mQM?list=PLkef4SGmngdZanrQtu_g9kiuAcYczzDfn&t=1959"]"
We hope that by developing simplified curation tools we will engage more domain experts into the curation efforts. 

## Guidelines for reporting new cell types  {.page_break_before}

# Additional Work {.page_break_before}

## Collaborations and manuscripts

### fcoex 

During the initial course of this PhD work, we also completed the development and reporting of _fcoex_, an R package for investigating cellular phenotypes using co-expression networks. [@url:https://www.bioconductor.org/packages/release/bioc/html/fcoex.html] The software was maintained to withstand new releases of dependencies and new R version and was published as a preprint on biorxiv. [@doi:10.1101/2021.12.07.471603v1]
 
### Wikidata Bots

Alongside the editing of cell-type information on Wikidata, I have joined different efforts to improve biological information on Wikidata.
I have collaborated with the ComplexPortal curators as part of the Virtual Elixir BioHackathon 2020 (https://github.com/virtual-biohackathons/covid-19-bh20/wiki) and for the following year, to build a Wikidata Bot to integrate information on protein complexes to Wikidata. An overview of the Wikidata integration is in Figure @fig:complexportal, presented in an article published in Nucleic Acid Research (re-use of the image and legend possible under the CC-BY license of the article). [@wikidata:Q109348309]

![Complex Portal and Wikidata. (A) example of an entry assertion in Wikidata with provenance pointing to Complex Portal (Q104836061). (B) The number of protein complexes in Wikidata per taxon (<https://w.wiki/3ggX>). (C) Subset of Wikidata connected to the SARS-CoV-2 polymerase complex (<https://w.wiki/3eta>).](https://oup.silverchair-cdn.com/oup/backfile/Content_public/Journal/nar/PAP/10.1093_nar_gkab991/2/gkab991fig3.jpeg?Expires=1641821957&Signature=RK-es18S~Qh6vGQE~61i6u4prMuij8kVTbrjN6WUJLfYHOAhUhx9qQorBxROohjLLxbHvZ2YK9e7EwlI9HjVeNoGZ2PJs0Pv78Y31MdZLY8FeLYI2E4azwrqRyv9q0AH8QL3RorWZV1AhOb9bl-44Mr97Q~9MWzeTDnQQbxpCnGLG~YoG49kocD5KE~dmTSQdkXBU7kZnuGM1NPqMHo5ZDUoCRFwmTbLvd4kXoH~6CTyqx4ruQRIO-ks4Q0FUjYnxGX18gCFvoO2LMPZUPrQjTgD35RrVAkLs91Ur6BQHUuZ-ZsE3Iag3mBDu27vT9Jr93bOj0i9wz~surTtEGATgw__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA){#fig:complexportal width="85%}

I have also collaborated with the Cellosaurus database [@wikidata:Q54370168] to revive the CellosaurusBot [@url:https://www.wikidata.org/wiki/User:CellosaurusBot], responsible for updating the metadata on more than 100,000 cell lines on Wikidata. The bot code, written in Python, was refactored entirely and runs semi-automatically after the Cellosaurus database was released. A write-up of the integration is in progress and is planned for release/submission in the second semester of 2022. 

### WiseCube - enterprise biomedical question and answering

During a part of this project, I have worked part-time as a consultant for the Wisecube company, based in Seattle, United States. [@url:https://www.wisecube.ai]
The job was approved by FAPESP and consisted mainly in writing SPARQL queries that probe Wikidata for answers to the questions posed by the BioASQ competition. [@wikidata:Q28646342]
It also entailed on-demand curation of biomedical topics on Wikidata based on requests by pharmaceutical companies as well as the development of dashboards targeted at providing insights to customers. 


## Awards and participation in events

* (Nov - 2021) Managed a project during BioHackathon Europe 2021, in Barcelona, Spain, on the representation of ELIXIR information on Wikidata. [@url:https://github.com/elixir-europe/biohackathon-projects-2021/tree/main/projects/32]
* (May - 2022) Presented the WikidataBib in a talk the 1st UK Local Biocuration conference, which got awarded as the Runner-Up Best Talk 



# Next steps  {.page_break_before}

After this second year of work, the next steps of this PhD project will be geared towards robustifying the systems for biocuration and improving the quality of cell type information on Wikidata.
This robustification will pave the way for the final phase of the project, where we plan to incorporate the organized information on Wikidata to standar workflows of single-cell RNA-seq data analysis.

In particular, the next part of the project includes the following steps:

* Develop Wikidata Bib into a mature system and deploy it as Open Source Software for the research community

* Improve the semantic infrastructure on Wikidata for handling knowledge about cell types

    * Establish a comprehensive catalog of cell types on Wikidata
    * Develop a portal for access and re-use of the Wikidata database, e.g. providing datasets for enrichment analysis of differentially expressed genes
    * Complete the mapping between Wikidata and Cell Ontology, as a stepping stone for integrating Wikidata in existing frameworks
  
* Improve the quality of bibliometric data on Wikidata, laying the foundations to ensure complete coverage of the Brazilian contributions to the Human Cell Atlas

# Chronogram



## Awards and participation in events

* (Nov - 2021) Managed a project during BioHackathon Europe 2021, in Barcelona, Spain, on the representation of ELIXIR information on Wikidata. [@url:https://github.com/elixir-europe/biohackathon-projects-2021/tree/main/projects/32]
* (May - 2022) Presented the WikidataBib in a talk the 1st UK Local Biocuration conference, which got awarded as the Runner-Up Best Talk 



# Preprints and articles  {.page_break_before}

## Pre-prints
- Using coexpression to explore cell-type diversity with the fcoex package (https://www.biorxiv.org/content/10.1101/2021.12.07.471603v1)

- Guidelines for reporting cell types: the MIRACL standard
https://arxiv.org/abs/2204.09673
## Peer-reviewed articles
- Complex Portal 2022: new curation frontiers (https://doi.org:: 10.1093/nar/gkab991)
-

## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
