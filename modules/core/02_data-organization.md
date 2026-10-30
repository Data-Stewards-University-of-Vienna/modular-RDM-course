
<!---
authors: Jeanne Wilbrandt, Michael Feichtinger, Isolde van Dorst

email: jeanne.wilbrandt@univie.ac.at, michael.feichtinger@univie.ac.at, isolde.van.dorst@univie.ac.at    

version:  1.0

language: en
--->

# Data Organization

Welcome to Module 2! In this module, you will learn about data organization: why is it important to organize your data, and how do you implement a good structure through the use of naming conventions. It will also discuss different file formats and how 

Objectives
--------------------

Learners will be able to:

* describe the relevance of file and folder naming conventions 
* state criteria for developing file and folder organization schemas
* develop naming conventions
* apply naming conventions to their own (and collaboratively) used research data
* describe the importance of choosing suitable file formats
* assess whether a specific file format is appropriate
  
Introduction
--------------------

**The Challenge**

In research, data flows from raw data to results, via tables and figures to communication outlets. We know there will be LOTS of files, that they can change over time (versions), have relationships to each other, and will be required to be understandable as the basis of our findings and publications. How can we keep track of all this?

<img width="337" height="318" alt="image" src="https://github.com/user-attachments/assets/94b6f07a-7445-4876-93d9-7f4e5a5c2d77" />
(JW, 2026-06-17_RDM_CoBeNe_Presentation_in-person_v02.key)

**The Solution**

To solve this challenge, you'll need to develop an organizational structure for all these files and come up with a system on how to name them. Just like in a well-sorted kitchen, it will make your work and collaboration a lot faster if you can find things easily. This means that file names and location need to be informative even before you open it. The more self-explanatory they are, the better.

There are two perspectives to keep in mind when to judging the quality of file and folder names: 1) Can you decide whether you want to open a folder or file, i.e., whether is it what you are looking for? And 2) Can you sort a file into a folder so you will able to find it again, i.e., do the folders match the natural categories of your work?

Organizing files well and sticking to naming conventions makes them more findable and accessible (feeding into the FAIR principles) and enable 'someone' to understand what you did -- that 'someone' is usually you in 6 months' time.

**The Imperative**

So in order to get to the solution, you need a plan and establish naming and structuring systems, document them, and make sure to use them consistently.

Any system is better than none!

How to Name Files and Folders
--------------------

Naming files and folders consistently ensures that there is a system in place when new files need to be added to ongoing projects. It will also enable you or others to find things again when returning to (potentially long finished) projects and files within those projects. Well thought-out naming conventions allow for easier and more efficient retrieval, tracking, and sharing of data.

Here are some guidelines for creating effective file names:
* **Give a unique name:** Each file should have a unique name that distinguishes it from other files.
* **Use elements essential to identify the file:** Include elements that are essential to identify the file, such as the name of the project, experiment, or subject.
* **Avoid long names, remove unnecessary elements:** Long file names can cause problems in storage, transfer, and handling of data. Keep file names concise and avoid unnecessary elements such as redundant information or irrelevant details.
* **Use ISO8601 standard for dates:** Using the ISO8601 standard for dates (i.e., YYYYMMDD) allows for consistent and chronological sorting of files.
* **Use ascending decimal version numbers:** When versioning files via filename, use ascending decimal version numbers (e.g., v1.0, v1.1, v1.2) to keep track of changes and updates.
* **Use alphanumerical characters only:** To ensure compatibility across platforms and systems, only use alphanumeric characters (A-Z, a-z, 0-9) in file names.
* **Do not use special characters:** Avoid using special characters in file names, as these can cause errors or conflicts in some systems.
* **Use underscores and camelCase to structure names:** Instead of using spaces in file names, use underscores ("_") for separation or write in camelCase.
* **Do not alter or remove the extension of a file:** File extensions indicate the format and type of the file. Do not alter or remove the extension of a file, as this can cause errors or prevent the file from being recognized by certain programs or systems.
* **Be consistent and reach consensus:** Be consistent in how you build up names and ensure that there is consensus among all team/project members to avoid confusion.
* **Document your naming scheme:** To ensure long-term accessibility and facilitate understanding you'll need to document your naming convention, for example in a README file (more on README files in the next module)

