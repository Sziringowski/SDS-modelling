protection=2REP
HW_chassis=VEGMAN
SSD=4
HDD=12


### 8 nodes 8kb write
INFO[14:04:18] Load started at:               Wed Nov 27 2024 14:04:18 GMT+0000 (UTC)  source=console
INFO[14:14:18] Load finished at:              Wed Nov 27 2024 14:14:18 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 34 GB   57 MB/s
     aws_obj_put_duration...: avg=167.84ms min=31.06ms  med=146.46ms max=1.86s p(90)=267.63ms p(95)=320.53ms
     aws_obj_put_success....: 4203625 7003.309872/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 34 GB   57 MB/s
     iteration_duration.....: avg=176.97ms min=225.15µs med=155.28ms max=1.87s p(90)=277.34ms p(95)=330ms   
     iterations.............: 4203625 7003.309872/s
     vus....................: 1240    min=1240      max=1240
ERRO[14:14:19] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.2s), 0000/1240 VUs, 4203625 complete and 0 interrupted iterations
write ✓ [======================================] 1240 VUs  10m0s

### 8 nodes 8kb read
INFO[14:24:20] Load started at:               Wed Nov 27 2024 14:24:20 GMT+0000 (UTC)  source=console
INFO[14:25:20] Load finished at:              Wed Nov 27 2024 14:25:20 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 4.9 GB 81 MB/s
     aws_obj_get_duration...: avg=125.29ms min=14.46ms  med=111.2ms  max=1.36s p(90)=193.1ms  p(95)=233.44ms
     aws_obj_get_success....: 593067 9860.143373/s
     data_received..........: 4.8 GB 81 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=125.37ms min=424.62µs med=111.28ms max=1.36s p(90)=193.17ms p(95)=233.53ms
     iterations.............: 593067 9860.143373/s
     vus....................: 1240   min=1240      max=1240
ERRO[14:25:20] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (1m00.1s), 0000/1240 VUs, 593067 complete and 0 interrupted iterations
read ✓ [======================================] 1240 VUs  1m0s

### 8 nodes 128kb write
INFO[17:05:42] Load started at:               Wed Nov 27 2024 17:05:42 GMT+0000 (UTC)  source=console
INFO[17:15:44] Load finished at:              Wed Nov 27 2024 17:15:44 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 12 GB 20 MB/s
     aws_obj_put_duration...: avg=4.73s min=19.24ms med=57.28ms max=9m57s p(90)=185.17ms p(95)=270.58ms
     aws_obj_put_fails......: 627   1.03633/s
     aws_obj_put_success....: 90301 149.253063/s
     data_received..........: 0 B   0 B/s
     data_sent..............: 12 GB 20 MB/s
     iteration_duration.....: avg=5.12s min=222.2µs med=67.2ms  max=9m57s p(90)=203.59ms p(95)=314.25ms
     iterations.............: 90928 150.289393/s
     vus....................: 942   min=942      max=1200
ERRO[17:15:44] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m05.0s), 0000/1200 VUs, 90928 complete and 933 interrupted iterations
write ✓ [======================================] 1200 VUs  10m0s

### 8 nodes 128kb read
INFO[17:20:42] Load started at:               Wed Nov 27 2024 17:20:42 GMT+0000 (UTC)  source=console
INFO[17:30:42] Load finished at:              Wed Nov 27 2024 17:30:42 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.0 TB  1.7 GB/s
     aws_obj_get_duration...: avg=93.12ms min=8.49ms   med=90.52ms max=535.35ms p(90)=136.14ms p(95)=150.67ms
     aws_obj_get_success....: 7723748 12870.276434/s
     data_received..........: 1.0 TB  1.7 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=93.2ms  min=226.55µs med=90.59ms max=535.42ms p(90)=136.22ms p(95)=150.75ms
     iterations.............: 7723748 12870.276434/s
     vus....................: 1200    min=1200       max=1200
ERRO[17:30:44] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.1s), 0000/1200 VUs, 7723748 complete and 0 interrupted iterations
read ✓ [======================================] 1200 VUs  10m0s

### 8 nodes 1mib write
INFO[12:12:37] Load started at:               Fri Dec 06 2024 12:12:37 GMT+0000 (UTC)  source=console
INFO[12:22:41] Load finished at:              Fri Dec 06 2024 12:22:41 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 66 GB 109 MB/s
     aws_obj_put_duration...: avg=1.98s min=45.24ms  med=88.05ms  max=8m6s p(90)=294.54ms p(95)=469.26ms
     aws_obj_put_fails......: 511   0.844598/s
     aws_obj_put_success....: 62922 103.999646/s
     data_received..........: 0 B   0 B/s
     data_sent..............: 66 GB 109 MB/s
     iteration_duration.....: avg=2.39s min=181.56µs med=104.99ms max=8m6s p(90)=323.87ms p(95)=571.71ms
     iterations.............: 63433 104.844245/s
     vus....................: 787   min=787      max=800
