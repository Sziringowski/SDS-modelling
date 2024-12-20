protection=EC2.1
HW_chassis=X205

### 16 nodes 8kb write
INFO[11:21:14] Load started at:               Tue Nov 05 2024 11:21:14 GMT+0000 (UTC)  source=console
INFO[11:31:17] Load finished at:              Tue Nov 05 2024 11:31:17 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 8.1 GB 13 MB/s
     aws_obj_put_duration...: avg=748.85ms min=44.74ms  med=413.1ms max=12.28s p(90)=1.8s  p(95)=2.91s
     aws_obj_put_success....: 985909 1634.879508/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 8.1 GB 13 MB/s
     iteration_duration.....: avg=757.3ms  min=223.73µs med=421.4ms max=12.3s  p(90)=1.81s p(95)=2.92s
     iterations.............: 985909 1634.879508/s
     vus....................: 792    min=792       max=1240

running (10m03.0s), 0000/1240 VUs, 985909 complete and 0 interrupted iterations
write ✓ [======================================] 1240 VUs  10m0s

INFO[11:20:41] Load started at:               Tue Nov 05 2024 11:20:41 GMT+0000 (UTC)  source=console
INFO[11:30:42] Load finished at:              Tue Nov 05 2024 11:30:42 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 7.7 GB 13 MB/s
     aws_obj_put_duration...: avg=782.15ms min=46.47ms med=430.92ms max=12.71s p(90)=1.95s p(95)=2.99s
     aws_obj_put_success....: 941504 1565.880436/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 7.7 GB 13 MB/s
     iteration_duration.....: avg=790.49ms min=200.5µs med=439.4ms  max=12.72s p(90)=1.96s p(95)=3s   
     iterations.............: 941504 1565.880436/s
     vus....................: 3      min=3         max=1240

running (10m01.3s), 0000/1240 VUs, 941504 complete and 0 interrupted iterations
write ✓ [======================================] 1240 VUs  10m0s

### 16 nodes 8kb read -
INFO[12:31:31] Load started at:               Tue Nov 05 2024 12:31:31 GMT+0000 (UTC)  source=console
INFO[12:41:32] Load finished at:              Tue Nov 05 2024 12:41:32 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 21 GB   34 MB/s
     aws_obj_get_duration...: avg=297.94ms min=13.47ms med=216.13ms max=19.78s p(90)=598.15ms p(95)=764.72ms
     aws_obj_get_success....: 2496670 4156.151253/s
     data_received..........: 20 GB   34 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=298.02ms min=204.8µs med=216.21ms max=19.78s p(90)=598.24ms p(95)=764.8ms 
     iterations.............: 2496670 4156.151253/s
     vus....................: 1240    min=1240      max=1240

running (10m00.7s), 0000/1240 VUs, 2496670 complete and 0 interrupted iterations
read ✓ [======================================] 1240 VUs  10m0s

INFO[12:31:16] Load started at:               Tue Nov 05 2024 12:31:16 GMT+0000 (UTC)  source=console
INFO[12:41:20] Load finished at:              Tue Nov 05 2024 12:41:20 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 20 GB   34 MB/s
     aws_obj_get_duration...: avg=298.62ms min=14.11ms  med=218.43ms max=24.62s p(90)=596.07ms p(95)=760.18ms
     aws_obj_get_success....: 2491971 4126.684397/s
     data_received..........: 20 GB   34 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=298.7ms  min=233.76µs med=218.51ms max=24.62s p(90)=596.15ms p(95)=760.27ms
     iterations.............: 2491971 4126.684397/s
     vus....................: 1       min=1         max=1240

running (10m03.9s), 0000/1240 VUs, 2491971 complete and 0 interrupted iterations
read ✓ [======================================] 1240 VUs  10m0s

