
### How to create basic auth passwords file :

```
htpasswd -m /etc/squid/myPasswordFile <user name>
```

### Contact proxy with curl

```
curl 'url' -x 127.0.0.1:3128 -U user:password
```

### Resources

- http://doc.ubuntu-fr.org/tutoriel/comment_mettre_en_place_un_proxy_squid_avec_authentification_ncsa
- http://dabase.com/blog/Minimal_squid3_proxy_configuration/