![XKCD Old Files](https://imgs.xkcd.com/comics/old_files.png " [Backups by XKCD](https://xkcd.com/1360/), [CC BY-NC 2.5](https://creativecommons.org/licenses/by-nc/2.5/legalcode0)")

For naming folders, similar guidelines apply, though they are usually more general in nature than the names of individual files. Here, you should also keep in mind that the structure of the folders matters. A well-designed folder structure can help you quickly and easily locate the data you need, saving you time and effort. A clear and consistent folder structure can also help you collaborate effectively with other members of your research team. By establishing a standardized approach, everyone involved can easily access and understand your data.

* **Design clear folder structures that align with the project:** Before starting your research, plan out a folder structure that aligns with the objectives and goals of your project. This structure should be intuitive, easy to understand, and should follow a logical sequence of stages.
* **Use the same structure for different locations:** If you are working on the project across multiple computers or with different team members, ensure that the same folder structure is used across all locations.
* **Use max. 4 levels of folders:** Keep the folder structure as simple as possible by limiting the number of levels to a maximum of four. This will make it easier to navigate and manage.
* **Classify folders according to different project stages (raw, processed, analyzed):** Classify the folders based on the different stages of the project, such as raw data, processed data, and analyzed data. This will help you to organize the files based on their current stage of completion and make it easier to locate the data when needed.
* **Document the folder structure:** Once you have finalized the folder structure, document it clearly to avoid confusion and ensure that all team members are on the same page.

To help make this more understandable, here is an example of such a folder structure:

<img width="520" height="454" alt="PhDModularCourse_02_DataOrganization_FolderStructure" src="https://github.com/user-attachments/assets/01da5a70-4953-4ca1-a6c9-ef26d9bb6b91" />

Types of Data to Organize
--------------------

Data can exist in different forms, and it is important to keep them separated. Generally speaking, data can be divided into three different types:
* **Raw data:** The original data that has not yet been processed, cleaned, or analyzed. It is unique and lossless, meaning it contains all the information collected by the instrument used to capture it. Raw data is typically in its original form, without any modifications, and may be in various formats, such as text, numerical, audio, or visual.
* **Processed data:** Data that has already been altered or cleaned in some way, such as normalization, removal of outliers, filled-in missing data, or any other modification to make it more suitable for specific analysis purposes. Processed data is typically in a format that is easier to work with, analyze, and visualize.
* **Analyzed data:** Can also be referred to as output data. This is the data that has been processed, interpreted, and analyzed. This stage often involves using statistical or other analytical techniques to extract insights or knowledge from the data. Analyzed data is often presented in the form of graphs, tables, or other visualizations that help to communicate the findings. This is often the type of data used in journal publications.

When preserving data, raw data is particularly valuable as it often cannot be reproduced easily. Raw data is unique and should be safeguarded to prevent loss. It should also be secured to prevent unauthorized access or modification through the use of password protection, encryption, or other security measures. While working on a dataset, it is useful to create a copy of the raw data as a working copy for processing and analysis. This will ensure that the original raw data does not accidentally get overwritten or edited.

Processed data can take several forms, but one of the more common ways to represent such data is through the use of 'tidy data'. Tidy data refers to a structured and standardized format that follows a set of principles, allowing for ease of data manipulation and interpretation. Tidy datasets are organized in a tabular manner in which each variable has its column, each observation has its row, and each value corresponds to a unique combination of variables and observations. Tidy data is the opposite of 'messy data', which is, as the name suggests, data that is mostly only readable by humans, and does not adhere to the clean organizational structure of tidy data.

Processing Data into Tidy Data
--------------------

Tidy data is structured into a data table, which is usually a structured format for organizing and presenting data. But to make your data understandable for your future self, colleagues and possible re-users of your data, you should learn how to create tidy data and how to recognize and fix common problems of spreadsheets and data tables.

By adhering to some simple rules you could create useful and tidy datasets that:

* facilitate clear and unambiguous communication
* are interoperable
* are easy to harmonize, sort, aggregate, and parse
* allow for the linking of source data and analyzed data
* accompany (machine-readable) metadata

When working with tables, standardization plays a pivotal role in ensuring accuracy and coherence. Consistency is key and it starts with harmonious coding. When creating tidy data tables, you should keep in mind the following key principles:

* **All data is labelled:** Each variable is clearly labeled in the header row, providing a descriptive name that represents the meaning of the data it contains.
* **Each subject has a unique ID:** Each subject or observation is assigned a unique identifier. This identifier serves as a key to differentiate between individual observations and enables tracking and referencing specific data points.
* **Data is in rectangular format:** Information is organized in a rectangular structure, where each row represents a distinct observation, and each column represents a unique variable.
* **Keep data and metadata separate:** Accompanying notes, annotations, or metadata are kept separate from your actual data. This separation ensures that the core dataset remains clean and uncluttered.
* **Do not encode information via color, font, etc.:** Conveying important information solely through visual attributes like color, font size, or formatting might improve your understanding, but introduces ambiguity and potential difficulties in the interpretation for other humans and machines.
* **Do not leave empty cells:** Missing data should not result in empty cells, instead, denote missing values clearly with a standardized label.

Research Group Norms, Rules, and Procedures for Data Organization
--------------------

While this module up to now has mostly focused on data organization for an individual, ideally there are also guidelines and practices in place within a research group. On the group level, further organizational structures might be necessary to ensure easy and effective collaboration with other members. Ask in your group about agreed upon practices and documentation of these practices. If there are none in place, you can also be the one to start this conversation. Clear structures and rules in a research group make it both easier for new members to find their way and can help prevent data and knowledge loss when people leave the group.

**README files**

The easiest aspect to introduce and maintain in a research group, is the use of README files. As will be discussed in more detail in the next module, a README file is an administrative metadata document detailing the specifics about a project or a dataset: Who created the data, what does the data entail, what file formats are there, how is data organized within folders, etc. A well written README file is a great starting point for someone accessing a new dataset or joining a project, as it will provide a brief overview of what is there. README files can be particularly helpful for research groups, as the specific composition of the project members might change over time and information might otherwise get lost.

**Templates**

A second great tool for a research group are data organization templates. While README files function on an overarching (meta)level, the templates can be used more specifically within projects. An example of a useful template would be a document detailing the metadata variables that should be collected during data collection, as well as the format in which to collect these variables. It could also include details on storage or other relevant aspects to the data collection, processing, or analyzing stages. The specifics of such templates will certainly vary between groups, but they can ensure consistency within a group, regardless of which project member is performing a task.

**Naming conventions**

Just as we discussed above, naming conventions can also be agreed upon within a whole research group. If files are stored in common spaces and need to be accessed by various group members, a common naming scheme will make the collaboration much easier.It can be very useful to sit down together and work through the needs of the research group overall and develop and document a file naming and organization system that works for everyone.

**Data clean up days**

An efficient way of ensuring all of the group members are able to keep up with the norms and procedures as planned out is the introduction of data clean up days. This might be especially helpful at the beginning phases of a new project or research group, or the introduction of a new person into the research group. On such days, the group members can sit together and work on implementing all the agreed-upon organizational structures according to the group's guidelines. 

File formats
--------------------

A file format is a way of encoding information within a computer file. A program or application must be able to recognise the file format in order to access data within the file. Understanding file formats is not just a technical consideration; it is a critical aspect of ensuring the reproducibility and transparency of your research.

In general, we can distinguish between proprietary and open formats. Files in proprietary formats usually must be opened by the software in which they were created. Someone without a licence to the software may not be able to open the file at all. Open formats, in which the software company or collective publishes the format rather than keeps it proprietary, are more likely to be readable by more than one application. Adobe PDF is an example of an open format that may be viewed in a number of applications, not just Adobe products. File formats that are non-proprietary (e.g. open source), or in widespread use, will tend to retain the best chance of being readable in the future. Proprietary formats, especially non-standard formats, used only by a specific software program or specific software version, are likely to present problems for future use. As you may have already surmised, archiving and publishing your data in the correct file format not only enhances their value but also promotes their FAIRness.^5^

A particular file format is often indicated as part of a file's name by a file name extension, or suffix. Conventionally, the extension follows a dot in the filename and contains three or four letters that identify the format (.jpg or .jpeg). In the Windows operating systems you can choose whether to display file suffixes or not. Mac files often do not have a suffix, which can be problematic when copying files to a different system to use.

** As a general rule, it is advisable not to alter or remove file name extensions.**

Text vs Binary formats and their suitability
--------------------

Text files are machine-readable through a character encoding standard such as ASCII or Unicode. Binary files can only be read by applicable software, and may be proprietary.

Some commonly used file extensions for saving plain text files include .txt, .csv, .html, .fastq and .tsv. The advantage of creating or saving research data in a text format, where possible, is that such files are highly machine-readable, tool-independent, and still readable for humans in any plain text editor. Therefore, text files are the most unlikely to become obsolete over time, and are a good format for sharing and long-term preservation. Unfortunately, converting binary formats into text files sometimes leads to the loss of valuable metadata associated with your research data (e.g. transforming your microscopy data into TIFF files). Therefore, it is advisable to consider storing and archiving your data in multiple formats to ensure the preservation of comprehensive metadata.^5^

In order to decide which format is most suitable for your data, you need to assess the following three criteria:

* **Compatibility:** Compatibility ensures that your archived data can be readily accessed and utilized in the future, without dependencies on proprietary software or outdated technologies.
* **Loss-less conversion to alternative formats:** This criterion is essential for future-proofing your data, as technologies and standards may evolve over time and to maintain all the consisting data.
* **Suitability for long-term archiving:** Consider formats that offer stability, robustness, and wide acceptance within the scientific community.

To help you determine whether to use a certain file format over another, this table provides an overview of various format properties and their suitability overall:

| Suitability | Readability for Machines | Readability for Humans | Long-Term Stability|Metadata|
| -----------|---------------|-------|---------|----------
| Very good | Using **very prevailing** software | **Yes** and without special software | **Standard** format | **Completely** included|
| Good      |Using **prevailing** and **documented** software |   Compressed using standard procedure, but in **uncompressed form yes** | Has been extensively **used** for a long time already | **Technical** information included |
| Mediocre  |**Proprietary** standard format|Can be **converted** into readable format using standard software|Relatively **new** format|**Some** important information (e.g., units) included|
| Bad       |**In-house** reader software|**No**|Just **contrived** format|**None**|

As a general rule, it is important not to become overwhelmed by the task of selecting a proper file format. It's essential to remember that there may not always be a perfect solution for every type of data. Consider the formats and software you are currently using, evaluate whether it makes sense to save your work in an additional format, and determine if you can easily convert between working/sharing formats and archiving formats. By considering these factors, you can make an informed decision that balances practicality and the long-term preservation of your research data.

Conclusion
--------------------

This module has taught you the importance of data organization through the use of naming conventions for your files and folders, the structure of your folders, and the implementation of organizational structures and guidelines for both individuals and research groups. This means that you will have the perfect organizational structure in place to actually document your research, i.e. the content of your files and folders. We have also discussed the importance of assessing file formats, and why it is important to choose these wisely to ensure longevity of the data. In the next module, you will learn what exactly should be included in your metadata for effective research documentation.

Knowledge Check
--------------------

Now that we discussed the importance of data organization with folder structures and file naming conventions, you can test your knowledge:

**Which of the following tips are good practice for file naming?**

  [[ ]] File names need to be unique, so longer names are most effective.
  [[X]] Dates should be recorded in the YYYYMMDD format.
  [[ ]] Each project member can have a unique naming system, as long as they are consistent themselves.
  [[X]] Underscores should be used instead of spaces in file names.
  [[X]] A document recording and describing your naming conventions and organizational structures should be kept for your project.
  [[X]] Versioning files via file names should use ascending decimal version numbers.
  [[ ]] A folder structure containing unlimited levels is fine when it is documented well.

**Organizing files makes them more findable and accessible.**

  [[X]] True
  [[ ]] False

**What type of data is processed data?**

  [[X]] Data that is in some form been modified, such as through normalization, to make it more suitable for analysis.
  [[ ]] Data that has been collected and automatically put into a tabular format, so that it can easily be understood by a computer.
  [[ ]] Data that has been interpreted, often through using statistical techniques to extract insights from the data.

**The introduction of a template for data organization is most useful when a project had ended.**

  [[ ]] True
  [[X]] False  

**When selecting file formats (for long-term archiving) you should consider:**

[[X]] Machine readability
[[X]] Long-term stability
[[X]] Human readability
[[ ]] University software availability
[[X]] Metadata inclusion   
