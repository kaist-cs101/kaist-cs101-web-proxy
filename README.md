
## kaist-cs101-web-proxy

This is a Dockerized web proxy based on Nginx for serving KAIST CS101 webpage.

To proxy the homepage on [kaist-cs101.github.io](https://kaist-cs101.github.io), run:

```
$ docker-compose up
```
- To run in background: -d
- To force the re-creation of image: --force-recreate

### Let's encrypt
Using Let's encrypt and Certbot, SSL certificate saved at certbot/conf for secure https connection
When docker up, Certbot will try to get or renew the certificate
