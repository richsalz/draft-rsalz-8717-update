---
title: "Update to RFC 8717: IETF Administrative Terminology"
abbrev: "8717update"
updates: 3710, 3929, 4633, 6702, 9281
docname: draft-rsalz-8717-update-latest
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
updates the source documents so that the job to be done, and who
the responsible entity is, are described.

--- middle

# Introduction

{{!RFC8717}} updated several RFCs pertaining to the organization of the IETF
to use the term "Managing Director, IETF Secretariat" (MDS).
As that term does not accurately reflect the organization or roles of
the IETF staff, the MDS term is no longer relevant.
This document removes mention of particular staff roles, and instead
updates the source documents so that the job to done, and who
the responsible entity is, are described.

This document updates {{RFC3710}} and {{RFC6702}}. It also changes the
status of {{RFC3929}} and {{RFC4633}} to Historic.

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

{{RFC3710, Section 2}} describes the composition of the IESG and mentions
the IETF Executive Director twice.

The first mention:

    The Internet Architecture Board (IAB) Chair and the IETF Executive
    Director, as ex-officio members of the IESG.

Is replaced with the following text:

    The Internet Architecture Board (IAB) Chair and the IETF Executive
    Director or their designee, as ex-officio members of the IESG.

The second mention:

    The IETF Executive Director is the person charged with running the
    IETF Secretariat.

is deleted.

##  Changes to RFC 3929

{{RFC3929}} is an Experimental RFC published in 2004. This document changes its status to
Historic.

##  Changes to RFC 4633

{{RFC4633}} is an Experimental RFC published in 2006. This document changes its status to
Historic.

##  Changes to RFC 6702

{{RFC6702, Section 5}} says that WG Chairs and Area Directors are
encouraged to ask the IETF Executive Directory to contact those who
submitted an early intellectual property disclosure and request an update.
This document specifies an email address to be used for that purpose:

    To help prevent early IPR disclosures from becoming stale
    or incomplete, at important junctures in the standardization process
    (e.g., at working group adoption, before Working Group Last Call, and
    before IETF Last Call) WG chairs and ADs are encouraged to request
    that the Executive Director of the IETF contact those who submitted
    early IPR disclosures about updating their disclosures by
    sending email to XXX@ietf.org.

# Security Considerations

This document has no security considerations.

# IANA Considerations

This document has no IANA actions.

--- back

# Acknowledgments
{:numbered="false"}

Just me.
