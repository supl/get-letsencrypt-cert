This script use certbot + webroot + nginx docker image to get a let's encrypt certificate

Make sure that you have:
1. Installed docker and certbot
2. sudo permission
3. Registered DNS A record pointing to the host you run this script
4. Make sure port 80 is connectable from the Internet

Then,
```
./get <domain>
```