ERRO[12:22:41] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m05.0s), 000/800 VUs, 63433 complete and 786 interrupted iterations
write ✓ [======================================] 800 VUs  10m0s

### 8 nodes 1mib read
INFO[15:45:49] Load started at:               Wed Nov 27 2024 15:45:49 GMT+0000 (UTC)  source=console
INFO[15:55:52] Load finished at:              Wed Nov 27 2024 15:55:52 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 3.1 TB  5.2 GB/s
     aws_obj_get_duration...: avg=160.29ms min=14.97ms med=154.35ms max=594.88ms p(90)=234.34ms p(95)=260.34ms
     aws_obj_get_fails......: 2111    3.517165/s
     aws_obj_get_success....: 2992190 4985.327007/s
     data_received..........: 3.1 TB  5.2 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=160.3ms  min=266µs   med=154.38ms max=594.95ms p(90)=234.39ms p(95)=260.38ms
     iterations.............: 2994301 4988.844172/s
     vus....................: 800     min=800       max=800
ERRO[15:55:53] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.2s), 000/800 VUs, 2994301 complete and 0 interrupted iterations
read ✓ [======================================] 800 VUs  10m0s

 "couldn't add new verion to tree service: unhealthy endpoint: '192.168.201.107:8080'"

### 8 nodes 128mib write
INFO[08:09:48] Load started at:               Mon Dec 09 2024 08:09:48 GMT+0000 (UTC)  source=console
INFO[08:19:50] Load finished at:              Mon Dec 09 2024 08:19:50 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.9 TB 3.1 GB/s
     aws_obj_put_duration...: avg=13.28s min=5.48s    med=13.16s max=23.07s p(90)=17.77s p(95)=18.72s
     aws_obj_put_success....: 14023  23.154224/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.9 TB 3.1 GB/s
     iteration_duration.....: avg=13.66s min=234.77µs med=13.53s max=24.89s p(90)=18.14s p(95)=19.11s
     iterations.............: 14015  23.141015/s
     vus....................: 191    min=0       max=320
ERRO[08:19:50] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m05.6s), 000/320 VUs, 14015 complete and 184 interrupted iterations
write ✓ [======================================] 320 VUs  10m0s

### 8 nodes 128mib read
INFO[08:30:48] Load started at:               Mon Dec 09 2024 08:30:48 GMT+0000 (UTC)  source=console
INFO[08:40:53] Load finished at:              Mon Dec 09 2024 08:40:53 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 3.4 TB 5.6 GB/s
     aws_obj_get_duration...: avg=7.68s min=3.22s    med=7.46s max=14.34s p(90)=9.65s p(95)=10.29s
     aws_obj_get_success....: 25097  41.50219/s
     data_received..........: 3.4 TB 5.6 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=7.68s min=378.72µs med=7.46s max=14.34s p(90)=9.65s p(95)=10.29s
     iterations.............: 25097  41.50219/s
     vus....................: 69     min=69     max=320
ERRO[08:40:53] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m04.7s), 000/320 VUs, 25097 complete and 0 interrupted iterations
read ✓ [======================================] 320 VUs  10m0s

### 7 nodes 8kb write
INFO[11:49:25] Load started at:               Fri Nov 29 2024 11:49:25 GMT+0000 (UTC)  source=console
INFO[11:59:25] Load finished at:              Fri Nov 29 2024 11:59:25 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 35 GB   59 MB/s
     aws_obj_put_duration...: avg=141.96ms min=30.82ms  med=126.69ms max=1.75s p(90)=207.78ms p(95)=244.12ms
     aws_obj_put_success....: 4311105 7182.942891/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 35 GB   59 MB/s
     iteration_duration.....: avg=150.98ms min=197.29µs med=134.59ms max=1.76s p(90)=216.66ms p(95)=254.11ms
     iterations.............: 4311105 7182.942891/s
     vus....................: 1085    min=1085      max=1085
ERRO[11:59:26] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.2s), 0000/1085 VUs, 4311105 complete and 0 interrupted iterations
write ✓ [======================================] 1085 VUs  10m0s

### 7 nodes 8kb read
INFO[14:53:33 ] Load started at:               Wed Dec 04 2024 14:53:33 GMT+0000 (UTC)  source=console
INFO[15:03:37] Load finished at:              Wed Dec 04 2024 15:03:37 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 73 GB   121 MB/s
     aws_obj_get_duration...: avg=73.21ms min=5.31ms   med=56.51ms max=3.66s p(90)=140.58ms p(95)=183.8ms 
     aws_obj_get_fails......: 425     0.708037/s
     aws_obj_get_success....: 8881440 14796.217575/s
     data_received..........: 73 GB   121 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=73.27ms min=211.19µs med=56.58ms max=3.66s p(90)=140.65ms p(95)=183.87ms
     iterations.............: 8881865 14796.925613/s
     vus....................: 1085    min=1085       max=1085
     vus_max................: 1085    min=1085  ERRO[15:03:39] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.3s), 0000/1085 VUs, 8881865 complete and 0 interrupted iterations
