# LARAVEL OCTANE SWOOLE
- Cpu: 8 treads
- Memória Ram: 8 gb
- Memória Swap: 8 gb
- WSL2: Ubuntu 20.04.5 LTS
- SO: Windows 10
- Aplicação: 
  - Laravel Sail, 
  - PHP 8.1.13
  - Laravel 9.42.2

<img src="./images/laravel-swoole.png">

---

## Tentativa 1
<p>
Server Software:<br>
Server Hostname:        localhost<br>
Server Port:            80<br>
Document Path:          /<br>
Document Length:        0 bytes<br>
Concurrency Level:      10<br>
Time taken for tests:   24.540 seconds<br>
Complete requests:      10000<br>
Failed requests:        0<br>
Keep-Alive requests:    0<br>
Total transferred:      0 bytes<br>
HTML transferred:       0 bytes<br>
Requests per second:    <strong>407.50</strong> [#/sec] (mean)<br>
Time per request:       24.540 [ms] (mean)<br>
Time per request:       2.454 [ms] (mean, across all concurrent requests)<br>
Transfer rate:          0.00 [Kbytes/sec] received<br>
</p>

---

## Tentativa 2
<p>
Server Software:<br>
Server Hostname:        localhost<br>
Server Port:            80<br>
Document Path:          /<br>
Document Length:        0 bytes<br>
Concurrency Level:      10<br>
Time taken for tests:   24.722 seconds<br>
Complete requests:      10000<br>
Failed requests:        0<br>
Keep-Alive requests:    0<br>
Total transferred:      0 bytes<br>
HTML transferred:       0 bytes<br>
Requests per second:    <strong>404.49</strong> [#/sec] (mean)<br>
Time per request:       24.722 [ms] (mean)<br>
Time per request:       2.472 [ms] (mean, across all concurrent requests)<br>
Transfer rate:          0.00 [Kbytes/sec] received<br>
</p>

---

## Tentativa 3
<p>
Server Software:<br>
Server Hostname:        localhost<br>
Server Port:            80<br>
Document Path:          /<br>
Document Length:        0 bytes<br>
Concurrency Level:      10<br>
Time taken for tests:   24.736 seconds<br>
Complete requests:      10000<br>
Failed requests:        0<br>
Keep-Alive requests:    0<br>
Total transferred:      0 bytes<br>
HTML transferred:       0 bytes<br>
Requests per second:    <strong>404.26</strong> [#/sec] (mean)<br>
Time per request:       24.736 [ms] (mean)<br>
Time per request:       2.474 [ms] (mean, across all concurrent requests)<br>
Transfer rate:          0.00 [Kbytes/sec] received<br>
</p>