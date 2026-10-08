---
title: Autopsy (software) - Wikipedia
source: https://en.wikipedia.org/wiki/Autopsy_(software)
author:
  - "[[Contributors to Wikimedia projects]]"
published: 2013-01-31
created: 2025-12-23
description:
tags:
  - windows
---
**Autopsy** is a [computer program](https://en.wikipedia.org/wiki/Computer_program "Computer program") that performs [forensic searches](https://en.wikipedia.org/wiki/Forensic_search "Forensic search") of [computer storage volumes](https://en.wikipedia.org/wiki/Volume_\(computing\) "Volume (computing)"). It is maintained by [Basis Technology Corp.](https://en.wikipedia.org/wiki/Basis_Technology_Corp. "Basis Technology Corp.") and community programmers. Basis Technology Corp. sells support services and training for the program.

## Features

### Cataloguing

Autopsy [hashes](https://en.wikipedia.org/wiki/Hash_function "Hash function") the files in the [volume](https://en.wikipedia.org/wiki/Volume_\(computing\) "Volume (computing)") it is analyzing, unpacking [compressed archives](https://en.wikipedia.org/wiki/Archive_file "Archive file") including [ZIP](https://en.wikipedia.org/wiki/ZIP_\(file_format\) "ZIP (file format)") and [JAR](https://en.wikipedia.org/wiki/JAR_\(file_format\) "JAR (file format)"). It extracts image [metadata](https://en.wikipedia.org/wiki/Metadata "Metadata") stored as [Exif](https://en.wikipedia.org/wiki/Exif "Exif") values and stores keywords in an index. Further, Autopsy [parses](https://en.wikipedia.org/wiki/Parsing "Parsing") and [catalogues](https://en.wikipedia.org/wiki/Cataloging_\(archival_science\) "Cataloging (archival science)") some email and contact file formats, flags phone numbers, email addresses, and files, as well as [SQLite](https://en.wikipedia.org/wiki/SQLite "SQLite") or [PostgreSQL](https://en.wikipedia.org/wiki/PostgreSQL "PostgreSQL") database stores occurrences of names, domains, phone numbers, and [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows "Microsoft Windows") registry files indicating past connections to [USB](https://en.wikipedia.org/wiki/USB "USB") devices. Multiple file systems can be catalogued in the same repository.

### Search

Autopsy can perform rule-based searches of indexed files, including searches for recent activity. It can generate reports in [HTML](https://en.wikipedia.org/wiki/HTML "HTML") or [PDF](https://en.wikipedia.org/wiki/PDF "PDF") format containing the results of searches. A partial image of files returned by a search can be saved in [VHD](https://en.wikipedia.org/wiki/VHD_\(file_format\) "VHD (file format)") format.

### File recovery

Autopsy can be used to recover data that has been infected by [WannaCry](https://en.wikipedia.org/wiki/WannaCry "WannaCry") [ransomware](https://en.wikipedia.org/wiki/Ransomware "Ransomware").[^2]

### Tools

Autopsy includes a [graphical user interface](https://en.wikipedia.org/wiki/Graphical_user_interface "Graphical user interface") to display its results, [wizards](https://en.wikipedia.org/wiki/Wizard_\(software\) "Wizard (software)") and historical tools to repeat configuration steps, and [plug-in](https://en.wikipedia.org/wiki/Plug-in_\(computing\) "Plug-in (computing)") support. Both open-source and closed-source Modules exist for the core browser, including functionality related to scanning files, browsing results, and summarizing findings.

## File systems

Supported file systems include:

- [NTFS](https://en.wikipedia.org/wiki/NTFS_links "NTFS links")
- [FAT](https://en.wikipedia.org/wiki/FAT_file_system "FAT file system")
- [ExFAT](https://en.wikipedia.org/wiki/ExFAT "ExFAT")
- [HFS+](https://en.wikipedia.org/wiki/HFS_Plus "HFS Plus")
- [Ext2](https://en.wikipedia.org/wiki/Ext2 "Ext2")
- [Ext3](https://en.wikipedia.org/wiki/Ext3 "Ext3")
- [Ext4](https://en.wikipedia.org/wiki/Ext4 "Ext4")
- [YAFFS2](https://en.wikipedia.org/wiki/YAFFS "YAFFS")

## Dependencies

Autopsy runs [open source programs](https://en.wikipedia.org/wiki/Open-source_software "Open-source software") and [plugins](https://en.wikipedia.org/wiki/Plug-in_\(computing\) "Plug-in (computing)") included in [The Sleuth Kit](https://en.wikipedia.org/wiki/The_Sleuth_Kit "The Sleuth Kit").[^3] It depends on a number of libraries with various licenses.[^4] It uses [SQLite](https://en.wikipedia.org/wiki/SQLite "SQLite") and [PostgreSQL](https://en.wikipedia.org/wiki/PostgreSQL "PostgreSQL") databases to store information. Its keyword search indices are built with [Lucene](https://en.wikipedia.org/wiki/Apache_Lucene "Apache Lucene") and SOLR.

## Version history

| Version | Language | Operating systems | License |
| --- | --- | --- | --- |
| 2.0 | [Perl](https://en.wikipedia.org/wiki/Perl "Perl") | [Linux](https://en.wikipedia.org/wiki/Linux "Linux"), [Unix](https://en.wikipedia.org/wiki/Unix "Unix"), [MacOS](https://en.wikipedia.org/wiki/MacOS "MacOS"), [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows "Microsoft Windows") | [GNU GPL](https://en.wikipedia.org/wiki/GNU_GPL "GNU GPL") 2.0 [^4] |
| 3.0 | [Java](https://en.wikipedia.org/wiki/Java_\(programming_language\) "Java (programming language)") |  | [Apache license](https://en.wikipedia.org/wiki/Apache_license "Apache license") 2.0 [^4] |
| 4.0 | Java | Windows, Linux, MacOS | Apache license 2.0 [^4] |

## References

## External links

- [Autopsy official website](https://www.autopsy.com/)
- [The Sleuth Kit official website](https://www.sleuthkit.org/)

[^1]: ["releases"](https://github.com/sleuthkit/autopsy/releases). *github.com*. Retrieved May 16, 2025.

[^2]: S. C. Nayak, V. Tiwari and B. K. Samanthula, "Review of Ransomware Attacks and a Data Recovery Framework using Autopsy Digital Forensics Platform," 2023 IEEE 13th Annual Computing and Communication Workshop and Conference (CCWC), Las Vegas, NV, USA, 2023, pp. 0605–0611, doi: 10.1109/CCWC57344.2023.10099169.

[^3]: ["The Sleuth Kit (TSK) & Autopsy: Open Source Digital Forensics Tools"](https://www.sleuthkit.org/). Brian Carrier.

[^4]: ["Autopsy: License"](https://www.sleuthkit.org/autopsy/licenses.php). Brian Carrier.
