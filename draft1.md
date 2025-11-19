## RFCs and Adjacent

### Request for Comments (RFCs)

The Digital Object Identifier (DOI) is now listed in each reference to
an RFC. The first example in [Section 4.8.6.2 of RFC
7322](https://www.rfc-editor.org/rfc/rfc7322#section-4.8.6.2) is updated
as follows.

**Template**

``` txt
   [RFCXXXX] Last name, First initial., Ed. (if applicable), “RFC Title”,
   Sub-series number (if applicable), RFC number, DOI, Date of publication,
   <https://www.rfc-editor.org/info/rfc#>.
```

**Example**

``` txt
   [RFC3080] Rose, M., “The Blocks Extensible Exchange Protocol Core”, RFC 3080,
   DOI 10.17487/RFC3080, March 2001, <https://www.rfc-editor.org/info/rfc3080>.
```

**Note:**

References to RFCs can be added using the BibXML service.

### Internet Drafts (I-Ds)

**Template**

``` txt
   [SYMBOLIC-TAG] Last name, First initial., Ed. (if applicable) and
   First initial.  Last name, Ed. (if applicable), "I-D Title", Work in
   Progress, Internet-Draft, draft-string-NN, Day Month Year,
   <https://datatracker.ietf.org/doc/html/draft-something>.
```

**Example**

``` txt
    [RFC-STYLE] Flanagan, H. and S.  Ginoza, "RFC Style Guide", Work in
    Progress, Internet-Draft, draft-flanagan-style-04, 27 September 2019,
    <https://datatracker.ietf.org/doc/html/draft-flanagan-style-04>.
```

**Note:**

References to I-Ds can be added using the BibXML service.

### Subseries - Best Current Practices (BCPs) and Internet Standards (STDs)

This guidance overrides [Section 4.8.6.3 of RFC
7322](https://www.rfc-editor.org/rfc/rfc7322#section-4.8.6.3).

Internet Standards (STDs) and Best Current Practices (BCPs) may consist
of a single RFC or multiple RFCs. When an STD or BCP is referenced, the
reference entry should include ALL of the RFCs comprising that
sub-series. The authors should refer to specific RFC numbers as part of
the text (not as citations) and cite the sub-series number. The URI to
the STD or BCP info page is to be included. The text should appear as
follows:

> See RFC 3552 \[BCP72\].

**Template**

``` txt
   [STDXXX] Internet Standard XXX, <https://www.rfc-editor.org/info/std#>. At the
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

References to subseries can be added using the BibXML service.

### Errata

The format for errata references described in [Section 4.8.6.5 of RFC
7322](https://www.rfc-editor.org/rfc/rfc7322.html#section-4.8.6.5) is
updated as follows:

**Template**

``` txt
   [ErrNumber] RFC Errata, Erratum ID number, RFC number, <URI>.
```

**Example**

``` txt
   [Err3607] RFC Errata, Erratum ID 3607, RFC 4627,
   <https://www.rfc-editor.org/errata/eid3607>.
```

**Note:**

For more details, see [the
announcement](https://mailarchive.ietf.org/arch/msg/rfc-interest/F4LLPSsmKKTr3McvyGCQEPiZFhE/)
on the RFC interest list.

Errata in the [Reported](https://www.rfc-editor.org/errata-definitions/)
state should not be referenced; they are not considered stable.

### IETF Proceedings and Workshops

**Template**

``` txt
   [CITE-TAG] Presenter Last Name, First Initial (if applicable), "Presentation
   Title", IETF # Proceedings, Month Year, <URL>.
```

**Example**

``` txt
  [MAPRG]  Bajpai, V., "Measuring YouTube Content Delivery over
       IPv6", IETF 99 Proceedings, July 2017,
       <https://datatracker.ietf.org/meeting/99/materials/slides-
       99-maprg-measuring-youtube-content-delivery-over-ipv6-00>.
```

**Note: Finding proceedings pages**

Past IETF meetings are listed here:
https://www.ietf.org/how/meetings/past/

Meeting materials can also be found on each working group’s meeting page
on Datatracker. For example,
https://datatracker.ietf.org/wg/quic/meetings/

### Working Group pages on Datatracker

**Template**

``` txt
   [CITE-TAG] IETF, "Working Group Name (abbreviation)", <URL>.
```

**Example**

``` txt
   [CDNI]     IETF, "Content Delivery Networks Interconnection (cdni)",
              <https://datatracker.ietf.org/wg/cdni/charter/>.
```

**Note: Finding a working group’s Datatracker page and the appropriate
URL**

A list of active IETF working groups is availabe on
[Datatracker](https://datatracker.ietf.org/wg/).

Use the WG’s datatracker URL. Both /charter and /about point to the same
page. Aim for consistency within a document.

Note that, while a WG can have a GitHub repo, and RFCs can point to
these, the text shouldn’t imply that the repo is the main information
page for the working group. There should be a link to the WG’s
datatracker page instead. A link to WG’s repo can be found on their
datatracker page under “Additional Resources”.

### Mailing List Discussions

#### Specific Message

**Template**

``` txt
   [reftag] Sender, A., "Subject: Subject line", message to the
   listname mailing list, DD Month YYYY, <URL>.
```

**Example**

``` txt
   [RPC-Meeting] Mahoney, J., "[rfc-i] RFC Production Center open meeting - Nov
   19", message to the rfc-interest mailing list, 12 November 2025,
   https://mailarchive.ietf.org/arch/msg/rfc-interest/czuWiLuFOiuXLmRw3Z6Syt9QXM4/.
```

**Note:**

For a message on a IETF mailing list, use mailarchive.ietf.org URLs. To
find a WG mailing list, check https://datatracker.ietf.org/wg/ and/or
https://datatracker.ietf.org/group/concluded/.

Note: mailing list addresses of the format “@lists.ietf.org” (mostly WG
lists) have not been valid since 2005.

#### Entire Mailing List

**Template**

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

**Template**

``` txt
   [NAME] IANA, “Registry Name”, <URL>.
```

**Example**

``` txt
   [IANA] IANA, “ANCP Message Types”, <https://www.iana.org/assignments/ancp>.
```

### IANA Registry Group

**Template**

``` txt
[NAME] IANA, “Registry Group”, <URL>.
```

**Example**

``` txt
   [IANA-ANCP] IANA, “Access Node Control Protocol (ANCP)”,
   <https://www.iana.org/assignments/ancp>.
```

## Standards

### ISO, IEC, and ISO/IEC

**Template**

**Example**

``` txt
   [SWID] ISO/IEC, "Information technology - IT asset management - Part 2: Software
   identification tag", ISO/IEC 19770-2:2015, October 2015,
   <https://www.iso.org/standard/65666.html>.
```

**Note:**

### IEEE

**Template**

**Example**

``` txt
   [IEEE802.1AX] IEEE, "IEEE Standard for Local and Metropolitan Area Networks
   -- Link Aggregation", IEEE Std 802.1AX-2020, DOI
   10.1109/IEEESTD.2020.9105034, 2020,
   <https://doi.org/10.1109/IEEESTD.2020.9105034>.
```

**Note:**

### ITU / ITU-T

**Template**

**Example**

``` txt
      [TAG]   ITU-T, "Functional requirements of software-
              defined networking", ITU-T Recommendation Y.3301,
              September 2016,
              <http://www.itu.int/rec/T-REC-Y.3301-201609-I/en>.
```

**Note:**

### W3C

**Template**

**Example**

``` txt
 [W3C.XML1.0] Bray, T., Ed., Paoli, J., Ed., Sperberg-McQueen, C.M., Ed., Maler,
 E., Ed., and F. Yergeau, Ed., "Extensible Markup Language (XML) 1.0 (Fifth
 Edition)", W3C Recommendation, 26 November 2008, <https://
 www.w3.org/TR/2008/REC-xml-20081126/>.
```

**Note:**

### WHATWG

**Template**

**Example**

``` txt
   [URL-PATTERN] WHATWG, "URL Pattern", WHATWG Living Standard, <https://urlpattern.spec.whatwg.org/>.

   Commit snapshot: https://urlpattern.spec.whatwg.org/commit-snapshots/d13ebead18003059a83ca4a25240e5cafc066c4c/
```

**Note:**

TODO note about why a commit snapshot is needed TODO should the date be
included

### 3GPP

**Template**

**Example**

**Note:**

### Unicode Consortium

**Template**

**Example**

**Note:**

## General Web Content

TODO Provide reasoning and examples for including dated URIs - when to
use?

**Dated URIs**

From [Section 4.8.6.1 of RFC
7322](https://www.rfc-editor.org/rfc/rfc7322.html#section-4.8.6.1):

> If a dated URI (one that includes a timestamp for the page) is
> available for a referenced web page, its use is required.

### Websites (Homepages, Blogs, etc)

**Template**

``` txt
   [SYMBOLIC-TAG] Author (if available), "Page Title (if available)", Date (if available), <URL>.
```

**Example**

``` txt
   [RFC-Editor] "RFC-Editor", <https://https://www.rfc-editor.org/>.
```

**Note:**

TODO - something about using common sense when it comes to page title -
something about using web archive links / checking the URLs before
submission to make sure they don’t redirect or that content changed over
time.

### Wikipedia Articles

**Template**

``` txt
   [CITE-TAG] Wikipedia, "Title of the Article", Date of most recent edit, <Dated URL>.
```

**Example**

``` txt
  [Magnet]   Wikipedia, "Magnet URI scheme", March 2013,
             <https://en.wikipedia.org/w/
             index.php?title=Magnet_URI_scheme&oldid=546892719>.
```

**Note:**

TODO Note on “most recent edit date”

When constructing the reference target in RFCXML, replace the ‘&’ in the
versioned URL with “&”:

``` xml
<reference anchor="Magnet" target="https://en.wikipedia.org/w/index.php?title=Magnet_URI_scheme&amp;oldid=546892719">
```

## Online Periodicals

### Journal Articles

**Template**

TODO

**Example**

``` txt
   [Dijkstra] Dijkstra, E., "A note on two problems in connexion with graphs", Numerische Mathematik,
              vol. 1, pp. 269-271, DOI 10.1007/BF01386390, December 1959, <https://link.springer.com/
              article/10.1007/BF01386390>.
```

**Note:**

### Conference Papers

**Template**

``` txt
   [CONF-PAPER] Author, A.B., "Title of Paper", Name of Conference, Date, pp. #,
   DOI (if applicable), <URL>.
```

**Example**

**Note:**

### Online Periodical (Newspaper, Magazine, etc.)

**Template**

TODO

**Example**

``` txt
  [Wired-IETF]   Borsook, P., "How Anarchy Works", Wired, October 1995,
                <https://www.wired.com/1995/10/ietf/>.
```

**Note:**

## Academic Sources

### Dissertations

**Template**

**Example**

**Note:**

## Web-based Public Code Repositories

### Repositories

**Template**

TODO

**Example**

``` txt
   [pysaml2] “Python implementation of SAML2”, commit 7135d53, March 2018,
   <https://github.com/IdentityPython/pysaml2>.
```

**Note:**

### Files within a repository

**Template**

TOOD

**Example**

TODO

**Note:**

## Government Publications

### NIST

#### NIST Federal Information Processing Standards Publications (FIPS)

**Template**

``` txt
  [NIST_FIPS] NIST, “Title of FIPS Publication”, NIST FIPS Number, DOI, Date of
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

**Template**

TODO add NIST as publisher?

``` txt
   [NIST_SP] Author(s), “Title of SP”, NIST SP Number, DOI, Date of Publication, <URL>.
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

**Template**

**Example**

**Note:**

## Specific

### Cryptology ePrint Archive Papers

**Template**

``` txt
   [CITE-TAG] Author(s), "Title of Paper", Cryptology ePrint Archive, Paper #, Date
   (year), <URL>.
```

**Example**

``` txt
   Courtois, N., " Security Evaluation of GOST 28147-89 In View Of International
   Standardisation", Cryptology ePrint Archive, Paper 2011/211, 2011,
   <https://eprint.iacr.org/2011/211>.
```

**Note:**

TODO Note on “don’t cite this URL and then include reference information
for the conference proceedings / journal this paper was also published
in. If referencing the Crypto ePrint Archive, use the above template.”

### arXiv Papers

**Template**

**Example**

**Note:**
