<!--
authors: Lukas Kraiger, Simone Spedicato 

email: lukas.kraiger@univie.ac.at, simone.spedicato@univie.ac.at    

version:  1.0

language: en

-->
## Storing and Securing your Data
Learning Objectives
=========================

1. Summarize the best practices for data storage and back-up. 
2. Know what storage resources are available to you at the University of Vienna.

### Best Practices for Storage and Back-up

The need for data storage arises early on in a research project, as you will need a space to place your newly created data. Therefore, it’s always a good practice to think about storage solutions during the project’s planning phase, request storage in advance, and ensure funds are available to pay for it^1^. 

The storage solution for your data should fulfill certain criteria (e.g. space, access & transfer speed, duration of storage, etc.), which should be discussed with an IT specialist or a member of a RDM team. You may choose a tiered storage system for assigning data to various types of storage spaces based on requirements for access, performance, recovery and cost. Using tiered storage allows you to classify data according to levels of importance and assign it to the appropriate storage tiers or move it to different tier. For example, once analysis is completed you might move data to lower tier for preservation or archiving^1^.

Tiered storage is usually classified as either “cold” or “hot” storage. Hot storage is associated with fast access speed, high access frequency, high value data that is stored on faster drives such as solid-state drives (SSD). This storage is usually located physically near the user (like on campus) and incurs higher costs. Cold storage is associate with low access speed and frequency and consists of slower drives or tapes. This data is usually stored in a more distant location and incurs lower costs^1^.

When looking for solutions to store your data during the collection or generation phase, you should consider the following aspects^1^.

* The volume of your data is an important discerning factor to determine the appropriate storage solution. At the minimum, try to estimate the volume of raw data that you are going to generate or collect.
* Know what kind of access/transfer speed and access frequency will be required for your data.
* Considering where the data will come from is also crucial. If the data comes from an external facility or needs to be transferred to a different server, you should think about an appropriate data transfer method.
* It's a good practice to have a copy of the original raw data in a separate location, to keep it untouched and unchanged (not editable).
* Know for how long the raw data, as well as data processing pipelines and analysis workflows need to be stored, especially after the end of the project. 
* Make sure to keep metadata together with the data or establish a clear link between data and metadata files.
* In addition to the original “read-only” raw (meta)data files, you need storage for files used for data processing and analysis, as well as the workflows/processes used to produce the data. 
* Consider who is allowed to access the data (in case of collaborative projects), how do they expect to access the data during the project. 
* Finally, consider any legal or ethical concerns. Sensitive data will require special storage conditions and your funding source, institute, or country may have legal limitations regarding how data is shared. 

If you are not working with sensitive data, a good rule for backing-up your files is the 3-2-1 concept. This rule states that there should be three copies of your files. These copies should be stored on at least two different storage mediums, like a personal computer, external hard drive, server, or cloud drive. One of these back-ups should be in a different physical location than the other two. Today, this often means that your data is back-up to a server outside of your univeristy building via a cloud service and your files are also saved to your computer and something like an external hard drive. 

It is recommended to utilize automatic backup systems whenever possible. One option is to use a software client on your PC that automatically syncs your data with the cloud, such as OneDrive or u:cloud (see more details below).

If you store your data on the institutional Share, your data is backed up once a day. You can restore deleted data, folders, and older versions of data. For data and folders up to 5 days old, you can perform the restoration yourself. However, for data and folders older than 5 days, please contact the ZID Helpdesk for assistance.

