# Certs Generation

This ansible script would automatically generate the CA certs and other certs signed by this CA automatically

## Config yaml

> Notice that the config file must be placed at the same level as gen_cert.ansible.yml and named as instances.yml

```=yaml
- hostname: "server1"
  ip: ["123.123.123.123"]
  dns: ["localhost","server1"]
- hostname: "server2"
  ip: ["123.123.123.124"]
  dns: ["localhost","server2"]
- hostname: "server3"
  ip: ["123.123.123.125"]
  dns: ["localhost","server3"]
```
