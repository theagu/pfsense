# pfsense

### squid-kibana
 Docker compose to up ELK.
 Configure de squid to export logs with TCP in:

 Services > Squid Proxy > General > Advanced Settings > *Custom Options (Before Auth)*
 
`access_log tcp://docker_ip:1025`

> Import in Kibana ALL .json file from folder kibana.