When working on the [Life Science Compute Cluster](https://lisc.univie.ac.at/) (LiSC), please note that only data in your `/home` and `/archive` are daily backed up to tape. The backup system retains 3 versions of each file and keeps inactive (deleted) files for 6 months. Data stored on `/scratch` has **no** backup. Only use it for everything intermediate that can be reproduced from your project data and scripts. You can find more information on the LiSC storage policy in the [LiSC Wiki](https://lisc.univie.ac.at/wiki/content/working_environment/storage_policy) (access requires a user account).

As we mentioned above, the rules for sensitive data are more complex and your should talk to a RDM specialist before you select storage solutions for information concerning living people. Additionally, it quickly can become problematic to store large datasets (>100 GB) using the 3-2-1 rule and shifts in planning often need to be made. 

### Storage Solutions at UNIVIE
Hopefully this hasn't made you feel too overwhelmed. Remember that RDM help at UNIVIE is always available. Furthermore, the university has several in-house storage options you can use, but keep in mind that some of these solutions do have associated fees.

|Service | Function | Storage Space | Collaboration Features|Cost|Availability|
| -----------|---------------|-------|---------|----------| -----------
|[Personal Online Storage Space (Z:Drive)](https://zid.univie.ac.at/en/online-storage-space/) | Personal file storage | 10 GB; Expandable with justification |None |Free|Immediate|
|[Share](https://zid.univie.ac.at/en/share/) | File storage and sharing; Managed through organizational unit| Ulimited |Between employees and students; Extended u:account available for guests  |EUR 0.03 per GB/year|Request Required|
|[u:cloud](https://zid.univie.ac.at/en/ucloud/) | Personal file storage and sharing| 50 GB  |Between employees and students; Extended u:account available for guests  |Free|Immediate|
|[u:cloud pro](https://zid.univie.ac.at/en/ucloud-pro/)| File storage and sharing; For projects or teams| 250 GB; expandable with justification  |Between employees and students; Outside users can upload and download  |EUR 0.03 per GB/year|Request Required|
|[One Drive by Microsoft 365](https://zid.univie.ac.at/en/microsoft-365/)| File storage and sharing| 50 GB|Internal and external sharing; Non-university users can edit files|Comes together with MS365 license for university employees|Immediate|
|[Gitlab*](https://zid.univie.ac.at/en/gitlab/)| Storing code; Version control| Unlimited; Code and supporting documentation|	Permissions and licensing options available|Free|Request Required|
|[Central Backup](https://zid.univie.ac.at/en/central-backup/)| For files not otherwised backed-up; Requires some user maintenance| Unlimited|None|Free|Request Required|

*At UNIVIE you are welcome to set-up your own Github or Gitlab account. 

### UNIVIE Tools for Collaborative Work 
At some point during your time at UNIVIE you will probably need to work on a project with other people. While u:cloud does have come collaboration features, we find the resources provided by Microsoft 365 to be the most intuitive and easiest to use with people outside the UNIVIE network. With this said, keep in mind that sensitive data should never be stored on Microsoft One Drive.

Github and Gitlab continue to be excellent choices for code collaboration. The LiSC operates a Gitlab virtual machine for their users as well, and you can obtain Gitlab access by contacting their [helpdesk](https://lisc.univie.ac.at/helpdesk).

Finally, if you need to send large files (up to 250 GB in size) to a collaborator, you can use [Aconet File Sender](https://zid.univie.ac.at/en/filesender/). 
If you are working on the LiSC and need to share data with external parties, you can utilize the `/fileshare` directory. For further details, please refer to the [LiSC Wiki](https://lisc.univie.ac.at/wiki/content/working_environment/fileshare) (access requires a user account) or reach out to the [LiSC helpdesk](https://lisc.univie.ac.at/helpdesk) for assistance. 

### A Note on Basic Security and Working with Sensitive Data 
We aren't going to go too deep into cyber security, but we wanted to pass on few tips that will help keep your data safe and secure: 
Create Strong Passwords: Avoid easily guessable information. Include upper case and lower case letters, special characters, and numbers in your passwords. Consider storing your passwords using an encrypted password storage application. 

* **Use Two-Factor Authentication**: When available, opt into two-factor authentication. 
* **Secure your Office**: Don't make it easy for bad guys to steal your shiny stuff. 
* **Lock your Devices**: When you leave your office, always lock your computer. Also enable biometric log-in or passcode log-in for your tables and cell phone. 
* **Remember to Update**: Keep your software and operating system up-to-date. Updates often include security patches. 
* **Be Cautious**: Be skeptical of emails from unknown senders, especially those who ask for your personal information. Do not click links or open attachments in suspicious emails.
* **Report Suspicious Activity**: You can forward suspicious emails as attached EML files to the ZID IT security team for analysis at security.zid@univie.ac.at.

We'll talk more about sensitive data below, but if you are planning a project that will use sensitive information, please contact the UNIVIE RDM team for help with data storage, back-up, and protection. 

If you are part of a project using sensitive data, keep these best practices in mind: 

* **Encryption**: Only store sensitive data on devices with full disk encryption.
* **Limit Copies**: Limit the copying of sensitive data. If you must copy sensitive data, always encrypt it. 
* **Be Mindful of Back-Ups**: Ensure all back ups, even those on the cloud, are encrypted.
* **Avoid Transport**: Even encrypted sensitive data should only leave your workspace when absolutely necessary. 
* **Be Cautious of Transfers**: Do not transfer un-encrypted sensitive data over the internet. 
* **Data Disposal**: Delete sensitive data when no longer needed. Use a digital file shredder to ensure data cannot be restored. Always empty your computer's trash bin. 

### Quiz

Yipee! Quiz time!  Each question has at least one correct answer, but there can also be multiple correct answers.

For datasets that are neither sensitive nor gigantic, how many copies of the file should exist? 

    [[ ]] 2
    [[X]] 3
    [[ ]] 4
    [[ ]] 5    

When making plans for storing your data during a project, what are some things you should consider? 

    [[ ]] If your metadata is publically available.
    [[X]] How long your files need to be stored.
    [[ ]] Who will require access to the data.
    [[ ]] The volume of your data.
    [[ ]] How often you will need to access the files.     

All UNIVIE storage options are free for students and employees. 

    [[ ]] true
    [[X]] false  
    
All UNIVIE storage options are suitable for sensitive data. 

    [[ ]] true
    [[X]] false    
