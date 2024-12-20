protection=EC2.1
HW_chassis=X205

### 15 nodes 8kb write
INFO[11:11:55] Load started at: Fri Oct 25 2024 11:11:55 GMT+0000 (UTC) source=console  
INFO[11:21:57] Load finished at: Fri Oct 25 2024 11:21:57 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_put_bytes......: 7.6 GB 13 MB/s
 aws_obj_put_duration...: avg=744.03ms min=31.39ms  med=302.29ms max=13.85s p(90)=2.03s p(95)=2.82s
 aws_obj_put_success....: 927223 1539.168897/s
 data_received..........: 0 B    0 B/s
 data_sent..............: 7.6 GB 13 MB/s
 iteration_duration.....: avg=752.9ms  min=269.05µs med=310.8ms  max=13.86s p(90)=2.03s p(95)=2.83s
 iterations.............: 927223 1539.168897/s
 vus....................: 19     min=19        max=1162
```

running (10m02.4s), 0000/1162 VUs, 927223 complete and 0 interrupted iterations  
write ✓ [======================================] 1162 VUs 10m0s

INFO[11:11:58] Load started at: Fri Oct 25 2024 11:11:58 GMT+0000 (UTC) source=console  
INFO[11:21:58] Load finished at: Fri Oct 25 2024 11:21:58 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_put_bytes......: 7.3 GB 12 MB/s
 aws_obj_put_duration...: avg=770.4ms  min=28.08ms  med=332.09ms max=10.37s p(90)=2.08s p(95)=2.87s
 aws_obj_put_success....: 895336 1490.153466/s
 data_received..........: 0 B    0 B/s
 data_sent..............: 7.3 GB 12 MB/s
 iteration_duration.....: avg=779.09ms min=179.67µs med=340.44ms max=10.38s p(90)=2.09s p(95)=2.88s
 iterations.............: 895336 1490.153466/s
 vus....................: 14     min=14        max=1162
```

running (10m00.8s), 0000/1162 VUs, 895336 complete and 0 interrupted iterations  
write ✓ [======================================] 1162 VUs 10m0s

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

### 15 nodes 128kb read
NFO[12:18:09] Load started at: Fri Oct 25 2024 12:18:09 GMT+0000 (UTC) source=console  
INFO[12:28:10] Load finished at: Fri Oct 25 2024 12:28:10 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_get_bytes......: 524 GB  873 MB/s
 aws_obj_get_duration...: avg=164.91ms min=8.82ms med=109.17ms max=11.86s p(90)=323.27ms p(95)=411.22ms
 aws_obj_get_fails......: 20      0.033299/s
 aws_obj_get_success....: 3999892 6659.683259/s
 data_received..........: 524 GB  872 MB/s
 data_sent..............: 0 B     0 B/s
 iteration_duration.....: avg=165.01ms min=2.22ms med=109.26ms max=11.86s p(90)=323.38ms p(95)=411.36ms
 iterations.............: 3999912 6659.716558/s
 vus....................: 1100    min=1100      max=1100
```

running (10m00.6s), 0000/1100 VUs, 3999912 complete and 0 interrupted iterations  
read ✓ [======================================] 1100 VUs 10m0s

INFO[12:18:19] Load started at: Fri Oct 25 2024 12:18:19 GMT+0000 (UTC) source=console  
INFO[12:28:19] Load finished at: Fri Oct 25 2024 12:28:19 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_get_bytes......: 529 GB  882 MB/s
 aws_obj_get_duration...: avg=163.3ms  min=8.98ms med=108.85ms max=13.51s p(90)=322.25ms p(95)=409.85ms
 aws_obj_get_fails......: 80      0.133282/s
 aws_obj_get_success....: 4039259 6729.496132/s
 data_received..........: 529 GB  881 MB/s
 data_sent..............: 0 B     0 B/s
 iteration_duration.....: avg=163.38ms min=1.02ms med=108.93ms max=13.51s p(90)=322.34ms p(95)=409.93ms
 iterations.............: 4039339 6729.629414/s
 vus....................: 1100    min=1100      max=1100
```

running (10m00.2s), 0000/1100 VUs, 4039339 complete and 0 interrupted iterations  
read ✓ [======================================] 1100 VUs 10m0s

### 15 nodes 128mib write
INFO[12:57:05] Load started at: Fri Oct 25 2024 12:57:05 GMT+0000 (UTC) source=console 
INFO[13:07:10] Load finished at: Fri Oct 25 2024 13:07:10 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_put_bytes......: 974 GB 1.6 GB/s
 aws_obj_put_duration...: avg=17.96s min=7.78s    med=16.79s max=1m19s p(90)=24.99s p(95)=28.22s
 aws_obj_put_fails......: 38     0.062744/s
 aws_obj_put_success....: 7257   11.982472/s
 data_received..........: 0 B    0 B/s
 data_sent..............: 974 GB 1.6 GB/s
 iteration_duration.....: avg=18.39s min=196.93µs med=17.22s max=1m20s p(90)=25.43s p(95)=28.63s
 iterations.............: 7293   12.041914/s
 vus....................: 2      min=0       max=225
