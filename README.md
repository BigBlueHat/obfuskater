# Obfuskater - Obfu-skates JSON API output

[couchmail.py](http://github.com/BigBlueHat/couchmail.py) was originally
built (like these
[other](https://github.com/maxogden/couchmail)
[couchmail](https://github.com/apage43/couchmail)'s
before it).

However, I also wanted to build couchmail.py to host public email archives
for [Apache CouchDB](http://couchdb.apache.org/) mailing lists and back
those archives with [Cloudant](http://cloudant.com/)'s Full-Text Search
indexing. So...a [CouchApp](http://github.com/couchapp/couchapp) prooved
insufficient.

#### Thus was born Obfuskater!

Currently, it does nothing more than hunt down the `from` address/field
in response JSON docs (after it retrieves them from a cloudant account)
and obfuscates them a bit (ex: b...@bigbluehat.com).

## License

[Apache License v2.0](http://www.apache.org/licenses/LICENSE-2.0)
