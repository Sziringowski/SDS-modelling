protection=2REP
HW_chassis=VEGMAN
SSD=2
HDD=12

### 4 nodes 1mib read
INFO[10:07:45] Load started at:               Fri Feb 28 2025 10:07:45 GMT+0000 (UTC)  source=console
INFO[10:17:45] Load finished at:              Fri Feb 28 2025 10:17:45 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.8 TB  3.0 GB/s
     aws_obj_get_duration...: avg=141.6ms  min=16.34ms med=128.26ms max=1.65s p(90)=232.24ms p(95)=268.22ms
     aws_obj_get_success....: 1693689 2821.695978/s
     data_received..........: 1.8 TB  3.0 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=141.69ms min=416.1µs med=128.36ms max=1.65s p(90)=232.33ms p(95)=268.32ms
     iterations.............: 1693689 2821.695978/s
     vus....................: 400     min=400       max=400
     vus_max................: 400     min=400       max=400
running (10m00.2s), 000/400 VUs, 1693689 complete and 0 interrupted iterations
read ✓ [==============] 400 VUs  10m0s

### 6 nodes 1mib read
INFO[20:07:07] Load started at:               Thu Feb 27 2025 20:07:07 GMT+0000 (UTC)  source=console
INFO[20:17:08] Load finished at:              Thu Feb 27 2025 20:17:08 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 2.4 TB  4.0 GB/s
     aws_obj_get_duration...: avg=158.67ms min=16.26ms  med=145.69ms max=3.09s p(90)=247.82ms p(95)=298.49ms
     aws_obj_get_success....: 2267583 3772.616767/s
     data_received..........: 2.4 TB  4.0 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=158.76ms min=409.17µs med=145.78ms max=3.09s p(90)=247.92ms p(95)=298.58ms
     iterations.............: 2267583 3772.616767/s
     vus....................: 1       min=1         max=600
     vus_max................: 600     min=600       max=600
running (10m01.1s), 000/600 VUs, 2267583 complete and 0 interrupted iterations
read ✓ [==============] 600 VUs  10m0s

### 8 nodes 1mib read
INFO[17:25:59] Load started at:               Thu Feb 27 2025 17:25:59 GMT+0000 (UTC)  source=console
INFO[17:35:59] Load finished at:              Thu Feb 27 2025 17:35:59 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_get_bytes......: 3.0 TB  5.1 GB/s
     aws_obj_get_duration...: avg=165.66ms min=13.7ms   med=144.91ms max=3.7s p(90)=267.93ms p(95)=349.42ms
     aws_obj_get_fails......: 3950    6.575857/s
     aws_obj_get_success....: 2894066 4817.965948/s
     data_received..........: 3.0 TB  5.0 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=165.63ms min=602.06µs med=144.89ms max=3.7s p(90)=267.9ms  p(95)=349.38ms
     iterations.............: 2898016 4824.541805/s
     vus....................: 800     min=800       max=800
     vus_max................: 800     min=800       max=800
running (10m00.7s), 000/800 VUs, 2898016 complete and 0 interrupted iterations
read ✓ [==============] 800 VUs  10m0s

### 4 nodes 128kb read
INFO[09:24:24] Load started at:               Fri Feb 28 2025 09:24:24 GMT+0000 (UTC)  source=console
INFO[09:34:24] Load finished at:              Fri Feb 28 2025 09:34:24 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_get_bytes......: 577 GB  961 MB/s
     aws_obj_get_duration...: avg=78.65ms min=6.95ms  med=71.03ms max=1.15s p(90)=131.55ms p(95)=155.41ms
     aws_obj_get_fails......: 296625  494.291814/s
     aws_obj_get_success....: 4398823 7330.138053/s
     data_received..........: 576 GB  960 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=76.65ms min=361.7µs med=69.15ms max=1.15s p(90)=129.66ms p(95)=153.53ms
     iterations.............: 4695448 7824.429867/s
     vus....................: 600     min=600       max=600
     vus_max................: 600     min=600       max=600
running (10m00.1s), 000/600 VUs, 4695448 complete and 0 interrupted iterations
read ✓ [==============] 600 VUs  10m0s

