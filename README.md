# Awesome-Ediscovery

## Top E-Discovery Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Legal Document Review, Forensic Data Processing, Early Case Assessment & Production*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **E-Discovery**. These tools help legal teams, forensic investigators, and litigation support professionals collect, process, review, and produce electronically stored information (ESI) for litigation, investigations, and regulatory compliance.



**Examples** include Relativity, Everlaw, DISCO, Reveal, Logikcull, Casepoint, Nextpoint, CloudNine, OpenText Axcelerate, and Exterro (the category leaders).



**Open-source emphasis**: This section documents every major active project for self-hosting, custom processing pipelines, and transparent review workflows — ideal for legal teams that need full control over sensitive case data without per-gigabyte SaaS pricing or vendor lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Relativity](https://www.relativity.com/)**  

  The dominant e-discovery platform for large law firms and corporations. Provides document review workflows, analytics, search, case management, and production. RelativityOne is the cloud-native version. Enterprise-scale pricing with significant implementation costs.



- **[Everlaw](https://www.everlaw.com/)**  

  Cloud-native e-discovery platform known for collaborative review, predictive coding, and intuitive interface. Popular with law firms and government agencies.



- **[DISCO](https://www.csdisco.com/)**  

  AI-powered e-discovery platform with automated document review, legal hold, and case management. Focuses on speed and ease of use for litigation teams.



- **[Reveal](https://www.revealdata.com/)**  

  AI-powered e-discovery and review platform. Provides processing, review, analytics, and production with strong AI capabilities including predictive coding and technology-assisted review.



- **[Logikcull](https://www.logikcull.com/)**  

  Cloud-based e-discovery platform designed for simplicity and speed. Popular with small to mid-sized law firms and corporate legal departments for quick, affordable document review.



- **[Casepoint](https://www.casepoint.com/)**  

  Cloud-based e-discovery and legal hold platform serving corporations, law firms, and government agencies. Provides data processing, review, analytics, and case management.



- **[Nextpoint](https://www.nextpoint.com/)**  

  Cloud e-discovery and trial preparation platform. Provides document review, deposition management, and trial presentation tools in a unified system.



- **[CloudNine](https://cloudnine.com/)**  

  E-discovery and legal document review platform. Provides data processing, review, and production with a focus on simplicity and affordability.



- **[OpenText Axcelerate](https://www.opentext.com/)**  

  E-discovery and investigation platform within OpenText's legal technology suite. Provides processing, review, analytics, and production for litigation and investigations.



- **[Exterro](https://www.exterro.com/)**  

  Integrated e-discovery and legal GRC platform. Provides legal hold, collection, processing, review, and production alongside data privacy and forensic capabilities.



## Open-Source GitHub Projects



- **[FreeEed](https://github.com/shmsoft/FreeEed)**  

  The most established open-source e-discovery tool. Built on Hadoop, HDFS, Solr, and MapReduce for handling large volumes of data (100s GB to terabytes) . Features GUI dashboard, full-text search, preview/tagging, chain of custody preservation, and scalable deployment from laptop to cloud. Comes as virtual machines for easy adoption across Mac, Windows, and Linux. Design goals include stability, extensibility, and preservation for long-term archiving . **Apache-2.0** .



- **[IPED](https://github.com/sepinf-inc/IPED)**  

  Production-grade open-source forensic platform developed by the Brazilian Federal Police since 2014. Turns large evidence collections into searchable, timeline-driven investigations. Handles E01, AFF, raw DD, iOS, Android, PST, OST, MBOX, cloud exports, and file system containers. Features Apache Lucene full-text indexing, hash-based deduplication, known-file filtering, timeline visualization, and review workflows. Scales to hundreds of gigabytes or terabytes. Considered a viable alternative to Autopsy and can take on some of Nuix's workload for massive evidence sets. Documentation is more Portuguese-oriented than English . **Open source**.



- **[rex (RexLit)](https://github.com/bginsber/rex)**  

  Offline-first UNIX litigation SDK/CLI for e-discovery and legal timeline management. Features document ingestion with metadata extraction, full-text search index building, privilege detection (Groq-powered classification with confidence scores), OCR for scanned documents, Bates numbering for PDFs, court-ready production set creation (DAT format), and deadline tracking with ICS calendar export for jurisdictions like Texas. Includes audit trail verification and hash-chain logging. Experimental React UI bridges to CLI through Bun/Elysia API . **Open source**.



- **[Autopsy](https://github.com/sleuthkit/autopsy)**  

  The most widely used open-source digital forensics platform and graphical interface to The Sleuth Kit. Can be used by law enforcement, military, and corporate examiners to investigate what happened on a computer. Features image/video gallery, communications visualization (email, social media, messaging), timeline editor, plugin extension system, Python module support, and simple tagging. **Apache-2.0**. Considered the best free/open-source alternative to Nuix for Windows, Linux, and Mac .



- **[Tabular Review for Lawyers](https://github.com/Kevin-Tucuxi/Tabular_Review)**  

  AI-powered document review workspace that transforms unstructured legal contracts into structured, queryable datasets. Features AI-powered extraction using Google Gemini, high-fidelity PDF/DOCX conversion via Docling (running locally), dynamic schema with natural language prompts, verification with source citations, spreadsheet interface, and integrated chat analyst. **MIT License** .



- **[FreeDiscovery](https://github.com/FreeDiscovery/FreeDiscovery)**  

  Web Service for E-Discovery Analytics. Python-based tool for document clustering, categorization, and similarity analysis in legal discovery contexts. ~73 stars .



- **[OpenDiscoverPlatformCaseStudy](https://github.com/dotfurther/OpenDiscoverPlatformCaseStudy)**  

  Case study using dotfurther's Open Discover Platform with RavenDB document store to rapidly create full-text search, e-discovery, and information governance demonstration applications .



- **[enigma](https://github.com/McFlip/enigma)**  

  eDiscovery tool for bulk decryption of emails in a batch of PST files, written in Go. Handles encrypted email extraction for forensic and legal review workflows .



- **[loadfile](https://github.com/gojefferson/loadfile)**  

  Convert .DAT load files to CSV or JSON. Load files are standard e-discovery production formats that map document images and metadata for review platforms. Essential utility for interoperability between systems .



- **[Sequence](https://github.com/reductech/sequence)**  

  Core SDK for building steps and sequences in e-discovery workflows. Interpreter and runtime for Sequence Configuration Language. Includes connectors for Relativity, filesystem, Tesseract OCR, SQL, REST, and structured data. Enables custom pipeline construction for processing and review workflows .



- **[RelativityOne-Bookmarklets](https://github.com/jankais3r/RelativityOne-Bookmarklets)**  

  Collection of bookmarklets for Relativity(One) administrators. Browser-based utilities for administrative tasks within the Relativity interface .



- **[ps-folderizer](https://github.com/andre-abadi/ps-folderizer)**  

  PowerShell eDiscovery Automatic Folderizer for Ringtail/NUIX Discover Imports. Automates file organization for import into review platforms .



- **[ps-bates-enumerator](https://github.com/andre-abadi/ps-bates-enumerator)**  

  PowerShell eDiscovery Automatic Bates File Enumerator. Automates Bates numbering workflows for production .



- **[dotnist](https://hub.docker.com/r/elemtart/dotnist-grpc)**  

  Like deNIST except dotnet. Intended to help identify NIST files in e-discovery processing. Docker container with gRPC server and included SQLite database for NIST file lookups .



### Additional Strong Open-Source Options



- **Full-Text Search Infrastructure**: **Apache Solr** (powers FreeEed's search), **Apache Lucene** (powers IPED's indexing), **Elasticsearch** for custom review platforms .

- **Forensic Processing**: **The Sleuth Kit** (command-line forensic tools underlying Autopsy), **Volatility** (memory forensics), **Plaso/log2timeline** (timeline creation).

- **Document Management**: **Paperless-ngx** (document management with search), **Lemmary** (self-hosted document library with AI-assisted search, OCR, and review workflows).

- **Legal Document Review**: **CaseBox** (HURIDOCS, fine-grained permissions for human rights legal work), **OpenSociety Foundations' VIS** .



**Frameworks for building custom systems**: Combine **FreeEed** for Hadoop-based scalable processing and Solr search, **IPED** for forensic-grade evidence processing and timeline analysis, **rex** for offline-first litigation workflows with privilege detection and Bates numbering, and **Autopsy** for digital forensics investigation. Add **Apache Tika** for content extraction, **Tesseract** for OCR, and **PostgreSQL** for metadata storage.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- E-discovery platforms handle sensitive legal and personal data; ensure compliance with relevant legal ethics rules, data protection regulations, and preservation obligations.

- **Open-source reality**: **FreeEed** and **IPED** are the most mature open-source e-discovery platforms, but neither matches the full workflow polish of commercial platforms (Relativity, Everlaw). FreeEed is built on older Hadoop infrastructure; IPED has more Portuguese documentation than English. For production litigation support, expect significant configuration and validation effort .



---



**Made for litigation support professionals, forensic examiners, legal technologists, and e-discovery practitioners.**  

Let's make e-discovery more open, transparent, and accessible.
