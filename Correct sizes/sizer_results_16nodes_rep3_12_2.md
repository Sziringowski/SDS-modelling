protection=3REP
HW_chassis=X205
SSD=2
HDD=12

### 16 nodes 8kb write
INFO[09:25:46] Load started at:               Tue Oct 29 2024 09:25:46 GMT+0000 (UTC)  source=console
INFO[09:35:49] Load finished at:              Tue Oct 29 2024 09:35:49 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 23 GB   38 MB/s
     aws_obj_put_duration...: avg=256.48ms min=42.75ms  med=150.98ms max=6.9s p(90)=348.55ms p(95)=760.18ms
     aws_obj_put_success....: 2807037 4659.528371/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 23 GB   38 MB/s
     iteration_duration.....: avg=265.1ms  min=195.22µs med=157.87ms max=6.9s p(90)=358.14ms p(95)=768.88ms
     iterations.............: 2807037 4659.528371/s
     vus....................: 35      min=35        max=1240

running (10m02.4s), 0000/1240 VUs, 2807037 complete and 0 interrupted iterations
write ✓ [======================================] 1240 VUs  10m0s

INFO[09:25:46] Load started at:               Tue Oct 29 2024 09:25:46 GMT+0000 (UTC)  source=console
INFO[09:35:47] Load finished at:              Tue Oct 29 2024 09:35:47 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 25 GB   41 MB/s
     aws_obj_put_duration...: avg=237.99ms min=43.89ms med=151.5ms  max=6.07s p(90)=322.08ms p(95)=600.25ms
     aws_obj_put_success....: 3018421 5021.02633/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 25 GB   41 MB/s
     iteration_duration.....: avg=246.57ms min=2.02ms  med=161.64ms max=6.08s p(90)=330.41ms p(95)=608.81ms
     iterations.............: 3018421 5021.02633/s
     vus....................: 201     min=201      max=1240

running (10m01.2s), 0000/1240 VUs, 3018421 complete and 0 interrupted iterations
write ✓ [======================================] 1240 VUs  10m0s

### 16 nodes 8kb read
INFO[08:37:58] Load started at:               Wed Oct 30 2024 08:37:58 GMT+0000 (UTC)  source=console
INFO[08:47:58] Load finished at:              Wed Oct 30 2024 08:47:58 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 48 GB   80 MB/s
     aws_obj_get_duration...: avg=119.4ms  min=5.54ms   med=57.86ms max=7.17s p(90)=270.59ms p(95)=437.09ms
     aws_obj_get_success....: 5824605 9703.677849/s
     data_received..........: 48 GB   79 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=119.47ms min=267.82µs med=57.94ms max=7.17s p(90)=270.67ms p(95)=437.17ms
     iterations.............: 5824605 9703.677849/s
     vus....................: 1160    min=1160      max=1160

running (10m00.2s), 0000/1160 VUs, 5824605 complete and 0 interrupted iterations
read ✓ [======================================] 1160 VUs  10m0s

INFO[08:38:07] Load started at:               Wed Oct 30 2024 08:38:07 GMT+0000 (UTC)  source=console
INFO[08:48:08] Load finished at:              Wed Oct 30 2024 08:48:08 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 51 GB   85 MB/s
     aws_obj_get_duration...: avg=111.69ms min=5.78ms med=57.47ms max=6.54s p(90)=246.85ms p(95)=400.85ms
     aws_obj_get_success....: 6225935 10361.656639/s
     data_received..........: 51 GB   85 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=111.77ms min=2.94ms med=57.55ms max=6.54s p(90)=246.93ms p(95)=400.93ms
     iterations.............: 6225935 10361.656639/s
     vus....................: 8       min=8          max=1160

running (10m00.9s), 0000/1160 VUs, 6225935 complete and 0 interrupted iterations
read ✓ [======================================] 1160 VUs  10m0s

### 16 nodes 128kb write
INFO[09:50:01] Load started at:               Wed Oct 30 2024 09:50:01 GMT+0000 (UTC)  source=console
INFO[10:00:02] Load finished at:              Wed Oct 30 2024 10:00:02 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 214 GB  355 MB/s
     aws_obj_put_duration...: avg=403.06ms min=30.07ms  med=203.77ms max=7.18s p(90)=1.01s p(95)=1.49s
     aws_obj_put_success....: 1629076 2710.390968/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 213 GB  355 MB/s
     iteration_duration.....: avg=412.85ms min=207.97µs med=214.79ms max=7.19s p(90)=1.02s p(95)=1.5s 
     iterations.............: 1629076 2710.390968/s
     vus....................: 193     min=193       max=1120

running (10m01.0s), 0000/1120 VUs, 1629076 complete and 0 interrupted iterations
write ✓ [======================================] 1120 VUs  10m0s

INFO[09:50:01] Load started at:               Wed Oct 30 2024 09:50:01 GMT+0000 (UTC)  source=console
INFO[10:00:02] Load finished at:              Wed Oct 30 2024 10:00:02 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 15 GB   24 MB/s
     aws_obj_put_duration...: avg=367.65ms min=34.53ms  med=190.82ms max=8.16s p(90)=884.62ms p(95)=1.36s
     aws_obj_put_success....: 1787473 2970.939132/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 15 GB   24 MB/s
     iteration_duration.....: avg=376.31ms min=621.84µs med=197.95ms max=8.17s p(90)=892.95ms p(95)=1.37s
     iterations.............: 1787473 2970.939132/s
     vus....................: 500     min=500       max=1120

running (10m01.7s), 0000/1120 VUs, 1787473 complete and 0 interrupted iterations
write ✓ [======================================] 1120 VUs  10m0s


### 16 nodes 128kb read
INFO[10:36:53] Load started at:               Wed Oct 30 2024 10:36:53 GMT+0000 (UTC)  source=console
INFO[10:46:54] Load finished at:              Wed Oct 30 2024 10:46:54 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 741 GB  1.2 GB/s
     aws_obj_get_duration...: avg=118.78ms min=8.4ms    med=99.43ms max=1.97s p(90)=213.82ms p(95)=267.62ms
     aws_obj_get_success....: 5652787 9409.358374/s
     data_received..........: 740 GB  1.2 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=118.87ms min=199.81µs med=99.52ms max=1.97s p(90)=213.91ms p(95)=267.71ms
     iterations.............: 5652787 9409.358374/s
     vus....................: 1120    min=1120      max=1120

running (10m00.8s), 0000/1120 VUs, 5652787 complete and 0 interrupted iterations
read ✓ [======================================] 1120 VUs  10m0s

INFO[10:36:54] Load started at:               Wed Oct 30 2024 10:36:54 GMT+0000 (UTC)  source=console
INFO[10:46:54] Load finished at:              Wed Oct 30 2024 10:46:54 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 738 GB  1.2 GB/s
     aws_obj_get_duration...: avg=119.2ms  min=8.06ms med=99.78ms max=2.72s p(90)=215.2ms  p(95)=269.4ms 
     aws_obj_get_success....: 5633167 9379.378902/s
     data_received..........: 737 GB  1.2 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=119.28ms min=1.01ms med=99.87ms max=2.72s p(90)=215.28ms p(95)=269.48ms
     iterations.............: 5633167 9379.378902/s
     vus....................: 1120    min=1120      max=1120

running (10m00.6s), 0000/1120 VUs, 5633167 complete and 0 interrupted iterations
read ✓ [======================================] 1120 VUs  10m0s

### 16 nodes 1mb write
INFO[11:25:57] Load started at:               Wed Oct 30 2024 11:25:57 GMT+0000 (UTC)  source=console
INFO[11:35:59] Load finished at:              Wed Oct 30 2024 11:35:59 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 642 GB 1.1 GB/s
     aws_obj_put_duration...: avg=729.27ms min=109.04ms med=672.99ms max=3.63s p(90)=1.13s p(95)=1.31s
     aws_obj_put_success....: 612088 1017.775695/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 642 GB 1.1 GB/s
     iteration_duration.....: avg=745.34ms min=306.81µs med=688.98ms max=3.65s p(90)=1.15s p(95)=1.33s
     iterations.............: 612088 1017.775695/s
     vus....................: 82     min=82        max=760

running (10m01.4s), 000/760 VUs, 612088 complete and 0 interrupted iterations
write ✓ [======================================] 760 VUs  10m0s

INFO[11:25:59] Load started at:               Wed Oct 30 2024 11:25:59 GMT+0000 (UTC)  source=console
INFO[11:35:59] Load finished at:              Wed Oct 30 2024 11:35:59 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 645 GB 1.1 GB/s
     aws_obj_put_duration...: avg=725.02ms min=101.32ms med=672.31ms max=3.47s p(90)=1.12s p(95)=1.3s 
     aws_obj_put_success....: 615285 1024.913984/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 645 GB 1.1 GB/s
     iteration_duration.....: avg=741.23ms min=495.22µs med=688.54ms max=3.49s p(90)=1.14s p(95)=1.31s
     iterations.............: 615285 1024.913984/s
     vus....................: 760    min=760       max=760

