protection=EC2.1
HW_chassis=X205
SSD=2


### 16 nodes 8kb write
INFO[14:33:29] Load started at:               Tue Nov 19 2024 14:33:29 GMT+0000 (UTC)  source=console
INFO[14:43:30] Load finished at:              Tue Nov 19 2024 14:43:30 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 14 GB   23 MB/s
     aws_obj_put_duration...: avg=431.06ms min=63.56ms  med=344.32ms max=13.69s p(90)=745.33ms p(95)=923.69ms
     aws_obj_put_success....: 1693466 2821.109584/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 14 GB   23 MB/s
     iteration_duration.....: avg=439.37ms min=226.14µs med=353.21ms max=13.7s  p(90)=753.86ms p(95)=932.08ms
     iterations.............: 1693466 2821.109584/s
     vus....................: 1240    min=1240      max=1240

running (10m00.3s), 0000/1240 VUs, 1693466 complete and 0 interrupted iterations
write ✓ [======================================] 1240 VUs  10m0s

INFO[14:33:27] Load started at:               Tue Nov 19 2024 14:33:27 GMT+0000 (UTC)  source=console
INFO[14:43:29] Load finished at:              Tue Nov 19 2024 14:43:29 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 14 GB   24 MB/s
     aws_obj_put_duration...: avg=419.13ms min=57.74ms med=332.78ms max=11.55s p(90)=727.25ms p(95)=904.96ms
     aws_obj_put_success....: 1741572 2896.928883/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 14 GB   24 MB/s
     iteration_duration.....: avg=427.34ms min=2.43ms  med=341.21ms max=11.55s p(90)=735.43ms p(95)=913.35ms
     iterations.............: 1741572 2896.928883/s
     vus....................: 45      min=45        max=1240

running (10m01.2s), 0000/1240 VUs, 1741572 complete and 0 interrupted iterations
write ✓ [======================================] 1240 VUs  10m0s

### 16 nodes 8kb read
INFO[10:35:47] Load started at:               Tue Nov 21 2024 10:35:47 GMT+0000 (UTC)  source=console
INFO[10:45:49] Load finished at:              Thu Nov 21 2024 10:45:49 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 24 GB   39 MB/s
     aws_obj_get_duration...: avg=257.82ms min=12.91ms  med=124.68ms max=23.78s p(90)=394.55ms p(95)=746.8ms 
     aws_obj_get_fails......: 1524    2.539048/s
     aws_obj_get_success....: 2883745 4804.439467/s
     data_received..........: 24 GB   39 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=257.85ms min=196.77µs med=124.69ms max=23.78s p(90)=394.61ms p(95)=746.83ms
     iterations.............: 2885269 4806.978515/s
     vus....................: 1240    min=1240      max=1240

running (10m00.2s), 0000/1240 VUs, 2885269 complete and 0 interrupted iterations
read ✓ [======================================] 1240 VUs  10m0s

INFO[10:35:47] Load started at:               Tue Nov 21 2024 10:35:47 GMT+0000 (UTC)  source=console
INFO[10:45:49] Load finished at:              Thu Nov 21 2024 10:45:49 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 24 GB   40 MB/s
     aws_obj_get_duration...: avg=254.45ms min=12.99ms  med=123.92ms max=27.51s p(90)=388.45ms p(95)=706.18ms
     aws_obj_get_fails......: 1594    2.649409/s
     aws_obj_get_success....: 2924067 4860.130475/s
     data_received..........: 24 GB   40 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=254.46ms min=199.09µs med=123.94ms max=27.51s p(90)=388.48ms p(95)=706.13ms
     iterations.............: 2925661 4862.779883/s
     vus....................: 313     min=313       max=1240

running (10m01.6s), 0000/1240 VUs, 2925661 complete and 0 interrupted iterations
read ✓ [======================================] 1240 VUs  10m0s

### 16 nodes 128kb write
INFO[14:24:29] Load started at:               Wed Nov 20 2024 14:24:29 GMT+0000 (UTC)  source=console
INFO[14:34:29] Load finished at:              Wed Nov 20 2024 14:34:29 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 195 GB  325 MB/s
     aws_obj_put_duration...: avg=473.98ms min=72.77ms  med=426.53ms max=15.39s p(90)=717.55ms p(95)=840.7ms 
     aws_obj_put_success....: 1489115 2480.732449/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 195 GB  325 MB/s
     iteration_duration.....: avg=483.5ms  min=202.31µs med=435.95ms max=15.4s  p(90)=727.02ms p(95)=850.21ms
     iterations.............: 1489115 2480.732449/s
     vus....................: 1200    min=1200      max=1200

running (10m00.3s), 0000/1200 VUs, 1489115 complete and 0 interrupted iterations
write ✓ [======================================] 1200 VUs  10m0s

INFO[14:24:27] Load started at:               Wed Nov 20 2024 14:24:27 GMT+0000 (UTC)  source=console
INFO[14:34:28] Load finished at:              Wed Nov 20 2024 14:34:28 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 196 GB  326 MB/s
     aws_obj_put_duration...: avg=472.67ms min=64.58ms  med=429.15ms max=11.79s p(90)=711.95ms p(95)=826.98ms
     aws_obj_put_success....: 1493991 2486.294838/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 196 GB  326 MB/s
     iteration_duration.....: avg=482.08ms min=269.32µs med=438.38ms max=11.8s  p(90)=721.4ms  p(95)=836.39ms
     iterations.............: 1493991 2486.294838/s
     vus....................: 13      min=13        max=1200

running (10m00.9s), 0000/1200 VUs, 1493991 complete and 0 interrupted iterations
write ✓ [======================================] 1200 VUs  10m0s

### 16 nodes 128kb read
INFO[14:53:13] Load started at:               Wed Nov 20 2024 14:53:13 GMT+0000 (UTC)  source=console
INFO[15:03:14] Load finished at:              Wed Nov 20 2024 15:03:14 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 286 GB  476 MB/s
     aws_obj_get_duration...: avg=330.14ms min=16.01ms  med=254.92ms max=4.85s p(90)=711.64ms p(95)=896.15ms
     aws_obj_get_fails......: 3       0.004997/s
     aws_obj_get_success....: 2180404 3631.868506/s
     data_received..........: 286 GB  476 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=330.23ms min=559.27µs med=255.01ms max=4.85s p(90)=711.73ms p(95)=896.24ms
     iterations.............: 2180407 3631.873503/s
     vus....................: 1200    min=1200      max=1200

running (10m00.4s), 0000/1200 VUs, 2180407 complete and 0 interrupted iterations
read ✓ [======================================] 1200 VUs  10m0s

INFO[14:53:11] Load started at:               Wed Nov 20 2024 14:53:11 GMT+0000 (UTC)  source=console
INFO[15:03:13] Load finished at:              Wed Nov 20 2024 15:03:13 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 284 GB  472 MB/s
     aws_obj_get_duration...: avg=332.49ms min=16.84ms  med=256.82ms max=7.2s p(90)=715.34ms p(95)=899.82ms
     aws_obj_get_fails......: 9       0.01496/s
     aws_obj_get_success....: 2165486 3599.400114/s
     data_received..........: 284 GB  472 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=332.58ms min=199.13µs med=256.91ms max=7.2s p(90)=715.43ms p(95)=899.9ms 
     iterations.............: 2165495 3599.415073/s
     vus....................: 100     min=100       max=1200

running (10m01.6s), 0000/1200 VUs, 2165495 complete and 0 interrupted iterations
read ✓ [======================================] 1200 VUs  10m0s

### 16 nodes 1mib write
INFO[13:54:23] Load started at:               Tue Nov 05 2024 13:54:23 GMT+0000 (UTC)  source=console
INFO[14:04:24] Load finished at:              Tue Nov 05 2024 14:04:24 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 828 GB 1.4 GB/s
     aws_obj_put_duration...: avg=724.48ms min=109.93ms med=695.83ms max=4.1s  p(90)=1.06s p(95)=1.19s
     aws_obj_put_success....: 647642 1078.814015/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 827 GB 1.4 GB/s
     iteration_duration.....: avg=741.24ms min=261.31µs med=712.78ms max=4.12s p(90)=1.08s p(95)=1.21s
     iterations.............: 647642 1078.814015/s
     vus....................: 800    min=800       max=800

running (10m00.3s), 000/800 VUs, 647642 complete and 0 interrupted iterations
write ✓ [======================================] 800 VUs  10m0s

INFO[13:54:20] Load started at:               Tue Nov 05 2024 13:54:20 GMT+0000 (UTC)  source=console
INFO[14:04:21] Load finished at:              Tue Nov 05 2024 14:04:21 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 838 GB 1.4 GB/s
     aws_obj_put_duration...: avg=715.34ms min=113.09ms med=686.7ms  max=4.64s p(90)=1.06s p(95)=1.19s
     aws_obj_put_success....: 656009 1091.610334/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 838 GB 1.4 GB/s
     iteration_duration.....: avg=732.01ms min=334.52µs med=703.53ms max=4.66s p(90)=1.08s p(95)=1.21s
     iterations.............: 656009 1091.610334/s
     vus....................: 172    min=172       max=800

running (10m01.0s), 000/800 VUs, 656009 complete and 0 interrupted iterations
write ✓ [======================================] 800 VUs  10m0s

### 16 nodes 1mib read
INFO[14:06:36] Load started at:               Tue Nov 05 2024 14:06:36 GMT+0000 (UTC)  source=console
INFO[14:16:37] Load finished at:              Tue Nov 05 2024 14:16:37 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.1 TB 1.9 GB/s
     aws_obj_get_duration...: avg=543.4ms  min=42.9ms   med=523.05ms max=3.73s p(90)=833.83ms p(95)=940.46ms
     aws_obj_get_success....: 883578 1470.126352/s
     data_received..........: 1.1 TB 1.9 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=543.49ms min=188.26µs med=523.14ms max=3.73s p(90)=833.92ms p(95)=940.56ms
     iterations.............: 883578 1470.126352/s
     vus....................: 18     min=18        max=800
     vus_max................: 800    m
running (10m01.0s), 000/800 VUs, 883578 complete and 0 interrupted iterations
read ✓ [=============] 800 VUs  10m0s

INFO[14:06:37] Load started at:               Tue Nov 05 2024 14:06:37 GMT+0000 (UTC)  source=console
INFO[14:16:38] Load finished at:              Tue Nov 05 2024 14:16:38 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.1 TB 1.9 GB/s
     aws_obj_get_duration...: avg=545.6ms  min=42.75ms  med=526.2ms max=3.89s p(90)=837.35ms p(95)=943.49ms
     aws_obj_get_success....: 879753 1464.431341/s
     data_received..........: 1.1 TB 1.9 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=545.69ms min=218.26µs med=526.3ms max=3.89s p(90)=837.46ms p(95)=943.59ms
     iterations.............: 879753 1464.431341/s
     vus....................: 800    min=800       max=800
     vus_max................: 800    m
running (10m00.7s), 000/800 VUs, 879753 complete and 0 interrupted iterations
read ✓ [=============] 800 VUs  10m0s

### 16 nodes 128mib write
INFO[14:41:40] Load started at:               Tue Nov 05 2024 14:41:40 GMT+0000 (UTC)  source=console
INFO[14:51:45] Load finished at:              Tue Nov 05 2024 14:51:45 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.3 TB 2.1 GB/s
     aws_obj_put_duration...: avg=14.92s min=5.86s   med=13.9s  max=1m41s p(90)=20.27s p(95)=22.07s
     aws_obj_put_success....: 9327   15.39726/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.3 TB 2.1 GB/s
     iteration_duration.....: avg=15.37s min=228.1µs med=14.35s max=1m42s p(90)=20.72s p(95)=22.51s
     iterations.............: 9320   15.385704/s
     vus....................: 151    min=0       max=240
     vus_max................: 240    min=102  
running (10m05.8s), 000/240 VUs, 9320 complete and 150 interrupted iterations
write ✓ [====================] 240 VUs  10m0s

INFO[14:41:41] Load started at:               Tue Nov 05 2024 14:41:41 GMT+0000 (UTC)  source=console
INFO[14:51:47] Load finished at:              Tue Nov 05 2024 14:51:47 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.2 TB 2.0 GB/s
     aws_obj_put_duration...: avg=15.68s min=5.54s    med=14.72s max=1m42s p(90)=21.3s  p(95)=22.85s
     aws_obj_put_success....: 8895   14.683431/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.2 TB 2.0 GB/s
     iteration_duration.....: avg=16.13s min=229.97µs med=15.16s max=1m43s p(90)=21.74s p(95)=23.29s
     iterations.............: 8875   14.650416/s
     vus....................: 170    min=0       max=240
     vus_max................: 240    min=99     
