Fix #1793

Batch label data: incrementally update labeled repositories in the Database technology area.

## Update Data

Update labeled data of open source DBMS repositories with GitHub repository links, based on dbdb.io and DB-Engines ranking data up to August 8, 2026 for July.

## Filter Conditions

- Collected by dbdb.io on August 8, 2026, or listed in the DB-Engines ranking table on July 31, 2026.
- Has an open source license.
- Has a repository link on GitHub.
- Incremental update relative to the previous database labeled data update for #1784.

## Summary

- Updated 11 database label files: Array, Document, Graph, Hierarchical, Key-value, Object Oriented, RDF, Relational, Search Engine, Vector, Wide Column.
- Added 99 repositories.
- Removed 2 repositories.
- Updated 43 repository names for existing GitHub repo ids.
- Changed label-repo records: +178, -69.
- Repo ids were queried from the GitHub REST API: `https://api.github.com/repos/{owner}/{repo}`.

### Change List

<details>
<summary>Renamed repositories: 43</summary>

- `apache/incubator-horaedb` -> `apache/horaedb` (`id: 496505424`; labels: Relational)
- `apache/incubator-hugegraph` -> `apache/hugegraph` (`id: 141376301`; labels: Graph)
- `badgerman/ennodb` -> `ennorehling/ennodb` (`id: 6768410`; labels: Key-value)
- `bitnine-oss/agensgraph` -> `skaiworldwide-oss/agensgraph` (`id: 57401138`; labels: Document, Graph, Key-value, Relational)
- `blazingdb/pyBlazing` -> `BlazingDB/blazingsql` (`id: 150149024`; labels: Relational)
- `c9fe/sirdb` -> `DO-SAY-GO/sirdb` (`id: 234091935`; labels: Document)
- `cloudberrydb/cloudberrydb` -> `apache/cloudberry` (`id: 644742603`; labels: Object Oriented, Relational)
- `coilhq/tigerbeetle` -> `tigerbeetle/tigerbeetle` (`id: 254418044`; labels: Relational)
- `dappkit/aviondb` -> `aviondb/aviondb` (`id: 249981301`; labels: Document)
- `darshan117/BroDB` -> `darshan117/BroSql` (`id: 824462634`; labels: Relational)
- `datafuselabs/databend` -> `databendlabs/databend` (`id: 302827809`; labels: Relational)
- `dicedb/dice` -> `dicedb/dicedb` (`id: 531220682`; labels: Key-value)
- `eleme/lindb` -> `lindb/lindb` (`id: 191676087`; labels: Wide Column)
- `featurebasedb/featurebase` / `pilosa/pilosa` -> `FeatureBaseDB/featurebase` / `featurebasedb/featurebase` (`id: 40127179`; labels: Relational, Vector)
- `featureform/embeddinghub` -> `featureform/featureform` (`id: 304530333`; labels: Vector)
- `genjidb/genji` -> `chaisql/chai` (`id: 138411034`; labels: Document)
- `georgia-tech-db/eva` -> `georgia-tech-db/evadb` (`id: 148087762`; labels: Relational)
- `Greg0/Lazer-Database` -> `Lazer-Database/Lazer-Database` (`id: 8313554`; labels: Document)
- `hivedb/hive` -> `isar/hive` (`id: 195895847`; labels: Key-value)
- `HydrasDB/hydra` -> `hydradatabase/columnar` (`id: 516821813`; labels: Object Oriented, Relational)
- `juji-io/datalevin` -> `datalevin/datalevin` (`id: 270858421`; labels: Document)
- `KvrocksLabs/kvrocks` -> `apache/kvrocks` (`id: 202483348`; labels: Key-value)
- `libsql/libsql` -> `tursodatabase/libsql` (`id: 543276238`; labels: Relational)
- `mbdavid/LiteDB` -> `litedb-org/LiteDB` (`id: 23315232`; labels: Document)
- `oasysai/oasysdb` -> `edwinkys/oasysdb` (`id: 722854801`; labels: Key-value, Vector)
- `orbitdb/orbit-db` -> `orbitdb/orbitdb` (`id: 48617634`; labels: Document, Key-value)
- `pouchdb/pouchdb` -> `apache/pouchdb` (`id: 714074`; labels: Document)
- `Qihoo360/pika` -> `OpenAtomFoundation/pikiwidb` (`id: 26127968`; labels: Key-value)
- `radare/sdb` -> `radareorg/sdb` (`id: 5665061`; labels: Document, Relational)
- `rakibtg/SleekDB` -> `SleekDB/SleekDB` (`id: 129436009`; labels: Document)
- `resilientdb/resilientdb` -> `apache/incubator-resilientdb` (`id: 223462217`; labels: Document)
- `roseduan/rosedb` -> `rosedblabs/rosedb` (`id: 318972528`; labels: Key-value)
- `scratchdata/ScratchDB` -> `scratchdata/scratchdata` (`id: 664816265`; labels: Document)
- `scylladb/scylla` -> `scylladb/scylladb` (`id: 28449431`; labels: Key-value, Wide Column)
- `semi-technologies/weaviate` -> `weaviate/weaviate` (`id: 55072677`; labels: Vector)
- `SnappyDataInc/snappydata` -> `TIBCOSoftware/snappydata` (`id: 42580991`; labels: Relational)
- `streamnative/oxia` -> `oxia-db/oxia` (`id: 454981666`; labels: Key-value)
- `stripe/sequins` -> `stripe-archive/sequins` (`id: 26888631`; labels: Key-value)
- `unnamed38/fueldb` -> `jbasiglio/fueldb` (`id: 25364889`; labels: Document)
- `web3-storage/pail` -> `storacha/pail` (`id: 580788054`; labels: Key-value)
- `xujiajun/nutsdb` -> `nutsdb/nutsdb` (`id: 160784930`; labels: Key-value)
- `youtrackdb/youtrackdb` -> `JetBrains/youtrackdb` (`id: 759929648`; labels: Graph)
- `zerodb/zerodb` -> `nucypher/zerodb` (`id: 47479424`; labels: Document)

