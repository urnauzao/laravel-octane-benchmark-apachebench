# Benchmarking performance Laravel Octane
- `br` Neste Projeto foi realizado teste realizado com 10.000 requisições, realizadas por 10 conexões simultâneas. Para isso foi utilizado a ferramenta de Benchmarking ApacheBench.
- `en` On this project were made Tests with 10.000 requests in 10 connections. For this, has used the Framework for Benchmarking ApacheBench.

## Swoole
- Request per Second(avg): <strong>2,627.16 </strong>(`br` 2.627,16)
- Total Request: 10,000 * 3(attempt)
- Best Time: 3.786 s (`br` 3,8 segundos) per 10k requests
- Lowest Time: 3.844 s (`br` 3,8 segundos) per 10k requests

## Roadrunner
- Request per Second(avg): <strong>173.80</strong>(`br` 173,80)
- Total Request: 10,000 * 3(attempt)
- Best Time: 53.707 s (`br` 53,7 segundos) per 10k requests
- Lowest Time: 63.587 s (`br` 63,6 segundos) per 10k requests

## Without Octane
- Request per Second(avg): <strong>405.41</strong>(`br` 405,41)
- Total Request: 10.000 * 3(attempt)
- Best Time: 24.540 s (`br` 24,5 segundos) per 10k requests
- Lowest Time: 24.736 s (`br` 24,7 segundos) per 10k requests

## Benchmarking Framework
- ApacheBench | [saiba mais](https://httpd.apache.org/docs/2.4/programs/ab.html)
- Script
> ab -c 10 -n 10000 -s 10 -m get -k http://localhost/