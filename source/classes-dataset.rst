Dataset
===============================

The properties and their acceptable values are outlined below:

.. list-table::
    :widths: 20 8 8 16 48
    :header-rows: 1

    * - Property
      - Man.
      - Card.
      - URI
      - Value
    * - identifier
      - man
      - 1..1
      - dct:identifier
      - xsd:anyURI
    * - title
      - man
      - 1..1
      - dct:title
      - xml:string
    * - description
      - man
      - 1..1
      - dct:description
      - xml:string
    * - keyword
      - rec
      - 0..n
      - dcat:keyword
      - xml:string
    * - metadataLanguage
      - man
      - 1..1
      - dct:language
      - donl:language
    * - language
      - man
      - 1..n
      - dct:language
      - donl:language
    * - theme
      - man
      - 1..n
      - dcat:theme
      - overheid:taxonomiebeleidsagenda
    * - modificationDate
      - man
      - 1..1
      - dct:modified
      - xsd:date (ISO 8601)
    * - authority
      - man
      - 1..1
      - overheid:authority
      - donl:authority
    * - publisher
      - man
      - 1..1
      - dct:publisher
      - donl:authority
    * - contactPoint
      - man
      - 1..1
      - dcat:contactPoint
      - vcard:Kind
    * - accessRights
      - rec
      - 0..1
      - dct:accessRights
      - overheid:openbaarheidsniveau
    * - datasetStatus
      - rec
      - 0..1
      - adms:status
      - overheid:datasetStatus
    * - landingPage
      - rec
      - 0..1
      - dcat:landingPage
      - xsd:anyURI
    * - spatial
      - rec
      - 0..n
      - dct:spatial
      - overheid:spatial
    * - temporal
      - rec
      - 0..1
      - dct:temporal
      - class **Period**
    * - conformsTo
      - rec
      - 0..n
      - dct:conformsTo
      - xsd:anyURI
    * - alternativeIdentifier
      - rec
      - 0..n
      - adms:identifier
      - xsd:anyURI
    * - relatedResource
      - rec
      - 0..n
      - dct:relation
      - xsd:anyURI
    * - source
      - rec
      - 0..n
      - dct:source
      - xsd:anyURI
    * - hasVersion
      - rec
      - 0..n
      - dct:hasVersion
      - xsd:anyURI
    * - isVersionOf
      - rec
      - 0..n
      - dct:isVersionOf
      - xsd:anyURI
    * - releaseDate
      - rec
      - 0..1
      - dct:issued
      - xsd:date (ISO 8601)
    * - version
      - rec
      - 0..1
      - owl:versionInfo
      - xml:string
    * - versionNotes
      - rec
      - 0..n
      - adms:versionNotes
      - xml:string
    * - legalFoundation
      - rec
      - 0..1
      - overheid:grondslag
      - class **LegalFoundation**
    * - datePlanned
      - opt
      - 0..1
      - skos:concept
      - xsd:date (ISO 8601)
    * - documentation
      - opt
      - 0..n
      - foaf:page
      - xsd:anyURI
    * - frequency
      - opt
      - 0..1
      - dct:accrualPeriodicity
      - overheid:frequency
    * - provenance
      - opt
      - 0..n
      - dct:provenance
      - xsd:anyURI
    * - sample
      - opt
      - 0..n
      - adms:sample
      - xsd:anyURI
    * - highValue
      - rec
      - 0..1
      - skos:concept
      - xsd:boolean
    * - basisRegister
      - rec
      - 0..1
      - skos:concept
      - xsd:boolean
    * - referentieData
      - rec
      - 0..1
      - skos:concept
      - xsd:boolean
    * - nationalCoverage
      - rec
      - 0..1
      - skos:concept
      - xsd:boolean
