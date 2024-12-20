protection=2REP
HW_chassis=X205

### 15 nodes 8kb write
INFO[13:08:47] Load started at:               Tue Oct 29 2024 13:08:47 GMT+0000 (UTC)  source=console
INFO[13:18:47] Load finished at:              Tue Oct 29 2024 13:18:47 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 27 GB   45 MB/s
     aws_obj_put_duration...: avg=202.83ms min=28.75ms  med=156.27ms max=13.69s p(90)=343.86ms p(95)=463.23ms
     aws_obj_put_success....: 3294391 5485.850446/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 27 GB   45 MB/s
     iteration_duration.....: avg=211.63ms min=213.78µs med=164.61ms max=13.7s  p(90)=351.31ms p(95)=472.31ms
     iterations.............: 3294391 5485.850446/s
     vus....................: 1162    min=1162      max=1162

running (10m00.5s), 0000/1162 VUs, 3294391 complete and 0 interrupted iterations
write ✓ [======================================] 1162 VUs  10m0s

INFO[13:08:47] Load started at:               Tue Oct 29 2024 13:08:47 GMT+0000 (UTC)  source=console
INFO[13:18:47] Load finished at:              Tue Oct 29 2024 13:18:47 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 26 GB   44 MB/s
     aws_obj_put_duration...: avg=209.34ms min=25.23ms  med=159.78ms max=15.07s p(90)=361.82ms p(95)=472.45ms
     aws_obj_put_success....: 3198122 5328.039475/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 26 GB   44 MB/s
     iteration_duration.....: avg=217.99ms min=205.06µs med=166.34ms max=15.08s p(90)=370.3ms  p(95)=482.16ms
     iterations.............: 3198122 5328.039475/s
     vus....................: 1162    min=1162      max=1162

running (10m00.2s), 0000/1162 VUs, 3198122 complete and 0 interrupted iterations
write ✓ [======================================] 1162 VUs  10m0s

### 15 nodes 128kb write
INFO[11:32:27] Load started at: Fri Oct 25 2024 11:32:27 GMT+0000 (UTC) source=console 
INFO[11:42:29] Load finished at: Fri Oct 25 2024 11:42:29 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_put_bytes......: 291 GB  484 MB/s
 aws_obj_put_duration...: avg=294.04ms min=37.05ms  med=202.21ms max=7.74s p(90)=473.3ms  p(95)=699.21ms
 aws_obj_put_success....: 2222854 3693.309977/s
 data_received..........: 0 B     0 B/s
 data_sent..............: 291 GB  483 MB/s
 iteration_duration.....: avg=303.8ms  min=300.01µs med=210.64ms max=7.75s p(90)=482.91ms p(95)=708.74ms
 iterations.............: 2222854 3693.309977/s
 vus....................: 32      min=32        max=1125
```

running (10m01.9s), 0000/1125 VUs, 2222854 complete and 0 interrupted iterations  
write ✓ [======================================] 1125 VUs 10m0s

INFO[11:32:26] Load started at: Fri Oct 25 2024 11:32:26 GMT+0000 (UTC) source=console 
INFO[11:42:28] Load finished at: Fri Oct 25 2024 11:42:28 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_put_bytes......: 299 GB  497 MB/s
 aws_obj_put_duration...: avg=286.07ms min=38.43ms med=197.3ms  max=7.95s p(90)=463.71ms p(95)=688.14ms
 aws_obj_put_success....: 2283780 3791.548478/s
 data_received..........: 0 B     0 B/s
 data_sent..............: 299 GB  496 MB/s
 iteration_duration.....: avg=295.75ms min=3.49ms  med=207.46ms max=7.96s p(90)=473.79ms p(95)=697.61ms
 iterations.............: 2283780 3791.548478/s
 vus....................: 70      min=70        max=1125
```

running (10m02.3s), 0000/1125 VUs, 2283780 complete and 0 interrupted iterations  
write ✓ [======================================] 1125 VUs 10m0s

