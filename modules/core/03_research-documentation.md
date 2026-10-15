<!--
authors: Mathias Mayrgündter, Simone Spedicato 

email: mathias.mayrguendter@univie.ac.at, simone.spedicato@univie.ac.at    

version:  1.0

language: en

TODO
- write first draft
- add section lines
- review round

-->

# Research Documentation

## Learning Objectives

## Data Documentation

Data documentation could be defined as the clear description of everything that a new “data user” or “your future-self” would need to know in order to find, understand, reproduce and reuse your data, independently. Data documentation should clearly describe how you generated or used the data, why, and where to find the related files. It could be used also as onboarding documentation for new colleagues, even if the responsible researcher leaves the project.

Due to the large variety of experiments, techniques and collaborative studies that usually occur within the same project, it is challenging to keep good documentation. However, lack of good data documentation often leads to data loss, not reproducible results or worklfows and therefore, waste of money and time.

By the end of this section, you should be familiar with best-practices considering data documentation.

### When documenting your data you should keep the following things in mind:

- Write the documentation in such a way that someone else who is known to the field cannot misinterpret any of the data. 

- Independently of the tools you will use, data documentation is needed at two levels:
    1. **Study-level** 
        * Documentation about the entire study or project

        * Study-level documentation describes the project title and summary, study aims, authors, institutions involved, funds, methods, licence and identifier for each dataset, folders structure, file naming conventions, versioning system, relation between files or tables and other general information.

    2. **Data-level** 
        * Documentation about individual records, observations or data points

        * Data-level documentation provides information about individual records or data points, such as the meaning of each variable name, label, ID or type (numeric, string, regular expression, date, etc.), units (i.e., cm, kg…), experimental factors, categories, controlled vocabulary or ontology terms accepted as values for each variable, missing values code and so on. 

        * An example could be a data file that contains a "sex" field: someone known to the field could try to misinterpret that from "external sex organs present at birth" to "chromosomal XX or XY" or "high or low testosterone level" or "social gender" or other. In order to avoid this, the way the assignment is made must be part of the documentation or of the data itself (controlled vocabulary). 

- Both the study- and data-level documentation must be generated as early as possible in the research process and also maintained, in order to be accurate and complete.

- Documentation is also required when publishing your data.

    * General-purpose repositories usually require only study-level documentation.

    * Discipline-specific repositories generally require both study-level and data-level documentation.

    * > [!IMPORTANT] \
        > Repositories often only accept data and documentation in a very strict format
        > - they can require a predefined set of attributes or fields (metadata checklists) to be filled, ontology terms to be used, specific (meta)data schemas to be adopted
        > - We recommend familiarising yourself with  the requirements of the repositories that could be appropriate for publishing your data already at the beginning of the project, so that you can start documenting and formatting your data accordingly as early as possible.

- Make sure the documentation is kept close to the data, so that nobody will be exposed to the data without being able to find the documentation.

### Documentation Tools

- It is best practice to use one appropriate tool or an integration of multiple tools for data documentation during a project. 

- Suitable tools for data documentation are Electronic Lab Notebooks (ELNs) and/or Laboratory Information Management Systems (LIMS). 

- At CeMESS there is currently the implementation of the ELN [RSpace](https://www.researchspace.com/) going on. 

- A university-wide solution does not exist so far, but if you are part of the Faculty of Life Sciences and your research group is interested to use RSpace, reach out to Emily Kate (emily.jean.kate@univie.ac.at).

- Futhermore, you could use online platforms for collaborative research and file sharing services (such as [OSF](https://osf.io/)) as ELN or data management systems. 

- For help making this decision, contact your data steward.

### Documentation File Format

- Data documentation files can be stored in several formats depending on the features available in your data documentation tool (if using one), your needs or skills. 

- Machine-readable or -actionable formats are preferred to non-machine-readable ones. 

- Also non-proprietary formats are preferred over proprietary ones.

### Conclusion

When it comes to addressing issues in data documentation, there is no single optimal solution; instead, it exists as a spectrum ranging from inadequate to excellent documentation. Even something as basic as maintaining a digital record of your handwritten lab notebook or including a reference to it in a README file alongside your dataset can serve as an initial step.

## Metadata Standards

## README files

## Version Control

## Workflow Tools

## Quiz