### 16 nodes 128kb write
INFO[12:07:16] Load started at:               Tue Nov 05 2024 12:07:16 GMT+0000 (UTC)  source=console
INFO[12:17:17] Load finished at:              Tue Nov 05 2024 12:17:17 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 102 GB 170 MB/s
     aws_obj_put_duration...: avg=914.8ms  min=52.15ms  med=761.58ms max=11.46s p(90)=1.74s p(95)=2.12s
     aws_obj_put_success....: 779624 1296.190599/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 102 GB 170 MB/s
     iteration_duration.....: avg=924.25ms min=453.44µs med=770.9ms  max=11.47s p(90)=1.75s p(95)=2.13s
     iterations.............: 779624 1296.190599/s
     vus....................: 425    min=425       max=1200

running (10m01.5s), 0000/1200 VUs, 779624 complete and 0 interrupted iterations
write ✓ [======================================] 1200 VUs  10m0s

INFO[12:07:15] Load started at:               Tue Nov 05 2024 12:07:15 GMT+0000 (UTC)  source=console
INFO[12:17:17] Load finished at:              Tue Nov 05 2024 12:17:17 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 103 GB 171 MB/s
     aws_obj_put_duration...: avg=910.09ms min=54.25ms med=753.94ms max=10.51s p(90)=1.73s p(95)=2.11s
     aws_obj_put_success....: 784034 1301.202195/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 103 GB 170 MB/s
     iteration_duration.....: avg=919.42ms min=2.64ms  med=763.3ms  max=10.52s p(90)=1.74s p(95)=2.12s
     iterations.............: 784034 1301.202195/s
     vus....................: 171    min=171       max=1200

running (10m02.5s), 0000/1200 VUs, 784034 complete and 0 interrupted iterations
write ✓ [======================================] 1200 VUs  10m0s

### 16 nodes 128kb read
INFO[12:18:52] Load started at:               Tue Nov 05 2024 12:18:52 GMT+0000 (UTC)  source=console
INFO[12:28:52] Load finished at:              Tue Nov 05 2024 12:28:52 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 208 GB  347 MB/s
     aws_obj_get_duration...: avg=453.04ms min=16.59ms  med=361.66ms max=17.49s p(90)=896.2ms  p(95)=1.13s
     aws_obj_get_fails......: 71      0.11824/s
     aws_obj_get_success....: 1589187 2646.563246/s
     data_received..........: 208 GB  347 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=453.12ms min=204.33µs med=361.74ms max=17.49s p(90)=896.27ms p(95)=1.13s
     iterations.............: 1589258 2646.681486/s
     vus....................: 1200    min=1200      max=1200

running (10m00.5s), 0000/1200 VUs, 1589258 complete and 0 interrupted iterations
read ✓ [======================================] 1200 VUs  10m0s

INFO[12:18:52] Load started at:               Tue Nov 05 2024 12:18:52 GMT+0000 (UTC)  source=console
INFO[12:28:52] Load finished at:              Tue Nov 05 2024 12:28:52 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 211 GB  350 MB/s
     aws_obj_get_duration...: avg=448.51ms min=16.19ms  med=357.15ms max=16.76s p(90)=890.18ms p(95)=1.12s
     aws_obj_get_fails......: 49      0.081547/s
     aws_obj_get_success....: 1605612 2672.112975/s
     data_received..........: 210 GB  350 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=448.59ms min=227.26µs med=357.23ms max=16.76s p(90)=890.26ms p(95)=1.12s
     iterations.............: 1605661 2672.194522/s
     vus....................: 18      min=18        max=1200

running (10m00.9s), 0000/1200 VUs, 1605661 complete and 0 interrupted iterations
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
INFO[11:52:10] Load started at:               Wed Nov 06 2024 11:52:10 GMT+0000 (UTC)  source=console
INFO[12:02:11] Load finished at:              Wed Nov 06 2024 12:02:11 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 154 GB  257 MB/s
     aws_obj_put_duration...: avg=563.59ms min=47.89ms  med=376.98ms max=18.98s p(90)=917.27ms p(95)=1.27s
     aws_obj_put_success....: 1177982 1961.887692/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 154 GB  257 MB/s
     iteration_duration.....: avg=573.12ms min=210.62µs med=386.31ms max=19s    p(90)=926.96ms p(95)=1.28s
     iterations.............: 1177982 1961.887692/s
     vus....................: 1125    min=1125      max=1125