### 15 nodes 128kb read
INFO[12:07:08] Load started at:               Fri Oct 25 2024 12:07:08 GMT+0000 (UTC)  source=console
INFO[12:17:08] Load finished at:              Fri Oct 25 2024 12:17:08 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 513 GB  854 MB/s
     aws_obj_get_duration...: avg=172.39ms min=10.45ms  med=123.98ms max=12.81s p(90)=324.78ms p(95)=408.65ms
     aws_obj_get_fails......: 39      0.064967/s
     aws_obj_get_success....: 3913081 6518.457511/s
     data_received..........: 513 GB  854 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=172.47ms min=616.92µs med=124.06ms max=12.81s p(90)=324.87ms p(95)=408.73ms
     iterations.............: 3913120 6518.522478/s
     vus....................: 1125    min=1125      max=1125

running (10m00.3s), 0000/1125 VUs, 3913120 complete and 0 interrupted iterations
read ✓ [======================================] 1125 VUs  10m0s

INFO[12:07:08] Load started at:               Fri Oct 25 2024 12:07:08 GMT+0000 (UTC)  source=console
INFO[12:17:07] Load finished at:              Fri Oct 25 2024 12:17:07 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 513 GB  854 MB/s
     aws_obj_get_duration...: avg=172.38ms min=9.74ms  med=125.89ms max=9.9s p(90)=329.45ms p(95)=415.24ms
     aws_obj_get_fails......: 40      0.066614/s
     aws_obj_get_success....: 3913729 6517.713245/s
     data_received..........: 513 GB  854 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=172.46ms min=837.2µs med=125.97ms max=9.9s p(90)=329.54ms p(95)=415.33ms
     iterations.............: 3913769 6517.779859/s
     vus....................: 1125    min=1125      max=1125

running (10m00.5s), 0000/1125 VUs, 3913769 complete and 0 interrupted iterations
read ✓ [======================================] 1125 VUs  10m0s

### 15 nodes 128mib write
INFO[11:16:25] Load started at:               Tue Oct 29 2024 11:16:25 GMT+0000 (UTC)  source=console
INFO[11:26:31] Load finished at:              Tue Oct 29 2024 11:26:31 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 930 GB 1.5 GB/s
     aws_obj_put_duration...: avg=18.87s min=6.77s    med=16.58s max=1m46s p(90)=27.1s p(95)=35.58s
     aws_obj_put_fails......: 1      0.001651/s
     aws_obj_put_success....: 6929   11.437345/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 930 GB 1.5 GB/s
     iteration_duration.....: avg=19.3s  min=186.14µs med=17.03s max=1m47s p(90)=27.5s p(95)=35.92s
     iterations.............: 6920   11.422489/s
     vus....................: 175    min=0       max=225

running (10m05.8s), 000/225 VUs, 6920 complete and 174 interrupted iterations
write ✓ [======================================] 225 VUs  10m0s

INFO[11:16:25] Load started at:               Tue Oct 29 2024 11:16:25 GMT+0000 (UTC)  source=console
INFO[11:26:32] Load finished at:              Tue Oct 29 2024 11:26:32 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 923 GB 1.5 GB/s
     aws_obj_put_duration...: avg=19.02s min=7.47s    med=16.54s max=1m43s p(90)=28.68s p(95)=37.46s
     aws_obj_put_fails......: 3      0.004953/s
     aws_obj_put_success....: 6875   11.351692/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 923 GB 1.5 GB/s
     iteration_duration.....: avg=19.46s min=182.76µs med=16.98s max=1m44s p(90)=29.13s p(95)=37.89s
     iterations.............: 6877   11.354995/s
     vus....................: 1      min=0       max=225

running (10m05.6s), 000/225 VUs, 6877 complete and 148 interrupted iterations
write ✓ [======================================] 225 VUs  10m0s

### 14 nodes 8kb write
INFO[13:55:39] Load started at:               Tue Oct 29 2024 13:55:39 GMT+0000 (UTC)  source=console
INFO[14:05:39] Load finished at:              Tue Oct 29 2024 14:05:39 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 27 GB   44 MB/s
     aws_obj_put_duration...: avg=191.4ms  min=32.65ms  med=166.76ms max=11.85s p(90)=282.25ms p(95)=340.62ms
     aws_obj_put_success....: 3251902 5418.24835/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 27 GB   44 MB/s
     iteration_duration.....: avg=200.17ms min=215.71µs med=175.02ms max=11.87s p(90)=289.51ms p(95)=349.61ms
     iterations.............: 3251902 5418.24835/s
     vus....................: 1085    min=1085     max=1085

running (10m00.2s), 0000/1085 VUs, 3251902 complete and 0 interrupted iterations
write ✓ [======================================] 1085 VUs  10m0s

