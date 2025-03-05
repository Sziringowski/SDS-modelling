protection=3REP
HW_chassis=VEGMAN
SSD=4
HDD=12

### 8 nodes 8kb write
INFO[10:14:02] Load started at:               Tue Feb 04 2025 10:14:02 GMT+0000 (UTC)  source=console
INFO[10:24:03] Load finished at:              Tue Feb 04 2025 10:24:03 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 38 GB   63 MB/s
     aws_obj_put_duration...: avg=162.04ms min=42.61ms  med=148.49ms max=1.64s p(90)=233.28ms p(95)=268.96ms
     aws_obj_put_success....: 4579834 7628.120051/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 37 GB   62 MB/s
     iteration_duration.....: avg=162.44ms min=152.95µs med=148.9ms  max=1.64s p(90)=233.68ms p(95)=269.36ms
     iterations.............: 4579834 7628.120051/s
     vus....................: 1240    min=1240      max=1240

running (10m00.4s), 0000/1240 VUs, 4579834 complete and 0 interrupted iterations
write ✓ [======================================] 1240 VUs  10m0s

### 8 nodes 8kb read
INFO[12:31:10] Load started at:               Fri Jan 24 2025 12:31:10 GMT+0000 (UTC)  source=console
INFO[12:41:10] Load finished at:              Fri Jan 24 2025 12:41:10 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 79 GB   132 MB/s
     aws_obj_get_duration...: avg=76.85ms min=5.57ms   med=73.22ms max=509.17ms p(90)=122.28ms p(95)=138.74ms
     aws_obj_get_success....: 9667230 16109.24745/s
     data_received..........: 79 GB   132 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=76.94ms min=288.83µs med=73.3ms  max=509.24ms p(90)=122.36ms p(95)=138.83ms
     iterations.............: 9667230 16109.24745/s
     vus....................: 1240    min=1240      max=1240

running (10m00.1s), 0000/1240 VUs, 9667230 complete and 0 interrupted iterations
read ✓ [======================================] 1240 VUs  10m0s

### 8 nodes 128kb write
INFO[10:11:08] Load started at:               Wed Feb 05 2025 10:11:08 GMT+0000 (UTC)  source=console
INFO[10:21:10] Load finished at:              Wed Feb 05 2025 10:21:10 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 87 GB   144 MB/s
     aws_obj_put_duration...: avg=496.5ms  min=19.06ms med=79.58ms max=7m6s p(90)=237.54ms p(95)=301.33ms
     aws_obj_put_fails......: 421692  696.987923/s
     aws_obj_put_success....: 663150  1096.078514/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 87 GB   144 MB/s
     iteration_duration.....: avg=594.69ms min=134.8µs med=96.73ms max=7m6s p(90)=433.52ms p(95)=804.05ms
     iterations.............: 1084842 1793.066437/s
     vus....................: 1200    min=1200      max=1200

running (10m05.0s), 0000/1200 VUs, 1084842 complete and 1200 interrupted iterations
write ✓ [======================================] 1200 VUs  10m0s

### 8 nodes 128kb read
INFO[12:03:35] Load started at:               Fri Jan 31 2025 12:03:35 GMT+0000 (UTC)  source=console
INFO[12:13:36] Load finished at:              Fri Jan 31 2025 12:13:36 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 936 GB  1.6 GB/s
     aws_obj_get_duration...: avg=100.54ms min=5.31ms   med=91.89ms max=652.71ms p(90)=164.94ms p(95)=192.54ms
     aws_obj_get_fails......: 17574   29.277702/s
     aws_obj_get_success....: 7142912 11899.854856/s
     data_received..........: 935 GB  1.6 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=100.53ms min=469.86µs med=91.88ms max=652.77ms p(90)=164.94ms p(95)=192.55ms
     iterations.............: 7160486 11929.132558/s
     vus....................: 1200    min=1200       max=1200

running (10m00.3s), 0000/1200 VUs, 7160486 complete and 0 interrupted iterations
read ✓ [======================================] 1200 VUs  10m0s

### 8 nodes 1mib write
INFO[11:14:19] Load started at:               Tue Feb 04 2025 11:14:19 GMT+0000 (UTC)  source=console
INFO[11:24:20] Load finished at:              Tue Feb 04 2025 11:24:20 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 204 GB 337 MB/s
     aws_obj_put_duration...: avg=1.42s    min=48.8ms  med=198.98ms max=5m7s p(90)=388.44ms p(95)=472.34ms
     aws_obj_put_fails......: 291633 482.0226/s
     aws_obj_put_success....: 194543 321.548394/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 204 GB 337 MB/s
     iteration_duration.....: avg=803.33ms min=86.45µs med=92.55ms  max=5m7s p(90)=307.51ms p(95)=388.59ms
     iterations.............: 486176 803.570994/s
     vus....................: 403    min=403      max=800