read ✓ [======================] 1085 VUs  10m0s


### 7 nodes 128kb write
INFO[10:55:16] Load started at:               Thu Dec 05 2024 10:55:16 GMT+0000 (UTC)  source=console
INFO[11:05:20] Load finished at:              Thu Dec 05 2024 11:05:20 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 7.4 GB 24 MB/s
     aws_obj_put_duration...: avg=1.52s min=22.86ms  med=99.57ms  max=4m31s p(90)=240.9ms  p(95)=317.27ms
     aws_obj_put_fails......: 439    1.439265/s
     aws_obj_put_success....: 56132  184.029227/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 7.3 GB 24 MB/s
     iteration_duration.....: avg=1.98s min=222.75µs med=112.25ms max=4m31s p(90)=259.15ms p(95)=351.6ms 
     iterations.............: 56571  185.468492/s
     vus....................: 795    min=795      max=800
ERRO[11:05:20] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (5m05.0s), 000/800 VUs, 56571 complete and 794 interrupted iterations
write ✓ [======================================] 800 VUs  5m0s

### 7 nodes 128kb read
INFO[11:27:25] Load started at:               Thu Dec 05 2024 11:27:25 GMT+0000 (UTC)  source=console
INFO[11:37:25] Load finished at:              Thu Dec 05 2024 11:37:25 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 923 GB  1.5 GB/s
     aws_obj_get_duration...: avg=68.11ms min=5.13ms   med=63.26ms max=365.09ms p(90)=112.57ms p(95)=129.04ms
     aws_obj_get_success....: 7037867 11728.06771/s
     data_received..........: 921 GB  1.5 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=68.18ms min=197.58µs med=63.34ms max=365.16ms p(90)=112.65ms p(95)=129.12ms
     iterations.............: 7037867 11728.06771/s
     vus....................: 800     min=800       max=800
ERRO[11:37:26] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.1s), 000/800 VUs, 7037867 complete and 0 interrupted iterations
read ✓ [======================================] 800 VUs  10m0s

### 7 nodes 1mib write
INFO[15:12:17] Load started at:               Thu Nov 28 2024 15:12:17 GMT+0000 (UTC)  source=console
INFO[15:22:20] Load finished at:              Thu Nov 28 2024 15:22:20 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 65 GB 108 MB/s
     aws_obj_put_duration...: avg=2.98s min=43.68ms  med=150.62ms max=8m38s p(90)=464.69ms p(95)=680.16ms
     aws_obj_put_fails......: 546   0.902451/s
     aws_obj_put_success....: 62004 102.482756/s
     data_received..........: 0 B   0 B/s
     data_sent..............: 65 GB 107 MB/s
     iteration_duration.....: avg=3.49s min=225.08µs med=168.26ms max=8m38s p(90)=502.71ms p(95)=763.82ms
     iterations.............: 62550 103.385207/s
     vus....................: 700   min=700      max=700
ERRO[15:22:20] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m05.0s), 000/700 VUs, 62550 complete and 700 interrupted iterations
write ✓ [======================================] 700 VUs  10m0s

### 7 nodes 1mib read
INFO[11:39:18] Load started at:               Mon Dec 09 2024 11:39:18 GMT+0000 (UTC)  source=console
INFO[11:44:18] Load finished at:              Mon Dec 09 2024 11:44:18 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.3 TB  4.5 GB/s
     aws_obj_get_duration...: avg=93.23ms min=12.93ms  med=88.79ms max=1.22s p(90)=140.38ms p(95)=157.42ms
     aws_obj_get_success....: 1285930 4284.828437/s
     data_received..........: 1.3 TB  4.5 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=93.31ms min=369.31µs med=88.86ms max=1.22s p(90)=140.46ms p(95)=157.49ms
     iterations.............: 1285930 4284.828437/s
     vus....................: 400     min=400       max=400
ERRO[11:44:18] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (5m00.1s), 000/400 VUs, 1285930 complete and 0 interrupted iterations
read ✓ [======================================] 400 VUs  5m0s

### 7 nodes 128mib write
INFO[12:37:54] Load started at:               Thu Dec 05 2024 12:37:54 GMT+0000 (UTC)  source=console
INFO[12:47:56] Load finished at:              Thu Dec 05 2024 12:47:56 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.6 TB 2.7 GB/s
     aws_obj_put_duration...: avg=9.96s  min=3.68s    med=9.01s max=1m9s  p(90)=14.02s p(95)=16.95s
     aws_obj_put_fails......: 4      0.006606/s
     aws_obj_put_success....: 12205  20.155648/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.6 TB 2.7 GB/s
     iteration_duration.....: avg=10.32s min=220.19µs med=9.38s max=1m10s p(90)=14.38s p(95)=17.32s
     iterations.............: 12202  20.150693/s
     vus....................: 97     min=0       max=210