running (10m00.3s), 000/760 VUs, 615285 complete and 0 interrupted iterations
write ✓ [======================================] 760 VUs  10m0s

### 16 nodes 1mb read
INFO[12:00:25] Load started at:               Wed Oct 30 2024 12:00:25 GMT+0000 (UTC)  source=console
INFO[12:10:25] Load finished at:              Wed Oct 30 2024 12:10:25 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.8 TB  3.1 GB/s
     aws_obj_get_duration...: avg=259.88ms min=21.08ms  med=234.35ms max=1.58s p(90)=424.78ms p(95)=514.68ms
     aws_obj_get_success....: 1754278 2920.539209/s
     data_received..........: 1.8 TB  3.1 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=259.97ms min=204.74µs med=234.44ms max=1.58s p(90)=424.87ms p(95)=514.77ms
     iterations.............: 1754278 2920.539209/s
     vus....................: 760     min=760       max=760

running (10m00.7s), 000/760 VUs, 1754278 complete and 0 interrupted iterations
read ✓ [======================================] 760 VUs  10m0s

INFO[12:00:25] Load started at:               Wed Oct 30 2024 12:00:25 GMT+0000 (UTC)  source=console
INFO[12:10:26] Load finished at:              Wed Oct 30 2024 12:10:26 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.8 TB  3.0 GB/s
     aws_obj_get_duration...: avg=261.08ms min=21.82ms  med=235.46ms max=1.73s p(90)=426.11ms p(95)=515.91ms
     aws_obj_get_success....: 1746032 2907.979749/s
     data_received..........: 1.8 TB  3.0 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=261.17ms min=199.13µs med=235.56ms max=1.73s p(90)=426.21ms p(95)=516.02ms
     iterations.............: 1746032 2907.979749/s
     vus....................: 760     min=760       max=760

running (10m00.4s), 000/760 VUs, 1746032 complete and 0 interrupted iterations
read ✓ [======================================] 760 VUs  10m0s

### 16 nodes 128mb write
INFO[13:38:52] Load started at:               Sat Nov 02 2024 13:38:52 GMT+0000 (UTC)  source=console
INFO[13:48:57] Load finished at:              Sat Nov 02 2024 13:48:57 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 774 GB 1.3 GB/s
     aws_obj_put_duration...: avg=16.14s min=5.95s    med=14.65s max=1m20s p(90)=22.97s p(95)=27.69s
     aws_obj_put_success....: 5766   9.520381/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 774 GB 1.3 GB/s
     iteration_duration.....: avg=16.57s min=181.09µs med=15.09s max=1m20s p(90)=23.41s p(95)=28.15s
     iterations.............: 5762   9.513776/s
     vus....................: 108    min=0      max=160

running (10m05.6s), 000/160 VUs, 5762 complete and 105 interrupted iterations
write ✓ [======================================] 160 VUs  10m0s

NFO[13:38:54] Load started at:               Sat Nov 02 2024 13:38:54 GMT+0000 (UTC)  source=console
INFO[13:48:59] Load finished at:              Sat Nov 02 2024 13:48:59 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 759 GB 1.3 GB/s
     aws_obj_put_duration...: avg=16.46s min=5.7s     med=14.9s  max=1m13s p(90)=23.54s p(95)=29.07s
     aws_obj_put_success....: 5656   9.337739/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 759 GB 1.3 GB/s
     iteration_duration.....: avg=16.9s  min=152.36µs med=15.34s max=1m14s p(90)=23.97s p(95)=29.5s 
     iterations.............: 5648   9.324531/s
     vus....................: 0      min=0      max=160

running (10m05.7s), 000/160 VUs, 5648 complete and 117 interrupted iterations
write ✓ [======================================] 160 VUs  10m0s

### 16 nodes 128mb read
INFO[14:10:54] Load started at:               Sat Nov 02 2024 14:10:54 GMT+0000 (UTC)  source=console
INFO[14:20:57] Load finished at:              Sat Nov 02 2024 14:20:57 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 2.5 TB 4.1 GB/s
     aws_obj_get_duration...: avg=5.24s min=1.8s     med=5.38s max=8.37s p(90)=6.6s p(95)=6.88s
     aws_obj_get_success....: 18349  30.432306/s
     data_received..........: 2.5 TB 4.1 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=5.24s min=384.05µs med=5.38s max=8.37s p(90)=6.6s p(95)=6.88s
     iterations.............: 18349  30.432306/s
     vus....................: 1      min=1       max=160

running (10m02.9s), 000/160 VUs, 18349 complete and 0 interrupted iterations
read ✓ [======================================] 160 VUs  10m0s

INFO[14:10:53] Load started at:               Sat Nov 02 2024 14:10:53 GMT+0000 (UTC)  source=console
INFO[14:20:57] Load finished at:              Sat Nov 02 2024 14:20:57 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 2.5 TB 4.1 GB/s
     aws_obj_get_duration...: avg=5.23s min=1.59s    med=5.3s max=8.52s p(90)=6.49s p(95)=6.8s
     aws_obj_get_success....: 18417  30.491472/s
     data_received..........: 2.5 TB 4.1 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=5.23s min=414.01µs med=5.3s max=8.52s p(90)=6.49s p(95)=6.8s
     iterations.............: 18417  30.491472/s
     vus....................: 2      min=2       max=160

running (10m04.0s), 000/160 VUs, 18417 complete and 0 interrupted iterations
read ✓ [======================================] 160 VUs  10m0s

### 15 nodes 128kb write
INFO[15:18:26] Load started at:               Fri Nov 01 2024 15:18:26 GMT+0000 (UTC)  source=console
INFO[15:28:31] Load finished at:              Fri Nov 01 2024 15:28:31 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 228 GB  378 MB/s
     aws_obj_put_duration...: avg=378.21ms min=36.23ms  med=174.29ms max=10.75s p(90)=663.59ms p(95)=1.68s
     aws_obj_put_success....: 1742848 2884.961743/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 228 GB  378 MB/s
     iteration_duration.....: avg=387.93ms min=202.79µs med=185.42ms max=10.77s p(90)=673.54ms p(95)=1.69s
     iterations.............: 1742848 2884.961743/s
     vus....................: 1       min=1         max=1125

running (10m04.1s), 0000/1125 VUs, 1742848 complete and 0 interrupted iterations
write ✓ [======================================] 1125 VUs  10m0s

INFO[15:18:27] Load started at:               Fri Nov 01 2024 15:18:27 GMT+0000 (UTC)  source=console
INFO[15:28:31] Load finished at:              Fri Nov 01 2024 15:28:31 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 221 GB  366 MB/s
     aws_obj_put_duration...: avg=391.32ms min=34.78ms  med=176.87ms max=10.88s p(90)=748.01ms p(95)=1.74s
     aws_obj_put_success....: 1686529 2793.705183/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 221 GB  366 MB/s
     iteration_duration.....: avg=400.88ms min=207.05µs med=187.36ms max=10.89s p(90)=757.73ms p(95)=1.75s
     iterations.............: 1686529 2793.705183/s
     vus....................: 32      min=32        max=1125

running (10m03.7s), 0000/1125 VUs, 1686529 complete and 0 interrupted iterations
write ✓ [======================================] 1125 VUs  10m0s

### 15 nodes 128kb read
INFO[15:44:02] Load started at:               Fri Nov 01 2024 15:44:02 GMT+0000 (UTC)  source=console
INFO[15:54:03] Load finished at:              Fri Nov 01 2024 15:54:03 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 653 GB  1.1 GB/s
     aws_obj_get_duration...: avg=135.35ms min=8.04ms  med=109.43ms max=2.63s p(90)=260.75ms p(95)=315.2ms 
     aws_obj_get_success....: 4983395 8298.056832/s
     data_received..........: 653 GB  1.1 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=135.44ms min=558.6µs med=109.52ms max=2.63s p(90)=260.83ms p(95)=315.29ms
     iterations.............: 4983395 8298.056832/s
     vus....................: 1125    min=1125      max=1125

running (10m00.5s), 0000/1125 VUs, 4983395 complete and 0 interrupted iterations
read ✓ [======================================] 1125 VUs  10m0s