running (10m05.8s), 000/240 VUs, 8875 complete and 166 interrupted iterations
write ✓ [======================] 240 VUs  10m0s

### 16 nodes 128mib read
INFO[14:54:02] Load started at:               Tue Nov 05 2024 14:54:02 GMT+0000 (UTC)  source=console
INFO[15:04:10] Load finished at:              Tue Nov 05 2024 15:04:10 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.5 TB 2.5 GB/s
     aws_obj_get_duration...: avg=12.76s min=3.84s   med=12.66s max=25.25s p(90)=16.72s p(95)=17.99s
     aws_obj_get_success....: 11275  18.524799/s
     data_received..........: 1.5 TB 2.5 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=12.76s min=379.4µs med=12.66s max=25.25s p(90)=16.72s p(95)=17.99s
     iterations.............: 11275  18.524799/s
     vus....................: 9      min=9       max=240
     vus_max................: 240    min=240  
running (10m08.6s), 000/240 VUs, 11275 complete and 112 interrupted iterations
read ✓ [=====================] 240 VUs  10m0s

INFO[14:54:02] Load started at:               Tue Nov 05 2024 14:54:02 GMT+0000 (UTC)  source=console
INFO[15:04:10] Load finished at:              Tue Nov 05 2024 15:04:10 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.5 TB 2.5 GB/s
     aws_obj_get_duration...: avg=12.65s min=3.77s    med=12.5s max=25.95s p(90)=16.81s p(95)=17.99s
     aws_obj_get_success....: 11433  18.871661/s
     data_received..........: 1.5 TB 2.5 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=12.64s min=695.76µs med=12.5s max=25.95s p(90)=16.81s p(95)=17.99s
     iterations.............: 11433  18.871661/s
     vus....................: 23     min=23      max=240
     vus_max................: 240    min=240    
running (10m05.8s), 000/240 VUs, 11433 complete and 19 interrupted iterations
read ✓ [=======================] 240 VUs  10m0s

### 15 nodes 8kb write
INFO[10:01:39] Load started at:               Wed Nov 06 2024 10:01:39 GMT+0000 (UTC)  source=console
INFO[10:11:41] Load finished at:              Wed Nov 06 2024 10:11:41 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 13 GB   22 MB/s
     aws_obj_put_duration...: avg=416.87ms min=63.33ms med=381.16ms max=8.85s p(90)=624.33ms p(95)=732.61ms
     aws_obj_put_success....: 1641010 2726.625241/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 13 GB   22 MB/s
     iteration_duration.....: avg=425.18ms min=1.69ms  med=389.19ms max=8.86s p(90)=632.44ms p(95)=740.93ms
     iterations.............: 1641010 2726.625241/s
     vus....................: 3       min=3         max=1162

running (10m01.8s), 0000/1162 VUs, 1641010 complete and 0 interrupted iterations
write ✓ [======================================] 1162 VUs  10m0s

INFO[10:01:42] Load started at:               Wed Nov 06 2024 10:01:42 GMT+0000 (UTC)  source=console
INFO[10:11:42] Load finished at:              Wed Nov 06 2024 10:11:42 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 13 GB   22 MB/s
     aws_obj_put_duration...: avg=419.79ms min=57.1ms   med=382.51ms max=10.44s p(90)=631.53ms p(95)=741.02ms
     aws_obj_put_success....: 1629220 2713.945359/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 13 GB   22 MB/s
     iteration_duration.....: avg=427.96ms min=549.54µs med=390.13ms max=10.45s p(90)=639.71ms p(95)=749.13ms
     iterations.............: 1629220 2713.945359/s
     vus....................: 1162    min=1162      max=1162

running (10m00.3s), 0000/1162 VUs, 1629220 complete and 0 interrupted iterations
write ✓ [======================================] 1162 VUs  10m0s

### 15 nodes 8kb read
INFO[10:37:59] Load started at:               Wed Nov 06 2024 10:37:59 GMT+0000 (UTC)  source=console
INFO[10:48:00] Load finished at:              Wed Nov 06 2024 10:48:00 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 24 GB   41 MB/s
     aws_obj_get_duration...: avg=234.35ms min=13.68ms  med=123.52ms max=26.47s p(90)=559.81ms p(95)=835.32ms
     aws_obj_get_fails......: 74      0.123089/s
     aws_obj_get_success....: 2974830 4948.220814/s
     data_received..........: 24 GB   41 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=234.43ms min=206.84µs med=123.6ms  max=26.47s p(90)=559.89ms p(95)=835.4ms 
     iterations.............: 2974904 4948.343903/s
     vus....................: 9       min=9         max=1162

running (10m01.2s), 0000/1162 VUs, 2974904 complete and 0 interrupted iterations
read ✓ [======================================] 1162 VUs  10m0s

INFO[10:37:59] Load started at:               Wed Nov 06 2024 10:37:59 GMT+0000 (UTC)  source=console
INFO[10:48:34] Load finished at:              Wed Nov 06 2024 10:48:34 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 24 GB   41 MB/s
     aws_obj_get_duration...: avg=234.77ms min=13.47ms med=123.65ms max=27.89s p(90)=561.99ms p(95)=840.06ms
     aws_obj_get_fails......: 127     0.211539/s
     aws_obj_get_success....: 2968619 4944.724867/s
     data_received..........: 24 GB   41 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=234.85ms min=1.23ms  med=123.72ms max=27.89s p(90)=562.07ms p(95)=840.12ms
     iterations.............: 2968746 4944.936406/s
     vus....................: 1162    min=1162      max=1162

running (10m00.4s), 0000/1162 VUs, 2968746 complete and 0 interrupted iterations
read ✓ [======================================] 1162 VUs  10m0s

### 15 nodes 128kb write
INFO[17:46:16] Load started at:               Wed Nov 20 2024 17:46:16 GMT+0000 (UTC)  source=console
INFO[17:56:17] Load finished at:              Wed Nov 20 2024 17:56:17 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 205 GB  341 MB/s
     aws_obj_put_duration...: avg=422.13ms min=53.14ms  med=354.47ms max=3.37s p(90)=798.85ms p(95)=975.76ms
     aws_obj_put_success....: 1562959 2602.986882/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 205 GB  341 MB/s
     iteration_duration.....: avg=431.92ms min=243.83µs med=364.38ms max=3.38s p(90)=808.61ms p(95)=985.68ms
     iterations.............: 1562959 2602.986882/s
     vus....................: 1125    min=1125      max=1125

running (10m00.4s), 0000/1125 VUs, 1562959 complete and 0 interrupted iterations
write ✓ [======================================] 1125 VUs  10m0s

INFO[17:46:14] Load started at:               Wed Nov 20 2024 17:46:14 GMT+0000 (UTC)  source=console
INFO[17:56:14] Load finished at:              Wed Nov 20 2024 17:56:14 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     data_received........: 0 B   0 B/s
     data_sent............: 0 B   0 B/s
     iteration_duration...: avg=10s min=202.5µs med=10s max=10.01s p(90)=10s p(95)=10s
     iterations...........: 67500 112.487847/s
     vus..................: 1125  min=1125     max=1125

running (10m00.1s), 0000/1125 VUs, 67500 complete and 0 interrupted iterations
read ✓ [======================================] 1125 VUs  10m0s

### 15 nodes 128kb read
INFO[11:33:00] Load started at:               Wed Nov 06 2024 11:33:00 GMT+0000 (UTC)  source=console
INFO[12:43:01] Load finished at:              Wed Nov 06 2024 12:43:01 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 225 GB  374 MB/s
     aws_obj_get_duration...: avg=367.32ms min=15.68ms  med=287.33ms max=10.8s p(90)=774.39ms p(95)=978.2ms 
     aws_obj_get_success....: 1714935 2855.666756/s
     data_received..........: 225 GB  374 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=367.4ms  min=208.07µs med=287.41ms max=10.8s p(90)=774.47ms p(95)=978.27ms
     iterations.............: 1714935 2855.666756/s
     vus....................: 1050    min=1050      max=1050

running (10m00.5s), 0000/1050 VUs, 1714935 complete and 0 interrupted iterations
read ✓ [======================================] 1050 VUs  10m0s

INFO[11:33:00] Load started at:               Wed Nov 06 2024 11:33:00 GMT+0000 (UTC)  source=console
INFO[12:43:00] Load finished at:              Wed Nov 06 2024 12:43:00 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 225 GB  374 MB/s
     aws_obj_get_duration...: avg=366.56ms min=16.16ms  med=285.41ms max=11.04s p(90)=775.19ms p(95)=981.11ms
     aws_obj_get_success....: 1718902 2856.210792/s
     data_received..........: 225 GB  374 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=366.65ms min=258.28µs med=285.49ms max=11.04s p(90)=775.27ms p(95)=981.2ms 
     iterations.............: 1718902 2856.210792/s
     vus....................: 38      min=38        max=1050

running (10m01.8s), 0000/1050 VUs, 1718902 complete and 0 interrupted iterations
read ✓ [======================================] 1050 VUs  10m0s

### 15 nodes 1mib write
INFO[11:16:27] Load started at:               Mon Nov 18 2024 11:16:27 GMT+0000 (UTC)  source=console
INFO[11:26:27] Load finished at:              Mon Nov 18 2024 11:26:27 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 709 GB 1.2 GB/s
     aws_obj_put_duration...: avg=650.22ms min=64.6ms   med=526.65ms max=15.18s p(90)=980.86ms p(95)=1.2s 
     aws_obj_put_success....: 675692 1125.650271/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 708 GB 1.2 GB/s
     iteration_duration.....: avg=666.08ms min=357.23µs med=542.51ms max=15.2s  p(90)=996.93ms p(95)=1.21s
     iterations.............: 675692 1125.650271/s
     vus....................: 750    min=750       max=750

running (10m00.3s), 000/750 VUs, 675692 complete and 0 interrupted iterations
write ✓ [======================================] 750 VUs  10m0s

INFO[11:16:25] Load started at:               Mon Nov 18 2024 11:16:25 GMT+0000 (UTC)  source=console
INFO[11:26:26] Load finished at:              Mon Nov 18 2024 11:26:26 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 691 GB 1.1 GB/s
     aws_obj_put_duration...: avg=667.65ms min=65.79ms  med=542.97ms max=14.76s p(90)=1.01s p(95)=1.23s
     aws_obj_put_success....: 658721 1095.83049/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 690 GB 1.1 GB/s
     iteration_duration.....: avg=683.46ms min=457.12µs med=558.7ms  max=14.77s p(90)=1.02s p(95)=1.25s
     iterations.............: 658721 1095.83049/s
     vus....................: 38     min=38       max=750

running (10m01.1s), 000/750 VUs, 658721 complete and 0 interrupted iterations
write ✓ [======================================] 750 VUs  10m0s

### 15 nodes 1mib read
INFO[13:10:12] Load started at:               Wed Nov 06 2024 13:10:12 GMT+0000 (UTC)  source=console
INFO[13:20:13] Load finished at:              Wed Nov 06 2024 13:20:13 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 703 GB 1.2 GB/s
     aws_obj_get_duration...: avg=671.2ms  min=30.53ms  med=565.41ms max=5.25s p(90)=1.35s p(95)=1.64s
     aws_obj_get_success....: 670489 1116.387731/s
     data_received..........: 703 GB 1.2 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=671.29ms min=184.52µs med=565.51ms max=5.25s p(90)=1.35s p(95)=1.64s
     iterations.............: 670489 1116.387731/s
     vus....................: 750    min=750       max=750

running (10m00.6s), 000/750 VUs, 670489 complete and 0 interrupted iterations
read ✓ [======================================] 750 VUs  10m0s

INFO[13:10:10] Load started at:               Wed Nov 06 2024 13:10:10 GMT+0000 (UTC)  source=console
INFO[13:20:13] Load finished at:              Wed Nov 06 2024 13:20:13 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 706 GB 1.2 GB/s
     aws_obj_get_duration...: avg=668.43ms min=32.33ms  med=563.4ms max=4.96s p(90)=1.35s p(95)=1.64s
     aws_obj_get_success....: 673624 1118.091057/s
     data_received..........: 706 GB 1.2 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=668.53ms min=245.71µs med=563.5ms max=4.96s p(90)=1.35s p(95)=1.64s
     iterations.............: 673624 1118.091057/s
     vus....................: 3      min=3         max=750

