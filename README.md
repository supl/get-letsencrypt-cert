This script use certbot + webroot + nginx docker image to get a let's encrypt certificate

Make sure that you have:
1. Installed docker
2. Registered DNS A record pointing to the host you run this script
3. Make sure port 80 is connectable from the Internet

Then,
```
./get <domain>
```

If everything goes well the certificate and key will be put in a temporary directory.
This script will hint the location.
However, you need roor permission to get them.