ERRO[12:47:56] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m05.5s), 000/210 VUs, 12202 complete and 87 interrupted iterations
write ✓ [======================================] 210 VUs  10m0s

### 7 nodes 128mib read
INFO[12:04:28] Load started at:               Mon Dec 09 2024 12:04:28 GMT+0000 (UTC)  source=console
INFO[12:09:31] Load finished at:              Mon Dec 09 2024 12:09:31 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.6 TB 5.3 GB/s
     aws_obj_get_duration...: avg=3.01s min=1.21s    med=2.9s max=9.11s p(90)=4.12s p(95)=4.51s
     aws_obj_get_success....: 12012  39.63584/s
     data_received..........: 1.6 TB 5.3 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=3s    min=269.62µs med=2.9s max=9.11s p(90)=4.12s p(95)=4.51s
     iterations.............: 12012  39.63584/s
     vus....................: 1      min=1      max=120
ERRO[12:09:31] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (5m03.1s), 000/120 VUs, 12012 complete and 0 interrupted iterations
read ✓ [======================================] 120 VUs  5m0s

### 6 nodes 8kb write
INFO[15:13:16] Load started at:               Fri Nov 29 2024 15:13:16 GMT+0000 (UTC)  source=console
INFO[15:23:17] Load started at:               Fri Nov 29 2024 15:23:17 GMT+0000 (UTC)  source=console

running (00m03.1s), 930/930 VUs, 17915INFO[15:33:18] Load finished at:              Fri Nov 29 2024 15:33:18 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 29 GB   49 MB/s
     aws_obj_put_duration...: avg=147.25ms min=28.45ms  med=127.95ms max=2.16s p(90)=223.56ms p(95)=267.62ms
     aws_obj_put_success....: 3572949 5953.366082/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 29 GB   49 MB/s
     iteration_duration.....: avg=156.15ms min=245.65µs med=135.61ms max=2.18s p(90)=231.89ms p(95)=277.27ms
     iterations.............: 3572949 5953.366082/s
     vus....................: 930     min=930       max=930
     vus_max................: 930     ERRO[15:33:18] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.2s), 000/930 VUs, 3572949 complete and 0 interrupted iterations
write ✓ [============] 930 VUs  10m0s

### 6 nodes 8kb read
INFO[16:13:05] Load started at:               Fri Nov 29 2024 16:13:05 GMT+0000 (UTC)  source=console
INFO[16:23:06] Load finished at:              Fri Nov 29 2024 16:23:06 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 63 GB   106 MB/s
     aws_obj_get_duration...: avg=71.98ms min=4.79ms   med=57.96ms max=1.7s p(90)=132.46ms p(95)=179.58ms
     aws_obj_get_fails......: 14      0.023323/s
     aws_obj_get_success....: 7742579 12898.704881/s
     data_received..........: 63 GB   106 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=72.05ms min=279.94µs med=58.03ms max=1.7s p(90)=132.53ms p(95)=179.65ms
     iterations.............: 7742593 12898.728204/s
     vus....................: 930     min=930        max=930
     vus_max................: 930     ERRO[16:23:08] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.3s), 000/930 VUs, 7742593 complete and 0 interrupted iterations
read ✓ [=============] 930 VUs  10m0s

### 6 nodes 128kb write
INFO[12:32:18] Load started at:               Mon Dec 09 2024 12:32:18 GMT+0000 (UTC)  source=console
INFO[12:42:18] Load finished at:              Mon Dec 09 2024 12:42:18 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 269 GB  448 MB/s
     aws_obj_put_duration...: avg=253.21ms min=17.51ms  med=216.65ms max=2.98s p(90)=455.81ms p(95)=554.79ms
     aws_obj_put_success....: 2053144 3417.896951/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 269 GB  447 MB/s
     iteration_duration.....: avg=263.05ms min=191.56µs med=226.8ms  max=2.98s p(90)=465.75ms p(95)=564.56ms
     iterations.............: 2053144 3417.896951/s
     vus....................: 900     min=900       max=900
ERRO[12:42:19] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.7s), 000/900 VUs, 2053144 complete and 0 interrupted iterations
write ✓ [======================================] 900 VUs  10m0s

