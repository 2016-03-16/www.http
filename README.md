# www



## HTTP

``` windows
ipconfig | findstr IPv4
```

``` linux
ifconfig | grep -w inet
```

``` python 3
python -m http.server
```

``` python 2
python -m SimpleHTTPServer
```



## HTTPS

生成证书
```
openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem
```

```
npm install -g http-server
```

```
http-server -h
http-server -S -C -K -o -p
```

```
http-server ./ -S
```