running (10m02.5s), 000/750 VUs, 673624 complete and 0 interrupted iterations
read ✓ [======================================] 750 VUs  10m0s

### 15 nodes 128mib write
INFO[13:51:49] Load started at:               Wed Nov 06 2024 13:51:49 GMT+0000 (UTC)  source=console
INFO[14:01:55] Load finished at:              Wed Nov 06 2024 14:01:55 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.0 TB 1.7 GB/s
     aws_obj_put_duration...: avg=16.71s min=5.37s    med=13.05s max=3m1s p(90)=25.25s p(95)=36.81s
     aws_obj_put_success....: 7754   12.799917/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.0 TB 1.7 GB/s
     iteration_duration.....: avg=17.16s min=208.78µs med=13.5s  max=3m1s p(90)=25.69s p(95)=37.25s
     iterations.............: 7741   12.778457/s
     vus....................: 11     min=0       max=225

running (10m05.8s), 000/225 VUs, 7741 complete and 155 interrupted iterations
write ✓ [======================================] 225 VUs  10m0s

INFO[13:51:48] Load started at:               Wed Nov 06 2024 13:51:48 GMT+0000 (UTC)  source=console
INFO[14:01:53] Load finished at:              Wed Nov 06 2024 14:01:53 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.1 TB 1.8 GB/s
     aws_obj_put_duration...: avg=16.3s  min=5.58s    med=12.77s max=2m41s p(90)=25.14s p(95)=36.25s
     aws_obj_put_fails......: 1      0.001651/s
     aws_obj_put_success....: 7952   13.127606/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.1 TB 1.8 GB/s
     iteration_duration.....: avg=16.75s min=220.36µs med=13.22s max=2m42s p(90)=25.62s p(95)=36.69s
     iterations.............: 7944   13.114399/s
     vus....................: 15     min=0       max=225

running (10m05.7s), 000/225 VUs, 7944 complete and 142 interrupted iterations
write ✓ [======================================] 225 VUs  10m0s

### 15 nodes 128mib read
INFO[14:06:26] Load started at:               Wed Nov 06 2024 14:06:26 GMT+0000 (UTC)  source=console
INFO[14:16:40] Load finished at:              Wed Nov 06 2024 14:16:40 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.4 TB 2.2 GB/s
     aws_obj_get_duration...: avg=13s    min=2.29s    med=9.06s max=7m16s p(90)=16.66s p(95)=29.6s 
     aws_obj_get_success....: 10182  16.577756/s
     data_received..........: 1.4 TB 2.2 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=12.99s min=178.18µs med=9.06s max=7m16s p(90)=16.66s p(95)=29.59s
     iterations.............: 10182  16.577756/s
     vus....................: 1      min=1       max=225

running (10m14.2s), 000/225 VUs, 10182 complete and 118 interrupted iterations
read ✓ [======================================] 225 VUs  10m0s

INFO[14:06:30] Load started at:               Wed Nov 06 2024 14:06:30 GMT+0000 (UTC)  source=console
INFO[14:16:40] Load finished at:              Wed Nov 06 2024 14:16:40 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.4 TB 2.2 GB/s
     aws_obj_get_duration...: avg=13.14s min=1.9s     med=9.13s max=6m48s p(90)=16.57s p(95)=26.06s
     aws_obj_get_success....: 10239  16.759326/s
     data_received..........: 1.4 TB 2.3 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=13.14s min=297.73µs med=9.13s max=6m48s p(90)=16.57s p(95)=26.06s
     iterations.............: 10239  16.759326/s
     vus....................: 1      min=1       max=225

running (10m10.9s), 000/225 VUs, 10239 complete and 55 interrupted iterations
read ✓ [======================================] 225 VUs  10m0s

### 14 nodes 8kb write
INFO[12:59:28] Load started at:               Thu Nov 07 2024 12:59:28 GMT+0000 (UTC)  source=console
INFO[13:09:29] Load finished at:              Thu Nov 07 2024 13:09:29 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 13 GB   21 MB/s
     aws_obj_put_duration...: avg=419.82ms min=56.03ms  med=256.8ms  max=16.63s p(90)=710.87ms p(95)=1.1s
     aws_obj_put_success....: 1521087 2534.344222/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 12 GB   21 MB/s
     iteration_duration.....: avg=427.99ms min=197.38µs med=264.57ms max=16.63s p(90)=719.02ms p(95)=1.1s
     iterations.............: 1521087 2534.344222/s
     vus....................: 1085    min=1085      max=1085

running (10m00.2s), 0000/1085 VUs, 1521087 complete and 0 interrupted iterations
write ✓ [======================================] 1085 VUs  10m0s

INFO[12:59:27] Load started at:               Thu Nov 07 2024 12:59:27 GMT+0000 (UTC)  source=console
INFO[13:09:28] Load finished at:              Thu Nov 07 2024 13:09:28 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 12 GB   20 MB/s
     aws_obj_put_duration...: avg=436.9ms  min=57.18ms  med=279.18ms max=18.02s p(90)=763.21ms p(95)=1.11s
     aws_obj_put_success....: 1462759 2433.733554/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 12 GB   20 MB/s
     iteration_duration.....: avg=445.19ms min=318.97µs med=286.95ms max=18.03s p(90)=771.44ms p(95)=1.12s
     iterations.............: 1462759 2433.733554/s
     vus....................: 4       min=4         max=1085

running (10m01.0s), 0000/1085 VUs, 1462759 complete and 0 interrupted iterations
write ✓ [======================================] 1085 VUs  10m0s

### 14 nodes 8kb read
INFO[13:55:42] Load started at:               Wed Nov 20 2024 13:55:42 GMT+0000 (UTC)  source=console
INFO[14:05:43] Load finished at:              Wed Nov 20 2024 14:05:43 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 24 GB   40 MB/s
     aws_obj_get_duration...: avg=214.65ms min=13.84ms  med=134.87ms max=3.43s p(90)=505.97ms p(95)=700.08ms
     aws_obj_get_success....: 2933961 4887.696564/s
     data_received..........: 24 GB   40 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=214.73ms min=234.41µs med=134.95ms max=3.43s p(90)=506.05ms p(95)=700.16ms
     iterations.............: 2933961 4887.696564/s
     vus....................: 1050    min=1050      max=1050

running (10m00.3s), 0000/1050 VUs, 2933961 complete and 0 interrupted iterations
read ✓ [======================================] 1050 VUs  10m0s

INFO[13:55:42] Load started at:               Wed Nov 20 2024 13:55:42 GMT+0000 (UTC)  source=console
INFO[14:05:34] Load finished at:              Wed Nov 20 2024 14:05:34 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 24 GB   40 MB/s
     aws_obj_get_duration...: avg=216.44ms min=13.8ms   med=136.15ms max=3.02s p(90)=510.8ms  p(95)=707.56ms
     aws_obj_get_fails......: 13      0.021643/s
     aws_obj_get_success....: 2910123 4844.891298/s
     data_received..........: 24 GB   40 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=216.52ms min=265.71µs med=136.23ms max=3.02s p(90)=510.88ms p(95)=707.63ms
     iterations.............: 2910136 4844.912941/s
     vus....................: 1050    min=1050      max=1050

running (10m00.7s), 0000/1050 VUs, 2910136 complete and 0 interrupted iterations
read ✓ [======================================] 1050 VUs  10m0s


### 14 nodes 128kb write -
INFO[15:23:35] Load started at:               Thu Nov 07 2024 15:23:35 GMT+0000 (UTC)  source=console
INFO[15:33:36] Load finished at:              Thu Nov 07 2024 15:33:36 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 175 GB  291 MB/s
     aws_obj_put_duration...: avg=463.27ms min=74.34ms  med=432.94ms max=10.98s p(90)=675.6ms  p(95)=770.81ms
     aws_obj_put_success....: 1332877 2219.208726/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 175 GB  291 MB/s
     iteration_duration.....: avg=472.76ms min=271.74µs med=442.3ms  max=10.99s p(90)=685.04ms p(95)=780.2ms 
     iterations.............: 1332877 2219.208726/s
     vus....................: 1050    min=1050      max=1050

running (10m00.6s), 0000/1050 VUs, 1332877 complete and 0 interrupted iterations
write ✓ [======================================] 1050 VUs  10m0s

INFO[15:23:38] Load started at:               Thu Nov 07 2024 15:23:38 GMT+0000 (UTC)  source=console
INFO[15:33:38] Load finished at:              Thu Nov 07 2024 15:33:38 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 180 GB  299 MB/s
     aws_obj_put_duration...: avg=450.27ms min=82.96ms  med=422.11ms max=10.38s p(90)=651.37ms p(95)=739.74ms
     aws_obj_put_success....: 1370679 2283.646576/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 180 GB  299 MB/s
     iteration_duration.....: avg=459.64ms min=235.11µs med=431.44ms max=10.39s p(90)=660.84ms p(95)=749.05ms
     iterations.............: 1370679 2283.646576/s
     vus....................: 1050    min=1050      max=1050

running (10m00.2s), 0000/1050 VUs, 1370679 complete and 0 interrupted iterations
write ✓ [======================================] 1050 VUs  10m0s

### 14 nodes 128kb read
INFO[12:06:01] Load started at:               Fri Nov 08 2024 12:06:01 GMT+0000 (UTC)  source=console
INFO[12:16:01] Load finished at:              Fri Nov 08 2024 12:16:01 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 259 GB  431 MB/s
     aws_obj_get_duration...: avg=319.34ms min=18.08ms  med=258.39ms max=6.67s p(90)=585.18ms p(95)=777.59ms
     aws_obj_get_success....: 1972511 3284.465018/s
     data_received..........: 258 GB  430 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=319.42ms min=281.48µs med=258.48ms max=6.67s p(90)=585.27ms p(95)=777.68ms
     iterations.............: 1972511 3284.465018/s
     vus....................: 1050    min=1050      max=1050

running (10m00.6s), 0000/1050 VUs, 1972511 complete and 0 interrupted iterations
read ✓ [======================================] 1050 VUs  10m0s

INFO[12:05:59] Load started at:               Fri Nov 08 2024 12:05:59 GMT+0000 (UTC)  source=console
INFO[12:16:01] Load finished at:              Fri Nov 08 2024 12:16:01 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 261 GB  433 MB/s
     aws_obj_get_duration...: avg=316.87ms min=17.47ms  med=256.98ms max=6.75s p(90)=580.69ms p(95)=767.69ms
     aws_obj_get_success....: 1988344 3304.200291/s
     data_received..........: 261 GB  433 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=316.96ms min=196.66µs med=257.07ms max=6.75s p(90)=580.78ms p(95)=767.78ms
     iterations.............: 1988344 3304.200291/s
     vus....................: 53      min=53        max=1050

running (10m01.8s), 0000/1050 VUs, 1988344 complete and 0 interrupted iterations
read ✓ [======================================] 1050 VUs  10m0s

### 14 nodes 1mib write
INFO[12:20:40] Load started at:               Mon Nov 18 2024 12:20:40 GMT+0000 (UTC)  source=console
INFO[12:30:40] Load finished at:              Mon Nov 18 2024 12:30:40 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 700 GB 1.2 GB/s
     aws_obj_put_duration...: avg=613.71ms min=95.83ms med=599ms    max=2.43s p(90)=862.22ms p(95)=948.36ms
     aws_obj_put_success....: 667198 1111.378343/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 699 GB 1.2 GB/s
     iteration_duration.....: avg=629.59ms min=337.9µs med=614.85ms max=2.45s p(90)=878.25ms p(95)=964.55ms
     iterations.............: 667198 1111.378343/s
     vus....................: 700    min=700       max=700

running (10m00.3s), 000/700 VUs, 667198 complete and 0 interrupted iterations
write ✓ [======================================] 700 VUs  10m0s

INFO[12:20:38] Load started at:               Mon Nov 18 2024 12:20:38 GMT+0000 (UTC)  source=console
INFO[12:30:39] Load finished at:              Mon Nov 18 2024 12:30:39 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 700 GB 1.2 GB/s
     aws_obj_put_duration...: avg=613.83ms min=100.77ms med=599.57ms max=2.62s p(90)=862.88ms p(95)=949.5ms 
     aws_obj_put_success....: 667248 1110.525232/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 699 GB 1.2 GB/s
     iteration_duration.....: avg=629.62ms min=396.09µs med=615.42ms max=2.63s p(90)=878.71ms p(95)=965.51ms
     iterations.............: 667248 1110.525232/s
     vus....................: 2      min=2         max=700

