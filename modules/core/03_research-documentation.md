
<!---
authors: Mathias Mayrgündter, Simone Spedicato 

email: mathias.mayrguendter@univie.ac.at, simone.spedicato@univie.ac.at    

version:  1.0

language: en

TODO
- review round

--->

# Research Documentation
Welcome, travelers, to Module 3! Now that we have covered some of the foundations of data organization, we can turn to more concrete aspects of your research—and to how you can document them effectively.

Objectives
-------------------- 
By the end of this module, you should be able to:

1. Summarize general considerations and solutions for your data documentation.
2. Demonstrate when and how to use README files and what they should include.
3. Know how to find appropriate standard metadata for datasets or samples. 
4. Summarize version control and the tools available for managing different versions of outputs. 
5. Explain how to document common scientific workflows and understand why documentation is important. 

Introduction
-------------------- 
Research documentation is the process of recording how research is planned, carried out, analysed, and managed. It can include notes on methods and decisions, laboratory or fieldwork records, protocols, code, data-processing steps, file structures, and changes made throughout a project. Clear documentation helps researchers keep track of their own work, makes collaboration easier, and supports the verification and reuse of research results. It is therefore an essential foundation for transparent, reliable, and reproducible research.

## Data Documentation

Data documentation could be defined as the clear description of everything that a new “data user” or “your future self” would need to know in order to find, understand, reproduce and reuse your data, independently. Data documentation should clearly describe how you generated or used the data, why, and where to find the related files. It could be used also as onboarding documentation for new colleagues, even if the responsible researcher leaves the project.

Due to the large variety of experiments, techniques and collaborative studies that usually occur within the same project, it is challenging to keep good documentation. However, lack of good data documentation often leads to data loss, not reproducible results or workflows and therefore, waste of money and time.

When documenting your data you should keep the following things in mind:
-------------------- 

- Write the documentation in such a way that someone else who is known to the field cannot misinterpret any of the data. 

- Independently of the tools you will use, data documentation is needed at two levels:
  1. **Study-level** 
     * Documentation about the entire study or project

     * Study-level documentation describes the project title and summary, study aims, authors, institutions involved, funds, methods, licence and identifier for each dataset, folders structure, file naming conventions, versioning system, relation between files or tables and other general information.

  2. **Data-level** 
     * Documentation about individual records, observations or data points

     * Data-level documentation provides information about individual records or data points, such as the meaning of each variable name, label, ID or type (numeric, string, regular expression, date, etc.), units (i.e., cm, kg…), experimental factors, categories, controlled vocabulary or ontology terms accepted as values for each variable, missing values code and so on. 

     * An example could be a data file that contains a "sex" field: someone known to the field could try to misinterpret that from "external sex organs present at birth" to "chromosomal XX or XY" or "high or low testosterone level" or "social gender" or other. In order to avoid this, the way the assignment is made must be part of the documentation or of the data itself (controlled vocabulary). 

- Both the study- and data-level documentation must be generated as early as possible in the research process and also continuously updated, in order to be accurate and complete.

- Documentation is also required when publishing your data.

  * General-purpose repositories usually require only study-level documentation.

  * Discipline-specific repositories generally require both study-level and data-level documentation.

  * > [!IMPORTANT] Repositories often only accept data and documentation in a very strict format
     - These can require a predefined set of attributes or fields (metadata checklists) to be filled, ontology terms to be used, specific (meta)data schemas to be adopted
     - We recommend familiarising yourself with  the requirements of the repositories that could be appropriate for publishing your data already at the beginning of the project, so that you can start documenting and formatting your data accordingly as early as possible.

- Make sure the documentation is kept close to the data, so that nobody will be exposed to the data without being able to find the documentation.

Documentation Tools
-------------------- 

- It is best practice to use one appropriate tool or an integration of multiple tools for data documentation during a project. 

- Suitable tools for data documentation are Electronic Lab Notebooks (ELNs) and/or Laboratory Information Management Systems (LIMS). 

