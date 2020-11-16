FROM ubuntu:18.04

# CMD while true; do sleep 20 ; echo "{\"app\": \"dummy\", \"foo\": \"bar\"}"; done

# CMD while true; do sleep 20 ; echo "{\"type\": \"log\", \"file\": \"test.log\"}" >>/test/log/test.log; done
CMD while true; do sleep 60 ; echo "[06-24 14:19:39] [p3744] [test] [logging_example.py:45] [INFO] - This is an info test" >>/test/log/test.log; done

CMD while true; do sleep 60 ; echo "2020-09-23 07:03:58,411 INFO  Hello" >>/test1/log/test.log; done
CMD while true; do sleep 60 ; echo "2020-09-23 07:03:58,411 ERROR  Postgres|dbserver1|postgres-connector-task  Producer failure   [io.debezium.pipeline.ErrorHandler]\n org.postgresql.util.PSQLException: Database connection failed when writing to copy\nat org.postgresql.core.v3.QueryExecutorImpl.flushCopy(QueryExecutorImpl.java:1052)\nat org.postgresql.core.v3.CopyDualImpl.flushCopy(CopyDualImpl.java:23)" >>/test1/log/test.log; done

#NGINX LOG
CMD while true; do sleep 60 ; echo '193.106.129.153 - - [10/Nov/2020:23:55:06 +0000] "GET /orders/api/v1/orders/rating/43?access_token=aB8jWCsubJEzn3LKOnF-hwR6Z5DhfNQvNnIj2ld-lTQqFEjD-EhnLp8oO-eWso-EYIf47oQMr6896RQDes5pog HTTP/1.1" 404 53 "-" "Dalvik/2.1.0 (Linux; U; Android 9; SM-G955F Build/PPR1.180610.011)" "-"' >>/test2/log/test.log; done
CMD while true; do sleep 60 ; echo '2020/11/11 21:19:40 [warn] 28#28: *524169 upstream server temporarily disabled while reading response header from upstream, client: 5.173.208.194, server: api.insbay.app, request: "GET /clothes/api/v1/clothes/famous_clothes_with_condition?user_type=7&access_token=aB8jWCsubJEzn3LKOnF-hwR6Z5DhfNQvNnIj2ld-lTQqFEjD-EhnLp8oO-eWso-EYIf47oQMr6896RQDes5pog HTTP/1.1", upstream: "http://172.31.3.237:80/api/v1/clothes/famous_clothes_with_condition?user_type=7&access_token=aB8jWCsubJEzn3LKOnF-hwR6Z5DhfNQvNnIj2ld-lTQqFEjD-EhnLp8oO-eWso-EYIf47oQMr6896RQDes5pog", host: "api.insbay.app"' >>/test2/log/test.log; done
CMD while true; do sleep 60 ; echo '2020/11/11 21:19:40 [error] 27#27: *524166 upstream prematurely closed connection while reading response header from upstream, client: 5.173.208.194, server: api.insbay.app, request: "GET /clothes/api/v1/outfits/list?user_type=7&limit=10&page=0&access_token=aB8jWCsubJEzn3LKOnF-hwR6Z5DhfNQvNnIj2ld-lTQqFEjD-EhnLp8oO-eWso-EYIf47oQMr6896RQDes5pog HTTP/1.1", upstream: "http://172.31.3.237:80/api/v1/outfits/list?user_type=7&limit=10&page=0&access_token=aB8jWCsubJEzn3LKOnF-hwR6Z5DhfNQvNnIj2ld-lTQqFEjD-EhnLp8oO-eWso-EYIf47oQMr6896RQDes5pog", host: "api.insbay.app"' >>/test2/log/test.log; done