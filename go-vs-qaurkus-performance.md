`➜  ~ ab -n 1000 http://code-with-quarkus-garima-joshi-dev.apps.sandbox-m2.ll9k.p1.openshiftapps.com/
This is ApacheBench, Version 2.3 <$Revision: 1901567 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking code-with-quarkus-garima-joshi-dev.apps.sandbox-m2.ll9k.p1.openshiftapps.com (be patient)
Completed 100 requests
Completed 200 requests
Completed 300 requests
Completed 400 requests
Completed 500 requests
Completed 600 requests
Completed 700 requests
Completed 800 requests
Completed 900 requests
Completed 1000 requests
Finished 1000 requests


Server Software:
Server Hostname:        code-with-quarkus-garima-joshi-dev.apps.sandbox-m2.ll9k.p1.openshiftapps.com
Server Port:            80

Document Path:          /
Document Length:        5254 bytes

Concurrency Level:      1
Time taken for tests:   230.751 seconds
Complete requests:      1000
Failed requests:        0
Total transferred:      5598000 bytes
HTML transferred:       5254000 bytes
Requests per second:    4.33 [#/sec] (mean)
Time per request:       230.751 [ms] (mean)
Time per request:       230.751 [ms] (mean, across all concurrent requests)
Transfer rate:          23.69 [Kbytes/sec] received

Connection Times (ms)
min  mean[+/-sd] median   max
Connect:      101  114   6.1    114     132
Processing:   106  117  12.8    118     482
Waiting:      105  116  12.8    118     482
Total:        210  231  15.8    232     605

Percentage of the requests served within a certain time (ms)
50%    232
66%    238
75%    240
80%    241
90%    243
95%    245
98%    247
99%    250
100%    605 (longest request)
➜  ~ ls
Applications                                  eclipse
Desktop                                       eclipse-workspace
Documents                                     gfortran-
Downloads                                     google-cloud-sdk
IdeaProjects                                  google-cloud-sdk-350.0.0-darwin-x86_64.tar.gz
Library                                       iCloud Drive (Archive)
Movies                                        openshift
Music                                         test.mv.db
Pictures                                      test.trace.db
Postman                                       testdb.mv.db
Public                                        testdb.trace.db`



`➜  ~ ab -n 1000 http://golang-sample-garima-joshi-dev.apps.sandbox-m2.ll9k.p1.openshiftapps.com/
This is ApacheBench, Version 2.3 <$Revision: 1901567 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking golang-sample-garima-joshi-dev.apps.sandbox-m2.ll9k.p1.openshiftapps.com (be patient)
Completed 100 requests
Completed 200 requests
Completed 300 requests
Completed 400 requests
Completed 500 requests
Completed 600 requests
Completed 700 requests
Completed 800 requests
Completed 900 requests
Completed 1000 requests
Finished 1000 requests


Server Software:
Server Hostname:        golang-sample-garima-joshi-dev.apps.sandbox-m2.ll9k.p1.openshiftapps.com
Server Port:            80

Document Path:          /
Document Length:        17 bytes

Concurrency Level:      1
Time taken for tests:   226.527 seconds
Complete requests:      1000
Failed requests:        0
Total transferred:      255000 bytes
HTML transferred:       17000 bytes
Requests per second:    4.41 [#/sec] (mean)
Time per request:       226.527 [ms] (mean)
Time per request:       226.527 [ms] (mean, across all concurrent requests)
Transfer rate:          1.10 [Kbytes/sec] received

Connection Times (ms)
min  mean[+/-sd] median   max
Connect:      100  113  13.3    112     490
Processing:   103  114   5.5    115     152
Waiting:      103  114   5.5    115     152
Total:        207  226  15.8    228     603

Percentage of the requests served within a certain time (ms)
50%    228
66%    233
75%    235
80%    236
90%    239
95%    241
98%    244
99%    246
100%    603 (longest request)`
