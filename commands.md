# Useful commands

### Check certs 

```sh
openssl s_client -showcerts -servername google.com -connect google.com:443 | openssl x509 -inform pem -noout -text
```

### tcpdump

```sh
# listen by port for eth0
sudo tcpdump -n -i eth0 -p -s 0 port 5672
# listen by protocol 
sudo tcpdump -n -i eth0 -p -s 0 proto \\icmp
```