INFO[13:55:38] Load started at:               Tue Oct 29 2024 13:55:38 GMT+0000 (UTC)  source=console
INFO[14:05:38] Load finished at:              Tue Oct 29 2024 14:05:38 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 26 GB   44 MB/s
     aws_obj_put_duration...: avg=194.9ms min=33.49ms  med=169.1ms  max=11.88s p(90)=288.57ms p(95)=352.98ms
     aws_obj_put_success....: 3199199 5323.587174/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 26 GB   44 MB/s
     iteration_duration.....: avg=203.5ms min=180.71µs med=175.96ms max=11.89s p(90)=297.83ms p(95)=360.9ms 
     iterations.............: 3199199 5323.587174/s
     vus....................: 13      min=13        max=1085

running (10m00.9s), 0000/1085 VUs, 3199199 complete and 0 interrupted iterations
write ✓ [======================================] 1085 VUs  10m0s

### 14 nodes 8kb read
INFO[14:25:23] Load started at:               Tue Oct 29 2024 14:25:23 GMT+0000 (UTC)  source=console
INFO[14:35:24] Load finished at:              Tue Oct 29 2024 14:35:24 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 47 GB   79 MB/s
     aws_obj_get_duration...: avg=112.54ms min=6.9ms    med=70.01ms max=5.57s p(90)=204.23ms p(95)=304.31ms
     aws_obj_get_fails......: 14      0.023316/s
     aws_obj_get_success....: 5779318 9625.05624/s
     data_received..........: 47 GB   79 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=112.62ms min=223.61µs med=70.08ms max=5.57s p(90)=204.31ms p(95)=304.39ms
     iterations.............: 5779332 9625.079557/s
     vus....................: 1085    min=1085      max=1085

running (10m00.4s), 0000/1085 VUs, 5779332 complete and 0 interrupted iterations
read ✓ [======================================] 1085 VUs  10m0s

INFO[14:25:21] Load started at:               Tue Oct 29 2024 14:25:21 GMT+0000 (UTC)  source=console
INFO[14:35:22] Load finished at:              Tue Oct 29 2024 14:35:22 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 47 GB   78 MB/s
     aws_obj_get_duration...: avg=114.21ms min=6.69ms med=71.03ms max=5.5s p(90)=208ms    p(95)=309.83ms
     aws_obj_get_fails......: 11      0.01832/s
     aws_obj_get_success....: 5695461 9485.35644/s
     data_received..........: 47 GB   78 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=114.28ms min=595µs  med=71.11ms max=5.5s p(90)=208.08ms p(95)=309.91ms
     iterations.............: 5695472 9485.37476/s
     vus....................: 1085    min=1085     max=1085

running (10m00.4s), 0000/1085 VUs, 5695472 complete and 0 interrupted iterations
read ✓ [======================================] 1085 VUs  10m0s

### 13 nodes 8kb write
INFO[12:12:39] Load started at:               Tue Oct 29 2024 12:12:39 GMT+0000 (UTC)  source=console
INFO[12:22:39] Load finished at:              Tue Oct 29 2024 12:22:39 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 25 GB   42 MB/s
     aws_obj_put_duration...: avg=186.81ms min=40ms     med=168.27ms max=9.01s p(90)=276.61ms p(95)=323.23ms
     aws_obj_put_success....: 3090342 5146.871931/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 25 GB   42 MB/s
     iteration_duration.....: avg=195.51ms min=695.82µs med=175.88ms max=9.01s p(90)=286.93ms p(95)=331.02ms
     iterations.............: 3090342 5146.871931/s
     vus....................: 1007    min=1007      max=1007

running (10m00.4s), 0000/1007 VUs, 3090342 complete and 0 interrupted iterations
write ✓ [======================================] 1007 VUs  10m0s

INFO[12:12:39] Load started at:               Tue Oct 29 2024 12:12:39 GMT+0000 (UTC)  source=console
INFO[12:22:40] Load finished at:              Tue Oct 29 2024 12:22:40 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 25 GB   42 MB/s
     aws_obj_put_duration...: avg=187.49ms min=40.3ms   med=167.1ms  max=8.99s p(90)=283.28ms p(95)=333.09ms
     aws_obj_put_success....: 3081423 5134.443718/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 25 GB   42 MB/s
     iteration_duration.....: avg=196.05ms min=207.08µs med=175.33ms max=9s    p(90)=290.37ms p(95)=340.99ms
     iterations.............: 3081423 5134.443718/s
     vus....................: 1007    min=1007      max=1007

