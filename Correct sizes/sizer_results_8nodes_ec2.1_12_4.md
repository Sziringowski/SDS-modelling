protection=EC2.1
HW_chassis=VEGMAN
SSD=4
HDD=12

### 4 nodes 1mib read
INFO[19:16:16] Load started at:               Fri Feb 21 2025 19:16:16 GMT+0000 (UTC)  source=console
INFO[19:26:17] Load finished at:              Fri Feb 21 2025 19:26:17 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_get_bytes......: 205 GB  341 MB/s
     aws_obj_get_duration...: avg=230.31ms min=21.52ms  med=189.33ms max=1.31s p(90)=480.82ms p(95)=568.35ms
     aws_obj_get_fails......: 7802017 12986.3002/s
     aws_obj_get_success....: 195160  324.83989/s
     data_received..........: 205 GB  340 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=30ms     min=304.08µs med=19.48ms  max=1.87s p(90)=60.35ms  p(95)=74.77ms 
     iterations.............: 7997177 13311.14009/s
     vus....................: 400     min=400       max=400
     vus_max................: 400     min=400       max=400
running (10m00.8s), 000/400 VUs, 7997177 complete and 0 interrupted iterations
read ✓ [==============] 400 VUs  10m0s

### 6 nodes 1mib read
INFO[12:04:16] Load started at:               Fri Feb 21 2025 12:04:16 GMT+0000 (UTC)  source=console
INFO[12:14:16] Load finished at:              Fri Feb 21 2025 12:14:16 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.4 TB  2.4 GB/s
     aws_obj_get_duration...: avg=265.95ms min=26.01ms  med=260.62ms max=1.61s p(90)=400.92ms p(95)=447.57ms
     aws_obj_get_success....: 1353366 2254.376714/s
     data_received..........: 1.4 TB  2.4 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=266.04ms min=312.92µs med=260.71ms max=1.61s p(90)=401.01ms p(95)=447.66ms
     iterations.............: 1353366 2254.376714/s
     vus....................: 600     min=600       max=600
     vus_max................: 600     min=600       max=600
running (10m00.3s), 000/600 VUs, 1353366 complete and 0 interrupted iterations
read ✓ [==============] 600 VUs  10m0s

### 8 nodes 1mib read
INFO[09:23:55] Load started at:               Fri Feb 21 2025 09:23:55 GMT+0000 (UTC)  source=console
INFO[09:33:55] Load finished at:              Fri Feb 21 2025 09:33:55 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_get_bytes......: 1.8 TB  2.9 GB/s
     aws_obj_get_duration...: avg=284.67ms min=17.76ms med=271.7ms  max=21.23s p(90)=470.67ms p(95)=531.86ms
     aws_obj_get_fails......: 578     0.9627/s
     aws_obj_get_success....: 1685430 2807.202268/s
     data_received..........: 1.8 TB  2.9 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=284.7ms  min=442µs   med=271.73ms max=21.23s p(90)=470.73ms p(95)=531.92ms
     iterations.............: 1686008 2808.164968/s
     vus....................: 800     min=800       max=800
     vus_max................: 800     min=800       max=800
running (10m00.4s), 000/800 VUs, 1686008 complete and 0 interrupted iterations
read ✓ [==============] 800 VUs  10m0s

### 4 nodes 128kb read
INFO[14:07:25] Load started at:               Fri Feb 21 2025 14:07:25 GMT+0000 (UTC)  source=console
INFO[14:17:25] Load finished at:              Fri Feb 21 2025 14:17:25 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 277 GB  462 MB/s
     aws_obj_get_duration...: avg=170.2ms  min=13.09ms  med=152.19ms max=1.03s p(90)=332.24ms p(95)=390.6ms 
     aws_obj_get_success....: 2114083 3522.327818/s
     data_received..........: 277 GB  461 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=170.28ms min=369.51µs med=152.27ms max=1.03s p(90)=332.33ms p(95)=390.68ms
     iterations.............: 2114083 3522.327818/s
     vus....................: 600     min=600       max=600
     vus_max................: 600     min=600       max=600
