---
inFeed: true
hasPage: true
inNav: true
inLanguage: null
keywords: []
description: 'There are far too many Oracle 11g new features for all of them to be covered in depth even if we were to write a book on them), so this is just a bird’s eye view of a few of the enhancements and new features along with links to more information in the following areas: '
datePublished: '2016-04-28T16:55:42.095Z'
dateModified: '2016-04-28T16:54:51.328Z'
title: ''
author: []
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
starred: false
sourcePath: _posts/2016-04-28-oracle-11g-new-features-overview.md
published: true
url: oracle-11g-new-features-overview/index.html
_type: Article

---
# Oracle 11g New Features Overview

There are far too many Oracle 11g new features for all of them to be covered in depth even if we were to write a book on them), so this is just a bird's eye view of a few of the enhancements and new features along with links to more information in the following areas: 

* performance
* grid computing
* data warehousing/business intelligence
* change management
* SQL
* PL/SQL 

## Oracle 11g Performance enhancements

Performance enhancements worth mentioning include those made to SecureFiles (the large objects (LOB) infrastructure), the new results cache for SQL and PL/SQL and PL/SQL native compilation. 

### Oracle SecureFiles enhancements

LOBs can now be compressed and encrypted and de-duplicated automatically, thereby reducing LOB storage requirements and making their handling much easier and faster. 

### Query results cache

Oracle 11g now enables the results of deterministic PL/SQL functions and SQL queries to be saved in the results cache area of the shared pool. The results cache is enabled via the result\_cache\_mode system parameter which has two values: 

* MANUAL - result caching is activated by a query hint 

* FORCE -all results are cached (when it is valid to do so). 

The result\_cache\_mode parameter can be modified at the session and system levels. The size of the results cache is set by the result\_cache\_max\_size system parameter. 

### PL/SQL compilation

Auto-compilation of Oracle 11g PL/SQL to native code without the need for a separate C compiler is the other big performance enhancement. Highly processor-intensive PL/SQL routines may be of an order of magnitude faster than in 10g. 

[See the Oracle documentation for more details. ][0]

## Oracle 11g Change Management Enhancements

One of the more significant enhancements in this area is what Oracle call [Real Application Testing ][1]. This feature reduces the risk of change by allowing real (i.e. production) workloads to be captured and then replayed on a test system to determine the impact of hardware or software changes.

The database replay feature also includes reporting to highlight potential issues such as errors encountered or divergence in performance and any recommend solutions. 

## Grid Computing New Features

Oracle 11g makes grid computing easy and straight forward with the enhancements to ADDM and ASM.

## ASM (Automatic Storage Management) enhancements

•a fast mirror resync when a failed disk is brought back online

•support for heterogeneous environments

•rolling upgrade to maintain database availability during patching/upgrades

•support for databases of 100s of TB in size

### ADDM (Automatic Database Diagnostic Monitor) enhancement

This has been made cluster aware in 11g so that it can detect global i/o and interconnect problems.

## Oracle 11g Data Warehousing New Features

Enhancements for data warehouses and business intelligence systems in 11g include three new partitioning options, the full integration of OLAP with the database and [new data warehousing features in SQL .][2]

### New Partitioning Options

•auto-range partitioning - eliminates the need to manually create new partitions at specific time intervals 

•composite partitioning - list-hash, list-list, list-range and range-range partitioning 

•partitioning by reference (child table references primary key of parent) 

### Integration of OLAP with the database

Oracle 11g introduces cube-organised materialized views, enabling cubes to be referenced in sql and the transparent rewrite of queries against relational tables to reference cubes instead. 

---------------------------------------

Looking to sky-rocket productivity, save time and reduce costs?

Training is a highly cost-effective and 

proven method of boosting productivity. Smartsoft offers instructor-led 

[training][3]

in Oracle and related 

technologies on or off site in cities across the UK as well as self-study 

[online training.][4]

See our scheduled [Oracle training courses,][5]

or [let us know your requirements .Oracle tips and tricks ][6]

[Subscribe to our newsletter, ][7]

jam-packed full of tips and tricks to help you slash costs, sky-

rocket productivity and make your systems better, faster and smarter.

[0]: http://docs.oracle.com/cd/B28359_01/appdev.111/b28370/tuning.htm#BABIBCBE
[1]: http://www.oracle.com/technetwork/oem/grid-control/overview/owp-real-application-testing-11g-1-129463.pdf
[2]: http://www.smart-soft.co.uk/Oracle/oracle-11g-sql-new-features-for-data-warehouses.htm
[3]: http://www.smart-soft.co.uk/oracle-and-unix-training.htm
[4]: http://www.smart-soft.co.uk/on-line-training.htm
[5]: http://www.smart-soft.co.uk/training/indexOracle.htm
[6]: http://www.smart-soft.co.uk/contactus.htm
[7]: http://eepurl.com/LXp-H