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
Time taken for tests:   227.300 seconds
Complete requests:      1000
Failed requests:        0
Total transferred:      255000 bytes
HTML transferred:       17000 bytes
Requests per second:    4.40 [#/sec] (mean)
Time per request:       227.300 [ms] (mean)
Time per request:       227.300 [ms] (mean, across all concurrent requests)
Transfer rate:          1.10 [Kbytes/sec] received

Connection Times (ms)
min  mean[+/-sd] median   max
Connect:      100  113   5.9    112     125
Processing:   103  115  20.6    116     734
Waiting:      101  114  20.7    116     734
Total:        208  227  22.3    228     840

Percentage of the requests served within a certain time (ms)
50%    228
66%    234
75%    236
80%    237
90%    240
95%    241
98%    243
99%    248
100%    840 (longest request)`


`➜  ~ ab -n 1000 http://java-springboot-basic-garima-joshi-dev.apps.sandbox-m2.ll9k.p1.openshiftapps.com/
This is ApacheBench, Version 2.3 <$Revision: 1901567 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking java-springboot-basic-garima-joshi-dev.apps.sandbox-m2.ll9k.p1.openshiftapps.com (be patient)
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
Server Hostname:        java-springboot-basic-garima-joshi-dev.apps.sandbox-m2.ll9k.p1.openshiftapps.com
Server Port:            80

Document Path:          /
Document Length:        12 bytes

Concurrency Level:      1
Time taken for tests:   231.053 seconds
Complete requests:      1000
Failed requests:        0
Total transferred:      290000 bytes
HTML transferred:       12000 bytes
Requests per second:    4.33 [#/sec] (mean)
Time per request:       231.053 [ms] (mean)
Time per request:       231.053 [ms] (mean, across all concurrent requests)
Transfer rate:          1.23 [Kbytes/sec] received

Connection Times (ms)
min  mean[+/-sd] median   max
Connect:      102  115  12.5    114     391
Processing:   106  116  27.0    117     722
Waiting:      106  116  27.0    117     722
Total:        209  231  30.4    231     836

Percentage of the requests served within a certain time (ms)
50%    231
66%    237
75%    239
80%    240
90%    242
95%    244
98%    247
99%    251
100%    836 (longest request)`