```

running (10m05.6s), 000/225 VUs, 7293 complete and 148 interrupted iterations  
write ✓ [======================================] 225 VUs 10m0s

INFO[12:57:04] Load started at: Fri Oct 25 2024 12:57:04 GMT+0000 (UTC) source=console 
INFO[13:07:09] Load finished at: Fri Oct 25 2024 13:07:09 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_put_bytes......: 961 GB 1.6 GB/s
 aws_obj_put_duration...: avg=18.18s min=6.42s    med=16.97s max=1m14s p(90)=25.58s p(95)=29.03s
 aws_obj_put_fails......: 45     0.074295/s
 aws_obj_put_success....: 7161   11.822784/s
 data_received..........: 0 B    0 B/s
 data_sent..............: 961 GB 1.6 GB/s
 iteration_duration.....: avg=18.59s min=195.54µs med=17.4s  max=1m14s p(90)=25.98s p(95)=29.41s
 iterations.............: 7200   11.887172/s
 vus....................: 6      min=0       max=225
```

running (10m05.7s), 000/225 VUs, 7200 complete and 155 interrupted iterations  
write ✓ [======================================] 225 VUs 10m0s

### 15 nodes 128mib read
INFO[13:17:06] Load started at: Fri Oct 25 2024 13:17:06 GMT+0000 (UTC) source=console 
INFO[13:27:16] Load finished at: Fri Oct 25 2024 13:27:16 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_get_bytes......: 1.7 TB 2.8 GB/s
 aws_obj_get_duration...: avg=10.42s min=486.05ms med=9.25s max=1m22s p(90)=17.18s p(95)=20.01s
 aws_obj_get_success....: 12951  21.212617/s
 data_received..........: 1.7 TB 2.9 GB/s
 data_sent..............: 0 B    0 B/s
 iteration_duration.....: avg=10.42s min=311.29µs med=9.25s max=1m22s p(90)=17.18s p(95)=20.01s
 iterations.............: 12951  21.212617/s
 vus....................: 1      min=1       max=225
```

running (10m10.5s), 000/225 VUs, 12951 complete and 83 interrupted iterations  
read ✓ [======================================] 225 VUs 10m0s

INFO[13:17:05] Load started at: Fri Oct 25 2024 13:17:05 GMT+0000 (UTC) source=console  
INFO[13:27:15] Load finished at: Fri Oct 25 2024 13:27:15 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_get_bytes......: 1.7 TB 2.8 GB/s
 aws_obj_get_duration...: avg=10.5s min=1.67s    med=9.28s max=1m18s p(90)=17.64s p(95)=20.71s
 aws_obj_get_success....: 12839  21.027533/s
 data_received..........: 1.7 TB 2.8 GB/s
 data_sent..............: 0 B    0 B/s
 iteration_duration.....: avg=10.5s min=335.63µs med=9.28s max=1m18s p(90)=17.64s p(95)=20.71s
 iterations.............: 12839  21.027533/s
 vus....................: 3      min=3       max=225
```

running (10m10.6s), 000/225 VUs, 12839 complete and 91 interrupted iterations  
read ✓ [======================================] 225 VUs 10m0s

### 14 nodes 8kb write
INFO[14:26:24] Load started at: Fri Oct 25 2024 14:26:24 GMT+0000 (UTC) source=console  
INFO[14:36:28] Load finished at: Fri Oct 25 2024 14:36:28 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_put_bytes......: 25 GB   42 MB/s
 aws_obj_put_duration...: avg=201.81ms min=41.18ms  med=176.42ms max=4.17s p(90)=306.52ms p(95)=372.42ms
 aws_obj_put_success....: 3097597 5134.152747/s
 data_received..........: 0 B     0 B/s
 data_sent..............: 25 GB   42 MB/s
 iteration_duration.....: avg=210.52ms min=235.04µs med=185.17ms max=4.18s p(90)=316.78ms p(95)=381.15ms
 iterations.............: 3097597 5134.152747/s
 vus....................: 98      min=98        max=1085
```

running (10m03.3s), 0000/1085 VUs, 3097597 complete and 0 interrupted iterations  
write ✓ [======================================] 1085 VUs 10m0s

INFO[14:26:23] Load started at: Fri Oct 25 2024 14:26:23 GMT+0000 (UTC) source=console  
INFO[14:36:24] Load finished at: Fri Oct 25 2024 14:36:24 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_put_bytes......: 26 GB   43 MB/s
 aws_obj_put_duration...: avg=199.28ms min=33.17ms  med=173.68ms max=5.04s p(90)=304.37ms p(95)=372.8ms
 aws_obj_put_success....: 3131122 5214.828466/s
 data_received..........: 0 B     0 B/s
 data_sent..............: 26 GB   43 MB/s
 iteration_duration.....: avg=207.91ms min=220.71µs med=184.02ms max=5.05s p(90)=311.56ms p(95)=381.3ms
 iterations.............: 3131122 5214.828466/s
 vus....................: 1085    min=1085      max=1085
```