running (10m00.4s), 0000/1125 VUs, 1177982 complete and 0 interrupted iterations
write ✓ [======================================] 1125 VUs  10m0s

INFO[11:52:09] Load started at:               Wed Nov 06 2024 11:52:09 GMT+0000 (UTC)  source=console
INFO[12:02:10] Load finished at:              Wed Nov 06 2024 12:02:10 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 157 GB  261 MB/s
     aws_obj_put_duration...: avg=554.78ms min=52.59ms  med=370.5ms  max=18.2s  p(90)=941.35ms p(95)=1.29s
     aws_obj_put_success....: 1196621 1991.360605/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 157 GB  261 MB/s
     iteration_duration.....: avg=564.25ms min=306.97µs med=380.26ms max=18.21s p(90)=950.79ms p(95)=1.3s 
     iterations.............: 1196621 1991.360605/s
     vus....................: 10      min=10        max=1125

running (10m00.9s), 0000/1125 VUs, 1196621 complete and 0 interrupted iterations
write ✓ [======================================] 1125 VUs  10m0s

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
INFO[12:56:13] Load started at:               Wed Nov 06 2024 12:56:13 GMT+0000 (UTC)  source=console
INFO[13:06:14] Load finished at:              Wed Nov 06 2024 13:06:14 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 333 GB 555 MB/s
     aws_obj_put_duration...: avg=1.39s min=65.92ms  med=1.29s max=7.64s p(90)=2.43s p(95)=2.8s 
     aws_obj_put_success....: 317993 529.345462/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 333 GB 555 MB/s
     iteration_duration.....: avg=1.41s min=238.07µs med=1.31s max=7.66s p(90)=2.45s p(95)=2.82s
     iterations.............: 317993 529.345462/s
     vus....................: 25     min=25       max=750

running (10m00.7s), 000/750 VUs, 317993 complete and 0 interrupted iterations
write ✓ [======================================] 750 VUs  10m0s

INFO[12:56:06] Load started at:               Wed Nov 06 2024 12:56:06 GMT+0000 (UTC)  source=console
INFO[13:06:09] Load finished at:              Wed Nov 06 2024 13:06:09 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 340 GB 564 MB/s
     aws_obj_put_duration...: avg=1.37s min=65.11ms  med=1.27s max=6.9s  p(90)=2.38s p(95)=2.75s
     aws_obj_put_success....: 324124 537.358327/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 340 GB 563 MB/s
     iteration_duration.....: avg=1.38s min=198.03µs med=1.28s max=6.92s p(90)=2.4s  p(95)=2.77s
     iterations.............: 324124 537.358327/s
     vus....................: 1      min=1        max=750

running (10m03.2s), 000/750 VUs, 324124 complete and 0 interrupted iterations
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
INFO[13:56:15] Load finished at:              Thu Nov 07 2024 13:56:15 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 18 GB   30 MB/s
     aws_obj_get_duration...: avg=275.92ms min=13.04ms med=161.47ms max=7.84s p(90)=665.69ms p(95)=948.6ms 
     aws_obj_get_fails......: 336     0.559374/s
     aws_obj_get_success....: 2206270 3673.004931/s
     data_received..........: 18 GB   30 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=275.98ms min=1.83ms  med=161.53ms max=7.84s p(90)=665.71ms p(95)=948.64ms
     iterations.............: 2206606 3673.564305/s
     vus....................: 1015    min=1015      max=1015

running (10m00.7s), 0000/1015 VUs, 2206606 complete and 0 interrupted iterations
read ✓ [======================================] 1015 VUs  10m0s

INFO[13:56:09] Load finished at:              Thu Nov 07 2024 13:56:09 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 17 GB   29 MB/s
     aws_obj_get_duration...: avg=286.53ms min=13.24ms  med=169.11ms max=8.47s p(90)=692.37ms p(95)=982.87ms
     aws_obj_get_fails......: 268     0.445522/s
     aws_obj_get_success....: 2125174 3532.881018/s
     data_received..........: 17 GB   29 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=286.6ms  min=215.47µs med=169.17ms max=8.47s p(90)=692.42ms p(95)=982.89ms
     iterations.............: 2125442 3533.32654/s
     vus....................: 17      min=17        max=1015