### 6 nodes 128kb read
INFO[19:22:11] Load started at:               Thu Feb 27 2025 19:22:11 GMT+0000 (UTC)  source=console
INFO[19:32:11] Load finished at:              Thu Feb 27 2025 19:32:11 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 802 GB  1.3 GB/s
     aws_obj_get_duration...: avg=88.1ms  min=7.04ms  med=81.9ms  max=553.96ms p(90)=145.08ms p(95)=165.63ms
     aws_obj_get_success....: 6122093 10201.338028/s
     data_received..........: 801 GB  1.3 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=88.19ms min=199.3µs med=81.99ms max=554.05ms p(90)=145.17ms p(95)=165.72ms
     iterations.............: 6122093 10201.338028/s
     vus....................: 900     min=900        max=900
     vus_max................: 900     min=900        max=900
running (10m00.1s), 000/900 VUs, 6122093 complete and 0 interrupted iterations
read ✓ [==============] 900 VUs  10m0s

### 8 nodes 128kb read
INFO[16:47:08] Load started at:               Thu Feb 27 2025 16:47:08 GMT+0000 (UTC)  source=console
INFO[16:57:08] Load finished at:              Thu Feb 27 2025 16:57:08 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.0 TB  1.7 GB/s
     aws_obj_get_duration...: avg=93.82ms min=7.02ms   med=87.63ms max=579.47ms p(90)=153.56ms p(95)=175.26ms
     aws_obj_get_success....: 7665819 12774.162585/s
     data_received..........: 1.0 TB  1.7 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=93.9ms  min=329.83µs med=87.71ms max=579.55ms p(90)=153.64ms p(95)=175.34ms
     iterations.............: 7665819 12774.162585/s
     vus....................: 1200    min=1200       max=1200
     vus_max................: 1200    min=1200       max=1200
running (10m00.1s), 0000/1200 VUs, 7665819 complete and 0 interrupted iterations
read ✓ [==============] 1200 VUs  10m0s

### 6 nodes 128mib read
INFO[20:49:03] Load started at:               Thu Feb 27 2025 20:49:03 GMT+0000 (UTC)  source=console
INFO[20:59:06] Load finished at:              Thu Feb 27 2025 20:59:06 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 3.3 TB 5.4 GB/s
     aws_obj_get_duration...: avg=4.44s min=931.94ms med=4.13s max=21.2s p(90)=6.59s p(95)=7.66s
     aws_obj_get_success....: 24381  40.429254/s
     data_received..........: 3.3 TB 5.4 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=4.44s min=407.85µs med=4.13s max=21.2s p(90)=6.59s p(95)=7.66s
     iterations.............: 24381  40.429254/s
     vus....................: 2      min=2       max=180
     vus_max................: 180    min=180     max=180
running (10m03.1s), 000/180 VUs, 24381 complete and 0 interrupted iterations
read ✓ [==============] 180 VUs  10m0s

### 8 nodes 128mib read
INFO[18:05:39] Load started at:               Thu Feb 27 2025 18:05:39 GMT+0000 (UTC)  source=console
INFO[18:15:43] Load finished at:              Thu Feb 27 2025 18:15:43 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 3.3 TB 5.5 GB/s
     aws_obj_get_duration...: avg=5.81s min=1.43s    med=5.6s max=18.7s p(90)=8.2s p(95)=9.04s
     aws_obj_get_success....: 24855  41.185834/s
     data_received..........: 3.3 TB 5.5 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=5.81s min=442.48µs med=5.6s max=18.7s p(90)=8.2s p(95)=9.04s
     iterations.............: 24855  41.185834/s
     vus....................: 42     min=42      max=240
     vus_max................: 240    min=240     max=240
running (10m03.5s), 000/240 VUs, 24855 complete and 0 interrupted iterations
read ✓ [==============] 240 VUs  10m0s

### 4 nodes 8kb read
INFO[08:30:54] Load started at:               Fri Feb 28 2025 08:30:54 GMT+0000 (UTC)  source=console
INFO[08:40:54] Load finished at:              Fri Feb 28 2025 08:40:54 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_get_bytes......: 48 GB   81 MB/s
     aws_obj_get_duration...: avg=61.99ms min=5.05ms   med=55.52ms max=628.42ms p(90)=101.87ms p(95)=120.41ms
     aws_obj_get_fails......: 99288   165.45669/s
     aws_obj_get_success....: 5912874 9853.401804/s
     data_received..........: 48 GB   81 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=61.85ms min=723.17µs med=55.39ms max=628.5ms  p(90)=101.77ms p(95)=120.35ms
     iterations.............: 6012162 10018.858494/s
     vus....................: 620     min=620        max=620
     vus_max................: 620     min=620        max=620
