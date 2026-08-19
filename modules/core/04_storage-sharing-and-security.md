<!--
authors: Lukas Kraiger, Simone Spedicato 

email: lukas.kraiger@univie.ac.at, simone.spedicato@univie.ac.at    

version:  1.0

language: en

-->

# Data Storage, Sharing, and Security

## Learning Objectives
Where is your data living right now—is it on a random USB drive on your desk, or just saved on your laptop's desktop?

Your research data is easily one of the most valuable thing you will produce during your PhD, and losing it can mean losing months or even years of hard work. That is why planning where and how your data will live should actually begin before you start collecting it. Setting up a good storage routine early on keeps your files safe, makes collaborating with others easy, and saves you from late-night panic.

By the end of this chapter, you will be able to:

* Select the right storage solutions for your specific research data.
* Explain the basic principles of secure data storage and backup.
* Identify and use the storage services supported directly by the University of Vienna.

## Choosing Appropriate Storage

Not all research data is created equal. If your PhD consists mostly of text documents, your storage needs will look very different from someone generating terabytes of high-resolution images or genetic sequencing data.

While it is tempting to just use a personal Dropbox or buy an external hard drive, we strongly recommend using the university’s official storage services (managed by the ZID). Think of them as a secure, worry-free home for your research. By using them, you get:

* Automatic backups: If your laptop gets stolen or you spill coffee on it, your data is still safe and sound.
* Easy sharing: You can easily show your work to your supervisor or collaborators without sending massive email attachments.
* Safety and privacy: Your data is kept secure and complies with privacy laws, which is especially important if you are working with sensitive information.
* Tech support: If something goes wrong, there is an IT team ready to help you sort it out.

Here is a quick cheat sheet of the different storage options available to you at the University of Vienna:

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

Even with the absolute best setup, things can still go wrong. Laptops get stolen, coffee gets spilled, hard drives crash, and sometimes you just accidentally hit "delete" on a file you actually needed. That is why having a solid backup routine is your ultimate safety net.

![XKCD Data Trap](https://imgs.xkcd.com/comics/backups.png " [Backups by XKCD](https://xkcd.com/1718/), [CC BY-NC 2.5](https://creativecommons.org/licenses/by-nc/2.5/legalcode0)")

**The 3-2-1 Rule**

If your project doesn't involve highly sensitive data, the easiest way to keep your work safe is the 3-2-1 Rule:

* 3 copies: Keep your main working file and at least two backup copies.
* 2 different types of media: Save them on different devices (for example, your laptop’s hard drive and a university cloud service).
* 1 offsite location: Keep at least one copy in a different physical place (like storing it on the university network rather than on an external drive sitting right next to your laptop at home).

Many university storage services already include automated backups, but it is important to understand what is—and is not—being backed up.

**Two Things to Keep in Mind:**

1. Test your backups (seriously!)

A backup is only helpful if it actually works. Every now and then, try restoring a few files from your backup just to make sure they open properly and nothing is corrupted. You don't want to find out your backup system has been failing for months on the day your laptop dies.

2. Hard drives don't live forever

USB sticks get lost, external hard drives crash, and even CDs degrade over time. No physical storage device lasts forever. This is another major perk of using the university's managed storage—their IT team constantly monitors the hardware and moves your data to new systems before the old ones fail.

## Data Security (a bit too lengthy, need to rework and add some links)

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

Research is rarely a solo sport. Whether you are collaborating with your supervisor, working with a lab mate, or teaming up with researchers on the other side of the world, you will need to share files.

But we’ve all been there: emailing files back and forth, ending up with confusing filenames like data_analysis_v2_final_corrected_FINAL.csv, and having no idea which version is actually the latest one.

Before you hit "share," take a quick second to ask yourself:

* Who actually needs to see this? (Does your whole team need access, or just one person?)
* What can they do with it? (Do they just need to read/view the data, or do they need to edit it?)
* How will we track changes? (If three people edit a file at the same time, will it create a mess?)
* Is any of it sensitive? (If yes, standard email is a big no-no).

To keep things organized and secure, step away from email attachments and personal Dropboxes. Instead, use the university-supported tools built specifically for this:

**Choosing the Right Tool**

Different collaboration tasks require different services.

| Purpose | Recommended service |
|----------|--------------------|
| Collaborative document editing | OneDrive, u:cloud |
| Team file storage | Share, u:cloud Pro |
| Source code and version control | GitHub, GitLab |
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

Here are three quiz questions matching your format and friendly tone, based on the sections we just worked on:

## Quiz

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
