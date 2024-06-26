---
title: Darwin Core
description: >
  Darwin Core is a standard maintained by the [Darwin Core maintenance group](/community/dwc). It includes a glossary of terms intended to **facilitate the sharing of information about biological diversity** by providing identifiers, labels, and definitions. Darwin Core is primarily based on taxa, their occurrence in nature as documented by observations, specimens, samples, and related information.
background:
  img: https://images.unsplash.com/photo-1492031215329-791748ee1253
  by: Alex Guillaume
  href: https://unsplash.com/photos/0MC0o-xLucM
github: https://github.com/tdwg/dwc
website: https://dwc.tdwg.org
toc: true
---

## Header section

Title
: Darwin Core

Permanent IRI (for citations and links)
: <http://www.tdwg.org/standards/450>

Publisher
: Biodiversity Information Standards (TDWG)

Ratified
: 2009-10-09

Status
: [Current standard](/standards/status-and-categories/#status)

Category
: [Technical specification](/standards/status-and-categories/#category)

Abstract
: Darwin Core is a standard maintained by the Darwin Core maintenance group. It includes a glossary of terms (in other contexts these might be called properties, elements, fields, columns, attributes, or concepts) intended to facilitate the sharing of information about biological diversity by providing identifiers, labels, and definitions. Darwin Core is primarily based on taxa, their occurrence in nature as documented by observations, specimens, samples, and related information.

Citation
: Darwin Core Task Group. 2009. Darwin Core. Biodiversity Information Standards (TDWG) <http://www.tdwg.org/standards/450>

## Maintenance group

Modifications and enhancements to Darwin Core are managed by the [Darwin Core Maintenance Group](/community/dwc).

The best way to be involved is to create an account on [GitHub](https://github.com), and "watch" the [Darwin Core GitHub repository](https://github.com/tdwg/dwc), as well as the [Darwin Core Questions & Answers repository](https://github.com/tdwg/dwc-qa), and respond to requests for comments or "issues" ([Darwin Core issues](https://github.com/tdwg/dwc/issues) and [Darwin Core QA issues](https://github.com/tdwg/dwc-qa/issues/)). Information about how to suggest changes to the standard can be found at the [Guidelines for Contributing](https://github.com/tdwg/dwc/blob/master/.github/CONTRIBUTING.md) page.

## Scope of Darwin Core

What is in scope?

- Collections of any kind of biological objects or data.
- Terminology associated with biological collection data.
- Striving for compatibility with other biodiversity-related standards.
- Facilitating the addition of components and attributes of biological data.

What is not in scope?

- Data interchange protocols.
- Non-biodiversity-related data.
- Purely taxonomic data.

## Audience

- Biodiversity data holders (organizations, institutions, researchers).
- Consumers of biodiversity data.
- Developers of collections management systems.
- Other TDWG interest and task groups.
- Protocol developers (TAPIR).
- Biodiversity network developers.

## Contributors

[List of contributors](https://github.com/tdwg/dwc/contributors)

## Resources

- Quick Reference Guide <https://dwc.tdwg.org/terms/>
- Maintenance group: <https://www.tdwg.org/community/dwc/>
- Primary collaboration platform: <https://github.com/tdwg/dwc>
- Darwin Core Questions & Answers: <https://github.com/tdwg/dwc-qa>
- Darwin Core landing page (this page): <https://www.tdwg.org/standards/dwc/>

## Parts of the standard

This standard is comprised of 7 vocabularies and 12 documents.

Vocabularies:

- Darwin Core main vocabulary (<http://rs.tdwg.org/dwc/>)
- establishmentMeans controlled vocabulary (<http://rs.tdwg.org/dwcem/>)
- degreeOfEstablishment controlled vocabulary (<http://rs.tdwg.org/dwcdoe/>)
- pathway controlled vocabulary (<http://rs.tdwg.org/dwcpw/>)
- Darwin Core Chronometric Age Extension vocabulary (<http://rs.tdwg.org/chrono/>)
- Humboldt Extension vocabulary (<http://rs.tdwg.org/eco/>)
- Taxon Completeness Reported Controlled Vocabulary (<http://rs.tdwg.org/ecotcr/>)

Documents:

### Darwin Core RDF Guide

Title
: Darwin Core RDF Guide

Permanent IRI
: [http://rs.tdwg.org/dwc/terms/guides/rdf/](https://dwc.tdwg.org/rdf/)

Created
: 2015-06-02

Last modified
: 2015-06-02

Contributors
: Steve Baskauf (lead author) - TDWG RDF/OWL Task Group
: John Wieczorek (author) - TDWG Darwin Core Task Group
: John Deck (author) - Genomic Biodiversity Working Group
: Campbell Webb (author) - TDWG RDF/OWL Task Group
: Paul J. Morris (author) - Harvard University Herbaria/Museum of Comparative Zoölogy
: Mark Schildhauer (author) - National Center for Ecological Analysis and Synthesis

Publisher
: Biodiversity Information Standards (TDWG)

Abstract
: This guide is intended to facilitate the use of Darwin Core terms in the Resource Description Framework (RDF). It explains basic features of RDF and provides details of how to expose data in the form of RDF using Darwin Core terms and terms from other key vocabularies. It defines terms in the namespace <http://rs.tdwg.org/dwc/iri/> which are intended for use excusively with non-literal objects.

Citation
: Darwin Core and RDF/OWL Task Groups. 2015. Darwin Core RDF Guide. Biodiversity Information Standards (TDWG). <http://rs.tdwg.org/dwc/terms/guides/rdf/>

### Darwin Core Text Guide

Title
: Darwin Core Text Guide

Permanent IRI
: [http://rs.tdwg.org/dwc/terms/guides/text/](https://dwc.tdwg.org/text/)

Created
: 2014-11-08

Last modified
: 2021-07-15

Contributors
: Tim Robertson (lead author) - Global Biodiversity Information Facility
: Markus Döring (author) - Global Biodiversity Information Facility
: John Wieczorek (author) - Darwin Core Maintenance Group
: Renato De Giovanni (author) - Centro de Referência em Informação Ambiental
: Dave Vieglais (author) - KU Natural History Museum
: Steve Baskauf (author) - Darwin Core Maintenance Group
: Gail E. Kampmeier (review manager) - University of Illinois at Urbana-Champaign

Publisher
: Biodiversity Information Standards (TDWG)

Abstract
: This document provides guidelines for implementing Darwin Core in Text files.

Citation
: Darwin Core Task Group. 2014. Darwin Core Text Guide. Biodiversity Information Standards (TDWG). <http://rs.tdwg.org/dwc/terms/guides/text/>

### Darwin Core XML Guide

Title
: Darwin Core XML Guide

Permanent IRI
: [http://rs.tdwg.org/dwc/terms/guides/xml/](https://dwc.tdwg.org/xml/)

Created
: 2014-11-08

Last modified
: 2014-11-08

Contributors
: John Wieczorek (lead author) - Museum of Vertebrate Zoology at Berkeley
: Markus Döring (author) - Global Biodiversity Information Facility
: Renato De Giovanni (author) - Centro de Referência em Informação Ambiental
: Tim Robertson (author) - Global Biodiversity Information Facility
: Dave Vieglais (author) - KU Natural History Museum
: Gail E. Kampmeier (review manager) - University of Illinois at Urbana-Champaign

Publisher
: Biodiversity Information Standards (TDWG)

Abstract
: This document provides guidelines for the implementation of Darwin Core in XML.

Citation
: Darwin Core Task Group. 2014. Darwin Core XML Guide. Biodiversity Information Standards (TDWG). <http://rs.tdwg.org/dwc/terms/guides/xml/>

### Simple Darwin Core

Title
: Simple Darwin Core

Permanent IRI
: [http://rs.tdwg.org/dwc/terms/simple/](https://dwc.tdwg.org/simple/)

Created
: 2014-11-08

Last modified
: 2014-11-08

Contributors
: John Wieczorek (lead author) - Museum of Vertebrate Zoology at Berkeley
: Markus Döring (author) - Global Biodiversity Information Facility
: Renato De Giovanni (author) - Centro de Referência em Informação Ambiental
: Tim Robertson (author) - Global Biodiversity Information Facility
: Dave Vieglais (author) - KU Natural History Museum
: Gail E. Kampmeier (review manager) - University of Illinois at Urbana-Champaign

Publisher
: Biodiversity Information Standards (TDWG)

Abstract
: This document is a reference for the Simple Darwin Core standard, a mechanism used to share biodiversity information using the simplest methods and structure.

Citation
: Darwin Core Task Group. 2014. Simple Darwin Core. Biodiversity Information Standards (TDWG). <http://rs.tdwg.org/dwc/terms/simple/>

### Darwin Core Namespace Policy

Title
: Darwin Core Namespace Policy

Permanent IRI
: [http://rs.tdwg.org/dwc/terms/namespace/](https://dwc.tdwg.org/namespace/)

Created
: 2014-11-08

Last modified
: 2014-11-08

Contributors
: John Wieczorek (lead author) - Museum of Vertebrate Zoology at Berkeley
: Markus Döring (author) - Global Biodiversity Information Facility
: Renato De Giovanni (author) - Centro de Referência em Informação Ambiental
: Tim Robertson (author) - Global Biodiversity Information Facility
: Dave Vieglais (author) - KU Natural History Museum
: Gail E. Kampmeier (review manager) - University of Illinois at Urbana-Champaign

Publisher
: Biodiversity Information Standards (TDWG)

Abstract
: All terms in the Darwin Core must be assigned a unique Uniform Resource Identifier (URI). For convenience, the term URIs that are assigned and managed by the Darwin Core Task Group are grouped into collections known as Darwin Core namespaces. This document describes how term URIs are allocated by the Darwin Core Task Group and the policies associated with Darwin Core namespaces.

Citation
: Darwin Core Task Group. 2014. Darwin Core Namespace Policy. Biodiversity Information Standards (TDWG). <http://rs.tdwg.org/dwc/terms/namespace/>

### Darwin Core List of Terms

Title
: Darwin Core List of Terms

Permanent IRI
: [http://rs.tdwg.org/dwc/doc/list/](https://dwc.tdwg.org/list/)

Created
: 2020-08-12

Last modified
: 2023-09-18

Contributors
: [John Wieczorek](https://orcid.org/0000-0003-1144-0290) ([VertNet](http://www.wikidata.org/entity/Q98382028))
: [Peter Desmet](https://orcid.org/0000-0002-8442-8025) ([Instituut voor Natuur- en Bosonderzoek (INBO)](http://www.wikidata.org/entity/Q7315097))
: [Steve Baskauf](https://orcid.org/0000-0003-4365-3135) ([Vanderbilt University Libraries](http://www.wikidata.org/entity/Q16849893))
: [Tim Robertson](https://orcid.org/0000-0001-6215-3617) ([Global Biodiversity Information Facility](http://www.wikidata.org/entity/Q1531570))
: [Markus Döring](https://orcid.org/0000-0001-7757-1889) ([Global Biodiversity Information Facility](http://www.wikidata.org/entity/Q1531570))
: [Quentin Groom](https://orcid.org/0000-0002-0596-5376) ([Botanic Garden Meise](http://www.wikidata.org/entity/Q3052500))
: [Stijn Van Hoey](https://orcid.org/0000-0001-6413-3185) ([Instituut voor Natuur- en Bosonderzoek (INBO)](http://www.wikidata.org/entity/Q7315097))
: [David Bloom](https://orcid.org/0000-0003-1273-1807) ([VertNet](http://www.wikidata.org/entity/Q98382028))
: [Paula Zermoglio](https://orcid.org/0000-0002-6056-5084) ([VertNet](http://www.wikidata.org/entity/Q98382028))
: [Robert Guralnick](https://orcid.org/0000-0001-6682-1504) ([University of Florida](http://www.wikidata.org/entity/Q501758))
: [John Deck](https://orcid.org/0000-0002-5905-1617) ([Genomic Biodiversity Working Group](http://www.wikidata.org/entity/Q98382041))
: [Gail Kampmeier](https://orcid.org/0000-0002-5178-4170) ([Illinois Natural History Survey](http://www.wikidata.org/entity/Q5999587))
: [Dave Vieglais](https://orcid.org/0000-0002-6513-4996) ([KU Natural History Museum](http://www.wikidata.org/entity/Q1111807))
: [Renato De Giovanni](https://orcid.org/0000-0002-7104-7266) ([Centro de Referência em Informação Ambiental](http://www.wikidata.org/entity/Q29168927))
: [Campbell Webb](https://orcid.org/0000-0003-1031-3249) ([TDWG RDF/OWL Task Group](http://www.wikidata.org/entity/Q4914768))
: [Paul J. Morris](http://purl.oclc.org/net/edu.harvard.huh/guid/uuid/5e51de22-d841-4c47-b0c4-d5ad0bd03035) ([Harvard University Herbaria/Museum of Comparative Zoölogy](http://www.wikidata.org/entity/Q51926077))
: [Mark Schildhauer](https://orcid.org/0000-0003-0632-7576) ([National Center for Ecological Analysis and Synthesis](http://www.wikidata.org/entity/Q6971323))
: [Sophia Ratcliffe](https://orcid.org/0000-0001-9284-7900) ([National Biodiversity Network Trust](http://www.wikidata.org/entity/Q6970988))
: [Teresa J. Mayfield-Meyer](https://orcid.org/0000-0002-1970-7044) ([The University of New Mexico, Arctos](http://www.wikidata.org/entity/Q1190812))
: [Christian Bölling](https://orcid.org/0000-0002-6544-1363) ([Museum für Naturkunde Berlin - Leibniz-Institut für Evolutions- und Biodiversitätsforschung](http://www.wikidata.org/entity/Q233098))

Publisher
: Biodiversity Information Standards (TDWG)

Abstract
: Darwin Core is a vocabulary standard for transmitting information about biodiversity. This document lists all terms in namespaces currently used in the vocabulary.

Citation
: Darwin Core Maintenance Group. 2023. List of Darwin Core terms. Biodiversity Information Standards (TDWG). <http://rs.tdwg.org/dwc/doc/list/2023-09-18>

### Degree of Establishment Controlled Vocabulary List of Terms

Title
: Degree of Establishment Controlled Vocabulary List of Terms

Permanent IRI
: [http://rs.tdwg.org/dwc/doc/doe/](https://dwc.tdwg.org/doe/)

Created
: 2020-10-13

Last modified
: 2021-09-01

Contributors
: Quentin Groom (lead author) - Botanic Garden Meise
: Peter Desmet (contributor) - Instituut voor Natuur- en Bosonderzoek (INBO)
: Lien Reyserhove (contributor) - Instituut voor Natuur- en Bosonderzoek (INBO)
: Tim Adriaens (contributor) - Instituut voor Natuur- en Bosonderzoek (INBO)
: Damiano Oldoni (contributor) - Instituut voor Natuur- en Bosonderzoek (INBO)
: Sonia Vanderhoeven (contributor) - Belgian Biodiversity Platform
: Steven J Baskauf (contributor) - Vanderbilt University Libraries
: Arthur Chapman (contributor) - Australian Biodiversity Information Services
: Melodie McGeoch (contributor) - McGeoch Research Group
: Ramona Walls (contributor) - University of Arizona
: John Wieczorek (contributor) - VertNet
: John R.U. Wilson (contributor) - South African National Biodiversity Institute
: Paula F F Zermoglio (contributor) - VertNet
: Annie Simpson (contributor) - U.S. Geological Survey

Publisher
: Biodiversity Information Standards (TDWG)

Abstract
: The Darwin Core term degreeOfEstablishment provides information about degree to which an Organism survives, reproduces, and expands its range at the given place and time.. The Degree of Establishment Controlled Vocabulary provides terms that should be used as values for dwc:degreeOfEstablishment and dwciri:degreeOfEstablishment.

Citation
: Darwin Core Maintenance Group. 2020. Degree of Establishment Controlled Vocabulary List of Terms. Biodiversity Information Standards (TDWG). <http://rs.tdwg.org/dwc/doc/doe/2020-10-13>

### Establishment Means Controlled Vocabulary List of Terms

Title
: Establishment Means Controlled Vocabulary List of Terms

Permanent IRI
: [http://rs.tdwg.org/dwc/doc/em/](https://dwc.tdwg.org/em/)

Created
: 2020-10-13

Last modified
: 2021-09-01

Contributors
: Quentin Groom (lead author) - Botanic Garden Meise
: Peter Desmet (contributor) - Instituut voor Natuur- en Bosonderzoek (INBO)
: Lien Reyserhove (contributor) - Instituut voor Natuur- en Bosonderzoek (INBO)
: Tim Adriaens (contributor) - Instituut voor Natuur- en Bosonderzoek (INBO)
: Damiano Oldoni (contributor) - Instituut voor Natuur- en Bosonderzoek (INBO)
: Sonia Vanderhoeven (contributor) - Belgian Biodiversity Platform
: Steven J Baskauf (contributor) - Vanderbilt University Libraries
: Arthur Chapman (contributor) - Australian Biodiversity Information Services
: Melodie McGeoch (contributor) - McGeoch Research Group
: Ramona Walls (contributor) - University of Arizona
: John Wieczorek (contributor) - VertNet
: John R.U. Wilson (contributor) - South African National Biodiversity Institute
: Paula F F Zermoglio (contributor) - VertNet
: Annie Simpson (contributor) - U.S. Geological Survey

Publisher
: Biodiversity Information Standards (TDWG)

Abstract
: The Darwin Core term establishmentMeans provides information about whether an organism or organisms have been introduced to a given place and time
through the direct or indirect activity of modern humans. The Establishment Means Controlled Vocabulary provides terms that should be used as values for dwc:establishmentMeans and dwciri:establishmentMeans.

Citation
: Darwin Core Maintenance Group. 2020. Establishment Means Controlled Vocabulary List of Terms. Biodiversity Information Standards (TDWG). <http://rs.tdwg.org/dwc/doc/em/2020-10-13>

### Pathway Controlled Vocabulary List of Terms

Title
: Pathway Controlled Vocabulary List of Terms

Permanent IRI
: [http://rs.tdwg.org/dwc/doc/pw/](https://dwc.tdwg.org/pw/)

Created
: 2020-10-13

Last modified
: 2021-09-01

Contributors
: Quentin Groom (lead author) - Botanic Garden Meise
: Peter Desmet (contributor) - Instituut voor Natuur- en Bosonderzoek (INBO)
: Lien Reyserhove (contributor) - Instituut voor Natuur- en Bosonderzoek (INBO)
: Tim Adriaens (contributor) - Instituut voor Natuur- en Bosonderzoek (INBO)
: Damiano Oldoni (contributor) - Instituut voor Natuur- en Bosonderzoek (INBO)
: Sonia Vanderhoeven (contributor) - Belgian Biodiversity Platform
: Steven J Baskauf (contributor) - Vanderbilt University Libraries
: Arthur Chapman (contributor) - Australian Biodiversity Information Services
: Melodie McGeoch (contributor) - McGeoch Research Group
: Ramona Walls (contributor) - University of Arizona
: John Wieczorek (contributor) - VertNet
: John R.U. Wilson (contributor) - South African National Biodiversity Institute
: Paula F F Zermoglio (contributor) - VertNet
: Annie Simpson (contributor) - U.S. Geological Survey

Publisher
: Biodiversity Information Standards (TDWG)

Abstract
: The Darwin Core term pathway provides information about the process by which an Organism came to be in a given place at a given time. The Pathway Controlled Vocabulary provides terms that should be used as values for dwc:pathway and dwciri:pathway.

Citation
: Darwin Core Maintenance Group. 2020. Pathway Controlled Vocabulary List of Terms. Biodiversity Information Standards (TDWG). <http://rs.tdwg.org/dwc/doc/pw//2020-10-13>

### Chronometric Age Vocabulary List of Terms

Title
: Chronometric Age Vocabulary List of Terms

Permanent IRI
: [http://rs.tdwg.org/dwc/doc/chrono/](https://tdwg.github.io/chrono/list/)

Created
: 2021-04-27

Last modified
: 2021-04-27

Contributors
: John Wieczorek (lead author) - VertNet
: Laura Brenskelle (contributor) - University of Florida
: Robert Guralnick (contributor) - University of Florida
: Kitty Emery (contributor) - University of Florida
: Michelle LeFebvre (contributor) - University of Florida
: Neill Wallis (contributor) - University of Florida
: Steve Baskauf (contributor) - Vanderbilt University Libraries
: Marie Elise Lecoq (contributor)
: Eric Kansa (contributor) - Harvard University
: Sarah Kansa (contributor) - The Alexandria Archive Institute
: Denné Reed (contributor) - University of Texas at Austin

Publisher
: Biodiversity Information Standards (TDWG)

Abstract
: The Chronometric Age Vocabulary is a standard for transmitting information about chronometric ages - the processes and results of an assay or other analysis used to determine the age of a MaterialSample. This document lists all terms in namespaces currently used in the vocabulary.

Citation
: TDWG Darwin Core Chronometric Age Extension Task Group. 2021. Chronometric Age Vocabulary List of Terms. Biodiversity Information Standards (TDWG). <http://rs.tdwg.org/dwc/doc/chrono/2021-04-27>

### Humboldt Extension Vocabulary List of Terms

Title
: Humboldt Extension Vocabulary List of Terms

Permanent IRI
: <http://rs.tdwg.org/dwc/doc/eco/>

Created
: 2024-02-28

Last modified
: 2024-03-26


Contributors
: [Yanina V. Sica](https://orcid.org/0000-0002-1720-0127) ([Yale University](http://www.wikidata.org/entity/Q49112))
: [Kate Ingenloff](https://orcid.org/0000-0001-5942-9053) ([Global Biodiversity Information Facility (GBIF)](http://www.wikidata.org/entity/Q1531570))
: [Paula Zermoglio](https://orcid.org/0000-0002-6056-5084) ([Instituto de Investigaciones en Recursos Naturales, Agroecología y Desarrollo Rural (IRNAD), UNRN-CONICET](http://www.wikidata.org/entity/Q6156591))
: [Yi-Ming Gan](https://orcid.org/0000-0001-7087-2646) ([Royal Belgian Institute of Natural Sciences](http://www.wikidata.org/entity/Q16665660))
: [Peter Brenton](https://orcid.org/0000-0001-9730-8340) ([Atlas of Living Australia, CSIRO](http://www.wikidata.org/entity/Q16335177))
: [John Wieczorek](https://orcid.org/0000-0003-1144-0290) ([VertNet](http://www.wikidata.org/entity/Q98382028))
: [Wesley M. Hochachka](https://orcid.org/0000-0002-0595-7827) ([Cornell Lab of Ornithology](http://www.wikidata.org/entity/Q2997535))
: [Zachary R. Kachian](https://orcid.org/0000-0002-0500-0339) ([Keller Science Action Center, Field Museum of Natural History](http://www.wikidata.org/entity/Q1122595))
: [Robert D. Stevenson](https://orcid.org/0000-0003-1617-5895) ([Department of Biology, University of Massachusetts Boston](http://www.wikidata.org/entity/Q15144))
: [Anahita J. N. Kazem](https://orcid.org/0000-0003-2475-132X) ([German Centre for Integrative Biodiversity Research, Leipzig and Friedrich Schiller University, Jena](http://www.wikidata.org/entity/Q1206134))
: [Dmitry Schigel](https://orcid.org/0000-0002-2919-1168) ([Global Biodiversity Information Facility (GBIF)](http://www.wikidata.org/entity/Q1531570))
: [Steven J. Baskauf](https://orcid.org/0000-0003-4365-3135) ([Vanderbilt University Libraries](http://www.wikidata.org/entity/Q16849893))
: [Tomomi Suwa](https://orcid.org/0000-0001-5010-3452) ([Keller Science Action Center, Field Museum of Natural History](http://www.wikidata.org/entity/Q1122595))
: [Robert Guralnick](https://orcid.org/0000-0001-6682-1504) ([Florida Museum of Natural History](http://www.wikidata.org/entity/Q3074272))
: [Ramona L. Walls](https://orcid.org/0000-0001-8815-0078) ([University of Arizona](http://www.wikidata.org/entity/Q503419))
: [Walter Jetz](https://orcid.org/0000-0002-1971-7277) ([Yale University](http://www.wikidata.org/entity/Q49112))

Publisher
: Biodiversity Information Standards (TDWG)

Abstract
: The Humboldt Extension for Ecological Inventories provides a standardized vocabulary to report key information about biodiversity inventories, checklists and surveys, maximizing the usability and interoperability of these data. This vocabulary is employed along with the Darwin Core (DwC) terms, effectively broadening the scope of dwc:Event records by incorporating terms absent from the main DwC vocabulary. Terms included in the extension are defined such that they can accommodate hierarchical data structures allowing the representation of complex, highly nested survey designs, permitting the computation of relative abundances of species. This document lists all terms currently used in the vocabulary providing comments and examples of their usage along with ancillary documents that provide guidance on the use and interpretation of terms and the data structure needed to accommodate dwc:Event hierarchies frequently observed in ecological inventories.

Citation
: TDWG Humboldt Extension Task Group. 2024. Humboldt Extension Vocabulary List of Terms. Biodiversity Information Standards (TDWG). <http://rs.tdwg.org/dwc/doc/eco/2024-03-26>

### Taxon Completeness Reported Controlled Vocabulary List of Terms

Title
: Taxon Completeness Reported Controlled Vocabulary List of Terms

Permanent IRI
: <http://rs.tdwg.org/dwc/doc/tcr/>

Created
: 2024-02-28

Last modified
: 2024-02-28

Contributors
: [Yanina V. Sica](https://orcid.org/0000-0002-1720-0127) ([Yale University](http://www.wikidata.org/entity/Q49112))
: [Wesley M. Hochachka](https://orcid.org/0000-0002-0595-7827) ([Cornell Lab of Ornithology](http://www.wikidata.org/entity/Q2997535))
: [Steven J. Baskauf](https://orcid.org/0000-0003-4365-3135) ([Vanderbilt University Libraries](http://www.wikidata.org/entity/Q16849893))

Publisher
: Biodiversity Information Standards (TDWG)

Abstract
: The Humboldt Extension for Ecological Inventories mints the term `taxonCompletenessReported` to alert users that the inventory was conducted in such a way that all of the target taxa should have been detectable if they were present during the dwc:Event. This vocabulary provides terms that should be used as values for `eco:taxonCompletenessReported` and `ecoiri:taxonCompletenessReported`.

Citation
: TDWG Humboldt Extension Task Group. 2024. Taxon Completeness Reported Controlled Vocabulary List of Terms. Biodiversity Information Standards (TDWG). <http://rs.tdwg.org/dwc/doc/tcr/2024-02-28>
