# Key Concepts and Principles 
Welcome to Module 2! In this module, we’ll build the foundation for the rest of the course by looking at what research data actually includes, how it can be managed throughout a project, and how RDM connects to FAIR data and Open Science. Let's just in! 

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

What is Metadata
--------------------

In the words of Mugatu from the legendary film *Zoolander*, metadata is “so hot right now.” Despite its seemingly sudden popularity, you might be wondering how to define metadata and what it means for your research. The University of Vienna defines metadata as information that is “used to describe managed resources in a unique and structured manner. The unique structure enables users to search for, find, and select relevant resources. Metadata are a means of communication between producers and users of research data, and are crucial for making data findable.” While accurate, perhaps this definition isn’t the most helpful for someone who is trying to figure how they can document their data more fully. To get a more hands-on explanation, take a look at this video from the University of Ghent.

!?[Ghent University Data Stewards (2020) Knowledge Clip: Metadata](https://youtu.be/DW2T_cnqKPU "[Ghent University Data Stewards (2020) Knowledge Clip: Metadata](https://youtu.be/DW2T_cnqKPU), [CC BY](https://creativecommons.org/licenses/by/3.0/legalcode)") 

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

We have a handy website at rdm.univie.ac.at and you can email us anytime at rdm@univie.ac.at. If you or your friends are part of any of the faculties or centers listed below, there is dedicated data steward who can help you too! Send a data steward or the RDM team an email with a question and we will get back to you within three working days. We’ll either answer your question or outline some next steps. 

* Faculty of Life Sciences 
* Centre for Microbiology and Environmental Systems Science (CeMESS) 
* Faculty of Earth Sciences, Geography, and Astronomy 
* Faculty of Psychology 
* Faculty of Business, Economics, and Statistics 
* Faculty of Philological and Cultural Studies 
* Faculty of Historical adn Cultural Studies 

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

Also, remember that when you work with sensitive or protected data, you should pseudonymize or anonymize your data during the processing phase whenever possible. You should also use discipline specific methods of encoding variables if they are available, and you should keep careful records of how data was pseudonymized or anonymized. It’s never a bad idea to also maintain a codebook where your vari ables are all explained. 

Step 4: Analyzing
--------------------
Data analysis begins when you finally dive into your data and use it to answer scientific questions or test hypotheses. The methods you use to analyze your data are also called a “workflow”. During many projects, workflows will likely be repeated several times and modified to increase reliability and efficiency. Always remember to keep clear records of how your workflow changes over time. You always want your workflows to be reproduceable by your team members and other researchers. This reproducibility is a central tenant of making science FAIR. Thinking about how you should analyze your data is certainly important, but you should also consider how you will document you analyses and investigations. 

Here are two last tips from people who know some things because they’ve seen some things and *occasionally* made mistakes themselves. First, always keep an unedited version of your unanalysed data stored. Never use this specific file to conduct analyses. Use a copy instead. This way, if you make a problematic edit to your data or your data gets jumbled, you can always make a copy of the original file and start again. This takes the situation from “data disaster” to an "inconvenient afternoon". Second, if you are conducting analyses and find yourself confused with a million files open and an inability to think clearly, it’s probably time for a break. Take a walk. Eat something. Have a nap. Drink some water. You aren’t going to make good analytical decisions when you’re frazzled, and you certainly won’t document things properly. A 30-minute break can save you hours of headache later. 

Step 5: Preserving
--------------------
When you hear of preserving, you might think of culinary delicacies such as smoked hams, canned pickles, or jarred jams. Sadly, this section will not be about any of those things. Data preservation is a process by which the safety, integrity, and accessibility of your data are ensured. In many cases, data should be preserved for years, or even decades. You might think that properly storing your data means it is preserved, but this is not quite the whole story. Preservation of digital information requires planning, policies, resources (time, funds, and people) as well as the right technology to ensure that the data stays functional and that it can be accessed. Therefore, true data preservation, or archiving, must be done by experts and dedicated services. In most instances, special long term data repositories should be used for digital preservation, where the data is actively maintained and information integrity is monitored.^1^ 

![Trader Joe's Pickle Car](https://upload.wikimedia.org/wikipedia/commons/4/43/Trader_Joe%27s_-_Pickle_Car_%2812221274575%29.jpg "We know you also wish this section was about making pickles and other preserves. Sadly, it isn't, but maybe you could get yourself a pickle as a treat for making it this far.  [Source: Prayitno / Thank you for (12 millions +) view from Los Angeles, USA](https://upload.wikimedia.org/wikipedia/commons/4/43/Trader_Joe%27s_-_Pickle_Car_%2812221274575%29.jpg), [CC BY](https://creativecommons.org/licenses/by/2.0/deed.en)") 


The first step in data preservation is to decide what data should be maintained and what data can be destroyed. All (non-sensitive) data that contributed to a publication should preserved. In most cases, publishers and funding agencies will require that this data be made available. In many projects, researchers generate more data than they include in publications. This is where the decision-making process can be a little tricky. When considering if unpublished datasets should be preserved, researchers can ask themselves some critical questions. 

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

he FAIR Principles were designed to support the sharing of research data. The intention of these principles is to improve the Findability, Accessibility, Interoperability and Reusability of data. 

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

For researchers, these national ambitions become most visible through funder and institutional policies. The Austrian policy calls for Data Management Plans to become standard, supports trusted repositories and FAIR data practices, promotes open access to publicly funded outputs, and recognizes that data management and sharing require resources. In practice, funder policies help translate these broader national goals into concrete expectations for research projects.

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

A useful point to remember is that Horizon Europe does not simply require “open data.” It requires responsible FAIR data management and expects openness by default where possible, while explicitly allowing justified restrictions.

**Österreichischer Wissenschaftsfonds (FWF)**

The Austrian Science Fund (FWF) translates Open Science principles into concrete requirements for funded research. For projects approved under the current framework, researchers are expected to plan for good research data management, provide open access to publications, and make the research data underlying publications openly available whenever possible.

In practice, researchers should:

* **Prepare a Data Management Plan (DMP)** A DMP is required for FWF-funded projects and must describe how data and metadata will be collected, organized, stored, shared, published, and archived. It should be treated as a living document and updated during the project.
* **Make peer-reviewed publications openly accessible** Publications arising wholly or partly from FWF funding must be available Open Access. This can be achieved through an eligible Open Access venue, certain transformative agreements, or immediate repository-based Green Open Access. FWF generally requires a CC BY licence.
* **Share the data needed to support published results** Research data and metadata necessary to reproduce and verify a publication must be made openly available as soon as possible and no later than publication. If data cannot be shared for legal, ethical, or other legitimate reasons, this must be explained in the DMP.
* **Make shared data FAIR and reusable** Data should be deposited in an appropriate repository, have a persistent identifier such as a DOI, include suitable metadata, and normally use an open licence. FWF funding can also cover eligible costs associated with preparing, archiving, and providing access to research data.

The important distinction is that FWF does not require every piece of project data to be made public: open access is mandatory for the data underlying publications, while decisions about sharing other project data remain with the principal investigator and should be addressed in the DMP.

<u>Policies Supporting Open Science at the University</u>

A Long Way to Go: The LERU Roadmap for Open Science 
--------------------

Policies and funder requirements tell us a lot about **what researchers are expected to do now**, but they do not necessarily show the full amount of work still needed to make Open Science routine and sustainable. One useful way of seeing that bigger picture is the **LERU Open Science Roadmap**. LERU is the League of European Research Universities, and its roadmap is only one interpretation of how Open Science should be implemented—but it is one we find especially useful because it looks beyond individual compliance and asks what universities themselves need to change, support, and invest in.

The roadmap organizes this work around **eight pillars**:

* **The future of scholarly publishing** – Moving toward publishing systems that are more open, accessible, sustainable, and supportive of wider access to research outputs.
* **FAIR data** – Ensuring that research data can be appropriately managed, documented, preserved, discovered, accessed, and reused.
* **The European Open Science Cloud (EOSC)** – Developing and connecting the infrastructure and services needed to support access to and reuse of research data across Europe.
* **Education and skills** – Giving researchers and research-support staff the knowledge and practical skills needed to work openly and manage research outputs effectively.
* **Rewards and incentives** – Ensuring that Open Science activities are recognized and valued in research careers rather than simply adding additional work without recognition.
* **Next-generation metrics** – Developing more responsible ways of assessing research and researchers that go beyond traditional publication counts and journal-based metrics.
* **Research integrity** – Supporting transparent, rigorous, and reproducible research practices as part of responsible research conduct.
* **Citizen science** – Creating opportunities for members of the public and other societal actors to participate meaningfully in research.

Taken together, these pillars give a fuller picture of the work involved in Open Science: **infrastructure, services, training, incentives, evaluation systems, policies, and cultural change all need attention**. This is an important distinction because current policies largely reflect the practices that have already become established enough to require; the roadmap also helps us see the areas where considerable institutional development and investment are still needed.

## Why are we doing all of this? 
Why do we put so much emphasis on Research Data Management, FAIR data, and Open Science? There are many practical reasons, but two arguments sit at the center of this course. The first is public benefit. Research is rarely an entirely private activity, and this is especially true in Europe, where a large proportion of research is supported directly or indirectly through public funding. In that sense, researchers at public universities are, at least in part, acting as public servants: society invests in research because research is expected to produce knowledge that benefits more than the individual researcher or research group. Good RDM and FAIR and Open Science practices help make that investment go further by allowing research outputs to be discovered, understood, combined, and reused rather than disappearing when a project ends.

This matters because scientific progress is cumulative. New discoveries do not appear out of nowhere; they are built from previous observations, datasets, methods, software, and ideas. When those outputs are well documented and made available under appropriate conditions, other researchers can ask new questions of existing data, combine information across studies, develop new methods, and sometimes make discoveries that the original researchers never anticipated. Not every dataset is going to change the world, of course, and not every dataset can or should be completely open. But making research as open as possible and as closed as necessary increases the chances that the work we do can continue to produce value after the original project has finished.

The second argument is about transparency and reproducibility. Scientific claims are more trustworthy when others can understand how they were produced. That requires more than publishing the final numbers in a paper: researchers need adequate information about the data, methods, processing decisions, analyses, software, and other steps that led from observation to conclusion. Good RDM makes those processes easier to reconstruct, FAIR practices make the relevant materials easier to find and interpret, and Open Science encourages researchers to make those processes and outputs visible wherever doing so is responsible. Together, these practices make it easier to verify findings, identify mistakes, reproduce analyses, and build confidently on previous research.

There are also important ethical arguments for careful data management and responsible openness. Questions about research participants, privacy, consent, sensitive information, ownership, equity, and responsible data sharing can determine what should be shared, with whom, and under what conditions. We will return to those issues in a dedicated module on research ethics. For now, the key point is that RDM, FAIR, and Open Science are not simply administrative requirements or boxes to tick for a funder. They are part of the infrastructure that allows research to be trustworthy, reusable, and genuinely useful to the scientific community and to the public that supports it.

## Conclusion 
--------------------
That brings us to the end of this module. You should now have a clearer picture of what we mean by research data and metadata, how data move through the research data life cycle, and how RDM, FAIR, and Open Science fit together as part of responsible and reusable research. Before moving on, complete the knowledge check (up next) to make sure the key concepts are in place. Then, in Module 3: Data Organization, we’ll shift from the big picture to the practical details and look at how thoughtful file structures, naming conventions, and documentation can make your research easier to manage now—and much easier for you and others to understand later.

## Knowledge Check