running (10m00.2s), 000/600 VUs, 2114083 complete and 0 interrupted iterations
read ✓ [==============] 600 VUs  10m0s

### 6 nodes 128kb read
INFO[11:22:23] Load started at:               Fri Feb 21 2025 11:22:23 GMT+0000 (UTC)  source=console
INFO[11:32:23] Load finished at:              Fri Feb 21 2025 11:32:23 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_get_bytes......: 396 GB  660 MB/s
     aws_obj_get_duration...: avg=178.72ms min=10.67ms  med=169.42ms max=1.94s p(90)=296.45ms p(95)=336.59ms
     aws_obj_get_fails......: 7       0.011663/s
     aws_obj_get_success....: 3019815 5031.325369/s
     data_received..........: 396 GB  659 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=178.81ms min=760.43µs med=169.5ms  max=1.94s p(90)=296.53ms p(95)=336.67ms
     iterations.............: 3019822 5031.337031/s
     vus....................: 900     min=900       max=900
     vus_max................: 900     min=900       max=900
running (10m00.2s), 000/900 VUs, 3019822 complete and 0 interrupted iterations
read ✓ [==============] 900 VUs  10m0s

### 8 nodes 128kb read
INFO[08:41:14] Load started at:               Fri Feb 21 2025 08:41:14 GMT+0000 (UTC)  source=console
INFO[08:51:14] Load finished at:              Fri Feb 21 2025 08:51:14 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_get_bytes......: 386 GB  643 MB/s
     aws_obj_get_duration...: avg=184.27ms min=13.26ms  med=165.57ms max=1.17s p(90)=352.41ms p(95)=410.15ms
     aws_obj_get_fails......: 2604966 4339.675737/s
     aws_obj_get_success....: 2945932 4907.699226/s
     data_received..........: 386 GB  643 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=129.7ms  min=200.65µs med=101.58ms max=1.17s p(90)=292.74ms p(95)=358.32ms
     iterations.............: 5550898 9247.374963/s
     vus....................: 1200    min=1200      max=1200
     vus_max................: 1200    min=1200      max=1200
running (10m00.3s), 0000/1200 VUs, 5550898 complete and 0 interrupted iterations
read ✓ [==============] 1200 VUs  10m0s

### 4 nodes 128mib read
INFO[19:57:10] Load started at:               Fri Feb 21 2025 19:57:10 GMT+0000 (UTC)  source=console
INFO[20:07:16] Load finished at:              Fri Feb 21 2025 20:07:16 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.8 TB 2.9 GB/s
     aws_obj_get_duration...: avg=5.45s min=1.54s    med=3.73s max=23.59s p(90)=10.91s p(95)=13.56s
     aws_obj_get_success....: 13238  21.861083/s
     data_received..........: 1.8 TB 2.9 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=5.45s min=404.87µs med=3.73s max=23.59s p(90)=10.91s p(95)=13.56s
     iterations.............: 13238  21.861083/s
     vus....................: 21     min=21      max=120
     vus_max................: 120    min=120     max=120
running (10m05.6s), 000/120 VUs, 13238 complete and 20 interrupted iterations
read ✓ [==============] 120 VUs  10m0s

### 6 nodes 128mib read
INFO[12:45:25] Load started at:               Fri Feb 21 2025 12:45:25 GMT+0000 (UTC)  source=console
INFO[12:55:31] Load finished at:              Fri Feb 21 2025 12:55:31 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 2.8 TB 4.7 GB/s
     aws_obj_get_duration...: avg=5.15s min=1.54s    med=4.27s max=24.19s p(90)=8.54s p(95)=11.03s
     aws_obj_get_success....: 21031  34.704646/s
     data_received..........: 2.8 TB 4.7 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=5.15s min=396.84µs med=4.27s max=24.19s p(90)=8.53s p(95)=11.03s
     iterations.............: 21031  34.704646/s
     vus....................: 1      min=1       max=180
     vus_max................: 180    min=180     max=180