running (10m00.1s), 000/620 VUs, 6012162 complete and 0 interrupted iterations
read ✓ [==============] 620 VUs  10m0s

### 6 nodes 8kb read
INFO[18:44:00] Load started at:               Thu Feb 27 2025 18:44:00 GMT+0000 (UTC)  source=console
INFO[18:54:00] Load finished at:              Thu Feb 27 2025 18:54:00 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 58 GB   97 MB/s
     aws_obj_get_duration...: avg=78.54ms min=5.49ms med=70.39ms max=553.44ms p(90)=134.23ms p(95)=157.88ms
     aws_obj_get_success....: 7095476 11823.897617/s
     data_received..........: 58 GB   97 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=78.62ms min=583µs  med=70.47ms max=553.52ms p(90)=134.32ms p(95)=157.97ms
     iterations.............: 7095476 11823.897617/s
     vus....................: 930     min=930        max=930
     vus_max................: 930     min=930        max=930
running (10m00.1s), 000/930 VUs, 7095476 complete and 0 interrupted iterations
read ✓ [==============] 930 VUs  10m0s

### 8 nodes 8kb read
INFO[16:08:16] Load started at:               Thu Feb 27 2025 16:08:16 GMT+0000 (UTC)  source=console
INFO[16:18:16] Load finished at:              Thu Feb 27 2025 16:18:16 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 79 GB   131 MB/s
     aws_obj_get_duration...: avg=77.37ms min=5.21ms   med=71.25ms max=583.12ms p(90)=125.98ms p(95)=145.37ms
     aws_obj_get_success....: 9603459 16002.245763/s
     data_received..........: 79 GB   131 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=77.45ms min=313.59µs med=71.34ms max=583.19ms p(90)=126.06ms p(95)=145.46ms
     iterations.............: 9603459 16002.245763/s
     vus....................: 1240    min=1240       max=1240
     vus_max................: 1240    min=1240       max=1240
running (10m00.1s), 0000/1240 VUs, 9603459 complete and 0 interrupted iterations
read ✓ [==============] 1240 VUs  10m0s

### 4 nodes 1mib write
INFO[10:17:48] Load started at:               Fri Feb 28 2025 10:17:48 GMT+0000 (UTC)  source=console
INFO[10:27:48] Load finished at:              Fri Feb 28 2025 10:27:48 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 537 GB 894 MB/s
     aws_obj_put_duration...: avg=468.54ms min=45.3ms   med=432ms    max=2.03s p(90)=768.65ms p(95)=890.53ms
     aws_obj_put_success....: 511862 852.543097/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 536 GB 893 MB/s
     iteration_duration.....: avg=468.93ms min=184.11µs med=432.39ms max=2.03s p(90)=769.06ms p(95)=890.96ms
     iterations.............: 511862 852.543097/s
     vus....................: 400    min=400      max=400
     vus_max................: 400    min=400      max=400
running (10m00.4s), 000/400 VUs, 511862 complete and 0 interrupted iterations
write ✓ [==============] 400 VUs  10m0s

### 6 nodes 1mib write
INFO[20:17:11] Load started at:               Thu Feb 27 2025 20:17:11 GMT+0000 (UTC)  source=console
INFO[20:27:12] Load finished at:              Thu Feb 27 2025 20:27:12 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 916 GB 1.5 GB/s
     aws_obj_put_duration...: avg=411.9ms  min=51.03ms  med=359.69ms max=2.36s p(90)=713.48ms p(95)=857.4ms 
     aws_obj_put_success....: 873238 1454.192181/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 915 GB 1.5 GB/s
     iteration_duration.....: avg=412.31ms min=225.02µs med=360.1ms  max=2.37s p(90)=713.9ms  p(95)=857.77ms
     iterations.............: 873238 1454.192181/s
     vus....................: 600    min=600       max=600
     vus_max................: 600    min=600       max=600
running (10m00.5s), 000/600 VUs, 873238 complete and 0 interrupted iterations
write ✓ [==============] 600 VUs  10m0s

