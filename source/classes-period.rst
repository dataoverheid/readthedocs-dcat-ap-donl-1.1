Period
=====================================

The properties and their acceptable values are outlined below:

.. list-table::
    :widths: 20 8 8 16 48
    :header-rows: 1

    * - Property
      - Man.
      - Card.
      - URI
      - Value
    * - label
      - rec
      - 0..1
      - skos:concept
      - xml:string
    * - startDate
      - rec
      - 0..1
      - schema:startDate
      - xsd:date (ISO 8601)
    * - endDate
      - rec
      - 0..1
      - schema:endDate
      - xsd:date (ISO 8601)

As stated, the :code:`Period` class consists of only recommended properties. However, when providing a Period for your dataset atleast `one` of these recommended properties must be provided. An empty :code:`Period` class is considered invalid.