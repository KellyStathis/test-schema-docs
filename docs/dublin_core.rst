DataCite to Dublin Core Mapping 4.4
========================================

Citation:
DataCite Metadata Working Group. (2021). DataCite to Dublin Core Mapping 4.4. DataCite e.V. https://doi.org/10.14454/qn00-qx85.

On the occasion of the release of `v4.4 of the DataCite Metadata Schema <https://schema.datacite.org/meta/kernel-4.4/doc/DataCite-MetadataKernel_v4.4.pdf>`_ the Metadata Working Group has updated the mapping to Dublin Core. This replaces the mapping in the Appendix of the `DataCite-MetadataKernel v2.1 <https://schema.datacite.org/archive/kernel-2.1/doc/DataCite-MetadataKernel_v2.1.pdf>`_.

The mapping can be used to convert records described following version 4.4 of the DataCite Metadata Schema into records that comply with the Dublin Core Metadata Initiative Schema.

Future developments
------------------------

The Metadata Working Group are in discussion with ongoing developments by a team at the National Library of Finland who have proposed a draft DC application profile called SRAP (Scholarly Resources Application Profile) “for expressing metadata about scholarly works such as dissertations and academic articles. Describing these documents using current DC Terms is not ideal because many relevant elements are missing”. This is an interesting development because they hope that a future version may focus on research datasets. Examples of proposed SRAP elements which are of value to DataCite include dcterms:affiliation; dcterms:grantNumber and using an id= or pid= for identifier or value URIs for elements such as dcterms:creator or dcterms:contributor.