running (10m00.8s), 000/700 VUs, 667248 complete and 0 interrupted iterations
write ✓ [======================================] 700 VUs  10m0s


### 14 nodes 1mib read
INFO[12:39:59] Load started at:               Fri Nov 08 2024 12:39:59 GMT+0000 (UTC)  source=console
INFO[12:50:00] Load finished at:              Fri Nov 08 2024 12:50:00 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 747 GB 1.2 GB/s
     aws_obj_get_duration...: avg=589.81ms min=29.55ms med=531.33ms max=4.57s p(90)=1.08s p(95)=1.27s
     aws_obj_get_success....: 712359 1184.539951/s
     data_received..........: 747 GB 1.2 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=589.91ms min=1.96ms  med=531.42ms max=4.57s p(90)=1.08s p(95)=1.27s
     iterations.............: 712359 1184.539951/s
     vus....................: 60     min=60        max=700

running (10m01.4s), 000/700 VUs, 712359 complete and 0 interrupted iterations
read ✓ [======================================] 700 VUs  10m0s

INFO[12:40:01] Load started at:               Fri Nov 08 2024 12:40:01 GMT+0000 (UTC)  source=console
INFO[12:50:01] Load finished at:              Fri Nov 08 2024 12:50:01 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 748 GB 1.2 GB/s
     aws_obj_get_duration...: avg=588.53ms min=29.11ms  med=530.28ms max=5.08s p(90)=1.08s p(95)=1.27s
     aws_obj_get_success....: 713702 1188.247332/s
     data_received..........: 748 GB 1.2 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=588.63ms min=196.31µs med=530.38ms max=5.08s p(90)=1.08s p(95)=1.27s
     iterations.............: 713702 1188.247332/s
     vus....................: 700    min=700       max=700

running (10m00.6s), 000/700 VUs, 713702 complete and 0 interrupted iterations
read ✓ [======================================] 700 VUs  10m0s

### 14 nodes 128mib write
INFO[13:03:36] Load started at:               Fri Nov 08 2024 13:03:36 GMT+0000 (UTC)  source=console
INFO[13:13:41] Load finished at:              Fri Nov 08 2024 13:13:41 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 825 GB 1.4 GB/s
     aws_obj_put_duration...: avg=19.77s min=7.4s     med=18.15s max=1m35s p(90)=28.31s p(95)=33.14s
     aws_obj_put_success....: 6144   10.148812/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 825 GB 1.4 GB/s
     iteration_duration.....: avg=20.2s  min=176.03µs med=18.6s  max=1m36s p(90)=28.74s p(95)=33.61s
     iterations.............: 6143   10.14716/s
     vus....................: 0      min=0       max=210

running (10m05.4s), 000/210 VUs, 6143 complete and 176 interrupted iterations
write ✓ [======================================] 210 VUs  10m0s

INFO[13:03:38] Load started at:               Fri Nov 08 2024 13:03:38 GMT+0000 (UTC)  source=console
INFO[13:13:44] Load finished at:              Fri Nov 08 2024 13:13:44 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 833 GB 1.4 GB/s
     aws_obj_put_duration...: avg=19.65s min=6.84s    med=18.15s max=1m36s p(90)=27.8s  p(95)=32.76s
     aws_obj_put_success....: 6207   10.245828/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 833 GB 1.4 GB/s
     iteration_duration.....: avg=20.09s min=259.41µs med=18.6s  max=1m36s p(90)=28.24s p(95)=33.19s
     iterations.............: 6196   10.22767/s
     vus....................: 10     min=0       max=210

running (10m05.8s), 000/210 VUs, 6196 complete and 155 interrupted iterations
write ✓ [======================================] 210 VUs  10m0s

### 14 nodes 128mib read
INFO[13:16:56] Load started at:               Fri Nov 08 2024 13:16:56 GMT+0000 (UTC)  source=console
INFO[13:27:10] Load finished at:              Fri Nov 08 2024 13:27:10 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.0 TB 1.7 GB/s
     aws_obj_get_duration...: avg=16.17s min=2.26s    med=14.71s max=1m26s p(90)=24.92s p(95)=28.9s 
     aws_obj_get_success....: 7747   12.623153/s
     data_received..........: 1.1 TB 1.7 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=16.17s min=197.13µs med=14.71s max=1m26s p(90)=24.92s p(95)=28.89s
     iterations.............: 7747   12.623153/s
     vus....................: 2      min=2       max=210

running (10m13.7s), 000/210 VUs, 7747 complete and 136 interrupted iterations
read ✓ [======================================] 210 VUs  10m0s

INFO[13:16:54] Load started at:               Fri Nov 08 2024 13:16:54 GMT+0000 (UTC)  source=console
INFO[13:27:09] Load finished at:              Fri Nov 08 2024 13:27:09 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.1 TB 1.7 GB/s
     aws_obj_get_duration...: avg=15.76s min=1.06s    med=14.26s max=1m35s p(90)=24.45s p(95)=28.08s
     aws_obj_get_success....: 7942   12.927228/s
     data_received..........: 1.1 TB 1.8 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=15.76s min=277.99µs med=14.26s max=1m35s p(90)=24.45s p(95)=28.08s
     iterations.............: 7942   12.927228/s
     vus....................: 2      min=2       max=210

running (10m14.4s), 000/210 VUs, 7942 complete and 129 interrupted iterations
read ✓ [======================================] 210 VUs  10m0s

### 12 nodes 8kb write
INFO[14:33:28] Load started at:               Fri Nov 08 2024 14:33:28 GMT+0000 (UTC)  source=console
INFO[14:38:29] Load finished at:              Fri Nov 08 2024 14:38:29 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 5.5 GB 18 MB/s
     aws_obj_put_duration...: avg=408.94ms min=51.34ms  med=374.76ms max=6.57s p(90)=616.16ms p(95)=711.21ms
     aws_obj_put_success....: 669583 2223.022657/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 5.5 GB 18 MB/s
     iteration_duration.....: avg=417.05ms min=203.87µs med=382.7ms  max=6.57s p(90)=624.37ms p(95)=719.39ms
     iterations.............: 669583 2223.022657/s
     vus....................: 30     min=30        max=930

running (5m01.2s), 000/930 VUs, 669583 complete and 0 interrupted iterations
write ✓ [======================================] 930 VUs  5m0s

INFO[14:33:30] Load started at:               Fri Nov 08 2024 14:33:30 GMT+0000 (UTC)  source=console
INFO[14:38:30] Load finished at:              Fri Nov 08 2024 14:38:30 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 5.4 GB 18 MB/s
     aws_obj_put_duration...: avg=413.04ms min=65.77ms  med=380.44ms max=6.21s p(90)=616.09ms p(95)=709.02ms
     aws_obj_put_success....: 662449 2204.953592/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 5.4 GB 18 MB/s
     iteration_duration.....: avg=421.31ms min=215.65µs med=389.05ms max=6.22s p(90)=624.37ms p(95)=717.3ms 
     iterations.............: 662449 2204.953592/s
     vus....................: 930    min=930       max=930

running (5m00.4s), 000/930 VUs, 662449 complete and 0 interrupted iterations
write ✓ [======================================] 930 VUs  5m0s

### 12 nodes 8kb read
INFO[21:48:26] Load started at:               Tue Nov 12 2024 21:48:26 GMT+0000 (UTC)  source=console
INFO[21:58:27] Load finished at:              Tue Nov 12 2024 21:58:27 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 23 GB   38 MB/s
     aws_obj_get_duration...: avg=201.09ms min=13.21ms med=172.91ms max=1.38s p(90)=393.27ms p(95)=471.48ms
     aws_obj_get_success....: 2773747 4620.363272/s
     data_received..........: 23 GB   38 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=201.17ms min=1.22ms  med=172.99ms max=1.38s p(90)=393.36ms p(95)=471.56ms
     iterations.............: 2773747 4620.363272/s
     vus....................: 930     min=930       max=930

running (10m00.3s), 000/930 VUs, 2773747 complete and 0 interrupted iterations
read ✓ [======================================] 930 VUs  10m0s

INFO[21:48:25] Load started at:               Tue Nov 12 2024 21:48:25 GMT+0000 (UTC)  source=console
INFO[21:58:26] Load finished at:              Tue Nov 12 2024 21:58:26 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 23 GB   38 MB/s
     aws_obj_get_duration...: avg=200.44ms min=14.7ms  med=172.5ms  max=1.47s p(90)=391.57ms p(95)=469.19ms
     aws_obj_get_success....: 2782975 4633.697933/s
     data_received..........: 23 GB   38 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=200.52ms min=517.1µs med=172.58ms max=1.47s p(90)=391.65ms p(95)=469.28ms
     iterations.............: 2782975 4633.697933/s
     vus....................: 930     min=930       max=930
ERRO[21:58:26] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.6s), 000/930 VUs, 2782975 complete and 0 interrupted iterations
read ✓ [======================================] 930 VUs  10m0s

### 12 nodes 128kb write
INFO[20:28:07] Load started at:               Wed Nov 20 2024 20:28:07 GMT+0000 (UTC)  source=console
INFO[20:38:07] Load finished at:              Wed Nov 20 2024 20:38:07 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 152 GB  254 MB/s
     aws_obj_put_duration...: avg=454.93ms min=78.48ms  med=420.69ms max=6.04s p(90)=689.15ms p(95)=795.88ms
     aws_obj_put_success....: 1162918 1936.978889/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 152 GB  254 MB/s
     iteration_duration.....: avg=464.38ms min=190.11µs med=430.22ms max=6.05s p(90)=698.73ms p(95)=805.47ms
     iterations.............: 1162918 1936.978889/s
     vus....................: 900     min=900       max=900

running (10m00.4s), 000/900 VUs, 1162918 complete and 0 interrupted iterations
write ✓ [======================================] 900 VUs  10m0s

INFO[20:28:04] Load started at:               Wed Nov 20 2024 20:28:04 GMT+0000 (UTC)  source=console
INFO[20:38:05] Load finished at:              Wed Nov 20 2024 20:38:05 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 149 GB  248 MB/s
     aws_obj_put_duration...: avg=466.4ms  min=71.62ms  med=434.48ms max=5.61s p(90)=698.18ms p(95)=798.9ms 
     aws_obj_put_success....: 1135415 1889.684348/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 149 GB  248 MB/s
     iteration_duration.....: avg=475.74ms min=210.12µs med=443.78ms max=5.62s p(90)=707.65ms p(95)=808.17ms
     iterations.............: 1135415 1889.684348/s
     vus....................: 1       min=1         max=900

running (10m00.8s), 000/900 VUs, 1135415 complete and 0 interrupted iterations
write ✓ [======================================] 900 VUs  10m0s

### 12 nodes 128kb read
INFO[15:26:17] Load started at:               Fri Nov 08 2024 15:26:17 GMT+0000 (UTC)  source=console
INFO[15:36:17] Load finished at:              Fri Nov 08 2024 15:36:17 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 195 GB  324 MB/s
     aws_obj_get_duration...: avg=363.52ms min=15.93ms med=264.62ms max=5.41s p(90)=808.1ms  p(95)=1.05s
     aws_obj_get_fails......: 1       0.001665/s
     aws_obj_get_success....: 1485347 2472.508/s
     data_received..........: 195 GB  324 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=363.6ms  min=1.73ms  med=264.7ms  max=5.41s p(90)=808.19ms p(95)=1.05s
     iterations.............: 1485348 2472.509664/s
     vus....................: 900     min=900       max=900

running (10m00.7s), 000/900 VUs, 1485348 complete and 0 interrupted iterations
read ✓ [======================================] 900 VUs  10m0s

INFO[15:26:15] Load started at:               Fri Nov 08 2024 15:26:15 GMT+0000 (UTC)  source=console
INFO[15:36:16] Load finished at:              Fri Nov 08 2024 15:36:16 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 195 GB  323 MB/s
     aws_obj_get_duration...: avg=363.79ms min=15.88ms med=264.89ms max=5.62s p(90)=807.41ms p(95)=1.05s
     aws_obj_get_fails......: 3       0.004986/s
     aws_obj_get_success....: 1484554 2467.175157/s
     data_received..........: 195 GB  323 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=363.88ms min=1.82ms  med=264.97ms max=5.62s p(90)=807.49ms p(95)=1.05s
     iterations.............: 1484557 2467.180142/s
     vus....................: 59      min=59        max=900