running (10m06.0s), 000/180 VUs, 21031 complete and 21 interrupted iterations
read ✓ [==============] 180 VUs  10m0s

### 8 nodes 128mib read
INFO[10:06:06] Load started at:               Fri Feb 21 2025 10:06:06 GMT+0000 (UTC)  source=console
INFO[10:16:11] Load finished at:              Fri Feb 21 2025 10:16:11 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 3.3 TB 5.5 GB/s
     aws_obj_get_duration...: avg=5.89s min=1.7s     med=5.28s max=1m14s p(90)=8.38s p(95)=9.73s
     aws_obj_get_success....: 24543  40.61565/s
     data_received..........: 3.3 TB 5.5 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=5.88s min=414.54µs med=5.28s max=1m14s p(90)=8.38s p(95)=9.73s
     iterations.............: 24543  40.61565/s
     vus....................: 4      min=4      max=240
     vus_max................: 240    min=240    max=240
running (10m04.3s), 000/240 VUs, 24543 complete and 0 interrupted iterations
read ✓ [==============] 240 VUs  10m0s

### 4 nodes 8kb read
INFO[13:30:51] Load started at:               Fri Feb 21 2025 13:30:51 GMT+0000 (UTC)  source=console
INFO[13:40:51] Load finished at:              Fri Feb 21 2025 13:40:51 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_get_bytes......: 24 GB   39 MB/s
     aws_obj_get_duration...: avg=129.43ms min=11ms     med=114.23ms max=1s p(90)=247.37ms p(95)=295.4ms 
     aws_obj_get_fails......: 1828    3.04616/s
     aws_obj_get_success....: 2871209 4784.5527/s
     data_received..........: 24 GB   39 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=129.46ms min=462.44µs med=114.25ms max=1s p(90)=247.41ms p(95)=295.44ms
     iterations.............: 2873037 4787.59886/s
     vus....................: 620     min=620      max=620
     vus_max................: 620     min=620      max=620
running (10m00.1s), 000/620 VUs, 2873037 complete and 0 interrupted iterations
read ✓ [==============] 620 VUs  10m0s

### 6 nodes 8kb read
INFO[10:44:14] Load started at:               Fri Feb 21 2025 10:44:14 GMT+0000 (UTC)  source=console
INFO[10:54:14] Load finished at:              Fri Feb 21 2025 10:54:14 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 33 GB   55 MB/s
     aws_obj_get_duration...: avg=139.49ms min=11.82ms  med=123.39ms max=958.19ms p(90)=259.66ms p(95)=306.8ms 
     aws_obj_get_success....: 3997655 6660.810255/s
     data_received..........: 33 GB   55 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=139.57ms min=233.54µs med=123.47ms max=958.26ms p(90)=259.74ms p(95)=306.88ms
     iterations.............: 3997655 6660.810255/s
     vus....................: 930     min=930       max=930
     vus_max................: 930     min=930       max=930
running (10m00.2s), 000/930 VUs, 3997655 complete and 0 interrupted iterations
read ✓ [==============] 930 VUs  10m0s

### 8 nodes 8kb read
INFO[08:02:18] Load started at:               Fri Feb 21 2025 08:02:18 GMT+0000 (UTC)  source=console
INFO[08:12:18] Load finished at:              Fri Feb 21 2025 08:12:18 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_get_bytes......: 28 GB   47 MB/s
     aws_obj_get_duration...: avg=144.79ms min=11.86ms  med=124.43ms max=5.06s p(90)=287.48ms p(95)=340.8ms 
     aws_obj_get_fails......: 3496037 5824.66141/s
     aws_obj_get_success....: 3434678 5722.432687/s
     data_received..........: 28 GB   47 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=107.33ms min=270.66µs med=84.22ms  max=5.06s p(90)=236.19ms p(95)=293.92ms
     iterations.............: 6930715 11547.094096/s
     vus....................: 1240    min=1240       max=1240
     vus_max................: 1240    min=1240       max=1240
running (10m00.2s), 0000/1240 VUs, 6930715 complete and 0 interrupted iterations
read ✓ [==============] 1240 VUs  10m0s