### 6 nodes 128kb read
INFO[12:51:54] Load started at:               Mon Dec 09 2024 12:51:54 GMT+0000 (UTC)  source=console
INFO[13:01:56] Load finished at:              Mon Dec 09 2024 13:01:56 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 630 GB  1.0 GB/s
     aws_obj_get_duration...: avg=112.21ms min=6.42ms med=83.78ms max=1.8s p(90)=219.19ms p(95)=280.1ms 
     aws_obj_get_fails......: 91      0.151615/s
     aws_obj_get_success....: 4808065 8010.686558/s
     data_received..........: 630 GB  1.0 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=112.29ms min=2.25ms med=83.86ms max=1.8s p(90)=219.27ms p(95)=280.17ms
     iterations.............: 4808156 8010.838173/s
     vus....................: 900     min=900       max=900
ERRO[13:01:57] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.2s), 000/900 VUs, 4808156 complete and 0 interrupted iterations
read ✓ [======================================] 900 VUs  10m0s

### 6 nodes 1mib write
INFO[14:27:04] Load started at:               Mon Dec 09 2024 14:27:04 GMT+0000 (UTC)  source=console
INFO[14:37:05] Load finished at:              Mon Dec 09 2024 14:37:05 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 848 GB 1.4 GB/s
     aws_obj_put_duration...: avg=429.39ms min=45.96ms  med=392.38ms max=2.13s p(90)=700.63ms p(95)=809.55ms
     aws_obj_put_success....: 808843 1346.68494/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 847 GB 1.4 GB/s
     iteration_duration.....: avg=445.19ms min=322.76µs med=408.29ms max=2.14s p(90)=716.72ms p(95)=825.75ms
     iterations.............: 808843 1346.68494/s
     vus....................: 600    min=600      max=600
ERRO[14:37:05] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.6s), 000/600 VUs, 808843 complete and 0 interrupted iterations
write ✓ [======================================] 600 VUs  10m0s

### 6 nodes 1mib read
INFO[14:50:08] Load started at:               Mon Dec 09 2024 14:50:08 GMT+0000 (UTC)  source=console
INFO[15:00:08] Load finished at:              Mon Dec 09 2024 15:00:08 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 2.0 TB  3.3 GB/s
     aws_obj_get_duration...: avg=190.12ms min=19.56ms  med=154.32ms max=1.31s p(90)=340.27ms p(95)=501.86ms
     aws_obj_get_success....: 1892955 3152.727498/s
     data_received..........: 2.0 TB  3.3 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=190.19ms min=325.26µs med=154.39ms max=1.31s p(90)=340.36ms p(95)=501.94ms
     iterations.............: 1892955 3152.727498/s
     vus....................: 600     min=600       max=600
ERRO[15:00:09] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.4s), 000/600 VUs, 1892955 complete and 0 interrupted iterations
read ✓ [======================================] 600 VUs  10m0s

### 6 nodes 128mib write
INFO[15:12:15] Load started at:               Mon Dec 09 2024 15:12:15 GMT+0000 (UTC)  source=console
INFO[15:22:16] Load finished at:              Mon Dec 09 2024 15:22:16 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.1 TB 1.9 GB/s
     aws_obj_put_duration...: avg=12.35s min=3.34s    med=10.05s max=1m23s p(90)=20.65s p(95)=26.56s
     aws_obj_put_fails......: 15     0.024772/s
     aws_obj_put_success....: 8392   13.858888/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.1 TB 1.9 GB/s
     iteration_duration.....: avg=12.79s min=220.89µs med=10.42s max=1m24s p(90)=21.06s p(95)=27.28s
     iterations.............: 8392   13.858888/s
     vus....................: 9      min=0       max=180
ERRO[15:22:16] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m05.5s), 000/180 VUs, 8392 complete and 84 interrupted iterations
write ✓ [======================================] 180 VUs  10m0s

### 6 nodes 128mib read
INFO[15:30:51] Load started at:               Mon Dec 09 2024 15:30:51 GMT+0000 (UTC)  source=console
INFO[15:41:01] Load finished at:              Mon Dec 09 2024 15:41:01 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 3.1 TB 5.1 GB/s
     aws_obj_get_duration...: avg=4.62s min=1.25s    med=3.36s max=1m10s p(90)=5.78s p(95)=8.01s
     aws_obj_get_success....: 23204  38.054408/s
     data_received..........: 3.1 TB 5.1 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=4.61s min=382.28µs med=3.36s max=1m10s p(90)=5.78s p(95)=8.01s
     iterations.............: 23204  38.054408/s
     vus....................: 9      min=9       max=180
ERRO[15:41:01] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m09.8s), 000/180 VUs, 23204 complete and 59 interrupted iterations
read ✓ [======================================] 180 VUs  10m0s

### 5 nodes 8kb write
INFO[07:29:52] Load started at:               Tue Dec 10 2024 07:29:52 GMT+0000 (UTC)  source=console
INFO[07:39:52] Load finished at:              Tue Dec 10 2024 07:39:52 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 25 GB   41 MB/s
     aws_obj_put_duration...: avg=145.77ms min=33ms    med=127.95ms max=2.19s p(90)=217.98ms p(95)=256.98ms
     aws_obj_put_success....: 3008731 5013.444646/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 25 GB   41 MB/s
     iteration_duration.....: avg=154.53ms min=962.9µs med=136.04ms max=2.2s  p(90)=227.51ms p(95)=265.57ms
     iterations.............: 3008731 5013.444646/s
     vus....................: 775     min=775       max=775
