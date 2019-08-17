# pfsense

### squid-kibana
 Docker compose para subir ELK.
 Configure o Squid para enviar os logs via tcp para o logstash:

 Services > Squid Proxy > General > Advanced Settings > *Custom Options (Before Auth)*
 
`access_log tcp://docker_ip:1025`

> Importe no Kibana TODOS os arquivos .json que estão no diretório kibana.