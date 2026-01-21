# Reference Style Guidance

This section covers style guidance for reference entries in
Internet-Drafts and RFCs.

If you have a question about how to format references that is not
covered here, please contact the RFC Production Center (RPC) at
rfc-editor@rfc-editor.org.

If you notice any issues or are aware of any updates to the
information on this page, please open an [issue on
GitHub](https://github.com/ietf/authors.ietf.org/issues) or send an
email to the RPC (rfc-editor@rfc-editor.org).

## RFC Series

### Request for Comments (RFC)

**Format**

``` txt
[CITE-TAG] Last name, First initial., Ed. (if applicable), “RFC Title”,
Subseries number (if applicable), RFC number, DOI, Date of publication,
<https://www.rfc-editor.org/info/rfc#>.
```

**Example**

``` txt
[RFC3080] Rose, M., “The Blocks Extensible Exchange Protocol Core”, RFC 3080,
DOI 10.17487/RFC3080, March 2001, <https://www.rfc-editor.org/info/rfc3080>.
```

**Note:**

References to RFCs can be added using the [BibXML
service](https://bib.ietf.org/). For example:

```xml
<xi:include href="https://bib.ietf.org/public/rfc/bibxml/reference.RFC.1234.xml"/>
```

### Internet Draft (I-D)

**Format**

``` txt
[CITE-TAG] Last name, First initial., Ed. (if applicable) and
First initial.  Last name, Ed. (if applicable), "I-D Title", Work in
Progress, Internet-Draft, draft-string-NN, Day Month Year,
<https://datatracker.ietf.org/doc/html/draft-something>.
```

**Example**

``` txt
[RFC-STYLE] Hoffman, P. and A. Rossi, "RFC Editor Model (Version 3)", Work in
Progress, Internet-Draft, draft-editorial-rswg-rfc9280-updates-04, 31 July 2025,
<https://datatracker.ietf.org/doc/draft-editorial-rswg-rfc9280-updates/>.
```

**Note:**

References to I-Ds can be added using the [BibXML
service](https://bib.ietf.org/). For example:

```xml
<xi:include href="https://bib.ietf.org/public/rfc/bibxml3/reference.I-D.rpc-rfc7322bis.xml"/>
```

### Subseries - Best Current Practices (BCPs) and Internet Standards (STDs)

This guidance overrides [Section 4.8.6.3 of RFC
7322](https://www.rfc-editor.org/rfc/rfc7322#section-4.8.6.3).

Internet Standards (STDs) and Best Current Practices (BCPs) may
consist of a single RFC or multiple RFCs. When an STD or BCP as a
whole is referenced, the reference entry should include ALL of the
RFCs comprising that subseries at the time of writing. The authors
should refer to specific RFC numbers as part of the text (not as
citations) and cite the subseries number. The URI to the STD or BCP
info page is to be included. The text should appear as follows:

> See RFC 3552 \[BCP72\].

**Format**

``` txt
[CITE-TAG] Internet Standard XXX, <https://www.rfc-editor.org/info/std#>. At the
time of writing, this STD comprises the following:

Last name, First initial., Ed. (if applicable), “RFC Title”, STD XXX, RFC
number, DOI number, Date of publication,
<https://www.rfc-editor.org/info/rfc#>.
```

**Example**

``` txt
[STD80] Internet Standard 80, <https://www.rfc-editor.org/info/std80>. At the
time of writing, this STD comprises the following:

Cerf, V., “ASCII format for network interchange”, STD 80, RFC 20, DOI
10.17487/RFC0020, October 1969, <https://www.rfc-editor.org/info/rfc20>:
```

**Note:**

References to subseries can be added using the [BibXML service](https://bib.ietf.org/).

### Errata

The format for references to errata reports described in [Section
4.8.6.5 of RFC
7322](https://www.rfc-editor.org/rfc/rfc7322.html#section-4.8.6.5) is
updated as follows:

**Format**

``` txt
[CITE-TAG] RFC Errata, Erratum ID number, RFC number, <URI>.
```

**Example**

``` txt
[Err3607] RFC Errata, Erratum ID 3607, RFC 4627,
<https://www.rfc-editor.org/errata/eid3607>.
```

**Note:**

Errata in the [Reported](https://www.rfc-editor.org/errata-definitions/)
state should not be referenced; they are not considered stable.

**Note on Updating or Obsoleting RFCs**

If you are writing an Internet-Draft that has an "Updates" or
"Obsoletes" relationship to a published RFC, we recommend asking your
Area Director (AD) or Stream Manager to verify any reported errata for
that RFC. Also, during the RPC intake process, please clarify if any
of the verified errata for that RFC are being addressed by your
document.

## IETF Proceedings and Workshops

**Format**

``` txt
[CITE-TAG] Presenter Last Name, First initial.,
"Presentation Title", IETF # Proceedings, Month Year, <URL>.
```

**Example**

``` txt
[MAPRG]  Bajpai, V., "Measuring YouTube Content Delivery over IPv6",
IETF 99 Proceedings, July 2017,
<https://datatracker.ietf.org/meeting/99/materials/slides-99-maprg-measuring-youtube-content-delivery-over-ipv6-00>.
```

**Note: Finding proceedings pages**

Past IETF meetings are listed here:
https://www.ietf.org/how/meetings/past/

Meeting materials can also be found on each working group’s meeting page
on Datatracker. For example,
https://datatracker.ietf.org/wg/quic/meetings/

## Working Group (WG) pages on Datatracker

**Format**

``` txt
[CITE-TAG] IETF, "Working Group Name (abbreviation)", <URL>.
```

**Example**

``` txt
[CDNI] IETF, "Content Delivery Networks Interconnection
(cdni)",<https://datatracker.ietf.org/wg/cdni/charter/>.
```

**Note: Finding a Working Group’s Datatracker page and the appropriate
URL**

A list of active IETF Working Groups is availabe on
[Datatracker](https://datatracker.ietf.org/wg/).

Use the WG’s Datatracker URL. Both /charter and /about point to the same
page. Aim for consistency within a document.

Note that, while a WG can have a GitHub repo, and RFCs can point to
these, the text shouldn’t imply that the repo is the main information
page for the working group. There should be a link to the WG’s
Datatracker page instead. A link to a  WG’s repo can be found on their
Datatracker page under “Additional Resources”.

## Mailing List Discussions

### Specific Message in a Mailing List Discussion

**Format**

``` txt
[CITE-TAG] Sender Name, "Subject: Subject line", message to the
listname mailing list, DD Month YYYY, <URL>.
```

**Example**

``` txt
[RPC-Meeting] Mahoney, J., "[rfc-i] RFC Production Center open meeting - Nov
19", message to the rfc-interest mailing list, 12 November 2025,
https://mailarchive.ietf.org/arch/msg/rfc-interest/czuWiLuFOiuXLmRw3Z6Syt9QXM4/.
```

**Note:**

For a message on an IETF mailing list, use mailarchive.ietf.org
URLs. To find a WG mailing list, check
https://datatracker.ietf.org/wg/ and/or
https://datatracker.ietf.org/group/concluded/.

Note: mailing list addresses of the format “@lists.ietf.org” (mostly WG
lists) have not been valid since 2005.

### Entire Mailing List

**Format**

``` txt
[CITE-TAG] Name of mail archive, "Name of Mailing List" Archive, <URL>.
```

**Example**

``` txt
[SAAG_list] IETF Mail Archive, "saag Archive",
<https://www.ietf.org/mail-archive/web/saag/current/maillist.html>.
```

## IANA Registries and Registry Groups

### IANA Registry

Note that the top-level URL is used when referring to a group of
registries and/or specific registries within the group.

This guidance was developed in coordination with IANA. See [“Guidance
for RFC Authors”](https://www.iana.org/help/protocol-registration) for
more information.

**Format**

``` txt
[CITE-TAG] IANA, “Registry Name”, <URL>.
```

**Example**

``` txt
[IANA] IANA, “ANCP Message Types”, <https://www.iana.org/assignments/ancp>.
```

### IANA Registry Group

**Format**

``` txt
[CITE-TAG] IANA, “Registry Group”, <URL>.
```

**Example**

``` txt
[IANA-ANCP] IANA, “Access Node Control Protocol (ANCP)”,
<https://www.iana.org/assignments/ancp>.
```

## Other Standards Development Organizations (SDOs)

### ISO, IEC, and ISO/IEC

**Format**

``` txt
[CITE-TAG] Organization, "Title", Standard Series number, Date, <URL>.
```

**Example**

``` txt
[SWID] ISO/IEC, "Information technology - IT asset management - Part 2: Software
identification tag", ISO/IEC 19770-2:2015, October 2015,
<https://www.iso.org/standard/65666.html>.
```

**Note:**

### IEEE Standards

**Format**

``` txt
[CITE-TAG] IEEE, "Title", IEEE Std #, DOI, Year, <URL or DOI URL>.
```

**Example**

``` txt
[IEEE802.1AX] IEEE, "IEEE Standard for Local and Metropolitan Area Networks
-- Link Aggregation", IEEE Std 802.1AX-2020, DOI
10.1109/IEEESTD.2020.9105034, 2020,
<https://ieeexplore.ieee.org/document/9105034>.
```

**Note:**

We recommend pointing to IEEExplore. For example: https://ieeexplore.ieee.org/document/9363693

### ITU-T Recommendations

**Format**

``` txt
[CITE-TAG] ITU-T, "Title", ITU-T Recommendation #, Date, <URL>.
```

**Example**

``` txt
[Y3301] ITU-T, "Functional requirements of software-defined
networking", ITU-T Recommendation Y.3301, September 2016,
<http://www.itu.int/rec/T-REC-Y.3301-201609-I/en>.
```

**Note:**

### W3C

**Format**

```txt
[CITE-TAG] Author(s), "Title", W3C Recommendation, Date of
Publication, <URL>.
```

**Example**

``` txt
[W3C.XML1.0] Bray, T., Ed., Paoli, J., Ed., Sperberg-McQueen, C.M., Ed., Maler,
E., Ed., and F. Yergeau, Ed., "Extensible Markup Language (XML) 1.0 (Fifth
Edition)", W3C Recommendation, 26 November 2008, <https://
www.w3.org/TR/2008/REC-xml-20081126/>.
```

**Note:**

When referencing W3C documents, consider whether you are referencing
the latest document in that series or the specific version of the W3C
document as it exists at the time of publication. From [Section 11.6
of "W3C Manual of
Style"](https://www.w3.org/guide/manual-of-style/#Linking) (19 November 2025):

> Unless intentionally referring to the latest document in a series, always refer
> to specific W3C documents by using the "this version" URI.

The example provided previously in this section uses the "This version" URL
provided by W3C (https://www.w3.org/TR/2008/REC-xml-20081126/).

REVIEW NOTE:
guidance is a little confusing from W3C;
https://www.w3.org/guide/manual-of-style/#ref-section recommends adding a
"latest version" URL

Should we also recommend adding this? A previous version of our guidance placed
the latest version in an annotation element?  Perhaps that could be the guidance
for most reference types with a "This version" and "Latest version" URL? That
is, include the "This version" URL as the main reference target and then add the
"Latest version" URL in the annotation.

### WHATWG

**Format**

``` txt
[CITE-TAG] WHATWG, "Title", WHATWG Living Standard,
<URL>.

Commit snapshot: <Commit Snapshot URL>
```

**Example**

``` txt
[URL-PATTERN] WHATWG, "URL Pattern", WHATWG Living Standard,
<https://urlpattern.spec.whatwg.org/>.

Commit snapshot:
<https://urlpattern.spec.whatwg.org/commit-snapshots/d13ebead18003059a83ca4a25240e5cafc066c4c/>
```

**Note:**

WHATWG provides ["commit
snapshots"](https://urlpattern.spec.whatwg.org/commit-snapshots/d13ebead18003059a83ca4a25240e5cafc066c4c/)
for their standards. Since WHATWG publishes ["Living
Standards"](https://whatwg.org/faq#living-standard) which are
regularly updated and changed, we recommend adding a URL to this
commit snapshot in the reference in an annotation.

The URL for the commit snapshot can be found by clicking the "Snapshot
as of this commit" link provided at the main URL for a Living
Standard.

For more information on WHATWG commit snapshots see:
https://whatwg.org/faq#change-at-any-time

### 3GPP

**Format**

```txt
[CITE-TAG] 3GPP, "Title", 3GPP TR/TS TR or TS Number, <URL>.
```

**Example**

```txt
[Spec-3GPP] 3GPP, "System architecture for the 5G System (5GS)", 3GPP
TS 23.501,
<https://portal.3gpp.org/desktopmodules/Specifications/SpecificationDetails.aspx?specificationId=3144>.
```

**Note:**

If referencing a specific version from a specific release by 3GPP, include the
version and release number, the date of publication, and the URL pointing to
that version. For example:

```txt
[TR.26.857] 3GPP, "5G Media Service Enablers", 3GPP TR 26.857, Version
1.0.0, Release 18, September 2022,
<https://ftp.3gpp.org//Specs/archive/26_series/26.857/26857-100.zip>.
```

### Unicode Consortium

The following guidance is adapted from the [Unicode Consortium's
reference guidance](https://www.unicode.org/versions/#References).

#### Referencing the latest version of the Unicode Standard (versionless)

```txt
[UNICODE] The Unicode Consortium, "The Unicode Standard",
<https://www.unicode.org/versions/latest/>.
```

#### Referencing a specific version of the Unicode Standard (versioned)

```txt
[UNICODE-V17] The Unicode Consortium, "The Unicode Standard", Version
17.0.0, 2025, <https://www.unicode.org/versions/Unicode17.0.0/>.
```

**Note:**

REVIEW:
How to phrase when to reference/cite the latest version vs. a
specific version? I like W3C way of doing this:

> Unless intentionally referring to the latest document in a series, always refer
> to specific W3C documents by using the "this version" URI.

Is this guidance we should include on this page?

## General Web Content

### Referencing Internet Content: Best Practices and Recommendations

This section provides more information to (or just "updates?") on the guidance
for using URIs in RFCs from [Section 4.8.6.1 of RFC
7322](https://www.rfc-editor.org/rfc/rfc7322.html#section-4.8.6.1):

> The use of URIs in references is acceptable, as long as the URI is
> the most stable (i.e., unlikely to change and expected to be
> continuously available) and direct reference possible.  The URI will
> be verified as valid during the RFC editorial process.
>
> If a dated URI (one that includes a timestamp for the page) is
> available for a referenced web page, its use is required.
>
> Note that URIs may not be the sole information provided for a
> reference entry.

**Assessing Reference URI/URL for Permanence and Stability**

From [Section 4.8.6.1 of RFC
7322](https://www.rfc-editor.org/rfc/rfc7322.html#section-4.8.6.1):

> The use of URIs in references is acceptable, as long as the URI is
> the most stable (i.e., unlikely to change and expected to be
> continuously available) and direct reference possible.  The URI will
> be verified as valid during the RFC editorial process.

When assessing URLs for stability, consider the following:

**"Link rot" and "content drift"**

"Link rot" is when the provided URL fails to point to its original target. This
failure is often the result of the resource being moved to a new address or
becoming permanently unavailable.

"Content drift" is the phenomenon where the URL functions, but the content
available at that URL changes over time - for example, an organization's
homepage content changing due to that organization changing its name or being
folded into another organization.

Using permanent identifiers and/or archived URLs may help preserve the stability
of a reference's URL and prevent a reference from being affected by link rot or
content drift.

For more information on link rot and content drift see:
- https://en.wikipedia.org/w/index.php?title=Link_rot&oldid=1324240675
- https://www.pewresearch.org/data-labs/2024/05/17/when-online-content-disappears/
- https://www.cjr.org/analysis/linkrot-content-drift-new-york-times.php
- https://dl.acm.org/doi/10.1145/602421.602422

**Using Permanent URLs - i.e., "permalinks", Digital Object Identifiers (DOIs), etc.**

- Is there a permanent identifier for the reference (for example, a Digital
  Object Identifier (DOI))?

If there is a permanent identifier for the reference, we recommend including it
in the reference entry.

**Using Archived URLs**

- Is there a concern about the longevity of the reference's URL? For example, is
  the URL likely to redirect or "break" in the next few years?

If there is a concern about the longevity of the URL, we recommending using an
archived URL in the reference. For example, using the [Internet Archive Wayback
Machine](https://web.archive.org/) or [Perma.cc](https://perma.cc/).

REVIEW:

Noting thtat this it seems like this was discussed by RSWG:
- https://www.rfc-editor.org/staff/wiki/doku.php?id=wayback_machine_url
- https://mailarchive.ietf.org/arch/msg/rswg/_X85fmA37bulrJHgy64pSMuSEPE/
Any other considerations?

### Websites

**Format**

``` txt
[CITE-TAG] Author (if available), "Title (if available)", Date (if available), <URL>.
```

**Example**

``` txt
[RFC-Editor] "RFC Editor", <https://https://www.rfc-editor.org/>.
```

**Note:**

**Titles for references to  websites.**

Some websites may not have exact titles or the title may not be clear. If this
is the case, a description may be used instead.

For example:

```txt
Microsoft, "Microsoft home page", <https://https://www.microsoft.com/en-us/>.
```

**Dates for references to websites**

If the website being reference includes a publication date or "Last modified"
date (or equivalent), include it as the date for the reference.

REVIEW should we include the archived date?

### Wikipedia Articles

**Format**

``` txt
[CITE-TAG] Wikipedia, "Title", Date of most recent edit, <Dated URL>.
```

**Example**

``` txt
[Magnet] Wikipedia, "Magnet URI scheme", March 2013,
<https://en.wikipedia.org/w/index.php?title=Magnet_URI_scheme&oldid=546892719>.
```

**Note:**

Wikipedia provides a permanent link under the "Tools" tab. A list of permanent
links is also available under the "View history" tab.

When constructing the reference target in RFCXML, replace the ‘&’ in the
versioned URL with “&”:

``` xml
<reference anchor="Magnet"
target="https://en.wikipedia.org/w/index.php?title=Magnet_URI_scheme&amp;oldid=546892719">

```

## Online Periodicals

### Journal Articles

**Format**

``` txt
[CITE-TAG] Author, "Title", Name of Journal, vol. # (if
applicable), no. # (if applicable), Date, pp. #, DOI (if applicable), <URL>.
```

**Example**

``` txt
[Dijkstra] Dijkstra, E., "A note on two problems in connexion with
graphs", Numerische Mathematik, vol. 1, pp. 269-271, DOI
10.1007/BF01386390, December 1959,
<https://link.springer.com/article/10.1007/BF01386390>.
```

**Note:**

For journal articles with volume and issue numbers we recommend using the
following style:

Volume 1 = vol. 1

Issue 1 = no. 1

### Conference Papers

**Format**

``` txt
[CITE-TAG] Author, "Title", Name of Conference, Date, pp. #,
DOI (if applicable), <URL>.
```

**Example**

TODO

**Note:**

### Online Periodical (Newspaper, Magazine, etc.)

**Format**

``` txt
[CITE-TAG] Author, "Title", Name of periodical / publication, Date, <URL>.
```

**Example**

``` txt
[Wired-IETF]   Borsook, P., "How Anarchy Works", Wired, October 1995,
<https://www.wired.com/1995/10/ietf/>.
```

**Note:**

## Academic Sources

### Dissertations

**Format**

```txt
[CITE-TAG] Author, "Title", MA/MS/Ph.D. Dissertation, Awarding
Institution, Date, <URL>.
```

**Example**

``` txt
[REST] Fielding, R., "Architectural Styles and the Design of Network-based
Software Architectures", Ph.D. Dissertation, University of California,
Irvine, 2000,
<https://www.ics.uci.edu/~fielding/pubs/dissertation/fielding_dissertation.pdf>.
```

**Note:**

TODO just noticed this URL no longer resolves to a pdf. Now states "Forbidden - You don't have permission to access this resource.". Find a better example.

## Web-based Public Code Repositories

### Repositories

**Format**

```txt
[CITE-TAG] "Name or description of repository", commit hash, Date, <URL>.
```

**Example**

``` txt
[pysaml2] “Python implementation of SAML2”, commit 7135d53, 6 March 2018,
<https://github.com/IdentityPython/pysaml2>.
```

**Note:**

Format of reference entries:

- authors — omit them
- title — include if available (some judgement may be required on the part of the editors and authors to have a sensible title)
- commit hash — include if exists, short form preferred if available
- date — use date of last commit at time doc is edited.
- URL — include URL to main page of repository

### Files within a repository

**Format**

```txt
[CITE-TAG] "filename", commit hash, date, <URL>.
```

**Example**

```txt
[pysaml2-config] "config.py", commit 74dc24d, 26 September 2023,
<https://github.com/IdentityPython/pysaml2/blob/master/src/saml2/config.py>.
```

**Note:**

## Government Publications

### NIST

#### NIST Federal Information Processing Standards Publications (FIPS)

**Format**

``` txt
[CITE-TAG] NIST, “Title of FIPS Publication”, NIST FIPS Number, DOI, Date of
Publication, <URL>.
```

**Example**

``` txt
[NIST_FIPS_180_4] NIST, “Secure Hash Standard”, NIST FIPS 180-4, DOI
10.6028/NIST.FIPS.180-4, August 2015,
<https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf>.
```

**Note:**

#### NIST Special Publications (SPs)

**Format**

TODO add NIST as publisher?

``` txt
[CITE-TAG] Author(s), “Title of SP”, NIST SP Number, DOI, Date of Publication, <URL>.
```

**Example**

``` txt
[NIST_SP_800-233] Chandramouli, R., Butcher, Z., and J. Callaghan, “Service Mesh
Proxy Models for Cloud-Native Applications”, NIST SP 800-233, DOI
10.6028/NIST.SP.800-233, October 2024,
<https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-233.pdf>.
```

**Note:**

### ETSI

**Format**

```txt
[CITE-TAG] ETSI, "Title", Document
identifier, Version number (if applicable), Date, <URL>.
```

**Example**

```txt
[nfv-framework] ETSI, "Network Functions Virtualisation (NFV); Architectural
Framework", ETSI GS NFV 002, V1.2.1, December 2014,
<https://www.etsi.org/deliver/etsi_gs/NFV/001_099/002/01.02.01_60/gs_NFV002v010201p.pdf>.
```

**Note:**

A list of the types of standards, specifications, and reports produced by ETSI
is available on [their
website](https://www.etsi.org/standards/types-of-standards).

## Specific

### Cryptology ePrint Archive Papers

**Format**

``` txt
[CITE-TAG] Author(s), "Title", Cryptology ePrint Archive, Paper #, Date
(year), <URL>.
```

**Example**

``` txt
Courtois, N., "Security Evaluation of GOST 28147-89 In View Of International
Standardisation", Cryptology ePrint Archive, Paper 2011/211, 2011,
<https://eprint.iacr.org/2011/211>.
```

**Note:**

### arXiv Papers

**Format**

```txt
[CITE-TAG] Author(s), "Title", arXiv#, DOI (if applicable), Date,
<URL>.
```

**Example**

```txt
[Shors96] Shor, P. W., "Polynomial-Time Algorithms for Prime Factorization and
Discrete Logarithms on a Quantum Computer", arXiv:quant-ph/9508027, DOI
10.48550/arXiv.quant-ph/9508027, January 1996, <https://arxiv.org/abs/quant-ph/9508027>.
```

**Note:**