ERRO[07:39:53] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.1s), 000/775 VUs, 3008731 complete and 0 interrupted iterations
write ✓ [======================================] 775 VUs  10m0s

### 5 nodes 8kb read
INFO[07:44:19] Load started at:               Tue Dec 10 2024 07:44:19 GMT+0000 (UTC)  source=console
INFO[07:54:19] Load finished at:              Tue Dec 10 2024 07:54:19 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 33 GB   55 MB/s
     aws_obj_get_duration...: avg=116.28ms min=5.21ms   med=74.76ms max=3.11s p(90)=270.24ms p(95)=366.43ms
     aws_obj_get_success....: 3996111 6657.23101/s
     data_received..........: 33 GB   55 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=116.35ms min=240.74µs med=74.83ms max=3.11s p(90)=270.31ms p(95)=366.5ms 
     iterations.............: 3996111 6657.23101/s
     vus....................: 775     min=775      max=775
ERRO[07:54:20] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.3s), 000/775 VUs, 3996111 complete and 0 interrupted iterations
read ✓ [======================================] 775 VUs  10m0s

### 5 nodes 128kb write
INFO[08:12:58] Load started at:               Tue Dec 10 2024 08:12:58 GMT+0000 (UTC)  source=console
INFO[08:22:59] Load finished at:              Tue Dec 10 2024 08:22:59 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 197 GB  328 MB/s
     aws_obj_put_duration...: avg=289ms   min=25.39ms med=260.5ms  max=2.01s p(90)=492.59ms p(95)=583.64ms
     aws_obj_put_success....: 1505946 2505.783242/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 197 GB  327 MB/s
     iteration_duration.....: avg=298.9ms min=3.46ms  med=270.37ms max=2.01s p(90)=502.52ms p(95)=593.62ms
     iterations.............: 1505946 2505.783242/s
     vus....................: 24      min=24        max=750
ERRO[08:22:59] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m01.0s), 000/750 VUs, 1505946 complete and 0 interrupted iterations
write ✓ [======================================] 750 VUs  10m0s

### 5 nodes 128kb read
INFO[08:30:43] Load started at:               Tue Dec 10 2024 08:30:43 GMT+0000 (UTC)  source=console
INFO[08:40:43] Load finished at:              Tue Dec 10 2024 08:40:43 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 521 GB  867 MB/s
     aws_obj_get_duration...: avg=113.2ms  min=6.3ms    med=87.72ms max=1.19s p(90)=216.93ms p(95)=276.27ms
     aws_obj_get_success....: 3971941 6617.366396/s
     data_received..........: 520 GB  867 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=113.28ms min=353.94µs med=87.79ms max=1.19s p(90)=217ms    p(95)=276.34ms
     iterations.............: 3971941 6617.366396/s
     vus....................: 750     min=750       max=750
ERRO[08:40:44] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.2s), 000/750 VUs, 3971941 complete and 0 interrupted iterations
read ✓ [======================================] 750 VUs  10m0s

### 5 nodes 1mib write
INFO[08:54:50] Load started at:               Tue Dec 10 2024 08:54:50 GMT+0000 (UTC)  source=console
INFO[09:04:50] Load finished at:              Tue Dec 10 2024 09:04:50 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 655 GB 1.1 GB/s
     aws_obj_put_duration...: avg=464.63ms min=52.12ms  med=435.45ms max=1.98s p(90)=733.28ms p(95)=838.28ms
     aws_obj_put_success....: 624225 1039.589058/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 654 GB 1.1 GB/s
     iteration_duration.....: avg=480.66ms min=371.02µs med=451.5ms  max=2s    p(90)=749.45ms p(95)=854.48ms
     iterations.............: 624225 1039.589058/s
     vus....................: 500    min=500       max=500
ERRO[09:04:50] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.5s), 000/500 VUs, 624225 complete and 0 interrupted iterations
write ✓ [======================================] 500 VUs  10m0s

### 5 nodes 1mib read
INFO[09:40:01] Load started at:               Tue Dec 10 2024 09:40:01 GMT+0000 (UTC)  source=console
INFO[09:50:01] Load finished at:              Tue Dec 10 2024 09:50:01 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.7 TB  2.8 GB/s
     aws_obj_get_duration...: avg=188.63ms min=15.92ms  med=157.6ms  max=1.18s p(90)=342.18ms p(95)=437.78ms
     aws_obj_get_success....: 1590136 2647.955742/s
     data_received..........: 1.7 TB  2.8 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=188.71ms min=289.92µs med=157.68ms max=1.18s p(90)=342.25ms p(95)=437.86ms
     iterations.............: 1590136 2647.955742/s
     vus....................: 500     min=500       max=500
