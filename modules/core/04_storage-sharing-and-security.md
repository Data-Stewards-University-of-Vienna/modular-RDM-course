


<!--
authors: Lukas Kraiger, Simone Spedicato 

email: lukas.kraiger@univie.ac.at, simone.spedicato@univie.ac.at    

version:  1.0

language: en

-->

# Data Storage, Sharing, and Security

## Learning Objectives

By the end of this chapter, you will be able to:

- select appropriate storage solutions for research data,
- explain the principles of good data storage and backup,
- identify university-supported storage services.

---

Research data is often one of the most valuable outputs of a project. Losing data can mean losing months or even years of work. For this reason, planning where and how your data will be stored should begin **before** data collection starts.

Storage planning is also part of good research data management. It helps ensure that data remain accessible throughout the project, can be shared with collaborators when needed, and are protected against accidental loss.

Before choosing a storage solution, you might want consider the following questions:

- How much data will your project generate?
- How quickly do you need to access the data?
- Who needs access?
- Does your project involve sensitive or confidential information?
- How long should the data be kept after the project ends?

Even a rough estimate of these requirements will help you choose an appropriate storage solution.

## Choosing Appropriate Storage

Different research projects have different storage requirements. A project consisting mainly of text documents has different needs from one producing terabytes of sequencing or imaging data.

Whenever possible, you should use **university-supported storage services**. These services are professionally managed and typically provide

- secure authentication,
- controlled access permissions,
- regular backups,
- technical support,
- reliable long-term operation.

Using institutional services also makes collaboration easier and reduces the risk of data loss compared with relying solely on personal computers or external hard drives.

**University Storage Services**

