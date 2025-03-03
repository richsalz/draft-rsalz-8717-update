---
title: "Update to RFC 8717"
abbrev: "8717update"
updates: 3710, 3929, 4633, 6702, 9281
docname: draft-8717-update-latest
category: bcp

ipr: trust200902
area: General
workgroup: TBD
keyword: Internet-Draft, IASA, terminology

stand_alone: yes
smart_quotes: no
pi: [toc, sortrefs, symrefs]

author:
 -
    ins: R. Salz
    name: Rich Salz
    organization: Akamai Technologies
    email: rsalz@akamai.com

normative:
  RFC3710:
  RFC3929:
  RFC4633:
  RFC6702:

informative:


--- abstract

RFC 8717 updated several RFCs pertaining to the organization of the IETF
to use the term "Managing Director, IETF Secretariat" (MDS).
As that term does not accurately reflect the organization or roles of
the IETF staff, the MDS term is no longer relevant.
This document removes mention of particular staff roles, and instead
updates the source documents so that the job to done, and who
the responsible entity is (generally, the IETF LLC) are described.

--- middle

# Introduction

{{!RFC8717}} updated several RFCs pertaining to the organization of the IETF
to use the term "Managing Director, IETF Secretariat" (MDS).
As that term does not accurately reflect the organization or roles of
the IETF staff, the MDS term is no longer relevant.
This document removes mention of particular staff roles, and instead
updates the source documents so that the job to done, and who
the responsible entity is (generally, the IETF LLC) are described.

This document updates
{{!RFC3710}},
{{!RFC3929}},
{{!RFC4633}}, and
{{!RFC6702}}.

# Conventions and Definitions

{::boilerplate bcp14-tagged}

# Updates Being Made

{{RFC8717, Section 2}} explained that {{?RFC2606}} did not need to be updated
because {{?RFC8179}} removed the need for it.
While the same section of RFC 8717 provided an update to {{?RFC2028}},
that has similarly been overtaken by events in that it was obsoleted by
{{?RFC9281}}, and Section 3 of RFC 9281 does not need revising.

Further, the IETF is in the "consideration" stage of forming a working
group to update {{?RFC2418}}; for discussion,
see [the mailing list](https://mailman3.ietf.org/mailman3/lists/procon.ietf.org/).
An online document proposing changes to RFC 2418 to comply with
[this document](https://github.com/richsalz/draft-rsalz-2418bis/pull/14)
are available.

The following sub-sections make the specific changes for each RFC and
therefore this document completely replaces Section 2 of RFC 8717.

##  Changes to RFC 3710

{{RFC3710, Section 2}} describes the composition of the IESG.
This section is updated to replace the original text that twice
mentions "IETF Executive Director" with "a member of the IETF staff as
specified by the IETF LLC."

##  Changes to RFC 3929

RFC 3929, an Experimental RFC, proposes a number of methods to resolve
a deadlock when an IETF Working Group is unable to come to a decision.

{{RFC3929, Section 4.1.1}} says that volunteers should send their
names to the IETF Executive Directory, who should use {{?RFC3797}} to
choose if their is an excess of volunteers.
As the IESG is responsible for the standards process, this task should
be fulfilled by someone they announce.

Similarly, in {{RFC3929, Section 4.3}} an alternate method is described. Again,
the text is changed so that the IESG announces who will perform that
task.

##  Changes to RFC 4633

{{RFC4633, Section 1}} says that the IETF Executive Director is empowered
to restrict posting to the [IETF discussion list](mailto:ietf@ietf.org).

This document updates RFC 4633 to remove that ability.

##  Changes to RFC 6702

{{RFC6702, Section 5}} says that WG Chairs and Area Directors are
encouraged to ask the IETF Executive Directory to contact those who
submitted an early intellectual property disclosure and request an update.

This document updates RFC 6702 to say that the IETF LLC, or their
designee, should be contacted.

# Security Considerations

This document has no security considerations.

# IANA Considerations

This document has no IANA actions.

--- back

# Acknowledgments
{:numbered="false"}

Just me.
