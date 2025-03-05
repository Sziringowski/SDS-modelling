protection=2REP
HW_chassis=X205
SSD=2
HDD=12

### 15 nodes 8kb write
INFO[11:11:55] Load started at:               Fri Oct 25 2024 11:11:55 GMT+0000 (UTC)  source=console
INFO[11:21:57] Load finished at:              Fri Oct 25 2024 11:21:57 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 7.6 GB 13 MB/s
     aws_obj_put_duration...: avg=744.03ms min=31.39ms  med=302.29ms max=13.85s p(90)=2.03s p(95)=2.82s
     aws_obj_put_success....: 927223 1539.168897/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 7.6 GB 13 MB/s
     iteration_duration.....: avg=752.9ms  min=269.05µs med=310.8ms  max=13.86s p(90)=2.03s p(95)=2.83s
     iterations.............: 927223 1539.168897/s
     vus....................: 19     min=19        max=1162

running (10m02.4s), 0000/1162 VUs, 927223 complete and 0 interrupted iterations
write ✓ [======================================] 1162 VUs  10m0s

INFO[11:11:58] Load started at:               Fri Oct 25 2024 11:11:58 GMT+0000 (UTC)  source=console
INFO[11:21:58] Load finished at:              Fri Oct 25 2024 11:21:58 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 7.3 GB 12 MB/s
     aws_obj_put_duration...: avg=770.4ms  min=28.08ms  med=332.09ms max=10.37s p(90)=2.08s p(95)=2.87s
     aws_obj_put_success....: 895336 1490.153466/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 7.3 GB 12 MB/s
     iteration_duration.....: avg=779.09ms min=179.67µs med=340.44ms max=10.38s p(90)=2.09s p(95)=2.88s
     iterations.............: 895336 1490.153466/s
     vus....................: 14     min=14        max=1162

running (10m00.8s), 0000/1162 VUs, 895336 complete and 0 interrupted iterations
write ✓ [======================================] 1162 VUs  10m0s

### 15 nodes 8kb read
INFO[10:59:46] Load started at:               Fri Sep 27 2024 10:59:46 GMT+0000 (UTC)  source=console
INFO[11:09:46] Load finished at:              Fri Sep 27 2024 11:09:46 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 51 GB   85 MB/s
     aws_obj_get_duration...: avg=111.38ms min=6.37ms med=97.3ms  max=3.31s p(90)=187.08ms p(95)=225.33ms
     aws_obj_get_success....: 6254504 10417.648337/s
     data_received..........: 51 GB   85 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=111.46ms min=1.08ms med=97.38ms max=3.31s p(90)=187.16ms p(95)=225.41ms
     iterations.............: 6254504 10417.648337/s
     vus....................: 1162    min=1162       max=1162

running (10m00.4s), 0000/1162 VUs, 6254504 complete and 0 interrupted iterations
read ✓ [======================================] 1162 VUs  10m0s

INFO[10:59:48] Load started at:               Fri Sep 27 2024 10:59:48 GMT+0000 (UTC)  source=console
INFO[11:09:48] Load finished at:              Fri Sep 27 2024 11:09:48 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 51 GB   85 MB/s
     aws_obj_get_duration...: avg=112.05ms min=6.93ms  med=98.13ms max=3.14s p(90)=187.96ms p(95)=226.08ms
     aws_obj_get_success....: 6216476 10359.219991/s
     data_received..........: 51 GB   85 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=112.13ms min=190.5ms med=98.21ms max=3.14s p(90)=188.04ms p(95)=226.16ms
     iterations.............: 6216476 10359.219991/s
     vus....................: 1162    min=1162       max=1162

running (10m00.1s), 0000/1162 VUs, 6216476 complete and 0 interrupted iterations
read ✓ [======================================] 1162 VUs  10m0s

### 15 nodes 1mb write
INFO[18:47:51] Load started at:               Thu Oct 24 2024 18:47:51 GMT+0000 (UTC)  source=console
INFO[18:57:51] Load finished at:              Thu Oct 24 2024 18:57:51 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 731 GB 1.2 GB/s
     aws_obj_put_duration...: avg=630.05ms min=79.84ms  med=524.56ms max=5.98s p(90)=1.09s p(95)=1.36s
     aws_obj_put_success....: 696837 1160.258289/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 730 GB 1.2 GB/s
     iteration_duration.....: avg=646.07ms min=346.19µs med=540.6ms  max=6s    p(90)=1.1s  p(95)=1.38s
     iterations.............: 696837 1160.258289/s
     vus....................: 750    min=750       max=750

running (10m00.6s), 000/750 VUs, 696837 complete and 0 interrupted iterations
write ✓ [======================================] 750 VUs  10m0s

INFO[18:47:50] Load started at:               Thu Oct 24 2024 18:47:50 GMT+0000 (UTC)  source=console
INFO[18:57:51] Load finished at:              Thu Oct 24 2024 18:57:51 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 737 GB 1.2 GB/s
     aws_obj_put_duration...: avg=624.98ms min=81.17ms med=516.02ms max=6.27s p(90)=1.08s p(95)=1.37s
     aws_obj_put_success....: 702575 1168.294319/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 736 GB 1.2 GB/s
     iteration_duration.....: avg=640.87ms min=297.2µs med=531.85ms max=6.29s p(90)=1.1s  p(95)=1.39s
     iterations.............: 702575 1168.294319/s
     vus....................: 134    min=134       max=750

running (10m01.4s), 000/750 VUs, 702575 complete and 0 interrupted iterations
write ✓ [======================================] 750 VUs  10m0s

### 15 nodes 1mb read
INFO[19:08:31] Load started at:               Thu Oct 24 2024 19:08:31 GMT+0000 (UTC)  source=console
INFO[19:18:33] Load finished at:              Thu Oct 24 2024 19:18:33 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.5 TB  2.5 GB/s
     aws_obj_get_duration...: avg=308.08ms min=25.92ms  med=269.09ms max=3.71s p(90)=532.69ms p(95)=640.94ms
     aws_obj_get_success....: 1460632 2429.066386/s
     data_received..........: 1.5 TB  2.5 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=308.17ms min=204.61µs med=269.18ms max=3.71s p(90)=532.78ms p(95)=641.03ms
     iterations.............: 1460632 2429.066386/s
     vus....................: 33      min=33        max=750

running (10m01.3s), 000/750 VUs, 1460632 complete and 0 interrupted iterations
read ✓ [======================================] 750 VUs  10m0s

INFO[19:08:33] Load started at:               Thu Oct 24 2024 19:08:33 GMT+0000 (UTC)  source=console
INFO[19:18:34] Load finished at:              Thu Oct 24 2024 19:18:34 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.5 TB  2.6 GB/s
     aws_obj_get_duration...: avg=305.87ms min=25.36ms  med=267.11ms max=3.65s p(90)=528.32ms p(95)=636.35ms
     aws_obj_get_success....: 1470895 2449.291112/s
     data_received..........: 1.5 TB  2.6 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=305.96ms min=203.74µs med=267.2ms  max=3.65s p(90)=528.41ms p(95)=636.44ms
     iterations.............: 1470895 2449.291112/s
     vus....................: 750     min=750       max=750

running (10m00.5s), 000/750 VUs, 1470895 complete and 0 interrupted iterations
read ✓ [======================================] 750 VUs  10m0s

### 15 nodes 128kb write
INFO[18:11:17] Load started at:               Thu Oct 24 2024 18:11:17 GMT+0000 (UTC)  source=console
INFO[18:21:20] Load finished at:              Thu Oct 24 2024 18:21:20 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 256 GB  425 MB/s
     aws_obj_put_duration...: avg=336.03ms min=32.4ms   med=188.13ms max=11.5s  p(90)=531.26ms p(95)=852.75ms
     aws_obj_put_success....: 1955061 3239.453703/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 256 GB  424 MB/s
     iteration_duration.....: avg=345.74ms min=919.13µs med=198.01ms max=11.51s p(90)=541.14ms p(95)=862.51ms
     iterations.............: 1955061 3239.453703/s
     vus....................: 119     min=119       max=1125

running (10m03.5s), 0000/1125 VUs, 1955061 complete and 0 interrupted iterations
write ✓ [======================================] 1125 VUs  10m0s

INFO[18:11:14] Load started at:               Thu Oct 24 2024 18:11:14 GMT+0000 (UTC)  source=console
INFO[18:21:18] Load finished at:              Thu Oct 24 2024 18:21:18 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 268 GB  444 MB/s
     aws_obj_put_duration...: avg=320.62ms min=32.73ms  med=185.89ms max=11.59s p(90)=470.47ms p(95)=747.61ms
     aws_obj_put_success....: 2046783 3388.714835/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 268 GB  444 MB/s
     iteration_duration.....: avg=330.26ms min=284.08µs med=196.56ms max=11.59s p(90)=479.76ms p(95)=757.18ms
     iterations.............: 2046783 3388.714835/s
     vus....................: 18      min=18        max=1125

running (10m04.0s), 0000/1125 VUs, 2046783 complete and 0 interrupted iterations
write ✓ [======================================] 1125 VUs  10m0s

### 15 nodes 128kb read
INFO[18:31:27] Load started at:               Thu Oct 24 2024 18:31:27 GMT+0000 (UTC)  source=console
INFO[18:41:27] Load finished at:              Thu Oct 24 2024 18:41:27 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 576 GB  959 MB/s
     aws_obj_get_duration...: avg=153.5ms  min=9.91ms med=124.4ms  max=2.92s p(90)=285.35ms p(95)=350.9ms 
       3       0.004995/s
     aws_obj_get_success....: 4394740 7317.791677/s
     data_received..........: 576 GB  958 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=153.58ms min=2.01ms med=124.48ms max=2.92s p(90)=285.44ms p(95)=350.99ms
     iterations.............: 4394743 7317.796672/s
     vus....................: 1125    min=1125      max=1125

running (10m00.6s), 0000/1125 VUs, 4394743 complete and 0 interrupted iterations
read ✓ [======================================] 1125 VUs  10m0s

INFO[18:31:27] Load started at:               Thu Oct 24 2024 18:31:27 GMT+0000 (UTC)  source=console
INFO[18:41:28] Load finished at:              Thu Oct 24 2024 18:41:28 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 582 GB  969 MB/s
     aws_obj_get_duration...: avg=152.03ms min=8.36ms med=122.96ms max=2.96s p(90)=282.92ms p(95)=348.06ms
     aws_obj_get_fails......: 15      0.024986/s
     aws_obj_get_success....: 4436794 7390.615128/s
     data_received..........: 581 GB  968 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=152.12ms min=2.58ms med=123.05ms max=2.96s p(90)=283.01ms p(95)=348.15ms
     iterations.............: 4436809 7390.640115/s
     vus....................: 1125    min=1125      max=1125

running (10m00.3s), 0000/1125 VUs, 4436809 complete and 0 interrupted iterations
read ✓ [======================================] 1125 VUs  10m0s

### 15 nodes 128mb write
INFO[10:03:02] Load started at:               Tue Oct 01 2024 10:03:02 GMT+0000 (UTC)  source=console
INFO[10:13:07] Load finished at:              Tue Oct 01 2024 10:13:07 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 733 GB 1.2 GB/s
     aws_obj_put_duration...: avg=23.88s min=7.61s    med=19.78s max=57.43s p(90)=39.61s p(95)=42.97s
     aws_obj_put_success....: 5462   9.015756/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 733 GB 1.2 GB/s
     iteration_duration.....: avg=24.32s min=190.35ms med=20.21s max=57.9s  p(90)=40.04s p(95)=43.42s
     iterations.............: 5455   9.004202/s
     vus....................: 7      min=0      max=225

running (10m05.8s), 000/225 VUs, 5455 complete and 180 interrupted iterations
write ✓ [======================================] 225 VUs  10m0s

INFO[10:03:00] Load started at:               Tue Oct 01 2024 10:03:00 GMT+0000 (UTC)  source=console
INFO[10:13:06] Load finished at:              Tue Oct 01 2024 10:13:06 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 732 GB 1.2 GB/s
     aws_obj_put_duration...: avg=23.84s min=7.01s    med=19.74s max=56.65s p(90)=39.01s p(95)=42.57s
     aws_obj_put_success....: 5457   9.007967/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 732 GB 1.2 GB/s
     iteration_duration.....: avg=24.27s min=159.44ms med=20.13s max=57.07s p(90)=39.43s p(95)=43.01s
     iterations.............: 5453   9.001364/s
     vus....................: 4      min=0      max=225

running (10m05.8s), 000/225 VUs, 5453 complete and 183 interrupted iterations
write ✓ [======================================] 225 VUs  10m0s

### 15 nodes 128mb read
INFO[10:16:17] Load started at:               Tue Oct 01 2024 10:16:17 GMT+0000 (UTC)  source=console
INFO[10:26:28] Load finished at:              Tue Oct 01 2024 10:26:28 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.3 TB 2.2 GB/s
     aws_obj_get_duration...: avg=13.57s min=1.86s    med=13.08s max=1m25s p(90)=20.8s p(95)=23.53s
     aws_obj_get_success....: 9911   16.199118/s
     data_received..........: 1.3 TB 2.2 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=13.57s min=286.54ms med=13.08s max=1m25s p(90)=20.8s p(95)=23.53s
     iterations.............: 9911   16.199118/s
     vus....................: 10     min=10      max=225

running (10m11.8s), 000/225 VUs, 9911 complete and 126 interrupted iterations
read ✓ [======================================] 225 VUs  10m0s

