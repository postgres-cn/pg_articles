# PostgreSQL文章翻译说明

## 1. 说明
本页面用于管理PostgreSQL相关外文文章的翻译，实施流程如下：

1. 发布翻译需求

    如果你发现一篇PostgreSQL相关的不错的外文文章，觉得有必要介绍给国内的pger，可以在这里发布翻译需求。
    具体做法是编辑本wiki页面，添加一个状态为“待翻译”的翻译任务。

2. 认领翻译任务

    如果你或你的团队热心于为社区做贡献可以在这里领取翻译任务。将认领的翻译任务状态修改为“翻译中”并在“翻译者”中登记自己的名字。你也可以自己发布需求自己认领，在这里登记可以避免重复翻译。 

3. 向社区投稿

    （1）文章翻译完成之后首先上传到[已翻译](https://github.com/postgres-cn/pg_articles/tree/master/%E5%B7%B2%E7%BF%BB%E8%AF%91)目录下，以便归档。

    （2）至少由另一名志愿者审核校对过译文稿件，确认文章翻译准确无误后，更新本页面的"翻译状态"为“已校对”。

    （3）通知PostgreSQL中文社区文章翻译负责人陈河堆审核确认，之后由陈河堆向PG中文社区推荐投稿，投稿格式要求为WORD格式，投稿翻译文章时请注明原文出处。相关要求参见：[翻译文章投稿要求](https://github.com/postgres-cn/pg_articles/wiki/%E7%BF%BB%E8%AF%91%E6%96%87%E7%AB%A0%E6%8A%95%E7%A8%BF%E8%A6%81%E6%B1%82)。确认可以投稿之后更新本页面的"翻译状态"为“已投稿”。

    （4）文章确认发表之后更新本页面的"翻译状态"为“已发表”。

## 2. 翻译任务列表

翻译状态:待翻译，翻译中，已校对，已投稿，已发表

备注：若文章链接无法打开，请自行翻墙

|NO|文章(标题&URL地址)|翻译状态|提交者|提交日期|翻译者+校对者|翻译日期|是否已投稿？|
|---|----------------|------|-------|-----------------|-------|---------|---|
|1|[The Curious Case of Split WAL Files](http://richyen.com/replication/postgres/2019/01/22/split_wal_files.html)|完成|francs|2018-01-24|彭煜玮|2018-01-28|已投稿|
|2|[Who Contributed to PostgreSQL Development in 2018?](https://rhaas.blogspot.com/2019/01/who-contributed-to-postgresql.html)|翻译中|francs|2018-01-25|doudou586|2019-03-05|No|
|3|[How Much maintenance_work_mem Do I Need?](https://rhaas.blogspot.com/2019/01/how-much-maintenanceworkmem-do-i-need.html)|翻译中|francs|2018-01-25|陈河堆|2018-02-20|已投稿|
|4|[LOOKING AT MYSQL 8 WITH POSTGRESQL GOGGLES ON](https://www.cybertec-postgresql.com/en/looking-at-mysql-8-with-postgresql-goggles-on/)|已校对|francs|2018-03-5|李冉+陈雁飞|2019-5-15|否|
|5|[Managing High Availability in PostgreSQL](https://scalegrid.io/blog/managing-high-availability-in-postgresql-part-2/)|翻译中|francs|2018-03-13|韩丹|||
|6|[Why hot_standby_feedback Can Be Misleading](https://www.enterprisedb.com/blog/why-hotstandbyfeedback-can-be-misleading)|已校对|陈河堆|2018-03-13|陈雁飞+李冉|2019-4-20|NO|
|7|[Why You Should Choose Postgres Over Oracle](https://www.enterprisedb.com/blog/why-you-should-choose-postgres-over-oracle)|完成|陈河堆|2018-03-13|KevinZhan|2019-4-17|已投稿|
|8|[massively parallel Postgres database onto Kubernetes](http://engineering.pivotal.io/post/how_we_moved_a_massively_parallel_postgres_database_onto_kubernetes)|翻译中|陈河堆|2018-03-30|[allen7lee](https://github.com/allen7lee)|2019-4-25|已投稿|
|9|[Why CockroachDB and PostgreSQL Are Compatible](https://www.cockroachlabs.com/blog/why-postgres/)|翻译中|fredchenbj|2019-04-14|fredchenbj|2019-4-14|No|
| 10| [The Internals of PostgreSQL](http://www.interdb.jp/pg/index.html "The Internals of PostgreSQL") |翻译中 | qinghui.guo     | 2019-04-14 | qinghui.guo | 无| 否|
|11|[GPU Accelerated SQL queries with PostgreSQL & PG-Strom in OpenShift-3.10](https://blog.openshift.com/gpu-accelerated-sql-queries-with-postgresql-pg-strom-in-openshift-3-10/ "GPU Accelerated SQL queries with PostgreSQL & PG-Strom in OpenShift-3.10")|完成|朱君鹏|2019-4-14|朱君鹏|2019-4-15|否|
|12|[Understanding caching in Postgres - An in-depth guide](https://madusudanan.com/blog/understanding-postgres-caching-in-depth/)|完成|LittleWuCoding|2019-4-14|LittleWuCoding|2019-4-29|已投稿|
|13|[An intelligent storage for PostgreSQL database](http://heterodb.com/blobs/P7130_KAIGAI_SSD2GPU_FIXTYPO.pdf)|完成|朱君鹏|2019-4-15|朱君鹏|2019-4-15|否|
|14|[PG-Strom Manual](https://heterodb.github.io/pg-strom/)|翻译中|朱君鹏|2019-4-15|朱君鹏|无|否|
|15|[pgBackRest - Performing Backups on a Standby Cluster](https://info.crunchydata.com/blog/pgbackrest-performing-backups-on-a-standby-cluster)|已翻译|秦红胜|2019-4-10|秦红胜|2018-04-15|已投稿|
|16|[GPU-based Sorting in PostgreSQL](https://pdfs.semanticscholar.org/869f/beb4db447174d4c6a475e942a2607465a410.pdf)|完成|朱君鹏|2019-4-16|朱君鹏|2018-4-16|已发表|
|17|[GPU-based PostgreSQL Extensions for Scalable High-throughput Pattern Matching](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6977041)|完成|朱君鹏|2019-4-18|朱君鹏|2018-4-18|已发表|
|18|[Optimizing storage of small tables in PostgreSQL 12](https://www.2ndquadrant.com/en/blog/optimizing-storage-small-tables-postgresql-12/)|完成|Nail|2019-4-19|Nail|2019-4-23|否|
|19|[ADDING AN INDEX CAN DECREASE SELECT PERFORMANCE](https://www.cybertec-postgresql.com/en/index-decreases-select-performance/)|已发表|陈雁飞|2019-4-20|陈雁飞+李冉|无|已投稿|
|20|[PostgreSQL: Access ClickHouse, One of the Fastest Column DBMSs, With clickhousedb_fdw](https://www.percona.com/blog/2019/03/29/postgresql-access-clickhouse-one-of-the-fastest-column-dbmss-with-clickhousedb_fdw/)|完成|李红艳|2019-4-20|李红艳+吴伟略|2019-5-17|否|
|21|[A Close Look at the Index Include Clause](https://use-the-index-luke.com/blog/2019-04/include-columns-in-btree-indexes)|翻译中|陈雁飞|2019-5-4|陈雁飞|2019-6-16|否|
|22|[Replication Between PostgreSQL Versions Using Logical Replication](https://www.percona.com/blog/2019/04/04/replication-between-postgresql-versions-using-logical-replication/)|已校对|崔鹏|2019-5-21|Qinghui.guo|2019-5-09|否|
|23|[PostgreSQL Locking Revealed](https://www.linkedin.com/pulse/postgresql-locking-revealed-petar-partlov)|翻译中|陈雁飞|2019-6-16|陈雁飞|NO|否|
|24|[Writing Postgres Extensions - the Basics](http://big-elephants.com/2015-10/writing-postgres-extensions-part-i/)|翻译中|李阳|2019-6-19|李阳|NO|否|
|25|[Writing Postgres Extensions - Types and Operators](http://big-elephants.com/2015-10/writing-postgres-extensions-part-ii/)|翻译中|李阳|2019-6-19|李阳|NO|否|
|26|[Writing Postgres Extensions - Debugging](http://big-elephants.com/2015-10/writing-postgres-extensions-part-iii/)|翻译中|李阳|2019-6-19|李阳|NO|否|
|27|[Writing Postgres Extensions - Testing](http://big-elephants.com/2015-10/writing-postgres-extensions-part-iv/)|翻译中|李阳|2019-6-19|李阳|NO|否|
|28|[Writing Postgres Extensions Code Organization and Versioning](http://big-elephants.com/2015-10/writing-postgres-extensions-part-v/)|翻译中|李阳|2019-6-19|李阳|NO|否|

