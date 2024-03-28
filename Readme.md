# pg Dump and Restore

### Dumping from Remote db to Local Binary

```.sql

pg_dump -h remote_host -U remote_username -d remote_database -F c -b -v -f dump_file.dump

```

### Dumping from Binary to Local or Remote db

```.sql

pg_restore -h localhost -U local_username -d local_database -v dump_file.dump


```
