---
title: "Introduction to data publication"
teaching: 15
exercises: 0
questions:
- "What are research data repositories?"
- "Why submit my data to a repository?"
- "How do I find a suitable repository?"
objectives:
- "Explain why data should be publicly available."
- "Explain different types of repositories and how to find a suitable one."
keypoints:
- "Benefits of sharing data are several e.g. reproducibility purposes, follow the Open Science directive, meet requirement from publishers."
- "If possible, use a domain-specific repository since it has maximum reach in the research community. This is the best way to ensure that your data becomes FAIR." 
- "[The EBI Repository Wizard](https://www.ebi.ac.uk/submission/) can help you find a suitable repository for your life science data."
- "If you ever are stuck, contact us data stewards at NBIS by sending an email to **[data-management@scilifelab.se](mailto:data-management@scilifelab.se)** or ask for a consultation via **[our homepage](https://nbis.se/support/supportform/index.php?form=consultation)**."
---
## What are research data repositories?
Traditionally 'all' research outputs were put in the published article only, resulting in that the findings often where difficult to reproduce let alone reuse, or put in a local web server with limited longevity. Fortunately times are changing and nowadays there is a pletora of repositories to choose between, in order to make research as easy and widely available as possible.

### What research outputs should be submitted?
Apart from the data itself, everything necessary to understand, reproduce and reuse the data should be submitted to a repository:
* Raw data: this is the data that comes straight from the instrument, e.g. RNA sequences in fastq format
* Processed & analysed data: this is the data where some type of analysis or processing has been done, e.g. normalization, removal of outliers, expression measurements, statistics, annotation
* Metadata: this is the description of the raw and processed data, e.g. in the form of minimum information to reproduce the data, sample information, precise protocols, analysis scripts and code, etc

### Types of repositories
As mentioned, there is now a pletora of repositories, with varying reach (impact) and depth (rich metadata descriptions), that are often divided into three categories:
* Domain-specific: 
    * Best choice if suitable, long-term plan, typically free of charge, maximum reach and possibilites for rich metadata in order to make the data as widely useful as possible
    * E.g. [European Nucleotide Archive](https://www.ebi.ac.uk/ena/browser/home), [ArrayExpress](https://www.ebi.ac.uk/arrayexpress), [PRIDE](http://www.ebi.ac.uk/pride)
* General purpose: 
    * Second best, long-term plan, might cost (now or in future), good reach but less specific regarding metadata → more difficult for future users to judge if a dataset will be useful
    * E.g. [Zenodo](https://zenodo.org/), [(SciLifeLab) Figshare](https://scilifelab.figshare.com/), [Dryad](https://datadryad.org/)
* In-house/institutional
    * For archive/backup purpose mainly, might cost, limited reach unless also published in data catalogue

## Why submit your datasets to a repository?
Why should you care? Submitting your data to a repository likely takes a lot of time, time you could spend on doing research, and employers as well as funders are only interested in how many articles you have published, not how many datasets you have published. Well, times are indeed changing, there are many institutions with data policies on sharing, and funders want maximum value for their invested money. Besides, if *you* do not share your data, you cannot ask of others to share either, it's as simple as that. You could argue that you do share your data if someone asks for it (aka the (in)famous phrase 'available upon request') but repositories provides the technical solution to FAIR data:

* **Findable** by being assigned a persistent identifier, and by being described with rich metadata.
* **Accessible** by being put in a resourse that is searchable, and enables easy access via internet
* **Interoperable** by using standard format and language to represent both the data and its metadata
* **Reusable** by fulfilling the F, A, and I, and by having a clear and accessible data usage license 

Hence, by submitting data to a repository, your data becomes FAIR and you do not have to provide a solution on your own.

Reasons for sharing in a repository:

* Open Science & FAIR - To meet the requirements from funders and society on Open Science & FAIR
* Reproducibility - So that your published research results can be reproduced
* Trail of evidence - To provide a provenance of the data
* Reusability / 3rd party access - To give others easy access to your data
* Archival purposes - Research data should be available for as long as it is useful to someone
* Publication of paper requires it - Nowadays most publishers require you to submit the data to a repository when publishing a paper

## How to find a suitable repository


### How find a domain-specific repository?
* [EBI repository wizard](https://www.ebi.ac.uk/submission/) - guide depending on data type
* [ELIXIR deposition databases](https://elixir-europe.org/platforms/data/elixir-deposition-databases) - core resources with long-term data preservation and accessibility plans
* [FAIRsharing.org/databases](https://fairsharing.org/databases/) - catalogue of many repositories, with possibility to filter on e.g. domain
* [Scientific Data Repository Guidance](https://www.nature.com/sdata/policies/repositories#life) - publisher’s recommendation

<!-- Do we have suggestions for how scientists outside of life science can find repos? -->

> ## Demo EBI Repository Wizard
>
> [EBI](https://www.ebi.ac.uk/) hosts several life science repositories, suitable for different types of life science data. The Repository Wizard helps you to identify which one is suitable for your data.
>
> Go to the Wizard at [https://www.ebi.ac.uk/submission/](https://www.ebi.ac.uk/submission/)
>
> ![wizard-home](../fig/wizard-home.jpg)
> 
> Either explore the wizard with the purpose of finding a suitable repository for one of your projects, or choose among the scenarios provided below. Which repository is recommended?
>  * Genomics project with RNA sequences
>  * X-ray crystollography structure of a protein
>  * Gene expression data
>  * Protein sequencing data
>  * Proteomics project using mass spectrometry
>  * Electron microscopy structure images
> 
  > ## Solution
  > * Genomics project with RNA sequences: [European Nucleotide Archive](https://www.ebi.ac.uk/ena/browser/submit) (DNA/RNA sequence -> no controlled access -> produced experimentally -> Other)
  > * X-ray crystollography structure of a protein: [wwPDB OneDep](https://deposit-pdbe.wwpdb.org/deposition) (Structures -> X-ray crystollography)
  > * Microarray gene expression data: [ArrayExpress](https://www.ebi.ac.uk/arrayexpress/submit/overview.html) (Expression data -> no controlled access -> Microarray gene expression)
  > * Protein sequencing data: [UniProt SPIN](https://www.ebi.ac.uk/swissprot/Submissions/spin/) (Protein data -> no controlled access -> produced experimentally -> Protein sequencing)
  > * Proteomics project using mass spectrometry: [PRIDE](https://www.ebi.ac.uk/pride/markdownpage/submitdatapage) (Protein data -> no controlled access -> produced experimentally -> Mass spectrometry -> Proteomics)
  > * Electron microscopy structure images: [EMPIAR](https://www.ebi.ac.uk/pdbe/emdb/empiar/deposition/) (Structures-> Electron microscopy -> micrographs or particle stacks)
  {: .solution}
{: .solution}

### How find a general purpose repository?

### Evaluation of the suitability of a repository

Apart from accepting your type of data, there are some questions to consider when deciding if a certain repository is suitable or not:

* Are others in the community using it? Explore what datasets are already in it.
* While exploring it, is it easy to navigate / user-friendly?
* Is there support / guidance for submission and reuse?
* Is it sustainable, i.e. will the repository be around for a while? Is there a long-term plan for financing the repository, is it managed by a thrustworthy group?
* Will the datasets obtain persistent identifiers? Is the repository itself FAIR?

{% include links.md %}

