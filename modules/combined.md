
<!--
authors: Emily J. Kate, Franziska Bauchinger

email: emily.jean.kate@univie.ac.at, franziska.bauchinger@univie.ac.at
version:  1.0

language: en

-->
# Orientation
**Welcome to Research Data Management for Ph.D. Candidates in CoBeNe** 

We’re so glad you’re here! Before we delve into the exciting world of Research Data Management (RDM), we want to make sure you know what you’ve gotten yourself into. Don’t worry. We removed most of the scary stuff during beta testing. 

**Blended Learning and Our Plan**

This course is designed around a concept called “blended learning”, which is a fancy way of saying that we use both online and in-person learning resources. In our case, you will have until the beginning of the in-person workshop to complete the online modules here on Moodle. The Moodle portion of the course should take you around 4 hours and we recommend you complete the modules in-order but you don't have to do them all at once. More details about the in-person workshop can be found on the course Moodle page.

![The Upturned Microscope](https://upmic.files.wordpress.com/2019/05/epfl-may2019-flipped-classroom.png?w=650&h=199 " [Flipped Classroom by Upturned Microscope](https://upmic.files.wordpress.com/2019/05/epfl-may2019-flipped-classroom.png?w=650&h=199),[CC BY-NC-ND 3.0](https://creativecommons.org/licenses/by-nc-nd/3.0/)")

**Will We be Graded?**

Diligent student that you are, you may be wondering about assignments, quizzes, and grades. The simple answer is that there are no grades. You signed up for this course because you have an interest in learning more about RDM. We agreed to teach the course because we like teaching about RDM and think students are the most fun to support. Throughout the Moodle modules, there are some self-knowledge quizzes. Most are multiple-choice and you can attempt them as often as you like. No one is keeping score. Actually, the code we used to build this course is digitally incapable of it.

**What about ECTS Credits?** 

We are often asked if students will receive ECTS credits for completing the Moodle modules and attending the in-person workshop. The answer varies depending upon which doctoral school you call home. You can always ask the data steward teaching this course if they know how the doctoral schools for each discipline handle this workshop, but doctoral school coordinators provide the final determination on awarded credits. 

With that said, if you attend both days of the workshop, you will receive a certificate of completion and the trainers will also send a list of participants to the doctoral schools. 

What will We Learn?
--------------------

What a good question! Below you will find the primary course objectives and an outline of the course modules. Keep in mind that each module also has specific learning objectives on which you should focus. 

**Primary Course Objectives**

By the end of this course, you should be able to: 

1. Describe the relevance of research data management (RDM) and open science (OS), as well as the advantages and disadvantages of RDM and OS for individual researchers and whole disciplines. 

2. Apply best practices in data preservation, documentation, and sharing to maximize the long-term impact and reusability of research outputs. 

3. Identify and address ethical, legal, and institutional considerations when collecting, managing, and sharing research data. 

**Course Modules**

The course contains nine modules that you should complete before attending the in-person sessions. 

**Module 1:** Orientation (You are here!)

**Module 2:** Key Principles 

**Module 3:** Data Organization 

**Module 4:** Research Documentation 

**Module 5:** Data Storage, Sharing, and Security

**Module 6:** Archiving and Publishing Data  

**Module 7:** Data Reuse 

**Module 8:** Ethical and Legal Issues in RDM

**Module 9:** Data Management Plans (DMPs)


Bye!
--------------------
If you have any questions during the course, please feel free to contact us! We would love to hear from you. See you soon!

**The UNIVIE Data Stewards**
<!--
authors: Emily J. Kate, Lukas Kraiger 
email: emily.jean.kate@univie.ac.at, lukas.kraiger@univie.ac.at    

version:  1.0

language: en

-->
# Key Concepts and Principles 
Welcome to Module 1! In this module, we’ll build the foundation for the rest of the course by looking at what research data actually includes, how it can be managed throughout a project, and how RDM connects to FAIR data and Open Science. Let's jump in! 

Objectives
-------------------- 
By the end of this module, you should be able to: 

1. Define research data and metadata, identify different forms of research data, and explain the role of metadata in making research data understandable and reusable.  

2. Describe the research data life cycle and identify good RDM practices that support data organization, documentation, preservation, sharing, and reuse across its stages.

3. Explain how RDM, FAIR data, and Open Science are connected, and describe how Open Science principles are reflected in current institutional, national, European, and funder expectations.

Introduction
--------------------
Before we get into file naming, tidy data, repositories, or any of the other practical parts of research data management, we need to make sure we are speaking the same language. This module introduces the core ideas that will come up again and again throughout the course: research data, metadata, Research Data Management, the research data life cycle, FAIR data, and Open Science. We’ll look at how these concepts fit together, why they matter for day-to-day research, and how broader Open Science principles are increasingly reflected in institutional, national, European, and funder expectations. Don’t worry about memorizing every policy, acronym, or framework along the way—the goal here is to understand the bigger picture and start thinking about where your own research fits within it.

## What is Research Data Management? 

What is Research Data?
--------------------
We all know what research data is, right? I mean, it’s data from research. The meaning is clear. Crisis averted. We can all go home. Or maybe not… The problem starts when we delve a little deeper into what we mean by “data”. 

The University of Vienna considers research data to be “all information (irrespective of its form or presentation) that supports or validates research activities (development, results, observations or findings, including contextual information). Research data comprise all materials that are created in the course of academic work, including records, source research, experiments, measurements, surveys and interviews, as well as software and code. Research data may take on various different forms: during the lifespan of a research activity, data may exist as gradations from raw data to processed data (and even include negative and inconclusive results)”.

What a mouthful, but the punchline is that your research data is a lot more than just the individual measurements you used to formulate your newest figure or validate your most recent hypothesis. Your research data certainly includes those things, but all information you create during the research process can be considered data too! Even your “negative results” are data. Not all data will be sent into the world as an open source dataset and that’s okay, but it doesn’t mean we shouldn’t give those tidbits as much care and attention as the other stuff. We’ll talk more about why some data shouldn’t be released into the wild a little later. 

Alright, now that we know what research data is, we can move onto metadata and that mysteriously bureaucratic phrase “research data management”. I bet the people who work in the RDM department are a bunch of boring pencil pushers…oh wait…I’m being told we work in that department…but I’m not boring and I rarely push pencils. 

What is Metadata?
--------------------

In the words of Mugatu from the legendary film *Zoolander*, metadata is “so hot right now.” Despite its seemingly sudden popularity, you might be wondering how to define metadata and what it means for your research. The University of Vienna defines metadata as information that is “used to describe managed resources in a unique and structured manner. The unique structure enables users to search for, find, and select relevant resources. Metadata are a means of communication between producers and users of research data, and are crucial for making data findable.” While accurate, perhaps this definition isn’t the most helpful for someone who is trying to figure how they can document their data more fully. To get a more hands-on explanation, take a look at this video from the University of Ghent.

!?[Ghent University Data Stewards (2020) Knowledge Clip: Metadata](https://youtu.be/DW2T_cnqKPU "[Ghent University Data Stewards (2020) Knowledge Clip: Metadata](https://youtu.be/DW2T_cnqKPU), [CC BY](https://creativecommons.org/licenses/by/3.0/legalcode)") 

In practice, metadata is simply the information that helps explain your data. It can be as basic as a title, the name of the creator, the date of collection, and a short description of what the data contain.

Good metadata helps others—and your future self—find, understand, and reuse your data. For example, if someone opens a file called `final_data_v2.csv`, metadata can explain what the file contains, what the columns mean, and how the data were created.

Essentially, metadata is data about your data and there are a few types of metadata you should think about: **administrative metadata**, **structural metadata**, and **descriptive metadata**. Let’s look at each type in a little more detail.

* **Administrative metadata** covers some technical and legal aspects of data creation and reuse. Administrative metadata of a technical nature often describes things like when files were created, the file types used, and how the files were created. Information about the owner and creator of the files can also be included here. On the more legal side, administrative metadata defines what license has been applied to a resource, how the resource can be reused, and how long and under what conditions the resource will be archived. 

* **Structural metadata** contains information about how a resource is organized and can also describe what one item’s relationship is to a larger collection. A book’s table of contents is a very good example of structural metadata. The table of contents tells you the book’s title, the names of the chapters, and their page numbers. It also points you to supplemental resources like the bibliography or index. A statement on the front cover of a book that tells you that it is part of a larger series can also be considered structural metadata. 

* **Descriptive metadata** is the largest category of metadata. In short, descriptive metadata ensures that an item is findable and interpretable. For example, in a library a book’s topic and unique call-number can be used to quickly locate it on the shelves. If data is archived online, a unique persistent identifier like a DOI might be used to ensure that resources can always be found again. Descriptive metadata might also include explanations of column headings or controlled vocabularies that have been used to describe observations. 

Within these categories, metadata can be **structured** or **unstructured**.

* **Structured metadata** records information in predefined fields using a consistent format or vocabulary. Because the information is organized predictably, it can be searched, filtered, compared, and processed efficiently by both humans and computers. Common examples of structured metadata are species names, authors, temperatures, or dates. 

* **Unstructured metadata** records information as free text without predefined fields or a standardized format. While it often provides rich context, it is more difficult for computers to search, compare, and process automatically. Common examples of unstructured metadata include lab notebooks and many README files. 

When you upload data to an archive or publish a paper you submit most of this information to the repository or publisher. In the best systems, this information is made machine-readable and can be picked-up by services like search engines so that your data doesn’t get lost in the chaos that is the internet. Because metadata documents important attributes of your data and makes it findable, it is important that metadata creation be handled with care and consideration! 

What is Research Data Management?
--------------------
If you guessed that research data management involves the management of research data, you’re right, but you also just reorganized three words to create a less-than-specific definition. Again, the University of Vienna has a specific definition for research data management (RDM), which is drawn from our RDM policy. Here it is in all its glory: 

“Given the heterogeneous nature of research data, research data management (RDM) may include different aspects depending on the relevant discipline. In general, RDM covers all research data during the entire research process, e.g. planning and generating data, documentation, data administration, secure storage, access management, as well as reuse, (long-term) archiving and access regulation. RDM should ensure that research data are effectively managed during the research project and that they are securely archived and made reusable after project completion…”

Our friends at Ghent University are also really passionate about RDM and they created this great video that provides another perspective on what RDM entails. 

!?[Ghent University Data Stewards (2020) Knowledge Clip: What is Research Data Management (RDM)](https://youtu.be/bbsLmy3Njv4 "[Ghent University Data Stewards 2020. Knowledge Clip: What is Research Data Management (RDM)](https://youtu.be/bbsLmy3Njv4), [CC BY](https://creativecommons.org/licenses/by/3.0/legalcode)") 

Finished watching? So now you know that research data management means ensuring that your data are well organized, documented, securely stored, eventually archived, findable, and reusable by others whenever possible. This might seem overwhelming, but never fear! The Research Data Management Team at the University of Vienna is here to help. 

We have a handy website at [rdm.univie.ac.at](https://rdm.univie.ac.at) and you can email us anytime at [RDM Team](mailto:rdm@univie.ac.at). If you or your friends are part of any of the faculties or centers listed below, there is dedicated data steward who can help you too! Send a data steward or the RDM team an email with a question and we will get back to you within three working days. We’ll either answer your question or outline some next steps. You can find the contact information for all of the data stewards on this 
[page](https://rdm.univie.ac.at/data-stewards-at-the-university/meet-the-data-stewards/).

* Faculty of Life Sciences 
* Centre for Microbiology and Environmental Systems Science (CeMESS) 
* Faculty of Earth Sciences, Geography, and Astronomy 
* Faculty of Psychology 
* Faculty of Business, Economics, and Statistics 
* Faculty of Philological and Cultural Studies 
* Faculty of Historical and Cultural Studies 
* Faculty of Chemistry (Mass Spectrometry Centre)

## The Research Data Life Cycle

The Data Life Cycle has seven stages that are pretty simple to understand. Way easier than remembering the cell cycle. The Data Life Cycle begins with the planning stages of your project and ends when your data is being re-used by someone else. In each of these stages, there are things you can do to care for your data and to encourage scientific cooperation.

![Research Data Life Cycle](https://github.com/elixir-europe/rdmkit/blob/master/images/data_life_cycle_9.png?raw=true "[Research Data Life Cycle by Elixir RDM Kit](https://rdmkit.elixir-europe.org/), [CC BY](https://github.com/elixir-europe/rdmkit/blob/master/LICENSE)") 

As you can see above, the stages of the Data Life Cycle are:

1. Planning 
2. Collecting 
3. Processing 
4. Analysing 
5. Preserving 
6. Sharing 
7. Reusing 

The cycle begins again when someone incorporates your data into their project or when you use data that was created by another researcher. Just remember PCPAPSR...XYZLMNOP...never mind. That's a terrible acronym. Actually, the best approach is for you to develop a good understanding of each stage in the research data life cycle. Watch this quick clip from the University of Ghent and then we will discuss each stage in more detail. By the end of this section, you should be able to explain the research data life cycle, but also think about how it relates to your work.    

!?[Ghent University Data Stewards (2020) Knowledge Clip: The Research Data Life Cycle](https://youtu.be/OL_Vd9dd-AQ "[Ghent University Data Stewards (2020) Knowledge Clip: The Research Data Life Cycle](https://youtu.be/OL_Vd9dd-AQ), [CC BY](https://creativecommons.org/licenses/by/3.0/legalcode)") 

Step 1: Planning
--------------------
Data management planning consists of defining the strategy that you will use for managing data and documentation generated within a project. It is about considering the best way to avoid problems or unexpected costs related to data management, while also setting-up your research data to achieve the highest possible impact, even after the end of your project.^1^ One of the most common ways to articulate this strategy is with a data management plan (DMP). You probably have questions about how to write a DMP, but we will cover that more in the final module of this course. 

Step 2: Collecting
--------------------
Data collection is the process by which information is gathered about specific variables of interest either using instrumentation or other methods, like questionnaires, patient records, or interviews. While data collection methods depend on the field and research subject, it is important to ensure data quality. Data collection could also mean reusing existing data in your project. This can be data you or your colleagues collected earlier, reference data from curated resources, or data uploaded to repositories by other researchers.^1^ 

![The Upturned Microscope Change the Data](https://upmic.files.wordpress.com/2023/03/comic-14-change-the-data.png?w=650 " [Change the Data by Upturned Microscope](https://upmic.files.wordpress.com/2023/03/comic-14-change-the-data.png?w=650), [CC BY-NC-ND 3.0](https://creativecommons.org/licenses/by-nc-nd/3.0/)")

Apart from being the source of information to build your findings on, the collection phase lays the foundation for the quality of both the data and its documentation. It is important that the decisions made regarding quality measures are implemented and that the collection procedures are appropriately recorded.^1^ When collecting data, you should ensure that whatever system you use does the following:  

* Captures important data like provenance of samples, their identifiers, the instruments used, and the researchers involved.
* Clearly defines the quality control standards you will use to assess data quality. 
* Details the experimental design of your project including information on important factors like repetitions, controls, and randomization. 
* Describes instrument settings and calibrations. 
* Adheres to any data protection, permission, or consent requirements within your project.
* Details how data will be stored, backed-up, and archived.
* Follows any discipline specific metadata standards. (More about this below!) 

Step 3: Processing
--------------------
Data processing is the phase in the project where data is converted into a desired format and prepared for analysis. When data has been freshly collected, data processing might include some automated steps that perform format conversions, quality checks, and preprocessing following a standardised protocol. The main aim of processing is to:

* Convert data into readable format, giving it the shape and form necessary for downstream analysis.
* Discard bad or low quality data in order to create clean, high-quality dataset for reliable results.

When data is imported from existing sources, like data downloaded from a repository, processing can also include manual steps to make it suitable for analysis. These steps include but are not limited to:

* Making changes to data formats such that different datasets will be compatible for integration with each other.
* Changing coding systems or ontologies for the data to bring everything to the same level. 
* Filtering data such that only data suitable for the project is retained.

After data processing, clean data is ready for analysis and should therefore be available to the members of the project team that need to perform the next steps. Data processing is important to ensure good quality of the collected data and to prepare it for meaningful data analysis. Accurate data processing is also essential for combining two or more datasets into a single dataset. An accurate documentation of every step done during data processing is key for the reproducibility of your result. Processing data correctly makes it easy to arrange, easy to analyse, and saves time.^1^

Also, remember that when you work with sensitive or protected data, you should pseudonymize or anonymize your data during the processing phase whenever possible. You should also use discipline specific methods of encoding variables if they are available, and you should keep careful records of how data was pseudonymized or anonymized. It’s never a bad idea to also maintain a codebook where your variables are all explained. 

Step 4: Analyzing
--------------------
Data analysis begins when you finally dive into your data and use it to answer scientific questions or test hypotheses. The methods you use to analyze your data are also called a “workflow”. During many projects, workflows will likely be repeated several times and modified to increase reliability and efficiency. Always remember to keep clear records of how your workflow changes over time. You always want your workflows to be reproduceable by your team members and other researchers. This reproducibility is a central tenant of making science FAIR. Thinking about how you should analyze your data is certainly important, but you should also consider how you will document your analyses and investigations. 

Here are two last tips from people who know some things because they’ve seen some things and *occasionally* made mistakes themselves. First, always keep an unedited version of your unanalysed data stored. Never use this specific file to conduct analyses. Use a copy instead. This way, if you make a problematic edit to your data or your data gets jumbled, you can always make a copy of the original file and start again. This takes the situation from “data disaster” to an "inconvenient afternoon". Second, if you are conducting analyses and find yourself confused with a million files open and an inability to think clearly, it’s probably time for a break. Take a walk. Eat something. Have a nap. Drink some water. You aren’t going to make good analytical decisions when you’re frazzled, and you certainly won’t document things properly. A 30-minute break can save you hours of headache later. 

Step 5: Preserving
--------------------
When you hear of preserving, you might think of culinary delicacies such as smoked hams, canned pickles, or jarred jams. Sadly, this section will not be about any of those things. Data preservation is a process by which the safety, integrity, and accessibility of your data are ensured. In many cases, data should be preserved for years, or even decades. You might think that properly storing your data means it is preserved, but this is not quite the whole story. Preservation of digital information requires planning, policies, resources (time, funds, and people) as well as the right technology to ensure that the data stays functional and that it can be accessed. Therefore, true data preservation, or archiving, must be done by experts and dedicated services. In most instances, special long term data repositories should be used for digital preservation, where the data is actively maintained and information integrity is monitored.^1^ 

![Trader Joe's Pickle Car](https://upload.wikimedia.org/wikipedia/commons/4/43/Trader_Joe%27s_-_Pickle_Car_%2812221274575%29.jpg "We know you also wish this section was about making pickles and other preserves. Sadly, it isn't, but maybe you could get yourself a pickle as a treat for making it this far.  [Source: Prayitno / Thank you for (12 millions +) view from Los Angeles, USA](https://upload.wikimedia.org/wikipedia/commons/4/43/Trader_Joe%27s_-_Pickle_Car_%2812221274575%29.jpg), [CC BY](https://creativecommons.org/licenses/by/2.0/deed.en)") 


The first step in data preservation is to decide what data should be maintained and what data can be destroyed. All (non-sensitive) data that contributed to a publication should be preserved. In most cases, publishers and funding agencies will require that this data be made available. In many projects, researchers generate more data than they include in publications. This is where the decision-making process can be a little tricky. When considering if unpublished datasets should be preserved, researchers can ask themselves some critical questions. 

First, is the data in question high-quality, reproducible, and well documented? You should only archive unpublished data if the answer is a confident “yes”. Second, ask yourself if the data would be a new contribution to the scientific community and if it would be truly useful to another researcher. This is not to say that your experiment confirming the effectiveness of someone else’s method is valueless, but if you are the 275th researcher to make this conclusion, then the data is probably not worth archiving. Also, results from a smattering of disjointed or unorganized experiments are unlikely to be truly helpful. With this said, you should always think very critically about how data you produce might be useful and sometimes the answer is not easy to determine. In these instances, conversations with trusted colleagues and RDM experts can help you make a good choice. Here are few summarizing points about what should always be archived: 

* Data that must be published because of funder, publisher, or institutional policies. 
* Data that must be preserved due to legal or ethical requirements. 
* Unique data that cannot be easily re-created due to factors like high costs. 
* Data that will probably be reused. 
* Data that is of great cultural, historical, or scientific importance. 

You should also know that there is some data that should be destroyed as soon as possible. Usually, this data contains sensitive information, but never delete data without talking your supervisor! A little later, we will talk more about things like how to select a repository for your data and how long your data should be preserved. 

Step 6: Sharing
--------------------
We all know that “sharing is caring”, but what does sharing mean in the context of research data management? Sharing data doesn’t mean that it is automatically open for others to use, but rather that your data is findable and that conscious choices have been made regarding who has access. You can actually share data at any time during the data life cycle and shift who can access the data as your project progresses. For example, you might share data with a collaborator or lab mates during the analysis phase but then place the data in an archive under a creative commons license once your papers are published. If you are thinking of sharing data, you should speak with your supervisor first, but here are some things to consider: 

* Are you the legal rights holder for the data? 
* Are there any ethical, legal, contractual, or intellectual property restrictions you need to consider? 
* Are there funder or institutional requirements that you are required to follow? 
* Consider what license you should use for your data based on your needs (more about this later).^1^

A little later in the course we will talk more about your data sharing and archiving options and how to select licenses for your data. If you have lots of questions, don’t worry. That’s completely normal.

Step 7: Reusing
--------------------
Data reuse means using data for other purposes than it was originally collected. Reuse of data is particularly important in science, as it allows different researchers to analyse and publish findings based on the same data independently of one another. Data that is well-described, curated and shared under clear terms and conditions is more likely to be reused. Integration with other data sources is also important, since that can enable new, yet unanticipated, uses for the data.

Data reuse is important because it allows researchers to:

* Obtain reference data for research.
* Run analyses to verify that reported findings are correct, making subsequent findings more robust. 
* Gain novel insights through metanalyses.^1^

If you are thinking about reusing data, here are a few things you should do or consider:

* Explore different sources for reusable data. A starting point can be to look for value added databases with curated content. Other possibilities include searching data deposition repositories for suitable datasets based on their annotation, or obtaining data directly from the author of a scientific article.
* Check under which terms and conditions the data is shared. Make sure that there is a licence, and that the licence gives you permission to do what you intend. If there is no license or reuse statement, you cannot reuse the data.
* Check whether there is sufficient supporting information to enable data reuse. Some types of data can be straightforward to reuse, while other may require extensive metadata to interpret and reuse.
* Assess the quality of the data. Evaluate if the data comes from a trusted source and if it adheres to discipline standards. 
* Verify that the data has been ethically collected and that your reuse of the data conforms with policies and regulations you are expected to follow. For personal (sensitive) data, there are usually legal and technical requirements that have to be met before data can be accessed. Getting access to personal (sensitive) data will therefore involve additional steps.
* If the data you are reusing has been updated, make sure to document which version of the data you are using. Also consider what impact the changes may have on your results.
* Cite the data properly by include a persistent identifier (such as a DOI) in the citation, if there is one.^1^

You should think about all of these things when you reuse data, but they should also be considered when you make decisions about sharing and archiving your own work. Remember to set your data up for success so it can go into the world and do great things!

![XKCD Effect Size](https://imgs.xkcd.com/comics/effect_size.png "[Effect Size by XKCD](https://xkcd.com/2755), [CC BY-NC 2.5](https://creativecommons.org/licenses/by-nc/2.5/legalcode0)")


## FAIR Data

The FAIR Principles were designed to support the sharing of research data. The intention of these principles is to improve the Findability, Accessibility, Interoperability and Reusability of data. 

At the heart of FAIR Science lies good data management practice. This is increasingly important as life science research becomes data-intensive and traditional ‘wet labs’ make space for ‘dry (computational) labs’.

The increasing volume, complexity and speed of data creation has made scientists rely on computational support exponentially. Therefore, the FAIR Principles place specific emphasis on enhancing the ability of machines to automatically find and use data, as well as supporting its reuse by other scientists, which facilitates knowledge discovery and improves research transparency^1^.

To learn a bit more about the FAIR principles, check out this clip from the University of Ghent. Then we will briefly summarize before moving onto the next section. Onwards! 

!?[Ghent University Data Stewards (2020) Knowledge Clip: FAIR data principles](https://youtu.be/2uZxFu9SFi8 "[Ghent University Data Stewards (2020) Knowledge Clip: Fair data](https://youtu.be/2uZxFu9SFi8), [CC BY](https://creativecommons.org/licenses/by/3.0/legalcode)") 

Findable 
--------------------

The first step in (re)using data is to find them. Metadata and data should be easy to find for both humans and computers. Machine-readable metadata are essential for automatic discovery of datasets and services, so this is an essential component of the FAIRification process.^2^ Data and their metadata should always be assigned a persistent unique identifier, like a DOI and this identifier should always be included in the metadata of an archived item. Data should also always be described by rich metadata that follows discipline specific standards whenever possible.  

Accessible
-------------------- 

For data to be accessible, how data can be acquired should be clear to others. This does not mean that everyone can access all archived data all the time. It simply means that who can access data and how it can be accessed is clear. All data the underlies a publication should be freely accessible unless there are legal or ethical reasons why it cannot be shared. Even if data are sensitive, there should be a clear protocol regarding how access can be requested. Furthermore, the metadata should always be open and accessible so that other researchers can find the data and estimate if it may be useful to them prior to requesting access. 

![FAIR Data Principles](https://www.ugent.be/img/doza/beleid/rdm/fair-data.png "[Image by Patrick Hochstenbach](https://www.ugent.be/img/doza/beleid/rdm/fair-data.png), [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)")


Interoperable
--------------------

When data is interoperable, it can be effectively combined with other datasets. This means that data is described in enough detail that other researchers will be able to assess the data’s quality and will be able to confidently combine it with other equally standardized datasets. File type is also an import part of interoperability. You may have the best organized and documented data in the world, but if it is stored in proprietary file type that no one else can open, it won’t be of much use. Because of this, you should always opt for non-proprietary file types whenever possible. 

Reuseable
--------------------

We discussed reusability a lot when we covered the research data life cycle, so we won’t belabor it here. In addition to making sure that your data is well documented and in an appropriate file format, a license should also be applied to your data or code that explains under what conditions your materials can be re-used. Remember that you should almost always assign a license. If no license is assigned, then the materials cannot be reused. We’ll talk more about picking an appropriate license a little later. 

If you are especially curious about how to make your data FAIR and about how FAIR data supports Open Science, you can check-out the [go-fair.org](https://www.go-fair.org/fair-principles/) website on the FAIR principles or read [Wilkinson et al.’s 2016](https://doi.org/10.1038/sdata.2016.18) paper on the FAIR principles and data stewardship. 

## Open Science 

Open Science is not a fixed concept with a single, universally accepted definition. It continues to evolve as research practices, technologies, policies, and community expectations change, and different disciplines and stakeholders often place emphasis on different aspects of it. Rather than viewing Open Science as a checklist to complete or a final goal to achieve, it is more useful to think of it as an approach to research and an ongoing process of continually improving how research is conducted, documented, shared, and reused.

To give a working definition we can build on, we would say that Open Science is the practice of making research as open as possible and as closed as necessary. It promotes transparent, reproducible, and collaborative research by sharing publications, data, software, methods, and other research outputs whenever this can be done responsibly. The goal is to improve the quality, efficiency, reproducibility, and impact of research for both the scientific community and society.

Achieving these goals, however, involves more than simply making research outputs openly available. Open Science also encourages us to critically examine the systems and practices that shape how research is conducted, evaluated, and rewarded. This includes developing new skills and competencies, adopting responsible research assessment practices, improving research data management and reproducibility, and fostering a research culture that values openness, collaboration, and transparency. In this way, Open Science is both a collection of practical research practices and an ongoing effort to improve the research ecosystem itself.

For most researchers, Open Science means planning from the beginning of a project how you will organize, document, preserve, and, where appropriate, share your research outputs so that they can be understood, verified, and reused by others. Much of the research conducted at public institutions and universities in Europe is supported by public funding, and Open Science encourages us to maximize the value of that investment by making research outputs available for others to build upon whenever this can be done responsibly.

This does not mean that every project needs to produce a breakthrough cancer treatment or a drought-resistant crop. More often, the value of Open Science lies in making incremental advances possible—allowing other researchers to understand your work, reproduce your methods, reuse your data, and build on your findings. Scientific progress is often achieved through many small contributions, and making those contributions easier to discover and reuse helps move research forward Something really exciting could be just around the corner.

In the following sections, we'll introduce some of the key principles, organizations, and initiatives that have shaped the Open Science movement. If you'd like to explore any of these topics in greater depth, we've also included suggestions for further reading.

The UNESCO Recommendations for Open Science^3^ 
--------------------

UNESCO stands for the United National Educational, Scientific, and and Cultural Organization, which is a specialized agency of the United Nations (UN). It's core areas of work include education, culture and cultural heritage, science, and communication. In 2021, UNESCO published the UNESCO Recommendation on Open Science, which provides an internationally agreed upon definition of Open Science as well as shard values and guiding principles that nations and organizations can use to promote inclusive, equitable, and sustainable systems of knowledge creation and dissemination. 

Overall, the recommendation is a high-level document that encourages signatory countries to:

* Promote a shared definition of Open Science and outline diverse paths to achieving it. 
* Develop an enabling policy environment for Open Science. 
* Invest in infrastructure and activities that contribute to Open Science. 
* Invest in training, education, digital literacy and capacity building to support Open Science. 
* Foster a culture of Open Science and align incentives to support it. 
* Promote innovative approaches for Open Science at all stages of the scientific process. 
* Encourage international and multi-stakeholder cooperation in the context of Open Science to reduce gaps in technology and knowledge.

Furthermore, it asks that changes be made inline with a set of values and guiding principles. As values, UNESCO has highlighted: 

* **Quality and integrity:** ensuring that science is high-quality and scrutinized by bringing together different sources of knowledge and making evaluation of scientific methods and outputs more transparent and accurate.
* **Collective benefit:** recognizing that science is a global public good that belongs to all of humanity.
* **Equity and fairness:** ensuring equitable, fair and reciprocal access to science for all producers and consumers of knowledge regardless of their location, nationality, race, age, gender, income, socio-economic circumstance, career stage, discipline, language, religion, disability, ethnicity, migratory status or any other grounds.
* **Diversity and inclusiveness:** embracing diversity of knowledge, practices, workflows, languages and research topics and outputs.

The guiding principles that are meant to help signatory countries uphold these values are: 

* **Transparency, scrutiny, critique, and reproducibility:** to reinforce the rigor of scientific results, enhance the positive impact of science on society and increase society’s ability to solve complex interconnected problems.
* **Equality of opportunities**: to ensure that all scientists and those with an interest in science have equal opportunity to access, contribute to and benefit from science, regardless of origin or circumstance.
* **Responsibility, respect, accountability:** to be responsible for and aware of public accountability, potential conflicts of interest, intellectual integrity and the possible social or ecological consequences of research activities.
* **Collaboration, participation, and inclusion:** to ensure that scientific collaborations transcend the boundaries of geography, language and resources, and include knowledge from marginalized communities to solve problems of great social importance.
* **Flexibility:** to acknowledge that there is no one-size-fits-all way to practice open science and to encourage different pathways to practicing it while upholding the core values.
* **Sustainability:** to be as efficient and impactful as possible by building on long-term practices, services, infrastructures and funding models to ensure participation of scientists from less-privileged countries or institutions.

Collectively, these principles and values apply to development and maintenance of Open Science infrastructures, both physical and virtual and the creation of Open Scientific knowledge in the form of scientific publications, open research data, open educational resources, open source software and code, and open hardware. They also guide how researchers interact with societal actors through things like citizen science, crowd sourcing, and crowd funding, or how they engage with other knowledge systems including local communities, marginalized scholars, and indigenous peoples. 

Taking into account that the needs and resources of each member state differ, the UNESCO Recommendation on Open Science does not provide a concrete roadmap for implementing Open Science globally, but it does inform Open Science policies and developments all over the world. If you would like to read the UNESCO Recommendation on Open Science, you can find it [HERE](https://doi.org/10.54677/MNMH8546). In the next section, we will discuss a set of Open Science policies shaping the Austrian scholarly landscape. 

Towards How: Open Science Policies 
--------------------

While, the EU’s Open Science agenda sets the overall direction, but most researchers are more likely to encounter it through the practical requirements attached to funding. Funders such as Horizon Europe (including the ERC and programs like the Marie Skłodowska-Curie Postdoctoral Fellowships) and the Austrian Science Fund (FWF) turn those broader policy goals into concrete expectations around Open Access, FAIR data, Data Management Plans, repositories, and responsible data sharing. The details are not exactly the same, but the overall direction is quite consistent, which means that learning good Open Science and RDM practices is useful across different funding contexts.

<u>Open Science in the European Union</u>

Building on the broad principles described in the UNESCO Recommendation, the European Union has made Open Science a central part of European research policy, particularly through the European Research Area (ERA). The ERA is the EU framework for creating a more integrated European research system in which researchers, knowledge, technologies, and research outputs can circulate more easily across countries, and Open Science is one of the areas being advanced through it. In practice, EU action works on several levels: it translates Open Science principles into expectations for researchers, most visibly through requirements and incentives attached to EU research funding, while also investing in the wider systems needed to make Open Science possible. A major example is the European Open Science Cloud (EOSC), a federated European environment intended to connect research data, services, tools, and infrastructures and make research outputs easier to find, access, combine, and reuse. EU Open Science policy therefore concerns not only what individual researchers are expected to do, but also the infrastructure, standards, skills, incentives, and coordination needed to support more open research across Europe.

<u>The Austrian Open Science Policy</u>

Austria’s 2022 Open Science Policy explicitly builds on European and international developments, including the European Research Area, Horizon Europe, FAIR data principles, and EOSC. It identifies priorities such as open access, FAIR research data, research assessment, scholarly communication, research integrity, Open Science skills, citizen science, and participation in EOSC. Importantly, it emphasizes that implementing Open Science requires coordinated action from government, funders, research institutions, libraries, infrastructures, and researchers.

For researchers, these national ambitions become most visible through funder and institutional policies. The Austrian policy calls for Data Management Plans to become standard, supports trusted repositories and FAIR data practices, promotes open access to publicly funded outputs, and recognizes that data management and sharing require resources. In practice, funder policies help translate these broader national goals into concrete expectations for research projects. To read the full policy, go to this [page](https://www.bmfwf.gv.at/wissenschaft/leitthemen/digitalisierung/open-science/open-science-policy-austria.html). The full policy can be found at the bottom in both German and English. 

<u>Funder Policies</u> 

The EU’s Open Science agenda sets the overall direction, but most researchers are more likely to encounter it through the practical requirements attached to funding. Funders such as Horizon Europe and the Austrian Science Fund (FWF) turn those broader policy goals into concrete expectations around Open Access, FAIR data, Data Management Plans, repositories, and responsible data sharing. The details are not exactly the same, but the overall direction is quite consistent, which means that learning good Open Science and RDM practices is useful across different funding contexts.

**Horizon Europe** 

Horizon Europe treats Open Science as part of normal project implementation. Funded projects are expected to manage research outputs responsibly, provide immediate Open Access to peer-reviewed publications, and manage research data according to the FAIR Principles. Applicants are also expected to explain in their proposal how appropriate Open Science practices will be used in the project.

In practice, researchers should:

* **Prepare and regularly update a Data Management Plan (DMP)** The DMP should describe how research data will be managed throughout the project.
Manage research data according to the FAIR Principles. Data generated by the project should be deposited in a trusted repository as soon as possible and according to the timeline established in the DMP. Some calls may additionally require use of a repository connected to EOSC.
* **Make research data “as open as possible, as closed as necessary”** Deposited data should normally be openly accessible under a licence such as CC BY or CC0, but access may be restricted where justified—for example because of legitimate commercial interests, legal obligations, confidentiality, or other constraints. Reasons for restricting access must be documented in the DMP.
* **Provide immediate Open Access to peer-reviewed publications** At publication, the published version or accepted manuscript must be deposited in a trusted repository and made immediately accessible, normally under a CC BY licence.
* **Make the materials needed to validate research findings available** Where relevant, repositories should also provide information about data, software, tools, or other research outputs necessary to validate publications or reuse deposited data.

A useful point to remember is that Horizon Europe does not simply require “open data.” It requires responsible FAIR data management and expects openness by default where possible, while explicitly allowing justified restrictions. To read more about Horizon Europe's open science requirements, this [page](https://rea.ec.europa.eu/open-science_en) is a great place to start, but many detailed guidelines can be found in the grant specific programme guide. 

**Österreichischer Wissenschaftsfonds (FWF)**

The Austrian Science Fund (FWF) translates Open Science principles into concrete requirements for funded research. For projects approved under the current framework, researchers are expected to plan for good research data management, provide open access to publications, and make the research data underlying publications openly available whenever possible.

In practice, researchers should:

* **Prepare a Data Management Plan (DMP)** A DMP is required for FWF-funded projects and must describe how data and metadata will be collected, organized, stored, shared, published, and archived. It should be treated as a living document and updated during the project.
* **Make peer-reviewed publications openly accessible** Publications arising wholly or partly from FWF funding must be available Open Access. This can be achieved through an eligible Open Access venue, certain transformative agreements, or immediate repository-based [Green Open Access](https://openaccess.univie.ac.at/en/oa-basics/). FWF generally requires a CC BY licence.
* **Share the data needed to support published results** Research data and metadata necessary to reproduce and verify a publication must be made openly available as soon as possible and no later than publication. If data cannot be shared for legal, ethical, or other legitimate reasons, this must be explained in the DMP.
* **Make shared data FAIR and reusable** Data should be deposited in an appropriate repository, have a persistent identifier such as a DOI, include suitable metadata, and normally use an open licence. FWF funding can also cover eligible costs associated with preparing, archiving, and providing access to research data.

The important distinction is that FWF does not require every piece of project data to be made public: open access is mandatory for the data underlying publications, while decisions about sharing other project data remain with the principal investigator and should be addressed in the DMP. If you would like to read more about the FWF's requirements regarding Open Science, you find the details [here](https://www.fwf.ac.at/en/about-us/what-we-do/open-science). 

<u>Policies Supporting Open Science at the University</u>

A Long Way to Go: The LERU Roadmap for Open Science 
--------------------

Policies and funder requirements tell us a lot about **what researchers are expected to do now**, but they do not necessarily show the full amount of work still needed to make Open Science routine and sustainable. One useful way of seeing that bigger picture is the **LERU Open Science Roadmap**. LERU is the League of European Research Universities, and its roadmap is only one interpretation of how Open Science should be implemented—but it is one we find especially useful because it looks beyond individual compliance and asks what universities themselves need to change, support, and invest in.

The roadmap organizes this work around **eight pillars**:

* **The future of scholarly publishing**: Moving toward publishing systems that are more open, accessible, sustainable, and supportive of wider access to research outputs.
* **FAIR data**: Ensuring that research data can be appropriately managed, documented, preserved, discovered, accessed, and reused.
* **The European Open Science Cloud (EOSC)**: Developing and connecting the infrastructure and services needed to support access to and reuse of research data across Europe.
* **Education and skills**: Giving researchers and research-support staff the knowledge and practical skills needed to work openly and manage research outputs effectively.
* **Rewards and incentives**: Ensuring that Open Science activities are recognized and valued in research careers rather than simply adding additional work without recognition.
* **Next-generation metrics**: Developing more responsible ways of assessing research and researchers that go beyond traditional publication counts and journal-based metrics.
* **Research integrity**: Supporting transparent, rigorous, and reproducible research practices as part of responsible research conduct.
* **Citizen science**: Creating opportunities for members of the public and other societal actors to participate meaningfully in research.

Taken together, these pillars give a fuller picture of the work involved in Open Science: **infrastructure, services, training, incentives, evaluation systems, policies, and cultural change all need attention**. This is an important distinction because current policies largely reflect the practices that have already become established enough to require; the roadmap also helps us see the areas where considerable institutional development and investment are still needed. If you would like to read more about the LERU Roadmap, you can read the original documentation [here](https://www.leru.org/publications/the-leru-roadmap-towards-open-access), but also find the [summary](https://www.ucl.ac.uk/library/open-science-research-support/open-science/8-pillars-open-science) from University College London to be great! 

## Why are we doing all of this? 
Why do we put so much emphasis on Research Data Management, FAIR data, and Open Science? There are many practical reasons, but two arguments sit at the center of this course. The first is public benefit. Research is rarely an entirely private activity, and this is especially true in Europe, where a large proportion of research is supported directly or indirectly through public funding. In that sense, researchers at public universities are, at least in part, acting as public servants: society invests in research because research is expected to produce knowledge that benefits more than the individual researcher or research group. Good RDM and FAIR and Open Science practices help make that investment go further by allowing research outputs to be discovered, understood, combined, and reused rather than disappearing when a project ends.

This matters because scientific progress is cumulative. New discoveries do not appear out of nowhere; they are built from previous observations, datasets, methods, software, and ideas. When those outputs are well documented and made available under appropriate conditions, other researchers can ask new questions of existing data, combine information across studies, develop new methods, and sometimes make discoveries that the original researchers never anticipated. Not every dataset is going to change the world, of course, and not every dataset can or should be completely open. But making research as open as possible and as closed as necessary increases the chances that the work we do can continue to produce value after the original project has finished.

The second argument is about transparency and reproducibility. Scientific claims are more trustworthy when others can understand how they were produced. That requires more than publishing the final numbers in a paper: researchers need adequate information about the data, methods, processing decisions, analyses, software, and other steps that led from observation to conclusion. Good RDM makes those processes easier to reconstruct, FAIR practices make the relevant materials easier to find and interpret, and Open Science encourages researchers to make those processes and outputs visible wherever doing so is responsible. Together, these practices make it easier to verify findings, identify mistakes, reproduce analyses, and build confidently on previous research.

There are also important ethical arguments for careful data management and responsible openness. Questions about research participants, privacy, consent, sensitive information, ownership, equity, and responsible data sharing can determine what should be shared, with whom, and under what conditions. We will return to those issues in a dedicated module on research ethics. For now, the key point is that RDM, FAIR, and Open Science are not simply administrative requirements or boxes to tick for a funder. They are part of the infrastructure that allows research to be trustworthy, reusable, and genuinely useful to the scientific community and to the public that supports it.

## Conclusion 
--------------------
That brings us to the end of this module. You should now have a clearer picture of what we mean by research data and metadata, how data move through the research data life cycle, and how RDM, FAIR, and Open Science fit together as part of responsible and reusable research. Before moving on, complete the knowledge check (up next) to make sure the key concepts are in place. Then, in Module 3: Data Organization, we’ll shift from the big picture to the practical details and look at how thoughtful file structures, naming conventions, and documentation can make your research easier to manage now—and much easier for you and others to understand later.

Before moving on to Module 3, take a few minutes to check your understanding of the key ideas from this module. The questions on the next page focus on the concepts you’ll keep using throughout the course, so use them as a chance to reinforce the big picture before we move into more practical data organization skills.

## Knowledge Check

**1. Which of the following best reflects the module’s definition of *research data*?**

[( )] Only the final dataset used to produce published figures and statistical results  
[( )] Any digital file created during a research project  
[(X)] Information created or used during research that supports or validates research activities, including data, documentation, software, code, and negative results  
[( )] Only data that will eventually be deposited in a public repository  

**********************************

**Explanation:** Research data includes much more than the final dataset used in a publication. It can include raw and processed data, measurements, interviews, software, code, contextual information, and even negative or inconclusive results. Not all of these materials will ultimately be shared publicly, but they still need to be managed appropriately.

**********************************

**2. A researcher downloads a dataset from a repository, converts several variables to a common coding system, removes records that do not meet the study criteria, and records each transformation in a script. Which stage of the research data life cycle does this primarily represent?**

[( )] Collecting  
[(X)] Processing  
[( )] Analysing  
[( )] Preserving  

**********************************

**Explanation:** **Processing** involves preparing data for analysis, including changing formats, harmonizing coding systems, filtering data, and performing quality-control steps. Documenting these transformations is particularly important because it allows others—and your future self—to understand how the analytical dataset was produced.

**********************************

**3. A research group deposits a sensitive dataset in a trusted repository. The data themselves can only be accessed following an application and approval process, but the dataset has an openly available metadata record explaining what it contains and how access can be requested. Which statement is most accurate?**

[( )] The dataset cannot be FAIR because FAIR data must be openly accessible  
[(X)] The dataset can still be FAIR because accessibility concerns having clear and appropriate conditions for access  
[( )] The dataset is FAIR only if the researchers eventually remove the access restrictions  
[( )] The dataset is Open Science, but it cannot satisfy the FAIR Principles  

**********************************

**Explanation:** **FAIR does not always mean open.** Under the Accessibility principle, it should be clear how data can be accessed and under what conditions. Sensitive data may therefore have legitimate access restrictions while remaining FAIR, particularly when the metadata remain findable and accessible and there is a clear procedure for requesting access.

**********************************

**4. Which researcher is most closely following the approach to Open Science described in this module?**

[( )] A researcher uploads every file from a project publicly because Open Science requires all research materials to be open  
[( )] A researcher waits until publication to decide whether any documentation or data management is necessary  
[(X)] A researcher plans how outputs will be organized, documented, preserved, and shared, while restricting access where legal, ethical, or other legitimate considerations require it  
[( )] A researcher publishes their articles Open Access but does not document or preserve the underlying research materials  

**********************************

**Explanation:** The module presents Open Science as making research **“as open as possible and as closed as necessary.”** It involves planning throughout the research process so that outputs can be understood, verified, preserved, and reused where appropriate. Openness is therefore not the same as releasing everything without restriction.

**********************************

**5. Why does the module introduce the LERU Open Science Roadmap after discussing EU, Austrian, and funder policies?**

[( )] Because LERU requirements replace Horizon Europe and FWF requirements at European universities  
[( )] Because it shows that Open Science has already been fully implemented across European research institutions  
[(X)] Because it illustrates the wider institutional changes and investments needed to make Open Science sustainable beyond the requirements currently placed on individual researchers  
[( )] Because its eight pillars provide a legally binding definition of Open Science for European researchers  

**********************************

**Explanation:** Funder and government policies show many of the Open Science practices that researchers are **already expected to follow**, but they do not capture everything required to transform the research system. The LERU roadmap highlights areas such as infrastructure, skills, research assessment, incentives, scholarly publishing, FAIR data, and citizen science, showing that institutions also need to invest resources and change systems and cultures.

**********************************

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
<!--
authors: Mathias Mayrgündter, Simone Spedicato 

email: mathias.mayrguendter@univie.ac.at, simone.spedicato@univie.ac.at    

version:  1.0

language: en

TODO
- review round

-->

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
<!--
authors: Lukas Kraiger, Simone Spedicato 

email: lukas.kraiger@univie.ac.at, simone.spedicato@univie.ac.at    

version:  1.0

language: en

-->

# Data Storage, Sharing, and Security
Welcome to the next module, where we will discuss storage and managing your research data - and what are considerations to keep in mind during your project!

Objectives
-------------------- 
Where is your data living right now—is it on a random USB drive on your desk, or just saved on your laptop's desktop?

Your research data is easily one of the most valuable things you will produce during your PhD, and losing it can mean losing months or even years of hard work. That is why planning where and how your data will live should actually begin before you start collecting it. Setting up a good storage routine early on keeps your files safe, makes collaborating with others easy, and saves you from late-night panic or panic in general.

By the end of this chapter, you will be able to:

1. Select the right storage solutions for your specific research data.
2. Explain the basic principles of secure data storage and backup.
3. Identify and use the storage services supported directly by the University of Vienna.

Introduction
-------------------- 
Where is your data living right now—is it on a random USB drive on your desk, or just saved on your laptop's desktop?

Your research data is easily one of the most valuable things you will produce during your PhD, and losing it can mean losing months or even years of hard work. That is why planning where and how your data will live should actually begin before you start collecting it. Setting up a good storage routine early on keeps your files safe, makes collaborating with others easy, and saves you from late-night panic or panic in general.

## Choosing Appropriate Storage

Not all research data is created equal. If your PhD consists mostly of text documents, your storage needs will look very different from someone generating terabytes of high-resolution images or genetic sequencing data.

While it is tempting to just use a personal Dropbox or buy an external hard drive, we strongly recommend using the university’s official storage services (managed by the ZID). Think of them as a secure, worry-free home for your research. By using them, you get:

* Automatic backups: If your laptop gets stolen or you spill coffee on it, your data is still safe and sound.
* Easy sharing: You can easily show your work to your supervisor or collaborators without sending massive email attachments.
* Safety and privacy: Your data is kept secure and complies with privacy laws, which is especially important if you are working with sensitive information.
* Tech support: If something goes wrong, there is an IT team ready to help you sort it out.

Here is a quick cheat sheet of the different storage options available to you at the University of Vienna:

University Storage Services
-------------------- 

|Service | Function | Storage Space | Collaboration Features|Cost|Availability|
| -----------|---------------|-------|---------|----------| -----------
|[Personal Online Storage Space](https://zid.univie.ac.at/en/online-storage-space/) | Personal file storage | 10 GB; Expandable with justification |None |Free|Immediate|
|[Share](https://zid.univie.ac.at/en/share/) | File storage and sharing; Managed through organizational unit| Unlimited |Between employees and students; Extended u:account available for guests  |EUR 0.03 per GB/year|Request Required|
|[u:cloud](https://zid.univie.ac.at/en/ucloud/) | Personal file storage and sharing| 100 GB  |Between employees and students; Extended u:account available for guests; Non-university users can edit files |Free|Immediate|
|[u:cloud pro](https://zid.univie.ac.at/en/ucloud-pro/)| File storage and sharing; For projects or teams| 250 GB; expandable with justification  |Between employees and students; Outside users can upload and download  |EUR 0.03 per GB/year|Request Required|
|[One Drive by Microsoft 365](https://zid.univie.ac.at/en/microsoft-365/)| File storage and sharing| 50 GB|Internal and external sharing; Non-university users can edit files|Comes together with MS365 license for university employees|Immediate|
|[Gitlab](https://zid.univie.ac.at/en/gitlab/)| Storing code; Version control| Unlimited; Code and supporting documentation|	Permissions and licensing options available|Free|Request Required|
|[Central Backup](https://zid.univie.ac.at/en/central-backup/)| For files not otherwised backed-up; Requires some user maintenance| Unlimited|None|Free|Request Required|

> **Tip:** If you are unsure which service best suits your project, contact the Research Data Management Support team before your project begins.

Backups and Data Preservation
-------------------- 

Even with the absolute best setup, things can still go wrong. Laptops get stolen, coffee gets spilled, hard drives crash, and sometimes you just accidentally hit "delete" on a file you actually needed. That is why having a solid backup routine is your ultimate safety net.

![XKCD Data Trap](https://imgs.xkcd.com/comics/backups.png " [Backups by XKCD](https://xkcd.com/1718/), [CC BY-NC 2.5](https://creativecommons.org/licenses/by-nc/2.5/legalcode0)")

The 3-2-1 Rule
-------------------- 

If your project doesn't involve highly sensitive data, the easiest way to keep your work safe is the 3-2-1 Rule:

* 3 copies: Keep your main working file and at least two backup copies.
* 2 different types of media: Save them on different devices (for example, your laptop’s hard drive and a university cloud service).
* 1 offsite location: Keep at least one copy in a different physical place (like storing it on the university network rather than on an external drive sitting right next to your laptop at home).

Many university storage services already include automated backups, but it is important to understand what is—and is not—being backed up.

Two Things to Keep in Mind:
-----------------

1. Test your backups (seriously!)

A backup is only helpful if it actually works. Every now and then, try restoring a few files from your backup just to make sure they open properly and nothing is corrupted. You don't want to find out your backup system has been failing for months on the day your laptop dies.

2. Hard drives don't live forever

USB sticks get lost, external hard drives crash, and even CDs degrade over time. No physical storage device lasts forever. This is another major perk of using the university's managed storage—their IT team constantly monitors the hardware and moves your data to new systems before the old ones fail.

## Data Security

Protecting research data is about more than preventing data loss. It also means ensuring that only authorised people can access the data and that information is handled in accordance with legal, ethical, and institutional requirements.

Good Security Practices
-------------------- 

Simple habits can significantly reduce the risk of data loss or unauthorised access:

- Use strong, unique passwords and, where available, enable multi-factor authentication.
- Keep your operating system and software up to date.
- Lock your computer when leaving your workspace (on Windows try Windows Key and L).
- Be cautious of [phishing emails](https://zid.univie.ac.at/it-security/ransomware#c6686) and suspicious links or attachments .
- Store research data on university-managed systems whenever possible.
- [Report suspected security incidents](https://servicedesk.univie.ac.at/plugins/servlet/desk/portal/10) promptly according to university procedures .

Security is not only a technical issue—it is also part of responsible research practice.

Working with Sensitive Data
-------------------- 

Some research projects involve sensitive data, such as:

- personal or identifiable information,
- health or medical data,
- genetic information,
- interview recordings,
- confidential commercial information,
- data protected by contractual agreements.

Sensitive data require additional protection.

Depending on the project, appropriate measures may include:

- encryption of storage devices,
- encrypted transfer of files,
- limiting access to authorised project members,
- minimising the number of copies,
- secure deletion when data are no longer required.


> **Important**
>
> Sensitive data require additional protection, and if your project involves sensitive information, contact the [Research Data Management Support Team](mailto:rdm@univie.ac.at) before data collection begins. They can help you identify suitable storage solutions and security measures for your project. Encryption may also be necessary in some cases, but it can introduce problems such as being unable to decrypt files later, so it should only be used when absolutely necessary and after careful consideration.

## Sharing Data During a Project

Research is rarely a solo sport. Whether you are collaborating with your supervisor, working with a lab mate, or teaming up with researchers on the other side of the world, you will need to share files.

But we’ve all been there: emailing files back and forth, ending up with confusing filenames like data_analysis_v2_final_corrected_FINAL.csv, and having no idea which version is actually the latest one.

Before you hit "share," take a quick second to ask yourself:

* Who actually needs to see this? (Does your whole team need access, or just one person?)
* What can they do with it? (Do they just need to read/view the data, or do they need to edit it?)
* How will we track changes? (If three people edit a file at the same time, will it create a mess?)
* Is any of it sensitive? (If yes, standard email or a Link without a password is a big no-no).

To keep things organized and secure, step away from email attachments and personal Dropboxes. Instead, use the university-supported tools built specifically for this:

Choosing the Right Tool
-------------------- 

Different collaboration tasks require different services.

| Purpose | Recommended service |
|----------|--------------------|
| Collaborative document editing | OneDrive, u:cloud |
| Team file storage | Share, u:cloud Pro |
| Source code and version control | GitHub, GitLab |
| Sending large files | ACONET FileSender |

For projects involving external collaborators, ensure that sharing arrangements comply with ethical approvals, funding requirements, and applicable legislation.With that said, most university services can accomodate users from outside the university. If you need help, just ask! Remember that not every dataset should be shared with every collaborator. Access should be limited to those who need it for their role in the project.


## Sharing Data Beyond the University

Collaborating with researchers outside your institution often involves sharing data or research materials. In some cases, formal agreements are required before this transfer can take place. Here, we briefly mention Data Transfer Agreements and Material Transfer Agreements, but they are covered more fully in the Legal and Ethics Module. 

Data Transfer Agreements (DTAs)
-------------------- 

A Data Transfer Agreement (DTA) defines the conditions under which data may be transferred between organisations.

A DTA typically specifies:

- which data will be shared,
- who may use the data,
- how the data may be used,
- responsibilities for protecting the data,
- conditions for storage and disposal.

DTAs help ensure that data sharing complies with legal, ethical, and contractual obligations.

Material Transfer Agreements (MTAs)
-------------------- 

A Material Transfer Agreement (MTA) serves a similar purpose but applies to **physical research materials**, such as:

- biological samples,
- microorganisms,
- cell lines,
- chemicals,
- laboratory reagents.

MTAs clarify how materials may be used, who owns resulting discoveries, and what happens to remaining materials after the collaboration.

Need advice?
-------------------- 
> If your project requires sharing data or research materials with another organisation, contact the appropriate university support office before any transfer takes place. THE RDM Team is always happy to answer your question directly, or direct you to the appropriate expert. 

## Planning for the End of Your Project

Research data often remain valuable long after a project has finished. Planning for the end of a project should therefore begin well before the final day of employment or study.

Before Leaving the University
--------------

University accounts, storage space, and access permissions cannot be guaranteed after you leave the University of Vienna.

Before leaving, consider:

- Where will the project data be stored?
- Who will remain responsible for the data?
- Have important datasets been archived appropriately?
- Can collaborators still access the files they require?
- Have any necessary transfer agreements been completed?

Planning ahead helps avoid interrupted access to important research data and ensures that ongoing projects can continue smoothly.

If data or research materials need to move to another institution, additional agreements—such as a Data Transfer Agreement (DTA) or Material Transfer Agreement (MTA)—may be required.

Discuss these questions with your supervisor/RDM Team/Legal Help Desk and complete any required offboarding procedures before your university account is closed. Normally you have quite some time but we all know what happens when life happens. In general you have 4 years to still access your data but after that all of your personal storage like your ucloud will be deleted and supervisors and collaborators are left with nothing. So it is advisable to safe your data somewhere central where they still have access. [More information](https://zid.univie.ac.at/uaccount-ablauf#c6401)

## Knowledge Check 

Test your understanding of data storage, security, and sharing.

**Question 1: The 3-2-1 Backup Rule**

According to the 3-2-1 backup rule, what is the safest way to keep your active research data safe?

[( )] Keep 3 copies of your data on 3 different USB sticks in your desk drawer.
[(X)] Keep 3 copies of your data, on 2 different types of media (e.g., your laptop and the cloud), with 1 copy stored in a different physical location.
[( )] Keep 1 copy on your laptop, but back it up once a year to a hard drive at your parents' house.

**Question 2: Handling Sensitive Data**

You are about to start a project that involves interviewing human participants. When is the best time to contact the Research Data Management (RDM) Support team?

[( )] Only at the very end of your PhD, when you are ready to delete the files.
[( )] Only if you accidentally lose the data and need someone to try and recover it.
[(X)] Before you start collecting any data, so they can help you set up secure storage and encryption from day one.

**Question 3: Sharing with Collaborators**

You need to work on a spreadsheet with a colleague from another university. What is the best way to collaborate without creating version chaos?

[( )] Emailing the file back and forth, adding your initials to the filename (e.g., `data_v2_final_JS.xlsx`).
[(X)] Using a university-supported sharing platform like u:cloud Pro or OneDrive instead of personal accounts or email.
[( )] Saving it to a personal, free Dropbox account because it is quicker than checking university options.
<!--
authors: Simone Spedicato, Michael Feichtinger 

email: simone.spedicato@univie.ac.at, michael.feichtinger@univie.ac.at    

version:  1.0

language: en

-->

# Archiving and Publishing
Welcome to Chapter 5, where we will discuss preserving data, what to preserve and which publication routes are out there. Enjoy!

Objectives
-------------------- 
Once your papers are written, you don’t want your hard-earned data to just gather dust on an old hard drive. In this section, we will cover how to publish your datasets online so other researchers can find, use, and cite your work—giving you extra academic credit and making your research part of the global open science community.

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

Once your data have been prepared, the next step is to deposit them in a **trusted repository**.

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

## Persistent Identifiers (PIDs)

Publishing data in a trusted repository is only part of making them FAIR. Research outputs should also receive **persistent identifiers (PIDs)**.

A PID is a permanent, globally unique identifier that continues to resolve to a digital resource even if its web address changes.

Persistent identifiers improve:

* findability;
* reliable citation;
* interoperability between research systems;
* long-term access to research outputs.

How to obtain a PID
----------------

The simplest and most common approach is to deposit your research outputs in a repository that automatically assigns persistent identifiers.

Some institutions also maintain local identifier systems, but these require long-term maintenance and governance. For most researchers, depositing data in a trusted public repository is therefore the preferred option.

ORCID
----------------

Researchers are strongly encouraged to obtain an **[ORCID](https://orcid.org/) iD**. ORCID provides a persistent identifier for researchers, making it easier to connect publications, datasets, software, grants, and other scholarly contributions across different systems.

Including your ORCID when depositing datasets improves attribution, discoverability, and recognition of your research contributions.

## Publishing and Sharing Research Data

Once your data have been prepared and a suitable repository has been selected, the final step is deciding **how** to make the data available. There are several routes for publishing research data, each with different advantages depending on the nature of the dataset and the goals of the project.

Publishing Routes
----------------

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

## Quiz

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
<!--
authors: Franziska Bauchinger, Simone Spedicato 

email: franziska.bauchinger@univie.ac.at, simone.spedicato@univie.ac.at    

version:  1.0

language: en

-->

# Data Reuse
Welcome to Chapter 6, where it's all about reusing the data, why that is important for different stakeholders and what to keep in mind when doing so. Have a nice read!

Objectives
-------------------- 
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

## How and where to find reusable data?
NOTE: do we want to add a recommendation concerning supplementaries? (aka: try to move away from that)

If you now come to the conclusion that, for your specific research question, reusing data would be beneficial,
what do you do? Where is reusable data stored and how can you find it?

How is data published?
-----------

Let's first have a look at how research data is published: 
Research data is generally published in an article appendix or supplement, a data journal, or a data respository.

Article appendix or supplement
------------

An article appendix or supplement (these terms are used interchangeably) is a separate, optional section of a research article that contains additional information.
Information you frequently find in an appendix are more detailed methods, additional figures or, of course, data.
Publishing the data corresponding to an article in its appendix is very common and you can usually download the supplementary material directly with the article on the publisher's website.
Take a look at this Nature article about the CRISPR-Cas system: https://doi.org/10.1038/s41586-026-10833-9. 
If you scroll all the way to the bottom of the article, you can see that the supplementary information contains additional figures and tables, as well as the exact source data that was used to create all figures.

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

Where can I find data?
------------

There are a couple of ways to look for published research data:

* In publications: Scopus (https://www.scopus.com/sources), Web of Science (), OpenAlex (https://openalex.org/), PubMed (https://pubmed.ncbi.nlm.nih.gov/)
* With google: Google Dataset Search (https://datasetsearch.research.google.com/)
* Use a meta search engine: B2FIND (https://b2find.eudat.eu/), OpenAIRE Explore (https://explore.openaire.eu/), Mendeley Data (https://data.mendeley.com/)
* Directly in the respositories - you can find repositories themselves on Re3Data (https://www.re3data.org/)

---

## Can I even reuse the data?

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
b<!--
authors: Lukas Kraiger, Emily Kate 

email: lukas.kraiger@univie.ac.at, emily.jean.kate@univie.ac.at    

version:  1.0

language: en

-->
# Ethical and Legal Aspects of RDM
Here's the deal. Issues related to research ethics and legal questions are a massive topic and we can't cover everything during this course. Frankly, we wouldn't be qualified to do that. What we want to do here is draw your attention to a few topics. By the end of this section, we hope you will have a developed a sense for when your project may involve legal or ethical issues, so that you can ask questions and get the help you need. 

Objectives
-------------------- 
1. Develop a sense for when your project involves legal or ethical issues that require consideration.

2. Know where you can find help with legal and ethical questions at UNIVIE.

Introduction
-------------------- 
In this module, we'll cover a lot of different topics. First, we'll briefly address Responsible Research and Innovation and Research Integrity, which provide a backbone for modern research ethics. Within that section, we'll also address the CARE principles. Next, we'll jump into some common legal legal issues within research. Not all of them will be relevant to your work, but it's likely that at least one topic will be related to something that interests you. We'll address data ownership, licensing data and outputs, working with imported samples, studies involving animals and humans, and relevant legal frameworks and agreements you might encounter. We'll also direct you towards people at the university who can help you with these issues. Let's get started! 

## Responsible Research and Innovation (RRI) and Research Integrity

Let’s talk about the difference between Responsible Research and Innovation (RRI) and Research Ethics. According to the European Union’s Horizon 2020 research program, RRI is defined as “an approach that anticipates and assesses potential implications and societal expectations with regard to research and innovation, with the aim to foster the design of inclusive and sustainable research and innovation” (European Commission, n.d.). There are two aspects of this definition worth focusing on for our purposes. First, RRI refers to “potential implications and societal expectations.” Second, it’s about “the design of inclusive and sustainable research”. These are two important aspects of the ethics of science: how does a project's design impact those who are participating that project and how could the outcomes of that project impact society, especially vulnerable communities, both human and biological. 

In contrast, Research Integrity refers to an “active adherence to the ethical principles and professional standards essential for the responsible practice of research” [(Korenman 2006)](https://ori.hhs.gov/education/products/ucla/default.htm). What this term brings into the discussion about research ethics are “professional standards” and “responsible practice”. Unlike in RRI, the question is no longer on the ethics of scientific output and its consequences, but on the ethics of how scientists conduct themselves. Research integrity, in a sense, captures the ethics of the work done “behind the scenes”, outside the view of the general public^3^.

RRI and research integrity are by no means entirely distinct, as they can overlap in important ways. However, three differences between the concepts are outlined below. 

First, we can see that who is most impacted by the ethical questions differs in each case. RRI can be understood as outward-looking and focused on public perception and impact. In contrast, research integrity refers to how research findings are produced — it is inward-looking. A common term to describe a lack of research integrity is “research misconduct”^3^, which can include things like data fabrication or plagiarism. 

Second, RRI and research integrity each refers to a different type of scientific interaction. On the one hand, RRI questions how scientists engage with research subjects, or the public. One (in)famous case in which there was no respect for data subjects was the Tuskagee experiments, wherein African-American men were recruited to study the development of untreated syphilis. Volunteers were falsely told they were receiving free treatment and the monitoring [(CDC 2021)](https://www.cdc.gov/tuskegee/timeline.htm). On the other hand, Research integrity can refer to how scientists engage with fellow researchers and their scientific community.^3^ 

Third, RRI and research integrity can also address how the scientific process is impacted by societal or institutional expectations and practices. Scientists are consistently tasked with communicating their findings to the public, and public interest in specific topics can increase or decrease through time. Projects that spark public interest tend to be more highly rewarded than projects that are important, but less eye-catching. At an institutional level, for example, we can begin to question how scientific achievements are rewarded and which kinds of approaches and outputs garner institutional support and prestige. 

These three factors discussed here are summarized in the table below. 

|Factor  | RRI | Research Integrity |
| -------- | -------- | -------- |
| Who is (most) impacted by ethical dilemas?     | Broader society    | The research community     |
| Who is interacting?     |Researchers working with the public or study participants     | Researchers working with other researchers    |
| What shapes research?    | Public expectations and perceptions    | Institutional policy and culture    |

Context Specific Ethics
-------------------- 
At times, generalized ethical principles in research aren't sufficient. They may not take into account the unique needs or vulnerabilities of specific communities. In other cases, they fail to take into account long histories that have created complex relationships between different communities or between communities and institutions. To address these shortcomings, specific guiding principles are sometimes adopted. One example is the CARE Principles.  

The **CARE Principles** for Indigenous Data Governance recognize that current movements towards FAIR and Open research fail to fully engage with the needs, rights, and interests of Indigenous communities. While the FAIR principles encourage a more generous and open scientific environment, they do not take into account power differentials and historic trajectories. Overall, the CARE Principles address the complex of social, political, and economic relationships that have existed between Indigenous Peoples, researchers, and the broader world. The four CARE principles are:

* **Collective Benefit:** Data ecosystems should be developed in a way that ensures Indigenous Peoples derive benefit from the data. 

* **Authority to Control:** Indigenous’ people’s rights and interests in Indigenous data should be recognized and they should be empowered to control how data is used. Indigenous Peoples should be able to establish how Indigenous lands, territories, resources, knowledge, geographical indicators, cultures, and bodies are represented and identified within data. 

* **Responsibility:** Researchers working with Indigenous data have a responsibility to understand and communicate how their work is used to support the self-determination and collective benefit of Indigenous communities. 

* **Ethics:** The rights and wellbeing of Indigenous Peoples should be at the forefront of all research practice. 

![GIDA Indigenous Peoples' Rights in Data](https://figshare.com/ndownloader/files/39449659/preview/39449659/preview.jpg "[GIDA Indigenous Peoples' Rights in Data](https://figshare.com/ndownloader/files/39449659/preview/39449659/preview.jpg), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)")

While, you might now work with Indigenous data, there could be other areas of your research where you touch upon complex power dynamics, problematic historic relationships, or unique vulnerabilities. When you encounter guidelines for these situations, listen first and then think critically about them. 

## Summarizing Thoughts on Research Ethics

Even if ethical and legal questions seem far removed from your everyday work, it is important to consider them—especially during the planning phase of a project. Ethical issues are not limited to research involving deception or obvious risks. They can also arise in seemingly harmless projects, for example through the way data are collected, stored, shared, or interpreted.

Try to consider your project from the perspective of the people, communities, or animals affected by it. If you were a research participant, would you feel adequately informed, respected, and protected? If your research uses existing data, have the people represented in those data been treated fairly, and are their privacy and rights adequately protected?

Researchers have a responsibility to minimise potential negative impacts of their work and to ensure that any risks are justified by the value of the research. This includes avoiding unnecessary physical, psychological, social, economic, or environmental harm. Where research involves animals, researchers must also carefully consider animal welfare and follow the relevant legal and ethical requirements.

Thinking about these questions early can help you identify potential concerns, adapt your research design where necessary, and seek advice before problems arise. At UNIVIE, we have an Ethics Committee, which provides reviews research projects conducted by researchers at UNIVIE. Keep in mind that the Ethics Committee cannot review projects that have already started or that have finished.  

Information about the Ethics Committee at UNIVIE can be found on their [website](https://ethikkommission.univie.ac.at/en/), which also includes contact information.

## Common Legal Issues in Research 
As mentioned above there are lots of legal issues that can arise in research. The goal of this section isn't to make you into a lawyer in the next 30 minutes. It's to equip you with compass that informs you when you should ask ask someone for help or be a bit careful in your next steps. In this section, well cover: 

* Licensing data, code, and outputs in research 
* Data ownership and intellectual property
* Working with animals 
* Working with imported samples 
* Working with humans 

One thing to remember as you read this section: Don't panic. We should take legal issues in research seriously, but there are very few problems that can't be solved. If there is something in your project or in a project you're working on that would possibly benefit from some advice and retooling, the important thing is to ask for help. It is highly unlikely that you'll tell any member of the RDM Team something that shocks them. 

Onwards...to licenses. 

Licensing Research Outputs 
-------------------- 
A license is a legal statement attached to your work. It explains what other people are allowed to do with it and which conditions they need to follow.

For example, a license can specify whether other people may:

* read, download, and share your work;
* copy or reuse your data, text, images, code, or other materials;
* adapt or build on your work;
* use your work for commercial purposes; and
* whether they have to name you as the original creator.

Without a license, it may be unclear whether other people are allowed to reuse your work. In many cases, your work is automatically protected by copyright as soon as you create it. This means that others generally need your permission before they can copy, share, or adapt it.

By choosing a license, you make your intentions clear. You can give others permission to use your work in specific ways without requiring them to ask you individually. For example, you may choose a license that allows people to share and adapt your work as long as they give you credit. Alternatively, you may choose a more restrictive license that allows sharing but does not permit commercial use or changes to the work.

**How do you assign a license?**
* Ensure that you are the owner of the output OR that you have been given the right to assign a license for the output. 
* Choose the license that fits how you want others to use your work and clearly attach it to the work, including the full license name and a link to the official license terms. No other steps are required to assign a license to something. 

**Can licenses be switched or changed?**
* Once something is released under a license, you generally cannot revoke those permissions or impose additional restrictions. 
* You can re-license work to remove previous limitations, but there is a preference for not modifying licenses once they have been assigned.

**Can licenses be modified?**
* You should not modify license terms yourself.
* Licenses are carefully written legal documents and changing them can make them unclear or invalid.

Not all licenses can be applied to every type of output. For example, different licenses are applied to written work and raw data than software and complex analytical code. Below, we provide a non-exhaustive list of licenses that are commonly used for different outputs. The two newest classes of licenses we mention are options for open hardware and for AI models. If you are licensing open hardware or an machine learning model, you do not need to use a specialized license, but they are available. Open hardware can also be licensed using the Creative Commons licenses and open software licenses are still frequently used for machine learning models.  

If you want help selecting a license, you can always ask a member of the RDM Team, but there are online tools that can be useful. For picking a license for non-code based outputs, try the [Creative Commons License Chooser](https://creativecommons.org/chooser/). You can try the [Open Source License Chooser](https://choosealicense.com/) for code and software. 

If, for any reason, the available licenses are not suitable for your situation, ask for advice before assigning a license to your work. We strongly advise against using a license to solve a problem it was not designed to address. For example, if your data or outputs should only be used for research purposes due to ethical concerns, simply assigning a non-commercial license won't really solve the problem. When in doubt, ask the [RDM Team](mailto:rdm@univie.ac.at) or your data steward for help! 

Frequently Used Licenses: Data
-------------------- 

**[Creative Commons](https://creativecommons.org/cc-licenses/):** 
* CC 0: Public Domain
* CC BY: Attribution
Credit must be given to the author
* CC NC: Non-Commercial
May not be used for commercial purposes
* CC ND: Non-Derivatives
May not be modified
* CC SA: Share Alike
Redistribution under the same licensing terms


**[Open Data Commons](https://opendatacommons.org):**
* Open Data Commons Open Database License
* Open Data Commons Attribution License
* Open Data Commons Public Domain Dedication and License
  
Frequently used licenses: Code
-------------------- 
* [MIT](https://mit-license.org/)
* [GNU General Public Licenses (GPL) and variations](https://www.gnu.org/licenses/licenses.en.html)
* [Apache](https://www.apache.org/licenses/)
* [Mozilla (MPL)](https://www.mozilla.org/en-US/MPL/)

Frequently used licenses: Open Hardware 
-------------------- 
* [CERN Open Hardware Licenses](https://cern-ohl.web.cern.ch/) 
* [TAPR Open Hardware Licenses](https://tapr.org/the-tapr-open-hardware-license/)

Frequently used licenses: Machine Learning Models
-------------------- 
* [OpenRAIL Licenses](https://www.licenses.ai/)


That's everything we have to say about licenses for now. In the next sections, we'll cover some considerations for working with intellectual property considerations, animals, imported samples, and other humans! 

### Data Ownership and Intellectual Property
Who actually owns the data and other research outputs you create?
It's easy to assume that because you collected the data, wrote the code, or developed the research methods, everything you produce belongs to you. However, the legal situation is often more complicated! Depending on your employment status, funding arrangements, and agreements with collaborators, different people or organizations may have rights to your research outputs.

Understanding these rights is particularly important when you want to publish, share, archive, or reuse your research data. Let's look at a few common situations you might encounter during your research career.

Who Owns Your Research Data?
-------------------- 
Research data ownership is a surprisingly complicated topic. In fact, under Austrian law, data themselves are not necessarily something that can be owned in the traditional legal sense. Instead, different rights and obligations may apply depending on the type of data, how they were created, and the agreements governing their use.

For example, copyright, database rights, employment contracts, confidentiality agreements, and data protection regulations may all influence what you are allowed to do with your research outputs.

**If you are employed by the University of Vienna, the university generally has extensive rights to research outputs created as part of your employment.** However, the exact situation depends on the type of output, applicable legislation, and your contractual arrangements. This does not necessarily mean that the university owns every piece of data or intellectual property you create.

Importantly, the **University of Vienna's [Research Data Management Policy](rdm.univie.ac.at/rdm-policy-and-faq/) explicitly gives university staff the right to publish their research data in repositories under open licenses or licenses for scientific use, provided that no legal, contractual, ethical, or other applicable restrictions prevent it.**

This means that even though the university may hold rights to the research outputs you create during your employment, you are generally permitted to make your research data openly available when the necessary conditions are met.

What does this mean for you? Before publishing or sharing research data, make sure you understand whether you have the necessary rights to do so. If you're unsure, talk with your supervisor or contact the appropriate university support services.

Copyright, Patents, and Intellectual Property
-------------------- 
You have probably encountered copyright when reading scientific publications or using images in presentations, but intellectual property (IP) can also play an important role in research data management.

Different types of research outputs may receive different forms of legal protection.
Copyright protects original creative or intellectual expressions, rather than the underlying facts or ideas. In a research context, copyright may protect things such as scientific articles, original figures and illustrations, software code, and certain databases or documentation.

However, not everything you produce as a researcher is protected by copyright! Individual measurements, factual observations, numerical values, and scientific discoveries generally do not receive copyright protection simply because someone collected or discovered them.

For example, imagine that you measure the heights of 500 plants during an experiment. The individual measurements are facts and generally are not protected by copyright. However, an original illustration explaining your experimental setup, the software you wrote to analyze the measurements, or an original written description of your methodology may be protected.

There are also other forms of intellectual property protection worth knowing about:
* **Database rights:** In the EU, certain databases may receive special legal protection when substantial investment has been made in obtaining, verifying, or presenting their contents.
* **Patents:** Some inventions and technical innovations developed during research may qualify for patent protection. If you think your research could lead to a patentable invention, seek advice before publicly disclosing it, as publication can affect patentability.
* **Trade secrets** Confidential research information, methods, or technical knowledge may be protected as trade secrets when the relevant legal conditions are met.
Keep in mind that being named as an author or creator does not necessarily mean that you control all the legal rights to an output. This is especially relevant when working with collaborators, external funding, or materials provided by another institution.

Privately Funded Research and Contractual Restrictions
-------------------- 
If your research project is supported by private funding, such as funding from a company or another external organization, make sure you carefully read any legal documentation provided at the beginning of your project.

Private funding agreements may include conditions about who can access the data, who holds intellectual property rights, whether research results can be published, and whether the data can be shared with other researchers.

Even if you are not personally responsible for negotiating these agreements, it's a good idea to talk with your supervisor about any private funding supporting your research. Your supervisor may have signed agreements that affect what you are allowed to do with the data you collect or create.

Some useful questions to ask include:
* Who has the legal rights to the research data and other outputs?
* Are there restrictions on publishing or sharing the results?
* Does the funder have the right to review publications before they are submitted?
* Can the data be deposited in a repository or made available under an open license?
* Are there confidentiality requirements or restrictions on future reuse?

These questions are particularly important if you intend to publish an open dataset, release software, or reuse research materials in a future project.

Data Transfer Agreements (DTAs)
-------------------- 
Just as physical research materials may be subject to MTAs, research data may be subject to Data Transfer Agreements (DTAs) or similar data-sharing agreements.

A DTA establishes the conditions under which data can be transferred between organizations or research partners. These agreements are particularly important when working with confidential, sensitive, commercially valuable, or personal data.
For example, imagine that a research group at another university agrees to share a dataset containing pseudonymized participant information. A DTA might specify who is allowed to access the data, what research purposes are permitted, which security measures must be followed, and whether the data can be shared with additional collaborators.

Depending on the circumstances, DTAs may also address data retention, deletion, publication, and future reuse. When personal data are involved, additional agreements or safeguards may be required under the GDPR. An important point to remember is that receiving a dataset does not automatically give you permission to use it for any purpose you choose. Always check whether restrictions apply, particularly before sharing the data with others or using them for a new research question.

If your project involves transferring data or materials between institutions, consult your supervisor and the relevant university support services before making arrangements.

Material Transfer Agreements (MTAs)
-------------------- 
If your research involves receiving or sending physical research materials, you may encounter a Material Transfer Agreement (MTA).

An MTA is a legal agreement that establishes the conditions under which research materials can be transferred between organizations. These agreements are particularly common when working with biological samples, cell lines, microorganisms, chemical compounds, or other specialized research materials.

For example, imagine that a collaborator at another university sends you a collection of bacterial strains to use in your research. An MTA might specify that you can use the strains for a particular research project but cannot distribute them to other researchers without permission.

MTAs may address questions such as who can use the materials, whether they can be transferred to third parties, what happens to any inventions or discoveries resulting from their use, and whether the materials must be returned or destroyed at the end of the project.

Before sending or receiving research materials, check whether an MTA is required. Don't assume that materials can be freely shared simply because they are being exchanged between academic researchers.

Where Can You Get Help?
--------------------
At the University of Vienna, Research Services can provide guidance on research contracts, intellectual property, and legal questions related to external funding. If you're unsure about the conditions attached to your project, it's much better to ask early than to discover restrictions when you're preparing to publish!

Depending on the topic, there are different teams at UNIVIE that you can contact, but don't worry too much about finding the right person. We regularly communicate with one another and transfer questions between units. 

For questions about patents, industry partnerships, and material transfer agreements, contact the [Technology Transfer Office](https://forschungsservice.univie.ac.at/en/impact-innovation/technology-transfer-industry). For other questions, you can reach out to the [RDM Team](mailto:rdm@univie.ac.at). 

### Working with Animals 
If your research project involves living animals, you may need special approval to begin your work. This is especially true if you plan to work with vertebrates or cephalopods. Different levels of permission are required for different types of projects. If your project is considered physically invasive, or causes significant psychological stress, your approval process will probably be more complex. If you are part of the Faculty of Life Sciences and are considering working with animals as part of your research project, you should contact **Herbert Gasser** (herbert.gasser@univie.ac.at) in the Dean’s Office. He can help you determine what permissions you will need and can give advice on how to proceed. If you work at another faculty that is conducting animal research and you have questions contacting the animal facility in your faculty is a great place to start! 

Ethics aside, keep in mind that many journals will ask to see a record of your permits or ethics board approvals before they will agree to publish you research, so be sure to ask questions early and to save important documentation. 

![Raptor Fences by XKCD](https://imgs.xkcd.com/comics/raptor_fences.png "[Raptor Fences by XKCD](https://xkcd.com/758), [CC BY-NC 2.5](https://creativecommons.org/licenses/by-nc/2.5/)")

### Working with Imported Samples
Even samples not derived from living humans that have been imported from abroad can carry restrictions and requirements. Plant and animal material, soil and water samples, and archaeological remains can all be subject to export and import regulations. Requirements vary considerably depending on the material type and origin location, but we mention a few considerations below. 

International Transport of Samples
-------------------- 
Depending on the types of samples you are working with and where they come from, you may need special permits or inspections before samples can leave their country of origin or enter Austria. You may also need permits to collect the samples in the first place. Legal requirements can vary significantly between countries, even those that are geographically or culturally close to one another.

Make sure to investigate these requirements early in the planning phase of your project to avoid surprises later! It's always a good idea to ask your supervisor and collaborators questions about where your samples came from, how they were collected, and what permits or permissions are already in place (or may still be needed). Don't assume that all the necessary paperwork has already been taken care of, especially if you are working with samples collected by someone else. In some regions, obtaining the necessary permits can be a challenging and time-consuming process, so give yourself plenty of time and consider reaching out to other researchers who have worked with similar materials from the same countries. They may have valuable advice to share.

Finally, keep in mind that many journals ask to see import and/or export permits before publishing research, just as they may request documentation for research involving animals. Be sure to follow all relevant regulations and keep copies of your permits and other important documentation so you have them when you need them. 

The Nagoya Protocol
-------------------- 
The Nagoya Protocol on Access to Genetic Resources and the Fair and Equitable Sharing of Benefits Arising from their Utilization (often simply called the Nagoya Protocol) is an international agreement that came into force on October 12, 2014. Its goal is to ensure that genetic resources and their derivatives (such as metabolites, lipids, and enzymes) are accessed under fair conditions and that the benefits arising from their use are shared equitably with the country providing them. These benefits can include commercial outcomes, but also non-commercial benefits, such as sharing research results, knowledge, or expertise.

Importantly, the Nagoya Protocol is relevant to both commercial and non-commercial research, including basic and applied research. However, whether specific research activities are subject to access and benefit-sharing requirements depends on factors such as the type of material, its country of origin, when it was accessed, and the applicable national legislation.

If you plan to work with genetic resources, it's a good idea to investigate potential Nagoya Protocol requirements early in your project planning. Talk to your supervisor and collaborators about where your samples came from, when and how they were obtained, and whether any permits or agreements are already in place. Depending on the circumstances, you may need to obtain prior informed consent and establish mutually agreed terms with the provider country before beginning your research. Researchers working in the EU may also be required to submit due diligence declarations documenting their compliance. Don't assume that samples are automatically exempt simply because they were provided by a collaborator or are being used for non-commercial research. Taking the time to clarify these questions early can help you avoid complications later in your project.

Documentation is an important part of Nagoya Protocol compliance! Under EU regulations, researchers must retain relevant documentation for 20 years after the end of the period of utilization of the genetic resources. A great way to manage this documentation for your lab is to set up a private collection in PHAIDRA, the University of Vienna's long-term digital repository. This allows your lab to keep permits, agreements, and other important records together in a secure, organized location where they can be accessed when needed. The RDM Team can help you set up a private PHAIDRA collection and develop a practical approach to organizing and preserving your documentation.

For legal support with NP you can contact [Sofiia Myklush](mailto:sofiia.myklush@univie.ac.at) at the UNIVIE [Technology Transfer Office](https://forschungsservice.univie.ac.at/transfer).

### Working with Humans and the General Data Protection Regulation (GDPR)
If your research project involves collecting, storing, analyzing, or otherwise processing information about living people, you will likely need to consider the General Data Protection Regulation (GDPR). The GDPR is an EU regulation that has applied since May 2018 and establishes rules for how personal data must be handled. It defines the rights of individuals whose data are processed, the responsibilities of those working with personal data, and the measures organizations must take to protect that information. Violations can result in significant penalties, so it's important to understand your responsibilities and plan for data protection from the beginning of your project.

Personal data includes any information relating to an identified or identifiable living person. This includes information about your research participants, but it can also include information about your colleagues, collaborators, and other members of your project team. Some types of personal data receive additional protection under the GDPR. These are known as special categories of personal data and include information revealing racial or ethnic origin, political opinions, religious or philosophical beliefs, and trade union membership, as well as genetic data, biometric data used for identification, health data, and information concerning a person's sex life or sexual orientation. Keep in mind that even information that does not directly identify someone, such as a dataset in which names have been replaced with participant codes, may still qualify as personal data under the GDPR.

If your research involves personal data, talk with your supervisor early in the planning phase of your project about what information you intend to collect, how it will be used, and what measures are needed to protect it. One important distinction to keep in mind is that consent to participate in a research study and consent to process personal data under the GDPR are not necessarily the same thing. While informed consent is often an important part of ethical research, it is not the only possible legal basis for processing personal data under the GDPR. Depending on the circumstances, research institutions may rely on other legal bases. This means that obtaining a participant's agreement to take part in your study does not automatically fulfill all your GDPR obligations.

Depending on your research, it may also be advisable or necessary to consult the [UNIVIE Ethics Committee](https://www.qs.univie.ac.at/en/services/ethics-committee/) or the [Data Protection Officer (DPO)](https://dsba.univie.ac.at/). Also remember that all projects and tools processing personal data must be entered in the UNIVIE [Verarbeitungsverzeichnis](https://wiki.univie.ac.at/spaces/POL/pages/171480014/Record+of+processing+activities) If you're unsure where to start or who to contact, your faculty data steward or the UNIVIE [RDM Team](mailto:rdm@univie.ac.at) can help you find the right resources and connect you with the appropriate experts.

Below, we cover a few more issues that are common when working with human partipants.

Consent Forms, Study Information, and Debriefing
-------------------- 
When your research involves human participants, you will often need to obtain their informed consent before collecting data. Informed consent means that participants receive clear, understandable information about the study, including what they will be asked to do, how their data will be used, and any potential risks or benefits. They should also have the opportunity to ask questions and make a voluntary, informed decision about whether they would like to participate.

Informed consent is more than just signing a form! It is an ongoing process that begins before the study and continues throughout a participant's involvement. Participants should feel comfortable asking questions, understand their options for withdrawing from the study, and be treated respectfully throughout the research process. Depending on the nature of the study, researchers may also need to provide a debriefing afterward, particularly if some information about the study was intentionally withheld to avoid influencing participants' behavior.

When preparing your consent forms and participant information sheets, think beyond the immediate needs of your study. Consider how the data might be stored, shared, archived, or reused in the future. For example, will you want to share anonymized data with other researchers, deposit a dataset in a repository, or make your data available for future research projects? These possibilities should be considered from the beginning and clearly communicated to participants where relevant. Planning ahead can help ensure that your consent materials support both your current research and potential future data sharing and reuse.

We strongly recommend having your consent forms and participant information sheets reviewed by a member of the UNIVIE [RDM Team](mailto:rdm@univie.ac.at) or the [Data Protection Officer (DPO)](https://dsba.univie.ac.at/) before you begin using them. They can help you identify potential issues, clarify data protection requirements, and ensure that your documentation appropriately addresses data management, sharing, and reuse. It's much easier to make adjustments before data collection begins than to discover later that your consent materials limit what you can do with your research data!

Finally, keep in mind that informed consent to participate in research is not necessarily the same as consent to process personal data under the GDPR. These serve different purposes, and obtaining informed consent does not automatically fulfill your data protection obligations. If you're unsure what types of consent or documentation your study requires, talk with your supervisor early in the planning process.

In the next sections, we'll take a closer look at providing study information, collecting consent, and debriefing participants. 

Providing Study Information
-------------------- 
Before deciding whether to take part in a study, participants should receive a clear **participant information sheet** or study information page that explains what participation will involve. This information should be written in language that your intended participants can easily understand, avoiding unnecessary technical terms or complicated explanations. Remember that your participants may not have the same scientific background as you do!

Your participant information sheet should generally include:
* Purpose of the study: What is the research about, and what are you hoping to learn?
* Research team and funding: Who is conducting the research, which institution is responsible, and who is funding the study?
* Contact information: How can participants contact the researchers with questions or concerns?
* What participation involves: What will participants be asked to do (e.g., complete a survey, participate in an interview, or be recorded), and how long will it take?
* Data collection and management: What types of data will be collected, and how will they be stored, protected, and used?
* Data sharing and reuse: Will the data be shared with other researchers, deposited in a repository, or potentially reused for future research? If so, under what conditions?
* Privacy and confidentiality: Will participants be anonymous, pseudonymised, or identifiable? Who will have access to their information?
* Risks and benefits: Are there any potential risks, discomforts, or benefits associated with participation?
* Compensation: Will participants receive payment, compensation, or reimbursement for their time or expenses?
* Voluntary participation and withdrawal: Make it clear that participation is voluntary, explain how participants can withdraw, and describe any limitations on withdrawing their data once they have been collected or anonymized.

Depending on the study and the applicable data protection requirements, you may also need to provide additional information, such as the legal basis for processing personal data, how long the data will be retained, and participants' rights under the GDPR.
Give participants enough time to read and consider this information before asking them to consent. They should also have an opportunity to ask questions and receive clear answers. The goal isn't simply to provide a document that checks all the necessary boxes, but to help participants make a genuinely informed decision about taking part in your research

Documenting Consent
-------------------- 
A **consent form** documents a participant's agreement to take part in a research study after receiving information about what participation involves. In many studies, participants provide their consent by signing a paper form. In online research, consent may be collected electronically, for example, by asking participants to actively agree to a consent statement before proceeding with a survey or other research activity.

Keep in mind that a written signature isn't always necessary or even the best option! For example, when researching sensitive topics, collecting signatures may create an unnecessary link between a participant's identity and their responses. Depending on your research design, participants, and the types of data being collected, other methods of documenting consent may be more appropriate. The important thing is that participants can make an informed, voluntary decision and that you have an appropriate way to document their agreement.

Participants should also understand that they can withdraw from a study without facing negative consequences. However, withdrawing from participation and requesting the removal of previously collected data are not always the same thing. For example, once data have been fully anonymized or incorporated into aggregated results, it may no longer be possible to identify and remove an individual participant's contributions. Any limitations on withdrawing data should be clearly explained before participants agree to take part. Again, if you're unsure how best to collect and document consent, talk with your supervisor and consider consulting the UNIVIE RDM Team or the Data Protection Officer (DPO). 

Debriefing Participants
-------------------- 
After participating, people should usually receive a **debriefing**. A debriefing provides information about what happened in the study and gives participants an opportunity to ask questions or raise concerns.

A debriefing may include:

* a reminder of the study’s purpose;
* further information that was not provided before the study;
* an explanation of any unusual procedures;
* contact details for the research team; and
* information about relevant support services, particularly if the study addressed sensitive or potentially distressing topics.

Debriefing is especially important when the study involves deception or does not disclose its full purpose in advance. In such cases, researchers should explain why this was necessary, provide the missing information as soon as possible, and give participants the option to withdraw their data where feasible.

Research involving children, people with limited capacity to consent, sensitive personal data, health information, or potentially vulnerable groups may be subject to additional ethical and legal requirements. If you are unsure about the information, consent, or debriefing requirements for your project, it's always best to ask for help! 

## Hidden Personal Data: When GDPR Applies Without Names
Personal data are not limited to obvious identifiers such as names, email addresses, or phone numbers. They can also include information such as photographs, location data, identification numbers, or details about a person's health, education, or employment. Under the GDPR, data count as personal data whenever they relate to an identified or identifiable living person.

This means that a dataset can still contain personal data even when names have been removed. If someone could reasonably identify a participant by combining the dataset with other available information, GDPR requirements may still apply.

Importantly, you may process personal data even if your research does not directly involve studying people. For example, a researcher studying the behavior or health of domestic dogs might collect the names and contact information of dog owners to arrange observations, conduct interviews, or share research results. Although the dogs are the subjects of the study, the information collected about their owners is still personal data.

For this reason, researchers in all disciplines should consider whether they collect, store, or otherwise process information about identifiable people, even when human participants are not the focus of their research.

Indirect Identifiers
-------------------- 

Indirect identifiers may identify a person when combined with other data. Examples include:

* age or date of birth;
* occupation, employer, or place of study;
* location or GPS data;
* dates of events;
* rare medical conditions or characteristics;
* detailed demographic information;
* photographs, voice recordings, or video; and
* IP addresses, device IDs, or online usernames.

For example, “the only 58-year-old cardiologist working at a particular hospital” may identify a person even without their name.

Personal data can also be hidden in:

* free-text survey responses, interview transcripts, and field notes;
* document metadata, comments, tracked changes, and file author information;
* photographs containing faces, name badges, addresses, or vehicle number plates;
* audio recordings containing identifiable voices;
* maps and detailed location data; and
* quotations from online platforms that can be searched and traced back to a user.

Pseudonymised Is Not Anonymous
-------------------- 

Replacing names with participant codes, such as `P001`, is called **pseudonymisation**. It is a useful protective measure, but pseudonymised data remain personal data under the GDPR if a key exists or participants can otherwise be reidentified.

Data are only **anonymous** when individuals can no longer be identified by reasonably likely means. Removing names alone is usually not enough, especially in small datasets or datasets containing detailed qualitative, geographic, health, genetic, or demographic information.

> If you, your team, or another person could realistically work out who a participant is, treat the data as personal data.

Public Data Are Not Automatically Free to Use
-------------------- 

Information posted publicly online may still be personal data. Collecting, storing, analysing, or sharing identifiable social-media posts, profile information, images, or online discussions can be subject to the GDPR, platform terms of use, and ethical requirements.

Be particularly careful when publishing direct quotations: readers may be able to search a quotation online and identify the author.

Before You Share Data
-------------------- 

Before sharing, publishing, or depositing data in a repository, check for hidden identifiers in the dataset and related materials, including file names, metadata, hidden spreadsheet columns, transcripts, images, recordings, codebooks, and README files.

Possible risk-reduction measures include:

* collecting only data necessary for the project;
* separating contact details and consent forms from research data;
* using participant codes and securely storing the reidentification key;
* generalising or removing detailed dates, locations, and rare characteristics;
* removing document metadata and tracked changes;
* limiting access to identifiable data; and
* using controlled-access sharing rather than open publication where needed.

If you are unsure whether your data are anonymous, assume that they are personal data and ask for advice. Contact the UNIVIE [Data Protection Officer (DPO)](https://dsba.univie.ac.at/), your faculty data steward, or the UNIVIE [RDM Team](mailto:rdm@univie.ac.at).


## Other EU Digital Regulations: Data Act, AI Act, Digital Services Act and more
The GDPR is not the only EU regulation that may affect your research. In recent years, the EU has adopted a series of laws that regulate data, digital services, and artificial intelligence. Most of them are not aimed at researchers specifically, but they can still apply when you collect, share, or analyze data, or when you use or develop digital tools. You do not need to become a legal expert, but you should know that these rules exist and when to ask for advice. Note that these regulations are being phased in over several years and some details are still evolving, so always check the current status with the RDM Team or the respective Website.

EU AI Act (Regulation (EU) 2024/1689
-------------------- 
The AI Act regulates the development and use of artificial intelligence systems based on their level of risk. Some practices are prohibited, high-risk systems (for example in education, employment, or law enforcement) face strict requirements, and certain systems (such as chatbots and AI-generated content) must be transparent about their use of AI. AI systems developed and used *solely for scientific research and development* are generally exempt from the Act. However, this exemption does not cover testing in real-world conditions, and the rules apply once a system is put on the market or into service. In practice, this means:
* If you develop AI models, document your training data, methods, and model versions carefully. This is good RDM practice and makes it easier to meet any requirements later.
* If you use third-party AI tools, check their terms of use, especially regarding the data you upload. Do not enter personal, confidential, or unpublished data into tools without checking how that data is stored and reused.
* Training data containing personal data still falls under the GDPR, and copyrighted material may be subject to copyright rules.
* If your results may be turned into a product or service, ask early whether the AI Act will apply.

Data Act (Regulation (EU) 2023/2854)
-------------------- 
The Data Act sets rules on who can access and use data generated by connected products (such as smart devices and sensors) and related services. It gives users of such products rights to access the data they generate and to share it with third parties. If your research uses data from connected devices, for example wearables, IoT sensors, or vehicles, the Data Act may affect how you can obtain and reuse these data. It also contains rules on data sharing contracts and on switching between cloud providers.

Data Governance Act (Regulation (EU) 2022/868)
-------------------- 
The Data Governance Act creates structures that make it easier to reuse certain protected public-sector data (for example data subject to confidentiality or third-party rights), and supports trusted data intermediaries and *data altruism*, where people or organizations voluntarily make data available for the common good. Researchers may benefit from these mechanisms when requesting access to protected public-sector data.

European Health Data Space (EHDS, Regulation (EU) 2025/327)
-------------------- 
The EHDS establishes common rules for the use of electronic health data in the EU. It covers both the use of health data for care (primary use) and for purposes such as research, innovation, and policy-making (secondary use). If you work with health data, expect access to such data to increasingly go through designated health data access bodies, in addition to GDPR requirements.

Digital Services Act (DSA, Regulation (EU) 2022/2065)
-------------------- 
The DSA regulates online intermediaries and platforms, such as social media, marketplaces, and search engines, and sets obligations for content moderation, transparency, and risk management. It is relevant to researchers who study online platforms: **Article 40** gives vetted researchers a legal route to request access to data from very large online platforms and search engines in order to study systemic risks in the EU. This can be an alternative to scraping, which may violate platform terms of use and raise GDPR concerns. Check which procedures and conditions currently apply before relying on this route.

Which rules might apply to me?
-------------------- 

| If your project... | Think about... |
|---|---|
| processes personal data | GDPR |
| develops or uses AI systems and models | AI Act, GDPR |
| uses data from connected devices | Data Act, GDPR |
| uses health data | GDPR, EHDS |
| studies online platforms or social media | DSA (Article 40), GDPR, platform terms of use |
| accesses protected public-sector data | Data Governance Act |

Several of these rules can apply to the same project at the same time. If you are unsure which ones apply to you, contact the UNIVIE [RDM Team](mailto:rdm@univie.ac.at), the [Data Protection Officer (DPO)](https://dsba.univie.ac.at/), or the [Technology Transfer Office](https://transfer.univie.ac.at/en/team-and-contact/).

## Conclusion
requirements to address at the end of a project. By considering these issues from the beginning, researchers can protect the rights and interests of others while supporting transparency, reproducibility, and the responsible reuse of research outputs.

This includes choosing appropriate licenses, protecting personal and sensitive data, and ensuring that informed consent is properly obtained and documented when required. Researchers should also be aware that, beyond the GDPR, other EU regulations, such as the AI Act, Data Act, and Digital Services Act, may affect how data can be obtained, used, and shared, depending on the nature of their research.

Not every legal or ethical question has a straightforward answer, particularly when research involves human or animal subjects, Indigenous data, intellectual property, or collaborations with external partners. You are not expected to navigate these complexities alone. Consulting the relevant university support services early in your project can help you identify potential challenges, understand your responsibilities, and make informed decisions.

Ultimately, responsible research data management is about more than meeting legal requirements. It is about conducting research in a way that respects others, builds trust, and enables scientific knowledge to be shared and used responsibly.

## Knowledge Check
Test your knowledge with the quiz below. Each question has at least one correct answer, but there can also be multiple correct answers.

Why are ethical considerations in research data management important beyond formal legal compliance?

    [[X]] They help protect participants, communities, and research integrity
    [[X]] They support trust in research and responsible reuse of data
    [[ ]] They only matter if a law requires them
    [[ ]] They only matter for research involving animals

What is a practical difference between data licensing (e.g., Creative Commons) and code licensing (e.g., MIT or GPL)?

    [[X]] Creative Commons licenses are designed for content and data, while MIT and GPL are designed for software
    [[ ]] Data and code can never be licensed under the same terms
    [[ ]] Code licenses are legally optional, data licenses are mandatory
    [[ ]] There is no difference

In which situations might additional ethics or legal review be required before data collection or sharing?

    [[X]] Research involving human participants or personal data
    [[X]] Research involving animals or imported samples
    [[X]] Data from Indigenous or local communities
    [[ ]] Only when the data is stored on a personal laptop

What does informed consent need to clarify so participants can make an informed decision?

    [[X]] What participation involves and how their data will be used
    [[X]] Potential risks and benefits, and that participation is voluntary
    [[X]] How they can withdraw and who to contact with questions
    [[ ]] That participants must agree to all future uses of the data without exceptions

How can the CARE principles influence decisions about data from local or Indigenous communities?

    [[X]] They emphasize collective benefit, authority to control, responsibility, and ethics
    [[X]] They encourage involving communities in decisions about how their data are used and shared
    [[ ]] They replace the need for any other legal or ethical review
    [[ ]] They only apply to data that is already openly published

Sample collection and export processes are the same in most countries.

      [[ ]] True
      [[X]] False
    
What are some examples of sensitive data under the GDPR? 

    [[ ]] A laboratory mouse model's genetic data
    [[X]] Personal data that can be linked to a living person
    [[X]] Information about racial identity or ethnic background
    [[X]] Data about political beliefs or affiliations
    [[ ]] Biometric information from a Roman soldier    

I am a scientist, therefore I need not concern myself with the legal documents sent to me by my funders.

    [[ ]] True
    [[X]] False
    
The CARE principles are designed to take into account the complex social, political, and economic relationships that exist between Indigenous Peoples, researchers, and the broader world.

    [[X]] True
    [[ ]] False
<!--
authors: Franziska Bauchinger, Jeanne Wilbrandt, Emily J. Kate 

email: franziska.bauchinger@univie.ac.at, jeanne.wilbrandt@univie.ac.at, emily.jean.kate@univie.ac.at 

version:  1.0

language: en

-->
# Data Management Plans (DMPs)

Objectives
-------------------- 
Welcome to Module 8! You've almost made it to the end of our online learning materials. In this module, we’ll pull together the lessons learned in the other modules and discuss how to write a data management plan for your project.

By the end of this section you will be able to:

1. explain how DMPs can be used to actively support a research project.

2. draft a DMP for your research project with potential input from your supervisor(s).

3. know who to contact for DMP support at the university.

Introduction
--------------------
A data management plan (DMP) is a formal document that outlines how research data will be handled, stored, organized, protected, and shared during and after a project. In the words of UNIVIE RDM Policy: “A DMP describes how research data should be handled, and is therefore a tool for research data management. The plan explains which data are collected or generated during a research activity and specifies what needs to be done during the data lifecycle, i.e. the whole data process (storage, publication, citation, long-term availability, pseudonymisation, anonymisation, reuse, deletion, etc.).” 

In the next sections, we'll discuss why we write DMPs, what should be included in them, and who you can ask for help at UNIVIE. 

## Why do we write DMPs?
Here's the deal. Nothing in your deep evolutionary past prepared you to be a great scientist. Being a good scientist requires long-term planning and organization. Our brains are much more focused on the short-term payouts released by sugar, fat, salt, and TikTok, that fuel our inherent dopamine addiction. That’s why we have to formulate plans about making plans...draw-up plans...and then follow the plan. DMPs are meant to fill this role for research data management. 

A lot of people will tell you that writing a DMP is a silly administrative task that slows down the pace of scientific discovery, but we find that it can actually save time and make researchers more confident about the progress of their projects. Sometimes writing a DMP is a bit like eating your vegetables. You might not want to do it, but you know you should. Here are a few ways writing a DMP now can help you in the future.

* A DMP describes how you will organize and document your data from the start, so you don't lose important information or spend days reorganizing files at the end of the project.

* Having a data storage and back-up plan makes it more likely that your data will be safe and secure. No one wants to re-do experiments because a computer crashed.

* Selecting potential repositories and publishing options forces you to assess if a portion of your budget will be needed to maintain and archive your data properly, so that you aren’t surprised later with unexpected costs.

* Detailing usage rights, responsibilities, and licensing choices early helps to limit conflicts and disagreements between project members later in the project.

And last but not least, funding agencies (think FWF or Horizon Europe) usually require researchers to write and hand in a DMP. Your doctoral school may require that you write a DMP as well. Which brings us straight to our next section:

## What do you include in a DMP?
As mentioned above, many funding agencies require that DMPs be drafted for funded projects. In most cases, the funding agency provides a DMP template that awardees are expected to complete early in their project. Using the provided DMP template ensures that the program officers can quickly evaluate and approve your DMP. The two most common DMP templates in Austria are those provided by the Österreichischer Wissenschaftsfonds (FWF) and Horizon Europe programs. Both templates cover the same information, just in a different format. In FWF projects, the first draft of the DMP must be submitted before the project begins. DMPs associated with Horizon Europe projects should be submitted within the first six months of the project, and both the FWF and Horizon Europe require that you provide a final report on your project's outputs, including what papers you published, where you deposited data and code, and if your project included any other outputs. 

If you would like to inspect the Horizon Europe and FWF templates, you can find them linked below. Also, if your PhD project is part of a larger funded project, you can ask your mentor to see the project-level DMP. We actually recommend that DMPs be made available to all project members. 

* [ERC/Horizon Europe RDM Guidelines and Templates](https://ec.europa.eu/research/participants/docs/h2020-funding-guide/cross-cutting-issues/open-access-data-management/data-management_en.htm) 
* [FWF RDM Guidelines and Templates](https://www.fwf.ac.at/en/about-us/what-we-do/open-science/research-data-management)

Not all funders require DMPs, but researchers are still welcome to write one. In fact, we encourage it!  If no template is provided, we usually suggest that researchers use the FWF template. We find it much easier to work through than the Horizon Europe template. 

Similarly, for PhD projects, we also recommend that students write a DMP that covers just their portion of a larger project. For PhD candidate projects, you will find a PhD project DMP template in the Moodle course accompanying this workshop. Just remember, the content of your project DMP should be harmonized with 1) the larger project DMP, if it exists, and 2) your research group's data handling procedures. 

Universal DMP Content
--------------------
So, what do all DMP templates have in common? What do they ask you to address? 

First, they ask you to provide basic administrative information for your project. This can include: 
* The date the DMP was drafted and the version number.  
* Your name
* Your institutional affiliation 
* Your contact information
* Basic information about your project partners. 
* A description of how the data management activities are distributed. 
* The resources you will need (time, hardware, and money) you will need to manage your data. 

Second, you're asked to provide information about the data you will generate or reuse during your project. When describing your data, you just need to provide some basic facts, such as: 
* A very, very short description of each dataset you will generate or reuse.
* The file formats you will use for each dataset during the active phases of your project. 
* The size of each dataset OR an estimate of your total data size in GBs or TBs
* The origin of any data you plan to reuse. 

Then DMPs always ask you to describe how your data and research will be documented and organized. This can include descriptions of things like: 
* Metadata standards or custom metadata schemas
* Lab Notebooks 
* READMEs 
* Data Analysis Logs
* Protocols or Standard Operating Procedures (SOPs)
* Quality Control Measures 

How your data is organized is often closely related to how your data is stored during the active phases of your project. The normally covers: 
* Where your data is stored. 
* How it is backed-up. 
* Who is responsible for maintaining the system housing your data. 

Once the active phases of your project are addressed, DMPs often turn towards data preservation and sharing. In these sections, you are often asked to describe: 
* What data you will deposit in a repository and when it will be released.  
* Which repositories you intend to use. 
* How you will license the data. 
* If any access restrictions will be imposed on the data. If so, you'll also be expected to explain why. 

Finally, DMPs often cover legal and ethical concerns. You do not need to fully describe your ethical, legal, or contractual obligations in this section. Instead, you should address: 
* Who owns the data you work with or generate. 
* If your project requires an ethical clearance and if that process has been completed. 
* If there are any legal or ethical restrictions that limit your ability to share data or outputs openly. 

Now that you know what a DMP should include, let's think about the process of writing a DMP. 

## How do you write a DMP?
Much like dissertations, the best DMP is the DMP that actually gets written. The first step is to select the template you want to use. You can use one from a funder, use the template we provide in this workshop, or make one of your own! Next, you should familiarize yourself with the requirements of your hosting institution, funders, and any other entity with whom you have a legally or ethically binding relationship. Also consider what (helpful) data management norms exist in your research group or among your collaborators. Whatever you write in the DMP should be aligned with all of these project stakeholders. Finally, work through all of the topics covered above, but don't expect to address all of them without consulting with your mentors and collaborators. Your mentors may be able to help answer questions and both mentors and colleagues should be involved in deciding what data is released, when, where, and under what licensing conditions. 

** But what if you are the pioneer in your group and the first to use a DMP? **

Never fear! 

There are people at UNIVIE who are here to help you!
The first points of contact regarding a DMP are the data stewards of the University of Vienna. You can find all of us listed here: https://rdm.univie.ac.at/data-stewards-at-the-university/

And of course, you will meet some of us during the in-person section of this course.
Alternatively, you can always reach the UNIVIE RDM team at rdm@univie.ac.at. They're available to anyone at the university and are always ready to help! No question too small! No mess too big!

## Knowledge Check

Alright, it's quiz time. Let's see what you learned about DMPs. Each question has at least one correct answer, but there can also be multiple correct answers.

**Question  1: **
You only need a DMP if your granting agency, doctoral school, or supervisor requires that you write one.

[( )] True
[(X)] False

** Question 2: ** 
A DMP should:

[(X)] Define researcher roles and responsibilities. 
[( )] Include the specs of your research equipment. 
[(X)] Explain how you will organize your data. 
[( )] Outline potential titles for papers that will result from your project. 
[(X)] Indicate how much data storage and archiving will cost. 

** Question 3: **
UNIVIE, I can get help with my DMP by:

[(X)] Contacting my faculty data steward.
[( )] Sending up a flare. 
[( )] Spinning in a circle three times while reciting an ancient incantation. 
[(X)] Reaching out to the UNIVIE RDM team via their website.
<!--
authors: Isolde van Dorst, Mathias Mayrgündter

email: isolde.van.dorst@univie.ac.at, mathias.mayrgündter@univie.ac.at

version:  1.0

language: en

-->

# Conclusion

Congratulations, you have made it to the end of the course! Let's have a little recap on what exactly this course has covered.

Recap of the course contents
--------------------

Through this course, you have been introduced to the core aspects of research data management.
* You know what research data is, what metadata entails, and are familiar with the research data life cycle. You understand the principles of FAIR data, Open Science, and understand why these things are important when doing research.
* You can organise your data, through the use of properly structured folders and files, which are named in a systematic and clearly labelled manner. You know how to set up and implement README files, templates, and procedures for both an individual researcher as well as a research group.
* You know why it is important to document your data, and how to do this properly through the use of metadata. You can distinguish between different types of documentation, as well as identify which documentation tools are applicable to different types of research.
* You understand why it is essential to store your data properly, and what it means to do so. You can identify and choose appropriate storage options based on different types of data, understand the importance of data security and how to secure your data, as well as how to safely share your data with others. You understand the value of backups.
* You know why and how to archive or publish data after the project has been completed, and understand why this is an important step in doing sustainable research. You know what aspects of documentation and organisation are needed to properly archive or publish your data, and can select the appropriate repository. You have also been made aware of the importance of PIDs, authorship and licensing. You can distinguish between different levels of access to data.
* You understand the benefits of reusing data, and of making your own data reusable. You know how to find reusable data, and to check whether data you find is actually reusable for you. You are also familiar with the ways to cite data that you reuse.
* You know how to approach and discuss legal and ethical considerations surrounding data. You are aware of Responsible Research and Innovation (RRI) and Research Integrity, and able to identify the types of data that invoke ethical considerations and the CARE principles. You can discuss legal issues, such as the licensing of research output, data, code, or other specific outputs. You can identify the differences between copyright, patent, and intellectual property, as well as the differences between legalities of working with animals or human participants.
* You know why a data management plan is useful in organising your research data, and you understand the different aspects of the research data life cycle that should be discussed in a DMP. You know how to find a template for a DMP, or how to contact someone who can help create such a template.

Where to find help
--------------------

While you have completed the course and have a (hopefully) better understanding of research data management than you did before the course, you can always ask for further help with anything that is still unclear, or that comes up in your research later. The Research Data Management Team at the University of Vienna is always happy to help! You can find us on the RDM website, or contact a data steward directly if your faculty or centre has a dedicated data steward. Even if your faculty or centre does not have a specific data steward yet, the RDM Team will always try to answer your query as best as possible. You can submit any questions to the RDM Helpdesk.


RDM website: [rdm.univie.ac.at](rdm.univie.ac.at)


Find out if your faculty/centre has a data steward: [click here](https://rdm.univie.ac.at/de/data-stewards-universitaet-wien/data-stewards-kennenlernen)


RDM Helpdesk: rdm@univie.ac.at


Sign-Off
--------------------

We hope you find this course helpful and interesting! It was a pleasure to have you along for the ride, and we look forward to seeing your research data out in the wild someday (with appropriate documentation, in a nicely organised structure, while adhering to all legal and ethical considerations, findable in a suitable repository)!


Additional RDM Tools and Resources (also integrated into the modules)
--------------------

(This is like an extended bibliography)
To be added by all module authors?