INFO[15:44:04] Load started at:               Fri Nov 01 2024 15:44:04 GMT+0000 (UTC)  source=console
INFO[15:54:04] Load finished at:              Fri Nov 01 2024 15:54:04 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 651 GB  1.1 GB/s
     aws_obj_get_duration...: avg=135.75ms min=8.69ms   med=109.83ms max=2.47s p(90)=261.3ms  p(95)=315.68ms
     aws_obj_get_success....: 4968685 8274.744336/s
     data_received..........: 651 GB  1.1 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=135.83ms min=246.71µs med=109.91ms max=2.47s p(90)=261.39ms p(95)=315.77ms
     iterations.............: 4968685 8274.744336/s
     vus....................: 1125    min=1125      max=1125

running (10m00.5s), 0000/1125 VUs, 4968685 complete and 0 interrupted iterations
read ✓ [======================================] 1125 VUs  10m0s

### 15 nodes 1mb write
INFO[16:00:01] Load started at:               Fri Nov 01 2024 16:00:01 GMT+0000 (UTC)  source=console
INFO[16:10:03] Load finished at:              Fri Nov 01 2024 16:10:03 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 608 GB 1.0 GB/s
     aws_obj_put_duration...: avg=760.48ms min=92.2ms   med=632.24ms max=6.48s p(90)=1.28s p(95)=1.64s
     aws_obj_put_success....: 579725 963.943542/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 608 GB 1.0 GB/s
     iteration_duration.....: avg=776.65ms min=250.51µs med=648.51ms max=6.49s p(90)=1.29s p(95)=1.66s
     iterations.............: 579725 963.943542/s
     vus....................: 73     min=73       max=750

running (10m01.4s), 000/750 VUs, 579725 complete and 0 interrupted iterations
write ✓ [======================================] 750 VUs  10m0s

INFO[16:00:02] Load started at:               Fri Nov 01 2024 16:00:02 GMT+0000 (UTC)  source=console
INFO[16:10:03] Load finished at:              Fri Nov 01 2024 16:10:03 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 623 GB 1.0 GB/s
     aws_obj_put_duration...: avg=741.32ms min=98.68ms  med=615.92ms max=7.28s p(90)=1.25s p(95)=1.6s 
     aws_obj_put_success....: 594213 989.345925/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 623 GB 1.0 GB/s
     iteration_duration.....: avg=757.59ms min=342.58µs med=632.21ms max=7.31s p(90)=1.26s p(95)=1.61s
     iterations.............: 594213 989.345925/s
     vus....................: 750    min=750      max=750

running (10m00.6s), 000/750 VUs, 594213 complete and 0 interrupted iterations
write ✓ [======================================] 750 VUs  10m0s

### 15 nodes 1mb read
INFO[16:22:31] Load started at:               Fri Nov 01 2024 16:22:31 GMT+0000 (UTC)  source=console
INFO[16:32:32] Load finished at:              Fri Nov 01 2024 16:32:32 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.7 TB  2.8 GB/s
     aws_obj_get_duration...: avg=278.47ms min=23.67ms med=243.74ms max=7.25s p(90)=455.36ms p(95)=539.76ms
     aws_obj_get_success....: 1615488 2691.349171/s
     data_received..........: 1.7 TB  2.8 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=278.56ms min=1.99ms  med=243.83ms max=7.25s p(90)=455.46ms p(95)=539.85ms
     iterations.............: 1615488 2691.349171/s
     vus....................: 750     min=750       max=750

running (10m00.3s), 000/750 VUs, 1615488 complete and 0 interrupted iterations
read ✓ [======================================] 750 VUs  10m0s

INFO[16:22:30] Load started at:               Fri Nov 01 2024 16:22:30 GMT+0000 (UTC)  source=console
INFO[16:32:31] Load finished at:              Fri Nov 01 2024 16:32:31 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.7 TB  2.8 GB/s
     aws_obj_get_duration...: avg=279.49ms min=20.49ms  med=244.82ms max=7.07s p(90)=457.03ms p(95)=541.77ms
     aws_obj_get_success....: 1609796 2680.091853/s
     data_received..........: 1.7 TB  2.8 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=279.58ms min=210.43µs med=244.91ms max=7.07s p(90)=457.12ms p(95)=541.86ms
     iterations.............: 1609796 2680.091853/s
     vus....................: 750     min=750       max=750

running (10m00.6s), 000/750 VUs, 1609796 complete and 0 interrupted iterations
read ✓ [======================================] 750 VUs  10m0s

### 15 nodes 128mb write
INFO[16:38:30] Load started at:               Fri Nov 01 2024 16:38:30 GMT+0000 (UTC)  source=console
INFO[16:48:36] Load finished at:              Fri Nov 01 2024 16:48:36 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 748 GB 1.2 GB/s
     aws_obj_put_duration...: avg=15.61s min=6.91s    med=14.51s max=53.01s p(90)=21.69s p(95)=25.39s
     aws_obj_put_fails......: 3      0.004953/s
     aws_obj_put_success....: 5569   9.193582/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 747 GB 1.2 GB/s
     iteration_duration.....: avg=16.04s min=178.36µs med=14.94s max=53.47s p(90)=22.11s p(95)=25.79s
     iterations.............: 5560   9.178725/s
     vus....................: 0      min=0      max=150

running (10m05.7s), 000/150 VUs, 5560 complete and 123 interrupted iterations
write ✓ [======================================] 150 VUs  10m0s

INFO[16:38:32] Load started at:               Fri Nov 01 2024 16:38:32 GMT+0000 (UTC)  source=console
INFO[16:48:37] Load finished at:              Fri Nov 01 2024 16:48:37 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 731 GB 1.2 GB/s
     aws_obj_put_duration...: avg=16s    min=7.11s    med=14.85s max=53.51s p(90)=22.5s  p(95)=25.81s
     aws_obj_put_fails......: 4      0.006606/s
     aws_obj_put_success....: 5447   8.996272/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 731 GB 1.2 GB/s
     iteration_duration.....: avg=16.43s min=201.39µs med=15.29s max=53.95s p(90)=22.94s p(95)=26.28s
     iterations.............: 5448   8.997924/s
     vus....................: 104    min=0      max=150

running (10m05.5s), 000/150 VUs, 5448 complete and 101 interrupted iterations
write ✓ [======================================] 150 VUs  10m0s

### 15 nodes 128mb read
INFO[17:01:23] Load started at:               Fri Nov 01 2024 17:01:23 GMT+0000 (UTC)  source=console
INFO[17:11:29] Load finished at:              Fri Nov 01 2024 17:11:29 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 2.1 TB 3.4 GB/s
     aws_obj_get_duration...: avg=5.86s min=1.51s    med=5.28s max=22.64s p(90)=9.61s p(95)=11.21s
     aws_obj_get_success....: 15395  25.383372/s
     data_received..........: 2.1 TB 3.4 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=5.86s min=310.79µs med=5.28s max=22.64s p(90)=9.61s p(95)=11.21s
     iterations.............: 15395  25.383372/s
     vus....................: 6      min=6       max=150

running (10m06.5s), 000/150 VUs, 15395 complete and 10 interrupted iterations
read ✓ [======================================] 150 VUs  10m0s

INFO[17:01:21] Load started at:               Fri Nov 01 2024 17:01:21 GMT+0000 (UTC)  source=console
INFO[17:11:29] Load finished at:              Fri Nov 01 2024 17:11:29 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 2.0 TB 3.3 GB/s
     aws_obj_get_duration...: avg=5.98s min=1.5s     med=5.41s max=23.95s p(90)=9.74s p(95)=11.34s
     aws_obj_get_success....: 15088  24.825863/s
     data_received..........: 2.0 TB 3.3 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=5.98s min=532.98µs med=5.41s max=23.95s p(90)=9.74s p(95)=11.34s
     iterations.............: 15088  24.825863/s
     vus....................: 1      min=1       max=150

running (10m07.8s), 000/150 VUs, 15088 complete and 27 interrupted iterations
read ✓ [======================================] 150 VUs  10m0s

### 12 nodes 8kb write
INFO[07:30:10] Load started at:               Sat Nov 02 2024 07:30:10 GMT+0000 (UTC)  source=console
INFO[07:40:10] Load finished at:              Sat Nov 02 2024 07:40:10 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 18 GB   30 MB/s
     aws_obj_put_duration...: avg=232.44ms min=41.57ms med=140.24ms max=4.62s p(90)=364.54ms p(95)=617.69ms
     aws_obj_put_success....: 2166687 3608.289955/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 18 GB   30 MB/s
     iteration_duration.....: avg=240.92ms min=613.4µs med=147.29ms max=4.63s p(90)=373.55ms p(95)=625.8ms 
     iterations.............: 2166687 3608.289955/s
     vus....................: 870     min=870       max=870

running (10m00.5s), 000/870 VUs, 2166687 complete and 0 interrupted iterations
write ✓ [======================================] 870 VUs  10m0s

