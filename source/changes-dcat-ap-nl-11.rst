Changes from the DCAT-AP-NL 1.1 standard
==========================================

The changes from `DCAT-AP-NL 1.1`_ to DCAT-AP-DONL 1.1 are listed below.

.. _DCAT-AP-NL 1.1: http://dcat-ap-nl.nl

New properties
------------------------------------------

The following properties have been introduced

Dataset:datasetStatus
    This recommended property defines in which part of a lifecycle a dataset exists. A dataset can
    be available, planned unavailable or being researched. Use Dataset:datePlanned to indicate when
    a dataset is expected to receive the datasetStatus available.

Dataset:datePlanned
    This optional property defines the planned date at which this dataset becomes available. It is
    closely related to the datasetStatus planned, unavailable and being researched.

Dataset:license
    This new, mandatory, property was introduced for the Dataset class. It allows a license to
    apply to a dataset, rather than a Distribution, which already had the license property.

Dataset:metadataLanguage
    This new mandatory property forces providers to clarify which language is used in the metadata
    of a Dataset.

Distribution:metadataLanguage
    This new mandatory property forces providers to clarify which language is used in the metadata
    of a Distribution.

Changed properties
------------------------------------------

The following properties have been modified

Dataset:title
    The cardinality has been changed from *1..n* to *1..1*. Data.Overheid.nl demands that metadata
    is provided in only *one* language, therefore there is no longer any need to support multiple
    titles for one dataset.

Dataset:description
    The cardinality has been changed from *1..n* to *1..1*. Data.Overheid.nl demands that metadata
    is provided in only *one* language, therefore there is no longer any need to support multiple
    descriptions for one dataset.

Dataset:theme
    This property was changed from *Recommended* to *Mandatory*. Data.Overheid.nl requires at least
    one theme to properly categorize datasets. Because of this, its cardinality is changed from
    *0..n* to *1..n*.

Dataset:authority
    This property was changed from *Recommended* to *Mandatory*. It must always be clear who owns
    the dataset, therefore this property needs to be mandatory. Because of this, its cardinality is
    changed from *0..1* to *1..1*.

Dataset:publisher
    This property was changed from *Recommended* to *Mandatory*. It must always be clear who
    published the dataset, therefore this property needs to be mandatory. Because of this, its
    cardinality is changed from *0..1* to *1..1*.

Dataset:contactPoint
    This property was changed from *Recommended* to *Mandatory*. A published dataset needs to have
    a contactPoint so that questions and/or comments regarding a dataset have a place to go.
    Because of this, its cardinality is changed from *0..n* to *1..1*.

Dataset:conformsTo
    This property was changed from *Optional* to *Recommended*. Data.Overheid.nl wants as much
    metadata about a dataset as possible. This is purely a semantic change to inspire providers to
    provide more metadata. Furthermore, its range was narrowed to *xsd:anyURI*. Data.Overheid.nl
    prefers resolvable URIs from a linked data perspective.

Dataset:alternativeIdentifier
    This property was changed from *Optional* to *Recommended*. The alternativeIdentifier is
    important in the quest to minimise duplicate datasets. As such this property now has a higher
    classification to signify this.

Dataset:relatedResource
    This property was changed from *Optional* to *Recommended*. Data.Overheid.nl wants as much
    metadata about a dataset as possible. This is purely a semantic change to inspire providers to
    provide more metadata. Furthermore, its range was narrowed to *xsd:anyURI*. Data.Overheid.nl
    prefers resolvable URIs from a linked data perspective.

Dataset:source
    This property was changed from *Optional* to *Recommended*. Data.Overheid.nl wants as much
    metadata about a dataset as possible. This is purely a semantic change to inspire providers to
    provide more metadata. Furthermore, its range was narrowed to *xsd:anyURI*. Data.Overheid.nl
    prefers resolvable URIs from a linked data perspective.