INFO[10:16:18] Load started at:               Tue Oct 01 2024 10:16:18 GMT+0000 (UTC)  source=console
INFO[10:26:30] Load finished at:              Tue Oct 01 2024 10:26:30 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.4 TB 2.3 GB/s
     aws_obj_get_duration...: avg=12.91s min=1.93s    med=12.37s max=1m21s p(90)=19.68s p(95)=22.19s
     aws_obj_get_success....: 10458  17.105048/s
     data_received..........: 1.4 TB 2.3 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=12.9s  min=216.25ms med=12.37s max=1m21s p(90)=19.68s p(95)=22.19s
     iterations.............: 10458  17.105048/s
     vus....................: 1      min=1       max=225

running (10m11.4s), 000/225 VUs, 10458 complete and 78 interrupted iterations
read ✓ [======================================] 225 VUs  10m0s

### 14 nodes 8kb write
INFO[12:25:12] Load started at:               Tue Oct 01 2024 12:25:12 GMT+0000 (UTC)  source=console
INFO[12:35:15] Load finished at:              Tue Oct 01 2024 12:35:15 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 6.3 GB 10 MB/s
     aws_obj_put_duration...: avg=844.1ms  min=32.64ms med=689.21ms max=8s    p(90)=1.65s p(95)=2.09s
     aws_obj_put_success....: 764716 1269.21642/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 6.2 GB 10 MB/s
     iteration_duration.....: avg=852.77ms min=2.37ms  med=697.97ms max=8.01s p(90)=1.66s p(95)=2.1s 
     iterations.............: 764716 1269.21642/s
     vus....................: 4      min=4        max=1085

running (10m02.5s), 0000/1085 VUs, 764716 complete and 0 interrupted iterations
write ✓ [======================================] 1085 VUs  10m0

INFO[12:25:14] Load started at:               Tue Oct 01 2024 12:25:14 GMT+0000 (UTC)  source=console
INFO[12:35:15] Load finished at:              Tue Oct 01 2024 12:35:15 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 6.2 GB 10 MB/s
     aws_obj_put_duration...: avg=849.57ms min=35.56ms  med=695.08ms max=8.2s  p(90)=1.66s p(95)=2.09s
     aws_obj_put_success....: 758571 1261.921216/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 6.2 GB 10 MB/s
     iteration_duration.....: avg=858.33ms min=191.01ms med=703.83ms max=8.21s p(90)=1.67s p(95)=2.1s 
     iterations.............: 758571 1261.921216/s
     vus....................: 11     min=11        max=1085

running (10m01.1s), 0000/1085 VUs, 758571 complete and 0 interrupted iterations
write ✓ [======================================] 1085 VUs  10m0s

### 14 nodes 8kb read
INFO[12:36:00] Load started at:               Tue Oct 01 2024 12:36:00 GMT+0000 (UTC)  source=console
INFO[12:46:01] Load finished at:              Tue Oct 01 2024 12:46:01 GMT+0000 (UTC)  source=console
          aws_obj_get_bytes......: 34 GB   56 MB/s
     aws_obj_get_duration...: avg=147.18ms min=5.63ms med=50.76ms max=12.22s p(90)=269.73ms p(95)=548.63ms
     aws_obj_get_fails......: 32      0.053209/s
     aws_obj_get_success....: 4136961 6878.801908/s
     data_received..........: 34 GB   56 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=147.25ms min=4.31ms med=50.84ms max=12.23s p(90)=269.82ms p(95)=548.7ms 
     iterations.............: 4136993 6878.855117/s
     vus....................: 46      min=46        max=1015

running (10m01.4s), 0000/1015 VUs, 4136993 complete and 0 interrupted iterations
read ✓ [======================================] 1015 VUs  10m0s

INFO[12:36:00] Load started at:               Tue Oct 01 2024 12:36:00 GMT+0000 (UTC)  source=console
INFO[12:46:01] Load finished at:              Tue Oct 01 2024 12:46:01 GMT+0000 (UTC)  source=console
     aws_obj_get_bytes......: 34 GB   56 MB/s
     aws_obj_get_duration...: avg=148.97ms min=5.6ms    med=51.58ms max=9.33s p(90)=276.81ms p(95)=562.85ms
     aws_obj_get_fails......: 40      0.066649/s
     aws_obj_get_success....: 4085283 6807.043604/s
     data_received..........: 33 GB   56 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=149.05ms min=725.43ms med=51.66ms max=9.33s p(90)=276.89ms p(95)=562.91ms
     iterations.............: 4085323 6807.110254/s
     vus....................: 1015    min=1015      max=1015

running (10m00.2s), 0000/1015 VUs, 4085323 complete and 0 interrupted iterations
read ✓ [======================================] 1015 VUs  10m0s

### 14 nodes 128kb write
INFO[14:16:27] Load started at:               Tue Oct 01 2024 14:16:27 GMT+0000 (UTC)  source=console
INFO[14:26:33] Load finished at:              Tue Oct 01 2024 14:26:33 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 226 GB  373 MB/s
     aws_obj_put_duration...: avg=344.97ms min=25.44ms  med=234.98ms max=10.12s p(90)=644.37ms p(95)=866.24ms
     aws_obj_put_success....: 1721729 2845.713104/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 225 GB  372 MB/s
     iteration_duration.....: avg=354.63ms min=224.25ms med=244.21ms max=10.14s p(90)=654.31ms p(95)=875.96ms
     iterations.............: 1721729 2845.713104/s
     vus....................: 27      min=27        max=1015

running (10m05.0s), 0000/1015 VUs, 1721729 complete and 27 interrupted iterations
write ✓ [======================================] 1015 VUs  10m0s

INFO[14:16:26] Load started at:               Tue Oct 01 2024 14:16:26 GMT+0000 (UTC)  source=console
INFO[14:26:31] Load finished at:              Tue Oct 01 2024 14:26:31 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 238 GB  394 MB/s
     aws_obj_put_duration...: avg=325.27ms min=26.65ms  med=224.1ms  max=9.87s p(90)=608.33ms p(95)=810.38ms
     aws_obj_put_success....: 1818351 3005.39883/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 238 GB  393 MB/s
     iteration_duration.....: avg=335.11ms min=241.17ms med=233.34ms max=9.88s p(90)=618.1ms  p(95)=820.23ms
     iterations.............: 1818351 3005.39883/s
     vus....................: 35      min=35       max=1015

running (10m05.0s), 0000/1015 VUs, 1818351 complete and 35 interrupted iterations
write ✓ [======================================] 1015 VUs  10m0s

### 14 nodes 128kb read
INFO[14:30:00] Load started at:               Tue Oct 01 2024 14:30:00 GMT+0000 (UTC) source=console
INFO[14:40:02] Load finished at:              Tue Oct 01 2024 14:40:02 GMT+0000 (UTC) source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 283 GB  942 MB/s
     aws_obj_get_duration...: avg=126.44ms min=8.99ms   med=104.7ms  max=871.55ms p(90)=230.32ms p(95)=279.68ms
     aws_obj_get_fails......: 165     0.549441/s
     aws_obj_get_success....: 2157372 7183.930678/s
     data_received..........: 283 GB  941 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=126.52ms min=207.15ms med=104.78ms max=871.66ms p(90)=230.4ms  p(95)=279.77ms
     iterations.............: 2157537 7184.480119/s
     vus....................: 910     min=910       max=910

running (5m00.3s), 000/910 VUs, 2157537 complete and 0 interrupted iterations
read ✓ [======================================] 910 VUs  5m0s

INFO[14:30:00] Load started at:               Tue Oct 01 2024 14:30:00 GMT+0000 (UTC)  source=console
INFO[14:40:02] Load finished at:              Tue Oct 01 2024 14:40:02 GMT+0000 (UTC) source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 277 GB  923 MB/s
     aws_obj_get_duration...: avg=129ms    min=8.77ms   med=107.32ms max=950.04ms p(90)=233.87ms p(95)=283.23ms
     aws_obj_get_fails......: 67      0.223214/s
     aws_obj_get_success....: 2114525 7044.652028/s
     data_received..........: 277 GB  923 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=129.09ms min=213.61ms med=107.41ms max=950.14ms p(90)=233.96ms p(95)=283.32ms
     iterations.............: 2114592 7044.875242/s
     vus....................: 910     min=910       max=910

running (5m00.2s), 000/910 VUs, 2114592 complete and 0 interrupted iterations
read ✓ [======================================] 910 VUs  5m0s

### 14 nodes 1mb write
INFO[15:12:43] Load started at:               Tue Oct 01 2024 15:12:43 GMT+0000 (UTC)  source=console
INFO[15:22:44] Load finished at:              Tue Oct 01 2024 15:22:44 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 746 GB 1.2 GB/s
     aws_obj_put_duration...: avg=574.26ms min=76.34ms  med=504.74ms max=5.01s p(90)=924.57ms p(95)=1.11s
     aws_obj_put_success....: 711793 1185.562802/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 746 GB 1.2 GB/s
     iteration_duration.....: avg=590.13ms min=299.65ms med=520.58ms max=5.02s p(90)=940.54ms p(95)=1.13s
     iterations.............: 711793 1185.562802/s
     vus....................: 700    min=700       max=700

running (10m00.4s), 000/700 VUs, 711793 complete and 0 interrupted iterations
write ✓ [======================================] 700 VUs  10m0s

INFO[15:12:42] Load started at:               Tue Oct 01 2024 15:12:42 GMT+0000 (UTC)  source=console
INFO[15:22:43] Load finished at:              Tue Oct 01 2024 15:22:43 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 735 GB 1.2 GB/s
     aws_obj_put_duration...: avg=583.6ms  min=82.78ms  med=510.56ms max=4.47s p(90)=944.15ms p(95)=1.14s
     aws_obj_put_success....: 700732 1166.064094/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 734 GB 1.2 GB/s
     iteration_duration.....: avg=599.59ms min=347.44ms med=526.63ms max=4.49s p(90)=960.3ms  p(95)=1.16s
     iterations.............: 700732 1166.064094/s
     vus....................: 31     min=31        max=700

running (10m00.9s), 000/700 VUs, 700732 complete and 0 interrupted iterations
write ✓ [======================================] 700 VUs  10m0s


### 14 nodes 1mb read
INFO[15:35:12] Load started at:               Tue Oct 01 2024 15:35:12 GMT+0000 (UTC)  source=console
INFO[15:45:13] Load finished at:              Tue Oct 01 2024 15:45:13 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.5 TB  2.6 GB/s
     aws_obj_get_duration...: avg=284.72ms min=22.31ms  med=243.19ms max=3.77s p(90)=489.8ms  p(95)=589.46ms
     aws_obj_get_success....: 1474886 2454.561037/s
     data_received..........: 1.5 TB  2.6 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=284.81ms min=211.17ms med=243.28ms max=3.77s p(90)=489.88ms p(95)=589.56ms
     iterations.............: 1474886 2454.561037/s
     vus....................: 0       min=0         max=700

running (10m00.9s), 000/700 VUs, 1474886 complete and 0 interrupted iterations
read ✓ [======================================] 700 VUs  10m0s

INFO[15:35:12] Load started at:               Tue Oct 01 2024 15:35:12 GMT+0000 (UTC)  source=console
INFO[15:45:13] Load finished at:              Tue Oct 01 2024 15:45:13 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.5 TB  2.6 GB/s
     aws_obj_get_duration...: avg=285.88ms min=23.67ms  med=242.64ms max=3.44s p(90)=492.62ms p(95)=595.46ms
     aws_obj_get_success....: 1468784 2446.341645/s
     data_received..........: 1.5 TB  2.6 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=285.97ms min=191.16ms med=242.74ms max=3.44s p(90)=492.72ms p(95)=595.56ms
     iterations.............: 1468784 2446.341645/s
     vus....................: 700     min=700       max=700

running (10m00.4s), 000/700 VUs, 1468784 complete and 0 interrupted iterations
read ✓ [======================================] 700 VUs  10m0s

### 14 nodes 128mb write
INFO[16:03:55] Load started at:               Tue Oct 01 2024 16:03:55 GMT+0000 (UTC)  source=console
INFO[16:13:56] Load finished at:              Tue Oct 01 2024 16:13:56 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.0 TB 1.7 GB/s
     aws_obj_put_duration...: avg=16.06s min=7.54s    med=15.84s max=30.07s p(90)=21.4s  p(95)=22.67s
     aws_obj_put_success....: 7580   12.509456/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.0 TB 1.7 GB/s
     iteration_duration.....: avg=16.51s min=202.55ms med=16.3s  max=30.61s p(90)=21.85s p(95)=23.13s
     iterations.............: 7574   12.499554/s
     vus....................: 160    min=0       max=210

running (10m05.9s), 000/210 VUs, 7574 complete and 160 interrupted iterations
write ✓ [======================================] 210 VUs  10m0s

INFO[16:03:55] Load started at:               Tue Oct 01 2024 16:03:55 GMT+0000 (UTC)  source=console
INFO[16:13:57] Load finished at:              Tue Oct 01 2024 16:13:57 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.0 TB 1.7 GB/s
     aws_obj_put_duration...: avg=16.04s min=7.84s    med=15.67s max=29.79s p(90)=21.5s  p(95)=22.71s
     aws_obj_put_success....: 7612   12.571539/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.0 TB 1.7 GB/s
     iteration_duration.....: avg=16.48s min=220.74ms med=16.11s max=30.23s p(90)=21.96s p(95)=23.17s
     iterations.............: 7609   12.566585/s
     vus....................: 2      min=0       max=210

running (10m05.5s), 000/210 VUs, 7609 complete and 134 interrupted iterations
write ✓ [======================================] 210 VUs  10m0s

### 13 nodes 8kb write
INFO[17:56:58] Load started at:               Fri Oct 25 2024 17:56:58 GMT+0000 (UTC)  source=console
INFO[18:07:00] Load finished at:              Fri Oct 25 2024 18:07:00 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 15 GB   25 MB/s
     aws_obj_put_duration...: avg=315.65ms min=29.25ms med=173.51ms max=11.17s p(90)=545.06ms p(95)=1.03s
     aws_obj_put_success....: 1865935 3099.652251/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 15 GB   25 MB/s
     iteration_duration.....: avg=324.21ms min=1.43ms  med=184ms    max=11.18s p(90)=554.23ms p(95)=1.03s
     iterations.............: 1865935 3099.652251/s
     vus....................: 11      min=11        max=1007

