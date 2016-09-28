#  Document Datastores

note:
- Considered to be a subclass of key-value
- That means:
 - Records do not need to have a uniform structure, i.e. different records may have different columns.
 - The types of the values ​​of individual columns can be different for each record.
 - Columns can have more than one value (arrays).
 - Records can have a nested structure.
- Document stores often use internal notations, which can be processed directly in applications, mostly JSON. JSON documents of course can also be stored as pure text in key-value stores or relational database systems. That would, however, require client-side processing of the structures, which has the disadvantage that the features offered by document stores (such as secondary indexes) are not available.