running (10m01.7s), 000/900 VUs, 1484557 complete and 0 interrupted iterations
read ✓ [======================================] 900 VUs  10m0s

### 12 nodes 1mib write
INFO[15:39:50] Load started at:               Fri Nov 08 2024 15:39:50 GMT+0000 (UTC)  source=console
INFO[15:49:52] Load finished at:              Fri Nov 08 2024 15:49:52 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 297 GB 494 MB/s
     aws_obj_put_duration...: avg=1.25s min=60.72ms  med=1.16s max=6.4s  p(90)=2.17s p(95)=2.51s
     aws_obj_put_success....: 283534 470.98126/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 297 GB 494 MB/s
     iteration_duration.....: avg=1.27s min=352.38µs med=1.17s max=6.42s p(90)=2.19s p(95)=2.53s
     iterations.............: 283534 470.98126/s
     vus....................: 1      min=1       max=600

running (10m02.0s), 000/600 VUs, 283534 complete and 0 interrupted iterations
write ✓ [======================================] 600 VUs  10m0s

INFO[15:39:52] Load started at:               Fri Nov 08 2024 15:39:52 GMT+0000 (UTC)  source=console
INFO[15:49:53] Load finished at:              Fri Nov 08 2024 15:49:53 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 300 GB 499 MB/s
     aws_obj_put_duration...: avg=1.24s min=67.03ms  med=1.14s max=7.09s p(90)=2.16s p(95)=2.49s
     aws_obj_put_success....: 285951 476.040066/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 300 GB 499 MB/s
     iteration_duration.....: avg=1.25s min=419.67µs med=1.16s max=7.1s  p(90)=2.18s p(95)=2.51s
     iterations.............: 285951 476.040066/s
     vus....................: 600    min=600      max=600

running (10m00.7s), 000/600 VUs, 285951 complete and 0 interrupted iterations
write ✓ [======================================] 600 VUs  10m0s

### 12 nodes 1mib read
INFO[13:27:02] Load started at:               Mon Nov 18 2024 13:27:02 GMT+0000 (UTC)  source=console
INFO[13:37:03] Load finished at:              Mon Nov 18 2024 13:37:03 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 600 GB 999 MB/s
     aws_obj_put_duration...: avg=612.87ms min=91.35ms  med=600.89ms max=2.52s p(90)=863.16ms p(95)=947.36ms
     aws_obj_put_success....: 572581 952.957542/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 600 GB 999 MB/s
     iteration_duration.....: avg=629.03ms min=294.69µs med=617.1ms  max=2.54s p(90)=879.22ms p(95)=963.89ms
     iterations.............: 572581 952.957542/s
     vus....................: 7      min=7        max=600

running (10m00.8s), 000/600 VUs, 572581 complete and 0 interrupted iterations
write ✓ [======================================] 600 VUs  10m0s

INFO[13:27:04] Load started at:               Mon Nov 18 2024 13:27:04 GMT+0000 (UTC)  source=console
INFO[13:37:06] Load finished at:              Mon Nov 18 2024 13:37:06 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 595 GB 988 MB/s
     aws_obj_put_duration...: avg=620.6ms  min=111.8ms  med=606.61ms max=3.08s p(90)=868.39ms p(95)=953.22ms
     aws_obj_put_success....: 567285 942.091052/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 595 GB 987 MB/s
     iteration_duration.....: avg=636.61ms min=508.38µs med=622.67ms max=3.1s  p(90)=884.42ms p(95)=969.72ms
     iterations.............: 567285 942.091052/s
     vus....................: 598    min=598      max=600

running (10m02.2s), 000/600 VUs, 567285 complete and 0 interrupted iterations
write ✓ [======================================] 600 VUs  10m0s

### 12 nodes 128mib write
INFO[16:05:41] Load started at:               Fri Nov 08 2024 16:05:41 GMT+0000 (UTC)  source=console
INFO[16:15:46] Load finished at:              Fri Nov 08 2024 16:15:46 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 711 GB 1.2 GB/s
     aws_obj_put_duration...: avg=19.83s min=8.08s    med=19.12s max=59.64s p(90)=27.26s p(95)=30.2s 
     aws_obj_put_success....: 5294   8.738181/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 711 GB 1.2 GB/s
     iteration_duration.....: avg=20.26s min=177.29µs med=19.56s max=1m0s   p(90)=27.69s p(95)=30.62s
     iterations.............: 5287   8.726627/s
     vus....................: 4      min=0      max=180

running (10m05.8s), 000/180 VUs, 5287 complete and 125 interrupted iterations
write ✓ [======================================] 180 VUs  10m0s

INFO[16:05:39] Load started at:               Fri Nov 08 2024 16:05:39 GMT+0000 (UTC)  source=console
INFO[16:15:44] Load finished at:              Fri Nov 08 2024 16:15:44 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 700 GB 1.2 GB/s
     aws_obj_put_duration...: avg=20.05s min=7.66s    med=19.21s max=58.85s p(90)=27.35s p(95)=30.43s
     aws_obj_put_fails......: 2      0.003302/s
     aws_obj_put_success....: 5213   8.606576/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 700 GB 1.2 GB/s
     iteration_duration.....: avg=20.48s min=172.13µs med=19.66s max=59.27s p(90)=27.78s p(95)=30.87s
     iterations.............: 5211   8.603274/s
     vus....................: 0      min=0      max=180

running (10m05.7s), 000/180 VUs, 5211 complete and 142 interrupted iterations
write ✓ [======================================] 180 VUs  10m0s

### 12 nodes 128mib read
INFO[16:16:57] Load started at:               Fri Nov 08 2024 16:16:57 GMT+0000 (UTC)  source=console
INFO[16:27:09] Load finished at:              Fri Nov 08 2024 16:27:09 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 913 GB 1.5 GB/s
     aws_obj_get_duration...: avg=15.68s min=2.19s    med=14.73s max=1m17s p(90)=23.73s p(95)=27.2s
     aws_obj_get_success....: 6846   11.182056/s
     data_received..........: 926 GB 1.5 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=15.68s min=697.57µs med=14.73s max=1m17s p(90)=23.73s p(95)=27.2s
     iterations.............: 6846   11.182056/s
     vus....................: 2      min=2       max=180

running (10m12.2s), 000/180 VUs, 6846 complete and 95 interrupted iterations
read ✓ [======================================] 180 VUs  10m0s

INFO[16:16:55] Load started at:               Fri Nov 08 2024 16:16:55 GMT+0000 (UTC)  source=console
INFO[16:27:08] Load finished at:              Fri Nov 08 2024 16:27:08 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 924 GB 1.5 GB/s
     aws_obj_get_duration...: avg=15.48s min=1.88s    med=14.44s max=1m9s p(90)=23.22s p(95)=26.79s
     aws_obj_get_success....: 6924   11.289043/s
     data_received..........: 940 GB 1.5 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=15.48s min=237.44µs med=14.44s max=1m9s p(90)=23.22s p(95)=26.79s
     iterations.............: 6924   11.289043/s
     vus....................: 1      min=1       max=180

running (10m13.3s), 000/180 VUs, 6924 complete and 123 interrupted iterations
read ✓ [======================================] 180 VUs  10m0s

### 8 nodes 8kb write
INFO[10:38:44] Load started at:               Tue Nov 12 2024 10:38:44 GMT+0000 (UTC)  source=console
INFO[10:48:44] Load finished at:              Tue Nov 12 2024 10:48:44 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 7.6 GB 13 MB/s
     aws_obj_put_duration...: avg=393.52ms min=80.42ms  med=381.59ms max=2.13s p(90)=538.39ms p(95)=592.96ms
     aws_obj_put_success....: 926313 1543.326961/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 7.6 GB 13 MB/s
     iteration_duration.....: avg=401.62ms min=976.69µs med=389.72ms max=2.14s p(90)=546.53ms p(95)=601.15ms
     iterations.............: 926313 1543.326961/s
     vus....................: 620    min=620       max=620
ERRO[10:48:44] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.2s), 000/620 VUs, 926313 complete and 0 interrupted iterations
write ✓ [======================================] 620 VUs  10m0s

INFO[10:38:42] Load started at:               Tue Nov 12 2024 10:38:42 GMT+0000 (UTC)  source=console
INFO[10:48:43] Load finished at:              Tue Nov 12 2024 10:48:43 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 7.6 GB 13 MB/s
     aws_obj_put_duration...: avg=391.26ms min=77.26ms  med=379.41ms max=2.03s p(90)=535.67ms p(95)=589.54ms
     aws_obj_put_success....: 931443 1551.06849/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 7.6 GB 13 MB/s
     iteration_duration.....: avg=399.48ms min=192.78µs med=387.65ms max=2.04s p(90)=543.89ms p(95)=597.76ms
     iterations.............: 931443 1551.06849/s
     vus....................: 620    min=620      max=620

running (10m00.5s), 000/620 VUs, 931443 complete and 0 interrupted iterations
write ✓ [======================================] 620 VUs  10m0s

### 8 nodes 8kb read
INFO[11:10:15] Load started at:               Tue Nov 12 2024 11:10:15 GMT+0000 (UTC)  source=console
INFO[11:20:15] Load finished at:              Tue Nov 12 2024 11:20:15 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 12 GB   20 MB/s
     aws_obj_get_duration...: avg=257.73ms min=12.81ms med=119.48ms max=6.48s p(90)=602.91ms p(95)=1.01s
     aws_obj_get_success....: 1443172 2403.249404/s
     data_received..........: 12 GB   20 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=257.82ms min=1.27ms  med=119.57ms max=6.48s p(90)=603ms    p(95)=1.01s
     iterations.............: 1443172 2403.249404/s
     vus....................: 620     min=620       max=620

running (10m00.5s), 000/620 VUs, 1443172 complete and 0 interrupted iterations
read ✓ [======================================] 620 VUs  10m0s

INFO[11:10:13] Load started at:               Tue Nov 12 2024 11:10:13 GMT+0000 (UTC)  source=console
INFO[11:20:15] Load finished at:              Tue Nov 12 2024 11:20:15 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 12 GB   20 MB/s
     aws_obj_get_duration...: avg=257.17ms min=12.87ms  med=118.74ms max=7.16s p(90)=599.94ms p(95)=1.01s
     aws_obj_get_success....: 1446789 2404.315281/s
     data_received..........: 12 GB   20 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=257.25ms min=206.09µs med=118.82ms max=7.16s p(90)=600.03ms p(95)=1.01s
     iterations.............: 1446789 2404.315281/s
     vus....................: 49      min=49        max=620
ERRO[11:20:15] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m01.7s), 000/620 VUs, 1446789 complete and 0 interrupted iterations
read ✓ [======================================] 620 VUs  10m0s

### 8 nodes 128kb write
INFO[08:27:51] Load started at:               Thu Nov 21 2024 08:27:51 GMT+0000 (UTC)  source=console
INFO[08:37:51] Load finished at:              Thu Nov 21 2024 08:37:51 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 103 GB 172 MB/s
     aws_obj_put_duration...: avg=448.2ms  min=83.25ms med=433.67ms max=2.22s p(90)=625.84ms p(95)=693.27ms
     aws_obj_put_success....: 786669 1310.664615/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 103 GB 172 MB/s
     iteration_duration.....: avg=457.64ms min=2.72ms  med=443.1ms  max=2.23s p(90)=635.3ms  p(95)=702.67ms
     iterations.............: 786669 1310.664615/s
     vus....................: 600    min=600       max=600

running (10m00.2s), 000/600 VUs, 786669 complete and 0 interrupted iterations
write ✓ [======================================] 600 VUs  10m0s

INFO[08:27:50] Load started at:               Thu Nov 21 2024 08:27:50 GMT+0000 (UTC)  source=console
INFO[08:37:50] Load finished at:              Thu Nov 21 2024 08:37:50 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 103 GB 172 MB/s
     aws_obj_put_duration...: avg=448.52ms min=84.18ms  med=434.16ms max=2.06s p(90)=626.23ms p(95)=694.13ms
     aws_obj_put_success....: 786513 1309.494909/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 103 GB 172 MB/s
     iteration_duration.....: avg=457.84ms min=206.13µs med=443.48ms max=2.07s p(90)=635.55ms p(95)=703.43ms
     iterations.............: 786513 1309.494909/s
     vus....................: 600    min=600       max=600