|Service | Function | Storage Space | Collaboration Features|Cost|Availability|
| -----------|---------------|-------|---------|----------| -----------
|[Personal Online Storage Space](https://zid.univie.ac.at/en/online-storage-space/) | Personal file storage | 10 GB; Expandable with justification |None |Free|Immediate|
|[Share](https://zid.univie.ac.at/en/share/) | File storage and sharing; Managed through organizational unit| Unlimited |Between employees and students; Extended u:account available for guests  |EUR 0.03 per GB/year|Request Required|
|[u:cloud](https://zid.univie.ac.at/en/ucloud/) | Personal file storage and sharing| 100 GB  |Between employees and students; Extended u:account available for guests  |Free|Immediate|
|[u:cloud pro](https://zid.univie.ac.at/en/ucloud-pro/)| File storage and sharing; For projects or teams| 250 GB; expandable with justification  |Between employees and students; Outside users can upload and download  |EUR 0.03 per GB/year|Request Required|
|[One Drive by Microsoft 365](https://zid.univie.ac.at/en/microsoft-365/)| File storage and sharing| 50 GB|Internal and external sharing; Non-university users can edit files|Comes together with MS365 license for university employees|Immediate|
|[Gitlab*](https://zid.univie.ac.at/en/gitlab/)| Storing code; Version control| Unlimited; Code and supporting documentation|	Permissions and licensing options available|Free|Request Required|
|[Central Backup](https://zid.univie.ac.at/en/central-backup/)| For files not otherwised backed-up; Requires some user maintenance| Unlimited|None|Free|Request Required|

*At UNIVIE you are welcome to set-up your own Github or Gitlab account. 


> **Tip:** If you are unsure which service best suits your project, contact the Research Data Management Support team before your project begins.

## Backups and Data Preservation

Even the best storage solution cannot completely eliminate the risk of accidental deletion, hardware failure, theft, or ransomware. Regular backups remain an essential part of research data management.

**The 3-2-1 Rule**

For projects that do not involve sensitive data, the 3-2-1 rule provides a simple guideline:

- Keep **three copies** of your data.
- Store them on **two different types of storage media**.
- Keep **one copy at a different physical location**.

Many university storage services already include automated backups, but it is important to understand what is—and is not—being backed up.

**Test Your Backups**

A backup is only useful if it can be restored successfully. Periodically test that files can be recovered and opened correctly, and verify that important metadata and permissions have been preserved.

**Storage Media Do Not Last Forever**

No storage medium is permanent. Hard drives fail, USB flash drives can become unreadable, and optical media degrade over time. Professionally managed institutional storage reduces these risks through monitoring, maintenance, and migration to newer storage systems when necessary.

## Data Security (need to add some links)

Protecting research data is about more than preventing data loss. It also means ensuring that only authorised people can access the data and that information is handled in accordance with legal, ethical, and institutional requirements.

**Good Security Practices**

Simple habits can significantly reduce the risk of data loss or unauthorised access:

- Use strong, unique passwords and, where available, enable multi-factor authentication.
- Keep your operating system and software up to date.
- Lock your computer when leaving your workspace.
- Be cautious of phishing emails and suspicious links or attachments.
- Store research data on university-managed systems whenever possible.
- Report suspected security incidents promptly according to university procedures.

Security is not only a technical issue—it is also part of responsible research practice.

**Working with Sensitive Data**

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
> If your project involves sensitive data, contact the Research Data Management Support team (rdm@univie.ac.at) before data collection begins. We can help identify appropriate storage solutions and security measures.

## Sharing Data During a Project

Research is, as we know, increasingly collaborative. Sharing data within a project allows team members to reproduce analyses, build on previous work, and avoid unnecessary duplication.

When sharing data, you should consider consider:

- who requires access,
- what level of access they need,
- how changes to files will be tracked,
- whether the data contain sensitive information.

Whenever possible, use university-supported collaboration platforms rather than exchanging files by email or using personal cloud storage.

**Choosing the Right Tool**

Different collaboration tasks require different services.

| Purpose | Recommended service |
|----------|--------------------|
| Collaborative document editing | OneDrive, u:cloud |
| Team file storage | Share, u:cloud Pro |
| Source code and version control | GitLab |
| Sending large files | ACONET FileSender |

For projects involving external collaborators, ensure that sharing arrangements comply with ethical approvals, funding requirements, and applicable legislation.

Remember that not every dataset should be shared with every collaborator. Access should be limited to those who need it for their role in the project.

## Data Ownership

Researchers often think of the data they create as "their data", but ownership and responsibility are not always the same.

At the University of Vienna, research data are generally governed by university policies, funding agreements, employment contracts, and legal requirements. The exact ownership of research data therefore depends on the circumstances of the project.

Understanding who owns the data is important because ownership affects:

- who may access the data,
- who can authorise sharing,
- who is responsible for long-term preservation,
- what happens to the data when a project ends.

If you are uncertain about data ownership in your project, discuss the issue with your supervisor or contact the appropriate university support service (RDM Team/Legal Help Desk) before sharing or transferring data.

## Sharing Data Beyond the University

Collaborating with researchers outside your institution often involves sharing data or research materials. In some cases, formal agreements are required before this transfer can take place.

**Data Transfer Agreements (DTAs)**

A Data Transfer Agreement (DTA) defines the conditions under which data may be transferred between organisations.

A DTA typically specifies:

- which data will be shared,
- who may use the data,
- how the data may be used,
- responsibilities for protecting the data,
- conditions for storage and disposal.

DTAs help ensure that data sharing complies with legal, ethical, and contractual obligations.

**Material Transfer Agreements (MTAs)**

A Material Transfer Agreement (MTA) serves a similar purpose but applies to **physical research materials**, such as:

- biological samples,
- microorganisms,
- cell lines,
- chemicals,
- laboratory reagents.

MTAs clarify how materials may be used, who owns resulting discoveries, and what happens to remaining materials after the collaboration.

> **Need advice?**
>
> If your project requires sharing data or research materials with another organisation, contact the appropriate university support office before any transfer takes place.

## Planning for the End of Your Project

Research data often remain valuable long after a project has finished. Planning for the end of a project should therefore begin well before the final day of employment or study.

**Before Leaving the University**

University accounts, storage space, and access permissions cannot be guaranteed after you leave the University of Vienna.

Before leaving, consider:

- Where will the project data be stored?
- Who will remain responsible for the data?
- Have important datasets been archived appropriately?
- Can collaborators still access the files they require?
- Have any necessary transfer agreements been completed?

Planning ahead helps avoid interrupted access to important research data and ensures that ongoing projects can continue smoothly.

If data or research materials need to move to another institution, additional agreements—such as a Data Transfer Agreement (DTA) or Material Transfer Agreement (MTA)—may be required.

Discuss these questions with your supervisor/RDM Team/Legal Help Desk and complete any required offboarding procedures before your university account is closed (how long?).