INFO[07:30:08] Load started at:               Sat Nov 02 2024 07:30:08 GMT+0000 (UTC)  source=console
INFO[07:40:10] Load finished at:              Sat Nov 02 2024 07:40:10 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 18 GB   30 MB/s
     aws_obj_put_duration...: avg=230.81ms min=39.85ms  med=141.77ms max=4.6s p(90)=343.47ms p(95)=593.49ms
     aws_obj_put_success....: 2183446 3628.254535/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 18 GB   30 MB/s
     iteration_duration.....: avg=239.18ms min=217.35µs med=148.58ms max=4.6s p(90)=352.43ms p(95)=602.11ms
     iterations.............: 2183446 3628.254535/s
     vus....................: 146     min=146       max=870

running (10m01.8s), 000/870 VUs, 2183446 complete and 0 interrupted iterations
write ✓ [======================================] 870 VUs  10m0s

### 12 nodes 8kb read
INFO[13:07:26] Load started at:               Sat Nov 02 2024 13:07:26 GMT+0000 (UTC)  source=console
INFO[13:17:26] Load finished at:              Sat Nov 02 2024 13:17:26 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 40 GB   66 MB/s
     aws_obj_get_duration...: avg=107.91ms min=6.69ms   med=67.6ms  max=4.78s p(90)=210.83ms p(95)=306.79ms
     aws_obj_get_fails......: 11      0.018309/s
     aws_obj_get_success....: 4832956 8044.348868/s
     data_received..........: 40 GB   66 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=107.99ms min=196.06µs med=67.68ms max=4.78s p(90)=210.91ms p(95)=306.87ms
     iterations.............: 4832967 8044.367177/s
     vus....................: 870     min=870       max=870

running (10m00.8s), 000/870 VUs, 4832967 complete and 0 interrupted iterations
read ✓ [======================================] 870 VUs  10m0s

INFO[13:06:58] Load started at:               Sat Nov 02 2024 13:06:58 GMT+0000 (UTC)  source=console
INFO[13:17:01] Load finished at:              Sat Nov 02 2024 13:17:01 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 38 GB   62 MB/s
     aws_obj_get_duration...: avg=113.59ms min=6.38ms   med=70.7ms  max=4.19s p(90)=228.15ms p(95)=330.25ms
     aws_obj_get_fails......: 29      0.048081/s
     aws_obj_get_success....: 4594213 7617.072403/s
     data_received..........: 38 GB   62 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=113.67ms min=226.87µs med=70.78ms max=4.19s p(90)=228.23ms p(95)=330.33ms
     iterations.............: 4594242 7617.120484/s
     vus....................: 5       min=5         max=870

running (10m03.1s), 000/870 VUs, 4594242 complete and 0 interrupted iterations
read ✓ [======================================] 870 VUs  10m0s

### 12 nodes 128kb write
INFO[07:56:01] Load started at:               Sat Nov 02 2024 07:56:01 GMT+0000 (UTC)  source=console
INFO[08:06:04] Load finished at:              Sat Nov 02 2024 08:06:04 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 178 GB  296 MB/s
     aws_obj_put_duration...: avg=348.32ms min=34.21ms  med=208.7ms  max=7.79s p(90)=546.25ms p(95)=1.12s
     aws_obj_put_success....: 1359641 2256.948163/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 178 GB  295 MB/s
     iteration_duration.....: avg=357.83ms min=200.01µs med=219.01ms max=7.8s  p(90)=556.05ms p(95)=1.13s
     iterations.............: 1359641 2256.948163/s
     vus....................: 96      min=96        max=810

running (10m02.4s), 000/810 VUs, 1359641 complete and 0 interrupted iterations
write ✓ [======================================] 810 VUs  10m0s

INFO[07:56:03] Load started at:               Sat Nov 02 2024 07:56:03 GMT+0000 (UTC)  source=console
INFO[08:06:06] Load finished at:              Sat Nov 02 2024 08:06:06 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 181 GB  300 MB/s
     aws_obj_put_duration...: avg=342.48ms min=33.55ms  med=203.77ms max=7.99s p(90)=541.91ms p(95)=1.09s
     aws_obj_put_success....: 1380740 2292.223497/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 181 GB  300 MB/s
     iteration_duration.....: avg=352.11ms min=548.26µs med=212.72ms max=8s    p(90)=551.63ms p(95)=1.1s 
     iterations.............: 1380740 2292.223497/s
     vus....................: 2       min=2         max=810

running (10m02.4s), 000/810 VUs, 1380740 complete and 0 interrupted iterations
write ✓ [======================================] 810 VUs  10m0s

### 12 nodes 128kb read
INFO[08:11:36] Load started at:               Sat Nov 02 2024 08:11:36 GMT+0000 (UTC)  source=console
INFO[08:21:37] Load finished at:              Sat Nov 02 2024 08:21:37 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 504 GB  839 MB/s
     aws_obj_get_duration...: avg=126.25ms min=7.89ms  med=91.19ms max=3.4s p(90)=270.79ms p(95)=332.83ms
     aws_obj_get_fails......: 8       0.013315/s
     aws_obj_get_success....: 3846835 6402.423919/s
     data_received..........: 504 GB  839 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=126.34ms min=197.1µs med=91.27ms max=3.4s p(90)=270.87ms p(95)=332.91ms
     iterations.............: 3846843 6402.437234/s
     vus....................: 810     min=810       max=810

running (10m00.8s), 000/810 VUs, 3846843 complete and 0 interrupted iterations
read ✓ [======================================] 810 VUs  10m0s

INFO[08:11:37] Load started at:               Sat Nov 02 2024 08:11:37 GMT+0000 (UTC)  source=console
INFO[08:21:38] Load finished at:              Sat Nov 02 2024 08:21:38 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 506 GB  842 MB/s
     aws_obj_get_duration...: avg=125.88ms min=7.68ms med=90.89ms max=4.04s p(90)=270.11ms p(95)=332.01ms
     aws_obj_get_fails......: 9       0.014989/s
     aws_obj_get_success....: 3857764 6424.754162/s
     data_received..........: 505 GB  841 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=125.96ms min=1.89ms med=90.97ms max=4.04s p(90)=270.19ms p(95)=332.1ms 
     iterations.............: 3857773 6424.76915/s
     vus....................: 810     min=810       max=810

running (10m00.5s), 000/810 VUs, 3857773 complete and 0 interrupted iterations
read ✓ [======================================] 810 VUs  10m0s
 
### 12 nodes 1mb write
INFO[09:11:46] Load started at:               Sat Nov 02 2024 09:11:46 GMT+0000 (UTC)  source=console
INFO[09:21:46] Load finished at:              Sat Nov 02 2024 09:21:46 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 538 GB 896 MB/s
     aws_obj_put_duration...: avg=685.29ms min=76.77ms med=597.42ms max=5.39s p(90)=1.17s p(95)=1.43s
     aws_obj_put_success....: 513189 854.884066/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 538 GB 896 MB/s
     iteration_duration.....: avg=701.62ms min=256.2µs med=613.85ms max=5.4s  p(90)=1.18s p(95)=1.44s
     iterations.............: 513189 854.884066/s
     vus....................: 600    min=600      max=600

running (10m00.3s), 000/600 VUs, 513189 complete and 0 interrupted iterations
write ✓ [======================================] 600 VUs  10m0s

INFO[09:11:44] Load started at:               Sat Nov 02 2024 09:11:44 GMT+0000 (UTC)  source=console
INFO[09:21:45] Load finished at:              Sat Nov 02 2024 09:21:45 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 528 GB 878 MB/s
     aws_obj_put_duration...: avg=699.16ms min=75.55ms  med=613.13ms max=5.65s p(90)=1.18s p(95)=1.44s
     aws_obj_put_success....: 503294 837.203603/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 528 GB 878 MB/s
     iteration_duration.....: avg=715.67ms min=248.75µs med=629.54ms max=5.66s p(90)=1.19s p(95)=1.45s
     iterations.............: 503294 837.203603/s
     vus....................: 63     min=63       max=600

running (10m01.2s), 000/600 VUs, 503294 complete and 0 interrupted iterations
write ✓ [======================================] 600 VUs  10m0s

### 12 nodes 1mb read
INFO[09:32:03] Load started at:               Sat Nov 02 2024 09:32:03 GMT+0000 (UTC)  source=console
INFO[09:42:03] Load finished at:              Sat Nov 02 2024 09:42:03 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.4 TB  2.3 GB/s
     aws_obj_get_duration...: avg=267.91ms min=22.6ms   med=236.25ms max=3.74s p(90)=457.37ms p(95)=535.75ms
     aws_obj_get_success....: 1343345 2237.581533/s
     data_received..........: 1.4 TB  2.3 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=268ms    min=197.83µs med=236.35ms max=3.74s p(90)=457.47ms p(95)=535.85ms
     iterations.............: 1343345 2237.581533/s
     vus....................: 600     min=600       max=600