### 4 nodes 1mib write
INFO[19:26:20] Load started at:               Fri Feb 21 2025 19:26:20 GMT+0000 (UTC)  source=console
INFO[19:36:20] Load finished at:              Fri Feb 21 2025 19:36:20 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_put_bytes......: 395 GB 658 MB/s
     aws_obj_put_duration...: avg=637.06ms min=64.95ms  med=620.35ms max=2.81s p(90)=966.02ms p(95)=1.08s
     aws_obj_put_fails......: 278    0.46298/s
     aws_obj_put_success....: 376604 627.194358/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 395 GB 657 MB/s
     iteration_duration.....: avg=637.03ms min=155.32µs med=620.51ms max=2.81s p(90)=966.3ms  p(95)=1.08s
     iterations.............: 376882 627.657337/s
     vus....................: 400    min=400      max=400
     vus_max................: 400    min=400      max=400
running (10m00.5s), 000/400 VUs, 376882 complete and 0 interrupted iterations
write ✓ [==============] 400 VUs  10m0s

### 6 nodes 1mib write
INFO[12:14:20] Load started at:               Fri Feb 21 2025 12:14:20 GMT+0000 (UTC)  source=console
INFO[12:24:21] Load finished at:              Fri Feb 21 2025 12:24:21 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 678 GB 1.1 GB/s
     aws_obj_put_duration...: avg=556.72ms min=63.75ms  med=527.63ms max=2.1s p(90)=820.66ms p(95)=933.26ms
     aws_obj_put_success....: 646440 1075.798162/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 677 GB 1.1 GB/s
     iteration_duration.....: avg=557.11ms min=151.95µs med=528.02ms max=2.1s p(90)=821.08ms p(95)=933.65ms
     iterations.............: 646440 1075.798162/s
     vus....................: 16     min=16        max=600
     vus_max................: 600    min=600       max=600
running (10m00.9s), 000/600 VUs, 646440 complete and 0 interrupted iterations
write ✓ [==============] 600 VUs  10m0s

### 8 nodes 1mib write
INFO[09:33:58] Load started at:               Fri Feb 21 2025 09:33:58 GMT+0000 (UTC)  source=console
INFO[09:44:03] Load finished at:              Fri Feb 21 2025 09:44:03 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_put_bytes......: 51 GB 84 MB/s
     aws_obj_put_duration...: avg=3.45s min=51.64ms  med=207.31ms max=8m29s p(90)=712.9ms  p(95)=1.1s  
     aws_obj_put_fails......: 915   1.51233/s
     aws_obj_put_success....: 48591 80.312186/s
     data_received..........: 0 B   0 B/s
     data_sent..............: 51 GB 84 MB/s
     iteration_duration.....: avg=4.5s  min=134.13µs med=213.09ms max=8m29s p(90)=774.51ms p(95)=22.47s
     iterations.............: 49506 81.824517/s
     vus....................: 791   min=791     max=800
     vus_max................: 800   min=800     max=800
running (10m05.0s), 000/800 VUs, 49506 complete and 790 interrupted iterations
write ✓ [==============] 800 VUs  10m0s

### 4 nodes 128kb write
INFO[14:17:28] Load started at:               Fri Feb 21 2025 14:17:28 GMT+0000 (UTC)  source=console
INFO[14:27:29] Load finished at:              Fri Feb 21 2025 14:27:29 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 121 GB 201 MB/s
     aws_obj_put_duration...: avg=390.35ms min=48.61ms  med=299.47ms max=4.08s p(90)=648.5ms p(95)=937.42ms
     aws_obj_put_success....: 921635 1534.14527/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 121 GB 201 MB/s
     iteration_duration.....: avg=390.74ms min=159.51µs med=299.85ms max=4.08s p(90)=648.9ms p(95)=937.79ms
     iterations.............: 921635 1534.14527/s
     vus....................: 600    min=600      max=600
     vus_max................: 600    min=600      max=600
