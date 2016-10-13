# Cheatsheet

### To create 10 virtual users every second for 60 seconds which will send 20 GET requests each.

```bash
artillery quick --duration 60 --rate 10 -n 20 http://kenazvmss4.westus.cloudapp.azure.com/
```

### IPs/Hostnames
| Host          | IP/DNS            |
| ------------- |:-------------:|
| wintest1      | 13.88.184.222 |
| kenazvmss     | kenazvmss1.westus.cloudapp.azure.com |

### Puppet Master FQDN
```
puppet0cbe.westus.cloudapp.azure.com
```