running (10m02.0s), 0000/1007 VUs, 1865935 complete and 0 interrupted iterations
write ✓ [======================================] 1007 VUs  10m0s

INFO[17:57:00] Load started at:               Fri Oct 25 2024 17:57:00 GMT+0000 (UTC)  source=console
INFO[18:07:01] Load finished at:              Fri Oct 25 2024 18:07:01 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 15 GB   25 MB/s
     aws_obj_put_duration...: avg=327.62ms min=29.63ms  med=176.64ms max=12.37s p(90)=596.61ms p(95)=1.06s
     aws_obj_put_success....: 1798895 2989.984883/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 15 GB   24 MB/s
     iteration_duration.....: avg=336.26ms min=209.18µs med=185.53ms max=12.38s p(90)=605.54ms p(95)=1.07s
     iterations.............: 1798895 2989.984883/s
     vus....................: 485     min=485       max=1007

running (10m01.6s), 0000/1007 VUs, 1798895 complete and 0 interrupted iterations
write ✓ [======================================] 1007 VUs  10m0s

### 13 nodes 128kb write
INFO[17:25:33] Load started at:               Tue Oct 01 2024 17:25:33 GMT+0000 (UTC)  source=console
INFO[17:35:36] Load finished at:              Tue Oct 01 2024 17:35:36 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 258 GB  428 MB/s
     aws_obj_put_duration...: avg=287.59ms min=35.61ms  med=194.61ms max=7.49s p(90)=434.45ms p(95)=626.87ms
     aws_obj_put_success....: 1969669 3261.281223/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 258 GB  427 MB/s
     iteration_duration.....: avg=297.28ms min=282.23ms med=205.17ms max=7.51s p(90)=444.02ms p(95)=636.59ms
     iterations.............: 1969669 3261.281223/s
     vus....................: 25      min=25        max=975

running (10m04.0s), 000/975 VUs, 1969669 complete and 0 interrupted iterations
write ✓ [======================================] 975 VUs  10m0s

INFO[17:25:33] Load started at:               Tue Oct 01 2024 17:25:33 GMT+0000 (UTC)  source=console
INFO[17:35:36] Load finished at:              Tue Oct 01 2024 17:35:36 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 262 GB  434 MB/s
     aws_obj_put_duration...: avg=283.66ms min=35.09ms  med=199.37ms max=7.16s p(90)=446.13ms p(95)=603.52ms
     aws_obj_put_success....: 1997660 3312.731379/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 262 GB  434 MB/s
     iteration_duration.....: avg=293.24ms min=210.29ms med=208.92ms max=7.17s p(90)=456.08ms p(95)=613.3ms 
     iterations.............: 1997660 3312.731379/s
     vus....................: 76      min=76        max=975

running (10m03.0s), 000/975 VUs, 1997660 complete and 0 interrupted iterations
write ✓ [======================================] 975 VUs  10m0s

### 13 nodes 128kb read
INFO[17:05:25] Load started at:               Tue Oct 01 2024 17:05:25 GMT+0000 (UTC)  source=console
INFO[18:15:27] Load finished at:              Tue Oct 01 2024 18:15:27 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 509 GB  848 MB/s
     aws_obj_get_duration...: avg=150.54ms min=9.08ms med=126.79ms max=1.33s p(90)=260ms    p(95)=319.79ms
     aws_obj_get_fails......: 882     1.469372/s
     aws_obj_get_success....: 3882613 6468.257336/s
     data_received..........: 508 GB  847 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=150.61ms min=1.59ms med=126.87ms max=1.33s p(90)=260.07ms p(95)=319.86ms
     iterations.............: 3883495 6469.726708/s
     vus....................: 975     min=975       max=975

running (10m00.3s), 000/975 VUs, 3883495 complete and 0 interrupted iterations
read ✓ [======================================] 975 VUs  10m0s

INFO[17:05:24] Load started at:               Tue Oct 01 2024 17:05:24 GMT+0000 (UTC)  source=console
INFO[18:15:25] Load finished at:              Tue Oct 01 2024 18:15:25 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 512 GB  853 MB/s
     aws_obj_get_duration...: avg=149.62ms min=10.44ms  med=125.89ms max=1.12s p(90)=259.01ms p(95)=318.76ms
     aws_obj_get_fails......: 881     1.467424/s
     aws_obj_get_success....: 3906974 6507.592909/s
     data_received..........: 512 GB  852 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=149.69ms min=205.24ms med=125.96ms max=1.12s p(90)=259.08ms p(95)=318.84ms
     iterations.............: 3907855 6509.060334/s
     vus....................: 975     min=975       max=975

running (10m00.4s), 000/975 VUs, 3907855 complete and 0 interrupted iterations
read ✓ [======================================] 975 VUs  10m0s

### 13 nodes 1mb write
INFO[11:20:40] Load started at:               Wed Oct 02 2024 11:20:40 GMT+0000 (UTC)  source=console
INFO[11:30:41] Load finished at:              Wed Oct 02 2024 11:30:41 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 697 GB 1.2 GB/s
     aws_obj_put_duration...: avg=571.05ms min=106.12ms med=530.19ms max=2.57s p(90)=861.39ms p(95)=991.69ms
     aws_obj_put_success....: 664650 1105.878929/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 697 GB 1.2 GB/s
     iteration_duration.....: avg=587.04ms min=334.32ms med=546.26ms max=2.59s p(90)=877.44ms p(95)=1s      
     iterations.............: 664650 1105.878929/s
     vus....................: 33     min=33        max=650

running (10m01.0s), 000/650 VUs, 664650 complete and 0 interrupted iterations
write ✓ [======================================] 650 VUs  10m0s

INFO[11:20:43] Load started at:               Wed Oct 02 2024 11:20:43 GMT+0000 (UTC)  source=console
INFO[11:30:43] Load finished at:              Wed Oct 02 2024 11:30:43 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 710 GB 1.2 GB/s
     aws_obj_put_duration...: avg=559.84ms min=105.34ms med=520.38ms max=2.6s  p(90)=840.46ms p(95)=963.08ms
     aws_obj_put_success....: 677267 1128.241477/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 710 GB 1.2 GB/s
     iteration_duration.....: avg=575.92ms min=251.18ms med=536.46ms max=2.62s p(90)=856.75ms p(95)=979.22ms
     iterations.............: 677267 1128.241477/s
     vus....................: 650    min=650       max=650

running (10m00.3s), 000/650 VUs, 677267 complete and 0 interrupted iterations
write ✓ [======================================] 650 VUs  10m0s

### 13 nodes 1mb read
INFO[11:49:50] Load started at:               Wed Oct 02 2024 11:49:50 GMT+0000 (UTC)  source=console
INFO[11:59:51] Load finished at:              Wed Oct 02 2024 11:59:51 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.4 TB  2.3 GB/s
     aws_obj_get_duration...: avg=295.79ms min=24.28ms med=268.53ms max=1.73s p(90)=482.63ms p(95)=566.01ms
     aws_obj_get_success....: 1318154 2195.246976/s
     data_received..........: 1.4 TB  2.3 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=295.89ms min=764.1ms med=268.63ms max=1.73s p(90)=482.73ms p(95)=566.1ms 
     iterations.............: 1318154 2195.246976/s
     vus....................: 650     min=650       max=650

running (10m00.5s), 000/650 VUs, 1318154 complete and 0 interrupted iterations
read ✓ [======================================] 650 VUs  10m0s

INFO[11:49:49] Load started at:               Wed Oct 02 2024 11:49:49 GMT+0000 (UTC)  source=console
INFO[11:59:50] Load finished at:              Wed Oct 02 2024 11:59:50 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.4 TB  2.3 GB/s
     aws_obj_get_duration...: avg=293.99ms min=25.44ms  med=267.26ms max=1.72s p(90)=479.19ms p(95)=562.17ms
     aws_obj_get_success....: 1326310 2207.618917/s
     data_received..........: 1.4 TB  2.3 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=294.09ms min=198.73ms med=267.36ms max=1.72s p(90)=479.28ms p(95)=562.27ms
     iterations.............: 1326310 2207.618917/s
     vus....................: 650     min=650       max=650

running (10m00.8s), 000/650 VUs, 1326310 complete and 0 interrupted iterations
read ✓ [======================================] 650 VUs  10m0s

### 13 nodes 128mb write
INFO[12:26:23] Load started at:               Wed Oct 02 2024 12:26:23 GMT+0000 (UTC)  source=console
INFO[12:36:28] Load finished at:              Wed Oct 02 2024 12:36:28 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 844 GB 1.4 GB/s
     aws_obj_put_duration...: avg=18s    min=7.75s    med=17.16s max=59.85s p(90)=24.51s p(95)=28.22s
     aws_obj_put_success....: 6291   10.386955/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 844 GB 1.4 GB/s
     iteration_duration.....: avg=18.44s min=209.09ms med=17.6s  max=1m0s   p(90)=24.94s p(95)=28.65s
     iterations.............: 6286   10.3787/s
     vus....................: 1      min=0       max=195

running (10m05.7s), 000/195 VUs, 6286 complete and 145 interrupted iterations
write ✓ [======================================] 195 VUs  10m0s

INFO[12:26:25] Load started at:               Wed Oct 02 2024 12:26:25 GMT+0000 (UTC)  source=console
INFO[12:36:30] Load finished at:              Wed Oct 02 2024 12:36:30 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 838 GB 1.4 GB/s
     aws_obj_put_duration...: avg=18.19s min=8.27s    med=17.16s max=1m3s p(90)=25.2s  p(95)=30.28s
     aws_obj_put_success....: 6245   10.308835/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 838 GB 1.4 GB/s
     iteration_duration.....: avg=18.63s min=180.27ms med=17.61s max=1m3s p(90)=25.67s p(95)=30.73s
     iterations.............: 6237   10.295629/s
     vus....................: 7      min=0       max=195

running (10m05.8s), 000/195 VUs, 6237 complete and 134 interrupted iterations
write ✓ [======================================] 195 VUs  10m0s

### 13 nodes 128mb read
INFO[12:44:35] Load started at:               Wed Oct 02 2024 12:44:35 GMT+0000 (UTC)  source=console
INFO[12:54:40] Load finished at:              Wed Oct 02 2024 12:54:40 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.7 TB 2.9 GB/s
     aws_obj_get_duration...: avg=9.04s min=2.78s    med=8.71s max=20.63s p(90)=11.92s p(95)=14.68s
     aws_obj_get_success....: 12993  21.480005/s
     data_received..........: 1.7 TB 2.9 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=9.04s min=372.44ms med=8.71s max=20.63s p(90)=11.92s p(95)=14.68s
     iterations.............: 12993  21.480005/s
     vus....................: 30     min=30      max=195

running (10m04.9s), 000/195 VUs, 12993 complete and 0 interrupted iterations
read ✓ [======================================] 195 VUs  10m0s

INFO[12:44:35] Load started at:               Wed Oct 02 2024 12:44:35 GMT+0000 (UTC)  source=console
INFO[12:54:40] Load finished at:              Wed Oct 02 2024 12:54:40 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.8 TB 2.9 GB/s
     aws_obj_get_duration...: avg=8.93s min=3.13s    med=8.48s max=20.66s p(90)=11.97s p(95)=14.64s
     aws_obj_get_success....: 13142  21.703274/s
     data_received..........: 1.8 TB 2.9 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=8.93s min=288.75ms med=8.48s max=20.66s p(90)=11.97s p(95)=14.64s
     iterations.............: 13142  21.703274/s
     vus....................: 15     min=15      max=195

running (10m05.5s), 000/195 VUs, 13142 complete and 13 interrupted iterations
read ✓ [======================================] 195 VUs  10m0s

### 12 nodes 8kb write
INFO[14:07:48] Load started at:               Wed Oct 02 2024 14:07:48 GMT+0000 (UTC)  source=console
INFO[14:17:48] Load finished at:              Wed Oct 02 2024 14:17:48 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 23 GB   38 MB/s
     aws_obj_put_duration...: avg=192.53ms min=41.34ms med=167.1ms  max=5.55s p(90)=305.94ms p(95)=367.11ms
     aws_obj_put_success....: 2775553 4624.491217/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 23 GB   38 MB/s
     iteration_duration.....: avg=201.02ms min=219.8ms med=175.57ms max=5.56s p(90)=313.16ms p(95)=374.38ms
     iterations.............: 2775553 4624.491217/s
     vus....................: 930     min=930       max=930

running (10m00.2s), 000/930 VUs, 2775553 complete and 0 interrupted iterations
write ✓ [======================================] 930 VUs  10m0s

INFO[14:07:46] Load started at:               Wed Oct 02 2024 14:07:46 GMT+0000 (UTC)  source=console
INFO[14:17:47] Load finished at:              Wed Oct 02 2024 14:17:47 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 22 GB   37 MB/s
     aws_obj_put_duration...: avg=198.74ms min=37.88ms med=173.66ms max=5.56s p(90)=314.8ms p(95)=375.08ms
     aws_obj_put_success....: 2691735 4482.781884/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 22 GB   37 MB/s
     iteration_duration.....: avg=207.31ms min=1.83ms  med=184.21ms max=5.57s p(90)=322.3ms p(95)=383.29ms
     iterations.............: 2691735 4482.781884/s
     vus....................: 930     min=930       max=930

running (10m00.5s), 000/930 VUs, 2691735 complete and 0 interrupted iterations
write ✓ [======================================] 930 VUs  10m0s

