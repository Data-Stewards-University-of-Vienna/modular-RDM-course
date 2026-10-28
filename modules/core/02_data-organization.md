
<!--
authors: Jeanne Wilbrandt, Michael Feichtinger, Isolde van Dorst

email: jeanne.wilbrandt@univie.ac.at, michael.feichtinger@univie.ac.at, isolde.van.dorst@univie.ac.at    

version:  1.0

language: en

TODO
- insert image properly
- review round

-->

# Data Organization

Objectives
--------------------

Learners will be able to:

* describe the relevance of file and folder naming conventions 
* state criteria for developing file and folder organization schemas
* develop naming conventions
* apply naming conventions to their own (and collaboratively) used research data
  
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

IMAGE: https://phdcomics.com/comics/archive.php?comicid=1323
("Piled Higher and Deeper" by Jorge Cham, www.phdcomics.com) -- I've emailed them to ask for permission to use it, just waiting for response. Haven't figured out how to actually format it to show up though...
IMAGE ALTERNATIVE: https://xkcd.com/1360/

For naming folders, similar guidelines apply, though they are usually more general in nature than the names of individual files. Here, you should also keep in mind that the structure of the folders matters. A well-designed folder structure can help you quickly and easily locate the data you need, saving you time and effort. A clear and consistent folder structure can also help you collaborate effectively with other members of your research team. By establishing a standardized approach, everyone involved can easily access and understand your data.

* **Design clear folder structures that align with the project:** Before starting your research, plan out a folder structure that aligns with the objectives and goals of your project. This structure should be intuitive, easy to understand, and should follow a logical sequence of stages.
* **Use the same structure for different locations:** If you are working on the project across multiple computers or with different team members, ensure that the same folder structure is used across all locations.
* **Use max. 4 levels of folders:** Keep the folder structure as simple as possible by limiting the number of levels to a maximum of four. This will make it easier to navigate and manage.
* **Classify folders according to different project stages (raw, processed, analyzed):** Classify the folders based on the different stages of the project, such as raw data, processed data, and analyzed data. This will help you to organize the files based on their current stage of completion and make it easier to locate the data when needed.
* **Document the folder structure:** Once you have finalized the folder structure, document it clearly to avoid confusion and ensure that all team members are on the same page.

Types of Data to Organise
--------------------

Data can exist in different forms, and it is important to keep them separated. Generally speaking, data can be divided into three different types:
* **Raw data:** The original data that has not yet been processed, cleaned, or analysed. It is unique and lossless, meaning it contains all the information collected by the instrument used to capture it. Raw data is typically in its original form, without any modifications, and may be in various formats, such as text, numerical, audio, or visual.
* **Processed data:** Data that has already been altered or cleaned in some way, such as normalisation, removal of outliers, filled-in missing data, or any other modification to make it more suitable for specific analysis purposes. Processed data is typically in a format that is easier to work with, analyze, and visualize.
* **Analysed data:** Can also be referred to as output data. This is the data that has been processed, interpreted, and analysed. This stage often involves using statistical or other analytical techniques to extract insights or knowledge from the data. Analyzed data is often presented in the form of graphs, tables, or other visualizations that help to communicate the findings. This is often the type of data used in journal publications.

When preserving data, raw data is particularly valuable as it often cannot be reproduced easily. Raw data is unique and should be safeguarded to prevent loss. It should also be secured to prevent unauthorised access or modification through the use of password protection, encryption, or other security measures. While working on a dataset, it is useful to create a copy of the raw data as a working copy for processing and analysis. This will ensure that the original raw data does not accidentally get overwritten or edited.

Research Group Norms, Rules, and Procedures for Data Organisation
--------------------

While this module up to now has mostly focussed on data organisation for an individual, ideally there are also guidelines and practices in place within a research group. On the group level, further organisational structures might be necessary to ensure easy and effective collaboration with other members. Ask in your group about agreed upon practices and documentation of these practices. If there are none in place, you can also be the one to start this conversation. Clear structures and rules in a research group make it both easier for new members to find their way and can help prevent data and knowledge loss when people leave the group.

**README files**

The easiest aspect to introduce and maintain in a research group, is the use of README files. As will be discussed in more detail in the next module, a README file is an administrative metadata document detailing the specifics about a project or a dataset: Who created the data, what does the data entail, what file formats are there, how is data organized within folders, etc. A well written README file is a great starting point for someone accessing a new dataset or joining a project, as it will provide a brief overview of what is there. README files can be particularly helpful for research groups, as the specific composition of the project members might change over time and information might otherwise get lost.

**Templates**

A second great tool for a research group are data organization templates. While README files function on an overarching (meta)level, the templates can be used more specifically within projects. An example of a useful template would be a document detailing the metadata variables that should be collected during data collection, as well as the format in which to collect these variables. It could also include details on storage or other relevant aspects to the data collection, processing, or analysing stages. The specifics of such templates will certainly vary between groups, but they can ensure consistency within a group, regardless of which project member is performing a task.

**Naming conventions**

Just as we discussed above, naming conventions can also be agreed upon within a whole research group. If files are stored in common spaces and need to be accessed by various group members, a common naming scheme will make the collaboration much easier.It can be very useful to sit down together and work through the needs of the research group overall and develop and document a file naming and organisation system that works for everyone.

**Data clean up days**

An efficient way of ensuring all of the group members are able to keep up with the norms and procedures as planned out is the introduction of data clean up days. This might be especially helpful at the beginning phases of a new project or research group, or the introduction of a new person into the research group. On such days, the group members can sit together and work on implementing all the agreed-upon organisational structures according to the group's guidelines. 

Conclusion
--------------------

This module has taught you the importance of data organisation through the use of naming conventions for your files and folders, the structure of your folders, and the implementation of organisational structures and guidelines for both individuals and research groups. This means that you will have the perfect organisational structure in place to actually document your research, i.e. the content of your files and folders. In the next module, you will learn just that: what exactly to include in your metadata for effective research documentation.

Quiz
--------------------

Now that we discussed the importance of data organization with folder structures and file naming conventions, you can test your knowledge:

**Which of the following tips are good practice for file naming?**

  [[ ]] File names need to be unique, so longer names are most effective.
  [[X]] Dates should be recorded in the YYYYMMDD format.
  [[ ]] Each project member can have a unique naming system, as long as they are consistent themselves.
  [[X]] Underscores should be used instead of spaces in file names.
  [[X]] A document recording and describing your naming conventions and organisational structures should be kept for your project.
  [[X]] Versioning files via file names should use ascending decimal version numbers.
  [[ ]] A folder structure containing unlimited levels is fine when it is documented well.

**Organising files makes them more findable and accessible.**

  [[X]] True
  [[ ]] False

**What type of data is processed data?**

  [[X]] Data that is in some form been modified, such as through normalisation, to make it more suitable for analysis.
  [[ ]] Data that has been collected and automatically put into a tabular format, so that it can easily be understood by a computer.
  [[ ]] Data that has been interpreted, often through using statistical techniques to extract insights from the data.

  **The introduction of a template for data organisation is most useful when a project had ended.**

  [[ ]] True
  [[X]] False  
