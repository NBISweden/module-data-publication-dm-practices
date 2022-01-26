---
title: "Planning for data publication"
teaching: 5
exercises: 30-60
questions:
- "How do I create a data publication plan?"
objectives:
- "After the exercise you will have exerience of how to find a suitable repository, and to find out what is required for a submission."
keypoints:
- "Planning for how, when and where research data will be made accessible is part of a Data Management Plan"
- "Plan ahead - by knowing where the data will be published already during the project, the data and metadata can be formatted according to the repository's requirements, thus reducing the labour when submitting"
---
<!--
Present the exercise, purpose, how
Present expected outcome, how to create the plan
Present the 3 scenarios
Present solutions
-->
## Exercise - make a plan for data publication
One of the questions that needs to be addressed in a Data Management Plan (DMP) is *"How, when and where will research data or information about data (metadata) be made accessible?"*. Since the first version of a DMP is to be written before a project begins, this means that you have to have a plan for data sharing early on. Also, different repositories have different requirements regarding which metadata to provide and which formats to use when submitting. Knowing the requirements early on in a project, allows you to collect and format the appropriate metadata already while working on the project, when it is fresh in yours and your collaborators minds. This will greatly reduce the time spent on submission.

During this exercise you will create a plan for making research data available to the public, by identifying a suitable repository and finding out what the requirements are for submission. Three data output scenarios will be presented.

### Data publication plan
Things to consider when making a data publication plan:

**1. What types of outputs will you be creating or collecting?**

Make a list of the outputs, start with the main, most important, data type(s) for the study, since these will indicate which repository is suitable.

**2. What are suitable repositories for your outputs?**

Depositing your data in a publicly accessible recognised repository which assigns a globally persistent identifier (e.g. a DOI) ensures that your dataset continues to be available to both humans and machines in a usable form in the future.
Try to identify suitable repositories for your main data type(s).