</details>

<details>
<summary>Added repositories: 99</summary>

- `539hex/zu` (`id: 981319788`; labels: Key-value)
- `ad-freiburg/qlever` (`id: 27594187`; labels: Graph, RDF)
- `akumuli/Akumuli` (`id: 16326644`; labels: Relational)
- `alibaba/neug` (`id: 1170374747`; labels: Graph)
- `alibaba/zvec` (`id: 1110443421`; labels: Vector)
- `antflydb/antfly` (`id: 1182753977`; labels: Graph, Vector)
- `antithesishq/valthree` (`id: 1034637202`; labels: Key-value)
- `antoniosarosi/mkdb` (`id: 700017073`; labels: Relational)
- `apache/incubator-tajo` (`id: 17971137`; labels: Relational)
- `apache/rya` (`id: 43734923`; labels: RDF)
- `apache/solr` (`id: 341374920`; labels: Document, Search Engine)
- `ariasql/ariasql` (`id: 757281035`; labels: Relational)
- `ArroyoSystems/arroyo` (`id: 621929252`; labels: Relational)
- `ayoubnabil/aiondb` (`id: 1237465314`; labels: Graph, Relational, Vector)
- `barrel-db/barrel` (`id: 1296163320`; labels: Document, Vector)
- `basho/bitcask` (`id: 632037`; labels: Key-value)
- `BemiHQ/BemiDB` (`id: 883391427`; labels: Relational)
- `blevesearch/bleve` (`id: 18893367`; labels: Document, Vector)
- `carlosbarbosamexico/narayana` (`id: 1099507418`; labels: Relational)
- `cockroachdb/pebble` (`id: 141339868`; labels: Key-value)
- `cube2222/octosql` (`id: 173582015`; labels: Relational)
- `dlitz/resin` (`id: 3115025`; labels: Key-value)
- `documentdb/documentdb` (`id: 920805662`; labels: Document)
- `earonesty/lakeql` (`id: 1268325095`; labels: Relational)
- `endee-io/endee` (`id: 1141278752`; labels: Vector)
- `estebanrfp/gdb` (`id: 590923204`; labels: Graph)
- `ExtendDB/extenddb` (`id: 1234582852`; labels: Document, Key-value)
- `facebookarchive/webscalesql-5.6` (`id: 13887383`; labels: Relational)
- `ferres-db/ferres-db` (`id: 1150783842`; labels: Vector)
- `glycerine/shore-mt` (`id: 6433550`; labels: Object Oriented)
- `GNS-Foundation/mobydb` (`id: 1199943658`; labels: Key-value)
- `graemedouglas/LittleD` (`id: 14753974`; labels: Relational)
- `GraphLite-AI/GraphLite` (`id: 1096820313`; labels: Graph)
- `guycipher/k4` (`id: 879526764`; labels: Key-value)
- `hexxla/hexxladb` (`id: 1208697458`; labels: Array, Vector)
- `hicder/muopdb` (`id: 869784587`; labels: Vector)
- `hydraide/hydraide` (`id: 952556108`; labels: Key-value)
- `hyparam/squirreling` (`id: 1101734601`; labels: Relational)
- `inder/salvobase` (`id: 1171244520`; labels: Document)
- `infino-ai/infino` (`id: 1243401750`; labels: Relational)
- `IssunDB/issun-db` (`id: 1244916331`; labels: Graph, Vector)
- `JagritGumber/evolvsql` (`id: 1188294539`; labels: Relational)
- `JakeRoggenbuck/kronicler` (`id: 1047223442`; labels: Relational)
- `JakeRoggenbuck/RedoxQL` (`id: 915978190`; labels: Relational)
- `jose-compu/logosdb` (`id: 1210826829`; labels: Vector)
- `kairosdb/kairosdb` (`id: 8039659`; labels: Key-value, Wide Column)
- `kashyap-devansh/Ark` (`id: 1174651148`; labels: Relational)
- `katehonz/barabaDB` (`id: 1230283259`; labels: Document, Graph, Wide Column)
- `kurrent-io/KurrentDB` (`id: 5844474`; labels: Document)
- `lasect/discodb` (`id: 1193777419`; labels: Relational)
- `leanstore/leanstore` (`id: 328647920`; labels: Key-value)
- `lispking/kvdb` (`id: 1198485229`; labels: Key-value)
- `Log2n-io/Typhon` (`id: 366298992`; labels: Object Oriented)
- `lotusdblabs/lotusdb` (`id: 438128602`; labels: Key-value)
- `LucidDB/luciddb` (`id: 3017505`; labels: Relational)
- `MauricioPerera/LOKIVECTOR` (`id: 1111440285`; labels: Document, Vector)
- `maxnilz/sboxdb` (`id: 780362035`; labels: Relational)
- `multigres/multigres` (`id: 999616035`; labels: Relational)
- `mzinsmeister/OxidSQL` (`id: 460512584`; labels: Relational)
- `nambok/mentedb` (`id: 1201033913`; labels: Graph, Vector)
- `namidb/namidb` (`id: 1242792159`; labels: Graph)
- `Netflix/dynomite` (`id: 13484625`; labels: Key-value)
- `nubskr/nubmq` (`id: 858384155`; labels: Key-value)
- `nubskr/satoriDB` (`id: 1108658403`; labels: Vector)
- `nukep/llamadb` (`id: 31960975`; labels: Relational)
- `NumstoreDB/Numstore` (`id: 1211040071`; labels: Array)
- `oceanbase/seekdb` (`id: 1080442728`; labels: Relational, Vector)
- `open-gpdb/gpdb` (`id: 813146214`; labels: Relational)
- `outr/HaloDB` (`id: 891723751`; labels: Key-value)
- `OxidizeLabs/ferrite` (`id: 828849220`; labels: Relational)
- `oxigraph/oxigraph` (`id: 133687025`; labels: Graph, RDF)
- `pmwkaa/sophia` (`id: 12843155`; labels: Key-value)
- `quqiangsheng/abhot` (`id: 95753144`; labels: Relational)
- `rax-maas/blueflood` (`id: 10081109`; labels: Key-value, Wide Column)
- `replikativ/datahike` (`id: 116407410`; labels: Key-value)
- `Schema-JS/schema-js` (`id: 836018246`; labels: Document)
- `shuruheel/mnestic` (`id: 1254385987`; labels: Relational)
- `skel84/allocdb` (`id: 1179701067`; labels: Relational)
- `sklad-dev/Sklad` (`id: 942380667`; labels: Key-value)
- `sochdb/sochdb` (`id: 1126115972`; labels: Graph, Relational, Vector)
- `softmaxdata/engram` (`id: 1169046116`; labels: Graph)
- `SouravRoy-ETL/slothdb` (`id: 1211492976`; labels: Relational)
- `spotify/sparkey` (`id: 12488811`; labels: Key-value)
- `SwellDB/SwellDB` (`id: 972754006`; labels: Relational)
- `Tencent/MMKV` (`id: 149111813`; labels: Key-value)
- `thetarby/helindb` (`id: 426652249`; labels: Key-value)
- `tidwall/pogocache` (`id: 1023788092`; labels: Key-value)
- `TieredMemDB/TieredMemDB` (`id: 415886839`; labels: Key-value)
- `Tokutek/mongo` (`id: 8729689`; labels: Document)
- `tursodatabase/turso` (`id: 683347556`; labels: Relational)
- `ubco-db/EmbedDB` (`id: 646912783`; labels: Relational)
- `Unconcurrent/SoloDB` (`id: 813243891`; labels: Document)
- `villagesql/villagesql-server` (`id: 975757837`; labels: Relational)
- `VincentKaufmann/GitDB` (`id: 1182378589`; labels: Document, Vector)
- `viyadb/viyadb` (`id: 104114230`; labels: Relational)
- `volcengine/OpenViking` (`id: 1128123594`; labels: Hierarchical)
- `warehouse-pg/warehouse-pg` (`id: 964004742`; labels: Relational)
- `yantrikos/yantrikdb` (`id: 1164482810`; labels: Graph, Key-value, Vector)
- `zaydmulani09/vecdb` (`id: 1242559745`; labels: Document, Vector)

