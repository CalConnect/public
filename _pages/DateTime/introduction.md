---
layout: toc-type
title: Timezone changes knowledge base
parent: "/DateTime"
mainParent: "DateTime"
parents: "DateTime:/DateTime"
order: 1
---

# Timezone changes knowledge base

This document is supposed to be a collection for structuring conceptual and factual information as well as emerging theories around the topic of timezone changes.

The purpose is to collect and distill knowledge from the CalConnect community to inform further discussion and output, such as the planned 2019-02 Zurich workshop and best practice documents for how to deal with timezone changes.

## EU DST documents

[State of the Union 2018 - Ending seasonal clock changes](https://ec.europa.eu/commission/priorities/state-union-speeches/state-union-2018/state-union-2018-ending-seasonal-clock-changes_en)
* The present system applies to the 2018-10-28 transition to winter time and the 2019-03-31 transition to summer time.
* The 2019-10-27 transition to winter time is optional; member states must announce by 2019-03-31 whether or not they will make it.
* After that, no seasonal changes are permitted.
* Member states can make one-off changes to a different UTC offset but must give at least 6 months notice and can't change their mind during the 6 month window (but can before that).

## Theory

### Reasons for timezone changes
* General ad hoc timezone practice (Fiji, Marocco)
* General DST considerations (economic, energy saving etc.)
* Events (e.g., Olympics)
* Elections (Turkey)
* Religious (Egypt)

### Types of timezone changes
* Change of DST rules
* Change of UTC diff
* Creating new TZID

### Empirics
* How often do timezones change: [tzdata-meta](https://tzdata-meta.timtimeonline.com/)

## Relevant timezone databases

### [IANA timezone db](https://www.iana.org/time-zones)
http://web.cs.ucla.edu/~eggert/tz/tz-link.htm#changes
"If your government plans to change its time zone boundaries or daylight saving rules, inform tz@iana.org well in advance, as this will coordinate updates too many cell phones, computers, and other devices around the world. With less than a year's notice there is a good chance that some computer-based clocks will operate incorrectly after the change, due to delays in propagating updates to software and data. The shorter the notice, the more likely clock problems will arise..."

### Databases derived from IANA

#### [Microsoft timezone db](https://support.microsoft.com/en-us/help/22803/daylight-saving-time)
"Recommendations: In order for Microsoft to provide an update at the earliest and ensure a seamless transition to new DST and TZ policies, Microsoft recommends that governments provide the following: Ample advance notice (1 year or more) of the planned change."
[https://blogs.technet.microsoft.com/dst2007/](https://blogs.technet.microsoft.com/dst2007/)

### IATA SSIM
The Standard Schedules Information Manual of the International Air Transport Association gives current time zone rules for airports served by commercial aviation.
The SSIM standards are maintained by the Schedules Information Standards Committee (SISC). New SSIM requirements and inquiries can be forwarded to SSIM@iata.org
Published only in English in March only.
[https://www.iata.org/publications/store/Pages/standard-schedules-information.aspx](https://www.iata.org/publications/store/Pages/standard-schedules-information.aspx)
IATA SSIM has - at least in the past - been used as a (comparative) source to [IANA tzdb](https://mm.icann.org/pipermail/tz/1997-March/009863.html)

## Major past timezone changes
(Timelines and press coverage)

### [2007 US EDST](https://en.wikipedia.org/wiki/Daylight_saving_time_in_the_United_States#2005%E2%80%932009:_Second_extension)

### 2014 Russian TZ changes
* 2013-12-30: First of six Russian regions announced change
* 2014-03-27: Change officially effective
* 2014-04-12: Patch for Windows Vista and later avail. by [Microsoft](https://support.microsoft.com/en-us/help/3148851/time-zone-changes-for-russia-in-windows)
* 2014-04-14: Some user providing [handcrafted patch](https://translate.google.de/translate?sl=ru&tl=en&js=y&prev=_t&hl=de&ie=UTF-8&u=https%3A%2F%2Frzhevsky.wordpress.com%2F2016%2F04%2F14%2Fkb3148851-tzupdatexp%2F&edit-text=) for WinXP / WinServer 03, which were not supported by Microsoft anymore 

### 2018 Proposal of the EU discontinuing seasonal changes
* 2018-08-31 Summertime Consultation: 84% want Europe to stop changing the clock
* 2018-09-12 Proposal for a DIRECTIVE OF THE EUROPEAN PARLIAMENT AND OF THE COUNCIL discontinuing seasonal changes of time and repealing Directive 2000/84/EC
* 2018-09-12 State of the Union 2018: Commission proposes to put an end to seasonal clock changes
* State of the Union 2018 [subpage on Seasonal Clock Changes](http://europa.eu/rapid/press-release_MEMO-18-5641_en.htm)
* 2018-10-29-30 Initial secretary-level [discussion](https://www.consilium.europa.eu/en/meetings/tte/2018/10/29-30/)
* 2019-03-31 Under the Commission’s plan, countries need to notify Brussels by March 31, 2019 what they want to do
* 2019-10 Last possible switch from DST to standard time

## Press
* [2018-10-16 Stuttgarter Nachrichten](https://www.stuttgarter-nachrichten.de/inhalt.eu-abschaffung-der-zeitumstellung-braucht-mehr-zeit.7a2c1f71-0dc7-4a3f-a2be-e7653f36948c.html)
* [2018-10-09](https://www.heise.de/newsticker/meldung/Ewige-Sommerzeit-Widerstand-aus-EU-Staaten-gegen-Ende-der-Zeitumstellung-4184638.html)


## General problems and issues
Keeping tz db up-to-date
….

## Particular problems and issues (anecdotes)


## Operation Systems distribution

### Android Versions:
* [Wikipedia](https://en.wikipedia.org/wiki/Android_(operating_system)#Platform_usage)
* [Netzwelt](https://www.netzwelt.de/update-fahrplan/android-handys-tablets-grosse-update-fahrplan.html) (German -> device -> OS)
* [Android tz Update Version >8.1](https://source.android.com/devices/tech/config/timezone-rules)

### iOS Versions:
* [Wikipedia](https://en.wikipedia.org/wiki/IOS)
* [Supportarticle](https://support.apple.com/en-us/HT206986) about how iOS handles timezone updates

### Windows versions:
* [Wikipedia](https://en.wikipedia.org/wiki/Microsoft_Windows#Usage_share_and_device_sales)



