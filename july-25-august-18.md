# _July 25-August 18_

From July 26-29, I took a break from my fieldwork to attend the Society of American Archivists national conference, [ARCHIVES 2017](https://www2.archivists.org/am2017), in Portland Oregon.

## Born-digital Processing Manuals

I continued work on manuals for processing born-digital materials through this period. In the course of creating manual content I inserted a large number of comments in the text, the purpose of which is to help me finalize a consistent, polished set of documentation. The final stage of work on this deliverable will be resolving these comments and performing copyediting and content-checking, to be completed by August 24. Following this, the manual set will be available via a link to anyone with a UW email address.

All manual sections will include version and contributor information, and be licensed under a Creative Commons [Attribution-NonCommercial 4.0 International](http://creativecommons.org/licenses/by-nc/4.0/) license, to facilitate future expansion and re-use of the documentation.

### _Note: The draft manuals can be viewed [here](https://drive.google.com/file/d/1tq0VwQp1xxNWqVGwSwHt7EKgcwEQPoVn/view?usp=sharing)._

## Workflow Testing and Feedback

As mentioned in a [previous post](/july-1-6.md), UW Special Collections is currently working to document and streamline the processing of born-digital collections. As part of this process, a working group has created a beginning-to-end test workflow for ingest, processing, appraisal and curation, and preservation of born-digital materials. This workflow and others in use at Special Collections was created in the [Asana](https://asana.com/) project-management web application.

An accession containing two physical carriers—one CD and one flash drive—was selected to pilot the workflow. After Special Collections staff had completed intake and accessioning steps, I was asked to complete the subsequent two sets of technical-processing tasks.

I imaged and analyzed the CD and flash drive using much of the same software I had used with 3.5-inch floppy discs included in a UW School of Public Health accession. As I recorded my progress in the Asana web application, I was able to edit and comment on each task to more accurately reflect the actions I had taken. These changes can then be compared to the original version of the workflow to further assess and improve it.

Following this I met with a policies and procedures working group[^1] to discuss my experience with the workflow. One specific challenge I had encountered was that many tasks were broadly defined, including aspects of technical processing alongside subject-area curation tasks. As an example of this, in the version of the workflow I used, tasks such as running reports on file types, personally-identifiable information, and directory structure were grouped together with the tasks of identifying material for removal from the accession and making decisions about how it should be organized and presented.

As a result of the discussion in this meeting, the workflow was edited to clearly demarcate technical processing on the one hand and curatorial decision-making on the other. The group hopes that these adjustments will clarify each step in this section of the workflow and make it easier to assign tasks appropriately.

### Software tools:

To complete the technical processing required for this workflow, I used a number of software packages for the first time.

* [FSlint](http://www.pixelbeat.org/fslint/) \(BitCurator environment\): Used to identify duplicate files in a given directory

* [TreeSize Free](https://www.jam-software.com/treesize_free/): A Windows application that creates easy-to-read representations of hierarchical directory structure and file formats

* [JR Directory Printer](http://www.spadixbd.com/freetools/jdirprint.htm): A Windows application that outputs directory contents to a plain text file

## Assessing Software for Email Archive Processing and Access

The third learning outcome for my directed fieldwork was to “\[g\]ain experience in researching software tools and platforms and assessing their feasibility of use in site-specific conditions.” One component of this goal was to participate in what will be a long-term effort to identify and evaluate digital preservation and access software for use at the UW Libraries Special Collections. While this effort has begun, it is still in early stages, with a list of functional requirements for software still being compiled. My participation has been minimal, and as a result, this component did not contribute significantly to achieving the learning outcome.

However, I have progressed in my individual work in assessing software for processing and providing access to email archives.

In consultation with my supervisor, I selected two applications to assess for use at UW Special Collections: [SysTools Outlook to PDF Converter](https://www.systoolsgroup.com/outlook-pst-to-pdf-converter.html) \(v.2.0.0.0\), proprietary software, and [ePADD](https://library.stanford.edu/projects/epadd), an [open-source software package](https://github.com/ePADD) developed by Stanford University's Special Collections & University Archives.

### SysTools Outlook to PDF Converter

The Outlook to PDF Converter generates individual PDF files from email threads, including attachments, which in most cases can then be opened easily in their default applications. However, the program lacks functionality for searching for and filtering messages. While newer versions include date-filtering capabilities, the older version in use in Special Collections does not. Once within a folder in the Outlook archive, there are no search capabilities, and messages cannot be sorted by date, sender, or other attributes. Messages may be selected either one at a time, or en masse with the option to deselect individual messages.

While the stability and compatibility of the PDF format makes it a good choice for providing patrons with access to archived emails, the lack of functionality here presents a real problem. The lack of ability to search for emails, to group and/or batch-edit them, or to perform any kind of redaction, seem to me to make this application useless in all but accessions with very small amounts of email data.

### ePADD

This application runs on Java and opens in a web browser, and comprises four distinct modules: appraisal, processing, discovery, and delivery. The following overview of these modules is not meant to be comprehensive, but rather to briefly outline features I explored during testing using a personal email archive[^2]. \(For a more complete overview of ePADD functionality, see the most current version of the [ePADD Installation and User Guide](https://docs.google.com/document/d/1joUmI8yZEOnFzuWaVN1A5gAEA8UawC-UnKycdcuG5Xc/edit#).\)

In order to offer a variety of searching and filtering functions, ePADD automatically performs processing on imported archives. During the initial import, named entity recognition is carried out to identify correspondents, persons mentioned, and other entities such as organizations and companies. By selecting any of these entities from the browsing menu—for example a particular correspondent—all messages from and to them can be viewed. Messages can be marked for exclusion from the transfer to a repository, flagged as having been reviewed, or annotated. Any of these actions can be carried out either on a single message, or applied to the entire group.

ePADD also offers a lexicon search function, in which users can select from preset groups of words, organized around themes such as “job,” “legal,” “student,” “health,” and “personal.” While the use of this searching is meant to help easily identify messages which may contain sensitive information, my searches had mixed results. A search using the Personally Identifiable Information Lexicon returned primarily listserve messages discussing the need for government to support social programs, with one message returned seemingly only because the character string “ss” was included in an html tag. Lexicons can be edited and/or created entirely by users, which may enhance their functionality for specific purposes. Selecting the “Regex” lexicon will allow users to search using regular expressions to return messages with credit cards or social security numbers.

In addition to the search and filtering methods listed above, users can browse the folder structure of the archive, as well as attachments and images contained in the data. The selection of an individual image or attachment takes the user to the source message.

#### ePADD modules

The appraisal module was conceived for use by donors, who can perform an initial sort of their email archive and select any messages which should not be passed on to the repository.

Once data has been exported from the appraisal module, the processing module allows archivists to perform the same functions: searching for, grouping, and viewing messages using a variety of search techniques; selecting messages to exclude from patron access; adding annotations; and flagging reviewed messages to track progress in preparation for access. Additionally, collection-level metadata can be entered here, and images can be assigned to collections to enhance visual display in the delivery module.

The discovery module is designed to allow patrons limited remote access to email archives via the internet. Message content is heavily redacted in this module, so that while patrons can search for messages using entities or correspondents, for example, they cannot view message text. This is intended to assist in situations where travel would be required to visit an institution, allowing patrons to gain an idea of whether or not the email archive includes subject matter they are interested in.

Once the archivist has reviewed and annotated messages, removing those which should not be available for access due to the presence of sensitive information or for other reasons, they can be exported to the delivery module for access by patrons. While this module provides all of the search functionality included in previous modules, editing functionality is more limited. Patrons can mark messages as reviewed and add annotations, and these changes may be saved at the end of a viewing session. These patron edits can easily be removed via a settings menu. One additional function is the ability to put messages in a cart. Returning to this cart allows patrons to export selected messages in mbox format if access policies allow for this, or simply to return to the list of saved messages for subsequent viewing.

### Potential for use in Special Collections

A “Virtual Vault” computer in the Special Collections reading room could be used to provide access to email archives using one or both of these programs. Because this machine is not connected to the Internet and no USB or other ports are accessible to patrons, it would be a relatively secure platform for this access.

PDF files output from the Outlook to PDF Converter application would be simple to load onto this machine, and if easy-to-understand directory structures and file-naming conventions were created, would offer some level of navigability. ePADD’s delivery module could also be installed here, allowing patrons a more fully-featured browsing experience.

A number of challenges remain, however, primarily the need to redact messages to protect privacy and safeguard personally-identifiable information. Outlook to PDF Converter provides no message redaction capabilities, and while ePADD’s discovery module redacts message contents viewed by remote users, I found no such functionality in the delivery module. This seems to leave two choices for patron access: provide messages in their entirety, or not at all. In this situation, an assessment of the risk associated with providing access and clear policies for including and excluding messages in data accessible to patrons would be essential.

[^1]: See “Other Work” in [this post](/july-1-6.md) for information about this and other working groups in Special Collections.

[^2]: I imported a web-based email account into Outlook, exported it as a .pst file, converted to mbox format, and finally imported it into the ePADD environment.

