
<!--
authors: Simone Spedicato, Michael Feichtinger 

email: simone.spedicato@univie.ac.at, michael.feichtinger@univie.ac.at    

version:  1.0

language: en

-->



<!--
authors: Simone Spedicato, Michael Feichtinger 

email: simone.spedicato@univie.ac.at, michael.feichtinger@univie.ac.at    

version:  1.0

language: en

-->

# Archiving and Publishing

## Learning Objectives

By the end of this section, you will be able to:

* Explain why long-term preservation of research data is an essential part of Research Data Management.
* Decide which research outputs should be preserved.
* Prepare data and documentation for long-term preservation.
* Select an appropriate repository for your research outputs.
* Understand the role of persistent identifiers (PIDs) in making research outputs FAIR and citable.

---

## Why Preserve and Publish Research Data?

Research data are valuable research outputs that often remain useful long after a project has ended. Preserving and publishing data allows other researchers to verify findings, reproduce analyses, and build upon existing work. It also increases the visibility and impact of your research by enabling data citation and reuse.

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

## Deciding What to Preserve

Not every file produced during a research project needs to be preserved. Long-term preservation requires resources, so you should carefully decide which outputs have lasting value.

As a general principle, all data that support published findings should be preserved. Increasingly, journals and funding agencies require researchers to deposit the data underlying publications in trusted repositories. For example, **[Horizon Europe](https://research-and-innovation.ec.europa.eu/funding/funding-opportunities/funding-programmes-and-open-calls/horizon-europe_en)** requires research data to be deposited in trusted repositories and made openly available whenever possible.

When deciding what to preserve, consider some of these aspects.

**Essential research outputs**

Preserve:

* the final or processed datasets supporting publications;
* sufficient raw or primary data to validate published results (subject to ethical and legal constraints);
* analysis workflows and processing pipelines;
* software and code used to generate results;
* metadata describing the data and their provenance;
* documentation such as README files, codebooks, variable dictionaries, laboratory protocols, and workflow descriptions;
* computational environments (for example, requirements files, containers, or workflow specifications) needed to reproduce analyses.

**Selection criteria**

The following questions can help determine whether data should be preserved:

* Are the data required by a funder, publisher, or institutional policy?
* Are there legal or ethical obligations to retain the data?
* Would the data be difficult or impossible to reproduce?
* Are the data likely to be reused in future research or teaching?
* Do the data have long-term scientific, historical, environmental, or societal value?

Typically, research data should be retained for **at least five to ten years** after the end of a project, although specific requirements vary between disciplines and funders.

---

## Preparing Data for Preservation

Preserving data successfully requires more than uploading files to a repository. Future users—including your future self—must be able to understand and reuse the data!

Before archiving your research outputs, ensure that they are complete, well organised, and sufficiently documented.

**Organise the data**

Prepare a well-structured dataset by:

* removing temporary or unnecessary files;
* using consistent folder structures and file naming conventions;
* separating raw data from processed data and analysis outputs;
* including only stable versions intended for preservation.

**Provide documentation**

Every preserved dataset should include enough information to understand how the data were created and processed.

Useful documentation includes:

* a README file;
* metadata describing the dataset;
* codebooks or variable dictionaries;
* laboratory protocols;
* descriptions of data processing workflows;
* provenance information documenting how the data evolved throughout the project.

**Use sustainable file formats**

Whenever possible, preserve data using open, well-documented file formats rather than proprietary formats. Open formats are more likely to remain readable over long periods and across different software platforms.

**Include licensing information**

Clearly specify how others may reuse your data by including appropriate licensing information in both the repository metadata and accompanying documentation.

**Special cases**

Some research outputs require specialised preservation strategies.

* Non-digital materials (such as paper records) may need to be digitised before preservation.
* Biological materials, microorganisms, or biomolecules should generally be deposited in appropriate biobanks or specialised collections rather than conventional data repositories.

---

## Choosing a Repository

Once your data have been prepared, the next step is to deposit them in a **trusted repository**.

Unlike ordinary storage services, repositories are designed for the long-term preservation, discovery, and citation of research outputs. Trusted repositories provide stable access, curated metadata, persistent identifiers, and long-term preservation policies.

**Repositories versus storage**

It is important to distinguish between storage services and repositories.

Storage services (such as institutional network drives or cloud synchronisation platforms) are designed for active work, collaboration, and backup. They generally do **not** provide:

* persistent identifiers;
* rich metadata;
* long-term preservation commitments;
* citation mechanisms;
* indexing by scholarly search engines.

Repositories, by contrast, focus on preserving, disseminating, and making research outputs discoverable.

**What makes a repository trustworthy?**

A trusted repository typically provides:

* persistent identifiers such as DOIs;
* stable landing pages for citation;
* standardised metadata;
* quality control and curation;
* long-term preservation policies;
* versioning and provenance tracking;
* access control and embargo options;

Repositories may also hold recognised certifications such as CoreTrustSeal.

**How to choose a repository**

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

**Repository hierarchy**

When choosing where to deposit your data, the following order is generally recommended.

<u>1. Discipline-specific repositories</u>

Whenever possible, use a repository recognised by your research community. These repositories typically provide discipline-specific metadata standards, established submission workflows, and increased discoverability.

Useful resources for identifying discipline-specific repositories include:

* [re3data.org](https://www.re3data.org/)
* [FAIRsharing](https://fairsharing.org/)
* Discipline-specific examples: EMBL-EBI Data Submission Wizard, ELIXIR Deposition Databases

Checking repositories used in recent publications within your field is also a useful strategy!

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

## Persistent Identifiers (PIDs)

Publishing data in a trusted repository is only part of making them FAIR. Research outputs should also receive **persistent identifiers (PIDs)**.

A PID is a permanent, globally unique identifier that continues to resolve to a digital resource even if its web address changes.

Persistent identifiers improve:

* findability;
* reliable citation;
* interoperability between research systems;
* long-term access to research outputs.

**How to obtain a PID**

The simplest and most common approach is to deposit your research outputs in a repository that automatically assigns persistent identifiers.

Some institutions also maintain local identifier systems, but these require long-term maintenance and governance. For most researchers, depositing data in a trusted public repository is therefore the preferred option.

**ORCID**

Researchers are strongly encouraged to obtain an **[ORCID](https://orcid.org/) iD**. ORCID provides a persistent identifier for researchers, making it easier to connect publications, datasets, software, grants, and other scholarly contributions across different systems.

Including your ORCID when depositing datasets improves attribution, discoverability, and recognition of your research contributions.

## Publishing and Sharing Research Data

Once your data have been prepared and a suitable repository has been selected, the final step is deciding **how** to make the data available. There are several routes for publishing research data, each with different advantages depending on the nature of the dataset and the goals of the project.

**Publishing Routes**

<u>Supplementary Material</u>

Many journals allow authors to upload datasets as supplementary files alongside a research article.

Advantages

- Simple publication process.
- Directly linked to the associated article.
- Often reviewed together with the manuscript.

Limitations

- Metadata are often minimal.
- Long-term preservation is not always guaranteed.
- Discoverability is usually poor.
- File size and format restrictions are common.
- Supplementary files often do not receive their own DOI.

This approach is most appropriate for **small datasets that are closely tied to a single publication**.

<u>Data Repositories</u>

Depositing data in a trusted repository is considered the preferred approach for most research projects.

Repositories typically provide:

- persistent identifiers (e.g. DOI);
- rich metadata;
- long-term preservation;
- version control;
- citation support;
- access management (including embargoes and restricted access).

<u>Data Journals</u>

Some journals publish **data descriptor articles**, which focus on describing datasets rather than reporting scientific findings.

These articles are peer reviewed and are linked to a dataset deposited in a repository.

Data journals are particularly valuable for:

- large or complex datasets;
- community reference datasets;
- datasets that require extensive methodological documentation.

---

## Managing Access to Research Data (maybe this in legal?)

Not all datasets can or should be made openly available. Ethical, legal, contractual, and commercial considerations may require restrictions on access.

Whenever possible, however, metadata describing the dataset should remain publicly available, even when access to the data themselves is restricted.

**Open Access**

Openly accessible datasets can be downloaded immediately under an open licence.

Open access maximises:

- reproducibility;
- transparency;
- reuse;
- scientific impact.

**Restricted Access**

Some datasets cannot be openly released but may be shared after approval.

Examples include:

- datasets requiring a Data Use Agreement (DUA);
- data that require review by a data access committee;
- collaborations involving confidential information.

In these cases, repository metadata remain public while access to the data is managed through an approval process.

**Controlled Access**

Highly sensitive datasets—particularly involving human participants—may require controlled access.

Access may involve:

- ethical approval;
- secure computing environments;
- virtual research environments;
- monitored data access procedures.

**Embargoes**

Researchers may wish to delay public release of a dataset until:

- a related article has been published;
- a patent application has been filed;
- an ongoing project has been completed.

Repositories usually support embargo periods while still allowing the dataset metadata to remain publicly discoverable.

**Sensitive Data**

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

## Archiving Research Software and Code (maybe this in satellite?)

Modern research increasingly depends on software for data processing, analysis, simulation, and visualisation. Reproducible research therefore requires preserving not only datasets but also the code used to generate results.

**Good Practices**

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

**GitHub/GitLab and Zenodo**

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

## Authorship and Licensing

Publishing data also requires decisions about authorship, attribution, and licensing.

These decisions should be agreed upon before publication.

**Dataset Authorship**

Dataset authorship should reflect substantial intellectual contributions to the creation and curation of the dataset.

Contributions can be documented using the **CRediT taxonomy**, which includes roles such as:

- Conceptualization;
- Data Curation;
- Methodology;
- Software;
- Validation;
- Investigation.

Repositories also allow researchers to associate datasets with their **ORCID iDs**, ensuring proper attribution.

In addition to listing authors, consider including:

- an AUTHORS or CONTRIBUTORS file;
- acknowledgements;
- funding information.

If third-party data are included, ensure that all original sources and licences are properly acknowledged.

---

**Choosing a Licence**

A licence specifies how others may use your research outputs.

Whenever possible, researchers should choose the **least restrictive licence** compatible with legal, contractual, and ethical obligations.

<u>Data Licences</u>

For research data, common recommendations include:

- **[CC0](https://creativecommons.org/public-domain/)**, which places data in the public domain;
- **[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.en)**, which requires attribution.

For databases, licences from the **[Open Data Commons](https://opendatacommons.org/)** family (e.g. ODC-By or ODbL) may also be appropriate.

Licences that restrict commercial use (NC) or derivative works (ND) reduce interoperability and are generally discouraged when the goal is Open Science.

If legal or ethical restrictions prevent open sharing, access should instead be managed through appropriate agreements rather than by applying an unsuitable open licence.

<u>Software Licences</u>

Creative Commons licences are not recommended for software.

Instead, use established software licences such as:

- [MIT](https://mit-license.org/);
- [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0.html);
- [GPL 3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).

You should also verify that the licences of software dependencies are compatible with their chosen licence.

**Implementing a Licence**

When publishing research outputs:

- include a LICENSE file in software repositories;
- specify the licence in repository metadata;
- document any third-party material and its licence;
- provide a recommended citation;
- ensure that you have the legal right to license all materials being shared.

---

## Summary

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

**Quiz**

You learned how to preserve and publish your data and all you get is another stupid quiz. Each question has at least one correct answer, but there can also be multiple correct answers.

All your data should be preserved for at least 5 to 10 years. 

    [[ ]] True
    [[X]] False

When choosing a repository:

    [[X]] You try to find a discipline-specific repository.
    [[X]] You check publications in your field to see which repositories are used by the community.
    [[ ]] You avoid repositories that use metadata standards.
    [[X]] You look for a repository that provides PIDs.
    
Which licenses make your data or software openly available and allows others to adapt them for their use? 

    [[X]] CC0
    [[X]] GNU General Public License 
    [[X]] CC BY
    [[ ]] CC BY-NC-ND