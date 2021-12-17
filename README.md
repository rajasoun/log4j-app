# Vulnerable Log4J Application 
-------

Log4j Application with Traefik Edge Router 


## Getting Started
------------

1. Manage `.env` file
```
cp .env.sample .env
```
2. Place Certificates `ssl_certificate.crt` and `ssl_certificate_key.key`  in `certs` directory 
3. Start the Servies
```
$ ./assist.bash router up
$ ./assist.bash router status
$ ./assist.bash router logs app
```
