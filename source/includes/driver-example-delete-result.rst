.. tabs::

   tabs:
     - id: shell
       content: |
         The method returns a document with the status of the operation. For
         more information and examples, see
         :method:`~db.collection.deleteMany()`.

     - id: python
       content: |
         The :py:meth:`~pymongo.collection.Collection.delete_many`
         method returns an instance of
         :py:class:`pymongo.results.DeleteResult` with the status of the
         operation.

     - id: java-sync
       content: |
         The com.mongodb.client.MongoCollection.deleteMany_
         method returns an instance of
         com.mongodb.client.result.DeleteResult_
         with the status of the
         operation.

     - id: nodejs
       content: |
         :node-api:`deleteMany() <Collection.html#deleteMany>` returns a
         promise that provides a ``result``. The ``result.deletedCount``
         property contains the number of documents that matched the
         filter.

     - id: php
       content: |
         Upon successful execution, the
         :phpmethod:`deleteMany() <phpmethod.MongoDB\\Collection::deleteMany>`
         method returns an instance of
         :phpclass:`MongoDB\\DeleteResult <phpclass.MongoDB\\DeleteResult>`
         whose :phpmethod:`getDeletedCount()<phpmethod.MongoDB\\DeleteResult::getDeletedCount>`
         method returns the number of documents that matched the filter.

     - id: perl
       content: |
         Upon successful execution, the
         :perl-api:`delete_many()<Collection#delete_many>` method
         returns an instance of
         :perl-api:`MongoDB::DeleteResult<DeleteResult>` whose
         ``deleted_count`` attribute contains the number of documents
         that matched the filter.