running (10m00.6s), 000/800 VUs, 486176 complete and 0 interrupted iterations
write ✓ [======================================] 800 VUs  10m0s

### 8 nodes 1mib read
INFO[13:28:56] Load started at:               Fri Jan 31 2025 13:28:56 GMT+0000 (UTC)  source=console
INFO[13:38:59] Load finished at:              Fri Jan 31 2025 13:38:59 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 3.0 TB  5.0 GB/s
     aws_obj_get_duration...: avg=167.26ms min=16.96ms med=147.81ms max=3.61s p(90)=265.42ms p(95)=359.72ms
     aws_obj_get_fails......: 4157    6.92167/s
     aws_obj_get_success....: 2866860 4773.504569/s
     data_received..........: 3.0 TB  5.0 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=167.19ms min=3.66ms  med=147.79ms max=3.61s p(90)=265.37ms p(95)=359.67ms
     iterations.............: 2871017 4780.426239/s
     vus....................: 800     min=800       max=800

running (10m00.6s), 000/800 VUs, 2871017 complete and 0 interrupted iterations
read ✓ [======================================] 800 VUs  10m0s

### 8 nodes 128mib write
INFO[13:56:03] Load started at:               Fri Jan 31 2025 13:56:03 GMT+0000 (UTC)  source=console
INFO[14:06:09] Load finished at:              Fri Jan 31 2025 14:06:09 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.4 TB 2.3 GB/s
     aws_obj_put_duration...: avg=13.19s min=3.41s    med=11.19s max=40.48s p(90)=23.92s p(95)=28.76s
     aws_obj_put_success....: 10477  17.293699/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.4 TB 2.3 GB/s
     iteration_duration.....: avg=13.71s min=194.84µs med=11.71s max=41.11s p(90)=24.49s p(95)=29.32s
     iterations.............: 10457  17.260686/s
     vus....................: 16     min=0       max=240

running (10m05.8s), 000/240 VUs, 10457 complete and 146 interrupted iterations
write ✓ [======================================] 240 VUs  10m0s

### 8 nodes 128mib read
INFO[14:16:44] Load started at:               Fri Jan 31 2025 14:16:44 GMT+0000 (UTC)  source=console
INFO[14:26:48] Load finished at:              Fri Jan 31 2025 14:26:48 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 3.3 TB 5.5 GB/s
     aws_obj_get_duration...: avg=5.81s min=1.25s  med=5.59s max=17.05s p(90)=8.31s p(95)=9.18s
     aws_obj_get_success....: 24837  41.105016/s
     data_received..........: 3.3 TB 5.5 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=5.81s min=1.28ms med=5.59s max=17.05s p(90)=8.31s p(95)=9.18s
     iterations.............: 24837  41.105016/s
     vus....................: 1      min=1       max=240

running (10m04.2s), 000/240 VUs, 24837 complete and 0 interrupted iterations
read ✓ [======================================] 240 VUs  10m0s

### 6 nodes 8kb write
INFO[12:06:42] Load started at:               Tue Feb 04 2025 12:06:42 GMT+0000 (UTC)  source=console
INFO[12:16:44] Load finished at:              Tue Feb 04 2025 12:16:44 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 25 GB   41 MB/s
     aws_obj_put_duration...: avg=182.3ms min=39.09ms  med=151ms    max=1.79s p(90)=288.46ms p(95)=394.96ms
     aws_obj_put_fails......: 33726   56.188408/s
     aws_obj_put_success....: 3008639 5012.472185/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 25 GB   41 MB/s
     iteration_duration.....: avg=183.4ms min=150.63µs med=150.71ms max=8.56s p(90)=287.93ms p(95)=394.51ms
     iterations.............: 3042365 5068.660593/s
     vus....................: 930     min=930       max=930

running (10m00.2s), 000/930 VUs, 3042365 complete and 0 interrupted iterations
write ✓ [======================================] 930 VUs  10m0s

### 6 nodes 8kb read
INFO[10:14:52] Load started at:               Mon Feb 03 2025 10:14:52 GMT+0000 (UTC)  source=console
INFO[10:24:52] Load finished at:              Mon Feb 03 2025 10:24:52 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 65 GB   108 MB/s
     aws_obj_get_duration...: avg=70.56ms min=5.39ms med=64.24ms max=477.74ms p(90)=118.49ms p(95)=138.1ms 
     aws_obj_get_success....: 7896608 13158.898064/s
     data_received..........: 65 GB   108 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=70.64ms min=2.59ms med=64.32ms max=477.82ms p(90)=118.57ms p(95)=138.18ms
     iterations.............: 7896608 13158.898064/s
     vus....................: 930     min=930        max=930