### 8 nodes 1mib write
INFO[17:36:03] Load started at:               Thu Feb 27 2025 17:36:03 GMT+0000 (UTC)  source=console
INFO[17:46:08] Load finished at:              Thu Feb 27 2025 17:46:08 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_put_bytes......: 28 GB 47 MB/s
     aws_obj_put_duration...: avg=3.89s min=48.08ms med=141.22ms max=9m2s p(90)=417.23ms p(95)=24.22s
     aws_obj_put_fails......: 436   0.720635/s
     aws_obj_put_success....: 26848 44.375259/s
     data_received..........: 0 B   0 B/s
     data_sent..............: 28 GB 47 MB/s
     iteration_duration.....: avg=4.79s min=90.13µs med=143.98ms max=9m2s p(90)=464.41ms p(95)=31.83s
     iterations.............: 27284 45.095894/s
     vus....................: 783   min=783     max=800
     vus_max................: 800   min=800     max=800
running (10m05.0s), 000/800 VUs, 27284 complete and 778 interrupted iterations
write ✓ [==============] 800 VUs  10m0s

### 4 nodes 128kb write
INFO[09:34:27] Load started at:               Fri Feb 28 2025 09:34:27 GMT+0000 (UTC)  source=console
INFO[09:44:29] Load finished at:              Fri Feb 28 2025 09:44:29 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 193 GB  322 MB/s
     aws_obj_put_duration...: avg=243.66ms min=22.39ms med=198.65ms max=3.12s p(90)=437ms    p(95)=559.91ms
     aws_obj_put_success....: 1475239 2454.104915/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 193 GB  321 MB/s
     iteration_duration.....: avg=244.06ms min=141.4µs med=199.05ms max=3.12s p(90)=437.41ms p(95)=560.28ms
     iterations.............: 1475239 2454.104915/s
     vus....................: 26      min=26        max=600
     vus_max................: 600     min=600       max=600
running (10m01.1s), 000/600 VUs, 1475239 complete and 0 interrupted iterations
write ✓ [==============] 600 VUs  10m0s

### 6 nodes 128kb write
INFO[19:32:15] Load started at:               Thu Feb 27 2025 19:32:15 GMT+0000 (UTC)  source=console
INFO[19:42:16] Load finished at:              Thu Feb 27 2025 19:42:16 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 324 GB  539 MB/s
     aws_obj_put_duration...: avg=218.16ms min=22.85ms  med=157.96ms max=3.58s p(90)=390.27ms p(95)=539.98ms
     aws_obj_put_success....: 2471499 4111.308259/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 323 GB  538 MB/s
     iteration_duration.....: avg=218.56ms min=179.39µs med=158.36ms max=3.58s p(90)=390.68ms p(95)=540.38ms
     iterations.............: 2471499 4111.308259/s
     vus....................: 119     min=119       max=900
     vus_max................: 900     min=900       max=900
running (10m01.1s), 000/900 VUs, 2471499 complete and 0 interrupted iterations
write ✓ [==============] 900 VUs  10m0s

### 8 nodes 128kb write
INFO[16:57:13] Load started at:               Thu Feb 27 2025 16:57:13 GMT+0000 (UTC)  source=console
INFO[17:07:18] Load finished at:              Thu Feb 27 2025 17:07:18 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_put_bytes......: 16 GB  26 MB/s
     aws_obj_put_duration...: avg=2.64s min=15.4ms  med=120.31ms max=9m36s p(90)=280.43ms p(95)=434.44ms
     aws_obj_put_fails......: 1331   2.199945/s
     aws_obj_put_success....: 119287 197.163659/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 16 GB  26 MB/s
     iteration_duration.....: avg=3.18s min=82.25µs med=121.55ms max=9m36s p(90)=293.57ms p(95)=532.34ms
     iterations.............: 120618 199.363604/s
     vus....................: 1200   min=1200     max=1200
     vus_max................: 1200   min=1200     max=1200
running (10m05.0s), 0000/1200 VUs, 120618 complete and 1200 interrupted iterations
write ✓ [==============] 1200 VUs  10m0s

### 6 nodes 128mib write
INFO[20:59:11] Load started at:               Thu Feb 27 2025 20:59:11 GMT+0000 (UTC)  source=console
INFO[21:09:16] Load finished at:              Thu Feb 27 2025 21:09:16 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.5 TB 2.5 GB/s
     aws_obj_put_duration...: avg=9.52s min=5.11s   med=9.21s max=21.94s p(90)=12.16s p(95)=13.27s
     aws_obj_put_success....: 11357  18.756033/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.5 TB 2.5 GB/s
     iteration_duration.....: avg=9.52s min=90.33µs med=9.21s max=21.94s p(90)=12.16s p(95)=13.27s
     iterations.............: 11357  18.756033/s
     vus....................: 96     min=0       max=180
     vus_max................: 180    min=98      max=180
