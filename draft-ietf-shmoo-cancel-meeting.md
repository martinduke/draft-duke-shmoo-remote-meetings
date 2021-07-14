---
title: Considerations for Cancellation of IETF Meetings
abbrev: Canceling Meetings
docname: draft-ietf-shmoo-cancel-meeting-latest
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


--- abstract

The IETF ordinarily holds three in-person meetings per year to discuss issues
and advance the Internet. However, various emergencies can make a planned
in-person meeting infeasible. This document provides criteria to aid the IETF
Administration LLC (LLC), Internet Engineering Steering Group (IESG), and
Internet Research Task Force (IRTF) Chair in deciding to postpone, move, or
cancel an in-person IETF meeting.

--- middle

# Introduction

Among the highlights of the IETF calendar are in-person general meetings, which
happen three times a year at various locations around the world.

Various major events may affect the suitability of a scheduled in-person IETF
meeting, though for some events this may not be immediately obvious. For
example:

* A meeting venue itself may unexpectedly close or otherwise be unable to meet
IETF meeting requirements due to a health issue, legal violation, or other
localized problem.

* A natural disaster could degrade the travel and meeting infrastructure in a
planned location and make it unethical to further burden that infrastructure
with a meeting.

* War, civil unrest, or public health crisis could make a meeting unsafe and/or
result in widespread national or corporate travel bans.

* An economic crisis could sharply reduce resources available for travel,
resulting in lower expected attendance.

* Changes in visa policy or other unexpected governmental restrictions might
make the venue inaccessible to numerous attendees.

This document provides criteria to aid the IETF Administration LLC (LLC),
Internet Engineering Steering Group (IESG), and Internet Research Task Force
(IRTF) Chair in deciding to postpone, move, or cancel an in-person IETF meeting.

# Conventions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this
document are to be interpreted as described in BCP 14 {{!RFC2119}} {{!RFC8174}}
when, and only when, they appear in all capitals, as shown here.

In this document, the term "venue" refers to both the facility that houses the
sessions and the official meeting hotel(s).

# Decision Criteria and Roles

The LLC assesses whether an in-person meeting is logistically and financially
viable in light of events, and assembles information about various travel
restrictions that might impact attendance. The Internet Engineering Steering
Group (IESG) and Internet Research Task Force (IRTF) Chair assess if the
projected attendance is sufficient for a viable in-person meeting.

## IETF LLC

The LLC is responsible for assessing the suitability of a venue for an IETF
meeting and is responsible for any reassessment in response to a major event
that leaves the prior conclusion in doubt. If such an event occurs more than
fourteen weeks before the start of the scheduled meeting, it is deemed a
non-emergency situation. Later events, up to and including the week of a meeting
itself, are deemed an emergency situation.

In non-emergency situations, if the LLC determines the scheduled meeting clearly
cannot proceed (e.g., the venue has permanently closed), then it MUST share the
reason(s) with the community and MUST consult on its proposed remedy. In less
clear cases, the LLC SHOULD conduct a formal reassessment process that includes:

* Consulting with the community on the timetable of the decision process.

* Consulting with the community on criteria to assess the impact of new
developments.

* Publishing an assessment report and recommended remedy.

* Seeking approval of the IESG and IRTF Chair for the recommendation.

In emergency situations, which lack the time for a consultation process, this
document provides criteria that have IETF consensus and which the LLC MUST apply
in its assessment.

The LLC will collect information about the likely impact to in-person
attendance of national travel advisories, national and corporate travel bans,
availability of transportation, quarantine requirements, etc. and report the
results to the IESG and IRTF Chair.

These criteria, some of which are derived from Section 3 of {{?RFC8718}}, apply
to venues that are re-evaluated due to an emergency:

* Local safety guidelines allow the venue and hotels to host a meeting with the
expected number of participants and staff.

* It is possible to provision Internet access to the venue that allows those
attending in person to utilize the Internet for all their IETF, business, and
day-to-day needs; in addition, there must be sufficient bandwidth and access for
remote attendees.  Provisions include, but are not limited to, native and
unmodified IPv4 and IPv6 connectivity, and global reachability; there may be no
additional limitation that would materially impact their Internet use.  To
ensure availability, it MUST be possible to provision redundant paths to the
Internet.

* A reasonable number of food and drink establishments are open and available
within walking distance to provide for the expected number of participants and
staff.

* Local health and public safety infrastructure expects to have adequate
capacity to support an influx of visitors during the meeting week.

Finally, the LLC MUST assess the impact on its own operations, including:

* The number of critical support staff, contractors, and volunteers who can be
at the venue.

* The financial impact of continuing a meeting, or implementing any of the
possible remedies.

The LLC SHOULD cancel an in-person meeting and explore potential remedies if it
judges a meeting to be logistically impossible or inconsistent with its
fiduciary responsibilities.

In the event of considerations this document does not foresee, the LLC should
protect the health and safety of attendees and staff, as well as the fiscal
health of the organization, with approval from the IESG and IRTF Chair. The IESG
should pursue a later update of this document.

## IESG and IRTF Chair

