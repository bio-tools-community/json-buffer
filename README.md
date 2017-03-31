# json-buffer

This is an intermediate repository of JSON data records in [biotoolsSchema format](https://github.com/bio-tools/biotoolsSchema) (see also [diagram](https://raw.githubusercontent.com/bio-tools/biotoolsSchema/master/versions/biotools-2.0.0/docs/biotools-2.0.0.png)), that are generated from __multiple sources of tool__(s) __descriptions__. Each of the sources should use its __own branch__(!) of these JSON data records, allowing eventual __merging__ of records that are described in multiple sources. The non-conflicting and the merged records should then be uploaded to [Bio.Tools](http://bio.tools).

## Current sources of tool descriptions imported into json-buffer:

 * __Debian Med__
 
 Further info:
  * Info about [EDAM annotations in Debian Med](https://wiki.debian.org/debian/upstream/edam)
  * Script exporting [EDAM annotations from the Debian DB](https://github.com/bio-tools/biotoolsConnect/blob/master/DebianMed/edam.sh)
  * Script creating [JSON records from Debian packages](http://anonscm.debian.org/viewvc/debian-med/trunk/community/edam/registry-tool.py?view=markup) that are committed here into json-buff
  * A [temporary doc](https://docs.google.com/document/d/1H44HxQik2RnxWzBui3GuYI9pAMfX5tNDBiwRa5g0WXg) with implementation thoughts
 
 
## Expected further sources of tool descriptions to be imported into json-buffer:
 
  * __Bio.Tools__ (__*NB.* that this could be a special case__ with ONLY the records already present in json-buff being updated from *bio.tools*, _i.e._ committed to a corresponding *branch*. Otherwise import either all *bio.tools* records, or ones selected by some criteria, _e.g._ software only)
  * __SEQwiki__
  * __Bioconda__
  * __biii.info/NEUBIAS__
  * _etc._ ...
