# Information Architecture: URL Structures

While the major facets may in some case be directly accesable by domain URLs (that is: all Cambrige-specific information can be portaled via www.ebi.ac.uk, or a specific training event might have micro-site domain).

##### Part of the EMBL Design Language Information Architecture
1. [Overview](https://github.com/EMBL-Design-Language/Information-Architecture)
1. [Architecture facets](https://github.com/EMBL-Design-Language/Information-Architecture/blob/master/facets-architecture.md)
    1. [Content facets](https://github.com/EMBL-Design-Language/Information-Architecture/blob/master/facets-content.md)
1. Websites
    1. [Navigation](https://github.com/EMBL-Design-Language/Information-Architecture/blob/master/website-navigation.md)
    1. [URL Structures](https://github.com/EMBL-Design-Language/Information-Architecture/blob/master/website-url-structure.md) (this document)

## EMBL.org Patterns for website URL paths

All EMBL.org url patterns are as follows:

- EMBL.org: portal to all EMBL content
- EMBL.org/`%facet%`/`%optional_facet_2%`/: [facets](https://github.com/EMBL-Design-Language/Information-Architecture/blob/master/facets.md) are appended immediately after the domain; that is:
    - `EMBL.org/people`: people directory
    - `EMBL.org/hamburg`: all Hamburg-specific information
      - `EMBL.org/hamburg/about`: About the hamburg site
    - `EMBL.org/research`: all research information

These URLs are shortcuts for facet query parameters:
1. Who
   - people: `?facet=people`
1. What
   - research: `?facet=research`
      - Cell Biology and Biophysics: `?facet=research-cell`
      - ...
   - services: `?facet=services`
      - online services (EBI): `?facet=services-online`
      - core facilities: `?facet=services-core`
   - ...
1. Where					
   - Heidelberg: `?facet=heidelberg`
   - ...

## Notes on non-EMBL.org domains

There are instances when content can also be available outside the EMBL.org site, these domains should be set up in consultation with the "content architecture team" (likely some hybrid of EMBL communications and EMBL-EBI web dev?).

Some examples:
1. all Cambridge-specific information is portaled via `www.ebi.ac.uk`
2. a specific training event might have micro-site domain
3. an online service will likely have an application-specific URL

Note that in all of these cases, content should be pulled from the main EMBL.org "content engine" (to be defined in another document) where possible to avoid data duplication.
