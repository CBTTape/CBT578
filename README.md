# CBT578
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 578 is from Roy Gardiner, and contains a general ISPF     *   FILE 578
//*           table handling facility, which allows you to drive    *   FILE 578
//*           your own ISPF panels with an easily creatable table   *   FILE 578
//*           update utility of your own making.                    *   FILE 578
//*                                                                 *   FILE 578
//*     ISPF general table handler                                  *   FILE 578
//*     --------------------------                                  *   FILE 578
//*                                                                 *   FILE 578
//*     Provided by Roy Gardiner    version 1.0 May 2002            *   FILE 578
//*                                                                 *   FILE 578
//*     Please e-mail comments and questions to:                    *   FILE 578
//*     roy@roygardiner.com                                         *   FILE 578
//*                                                                 *   FILE 578
//*     Summary                                                     *   FILE 578
//*     -------                                                     *   FILE 578
//*                                                                 *   FILE 578
//*     This package will enable you to maintain any ISPF table     *   FILE 578
//*     which has one or two key fields. You only need to code,     *   FILE 578
//*     by copying the examples given here, (1) a scrollable        *   FILE 578
//*     display for the whole table (2) a display panel for         *   FILE 578
//*     full details of a single row.  The benefit of the           *   FILE 578
//*     package is that it enables you to create in a few           *   FILE 578
//*     minutes a table update utility using your own panels.       *   FILE 578
//*                                                                 *   FILE 578
//*     Basic features provided                                     *   FILE 578
//*     -----------------------                                     *   FILE 578
//*                                                                 *   FILE 578
//*     Just by cloning the sample panels you will be able to:      *   FILE 578
//*                                                                 *   FILE 578
//*       - see a scrollable display of your table                  *   FILE 578
//*       - use the Locate command to find rows                     *   FILE 578
//*       - sort the table display                                  *   FILE 578
//*       - display extra information which will not fit on a       *   FILE 578
//*           single display line                                   *   FILE 578
//*       - update the table (multiple users)                       *   FILE 578
//*       - protect against concurrent update                       *   FILE 578
//*       - edit any number of extension variables to any row,      *   FILE 578
//*           without knowing the names of the variables            *   FILE 578
//*       - provide simple data dictionary (along the lines of:     *   FILE 578
//*           this is a variable name, this is what it means)       *   FILE 578
//*                                                                 *   FILE 578
//*     (Note that this package does NOT handle non-keyed tables)   *   FILE 578
//*                                                                 *   FILE 578
//*     The benefit of using the package is development speed;      *   FILE 578
//*     all you need to do is to modify the example panels to       *   FILE 578
//*     match your table layout - a few minutes work.               *   FILE 578
//*                                                                 *   FILE 578
//*     The package is not designed to handle large volumes of      *   FILE 578
//*     data; for tables larger than 1000 rows which need to be     *   FILE 578
//*     updated by more than about a dozen people, consider DB2     *   FILE 578
//*     or another proper database.  Large tables combined with     *   FILE 578
//*     many users create unacceptable performance and              *   FILE 578
//*     especially update contention issues.                        *   FILE 578
//*                                                                 *   FILE 578
```