running (10m01.5s), 0000/1015 VUs, 2125442 complete and 0 interrupted iterations
read ✓ [======================================] 1015 VUs  10m0s

### 14 nodes 128kb write
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
INFO[12:28:11] Load started at:               Fri Nov 08 2024 12:28:11 GMT+0000 (UTC)  source=console
INFO[12:38:13] Load finished at:              Fri Nov 08 2024 12:38:13 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 390 GB 648 MB/s
     aws_obj_put_duration...: avg=1.11s min=70.79ms  med=1.06s max=5.45s p(90)=1.73s p(95)=1.99s
     aws_obj_put_success....: 372166 617.834002/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 390 GB 648 MB/s
     iteration_duration.....: avg=1.12s min=187.54µs med=1.08s max=5.46s p(90)=1.75s p(95)=2.01s
     iterations.............: 372166 617.834002/s
     vus....................: 8      min=8        max=700

running (10m02.4s), 000/700 VUs, 372166 complete and 0 interrupted iterations
write ✓ [======================================] 700 VUs  10m0s

INFO[12:28:14] Load started at:               Fri Nov 08 2024 12:28:14 GMT+0000 (UTC)  source=console
INFO[12:38:15] Load finished at:              Fri Nov 08 2024 12:38:15 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 392 GB 652 MB/s
     aws_obj_put_duration...: avg=1.1s  min=70.64ms med=1.05s max=4.73s p(90)=1.73s p(95)=1.98s
     aws_obj_put_success....: 373478 621.897264/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 392 GB 652 MB/s
     iteration_duration.....: avg=1.12s min=327.2µs med=1.07s max=4.74s p(90)=1.74s p(95)=2s   
     iterations.............: 373478 621.897264/s
     vus....................: 700    min=700      max=700

running (10m00.5s), 000/700 VUs, 373478 complete and 0 interrupted iterations
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
INFO[15:13:11] Load started at:               Fri Nov 08 2024 15:13:11 GMT+0000 (UTC)  source=console
INFO[15:23:13] Load finished at:              Fri Nov 08 2024 15:23:13 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 83 GB  138 MB/s
     aws_obj_put_duration...: avg=843.05ms min=53.81ms med=721.04ms max=5.33s p(90)=1.64s p(95)=1.94s
     aws_obj_put_success....: 633933 1053.611034/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 83 GB  138 MB/s
     iteration_duration.....: avg=852.45ms min=191.1µs med=730.41ms max=5.34s p(90)=1.65s p(95)=1.95s
     iterations.............: 633933 1053.611034/s
     vus....................: 192    min=192       max=900

running (10m01.7s), 000/900 VUs, 633933 complete and 0 interrupted iterations
write ✓ [======================================] 900 VUs  10m0s

INFO[15:13:13] Load started at:               Fri Nov 08 2024 15:13:13 GMT+0000 (UTC)  source=console
INFO[15:23:13] Load finished at:              Fri Nov 08 2024 15:23:13 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 83 GB  139 MB/s
     aws_obj_put_duration...: avg=840.18ms min=52.97ms  med=719.28ms max=5.55s p(90)=1.63s p(95)=1.93s
     aws_obj_put_success....: 635843 1058.895931/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 83 GB  139 MB/s
     iteration_duration.....: avg=849.46ms min=241.14µs med=728.51ms max=5.56s p(90)=1.64s p(95)=1.94s
     iterations.............: 635843 1058.895931/s
     vus....................: 900    min=900       max=900

