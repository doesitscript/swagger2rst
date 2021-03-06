API title 0.0.1
===============

.. toctree::
    :maxdepth: 3





Base URL
~~~~~~~~

http:///



QUESTIONNAIRE
~~~~~~~~~~~~~



GET ``/api/v1/questionnaire/get/``
----------------------------------


Summary
+++++++

Return Recording Questionnaire



Request
+++++++



Responses
+++++++++

**200**
^^^^^^^

Redefined update method

 
.. _i_402f8658cb1ddecd701314b28554a7cc:

**Response Schema:**


:ref:`RecordingSerializer <d_e408f13b0c465e8b895d79e7a4a4971c>` extended :ref:`inline <i_a2f119cfb8a0ff58060c0da8d89f9a51>`


.. _i_a2f119cfb8a0ff58060c0da8d89f9a51:

**Inline schema:**


.. csv-table::
    :delim: |
    :header: "Name", "Required", "Type", "Format", "Properties", "Description"
    :widths: 20, 10, 15, 15, 30, 25

        favorites1 | Yes | array of string |  |  | custom answer Description 
        guid1 | Yes | string |  |  |  
        pdf_url | No | string |  |  |  
        phrase_id | Yes | integer |  |  |  
        record_id | Yes | integer |  |  |  
        recording | Yes | string |  |  |  




**Example:**

.. code-block:: javascript

    {
        "favorites1": [
            "value", 
            "value", 
            "value"
        ], 
        "guid1": "value", 
        "pdf_url": "value", 
        "phrase_id": 5, 
        "record_id": 5, 
        "recording": "value"
    }

**201**
^^^^^^^

Redefined create method

 
.. _i_5989b460297e96c997e81f0bd37f97af:

**Response Schema:**


:ref:`AnswerModel <d_74b96a00174cffc078641e1f8c9fbb40>` extended :ref:`inline <i_a2f119cfb8a0ff58060c0da8d89f9a51>`

.. _i_a2f119cfb8a0ff58060c0da8d89f9a51:

**Inline schema:**


.. csv-table::
    :delim: |
    :header: "Name", "Required", "Type", "Format", "Properties", "Description"
    :widths: 20, 10, 15, 15, 30, 25

        favorites1 | Yes | array of string |  |  | custom answer Description 
        guid1 | Yes | string |  |  |  
        pdf_url | No | string |  |  |  
        phrase_id | Yes | integer |  |  |  
        record_id | Yes | integer |  |  |  
        recording | Yes | string |  |  |  




**Example:**

.. code-block:: javascript

    {
        "favorites1": [
            "value", 
            "value", 
            "value"
        ], 
        "guid1": "value", 
        "pdf_url": "value", 
        "phrase_id": 5, 
        "record_id": 5, 
        "recording": "value"
    }

  

  
  
Data Structures
~~~~~~~~~~~~~~~


.. _d_74b96a00174cffc078641e1f8c9fbb40:

AnswerModel Model Structure
---------------------------


.. csv-table::
    :delim: |
    :header: "Name", "Required", "Type", "Format", "Properties", "Description"
    :widths: 20, 10, 15, 15, 30, 25

        favorites1 | Yes | array of string |  |  | custom answer Description 
        guid1 | Yes | string |  |  |  




.. _d_e408f13b0c465e8b895d79e7a4a4971c:

RecordingSerializer Model Structure
-----------------------------------


.. csv-table::
    :delim: |
    :header: "Name", "Required", "Type", "Format", "Properties", "Description"
    :widths: 20, 10, 15, 15, 30, 25

        phrase_id | Yes | integer |  |  |  
        record_id | Yes | integer |  |  |  
        recording | Yes | string |  |  |  