### 12 nodes 8kb read
INFO[14:30:37] Load started at:               Wed Oct 02 2024 14:30:37 GMT+0000 (UTC)  source=console
INFO[14:40:38] Load finished at:              Wed Oct 02 2024 14:40:38 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 35 GB   58 MB/s
     aws_obj_get_duration...: avg=130.3ms  min=7.36ms   med=77.6ms  max=5.17s p(90)=257.07ms p(95)=419.84ms
     aws_obj_get_fails......: 10      0.01665/s
     aws_obj_get_success....: 4279397 7125.188686/s
     data_received..........: 35 GB   58 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=130.38ms min=196.38ms med=77.68ms max=5.17s p(90)=257.15ms p(95)=419.94ms
     iterations.............: 4279407 7125.205336/s
     vus....................: 930     min=930       max=930

running (10m00.6s), 000/930 VUs, 4279407 complete and 0 interrupted iterations
read ✓ [======================================] 930 VUs  10m0s

INFO[14:30:37] Load started at:               Wed Oct 02 2024 14:30:37 GMT+0000 (UTC)  source=console
INFO[14:40:38] Load finished at:              Wed Oct 02 2024 14:40:38 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 35 GB   58 MB/s
     aws_obj_get_duration...: avg=130.68ms min=7.38ms   med=77.56ms max=6.07s p(90)=257.62ms p(95)=419.4ms 
     aws_obj_get_fails......: 10      0.016626/s
     aws_obj_get_success....: 4267833 7095.876052/s
     data_received..........: 35 GB   58 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=130.76ms min=210.53ms med=77.63ms max=6.07s p(90)=257.69ms p(95)=419.49ms
     iterations.............: 4267843 7095.892678/s
     vus....................: 61      min=61        max=930

running (10m01.5s), 000/930 VUs, 4267843 complete and 0 interrupted iterations
read ✓ [======================================] 930 VUs  10m0s

### 12 nodes 128kb write
INFO[10:24:31] Load started at:               Thu Oct 03 2024 10:24:31 GMT+0000 (UTC)  source=console
INFO[10:34:33] Load finished at:              Thu Oct 03 2024 10:34:33 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 244 GB  405 MB/s
     aws_obj_put_duration...: avg=280.86ms min=32.88ms  med=194.29ms max=7.09s p(90)=439.28ms p(95)=666.01ms
     aws_obj_put_success....: 1859732 3089.032305/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 243 GB  404 MB/s
     iteration_duration.....: avg=290.54ms min=206.95ms med=204.72ms max=7.09s p(90)=449ms    p(95)=675.7ms 
     iterations.............: 1859732 3089.032305/s
     vus....................: 5       min=5         max=900

running (10m02.0s), 000/900 VUs, 1859732 complete and 0 interrupted iterations
write ✓ [======================================] 900 VUs  10m0s

INFO[10:24:31] Load started at:               Thu Oct 03 2024 10:24:31 GMT+0000 (UTC)  source=console
INFO[10:34:33] Load finished at:              Thu Oct 03 2024 10:34:33 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 243 GB  403 MB/s
     aws_obj_put_duration...: avg=282.21ms min=35.94ms med=197.71ms max=7.01s p(90)=433.18ms p(95)=656.86ms
     aws_obj_put_success....: 1851660 3076.597942/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 242 GB  403 MB/s
     iteration_duration.....: avg=291.78ms min=1.96ms  med=208.05ms max=7.02s p(90)=442.43ms p(95)=666.45ms
     iterations.............: 1851660 3076.597942/s
     vus....................: 2       min=2         max=900

running (10m01.9s), 000/900 VUs, 1851660 complete and 0 interrupted iterations
write ✓ [======================================] 900 VUs  10m0s

### 12 nodes 128kb read
INFO[10:48:38] Load started at:               Thu Oct 03 2024 10:48:38 GMT+0000 (UTC)  source=console
INFO[10:58:39] Load finished at:              Thu Oct 03 2024 10:58:39 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 487 GB  811 MB/s
     aws_obj_get_duration...: avg=125.91ms min=8.81ms   med=102.24ms max=3.55s p(90)=232.09ms p(95)=290.56ms
     aws_obj_get_fails......: 85      0.141618/s
     aws_obj_get_success....: 3713831 6187.583278/s
     data_received..........: 486 GB  810 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=125.99ms min=542.46ms med=102.33ms max=3.55s p(90)=232.17ms p(95)=290.65ms
     iterations.............: 3713916 6187.724896/s
     vus....................: 780     min=780       max=780

running (10m00.2s), 000/780 VUs, 3713916 complete and 0 interrupted iterations
read ✓ [======================================] 780 VUs  10m0s

INFO[10:48:37] Load started at:               Thu Oct 03 2024 10:48:37 GMT+0000 (UTC)  source=console
INFO[10:58:38] Load finished at:              Thu Oct 03 2024 10:58:38 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 482 GB  803 MB/s
     aws_obj_get_duration...: avg=127.12ms min=9.62ms   med=103.28ms max=5.56s p(90)=234.05ms p(95)=292.34ms
     aws_obj_get_fails......: 83      0.138213/s
     aws_obj_get_success....: 3678750 6125.911381/s
     data_received..........: 482 GB  802 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=127.2ms  min=198.82ms med=103.36ms max=5.56s p(90)=234.13ms p(95)=292.43ms
     iterations.............: 3678833 6126.049594/s
     vus....................: 780     min=780       max=780

running (10m00.5s), 000/780 VUs, 3678833 complete and 0 interrupted iterations
read ✓ [======================================] 780 VUs  10m0s

### 12 nodes 1mb write 
INFO[11:14:59] Load started at:               Thu Oct 03 2024 11:14:59 GMT+0000 (UTC)  source=console
INFO[11:25:00] Load finished at:              Thu Oct 03 2024 11:25:00 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 620 GB 1.0 GB/s
     aws_obj_put_duration...: avg=592.45ms min=103.36ms med=502.24ms max=7.38s p(90)=832.37ms p(95)=1.06s
     aws_obj_put_success....: 591540 985.02951/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 620 GB 1.0 GB/s
     iteration_duration.....: avg=608.72ms min=391.65ms med=518.51ms max=7.39s p(90)=848.7ms  p(95)=1.08s
     iterations.............: 591540 985.02951/s
     vus....................: 600    min=600     max=600

running (10m00.5s), 000/600 VUs, 591540 complete and 0 interrupted iterations
write ✓ [======================================] 600 VUs  10m0s

INFO[11:14:58] Load started at:               Thu Oct 03 2024 11:14:58 GMT+0000 (UTC)  source=console
INFO[11:25:00] Load finished at:              Thu Oct 03 2024 11:25:00 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 633 GB 1.1 GB/s
     aws_obj_put_duration...: avg=580.23ms min=103.83ms med=499.63ms max=5.47s p(90)=815.82ms p(95)=991.83ms
     aws_obj_put_success....: 603978 1003.557423/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 633 GB 1.1 GB/s
     iteration_duration.....: avg=596.36ms min=390.85ms med=515.71ms max=5.49s p(90)=831.96ms p(95)=1s      
     iterations.............: 603978 1003.557423/s
     vus....................: 21     min=21        max=600

running (10m01.8s), 000/600 VUs, 603978 complete and 0 interrupted iterations
write ✓ [======================================] 600 VUs  10m0s

### 12 nodes 1mb read
NFO[11:35:12] Load started at:               Thu Oct 03 2024 11:35:12 GMT+0000 (UTC)  source=console
INFO[11:45:13] Load finished at:              Thu Oct 03 2024 11:45:13 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.3 TB  2.2 GB/s
     aws_obj_get_duration...: avg=280.25ms min=20.82ms  med=252.77ms max=1.7s p(90)=463.53ms p(95)=540.56ms
     aws_obj_get_success....: 1284296 2137.878306/s
     data_received..........: 1.3 TB  2.2 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=280.35ms min=206.21ms med=252.87ms max=1.7s p(90)=463.62ms p(95)=540.65ms
     iterations.............: 1284296 2137.878306/s
     vus....................: 600     min=600       max=600

running (10m00.7s), 000/600 VUs, 1284296 complete and 0 interrupted iterations
read ✓ [======================================] 600 VUs  10m0s

INFO[11:35:15] Load started at:               Thu Oct 03 2024 11:35:15 GMT+0000 (UTC)  source=console
INFO[11:45:15] Load finished at:              Thu Oct 03 2024 11:45:15 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.3 TB  2.2 GB/s
     aws_obj_get_duration...: avg=282.57ms min=22.95ms med=254.43ms max=1.65s p(90)=468.84ms p(95)=546.4ms
     aws_obj_get_success....: 1273606 2120.661815/s
     data_received..........: 1.3 TB  2.2 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=282.67ms min=1.79ms  med=254.52ms max=1.65s p(90)=468.94ms p(95)=546.5ms
     iterations.............: 1273606 2120.661815/s
     vus....................: 600     min=600       max=600

running (10m00.6s), 000/600 VUs, 1273606 complete and 0 interrupted iterations
read ✓ [======================================] 600 VUs  10m0s

### 12 nodes 128mb write
INFO[12:26:38] Load started at:               Thu Oct 03 2024 12:26:38 GMT+0000 (UTC)  source=console
INFO[12:36:43] Load finished at:              Thu Oct 03 2024 12:36:43 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 758 GB 1.3 GB/s
     aws_obj_put_duration...: avg=18.54s min=8.87s    med=18.29s max=37.58s p(90)=23.94s p(95)=25.41s
     aws_obj_put_success....: 5649   9.325647/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 758 GB 1.3 GB/s
     iteration_duration.....: avg=18.98s min=184.58ms med=18.73s max=38.04s p(90)=24.39s p(95)=25.85s
     iterations.............: 5644   9.317393/s
     vus....................: 0      min=0      max=180

running (10m05.7s), 000/180 VUs, 5644 complete and 126 interrupted iterations
write ✓ [======================================] 180 VUs  10m0s

INFO[12:26:36] Load started at:               Thu Oct 03 2024 12:26:36 GMT+0000 (UTC)  source=console
INFO[12:36:42] Load finished at:              Thu Oct 03 2024 12:36:42 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 805 GB 1.3 GB/s
     aws_obj_put_duration...: avg=17.46s min=7.84s    med=17.37s max=35.25s p(90)=22.46s p(95)=24.15s
     aws_obj_put_success....: 5999   9.902939/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 805 GB 1.3 GB/s
     iteration_duration.....: avg=17.9s  min=172.95ms med=17.81s max=35.68s p(90)=22.9s  p(95)=24.59s
     iterations.............: 5992   9.891384/s
     vus....................: 1      min=0      max=180

running (10m05.8s), 000/180 VUs, 5992 complete and 124 interrupted iterations
write ✓ [======================================] 180 VUs  10m0s

### 12 nodes 128mb read
INFO[12:44:45] Load started at:               Thu Oct 03 2024 12:44:45 GMT+0000 (UTC)  source=console
INFO[12:54:50] Load finished at:              Thu Oct 03 2024 12:54:50 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.7 TB 2.7 GB/s
     aws_obj_get_duration...: avg=8.78s min=2.95s    med=9.1s max=16.96s p(90)=11.25s p(95)=11.86s
     aws_obj_get_success....: 12355  20.423344/s
     data_received..........: 1.7 TB 2.7 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=8.78s min=278.77ms med=9.1s max=16.96s p(90)=11.25s p(95)=11.86s
     iterations.............: 12355  20.423344/s
     vus....................: 1      min=1       max=180

running (10m04.9s), 000/180 VUs, 12355 complete and 0 interrupted iterations
read ✓ [======================================] 180 VUs  10m0s

INFO[12:44:44] Load started at:               Thu Oct 03 2024 12:44:44 GMT+0000 (UTC)  source=console
INFO[12:54:50] Load finished at:              Thu Oct 03 2024 12:54:50 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.6 TB 2.7 GB/s
     aws_obj_get_duration...: avg=8.9s min=2.62s    med=9.14s max=17.85s p(90)=11.11s p(95)=11.69s
     aws_obj_get_success....: 12166  20.079077/s
     data_received..........: 1.6 TB 2.7 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=8.9s min=265.29ms med=9.14s max=17.85s p(90)=11.11s p(95)=11.69s
     iterations.............: 12166  20.079077/s
     vus....................: 36     min=36      max=180

running (10m05.9s), 000/180 VUs, 12166 complete and 33 interrupted iterations
read ✓ [======================================] 180 VUs  10m0s

### 10 nodes 8kb write
INFO[13:43:36] Load started at:               Thu Oct 03 2024 13:43:36 GMT+0000 (UTC)  source=console
INFO[13:53:36] Load finished at:              Thu Oct 03 2024 13:53:36 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 21 GB   35 MB/s
     aws_obj_put_duration...: avg=171.78ms min=36.06ms  med=144.17ms max=1.73s p(90)=264.63ms p(95)=349.41ms
     aws_obj_put_success....: 2578479 4295.171183/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 21 GB   35 MB/s
     iteration_duration.....: avg=180.32ms min=286.88ms med=154.21ms max=1.74s p(90)=272.01ms p(95)=358.72ms
     iterations.............: 2578479 4295.171183/s
     vus....................: 775     min=775       max=775

running (10m00.3s), 000/775 VUs, 2578479 complete and 0 interrupted iterations
write ✓ [======================================] 775 VUs  10m0s

INFO[13:43:34] Load started at:               Thu Oct 03 2024 13:43:34 GMT+0000 (UTC)  source=console
INFO[13:53:35] Load finished at:              Thu Oct 03 2024 13:53:35 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 20 GB   33 MB/s
     aws_obj_put_duration...: avg=182.14ms min=34.41ms  med=148.92ms max=1.8s  p(90)=296.8ms  p(95)=403.2ms 
     aws_obj_put_success....: 2440684 4064.031056/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 20 GB   33 MB/s
     iteration_duration.....: avg=190.52ms min=204.45ms med=156.24ms max=1.81s p(90)=304.28ms p(95)=412.59ms
     iterations.............: 2440684 4064.031056/s
     vus....................: 775     min=775       max=775