running (10m00.1s), 000/930 VUs, 7896608 complete and 0 interrupted iterations
read ✓ [======================================] 930 VUs  10m0s

### 6 nodes 128kb write
INFO[12:30:38] Load started at:               Tue Feb 04 2025 12:30:38 GMT+0000 (UTC)  source=console
INFO[12:40:41] Load finished at:              Tue Feb 04 2025 12:40:41 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 270 GB  449 MB/s
     aws_obj_put_duration...: avg=261.78ms min=23.19ms  med=184.81ms max=3.96s p(90)=428.1ms p(95)=684.79ms
     aws_obj_put_fails......: 57      0.09461/s
     aws_obj_put_success....: 2062677 3423.69669/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 270 GB  448 MB/s
     iteration_duration.....: avg=262.17ms min=158.26µs med=185.2ms  max=3.96s p(90)=428.5ms p(95)=685.13ms
     iterations.............: 2062734 3423.7913/s
     vus....................: 247     min=247      max=900

running (10m02.5s), 000/900 VUs, 2062734 complete and 0 interrupted iterations
write ✓ [======================================] 900 VUs  10m0s

### 6 nodes 128kb read
INFO[12:06:03] Load started at:               Mon Feb 03 2025 12:06:03 GMT+0000 (UTC)  source=console
INFO[12:16:03] Load finished at:              Mon Feb 03 2025 12:16:03 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 836 GB  1.4 GB/s
     aws_obj_get_duration...: avg=84.6ms  min=6.62ms   med=78.5ms  max=479.12ms p(90)=141.69ms p(95)=162.05ms
     aws_obj_get_success....: 6374487 10622.051182/s
     data_received..........: 834 GB  1.4 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=84.69ms min=241.41µs med=78.59ms max=479.2ms  p(90)=141.77ms p(95)=162.13ms
     iterations.............: 6374487 10622.051182/s
     vus....................: 900     min=900        max=900

running (10m00.1s), 000/900 VUs, 6374487 complete and 0 interrupted iterations
read ✓ [======================================] 900 VUs  10m0s

### 6 nodes 1mib write
INFO[13:04:13] Load started at:               Tue Feb 04 2025 13:04:13 GMT+0000 (UTC)  source=console
INFO[13:14:15] Load finished at:              Tue Feb 04 2025 13:14:15 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 593 GB  988 MB/s
     aws_obj_put_duration...: avg=465.6ms  min=47.29ms med=432.27ms max=5.87s  p(90)=746.03ms p(95)=858.51ms
     aws_obj_put_fails......: 623838  1038.80016/s
     aws_obj_put_success....: 565659  941.921877/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 593 GB  987 MB/s
     iteration_duration.....: avg=302.67ms min=172.2µs med=228.92ms max=11.02s p(90)=633.4ms  p(95)=763.22ms
     iterations.............: 1189497 1980.722037/s
     vus....................: 600     min=600       max=600

running (10m00.5s), 000/600 VUs, 1189497 complete and 0 interrupted iterations
write ✓ [======================================] 600 VUs  10m0s

### 6 nodes 1mib read
INFO[13:54:03] Load started at:               Mon Feb 03 2025 13:54:03 GMT+0000 (UTC)  source=console
INFO[14:04:03] Load finished at:              Mon Feb 03 2025 14:04:03 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 2.5 TB  4.2 GB/s
     aws_obj_get_duration...: avg=149.99ms min=15.63ms  med=136.15ms max=2.2s p(90)=237.11ms p(95)=295.38ms
     aws_obj_get_success....: 2398653 3994.211651/s
     data_received..........: 2.5 TB  4.2 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=150.08ms min=416.46µs med=136.24ms max=2.2s p(90)=237.2ms  p(95)=295.47ms
     iterations.............: 2398653 3994.211651/s
     vus....................: 600     min=600       max=600

running (10m00.5s), 000/600 VUs, 2398653 complete and 0 interrupted iterations
read ✓ [======================================] 600 VUs  10m0s

