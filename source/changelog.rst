Changelog
========================================

The following changes have been applied over time to the standard and/or its documentation.

03/07/2019
----------------------------------------
- Introduced a new property for the :code:`Dataset` class: :code:`nationalCoverage`. This property is an optional boolean. When this property is not present in a dataset it is considered 'false'.

12/11/2018
----------------------------------------

- The property :code:`keyword` was incorrectly listed as :code:`mandatory`. It has been updated to accurately describe its :code:`recommended` status

05/11/2018
----------------------------------------

- The :code:`downloadURL` property of a :code:`Distribution` was incorrectly listed as having a :code:`1..n` cardinality, this has been corrected to :code:`0..n` to accurately reflect its recommended state.
- Further clarified the :code:`Period` class. this class consists of only recommended properties but has additional rules which state that at least one of these properties should be present. An empty Period class is considered invalid.
- Introduced three new properties for the :code:`Dataset` class, :code:`highValue`, :code:`basisRegister` and :code:`referentieData`. These new properties are optional boolean properties. When these properties are not present in a dataset they are considered 'false'.
- The property :code:`rights` of :code:`Distribution` was incorrectly listed as mandatory, this property is recommended. Its state and cardinality have been corrected.
