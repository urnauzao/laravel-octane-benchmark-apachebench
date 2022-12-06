# LARAVEL OCTANE ROADRUNNER
- Cpu: 8 treads
- Memória Ram: 8 gb
- Memória Swap: 8 gb
- WSL2: Ubuntu 20.04.5 LTS
- SO: Windows 10
- Aplicação: 
  - Laravel Sail, 
  - PHP 8.1.13
  - Laravel 9.42.2

<img src="./images/laravel-without-octane.png">

---

## Tentativa 1
<p>
Server Software:<br>
Server Hostname:        localhost<br>
Server Port:            80<br>
Document Path:          /<br>
Document Length:        17632 bytes<br>
Concurrency Level:      10<br>
Time taken for tests:   63.587 seconds<br>
Complete requests:      10000<br>
Failed requests:        0<br>
Keep-Alive requests:    0<br>
Total transferred:      186610000 bytes<br>
HTML transferred:       176320000 bytes<br>
Requests per second:    <strong>157.27</strong> [#/sec] (mean)<br>
Time per request:       63.587 [ms] (mean)<br>
Time per request:       6.359 [ms] (mean, across all concurrent requests)<br>
Transfer rate:          2865.95 [Kbytes/sec] received<br>
</p>

---

## Tentativa 2
<p>
Server Software:<br>
Server Hostname:        localhost<br>
Server Port:            80<br>
Document Path:          /<br>
Document Length:        17632 bytes<br>
Concurrency Level:      10<br>
Time taken for tests:   53.707 seconds<br>
Complete requests:      10000<br>
Failed requests:        0<br>
Keep-Alive requests:    0<br>
Total transferred:      186610000 bytes<br>
HTML transferred:       176320000 bytes<br>
Requests per second:    </strong>186.19</strong> [#/sec] (mean)<br>
Time per request:       53.707 [ms] (mean)<br>
Time per request:       5.371 [ms] (mean, across all concurrent requests)<br>
Transfer rate:          3393.14 [Kbytes/sec] received<br>
</p>

---

## Tentativa 3
<p>
Server Software:<br>
Server Hostname:        localhost<br>
Server Port:            80<br>
Document Path:          /<br>
Document Length:        17632 bytes<br>
Concurrency Level:      10<br>
Time taken for tests:   56.194 seconds<br>
Complete requests:      10000<br>
Failed requests:        0<br>
Keep-Alive requests:    0<br>
Total transferred:      186610000 bytes<br>
HTML transferred:       176320000 bytes<br>
Requests per second:    <strong>177.95</strong> [#/sec] (mean)<br>
Time per request:       56.194 [ms] (mean)<br>
Time per request:       5.619 [ms] (mean, across all concurrent requests)<br>
Transfer rate:          3242.99 [Kbytes/sec] received<br>
</p>