Classes
========================================

DCAT-AP-DONL 1.1 is based on the DCAT-AP-NL 1.1 standard. As such it inherits all the specifications
from said standard. DCAT-AP-DONL 1.1 does modify the classes 'Dataset' and 'Distribution'. The
specifications of the DCAT-AP-DONL versions of these classes will now be handled. Given the fact
that DCAT-AP-DONL must remain compatible with DCAT-AP-NL and by extension DCAT-AP-EU, these changes
will not be groundbreaking.

In the schemas of the classes a column exists named 'Man.'. This details whether a property is
Mandatory (man), Recommended (rec) or Optional (opt).

There are direct references in the schemas below to the classes Period, LegalFoundation and Checksum
, for the sake of clarity these are included in this documentation, however, these are direct copies
of their counterparts in the DCAT-AP-NL standard.

.. toctree::
   :maxdepth: 2
   :caption: Documented classes

   classes-dataset
   classes-distribution
   classes-period
   classes-legalfoundation
   classes-checksum

All other classes of the DCAT-AP-DONL standard are fully inherited from the DCAT-AP-NL standard.