running (10m00.5s), 000/900 VUs, 635843 complete and 0 interrupted iterations
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
INFO[15:51:48] Load started at:               Fri Nov 08 2024 15:51:48 GMT+0000 (UTC)  source=console
INFO[16:01:49] Load finished at:              Fri Nov 08 2024 16:01:49 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 587 GB 976 MB/s
     aws_obj_get_duration...: avg=643.49ms min=28.64ms  med=540.4ms  max=5.97s p(90)=1.29s p(95)=1.58s
     aws_obj_get_success....: 559551 931.120316/s
     data_received..........: 587 GB 976 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=643.59ms min=209.85µs med=540.52ms max=5.97s p(90)=1.29s p(95)=1.58s
     iterations.............: 559551 931.120316/s
     vus....................: 15     min=15       max=600

running (10m00.9s), 000/600 VUs, 559551 complete and 0 interrupted iterations
read ✓ [======================================] 600 VUs  10m0s

INFO[15:51:46] Load started at:               Fri Nov 08 2024 15:51:46 GMT+0000 (UTC)  source=console
INFO[16:01:48] Load finished at:              Fri Nov 08 2024 16:01:48 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 591 GB 982 MB/s
     aws_obj_get_duration...: avg=638.86ms min=29.05ms med=536.75ms max=5.18s p(90)=1.29s p(95)=1.56s
     aws_obj_get_success....: 563767 936.873742/s
     data_received..........: 591 GB 982 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=638.95ms min=966.2µs med=536.85ms max=5.18s p(90)=1.29s p(95)=1.56s
     iterations.............: 563767 936.873742/s
     vus....................: 56     min=56       max=600

running (10m01.8s), 000/600 VUs, 563767 complete and 0 interrupted iterations
read ✓ [======================================] 600 VUs  10m0s

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
INFO[11:24:44] Load started at:               Tue Nov 12 2024 11:24:44 GMT+0000 (UTC)  source=console
INFO[11:34:45] Load finished at:              Tue Nov 12 2024 11:34:45 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 58 GB  97 MB/s
     aws_obj_put_duration...: avg=798.07ms min=52.8ms   med=697.96ms max=5.86s p(90)=1.5s  p(95)=1.79s
     aws_obj_put_success....: 445894 742.665522/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 58 GB  97 MB/s
     iteration_duration.....: avg=807.53ms min=248.79µs med=707.42ms max=5.87s p(90)=1.51s p(95)=1.8s 
     iterations.............: 445894 742.665522/s
     vus....................: 600    min=600      max=600

running (10m00.4s), 000/600 VUs, 445894 complete and 0 interrupted iterations
write ✓ [======================================] 600 VUs  10m0s

INFO[11:24:43] Load started at:               Tue Nov 12 2024 11:24:43 GMT+0000 (UTC)  source=console
INFO[11:34:45] Load finished at:              Tue Nov 12 2024 11:34:45 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 58 GB  97 MB/s
     aws_obj_put_duration...: avg=799.4ms  min=54.51ms  med=697.37ms max=5.54s p(90)=1.51s p(95)=1.79s
     aws_obj_put_success....: 445381 740.661269/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 58 GB  97 MB/s
     iteration_duration.....: avg=808.73ms min=190.33µs med=706.8ms  max=5.54s p(90)=1.52s p(95)=1.8s 
     iterations.............: 445381 740.661269/s
     vus....................: 33     min=33       max=600
ERRO[11:34:45] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m01.3s), 000/600 VUs, 445381 complete and 0 interrupted iterations
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
INFO[12:16:18] Load started at:               Tue Nov 12 2024 12:16:18 GMT+0000 (UTC)  source=console
INFO[12:26:19] Load finished at:              Tue Nov 12 2024 12:26:19 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 378 GB 629 MB/s
     aws_obj_put_duration...: avg=649.77ms min=76.46ms  med=650.04ms max=1.73s p(90)=881.73ms p(95)=954.7ms 
     aws_obj_put_fails......: 1      0.001665/s
     aws_obj_put_success....: 360204 599.740692/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 378 GB 629 MB/s
     iteration_duration.....: avg=666.51ms min=321.47µs med=666.78ms max=1.74s p(90)=898.42ms p(95)=972.11ms
     iterations.............: 360205 599.742357/s
     vus....................: 400    min=400      max=400

