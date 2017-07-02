# Information Architecture: URL Structures
##### Part of the EMBL Design Language

While the major facets may in some case be directly accesable by domain URLs (that is: all Cambrige-specific information can be portaled via www.ebi.ac.uk, or a specific training event might have micro-site domain), all EMBL.org url partterns are as follows:

## EMBL.org Patterns for website URL paths

- EMBL.org: portal to all EMBL content
- EMBL.org/`%facet%`/`%optional_facet_2%`/: immediately following the URL [is one of the facets](https://github.com/EMBL-Design-Language/Information-Architecture/blob/master/facets.md); that is:
    - `EMBL.org/people`: people directory 
    - `EMBL.org/hamburg`: all Hamburg-specific information
      - `EMBL.org/hamburg/about`: About the hamburg site
    - `EMBL.org/research`: all research information
    
These URLs are shortcuts for facet query paramaters:
1. Who	
   - people: `?facet=people`
1. Mission
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
1. all Cambrige-specific information is portaled via `www.ebi.ac.uk`
2. a specific training event might have micro-site domain
3. an online service will likely have an application-specific URL

Note that in all of these cases, content should be pulled from the main EMBL.org "content engine" (to be defined in another document) where possible to avoid data duplication.
