# Useful commands

### Check certs 

```sh
openssl s_client -showcerts -servername google.com -connect google.com:443 | openssl x509 -inform pem -noout -text
```