##### Tools
* [ELIXIR Deposition Databases for Biomolecular Data](https://www.elixir-europe.org/platforms/data/elixir-deposition-databases)
* [EBI Repository Wizard](https://www.ebi.ac.uk/submission/)
* [Scientific Data Repository Guidance](https://www.nature.com/sdata/policies/repositories#life)

**3. What are the documentation guidelines for the repositories?**

Repositories often have documentation guidelines that are according to domain-specific standards, which will improve the FAIRness of your data. Organising your output documentation according to these guidelines and standards from the start will make your FAIRification journey much easier.

**4. What preparations are needed to make data and documentation (metadata) ready for submission?**

What is needed in order to be able to do a submission to the chosen repository? Do you e.g. have all metadata at hand, is the (meta) data in an appropriate format?
<!-- not sure what we aim for in this section -->
<!-- Niclas: This is about how to format the metadata, isn't it? -->

**5. Under what licenses will your research outputs be shared?**

Does the repository decide the license, or is this decided by you as a submitter? Identify the terms of the repository. If you decide, which license would you choose and why? The [Creative commons license chooser](https://creativecommons.org/choose/) is a tool to assist you in finding an appropriate license.
<!-- is this accurate? -->

### The scenarios
Select one of the scenarios below and answer the questions.
<!-- for each project, present a brief description of the research question and the main outcomes; data types, excel sheets, analysis scripts? -->

> ## Project A <!-- ArrayExpress -->
> <!-- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7766033/, https://www.ebi.ac.uk/arrayexpress/experiments/E-MTAB-7276/ -->
> Gene expression profiling of Fowlpox knock-out mutant viruses using genome arrays in order to investigate the ability of avian fowlpox virus to modulate host antiviral immune responses.
{: .solution}

> ## Project B <!-- PRIDE -->
> <!-- https://www.ebi.ac.uk/pride/archive/projects/PXD029490 -->
> Proteomics experiment in order to identify novel protein binders of human MIRO2 in prostate cancer using tandem mass spectrometry (MS/MS).
> <!-- keywords needed for the ENA repo wizard: protein data -> mass spectrometry -> proteomics -->
{: .solution}

> ## Project C <!-- SLL Figshare -->
> <!-- https://scilifelab.figshare.com/articles/dataset/Thermal_Proteome_Profiling_dataset_from_Hazara_virus_infected_SW13_cells_treated_with_DMSO_or_antiviral_inhibitor_20_M_TH6744_/13089023 -->
> Thermal proteome profiling dataset of Hazara virus infected cells under different conditions. The dataset consists of a spreadsheet where a list of proteins identified in each replicate and experimental condition is summarized.
> <!-- how describe so that it indicates that a general purpose repo might be a good choice? -->
{: .solution}

### Questions to answer
* What types of outputs will you be creating or collecting?
* What are suitable repositories for your outputs?
* What are the documentation guidelines for the repositories?
* What preparations are needed to make data and documentation (metadata) ready for submission?
* Under what licenses will your research outputs be shared?

### Solutions
  > ## Solution project A <!-- ArrayExpress -->
  > **Data types**
  > * Gene expression
  >
  > **Repository**
  > * [ArrayExpress](https://www.ebi.ac.uk/arrayexpress/)
  >
  > **Documentation guidelines**
  > * [Submission help](https://www.ebi.ac.uk/arrayexpress/help/submissions_overview.html)
  > * [What to prepare](https://www.ebi.ac.uk/fg/annotare/help/what_to_submit.html#what_to_prepare)
  > * [Sequencing library information](https://www.ebi.ac.uk/fg/annotare/help/seq_lib_spec.html)
  >
  > **Needed preparations**
  > * Collect the sample descriptions in txt format according to the metadata standard [Minimum Information About a Sequencing Experiment (MINSEQE)](http://fged.org/projects/minseqe/)
  >
  > **License**
  >
  > Unless stated otherwise, Creative Commons Zero (CC0) is applied to all EBI resources, see further [https://www.ebi.ac.uk/licencing](https://www.ebi.ac.uk/licencing)
  >
  {: .solution}

  > ## Solution project B <!-- PRIDE -->
  > **Data types**
  > * Mass spectra
  >
  > **Repository**
  > * [PRIDE](https://www.ebi.ac.uk/pride/)
  >
  > **Documentation guidelines**
  > [How to submit](https://www.ebi.ac.uk/pride/markdownpage/submitdatapage#prepare_submission)
  >
  > **Needed preparations**
  > * Ensure that we have RAW (raw data files), RESULT (analysis files in mzIdentML format) and PEAK files
  > * Collect project level information
  > <!-- what else? -->
  >
  > **License**
  >
  > Unless stated otherwise, Creative Commons Zero (CC0) is applied to all EBI resources, see further [https://www.ebi.ac.uk/licencing](https://www.ebi.ac.uk/licencing)
  >
  {: .solution}

  > ## Solution project C <!-- SLL Figshare -->
  > **Data types**
  > * Spreadsheet in xlsx format
  >
  > **Repository**
  > * [SciLifeLab Data Repository](https://scilifelab.figshare.com/)
  >
  > **Documentation guidelines**
  > * [Submission guidelines](https://www.scilifelab.se/data/repository/submission/)
  >
  > **Needed preparations**
  > * Collect necessary project level metadata such as title, authors, discipline category (ontology controlled), keywords etc.
  > * Write a data dictionary to describe the different metadata attributes
  > * Write a manifest file, [(example)](https://www.scilifelab.se/wp-content/uploads/2021/10/MANIFEST.txt)
  > * Write a README file, [(example)](https://www.scilifelab.se/wp-content/uploads/2021/10/README-1.txt)
  >
  > **License**
  >
  > There are several licenses to choose between, we decided upon Creative Commons Zero (CC0) in order to make the dataset as open and freely available as possible.
  {: .solution}
