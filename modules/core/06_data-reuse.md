<!--
authors: Franziska Bauchinger, Simone Spedicato 

email: franziska.bauchinger@univie.ac.at, simone.spedicato@univie.ac.at    

version:  1.0

language: en

-->

# Data Reuse

## Objectives
Data reuse means using data for other purposes than it was originally collected for. Reuse of data is particularly important in science, as it allows different researchers to analyse and publish findings based on the same data independently of one another. Data that is well-described, curated and shared under clear terms and conditions is more likely to be reused. Integration with other data sources is also important, since that can enable new, yet unanticipated, uses for the data.

By the end of this section you will be able to:

* explain the legal framework surrounding data reuse and evaluate if proper permissions exist to reuse specific resources.
* explain the benefits of data reuse for both data producers and users.
* evaluate the basic quality and reliability of reuseable data and outputs.

## What are the benefits of reusing data (and making data available for reuse)?

But why would a researcher reuse data? Isn't research all about creating new data?
Not really... research is all about creating knowledge and there is a lot of knowledge 
still to be gained from "old" data. Besides, if you reuse data you will almost inevitably create new data too.

![XKCD Data Trap](https://imgs.xkcd.com/comics/data_trap.png " [Data Trap by XKCD](https://xkcd.com/2582), [CC BY-NC 2.5](https://creativecommons.org/licenses/by-nc/2.5/legalcode0)")

There are four primary groups that can benefit from data reuse: 
data reusers themselves, data producers and publishers, 
research disciplines and communities, and society or the public. 
Let's have a closer look at the benefits for each group.

**Data reusers**

If you reuse already existing data 
* you can save time and money, because you don't have to produce the data yourself
* you can test your new questions or methods on additional data
* you can test for change over time by comparing to older data
* you can find new collaborators through the data they published

**Data producers and publishers**

If data you published is reused by others
* you receive more citations and your research becomes more visible
* your work becomes more transparent
* your professional reputation can increase
* you can find new collaborators

**Research disciplines and communities**

If more data from a research discipline or community is available for reuse
* they can gain a better understanding of results
* they can verify results on more data
* everyone gains access to expensive or difficult to generate data
* they have access to varied data for teaching purposes

**Society or the public**

If more research data is available for reuse
* research becomes more transparent which can increase the public confidence in science
* tax dollars spent on research can deliver a greater impact
* private and public sectors can reuse the data and benefit society

---

## How and where to find reusable data?
NOTE: do we want to add a recommendation concerning supplementaries? (aka: try to move away from that)

If you now come to the conclusion that, for your specific research question, reusing data would be beneficial,
what do you do? Where is reusable data stored and how can you find it?

**How is data published?**

Let's first have a look at how research data is published: 
Research data is generally published in an article appendix or supplement, a data journal, or a data respository.

**Article appendix or supplement**

An article appendix or supplement (these terms are used interchangeably) is a separate, optional section of a research article that contains additional information.
Information you frequently find in an appendix are more detailed methods, additional figures or, of course, data.
Publishing the data corresponding to an article in its appendix is very common and you can usually download the supplementary material directly with the article on the publisher's website.
Take a look at this Nature article about the CRISPR-Cas system: https://doi.org/10.1038/s41586-026-10833-9. 
If you scroll all the way to the bottom of the article, you can see that the supplementary information contains additional figures and tables, as well as the exact source data that was used to create all figures.

**Data journals**

A data journal is a peer-reviewed academic publication that focuses on sharing and describing research datasets. 
The articles of such a journal describe how data was collected, processed, formatted, etc. The data itself is not stored with the data journal but in a research data repository and the article simply links to the repository entry. Let's look at this article published in Scientific Data: https://doi.org/10.1038/s41597-025-05635-z. The article includes a detailed description of the methodology and in the references you find the link to the published dataset which is located on an institute repository:

> White, E. C., Seymour, A., Dale, J., Newton, E. & Johnston, D. W. Mapping the Ghost Fleet: Orthomosaics and ship locations from drone-based imagery of Mallows Bay, Maryland. Duke Research Data Repository.  https://doi.org/10.7924/r4v12927x (2024)

Data journals can be broad in scope (e.g. Scientific Data) or discipline-specific (e.g. Viticulture Data Journal). You can find a list of data journals on Zenodo (no guarentee for completeness): https://zenodo.org/records/7082126

**Data repositories**

Data repositories are centralized places to hold, organize and share data. They keep data save and usable over time, allow sharing of data and enable proper tracking and citing of datasets by assigning unique persistent identifiers (usually DOIs - digital object identifiers - or accession numbers).
We distinguish three types of research data repositories:

* Institutional repositories: managed by universities or organizations (e.g. PHAIDRA at the University of Vienna: https://phaidra.univie.ac.at/)

* Discipline-specific repositories: tailored to specific fields and data types (e.g. Oral-History.Digital: https://www.oral-history.digital/)

* Generalist repositories: large platforms that accept a variety of datasets (e.g. Zenodo: https://zenodo.org/)

Usually, discipline-specific repositories require the data to be curated and follow certain formatting and metadata standards. Generalist repositories tend to have no specific requirements due to their broad nature.

**Where can I find data?**

There are a couple of ways to look for published research data:

* In publications: Scopus (https://www.scopus.com/sources), Web of Science (), OpenAlex (https://openalex.org/), PubMed (https://pubmed.ncbi.nlm.nih.gov/)
* With google: Google Dataset Search (https://datasetsearch.research.google.com/)
* Use a meta search engine: B2FIND (https://b2find.eudat.eu/), OpenAIRE Explore (https://explore.openaire.eu/), Mendeley Data (https://data.mendeley.com/)
* Directly in the respositories - you can find repositories themselves on Re3Data (https://www.re3data.org/)

---

## Can I even reuse the data?

Imagine you’ve now found an interesting dataset you might want to reuse. Before integrating it into your workflow, you must evaluate some aspects, such as its suitability, quality, and legal status.

**How to evaluate reusability?**

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

---

## Citing Data you Reuse

Just like traditional literature, research data is a first-class scholarly output and must be cited formally. Proper citation ensures academic integrity, enables reproducibility, and gives credit to the original creators.

**Guidelines for Citing Datasets**

* **Give Credit:** Always include the core citation elements: Author(s), Publication Year, Dataset Title, Publisher/Repository, and Version (if applicable).
* **Indicate the License:** Mention the license of the original dataset to show you have the legal right to use and distribute your findings.
* **Use Persistent Identifiers (PIDs):** Always include a resolving link such as a DOI (Digital Object Identifier), accession number, or handle. Do not rely on temporary URLs.
* **Follow Citation Styles:** Most major citation styles (APA, Chicago, MLA, Harvard) now have official guidelines for datasets.
* **Double Cite:** If a dataset is associated with a peer-reviewed paper, it is best practice to cite **both** the dataset itself and the article describing it.

Example (APA 7th Style):
> Creator, A. A., & Creator, B. B. (Year). *Title of the dataset* (Version V) [Data set]. Repository Name. https://doi.org/10.xxxx/xxxxx

---

## Quiz

Test your understanding of data reuse and citation.

**Question 1: Repository Quality Control**
Does the fact that a dataset is published in a reputable repository guarantee its scientific quality?

[( )] Yes, repositories conduct rigorous scientific peer-reviews of all deposited data.
[(X)] No, repositories mostly perform technical checks; the scientific evaluation is the user's responsibility.
[( )] Yes, but only if the repository is discipline-specific.

**Question 2: Beneficiaries of Data Reuse**
Which of the following correctly matches one of the four primary groups with a benefit of data reuse?

[( )] Data producers benefit because they save time and money by not having to produce the data themselves.
[(X)] Research disciplines benefit because everyone gains access to expensive or difficult-to-generate data.
[( )] Society benefits primarily because individual researchers receive more academic citations.

**Question 3: Data Citation Best Practices**
Which of the following is considered best practice when citing a reused dataset that has a corresponding journal paper?

[( )] Cite only the journal paper, as datasets are not formal publications.
[( )] Cite only the dataset, as the paper is redundant.
[(X)] Cite both the dataset (using its DOI) and the corresponding journal paper.
