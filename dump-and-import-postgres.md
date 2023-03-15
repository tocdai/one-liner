## Dump
pg_dump -h <public dns> -U <my username> -f dump.sql <name of my database>
## Drop DB
dropdb -U <my username> <database name>
## Import
psql -U <my username> –d <new database name> < dump.sql