# Restore Audit for PR #1793

These entries existed in `open-digger` HEAD but were missing after directly replacing generated output into `labeled_data/technology/database`.
Accessible/manually confirmed entries were restored. Entries whose repo URL API and repository id API both return 404 were intentionally not restored.

- File-level candidates reviewed: 8
- Restored file-level entries: 6
- Not restored file-level entries: 2

## Restored

- `apache/lucene-solr` (`id: 50229487`) in `labeled_data/technology/database/document.yml` at id line 99, name line 100
- `mdaniel/svn-caucho-com-resin` (`id: 3596087`) in `labeled_data/technology/database/key_value.yml` at id line 285, name line 286
- `prologic/bitcask` (`id: 385283362`) in `labeled_data/technology/database/key_value.yml` at id line 333, name line 334
- `objectbox/objectbox-java` (`id: 79901405`) in `labeled_data/technology/database/object_oriented.yml` at id line 76, name line 77
- `apache/tajo` (`id: 17971138`) in `labeled_data/technology/database/relational.yml` at id line 179, name line 180
- `apache/lucene-solr` (`id: 50229487`) in `labeled_data/technology/database/search_engine.yml` at id line 16, name line 17

## Not Restored

- `petermattis/pebble` (`id: 278684767`) in `labeled_data/technology/database/key_value.yml`. Not restored because both `https://api.github.com/repos/petermattis/pebble` and `https://api.github.com/repositories/278684767` return 404.
- `xap/xap` (`id: 65259211`) in `labeled_data/technology/database/key_value.yml`. Not restored because both `https://api.github.com/repos/xap/xap` and `https://api.github.com/repositories/65259211` return 404.
