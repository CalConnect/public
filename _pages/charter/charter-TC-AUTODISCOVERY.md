---
layout: toc-type
title: CalConnect AUTODISCOVERY Technical Committee
parent: "/charter"
mainParent: "charter"
parents: "charter:/charter"
order: 3
published: false
---

# CalConnect AUTODISCOVERY Technical Committee

## Background

There are currently various systems in place for discovery and configuration of individual protocols, but the process can often require a series of requests using different protocols to discover all of the details needed to set up the various client services which an individual might use to interact with an organisation or provision a new device.

Consider a new employee at "Widget Enterprises". The employee needs to configure his e-mail program to use IMAP + TLS on port 143 against mail.widget.com, he needs to send mail on port 8557 via TLS+SMTP to smtp.widget.com, his calendar is on port 8443 at https://caldav.widget.com:8443/calendar/, and so forth. Some of these things can be discovered relatively easily, but the combination of DNS queries (including SRV lookups, certificate checking, and http requests) is complex; furthermore, some things cannot be discovered readily at all. Similarly, an individual acquiring a new smartphone and wishing to configure services such as e-mail, calendar and perhaps address book faces this experience with far less knowledge and ability to cope with the complexity.

## Charter

TC AUTODISCOVERY will define and produce a standard protocol which will allow discovery of a variety of services in as few HTTP requests as possible, allowing developers to simplify the user interface in client software, and in particular in multi-function client software such as a combined e-mail and calendar client, or a multi-function device such as a smartphone.

This protocol is intended to allow discovery of services based on internet standard protocols, and should be based on existing technology and protocols to the extent possible, to ease the adoption of the new autodiscovery mechanism by developers.

In order to provide a standard which can be agreed in a timely manner, and which is flexible enough to cover a wide variety of current and future protocols, it is expected that this standard will provide the framework and a registry of services, each of which will define their own set of parameters and which will be extended over time.

## Out of Scope 

- 
 
## Deliverables

-

## Begin and End Dates

* **Begin:** June 2012
* **End:** tbd

## Milestones and Work Products

| Period | Milestone |
| --- | --- |
| June 2012 |	Participate in IETF APP list discussion and achieve consensus on protocol base |
| August 2012 |	Complete initial protocol specification |
| August 2012 |	Initial submission of [Autodiscovery](https://datatracker.ietf.org/doc/draft-daboo-aggregated-service-discovery/) Internet Draft to IETF |
| October 2012 |	Review protocol specification at CalConnect XXV in Zurich |
| January 2013 |	Interoperability testing of first implementations at CalConnect XXVI |
| June 2013 |	On hold pending discussion on IETF mailing lists |

## API Mailing List

You must be an employee of a Consortium member to be subscribed to this mailing list.
You must be subscribed to the TC AUTODISCOVERY mailing list to post messages to this mailing list.

[tc-autodiscovery-l](mailto:tc-autodiscovery-l@lists.calconnect.org)

Participation on the AUTODISCOVERY mailing list will be in accordance with standard CalConnect practices and procedures.

## Chair 

Marten Gajda, dmfs ([marten@dmfs.org](mailto:marten@dmfs.org))

Please contact the Chair for more information or to join this Technical Committee.
