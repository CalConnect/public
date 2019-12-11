---
layout: toc-type
title: CalConnect TESTER Technical Committee
parent: "/charter"
mainParent: "charter"
parents: "charter:/charter"
order: 14
---

# CalConnect TESTER Technical Committee

## Background

The Apple Darwin site hosts a CalDAV and CardDAV test suite which has very many tests covering most of the features of those protocols. This suite has been invaluable to many of us in developing our implementations. However, as time has passed, some of the tests are incorrect and need work and some of them are specific to Apple features. The full set of tests is also very comprehensive and there is no easy way to determine which tests are required for a minimal or small implementation. It is also very difficult to get a 100% pass rate.

## Charter

The goal of TC TESTER is to develop a forked version of the test suite which is less Apple specific. A further target is to define smaller sets of tests which either target specific feature sets or provide a quick regression test of major features.

Additionally the TC will develop features which allow the easy exclusion or inclusion of individual tests allowing developers to skip tests for features that may need development. Where appropriate new tests will be created in parallel to standards to support their implementation.. TC TESTER will also provide content for the Calendar Developers Guide (TC DEVGUIDE) to assist users of the test suite.

Finally, the TC will work towards a version of the test suite to be used in a certification program for CalDAV server implementations. 

## Out of Scope 

- 
 
## Deliverables

- A cleaned up set of tests
- Subsets of tests for various features and levels of implementation
- A test suite interface which maintains the state of previous runs, allows the definition of named subsets of the tests and allows implementors to exclude individual tests.

## Begin and End Dates

* **Begin:** October 2016
* **End:** tbd

## Milestones and Work Products

| Period | Milestone |
| --- | --- |
| February 2017 | Provide an initial clean subset of the tests and an initial devguide page |

## TESTER Mailing List

You must be an employee of a Consortium member to be subscribed to this mailing list.
You must be subscribed to the TC TESTER mailing list to post messages to this mailing list.

[tc-tester-l](mailto:tc-tester-l@lists.calconnect.org)

Participation on the TESTER mailing list will be in accordance with standard CalConnect practices and procedures.

## Co-Chairs 

Ralf Becker, eGroupware ([RalfBecker@outdoor-training.de](RalfBecker@outdoor-training.de))

Mike Douglass (SCG) ([mikeadouglass@gmail.com](mikeadouglass@gmail.com))

Please contact the Chairs for more information or to join this Technical Committee.
