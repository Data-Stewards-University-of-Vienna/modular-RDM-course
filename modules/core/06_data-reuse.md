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

(Franzi)
## Why would you want to reuse data?

Data reuse is important because it allows researchers to:

4 categories (NOTE: do not necessarily reuse these categories, but the underlying reasons and ideas)

Benefits for data reusers:
* save time and money
* test new questions and methods on old data
* test for change over time
* find new collaborators

Benefits for producers or publishers:
* receiver more citatiations and become more visible
* my work is more transparent 
* professional reputation increases
* can find new collaborators

Benefits for research community:
* Better understand results/Verify results on more data
* more efficent research 
* access expensive or difficult to generate data
* use data in teaching

Benefits for society:
* transparent research
* confidence in science
* tax dollars deliver great impact
* we benefit from private and public sector use of data 

## How and where to find reusable data?

**How is data published?**
NOTE: add examples
* Article ,appendix or supplement
* Data Journal 
* Data repository

**Where can I find data?**

If the data is published thourgh article (inludes data journal): Open Alex, etc..

Data sets themselves you can find in repositories:
* Repositories (general vs discipline specific, re3data if you don't know where to start)
* Meta search (B2FIND, examples..)
* Google

## Can I use the data? 

Let's talk about licensing.

**What are licenses?**
A license is a clear legal statement that specifies what other people are allowed to do with your work and under what conditions.

**How do you assign a license?**
* Ensure that you are the owner of the output OR that you have been given the right to assign a license for the output. 
* Choose the license that fits how you want others to use your work and clearly attach it to the work, including the full license name and a link to the official license terms.

**Can licenses be switched or changed?**
* Once something is released under a license, you generally cannot revoke those permissions or impose additional restrictions. 
* You can re-license work to remove previous limitations.

**Can licenses be modifiedß**
* You should not modify license terms yourself.
* Licenses are carefully written legal documents and changing them can make them unclear or invalid.

**Frequently used licenses: Data**
Creative Commons (CC Licences):
* CC 0: Public Domain
* CC BY: Attribution
Credit must be given to the author
* CC NC: Non-Commercial
May not be used for commercial purposes
* CC ND: Non-Derivatives
May not be modified
* CC SA: Share Alike
Redistribution under the same licensing terms

Open Data Commons (https://opendatacommons.org)
* Open Data Commons Open Database License
* Open Data Commons Atribution License
* Open Data Commons Public Domain Dedication and License 

NOTE: add overview table of CC licenses

**Frequently used licenses: Code**
* MIT
* GNU General Public Licenses (GPL) and variations
* Apache

At end: what happens if I don't apply a license? 

## Do I even want to reuse the data?

Imagine you’ve now found an interesting dataset you might want to reuse. Before integrating it into your workflow, you must evaluate some aspects, such as its suitability, quality, and legal status.

**How to evaluate reusability?**

When assessing a dataset, ask yourself the following questions:

* **Legal Terms:** Is an appropriate license applied (e.g., Creative Commons) that permits reuse?
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


**Question 2: Data Citation Best Practices**
Which of the following is considered best practice when citing a reused dataset that has a corresponding journal paper?

[( )] Cite only the journal paper, as datasets are not formal publications.
[( )] Cite only the dataset, as the paper is redundant.
[(X)] Cite both the dataset (using its DOI) and the corresponding journal paper.