running (10m00.4s), 000/600 VUs, 1343345 complete and 0 interrupted iterations
read ✓ [======================================] 600 VUs  10m0s

INFO[09:32:01] Load started at:               Sat Nov 02 2024 09:32:01 GMT+0000 (UTC)  source=console
INFO[09:42:02] Load finished at:              Sat Nov 02 2024 09:42:02 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.4 TB  2.3 GB/s
     aws_obj_get_duration...: avg=269.09ms min=21.85ms  med=236.84ms max=3.54s p(90)=460.05ms p(95)=539.14ms
     aws_obj_get_success....: 1337536 2226.85145/s
     data_received..........: 1.4 TB  2.3 GB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=269.19ms min=517.32µs med=236.93ms max=3.54s p(90)=460.14ms p(95)=539.24ms
     iterations.............: 1337536 2226.85145/s
     vus....................: 600     min=600      max=600

running (10m00.6s), 000/600 VUs, 1337536 complete and 0 interrupted iterations
read ✓ [======================================] 600 VUs  10m0s


### 12 nodes 128mb write
INFO[11:14:47] Load started at:               Sat Nov 02 2024 11:14:47 GMT+0000 (UTC)  source=console
INFO[11:24:52] Load finished at:              Sat Nov 02 2024 11:24:52 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 581 GB 960 MB/s
     aws_obj_put_duration...: avg=16.1s  min=6.44s    med=15.11s max=1m0s p(90)=21.97s p(95)=24.6s 
     aws_obj_put_success....: 4331   7.150328/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 581 GB 960 MB/s
     iteration_duration.....: avg=16.54s min=192.09µs med=15.54s max=1m0s p(90)=22.4s  p(95)=25.03s
     iterations.............: 4323   7.13712/s
     vus....................: 79     min=0      max=120

running (10m05.7s), 000/120 VUs, 4323 complete and 78 interrupted iterations
write ✓ [======================================] 120 VUs  10m0s

INFO[11:14:47] Load started at:               Sat Nov 02 2024 11:14:47 GMT+0000 (UTC)  source=console
INFO[11:24:52] Load finished at:              Sat Nov 02 2024 11:24:52 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 581 GB 960 MB/s
     aws_obj_put_duration...: avg=16.1s  min=6.44s    med=15.11s max=1m0s p(90)=21.97s p(95)=24.6s 
     aws_obj_put_success....: 4331   7.150328/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 581 GB 960 MB/s
     iteration_duration.....: avg=16.54s min=192.09µs med=15.54s max=1m0s p(90)=22.4s  p(95)=25.03s
     iterations.............: 4323   7.13712/s
     vus....................: 79     min=0      max=120

running (10m05.7s), 000/120 VUs, 4323 complete and 78 interrupted iterations
write ✓ [======================================] 120 VUs  10m0s

### 12 nodes 128mb read
INFO[11:43:23] Load started at:               Sat Nov 02 2024 11:43:23 GMT+0000 (UTC)  source=console
INFO[11:53:26] Load finished at:              Sat Nov 02 2024 11:53:26 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.9 TB 3.2 GB/s
     aws_obj_get_duration...: avg=5.03s min=1.51s    med=4.64s max=58.38s p(90)=7.1s p(95)=8.27s
     aws_obj_get_success....: 14343  23.777464/s
     data_received..........: 1.9 TB 3.2 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=5.03s min=338.09µs med=4.64s max=58.38s p(90)=7.1s p(95)=8.27s
     iterations.............: 14343  23.777464/s
     vus....................: 6      min=6       max=120

running (10m03.2s), 000/120 VUs, 14343 complete and 0 interrupted iterations
read ✓ [======================================] 120 VUs  10m0s

INFO[11:43:21] Load started at:               Sat Nov 02 2024 11:43:21 GMT+0000 (UTC)  source=console
INFO[11:53:26] Load finished at:              Sat Nov 02 2024 11:53:26 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.9 TB 3.2 GB/s
     aws_obj_get_duration...: avg=5.04s min=1.66s    med=4.67s max=57.39s p(90)=7.11s p(95)=8.27s
     aws_obj_get_success....: 14333  23.698084/s
     data_received..........: 1.9 TB 3.2 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=5.04s min=166.41µs med=4.67s max=57.39s p(90)=7.11s p(95)=8.27s
     iterations.............: 14333  23.698084/s
     vus....................: 8      min=8       max=120

running (10m04.8s), 000/120 VUs, 14333 complete and 0 interrupted iterations
read ✓ [======================================] 120 VUs  10m0s

### 8 nodes 8kb write
INFO[17:51:29] Load started at:               Fri Nov 01 2024 17:51:29 GMT+0000 (UTC)  source=console
INFO[18:01:30] Load finished at:              Fri Nov 01 2024 18:01:30 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 12 GB   20 MB/s
     aws_obj_put_duration...: avg=225.03ms min=38.81ms  med=155.36ms max=7.86s p(90)=441.11ms p(95)=679.14ms
     aws_obj_put_success....: 1491275 2480.991169/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 12 GB   20 MB/s
     iteration_duration.....: avg=233.4ms  min=211.89µs med=163.36ms max=7.87s p(90)=449.4ms  p(95)=687.56ms
     iterations.............: 1491275 2480.991169/s
     vus....................: 1       min=1         max=580

running (10m01.1s), 000/580 VUs, 1491275 complete and 0 interrupted iterations
write ✓ [======================================] 580 VUs  10m0s

INFO[17:51:40] Load started at:               Fri Nov 01 2024 17:51:40 GMT+0000 (UTC)  source=console
INFO[18:01:41] Load finished at:              Fri Nov 01 2024 18:01:41 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 12 GB   20 MB/s
     aws_obj_put_duration...: avg=227.99ms min=39.21ms  med=152.66ms max=7.96s p(90)=469.52ms p(95)=726.61ms
     aws_obj_put_success....: 1473181 2454.737954/s
     data_received..........: 0 B     0 B/s
     data_sent..............: 12 GB   20 MB/s
     iteration_duration.....: avg=236.21ms min=193.47µs med=160.19ms max=7.97s p(90)=477.76ms p(95)=734.84ms
     iterations.............: 1473181 2454.737954/s
     vus....................: 580     min=580       max=580

running (10m00.1s), 000/580 VUs, 1473181 complete and 0 interrupted iterations
write ✓ [======================================] 580 VUs  10m0s

### 8 nodes 8kb read
INFO[18:03:32] Load started at:               Fri Nov 01 2024 18:03:32 GMT+0000 (UTC)  source=console
INFO[18:13:34] Load finished at:              Fri Nov 01 2024 18:13:34 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 26 GB   43 MB/s
     aws_obj_get_duration...: avg=110.21ms min=5.75ms   med=62.79ms max=6.14s p(90)=205.83ms p(95)=329.18ms
     aws_obj_get_success....: 3156204 5238.497565/s
     data_received..........: 26 GB   43 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=110.29ms min=185.79µs med=62.87ms max=6.14s p(90)=205.9ms  p(95)=329.26ms
     iterations.............: 3156204 5238.497565/s
     vus....................: 9       min=9         max=580

running (10m02.5s), 000/580 VUs, 3156204 complete and 0 interrupted iterations
read ✓ [======================================] 580 VUs  10m0s

INFO[18:03:34] Load started at:               Fri Nov 01 2024 18:03:34 GMT+0000 (UTC)  source=console
INFO[18:13:35] Load finished at:              Fri Nov 01 2024 18:13:35 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 26 GB   44 MB/s
     aws_obj_get_duration...: avg=108.75ms min=6.01ms   med=61.74ms max=6.04s p(90)=204.38ms p(95)=326.22ms
     aws_obj_get_success....: 3197807 5323.334442/s
     data_received..........: 26 GB   44 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=108.83ms min=217.01µs med=61.82ms max=6.04s p(90)=204.46ms p(95)=326.3ms 
     iterations.............: 3197807 5323.334442/s
     vus....................: 580     min=580       max=580

running (10m00.7s), 000/580 VUs, 3197807 complete and 0 interrupted iterations
read ✓ [======================================] 580 VUs  10m0s

### 8 nodes 128kb write
INFO[18:18:30] Load started at:               Fri Nov 01 2024 18:18:30 GMT+0000 (UTC)  source=console
INFO[18:28:32] Load finished at:              Fri Nov 01 2024 18:28:32 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 121 GB 201 MB/s
     aws_obj_put_duration...: avg=342.57ms min=36.29ms  med=199.03ms max=7.2s p(90)=538.63ms p(95)=929.55ms
     aws_obj_put_success....: 922098 1530.533661/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 121 GB 200 MB/s
     iteration_duration.....: avg=352ms    min=447.67µs med=208.15ms max=7.2s p(90)=548.13ms p(95)=938.99ms
     iterations.............: 922098 1530.533661/s
     vus....................: 176    min=176       max=540