running (10m00.6s), 000/775 VUs, 2440684 complete and 0 interrupted iterations
write ✓ [======================================] 775 VUs  10m0s

### 10 nodes 8kb read
INFO[14:26:30] Load started at:               Thu Oct 03 2024 14:26:30 GMT+0000 (UTC)  source=console
INFO[14:36:31] Load finished at:              Thu Oct 03 2024 14:36:31 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 29 GB   48 MB/s
     aws_obj_get_duration...: avg=101.57ms min=6.24ms   med=66.25ms max=3.12s p(90)=211.53ms p(95)=317.26ms
     aws_obj_get_fails......: 4       0.006659/s
     aws_obj_get_success....: 3541328 5895.139902/s
     data_received..........: 29 GB   48 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=101.65ms min=297.47ms med=66.33ms max=3.12s p(90)=211.61ms p(95)=317.34ms
     iterations.............: 3541332 5895.146561/s
     vus....................: 600     min=600       max=600

running (10m00.7s), 000/600 VUs, 3541332 complete and 0 interrupted iterations
read ✓ [======================================] 600 VUs  10m0s

INFO[14:26:28] Load started at:               Thu Oct 03 2024 14:26:28 GMT+0000 (UTC)  source=console
INFO[14:36:29] Load finished at:              Thu Oct 03 2024 14:36:29 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 29 GB   48 MB/s
     aws_obj_get_duration...: avg=101.86ms min=6.25ms   med=66.14ms max=3.2s p(90)=213.97ms p(95)=317.99ms
     aws_obj_get_fails......: 2       0.003327/s
     aws_obj_get_success....: 3531702 5875.407417/s
     data_received..........: 29 GB   48 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=101.94ms min=232.27ms med=66.22ms max=3.2s p(90)=214.05ms p(95)=318.07ms
     iterations.............: 3531704 5875.410744/s
     vus....................: 5       min=5         max=600

running (10m01.1s), 000/600 VUs, 3531704 complete and 0 interrupted iterations
read ✓ [======================================] 600 VUs  10m0s

### 10 nodes 128kb write
INFO[14:47:53] Load started at:               Thu Oct 03 2024 14:47:53 GMT+0000 (UTC)  source=console
INFO[14:57:56] Load finished at:              Thu Oct 03 2024 14:57:56 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 231 GB  383 MB/s
     aws_obj_put_duration...: avg=245.65ms min=34.19ms  med=180.24ms max=6.87s p(90)=355.96ms p(95)=478.96ms
     aws_obj_put_success....: 1763067 2924.067298/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 231 GB  383 MB/s
     iteration_duration.....: avg=255.31ms min=213.16ms med=189.5ms  max=6.88s p(90)=366.06ms p(95)=488.4ms 
     iterations.............: 1763067 2924.067298/s
     vus....................: 22      min=22        max=750

running (10m03.0s), 000/750 VUs, 1763067 complete and 0 interrupted iterations
write ✓ [======================================] 750 VUs  10m0s

INFO[14:47:52] Load started at:               Thu Oct 03 2024 14:47:52 GMT+0000 (UTC)  source=console
INFO[14:57:54] Load finished at:              Thu Oct 03 2024 14:57:54 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 233 GB  387 MB/s
     aws_obj_put_duration...: avg=244.25ms min=34.58ms  med=176.55ms max=7.2s  p(90)=360.28ms p(95)=507.78ms
     aws_obj_put_success....: 1775142 2948.718296/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 232 GB  386 MB/s
     iteration_duration.....: avg=253.78ms min=228.21ms med=187.16ms max=7.21s p(90)=369.52ms p(95)=517.18ms
     iterations.............: 1775142 2948.718296/s
     vus....................: 8       min=8         max=750

running (10m02.0s), 000/750 VUs, 1775142 complete and 0 interrupted iterations
write ✓ [======================================] 750 VUs  10m0s

### 10 nodes 128kb read
INFO[15:19:23] Load started at:               Thu Oct 03 2024 15:19:23 GMT+0000 (UTC)  source=console
INFO[15:29:25] Load finished at:              Thu Oct 03 2024 15:29:25 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 417 GB  695 MB/s
     aws_obj_get_duration...: avg=141.35ms min=11.6ms   med=118.8ms  max=1.65s p(90)=240.32ms p(95)=296.51ms
     aws_obj_get_fails......: 59      0.098262/s
     aws_obj_get_success....: 3181564 5298.774958/s
     data_received..........: 417 GB  694 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=141.43ms min=198.55ms med=118.88ms max=1.65s p(90)=240.41ms p(95)=296.6ms 
     iterations.............: 3181623 5298.87322/s
     vus....................: 750     min=750       max=750

running (10m00.4s), 000/750 VUs, 3181623 complete and 0 interrupted iterations
read ✓ [======================================] 750 VUs  10m0s

INFO[15:19:23] Load started at:               Thu Oct 03 2024 15:19:23 GMT+0000 (UTC)  source=console
INFO[15:29:26] Load finished at:              Thu Oct 03 2024 15:29:26 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 418 GB  697 MB/s
     aws_obj_get_duration...: avg=140.97ms min=10.07ms  med=118.31ms max=1.71s p(90)=238.94ms p(95)=295.21ms
     aws_obj_get_fails......: 50      0.083299/s
     aws_obj_get_success....: 3189730 5314.021044/s
     data_received..........: 418 GB  696 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=141.06ms min=204.67ms med=118.4ms  max=1.71s p(90)=239.03ms p(95)=295.29ms
     iterations.............: 3189780 5314.104343/s
     vus....................: 750     min=750       max=750

running (10m00.2s), 000/750 VUs, 3189780 complete and 0 interrupted iterations
read ✓ [======================================] 750 VUs  10m0s

### 10 nodes 1mb write
INFO[15:48:30] Load started at:               Thu Oct 03 2024 15:48:30 GMT+0000 (UTC)  source=console
INFO[15:58:31] Load finished at:              Thu Oct 03 2024 15:58:31 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 547 GB 910 MB/s
     aws_obj_put_duration...: avg=415.2ms  min=66.28ms  med=377.24ms max=3.86s p(90)=645.46ms p(95)=761.03ms
     aws_obj_put_success....: 521384 867.901026/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 547 GB 910 MB/s
     iteration_duration.....: avg=431.65ms min=387.61ms med=393.71ms max=3.88s p(90)=661.94ms p(95)=777.56ms
     iterations.............: 521384 867.901026/s
     vus....................: 375    min=375      max=375

running (10m00.7s), 000/375 VUs, 521384 complete and 0 interrupted iterations
write ✓ [======================================] 375 VUs  10m0s

INFO[15:48:31] Load started at:               Thu Oct 03 2024 15:48:31 GMT+0000 (UTC)  source=console
INFO[15:58:32] Load finished at:              Thu Oct 03 2024 15:58:32 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 535 GB 892 MB/s
     aws_obj_put_duration...: avg=424.5ms  min=63.07ms  med=381.84ms max=3.53s p(90)=673.14ms p(95)=796.18ms
     aws_obj_put_success....: 510427 850.387801/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 535 GB 891 MB/s
     iteration_duration.....: avg=440.85ms min=378.72ms med=398.25ms max=3.54s p(90)=689.7ms  p(95)=812.78ms
     iterations.............: 510427 850.387801/s
     vus....................: 375    min=375      max=375

running (10m00.2s), 000/375 VUs, 510427 complete and 0 interrupted iterations
write ✓ [======================================] 375 VUs  10m0s

### 10 nodes 1mb read
INFO[16:10:15] Load started at:               Thu Oct 03 2024 16:10:15 GMT+0000 (UTC)  source=console
INFO[16:20:15] Load finished at:              Thu Oct 03 2024 16:20:15 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.1 TB  1.8 GB/s
     aws_obj_get_duration...: avg=214.46ms min=22.84ms  med=192.24ms max=1.36s p(90)=352.66ms p(95)=429.91ms
     aws_obj_get_success....: 1048741 1746.250799/s
     data_received..........: 1.1 TB  1.8 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=214.55ms min=248.06ms med=192.34ms max=1.36s p(90)=352.75ms p(95)=430.01ms
     iterations.............: 1048741 1746.250799/s
     vus....................: 375     min=375       max=375

running (10m00.6s), 000/375 VUs, 1048741 complete and 0 interrupted iterations
read ✓ [======================================] 375 VUs  10m0s

INFO[16:10:16] Load started at:               Thu Oct 03 2024 16:10:16 GMT+0000 (UTC)  source=console
INFO[16:20:16] Load finished at:              Thu Oct 03 2024 16:20:16 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.1 TB  1.8 GB/s
     aws_obj_get_duration...: avg=215.19ms min=23.33ms  med=192.83ms max=1.44s p(90)=354.45ms p(95)=432.5ms
     aws_obj_get_success....: 1045112 1741.333228/s
     data_received..........: 1.1 TB  1.8 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=215.28ms min=311.62ms med=192.93ms max=1.44s p(90)=354.56ms p(95)=432.6ms
     iterations.............: 1045112 1741.333228/s
     vus....................: 375     min=375       max=375

running (10m00.2s), 000/375 VUs, 1045112 complete and 0 interrupted iterations
read ✓ [======================================] 375 VUs  10m0s

### 10 nodes 128mb write
INFO[16:39:53] Load started at:               Thu Oct 03 2024 16:39:53 GMT+0000 (UTC)  source=console
INFO[16:49:58] Load finished at:              Thu Oct 03 2024 16:49:58 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 685 GB 1.1 GB/s
     aws_obj_put_duration...: avg=17.08s min=8.52s    med=16.76s max=36.68s p(90)=22.29s p(95)=24.04s
     aws_obj_put_success....: 5104   8.430748/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 685 GB 1.1 GB/s
     iteration_duration.....: avg=17.51s min=154.58ms med=17.2s  max=37.14s p(90)=22.75s p(95)=24.49s
     iterations.............: 5104   8.430748/s
     vus....................: 104    min=0      max=150

running (10m05.4s), 000/150 VUs, 5104 complete and 103 interrupted iterations
write ✓ [======================================] 150 VUs  10m0s

INFO[16:39:51] Load started at:               Thu Oct 03 2024 16:39:51 GMT+0000 (UTC)  source=console
INFO[16:49:57] Load finished at:              Thu Oct 03 2024 16:49:57 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 703 GB 1.2 GB/s
     aws_obj_put_duration...: avg=16.65s min=7.77s    med=16.31s max=32.57s p(90)=22.14s p(95)=23.89s
     aws_obj_put_success....: 5237   8.647135/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 703 GB 1.2 GB/s
     iteration_duration.....: avg=17.08s min=157.96ms med=16.74s max=33.01s p(90)=22.58s p(95)=24.32s
     iterations.............: 5230   8.635577/s
     vus....................: 116    min=0      max=150

running (10m05.6s), 000/150 VUs, 5230 complete and 111 interrupted iterations
write ✓ [======================================] 150 VUs  10m0s

### 10 nodes 128mb read
INFO[16:56:32] Load started at:               Thu Oct 03 2024 16:56:32 GMT+0000 (UTC)  source=console
INFO[17:06:37] Load finished at:              Thu Oct 03 2024 17:06:37 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.4 TB 2.4 GB/s
     aws_obj_get_duration...: avg=8.41s min=2.74s    med=8.46s max=14.24s p(90)=10.53s p(95)=11.07s
     aws_obj_get_success....: 10747  17.764207/s
     data_received..........: 1.4 TB 2.4 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=8.41s min=382.44ms med=8.46s max=14.24s p(90)=10.53s p(95)=11.07s
     iterations.............: 10747  17.764207/s
     vus....................: 1      min=1       max=150

running (10m05.0s), 000/150 VUs, 10747 complete and 0 interrupted iterations
read ✓ [======================================] 150 VUs  10m0s

INFO[16:56:31] Load started at:               Thu Oct 03 2024 16:56:31 GMT+0000 (UTC)  source=console
INFO[17:06:37] Load finished at:              Thu Oct 03 2024 17:06:37 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.4 TB 2.4 GB/s
     aws_obj_get_duration...: avg=8.5s min=2.85s    med=8.54s max=13.93s p(90)=10.67s p(95)=11.24s
     aws_obj_get_success....: 10629  17.539653/s
     data_received..........: 1.4 TB 2.4 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=8.5s min=314.51ms med=8.54s max=13.93s p(90)=10.67s p(95)=11.24s
     iterations.............: 10629  17.539653/s
     vus....................: 1      min=1       max=150

running (10m06.0s), 000/150 VUs, 10629 complete and 10 interrupted iterations
read ✓ [======================================] 150 VUs  10m0s

### 8 nodes 8kb write
INFO[10:30:38] Load started at:               Fri Oct 04 2024 10:30:38 GMT+0000 (UTC)  source=console
INFO[10:40:40] Load finished at:              Fri Oct 04 2024 10:40:40 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 8.4 GB  14 MB/s
     aws_obj_put_duration...: avg=355.37ms min=33.99ms  med=210.07ms max=14.75s p(90)=651.33ms p(95)=922.25ms
     aws_obj_put_success....: 1022903 1699.637911/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 8.4 GB  14 MB/s
     iteration_duration.....: avg=363.7ms  min=302.61ms med=219.06ms max=14.76s p(90)=659.88ms p(95)=930.56ms
     iterations.............: 1022903 1699.637911/s
     vus....................: 17      min=17        max=620

running (10m01.8s), 000/620 VUs, 1022903 complete and 0 interrupted iterations
write ✓ [======================================] 620 VUs  10m0s