running (10m05.5s), 000/180 VUs, 11357 complete and 68 interrupted iterations
write ✓ [==============] 180 VUs  10m0s

### 8 nodes 128mib write
INFO[18:15:47] Load started at:               Thu Feb 27 2025 18:15:47 GMT+0000 (UTC)  source=console
INFO[18:25:53] Load finished at:              Thu Feb 27 2025 18:25:53 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_put_bytes......: 1.9 TB 3.2 GB/s
     aws_obj_put_duration...: avg=10.02s min=4.38s    med=9.45s max=31.96s p(90)=13.76s p(95)=15.36s
     aws_obj_put_fails......: 1      0.001651/s
     aws_obj_put_success....: 14372  23.735024/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.9 TB 3.2 GB/s
     iteration_duration.....: avg=10.02s min=100.44µs med=9.45s max=31.96s p(90)=13.76s p(95)=15.36s
     iterations.............: 14373  23.736675/s
     vus....................: 101    min=0       max=240
     vus_max................: 240    min=136     max=240
running (10m05.5s), 000/240 VUs, 14373 complete and 79 interrupted iterations
write ✓ [==============] 240 VUs  10m0s

### 4 nodes 8kb write
INFO[08:40:58] Load started at:               Fri Feb 28 2025 08:40:58 GMT+0000 (UTC)  source=console
INFO[08:50:58] Load finished at:              Fri Feb 28 2025 08:50:58 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_put_bytes......: 21 GB   35 MB/s
     aws_obj_put_duration...: avg=144.36ms min=30.01ms  med=123.19ms max=2.12s p(90)=224.3ms p(95)=270.19ms
     aws_obj_put_fails......: 121     0.201573/s
     aws_obj_put_success....: 2569554 4280.599293/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 21 GB   35 MB/s
     iteration_duration.....: avg=144.76ms min=152.09µs med=123.59ms max=2.12s p(90)=224.7ms p(95)=270.58ms
     iterations.............: 2569675 4280.800865/s
     vus....................: 620     min=620       max=620
     vus_max................: 620     min=620       max=620
running (10m00.3s), 000/620 VUs, 2569675 complete and 0 interrupted iterations
write ✓ [==============] 620 VUs  10m0s

### 6 nodes 8kb write
INFO[18:54:04] Load started at:               Thu Feb 27 2025 18:54:04 GMT+0000 (UTC)  source=console
INFO[19:04:05] Load finished at:              Thu Feb 27 2025 19:04:05 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 30 GB   50 MB/s
     aws_obj_put_duration...: avg=153.46ms min=33.44ms  med=126.61ms max=2.2s p(90)=249.05ms p(95)=314.75ms
     aws_obj_put_success....: 3626449 6042.026163/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 30 GB   49 MB/s
     iteration_duration.....: avg=153.86ms min=210.89µs med=127.01ms max=2.2s p(90)=249.44ms p(95)=315.15ms
     iterations.............: 3626449 6042.026163/s
     vus....................: 930     min=930       max=930
     vus_max................: 930     min=930       max=930
running (10m00.2s), 000/930 VUs, 3626449 complete and 0 interrupted iterations
write ✓ [==============] 930 VUs  10m0s

### 8 nodes 8kb write
INFO[16:18:21] Load started at:               Thu Feb 27 2025 16:18:21 GMT+0000 (UTC)  source=console
INFO[16:28:21] Load finished at:              Thu Feb 27 2025 16:28:21 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 33 GB   55 MB/s
     aws_obj_put_duration...: avg=186.03ms min=29.5ms   med=129.47ms max=32.16s p(90)=231.86ms p(95)=281.61ms
     aws_obj_put_success....: 3990615 6648.975332/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 33 GB   54 MB/s
     iteration_duration.....: avg=186.42ms min=157.14µs med=129.87ms max=32.16s p(90)=232.25ms p(95)=282.01ms
     iterations.............: 3990615 6648.975332/s
     vus....................: 1240    min=1240      max=1240
     vus_max................: 1240    min=1240      max=1240
running (10m00.2s), 0000/1240 VUs, 3990615 complete and 0 interrupted iterations
write ✓ [==============] 1240 VUs  10m0s