running (10m00.7s), 000/600 VUs, 921635 complete and 0 interrupted iterations
write ✓ [==============] 600 VUs  10m0s

### 6 nodes 128kb write
INFO[11:32:26] Load started at:               Fri Feb 21 2025 11:32:26 GMT+0000 (UTC)  source=console
INFO[11:42:26] Load finished at:              Fri Feb 21 2025 11:42:26 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 170 GB  283 MB/s
     aws_obj_put_duration...: avg=416.11ms min=59.16ms  med=394.25ms max=2.26s p(90)=598.32ms p(95)=682.23ms
     aws_obj_put_success....: 1296713 2160.318864/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 170 GB  283 MB/s
     iteration_duration.....: avg=416.5ms  min=161.83µs med=394.63ms max=2.26s p(90)=598.71ms p(95)=682.64ms
     iterations.............: 1296713 2160.318864/s
     vus....................: 900     min=900       max=900
     vus_max................: 900     min=900       max=900
running (10m00.2s), 000/900 VUs, 1296713 complete and 0 interrupted iterations
write ✓ [==============] 900 VUs  10m0s

### 8 nodes 128kb write
INFO[08:51:18] Load started at:               Fri Feb 21 2025 08:51:18 GMT+0000 (UTC)  source=console
INFO[09:01:18] Load finished at:              Fri Feb 21 2025 09:01:18 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_put_bytes......: 177 GB  295 MB/s
     aws_obj_put_duration...: avg=528.27ms min=41.19ms  med=444.73ms max=1m3s p(90)=746.58ms p(95)=862.24ms
     aws_obj_put_fails......: 101     0.168236/s
     aws_obj_put_success....: 1350661 2249.8054/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 177 GB  295 MB/s
     iteration_duration.....: avg=533.09ms min=159.54µs med=445.12ms max=1m3s p(90)=747.09ms p(95)=862.87ms
     iterations.............: 1350762 2249.973637/s
     vus....................: 1200    min=1200      max=1200
     vus_max................: 1200    min=1200      max=1200
running (10m00.3s), 0000/1200 VUs, 1350762 complete and 0 interrupted iterations
write ✓ [==============] 1200 VUs  10m0s

### 4 nodes 128mib write
INFO[20:07:20] Load started at:               Fri Feb 21 2025 20:07:20 GMT+0000 (UTC)  source=console
INFO[20:17:26] Load finished at:              Fri Feb 21 2025 20:17:26 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.2 TB 2.0 GB/s
     aws_obj_put_duration...: avg=7.84s min=4.17s    med=7.65s max=20.84s p(90)=9.9s p(95)=10.64s
     aws_obj_put_success....: 9212   15.213308/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.2 TB 2.0 GB/s
     iteration_duration.....: avg=7.84s min=102.23µs med=7.65s max=20.84s p(90)=9.9s p(95)=10.65s
     iterations.............: 9212   15.213308/s
     vus....................: 16     min=0       max=120
     vus_max................: 120    min=120     max=120
running (10m05.5s), 000/120 VUs, 9212 complete and 11 interrupted iterations
write ✓ [==============] 120 VUs  10m0s

### 6 nodes 128mib write
INFO[12:55:36] Load started at:               Fri Feb 21 2025 12:55:36 GMT+0000 (UTC)  source=console
INFO[13:05:41] Load finished at:              Fri Feb 21 2025 13:05:41 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.6 TB 2.7 GB/s
     aws_obj_put_duration...: avg=8.8s min=3.91s   med=6.17s max=57.27s p(90)=14.17s p(95)=26.38s
     aws_obj_put_success....: 12188  20.131187/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.6 TB 2.7 GB/s
     iteration_duration.....: avg=8.8s min=92.86µs med=6.17s max=57.27s p(90)=14.18s p(95)=26.37s
     iterations.............: 12188  20.131187/s
     vus....................: 71     min=0       max=180
     vus_max................: 180    min=91      max=180
running (10m05.4s), 000/180 VUs, 12188 complete and 62 interrupted iterations
write ✓ [==============] 180 VUs  10m0s