INFO[10:30:36] Load started at:               Fri Oct 04 2024 10:30:36 GMT+0000 (UTC)  source=console
INFO[10:40:37] Load finished at:              Fri Oct 04 2024 10:40:37 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 8.4 GB  14 MB/s
     aws_obj_put_duration...: avg=355ms    min=35.18ms  med=210.59ms max=13.44s p(90)=647.22ms p(95)=912.18ms
     aws_obj_put_success....: 1023632 1705.17227/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 8.4 GB  14 MB/s
     iteration_duration.....: avg=363.44ms min=207.11ms med=219.48ms max=13.45s p(90)=655.98ms p(95)=920.97ms
     iterations.............: 1023632 1705.17227/s
     vus....................: 620     min=620      max=620

running (10m00.3s), 000/620 VUs, 1023632 complete and 0 interrupted iterations
write ✓ [======================================] 620 VUs  10m0s

### 8 nodes 8kb read
INFO[10:49:20] Load started at:               Fri Oct 04 2024 10:49:20 GMT+0000 (UTC)  source=console
INFO[10:59:22] Load finished at:              Fri Oct 04 2024 10:59:22 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 20 GB   34 MB/s
     aws_obj_get_duration...: avg=151.45ms min=5.78ms   med=52.46ms max=6.88s p(90)=240.41ms p(95)=645.89ms
     aws_obj_get_fails......: 282     0.469093/s
     aws_obj_get_success....: 2455304 4084.274678/s
     data_received..........: 20 GB   33 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=151.52ms min=196.93ms med=52.53ms max=6.88s p(90)=240.46ms p(95)=645.86ms
     iterations.............: 2455586 4084.743771/s
     vus....................: 21      min=21        max=620

running (10m01.2s), 000/620 VUs, 2455586 complete and 0 interrupted iterations
read ✓ [======================================] 620 VUs  10m0s

INFO[10:49:20] Load started at:               Fri Oct 04 2024 10:49:20 GMT+0000 (UTC)  source=console
INFO[10:59:21] Load finished at:              Fri Oct 04 2024 10:59:21 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 21 GB   34 MB/s
     aws_obj_get_duration...: avg=147.82ms min=5.95ms   med=51.28ms max=6.54s p(90)=233.11ms p(95)=618.06ms
     aws_obj_get_fails......: 245     0.406738/s
     aws_obj_get_success....: 2515936 4176.841096/s
     data_received..........: 21 GB   34 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=147.89ms min=200.24ms med=51.36ms max=6.54s p(90)=233.17ms p(95)=618.09ms
     iterations.............: 2516181 4177.247834/s
     vus....................: 7       min=7         max=620

running (10m02.4s), 000/620 VUs, 2516181 complete and 0 interrupted iterations
read ✓ [======================================] 620 VUs  10m0s

### 8 nodes 128kb write
NFO[12:39:47] Load started at:               Fri Oct 04 2024 12:39:47 GMT+0000 (UTC)  source=console
INFO[12:49:50] Load finished at:              Fri Oct 04 2024 12:49:50 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 109 GB 181 MB/s
     aws_obj_put_duration...: avg=422.6ms  min=33.1ms   med=214.87ms max=14.78s p(90)=758.63ms p(95)=1.41s
     aws_obj_put_success....: 834047 1383.10943/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 109 GB 181 MB/s
     iteration_duration.....: avg=432.05ms min=208.75ms med=224.47ms max=14.79s p(90)=768.08ms p(95)=1.42s
     iterations.............: 834047 1383.10943/s
     vus....................: 3      min=3        max=600

running (10m03.0s), 000/600 VUs, 834047 complete and 0 interrupted iterations
write ✓ [======================================] 600 VUs  10m0s

INFO[12:39:48] Load started at:               Fri Oct 04 2024 12:39:48 GMT+0000 (UTC)  source=console
INFO[12:49:50] Load finished at:              Fri Oct 04 2024 12:49:50 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 113 GB 188 MB/s
     aws_obj_put_duration...: avg=407.64ms min=31.64ms med=204.07ms max=11.87s p(90)=742.14ms p(95)=1.37s
     aws_obj_put_success....: 864065 1434.481434/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 113 GB 188 MB/s
     iteration_duration.....: avg=416.99ms min=1.56ms  med=213.71ms max=11.88s p(90)=751.52ms p(95)=1.37s
     iterations.............: 864065 1434.481434/s
     vus....................: 94     min=94        max=600

running (10m02.4s), 000/600 VUs, 864065 complete and 0 interrupted iterations
write ✓ [======================================] 600 VUs  10m0s

### 8 nodes 128kb read
INFO[13:21:32] Load started at:               Fri Oct 04 2024 13:21:32 GMT+0000 (UTC)  source=console
INFO[13:31:35] Load finished at:              Fri Oct 04 2024 13:31:35 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 315 GB  524 MB/s
     aws_obj_get_duration...: avg=124.83ms min=7.74ms   med=96.31ms max=1.78s p(90)=254.76ms p(95)=314.4ms 
     aws_obj_get_fails......: 324     0.539703/s
     aws_obj_get_success....: 2401486 4000.278243/s
     data_received..........: 315 GB  524 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=124.92ms min=186.96ms med=96.39ms max=1.8s  p(90)=254.85ms p(95)=314.48ms
     iterations.............: 2401810 4000.817946/s
     vus....................: 500     min=500       max=500

running (10m00.3s), 000/500 VUs, 2401810 complete and 0 interrupted iterations
read ✓ [======================================] 500 VUs  10m0s

INFO[13:21:32] Load started at:               Fri Oct 04 2024 13:21:32 GMT+0000 (UTC)  source=console
INFO[13:31:35] Load finished at:              Fri Oct 04 2024 13:31:35 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 312 GB  520 MB/s
     aws_obj_get_duration...: avg=125.88ms min=7.75ms   med=97.35ms max=1.74s p(90)=256.24ms p(95)=315.78ms
     aws_obj_get_fails......: 533     0.887652/s
     aws_obj_get_success....: 2381086 3965.432749/s
     data_received..........: 312 GB  519 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=125.96ms min=209.96ms med=97.43ms max=1.74s p(90)=256.31ms p(95)=315.85ms
     iterations.............: 2381619 3966.320401/s
     vus....................: 500     min=500       max=500

running (10m00.5s), 000/500 VUs, 2381619 complete and 0 interrupted iterations
read ✓ [======================================] 500 VUs  10m0s

### 8 nodes 1mb write
INFO[06:58:50] Load started at:               Fri Oct 25 2024 06:58:50 GMT+0000 (UTC)  source=console
INFO[07:08:52] Load finished at:              Fri Oct 25 2024 07:08:52 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 411 GB 683 MB/s
     aws_obj_put_duration...: avg=596.32ms min=93.07ms  med=511.32ms max=3.55s p(90)=1.02s p(95)=1.22s
     aws_obj_put_success....: 391585 651.49534/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 411 GB 683 MB/s
     iteration_duration.....: avg=613.12ms min=420.66µs med=528.23ms max=3.56s p(90)=1.04s p(95)=1.23s
     iterations.............: 391585 651.49534/s
     vus....................: 9      min=9       max=400

running (10m01.1s), 000/400 VUs, 391585 complete and 0 interrupted iterations
write ✓ [======================================] 400 VUs  10m0s

INFO[06:58:53] Load started at:               Fri Oct 25 2024 06:58:53 GMT+0000 (UTC)  source=console
INFO[07:08:53] Load finished at:              Fri Oct 25 2024 07:08:53 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 396 GB 659 MB/s
     aws_obj_put_duration...: avg=619.76ms min=81.12ms  med=539.59ms max=3.18s p(90)=1.05s p(95)=1.24s
     aws_obj_put_success....: 377154 628.293522/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 395 GB 659 MB/s
     iteration_duration.....: avg=636.45ms min=347.35µs med=556.36ms max=3.2s  p(90)=1.06s p(95)=1.26s
     iterations.............: 377154 628.293522/s
     vus....................: 400    min=400      max=400

running (10m00.3s), 000/400 VUs, 377154 complete and 0 interrupted iterations
write ✓ [======================================] 400 VUs  10m0s

### 8 nodes 1mb read
INFO[07:19:50] Load started at:               Fri Oct 25 2024 07:19:50 GMT+0000 (UTC)  source=console
INFO[07:29:51] Load finished at:              Fri Oct 25 2024 07:29:51 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 921 GB 1.5 GB/s
     aws_obj_get_duration...: avg=273.22ms min=23.05ms  med=230.88ms max=4.35s p(90)=476.53ms p(95)=586.2ms 
     aws_obj_get_fails......: 20     0.033279/s
     aws_obj_get_success....: 878271 1461.394981/s
     data_received..........: 921 GB 1.5 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=273.32ms min=654.96µs med=230.98ms max=4.35s p(90)=476.63ms p(95)=586.29ms
     iterations.............: 878291 1461.42826/s
     vus....................: 1      min=1         max=400

running (10m01.0s), 000/400 VUs, 878291 complete and 0 interrupted iterations
read ✓ [======================================] 400 VUs  10m0s


INFO[07:19:51] Load started at:               Fri Oct 25 2024 07:19:51 GMT+0000 (UTC)  source=console
INFO[07:29:52] Load finished at:              Fri Oct 25 2024 07:29:52 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 917 GB 1.5 GB/s
     aws_obj_get_duration...: avg=274.31ms min=23.67ms med=232.33ms max=4.33s p(90)=478.43ms p(95)=589.23ms
     aws_obj_get_fails......: 22     0.036627/s
     aws_obj_get_success....: 874709 1456.258286/s
     data_received..........: 917 GB 1.5 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=274.41ms min=202.9µs med=232.42ms max=4.33s p(90)=478.52ms p(95)=589.33ms
     iterations.............: 874731 1456.294912/s
     vus....................: 400    min=400       max=400

running (10m00.7s), 000/400 VUs, 874731 complete and 0 interrupted iterations
read ✓ [======================================] 400 VUs  10m0s


### 8 nodes 128mb write
INFO[15:46:48] Load started at:               Fri Oct 04 2024 15:46:48 GMT+0000 (UTC)  source=console
INFO[15:56:53] Load finished at:              Fri Oct 04 2024 15:56:53 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 671 GB 1.1 GB/s
     aws_obj_put_duration...: avg=13.91s min=6.87s    med=13.62s max=28.86s p(90)=18.13s p(95)=19.52s
     aws_obj_put_success....: 4998   8.255612/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 671 GB 1.1 GB/s
     iteration_duration.....: avg=14.35s min=136.17µs med=14.05s max=29.45s p(90)=18.57s p(95)=19.96s
     iterations.............: 4998   8.255612/s
     vus....................: 75     min=0      max=120

running (10m05.4s), 000/120 VUs, 4998 complete and 75 interrupted iterations
write ✓ [======================================] 120 VUs  10m0s

INFO[15:46:49] Load started at:               Fri Oct 04 2024 15:46:49 GMT+0000 (UTC)  source=console
INFO[15:56:55] Load finished at:              Fri Oct 04 2024 15:56:55 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 678 GB 1.1 GB/s
     aws_obj_put_duration...: avg=13.77s min=6.73s    med=13.52s max=25.09s p(90)=17.89s p(95)=19.16s
     aws_obj_put_success....: 5052   8.340935/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 678 GB 1.1 GB/s
     iteration_duration.....: avg=14.2s  min=129.23µs med=13.96s max=25.5s  p(90)=18.35s p(95)=19.6s 
     iterations.............: 5051   8.339284/s
     vus....................: 67     min=0      max=120

running (10m05.7s), 000/120 VUs, 5051 complete and 66 interrupted iterations
write ✓ [======================================] 120 VUs  10m0s

### 8 nodes 128mb read
INFO[15:58:48] Load started at:               Fri Oct 04 2024 15:58:48 GMT+0000 (UTC)  source=console
INFO[16:08:54] Load finished at:              Fri Oct 04 2024 16:08:54 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.2 TB 2.0 GB/s
     aws_obj_get_duration...: avg=7.97s min=2.45s    med=7.66s max=17.42s p(90)=10.25s p(95)=11s
     aws_obj_get_success....: 9062   14.954998/s
     data_received..........: 1.2 TB 2.0 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=7.97s min=373.82µs med=7.66s max=17.42s p(90)=10.25s p(95)=11s
     iterations.............: 9062   14.954998/s
     vus....................: 19     min=19      max=120

running (10m06.0s), 000/120 VUs, 9062 complete and 17 interrupted iterations
read ✓ [======================================] 120 VUs  10m0s

INFO[15:58:49] Load started at:               Fri Oct 04 2024 15:58:49 GMT+0000 (UTC)  source=console
INFO[16:08:54] Load finished at:              Fri Oct 04 2024 16:08:54 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.2 TB 2.0 GB/s
     aws_obj_get_duration...: avg=7.88s min=3.09s    med=7.57s max=17.58s p(90)=10.08s p(95)=10.81s
     aws_obj_get_success....: 9172   15.165742/s
     data_received..........: 1.2 TB 2.0 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=7.88s min=466.77µs med=7.57s max=17.58s p(90)=10.08s p(95)=10.81s
     iterations.............: 9172   15.165742/s
     vus....................: 14     min=14      max=120

running (10m04.8s), 000/120 VUs, 9172 complete and 0 interrupted iterations
read ✓ [======================================] 120 VUs  10m0s

### 6 nodes 8kb write
INFO[08:36:00] Load started at:               Fri Oct 25 2024 08:36:00 GMT+0000 (UTC)  source=console
INFO[08:46:03] Load finished at:              Fri Oct 25 2024 08:46:03 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 3.0 GB 4.9 MB/s
     aws_obj_put_duration...: avg=764.29ms min=33.16ms  med=432.99ms max=8.69s p(90)=1.91s p(95)=2.49s
     aws_obj_put_success....: 361640 599.925411/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 3.0 GB 4.9 MB/s
     iteration_duration.....: avg=773.03ms min=336.28µs med=441.72ms max=8.69s p(90)=1.92s p(95)=2.49s
     iterations.............: 361640 599.925411/s
     vus....................: 38     min=38       max=465