- At CeMESS there is currently the implementation of the ELN [RSpace](https://www.researchspace.com/) going on. 

- A university-wide solution does not exist so far, but if you are part of the Faculty of Life Sciences and your research group is interested to use RSpace, reach out to Emily Kate (emily.jean.kate@univie.ac.at).

- Futhermore, you could use online platforms for collaborative research and file sharing services (such as [OSF](https://osf.io/)) as ELN or data management systems. 

- Also standard tools like OneNote from Office 365 or simple spreadsheets like Excel, LibreOffice Calc or Google Sheets can be used in combination with file sharing. The university provides such share options with [ucloud](https://zid.univie.ac.at/ucloud) or the [Share](https://zid.univie.ac.at/share), but also selfhost alternatives are a possibility such as [Nextcloud](https://nextcloud.com) and  [ONLYOFFICE](https://www.onlyoffice.com/).

- More tools:
   * Wikis like the [University of Vienna's Wiki](https://zid.univie.ac.at/en/uwiki/), [Confluence](https://www.atlassian.com/software/confluence) or [Outline](https://www.getoutline.com)
   * Markdown notebooks such as [Notion](https://www.notion.com) or [Obsidian](https://obsidian.md)
   * Project tracking with docs like [Jira](https://www.atlassian.com/software/jira) or [OpenProject](https://www.openproject.org)

- For help making this decision, contact your data steward.

Documentation File Format
-------------------- 

- Data documentation files can be stored in several formats depending on the features available in your data documentation tool (if using one), your needs or skills. 

- Machine-readable or -actionable formats are preferred to non-machine-readable ones. 

- Also non-proprietary formats are preferred over proprietary ones.

> **Need advice?**  
>
> There is no single perfect approach to data documentation—every improvement is a valuable step. For example, you could keep a digital copy of a handwritten lab notebook or refer to it in a README file accompanying your dataset. For questions or guidance, contact the Research Data Management Support team at [RDM Team](mailto:rdm@univie.ac.at).


## Metadata Standards

Highly structured data documentation is called **metadata**. Generating metadata in a machine-readable or -actionable format makes your data more FAIR . Metadata provides structured and searchable information so that a user can find existing data, evaluate its reusability and cite it.

It is good practice to use international standard metadata schemas to organise and store your (meta)data in a structured way. A metadata schema describes the relations, such as hierarchy, of the elements that belong to the structure. Most metadata schema are accompanied by a fixed set of attributes about the data that needs to be provided. Such metadata standards are community efforts and often under a constant development process. 

Metadata standards often depend on the use of **ontologies** and **controlled vocabularies**. An ontology is a formal representation of knowledge that defines concepts, their properties, and the relationships between them and establishes a hierarchical structure that organizes knowledge in a logical and systematic manner. Controlled vocabularies, on the other hand, consist of a predefined set of terms with specific meanings. They establish a controlled and standardized vocabulary for describing data elements, attributes, or concepts within a specific context. Used wisely, they can enable both humans and computers to understand your data. There is no clear-cut division between the terms "vocabulary" and "ontology", but the latter is more commonly used when dealing with complex (and perhaps more formal) collections of terms and relationships. Ontologies typically provide an identifier. 

The real challenge, however, is to decide on what metadata standards, ontologies and controlled vocabuleries you may want to or have to use for your data.

Finding Metadata Standards for your Datasets
--------------------

There are multiple standards for different types of data, ranging from generic dataset descriptions (e.g. DCAT, Dublin core, (bio)schema.org) to specific data types (e.g. MIABIS for biosamples).

You should decide at the beginning of the project what are the recommended repositories for your data types (you will learn more on repository choice in the following module). Some repositories require a specific metadata standard. We, therefore, recommend familiarising yourself with the requirements of the repositories that could be appropriate for publishing your data already at the beginning of the project, so that you can start documenting and formatting your data according to their requirements as early as possible.

- ***If you have a repository in mind:***

  * Go to the repository website and check the “help”, "guide" or “how to submit” tab to find information about required metadata.
  - On the repository website, go through the submission process (try to submit some dummy data) to identify metadata requirements. 
  * For instance, if you consider publishing your transcriptomic data in ArrayExpress, you can make your metadata spreadsheet by using [Annotare 2.0 submission tool](https://www.ebi.ac.uk/fg/annotare/), at the beginning of the project.
  * Be aware that data type specific repositories usually have check-lists for metadata. For example, the European Nucleotide Archive provides [sample checklists](https://www.ebi.ac.uk/ena/browser/checklists) that can also be downloaded as a spreadsheet after log in.

- ***If you do not know yet what repository you will use:***

  * look for what is the recommended minimal information required for your type of data in your community
  * i.e. “Minimum Information ...your topic”,

     - e.g. [MIAME](https://www.fged.org/projects/miame)
     - or [MINSEQE](https://www.fged.org/projects/minseqe)
     - or [MIAPPE](https://www.miappe.org)

- ***or other metadata, at the following resources:***

  * [Research Data Alliance (RDA): Metadata Dictionary: Standards](https://rd-alliance.github.io/metadata-directory/standards/)
  * [FAIRsharing.org](https://fairsharing.org) at “Standards” and “Collections”
  * [The Digital Curation Centre (DCC): List of Metadata Standards](https://www.dcc.ac.uk/guidance/standards/metadata/list)

Please note that for certain data types, metadata standards may not be established by the research community. In such cases, README files are commonly used to describe the datasets (see below).^1^

Finding appropriate Vocabularies and/or Ontologies
--------------------

There are many vocabularies and ontologies available on the web. Finding a suitable one can be difficult and time-consuming.

Similarly to the metadata standards, check whether you really need to find a suitable ontology or vocabulary yourself. Perhaps the repository where you are about to submit your data have recommendations? Or the journal where you plan to publish your results? You also have to consider your goal with sharing data. Which formal requirements (by e.g. by funder or publisher) need to be fulfilled? Which parts of your data would benefit the most from adopting ontologies?

- After taking these considerations into account and deciding to adopt specific ontologies or vocabularies for your data, there are several factors you should consider:

  * Learn the basics about ontologies. This will be helpful when you search for terms in ontologies and want to understand how terms are related to one another.
  * Define a list of terms that you want to find ontologies for. Include in the list also any alternative term names that you are aware of.
  * Search for your listed terms on dedicated web portals. These are a few:

     - [Linked Open Vocabularies (LOV)](https://lov.linkeddata.es/dataset/lov/)
     - [EMBL-EBI Ontology Lookup Service](https://www.ebi.ac.uk/ols/index)
     - [Ontobee](http://www.ontobee.org)
     - [BioPortal](https://bioportal.bioontology.org)
     - [AgroPortal](https://agroportal.lirmm.fr)

- Accept that one ontology may not be sufficient to describe your data. It is very common that you have to combine terms from more than one ontology.
- Accept terms that are good enough. Sometimes you you cannot find a term that perfectly match what you want to express. Choosing the best available term is often better than not choosing a term at all. Note that the same concept may also be present in multiple ontologies.^1^

Metadata formats
--------------------

Most repositories require specific formats for uploaded metadata, particularly in the life sciences, where these formats can be highly subject-specific. It is always advisable to check the requirements of the various repositories.

Here are some formats:
- [ISA-Tab](https://isa-specs.readthedocs.io/en/latest/isatab.html)
- [mzTab-M](https://hupo-psi.github.io/mzTab/2_0-metabolomics-release/mzTab_format_specification_2_0-M_release.html)
- [ISA-JSON](https://isa-specs.readthedocs.io/en/latest/isajson.html)
- [MIxS](https://genomicsstandardsconsortium.github.io/mixs)
- [EML](https://eml.ecoinformatics.org)
- [Darwin Core](https://dwc.tdwg.org)
- [TEI P5](https://tei-c.org/release/doc/tei-p5-doc/en/html/index.html)
- [ISO 19115 / 19139](https://doc.esri.com/en/arcgis-pro/latest/help/metadata/create-iso-19115-and-iso-19139-metadata.html)
- [FITS](https://fits.gsfc.nasa.gov/)
- [CDISC SDTM / ADaM](https://www.cdisc.org/standards/foundational/adam)

## README files

README text files are often the simplest and most effective way to document your data, particularly when there are no established metadata standards. They serve as valuable documentation, making your data more understandable and reusable. README files can be used to include notes on the organization and content of digital folders and files. In the following paragraphs, you will discover best practices for creating README files and incorporating them as study- and data-level documentation.

When creating your README files follow these best practices:
--------------------

- Create READMEs for logical clusters: 
   * The amount and scope of your clusters depends on the size and complexity of your data. 
   * Each cluster should have its own readme file, providing an overview and details specific to that cluster. 
   * You should at least have one README file describing your project and one for your raw data.
- Name the README properly: 
   *Give your README file a clear and descriptive name that reflects its content and purpose.
- Write your readme as a plain text file and avoid propriertary formats.
- Format multiple readme files identically to enhance readbility and reduce confusion when you or others navigate through your different datasets. 
   * Remember to use standard formats, such as YYYY-MM-DD for dates, to promote interoperability and ease of understanding.
- Follow your discipline’s conventions for units, names, and keywords.

You can strategically plan the level of detail in your README files to ensure it is realistically manageable for you, while also providing sufficient information for someone who encounters your data for the first time to understand it.

Project-Level README
--------------------

**Your project-level README should include the following information:**

- Project title and a concise project description explaining the purpose of data collection.
- Creator's name and contact information for potential inquiries or collaborations.
- Details about the project's funding, including the funding agency and grant number associated with the project.
- Titles of the datasets used or generated by the project.
- Information regarding data confidentiality, access restrictions, and conditions of use.
- A comprehensive list of publications that cite or utilize the data from this project.
- Description of the file structure and organization, including folder hierarchies, naming conventions, file formats, and the relationships between different datasets.

Such well-structured project-level README that encompasses the aforementioned information will facilitate understanding, collaboration, and reproducibility of your project.

**Here is an example how such README file could look like:**

![README File Example1](https://raw.githubusercontent.com/feichtingerm/rdmlifesciunivie/main/images/projectlevelreadme_example.png)
![README File Example2](https://raw.githubusercontent.com/feichtingerm/rdmlifesciunivie/main/images/filetree_example.png " [README File Examples](https://zenodo.org/record/7573695/files/3-2_Espresso_READMEs.pdf?download=1), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode) ")

> [!Note] Please keep in mind that the provided format may not be optimized for machine-readability when compared to formats such as JSON files.

Data-Level README
--------------------
Your data-level README should encompass the following information:

- Title and a concise description of the dataset.
- Methodological details, including instrument- or software-specific information, standards, calibration information, and environmental or experimental conditions.
- Validation and quality assurance procedures employed during data collection.
- Data processing steps undertaken and any resulting alterations made to the data.
- A comprehensive variable list, including complete names and definitions of tabular data.
- Units of measurement for each variable.
- Abbreviations or acronyms used throughout the dataset.
- Codes used to indicate missing or invalid data.
- Reference to the project-level README for additional context and information.

By including these elements in your data-level README, you ensure that users have the necessary information to understand, analyze, and interpret the dataset accurately.You can access a comprehensive data-level README template provided by Cornell University [here](https://cornell.app.box.com/v/ReadmeTemplate). 

In conclusion, the richness and structure of README files add significant value to your data, providing understanding and reusability. However, it is essential to **strike a practical balance in the level of detail to ensure manageability for yourself**.

## Version Control

Version control is a way to keep track of changes made to files and datasets. While the implementation of a good file naming convention will indicate that different versions exist, this will not explain the difference between two (or more) versions. File versioning will enable transparency about which actions and changes were made and when. This makes it easy to backtrack and find something that was present in a previous version, but was later deleted or changed.

When considering which method of version control to employ, you may want to ask yourself the following questions:
--------------------

- Do I need to collaborate on files, perhaps at the same time?
- Is there a need to be able to backtrack and restore a previous version?
- Will there be many changes made?

For smaller demands of versioning, manual management can be sufficient. This can be done by keeping a log where changes for each respective file are documented, version by version or even descriptive file names.

Many cloud storage services, like u:cloud and OneDrive, provide automatic file versioning, which can be convenient for spreadsheets, text files, and slides.

Version Control with Git
--------------------

For more advanced version control, conflict resolution, and back-tracing capabilities, it is recommended to use dedicated version control software such as Git. Git can be hosted on platforms like [GitHub](https://github.com/) and [GitLab](https://gitlab.com/), but also on internal GitLab services like the University of Vienna [Phaidra GitLab](https://gitlab.phaidra.org).

It is primarily designed for managing source code files. But you could use it for anything text based. It's important to note that large binary files (e.g., videos, large images) may not be suitable for Git repositories due to their size, as they can bloat the repository and slow down operations. 
While operating Git through the command line may initially seem daunting, there are plenty of short tutorials available online that can help you use it with ease.

Some useful links:
- [Git Official Documentation](https://git-scm.dev/doc)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [Git as GUI](https://git-scm.com/tools/guis)
- [.gitignore File Creator](https://www.toptal.com/developers/gitignore/)


## Workflow Tools

In addition to version control and manual management, there are cases where using workflow tools can be highly beneficial. Workflow management systems help organize and automate the execution of computational tools. Compared to standalone scripts, workflow systems provide advantages such as documentation of computational analyses, scalability (including cloud execution), and improved reproducibility.

Workflow tools enable the specification of software packages or containers for the tools used within the workflow. This allows others to easily rerun the workflow without the need to pre-install every required software component, enhancing reproducibility. The field of workflow management is thriving, and [numerous workflow management systems](https://s.apache.org/existing-workflow-systems) are available.

Among the many workflow management systems available, one can mention:
--------------------

- Workflow platforms that manage your data and provide an interface (web, GUI, APIs) to run complex pipelines and review their results, such as [Galaxy](https://galaxyproject.org/).
- Workflow runners that take a workflow written in a proprietary or standardized format and execute it locally or on a remote compute infrastructure, such as [Nextflow](https://www.nextflow.io/) or [Snakemake](https://snakemake.readthedocs.io/).
    - If you are planning to use Snakemake on the [Life Science Compute Cluster](https://lisc.univie.ac.at/) (LiSC) there is a page in the [LiSC Wiki](https://lisc.univie.ac.at/wiki/content/working_environment/applications/snakemake) that provides support (access requires a user account).

Additionally, existing workflows can be reused or shared on popular services like [WorkflowHub](https://workflowhub.eu/) and [Dockstore](https://dockstore.org/), which provide repositories for workflows, making them accessible to the wider community.^1^

![XKCD Data Pipeline](https://imgs.xkcd.com/comics/data_pipeline.png "[Data Pipeline by XKCD](https://xkcd.com/2054), [CC BY-NC 2.5](https://creativecommons.org/licenses/by-nc/2.5/legalcode0)")

## Conclusion 
--------------------
Good research documentation makes your work easier to understand, manage, and build on—both for yourself and for others. In this module, you explored the basics of documenting research data, the role of metadata and relevant standards, and practical tools such as README files and version control. Together, these practices help you record what your data are, how they were created and processed, and how changes were made over time.

## Knowledge Check

- Wikis like Confluence and Outline or markdown notebooks such as Notion or ObsidianWhat a surprise, another quiz. Each question has at least one correct answer, but there can also be multiple correct answers.

Your data documentation should, at least, include documentation on:

    [[X]] Study-level
    [[ ]] Folder-level
    [[ ]] File-level
    [[X]] Data-level
    
Metadata standards, ontologies and controlled vocabularies:

    [[ ]] Should never be used together.
    [[X]] Can enable both humans and computers to understand your data.
    [[X]] Describe your data.
    [[ ]] Require hardly any effort to be established.
    [[X]] Can be required for specific repositories.
    
A README file describing one of your datasets should contain:

    [[X]] Methodological details.
    [[X]] Validation and quality assurance procedures.
    [[X]] Data processing steps.
    [[ ]] A definition of the FAIR principles.
    [[X]] units of measurement for each variable.
    [[ ]] As much information as possible.

Which statements on version control are correct:

    [[ ]] You should always use Git for any form of version control.
    [[X]] Descriptive file names can be used as version control.
    [[X]] Cloud storage services often provide automatic file versioning.
    [[X]] File versioning is particulary useful when working collaboratively.


## Sources 

Quotations
--------------------
**To make this course, we used resurces and text from a diversity of sources. If we quoted text directly from a source or we only lightly edited the text, that quotation is indicated by a superscript number. A list of those sources can be found here.**

^1^ ELIXIR. Research Data Management Kit. A deliverable from the EU-funded ELIXIR-CONVERGE project (grant agreement 871075). 2021. URL: https://rdmkit.elixir-europe.org/.
