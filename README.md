# json-buffer

This is an intermediate repository of JSON data records in [biotoolsSchema format](https://github.com/bio-tools/biotoolsSchema), that are generated from __multiple sources of tools descriptions__. Each of the sources should use its __own branch__(!) of these JSON data records, allowing eventual __merging__ of records that are described in multiple sources. The non-conflicting and the merged records should then be uploaded to [Bio.Tools](http://bio.tools).

# Current sources of tools descriptions imported into json-buffer:

 * __Debian Med__. Further info: Info about [EDAM annotations in Debian Med](https://wiki.debian.org/debian/upstream/edam); Script exporting [EDAM annotations from the Debian DB](https://github.com/bio-tools/biotoolsConnect/blob/master/DebianMed/edam.sh); Script creating [JSON records from Debian packages](http://anonscm.debian.org/viewvc/debian-med/trunk/community/edam/registry-tool.py?view=markup) that are committed here into json-buff. (And a [temporary doc](https://docs.google.com/document/d/1H44HxQik2RnxWzBui3GuYI9pAMfX5tNDBiwRa5g0WXg) with implementation thoughts)
 
 
# Expected further sources of tools descriptions to be imported into json-buffer:
 
  * __Bio.Tools__ (__*NB.* that this is a special case:__ ONLY the records already present in json-buff should have updates from *bio.tools* committed to a corresponding *branch*)
  * __SEQwiki__
  * _etc._ ...
