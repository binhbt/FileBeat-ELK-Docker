FROM ubuntu:18.04

# CMD while true; do sleep 20 ; echo "{\"app\": \"dummy\", \"foo\": \"bar\"}"; done

# CMD while true; do sleep 20 ; echo "{\"type\": \"log\", \"file\": \"test.log\"}" >>/test/log/test.log; done
CMD while true; do sleep 60 ; echo "[06-24 14:19:39] [p3744] [test] [logging_example.py:45] [INFO] - This is an info test" >>/test/log/test.log; done

CMD while true; do sleep 60 ; echo "2020-09-23 07:03:58,411 ERROR  Postgres|dbserver1|postgres-connector-task  Producer failure   [io.debezium.pipeline.ErrorHandler]\n org.postgresql.util.PSQLException: Database connection failed when writing to copy\nat org.postgresql.core.v3.QueryExecutorImpl.flushCopy(QueryExecutorImpl.java:1052)\nat org.postgresql.core.v3.CopyDualImpl.flushCopy(CopyDualImpl.java:23)" >>/test1/log/test.log; done