running (10m02.5s), 000/540 VUs, 922098 complete and 0 interrupted iterations
write ✓ [======================================] 540 VUs  10m0s

INFO[18:18:28] Load started at:               Fri Nov 01 2024 18:18:28 GMT+0000 (UTC)  source=console
INFO[18:28:32] Load finished at:              Fri Nov 01 2024 18:28:32 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 119 GB 196 MB/s
     aws_obj_put_duration...: avg=348.43ms min=30.4ms   med=201.46ms max=7.16s p(90)=552.69ms p(95)=957.88ms
     aws_obj_put_success....: 905840 1498.778524/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 119 GB 196 MB/s
     iteration_duration.....: avg=358.13ms min=239.01µs med=211.37ms max=7.17s p(90)=562.49ms p(95)=967.51ms
     iterations.............: 905840 1498.778524/s
     vus....................: 6      min=6         max=540

running (10m04.4s), 000/540 VUs, 905840 complete and 0 interrupted iterations
write ✓ [======================================] 540 VUs  10m0s

### 8 nodes 128kb read
INFO[18:38:31] Load started at:               Fri Nov 01 2024 18:38:31 GMT+0000 (UTC)  source=console
INFO[18:48:31] Load finished at:              Fri Nov 01 2024 18:48:31 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 358 GB  596 MB/s
     aws_obj_get_duration...: avg=118.57ms min=7.44ms med=85.54ms max=2.81s p(90)=256.26ms p(95)=317.45ms
     aws_obj_get_fails......: 17      0.028326/s
     aws_obj_get_success....: 2730100 4548.922732/s
     data_received..........: 358 GB  596 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=118.66ms min=1.22ms med=85.62ms max=2.81s p(90)=256.35ms p(95)=317.54ms
     iterations.............: 2730117 4548.951058/s
     vus....................: 540     min=540       max=540

running (10m00.2s), 000/540 VUs, 2730117 complete and 0 interrupted iterations
read ✓ [======================================] 540 VUs  10m0s

INFO[18:38:29] Load started at:               Fri Nov 01 2024 18:38:29 GMT+0000 (UTC)  source=console
INFO[18:48:29] Load finished at:              Fri Nov 01 2024 18:48:29 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 358 GB  596 MB/s
     aws_obj_get_duration...: avg=118.5ms  min=7.57ms   med=85.32ms max=2.74s p(90)=256.32ms p(95)=317.24ms
     aws_obj_get_fails......: 18      0.029975/s
     aws_obj_get_success....: 2731862 4549.322039/s
     data_received..........: 358 GB  596 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=118.59ms min=199.04µs med=85.4ms  max=2.74s p(90)=256.42ms p(95)=317.33ms
     iterations.............: 2731880 4549.352014/s
     vus....................: 540     min=540       max=540

running (10m00.5s), 000/540 VUs, 2731880 complete and 0 interrupted iterations
read ✓ [======================================] 540 VUs  10m0s

### 8 nodes 1mb write
INFO[18:54:37] Load started at:               Fri Nov 01 2024 18:54:37 GMT+0000 (UTC)  source=console
INFO[19:04:39] Load finished at:              Fri Nov 01 2024 19:04:39 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 323 GB 537 MB/s
     aws_obj_put_duration...: avg=762.28ms min=84.12ms  med=545.83ms max=9.3s  p(90)=1.37s p(95)=2.1s 
     aws_obj_put_success....: 308101 512.300309/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 323 GB 537 MB/s
     iteration_duration.....: avg=779.45ms min=284.82µs med=563.1ms  max=9.32s p(90)=1.39s p(95)=2.12s
     iterations.............: 308101 512.300309/s
     vus....................: 27     min=27       max=400

running (10m01.4s), 000/400 VUs, 308101 complete and 0 interrupted iterations
write ✓ [======================================] 400 VUs  10m0s

INFO[18:54:39] Load started at:               Fri Nov 01 2024 18:54:39 GMT+0000 (UTC)  source=console
INFO[19:04:40] Load finished at:              Fri Nov 01 2024 19:04:40 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 354 GB 589 MB/s
     aws_obj_put_duration...: avg=694.48ms min=79.97ms  med=503.21ms max=9.65s p(90)=1.22s p(95)=1.85s
     aws_obj_put_fails......: 2      0.003329/s
     aws_obj_put_success....: 337458 561.712071/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 354 GB 589 MB/s
     iteration_duration.....: avg=711.37ms min=192.27µs med=520.07ms max=9.67s p(90)=1.23s p(95)=1.86s
     iterations.............: 337460 561.7154/s
     vus....................: 400    min=400      max=400

running (10m00.8s), 000/400 VUs, 337460 complete and 0 interrupted iterations
write ✓ [======================================] 400 VUs  10m0s

### 8 nodes 1mb read
INFO[19:16:42] Load started at:               Fri Nov 01 2024 19:16:42 GMT+0000 (UTC)  source=console
INFO[19:26:43] Load finished at:              Fri Nov 01 2024 19:26:43 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 926 GB 1.5 GB/s
     aws_obj_get_duration...: avg=271.82ms min=24.58ms med=206.29ms max=4.89s p(90)=445.09ms p(95)=577.72ms
     aws_obj_get_success....: 882650 1469.731268/s
     data_received..........: 925 GB 1.5 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=271.92ms min=259.1µs med=206.39ms max=4.89s p(90)=445.19ms p(95)=577.81ms
     iterations.............: 882650 1469.731268/s
     vus....................: 400    min=400       max=400

running (10m00.6s), 000/400 VUs, 882650 complete and 0 interrupted iterations
read ✓ [======================================] 400 VUs  10m0s

INFO[19:16:40] Load started at:               Fri Nov 01 2024 19:16:40 GMT+0000 (UTC)  source=console
INFO[19:26:41] Load finished at:              Fri Nov 01 2024 19:26:41 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 927 GB 1.5 GB/s
     aws_obj_get_duration...: avg=271.48ms min=24.39ms  med=204.97ms max=5.41s p(90)=446.42ms p(95)=584.6ms
     aws_obj_get_success....: 883851 1471.85554/s
     data_received..........: 927 GB 1.5 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=271.58ms min=178.66µs med=205.07ms max=5.41s p(90)=446.52ms p(95)=584.7ms
     iterations.............: 883851 1471.85554/s
     vus....................: 400    min=400      max=400

running (10m00.5s), 000/400 VUs, 883851 complete and 0 interrupted iterations
read ✓ [======================================] 400 VUs  10m0s

### 8 nodes 128mb write
INFO[19:43:54] Load started at:               Fri Nov 01 2024 19:43:54 GMT+0000 (UTC)  source=console
INFO[19:53:59] Load finished at:              Fri Nov 01 2024 19:53:59 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 417 GB 689 MB/s
     aws_obj_put_duration...: avg=14.95s min=7s      med=14.39s max=34.56s p(90)=19.6s  p(95)=21.57s
     aws_obj_put_fails......: 2      0.003304/s
     aws_obj_put_success....: 3107   5.132104/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 417 GB 689 MB/s
     iteration_duration.....: avg=15.37s min=172.9µs med=14.81s max=34.98s p(90)=20.03s p(95)=21.98s
     iterations.............: 3109   5.135407/s
     vus....................: 50     min=0      max=80

running (10m05.4s), 00/80 VUs, 3109 complete and 50 interrupted iterations
write ✓ [======================================] 80 VUs  10m0s

INFO[19:43:57] Load started at:               Fri Nov 01 2024 19:43:57 GMT+0000 (UTC)  source=console
INFO[19:54:02] Load finished at:              Fri Nov 01 2024 19:54:02 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 419 GB 692 MB/s
     aws_obj_put_duration...: avg=14.94s min=7.37s    med=14.5s  max=29.82s p(90)=19.52s p(95)=21.28s
     aws_obj_put_success....: 3122   5.155105/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 419 GB 692 MB/s
     iteration_duration.....: avg=15.36s min=156.56µs med=14.94s max=30.25s p(90)=19.94s p(95)=21.7s 
     iterations.............: 3121   5.153454/s
     vus....................: 43     min=0      max=80

running (10m05.6s), 00/80 VUs, 3121 complete and 42 interrupted iterations
write ✓ [======================================] 80 VUs  10m0s

### 8 nodes 128mb read
INFO[20:06:10] Load started at:               Fri Nov 01 2024 20:06:10 GMT+0000 (UTC)  source=console
INFO[20:16:16] Load finished at:              Fri Nov 01 2024 20:16:16 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.2 TB 2.0 GB/s
     aws_obj_get_duration...: avg=5.34s min=1.48s    med=4.62s max=27.15s p(90)=9.17s p(95)=10.98s
     aws_obj_get_success....: 8999   14.838113/s
     data_received..........: 1.2 TB 2.0 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=5.34s min=412.72µs med=4.62s max=27.15s p(90)=9.17s p(95)=10.97s
     iterations.............: 8999   14.838113/s
     vus....................: 2      min=2       max=80

