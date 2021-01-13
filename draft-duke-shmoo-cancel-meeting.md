---
title: Considerations for Cancellation of IETF Meetings
abbrev: Canceling Meetings
docname: draft-duke-shmoo-cancel-meeting-01
date: {DATE}
category: bcp
ipr: trust200902
area: General
workgroup: shmoo

stand_alone: yes
pi: [toc, sortrefs, symrefs, docmapping]

author:
  -
    ins: M. Duke
    name: Martin Duke
    org: F5 Networks, Inc.
    email: martin.h.duke@gmail.com

normative:


informative:

  USSTATE:
    title: International Travel
    author:
      - name: U.S. Dept. of State
    target: "https://travel.state.gov/content/travel/en/international-travel.html"
  UKFO:
    title: Foreign Travel Advice
    author:
      - name: U.K. Foreign Office
    target: "https://www.gov.uk/foreign-travel-advice"

--- abstract

The IETF firmly believes in the value of in-person meetings to reach consensus
on documents. However, various emergencies can make a planned in-person meeting
impossible. This document provides criteria for making this judgment.

--- middle

# Introduction

One highlight of the IETF calendar is in-person general meetings, which happen
three times a year at various locations around the world.

Various events could make a scheduled IETF meeting impossible, in that a
particular time or place can be largely closed to travel or assembly. These
conditions do not always have obvious thresholds. For example:

* The meeting venue itself may close unexpectedly due to a health issue, legal
violation, or other localized problem.

* A natural disaster could degrade the travel and event infrastructure in a
planned location and make it unethical to further burden that infrastructure
with a meeting.

* War, civil unrest, or public health crisis could make a meeting unsafe and/or
result in widespread national or corporate travel bans.

* An economic crisis could sharply reduce resources available for travel.

* Changes in visa policy or other unexpected governmental restrictions might
make the venue inaccessible to numerous attendees.

This document provides procedures for the IETF to decide to postpone, move, or
cancel an in-person IETF meeting.

# Conventions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be
interpreted as described in RFC 2119 {{?RFC2119}}.

In this document, the term "venue" refers to both the facility that houses the
sessions and the official meeting hotel(s).

# Decision Criteria and Roles

## IETF LLC

The LLC is responsible for assessing if it is safe to hold the meeting given the
following criteria. This assessment SHOULD occur eight weeks prior to the first
day of the meeting, though events may require reevaluation as late as during the
meeting itself.

The criteria in Section 3.1 of {{?RFC8718}} apply to venues that have changed
status. Specifically:

* Local safety guidelines allow the venue and hotels to host a meeting with the
expected number of participants and staff.

* It MUST be possible to provision Internet Access to the Facility and IETF
Hotels that allows those attending in person to utilize the Internet for all
their IETF, business, and day-to-day needs; in addition, there must be
sufficient bandwidth and access for remote attendees.  Provisions include, but
are not limited to, native and unmodified IPv4 and IPv6 connectivity, and global
reachability; there may be no additional limitation that would materially impact
their Internet use.  To ensure availability, it MUST be possible to provision
redundant paths to the Internet.

* A reasonable number of food and drink establishments are open and available
within walking distance to provide for the full number of participants and
staff.

* Local health and public safety infrastructure should expect to have adequate
capacity to support an influx of visitors during the meeting week.

The LLC must also confirm that:

* There are no US [USSTATE], UK [UKFO], or local authority travel advisories for
the location of the meeting. The first two are chosen to be easily accessible in
English, which all IETF staff can read. This should not be interpreted as
requiring cancellation due to a warning about a different region in the host
nation, or in the rural area surrounding a host city provided transportation to
the airport is secure.

* Air travel is assessed as safe by the relevent health and safety authorities.

* Travel insurance is both available and priced close to norms.

* There is no quarantine or self-isolation requirement at the location.

* Other similar international meetings (conferences)
are going ahead at a similar time to IETF.

Finally, the LLC should assess the impact of various travel restrictions, legal
and corporate, on the ability of critical support staff and contractors to enter
the host nation. The LLC can cancel the event if it concludes it cannot
adequately support it.

## IESG

The IESG assesses if projected attendance is high enough to capture the benefit
of an in-person meeting. In some cases, corporate travel restrictions may lower
attendance in the absence of any formal guidance from authorities. If it
concludes that attendance is too low, it can cancel the meeting regardless of
the LLC's safety assessment.

The IESG is discouraged from relying on a simple head count of expected event
attendance. Even dramatically smaller events with large remote participation may
be successful.  The IESG might consider:

* Are many working groups largely unaffected by the restrictions, so that they
can operate effectively?

* Is there a critical mass of key personnel at most working group meetings to
leverage the advantages of in-person meetings, even if many participants are
remote?

The IESG is encouraged to solicit information from Working Group chairs to make
this assessment.

# Remedies

In the event cannot be held at the scheduled time and place, the IETF has
several options. The remedies below should be consdered in light of these
principles, presented in no particular order:

* Hold the scheduled sessions of the meeting in some format

* Provide benefits of in-person interactions when possible

* Avoid exorbitant additional travel expenses due to last minute flight changes,
etc.

* The available time and resources allow the alternative to be adequately
prepared.

## Relocation

For attendees, the least disruptive response is to retain the meeting week but
move it to a more accessible venue. To the maximum extent possible, this will be
geographically close to the original venue. In particular, the IETF should
strive to meet the criteria in {{?RFC8718}} and {{?RFC8719}}.

Relocation that requires new air travel arrangements for attendees SHOULD NOT
occur less than one month prior to the start of the meeting.

## Virtualization

The second option, and one that has fewer issues with venue availability, is to
make the meeting fully remote. This requires different IETF processes and
logistical operations that are outside the scope of this document.

## Postponement

Although it is more disruptive to the schedules of participants, the next best
option is to delay the meeting until a specific date at which conditions are
expected to improve. The new end date of the meeting must be at least 30 days
before the beginning of the following IETF meeting.

Due to scheduling constraints at the venue, this will usually not be feasible.
However, it is more likely to allow attendees to recover at least some of their
travel expenses than other options.

## Cancellation

As a last resort, IETF may cancel the meeting totally. This is a last resort in
the event that worldwide conditions make it difficult for attendees to even
attend remotely. Not holding a meeting at all has wide implications for the
rhythm of IETF personnel policies, such as the nomination process and seating
of new officers.

Cancellation is likely the only practical alternative when emergencies occur
immeidiately before or during the meeting, so that there is no opportunity to
make other arrangements.

# Refunds

The IETF SHOULD NOT reimburse registered attendees for unrecoverable travel
expenses (airfare, hotel deposits, etc).

However, there are several cases where full or partial refund of registration
fees is appropriate:

* Cancellation SHOULD result in a full refund to all participants. It MAY be
prorated if some portion of the sessions completed without incident.
         
* Upon postponement, the LLC SHOULD offer refunds to registered attendees who
claim they cannot attend at the newly scheduled time.

* When the meeting becomes remote, the LLC SHOULD attempt to recover whatever
venue-related payments, past or future, it can and rebate this to registered
attendees, up to a maximum of their total cost of registration.

These provisions intend to maintain trust between the IETF and its participants.
However, under extraordinary threats to the solvency of the organization, the
LLC may suspend them.

# Security Considerations

This document introduces no new concerns for the security of internet protocols.

# IANA Considerations

There are no IANA requirements.

--- back

# Acknowledgments

# Change Log

## Since draft-duke-remote-meetings-00
* Defined "venue"
* Added principles for selecting remedies and rewrote alternatives.
* Added local authority travel advisories
* Added some criteria from IETF 109
