# CBT137
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 137 is from Billy Fenwick and contains a detailed report  *   FILE 137
//*           system, to carefully and accurately control the       *   FILE 137
//*           distribution of reports, to only those people who are *   FILE 137
//*           allowed to see them.                                  *   FILE 137
//*                                                                 *   FILE 137
//*           email:  whfenwick01@gmail.com                         *   FILE 137
//*                                                                 *   FILE 137
//*       Copyright (c) 1991-2020 William H. Fenwick                *   FILE 137
//*                                                                 *   FILE 137
//*       Permission is granted for this software product to be     *   FILE 137
//*       distributed on the CBT Tape, and it may be used by        *   FILE 137
//*       anyone, but it may not be sold.  All CBT Tape disclaimers *   FILE 137
//*       apply.                                                    *   FILE 137
//*                                                                 *   FILE 137
//*       This a general description of the package.                *   FILE 137
//*                                                                 *   FILE 137
//*       This is a COBOL/CICS/VSAM based report viewing system.    *   FILE 137
//*       While most z/OS shops today have several ways to view     *   FILE 137
//*       reports.  I believe this system is unique in the way it   *   FILE 137
//*       allows users to view reports.  There is an internal       *   FILE 137
//*       security system in place that allows users to see only    *   FILE 137
//*       the reports they have access to or parts of a report.     *   FILE 137
//*       Multiple reports for multiple dates are normally stored   *   FILE 137
//*       in the VSAM files.  Also, users are only allowed to       *   FILE 137
//*       view reports for the Bank and Branch they have access     *   FILE 137
//*       to.  While this system was written for a Bank and         *   FILE 137
//*       Branch environment it can be made to fit other formats.   *   FILE 137
//*       Division and Department, Region and Division,, etc.       *   FILE 137
//*                                                                 *   FILE 137
//*       This system has a batch process that scans (JES2)         *   FILE 137
//*       report data and builds data records, index records and    *   FILE 137
//*       history records.  The CICS access process uses the        *   FILE 137
//*       History and Index records to access the Report data.      *   FILE 137
//*       Security records are used to verify exactly what a user   *   FILE 137
//*       is allowed to view.                                       *   FILE 137
//*                                                                 *   FILE 137
//*       My intent in the general copyright stuff was to say       *   FILE 137
//*       you can you this system freely.  However I don't want     *   FILE 137
//*       someone to install and use the system then charge their   *   FILE 137
//*       customers for using it.  Also I don't want someone to     *   FILE 137
//*       sell this system or at least not sell it without          *   FILE 137
//*       including me.                                             *   FILE 137
//*                                                                 *   FILE 137
//*       Having said that we don't really have a good way to       *   FILE 137
//*       manage that either.  In the end you have to trust         *   FILE 137
//*       folks.                                                    *   FILE 137
//*                                                                 *   FILE 137
```
