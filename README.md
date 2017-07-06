# Information-Architecture
##### Part of the EMBL Design Language
The structure of EMBL's who, what and where.

This primarily applies to web content and navigation, but this architecture is also designed to include print and other digital materials as well (e-mail, slide decks, etc.)

## TOC
1. [Overview](https://github.com/EMBL-Design-Language/Information-Architecture) (this document)
1. [Architecture facets](https://github.com/EMBL-Design-Language/Information-Architecture/blob/master/facets-architecture.md)
    1. [Content facets](https://github.com/EMBL-Design-Language/Information-Architecture/blob/master/content-facets.md)
1. Websites
    1. [Navigation](https://github.com/EMBL-Design-Language/Information-Architecture/blob/master/website-navigation.md)
    1. [URL Structures](https://github.com/EMBL-Design-Language/Information-Architecture/blob/master/website-url-structure.md)

## Major facets

There are three major facets that reflect EMBL's internal organisation and the outside user's need. 

1. Who: the EMBL people involved
1. What: the division (research, services, training, industry transfer)
    - Activity: the type of work being done (disease modeling, bioinformatics, structural biology, mouse biology, etc.)
1. Where: EMBL's six physical geographic sites and virtual websites

Each and all of these three are part and make of [EMBL's mission](https://github.com/EMBL-Design-Language/About#purpose).

A visulisation of how these interplay:
<img src="https://raw.githubusercontent.com/EMBL-Design-Language/Information-Architecture/master/assets/ia-map-v3.png" />

For more details on facets as they map to EMBL's structure, [see this explainer](https://github.com/EMBL-Design-Language/Information-Architecture/blob/master/facets.md)

## Requirements

From the above we can draw requirements on what the IA must provide:
1. Extreme flexibility: Content templates must accommodate a mix of any/all the major facets, or they need to specifically exclude address limited facets (i.e. A research webpage template can never be used for training, services, or industry transfer)
    - No website sub-page lock in: Navigation must allow easy transition between areas (i.e. from "Rome research" to "Heidelberg research")
    - Always point to the "mothership": EMBL's diversified (silo) nature means a user may navigagte down to (or enter from) a distant brand subpoint (i.e. Ensembl) and a user should always be able to traverse the chain back to EMBL. Both navigationally and branding-wise
1. Content maps to user needs: the facets used by content can reveal target users (once we identify our target user types)
    - Goals: we can map the content -> users -> goals. These should be trackable (this is easier with web analytics, but not impossible in print)
1. Support multiple relationships: Many sub-pages have a plethora of relationships, from collaborators, funders, parent organisations, to endorsements. We need a structured and visually semantic/intuitive way to represent these.

### 1. Extreme flexibility: Impact on structures 

The mix of facets presented will vary across each content item (microsite, service, homepage, brochure).

As user needs vary we must shift the presentation order of each facet and some content will be location specific: 
- a list of structural researchers;
- a visitor map of the EMBL Cambridge (EBI); or
- a bioinformatics service listing. 

The website structure must be able to facilitate multi-faceted content categorisation and user navigation. 

### 2. Content maps to user needs: Only as important as it is to a user

The importance of each major facet varies according to user needs at a given time; a user might: 
- look to connect a person at EMBL;
- find a bioinformatics service/tool;
- read about news from EMBL Rome; or
- discover structural biology research being performed by Jane Doe at Grenoble. 

### 3. Support multiple relationships: A world of parents, funders, sponsors, collaborators
To come. (will reference work done for ELIXIR; see owncloud documents for now)