If the LLC assesses there are no fundamental logistical or financial obstacles
to holding a meeting in an emergency situation, the IESG and IRTF Chair assess
if projected attendance is high enough to achieve the benefit of an in-person
meeting. The IESG and IRTF Chair SHOULD cancel the in-person meeting if that
benefit is insufficient.

The IESG and IRTF Chair are discouraged from relying on a simple head count of
expected meeting attendance. Even dramatically smaller meetings with large
remote participation may be successful.  In addition to the LLC's estimate, the
IESG and IRTF Chair might consider:

* Are many working groups and research groups largely unaffected by the
restrictions, so that they can operate effectively?

* Is there a critical mass of key personnel at most working group meetings to
leverage the advantages of in-person meetings, even if many participants are
remote?

# Remedies

If a meeting cannot be held at the scheduled time and place, the LLC, IESG, and
IRTF Chair have several options. The remedies in this section should be
considered in light of four principles, presented in no particular order:

* Hold the scheduled sessions of a meeting in some format.

* Provide benefits of in-person interactions when possible.

* Avoid exorbitant additional travel expenses due to last minute flight changes,
etc.

* Ensure sufficient time and resources to adequately prepare an alternative.

These remedies are listed in approximate declining order of preference.

## Relocation

For attendees, the least disruptive response is to retain the meeting week but
move it to a more accessible venue. To the maximum extent possible, this will be
geographically close to the original venue. In particular, the LLC SHOULD meet
the criteria in {{!RFC8718}} and {{!RFC8719}}.

Relocation that requires new air travel arrangements for attendees SHOULD NOT
occur less than one month prior to the start of the meeting.

## Virtualization

The second option, and one that has fewer issues with venue availability, is to
make a meeting fully online. This requires different IETF processes and
logistical operations that are outside the scope of this document.

## Postponement

Although it is more disruptive to the schedules of participants, the next best
option is to delay a meeting until a specific date, at the same venue, at
which conditions are expected to improve. The new end date of a meeting must
be at least 30 days before the beginning of the following IETF meeting, and a
meeting MUST begin no earlier than 30 days after the postponement announcement.

Due to scheduling constraints at the venue, this will usually not be feasible.
However, it is more likely to allow attendees to recover at least some of their
travel expenses than other options.

Note that it is possible to both postpone and relocate a meeting, though this
has the disadvantages of both.

## Cancellation

The LLC, IESG, and IRTF Chair may cancel a meeting entirely in the event that
worldwide conditions make it difficult for attendees to even attend online. Not
holding a meeting at all can have wide implications, such as effects on the
nomination process and seating of new officers.

Cancellation is likely the only practical alternative when emergencies occur
immediately before or during a meeting, so that there is no opportunity to
make other arrangements.

# Refunds

The IETF SHOULD NOT reimburse registered attendees for unrecoverable travel
expenses (airfare, hotel deposits, etc).

However, there are several cases where full or partial refund of registration
fees is appropriate:

* Cancellation SHOULD result in a full refund to all participants. It MAY be
prorated if some portion of the sessions completed without incident.

* Upon postponement, the LLC SHOULD offer refunds to registered attendees who
claim they cannot attend at the newly scheduled time. Attendees can opt out of
receiving a refund.

* When a meeting is virtualized, the LLC MUST offer to refund registered
attendees the difference between their paid registration fee and the equivalent
fee for an online meeting. The LLC SHOULD offer refunds to registered attendees
who do not wish to attend an online meeting.

* The LLC SHOULD offer refunds to attendees whose government forbids, or has
issued a safety advisory against, visits to the host venue, even if the
in-person meeting will continue. It SHOULD NOT refund cancellations due to
employer policy or personal risk assessments.

These provisions intend to maintain trust between the IETF and its participants.
However, under extraordinary threats to the solvency of the organization, the
LLC may suspend them.

# Security Considerations

This document introduces no new concerns for the security of Internet protocols.

# IANA Considerations

There are no IANA requirements.

--- back

# Acknowledgments

Jay Daley provided extensive input to make this document more usable by the LLC.
Many members of the IESG and the SHMOO working group also provided useful
comments.

# Change Log

## Since draft-ietf-shmoo-cancel-meetings-05
* Minor changes from IETF review

## Since draft-ietf-shmoo-cancel-meetings-04
* Threshold for "emergency" changes to 14 weeks
* Clarified refund policy
* IETF Last Call nits

## Since draft-ietf-shmoo-cancel-meetings-03
* Clarifications from AD review

## Since draft-ietf-shmoo-cancel-meetings-02
* Added IRTF to IESG responsibilities
* WGLC Nits

## Since draft-ietf-shmoo-cancel-meetings-01
* Added refund principles for hybrid meetings

## Since draft-ietf-shmoo-cancel-meetings-00
* Jay Daley's nits
* Distinguish the emergency and non-emergency process
* Eliminated USSTATE/UKFO references
* Clarified roles of LLC and IESG

## Since draft-duke-shmoo-cancel-meetings-01
* Change to WG draft

## Since draft-duke-shmoo-cancel-meetings-00
* Added mention of IRTF
* Discussed consensus on cancellation

## Since draft-duke-remote-meetings-00
* Defined "venue"
* Added principles for selecting remedies and rewrote alternatives.
* Added local authority travel advisories
* Added some criteria from IETF 109