running (10m02.8s), 000/465 VUs, 361640 complete and 0 interrupted iterations
write ✓ [======================================] 465 VUs  10m0s

INFO[08:36:04] Load started at:               Fri Oct 25 2024 08:36:04 GMT+0000 (UTC)  source=console
INFO[08:46:05] Load finished at:              Fri Oct 25 2024 08:46:05 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 2.8 GB 4.7 MB/s
     aws_obj_put_duration...: avg=797.79ms min=35.41ms  med=483.25ms max=8.64s p(90)=1.93s p(95)=2.49s
     aws_obj_put_success....: 346177 575.999115/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 2.8 GB 4.7 MB/s
     iteration_duration.....: avg=806.32ms min=292.86µs med=491.99ms max=8.65s p(90)=1.94s p(95)=2.5s 
     iterations.............: 346177 575.999115/s
     vus....................: 1      min=1        max=465

running (10m01.0s), 000/465 VUs, 346177 complete and 0 interrupted iterations
write ✓ [======================================] 465 VUs  10m0s

### 6 nodes 8kb read
INFO[08:47:16] Load started at:               Fri Oct 25 2024 08:47:16 GMT+0000 (UTC)  source=console
INFO[08:57:18] Load finished at:              Fri Oct 25 2024 08:57:18 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 17 GB   29 MB/s
     aws_obj_get_duration...: avg=131.83ms min=6.19ms   med=114.42ms max=1.1s p(90)=241.82ms p(95)=287.4ms 
     aws_obj_get_fails......: 7543    12.569847/s
     aws_obj_get_success....: 2110588 3517.137628/s
     data_received..........: 17 GB   29 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=131.7ms  min=245.04µs med=114.29ms max=1.1s p(90)=241.71ms p(95)=287.29ms
     iterations.............: 2118131 3529.707476/s
     vus....................: 465     min=465       max=465

running (10m00.1s), 000/465 VUs, 2118131 complete and 0 interrupted iterations
read ✓ [======================================] 465 VUs  10m0s

INFO[08:47:16] Load started at:               Fri Oct 25 2024 08:47:16 GMT+0000 (UTC)  source=console
INFO[08:57:18] Load finished at:              Fri Oct 25 2024 08:57:18 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 17 GB   29 MB/s
     aws_obj_get_duration...: avg=133.45ms min=6.43ms   med=115.91ms max=1.26s p(90)=244.83ms p(95)=290.55ms
     aws_obj_get_fails......: 7716    12.852978/s
     aws_obj_get_success....: 2084889 3472.917726/s
     data_received..........: 17 GB   28 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=133.32ms min=188.58µs med=115.76ms max=1.26s p(90)=244.7ms  p(95)=290.43ms
     iterations.............: 2092605 3485.770704/s
     vus....................: 465     min=465       max=465

running (10m00.3s), 000/465 VUs, 2092605 complete and 0 interrupted iterations
read ✓ [======================================] 465 VUs  10m0s

### 6 nodes 128kb write
INFO[12:56:59] Load started at:               Sun Oct 06 2024 12:56:59 GMT+0000 (UTC)  source=console
INFO[13:06:59] Load finished at:              Sun Oct 06 2024 13:06:59 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 147 GB  245 MB/s
     aws_obj_put_duration...: avg=230.74ms min=24.72ms  med=165.41ms max=3.79s p(90)=448.07ms p(95)=584.84ms
     aws_obj_put_success....: 1122992 1870.989196/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 147 GB  245 MB/s
     iteration_duration.....: avg=240.42ms min=269.01µs med=174.82ms max=3.81s p(90)=457.68ms p(95)=594.61ms
     iterations.............: 1122992 1870.989196/s
     vus....................: 450     min=450       max=450

running (10m00.2s), 000/450 VUs, 1122992 complete and 0 interrupted iterations
write ✓ [======================================] 450 VUs  10m0s

INFO[12:56:58] Load started at:               Sun Oct 06 2024 12:56:58 GMT+0000 (UTC)  source=console
INFO[13:06:59] Load finished at:              Sun Oct 06 2024 13:06:59 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 151 GB  251 MB/s
     aws_obj_put_duration...: avg=224.89ms min=27.51ms  med=160.4ms  max=3.88s p(90)=438.8ms  p(95)=572.53ms
     aws_obj_put_success....: 1151656 1917.087312/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 151 GB  251 MB/s
     iteration_duration.....: avg=234.52ms min=197.21µs med=170.07ms max=3.88s p(90)=448.38ms p(95)=582.4ms 
     iterations.............: 1151656 1917.087312/s
     vus....................: 450     min=450       max=450

running (10m00.7s), 000/450 VUs, 1151656 complete and 0 interrupted iterations
write ✓ [======================================] 450 VUs  10m0s

### 6 nodes 128kb read
INFO[13:08:35] Load started at:               Sun Oct 06 2024 13:08:35 GMT+0000 (UTC)  source=console
INFO[13:18:36] Load finished at:              Sun Oct 06 2024 13:18:36 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 236 GB  394 MB/s
     aws_obj_get_duration...: avg=149.63ms min=7.37ms   med=105.75ms max=3.3s p(90)=283.54ms p(95)=396.99ms
     aws_obj_get_fails......: 4       0.006659/s
     aws_obj_get_success....: 1803254 3002.155809/s
     data_received..........: 236 GB  393 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=149.72ms min=221.21µs med=105.84ms max=3.3s p(90)=283.63ms p(95)=397.08ms
     iterations.............: 1803258 3002.162468/s
     vus....................: 450     min=450       max=450

running (10m00.7s), 000/450 VUs, 1803258 complete and 0 interrupted iterations
read ✓ [======================================] 450 VUs  10m0s

INFO[13:08:36] Load started at:               Sun Oct 06 2024 13:08:36 GMT+0000 (UTC)  source=console
INFO[13:18:37] Load finished at:              Sun Oct 06 2024 13:18:37 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 244 GB  407 MB/s
     aws_obj_get_duration...: avg=144.79ms min=7.53ms   med=103.3ms  max=3.14s p(90)=274.31ms p(95)=383.18ms
     aws_obj_get_fails......: 2       0.00333/s
     aws_obj_get_success....: 1863717 3102.91808/s
     data_received..........: 244 GB  407 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=144.88ms min=201.17µs med=103.38ms max=3.14s p(90)=274.4ms  p(95)=383.27ms
     iterations.............: 1863719 3102.921409/s
     vus....................: 450     min=450       max=450

running (10m00.6s), 000/450 VUs, 1863719 complete and 0 interrupted iterations
read ✓ [======================================] 450 VUs  10m0s

### 6 nodes 1mb write
NFO[19:18:04] Load started at:               Fri Oct 04 2024 19:18:04 GMT+0000 (UTC)  source=console
INFO[19:28:04] Load finished at:              Fri Oct 04 2024 19:28:04 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 342 GB 569 MB/s
     aws_obj_put_duration...: avg=535.07ms min=58.32ms  med=454.99ms max=5.02s p(90)=950.85ms p(95)=1.15s
     aws_obj_put_success....: 325991 542.930825/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 342 GB 569 MB/s
     iteration_duration.....: avg=552.27ms min=214.83µs med=472.32ms max=5.03s p(90)=967.89ms p(95)=1.17s
     iterations.............: 325991 542.930825/s
     vus....................: 300    min=300      max=300

running (10m00.4s), 000/300 VUs, 325991 complete and 0 interrupted iterations
write ✓ [======================================] 300 VUs  10m0s

INFO[19:18:01] Load started at:               Fri Oct 04 2024 19:18:01 GMT+0000 (UTC)  source=console
INFO[19:28:02] Load finished at:              Fri Oct 04 2024 19:28:02 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 335 GB 558 MB/s
     aws_obj_put_duration...: avg=546.25ms min=65.89ms  med=462.61ms max=4.73s p(90)=970.46ms p(95)=1.18s
     aws_obj_put_success....: 319593 531.903428/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 335 GB 557 MB/s
     iteration_duration.....: avg=563.31ms min=482.82µs med=479.68ms max=4.75s p(90)=987.53ms p(95)=1.2s 
     iterations.............: 319593 531.903428/s
     vus....................: 1      min=1        max=300

running (10m00.8s), 000/300 VUs, 319593 complete and 0 interrupted iterations
write ✓ [======================================] 300 VUs  10m0s

### 6 nodes 1mb read
INFO[19:40:01] Load started at:               Fri Oct 04 2024 19:40:01 GMT+0000 (UTC)  source=console
INFO[19:50:02] Load finished at:              Fri Oct 04 2024 19:50:02 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 682 GB 1.1 GB/s
     aws_obj_get_duration...: avg=276.86ms min=18.06ms med=216.96ms max=5.54s p(90)=487.54ms p(95)=613.6ms
     aws_obj_get_success....: 650036 1082.08781/s
     data_received..........: 682 GB 1.1 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=276.96ms min=1.61ms  med=217.06ms max=5.54s p(90)=487.64ms p(95)=613.7ms
     iterations.............: 650036 1082.08781/s
     vus....................: 300    min=300      max=300

running (10m00.7s), 000/300 VUs, 650036 complete and 0 interrupted iterations
read ✓ [======================================] 300 VUs  10m0s

INFO[19:40:02] Load started at:               Fri Oct 04 2024 19:40:02 GMT+0000 (UTC)  source=console
INFO[19:50:03] Load finished at:              Fri Oct 04 2024 19:50:03 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 674 GB 1.1 GB/s
     aws_obj_get_duration...: avg=280.09ms min=18.93ms  med=217.35ms max=5.26s p(90)=492.98ms p(95)=628.89ms
     aws_obj_get_success....: 642467 1069.578338/s
     data_received..........: 674 GB 1.1 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=280.19ms min=551.13µs med=217.45ms max=5.26s p(90)=493.08ms p(95)=628.98ms
     iterations.............: 642467 1069.578338/s
     vus....................: 300    min=300       max=300

running (10m00.7s), 000/300 VUs, 642467 complete and 0 interrupted iterations
read ✓ [======================================] 300 VUs  10m0s

### 6 nodes 128mb write
INFO[18:19:58] Load started at:               Fri Oct 04 2024 18:19:58 GMT+0000 (UTC)  source=console
INFO[18:30:03] Load finished at:              Fri Oct 04 2024 18:30:03 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 436 GB 721 MB/s
     aws_obj_put_duration...: avg=16.06s min=6.51s    med=15.48s max=31.88s p(90)=22.29s p(95)=24.12s
     aws_obj_put_success....: 3251   5.369735/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 436 GB 721 MB/s
     iteration_duration.....: avg=16.48s min=166.72µs med=15.91s max=32.33s p(90)=22.7s  p(95)=24.54s
     iterations.............: 3251   5.369735/s
     vus....................: 72     min=0      max=90

running (10m05.4s), 00/90 VUs, 3251 complete and 72 interrupted iterations
write ✓ [======================================] 90 VUs  10m0s

INFO[18:19:57] Load started at:               Fri Oct 04 2024 18:19:57 GMT+0000 (UTC)  source=console
INFO[18:30:02] Load finished at:              Fri Oct 04 2024 18:30:02 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 454 GB 749 MB/s
     aws_obj_put_duration...: avg=15.46s min=5.58s    med=15.17s max=31.23s p(90)=20.77s p(95)=22.53s
     aws_obj_put_success....: 3382   5.582634/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 454 GB 749 MB/s
     iteration_duration.....: avg=15.88s min=177.05µs med=15.6s  max=31.67s p(90)=21.19s p(95)=22.99s
     iterations.............: 3379   5.577682/s
     vus....................: 60     min=0      max=90

running (10m05.8s), 00/90 VUs, 3379 complete and 60 interrupted iterations
write ✓ [======================================] 90 VUs  10m0s

### 6 nodes 128mb read
INFO[18:37:10] Load started at:               Fri Oct 04 2024 18:37:10 GMT+0000 (UTC)  source=console
INFO[18:47:15] Load finished at:              Fri Oct 04 2024 18:47:15 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 893 GB 1.5 GB/s
     aws_obj_get_duration...: avg=8.14s min=1.55s    med=7.9s max=16.47s p(90)=10.39s p(95)=11.34s
     aws_obj_get_success....: 6655   11.000834/s
     data_received..........: 893 GB 1.5 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=8.14s min=369.66µs med=7.9s max=16.47s p(90)=10.39s p(95)=11.34s
     iterations.............: 6655   11.000834/s
     vus....................: 9      min=9       max=90

running (10m05.0s), 00/90 VUs, 6655 complete and 0 interrupted iterations
read ✓ [======================================] 90 VUs  10m0s

INFO[18:37:09] Load started at:               Fri Oct 04 2024 18:37:09 GMT+0000 (UTC)  source=console
INFO[18:47:15] Load finished at:              Fri Oct 04 2024 18:47:15 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 907 GB 1.5 GB/s
     aws_obj_get_duration...: avg=8.02s min=2.81s    med=7.79s max=16.62s p(90)=10.42s p(95)=11.4s
     aws_obj_get_success....: 6761   11.158189/s
     data_received..........: 908 GB 1.5 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=8.02s min=467.22µs med=7.79s max=16.62s p(90)=10.42s p(95)=11.4s
     iterations.............: 6761   11.158189/s
     vus....................: 7      min=7       max=90

running (10m05.9s), 00/90 VUs, 6761 complete and 5 interrupted iterations
read ✓ [======================================] 90 VUs  10m0s

