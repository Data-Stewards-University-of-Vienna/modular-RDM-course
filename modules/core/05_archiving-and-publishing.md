
<!--
authors: Simone Spedicato, Michael Feichtinger 

email: simone.spedicato@univie.ac.at, michael.feichtinger@univie.ac.at    

version:  1.0

language: en

-->

# Archiving and Publishing 

## Objectives
Welcome to the **Archiving and Publishing** section! In this part of the course, you’ll learn why keeping research data for the long term matters, what kinds of data to keep, how to pick a good repository, and how to choose one that fits your needs.

First things first: why preserve data long term?
- It lets others verify and reuse your work, enables meta-analyses, and can boost your impact and citations.
- It helps you meet funder and journal requirements and supports FAIR and Open Science.
- It protects against data loss and tech obsolescence and keeps a clear record of your research.

But what should you preserve exactly?
- Final or processed datasets that support your publications and main findings.
- Enough raw/primary data to validate results (within ethical, legal, and practical limits!).
- Documentation: a clear README, codebooks, variable dictionaries, lab protocols, and workflows.
- Code and computing environments (e.g., requirements, containers) and key parameters to reproduce results.
- Metadata and provenance: what the data are, how they were created, and how they changed over time.

## How to Publish Data (need to be reworked from here, but main points should be present)
**To-Do: compare with old course**

Routes to publish/share (review):
- Supplements
  - Upload data files alongside a journal article as “Supplementary Information.”
  - Pros: Simple, ties data to the paper; peer-review alignment.
  - Cons: Often poor metadata; weak preservation guarantees; limited discoverability; size/type restrictions; no independent DOI in many cases.
  - Use when: Small, simple datasets tightly coupled to a single paper and journal has robust supplement hosting.

- Datasets
  - Deposit in a trusted repository that assigns a DOI, curates metadata, and preserves the data.
  - Pros: Better discoverability, citation, versioning, access controls, long-term preservation.
  - Cons: May involve submission effort, curation checks, or fees.
  - Use when: You want a citable, reusable dataset with clear licensing and preservation.

- Data Journals
  - Publish a peer-reviewed “data descriptor” article linked to a repository record.
  - Pros: Formal peer review of methods and metadata; credit for data creation; increased visibility.
  - Cons: Additional writing/review time; article APCs possible.
  - Use when: Complex datasets warrant detailed description; you seek academic credit for data.

## What do repositories do? How do they differ from storage?

Repositories/archives typically provide:
- Persistent identifiers (e.g., DOI/Handle), stable landing pages, and citations.
- Rich, standardized metadata; indexing by scholarly search engines.
- Curation and quality checks; file format normalization.
- Long-term preservation commitments (bit-level preservation, migration plans).
- Access controls, embargoes, and usage analytics.
- Versioning and provenance, links to related works (articles, code).
- Clear policies on retention, governance, sustainability.

How they differ from “storage” or syncing services:
- Storage (e.g., institutional drives, cloud sync) provides convenience and backup but no guarantees for discovery, citation, preservation, or metadata/curation.
- Repositories are for sharing, discovery, and preservation; storage is for working copies and collaboration.

Archives vs repositories:
- Overlap in practice. “Archives” emphasize long-term preservation and records management; “repositories” emphasize dissemination and access. Many trusted repositories function as archives.

## Repositories

How to select a repository:
- Scope fit: disciplinary relevance; accepts your data types/size.
- Trust and certification: CoreTrustSeal, ISO 16363, or recognized community trust.
- Persistence: PIDs (DOIs), long-term preservation policy, sustainability.
- Metadata: supports community schemas (e.g., Dublin Core, DataCite, domain standards).
- Licensing: supports open licenses and clear terms of use.
- Access options: open/restricted/controlled, embargo support, DUAs if needed.
- Compliance: meets funder/publisher requirements; ethical/legal compliance.
- Features: versioning, ORCID linking, related works, APIs, interoperability.
- Costs: deposit/curation fees, storage limits, and who pays.
- Citability and indexing: widely indexed (DataCite, Google Scholar, OpenAIRE).

