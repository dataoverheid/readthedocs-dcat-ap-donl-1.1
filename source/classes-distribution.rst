Distribution
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
    * - accessURL
      - man
      - 1..1
      - dcat:accessURL
      - xsd:anyURI
    * - license
      - man
      - 1..1
      - dct:license
      - overheid:license
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
    * - language
      - man
      - 1..n
      - dct:language
      - donl:language
    * - format
      - man
      - 1..1
      - dct:format
      - mdr:filetype
    * - rights
      - rec
      - 0..1
      - dct:rights
      - xml:string
    * - status
      - rec
      - 0..1
      - adms:status
      - adms:distributiestatus
    * - releaseDate
      - rec
      - 0..1
      - dct:issued
      - xsd:date (ISO 8601)
    * - modificationDate
      - rec
      - 0..1
      - dct:modified
      - xsd:date (ISO 8601)
    * - byteSize
      - rec
      - 0..1
      - dcat:byteSize
      - xml:number
    * - downloadURL
      - rec
      - 0..n
      - dcat:downloadURL
      - xsd:anyURI
    * - mediaType
      - rec
      - 0..1
      - dcat:mediaType
      - iana:mediatype
    * - linkedSchemas
      - rec
      - 0..n
      - dct:conformsTo
      - xsd:anyURI
    * - checksum
      - opt
      - 0..1
      - spdc:checksum
      - class **Checksum**
    * - documentation
      - opt
      - 0..n
      - foaf:page
      - xsd:anyURI
