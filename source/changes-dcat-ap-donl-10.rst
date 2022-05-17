Changes from the DCAT-AP-DONL 1.0 standard
==========================================

The changes from DCAT-AP-DONL 1.0 to DCAT-AP-DONL 1.1 are listed below.

.. note::
    DCAT-AP-DONL 1.0 was surprisingly poorly documented, given this, the list below may not be
    fully accurate. This changelog is based on **2015-04-17 Mapping Modellen_0.xslx**.

New properties
------------------------------------------

The following properties have been introduced

.. note::
    Most of the new properties are due to changes in the parent standard DCAT-AP-NL 1.1. These
    hanges will be listed, but not motivated.

Dataset:metadataLanguage
    This new mandatory property forces providers to clarify which language is used in the metadata
    of a Dataset.

Dataset:alternativeIdentifier
    From DCAT-AP-NL 1.1

Dataset:relatedResource
    From DCAT-AP-NL 1.1

Dataset:source
    From DCAT-AP-NL 1.1

Dataset:hasVersion
    From DCAT-AP-NL 1.1

Dataset:isVersionOf
    From DCAT-AP-NL 1.1

Dataset:documentation
    From DCAT-AP-NL 1.1

Dataset:provenance
    From DCAT-AP-NL 1.1

Dataset:sample
    From DCAT-AP-NL 1.1

Distribution:metadataLanguage
    This new mandatory property forces providers to clarify which language is used in the metadata
    of a Distribution.

Distribution:license
    From DCAT-AP-NL 1.1

Distribution:language
    From DCAT-AP-NL 1.1

Distribution:rights
    From DCAT-AP-NL 1.1

Distribution:linkedSchemas
    From DCAT-AP-NL 1.1

Distribution:checksum
    From DCAT-AP-NL 1.1

Distribution:documentation
    From DCAT-AP-NL 1.1

Changed properties
------------------------------------------

Changes have been made to every property of DCAT-AP-DONL 1.0. See the new class definitions for the
new version of the classes. The most important  conceptual changes are detailed and motivated below

Standardization of values
    In order to combat the fifty different spellings of 'Gemeente Nijmegen' and the likes, most
    property ranges have been limited to a certain list of acceptable values. These lists of values
    contain URIs that reference resources that have acceptable values for the given property, e.g.
    *http://standaarden.overheid.nl/owms/terms/Nijmegen_(gemeente)*.

Promoting linked data
    Most property ranges have been limited from *xml:string* to *xsd:anyURI*. Data.Overheid.nl
    prefers resolvable URIs from a linked data perspective.

Removed properties
------------------------------------------

The following properties have been removed

.. note::
    Most of the removed properties are due to changes in the parent standard DCAT-AP-NL 1.1. These
    changes will be listed, but not motivated.

Dataset:LODStars
    From DCAT-AP-NL 1.1

Dataset:doel
    From DCAT-AP-NL 1.1

Dataset:kwaliteit
    From DCAT-AP-NL 1.1