running (10m00.6s), 000/600 VUs, 786513 complete and 0 interrupted iterations
write ✓ [======================================] 600 VUs  10m0s

### 8 nodes 128kb read
INFO[11:36:47] Load started at:               Tue Nov 12 2024 11:36:47 GMT+0000 (UTC)  source=console
INFO[11:46:47] Load finished at:              Tue Nov 12 2024 11:46:47 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 140 GB  234 MB/s
     aws_obj_get_duration...: avg=336.5ms  min=15.75ms  med=250.21ms max=4.69s p(90)=741.27ms p(95)=953.99ms
     aws_obj_get_success....: 1069623 1781.631297/s
     data_received..........: 140 GB  234 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=336.59ms min=190.95µs med=250.3ms  max=4.69s p(90)=741.36ms p(95)=954.09ms
     iterations.............: 1069623 1781.631297/s
     vus....................: 600     min=600       max=600

running (10m00.4s), 000/600 VUs, 1069623 complete and 0 interrupted iterations
read ✓ [======================================] 600 VUs  10m0s

INFO[11:36:45] Load started at:               Tue Nov 12 2024 11:36:45 GMT+0000 (UTC)  source=console
INFO[11:46:47] Load finished at:              Tue Nov 12 2024 11:46:47 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 140 GB  233 MB/s
     aws_obj_get_duration...: avg=337.22ms min=15.55ms  med=251.02ms max=4.83s p(90)=743.32ms p(95)=955.12ms
     aws_obj_get_success....: 1067700 1774.387269/s
     data_received..........: 140 GB  233 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=337.31ms min=194.89µs med=251.11ms max=4.83s p(90)=743.41ms p(95)=955.21ms
     iterations.............: 1067700 1774.387269/s
     vus....................: 16      min=16        max=600
ERRO[11:46:47] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m01.7s), 000/600 VUs, 1067700 complete and 0 interrupted iterations
read ✓ [======================================] 600 VUs  10m0s

### 8 nodes 1mib write
INFO[15:57:16] Load started at:               Mon Nov 18 2024 15:57:16 GMT+0000 (UTC)  source=console
INFO[16:07:17] Load finished at:              Mon Nov 18 2024 16:07:17 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 387 GB 645 MB/s
     aws_obj_put_duration...: avg=633.34ms min=70.1ms   med=634.71ms max=4.14s p(90)=872.79ms p(95)=947.22ms
     aws_obj_put_success....: 369293 614.609388/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 387 GB 644 MB/s
     iteration_duration.....: avg=650.07ms min=916.44µs med=651.38ms max=4.17s p(90)=889.56ms p(95)=964.22ms
     iterations.............: 369293 614.609388/s
     vus....................: 1      min=1        max=400

running (10m00.9s), 000/400 VUs, 369293 complete and 0 interrupted iterations
write ✓ [======================================] 400 VUs  10m0s

INFO[15:57:30] Load started at:               Mon Nov 18 2024 15:57:30 GMT+0000 (UTC)  source=console
INFO[16:07:30] Load finished at:              Mon Nov 18 2024 16:07:30 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 390 GB 649 MB/s
     aws_obj_put_duration...: avg=629.71ms min=67.15ms  med=628.56ms max=4.15s p(90)=865.56ms p(95)=941.03ms
     aws_obj_put_success....: 371412 618.731687/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 389 GB 649 MB/s
     iteration_duration.....: avg=646.27ms min=324.46µs med=645.02ms max=4.17s p(90)=882.1ms  p(95)=958.04ms
     iterations.............: 371412 618.731687/s
     vus....................: 400    min=400      max=400

running (10m00.3s), 000/400 VUs, 371412 complete and 0 interrupted iterations
write ✓ [======================================] 400 VUs  10m0s


### 8 nodes 1mib read
INFO[12:28:05] Load started at:               Tue Nov 12 2024 12:28:05 GMT+0000 (UTC)  source=console
INFO[12:38:05] Load finished at:              Tue Nov 12 2024 12:38:05 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 575 GB 959 MB/s
     aws_obj_get_duration...: avg=437.31ms min=35.71ms  med=414.62ms max=3.16s p(90)=686.55ms p(95)=778.17ms
     aws_obj_get_success....: 548741 914.122091/s
     data_received..........: 575 GB 958 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=437.41ms min=234.15µs med=414.72ms max=3.16s p(90)=686.64ms p(95)=778.27ms
     iterations.............: 548741 914.122091/s
     vus....................: 400    min=400      max=400

running (10m00.3s), 000/400 VUs, 548741 complete and 0 interrupted iterations
read ✓ [======================================] 400 VUs  10m0s

INFO[12:28:02] Load started at:               Tue Nov 12 2024 12:28:02 GMT+0000 (UTC)  source=console
INFO[12:38:03] Load finished at:              Tue Nov 12 2024 12:38:03 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 580 GB 965 MB/s
     aws_obj_get_duration...: avg=434.32ms min=37.43ms  med=411.49ms max=3.37s p(90)=684.22ms p(95)=776.06ms
     aws_obj_get_success....: 552636 919.999063/s
     data_received..........: 579 GB 965 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=434.42ms min=176.04µs med=411.58ms max=3.37s p(90)=684.31ms p(95)=776.16ms
     iterations.............: 552636 919.999063/s
     vus....................: 400    min=400      max=400
ERRO[12:38:03] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.7s), 000/400 VUs, 552636 complete and 0 interrupted iterations
read ✓ [======================================] 400 VUs  10m0s

### 8 nodes 128mib write
INFO[12:55:38] Load started at:               Tue Nov 12 2024 12:55:38 GMT+0000 (UTC)  source=console
INFO[13:05:43] Load finished at:              Tue Nov 12 2024 13:05:43 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 618 GB 1.0 GB/s
     aws_obj_put_duration...: avg=15.09s min=7.15s    med=13.3s  max=1m23s p(90)=21.19s p(95)=25.62s
     aws_obj_put_fails......: 3      0.004954/s
     aws_obj_put_success....: 4605   7.603956/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 618 GB 1.0 GB/s
     iteration_duration.....: avg=15.53s min=197.25µs med=13.73s max=1m24s p(90)=21.64s p(95)=26.17s
     iterations.............: 4598   7.592397/s
     vus....................: 78     min=0      max=120
ERRO[13:05:43] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m05.6s), 000/120 VUs, 4598 complete and 77 interrupted iterations
write ✓ [======================================] 120 VUs  10m0s

INFO[12:55:36] Load started at:               Tue Nov 12 2024 12:55:36 GMT+0000 (UTC)  source=console
INFO[13:05:41] Load finished at:              Tue Nov 12 2024 13:05:41 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 617 GB 1.0 GB/s
     aws_obj_put_duration...: avg=15.13s min=6.91s    med=13.35s max=1m23s p(90)=21.04s p(95)=26.65s
     aws_obj_put_fails......: 7      0.011556/s
     aws_obj_put_success....: 4594   7.584092/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 617 GB 1.0 GB/s
     iteration_duration.....: avg=15.57s min=193.91µs med=13.78s max=1m24s p(90)=21.53s p(95)=27.17s
     iterations.............: 4596   7.587394/s
     vus....................: 84     min=0      max=120

running (10m05.7s), 000/120 VUs, 4596 complete and 80 interrupted iterations
write ✓ [======================================] 120 VUs  10m0s

### 8 nodes 128mib read
INFO[13:11:08] Load started at:               Tue Nov 12 2024 13:11:08 GMT+0000 (UTC)  source=console
INFO[13:21:21] Load finished at:              Tue Nov 12 2024 13:21:21 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 833 GB 1.4 GB/s
     aws_obj_get_duration...: avg=11.3s min=2.27s    med=8.54s max=4m1s p(90)=16.55s p(95)=24.38s
     aws_obj_get_success....: 6259   10.213472/s
     data_received..........: 841 GB 1.4 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=11.3s min=288.26µs med=8.53s max=4m1s p(90)=16.55s p(95)=24.38s
     iterations.............: 6259   10.213472/s
     vus....................: 11     min=11      max=120

running (10m12.8s), 000/120 VUs, 6259 complete and 59 interrupted iterations
read ✓ [======================================] 120 VUs  10m0s

INFO[13:11:11] Load started at:               Tue Nov 12 2024 13:11:11 GMT+0000 (UTC)  source=console
INFO[13:21:21] Load finished at:              Tue Nov 12 2024 13:21:21 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 798 GB 1.3 GB/s
     aws_obj_get_duration...: avg=11.76s min=1.78s    med=8.69s max=3m57s p(90)=16.96s p(95)=27.88s
     aws_obj_get_success....: 6023   9.871781/s
     data_received..........: 803 GB 1.3 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=11.75s min=325.82µs med=8.69s max=3m57s p(90)=16.95s p(95)=27.86s
     iterations.............: 6023   9.871781/s
     vus....................: 2      min=2      max=120
ERRO[13:21:21] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m10.1s), 000/120 VUs, 6023 complete and 34 interrupted iterations
read ✓ [======================================] 120 VUs  10m0s

### 6 nodes 8kb write
INFO[13:39:59] Load started at:               Tue Nov 12 2024 13:39:59 GMT+0000 (UTC)  source=console
INFO[13:49:59] Load finished at:              Tue Nov 12 2024 13:49:59 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 5.8 GB 9.7 MB/s
     aws_obj_put_duration...: avg=383.49ms min=97.39ms med=373.79ms max=1.34s p(90)=509.4ms  p(95)=556.17ms
     aws_obj_put_success....: 712260 1186.741571/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 5.8 GB 9.7 MB/s
     iteration_duration.....: avg=391.74ms min=211.2µs med=381.98ms max=1.35s p(90)=517.68ms p(95)=564.51ms
     iterations.............: 712260 1186.741571/s
     vus....................: 465    min=465       max=465

running (10m00.2s), 000/465 VUs, 712260 complete and 0 interrupted iterations
write ✓ [======================================] 465 VUs  10m0s

INFO[13:39:57] Load started at:               Tue Nov 12 2024 13:39:57 GMT+0000 (UTC)  source=console
INFO[13:49:57] Load finished at:              Tue Nov 12 2024 13:49:57 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 5.8 GB 9.7 MB/s
     aws_obj_put_duration...: avg=383.17ms min=66.73ms  med=373.46ms max=1.35s p(90)=509.34ms p(95)=556.22ms
     aws_obj_put_success....: 713194 1187.556663/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 5.8 GB 9.7 MB/s
     iteration_duration.....: avg=391.3ms  min=945.33µs med=381.67ms max=1.36s p(90)=517.54ms p(95)=564.5ms 
     iterations.............: 713194 1187.556663/s
     vus....................: 465    min=465       max=465
ERRO[13:49:57] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.6s), 000/465 VUs, 713194 complete and 0 interrupted iterations
write ✓ [======================================] 465 VUs  10m0s

### 6 nodes 8kb read
INFO[14:03:31] Load started at:               Tue Nov 12 2024 14:03:31 GMT+0000 (UTC)  source=console
INFO[14:13:32] Load finished at:              Tue Nov 12 2024 14:13:32 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 8.8 GB  15 MB/s
     aws_obj_get_duration...: avg=260.43ms min=14.05ms  med=134.87ms max=6.3s p(90)=574.94ms p(95)=1.02s
     aws_obj_get_success....: 1071193 1782.035313/s
     data_received..........: 8.8 GB  15 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=260.51ms min=184.35µs med=134.96ms max=6.3s p(90)=575.03ms p(95)=1.02s
     iterations.............: 1071193 1782.035313/s
     vus....................: 7       min=7         max=465

running (10m01.1s), 000/465 VUs, 1071193 complete and 0 interrupted iterations
read ✓ [======================================] 465 VUs  10m0s

INFO[14:03:29] Load started at:               Tue Nov 12 2024 14:03:29 GMT+0000 (UTC)  source=console
INFO[14:13:32] Load finished at:              Tue Nov 12 2024 14:13:32 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 8.7 GB  15 MB/s
     aws_obj_get_duration...: avg=261.37ms min=14.7ms   med=135.69ms max=6.01s p(90)=576.19ms p(95)=1.02s
     aws_obj_get_success....: 1067639 1771.39521/s
     data_received..........: 8.7 GB  15 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=261.46ms min=251.46µs med=135.77ms max=6.01s p(90)=576.28ms p(95)=1.02s
     iterations.............: 1067639 1771.39521/s
     vus....................: 5       min=5        max=465