running (10m00.6s), 000/400 VUs, 360205 complete and 0 interrupted iterations
write ✓ [======================================] 400 VUs  10m0s

INFO[12:16:20] Load started at:               Tue Nov 12 2024 12:16:20 GMT+0000 (UTC)  source=console
INFO[12:26:20] Load finished at:              Tue Nov 12 2024 12:26:20 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 381 GB 635 MB/s
     aws_obj_put_duration...: avg=644.31ms min=112.58ms med=644.72ms max=1.6s  p(90)=875.67ms p(95)=948.44ms
     aws_obj_put_success....: 363182 605.077737/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 381 GB 634 MB/s
     iteration_duration.....: avg=660.89ms min=304.19µs med=661.31ms max=1.61s p(90)=892.25ms p(95)=965.34ms
     iterations.............: 363182 605.077737/s
     vus....................: 400    min=400      max=400
ERRO[12:26:20] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m00.2s), 000/400 VUs, 363182 complete and 0 interrupted iterations
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
INFO[14:19:30] Load started at:               Tue Nov 12 2024 14:19:30 GMT+0000 (UTC)  source=console
INFO[14:29:31] Load finished at:              Tue Nov 12 2024 14:29:31 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 43 GB  72 MB/s
     aws_obj_put_duration...: avg=810.13ms min=59.98ms  med=714.6ms  max=5.01s p(90)=1.45s p(95)=1.74s
     aws_obj_put_success....: 329474 548.730061/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 43 GB  72 MB/s
     iteration_duration.....: avg=819.72ms min=247.87µs med=724.19ms max=5.01s p(90)=1.46s p(95)=1.75s
     iterations.............: 329474 548.730061/s
     vus....................: 450    min=450      max=450

running (10m00.4s), 000/450 VUs, 329474 complete and 0 interrupted iterations
write ✓ [======================================] 450 VUs  10m0s

INFO[14:19:29] Load started at:               Tue Nov 12 2024 14:19:29 GMT+0000 (UTC)  source=console
INFO[14:29:30] Load finished at:              Tue Nov 12 2024 14:29:30 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 43 GB  72 MB/s
     aws_obj_put_duration...: avg=809.02ms min=57.24ms  med=712.59ms max=5.31s p(90)=1.45s p(95)=1.73s
     aws_obj_put_success....: 330130 548.652374/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 43 GB  72 MB/s
     iteration_duration.....: avg=818.47ms min=252.78µs med=722.02ms max=5.32s p(90)=1.46s p(95)=1.74s
     iterations.............: 330130 548.652374/s
     vus....................: 52     min=52       max=450
ERRO[14:29:31] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m01.7s), 000/450 VUs, 330130 complete and 0 interrupted iterations
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
INFO[14:43:48] Load started at:               Tue Nov 12 2024 14:43:48 GMT+0000 (UTC)  source=console
INFO[14:53:49] Load finished at:              Tue Nov 12 2024 14:53:49 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 160 GB 266 MB/s
     aws_obj_put_duration...: avg=1.16s min=71.18ms  med=1.1s  max=5.79s p(90)=1.86s p(95)=2.12s
     aws_obj_put_success....: 152494 253.937769/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 160 GB 266 MB/s
     iteration_duration.....: avg=1.18s min=333.63µs med=1.12s max=5.81s p(90)=1.87s p(95)=2.14s
     iterations.............: 152494 253.937769/s
     vus....................: 300    min=300      max=300

running (10m00.5s), 000/300 VUs, 152494 complete and 0 interrupted iterations
write ✓ [======================================] 300 VUs  10m0s

INFO[14:43:46] Load started at:               Tue Nov 12 2024 14:43:46 GMT+0000 (UTC)  source=console
INFO[14:53:48] Load finished at:              Tue Nov 12 2024 14:53:48 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 160 GB 266 MB/s
     aws_obj_put_duration...: avg=1.16s min=69.2ms   med=1.1s  max=5.28s p(90)=1.85s p(95)=2.12s
     aws_obj_put_success....: 152798 253.902942/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 160 GB 266 MB/s
     iteration_duration.....: avg=1.17s min=346.84µs med=1.12s max=5.29s p(90)=1.87s p(95)=2.14s
     iterations.............: 152798 253.902942/s
     vus....................: 57     min=57       max=300
