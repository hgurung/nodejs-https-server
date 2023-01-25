## nodejs-https-server

Simple https server using server.key and server.cert

### Certificates are generated using openssl

```

openssl req -nodes -new -x509 -keyout server.key -out server.cert

```

### Running applications

```

node app.js

```