Discipline-specific examples (illustrative):
- TBD

Institutional repositories:
- Pros: Supported by your university; curation help; compliance with institutional policies.
- Cons: May be generalist; size/type restrictions; variable domain discoverability.
- PHIADRA (UNIVIE Solution)

Generalist repositories:
- Zenodo (DOIs; integrates with GitHub/GitLab; no-fee up to limits).
- Figshare (institutional and public instances; DOIs).
- Dryad (curated; APC-based).
- OSF (project structure; integrations).
- Dataverse installations (Harvard Dataverse and others).
- Mendeley Data (DOIs; curation options).

Discovery tools for repositories:
- re3data.org (registry of repositories), FAIRsharing.org, OpenAIRE, NIH/NSF repository lists.

## Access Permissions and Embargos

- Open access: data publicly downloadable under an open license.
- Restricted access: metadata public; data available upon request or approval (e.g., DUAs, data access committees).
- Controlled access: stringent review, secure enclaves/VMs; often for sensitive human data.
- Embargo: delay public release until a set date or event (e.g., article acceptance). Clearly state duration and conditions; keep metadata public if possible.
- Sensitive data: de-identify/anonymize; respect consent terms; consider synthetic or aggregated releases; provide access to code and metadata even if data are controlled.
- Document any access restrictions in README and repository metadata.

## Code

Good practices:
- Use version control (Git); keep code and data separate. Avoid committing large/binary data; use Git LFS (https://git-lfs.com/) if necessary.
- Provide README, environment files (requirements.txt, environment.yml), container/Dockerfile or workflow (Snakemake/Nextflow), and tests.
- Add LICENSE and CITATION.cff for easy citation; include ORCIDs.

GitHub/GitLab + Zenodo workflow:
- Link your repo to Zenodo; create a tagged release in GitHub/GitLab.
- Zenodo archives the snapshot and mints a DOI (one concept DOI + version-specific DOIs).
- Cite the Zenodo DOI in your paper and repository README. Keep archiving for each release.

Additional archiving:
- Software Heritage captures full Git history for long-term preservation.
- For research compendia, consider depositing an artifact (code + small sample data) in a repository and link to the main dataset.

## Thinking about authorship when data sharing

- Define who qualifies as a dataset author vs contributor; use CRediT roles (https://credit.niso.org/) to document contributions (Conceptualization, Data Curation, Methodology, etc.).
- Establish authorship order and corresponding contact for the dataset record; include ORCIDs.
- Include a CONTRIBUTORS or AUTHORS file and acknowledgments (infrastructure, funding).
- Ensure consent from all contributors for release, licensing, and responsibility for updates.
- If reusing third-party data, clearly attribute sources and licenses; clarify your added value (curation, integration).

## Note about licensing (more in later section)

Choosing a license:
- Data:
  - Prefer open data licenses enabling reuse: CC0 (public domain) or CC BY 4.0 (attribution). Many repositories recommend CC0 for maximal reuse.
  - For databases: Open Data Commons (ODC-By, ODbL) may be appropriate.
  - Avoid NC/ND if your goal is open science; they limit reuse and interoperability.
  - Sensitive/consented data: license must align with consent and legal constraints; sometimes no open license is possible—use DUAs instead.
- Code/software:
  - Permissive: MIT, BSD, Apache-2.0 (patent grants with Apache).
  - Copyleft: GPL-3.0 (derivatives must remain GPL).
  - Ensure dependencies’ licenses are compatible.

Implementation:
- Include a LICENSE file in code repositories; specify license in dataset metadata and README.
- Provide a recommended citation and terms of use.
- Check IP/contractual obligations (sponsors, collaborators, institutional policies); avoid licensing data you don’t own.
- Document any third-party components and their licenses.

Citing data:
- Always cite with author(s), year, title, repository, version, and DOI. Include data availability statements in related publications.