running (10m00.1s), 0000/1007 VUs, 3081423 complete and 0 interrupted iterations
write ✓ [======================================] 1007 VUs  10m0s

### 13 nodes 8kb read
INFO[12:31:08] Load started at:               Tue Oct 29 2024 12:31:08 GMT+0000 (UTC)  source=console
INFO[12:41:08] Load finished at:              Tue Oct 29 2024 12:41:08 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 42 GB   70 MB/s
     aws_obj_get_duration...: avg=117.73ms min=6.85ms med=71.01ms max=7.42s p(90)=229.65ms p(95)=343.45ms
     aws_obj_get_fails......: 16      0.026641/s
     aws_obj_get_success....: 5128094 8538.48851/s
     data_received..........: 42 GB   70 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=117.81ms min=2.41ms med=71.09ms max=7.42s p(90)=229.73ms p(95)=343.53ms
     iterations.............: 5128110 8538.515151/s
     vus....................: 1007    min=1007      max=1007

running (10m00.6s), 0000/1007 VUs, 5128110 complete and 0 interrupted iterations
read ✓ [======================================] 1007 VUs  10m0s

INFO[12:31:16] Load started at:               Tue Oct 29 2024 12:31:16 GMT+0000 (UTC)  source=console
INFO[12:41:16] Load finished at:              Tue Oct 29 2024 12:41:16 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 42 GB   70 MB/s
     aws_obj_get_duration...: avg=117.14ms min=6.7ms    med=70.63ms max=5.54s p(90)=226.2ms  p(95)=340.74ms
     aws_obj_get_fails......: 24      0.039977/s
     aws_obj_get_success....: 5153456 8584.127162/s
     data_received..........: 42 GB   70 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=117.22ms min=237.02µs med=70.71ms max=5.54s p(90)=226.27ms p(95)=340.82ms
     iterations.............: 5153480 8584.167139/s
     vus....................: 1007    min=1007      max=1007

running (10m00.3s), 0000/1007 VUs, 5153480 complete and 0 interrupted iterations
read ✓ [======================================] 1007 VUs  10m0s

### 8 nodes 128kb write
INFO[18:40:55] Load started at: Fri Oct 25 2024 18:40:55 GMT+0000 (UTC) source=console  
INFO[18:50:56] Load finished at: Fri Oct 25 2024 18:50:56 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_put_bytes......: 160 GB  266 MB/s
 aws_obj_put_duration...: avg=285.42ms min=37.34ms  med=211.87ms max=7.3s p(90)=441.74ms p(95)=578.33ms
 aws_obj_put_success....: 1221233 2030.952633/s
 data_received..........: 0 B     0 B/s
 data_sent..............: 160 GB  266 MB/s
 iteration_duration.....: avg=294.82ms min=353.96µs med=221.84ms max=7.3s p(90)=451.11ms p(95)=587.58ms
 iterations.............: 1221233 2030.952633/s
 vus....................: 40      min=40        max=600
```

running (10m01.3s), 000/600 VUs, 1221233 complete and 0 interrupted iterations  
write ✓ [======================================] 600 VUs 10m0s

INFO[18:40:55] Load started at: Fri Oct 25 2024 18:40:55 GMT+0000 (UTC) source=console  
INFO[18:50:57] Load finished at: Fri Oct 25 2024 18:50:57 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_put_bytes......: 165 GB  274 MB/s
 aws_obj_put_duration...: avg=276.68ms min=32.85ms  med=203.94ms max=7.41s p(90)=430.39ms p(95)=598.22ms
 aws_obj_put_success....: 1258221 2090.230967/s
 data_received..........: 0 B     0 B/s
 data_sent..............: 165 GB  274 MB/s
 iteration_duration.....: avg=286.21ms min=295.75µs med=213.57ms max=7.43s p(90)=439.8ms  p(95)=607.9ms 
 iterations.............: 1258221 2090.230967/s
 vus....................: 19      min=19        max=600
```

running (10m02.0s), 000/600 VUs, 1258221 complete and 0 interrupted iterations  
write ✓ [======================================] 600 VUs 10m0s

YCRPeDS6Sjuyj4ppmDdx3L3