### 8 nodes 128mib write
INFO[10:16:17] Load started at:               Fri Feb 21 2025 10:16:17 GMT+0000 (UTC)  source=console
INFO[10:26:22] Load finished at:              Fri Feb 21 2025 10:26:22 GMT+0000 (UTC)  source=console

     █ teardown

     aws_obj_put_bytes......: 2.3 TB 3.7 GB/s
     aws_obj_put_duration...: avg=8.52s min=4.25s    med=7.42s max=46.66s p(90)=12.51s p(95)=15.13s
     aws_obj_put_fails......: 53     0.087528/s
     aws_obj_put_success....: 16918  27.93961/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 2.3 TB 3.7 GB/s
     iteration_duration.....: avg=8.51s min=107.53µs med=7.41s max=46.66s p(90)=12.51s p(95)=15.12s
     iterations.............: 16971  28.027138/s
     vus....................: 0      min=0       max=240
     vus_max................: 240    min=90      max=240
running (10m05.5s), 000/240 VUs, 16971 complete and 35 interrupted iterations
write ✓ [==============] 240 VUs  10m0s

### 4 nodes 8kb write
INFO[13:40:54] Load started at:               Fri Feb 21 2025 13:40:54 GMT+0000 (UTC)  source=console
INFO[13:50:54] Load finished at:              Fri Feb 21 2025 13:50:54 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 11 GB   18 MB/s
     aws_obj_put_duration...: avg=282.03ms min=44.11ms  med=249.1ms  max=2.24s p(90)=458.56ms p(95)=558.98ms
     aws_obj_put_success....: 1317302 2194.784586/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 11 GB   18 MB/s
     iteration_duration.....: avg=282.41ms min=141.94µs med=249.48ms max=2.24s p(90)=458.94ms p(95)=559.38ms
     iterations.............: 1317302 2194.784586/s
     vus....................: 620     min=620       max=620
     vus_max................: 620     min=620       max=620
running (10m00.2s), 000/620 VUs, 1317302 complete and 0 interrupted iterations
write ✓ [==============] 620 VUs  10m0s

### 6 nodes 8kb write
INFO[10:54:17] Load started at:               Fri Feb 21 2025 10:54:17 GMT+0000 (UTC)  source=console
INFO[11:04:18] Load finished at:              Fri Feb 21 2025 11:04:18 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 12 GB   20 MB/s
     aws_obj_put_duration...: avg=379.35ms min=43.43ms  med=358.6ms  max=1.65s p(90)=571.88ms p(95)=652.56ms
     aws_obj_put_success....: 1469680 2448.199871/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 12 GB   20 MB/s
     iteration_duration.....: avg=379.73ms min=150.74µs med=358.98ms max=1.65s p(90)=572.28ms p(95)=652.92ms
     iterations.............: 1469680 2448.199871/s
     vus....................: 930     min=930       max=930
     vus_max................: 930     min=930       max=930
running (10m00.3s), 000/930 VUs, 1469680 complete and 0 interrupted iterations
write ✓ [==============] 930 VUs  10m0s

### 8 nodes 8kb write
INFO[08:12:22] Load started at:               Fri Feb 21 2025 08:12:22 GMT+0000 (UTC)  source=console
INFO[08:22:22] Load finished at:              Fri Feb 21 2025 08:22:22 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 15 GB   25 MB/s
     aws_obj_put_duration...: avg=399.73ms min=37.35ms  med=369.65ms max=2.05s p(90)=646.34ms p(95)=765.38ms
     aws_obj_put_success....: 1859792 3096.204997/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 15 GB   25 MB/s
     iteration_duration.....: avg=400.1ms  min=198.95µs med=370.01ms max=2.05s p(90)=646.69ms p(95)=765.74ms
     iterations.............: 1859792 3096.204997/s
     vus....................: 1240    min=1240      max=1240
     vus_max................: 1240    min=1240      max=1240
running (10m00.7s), 0000/1240 VUs, 1859792 complete and 0 interrupted iterations
write ✓ [==============] 1240 VUs  10m0s

