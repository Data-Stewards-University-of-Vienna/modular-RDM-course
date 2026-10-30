
<!---
authors: Simone Spedicato, Franziska Bauchinger

email: simone.spedicato@univie.ac.at, franziska.bauchinger@univie.ac.at

version: 1.0

language: en
--->

# Archiving and Publishing Research Data

Welcome to this module, where we will discuss preserving data, what to preserve, which publication routes are out there, how to find and evaluate data for reuse — and why reusing data is an important aspect for different stakeholders. Enjoy!

Objectives
--------------------

By the end of this section, you will be able to:

* Explain why long-term preservation of research data is an essential part of Research Data Management.
* Decide which research outputs should be preserved.
* Select an appropriate repository for your research outputs.
* Understand the role of persistent identifiers (PIDs) in making research outputs FAIR and citable.
* Explain the legal framework surrounding data reuse and evaluate if proper permissions exist to reuse specific resources.
* Evaluate the basic quality and reliability of reuseable data and outputs.

Introduction
----------
Research data can remain valuable long after a project has ended—provided that they are properly preserved, documented, published, and shared. This module introduces the key steps for preparing research outputs for long-term preservation, selecting repositories, managing access, and making data citable. It also explores how to find, evaluate, legally reuse, and cite data created by others.

---

## Why Preserve and Publish Research Data?

Data preservation is more than simply storing files or creating backups. While storage protects against accidental loss, preservation ensures that data remain **accessible, understandable, and reusable** for many years, even as technologies evolve.