ERRO[14:53:48] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m01.8s), 000/300 VUs, 152798 complete and 0 interrupted iterations
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
INFO[16:49:50] Load started at:               Tue Nov 12 2024 16:49:50 GMT+0000 (UTC)  source=console
INFO[16:59:51] Load finished at:              Tue Nov 12 2024 16:59:51 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 36 GB  60 MB/s
     aws_obj_put_duration...: avg=646.75ms min=55.44ms  med=566.65ms max=4.78s p(90)=1.14s p(95)=1.36s
     aws_obj_put_success....: 274355 456.51664/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 36 GB  60 MB/s
     iteration_duration.....: avg=656.35ms min=298.51µs med=576.21ms max=4.79s p(90)=1.15s p(95)=1.37s
     iterations.............: 274355 456.51664/s
     vus....................: 1      min=1       max=300
ERRO[16:59:51] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m01.0s), 000/300 VUs, 274355 complete and 0 interrupted iterations
write ✓ [======================================] 300 VUs  10m0s

INFO[16:49:52] Load started at:               Tue Nov 12 2024 16:49:52 GMT+0000 (UTC)  source=console
INFO[16:59:52] Load finished at:              Tue Nov 12 2024 16:59:52 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 36 GB  60 MB/s
     aws_obj_put_duration...: avg=643.8ms  min=57.2ms   med=564.18ms max=4.82s p(90)=1.14s p(95)=1.36s
     aws_obj_put_success....: 275514 458.789607/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 36 GB  60 MB/s
     iteration_duration.....: avg=653.54ms min=282.11µs med=573.98ms max=4.83s p(90)=1.15s p(95)=1.37s
     iterations.............: 275514 458.789607/s
     vus....................: 300    min=300      max=300

running (10m00.5s), 000/300 VUs, 275514 complete and 0 interrupted iterations
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
INFO[17:22:50] Load started at:               Tue Nov 12 2024 17:22:50 GMT+0000 (UTC)  source=console
INFO[17:32:50] Load finished at:              Tue Nov 12 2024 17:32:50 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 115 GB 191 MB/s
     aws_obj_put_duration...: avg=1.07s min=76.53ms  med=1.01s max=5.41s p(90)=1.8s  p(95)=2.08s
     aws_obj_put_success....: 109267 181.941128/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 115 GB 191 MB/s
     iteration_duration.....: avg=1.09s min=534.33µs med=1.03s max=5.42s p(90)=1.82s p(95)=2.1s 
     iterations.............: 109267 181.941128/s
     vus....................: 200    min=200      max=200

running (10m00.6s), 000/200 VUs, 109267 complete and 0 interrupted iterations
write ✓ [======================================] 200 VUs  10m0s

INFO[17:22:48] Load started at:               Tue Nov 12 2024 17:22:48 GMT+0000 (UTC)  source=console
INFO[17:32:50] Load finished at:              Tue Nov 12 2024 17:32:50 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 114 GB 190 MB/s
     aws_obj_put_duration...: avg=1.08s min=84.45ms  med=1.01s max=4.96s p(90)=1.81s p(95)=2.09s
     aws_obj_put_success....: 108742 180.713797/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 114 GB 189 MB/s
     iteration_duration.....: avg=1.1s  min=312.63µs med=1.03s max=4.98s p(90)=1.82s p(95)=2.11s
     iterations.............: 108742 180.713797/s
     vus....................: 72     min=72       max=200
ERRO[17:32:50] failed to handle the end-of-test summary      error="Could not save some summary information:\n\t- could not open '/tmp/summary.json': open /tmp/summary.json: permission denied"

running (10m01.7s), 000/200 VUs, 108742 complete and 0 interrupted iterations
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