running (10m06.5s), 00/80 VUs, 8999 complete and 3 interrupted iterations
read ✓ [======================================] 80 VUs  10m0s

INFO[20:06:08] Load started at:               Fri Nov 01 2024 20:06:08 GMT+0000 (UTC)  source=console
INFO[20:16:16] Load finished at:              Fri Nov 01 2024 20:16:16 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 1.2 TB 1.9 GB/s
     aws_obj_get_duration...: avg=5.55s min=1.43s    med=4.87s max=24.12s p(90)=9.47s p(95)=11.27s
     aws_obj_get_success....: 8667   14.263237/s
     data_received..........: 1.2 TB 1.9 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=5.55s min=353.64µs med=4.87s max=24.12s p(90)=9.47s p(95)=11.27s
     iterations.............: 8667   14.263237/s
     vus....................: 1      min=1       max=80

running (10m07.6s), 00/80 VUs, 8667 complete and 1 interrupted iterations
read ✓ [======================================] 80 VUs  10m0s

### 4 nodes 8kb write
INFO[13:50:15] Load started at:               Wed Oct 30 2024 13:50:15 GMT+0000 (UTC)  source=console
INFO[14:00:15] Load finished at:              Wed Oct 30 2024 14:00:15 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 6.1 GB 10 MB/s
     aws_obj_put_duration...: avg=226.68ms min=41.12ms med=180.38ms max=10.53s p(90)=348.67ms p(95)=445.63ms
     aws_obj_put_success....: 740542 1233.040934/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 6.1 GB 10 MB/s
     iteration_duration.....: avg=235ms    min=159.9µs med=188.63ms max=10.54s p(90)=357.18ms p(95)=454.03ms
     iterations.............: 740542 1233.040934/s
     vus....................: 290    min=290       max=290

running (10m00.6s), 000/290 VUs, 740542 complete and 0 interrupted iterations
write ✓ [======================================] 290 VUs  10m0s

INFO[13:50:24] Load started at:               Wed Oct 30 2024 13:50:24 GMT+0000 (UTC)  source=console
INFO[14:00:27] Load finished at:              Wed Oct 30 2024 14:00:27 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 6.0 GB 10 MB/s
     aws_obj_put_duration...: avg=227.67ms min=49.39ms  med=182.1ms max=10.35s p(90)=342.25ms p(95)=441.09ms
     aws_obj_put_success....: 738149 1224.250437/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 6.0 GB 10 MB/s
     iteration_duration.....: avg=235.86ms min=202.92µs med=190.2ms max=10.35s p(90)=350.38ms p(95)=449.32ms
     iterations.............: 738149 1224.250437/s
     vus....................: 5      min=5         max=290

running (10m02.9s), 000/290 VUs, 738149 complete and 0 interrupted iterations
write ✓ [======================================] 290 VUs  10m0s

### 4 nodes 8kb write
INFO[14:16:14] Load started at:               Wed Oct 30 2024 14:16:14 GMT+0000 (UTC)  source=console
INFO[14:26:16] Load finished at:              Wed Oct 30 2024 14:26:16 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.7 GB 2.8 MB/s
     aws_obj_put_duration...: avg=853.88ms min=44.13ms  med=649.13ms max=8.38s p(90)=1.77s p(95)=2.36s
     aws_obj_put_success....: 201980 335.860841/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.7 GB 2.7 MB/s
     iteration_duration.....: avg=862.5ms  min=271.41µs med=657.88ms max=8.38s p(90)=1.78s p(95)=2.37s
     iterations.............: 201980 335.860841/s
     vus....................: 50     min=50       max=290

running (10m01.4s), 000/290 VUs, 201980 complete and 0 interrupted iterations
write ✓ [======================================] 290 VUs  10m0s

INFO[14:16:15] Load started at:               Wed Oct 30 2024 14:16:15 GMT+0000 (UTC)  source=console
INFO[14:26:16] Load finished at:              Wed Oct 30 2024 14:26:16 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 1.6 GB 2.7 MB/s
     aws_obj_put_duration...: avg=862.44ms min=43.44ms  med=656.73ms max=8.5s  p(90)=1.79s p(95)=2.38s
     aws_obj_put_success....: 199939 332.891912/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 1.6 GB 2.7 MB/s
     iteration_duration.....: avg=870.92ms min=252.91µs med=665.38ms max=8.51s p(90)=1.8s  p(95)=2.39s
     iterations.............: 199939 332.891912/s
     vus....................: 290    min=290      max=290

running (10m00.6s), 000/290 VUs, 199939 complete and 0 interrupted iterations
write ✓ [======================================] 290 VUs  10m0s

### 4 nodes 8kb read 
INFO[14:35:34] Load started at:               Wed Oct 30 2024 14:35:34 GMT+0000 (UTC)  source=console
INFO[14:45:34] Load finished at:              Wed Oct 30 2024 14:45:34 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 16 GB   26 MB/s
     aws_obj_get_duration...: avg=91.49ms min=5.3ms    med=53.18ms max=2.47s p(90)=217.2ms  p(95)=298.95ms
     aws_obj_get_success....: 1899790 3164.294872/s
     data_received..........: 16 GB   26 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=91.57ms min=254.02µs med=53.26ms max=2.47s p(90)=217.28ms p(95)=299.04ms
     iterations.............: 1899790 3164.294872/s
     vus....................: 290     min=290       max=290

running (10m00.4s), 000/290 VUs, 1899790 complete and 0 interrupted iterations
read ✓ [======================================] 290 VUs  10m0s

INFO[14:35:33] Load started at:               Wed Oct 30 2024 14:35:33 GMT+0000 (UTC)  source=console
INFO[14:45:33] Load finished at:              Wed Oct 30 2024 14:45:33 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 15 GB   26 MB/s
     aws_obj_get_duration...: avg=92.34ms min=5.27ms  med=53.43ms max=2.43s p(90)=219.67ms p(95)=303.29ms
     aws_obj_get_success....: 1882837 3134.644282/s
     data_received..........: 15 GB   26 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=92.42ms min=210.2µs med=53.51ms max=2.43s p(90)=219.76ms p(95)=303.38ms
     iterations.............: 1882837 3134.644282/s
     vus....................: 290     min=290       max=290

running (10m00.7s), 000/290 VUs, 1882837 complete and 0 interrupted iterations
read ✓ [======================================] 290 VUs  10m0s

### 4 nodes 128kb write
INFO[15:15:17] Load started at:               Wed Oct 30 2024 15:15:17 GMT+0000 (UTC)  source=console
INFO[15:25:18] Load finished at:              Wed Oct 30 2024 15:25:18 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 61 GB  102 MB/s
     aws_obj_put_duration...: avg=336.55ms min=34.32ms  med=199.23ms max=6.23s p(90)=516.76ms p(95)=1.09s
     aws_obj_put_success....: 468267 778.338721/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 61 GB  102 MB/s
     iteration_duration.....: avg=346.12ms min=269.92µs med=208.88ms max=6.24s p(90)=526.55ms p(95)=1.1s 
     iterations.............: 468267 778.338721/s
     vus....................: 53     min=53       max=270

running (10m01.6s), 000/270 VUs, 468267 complete and 0 interrupted iterations
write ✓ [======================================] 270 VUs  10m0s

INFO[15:15:16] Load started at:               Wed Oct 30 2024 15:15:16 GMT+0000 (UTC)  source=console
INFO[15:25:18] Load finished at:              Wed Oct 30 2024 15:25:18 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 63 GB  105 MB/s
     aws_obj_put_duration...: avg=327.94ms min=35.98ms  med=192.65ms max=6.75s p(90)=514.91ms p(95)=1.04s
     aws_obj_put_success....: 480515 798.470001/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 63 GB  105 MB/s
     iteration_duration.....: avg=337.41ms min=486.71µs med=202.16ms max=6.76s p(90)=524.2ms  p(95)=1.05s
     iterations.............: 480515 798.470001/s
     vus....................: 30     min=30       max=270

running (10m01.8s), 000/270 VUs, 480515 complete and 0 interrupted iterations
write ✓ [======================================] 270 VUs  10m0s

