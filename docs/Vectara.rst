
Reference of ``vectara``
==================================

.. include::
   functions.rst

The background classes
----------------------

Here are the classes used by the `Vectara` class.

.. automodule:: vectara
.. autoclass:: Filter

The ``Vectara`` class
--------------------

The ``Vectara`` class is the main offering of the ``vectara`` package. It allows you to establish a connection to the Vectara service, upload data, and make queries.

.. automodule:: vectara
.. autoclass:: Vectara
   :members: __init__, create_corpus, reset_corpus, list_documents, delete_document, list_jobs, upload, set_corpus_filters, query, create_document_from_sections, create_document_from_chunks
   

