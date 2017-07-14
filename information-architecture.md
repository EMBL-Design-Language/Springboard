---
layout: default
title: Information architecture
subtitle: "The structure of EMBL's who, what and where"
group: "in_local_navigation"
order: 3
---

<p class="lead">We use a concept of facets to explain and relate the core EMBL IA. This primarily applies to web content and navigation, but the architecture is also designed to include print and other digital materials (e-mail, slide decks, etc.)</p>

<div class="grid-x grid-padding-x">
<div class="callout large-8 medium-9 small-12 cell" markdown="1">
<hr/>
## Table of contents
Todo: add anchor links
1. What this is about
2. Major facets
3. ...
<hr/>
</div>
</div>

## What this is about

**Add user journey that makes the case for a flexible IA**

User connects to a twitter share story about proteomics, pivots to grenoble...

## Major facets

There are three major facets that reflect EMBL's internal organisation and the outside user's need.

1. Who: the EMBL people involved
1. What: the division (research, services, training, industry transfer)
    - Activity: the type of work being done (disease modeling, bioinformatics, structural biology, mouse biology, etc.)
1. Where: EMBL's six physical geographic sites and virtual websites

Each and all of these three are part and make of [EMBL's mission](https://github.com/EMBL-Design-Language/About#purpose) and they were distilled from EMBL's identity map:

add postits and sphere graph

## Facet structure and categories

The overlay of the IA facets creates a venn diagram mirroring EMBL's mission.

The components of the three major facets that reflect EMBL's internal organisation and the outside user's need.

1. Who
   - people
1. What
   - research
      - Cell Biology and Biophysics
      - Developmental Biology
      - Genome Biology
      - Structural and Computational Biology
      - Directors' Research
      - Tissue biology and disease modelling
      - Mouse biology
      - Bioinformatics (EBI)
   - services
      - online services (EBI)
      - core facilities
   - training
      - online/external
      - collaboration
   - industry transfer
   - about
     - meta info on the mission (news, jobs, mission statement, etc.)
1. Where
   - Heidelberg
   - Barcelona
   - Grenoble
   - Hamburg
   - Hinxton
   - Rome

### Explainer demonstration

**To do: show this as a separate page, or accoridan?**

These facets can be matrixed in a number of ways, here is a sample to help visualise relationships.

**Facets pivoted by EMBL site**<br/>
Note: the information below is representative.

| Where                                                                   |                                      | Heidelberg | Barcelona | Grenoble | Hamburg | Cambridge | Rome |
|-------------------------------------------------------------------------|--------------------------------------|------------|-----------|----------|---------|---------|------|
| **Who**                                                                 |                                      | 12         | 5         | 5        | 6       | 8       | 5    |
| people                                                                  |                                      | X          | X         | X        | X       | X       | X    |
| **What**                                                             | **Activity**                             |            |           |          |         |         |      |
| research                                                                |                                      | X          | X         | X        | X       | X       | X    |
|                                                                         | Cell Biology and Biophysics          | X          |           |          |         |         |      |
|                                                                         | Developmental Biology                | X          |           |          |         |         |      |
|                                                                         | Genome Biology                       | X          |           |          |         |         |      |
|                                                                         | Structural and Computational Biology | X          |           | X        | X       |         |      |
|                                                                         | Directors' Research                  | X          |           |          |         |         |      |
|                                                                         | Tissue biology and disease modelling |            | X         |          |         |         |      |
|                                                                         | Mouse biology                        |            |           |          |         |         | X    |
|                                                                         | bioinformatics (EBI)                 |            |           |          |         | X       |      |
| services                                                                |                                      |            |           |          |         |         |      |
|                                                                         | online services (EBI)                |            |           |          |         | X       |      |
|                                                                         | core facilities                      | X          |           |          | X       |         |      |
| training                                                                |                                      |            |           |          |         |         |      |
|                                                                         | online/external                      | X          |           |          |         | X       |      |
|                                                                         | collaboration                        | X          | X         | X        | X       | X       | X    |
| industry transfer                                                       |                                      | X          |           |          |         | X       |      |
| about                                         | meta info on the mission (news, jobs, mission statement, etc.) | X          | X         | X        | X       | X       | X    |




## IA Functional requirements

From the above we can draw three major requirements on what the IA must provide:

A visulisation of how these interplay:
<img src="https://raw.githubusercontent.com/EMBL-Design-Language/Information-Architecture/master/assets/ia-map-v3.png" />


### 1. Extreme flexibility: Impact on structures

The mix of facets presented will vary across each content item (microsite, service, homepage, brochure).

Content templates must accommodate a mix of any/all the major facets, or they need to specifically exclude address limited facets (i.e. A research webpage template can never be used for training, services, or industry transfer)
  - No website sub-page lock in:
    - Navigation must allow easy transition between areas (i.e. from "Rome research" to "Heidelberg research")
    - As user needs vary we must shift the presentation order of each facet and some content will be location specific:
      - a list of structural researchers;
      - a visitor map of the EMBL Cambridge (EMBL-EBI); or
      - a bioinformatics service listing.
  - Always point to the "mothership":
    - EMBL's diversified (silo) nature means a user may navigate down to (or enter from) a distant brand sub-point (i.e. Ensembl) and a user should always be able to traverse the chain back to EMBL. Both navigationally and branding-wise.


### 2. Content maps to user needs: Only as important as it is to a user

The facets used by content are linked to targeted user types so we can map content -> users -> goals.

The importance of each major facet varies according to user needs at a given time; a user might:
- look to connect a person at EMBL;
- find a bioinformatics service/tool;
- read about news from EMBL Rome; or
- discover structural biology research being performed by Jane Doe at Grenoble.

### 3. Support multiple relationships: A world of parents, funders, sponsors, collaborators

Many sub-pages have a plethora of relationships, from collaborators, funders, parent organisations, to endorsements. We need a structured and visually semantic/intuitive way to represent these.

More to come. (will reference work done for ELIXIR; see owncloud documents for now)




## Facets of content types

Core content types are common throughout EMBL (people, news, events) and we will want to share, import, compile, and distribute these. So it is important that we have an agreement on what these content types are made of.

Note: all content facets contain: who, what and where (the major facet) records.

#### News

- Headline (text, 255 chars)
- URL
- Body (rich text/html)
- Image
- **Who**: Associated people and/or teams
  - Reference EMBL person(s) and/or free-form name+URL
- **What**: Major domain; multi-level (research, research->structural, services, training, training->bioinformatics)
- **Where**: The related organisation(s), EMBL, Rome, etc.
- Tags
  - Topic tags: free form
  - [EDAM ontology](https://www.ebi.ac.uk/ols/ontologies/edam)
- Source link: Specifically when re-posting news snippets
- Semantic meta-information (optional):
  - Longevity: Score of how long this will be relevant for [0-100]
  - Importance: Score of how "important" this is [0-100]

#### People
... to come

#### Events
.. to come

#### More types
.. to come



## Facets on print materials, slides

This is somewhat less complex as it does not need to facilitate navigation, however the contextual placement who, what and where is still important.

(Add information and diagrams here)


## Facets on websites

### Facets in URL structures

While the major facets may in some case be directly accessible by domain URLs (that is: all Cambridge-specific information can be portaled via www.ebi.ac.uk, or a specific training event might have micro-site domain).

#### EMBL.org Patterns for website URL paths

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

#### Notes on non-EMBL.org domains

There are instances when content can also be available outside the EMBL.org site, these domains should be set up in consultation with the "content architecture team" (likely some hybrid of EMBL communications and EMBL-EBI web dev?).

Some examples:
1. all Cambridge-specific information is portaled via `www.ebi.ac.uk`
2. a specific training event might have micro-site domain
3. an online service will likely have an application-specific URL

Note that in all of these cases, content should be pulled from the main EMBL.org "content engine" (to be defined in another document) where possible to avoid data duplication.


### Faceted website navigation

There are three main concepts in our navigation: scope, reset, and pivot.

Let's look back at our IA requirements, particularly item #1:
> 1. Extreme flexibility: Impact on structures
> The mix of facets presented will vary across each content item (microsite, service, homepage, brochure).
>
> As user needs vary we must shift the presentation order of each facet and some content will be location specific:
> - a list of structural researchers;
> - a visitor map of the EMBL Cambridge (EMBL-EBI); or
> - a bioinformatics service listing.
> - The website structure must be able to facilitate multi-faceted content categorisation and user navigation.

This means we must
1. Many paths: provide the functional ability to navigate a series of website properties that can share many or few relationships
2. Orientation: provide enough context/hierarchy/rigidity to allow the user to orient; and
3. Flexibility: enough flexibility to allow the site maintainers to customise within the scope of the system.

Not hard, but it will be complex.

#### Schematic

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

{% include navigation_list.html %}
