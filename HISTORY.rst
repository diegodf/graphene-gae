.. :changelog:

History
-------

0.1.4 (TBD)
---------------------
* NdbConnectionField added arguments that can be used in quert:
    * keys_only - to execute a keys only query
    * batch_size - to control the NDB query iteration batch size
    * page_size - control the page sizes when paginating connection results
* Added support for LocalStructuredProperty.
    * Given a property `ndb.LocalStructuredType(Something)` it will automatically
      map to a Field(SomethingType) - SomethingType has to be part of the schema.
    * Support for `repeated` and `required` propeties.

0.1.3 (2016-05-27)
---------------------
* Added `graphene_gae.webapp2.GraphQLHandler` - a basic HTTP Handler to process GraphQL requests


0.1.1 (2016-05-25)
---------------------

* Updated graphene dependency to latest 0.10.1 version.
    * NdbConnection.from_list now gets context as parameter


0.1.0 (2016-05-11)
---------------------

* First release on PyPI.
