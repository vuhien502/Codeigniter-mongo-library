CIMongo - MongoDB Library for Codeigniter 2
=======

This library help you to use perform MongoDB based queries just like active record in CodeIgniter.

This library support
* Write Concern and journal
* Read Preference
* Aggregation Framework



#Methods

##Insert Method
* `insert` Insert a new document into a collection
* `batch_insert` Insert multiple new documents into a collection

##Select Method
* `select` Get select fields from returned documents
* `where` OR `get_where` Where section of the query
* `where_in` Where something is in an array of something
* `where_in_all` Where something is in all of an array of * something
* `where_not_in` Where something is not in array of something
* `where_or` Where something is based on or
* `where_gt` Where something is greater than something
* `where_gte` Where something is greater than or equal to something
* `where_lt` Where something is less than something
* `where_lte` Where something is less than or equal to something
* `where_between` Where something is in between to something
* `where_between_ne` Where something is in between and but not equal to something
* `where_ne` Where something is not equal to something
* `like` Where something is search by like query
* `order_by` Order the results
* `limit` OR `offset` Limit the number of returned results
* `count` Document Count based on where query

##Update Method
* `set` Sets a field to a value
* `unset_field` Unsets a field
* `addtoset` Adds a value to an array if doesn't exist
* `push` Pushes a value into an array field
* `pop` Pops a value from an array field
* `pull` Removes an array by the value of a field
* `rename_field` Rename a field
* `inc` Increments the value of a field
* `mul` Multiple the value of a field
* `update` Update a single document in a collection
* `update_all` Update all documents in a collection

##Delete Method
* `delete` Delete a single document in a collection
* `delete_all` Delete all documents in a collection

##Aggregation Method
* `aggregate` Perform aggregation query on document

##Index Method
* `add_index` Create a new index on collection
* `remove_index` Remove index from collection
* `list_indexes` Show all index created on collections

##DB Method
* `switch_db` Switch to a different database
* `drop_db` Drops a database
* `drop_collection` Drops a collection

##Extra Helper
* `date` Create or convert date to MongoDB based Date
