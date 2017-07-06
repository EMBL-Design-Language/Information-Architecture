# Information Architecture: Website navigation

There are three main concepts in our navigation: scope, reset, and pivot. Read on for more on those.

##### Part of the EMBL Design Language Information Architecture
1. [Overview](https://github.com/EMBL-Design-Language/Information-Architecture)
1. [Architecture facets](https://github.com/EMBL-Design-Language/Information-Architecture/blob/master/facets-architecture.md)
    1. [Content facets](https://github.com/EMBL-Design-Language/Information-Architecture/blob/master/facets-content.md)
1. Websites
    1. [Navigation](https://github.com/EMBL-Design-Language/Information-Architecture/blob/master/website-navigation.md) (this document)
    1. [URL Structures](https://github.com/EMBL-Design-Language/Information-Architecture/blob/master/website-url-structure.md)

## Intro
It's worth a moment to look back at our IA requirements, particularly item #1:
> 1. Extreme flexibility: Impact on structures
> The mix of facets presented will vary across each content item (microsite, service, homepage, brochure).
>
> As user needs vary we must shift the presentation order of each facet and some content will be location specific:
> - a list of structural researchers;
> - a visitor map of the EMBL Cambridge (EBI); or
> - a bioinformatics service listing.
> - The website structure must be able to facilitate multi-faceted content categorisation and user navigation.

This means we must
1. Many paths: provide the functional ability to navigate a series of website properties that can share many or few relationships
2. Orientation: provide enough context/hierarchy/rigidity to allow the user to orient; and
3. Flexibility: enough flexibility to allow the site maintainers to customise within the scope of the system.

Not hard, but it will be complex.

## Schematic

A reminder of what we're trying to make navigable:

<img src="https://raw.githubusercontent.com/EMBL-Design-Language/Information-Architecture/master/assets/ia-map-v3.png"/>

Each of these scenarios will have:
1. Incremental context-specific navigation (i.e. a research overview page will link to research teams)
1. "Wormhole" navigation; to illustrate:
    1. The `EMBL logo` is linked to the `embl.org` for quick escape to the homepage
    1. The `Grenoble Research` page needs "pivot" navigation to:
        - `Rome Research`
        - `Grenoble People`

That is, navigation must allow the user to:
- Scope: Widen and narrow scope of content (likely in-context incremental navigation)
- Reset: Allow escape to the homepage (traditional logo linking)
- Pivot: Transition from one facet (who, what, or where) to another (from Cambridge information to Grenoble)

[to do: add illustrations of these paths]
