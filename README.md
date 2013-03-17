# Rack::Synctime demo

Simple rails app that prints Hello text and uses Rack::Synctime as middleware.

## Launching demo

Setup your gemset and install app.

Star server and then in your fav terminal use curl command to verify it:

```
curl -G -i http://localhost:3000
```

Example output:

```
HTTP/1.1 200 OK
Content-Type: text/html; charset=utf-8
X-Synced-At: 1363562636
X-Ua-Compatible: IE=Edge
Etag: "952d2c56d0485958336747bcdd98590d"
Cache-Control: max-age=0, private, must-revalidate
X-Request-Id: 1b624e1bc4b398bac87fe51de8533324
X-Runtime: 0.002035
Server: WEBrick/1.3.1 (Ruby/1.9.3/2012-12-25)
Date: Sun, 17 Mar 2013 23:23:56 GMT
Content-Length: 6
Connection: Keep-Alive

Hello!
```

If you don't like use curl, you can verify your requests in web browser like Chrome using Inspector.