</details>

<details>
<summary>Removed repositories: 2</summary>

- `petermattis/pebble` (`id: 278684767`; labels: Key-value). Reason: Not restored because both `https://api.github.com/repos/petermattis/pebble` and `https://api.github.com/repositories/278684767` return 404.
- `xap/xap` (`id: 65259211`; labels: Key-value). Reason: Not restored because both `https://api.github.com/repos/xap/xap` and `https://api.github.com/repositories/65259211` return 404.

</details>

## Changed Files

- `labeled_data/technology/database/array.yml`
- `labeled_data/technology/database/document.yml`
- `labeled_data/technology/database/graph.yml`
- `labeled_data/technology/database/hierarchical.yml`
- `labeled_data/technology/database/key_value.yml`
- `labeled_data/technology/database/object_oriented.yml`
- `labeled_data/technology/database/rdf.yml`
- `labeled_data/technology/database/relational.yml`
- `labeled_data/technology/database/search_engine.yml`
- `labeled_data/technology/database/vector.yml`
- `labeled_data/technology/database/wide_column.yml`

## Validation

- Regenerated the parsed GitHub repo id data from `issue_body_format.txt`.
- Verified all changed database YAML files can be parsed as YAML.
- Preserved existing OpenDigger entries that remain accessible or manually confirmed; see local restore audit `temp/pr_1793_restore_needed.md`.
- Did not restore removed entries whose repository URL API and repository id API both return 404.