ERRO[14:13:32] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m02.7s), 000/465 VUs, 1067639 complete and 0 interrupted iterations
read ✓ [======================================] 465 VUs  10m0s

### 6 nodes 128kb write
INFO[09:03:04] Load started at:               Thu Nov 21 2024 09:03:04 GMT+0000 (UTC)  source=console
INFO[09:13:05] Load finished at:              Thu Nov 21 2024 09:13:05 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 78 GB  129 MB/s
     aws_obj_put_duration...: avg=446.93ms min=92.82ms  med=436.36ms max=2.43s p(90)=617.25ms p(95)=680.78ms
     aws_obj_put_success....: 591620 985.593171/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 78 GB  129 MB/s
     iteration_duration.....: avg=456.41ms min=206.17µs med=445.81ms max=2.44s p(90)=626.82ms p(95)=690.47ms
     iterations.............: 591620 985.593171/s
     vus....................: 450    min=450      max=450

running (10m00.3s), 000/450 VUs, 591620 complete and 0 interrupted iterations
write ✓ [======================================] 450 VUs  10m0s

INFO[09:03:03] Load started at:               Thu Nov 21 2024 09:03:03 GMT+0000 (UTC)  source=console
INFO[09:13:04] Load finished at:              Thu Nov 21 2024 09:13:04 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 78 GB  129 MB/s
     aws_obj_put_duration...: avg=446.04ms min=81.08ms  med=434.73ms max=2.61s p(90)=618.57ms p(95)=684.25ms
     aws_obj_put_success....: 593112 987.055248/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 78 GB  129 MB/s
     iteration_duration.....: avg=455.41ms min=211.77µs med=444.31ms max=2.61s p(90)=627.94ms p(95)=693.68ms
     iterations.............: 593112 987.055248/s
     vus....................: 1      min=1        max=450

running (10m00.9s), 000/450 VUs, 593112 complete and 0 interrupted iterations
write ✓ [======================================] 450 VUs  10m0s

### 6 nodes 128kb read
INFO[14:30:50] Load started at:               Tue Nov 12 2024 14:30:50 GMT+0000 (UTC)  source=console
INFO[14:40:50] Load finished at:              Tue Nov 12 2024 14:40:50 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 115 GB 191 MB/s
     aws_obj_get_duration...: avg=308.87ms min=15.69ms  med=246.97ms max=3.41s p(90)=643.51ms p(95)=804.16ms
     aws_obj_get_success....: 873938 1455.446493/s
     data_received..........: 115 GB 191 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=308.96ms min=574.85µs med=247.05ms max=3.41s p(90)=643.59ms p(95)=804.26ms
     iterations.............: 873938 1455.446493/s
     vus....................: 450    min=450       max=450

running (10m00.5s), 000/450 VUs, 873938 complete and 0 interrupted iterations
read ✓ [======================================] 450 VUs  10m0s

INFO[14:30:48] Load started at:               Tue Nov 12 2024 14:30:48 GMT+0000 (UTC)  source=console
INFO[14:40:50] Load finished at:              Tue Nov 12 2024 14:40:50 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 114 GB 190 MB/s
     aws_obj_get_duration...: avg=309.51ms min=15.9ms   med=247.58ms max=3.31s p(90)=643.7ms  p(95)=807.9ms 
     aws_obj_get_success....: 872443 1451.163046/s
     data_received..........: 114 GB 190 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=309.6ms  min=399.91µs med=247.68ms max=3.31s p(90)=643.79ms p(95)=807.98ms
     iterations.............: 872443 1451.163046/s
     vus....................: 23     min=23        max=450
ERRO[14:40:50] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m01.2s), 000/450 VUs, 872443 complete and 0 interrupted iterations
read ✓ [======================================] 450 VUs  10m0s

### 6 nodes 1mib write
INFO[19:35:22] Load started at:               Mon Nov 18 2024 19:35:22 GMT+0000 (UTC)  source=console
INFO[19:45:22] Load finished at:              Mon Nov 18 2024 19:45:22 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 276 GB 460 MB/s
     aws_obj_put_duration...: avg=667.11ms min=107.54ms med=671.27ms max=1.68s p(90)=881.42ms p(95)=951.19ms
     aws_obj_put_success....: 263144 438.34781/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 276 GB 459 MB/s
     iteration_duration.....: avg=684.25ms min=333.67µs med=688.1ms  max=1.7s  p(90)=898.92ms p(95)=968.97ms
     iterations.............: 263144 438.34781/s
     vus....................: 300    min=300     max=300

running (10m00.3s), 000/300 VUs, 263144 complete and 0 interrupted iterations
write ✓ [======================================] 300 VUs  10m0s

INFO[19:35:20] Load started at:               Mon Nov 18 2024 19:35:20 GMT+0000 (UTC)  source=console
INFO[19:45:21] Load finished at:              Mon Nov 18 2024 19:45:21 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 276 GB 460 MB/s
     aws_obj_put_duration...: avg=666.82ms min=73.71ms  med=671.29ms max=1.59s p(90)=881.12ms p(95)=950.38ms
     aws_obj_put_success....: 263314 438.404379/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 276 GB 460 MB/s
     iteration_duration.....: avg=683.78ms min=280.89µs med=688.01ms max=1.61s p(90)=898.1ms  p(95)=968.05ms
     iterations.............: 263314 438.404379/s
     vus....................: 300    min=300      max=300

running (10m00.6s), 000/300 VUs, 263314 complete and 0 interrupted iterations
write ✓ [======================================] 300 VUs  10m0s

### 6 nodes 1mib read
INFO[14:54:34] Load started at:               Tue Nov 12 2024 14:54:34 GMT+0000 (UTC)  source=console
INFO[15:04:34] Load finished at:              Tue Nov 12 2024 15:04:34 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 340 GB 566 MB/s
     aws_obj_get_duration...: avg=555.27ms min=29.67ms  med=486.92ms max=4.69s p(90)=1.06s p(95)=1.27s
     aws_obj_get_success....: 324146 539.995356/s
     data_received..........: 340 GB 566 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=555.36ms min=331.23µs med=487.03ms max=4.69s p(90)=1.06s p(95)=1.27s
     iterations.............: 324146 539.995356/s
     vus....................: 300    min=300      max=300

running (10m00.3s), 000/300 VUs, 324146 complete and 0 interrupted iterations
read ✓ [======================================] 300 VUs  10m0s

INFO[14:54:33] Load started at:               Tue Nov 12 2024 14:54:33 GMT+0000 (UTC)  source=console
INFO[15:04:34] Load finished at:              Tue Nov 12 2024 15:04:34 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 340 GB 565 MB/s
     aws_obj_get_duration...: avg=555.5ms  min=29.82ms med=488.06ms max=4.17s p(90)=1.06s p(95)=1.26s
     aws_obj_get_success....: 324156 538.904524/s
     data_received..........: 340 GB 565 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=555.59ms min=200.6µs med=488.16ms max=4.17s p(90)=1.06s p(95)=1.26s
     iterations.............: 324156 538.904524/s
     vus....................: 9      min=9        max=300
ERRO[15:04:34] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m01.5s), 000/300 VUs, 324156 complete and 0 interrupted iterations
read ✓ [======================================] 300 VUs  10m0s

### 6 nodes 128mib write

INFO[15:18:17] Load started at:               Tue Nov 12 2024 15:18:17 GMT+0000 (UTC)  source=console
INFO[15:28:22] Load finished at:              Tue Nov 12 2024 15:28:22 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 478 GB 789 MB/s
     aws_obj_put_duration...: avg=14.53s min=6.2s     med=13.17s max=1m13s p(90)=19.43s p(95)=23.79s
     aws_obj_put_fails......: 2      0.003302/s
     aws_obj_put_success....: 3560   5.876874/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 478 GB 789 MB/s
     iteration_duration.....: avg=14.96s min=192.74µs med=13.61s max=1m14s p(90)=19.85s p(95)=24.23s
     iterations.............: 3559   5.875223/s
     vus....................: 51     min=0      max=90

running (10m05.8s), 00/90 VUs, 3559 complete and 51 interrupted iterations
write ✓ [======================================] 90 VUs  10m0s

INFO[15:18:15] Load started at:               Tue Nov 12 2024 15:18:15 GMT+0000 (UTC)  source=console
INFO[15:28:20] Load finished at:              Tue Nov 12 2024 15:28:20 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 480 GB 793 MB/s
     aws_obj_put_duration...: avg=14.55s min=6.16s    med=13.11s max=1m12s p(90)=19.53s p(95)=24.15s
     aws_obj_put_fails......: 1      0.001651/s
     aws_obj_put_success....: 3579   5.909418/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 480 GB 793 MB/s
     iteration_duration.....: avg=14.97s min=178.56µs med=13.54s max=1m13s p(90)=19.96s p(95)=24.58s
     iterations.............: 3576   5.904464/s
     vus....................: 62     min=0      max=90
ERRO[15:28:21] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m05.6s), 00/90 VUs, 3576 complete and 62 interrupted iterations
write ✓ [======================================] 90 VUs  10m0s

### 6 nodes 128mib read
INFO[15:29:58] Load started at:               Tue Nov 12 2024 15:29:58 GMT+0000 (UTC)  source=console
INFO[15:40:06] Load finished at:              Tue Nov 12 2024 15:40:06 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 686 GB 1.1 GB/s
     aws_obj_get_duration...: avg=10.32s min=1.83s    med=7.27s max=1m58s p(90)=15.32s p(95)=31.62s
     aws_obj_get_success....: 5193   8.544975/s
     data_received..........: 689 GB 1.1 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=10.32s min=248.65µs med=7.27s max=1m58s p(90)=15.31s p(95)=31.62s
     iterations.............: 5193   8.544975/s
     vus....................: 6      min=6      max=90

running (10m07.7s), 00/90 VUs, 5193 complete and 19 interrupted iterations
read ✓ [======================================] 90 VUs  10m0s

INFO[15:29:56] Load started at:               Tue Nov 12 2024 15:29:56 GMT+0000 (UTC)  source=console
INFO[15:40:06] Load finished at:              Tue Nov 12 2024 15:40:06 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 657 GB 1.1 GB/s
     aws_obj_get_duration...: avg=10.79s min=1.68s   med=7.58s max=2m0s p(90)=15.24s p(95)=35.75s
     aws_obj_get_success....: 4968   8.150106/s
     data_received..........: 660 GB 1.1 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=10.78s min=366.5µs med=7.58s max=2m0s p(90)=15.23s p(95)=35.75s
     iterations.............: 4968   8.150106/s
     vus....................: 7      min=7      max=90
ERRO[15:40:06] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m09.6s), 00/90 VUs, 4968 complete and 26 interrupted iterations
read ✓ [======================================] 90 VUs  10m0s

### 4 nodes 8kb write
INFO[16:10:10] Load started at:               Tue Nov 12 2024 16:10:10 GMT+0000 (UTC)  source=console
INFO[16:20:10] Load finished at:              Tue Nov 12 2024 16:20:10 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 3.5 GB 5.9 MB/s
     aws_obj_put_duration...: avg=437.22ms min=57.34ms  med=376.55ms max=1.77s p(90)=772ms    p(95)=884.57ms
     aws_obj_put_success....: 430836 717.81308/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 3.5 GB 5.9 MB/s
     iteration_duration.....: avg=445.69ms min=254.84µs med=385.05ms max=1.78s p(90)=780.57ms p(95)=893.27ms
     iterations.............: 430836 717.81308/s
     vus....................: 320    min=320     max=320

running (10m00.2s), 000/320 VUs, 430836 complete and 0 interrupted iterations
write ✓ [======================================] 320 VUs  10m0s

INFO[16:10:08] Load started at:               Tue Nov 12 2024 16:10:08 GMT+0000 (UTC)  source=console
INFO[16:20:08] Load finished at:              Tue Nov 12 2024 16:20:08 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 3.5 GB 5.9 MB/s
     aws_obj_put_duration...: avg=438.14ms min=48.02ms med=378.12ms max=2.15s p(90)=774.32ms p(95)=887.84ms
     aws_obj_put_success....: 430134 716.411524/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 3.5 GB 5.9 MB/s
     iteration_duration.....: avg=446.46ms min=1.66ms  med=386.46ms max=2.17s p(90)=782.6ms  p(95)=896.14ms
     iterations.............: 430134 716.411524/s
     vus....................: 320    min=320      max=320
