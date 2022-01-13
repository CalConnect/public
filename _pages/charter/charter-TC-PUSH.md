---
layout: toc-type
title: CalConnect PUSH Technical Committee
parent: "/charter"
mainParent: "charter"
parents: "charter:/charter"
order: 11
published: false
---

# CalConnect PUSH Technical Committee

## Background

To keep client data in sync, CalDAV and CardDAV clients need to refresh their state from the server. Typically clients will "poll" servers at regular intervals to determine if any changes have been made. This behavior is inefficient for a number of reasons: Typically a sync will not happen right after a change on the server, so the client database may be out of sync for longer periods.

High frequency polling will cause higher bandwidth and CPU consumption on both, client side and server side. In addition users expect to be notified of changes as soon as they occur - but using a short polling interval affects device performance in a negative way (more network bandwidth used, more power drain etc). A better approach is for the server to send a (push) notification to the client when data on the server has changed. This is more efficient as it avoids unnecessary network activity on the part of the client when data changes infrequently. Plus this gives users a more "real time" experience when it comes to notifications.

To date, a number of proprietary push notification schemes are in use. In many cases, the choice of protocol is dictated by infrastructure requirements of particular vendors (in particular the nature of sending push messages to mobile devices). However, these are very dependent on particular client/server vendor protocols, leading to "lock-out" - i.e. one vendor's clients won't work with another vendor's server which only supports that vendor's push protocol. This also means 3rd party client implementors are forced to potentially implement many different push protocols. In addition there are devices (like desktop computers) without a native push solution. At present these devices are not able to receive push notifications for CalDAV and CardDAV.

## Charter

TC PUSH will define a generic framework for push notifications within CalDAV (and CardDAV). One goal is to provide a common set of properties that servers advertise to clients that describe the various push mechanisms supported by the server in a standard way. Clients can then use that information to determine which push mechanism is appropriate for them to use based on their current environment. The TC will define one standard push protocol which servers will be encouraged to support. However, proprietary push protocols will also be supported with the framework. Wherever possible the TC will make use of existing protocols or technologies as opposed to creating new protocols. The TC will not consider scaleable server-to-server notifications as part of this work.

The TC will define the requirements of a push notification framework (e.g. how servers should advertise protocols to clients, how clients can subscribe to notifications, and how clients receive those notifications), looking at existing deployed push protocols.

## Out of Scope for PUSH

-
 
## Deliverables

- a CalConnect "7-things" document about push notifications
- a specification defining how servers advertise supported push protocols, and how clients can use that information to receive notifications
- a generic push protocol for CalDAV and CardDAV, based on WebDAV technologies, that will be allow clients to have one interoperable solution available, in the absence of being able to support the proprietary push protocols
- an implementation guide describing how servers and clients can efficiently implement push and poll based strategies based on overall load and other factors, such as importance of the change. This guide may be part of the main specifications

## Begin and End Dates

* **Begin:** December 2013
* **End:** tbd

## Milestones and Work Products

| Period | Milestone |
| --- | --- |
| February 2014 |	Report on requirements to the Technical Conference |
| March 2014 |	Develop and publish a 7-things document |
| January 2015 |	Initial specifications and implementation guide for push framework and generic push protocol presented to Technical Conference; initial interoperability testing |
| May 2015 |	Final specifications and implementation guide presented to Technical Conference; more detailed  |interoperability testing |
| June 2015 |	Submit internet drafts to the IETF |

## PUSH Mailing List

You must be an employee of a Consortium member to be subscribed to this mailing list.
You must be subscribed to the TC PUSH mailing list to post messages to this mailing list.

[tc-push-l](mailto:tc-push-l@lists.calconnect.org)

Participation on the PUSH mailing list will be in accordance with standard CalConnect practices and procedures.

## Chair 

Marten Gajda, dmfs ([marten@dmfs.org](mailto:marten@dmfs.org))

Please contact the Chair for more information or to join this Technical Committee.
