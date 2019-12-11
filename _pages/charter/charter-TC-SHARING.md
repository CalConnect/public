---
layout: toc-type
title: CalConnect SHARING Technical Committee
parent: "/charter"
mainParent: "charter"
parents: "charter:/charter"
order: 12
---

# CalConnect SHARING Technical Committee

## Background

Users of CalDAV and CardDAV systems have the need to share calendars and address books with other users. The existing specifications for caldav-sharing and caldav-notifications provide the requirements for sharing calendars and sending and replying to invite notifications. But they do not directly address the requirements for address book sharing and notifications. Given that CalDAV and CardDAV are based on WebDAV, a more generic specification for WebDAV collection sharing and notifications that encompasses multiple resource types, including calendars, address books, files, etc, can be developed.

Additionally, subscriptions to .ics files can place a significant load on servers; even for small changes, the entire file will be downloaded by clients. 

## Charter

The Calendar and Contacts Sharing Technical Committee is chartered to extend the existing caldav-sharing and caldav-notifications specifications to support address books and other resource types. This will be accomplished by reducing the scope of the current specs and refactoring them into multiple smaller specifications focused on a specific resource or notification type. To that end the committee will define foundation specifications for WebDAV notifications and collection sharing, with sibling specifications for CalDAV sharing, CardDAV sharing, and other resource types.

The TC is also chartered to develop an enhanced subscription model which will allow servers to advertise enhanced subscription access points.  These will implement various protocol features such as sync-report and CalDAV or a CalDAV subset allowing for a more efficient update. 

## Out of Scope 

- 
 
## Deliverables

- WebDAV notifications specification (generic spec that does not define any "real" notification types)
- WebDAV collection sharing specification (also defines sharing invite/reply notifications)
- Calendar sharing specification (defines sharing and notification features specific to calendars)
- Contacts sharing specification (defines sharing and notification features specific to contacts)
- A CalConnect "7-things" document about Calendar and Contacts Sharing
- Enhanced subscription model

## Begin and End Dates

* **Begin:** June 2014
* **End:** tbd

## Milestones and Work Products

| Period | Milestone |
| --- | --- |
| May 2014 |	Present findings and recommendation for future work to CalConnect XXX (as Contacts Provisional Committee) |
| September 2014 |	Present Draft Specifications and 7-things document at CalConnect XXXI |
| October 2014 |	Submit initial versions of specifications to IETF |
| February 2017 |	Initial enhanced subscription model plus working implementations for testing at CalConnect XXXVIII |

## SHARING Mailing List

You must be an employee of a Consortium member to be subscribed to this mailing list.
You must be subscribed to the TC SHARING mailing list to post messages to this mailing list.

[tc-sharing-l](mailto:tc-sharing-l@lists.calconnect.org)

Participation on the SHARING mailing list will be in accordance with standard CalConnect practices and procedures.

## Chair 

Mike Douglass (SCG) ([mikeadouglass@gmail.com](mikeadouglass@gmail.com))

Please contact the Chairs for more information or to join this Technical Committee. 
