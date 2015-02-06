
# How to create basic auth passwords file :

```
htpasswd -m /etc/squid/myPasswordFile <user name>
```

# Contact proxy with curl

```
curl 'url' -x 127.0.0.1:3128 -U user:password
```



