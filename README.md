# json-buffer

This is an intermediate repository of JSON data records in [biotoolsSchema format](https://github.com/bio-tools/biotoolsSchema), that are generated from __multiple sources of tools descriptions__. Each of the sources should use its __own branch(!)__ of these JSON data records, allowing eventual __merge__ of records that are described in multiple sources. The non-conflicting and the merged records should then be uploaded to [Bio.Tools](http://bio.tools).

# Current sources of tools descriptions imported into json-buffer:

 * __Debian Med__. Further info: Info about [EDAM annotations in Debian Med](); Script exporting [EDAM annotations from the Debian DB](); Script creating [JSON records from Debian packages]() that are committed here into json-buff.
 
 
 # Expected further sources of tools descriptions to be imported into json-buffer:
 
  * __Bio.Tools (*NB.* that this is a special case: ONLY the records already present in json-buff should have updates from *bio.tools* committed to a corresponding *branch*)__
  * __SEQwiki__
  * _etc._ ...