### 4 nodes 128kb read
INFO[15:43:31] Load started at:               Wed Oct 30 2024 15:43:31 GMT+0000 (UTC)  source=console
INFO[15:53:32] Load finished at:              Wed Oct 30 2024 15:53:32 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 226 GB  377 MB/s
     aws_obj_get_duration...: avg=93.74ms min=7.28ms  med=74.67ms max=811.82ms p(90)=177.4ms  p(95)=222.55ms
     aws_obj_get_success....: 1726276 2876.208682/s
     data_received..........: 226 GB  377 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=93.83ms min=604.6µs med=74.75ms max=811.92ms p(90)=177.49ms p(95)=222.64ms
     iterations.............: 1726276 2876.208682/s
     vus....................: 270     min=270       max=270

running (10m00.2s), 000/270 VUs, 1726276 complete and 0 interrupted iterations
read ✓ [======================================] 270 VUs  10m0s

INFO[15:43:30] Load started at:               Wed Oct 30 2024 15:43:30 GMT+0000 (UTC)  source=console
INFO[15:53:31] Load finished at:              Wed Oct 30 2024 15:53:31 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 227 GB  378 MB/s
     aws_obj_get_duration...: avg=93.59ms min=7.62ms   med=74.37ms max=796.28ms p(90)=177.33ms p(95)=222.59ms
     aws_obj_get_success....: 1729146 2880.537547/s
     data_received..........: 227 GB  377 MB/s
     data_sent..............: 0 B     0 B/s
     iteration_duration.....: avg=93.68ms min=261.35µs med=74.46ms max=796.37ms p(90)=177.42ms p(95)=222.69ms
     iterations.............: 1729146 2880.537547/s
     vus....................: 270     min=270       max=270

running (10m00.3s), 000/270 VUs, 1729146 complete and 0 interrupted iterations
read ✓ [======================================] 270 VUs  10m0s

### 4 nodes 1mb write
INFO[07:36:49] Load started at:               Thu Oct 31 2024 07:36:49 GMT+0000 (UTC)  source=console
INFO[07:46:50] Load finished at:              Thu Oct 31 2024 07:46:50 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 185 GB 308 MB/s
     aws_obj_put_duration...: avg=628.48ms min=73.32ms  med=603.63ms max=2.5s  p(90)=882ms    p(95)=991.67ms
     aws_obj_put_success....: 176400 293.667601/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 185 GB 308 MB/s
     iteration_duration.....: avg=646.52ms min=556.59µs med=621.81ms max=2.51s p(90)=900.12ms p(95)=1s      
     iterations.............: 176400 293.667601/s
     vus....................: 190    min=190      max=190

running (10m00.7s), 000/190 VUs, 176400 complete and 0 interrupted iterations
write ✓ [======================================] 190 VUs  10m0s

INFO[07:36:50] Load started at:               Thu Oct 31 2024 07:36:50 GMT+0000 (UTC)  source=console
INFO[07:46:51] Load finished at:              Thu Oct 31 2024 07:46:51 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 187 GB 311 MB/s
     aws_obj_put_duration...: avg=621.77ms min=81.96ms  med=597.08ms max=2.21s p(90)=871.55ms p(95)=980.23ms
     aws_obj_put_success....: 178269 297.012426/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 187 GB 311 MB/s
     iteration_duration.....: avg=639.55ms min=310.23µs med=614.87ms max=2.23s p(90)=889.28ms p(95)=997.91ms
     iterations.............: 178269 297.012426/s
     vus....................: 190    min=190      max=190

running (10m00.2s), 000/190 VUs, 178269 complete and 0 interrupted iterations
write ✓ [======================================] 190 VUs  10m0s

### 4 nodes 1mb read
INFO[08:08:11] Load started at:               Thu Oct 31 2024 08:08:11 GMT+0000 (UTC)  source=console
INFO[08:18:12] Load finished at:              Thu Oct 31 2024 08:18:12 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 579 GB 964 MB/s
     aws_obj_get_duration...: avg=206.42ms min=22.18ms  med=181.53ms max=1.12s p(90)=369.72ms p(95)=424.34ms
     aws_obj_get_success....: 552113 919.024594/s
     data_received..........: 579 GB 964 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=206.52ms min=281.28µs med=181.63ms max=1.12s p(90)=369.82ms p(95)=424.44ms
     iterations.............: 552113 919.024594/s
     vus....................: 190    min=190      max=190

running (10m00.8s), 000/190 VUs, 552113 complete and 0 interrupted iterations
read ✓ [======================================] 190 VUs  10m0s

INFO[08:08:10] Load started at:               Thu Oct 31 2024 08:08:10 GMT+0000 (UTC)  source=console
INFO[08:18:10] Load finished at:              Thu Oct 31 2024 08:18:10 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 578 GB 964 MB/s
     aws_obj_get_duration...: avg=206.55ms min=23.21ms  med=181.56ms max=1.16s p(90)=370ms   p(95)=424.28ms
     aws_obj_get_success....: 551638 918.979411/s
     data_received..........: 578 GB 963 MB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=206.66ms min=324.18µs med=181.67ms max=1.16s p(90)=370.1ms p(95)=424.4ms 
     iterations.............: 551638 918.979411/s
     vus....................: 190    min=190      max=190

running (10m00.3s), 000/190 VUs, 551638 complete and 0 interrupted iterations
read ✓ [======================================] 190 VUs  10m0s

### 4 nodes 128mb write
INFO[09:13:38] Load started at:               Thu Oct 31 2024 09:13:38 GMT+0000 (UTC)  source=console
INFO[09:23:44] Load finished at:              Thu Oct 31 2024 09:23:44 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 205 GB 339 MB/s
     aws_obj_put_duration...: avg=15.23s min=6.57s    med=14.57s max=33.48s p(90)=20.54s p(95)=23.81s
     aws_obj_put_success....: 1530   2.526294/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 205 GB 339 MB/s
     iteration_duration.....: avg=15.64s min=162.67µs med=14.99s max=33.89s p(90)=20.96s p(95)=24.22s
     iterations.............: 1528   2.522992/s
     vus....................: 0      min=0      max=40

running (10m05.6s), 00/40 VUs, 1528 complete and 25 interrupted iterations
write ✓ [======================================] 40 VUs  10m0s

INFO[09:13:37] Load started at:               Thu Oct 31 2024 09:13:37 GMT+0000 (UTC)  source=console
INFO[09:23:42] Load finished at:              Thu Oct 31 2024 09:23:42 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_put_bytes......: 207 GB 341 MB/s
     aws_obj_put_duration...: avg=15.11s min=6.38s    med=14.24s max=33.29s p(90)=20.61s p(95)=24.94s
     aws_obj_put_success....: 1540   2.542657/s
     data_received..........: 0 B    0 B/s
     data_sent..............: 207 GB 341 MB/s
     iteration_duration.....: avg=15.51s min=139.12µs med=14.65s max=33.71s p(90)=21.03s p(95)=25.37s
     iterations.............: 1538   2.539355/s
     vus....................: 0      min=0      max=40

running (10m05.7s), 00/40 VUs, 1538 complete and 30 interrupted iterations
write ✓ [======================================] 40 VUs  10m0s

### 4 nodes 128mb read
INFO[09:25:00] Load started at:               Thu Oct 31 2024 09:25:00 GMT+0000 (UTC)  source=console
INFO[09:35:02] Load finished at:              Thu Oct 31 2024 09:35:02 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 819 GB 1.4 GB/s
     aws_obj_get_duration...: avg=3.93s min=1.55s    med=3.64s max=16s p(90)=5.63s p(95)=6.67s
     aws_obj_get_success....: 6105   10.13168/s
     data_received..........: 819 GB 1.4 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=3.93s min=385.83µs med=3.64s max=16s p(90)=5.63s p(95)=6.67s
     iterations.............: 6105   10.13168/s
     vus....................: 4      min=4      max=40

running (10m02.6s), 00/40 VUs, 6105 complete and 0 interrupted iterations
read ✓ [======================================] 40 VUs  10m0s

INFO[09:24:58] Load started at:               Thu Oct 31 2024 09:24:58 GMT+0000 (UTC)  source=console
INFO[09:35:02] Load finished at:              Thu Oct 31 2024 09:35:02 GMT+0000 (UTC)  source=console
     █ setup

     █ teardown

     aws_obj_get_bytes......: 818 GB 1.4 GB/s
     aws_obj_get_duration...: avg=3.95s min=1.51s    med=3.77s max=15.2s p(90)=5.42s p(95)=6.44s
     aws_obj_get_success....: 6091   10.097728/s
     data_received..........: 818 GB 1.4 GB/s
     data_sent..............: 0 B    0 B/s
     iteration_duration.....: avg=3.95s min=267.63µs med=3.77s max=15.2s p(90)=5.42s p(95)=6.44s
     iterations.............: 6091   10.097728/s
     vus....................: 3      min=3       max=40

running (10m03.2s), 00/40 VUs, 6091 complete and 0 interrupted iterations
read ✓ [======================================] 40 VUs  10m0s
