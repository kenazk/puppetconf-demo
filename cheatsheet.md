# Cheatsheet

### To create 10 virtual users every second for 60 seconds which will send 20 GET requests each.

#### VMSS
```bash
artillery quick --duration 120 --rate 500 -n 20 http://kenazvmss1.westus.cloudapp.azure.com
```

#### wintest1
artillery quick --duration 120 --rate 500 -n 20 http:// kenaz-wintest1.westus.cloudapp.azure.com

### IPs/Hostnames
| Host          | IP/DNS            |
| ------------- |:-------------:|
| wintest1      | 13.88.184.222 |
| kenazvmss     | kenazvmss1.westus.cloudapp.azure.com |

### Puppet Master FQDN
```
puppet0cbe.westus.cloudapp.azure.com
```