### 4 nodes 8kb write
INFO[19:46:34] Load started at:               Sun Oct 06 2024 19:46:34 GMT+0000 (UTC)  source=console
INFO[19:56:35] Load finished at:              Sun Oct 06 2024 19:56:35 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 3.2 GB 5.3 MB/s
     aws_obj_put_duration...: avg=470.38ms min=34.11ms  med=326.84ms max=6.09s p(90)=863.97ms p(95)=1.32s
     aws_obj_put_success....: 388298 646.611116/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 3.2 GB 5.3 MB/s
     iteration_duration.....: avg=479.15ms min=245.39µs med=335.74ms max=6.1s  p(90)=872.76ms p(95)=1.33s
     iterations.............: 388298 646.611116/s
     vus....................: 310    min=310      max=310

running (10m00.5s), 000/310 VUs, 388298 complete and 0 interrupted iterations
write ✓ [======================================] 310 VUs  10m0s

INFO[19:46:34] Load started at:               Sun Oct 06 2024 19:46:34 GMT+0000 (UTC)  source=console
INFO[19:56:34] Load finished at:              Sun Oct 06 2024 19:56:34 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 3.3 GB 5.4 MB/s
     aws_obj_put_duration...: avg=457.44ms min=33.31ms  med=317.5ms max=6.06s p(90)=834.45ms p(95)=1.28s
     aws_obj_put_success....: 399131 664.712459/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 3.3 GB 5.4 MB/s
     iteration_duration.....: avg=466.08ms min=262.88µs med=326.3ms max=6.06s p(90)=843ms    p(95)=1.29s
     iterations.............: 399131 664.712459/s
     vus....................: 310    min=310      max=310

running (10m00.5s), 000/310 VUs, 399131 complete and 0 interrupted iterations
write ✓ [======================================] 310 VUs  10m0s

### 4 nodes 8kb read
INFO[19:57:56] Load started at:               Sun Oct 06 2024 19:57:56 GMT+0000 (UTC)  source=console
INFO[20:07:57] Load finished at:              Sun Oct 06 2024 20:07:57 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 9.7 GB  16 MB/s
     aws_obj_get_duration...: avg=157.28ms min=5.57ms   med=75.29ms max=5.7s p(90)=336.42ms p(95)=517.61ms
     aws_obj_get_success....: 1182280 1967.261206/s
     data_received..........: 9.7 GB  16 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=157.37ms min=216.73µs med=75.38ms max=5.7s p(90)=336.51ms p(95)=517.71ms
     iterations.............: 1182280 1967.261206/s
     vus....................: 2       min=2         max=310

running (10m01.0s), 000/310 VUs, 1182280 complete and 0 interrupted iterations
read ✓ [======================================] 310 VUs  10m0s

INFO[19:57:55] Load started at:               Sun Oct 06 2024 19:57:55 GMT+0000 (UTC)  source=console
INFO[20:07:56] Load finished at:              Sun Oct 06 2024 20:07:56 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 10 GB   17 MB/s
     aws_obj_get_duration...: avg=146.74ms min=5.54ms  med=70.09ms max=5.54s p(90)=314.54ms p(95)=489.16ms
     aws_obj_get_success....: 1267146 2109.048984/s
     data_received..........: 10 GB   17 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=146.83ms min=229.4µs med=70.17ms max=5.54s p(90)=314.61ms p(95)=489.23ms
     iterations.............: 1267146 2109.048984/s
     vus....................: 310     min=310       max=310

running (10m00.8s), 000/310 VUs, 1267146 complete and 0 interrupted iterations
read ✓ [======================================] 310 VUs  10m0s

### 4 nodes 128kb write
INFO[18:57:34] Load started at:               Sun Oct 06 2024 18:57:34 GMT+0000 (UTC)  source=console
INFO[19:07:34] Load finished at:              Sun Oct 06 2024 19:07:34 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 94 GB  157 MB/s
     aws_obj_put_duration...: avg=240.69ms min=29.34ms  med=167.47ms max=4.35s p(90)=483.78ms p(95)=635.96ms
     aws_obj_put_success....: 718743 1197.27101/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 94 GB  157 MB/s
     iteration_duration.....: avg=250.44ms min=211.61µs med=177.18ms max=4.36s p(90)=493.56ms p(95)=646.01ms
     iterations.............: 718743 1197.27101/s
     vus....................: 300    min=300      max=300

running (10m00.3s), 000/300 VUs, 718743 complete and 0 interrupted iterations
write ✓ [======================================] 300 VUs  10m0s

INFO[18:57:33] Load started at:               Sun Oct 06 2024 18:57:33 GMT+0000 (UTC)  source=console
INFO[19:07:34] Load finished at:              Sun Oct 06 2024 19:07:34 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 96 GB  160 MB/s
     aws_obj_put_duration...: avg=236.1ms  min=26.02ms  med=163.28ms max=4.89s p(90)=476.01ms p(95)=624ms   
     aws_obj_put_success....: 732503 1218.72713/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 96 GB  160 MB/s
     iteration_duration.....: avg=245.81ms min=351.12µs med=173.07ms max=4.89s p(90)=485.85ms p(95)=634.42ms
     iterations.............: 732503 1218.72713/s
     vus....................: 9      min=9        max=300

running (10m01.0s), 000/300 VUs, 732503 complete and 0 interrupted iterations
write ✓ [======================================] 300 VUs  10m0s

### 4 nodes 128kb read
INFO[19:18:33] Load started at:               Sun Oct 06 2024 19:18:33 GMT+0000 (UTC)  source=console
INFO[19:28:33] Load finished at:              Sun Oct 06 2024 19:28:33 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 160 GB  267 MB/s
     aws_obj_get_duration...: avg=147.16ms min=7.63ms   med=100.94ms max=5.14s p(90)=273.07ms p(95)=392.53ms
     aws_obj_get_success....: 1222298 2035.61426/s
     data_received..........: 160 GB  267 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=147.25ms min=207.18µs med=101.04ms max=5.14s p(90)=273.16ms p(95)=392.62ms
     iterations.............: 1222298 2035.61426/s
     vus....................: 300     min=300      max=300

running (10m00.5s), 000/300 VUs, 1222298 complete and 0 interrupted iterations
read ✓ [======================================] 300 VUs  10m0s

INFO[19:18:32] Load started at:               Sun Oct 06 2024 19:18:32 GMT+0000 (UTC)  source=console
INFO[19:28:32] Load finished at:              Sun Oct 06 2024 19:28:32 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 164 GB  273 MB/s
     aws_obj_get_duration...: avg=144ms    min=7.1ms    med=99.27ms max=4.94s p(90)=267.92ms p(95)=382.24ms
     aws_obj_get_success....: 1249410 2081.039661/s
     data_received..........: 164 GB  273 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=144.09ms min=165.07µs med=99.35ms max=4.94s p(90)=268.01ms p(95)=382.33ms
     iterations.............: 1249410 2081.039661/s
     vus....................: 300     min=300       max=300

running (10m00.4s), 000/300 VUs, 1249410 complete and 0 interrupted iterations
read ✓ [======================================] 300 VUs  10m0s

### 4 nodes 1mb write
INFO[21:06:30] Load started at:               Sun Oct 06 2024 21:06:30 GMT+0000 (UTC)  source=console
INFO[21:16:32] Load finished at:              Sun Oct 06 2024 21:16:32 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 195 GB 323 MB/s
     aws_obj_put_duration...: avg=629.38ms min=64.32ms  med=521.35ms max=5.36s p(90)=1.08s p(95)=1.39s
     aws_obj_put_success....: 185567 307.947157/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 194 GB 323 MB/s
     iteration_duration.....: avg=647.23ms min=308.99µs med=539.01ms max=5.38s p(90)=1.1s  p(95)=1.4s 
     iterations.............: 185567 307.947157/s
     vus....................: 19     min=19       max=200

running (10m02.6s), 000/200 VUs, 185567 complete and 0 interrupted iterations
write ✓ [======================================] 200 VUs  10m0s

INFO[21:06:31] Load started at:               Sun Oct 06 2024 21:06:31 GMT+0000 (UTC)  source=console
INFO[21:16:33] Load finished at:              Sun Oct 06 2024 21:16:33 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 192 GB 320 MB/s
     aws_obj_put_duration...: avg=636.9ms min=61.22ms  med=529.61ms max=5.47s p(90)=1.09s p(95)=1.39s
     aws_obj_put_success....: 183501 304.718803/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 192 GB 319 MB/s
     iteration_duration.....: avg=654.9ms min=257.41µs med=547.54ms max=5.49s p(90)=1.11s p(95)=1.41s
     iterations.............: 183501 304.718803/s
     vus....................: 16     min=16       max=200

running (10m02.2s), 000/200 VUs, 183501 complete and 0 interrupted iterations
write ✓ [======================================] 200 VUs  10m0s

### 4 nodes 1mb read
INFO[21:25:12] Load started at:               Sun Oct 06 2024 21:25:12 GMT+0000 (UTC)  source=console
INFO[21:35:13] Load finished at:              Sun Oct 06 2024 21:35:13 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 409 GB 680 MB/s
     aws_obj_get_duration...: avg=307.89ms min=23.38ms  med=266.79ms max=5.19s p(90)=516.45ms p(95)=611.07ms
     aws_obj_get_success....: 389648 648.635301/s
     data_received..........: 409 GB 680 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=307.99ms min=176.22µs med=266.89ms max=5.19s p(90)=516.54ms p(95)=611.19ms
     iterations.............: 389648 648.635301/s
     vus....................: 200    min=200      max=200

running (10m00.7s), 000/200 VUs, 389648 complete and 0 interrupted iterations
read ✓ [======================================] 200 VUs  10m0s

INFO[21:25:12] Load started at:               Sun Oct 06 2024 21:25:12 GMT+0000 (UTC)  source=console
INFO[21:35:13] Load finished at:              Sun Oct 06 2024 21:35:13 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 419 GB 697 MB/s
     aws_obj_get_duration...: avg=300.49ms min=25.54ms  med=259.99ms max=4.93s p(90)=505.66ms p(95)=599.94ms
     aws_obj_get_success....: 399317 664.302562/s
     data_received..........: 419 GB 697 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=300.59ms min=222.76µs med=260.09ms max=4.93s p(90)=505.76ms p(95)=600.06ms
     iterations.............: 399317 664.302562/s
     vus....................: 1      min=1        max=200

running (10m01.1s), 000/200 VUs, 399317 complete and 0 interrupted iterations
read ✓ [======================================] 200 VUs  10m0s

### 4 nodes 128mb write
INFO[20:31:28] Load started at:               Sun Oct 06 2024 20:31:28 GMT+0000 (UTC)  source=console
INFO[20:41:33] Load finished at:              Sun Oct 06 2024 20:41:33 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 335 GB 553 MB/s
     aws_obj_put_duration...: avg=13.98s min=8.14s    med=13.11s max=27.89s p(90)=18.83s p(95)=19.74s
     aws_obj_put_success....: 2493   4.116681/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 335 GB 553 MB/s
     iteration_duration.....: avg=14.4s  min=147.74µs med=13.54s max=28.34s p(90)=19.25s p(95)=20.17s
     iterations.............: 2492   4.115029/s
     vus....................: 1      min=1      max=60

running (10m05.6s), 00/60 VUs, 2492 complete and 32 interrupted iterations
write ✓ [======================================] 60 VUs  10m0s

INFO[20:31:27] Load started at:               Sun Oct 06 2024 20:31:27 GMT+0000 (UTC)  source=console
INFO[20:41:32] Load finished at:              Sun Oct 06 2024 20:41:32 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 326 GB 539 MB/s
     aws_obj_put_duration...: avg=14.35s min=8.84s    med=13.61s max=28.17s p(90)=19.06s p(95)=20.07s
     aws_obj_put_success....: 2430   4.012232/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 326 GB 539 MB/s
     iteration_duration.....: avg=14.77s min=186.55µs med=14.04s max=28.59s p(90)=19.49s p(95)=20.51s
     iterations.............: 2424   4.002325/s
     vus....................: 1      min=1      max=60

running (10m05.6s), 00/60 VUs, 2424 complete and 40 interrupted iterations
write ✓ [======================================] 60 VUs  10m0s

### 4 nodes 128mb read
INFO[20:42:47] Load started at:               Sun Oct 06 2024 20:42:47 GMT+0000 (UTC)  source=console
INFO[20:52:53] Load finished at:              Sun Oct 06 2024 20:52:53 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 594 GB 981 MB/s
     aws_obj_get_duration...: avg=8.16s min=3.71s    med=7.49s max=16.08s p(90)=11.36s p(95)=12.21s
     aws_obj_get_success....: 4425   7.305471/s
     data_received..........: 595 GB 982 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=8.15s min=266.94µs med=7.49s max=16.08s p(90)=11.36s p(95)=12.21s
     iterations.............: 4425   7.305471/s
     vus....................: 7      min=7      max=60

running (10m05.7s), 00/60 VUs, 4425 complete and 7 interrupted iterations
read ✓ [======================================] 60 VUs  10m0s

INFO[20:42:48] Load started at:               Sun Oct 06 2024 20:42:48 GMT+0000 (UTC)  source=console
INFO[20:52:53] Load finished at:              Sun Oct 06 2024 20:52:53 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 542 GB 896 MB/s
     aws_obj_get_duration...: avg=8.95s min=3.21s    med=9.15s max=15.42s p(90)=11.89s p(95)=12.69s
     aws_obj_get_success....: 4037   6.672877/s
     data_received..........: 542 GB 896 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=8.95s min=290.02µs med=9.14s max=15.42s p(90)=11.89s p(95)=12.69s
     iterations.............: 4037   6.672877/s
     vus....................: 2      min=2      max=60

running (10m05.0s), 00/60 VUs, 4037 complete and 0 interrupted iterations
read ✓ [======================================] 60 VUs  10m0s

