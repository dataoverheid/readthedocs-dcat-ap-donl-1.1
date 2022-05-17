Valuelists
===============================

The DCAT-AP-DONL 1.1 standard uses lists of acceptable values in order to standardize the values of
properties wherever possible. These lists are mostly inherited from the parent standard
`DCAT-AP-NL 1.1`_. These lists are shown below.

These valuelists are published on `waardelijsten.dcat-ap-donl.nl`_.

.. list-table::
    :widths: 32 68
    :header-rows: 1

    * - Name
      - Location
    * - adms:changetype
      - http://waardelijsten.dcat-ap-donl.nl/adms_changetype.json
    * - adms:distributiestatus
      - http://waardelijsten.dcat-ap-donl.nl/adms_distributiestatus.json
    * - donl:catalogs
      - http://waardelijsten.dcat-ap-donl.nl/donl_catalogs.json
    * - donl:language
      - http://waardelijsten.dcat-ap-donl.nl/donl_language.json
    * - donl:organization
      - http://waardelijsten.dcat-ap-donl.nl/donl_organization.json
    * - iana:mediatypes
      - http://waardelijsten.dcat-ap-donl.nl/iana_mediatypes.json
    * - mdr:filetype_nal
      - http://waardelijsten.dcat-ap-donl.nl/mdr_filetype_nal.json
    * - overheid:dataset_status
      - http://waardelijsten.dcat-ap-donl.nl/overheid_dataset_status.json
    * - overheid:frequency
      - http://waardelijsten.dcat-ap-donl.nl/overheid_frequency.json
    * - overheid:license
      - http://waardelijsten.dcat-ap-donl.nl/overheid_license.json
    * - overheid:openbaarheidsniveau
      - http://waardelijsten.dcat-ap-donl.nl/overheid_openbaarheidsniveau.json
    * - overheid:spatial_gemeente
      - http://waardelijsten.dcat-ap-donl.nl/overheid_spatial_gemeente.json
    * - overheid:spatial_koninkrijksdeel
      - http://waardelijsten.dcat-ap-donl.nl/overheid_spatial_koninkrijksdeel.json
    * - overheid:spatial_provincie
      - http://waardelijsten.dcat-ap-donl.nl/overheid_spatial_provincie.json
    * - overheid:spatial_scheme
      - http://waardelijsten.dcat-ap-donl.nl/overheid_spatial_scheme.json
    * - overheid:spatial_waterschap
      - http://waardelijsten.dcat-ap-donl.nl/overheid_spatial_waterschap.json
    * - overheid:taxonomiebeleidsagenda
      - http://waardelijsten.dcat-ap-donl.nl/overheid_taxonomiebeleidsagenda.json

DCAT-AP-DONL 1.1 maintains its own valuelists rather than simply using the DCAT-AP-NL valuelists.
The primary motivater behind this decision is that DCAT-AP-DONL may elect **not** to support certain
values of the DCAT-AP-NL valuelists. In order to support this feature, DCAT-AP-DONL has to maintain
its own valuelists. An example of such a usecase is where DCAT-AP-DONL may decide not to support a
certain license that DCAT-AP-NL supports.

.. _DCAT-AP-NL 1.1: https://dcat-ap-nl.nl
.. _waardelijsten.dcat-ap-donl.nl: http://waardelijsten.dcat-ap-donl.nl