.. list-table::
   :header-rows: 1
   :widths: auto

   * - ID
     - DataCite-Property
     - Dublin Core
   * - 1
     - Identifier
     - dcterms:identifier
   * - 1.a
     - identifierType
     - Not present in Dublin Core
   * - 2
     - Creator
     - dcterms:creator
   * - 2.1
     - creatorName
     - dcterms:creator
   * - 2.1.a
     - nameType
     - Not present in Dublin Core
   * - 2.2
     - givenName
     - Not present in Dublin Core
   * - 2.3
     - familyName
     - Not present in Dublin Core
   * - 2.4
     - nameIdentifier
     - dcterms:identifier
   * - 2.4.a
     - nameIdentifierScheme
     - Not present in Dublin Core
   * - 2.4.b
     - schemeURI
     - Not present in Dublin Core
   * - 2.5
     - Affiliation
     - dcterms:contributor
   * - 2.5.a
     - affiliationIdentifier
     - dcterms:identifier
   * - 2.5.b
     - affiliationIdentifierScheme
     - Not present in Dublin Core
   * - 2.5.c
     - SchemeURI
     - Not present in Dublin Core
   * - 3
     - Title
     - dcterms:title
   * - 3.a
     - titleType
     - dcterms:alternative
   * - 4
     - Publisher
     - dcterms:publisher
   * - 5
     - publicationYear
     - dcterms:issued
   * - 6
     - Subject
     - dcterms:subject
   * - 6.a
     - subjectScheme
     - Not present in Dublin Core
   * - 6.b
     - schemeURI
     - Not present in Dublin Core
   * - 6.c
     - valueURI
     - dcterms:subject
   * - 6.d
     - classificationCode
     - dcterms:subject
   * - 7
     - Contributor
     - dcterms:contributor
   * - 7.a
     - contributorType
     - Not present in Dublin Core
   * - 7.1
     - contributorName
     - dcterms:contributor
   * - 7.1.a
     - nameType
     - Not present in Dublin Core
   * - 7.2
     - givenName
     - Not present in Dublin Core
   * - 7.3
     - familyName
     - Not present in Dublin Core
   * - 7.4
     - nameIdentifier
     - dcterms:identifier
   * - 7.4.a
     - nameIdentifierScheme
     - Not present in Dublin Core
   * - 7.4.b
     - schemeURI
     - Not present in Dublin Core
   * - 7.5
     - Affiliation
     - dcterms:contributor
   * - 7.5.a
     - affiliationIdentifier
     - dcterms:identifier
   * - 7.5.b
     - affiliationIdentifierScheme
     - Not present in Dublin Core
   * - 7.5.c
     - SchemeURI
     - Not present in Dublin Core
   * - 8
     - Date
     - dcterms:date
   * - 8.a
     - dateType [i]_
     -
   * -
     - Accepted
     - dcterms:dateAccepted
   * -
     - Available
     - dcterms:available
   * -
     - Collected
     - dcterms:date
   * -
     - Copyrighted
     - dcterms:dateCopyrighted
   * -
     - Created
     - dcterms:created
   * -
     - Issued
     - dcterms:issue
   * -
     - Submitted
     - dcterms:dateSubmitte
   * -
     - Updated
     - dcterms:modified
   * - 8.a
     - dateType (for StartDate/EndDate)
     - dcterms:temporal
   * - 8.b
     - dateInformation
     - Not present in Dublin Core
   * - 9
     - Language
     - dcterms:language
   * - 10
     - resourceType
     - dcterms:type
   * - 10.a
     - resourceTypeGeneral
     - dcterms:type
   * - 11
     - alternateIdentifier
     - dcterms:identifier
   * - 11.a
     - alternateIdentifierType
     - Not present in Dublin Core
   * - 12
     - relatedIdentifier
     - dcterms:relation
   * - 12.a
     - relatedIdentifierType
     - Not present in Dublin Core
   * - 12.b
     - relationType [ii]_
     -
   * -
     - isReferencedBy
     - dcterms:isReferencedBy
   * -
     - references
     - dcterms:references
   * -
     - isVersionOf
     - dcterms:isVersionOf
   * -
     - hasVersion
     - dcterms:hasVersion
   * -
     - isVariantFormatOf
     - dcterms:isFormatOf
   * -
     - isPartOf
     - dcterms:isPartOf
   * -
     - hasPart
     - dcterms:hasPart
   * -
     - isObsoletedBy
     - dcterms:isReplacedBy
   * -
     - obsoletes
     - dcterms:replaces
   * -
     - isDerivedFrom
     - dcterms:source
   * -
     - *Other relation types*
     - dcterms:relation
   * - 12.c
     - relatedMetadataScheme
     - dcterms:relation
   * - 12.d
     - schemeURI
     - Not present in Dublin Core
   * - 12.e
     - schemeType
     - Not present in Dublin Core
   * - 12.f
     - resourceTypeGeneral
     - dcterms:relation
   * - 13
     - Size
     - dcterms:extent
   * - 14
     - Format
     - dcterms:format
   * - 15
     - Version
     - Not present in Dublin Core
   * - 16
     - Rights
     - dcterms:rights
   * - 16.a
     - rightsURI
     - dcterms:rights
   * - 16.b
     - rightsIdentifier
     - dcterms:rights
   * - 16.c
     - rightsIdentfierScheme
     - Not present in Dublin Core
   * - 16.c
     - schemeURI
     - Not present in Dublin Core
   * - 17
     - Description
     - dcterms:description
   * - 17.a
     - descriptionType
     - dcterms:description
   * -
     - Abstract
     - dcterms:abstrac
   * -
     - Methods
     - dcterms:description
   * -
     - TechnicalInformation
     - dcterms:description
   * -
     - TableOfContents
     - dcterms:tableOfContents
   * -
     - Other
     - dcterms:description
   * - 18
     - GeoLocation
     - dcterms:spatial
   * - 18.1
     - geoLocationPoint
     - dcterms:spatial
   * - 18.1.1
     - pointLongitude
     - dcterms:spatial
   * - 18.1.2
     - pointLatitude
     - dcterms:spatial
   * - 18.2
     - geoLocationBox
     - dcterms:spatial
   * - 18.2.1
     - westBoundLongitude
     - dcterms:spatial
   * - 18.2.2
     - eastBoundLongitude
     - dcterms:spatial
   * - 18.2.3
     - southBoundLatitude
     - dcterms:spatial
   * - 18.2.4
     - northBoundLatitude
     - dcterms:spatial
   * - 18.3
     - geoLocationPlace
     - dcterms:spatial
   * - 18.4
     - geoLocationPolygon
     - dcterms:spatial
   * - 18.4.1
     - polygonPoint
     - dcterms:spatial
   * - 18.4.1.1
     - pointLongitude
     - dcterms:spatial
   * - 18.4.1.2
     - pointLatitude
     - dcterms:spatial
   * - 18.4.2
     - inPolygonPoint
     - dcterms:spatial
   * - 18.4.2.1
     - pointLongitude
     - dcterms:spatial
   * - 18.4.2.2
     - pointLatitude
     - dcterms:spatial
   * - 19
     - fundingReference
     - dcterms:contributor
   * - 19.1
     - funderName
     - dcterms:contributor
   * - 19.2
     - funderIdentifier
     - dcterms:contributor
   * - 19.2.a
     - funderIdentifierType
     - Not present in Dublin Core
   * - 19.2.b
     - SchemeURI
     - Not present in Dublin Core
   * - 19.3
     - awardNumber
     - dcterms:identifier
   * - 19.3.a
     - awardURI
     - dcterms:identifier
   * - 19.4
     - awardTitle
     - dcterms:description

   * - 20
     - RelatedItem
     - | dcterms:relation
       | *For the details of the related ítem i.e. title etc., use dcterms:bibliographicCitation. Concatenate the content according to any preferred Citation format*
   * - 20.a
     - relationType [ii]_
     -
   * -
     - isReferencedBy
     - dcterms:isReferencedBy
   * -
     - references
     - dcterms:references
   * -
     - isVersionOf
     - dcterms:isVersionOf
   * -
     - hasVersion
     - dcterms:hasVersion
   * -
     - isVariantFormatOf
     - dcterms:isFormatOf
   * -
     - isPartOf
     - dcterms:isPartOf
   * -
     - hasPart
     - dcterms:hasPart
   * -
     - isObsoletedBy
     - dcterms:isReplacedBy
   * -
     - obsoletes
     - dcterms:replaces
   * -
     - isDerivedFrom
     - dcterms:source
   * -
     - *Other relation types*
     - dcterms:relation
   * - 20.b
     - relatedItemType
     - dcterms:relation
   * - 20.c
     - relatedItemIdentifier
     - dcterms:relation
   * - 20.d
     - relatedItemIdentifierType
     - Not present in Dublin Core
   * - 20.1
     - Title
     - dcterms:bibliographicCitation
   * - 20.1.a
     - Type
     - dcterms:bibliographicCitation
   * - 20.2
     - Volume
     - dcterms:bibliographicCitation
   * - 20.3
     - Issue
     - dcterms:bibliographicCitation
   * - 20.4
     - Number
     - dcterms:bibliographicCitation
   * - 20.4.a
     - Type
     - dcterms:bibliographicCitation
   * - 20.5
     - firstPage
     - dcterms:bibliographicCitation
   * - 20.6
     - lastPage
     - dcterms:bibliographicCitation
   * - 20.7
     - Year
     - dcterms:bibliographicCitation
   * - 20.8
     - Month
     - dcterms:bibliographicCitation
   * - 20.9
     - Day
     - dcterms:bibliographicCitation
   * - 20.10
     - Edition
     - dcterms:bibliographicCitation
   * - 20.11
     - Creator
     - dcterms:bibliographicCitation
   * - 20.11.a
     - creatorName
     - dcterms:bibliographicCitation
   * - 20.11.b
     - nameIdentifier
     - dcterms:bibliographicCitation
   * - 20.12
     - Contributor
     - dcterms:bibliographicCitation
   * - 20.12.a
     - contributorName
     - dcterms:bibliographicCitation
   * - 20.12.b
     - nameIdentifier
     - dcterms:bibliographicCitation

.. rubric:: Footnotes

.. [i] dateType is mandatory in DataCite if Date is used. Controlled List Values: Accepted, Available, Copyrighted, Collected, Created, Issued, Submitted, Updated.

.. [ii] relationType is mandatory in DataCite if RelatedIdentifier is used. Controlled List Values: IsCitedBy, Cites, IsSupplementTo, IsSupplementedBy, IsContinuedBy, Continues, IsDescribedBy, Describes, HasMetadata, IsMetadataFor, HasVersion, IsVersionOf, IsNewVersionOf, IsPreviousVersionOf, IsPartOf, HasPart, IsPublishedIn, IsReferencedBy, References, IsDocumentedBy, Documents, IsCompiledBy, Compiles, IsVariantFormOf, IsOriginalFormOf, IsIdenticalTo, IsReviewedBy, Reviews, IsDerivedFrom, IsSourceOf, IsRequiredBy, Requires, IsObsoletedBy, Obsoletes.