ERRO[16:20:09] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.4s), 000/320 VUs, 430134 complete and 0 interrupted iterations
write ✓ [======================================] 320 VUs  10m0s

### 4 nodes 8kb read
INFO[16:34:57] Load started at:               Tue Nov 12 2024 16:34:57 GMT+0000 (UTC)  source=console
INFO[16:44:57] Load finished at:              Tue Nov 12 2024 16:44:57 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 4.1 GB 6.8 MB/s
     aws_obj_get_duration...: avg=382.81ms min=13.95ms  med=258.86ms max=4.29s p(90)=903.99ms p(95)=1.17s
     aws_obj_get_success....: 501576 834.995436/s
     data_received..........: 4.1 GB 6.8 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=382.9ms  min=314.73µs med=258.95ms max=4.29s p(90)=904.08ms p(95)=1.17s
     iterations.............: 501576 834.995436/s
     vus....................: 320    min=320      max=320

running (10m00.7s), 000/320 VUs, 501576 complete and 0 interrupted iterations
read ✓ [======================================] 320 VUs  10m0s

INFO[16:34:54] Load started at:               Tue Nov 12 2024 16:34:54 GMT+0000 (UTC)  source=console
INFO[16:44:56] Load finished at:              Tue Nov 12 2024 16:44:56 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 4.1 GB 6.8 MB/s
     aws_obj_get_duration...: avg=382.83ms min=13.95ms  med=258.24ms max=4.49s p(90)=905.24ms p(95)=1.17s
     aws_obj_get_success....: 501610 834.207076/s
     data_received..........: 4.1 GB 6.8 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=382.92ms min=178.96µs med=258.34ms max=4.49s p(90)=905.34ms p(95)=1.17s
     iterations.............: 501610 834.207076/s
     vus....................: 12     min=12       max=320
ERRO[16:44:56] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m01.3s), 000/320 VUs, 501610 complete and 0 interrupted iterations
read ✓ [======================================] 320 VUs  10m0s

### 4 nodes 128kb write
INFO[09:27:12] Load started at:               Thu Nov 21 2024 09:27:12 GMT+0000 (UTC)  source=console
INFO[09:37:12] Load finished at:              Thu Nov 21 2024 09:37:12 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 58 GB  96 MB/s
     aws_obj_put_duration...: avg=398.59ms min=47.65ms  med=353.86ms max=11.51s p(90)=608.76ms p(95)=702.93ms
     aws_obj_put_success....: 441055 734.865838/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 58 GB  96 MB/s
     iteration_duration.....: avg=408.13ms min=202.46µs med=363.47ms max=11.52s p(90)=618.25ms p(95)=712.65ms
     iterations.............: 441055 734.865838/s
     vus....................: 300    min=300      max=300

running (10m00.2s), 000/300 VUs, 441055 complete and 0 interrupted iterations
write ✓ [======================================] 300 VUs  10m0s

INFO[09:27:07] Load started at:               Thu Nov 21 2024 09:27:07 GMT+0000 (UTC)  source=console
INFO[09:37:08] Load finished at:              Thu Nov 21 2024 09:37:08 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 56 GB  94 MB/s
     aws_obj_put_duration...: avg=409.56ms min=52.45ms  med=361.88ms max=11.46s p(90)=619.15ms p(95)=713.92ms
     aws_obj_put_success....: 429687 715.487067/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 56 GB  94 MB/s
     iteration_duration.....: avg=418.98ms min=325.67µs med=371.25ms max=11.47s p(90)=628.53ms p(95)=723.37ms
     iterations.............: 429687 715.487067/s
     vus....................: 300    min=300      max=300

running (10m00.6s), 000/300 VUs, 429687 complete and 0 interrupted iterations
write ✓ [======================================] 300 VUs  10m0s

### 4 nodes 128kb read
INFO[17:00:51] Load started at:               Tue Nov 12 2024 17:00:51 GMT+0000 (UTC)  source=console
INFO[17:10:52] Load finished at:              Tue Nov 12 2024 17:10:52 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 76 GB  127 MB/s
     aws_obj_get_duration...: avg=309.62ms min=14.72ms  med=219.4ms max=5.12s p(90)=682.93ms p(95)=898.57ms
     aws_obj_get_success....: 581441 966.448925/s
     data_received..........: 76 GB  127 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=309.72ms min=260.91µs med=219.5ms max=5.12s p(90)=683.03ms p(95)=898.67ms
     iterations.............: 581441 966.448925/s
     vus....................: 25     min=25       max=300
ERRO[17:10:53] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m01.6s), 000/300 VUs, 581441 complete and 0 interrupted iterations
read ✓ [======================================] 300 VUs  10m0s

INFO[17:00:52] Load started at:               Tue Nov 12 2024 17:00:52 GMT+0000 (UTC)  source=console
INFO[17:10:53] Load finished at:              Tue Nov 12 2024 17:10:53 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 76 GB  127 MB/s
     aws_obj_get_duration...: avg=308.88ms min=15.09ms  med=218.46ms max=4.47s p(90)=683.36ms p(95)=900.94ms
     aws_obj_get_success....: 582649 970.097194/s
     data_received..........: 76 GB  127 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=308.98ms min=265.09µs med=218.55ms max=4.47s p(90)=683.45ms p(95)=901.04ms
     iterations.............: 582649 970.097194/s
     vus....................: 300    min=300      max=300

running (10m00.6s), 000/300 VUs, 582649 complete and 0 interrupted iterations
read ✓ [======================================] 300 VUs  10m0s

### 4 nodes 1mib write
INFO[20:17:16] Load started at:               Mon Nov 18 2024 20:17:16 GMT+0000 (UTC)  source=console
INFO[20:27:17] Load finished at:              Mon Nov 18 2024 20:27:17 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 204 GB 339 MB/s
     aws_obj_put_duration...: avg=599.93ms min=71.94ms  med=603.74ms max=1.54s p(90)=800.74ms p(95)=866.55ms
     aws_obj_put_success....: 194415 323.715269/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 204 GB 339 MB/s
     iteration_duration.....: avg=617.39ms min=363.54µs med=621.06ms max=1.56s p(90)=818.62ms p(95)=884.39ms
     iterations.............: 194415 323.715269/s
     vus....................: 200    min=200      max=200

running (10m00.6s), 000/200 VUs, 194415 complete and 0 interrupted iterations
write ✓ [======================================] 200 VUs  10m0s

INFO[20:17:18] Load started at:               Mon Nov 18 2024 20:17:18 GMT+0000 (UTC)  source=console
INFO[20:27:19] Load finished at:              Mon Nov 18 2024 20:27:19 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 204 GB 339 MB/s
     aws_obj_put_duration...: avg=600.85ms min=85.56ms med=603.82ms max=1.65s p(90)=801.98ms p(95)=867.59ms
     aws_obj_put_success....: 194055 323.259218/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 203 GB 339 MB/s
     iteration_duration.....: avg=618.48ms min=221.7µs med=621.26ms max=1.67s p(90)=819.63ms p(95)=885.73ms
     iterations.............: 194055 323.259218/s
     vus....................: 200    min=200      max=200

running (10m00.3s), 000/200 VUs, 194055 complete and 0 interrupted iterations
write ✓ [======================================] 200 VUs  10m0s


### 4 nodes 1mib read
INFO[17:34:44] Load started at:               Tue Nov 12 2024 17:34:44 GMT+0000 (UTC)  source=console
INFO[17:44:44] Load finished at:              Tue Nov 12 2024 17:44:44 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 251 GB 418 MB/s
     aws_obj_get_duration...: avg=501.17ms min=28.38ms med=407.8ms  max=4.87s p(90)=1.02s p(95)=1.26s
     aws_obj_get_success....: 239458 398.798256/s
     data_received..........: 251 GB 418 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=501.27ms min=2.66ms  med=407.88ms max=4.87s p(90)=1.02s p(95)=1.26s
     iterations.............: 239458 398.798256/s
     vus....................: 200    min=200      max=200

running (10m00.4s), 000/200 VUs, 239458 complete and 0 interrupted iterations
read ✓ [======================================] 200 VUs  10m0s

INFO[17:34:42] Load started at:               Tue Nov 12 2024 17:34:42 GMT+0000 (UTC)  source=console
INFO[17:44:43] Load finished at:              Tue Nov 12 2024 17:44:43 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 251 GB 418 MB/s
     aws_obj_get_duration...: avg=501.05ms min=23.6ms   med=408.51ms max=4.83s p(90)=1.02s p(95)=1.26s
     aws_obj_get_success....: 239655 398.394462/s
     data_received..........: 251 GB 418 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=501.15ms min=182.28µs med=408.6ms  max=4.83s p(90)=1.02s p(95)=1.26s
     iterations.............: 239655 398.394462/s
     vus....................: 59     min=59       max=200
ERRO[17:44:43] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m01.6s), 000/200 VUs, 239655 complete and 0 interrupted iterations
read ✓ [======================================] 200 VUs  10m0s

### 4 nodes 128mib write
INFO[20:41:01] Load started at:               Tue Nov 12 2024 20:41:01 GMT+0000 (UTC)  source=console
INFO[20:51:07] Load finished at:              Tue Nov 12 2024 20:51:07 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 325 GB 536 MB/s
     aws_obj_put_duration...: avg=14.4s  min=5.15s    med=13.05s max=1m23s p(90)=19.66s p(95)=25.51s
     aws_obj_put_success....: 2418   3.994011/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 325 GB 536 MB/s
     iteration_duration.....: avg=14.81s min=189.06µs med=13.47s max=1m24s p(90)=20.09s p(95)=25.89s
     iterations.............: 2418   3.994011/s
     vus....................: 37     min=37     max=60

running (10m05.4s), 00/60 VUs, 2418 complete and 35 interrupted iterations
write ✓ [======================================] 60 VUs  10m0s

INFO[20:41:03] Load started at:               Tue Nov 12 2024 20:41:03 GMT+0000 (UTC)  source=console
INFO[20:51:09] Load finished at:              Tue Nov 12 2024 20:51:09 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 325 GB 537 MB/s
     aws_obj_put_duration...: avg=14.4s  min=5.92s    med=13.07s max=1m19s p(90)=19.98s p(95)=24.82s
     aws_obj_put_success....: 2423   4.000034/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 325 GB 537 MB/s
     iteration_duration.....: avg=14.81s min=175.16µs med=13.49s max=1m20s p(90)=20.38s p(95)=25.19s
     iterations.............: 2419   3.99343/s
     vus....................: 1      min=1      max=60
ERRO[20:51:09] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m05.7s), 00/60 VUs, 2419 complete and 37 interrupted iterations
write ✓ [======================================] 60 VUs  10m0s

### 4 nodes 128mib read
INFO[20:52:50] Load started at:               Tue Nov 12 2024 20:52:50 GMT+0000 (UTC)  source=console
INFO[21:02:56] Load finished at:              Tue Nov 12 2024 21:02:56 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 490 GB 809 MB/s
     aws_obj_get_duration...: avg=9.87s min=2.77s    med=8.65s max=1m6s p(90)=15.16s p(95)=18.9s
     aws_obj_get_success....: 3654   6.025155/s
     data_received..........: 492 GB 812 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=9.86s min=355.48µs med=8.65s max=1m6s p(90)=15.16s p(95)=18.9s
     iterations.............: 3654   6.025155/s
     vus....................: 3      min=3      max=60

running (10m06.5s), 00/60 VUs, 3654 complete and 13 interrupted iterations
read ✓ [======================================] 60 VUs  10m0s

INFO[20:52:48] Load started at:               Tue Nov 12 2024 20:52:48 GMT+0000 (UTC)  source=console
INFO[21:02:56] Load finished at:              Tue Nov 12 2024 21:02:56 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 480 GB 789 MB/s
     aws_obj_get_duration...: avg=10.07s min=2.58s    med=8.98s max=1m9s p(90)=15.1s p(95)=18.27s
     aws_obj_get_success....: 3574   5.878762/s
     data_received..........: 484 GB 795 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=10.06s min=357.54µs med=8.98s max=1m9s p(90)=15.1s p(95)=18.26s
     iterations.............: 3574   5.878762/s
     vus....................: 16     min=16     max=60
ERRO[21:02:56] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m08.0s), 00/60 VUs, 3574 complete and 29 interrupted iterations
read ✓ [======================================] 60 VUs  10m0s