![XKCD Digital Resource Lifespan](https://imgs.xkcd.com/comics/digital_resource_lifespan.png "[Digital Resource Lifespan by XKCD](https://xkcd.com/1909), [CC BY-NC 2.5](https://creativecommons.org/licenses/by-nc/2.5/legalcode0)")

Many funders, journals, and research institutions now require research data to remain available for several years after project completion. Preserving data also supports the principles of **FAIR data** and **Open Science**, helping to make research outputs findable, accessible, interoperable and reusable.

Long-term preservation benefits both individual researchers and the wider scientific community by:

* enabling verification and reproducibility of published results;
* facilitating future reuse, including meta-analyses and teaching;
* increasing research visibility and citation;
* protecting against data loss;
* preserving data of historical, scientific, environmental, or societal value.

The **[University of Vienna Research Data Management Policy](https://rdm.univie.ac.at/rdm-policy-and-faq/)** encourages researchers to preserve research data while complying with funder requirements, journal policies, and applicable legal or ethical obligations.

---

## What are the benefits of reusing data (and making data available for reuse)?

On the other side, reusing existing data that was published has a lot advantages - not only for you, but also for communities and the public around you. 

There are four primary groups that can benefit from data reuse: 
data reusers themselves, data producers and publishers, 
research disciplines and communities, and society or the public. 
Let's have a closer look at the benefits for each group.

Data reusers
---------

If you reuse already existing data 
* you can save time and money, because you don't have to produce the data yourself
* you can test your new questions or methods on additional data
* you can test for change over time by comparing to older data
* you can find new collaborators through the data they published

Data producers and publishers
-----------

If data you published is reused by others
* you receive more citations and your research becomes more visible
* your work becomes more transparent
* your professional reputation can increase
* you can find new collaborators

Research disciplines and communities
----------

If more data from a research discipline or community is available for reuse
* they can gain a better understanding of results
* they can verify results on more data
* everyone gains access to expensive or difficult to generate data
* they have access to varied data for teaching purposes

Society or the public
------------

If more research data is available for reuse
* research becomes more transparent which can increase the public confidence in science
* tax dollars spent on research can deliver a greater impact
* private and public sectors can reuse the data and benefit society

---

## Publishing and Sharing Research Data

Let's first have a look at how research data is published: 
Research data is generally published in an article appendix or supplement, a data journal, or a data repository.

Article appendix or supplement
------------

An article appendix or supplement (these terms are used interchangeably) is a separate, optional section of a research article that contains additional information.
Information you frequently find in an appendix are more detailed methods, additional figures or, of course, data.
Publishing the data corresponding to an article in its appendix is very common and you can usually download the supplementary material directly with the article on the publisher's website.
Take a look at this Nature article about the CRISPR-Cas system: https://doi.org/10.1038/s41586-026-10833-9. 
If you scroll all the way to the bottom of the article, you can see that the supplementary information contains additional figures and tables, as well as the exact source data that was used to create all figures.

> Our advice: avoid publishing datasets solely as supplementary material. Supplementary files often have limited metadata, file-size restrictions, and may be difficult to find, cite, preserve, or reuse in the long term. Instead, deposit your data in a trusted repository and link to it from the publication using the dataset’s DOI.
Data journals
------------

A data journal is a peer-reviewed academic publication that focuses on sharing and describing research datasets. 
The articles of such a journal describe how data was collected, processed, formatted, etc. The data itself is not stored with the data journal but in a research data repository and the article simply links to the repository entry. Let's look at this article published in Scientific Data: https://doi.org/10.1038/s41597-025-05635-z. The article includes a detailed description of the methodology and in the references you find the link to the published dataset which is located on an institute repository:

> White, E. C., Seymour, A., Dale, J., Newton, E. & Johnston, D. W. Mapping the Ghost Fleet: Orthomosaics and ship locations from drone-based imagery of Mallows Bay, Maryland. Duke Research Data Repository.  https://doi.org/10.7924/r4v12927x (2024)

Data journals can be broad in scope (e.g. Scientific Data) or discipline-specific (e.g. Viticulture Data Journal). You can find a list of data journals on Zenodo (no guarentee for completeness): https://zenodo.org/records/7082126

Data repositories
------------

Data repositories are centralized places to hold, organize and share data. They keep data save and usable over time, allow sharing of data and enable proper tracking and citing of datasets by assigning unique persistent identifiers (usually DOIs - digital object identifiers - or accession numbers).
We distinguish three types of research data repositories:

* Institutional repositories: managed by universities or organizations (e.g. PHAIDRA at the University of Vienna: https://phaidra.univie.ac.at/)

* Discipline-specific repositories: tailored to specific fields and data types (e.g. Oral-History.Digital: https://www.oral-history.digital/)

* Generalist repositories: large platforms that accept a variety of datasets (e.g. Zenodo: https://zenodo.org/)

Usually, discipline-specific repositories require the data to be curated and follow certain formatting and metadata standards. Generalist repositories tend to have no specific requirements due to their broad nature.

---
## Deciding What to Preserve

Now that you have an idea of where to put your data, you might be asking yourself: do I really need to put everything up there? Actually: no! Not every file produced during a research project needs to be preserved. Long-term preservation requires resources, so you should carefully decide which outputs have lasting value.

As a general principle, all data that support published findings should be preserved. Increasingly, journals and funding agencies require researchers to deposit the data underlying publications in trusted repositories. For example, **[Horizon Europe](https://research-and-innovation.ec.europa.eu/funding/funding-opportunities/funding-programmes-and-open-calls/horizon-europe_en)** requires research data to be deposited in trusted repositories and made openly available whenever possible.

When deciding what to preserve, consider:

* the final or processed datasets supporting publications;
* sufficient raw or primary data to validate published results (subject to ethical and legal constraints);
* analysis workflows and processing pipelines;
* software and code used to generate results;
* metadata describing the data and their provenance;
* documentation such as README files, codebooks, variable dictionaries, and laboratory protocols;
* computational environments (for example, requirements files, containers, or workflow specifications) needed to reproduce analyses.

Typically, research data should be retained for **at least five to ten years** after the end of a project, although specific requirements vary between disciplines and funders.

---

## Preparing Data for Preservation

Preserving data successfully requires more than uploading files to a repository. Future users—including your future self!—must be able to understand and reuse the data!

Before archiving your research outputs, ensure that they are complete, well organised, and sufficiently documented.

Organise the data
----------------

Prepare a well-structured dataset by:

* removing temporary or unnecessary files;
* using consistent folder structures and file naming conventions (EXAMPLE?);
* separating raw data from processed data and analysis outputs;
* including only stable versions intended for preservation.

Provide documentation
----------------

Every preserved dataset should include enough information to understand how the data were created and processed.

Useful documentation includes:

* a README file;
* metadata describing the dataset;
* codebooks or variable dictionaries;
* laboratory protocols;
* descriptions of data processing workflows;
* provenance information documenting how the data evolved throughout the project.

Use sustainable file formats
----------------

Whenever possible, preserve data using open, well-documented file formats rather than proprietary formats. Open formats are more likely to remain readable over long periods and across different software platforms.

Include licensing information
----------------

Clearly specify how others may reuse your data by including appropriate licensing information in both the repository metadata and accompanying documentation. This will be further discussed in the "Ethics and Legal" section.

Special cases
----------------

Some research outputs require specialised preservation strategies.

* Non-digital materials (such as paper records) may need to be digitised before preservation.
* Biological materials, microorganisms, or biomolecules should generally be deposited in appropriate biobanks or specialised collections rather than conventional data repositories.

---

## Choosing a Repository

Once your data have been prepared, the next step might be to deposit them in a **trusted repository** (if you chose this publication route!).

Unlike ordinary storage services, repositories are designed for the long-term preservation, discovery, and citation of research outputs. Trusted repositories provide stable access, curated metadata, persistent identifiers, and long-term preservation policies.

Repositories versus storage
----------------

It is important to distinguish between storage services and repositories.

Storage services (such as institutional network drives or cloud synchronisation platforms) are designed for active work, collaboration, and backup. They generally do **not** provide:

* persistent identifiers;
* rich metadata;
* long-term preservation commitments;
* citation mechanisms;
* indexing by scholarly search engines.

Repositories, by contrast, focus on preserving, disseminating, and making research outputs discoverable.

What makes a repository trustworthy?
----------------

A trusted repository typically provides:

* persistent identifiers such as DOIs;
* stable landing pages for citation;
* standardised metadata;
* quality control and curation;
* long-term preservation policies;
* versioning and provenance tracking;
* access control and embargo options;

Repositories may also hold recognised certifications such as CoreTrustSeal.

How to choose a repository
----------------

When selecting a repository, consider:

* disciplinary relevance;
* accepted data types and file sizes;
* compliance with funder and publisher requirements;
* metadata standards;
* long-term sustainability;
* licensing options;
* access restrictions or embargo support;
* versioning capabilities;
* integration with ORCID and other research infrastructures;
* deposit costs, storage limits, and curation fees;
* discoverability through services such as DataCite, OpenAIRE, or Google Scholar.

Repository hierarchy
----------------

When choosing where to deposit your data, the following order is generally recommended.

<u>1. Discipline-specific repositories</u>

Whenever possible, use a repository recognised by your research community. These repositories typically provide discipline-specific metadata standards, established submission workflows, and increased discoverability.

Useful resources for identifying discipline-specific repositories include:

* [re3data.org](https://www.re3data.org/)
* [FAIRsharing](https://fairsharing.org/)
* Discipline-specific examples: EMBL-EBI Data Submission Wizard, ELIXIR Deposition Databases

Keep in mind that some specialist repositories may have longer processing times before datasets are published, so it is worth planning for this in advance. If you have any questions or run into issues, you can always contact the repository team for support.
> **Tip:** Checking repositories used in recent publications within your field is also a useful strategy!

<u>2. Institutional repositories</u>

If no suitable disciplinary repository exists, an institutional repository is usually the next best option.

The University of Vienna operates **[PHAIDRA](https://phaidra.univie.ac.at/)**, which supports the preservation of a wide range of research outputs and provides professional long-term management.

<u>3. General-purpose repositories</u>

When neither a disciplinary nor institutional repository is appropriate, general-purpose repositories provide an excellent alternative.

Popular examples include:

* [Zenodo](https://zenodo.org/)
* [Figshare](https://figshare.com/)
* [Dryad](https://figshare.com/)
* [Mendeley Data](https://data.mendeley.com/)

---

Publishing data in a trusted repository is only part of making it FAIR. To make research outputs easier to find, cite, connect, and reuse, they should also receive appropriate **persistent identifiers (PIDs)**.

A PID is a permanent, globally unique identifier that points to a digital resource or entity. Unlike a normal web address, a PID is designed to keep resolving even if the location of the resource changes.

Persistent identifiers improve:

* findability;
* reliable citation and attribution;
* interoperability between research systems;
* linking between people, organisations, outputs, funders, and instruments;
* long-term access to research outputs.

## Persistent identifiers (PIDs)

The most common PID for datasets is a **Digital Object Identifier (DOI)**. DOIs can be assigned to datasets, software, publications, preprints, protocols, reports, and other research outputs. A DOI allows others to cite a specific output reliably and helps link it to related publications, authors, and funders.

Repositories may also use other PID systems, such as:

* **Handles** — a persistent identifier system often used by institutional repositories;
* **ARKs (Archival Resource Keys)** — identifiers commonly used by archives, libraries, and cultural-heritage institutions;
* **accession numbers** — identifiers assigned by specialist repositories, for example for sequencing data, protein structures, or other domain-specific datasets. These may be linked to a DOI, but can also function as the primary identifier in a particular research community.

When choosing a repository, check whether it assigns a DOI or another widely recognised, persistent identifier. Specialist repositories are often preferable where they exist, as they use domain-specific metadata standards and identifiers that are familiar to researchers in the field.

Persistent identifiers for people: ORCID
--------

Researchers are strongly encouraged to obtain an **[ORCID](https://orcid.org/) iD**. ORCID provides a persistent identifier for individual researchers, making it easier to distinguish you from others with a similar name and to connect your publications, datasets, software, grants, peer-review activities, and other scholarly contributions across different systems.

Include your ORCID iD when depositing datasets, submitting manuscripts, applying for funding, or registering software. This improves attribution, discoverability, and recognition of your contributions.

Persistent identifiers for organisations: ROR
--------

A **[Research Organization Registry (ROR)](https://ror.org/) ID** is a persistent identifier for research organisations, such as universities, research institutes, hospitals, funders, and government organisations.

Including a ROR ID where possible helps make institutional affiliations more consistent and machine-readable. For example, it can help distinguish between organisations with similar names, identify the correct institutional affiliation of dataset creators, and support reporting on an institution’s research outputs.

Many repositories and publishing systems allow you to select an organisation from a standardised list; these entries may be connected to ROR IDs in the background.

Other useful PIDs
---------

Other PID types may be relevant depending on your discipline and the type of research:

* **RAiD (Research Activity Identifier):** identifies a research project or activity and can link the people, organisations, outputs, and funding associated with it.
* **Grant identifiers:** identify a specific funding award or project. These should be included in dataset metadata where available.
* **RRIDs (Research Resource Identifiers):** identify research resources such as antibodies, model organisms, cell lines, software tools, and databases.
* **IGSNs (International Generic Sample Numbers):** identify physical samples, such as geological, environmental, or archaeological samples.
* **PIDs for instruments and facilities:** in some fields, identifiers can be assigned to instruments, laboratory equipment, or research infrastructures to support provenance and reproducibility.

How to obtain a PID
--------

For most researchers, the simplest approach is to deposit research outputs in a trusted repository that automatically assigns a DOI or another suitable PID. When depositing your data, provide as much metadata as possible, including author ORCID iDs, institutional affiliations, funder information, grant numbers, and links to related publications or software.

Some institutions maintain local identifier systems, but these require long-term maintenance and governance. For most researchers, depositing data in a trusted public or disciplinary repository is therefore the preferred option.

## Managing Access to Research Data

Not all datasets can or should be made openly available. Ethical, legal, contractual, and commercial considerations may require restrictions on access.

Whenever possible, however, metadata describing the dataset should remain publicly available, even when access to the data themselves is restricted.

Open Access
----------------

Openly accessible datasets can be downloaded immediately under an open licence.

Open access maximises:

- reproducibility;
- transparency;
- reuse;
- scientific impact.

Restricted Access
----------------

Some datasets cannot be openly released but may be shared after approval.

Examples include:

- datasets requiring a Data Use Agreement (DUA);
- data that require review by a data access committee;
- collaborations involving confidential information.

In these cases, repository metadata remain public while access to the data is managed through an approval process.

Controlled Access
----------------

Highly sensitive datasets—particularly involving human participants—may require controlled access.

Access may involve:

- ethical approval;
- secure computing environments;
- virtual research environments;
- monitored data access procedures.

Embargoes
----------------

Researchers may wish to delay public release of a dataset until:

- a related article has been published;
- a patent application has been filed;
- an ongoing project has been completed.

Repositories usually support embargo periods while still allowing the dataset metadata to remain publicly discoverable.

Sensitive Data
----------------
Sensitive research data require particular care.

Before sharing such data, researchers should consider:

- anonymisation or de-identification;
- participant consent;
- legal requirements (e.g. GDPR);
- institutional policies.

Where data cannot be shared openly, researchers should still aim to publish:

- metadata;
- documentation;
- analysis code;
- synthetic or aggregated datasets where appropriate.

Any access restrictions should be clearly documented in the repository metadata and accompanying README files.

---
## Can I even reuse that data?
Imagine you’ve now found an interesting dataset you might want to reuse. Before integrating it into your workflow, you must evaluate some aspects, such as its suitability, quality, and legal status.

How to evaluate reusability?
------------

When assessing a dataset, ask yourself the following questions:

* **Legal Terms:** Is an appropriate license applied (e.g., Creative Commons) that permits reuse? (more details on proper licensing in the next section)
* **Scientific Relevance:** Does the data match your research question?
* **Methodology:** Are the collection methods well-documented? Do they match current quality standards in your field?
* **Metadata & Context:** 
  * Does the dataset include important information about instruments and parameters?
  * Is the data described in a way that allows you to understand its context?
* **Provenance:** Has the data been processed since collection? Are those processing steps clear?
* **Clarity:** Are variables, units, or abbreviations clearly defined? Is the documentation internally consistent?
* **Trustworthiness:** Does the data come from a reputable source or a trusted repository?

> Data documentation does not always equal data quality

It is important to distinguish between how well a dataset is *documented* and the actual *quality* of the data itself:
* **High documentation, low quality:** A dataset can have perfect metadata, clear variables, and a complete readme file, yet the actual measurements may be imprecise, biased, or scientifically flawed.
* **Low documentation, high quality:** Conversely, highly precise and valuable data may be practically useless if it lacks the documentation needed to understand and interpret it.

*Always evaluate both the completeness of the documentation and the scientific validity of the methodology.*

> Repositories don't check if data is correct/high quality

A common misconception is that hosting platform approval equals scientific validation. 
* **The Role of Repositories:** Most data repositories (such as Zenodo, Figshare, or Dryad) perform basic technical checks (e.g., checking if files open or if metadata fields are filled). They generally do **not** peer-review the scientific accuracy, integrity, or quality of the dataset. 
* **Your Responsibility:** As the reusing researcher, the responsibility of quality assurance lies entirely with you.


## Archiving Research Software and Code

Modern research increasingly depends on software for data processing, analysis, simulation, and visualisation. Reproducible research therefore requires preserving not only datasets but also the code used to generate results.

Good Practices
----------------

Research software should be managed using version control systems such as **Git**.

Recommended practices include:

- keeping code separate from data;
- documenting the project with a README;
- providing dependency information (e.g. `requirements.txt` or `environment.yml`);
- including workflow descriptions or containers where appropriate;
- adding tests where possible;
- providing a software licence;
- including a `CITATION.cff` file to facilitate software citation.

Large binary datasets should generally not be stored directly in Git repositories. If necessary, technologies such as **[Git LFS](https://git-lfs.com/)** can be used.

GitHub/GitLab and Zenodo
----------------

A widely adopted workflow combines GitHub or GitLab with Zenodo.

The typical workflow is:

1. Develop software using Git.
2. Create a tagged software release.
3. Connect the repository to Zenodo.
4. Zenodo archives the release and assigns a DOI.

Zenodo creates:

- one **Concept DOI**, representing the software project as a whole;
- one DOI for each released version.

The version-specific DOI should be cited in publications to ensure reproducibility.


---

## Citing Data you Reuse

Just like traditional literature, research data is a first-class scholarly output and must be cited formally. Proper citation ensures academic integrity, enables reproducibility, and gives credit to the original creators.

Guidelines for Citing Datasets
-----------

* **Give Credit:** Always include the core citation elements: Author(s), Publication Year, Dataset Title, Publisher/Repository, and Version (if applicable).
* **Indicate the License:** Mention the license of the original dataset to show you have the legal right to use and distribute your findings.
* **Use Persistent Identifiers (PIDs):** Always include a resolving link such as a DOI (Digital Object Identifier), accession number, or handle. Do not rely on temporary URLs.
* **Follow Citation Styles:** Most major citation styles (APA, Chicago, MLA, Harvard) now have official guidelines for datasets.
* **Double Cite:** If a dataset is associated with a peer-reviewed paper, it is best practice to cite **both** the dataset itself and the article describing it.

Example (APA 7th Style):
> Creator, A. A., & Creator, B. B. (Year). *Title of the dataset* (Version V) [Data set]. Repository Name. https://doi.org/10.xxxx/xxxxx

---


## Conclusions

Long-term preservation and publication are essential components of responsible Research Data Management. Preserving research outputs ensures that they remain understandable, accessible, and reusable long after a project has ended.

A successful preservation strategy involves:

- selecting the research outputs that have long-term value;
- preparing data with appropriate documentation and metadata;
- depositing them in trusted repositories;
- assigning persistent identifiers;
- choosing suitable licences;
- documenting software, workflows, and computational environments;
- making data as open as possible while respecting ethical and legal constraints.

Publishing research data not only satisfies the requirements of many funders and journals but also improves the visibility, reproducibility, and long-term impact of research.

---

## Knowledge Check
You learned how to preserve and publish your data and all you get is another stupid quiz. Each question has at least one correct answer, but there can also be multiple correct answers.

All your data should be preserved for at least 5 to 10 years. 

    [[ ]] True
    [[X]] False

When choosing a repository:

    [[X]] You try to find a discipline-specific repository.
    [[X]] You check publications in your field to see which repositories are used by the community.
    [[ ]] You avoid repositories that use metadata standards.
    [[X]] You look for a repository that provides PIDs.
    
Which of the following steps help prepare a dataset for long-term preservation and reuse?

    [[X]] Include a README file explaining the dataset, its contents, and how it was created.
    [[X]] Provide metadata and, where relevant, codebooks or variable dictionaries.
    [[X]] Use open, well-documented file formats where possible.
    [[ ]] Upload temporary files, duplicate files, and every working draft created during the project.

Does the fact that a dataset is published in a reputable repository guarantee its scientific quality?

[( )] Yes, repositories conduct rigorous scientific peer-reviews of all deposited data.
[(X)] No, repositories mostly perform technical checks; the scientific evaluation is the user's responsibility.
[( )] Yes, but only if the repository is discipline-specific.

Which of the following correctly matches one of the four primary groups with a benefit of data reuse?

[( )] Data producers benefit because they save time and money by not having to produce the data themselves.
[(X)] Research disciplines benefit because everyone gains access to expensive or difficult-to-generate data.
[( )] Society benefits primarily because individual researchers receive more academic citations.

Which of the following is considered best practice when citing a reused dataset that has a corresponding journal paper?

[( )] Cite only the journal paper, as datasets are not formal publications.
[( )] Cite only the dataset, as the paper is redundant.
[(X)] Cite both the dataset (using its DOI) and the corresponding journal paper.

## Sources