### 6 nodes 128mib write
INFO[14:47:45] Load started at:               Mon Feb 03 2025 14:47:45 GMT+0000 (UTC)  source=console
INFO[14:57:47] Load finished at:              Mon Feb 03 2025 14:57:47 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.1 TB 1.8 GB/s
     aws_obj_put_duration...: avg=11.57s min=3.69s    med=10.79s max=28.85s p(90)=16.85s p(95)=18.92s
     aws_obj_put_fails......: 1298   2.142391/s
     aws_obj_put_success....: 8192   13.521161/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.1 TB 1.8 GB/s
     iteration_duration.....: avg=11.38s min=217.97µs med=10.8s  max=28.9s  p(90)=16.83s p(95)=18.99s
     iterations.............: 9476   15.640444/s
     vus....................: 0      min=0       max=180

running (10m05.9s), 000/180 VUs, 9476 complete and 84 interrupted iterations
write ✓ [======================================] 180 VUs  10m0s

### 6 nodes 128mib read
INFO[15:00:56] Load started at:               Mon Feb 03 2025 15:00:56 GMT+0000 (UTC)  source=console
INFO[15:10:59] Load finished at:              Mon Feb 03 2025 15:10:59 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 3.3 TB 5.5 GB/s
     aws_obj_get_duration...: avg=4.39s min=1.19s    med=4.17s max=11.93s p(90)=6.35s p(95)=7.12s
     aws_obj_get_success....: 24663  40.914418/s
     data_received..........: 3.3 TB 5.5 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=4.39s min=451.19µs med=4.17s max=11.93s p(90)=6.35s p(95)=7.12s
     iterations.............: 24663  40.914418/s
     vus....................: 87     min=87      max=180

running (10m02.8s), 000/180 VUs, 24663 complete and 0 interrupted iterations
read ✓ [======================================] 180 VUs  10m0s

### 4 nodes 8kb write
INFO[13:26:24] Load started at:               Tue Feb 04 2025 13:26:24 GMT+0000 (UTC)  source=console
INFO[13:36:27] Load finished at:              Tue Feb 04 2025 13:36:27 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 14 GB   24 MB/s
     aws_obj_put_duration...: avg=180.91ms min=39.67ms  med=154.83ms max=28.69s p(90)=247.46ms p(95)=290.81ms
     aws_obj_put_fails......: 1711286 2851.135168/s
     aws_obj_put_success....: 1732901 2887.147434/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 14 GB   24 MB/s
     iteration_duration.....: avg=107.99ms min=148.53µs med=90.74ms  max=28.69s p(90)=208.97ms p(95)=248.97ms
     iterations.............: 3444187 5738.282602/s
     vus....................: 620     min=620       max=620

running (10m00.2s), 000/620 VUs, 3444187 complete and 0 interrupted iterations
write ✓ [======================================] 620 VUs  10m0s

### 4 nodes 8kb read
INFO[07:57:22] Load started at:               Tue Feb 04 2025 07:57:22 GMT+0000 (UTC)  source=console
INFO[08:07:22] Load finished at:              Tue Feb 04 2025 08:07:22 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 54 GB   89 MB/s
     aws_obj_get_duration...: avg=56.88ms min=4.84ms med=51.12ms max=397.7ms  p(90)=94.6ms  p(95)=110.91ms
     aws_obj_get_success....: 6527961 10878.146385/s
     data_received..........: 53 GB   89 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=56.96ms min=4.9ms  med=51.21ms max=401.68ms p(90)=94.68ms p(95)=110.99ms
     iterations.............: 6527961 10878.146385/s
     vus....................: 620     min=620        max=620

running (10m00.1s), 000/620 VUs, 6527961 complete and 0 interrupted iterations
read ✓ [======================================] 620 VUs  10m0s

### 4 nodes 128kb write
INFO[08:54:00] Load started at:               Tue Feb 04 2025 08:54:00 GMT+0000 (UTC)  source=console
INFO[08:59:02] Load finished at:              Tue Feb 04 2025 08:59:02 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 88 GB  290 MB/s
     aws_obj_put_duration...: avg=242.55ms min=29.45ms  med=211.58ms max=2.29s p(90)=410.8ms p(95)=506.52ms
     aws_obj_put_success....: 667471 2214.257436/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 87 GB  290 MB/s
     iteration_duration.....: avg=242.95ms min=163.55µs med=211.98ms max=2.29s p(90)=411.2ms p(95)=506.9ms 
     iterations.............: 667471 2214.257436/s
     vus....................: 132    min=132       max=540

running (5m01.4s), 000/540 VUs, 667471 complete and 0 interrupted iterations
write ✓ [======================================] 540 VUs  5m0s