ERRO[09:50:02] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.5s), 000/500 VUs, 1590136 complete and 0 interrupted iterations
read ✓ [======================================] 500 VUs  10m0s

### 5 nodes 128mib write
INFO[10:09:43] Load started at:               Tue Dec 10 2024 10:09:43 GMT+0000 (UTC)  source=console
INFO[10:19:48] Load finished at:              Tue Dec 10 2024 10:19:48 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.2 TB 1.9 GB/s
     aws_obj_put_duration...: avg=10.15s min=4.07s    med=9.19s max=44.93s p(90)=14.75s p(95)=17.24s
     aws_obj_put_success....: 8586   14.179575/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.2 TB 1.9 GB/s
     iteration_duration.....: avg=10.51s min=207.39µs med=9.55s max=45.28s p(90)=15.1s  p(95)=17.59s
     iterations.............: 8582   14.172969/s
     vus....................: 0      min=0       max=150
ERRO[10:19:49] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m05.5s), 000/150 VUs, 8582 complete and 36 interrupted iterations
write ✓ [======================================] 150 VUs  10m0s

### 5 nodes 128mib read
INFO[10:31:54] Load started at:               Tue Dec 10 2024 10:31:54 GMT+0000 (UTC)  source=console
INFO[10:41:57] Load finished at:              Tue Dec 10 2024 10:41:57 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 2.7 TB 4.5 GB/s
     aws_obj_get_duration...: avg=4.42s min=1.22s    med=3.96s max=18.02s p(90)=6.96s p(95)=8.32s
     aws_obj_get_success....: 20397  33.804264/s
     data_received..........: 2.7 TB 4.5 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=4.42s min=371.49µs med=3.96s max=18.02s p(90)=6.96s p(95)=8.32s
     iterations.............: 20397  33.804264/s
     vus....................: 9      min=9       max=150
ERRO[10:41:57] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m03.4s), 000/150 VUs, 20397 complete and 0 interrupted iterations
read ✓ [======================================] 150 VUs  10m0s

### 4 nodes 8kb write
INFO[11:09:52] Load started at:               Tue Dec 10 2024 11:09:52 GMT+0000 (UTC)  source=console
INFO[11:19:53] Load finished at:              Tue Dec 10 2024 11:19:53 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 20 GB   33 MB/s
     aws_obj_put_duration...: avg=143.62ms min=29.29ms  med=123.07ms max=1.6s p(90)=220.5ms  p(95)=267.85ms
     aws_obj_put_success....: 2442159 4068.317338/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 20 GB   33 MB/s
     iteration_duration.....: avg=152.32ms min=196.53µs med=132.14ms max=1.6s p(90)=229.59ms p(95)=276.49ms
     iterations.............: 2442159 4068.317338/s
     vus....................: 620     min=620       max=620
ERRO[11:19:53] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.3s), 000/620 VUs, 2442159 complete and 0 interrupted iterations
write ✓ [======================================] 620 VUs  10m0s

### 4 nodes 8kb read
INFO[11:24:50] Load started at:               Tue Dec 10 2024 11:24:50 GMT+0000 (UTC)  source=console
INFO[11:34:50] Load finished at:              Tue Dec 10 2024 11:34:50 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 39 GB   65 MB/s
     aws_obj_get_duration...: avg=78.54ms min=5.47ms   med=65.07ms max=1.38s p(90)=143.27ms p(95)=181.81ms
     aws_obj_get_success....: 4730822 7881.986505/s
     data_received..........: 39 GB   65 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=78.61ms min=243.04µs med=65.14ms max=1.39s p(90)=143.34ms p(95)=181.89ms
     iterations.............: 4730822 7881.986505/s
     vus....................: 620     min=620       max=620
ERRO[11:34:51] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.2s), 000/620 VUs, 4730822 complete and 0 interrupted iterations
read ✓ [======================================] 620 VUs  10m0s

### 4 nodes 128kb write
INFO[11:46:02] Load started at:               Tue Dec 10 2024 11:46:02 GMT+0000 (UTC)  source=console
INFO[11:56:03] Load finished at:              Tue Dec 10 2024 11:56:03 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 163 GB  271 MB/s
     aws_obj_put_duration...: avg=280.05ms min=22.09ms  med=252.48ms max=2.34s p(90)=485.21ms p(95)=573.79ms
     aws_obj_put_success....: 1242470 2069.574326/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 162 GB  270 MB/s
     iteration_duration.....: avg=289.77ms min=184.43µs med=262.17ms max=2.35s p(90)=495.06ms p(95)=583.66ms
     iterations.............: 1242470 2069.574326/s
     vus....................: 600     min=600       max=600