running (10m00.4s), 0000/1085 VUs, 3131122 complete and 0 interrupted iterations  
write ✓ [======================================] 1085 VUs 10m0s

### 13 nodes 8kb write
INFO[17:56:58] Load started at: Fri Oct 25 2024 17:56:58 GMT+0000 (UTC) source=console
INFO[18:07:00] Load finished at: Fri Oct 25 2024 18:07:00 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_put_bytes......: 15 GB   25 MB/s
 aws_obj_put_duration...: avg=315.65ms min=29.25ms med=173.51ms max=11.17s p(90)=545.06ms p(95)=1.03s
 aws_obj_put_success....: 1865935 3099.652251/s
 data_received..........: 0 B     0 B/s
 data_sent..............: 15 GB   25 MB/s
 iteration_duration.....: avg=324.21ms min=1.43ms  med=184ms    max=11.18s p(90)=554.23ms p(95)=1.03s
 iterations.............: 1865935 3099.652251/s
 vus....................: 11      min=11        max=1007
```

running (10m02.0s), 0000/1007 VUs, 1865935 complete and 0 interrupted iterations  
write ✓ [======================================] 1007 VUs 10m0s

INFO[17:57:00] Load started at: Fri Oct 25 2024 17:57:00 GMT+0000 (UTC) source=console 
INFO[18:07:01] Load finished at: Fri Oct 25 2024 18:07:01 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_put_bytes......: 15 GB   25 MB/s
 aws_obj_put_duration...: avg=327.62ms min=29.63ms  med=176.64ms max=12.37s p(90)=596.61ms p(95)=1.06s
 aws_obj_put_success....: 1798895 2989.984883/s
 data_received..........: 0 B     0 B/s
 data_sent..............: 15 GB   24 MB/s
 iteration_duration.....: avg=336.26ms min=209.18µs med=185.53ms max=12.38s p(90)=605.54ms p(95)=1.07s
 iterations.............: 1798895 2989.984883/s
 vus....................: 485     min=485       max=1007
```

running (10m01.6s), 0000/1007 VUs, 1798895 complete and 0 interrupted iterations  
write ✓ [======================================] 1007 VUs 10m0s

### 13 nodes 8kb read
INFO[18:11:33] Load started at: Tue Oct 25 2024 18:11:33 GMT+0000 (UTC) source=console  
INFO[18:21:36] Load finished at: Fri Oct 25 2024 18:21:36 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_get_bytes......: 28 GB   47 MB/s
 aws_obj_get_duration...: avg=174.21ms min=6.07ms  med=87.22ms max=6.28s p(90)=427.61ms p(95)=630.48ms
 aws_obj_get_fails......: 839     1.396622/s
 aws_obj_get_success....: 3466287 5770.074247/s
 data_received..........: 28 GB   47 MB/s
 data_sent..............: 0 B     0 B/s
 iteration_duration.....: avg=174.28ms min=191.6µs med=87.28ms max=6.28s p(90)=427.67ms p(95)=630.55ms
 iterations.............: 3467126 5771.470868/s
 vus....................: 1007    min=1007      max=1007
```

running (10m00.7s), 0000/1007 VUs, 3467126 complete and 0 interrupted iterations  
read ✓ [======================================] 1007 VUs 10m0s

INFO[18:11:33] Load started at: Tue Oct 25 2024 18:11:33 GMT+0000 (UTC) source=console  
INFO[18:21:36] Load finished at: Fri Oct 25 2024 18:21:36 GMT+0000 (UTC) source=console  
█ setup

```
 █ teardown

 aws_obj_get_bytes......: 28 GB   47 MB/s
 aws_obj_get_duration...: avg=176.98ms min=5.87ms   med=88.41ms max=6.88s p(90)=433.58ms p(95)=640.51ms
 aws_obj_get_fails......: 796     1.325938/s
 aws_obj_get_success....: 3411519 5682.741864/s
 data_received..........: 28 GB   47 MB/s
 data_sent..............: 0 B     0 B/s
 iteration_duration.....: avg=177.05ms min=214.43µs med=88.48ms max=6.88s p(90)=433.65ms p(95)=640.6ms 
 iterations.............: 3412315 5684.067802/s
 vus....................: 1007    min=1007      max=1007
```

running (10m00.3s), 0000/1007 VUs, 3412315 complete and 0 interrupted iterations  
read ✓ [======================================] 1007 VUs 10m0s

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