Dataset:hasVersion
    This property was changed from *Optional* to *Recommended*. Data.Overheid.nl wants as much
    metadata about a dataset as possible. This is purely a semantic change to inspire providers to
    provide more metadata. Furthermore, its range was narrowed to *xsd:anyURI*. Data.Overheid.nl
    prefers resolvable URIs from a linked data perspective.

Dataset:isVersionOf
    This property was changed from *Optional* to *Recommended*. Data.Overheid.nl wants as much
    metadata about a dataset as possible. This is purely a semantic change to inspire providers to
    provide more metadata. Furthermore, its range was narrowed to *xsd:anyURI*. Data.Overheid.nl
    prefers resolvable URIs from a linked data perspective.

Dataset:releaseDate
    This property was changed from *Optional* to *Recommended*. Data.Overheid.nl wants as much
    metadata about a dataset as possible. This is purely a semantic change to inspire providers to
    provide more metadata.

Dataset:version
    This property was changed from *Optional* to *Recommended*. Data.Overheid.nl wants as much
    metadata about a dataset as possible. This is purely a semantic change to inspire providers to
    provide more metadata.

Dataset:version_notes
    This property was changed from *Optional* to *Recommended*. Data.Overheid.nl wants as much
    metadata about a dataset as possible. This is purely a semantic change to inspire providers to
    provide more metadata.

Distribution:license
    This property was changed from *Recommended* to *Mandatory*. Data.Overheid.nl requires that all
    distributions have a license property. It must always be clear what license applies to a
    distribution. Because of this, its cardinality is changed from *0..1* to *1..1*.

Distribution:title
    The cardinality has been changed from *1..n* to *1..1*. Data.Overheid.nl demands that metadata
    is provided in only *one* language, therefore there is no longer any need to support multiple
    titles for one distribution.

Distribution:description
    The cardinality has been changed from *1..n* to *1..1*. Data.Overheid.nl demands that metadata
    is provided in only *one* language, therefore there is no longer any need to support multiple
    titles for one distribution.

Distribution:format
    This property was changed from *Recommended* to *Mandatory*. A Distribution always has a format,
    as such, it should be provided. Because of this, its cardinality is changed from *0..1* to
    *1..1*.

Distribution:byteSize
    This property was changed from *Optional* to *Recommended*. Data.Overheid.nl wants as much
    metadata about a distributions as possible. This is purely a semantic change to inspire
    providers to provide more metadata.

Distribution:downloadURL
    This property was changed from *Optional* to *Recommended*. Data.Overheid.nl wants as much
    metadata about a distributions as possible. This is purely a semantic change to inspire
    providers to provide more metadata.

Distribution:mediaType
    This property was changed from *Optional* to *Recommended*. Data.Overheid.nl wants as much
    metadata about a distributions as possible. This is purely a semantic change to inspire
    providers to provide more metadata.

Distribution:releaseDate
    This property was changed from *Optional* to *Recommended*. Data.Overheid.nl wants as much
    metadata about a distributions as possible. This is purely a semantic change to inspire
    providers to provide more metadata.

Distribution:rights
    This property was changed from *optional* to *Mandatory*. Rights always apply to Distributions,
    therefore providers must dictate which rights apply to the Distribution. Because of this, its
    cardinality is changed from *0..1* to *1..1*.

Distribution:status
    This property was changed from *Optional* to *Recommended*. Data.Overheid.nl wants as much
    metadata about a distributions as possible. This is purely a semantic change to inspire
    providers to provide more metadata.

Distribution:modificationDate
    This property was changed from *Optional* to *Recommended*. Data.Overheid.nl wants as much
    metadata about a distributions as possible. This is purely a semantic change to inspire
    providers to provide more metadata.

Distribution:linkedSchemas
    This property was changed from *Optional* to *Recommended*. Data.Overheid.nl wants as much
    metadata about a distributions as possible. Furthermore its range has been narrowed to only
    allow valid URIs. Data.Overheid.nl prefers resolvable URIs from a linked data perspective.

Removed properties
------------------------------------------

The following properties have been removed

None
    No properties have been removed that were part of the DCAT-AP-NL 1.1 standard.