ERRO[11:56:03] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.4s), 000/600 VUs, 1242470 complete and 0 interrupted iterations
write ✓ [======================================] 600 VUs  10m0s

### 4 nodes 128kb read 
INFO[12:11:03] Load started at:               Tue Dec 10 2024 12:11:03 GMT+0000 (UTC)  source=console
INFO[12:21:03] Load finished at:              Tue Dec 10 2024 12:21:03 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 487 GB  812 MB/s
     aws_obj_get_duration...: avg=96.73ms min=6ms      med=77.54ms max=1.26s p(90)=177.46ms p(95)=225.07ms
     aws_obj_get_success....: 3718200 6195.30089/s
     data_received..........: 487 GB  811 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=96.8ms  min=257.39µs med=77.62ms max=1.26s p(90)=177.54ms p(95)=225.15ms
     iterations.............: 3718200 6195.30089/s
     vus....................: 600     min=600      max=600
ERRO[12:21:04] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.2s), 000/600 VUs, 3718200 complete and 0 interrupted iterations
read ✓ [======================================] 600 VUs  10m0s

### 4 nodes 1mib write
INFO[12:42:01] Load started at:               Tue Dec 10 2024 12:42:01 GMT+0000 (UTC)  source=console
INFO[12:52:01] Load finished at:              Tue Dec 10 2024 12:52:01 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 475 GB 790 MB/s
     aws_obj_put_duration...: avg=513.83ms min=40.61ms  med=432.78ms max=12.39s p(90)=740.19ms p(95)=860.46ms
     aws_obj_put_success....: 452742 753.797113/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 474 GB 789 MB/s
     iteration_duration.....: avg=530.27ms min=274.67µs med=449.4ms  max=12.41s p(90)=756.76ms p(95)=877.61ms
     iterations.............: 452742 753.797113/s
     vus....................: 400    min=400      max=400
ERRO[12:52:01] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.6s), 000/400 VUs, 452742 complete and 0 interrupted iterations
write ✓ [======================================] 400 VUs  10m0s

### 4 nodes 1mib read
INFO[13:12:43] Load started at:               Tue Dec 10 2024 13:12:43 GMT+0000 (UTC)  source=console
INFO[13:22:46] Load finished at:              Tue Dec 10 2024 13:22:46 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.5 TB  2.5 GB/s
     aws_obj_get_duration...: avg=166.97ms min=18.47ms med=138.17ms max=1.08s p(90)=304.46ms p(95)=405.03ms
     aws_obj_get_fails......: 38      0.063305/s
     aws_obj_get_success....: 1436640 2393.310289/s
     data_received..........: 1.5 TB  2.5 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=167.05ms min=341.8µs med=138.25ms max=1.08s p(90)=304.54ms p(95)=405.11ms
     iterations.............: 1436678 2393.373593/s
     vus....................: 400     min=400       max=400
ERRO[13:22:47] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.3s), 000/400 VUs, 1436678 complete and 0 interrupted iterations
read ✓ [======================================] 400 VUs  10m0s

### 4 nodes 128mib write
INFO[14:04:56] Load started at:               Tue Dec 10 2024 14:04:56 GMT+0000 (UTC)  source=console
INFO[14:15:01] Load finished at:              Tue Dec 10 2024 14:15:01 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 895 GB 1.5 GB/s
     aws_obj_put_duration...: avg=10.47s min=3.76s    med=8.74s max=40.42s p(90)=17.98s p(95)=22.28s
     aws_obj_put_success....: 6669   11.011026/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 895 GB 1.5 GB/s
     iteration_duration.....: avg=10.83s min=179.36µs med=9.1s  max=40.77s p(90)=18.39s p(95)=22.68s
     iterations.............: 6656   10.989563/s
     vus....................: 49     min=0       max=120
ERRO[14:15:01] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m05.7s), 000/120 VUs, 6656 complete and 42 interrupted iterations
write ✓ [======================================] 120 VUs  10m0s

### 4 nodes 128mib read
INFO[14:28:01] Load started at:               Tue Dec 10 2024 14:28:01 GMT+0000 (UTC)  source=console
INFO[14:38:05] Load finished at:              Tue Dec 10 2024 14:38:05 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 2.2 TB 3.7 GB/s
     aws_obj_get_duration...: avg=4.35s min=1.18s    med=3.47s max=25.72s p(90)=7.66s p(95)=10.46s
     aws_obj_get_success....: 16580  27.444042/s
     data_received..........: 2.2 TB 3.7 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=4.35s min=363.22µs med=3.47s max=25.72s p(90)=7.66s p(95)=10.46s
     iterations.............: 16580  27.444042/s
     vus....................: 3      min=3       max=120
ERRO[14:38:05] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m04.1s), 000/120 VUs, 16580 complete and 0 interrupted iterations
read ✓ [======================================] 120 VUs  10m0s