### 4 nodes 128kb read
INFO[08:36:38] Load started at:               Tue Feb 04 2025 08:36:38 GMT+0000 (UTC)  source=console
INFO[08:46:38] Load finished at:              Tue Feb 04 2025 08:46:38 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 642 GB  1.1 GB/s
     aws_obj_get_duration...: avg=66ms    min=6.43ms   med=59.15ms max=414.71ms p(90)=112.07ms p(95)=132.88ms
     aws_obj_get_success....: 4900466 8166.435333/s
     data_received..........: 642 GB  1.1 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=66.09ms min=451.89µs med=59.24ms max=414.79ms p(90)=112.16ms p(95)=132.98ms
     iterations.............: 4900466 8166.435333/s
     vus....................: 540     min=540       max=540

running (10m00.1s), 000/540 VUs, 4900466 complete and 0 interrupted iterations
read ✓ [======================================] 540 VUs  10m0s

### 4 nodes 1mib write
INFO[14:20:13] Load started at:               Tue Feb 04 2025 14:20:13 GMT+0000 (UTC)  source=console
INFO[14:30:14] Load finished at:              Tue Feb 04 2025 14:30:14 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 518 GB 863 MB/s
     aws_obj_put_duration...: avg=485.18ms min=63.6ms   med=459.42ms max=1.83s p(90)=749.39ms p(95)=851.29ms
     aws_obj_put_fails......: 1      0.001665/s
     aws_obj_put_success....: 494373 823.096966/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 518 GB 862 MB/s
     iteration_duration.....: avg=485.57ms min=158.84µs med=459.83ms max=1.83s p(90)=749.79ms p(95)=851.71ms
     iterations.............: 494374 823.098631/s
     vus....................: 400    min=400      max=400

running (10m00.6s), 000/400 VUs, 494374 complete and 0 interrupted iterations
write ✓ [======================================] 400 VUs  10m0s

### 4 nodes 1mib read
INFO[07:49:29] Load started at:               Wed Feb 05 2025 07:49:29 GMT+0000 (UTC)  source=console
INFO[07:59:31] Load finished at:              Wed Feb 05 2025 07:59:31 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.9 TB  3.1 GB/s
     aws_obj_get_duration...: avg=134.29ms min=15.47ms  med=112.51ms max=1.61s p(90)=233.68ms p(95)=329.18ms
     aws_obj_get_fails......: 303     0.504777/s
     aws_obj_get_success....: 1785770 2974.971346/s
     data_received..........: 1.9 TB  3.1 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=134.36ms min=493.55µs med=112.6ms  max=1.61s p(90)=233.77ms p(95)=329.25ms
     iterations.............: 1786073 2975.476123/s
     vus....................: 400     min=400       max=400

running (10m00.3s), 000/400 VUs, 1786073 complete and 0 interrupted iterations
read ✓ [======================================] 400 VUs  10m0s

### 4 nodes 128mib write
INFO[08:46:52] Load started at:               Wed Feb 05 2025 08:46:52 GMT+0000 (UTC)  source=console
INFO[08:56:57] Load finished at:              Wed Feb 05 2025 08:56:57 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 686 GB 1.1 GB/s
     aws_obj_put_duration...: avg=13.97s min=3.77s   med=12.17s max=35.12s p(90)=24.74s p(95)=27.5s
     aws_obj_put_fails......: 5      0.008259/s
     aws_obj_put_success....: 5111   8.44195/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 686 GB 1.1 GB/s
     iteration_duration.....: avg=13.96s min=92.21µs med=12.16s max=35.12s p(90)=24.74s p(95)=27.5s
     iterations.............: 5116   8.450209/s
     vus....................: 76     min=0      max=120

running (10m05.4s), 000/120 VUs, 5116 complete and 75 interrupted iterations
write ✓ [======================================] 120 VUs  10m0s

### 4 nodes 128mib read
INFO[08:33:38] Load started at:               Wed Feb 05 2025 08:33:38 GMT+0000 (UTC)  source=console
INFO[08:43:42] Load finished at:              Wed Feb 05 2025 08:43:42 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 3.1 TB 5.1 GB/s
     aws_obj_get_duration...: avg=3.15s min=866.68ms med=2.76s max=20.74s p(90)=4.86s p(95)=5.77s
     aws_obj_get_success....: 22881  37.903719/s
     data_received..........: 3.1 TB 5.1 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=3.15s min=473.17µs med=2.76s max=20.74s p(90)=4.86s p(95)=5.77s
     iterations.............: 22881  37.903719/s
     vus....................: 10     min=10      max=120

running (10m03.7s), 000/120 VUs, 22881 complete and 0 interrupted iterations
read ✓ [======================================] 120 VUs  10m0s